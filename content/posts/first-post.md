---
date: 2025-02-22
tags: ["technology"]
categories: "Network"
title: "網路概述"
featured_image: "images/2025-2-22_Networking-intro.jpg"
images: ["/images/2025-2-22_Networking-intro.jpg"]
---

## 什麼是網路?

網路使兩台電腦能互相通訊，有各種**拓樸**(topologies，指網路成員間的特定排列方式)、**媒介**(mediums，如光纖、同軸電纜等)和**通訊協定**(protocols，如 TCP/IPX 等)

## 網路如何運作?

我們可以將網路運作想像成一台電腦發送郵件或包裹並由另一台電腦接收的過程。

假設一個場景:我們從 Home Network 造訪某家公司的網站，並與位於 Company Network 的公司網站交換資料，就像發送包裹一樣，我們應該會知道包裹的目的地(地址)。

我們在瀏覽器輸入的網路位址或是全球資源定位器(**Uniform Resource Locator/URL**)，又稱完全合格網域名稱(**Fully Qualified Domain Name/FQDN**)

兩者的差別在於:

- FQDN:僅指定建築物的地址
- URL: 也指定了包裹的「樓層」、「辦公室」、「郵箱」和對應的「員工」。

但是，我們只知道地址，並不知道實際的地理位置，這時候就要透過郵局將包裹轉發到總郵局(**網路服務供應商/ISP**)。

郵局就是我們的路由器，利用它連結網路中的**網際網路**。

當我們透過郵局(路由器)傳送資料包，資料包就會被轉發到總郵局(ISP)，總郵局便會尋找該位址對應的登記簿(網域名稱服務)，並傳回對應的地理座標（IP 位址）。

在我們知道了地址的確切位置，我們的包裹將透過總郵局的直飛航班直接發送到那裡。

![alt text](/images/Networking-intro.jpg)

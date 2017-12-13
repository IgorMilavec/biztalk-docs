---
title: "How to Monitor the Health of Host Integration Server with WMI2 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 2f298655-ca71-4441-ad72-2ac2e93e5335
caps.latest.revision: 3
---
# How to Monitor the Health of Host Integration Server with WMI
Health monitoring refers to viewing the current status of different aspects of Host Integration Server through the **WmiSnaStatus** provider. You can access **WmiSnaStatus** provider in the same manner as you would any other instance and method provider. You use **ExecQuery** to query for the relevant information, and then display the information to screen or write the information to a log file. Some **WmiSnaStatus** classes also have methods that let you start and stop related services.  
  
### To monitor the health of Host Integration Server with WMI  
  
1.  Connect to the namespace using **GetObject** with a moniker in the parameter.  
  
2.  Retrieve the object representing the SNA Status provider using **ExecQuery**.  
  
3.  Use the information gathered from the **ExecQuery** as appropriate.  
  
 You can see an example of health monitoring in [How to Display Connection Status](../HIS2010/how-to-display-connection-status2.md).
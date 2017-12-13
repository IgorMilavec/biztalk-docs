---
title: "Creating an Application for the BizTalk Adapter for Host Applications1 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: d54d86f7-b876-4f25-bef1-c142f58fc832
caps.latest.revision: 5
---
# Creating an Application for the BizTalk Adapter for Host Applications
The following list describes the steps that you must follow to create an application that uses the BizTalk Adapter for Host Applications:  
  
1.  Set your mainframe environment and communications protocols to run your application.  
  
2.  Create a Visual Studio solution to contain all the necessary BizTalk and Host Integration Server projects for your application.  
  
3.  Create a Transaction Integrator (TI) project that will hold the interface definition of the host application.  
  
     If necessary, you may modify the generated XML file to pass client context information.  
  
4.  Create a BizTalk project that will hold your BizTalk application, using the created interface definition and associated schema.  
  
5.  Create your BizTalk application, using the ports and settings that were defined earlier.  
  
6.  Associate the interface definition with the mainframe environment using TI Manager.  
  
7.  Deploy the schema.  
  
8.  Build the BizTalk Server deployment MSI package.  
  
 After you create the export package, you can move the solution to a staging or production server and import the package.  
  
 For more information, see [Application Integration Programmer’s Guide](../HIS2010/application-integration-programmer’s-guide1.md).  
  
## In This Section  
 [Mainframe Setup](../HIS2010/mainframe-setup1.md)  
  
 [How to Create a Visual Studio Solution](../HIS2010/how-to-create-a-visual-studio-solution2.md)  
  
 [How to Create a Transaction Integrator Project and Interface Definition](../HIS2010/how-to-create-a-transaction-integrator-project-and-interface-definition2.md)  
  
 [How to use a Client Context with the BizTalk Adapter for Host Applications](../HIS2010/how-to-use-a-client-context-with-the-biztalk-adapter-for-host-applications1.md)  
  
 [How to Create a BizTalk Project](../HIS2010/how-to-create-a-biztalk-project1.md)  
  
 [Creating a BizTalk Application](../HIS2010/creating-a-biztalk-application2.md)  
  
 [How to Associate the Interface Definition with the Mainframe Environment](../HIS2010/how-to-associate-the-interface-definition-with-the-mainframe-environment1.md)  
  
 [How to Export the Schema](../HIS2010/how-to-export-the-schema2.md)  
  
 [How to Create a BizTalk Server Export Package](../HIS2010/how-to-create-a-biztalk-server-export-package2.md)
---
title: App-V 4.6 Release Notes
description: App-V 4.6 Release Notes
author: dansimp
ms.assetid: a3eba129-edac-48bf-a933-3bf43a9873e5
ms.reviewer: 
manager: dansimp
ms.author: dansimp
ms.pagetype: mdop, appcompat, virtualization
ms.mktglfcycl: deploy
ms.sitesec: library
ms.prod: w8
ms.date: 08/30/2016
---


# App-V 4.6 Release Notes


To search these Release Notes, press CTRL+F.

**Important**  
Read these Release Notes thoroughly before you install the Microsoft Application Virtualization (App-V) Management System. These Release Notes contain information that you need to successfully install Application Virtualization (App-V) 4.6. This document contains information that is not available in the product documentation. If there is a discrepancy between these Release Notes and other App-V documentation, the latest change should be considered authoritative.

 

## Protect Against Security Vulnerabilities and Viruses


To help protect against security vulnerabilities and viruses, it is important to install the latest available security updates for any new software being installed. For more information, see the [Microsoft Security Web site](https://go.microsoft.com/fwlink/?LinkId=3482) (https://go.microsoft.com/fwlink/?LinkId=3482).

## Known Issues with Application Virtualization 4.6


This section provides the most up-to-date information about issues with Microsoft Application Virtualization (App-V) 4.6. These issues do not appear in the product documentation and in some cases might contradict existing product documentation. Whenever possible, these issues will be addressed in later releases.

### Load/install error running a Windows Installer file generated by the App-V 4.5 Sequencer

Running a Windows Installer file generated by the App-V 4.5 Sequencer produces a load/install error when trying to run it on an App-V 4.6 client. You will see the following message: "This package requires Microsoft Application Virtualization Client 4.5 or later". Please use the following workaround.

WORKAROUND   Open the old package with either the App-V 4.5 SP1 Sequencer or the App-V 4.6 Sequencer and generate a new .msi file for the package.

**Note**  
Alternatively, at the command prompt, the App-V Sequencer can generate the new .msi file by using the */OPEN* and */MSI* parameters, for example, `SFTSequencer /Open:”package.sprj” /MSI`. For more information, see [How to Upgrade a Virtual Application by Using the Command Line](how-to-upgrade-a-virtual-application-by-using-the-command-line.md).

 

### Release Notes Copyright Information

This document is provided “as-is”. Information and views expressed in this document, including URL and other Internet Web site references, may change without notice. You bear the risk of using it.

Some examples depicted herein are provided for illustration only and are fictitious.  No real association or connection is intended or should be inferred.

This document does not provide you with any legal rights to any intellectual property in any Microsoft product. You may copy and use this document for your internal, reference purposes. You may modify this document for your internal, reference purposes.



Microsoft, Active Directory, ActiveSync, ActiveX, Excel, SQL Server, Windows, Windows PowerShell, Windows Server, and Windows Vista are trademarks of the Microsoft group of companies.

All other trademarks are property of their respective owners.

 

 






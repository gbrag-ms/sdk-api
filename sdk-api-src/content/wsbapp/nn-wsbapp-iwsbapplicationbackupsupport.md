---
UID: NN:wsbapp.IWsbApplicationBackupSupport
title: IWsbApplicationBackupSupport (wsbapp.h)
description: Defines a method for checking the consistency of the application's VSS writer's components.
helpviewer_keywords: ["IWsbApplicationBackupSupport","IWsbApplicationBackupSupport interface [Windows Server Backup]","IWsbApplicationBackupSupport interface [Windows Server Backup]","described","wsb.iwsbapplicationbackupsupport","wsbapp/IWsbApplicationBackupSupport"]
old-location: wsb\iwsbapplicationbackupsupport.htm
tech.root: wsb
ms.assetid: 45865f1b-0f0a-46fc-b1f3-f2fd7c49f56f
ms.date: 12/05/2018
ms.keywords: IWsbApplicationBackupSupport, IWsbApplicationBackupSupport interface [Windows Server Backup], IWsbApplicationBackupSupport interface [Windows Server Backup],described, wsb.iwsbapplicationbackupsupport, wsbapp/IWsbApplicationBackupSupport
req.header: wsbapp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2008
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: WsbApp.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IWsbApplicationBackupSupport
 - wsbapp/IWsbApplicationBackupSupport
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - WsbApp.h
api_name:
 - IWsbApplicationBackupSupport
---

# IWsbApplicationBackupSupport interface


## -description

Defines a method for checking the consistency of the application's VSS writer's components.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IWsbApplicationBackupSupport</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IWsbApplicationBackupSupport</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IWsbApplicationBackupSupport</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/wsbapp/nf-wsbapp-iwsbapplicationbackupsupport-checkconsistency">CheckConsistency</a>
</td>
<td align="left" width="63%">
Checks the consistency of the VSS writer's components in the shadow copy after shadow copies are created for the volumes to be backed up.

</td>
</tr>
</table>


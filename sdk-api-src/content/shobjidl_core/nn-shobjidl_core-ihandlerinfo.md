---
UID: NN:shobjidl_core.IHandlerInfo
title: IHandlerInfo (shobjidl_core.h)
description: Supplies methods that provide information about the handler to methods of the IHandlerActivationHost interface.
helpviewer_keywords: ["IHandlerInfo","IHandlerInfo interface [Windows Shell]","IHandlerInfo interface [Windows Shell]","described","shell.IHandlerInfo","shobjidl_core/IHandlerInfo"]
old-location: shell\IHandlerInfo.htm
tech.root: shell
ms.assetid: f0b8da9f-75ee-418d-8df6-fa0d7c600e62
ms.date: 12/05/2018
ms.keywords: IHandlerInfo, IHandlerInfo interface [Windows Shell], IHandlerInfo interface [Windows Shell],described, shell.IHandlerInfo, shobjidl_core/IHandlerInfo
req.header: shobjidl_core.h
req.include-header: Shobjidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows 8 [desktop apps only]
req.target-min-winversvr: Windows Server 2012 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl.idl
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
 - IHandlerInfo
 - shobjidl_core/IHandlerInfo
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - shobjidl_core.h
api_name:
 - IHandlerInfo
---

# IHandlerInfo interface


## -description

Supplies methods that provide information about the handler to methods of the <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ihandleractivationhost">IHandlerActivationHost</a> interface.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IHandlerInfo</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IHandlerInfo</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IHandlerInfo</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ihandlerinfo-getapplicationdisplayname">GetApplicationDisplayName</a>
</td>
<td align="left" width="63%">
Retrieves the display name of the application that implemented the handler.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ihandlerinfo-getapplicationiconreference">GetApplicationIconReference</a>
</td>
<td align="left" width="63%">
Retrieves the icon of the application that implemented the handler.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ihandlerinfo-getapplicationpublisher">GetApplicationPublisher</a>
</td>
<td align="left" width="63%">
Retrieves the name of the publisher of the application that implemented the handler.

</td>
</tr>
</table>


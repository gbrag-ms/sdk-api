---
UID: NF:windows.media.streaming.IMediaRenderer.GetVolumeAsync
title: IMediaRenderer::streaming (windows.media.streaming.h)
description: Queries the DMR asynchronously for its current audio volume level.
helpviewer_keywords: ["GetVolumeAsync","GetVolumeAsync method [Media Streaming API]","GetVolumeAsync method [Media Streaming API]","IMediaRenderer interface","IMediaRenderer interface [Media Streaming API]","GetVolumeAsync method","IMediaRenderer.GetVolumeAsync","IMediaRenderer.streaming","IMediaRenderer::GetVolumeAsync","IMediaRenderer::streaming","mediastreaming.imediarenderer_getvolumeasync","windows/IMediaRenderer::GetVolumeAsync"]
old-location: mediastreaming\imediarenderer_getvolumeasync.htm
tech.root: mediastreaming
ms.assetid: CBE8E7EE-DC64-4FB0-B09D-58EC9BACCA26
ms.date: 12/05/2018
ms.keywords: GetVolumeAsync, GetVolumeAsync method [Media Streaming API], GetVolumeAsync method [Media Streaming API],IMediaRenderer interface, IMediaRenderer interface [Media Streaming API],GetVolumeAsync method, IMediaRenderer.GetVolumeAsync, IMediaRenderer.streaming, IMediaRenderer::GetVolumeAsync, IMediaRenderer::streaming, mediastreaming.imediarenderer_getvolumeasync, windows/IMediaRenderer::GetVolumeAsync
req.header: windows.media.streaming.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
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
 - IMediaRenderer::GetVolumeAsync
 - windows.media.streaming/IMediaRenderer::GetVolumeAsync
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - windows.media.streaming.h
api_name:
 - IMediaRenderer.GetVolumeAsync
---

# IMediaRenderer::streaming


## -description

Queries the DMR asynchronously for its current audio volume level.

## -parameters

### -param value [out]

Receives a reference to a <a href="https://docs.microsoft.com/windows/desktop/mediastreaming/getvolumeoperation">GetVolumeOperation</a> object that is used to get results from the asynchronous operation.

## -returns

The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/mediastreaming/imediarenderer">IMediaRenderer</a>


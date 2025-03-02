---
UID: NF:syncmgr.ISyncMgrSyncItemInfo.GetComment
title: ISyncMgrSyncItemInfo::GetComment (syncmgr.h)
description: Gets a string that contains commentary regarding the item.
helpviewer_keywords: ["GetComment","GetComment method [Windows Shell]","GetComment method [Windows Shell]","ISyncMgrSyncItemInfo interface","ISyncMgrSyncItemInfo interface [Windows Shell]","GetComment method","ISyncMgrSyncItemInfo.GetComment","ISyncMgrSyncItemInfo::GetComment","_shell_ISyncMgrSyncItemInfo_GetComment","shell.ISyncMgrSyncItemInfo_GetComment","syncmgr/ISyncMgrSyncItemInfo::GetComment"]
old-location: shell\ISyncMgrSyncItemInfo_GetComment.htm
tech.root: shell
ms.assetid: 3959784b-2926-43fd-b8e5-bb1884e5d321
ms.date: 12/05/2018
ms.keywords: GetComment, GetComment method [Windows Shell], GetComment method [Windows Shell],ISyncMgrSyncItemInfo interface, ISyncMgrSyncItemInfo interface [Windows Shell],GetComment method, ISyncMgrSyncItemInfo.GetComment, ISyncMgrSyncItemInfo::GetComment, _shell_ISyncMgrSyncItemInfo_GetComment, shell.ISyncMgrSyncItemInfo_GetComment, syncmgr/ISyncMgrSyncItemInfo::GetComment
req.header: syncmgr.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Syncmgr.idl
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
 - ISyncMgrSyncItemInfo::GetComment
 - syncmgr/ISyncMgrSyncItemInfo::GetComment
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Syncmgr.h
api_name:
 - ISyncMgrSyncItemInfo.GetComment
---

# ISyncMgrSyncItemInfo::GetComment


## -description

Gets a string that contains commentary regarding the item.

## -parameters

### -param ppszComment [out]

Type: <b>LPWSTR*</b>

When this method returns, contains a pointer to a buffer containing the comment string. This string is of maximum length MAX_SYNCMGR_NAME including the terminating null character.

## -returns

Type: <b>HRESULT</b>

Returns S_OK if successful, or an error value otherwise. If the method fails, <i>ppszComment</i> contains an empty string.

## -remarks

This string could be provided by an item to display a summary of its contents, for example, "32 contacts" or "13 songs". The string can have a maximum length of MAX_SYNCMGR_NAME including the terminating null character.

The comment value is displayed as the System.Sync.Comments (PKEY_Sync_Comments) property in the folder UI when a synchronization is not being performed.

Sync Center calls this method whenever the <a href="https://docs.microsoft.com/windows/desktop/api/syncmgr/nf-syncmgr-isyncmgrcontrol-updatehandler">UpdateHandler</a> method is called.

The item is responsible for allocating the string buffer pointed to by <i>ppszComment</i> through <a href="https://docs.microsoft.com/windows/desktop/api/combaseapi/nf-combaseapi-cotaskmemalloc">CoTaskMemAlloc</a>. Sync Center deallocates the string buffer through <a href="https://docs.microsoft.com/windows/desktop/api/combaseapi/nf-combaseapi-cotaskmemfree">CoTaskMemFree</a>.


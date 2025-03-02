---
UID: NF:eapmethodpeerapis.EapPeerCredentialsXml2Blob
title: EapPeerCredentialsXml2Blob function (eapmethodpeerapis.h)
description: Converts XML into the configuration BLOB.
helpviewer_keywords: ["EapPeerCredentialsXml2Blob","EapPeerCredentialsXml2Blob function [EAPHost]","eaphost.eappeercredentialsxml2blob","eapmethodpeerapis/EapPeerCredentialsXml2Blob"]
old-location: eaphost\eappeercredentialsxml2blob.htm
tech.root: eaphost
ms.assetid: 45a13be7-9a01-467b-97db-ca896d945ee7
ms.date: 12/05/2018
ms.keywords: EapPeerCredentialsXml2Blob, EapPeerCredentialsXml2Blob function [EAPHost], eaphost.eappeercredentialsxml2blob, eapmethodpeerapis/EapPeerCredentialsXml2Blob
req.header: eapmethodpeerapis.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
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
 - EapPeerCredentialsXml2Blob
 - eapmethodpeerapis/EapPeerCredentialsXml2Blob
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - eapmethodpeerapis.h
api_name:
 - EapPeerCredentialsXml2Blob
---

# EapPeerCredentialsXml2Blob function


## -description

 Converts XML into the configuration  BLOB. The XML based credentials can come from group policy or from a system administrator.

## -parameters

### -param dwFlags [in]

Not used. Set to 0.

### -param eapMethodType [in]

An <a href="https://docs.microsoft.com/windows/desktop/api/eaptypes/ns-eaptypes-eap_method_type">EAP_METHOD_TYPE</a> structure that contains vendor and author information about the EAP method used for authenticating the connection.

### -param pCredentialsDoc [in]

A pointer to an XML node that contains credentials, which are either user or machine credentials depending on the configuration passed in. The XML document is created with the [EapHostUserCredentials Schema](/windows/win32/eaphost/eaphostusercredentialsschema-schema).

### -param pConfigIn [in]

A pointer to a byte buffer that contains a configuration BLOB for which the credentials are configured. The  buffer is of size <i>dwSizeofConfigIn</i>.

### -param dwSizeOfConfigIn [in]

The size, in bytes, of the buffer pointed to by <i>pConfigIn</i>.

### -param ppCredentialsOut [out]

A pointer to the byte buffer that receives the credentials BLOB buffer generated by the input XML. The buffer can is of size <i>pdwSizeofCredentialsOut</i>. After consuming the data, this memory must be freed by calling  <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/eapmethodpeerapis/nf-eapmethodpeerapis-eappeerfreememory">EapPeerFreeMemory</a>.

### -param pdwSizeOfCredentialsOut [out]

The size, in bytes, of the buffer pointed to by <i>ppCredentialsOut</i>.

### -param ppEapError [out]

A pointer to the address of an <a href="https://docs.microsoft.com/windows/desktop/api/eaptypes/ns-eaptypes-eap_error">EAP_ERROR</a> structure that contains any errors raised  by EAPHost during  the execution of this function call. After consuming the error data, this memory must be freed by calling <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/eapmethodpeerapis/nf-eapmethodpeerapis-eappeerfreeerrormemory">EapPeerFreeErrorMemory</a>.

## -see-also

[EAPHost Peer Method Configuration Functions](/windows/win32/eaphost/eaphost-peer-method-configuration-functions)


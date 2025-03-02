---
UID: NF:dcomp.IDCompositionLinearTransferEffect.SetGreenYIntercept(IDCompositionAnimation)
title: IDCompositionLinearTransferEffect::SetGreenYIntercept(IDCompositionAnimation) (dcomp.h)
description: Sets the Y-intercept of the linear function for the green channel.
helpviewer_keywords: ["IDCompositionLinearTransferEffect interface [DirectComposition]","SetGreenYIntercept method","IDCompositionLinearTransferEffect.SetGreenYIntercept","IDCompositionLinearTransferEffect.SetGreenYIntercept(IDCompositionAnimation)","IDCompositionLinearTransferEffect::SetGreenYIntercept","IDCompositionLinearTransferEffect::SetGreenYIntercept(IDCompositionAnimation)","SetGreenYIntercept","SetGreenYIntercept method [DirectComposition]","SetGreenYIntercept method [DirectComposition]","IDCompositionLinearTransferEffect interface","dcomp/IDCompositionLinearTransferEffect::SetGreenYIntercept","directcomp.idcompositionlineartransfereffect_setgreenyintercept_2"]
old-location: directcomp\idcompositionlineartransfereffect_setgreenyintercept_2.htm
tech.root: directcomp
ms.assetid: 73631804-5749-4764-9335-42F04D6BCB62
ms.date: 12/05/2018
ms.keywords: IDCompositionLinearTransferEffect interface [DirectComposition],SetGreenYIntercept method, IDCompositionLinearTransferEffect.SetGreenYIntercept, IDCompositionLinearTransferEffect.SetGreenYIntercept(IDCompositionAnimation), IDCompositionLinearTransferEffect::SetGreenYIntercept, IDCompositionLinearTransferEffect::SetGreenYIntercept(IDCompositionAnimation), SetGreenYIntercept, SetGreenYIntercept method [DirectComposition], SetGreenYIntercept method [DirectComposition],IDCompositionLinearTransferEffect interface, dcomp/IDCompositionLinearTransferEffect::SetGreenYIntercept, directcomp.idcompositionlineartransfereffect_setgreenyintercept_2
req.header: dcomp.h
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
req.lib: Dcomp.lib
req.dll: Dcomp.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IDCompositionLinearTransferEffect::SetGreenYIntercept
 - dcomp/IDCompositionLinearTransferEffect::SetGreenYIntercept
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Dcomp.dll
api_name:
 - IDCompositionLinearTransferEffect.SetGreenYIntercept
---

# IDCompositionLinearTransferEffect::SetGreenYIntercept(IDCompositionAnimation)


## -description

Sets the Y-intercept of the linear function for the green channel.

## -parameters

### -param animation [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/dcompanimation/nn-dcompanimation-idcompositionanimation">IDCompositionAnimation</a>*</b>

An animation that represents how the Y-intercept of the linear function for the green channel changes over time. This parameter must not be NULL.

## -returns

Type: <b><a href="/windows/win32/com/structure-of-com-error-codes">HRESULT</a></b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/dcomp/nn-dcomp-idcompositionlineartransfereffect">IDCompositionLinearTransferEffect</a>


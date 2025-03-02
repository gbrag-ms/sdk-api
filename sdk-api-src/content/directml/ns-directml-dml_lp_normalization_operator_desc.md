---
UID: NS:directml.DML_LP_NORMALIZATION_OPERATOR_DESC
title: DML_LP_NORMALIZATION_OPERATOR_DESC
description: Describes a DirectML operator that performs an Lp-normalization function along the specified axis of the input tensor.
helpviewer_keywords: ["DML_LP_NORMALIZATION_OPERATOR_DESC","DML_LP_NORMALIZATION_OPERATOR_DESC structure","direct3d12.dml_lp_normalization_operator_desc","directml/DML_LP_NORMALIZATION_OPERATOR_DESC"]
old-location: direct3d12\dml_lp_normalization_operator_desc.htm
tech.root: directml
ms.assetid: EEE59313-F8F4-4617-9499-1BEF5A4C635D
ms.date: 12/5/2018
ms.keywords: DML_LP_NORMALIZATION_OPERATOR_DESC, DML_LP_NORMALIZATION_OPERATOR_DESC structure, direct3d12.dml_lp_normalization_operator_desc, directml/DML_LP_NORMALIZATION_OPERATOR_DESC
req.header: directml.h
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
 - DML_LP_NORMALIZATION_OPERATOR_DESC
 - directml/DML_LP_NORMALIZATION_OPERATOR_DESC
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - DirectML.h
api_name:
 - DML_LP_NORMALIZATION_OPERATOR_DESC
---

# DML_LP_NORMALIZATION_OPERATOR_DESC structure


## -description

Describes a DirectML operator that performs an Lp-normalization function along the specified axis of the input tensor.

## -struct-fields

### -field InputTensor

Type: **const [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc)\***

A pointer to a constant [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc) containing the description of the tensor to read from.

### -field OutputTensor

Type: **const [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc)\***

A pointer to a constant [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc) containing the description of the tensor to write the results to.

### -field Axis

Type: [**UINT**](/windows/desktop/winprog/windows-data-types)

The axis on which to apply normalization. You can use a default value of -1 to mean the last axis.

### -field Epsilon

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">FLOAT</a></b>

The epsilon value to use to avoid division by zero.

### -field P

Type: [**UINT**](/windows/desktop/winprog/windows-data-types)

The order of the normalization (either 1 or 2). You can use a default value of 2.


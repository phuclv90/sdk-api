---
UID: NF:mi.MI_DestinationOptions_SetImpersonationType
title: MI_DestinationOptions_SetImpersonationType function (mi.h)
description: Sets the impersonation type.
old-location: wmi_v2\mi_destinationoptions_setimpersonationtype.htm
tech.root: wmi_v2
ms.assetid: f52370cb-b26c-4f0f-9869-1207c906e4e8
ms.date: 12/05/2018
ms.keywords: MI_DestinationOptions_SetImpersonationType, MI_DestinationOptions_SetImpersonationType function [Windows Management Infrastructure (MI)], mi/MI_DestinationOptions_SetImpersonationType, wmi_v2.mi_destinationoptions_setimpersonationtype
f1_keywords:
- mi/MI_DestinationOptions_SetImpersonationType
dev_langs:
- c++
req.header: mi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
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
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Mi.h
api_name:
- MI_DestinationOptions_SetImpersonationType
targetos: Windows
req.typenames: 
req.redist: Windows Management Framework 3.0 on Windows Server 2008 R2 with SP1, Windows 7 with SP1, and Windows Server 2008 with SP2
ms.custom: 19H1
---

# MI_DestinationOptions_SetImpersonationType function


## -description


Sets the impersonation type.


## -parameters




### -param options [in, out]

A pointer to a <a href="https://docs.microsoft.com/windows/desktop/api/mi/ns-mi-mi_destinationoptions">MI_DestinationOptions</a> object returned from the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/mi/nf-mi-mi_application_newdestinationoptions">MI_Application_NewDestinationOptions</a> function.


### -param impersonationType [in]


<a href="https://docs.microsoft.com/windows/desktop/api/mi/ne-mi-mi_destinationoptions_impersonationtype">MI_DestinationOptions_ImpersonationType</a> enumeration.


## -returns



A value of the <a href="https://docs.microsoft.com/windows/desktop/api/mi/ne-mi-mi_result">MI_Result</a> enumeration that specifies the function return code. This can be one of the following codes.




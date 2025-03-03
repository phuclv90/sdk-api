---
UID: NF:msvidctl.IMSVidCtl.put_AutoSize
title: IMSVidCtl::put_AutoSize (msvidctl.h)
description: The put_AutoSize method specifies whether the Video Control automatically resizes to display its entire contents.
old-location: mstv\imsvidctl_put_autosize.htm
tech.root: mstv
ms.assetid: eb5863e2-380b-4bee-ac18-e5f28551a6ab
ms.date: 12/05/2018
ms.keywords: IMSVidCtl interface [Microsoft TV Technologies],put_AutoSize method, IMSVidCtl.put_AutoSize, IMSVidCtl::put_AutoSize, IMSVidCtlput_AutoSize, mstv.imsvidctl_put_autosize, msvidctl/IMSVidCtl::put_AutoSize, put_AutoSize, put_AutoSize method [Microsoft TV Technologies], put_AutoSize method [Microsoft TV Technologies],IMSVidCtl interface
f1_keywords:
- msvidctl/IMSVidCtl.put_AutoSize
dev_langs:
- c++
req.header: msvidctl.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Msvidctl.idl
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
- COM
api_location:
- msvidctl.h
api_name:
- IMSVidCtl.put_AutoSize
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMSVidCtl::put_AutoSize


## -description


The <b>put_AutoSize</b> method specifies whether the Video Control automatically resizes to display its entire contents.


## -parameters




### -param vbool [in]

Specifies whether the Video Control automatically resizes. Use one of the following values.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td>VARIANT_TRUE</td>
<td>The Video Control automatically resizes.</td>
</tr>
<tr>
<td>VARIANT_FALSE</td>
<td>The Video Control does not automatically resize.</td>
</tr>
</table>
 


## -returns



If the method succeeds, it returns S_OK. If it fails, it returns an error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/msvidctl">IMSVidCtl Interface</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/msvidctl/nf-msvidctl-imsvidctl-get_autosize">IMSVidCtl::get_AutoSize</a>
 

 


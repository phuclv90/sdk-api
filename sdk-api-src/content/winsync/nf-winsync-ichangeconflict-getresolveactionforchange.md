---
UID: NF:winsync.IChangeConflict.GetResolveActionForChange
title: IChangeConflict::GetResolveActionForChange (winsync.h)
description: Gets the conflict resolution action for the conflict.
old-location: winsync\ichangeconflict_getresolveactionforchange.htm
tech.root: winsync
ms.assetid: b89124fe-200e-4061-974e-2d686de7a932
ms.date: 12/05/2018
ms.keywords: GetResolveActionForChange, GetResolveActionForChange method [Windows Sync], GetResolveActionForChange method [Windows Sync],IChangeConflict interface, IChangeConflict interface [Windows Sync],GetResolveActionForChange method, IChangeConflict.GetResolveActionForChange, IChangeConflict::GetResolveActionForChange, winsync.ichangeconflict_getresolveactionforchange, winsync/IChangeConflict::GetResolveActionForChange
f1_keywords:
- winsync/IChangeConflict.GetResolveActionForChange
dev_langs:
- c++
req.header: winsync.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
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
- COM
api_location:
- winsync.h
api_name:
- IChangeConflict.GetResolveActionForChange
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IChangeConflict::GetResolveActionForChange


## -description


Gets the conflict resolution action for the conflict.


## -parameters




### -param pResolveAction [out]

Returns the conflict resolution action for the conflict.


## -returns



The possible return codes include, but are not limited to, the values shown in the following table.

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
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
Invalid pointer.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/winsync/nn-winsync-ichangeconflict">IChangeConflict Interface</a>



<a href="https://docs.microsoft.com/windows/win32/api/winsync/ne-winsync-sync_resolve_action">SYNC RESOLVE ACTION Enumeration</a>
 

 


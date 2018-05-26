---
title: RB\_MAXIMIZEBAND message
description: Resizes a band in a rebar control to either its ideal or largest size.
ms.assetid: 79fff6d0-01f2-4308-b916-38dc06dad894
keywords:
- RB_MAXIMIZEBAND message Windows Controls
topic_type:
- apiref
api_name:
- RB_MAXIMIZEBAND
api_location:
- Commctrl.h
api_type:
- HeaderDef
ms.date: 05/31/2018
ms.topic: article
ms.author: windowssdkdev
ms.prod: windows
ms.technology: desktop
---

# RB\_MAXIMIZEBAND message

Resizes a band in a rebar control to either its ideal or largest size.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

Zero-based index of the band to be maximized.

</dd> <dt>

*lParam* 
</dt> <dd>

Indicates if the ideal width of the band should be used when the band is maximized. If this value is nonzero, the ideal width will be used. If this value is zero, the band will be made as large as possible.

</dd> </dl>

## Return value

The return value is not used.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



## See also

<dl> <dt>

**Reference**
</dt> <dt>

[**RB\_SETBANDINFO**](rb-setbandinfo.md)
</dt> </dl>

 

 





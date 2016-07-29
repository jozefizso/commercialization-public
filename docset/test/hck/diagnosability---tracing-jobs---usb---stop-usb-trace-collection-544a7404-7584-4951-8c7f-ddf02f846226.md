---
author: joshbax-msft
title: Diagnosability - Tracing Jobs - USB - Stop USB trace collection
description: Diagnosability - Tracing Jobs - USB - Stop USB trace collection
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 3e17ca61-3022-4d83-8cd8-e0aacb9834c2
---

# Diagnosability - Tracing Jobs - USB - Stop USB trace collection


This optional test is provided to help troubleshoot certain test failures and is not required for certification.

This optional test stops USB operating system trace collection. Traces are saved to the **%SystemDrive%\\USB\_Traces** folder on the Windows Hardware Certification Kit (Windows HCK) test system.

## Test details


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Associated requirements</strong></p></td>
<td><p>Device.DevFund.Reliability.Discretional System.Fundamentals.Reliability.Discretional</p>
<p>[See the system hardware requirements.](http://go.microsoft.com/fwlink/p/?linkid=254482)</p></td>
</tr>
<tr class="even">
<td><p><strong>Platforms</strong></p></td>
<td><p>Windows 7 (x64) Windows 7 (x86) Windows RT (ARM-based) Windows 8 (x64) Windows 8 (x86) Windows Server 2012 (x64) Windows Server 2008 R2 (x64) Windows RT 8.1 Windows 8.1 x64 Windows 8.1 x86 Windows Server 2012 R2</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expected run time</strong></p></td>
<td><p>~5 minutes</p></td>
</tr>
<tr class="even">
<td><p><strong>Categories</strong></p></td>
<td><p>Optional</p></td>
</tr>
<tr class="odd">
<td><p><strong>Type</strong></p></td>
<td><p>Automated</p></td>
</tr>
</tbody>
</table>

 

## Running the test


Before you can run this test, you must run the [Diagnosability - Tracing Jobs - USB - Start USB trace collection](diagnosability---tracing-jobs---usb---start-usb-trace-collection-f246772d-dccb-4d1e-9b68-9f823af0f456.md).

## Related topics


[Diagnosability - USB Tracing](diagnosability---usb-tracing.md)

 

 







---
title: At least one network for live migration traffic should have a link speed of at least 1 Gbps
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: 
  - hyper-v
  - techgroup-compute
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 5714df3f-f810-4618-8c93-e24881651100
author: KBDAzure
---
# At least one network for live migration traffic should have a link speed of at least 1 Gbps
\[This information is preliminary and subject to change.\]  
  
|||  
|-|-|  
|**Operating System**|[!INCLUDE[winthreshold_server_2](../../../includes/winthreshold_server_2_md.md)]|  
|**Product\/Feature**|Hyper\-V|  
|**Severity**|Error|  
|**Category**|Configuration|  
  
In the following sections, italics indicates UI text that appears in the Best Practices Analyzer tool for this issue.  
  
## Issue  
*None of the networks for live migration traffic have a link speed of at least 1 Gbps.*  
  
## Impact  
*Live migrations might occur slowly, which could disrupt the network connection due to a TCP connection timeout.*  
  
## Resolution  
*Configure at least one live migration network with a speed of 1 Gbps or faster.*  
  
See the documentation from your network hardware vendor to find out if any of your existing network adapters can support a link speed of at least 1 Gbps.  
  

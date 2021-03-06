---
title: "CubeName Element (XMLA) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services, azure-analysis-services"
ms.service: ""
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "CubeName Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
f1_keywords: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine#CubeName"
  - "urn:schemas-microsoft-com:xml-analysis#CubeName"
  - "microsoft.xml.analysis.cubename"
helpviewer_keywords: 
  - "CubeName element"
ms.assetid: c5c0546e-b9b2-4813-82a9-b028628b88dc
caps.latest.revision: 12
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
ms.workload: "Inactive"
---
# CubeName Element (XMLA)
[!INCLUDE[ssas-appliesto-sqlas-aas](../../../includes/ssas-appliesto-sqlas-aas.md)]
  Contains the name of the cube represented by the parent [Cube](../../../analysis-services/xmla/xml-elements-properties/cube-element-olapinfo-xmla.md) element.  
  
## Syntax  
  
```xml  
  
<Cube>  
   ...  
   <CubeName>...</CubeName>  
   ...  
</Cube>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|String|  
|Default value|None|  
|Cardinality|1-1: Required element that occurs once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Cube](../../../analysis-services/xmla/xml-elements-properties/cube-element-olapinfo-xmla.md)|  
|Child elements|None|  
  
## Remarks  
  
## See Also  
 [Properties &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-properties/xml-elements-properties.md)  
  
  

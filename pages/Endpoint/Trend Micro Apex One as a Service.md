---
layout: default
title: Trend Micro Apex One as a Service - Endpoint
---

# Trend Micro Apex One as a Service
**Layer:** Endpoint

This documentation provides detailed information about all fields available for Trend Micro Apex One as a Service.

<style>

.table-container {
  width: 100%;
  overflow-x: auto;
  margin: 20px 0;
}

.property-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 13px;
  table-layout: fixed;
}

.property-table th,
.property-table td {
  border: 1px solid #ddd;
  padding: 6px;
  text-align: left;
  vertical-align: top;
  word-wrap: break-word;
  overflow-wrap: break-word;
}

.property-table th {
  background-color: #f2f2f2;
  font-weight: bold;
  position: sticky;
  top: 0;
  z-index: 10;
}

.property-table tr:nth-child(even) {
  background-color: #f9f9f9;
}

.property-table tr:hover {
  background-color: #f5f5f5;
}

.field-name {
  width: 12%;
  font-family: 'Courier New', monospace;
  font-weight: bold;
  font-size: 12px;
}

.type {
  width: 8%;
  font-family: 'Courier New', monospace;
  font-size: 11px;
}

.general-field {
  width: 12%;
  text-align: center;
  font-size: 11px;
}

.description {
  width: 25%;
  line-height: 1.3;
  font-size: 12px;
}

.example {
  width: 20%;
  font-family: 'Courier New', monospace;
  font-size: 10px;
  line-height: 1.2;
}

.products {
  width: 25%;
  font-size: 10px;
}

.example ul, .general-field ul, .products ul {
  margin: 0;
  padding-left: 12px;
  list-style-type: disc;
}

.example li, .general-field li, .products li {
  margin: 1px 0;
  word-break: break-word;
}

/* Responsive design */
@media screen and (max-width: 1200px) {
  .property-table {
    font-size: 12px;
  }
  
  .field-name {
    width: 12%;
  }
  
  .type {
    width: 8%;
  }
  
  .general-field {
    width: 12%;
  }
  
  .description {
    width: 25%;
  }
  
  .example {
    width: 20%;
  }
  
  .products {
    width: 25%;
  }
}

@media screen and (max-width: 768px) {
  .property-table {
    font-size: 11px;
  }
  
  .property-table th,
  .property-table td {
    padding: 4px;
  }
  
  .field-name {
    width: 12%;
    font-size: 11px;
  }
  
  .type {
    width: 8%;
    font-size: 10px;
  }
  
  .general-field {
    width: 12%;
    font-size: 10px;
  }
  
  .description {
    width: 25%;
    font-size: 11px;
  }
  
  .example {
    width: 20%;
    font-size: 9px;
  }
  
  .products {
    width: 25%;
    font-size: 9px;
  }
}

</style>

<div class="table-container">

<table class="property-table">
  <thead>
    <tr>
      <th class="field-name">Field Name</th>
      <th class="type">Type</th>
      <th class="general-field">General Field</th>
      <th class="description">Description</th>
      <th class="example">Example</th>
      <th class="products">Products</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="field-name">accessPermission</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The access permission type</td>
      <td class="example">
        <ul>
          <li>Modify</li>
          <li>Read and execute</li>
          <li>List device content only</li>
          <li>Block</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">act</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The actions taken to mitigate the event</td>
      <td class="example">
        <ul>
          <li>log</li>
          <li>isolate</li>
          <li>terminate</li>
          <li>not blocked</li>
          <li>Block</li>
          <li>No action</li>
          <li>Reset</li>
          <li>Pass</li>
          <li>User Decision</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Vision One Container Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Email Sensor</li>
          <li>Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">actResult</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The result of an action</td>
      <td class="example">
        <ul>
          <li>Dropped</li>
          <li>Successful</li>
          <li>Accepted</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne StellarOne</li>
          <li>Mobile Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">additionalInfo</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The filter rule info</td>
      <td class="example">Default</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">aggregatedCount</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The number of aggregated events</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
          <li>3</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne StellarOne</li>
          <li>Data Detection and Response</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">application</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the requested application</td>
      <td class="example">
        <ul>
          <li>HyperText Transfer Protocol</li>
          <li>DoubleClick</li>
          <li>The Secure HyperText Transfer Protocol</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">authId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The authorization ID</td>
      <td class="example">
        <ul>
          <li>999</li>
          <li>996</li>
          <li>997</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">behaviorCat</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The matched policy category</td>
      <td class="example">
        <ul>
          <li>Policy Enforcement</li>
          <li>Grey-Detection</li>
          <li>Threat-Detection</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">blocking</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The blocking type</td>
      <td class="example">
        <ul>
          <li>Web reputation</li>
          <li>Web Server</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">bmGroup</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The one-to-many data structure</td>
      <td class="example">logGenLocalDatetime:2022-07-08T09:21:11+00:00, act:Assessment, behaviorType:Registry, riskConfidenceLevel:1, ruleId:7, ruleName:New Service, behaviorCategory:Policy Enforcement, processFilePath:C:\Windows\SysWOW64\srts\wmipr.exe, aegisOperation:Set Key, objectFilePath:HKLM\SYSTEM\CurrentControlSet\Services\DpsiBSvc\Start, policyId:007, objectFileHashSha1:null, objectCmd:null, processFileHashSha1:null, processCmd:null, objectRegistryData:null, objectRegistryKeyHandle:null, objectRegistryValue:null</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">cat</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The weighted priority of the incident</td>
      <td class="example">
        <ul>
          <li>100</li>
          <li>200</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">cccaDetection</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Is this log identified as a C&amp;C callback address detection</td>
      <td class="example">Yes</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">cccaDetectionSource</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Which list defines this CCCA detection rule</td>
      <td class="example">
        <ul>
          <li>CCCA_GLOBAL_LIST (0)</li>
          <li>GLOBAL_INTELLIGENCE</li>
          <li>USER_DEFINED</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">cccaRiskLevel</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The severity level of the threat actors associated with the C&amp;C servers</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">censusMaturityValue</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The CENSUS maturity value</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">censusPrevalenceValue</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The CENSUS prevalence value</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">channel</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The channel through which the demanded WinEvent is delivered</td>
      <td class="example">
        <ul>
          <li>Local file or network drive</li>
          <li>Local file</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">channel</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event channel</td>
      <td class="example">
        <ul>
          <li>Security</li>
          <li>Microsoft-Windows-WMI-Activity/Trace</li>
          <li>Microsoft-Windows-TaskScheduler/Operational</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">clientStatus</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The client status when the event occurred</td>
      <td class="example">
        <ul>
          <li>Rebuilding database</li>
          <li>Online</li>
          <li>Offline</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">compressedFileHash</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the decompressed archive</td>
      <td class="example">
        <ul>
          <li>6E2ECB34B7798E179CC704111FB9733FBAAD5ACA</li>
          <li>FA71B59F35F0EE44D27F74917EF5A0DA2797E80B</li>
          <li>14D2302172EB81465CE12E01361AE24CDE170F7B</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">compressedFileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the compressed suspicious file</td>
      <td class="example">
        <ul>
          <li>60C7C5924DD09F7C6B150120FB92DCEE00AE82DB75C7402FA4D9152CF487A94F</li>
          <li>482FFC4F87B78C3C7073983CF65B593D9F13F0A3D6DC54B4A3F616F79838F3CE</li>
          <li>68C0126D9B4B0FC32DE181D0D67DA8FE82E23745F6023317D5E053B6F6ED26CF</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">compressedFileName</td>
      <td class="type">string</td>
      <td class="general-field">FileName</td>
      <td class="description">The file name of the compressed file</td>
      <td class="example">
        <ul>
          <li>/proc/32058/fd/150</li>
          <li>NONAMEFL</li>
          <li>/proc/10006/fd/30</li>
          <li>VirusActionSample/RPF2_OtherMalwareSample-other.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">computerDomain</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The computer domain</td>
      <td class="example">
        <ul>
          <li>COMCEL_DOMINIO</li>
          <li>HDWA</li>
          <li>RANDON</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">confidence</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The confidence rating returned from TrendX Hybrid Model (predictive machine learning). Values from 1-99.</td>
      <td class="example">94</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>File Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">correlationData</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The data for correlation</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">customAssetTags</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of custom asset tags</td>
      <td class="example">{&quot;os&quot;:[&quot;linux&quot;, &quot;windows&quot;], &quot;org&quot;:[&quot;bu1&quot;]}</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">customAssetTags</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of custom asset tags</td>
      <td class="example">{&quot;os&quot;:[&quot;linux&quot;, &quot;windows&quot;], &quot;org&quot;:[&quot;bu1&quot;]}</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dacDeviceType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The device type</td>
      <td class="example">
        <ul>
          <li>USB storage device</li>
          <li>Mobile devices</li>
          <li>Floppy disks</li>
          <li>Network driver</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">dceArtifactActions</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The actions performed on Damage Cleanup Engine artifacts</td>
      <td class="example">
        <ul>
          <li>folder_backup</li>
          <li>objproc_dump</li>
          <li>subproc_dump</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">destinationPath</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The intended destination of the file containing the digital asset or channel</td>
      <td class="example">
        <ul>
          <li>Cloud Storage (OneDrive)</li>
          <li>Printer</li>
          <li>example.sharepoint.com/personal/page_path/onedrive.aspx</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">detailTrace</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">Whether the detection comes with a detailed trace footprint</td>
      <td class="example">-</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">detectedActions</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The actions performed on detected artifacts</td>
      <td class="example">
        <ul>
          <li>folder_backup</li>
          <li>objproc_dump</li>
          <li>subproc_dump</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectedBackupArtifacts</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The information about detected artifacts</td>
      <td class="example">{&quot;objectArtifactId&quot;: &quot;025d9f2a-ac9c-4cdf-b9e4-cf20c6e40281_0.dmp&quot;, &quot;action&quot;: &quot;object_process_dump&quot;, &quot;status&quot;: 0, &quot;processCreationTime&quot;: &quot;1627574338077&quot;, &quot;processImageFileName&quot;: &quot;C:\Program Files\aaa\bbb\objprocess.exe&quot;}</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectedBackupArtifactsStatus</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The backup status of detected artifacts</td>
      <td class="example">[&#x27;0&#x27;, &#x27;-67&#x27;]</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectedBackupFolder</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The folder path for detected backup folders</td>
      <td class="example">C:\\Program Files (x86)\\Trend Micro\\artifact\\DCE</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectedPattern</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The detected pattern</td>
      <td class="example">dct.virus</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionAggregationIds</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of detection aggregation IDs</td>
      <td class="example">[&#x27;11111111-1111-1111-1111-111111111111&#x27;]</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionAggressivenessLevel</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The detection aggressiveness level</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
          <li>3</li>
          <li>4</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionEngineVersion</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The detection engine version</td>
      <td class="example">7.6.0</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionMeta</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The descriptions of the detected techniques</td>
      <td class="example">[&#x27;T1204 some description about this technique&#x27;, &#x27;T1573.001_AES another description about this technique&#x27;]</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The general name for the detection</td>
      <td class="example">
        <ul>
          <li>Troj.Win32.TRX.XXPE50F13017</li>
          <li>Troj.Win32.TRX.XXPE50FFF059</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Mobile Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionNames</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The rules that triggered the event</td>
      <td class="example">[&#x27;HS_EMOTET.SMAA&#x27;, &#x27;HM_AVEDOWN.SMZTIG-A&#x27;, &#x27;HE_DOCQRPHISH.SM&#x27;]</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The detection type</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>File</li>
          <li>Process</li>
          <li>net</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Email Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">deviceGUID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The GUID of the agent which reported the detection</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000</li>
          <li>11111111-1111-1111-1111-111111111111</li>
          <li>22222222-2222-2222-2222-222222222222</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">deviceModel</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The device model number</td>
      <td class="example">c96a</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">deviceSerial</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The device serial ID</td>
      <td class="example">000000063a2e8f</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">direction</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The direction</td>
      <td class="example">
        <ul>
          <li>Incoming</li>
          <li>Outgoing</li>
          <li>Unknown</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dmac</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The MAC address of the destination IP (dest_ip)</td>
      <td class="example">
        <ul>
          <li>00:00:00:00:00:00</li>
          <li>ff:ff:ff:ff:ff:ff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">domainName</td>
      <td class="type">string</td>
      <td class="general-field">DomainName</td>
      <td class="description">The detected domain name</td>
      <td class="example">
        <ul>
          <li>http://10.10.10.10</li>
          <li>example.domain.com</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dpt</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The destination port</td>
      <td class="example">
        <ul>
          <li>445</li>
          <li>80</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Endpoint Sensor</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dpt</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The destination port number</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dst</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The destination IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dst</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The destination IP address</td>
      <td class="example">
        <ul>
          <li>::</li>
          <li>10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">duser</td>
      <td class="type">dynamic</td>
      <td class="general-field">EmailRecipient</td>
      <td class="description">The email recipient</td>
      <td class="example">
        <ul>
          <li>(no user)</li>
          <li>SYSTEM</li>
          <li> SYSTEM</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dvchost</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The computer which installed the Trend Micro product</td>
      <td class="example">
        <ul>
          <li>CU-PRO1-9039-2</li>
          <li>LTPF32PMNN</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointGUID</td>
      <td class="type">string</td>
      <td class="general-field">EndpointID</td>
      <td class="description">The GUID of the agent which reported the detection</td>
      <td class="example">
        <ul>
          <li>ae4d64aa-f8b8-bb36-b265-f59272ed342f</li>
          <li>8fb979f6-1376-bed3-227f-f2886e66194e</li>
          <li>ca2b3a7e-8415-c571-cc19-e45f69470026</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>TXOne StellarOne</li>
          <li>Trend Vision One Container Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointGuid</td>
      <td class="type">string</td>
      <td class="general-field">EndpointID</td>
      <td class="description">Host GUID of the endpoint on which the event was detected</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointHostName</td>
      <td class="type">string</td>
      <td class="general-field">EndpointName</td>
      <td class="description">The endpoint hostname or node where the event was detected</td>
      <td class="example">
        <ul>
          <li>10.10.10.10 (swpos-aws-aza02) [i-0f0f0f0f0f0f0f0f0]</li>
          <li>ip-10-10-10-10.us-west-1.compute.internal</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>TXOne StellarOne</li>
          <li>Trend Vision One Container Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointHostName</td>
      <td class="type">string</td>
      <td class="general-field">EndpointName</td>
      <td class="description">The host name of the endpoint on which the event was detected</td>
      <td class="example">
        <ul>
          <li>PHILIPSIBE09</li>
          <li>WHAM6WK8XG2</li>
          <li>MacBook-Pro-del-Meno</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointIp</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The IP address of the endpoint on which the event was detected</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Network Security</li>
          <li>TXOne EdgeOne</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointIp</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">IP address of the endpoint on which the event was detected</td>
      <td class="example">
        <ul>
          <li>10.10.10.10</li>
          <li>::1</li>
          <li>fe80::1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointMacAddress</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The MAC address of endpoint</td>
      <td class="example">
        <ul>
          <li>00:00:00:00:00:00</li>
          <li>ff:ff:ff:ff:ff:ff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>TXOne EdgeOne</li>
          <li>TXOne StellarOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">endpointMacAddress</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The host MAC address</td>
      <td class="example">
        <ul>
          <li>0-0-0-0-0-0-0-e0</li>
          <li>00:00:00:ff:ff:ff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">engineOperation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The operation of the engine event</td>
      <td class="example">
        <ul>
          <li>Set Key</li>
          <li>Invoke API</li>
          <li>Create</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">engType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The engine type</td>
      <td class="example">
        <ul>
          <li>Virus Scan Engine (Windows XP/Server 2003, x64)</li>
          <li>Virus Scan NT Kernel Engine</li>
          <li>Spyware/Grayware Scan Engine v.6 (64-bit)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>File Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">engVer</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The engine version</td>
      <td class="example">
        <ul>
          <li>1.0.0.1123_1.0.0.1101</li>
          <li>9.0.1004</li>
          <li>22.540.1001</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>File Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataAccessList</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The list of requested access rights</td>
      <td class="example">
        <ul>
          <li>%%4416</li>
          <li>%%4417</li>
          <li>%%4418</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataAccessMask</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The hexadecimal value of the requested or used permissions during an access attempt</td>
      <td class="example">
        <ul>
          <li>16</li>
          <li>2147483648</li>
          <li>1048576</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataActionName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The action performed</td>
      <td class="example">
        <ul>
          <li>Language Components Installer</li>
          <li>Group Policy Background Processing</li>
          <li>C:\Program Files (x86)\Microsoft\EdgeUpdate\MicrosoftEdgeUpdate.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataAuthenticationPackageName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The authentication package name of the Windows event data</td>
      <td class="example">
        <ul>
          <li>NTLM</li>
          <li>Negotiate</li>
          <li>MICROSOFT_AUTHENTICATION_PACKAGE_V1_0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataElevatedToken</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Whether the session is elevated and has administrator privileges</td>
      <td class="example">
        <ul>
          <li>%%1842</li>
          <li>%%1843</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataFullyQualifiedAssemblyName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The fully qualified .NET assembly name</td>
      <td class="example">
        <ul>
          <li>System.Runtime, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a</li>
          <li>System.Xml, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089</li>
          <li>System.Diagnostics.Process, Version=8.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataImpersonationLevel</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in session impersonation level</td>
      <td class="example">
        <ul>
          <li>%%1830</li>
          <li>%%1832</li>
          <li>%%1833</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataIpAddress</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The IP address for Windows event 4624 which is &quot;An account was successfully logged on&quot;</td>
      <td class="example">
        <ul>
          <li>-</li>
          <li>10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataJobOwner</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the account that initiated the event</td>
      <td class="example">
        <ul>
          <li>BEI\holdej</li>
          <li>NT AUTHORITY\SYSTEM</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">eventDataLogonProcessName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the Windows event sign in process name</td>
      <td class="example">
        <ul>
          <li>NtLmSsp </li>
          <li>Advapi  </li>
          <li>Advapi</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataLogonType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The logon type for Windows event 4624 which is &quot;An account was successfully logged on&quot;</td>
      <td class="example">
        <ul>
          <li>3</li>
          <li>5</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataModuleILPath</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The CIL image path of the module or the dynamic module name</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\Cymulate\Agent\System.Threading.dll</li>
          <li>C:\windows\system32\tzsync.exe</li>
          <li>C:\Program.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The identifying information about the object for which access was requested</td>
      <td class="example">
        <ul>
          <li>\Device\HarddiskVolume2\Windows\System32\lsass.exe</li>
          <li>C:\Windows\System32\osk.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object type</td>
      <td class="example">
        <ul>
          <li>Process</li>
          <li>File</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataOperation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Windows event 11</td>
      <td class="example">
        <ul>
          <li>Start IWbemServices::ExecQuery - root\ccm : select * from SMS_Authority</li>
          <li>Start IWbemServices::ExecQuery - root\cimv2 : select * from win32_process</li>
          <li>Start IWbemServices::ExecQuery - root\ccm : SELECT * FROM SMS_Authority</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataPath</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The path of the Windows event data</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\Common Files\Microsoft Shared\ClickToRun\officesvcmgr.exe</li>
          <li>taskhostw.exe</li>
          <li>gpupdate.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataProcessPath</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The process path that initiated the event</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\Microsoft Office\Office15\OUTLOOK.EXE</li>
          <li>C:\Program Files (x86)\Common Files\Adobe\ARM\1.0\AdobeARM.exe</li>
          <li>C:\Program Files\Microsoft Office\root\Office16\OUTLOOK.EXE</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">eventDataScriptBlockText</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Windows event 4104, Creating Scriptblock text</td>
      <td class="example">
        <ul>
          <li>$global:?</li>
          <li>0</li>
          <li>{ Set-StrictMode -Version 1; $_.PSMessageDetails }</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">eventDataStatus</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event data status</td>
      <td class="example">
        <ul>
          <li>0xc000006d</li>
          <li>-1073741715</li>
          <li>0xc000006e</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubjectUserName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The account name</td>
      <td class="example">
        <ul>
          <li>dadmin</li>
          <li>Alex</li>
          <li>london$</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubStatus</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event data sub status</td>
      <td class="example">
        <ul>
          <li>0xc0000064</li>
          <li>0xc000006a</li>
          <li>-1073741724</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetDomainName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The target sign-in account domain or computer name</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>Builtin</li>
          <li>SHOCKWAVE</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The service, application, or network resource name</td>
      <td class="example">
        <ul>
          <li>Microsoft_RssPlatform_*</li>
          <li>WindowsLive:target=virtualapp/didlogical</li>
          <li>MicrosoftOffice*</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetUserName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The user name of the Windows event data target</td>
      <td class="example">
        <ul>
          <li>Offer Remote Assistance Helpers</li>
          <li>Administrators</li>
          <li>Administradores</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTaskName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The task name logged by the Windows event</td>
      <td class="example">
        <ul>
          <li>\Microsoft\Windows\LanguageComponentsInstaller\Installation</li>
          <li>\Microsoft\Office\Office Serviceability Manager</li>
          <li>\MicrosoftEdgeUpdateTaskMachineUA</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataTicketEncryptionType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The cryptographic suite used for the Kerberos TGS</td>
      <td class="example">
        <ul>
          <li>0x12</li>
          <li>0x17</li>
          <li>0x18</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataTicketOptions</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The authentication request Kerberos ticket behavior and permissions flags</td>
      <td class="example">
        <ul>
          <li>0x40810000</li>
          <li>0x40810010</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataUserContext</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The user context of the Windows event data</td>
      <td class="example">
        <ul>
          <li>MP\MPBSA179345$</li>
          <li>MP\MPBSASPU179370$</li>
          <li>MP\MPBSA4025625$</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventDataWorkstationName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the computer used in the sign-in attempt</td>
      <td class="example">
        <ul>
          <li>WIN-GG82ULGC9GO</li>
          <li>DESKTOP-123ABC</li>
          <li>CLIENT01</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventHashId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The event hash ID</td>
      <td class="example">
        <ul>
          <li>-8406473586387535914</li>
          <li>138486453338666581</li>
          <li>-7909265752378976284</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The event ID from the logs of each product</td>
      <td class="example">
        <ul>
          <li>100100</li>
          <li>100101</li>
          <li>100116</li>
          <li>100117</li>
          <li>100119</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Email Security</li>
          <li>TXOne StellarOne</li>
          <li>Trend Vision One Container Security</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">Event type</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventMessage</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The event message</td>
      <td class="example">[0x13bb4e2a0] activating connection: mach=true listener=false peer=false name=com.apple.airportd</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The event type</td>
      <td class="example">
        <ul>
          <li>LOG_INSPECTION_EVENT</li>
          <li>SECURITY_RISK_DETECTION</li>
          <li>WEB_THREAT_DETECTION</li>
          <li>LOG_INSPECTION_EVENT</li>
          <li>MALWARE_DETECTION</li>
          <li>PROCESS_ACTIVITY</li>
          <li>WEB_POLICY_VIOLATION</li>
          <li>DEEP_PACKET_INSPECTION_EVENT</li>
          <li>INTEGRITY_MONITORING_EVENT</li>
          <li>DISRUPTIVE_APPLICATION_DETECTION</li>
          <li>PRODUCT_SUMMARY</li>
          <li>PRODUCT_UPDATE</li>
          <li>BEHAVIORAL_VIOLATION</li>
          <li>FIREWALL_POLICY_VIOLATION</li>
          <li>SUSPICIOUS_BEHAVIOUR_DETECTION</li>
          <li>DENYLIST_CHANGE</li>
          <li>MACHINE_LEARNING_DETECTION</li>
          <li>DLP_VIOLATION</li>
          <li>MALWARE_OUTBREAK_DETECTION</li>
          <li>SENSITIVE_DATA_DETECTION</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>TXOne StellarOne</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventSubId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The access type</td>
      <td class="example">
        <ul>
          <li>2 - TELEMETRY_PROCESS_CREATE</li>
          <li>101 - TELEMETRY_FILE_CREATE</li>
          <li>204 - TELEMETRY_CONNECTION_CONNECT_OUTBOUND</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventSubName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The event type sub-name</td>
      <td class="example">
        <ul>
          <li>IPS Detection</li>
          <li>Personal Firewall</li>
          <li>Attack Discovery</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Email Security</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent detected the event</td>
      <td class="example">1657781088000</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">extraInfo</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The network application name</td>
      <td class="example">
        <ul>
          <li>N/A</li>
          <li>Web Client Common</li>
          <li>DCERPC Services</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">fileCreation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file creation date</td>
      <td class="example">1595918517000</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">fileDesc</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file description</td>
      <td class="example">
        <ul>
          <li>Atualiza PJRO</li>
          <li>Carpeta de archivos</li>
          <li>7z Setup SFX (x86)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileHash</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the file that triggered the rule or policy</td>
      <td class="example">
        <ul>
          <li>DA39A3EE5E6B4B0D3255BFEF95601890AFD80709</li>
          <li>89CE26EAD139D52B8A6B61BFFC6AF89AF246580F</li>
          <li>3AD1F4E7CAA11E5199EE80B8983677ADDD065450</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the file (fileName)</td>
      <td class="example">
        <ul>
          <li>6A6EB2D717CEA041B4444193B45EDFB6CA1287518203B7230B3C4B8FFB031EAB</li>
          <li>BFF703FF836196644586014DA13A097C2EE9A08E4D596DFB7C8E0F685FE01294</li>
          <li>12327F460AC9CBBC34D39EB3CF89C7FECCA37F08773A04566840F73F6ECC4104</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileName</td>
      <td class="type">dynamic</td>
      <td class="general-field">FileName</td>
      <td class="description">The file name</td>
      <td class="example">
        <ul>
          <li>spoolss</li>
          <li>hosts</li>
          <li>svcrestarttask</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne StellarOne</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">filePath</td>
      <td class="type">string</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The file path without the file name</td>
      <td class="example">
        <ul>
          <li>security</li>
          <li>/var/log/audit/audit.log</li>
          <li>application</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>TXOne StellarOne</li>
          <li>File Security</li>
          <li>File Security Storage</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the suspicious file</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1255856</li>
          <li>1237880</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileVer</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file version</td>
      <td class="example">
        <ul>
          <li>10.0.19041.1</li>
          <li>10.0.19041.1766</li>
          <li>10.0.18362.1</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">filterName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The filter name</td>
      <td class="example">
        <ul>
          <li>ConnectionFilter</li>
          <li>Virtual Analyzer</li>
          <li>Data Loss Prevention</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">filterType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The filter type</td>
      <td class="example">
        <ul>
          <li>Spam filter</li>
          <li>Size filter</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">firstAct</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The first scan action</td>
      <td class="example">
        <ul>
          <li>Pass</li>
          <li>Quarantine</li>
          <li>Clean</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">firstActResult</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The first scan action result</td>
      <td class="example">
        <ul>
          <li>File passed</li>
          <li>Unable to quarantine file</li>
          <li>File quarantined</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">firstSeen</td>
      <td class="type">real</td>
      <td class="general-field">-</td>
      <td class="description">The first time the event was seen</td>
      <td class="example">1656355418449</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">forensicFileHash</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The hash value of the forensic data file</td>
      <td class="example">
        <ul>
          <li>177844c5927d0f20da06d79d986c7e7f8c7a3b6a</li>
          <li>da39a3ee5e6b4b0d3255bfef95601890afd80709</li>
          <li>8dab234ab6cd96301f9452994f015a449d629edd</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">forensicFilePath</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file path of the forensic file (When a Data Loss Prevention policy is triggered, the file is encrypted and copied to the OfficeScan server for post-mortem analysis)</td>
      <td class="example">
        <ul>
          <li>C:\Program Files (x86)\Trend Micro\OfficeScan Client\dlplite\forensic\frnsc_200411DC0594_xml_00000000000_20220314_132326281</li>
          <li>C:\Program Files (x86)\Trend Micro\OfficeScan Client\dlplite\forensic\frnsc_CIL-OPRCOGEN_docx_00000000000_20211025_225445873</li>
          <li>C:\Program Files (x86)\Trend Micro\OfficeScan Client\dlplite\forensic\frnsc_SHA-ESHOU_h265_00000000000_20220601_082417865</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">ftpUser</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The FTP login user name</td>
      <td class="example">
        <ul>
          <li>USER\TREND</li>
          <li>User</li>
          <li>ftpuser_service</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">fullPath</td>
      <td class="type">string</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The combination of the file path and the file name</td>
      <td class="example">
        <ul>
          <li>\etc\hosts</li>
          <li>c:\windows\system32\tasks\microsoft\windows\softwareprotectionplatform\svcrestarttask</li>
          <li>\var\log\auth.log</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne StellarOne</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">hookId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The hook ID</td>
      <td class="example">
        <ul>
          <li>-1</li>
          <li>5</li>
          <li>4</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">hostName</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>DomainName</li>
          <li>HostDomain</li>
        </ul>
      </td>
      <td class="description">The domain name</td>
      <td class="example">
        <ul>
          <li>localhost</li>
          <li>wpad</li>
          <li>settings-win.data.microsoft.com</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">httpReferer</td>
      <td class="type">string</td>
      <td class="general-field">URL</td>
      <td class="description">The HTTP referer</td>
      <td class="example">
        <ul>
          <li>http://172.16.58.233/</li>
          <li>http://example/page1/</li>
          <li>https://www.google.com/</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">httpReferer</td>
      <td class="type">string</td>
      <td class="general-field">URL</td>
      <td class="description">The HTTP header referer</td>
      <td class="example">
        <ul>
          <li>http://10.10.10.10/</li>
          <li>http://fake/home/</li>
          <li>http://fake.com/page/Test.jsp</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">instanceId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The ID of the instance that indicates the meta-cloud or data center VM</td>
      <td class="example">
        <ul>
          <li>52294e7b-f732-c6e9-b2c3-7a6b6f50d101</li>
          <li>00030912-c5e7-4348-9012-7c684751c531</li>
          <li>0008ae58-db0c-34ee-3e5c-5dfc9b10a739</li>
          <li>i-0b22a22eec53b9321</li>
          <li>/subscriptions/bae4f362-e3a0-482f-ba7a-f883d8b410ce/resourceGroups/avtd-csf-sg-lzniibr0/providers/Microsoft.Compute/virtualMachines/avtd-csf-scanner-lzniibr0</li>
          <li>ocid1.instance.oc1.us-ashburn-1.an2g6ljrgs553pqcjuokzvvwpmwxh564f6f5sx3jpi2sowt6as44uejmsrzq</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">integrityLevel</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The integrity level of a process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">interestedHost</td>
      <td class="type">string</td>
      <td class="general-field">DomainName</td>
      <td class="description">The endpoint hostname (For example, if an intranet host accesses a suspicious internet host, the intranet host is the &quot;peerHost&quot; and the internet host is the &quot;interestedHost&quot;)</td>
      <td class="example">
        <ul>
          <li>10.10.10.10 (swpos-aws-aza02) [i-0f0f0f0f0f0f0f0f0]</li>
          <li>es-dtc-w-dc02.example.corp</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">interestedIp</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The IP of the interestedHost</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Network Security</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">interestedMacAddress</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The MAC address identified as the log owner&#x27;s</td>
      <td class="example">
        <ul>
          <li>00:00:00:00:00:00</li>
          <li>ff:ff:ff:ff:ff:ff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">isHidden</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Whether the detection log generated a grey rule match</td>
      <td class="example">Yes</td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">isProxy</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">Whether something is a proxy</td>
      <td class="example">False</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">lastSeen</td>
      <td class="type">real</td>
      <td class="general-field">-</td>
      <td class="description">The last time the event was seen</td>
      <td class="example">1656355418449</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">logKey</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The unique key of the event</td>
      <td class="example">
        <ul>
          <li>123e4567-e89b-12d3-a456-426614174000</li>
          <li>987f6543-21ba-43cd-9e8f-123456789abc</li>
          <li>456789ab-cdef-1234-5678-9abcdef01234</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">logonUser</td>
      <td class="type">dynamic</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The logon user name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>SISTEMA</li>
          <li>oracle</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailDeliveryTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The mail delivery time</td>
      <td class="example">1900-1-1 00:00:00</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">mailMsgSubject</td>
      <td class="type">string</td>
      <td class="general-field">EmailSubject</td>
      <td class="description">The email subject</td>
      <td class="example">
        <ul>
          <li>FW. mail subject</li>
          <li>ManageEngine</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">malDst</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The malware infection destination</td>
      <td class="example">
        <ul>
          <li>3334_02W3P7</li>
          <li>2666_02N413</li>
          <li>3334_02NHEL</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">malFamily</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The threat family</td>
      <td class="example">
        <ul>
          <li>EQUATED</li>
          <li>STARTER</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>File Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">malName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the detected malware</td>
      <td class="example">
        <ul>
          <li>SecurityLevelDrop</li>
          <li>Regla Logs All</li>
          <li>USR_SUSPICIOUS_DOMAIN.UMXX</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Web Security</li>
          <li>TXOne StellarOne</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">malSrc</td>
      <td class="type">string</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The malware infection source</td>
      <td class="example">
        <ul>
          <li>\\10.172.1.33\kortiz</li>
          <li>\\10.240.0.148\wbind</li>
          <li>\\10.240.1.69\MT26933059</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">malSubType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The subsidiary virus type</td>
      <td class="example">Unknown</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>File Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">malType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The risk type for Network Content Correlation Engine rules</td>
      <td class="example">
        <ul>
          <li>OTHERS</li>
          <li>MALWARE</li>
          <li>Others</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>File Security</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">matchedContent</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The one-to-many data structure</td>
      <td class="example">
        <ul>
          <li>[&#x27;matchedContentEx:client_id=00000000-0000-0000-0000-000000000000&amp;redirect_uri=https://example.page.com, matchedInfo:0,6|0,6&#x27;]</li>
          <li>[&#x27;matchedContentEx:example string, matchedInfo:0,6&#x27;]</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">mDevice</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">IP of the source</td>
      <td class="example">
        <ul>
          <li>10.10.10.10</li>
          <li>fe80::1234:5678:9abc:def0</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">mDeviceGUID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The GUID of the agent host</td>
      <td class="example">
        <ul>
          <li>C5B09EDD-C725-907F-29D9-B8C30D18C48F</li>
          <li>C05B75AB-B518-BDD0-D2B5-E9CB631C539F</li>
          <li>9C28ACD3-D0EC-22A4-B08D-5B0BEFF501FC</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">messageType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The message type</td>
      <td class="example">Default</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">moduleName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The module where a hook procedure was set up</td>
      <td class="example">
        <ul>
          <li>c:\program files (x86)\desktopcentral_agent\bin\dcusbsummary.exe</li>
          <li>c:\program files\common files\microsoft shared\clicktorun\officesvcmgr.exe</li>
          <li>c:\program files (x86)\sharp\sharp pen software\prsnspttool.exe</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">moduleScanType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The module scan type</td>
      <td class="example">traditional</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mpname</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The management product name</td>
      <td class="example">
        <ul>
          <li>Cloud One - Workload Security</li>
          <li>Apex Central</li>
          <li>Deep Security Software</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mpver</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The product version</td>
      <td class="example">
        <ul>
          <li>Microsoft-Windows-Security-Auditing</li>
          <li>Level -- Medium security</li>
          <li>TASK1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">msgAct</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The message action</td>
      <td class="example">
        <ul>
          <li>Quarantine</li>
          <li>Deliver</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">msgId</td>
      <td class="type">string</td>
      <td class="general-field">EmailMessageID</td>
      <td class="description">The internet message ID</td>
      <td class="example">
        <ul>
          <li>66.6.00.0006</li>
          <li>example.test.com</li>
          <li>dameware1svr</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectAppName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Name of the app involved in the AMSI event</td>
      <td class="example">
        <ul>
          <li>Exchange Server 2016</li>
          <li>PowerShell_C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe_10.0.19041.1</li>
          <li>PowerShell_C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe_10.0.14393.0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectArtifactIds</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The artifact IDs generated by objectAction</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000_0.dmp</li>
          <li>11111111-1111-1111-1111-111111111111_2.bak</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectAttributes</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object attributes</td>
      <td class="example">attribute</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectAuthId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object authorization ID</td>
      <td class="example">
        <ul>
          <li>999</li>
          <li>996</li>
          <li>997</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectCmd</td>
      <td class="type">dynamic</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The object process command line</td>
      <td class="example">
        <ul>
          <li>C:\WINDOWS\system32\wbem\wmiprvse.exe -Embedding</li>
          <li>&quot;C:\WINDOWS\system32\WindowsPowerShell\v1.0\PowerShell.exe&quot; -NoLogo -Noninteractive -NoProfile  -ExecutionPolicy Bypass &quot;&amp; &#x27;C:\WINDOWS\CCM\SystemTemp\afd6f0e5-e491-4764-a20a-9f1d9edf3cce.ps1&#x27;&quot;</li>
          <li>C:\WINDOWS\system32\lsass.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectCmd</td>
      <td class="type">string</td>
      <td class="general-field">CLICommand</td>
      <td class="description">Command line entry of target process</td>
      <td class="example">
        <ul>
          <li>wc -l</li>
          <li>runc init</li>
          <li>docker-init --version</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectContentName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The AMSI object content name</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\WindowsPowerShell\Modules\PowerShellGet\1.2\PowerShellGet.psd1</li>
          <li>c:\synclog\BLAST_SCAN.vbs</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectCurrentFileSize</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">Previous size of modified object file</td>
      <td class="example">
        <ul>
          <li>59456</li>
          <li>60</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectEntityName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object entity name</td>
      <td class="example">
        <ul>
          <li>any_process</li>
          <li>exe_file</li>
          <li>powershell</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">objectFileAccess</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object file access details</td>
      <td class="example">1717658631000</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileCreation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The UTC time that the object was created</td>
      <td class="example">
        <ul>
          <li>2014-11-22T01:45:51-06:00</li>
          <li>2009-07-13T23:31:13-05:00</li>
          <li>2014-11-21T02:43:28-05:00</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileCreation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the object file was created</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1648279273000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileCurrentOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current owner name of the object file</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY\SYSTEM</li>
          <li>BUILTIN\Administrators</li>
          <li>BUILTIN\Administradores</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileCurrentOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current security identifier owner of the object file</td>
      <td class="example">
        <ul>
          <li>S-1-5-18</li>
          <li>S-1-5-32-544</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileDaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The discretionary access control list of the object file</td>
      <td class="example">
        <ul>
          <li>D:(A;;FA;;;S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464)(A;;0x1200a9;;;BA)(A;;0x1200a9;;;SY)(A;;0x1200a9;;;BU)(A;;0x1200a9;;;AC)(A;;0x1200a9;;;S-1-15-2-2)</li>
          <li>D:(A;OICI;GA;;;SY)(A;OICI;0xa0120000;;;WD)(A;OICI;GA;;;BA)</li>
          <li>D:(A;ID;FA;;;SY)(A;ID;FA;;;BA)(A;ID;0x1200a9;;;BU)(A;ID;0x1200a9;;;AC)(A;ID;0x1200a9;;;S-1-15-2-2)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileExtendedAttribute</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The extended attributes of the file</td>
      <td class="example">
        <ul>
          <li>com.apple.quarantine</li>
          <li>com.apple.metadata:kMDItemWhereFroms</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileGroupName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object file user group name</td>
      <td class="example">
        <ul>
          <li>wheel</li>
          <li>staff</li>
          <li>admin</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileGroupSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the object file group</td>
      <td class="example">
        <ul>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-18</li>
          <li>S-1-5-21-397955417-626881126-188441444-513</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object file hash ID</td>
      <td class="example">
        <ul>
          <li>2141057820373638746</li>
          <li>-6516669617381620295</li>
          <li>-4912169863817247597</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashMd5</td>
      <td class="type">string</td>
      <td class="general-field">FileMD5</td>
      <td class="description">The MD5 of the object</td>
      <td class="example">
        <ul>
          <li>801E8003C257C8F540B20F1E0DECD3A6</li>
          <li>CDA48FC75952AD12D99E526D0B6BF70A</li>
          <li>D5120786925038601A77C2E1EB9A3A0A</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashMd5</td>
      <td class="type">string</td>
      <td class="general-field">FileMD5</td>
      <td class="description">The md5 hash of target process image or target file</td>
      <td class="example">
        <ul>
          <li>7ac47235c7bb452a03d3afd872f44c9e</li>
          <li>c9873d83a969645a97f21adc1b164cc5</li>
          <li>3b32b378c8b288de6f15e1607a8c2145</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashSha1</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the objectFilePath object</td>
      <td class="example">
        <ul>
          <li>51B8646308EE0B68AD1F7F1291B85395434DE49A</li>
          <li>36C5D12033B2EAF251BAE61C00690FFB17FDDC87</li>
          <li>2586528000199793730B05D3F169BCF139E4D7A1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashSha1</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA1 hash of target process image or target file</td>
      <td class="example">
        <ul>
          <li>ded3833f145989fd86c1f4811b61497298ebc7fd</li>
          <li>c4fa06404142f1994431f9eef3df2cbe0f1998f1</li>
          <li>3c01d486ed5aa1ecc2d8f33dc24b0ed59b3e609e</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the object (objectFilePath)</td>
      <td class="example">
        <ul>
          <li>A75C85F3B089993E9C042FB82ECB7757E8F460ED8065FC7991CAA38A6DE0F50C</li>
          <li>908B64B1971A979C7E3E8CE4621945CBA84854CB98D76367B791A6E22B5F6D53</li>
          <li>1A2ABAAD8A166B66CA35AB51C7432C5A7E46996472C8174281842896408D7F96</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA256 hash of target process image or target file</td>
      <td class="example">
        <ul>
          <li>39109eef00821658893b45634fe2f4664f880da9242712df907f1327d4ceefb8</li>
          <li>49fa3e206abf6a1f4546417dbe09f3f06b38847866a4a66de75bd90f39cb6c1c</li>
          <li>0969321ad5a0923f0f03896ad2c10e49290515c44b721d773942a37f62a24893</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileIsRemoteAccess</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">The remote access to the object file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileModified</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The UTC time that the object was modified</td>
      <td class="example">
        <ul>
          <li>2024-10-10T10:10:10.0000000Z</li>
          <li>2024-11-11T11:11:11.0000000Z</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileModifiedTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the object file was modified</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1648279273000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileName</td>
      <td class="type">string</td>
      <td class="general-field">FileName</td>
      <td class="description">The object file name</td>
      <td class="example">
        <ul>
          <li>powershell.exe</li>
          <li>wmiprvse.exe</li>
          <li>dismhost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Vision One Container Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileOriginalName</td>
      <td class="type">string</td>
      <td class="general-field">FileName</td>
      <td class="description">The original file name of the object image</td>
      <td class="example">
        <ul>
          <li>Taskmgr.exe</li>
          <li>WINLOGON.EXE</li>
          <li>svchost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object file owner name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>NT SERVICE\TrustedInstaller</li>
          <li>BUILTIN\Administrators</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the object file owner</td>
      <td class="example">
        <ul>
          <li>S-1-5-32-544</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-18</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFilePath</td>
      <td class="type">string</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The file path of the target process image or target file</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\windowspowershell\v1.0\powershell.exe</li>
          <li>zwwritevirtualmemory</li>
          <li>c:\windows\system32\wbem\wmiprvse.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFilePath</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The file path of the target process image or target file</td>
      <td class="example">
        <ul>
          <li>/usr/bin/bash</li>
          <li>/bin/bash</li>
          <li>/opt/folder1/probes/system/processes/processes</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileRemoteAccess</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">The remote access for the object file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileSaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The system access control list of the object file</td>
      <td class="example">
        <ul>
          <li>S:NO_ACCESS_CONTROL</li>
          <li>S:(AU;SAFA;DCLCRPCRSDWDWO;;;WD)</li>
          <li>S:(AU;SAFA;0x1f0116;;;WD)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the object file</td>
      <td class="example">
        <ul>
          <li>59456</li>
          <li>60</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFirstRecorded</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The first time that the object appeared</td>
      <td class="example">-</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">objectFirstSeen</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The first time the object was seen</td>
      <td class="example">
        <ul>
          <li>1656458063638</li>
          <li>1656260547165</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The object hash ID</td>
      <td class="example">
        <ul>
          <li>8576474808125313522</li>
          <li>-599270888483415002</li>
          <li>2177864258235728980</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectHostName</td>
      <td class="type">string</td>
      <td class="general-field">DomainName</td>
      <td class="description">Server name where Internet event was detected</td>
      <td class="example">
        <ul>
          <li>10.10.10.10</li>
          <li>sample.test.org</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The UUID of the object</td>
      <td class="example">
        <ul>
          <li>3</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectIntegrityLevel</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">Integrity level of target process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectIp</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">IP address of internet event</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectIps</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">IP address list of internet event</td>
      <td class="example">
        <ul>
          <li>::1</li>
          <li>10.10.10.10</li>
          <li>::ffff:10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLastSeen</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The last time the object was seen</td>
      <td class="example">
        <ul>
          <li>1656458354730</li>
          <li>1656260580722</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLaunchTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object launch time of the Windows event</td>
      <td class="example">
        <ul>
          <li>1616412892557</li>
          <li>1620778597056</li>
          <li>1616414113105</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutFailureMessage</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in/sign-out error message</td>
      <td class="example">Login incorrect</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutFirstSeen</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The first time the object sign-in/sign-out was seen</td>
      <td class="example">1713903612</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The FNV of the object sign-in/sign-out meta</td>
      <td class="example">-8981232070268295229</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutLastSeen</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The last time the object sign-in/sign-out was seen</td>
      <td class="example">1713903612</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutMetaType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in/sign-out meta</td>
      <td class="example">1 - LOGIN_OUT_META_TYPE_OPENSSH</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutSessionId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in/sign-out session ID</td>
      <td class="example">260</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutSourceAddress</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in/sign-out source IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectLoginOutStatus</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in/sign-out status</td>
      <td class="example">-1</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The base name of the object file or process</td>
      <td class="example">net.exe</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object name</td>
      <td class="example">
        <ul>
          <li>/usr/bin/bash</li>
          <li>/bin/bash</li>
          <li>/opt/folder1/probes/system/processes/processes</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectPid</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The object process PID</td>
      <td class="example">
        <ul>
          <li>17000</li>
          <li>22000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectPid</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The PID of target process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectPort</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The port number used by internet event</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectProcessHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">FNV of target process</td>
      <td class="example">
        <ul>
          <li>1415699552492662761</li>
          <li>-100650285065767982</li>
          <li>-1139416698673814436</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRawDataSize</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The raw data size of the Windows event object</td>
      <td class="example">
        <ul>
          <li>9</li>
          <li>1</li>
          <li>564</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRawDataStr</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The data contents of the AMSI event</td>
      <td class="example">
        <ul>
          <li>$global:?</li>
          <li>0</li>
          <li>$servicename = &quot;WinRM&quot;
$arrService = Get-Service $servicename

if ($arrService.Status -ne &quot;Running&quot;)

{

	Restart-Service $servicename


}
</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryData</td>
      <td class="type">string</td>
      <td class="general-field">RegistryValueData</td>
      <td class="description">The registry data contents</td>
      <td class="example">C:\Program Files\AlertMedia\AlertMedia Desktop Notifications\AlertMedia.exe</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryData</td>
      <td class="type">string</td>
      <td class="general-field">RegistryValueData</td>
      <td class="description">The registry value data</td>
      <td class="example">
        <ul>
          <li>{11111111-1111-1111-1111-111111111111}</li>
          <li>1</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryKeyHandle</td>
      <td class="type">string</td>
      <td class="general-field">RegistryKey</td>
      <td class="description">The registry key path</td>
      <td class="example">
        <ul>
          <li>HKCR\CID\{00000000-0000-0000-0000-000000000001}</li>
          <li>HKLM\SOFTWARE\WOW6432Node\Eos</li>
          <li>HKCU\SOFTWARE\Cerner\InstantAccess</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryKeyHandle</td>
      <td class="type">string</td>
      <td class="general-field">RegistryKey</td>
      <td class="description">The registry key</td>
      <td class="example">
        <ul>
          <li>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters</li>
          <li>HKLM\system\currentcontrolset\services\w32time\config</li>
          <li>HKLM\system\currentcontrolset\services\tcpip\parameters</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryRoot</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The Windows Registry Root ID</td>
      <td class="example">
        <ul>
          <li>3</li>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryValue</td>
      <td class="type">string</td>
      <td class="general-field">RegistryValue</td>
      <td class="description">The registry value name</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>key</li>
          <li>reg</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryValue</td>
      <td class="type">string</td>
      <td class="general-field">RegistryValue</td>
      <td class="description">Registry value name</td>
      <td class="example">
        <ul>
          <li>lastknowngoodtime</li>
          <li>threadingmodel</li>
          <li>epoch</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The Windows Registry Type ID</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>11</li>
          <li>4</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRunAsLocalAccount</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">The &quot;runas&quot; command uses a local account</td>
      <td class="example">
        <ul>
          <li>1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSessionId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object session ID</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSigner</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signers</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows</li>
          <li>Microsoft Windows Publisher</li>
          <li>SecureWorks Inc</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSigner</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">Certificate signer of object process or file</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows</li>
          <li>Software Signing;Apple Code Signing Certification Authority;Apple Root CA;</li>
          <li>Microsoft Corporation</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process or file signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process or file signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process or file signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">Validity of certificate signer</td>
      <td class="example">
        <ul>
          <li>1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSubTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">File object&#x27;s true sub-type</td>
      <td class="example">
        <ul>
          <li>5000</li>
          <li>18000</li>
          <li>28001</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectThreadId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object process thread ID</td>
      <td class="example">
        <ul>
          <li>10196</li>
          <li>10104</li>
          <li>10004</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">objectTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">File object&#x27;s true major type</td>
      <td class="example">
        <ul>
          <li>7</li>
          <li>5</li>
          <li>18</li>
          <li>4051</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object type</td>
      <td class="example">
        <ul>
          <li>file</li>
          <li>process</li>
          <li>qil</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Email Security</li>
          <li>Endpoint Sensor</li>
          <li>File Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectUser</td>
      <td class="type">string</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The owner name of the target process or the login user name</td>
      <td class="example">
        <ul>
          <li>Système</li>
          <li>SYSTEM</li>
          <li>SISTEMA</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectUser</td>
      <td class="type">string</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The owner name of the target process or the login user name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>SYSTEM</li>
          <li>oracle</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectUserDomain</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The owner domain of the target process</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>UNEB</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectUserDomain</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The object user domain</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>AUTORIDADE NT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectUserGroup</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The user group name</td>
      <td class="example">
        <ul>
          <li>staff</li>
          <li>_spotlight</li>
          <li>wheel</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">online</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The flag to identify whether the endpoint is online</td>
      <td class="example">
        <ul>
          <li>Yes</li>
          <li>No</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">operationLevel</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The level that is used to indicate the handler layer at SOC</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>3</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">originalFileHashes</td>
      <td class="type">dynamic</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The hashes of the original file</td>
      <td class="example">
        <ul>
          <li>ba4700bfd55741c657a99fbe416787835fb384da</li>
          <li>639dfe4a69c1e6aace1e4eece3b3bb25af6a1392</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">originalFilePaths</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The paths of the original file</td>
      <td class="example">C:\\Users\\user_name\\Downloads\\run.exe</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osDescription</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The OS version</td>
      <td class="example">
        <ul>
          <li>Windows 10 (64 bit)</li>
          <li>Windows 10 Pro (64 bit) build 19044</li>
          <li>Amazon Linux 2 (64 bit) (5.4.188-104.359.amzn2.x86_64)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The host operating system name</td>
      <td class="example">
        <ul>
          <li>Windows</li>
          <li>Linux</li>
          <li>macOS</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The host operating system type</td>
      <td class="example">
        <ul>
          <li>0x00000030</li>
          <li>4</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osVer</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The version of the host operating system</td>
      <td class="example">
        <ul>
          <li>Amazon Linux 2</li>
          <li>10.0.19044</li>
          <li>10.0.19042</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentAuthId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The parent authorization ID</td>
      <td class="example">
        <ul>
          <li>999</li>
          <li>996</li>
          <li>997</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentCmd</td>
      <td class="type">string</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The command line entry of the parent process</td>
      <td class="example">
        <ul>
          <li>C:\WINDOWS\system32\services.exe</li>
          <li>C:\Windows\system32\services.exe</li>
          <li>/sbin/launchd</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileCreation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the parent file was created</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1635172968000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileCurrentOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current owner name of the parent file</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY\SYSTEM</li>
          <li>BUILTIN\Administradores</li>
          <li>BUILTIN\Administrators</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileCurrentOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current security identifier owner of the parent file</td>
      <td class="example">
        <ul>
          <li>S-1-5-32-544</li>
          <li>S-1-5-18</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileDaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The discretionary access control list of the parent file</td>
      <td class="example">
        <ul>
          <li>D:(A;;FA;;;S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464)(A;;0x1200a9;;;BA)(A;;0x1200a9;;;SY)(A;;0x1200a9;;;BU)(A;;0x1200a9;;;AC)(A;;0x1200a9;;;S-1-15-2-2)</li>
          <li>D:(A;OICI;GA;;;SY)(A;OICI;0xa0120000;;;WD)(A;OICI;GA;;;BA)</li>
          <li>D:(A;ID;0x1200a9;;;AC)(A;ID;FA;;;SY)(A;ID;FA;;;BA)(A;ID;0x1200a9;;;BU)(A;ID;0x1200a9;;;S-1-15-2-2)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileGroupName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the parent file user group</td>
      <td class="example">
        <ul>
          <li>wheel</li>
          <li>admin</li>
          <li>staff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileGroupSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the parent process file group</td>
      <td class="example">
        <ul>
          <li>S-1-5-18</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-32-544</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The parent file hash ID</td>
      <td class="example">
        <ul>
          <li>-4092577940452904134</li>
          <li>2141057820373638746</li>
          <li>-821808160829839906</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileHashMd5</td>
      <td class="type">string</td>
      <td class="general-field">FileMD5</td>
      <td class="description">The md5 hash of parent process</td>
      <td class="example">
        <ul>
          <li>d8e577bf078c45954f4531885478d5a9</li>
          <li>cd10cb894be2128fca0bf0e2b0c27c16</li>
          <li>cfd65bed18a1fae631091c3a4c4dd533</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileHashSha1</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA1 hash of parent process</td>
      <td class="example">
        <ul>
          <li>d7a213f3cfee2a8a191769eb33847953be51de54</li>
          <li>1f912d4bec338ef10b7c9f19976286f8acc4eb97</li>
          <li>9ad737cbd8bbdddc96726156dbd3bc03936bf02f</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA256 hash of parent process</td>
      <td class="example">
        <ul>
          <li>dfbea9e8c316d9bc118b454b0c722cd674c30d0a256340200e2c3a7480cba674</li>
          <li>f3feb95e7bcfb0766a694d93fca29eda7e2ca977c2395b4be75242814eb6d881</li>
          <li>00f8cbc5b3a6640af5ac18d01bc5a666f6f583b1379b9491e0bcc28ba78c92e9</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileModifiedTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the parent file was modified</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1635172968000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileOriginalName</td>
      <td class="type">string</td>
      <td class="general-field">FileName</td>
      <td class="description">The original file name of the parent image</td>
      <td class="example">
        <ul>
          <li>Taskmgr.exe</li>
          <li>WINLOGON.EXE</li>
          <li>svchost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The owner name of the parent file</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>cit</li>
          <li>BUILTIN\Administrators</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the parent file owner</td>
      <td class="example">
        <ul>
          <li>S-1-5-32-544</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-18</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFilePath</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The file path of the parent process</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\services.exe</li>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileRemoteAccess</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">The remote access to the parent file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileSaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The system access control list of the parent file</td>
      <td class="example">
        <ul>
          <li>S:(AU;SAFA;DCLCRPCRSDWDWO;;;WD)</li>
          <li>S:NO_ACCESS_CONTROL</li>
          <li>S:(AU;IDSAFA;DCLCRPSDWDWO;;;AU)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentFileSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the parent file</td>
      <td class="example">
        <ul>
          <li>714856</li>
          <li>59952</li>
          <li>5114880</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The parent hash ID</td>
      <td class="example">
        <ul>
          <li>-865367326691173681</li>
          <li>-2903238741593506113</li>
          <li>-4358168316031740439</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentIntegrityLevel</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The integrity level of a parent</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentLaunchTime</td>
      <td class="type">real</td>
      <td class="general-field">-</td>
      <td class="description">The time when the parent process was launched</td>
      <td class="example">
        <ul>
          <li>1653614773895</li>
          <li>1656118625928</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The image name of the parent process</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\services.exe</li>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentPid</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The PID of the parent process</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>976</li>
          <li>920</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSessionId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The parent session ID</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSigner</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The signer of the parent file</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows Publisher</li>
          <li>Microsoft Windows</li>
          <li>Software Signing;Apple Code Signing Certification Authority;Apple Root CA;</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The validity of the parent signer</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSubTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The true file subtype of the parent file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The true file type of the parent file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentUser</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The type of user that executed the parent process</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>SYSTEM</li>
          <li>SISTEMA</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentUserDomain</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The user domain of the parent process</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>AUTORIDADE NT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">patType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The pattern type</td>
      <td class="example">
        <ul>
          <li>NCIE CNC Pattern</li>
          <li>NCIE RR Pattern</li>
          <li>NCIE User Define Block List</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">patVer</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The version of the behavior pattern</td>
      <td class="example">
        <ul>
          <li>35.1053.00</li>
          <li>630</li>
          <li>35.1071.00</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Cloud App Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pComp</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The component that made the detection</td>
      <td class="example">
        <ul>
          <li>CAV</li>
          <li>NCIE</li>
          <li>TMUFE</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">peerIp</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The IP of peerHost</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">plang</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The product language</td>
      <td class="example">
        <ul>
          <li>1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">platformAssetTags</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of platform custom asset tags</td>
      <td class="example">{&quot;Asset group&quot;:[&quot;finance&quot;], &quot;some.ip&quot;: [&quot;10.1.0.1&quot;]}</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">platformAssetTags</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of platform custom asset tags</td>
      <td class="example">{&quot;Asset group&quot;:[&quot;finance&quot;], &quot;some.ip&quot;: [&quot;10.1.0.1&quot;]}</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The internal product ID</td>
      <td class="example">
        <ul>
          <li>Trend Micro Deep Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Apex One</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Trend Vision One Container Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Internal product ID (Deprecated, use productCode)</td>
      <td class="example">
        <ul>
          <li>2200</li>
          <li>751</li>
          <li>533</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The policy ID of which the event was detected</td>
      <td class="example">
        <ul>
          <li>00000001-0001-0001-0001-000000007610</li>
          <li>007</li>
          <li>003</li>
          <li>TM000001</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the triggered policy</td>
      <td class="example">
        <ul>
          <li>Steelcase</li>
          <li>Cabot</li>
          <li>Tigre - Medium Policy</li>
          <li>apiPostedPolicy</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Micro Email Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyTemplate</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The one-to-many data structure</td>
      <td class="example">
        <ul>
          <li>policyName:Monitoreo All Files, template:Managed - All files</li>
          <li>policyName:HSS DLP, template:All File Extension</li>
          <li>India: Mobile Numbers</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pplat</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The product platform</td>
      <td class="example">
        <ul>
          <li>5889</li>
          <li>9217</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processArtifactIds</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The artifact IDs generated by processAction</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000_1.dmp</li>
          <li>11111111-1111-1111-1111-111111111111_2.bak</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processCmd</td>
      <td class="type">string</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The subject process command line</td>
      <td class="example">
        <ul>
          <li>&quot;C:\Program Files (x86)\AADM\AADM.exe&quot; </li>
          <li>/usr/lib/inet/sendmail -bl -q15m</li>
          <li>ComDir</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processCmd</td>
      <td class="type">string</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The command line entry of the subject process</td>
      <td class="example">
        <ul>
          <li>C:\Windows\system32\lsass.exe</li>
          <li>C:\WINDOWS\system32\lsass.exe</li>
          <li>nimbus(processes)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileCreation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the process file was created</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1635172906000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileCurrentOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current owner name of the process file</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY\SYSTEM</li>
          <li>BUILTIN\Administrators</li>
          <li>BUILTIN\Administradores</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileCurrentOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The owner of the process file current security identifier</td>
      <td class="example">
        <ul>
          <li>S-1-5-18</li>
          <li>S-1-5-32-544</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileDaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The discretionary access control list of the process file</td>
      <td class="example">
        <ul>
          <li>D:(A;ID;0x1200a9;;;AC)(A;ID;FA;;;SY)(A;ID;FA;;;BA)(A;ID;0x1200a9;;;BU)(A;ID;0x1200a9;;;S-1-15-2-2)</li>
          <li>D:(A;ID;FA;;;SY)</li>
          <li>D:(A;ID;FA;;;BA)(A;ID;FA;;;SY)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileGroupName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the process file user group</td>
      <td class="example">
        <ul>
          <li>wheel</li>
          <li>admin</li>
          <li>staff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileGroupSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the process file group</td>
      <td class="example">
        <ul>
          <li>S-1-5-18</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-32-544</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The file hash of the process</td>
      <td class="example">
        <ul>
          <li>2141057820373638746</li>
          <li>-821808160829839906</li>
          <li>5222963427542927736</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashMd5</td>
      <td class="type">string</td>
      <td class="general-field">FileMD5</td>
      <td class="description">The MD5 hash of the subject process image</td>
      <td class="example">
        <ul>
          <li>cd10cb894be2128fca0bf0e2b0c27c16</li>
          <li>7ac47235c7bb452a03d3afd872f44c9e</li>
          <li>cfd65bed18a1fae631091c3a4c4dd533</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashSha1</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the subject process</td>
      <td class="example">
        <ul>
          <li>C0885381EBAC94AB20E78936434FA208F6B65352</li>
          <li>ac373ed32b491da22924e2e11e36574e5d582a35</li>
          <li>DF93F7DF887E86C3B56539B5046B286001C6F150</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashSha1</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA1 hash of subject process image</td>
      <td class="example">
        <ul>
          <li>1f912d4bec338ef10b7c9f19976286f8acc4eb97</li>
          <li>ded3833f145989fd86c1f4811b61497298ebc7fd</li>
          <li>9ad737cbd8bbdddc96726156dbd3bc03936bf02f</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA256 hash of subject process image</td>
      <td class="example">
        <ul>
          <li>f3feb95e7bcfb0766a694d93fca29eda7e2ca977c2395b4be75242814eb6d881</li>
          <li>39109eef00821658893b45634fe2f4664f880da9242712df907f1327d4ceefb8</li>
          <li>00f8cbc5b3a6640af5ac18d01bc5a666f6f583b1379b9491e0bcc28ba78c92e9</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileModifiedTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the process file was modified</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1633413236462</li>
          <li>1414554708877</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileOriginalName</td>
      <td class="type">string</td>
      <td class="general-field">FileName</td>
      <td class="description">The original file name of the process image</td>
      <td class="example">
        <ul>
          <li>Taskmgr.exe</li>
          <li>WINLOGON.EXE</li>
          <li>svchost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The process file owner name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>cit</li>
          <li>BUILTIN\Administrators</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the process file owner</td>
      <td class="example">
        <ul>
          <li>S-1-5-32-544</li>
          <li>S-1-5-18</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFilePath</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>ProcessFullPath</li>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The file path of the subject process</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\svchost.exe</li>
          <li>c:\windows\system32\windowspowershell\v1.0\powershell.exe</li>
          <li>c:\windows\syswow64\srts\wmipr.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFilePath</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>ProcessFullPath</li>
          <li>ProcessName</li>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The file path of the subject process</td>
      <td class="example">
        <ul>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
          <li>c:\windows\system32\lsass.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileRemoteAccess</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">The remote access to the process file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileSaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The system access control list of the process file</td>
      <td class="example">
        <ul>
          <li>S:(AU;SAFA;DCLCRPCRSDWDWO;;;WD)</li>
          <li>S:(AU;IDSAFA;DCLCRPSDWDWO;;;AU)</li>
          <li>S:NO_ACCESS_CONTROL</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the process file</td>
      <td class="example">
        <ul>
          <li>59952</li>
          <li>59456</li>
          <li>47024</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The FNV of subject process</td>
      <td class="example">
        <ul>
          <li>7114696589795796819</li>
          <li>1307755369266815004</li>
          <li>-5015325378148567246</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processImageFileNames</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The process image file names of detected backup artifacts</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\aaa\bbb\objprocess.exe</li>
          <li>C:\Program Files\ccc\ddd\sample.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processLaunchTime</td>
      <td class="type">real</td>
      <td class="general-field">-</td>
      <td class="description">The time the subject process was launched</td>
      <td class="example">
        <ul>
          <li>1653614775212</li>
          <li>1656118626642</li>
          <li>1652098160298</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processName</td>
      <td class="type">string</td>
      <td class="general-field">ProcessName</td>
      <td class="description">The image name of the process that triggered the event</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\svchost.exe</li>
          <li>/usr/bin/python2.7</li>
          <li>/usr/bin/sed</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Vision One Container Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processName</td>
      <td class="type">string</td>
      <td class="general-field">ProcessName</td>
      <td class="description">The image name of the process that triggered the event</td>
      <td class="example">
        <ul>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
          <li>c:\windows\system32\lsass.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processPid</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The PID of the subject process</td>
      <td class="example">
        <ul>
          <li>4</li>
          <li>1</li>
          <li>784</li>
          <li>792</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSigner</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The process file signer</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows</li>
          <li>Microsoft Windows Publisher</li>
          <li>Microsoft Corporation</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The validity of the process signer</td>
      <td class="example">
        <ul>
          <li>1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSubTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The true file subtype of the process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The true file type of the process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processUser</td>
      <td class="type">string</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user name of the process or the file creator</td>
      <td class="example">
        <ul>
          <li>SYSTEM</li>
          <li>SVC_JENKINS_CODE_DEV</li>
          <li>NETWORK SERVICE</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processUser</td>
      <td class="type">string</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The owner name of subject process image</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>SYSTEM</li>
          <li>SISTEMA</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processUserDomain</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The process user domain</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>AUTORIDADE NT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">proto</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The protocol type</td>
      <td class="example">
        <ul>
          <li>TELEMETRY_CONNECTION_TCP</li>
          <li>TELEMETRY_CONNECTION_UDP</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">providerGUID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The GUID of the Windows event provider</td>
      <td class="example">{11111111-1111-1111-1111-111111111111}</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">providerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the Windows event provider</td>
      <td class="example">
        <ul>
          <li>Microsoft-Windows-Security-Auditing</li>
          <li>Microsoft-Windows-WMI-Activity</li>
          <li>Microsoft-Windows-TaskScheduler</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">proxy</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The proxy address</td>
      <td class="example">
        <ul>
          <li>proxy.sample:8080</li>
          <li>10.10.10.10:8080</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pver</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The product version</td>
      <td class="example">
        <ul>
          <li>20.0.0.4726</li>
          <li>20.0.0.4416</li>
          <li>6.2.1125</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Trend Vision One Container Security</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pver</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The product version</td>
      <td class="example">
        <ul>
          <li>1.2.0.2752</li>
          <li>1.0.345</li>
          <li>1.2.0.2657</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineFileId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The unique identifier of the quarantined object</td>
      <td class="example">ASLUMVS0.4FC</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineFilePath</td>
      <td class="type">string</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The file path of the quarantined object</td>
      <td class="example">C:\ProgramData\Trend Micro\AMSP\quarantine\ASLUMVS0.4FC</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineFileSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the quarantined object</td>
      <td class="example">84B2FA19B05EA88D6E785B4ADB528120485AA3F72F3E5E114DE6D3696B0D151F</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The descriptive name for the quarantine area</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1</li>
          <li>538</li>
        </ul>
      </td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">rating</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The credibility level</td>
      <td class="example">
        <ul>
          <li>Safe</li>
          <li>Unknown</li>
          <li>Dangerous</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rawDataSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The size of the Windows event log</td>
      <td class="example">
        <ul>
          <li>1128</li>
          <li>1129</li>
          <li>1127</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rawDataStr</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Windows event raw contents</td>
      <td class="example">
        <ul>
          <li>{
   &quot;EventData&quot; : {
      &quot;LogonType&quot; : &quot;&quot;,
      &quot;TargetDomainName&quot; : &quot;&quot;,
      &quot;TargetLogonId&quot; : &quot;&quot;,
      &quot;TargetUserName&quot; : &quot;&quot;,
      &quot;TargetUserSid&quot; : &quot;&quot;
   }
}
</li>
          <li>{
   &quot;EventData&quot; : {
      &quot;LogonType&quot; : &quot;10&quot;,
      &quot;TargetDomainName&quot; : &quot;AFASADV&quot;,
      &quot;TargetLogonId&quot; : &quot;14941011731&quot;,
      &quot;TargetUserName&quot; : &quot;administrator&quot;,
      &quot;TargetUserSid&quot; : &quot;S-1-5-21-1507008304-2416677881-2121376573-500&quot;
   }
}
</li>
          <li>{
   &quot;EventData&quot; : {
      &quot;LogonType&quot; : &quot;10&quot;,
      &quot;TargetDomainName&quot; : &quot;AIS&quot;,
      &quot;TargetLogonId&quot; : &quot;216921070&quot;,
      &quot;TargetUserName&quot; : &quot;MWoodr01&quot;,
      &quot;TargetUserSid&quot; : &quot;S-1-5-21-1873864278-1756520048-3043165120-15057&quot;
   }
}
</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">remarks</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The additional information</td>
      <td class="example">
        <ul>
          <li>warning: fork: Resource temporarily unavailable</li>
          <li>pam_unix(cron:session): session opened for user root by (uid=0)</li>
          <li>WinEvtLog: Application: AUDIT_FAILURE(18470): MSSQL$SA: (no user): no domain: EXAMPLE.com: Login failed for user &#x27;example_user&#x27;. Reason: The account is disabled. [CLIENT: 10.10.10.10]  </li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>TXOne EdgeOne</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">request</td>
      <td class="type">string</td>
      <td class="general-field">URL</td>
      <td class="description">The notable URLs</td>
      <td class="example">
        <ul>
          <li>http://example.page.com/canonical.html</li>
          <li>http://10.10.10.10</li>
          <li>https://drive.google.com/</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">request</td>
      <td class="type">string</td>
      <td class="general-field">URL</td>
      <td class="description">Request URL</td>
      <td class="example">
        <ul>
          <li>http://10.10.10.10/fake/site</li>
          <li>http:///fake/param.cgi?action=list&amp;group=Alarm.Status</li>
          <li>http://fake.com/</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestClientApplication</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The protocol user agent information</td>
      <td class="example">
        <ul>
          <li>Microsoft-Delivery-Optimization/10.0</li>
          <li>Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 5.1; Trident/4.0)</li>
          <li>example Software GmbH</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestMethod</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The network protocol request method</td>
      <td class="example">
        <ul>
          <li>GET</li>
          <li>POST</li>
          <li>PUT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">riskConfidenceLevel</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The risk confidence level</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">riskLevel</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The risk level</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>high</li>
          <li>No Risk</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rt</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Unix time of the log generation</td>
      <td class="example">1656324260000</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rt</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The event time</td>
      <td class="example">1657781088000</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rtDate</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The date of the log generation</td>
      <td class="example">1655337600000</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rtHour</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The hour of the log generation</td>
      <td class="example">
        <ul>
          <li>9</li>
          <li>8</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">rtWeekDay</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The weekday of the log generation</td>
      <td class="example">
        <ul>
          <li>Monday</li>
          <li>Tuesday</li>
          <li>Friday</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID</td>
      <td class="example">
        <ul>
          <li>1002795</li>
          <li>1003802</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID</td>
      <td class="example">1005566</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the rule that triggered the event</td>
      <td class="example">
        <ul>
          <li>Directory Server - Microsoft Windows Active Directory</li>
          <li>Microsoft Windows Events</li>
          <li>Microsoft Windows Security Events - 3</li>
          <li>(T1234) New executable created (chmod)</li>
          <li>Sensitive Files Upload to Personal Cloud</li>
          <li>Multiple Sensitive Files Compression</li>
          <li>Transfer Sensitive Files to Removable Storage</li>
          <li>Move Multiple Sensitive Files to Central Location</li>
          <li>Multiple Sensitive Files Modification</li>
          <li>Multiple Sensitive Files Deletion</li>
          <li>GEN_CCFR_OVERLAY_TEST.A</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
          <li>Email Sensor</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The access rule type</td>
      <td class="example">
        <ul>
          <li>udso</li>
          <li>point of entry</li>
          <li>unknown</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">scanType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The scan type</td>
      <td class="example">
        <ul>
          <li>realtime_mailmeta-exchange</li>
          <li>exchange_mailbox_realtime_detection_logs</li>
          <li>gateway_realtime_blocking_traffic</li>
          <li>malware_schedule_image</li>
          <li>malware_schedule_file</li>
          <li>malware_realtime_image</li>
          <li>malware_realtime_file</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">score</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The Web Reputation Services URL rating</td>
      <td class="example">
        <ul>
          <li>71</li>
          <li>81</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Mobile Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">secondAct</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The second scan action</td>
      <td class="example">
        <ul>
          <li>Unknown</li>
          <li>N/A</li>
          <li>Deny Access</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">secondActResult</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The result of the second scan action</td>
      <td class="example">
        <ul>
          <li>Unknown</li>
          <li>N/A</li>
          <li>Access denied</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">senderGUID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sender GUID</td>
      <td class="example">
        <ul>
          <li>346648FC-9862-D2F0-F94C-FAB1A838ABD7</li>
          <li>36E5239E-EEBA-0100-C10E-C057E0455E1D</li>
          <li>9606BBD5-38A7-9024-83C8-9C88A2AF90CC</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">senderIp</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The sender IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Email Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">sessionId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The session ID</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">severity</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The severity of the event</td>
      <td class="example">
        <ul>
          <li>2</li>
          <li>4</li>
          <li>6</li>
          <li>8</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">signer</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The signer of the file</td>
      <td class="example">Shenzhen Smartspace Software technology Co.,Limited;Symantec Class 3 SHA256 Code Signing CA;1429491600;1492649999</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">smac</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The source MAC address</td>
      <td class="example">
        <ul>
          <li>00:11:22:33:44:55</li>
          <li>66:77:88:99:AA:BB</li>
          <li>CC:DD:EE:FF:00:11</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">sourceType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The source type</td>
      <td class="example">
        <ul>
          <li>user defined</li>
          <li>sandbox</li>
          <li>syscall</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Vision One Container Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">spt</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The source port</td>
      <td class="example">
        <ul>
          <li>53</li>
          <li>7680</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Endpoint Sensor</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">spt</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The source port number</td>
      <td class="example">
        <ul>
          <li>53</li>
          <li>5353</li>
          <li>443</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">src</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The source IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">src</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The source address</td>
      <td class="example">
        <ul>
          <li>::</li>
          <li>10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileCreation</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the source file was created</td>
      <td class="example">
        <ul>
          <li>1577865600000</li>
          <li>1626201752000</li>
          <li>1626201750000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileCurrentOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current owner name of the source file</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY\SYSTEM</li>
          <li>BUILTIN\Administrators</li>
          <li>AUTORIDADE NT\SISTEMA</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileCurrentOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The current security identifier owner of the source file</td>
      <td class="example">
        <ul>
          <li>S-1-5-18</li>
          <li>S-1-5-32-544</li>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileDaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The discretionary access control list of the source file</td>
      <td class="example">
        <ul>
          <li>D:(A;;FA;;;S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464)(A;;0x1200a9;;;BA)(A;;0x1200a9;;;SY)(A;;0x1200a9;;;BU)(A;;0x1200a9;;;AC)(A;;0x1200a9;;;S-1-15-2-2)</li>
          <li>D:(A;ID;FA;;;SY)(A;ID;FA;;;BA)(A;ID;0x1200a9;;;BU)(A;ID;0x1200a9;;;AC)(A;ID;0x1200a9;;;S-1-15-2-2)</li>
          <li>D:(A;ID;FA;;;SY)(A;ID;FA;;;BA)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileGroupName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The source file user group name</td>
      <td class="example">
        <ul>
          <li>wheel</li>
          <li>staff</li>
          <li>NT SERVICE\TrustedInstaller</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileGroupSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the source file group</td>
      <td class="example">
        <ul>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-18</li>
          <li>S-1-5-21-3770350686-3666354711-3866293128-513</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The source file hash ID</td>
      <td class="example">
        <ul>
          <li>1102079405020678318</li>
          <li>-6926286289273504319</li>
          <li>8528955148329941480</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashMd5</td>
      <td class="type">string</td>
      <td class="general-field">FileMD5</td>
      <td class="description">The md5 hash of source file</td>
      <td class="example">
        <ul>
          <li>e5d5e9c1f65b8ec7aa5b7f1b1acdd731</li>
          <li>a6779bf446db07e4c4ba3516b273c496</li>
          <li>4bb7334fdadc6eccb8e6ab402aae013b</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashSha1</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA1 hash of source file</td>
      <td class="example">
        <ul>
          <li>5d34902fecc1760138212ada36be1e742bda5e52</li>
          <li>dbb14dcda6502ab1d23a7c77d405dafbcbeb439e</li>
          <li>2292f8109cd756e790c068a52d50f1b0858f503b</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA256 hash of source file</td>
      <td class="example">
        <ul>
          <li>4eaa002225f4ea2dedcd19b7f1337d7c58ea7dd6d4571c12468dde95e6bcfdaf</li>
          <li>e30508e2088bc16b2a84233ced64995f738deaef2366ac6c86b35c93bbcd9d80</li>
          <li>16b20a3ad485b4fbbe3028c7e743b226db21ea93cacc8b3d7d7d4a731bf02333</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileIsRemoteAccess</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">The remote access of the source file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileModifiedTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the source file was modified</td>
      <td class="example">
        <ul>
          <li>1626201752000</li>
          <li>1626201750000</li>
          <li>1577865600000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileOwnerName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The source file owner name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>NT SERVICE\TrustedInstaller</li>
          <li>NT AUTHORITY\SYSTEM</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileOwnerSid</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier of the source file owner</td>
      <td class="example">
        <ul>
          <li>S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464</li>
          <li>S-1-5-18</li>
          <li>S-1-5-32-544</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFilePath</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The source file path</td>
      <td class="example">
        <ul>
          <li>\\cnva-apps\megaclockprod\traveler\travelerprint.accdb</li>
          <li>c:\program files\common files\microsoft shared\clicktorun\officesvcmgrschedule.xml</li>
          <li>q:\a7_dbs\a4_pkg\a4_packaging.accde</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileSaclString</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The system access control list of the source file</td>
      <td class="example">
        <ul>
          <li>S:NO_ACCESS_CONTROL</li>
          <li>S:(AU;SAFA;DCLCRPCRSDWDWO;;;WD)</li>
          <li>S:(AU;IDSAFA;DCLCRPSDWDWO;;;AU)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the source file</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>131072</li>
          <li>196608</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFirstSeen</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The first time the source file was seen</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1656355418449</li>
          <li>1656714760440</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcHashId</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The source hash ID</td>
      <td class="example">
        <ul>
          <li>4070054759888344851</li>
          <li>2177864258235728980</li>
          <li>3476454206648023552</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcLastSeen</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The last time the source file was seen</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1656355418449</li>
          <li>1656715147313</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcSigner</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The signer of the source file</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows</li>
          <li>Microsoft Corporation</li>
          <li>Google LLC</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of source file signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of source file signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of source file signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcSignerValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The validity of the source file signer</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcSubTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The true file subtype of the source file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcTrueType</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The true file type of the source file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">status</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The HTTP response status code</td>
      <td class="example">
        <ul>
          <li>200</li>
          <li>500</li>
          <li>403</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">subSystem</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sub system information</td>
      <td class="example">com.apple.xpc</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">suid</td>
      <td class="type">string</td>
      <td class="general-field">UserAccount</td>
      <td class="description">User name or mailbox</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>US EXAMPLE\TEST</li>
          <li>sample_email@trendmicro.com</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">suser</td>
      <td class="type">dynamic</td>
      <td class="general-field">EmailSender</td>
      <td class="description">The email sender</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">tacticId</td>
      <td class="type">dynamic</td>
      <td class="general-field">Tactic</td>
      <td class="description">The list of MITRE tactic IDs</td>
      <td class="example">
        <ul>
          <li>TA0011</li>
          <li>TA0008</li>
          <li>TA0001</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">tags</td>
      <td class="type">dynamic</td>
      <td class="general-field">
        <ul>
          <li>Technique</li>
          <li>Tactic</li>
        </ul>
      </td>
      <td class="description">The detected technique ID based on the alert filter</td>
      <td class="example">
        <ul>
          <li>MITREV9.T1090</li>
          <li>MITRE.T1071</li>
          <li>MITREV9.T1059.001</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">threatName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The threat name</td>
      <td class="example">
        <ul>
          <li>Malicious_CnC_access_on_UDP_blocked</li>
          <li>Malicious_CnC_access_on_TCP_blocked</li>
          <li>Other protected file</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">threatType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The log threat type</td>
      <td class="example">
        <ul>
          <li>2</li>
          <li>99</li>
          <li>5</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">timezone</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The host time zone</td>
      <td class="example">
        <ul>
          <li>UTC+00:00</li>
          <li>UTC-05:00</li>
          <li>UTC-03:00</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">trigger</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The action trigger</td>
      <td class="example">
        <ul>
          <li>ATSE</li>
          <li>On-demand scan</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">triggerInfo</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The trigger information</td>
      <td class="example">[{&#x27;triggerModule&#x27;: &#x27;ODS&#x27;, &#x27;triggerReason&#x27;: &#x27;System Schedule Scan&#x27;}]</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">triggerReason</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The cause of the triggered action</td>
      <td class="example">
        <ul>
          <li>FILEMETA.T1027.009.TRICKBOT.SMITRE1B2, T1027.009</li>
          <li>ST002</li>
          <li>Scheduled Scan (custom)</li>
          <li>Scheduled Scan (system)</li>
          <li>Remote Scan: the user triggered the Apex One agent from the Trend Vision One console</li>
          <li>Manual Scan: the user triggered the local agent</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">urlCat</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The requested URL category</td>
      <td class="example">
        <ul>
          <li>Untested</li>
          <li>158</li>
          <li>Web Advertisement</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Web Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Mobile Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDomain</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>EndpointName</li>
          <li>DomainName</li>
          <li>AccountDomain</li>
        </ul>
      </td>
      <td class="description">The user domain</td>
      <td class="example">
        <ul>
          <li>example.com.pa</li>
          <li>DOMAIN</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDomain</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The user domain name</td>
      <td class="example">
        <ul>
          <li>CORP</li>
          <li>AUTORIDADE NT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">vendor</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The device vendor</td>
      <td class="example">adata</td>
      <td class="products">Trend Micro Apex One as a Service</td>
    </tr>
    <tr>
      <td class="field-name">winEventId</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">Event ID of Windows event</td>
      <td class="example">
        <ul>
          <li>11</li>
          <li>4624</li>
          <li>4670</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 433
- **Layer:** Endpoint
- **Product:** Trend Micro Apex One as a Service

---
*Generated by XDR Common Schema Public Doc Generator V2*

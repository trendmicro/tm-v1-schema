---
layout: default
title: Trend Cloud One - Endpoint & Workload Security - Endpoint
---

# Trend Cloud One - Endpoint & Workload Security
**Layer:** Endpoint

This documentation provides detailed information about all fields available for Trend Cloud One - Endpoint & Workload Security.

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
  width: 11%;
  font-family: 'Courier New', monospace;
  font-weight: bold;
  font-size: 12px;
}

.type {
  width: 7%;
  font-family: 'Courier New', monospace;
  font-size: 11px;
}

.searchable {
  width: 8%;
  text-align: center;
  font-size: 11px;
}

.general-field {
  width: 11%;
  text-align: center;
  font-size: 11px;
}

.description {
  width: 23%;
  line-height: 1.3;
  font-size: 12px;
}

.example {
  width: 18%;
  font-family: 'Courier New', monospace;
  font-size: 10px;
  line-height: 1.2;
}

.products {
  width: 22%;
  font-size: 10px;
}

.example ul, .searchable ul, .general-field ul, .products ul {
  margin: 0;
  padding-left: 12px;
  list-style-type: disc;
}

.example li, .searchable li, .general-field li, .products li {
  margin: 1px 0;
  word-break: break-word;
}

/* Responsive design */
@media screen and (max-width: 1200px) {
  .property-table {
    font-size: 12px;
  }
  
  .field-name {
    width: 11%;
  }
  
  .type {
    width: 7%;
  }
  
  .searchable {
    width: 8%;
  }
  
  .general-field {
    width: 11%;
  }
  
  .description {
    width: 23%;
  }
  
  .example {
    width: 18%;
  }
  
  .products {
    width: 22%;
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
    width: 11%;
    font-size: 11px;
  }
  
  .type {
    width: 7%;
    font-size: 10px;
  }
  
  .searchable {
    width: 8%;
    font-size: 10px;
  }
  
  .general-field {
    width: 11%;
    font-size: 10px;
  }
  
  .description {
    width: 23%;
    font-size: 11px;
  }
  
  .example {
    width: 18%;
    font-size: 9px;
  }
  
  .products {
    width: 22%;
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
      <th class="searchable">Searchable</th>
      <th class="general-field">General Field</th>
      <th class="description">Description</th>
      <th class="example">Example</th>
      <th class="products">Products</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="field-name">act</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">actResult</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">aggregatedCount</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">behaviorCat</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">cat</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="field-name">category</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event category</td>
      <td class="example">
        <ul>
          <li>Exploits</li>
          <li>Reconnaissance</li>
          <li>Vulnerabilities</li>
          <li>Security Policy</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>TippingPoint Security Management System</li>
          <li>Mobile Network Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">censusMaturityValue</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">cloudProvider</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The service provider of the cloud asset</td>
      <td class="example">
        <ul>
          <li>alibaba cloud</li>
          <li>aws</li>
          <li>azure</li>
          <li>gcp</li>
          <li>oci</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">cloudProvider</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The service provider of the cloud asset</td>
      <td class="example">
        <ul>
          <li>aws</li>
          <li>azure</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">compressedFileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">customAssetTags</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">cves</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The CVEs associated with this filter</td>
      <td class="example">
        <ul>
          <li>CVE-2014-3567</li>
          <li>CVE-2016-6304</li>
          <li>CVE-2011-1385</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dceArtifactActions</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="field-name">detectedActions</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">detectionNames</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dmac</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">dpt</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">endpointGUID</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="field-name">endTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the last event was received (in Unix milliseconds)</td>
      <td class="example">1750983926000</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">eventHashId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="field-name">eventName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventSubId</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The access type</td>
      <td class="example">
        <ul>
          <li>4</li>
          <li>101</li>
          <li>102</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>TXOne StellarOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventSubId</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">fileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">fileOperation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The operation of the file</td>
      <td class="example">
        <ul>
          <li>Created</li>
          <li>Updated</li>
          <li>Deleted</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">filePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">filePathName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The file path with the file name</td>
      <td class="example">
        <ul>
          <li>vss</li>
          <li>spoolss</li>
          <li>/etc/hosts</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne StellarOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">firstAct</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="field-name">fullPath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">groups</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The OSSEC rule group names</td>
      <td class="example">
        <ul>
          <li>auditd,audit,</li>
          <li>dirservice_log,authentication_failure,</li>
          <li>windows,authentication_failures,</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">hostId</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The host ID</td>
      <td class="example">
        <ul>
          <li>20548</li>
          <li>967</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">hostName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>DomainName</li>
          <li>HostDomain</li>
        </ul>
      </td>
      <td class="description">The computer name of the client host (The hostname from the suspicious URL detected by Deep Discovery Inspector)</td>
      <td class="example">
        <ul>
          <li>Let&#x27;s Encrypt</li>
          <li>10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne EdgeOne</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">hostName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">instanceId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">instanceId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The virtual machine instance ID on the cloud platform</td>
      <td class="example">i-01234567890abcdef</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">interestedHost</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">isEntity</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The current entity (or after change/modification)</td>
      <td class="example">
        <ul>
          <li>{&quot;key&quot;:&quot;&lt;example&gt;&quot;,&quot;type&quot;:&quot;Service&quot;,&quot;attributes&quot;:[{&quot;friendlyValue&quot;:null,&quot;name&quot;:&quot;binaryPathName&quot;,&quot;value&quot;:&quot;C:\\Windows\\system32\\vssvc.exe&quot;},{&quot;friendlyValue&quot;:&quot;manual&quot;,&quot;name&quot;:&quot;startType&quot;,&quot;value&quot;:&quot;3&quot;},{&quot;friendlyValue&quot;:&quot;running&quot;,&quot;name&quot;:&quot;state&quot;,&quot;value&quot;:&quot;4&quot;}]}</li>
          <li>{&quot;key&quot;:&quot;&lt;example&gt;&quot;:&quot;Service&quot;,&quot;attributes&quot;:[{&quot;friendlyValue&quot;:null,&quot;name&quot;:&quot;binaryPathName&quot;,&quot;value&quot;:&quot;C:\\Windows\\system32\\vssvc.exe&quot;},{&quot;friendlyValue&quot;:&quot;manual&quot;,&quot;name&quot;:&quot;startType&quot;,&quot;value&quot;:&quot;3&quot;},{&quot;friendlyValue&quot;:&quot;stopped&quot;,&quot;name&quot;:&quot;state&quot;,&quot;value&quot;:&quot;1&quot;}]}</li>
          <li>{&quot;key&quot;:&quot;&lt;example&gt;&quot;,&quot;type&quot;:&quot;File&quot;,&quot;attributes&quot;:[]}</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">isProxy</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">majorVirusType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The virus type</td>
      <td class="example">
        <ul>
          <li>Virus</li>
          <li>Suspicious Activity</li>
          <li>Trojan</li>
          <li>TROJ</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Vision One Mobile Security</li>
          <li>TXOne EdgeOne</li>
          <li>TXOne StellarOne</li>
          <li>File Security Storage</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">malFamily</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">malType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">mDeviceGUID</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">mitreVersion</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The MITRE version</td>
      <td class="example">
        <ul>
          <li>v9</li>
          <li>v6</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">moduleScanType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectAppName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectBmData</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The data of BM event</td>
      <td class="example">
        <ul>
          <li>{&quot;provider&quot;:&quot;ORCA&quot;,&quot;schema_version&quot;:1,&quot;data&quot;:[{&quot;str&quot;:&quot;Access /proc/&lt;pid&gt;/*&quot;}]}</li>
          <li>{&quot;provider&quot;:&quot;ORCA&quot;,&quot;schema_version&quot;:1,&quot;data&quot;:[{&quot;str&quot;:&quot;source &#x27;/etc/profile.d/lang.sh&#x27;&quot;}]}</li>
          <li>{&quot;provider&quot;:&quot;ORCA&quot;,&quot;schema_version&quot;:1,&quot;data&quot;:[{&quot;str&quot;:&quot;source &#x27;/etc/profile.d/bash_completion.sh&#x27;&quot;}]}</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectCmd</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectCurrentPosixPermission</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The new POSIX permission file used in file events and CHMOD events</td>
      <td class="example">1050180</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">objectFileAccess</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectFileGroupName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">objectFileHashId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectFilePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectFileSize</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The object file size</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>59456</li>
          <li>60</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">objectFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">objectFirstSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="field-name">objectIp</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The IP address of the domain</td>
      <td class="example">10.10.10.10</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">objectIps</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectPosixPermission</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The current POSIX permission for the file</td>
      <td class="example">1050112</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">objectPosixPermissionHashId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The POSIX permission hash ID</td>
      <td class="example">-8931783023607715387</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">objectProcessHashId</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the object registry root key</td>
      <td class="example">
        <ul>
          <li>HKCR</li>
          <li>HKLM</li>
          <li>HKCU</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectRegistryRoot</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectSignerValid</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">objectTrueType</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">oldFileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the target process image or target file (wasEntity from an IM event)</td>
      <td class="example">
        <ul>
          <li>DA39A3EE5E6B4B0D3255BFEF95601890AFD80709</li>
          <li>89CE26EAD139D52B8A6B61BFFC6AF89AF246580F</li>
          <li>57247B810B0EE61DD86CE24AC14097B9B5405EEC</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">originalFileHashes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">out</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The IP datagram length (in bytes)</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>439</li>
          <li>1314</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentCmd</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">parentFileGroupName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">parentFileHashId</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">parentFilePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">parentFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">parentLaunchTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The PID of the parent process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentPid</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">parentSignerValid</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The account name of the parent process</td>
      <td class="example">Administrator</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">parentUser</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The domain name of the parent process</td>
      <td class="example">builtindomain</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">parentUserDomain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">plang</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Trend Vision One Container Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">pplat</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Unix time of object creation</td>
      <td class="example">
        <ul>
          <li>1645828113585</li>
          <li>1655412594237</li>
          <li>1647162053219</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">processFileCreation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">processFileGroupName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">processFileHashId</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">FileMD5</td>
      <td class="description">The MD5 of the subject process</td>
      <td class="example">
        <ul>
          <li>D07ADD0CE6E000D3CD20193B891E8ED3</li>
          <li>1a9ba93ebe4cb60030831f8ce9e7d5f9</li>
          <li>EEE6691B48D2FB604DDF0CBC90D75B0E</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashMd5</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the subject process</td>
      <td class="example">
        <ul>
          <li>4314A869B8DAE1BD3FFF810B1366E90FB7C961D4A3424260692377FDD87361D2</li>
          <li>7824c45fc033696603fe97d8f193a1872dfb2b5db75f0cda21df27017b3cb623</li>
          <li>1A6D5986EFEAE89308D9EE11B4A7907012603392E0E66D0E529DB09DF1B4CB64</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processFileHashSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">processFilePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">processFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">processImagePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The process triggered by the file event</td>
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
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processLaunchTime</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the subject process was launched</td>
      <td class="example">
        <ul>
          <li>1656400286556</li>
          <li>1656566610259</li>
          <li>1656587180493</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">processLaunchTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The PID of the subject process</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processPid</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The signer name list of the subject process</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows</li>
          <li>Microsoft Windows Publisher</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSigner</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="field-name">processSignerValid</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The owner domain of the subject process image</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>DOMAINBA</li>
          <li>PAEDMZ</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">processUserDomain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">processUserGroupId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The process user group ID or file creator</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>S-1-5-1</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">processUserGroupName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The process user group name or file creator</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>NT AUTHORITY</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">processUserId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The process user ID or file creator</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>S-1-5-1</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">proto</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The exploited layer network protocol</td>
      <td class="example">
        <ul>
          <li>6</li>
          <li>TCP</li>
          <li>17</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>TXOne EdgeOne</li>
          <li>Trend Vision One Container Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">proto</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="field-name">protoFlag</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The data flags</td>
      <td class="example">
        <ul>
          <li>ACK PSH DF=1</li>
          <li>ACK DF=1</li>
          <li>DF=1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pver</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">regionId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cloud asset region</td>
      <td class="example">
        <ul>
          <li>US East (N. Virginia)</li>
          <li>Europe (Frankfurt)</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">regionId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cloud asset region</td>
      <td class="example">
        <ul>
          <li>US East (N. Virginia)</li>
          <li>Europe (Frankfurt)</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">remarks</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestClientApplication</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">riskLevel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="field-name">rtDate</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">ruleName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">ruleSetName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The rule set name</td>
      <td class="example">AllRules</td>
      <td class="products">
        <ul>
          <li>Trend Vision One Container Security</li>
          <li>Trend Cloud One - Network Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleVer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The rule version</td>
      <td class="example">
        <ul>
          <li>202207060001</li>
          <li>202207190001</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">scanType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">secondAct</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">sessionId</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">shost</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">DomainName</td>
      <td class="description">The source hostname</td>
      <td class="example">
        <ul>
          <li>dns.google</li>
          <li>sw_us-east-1a_10-124-17-69</li>
          <li>sw_us-east-1c_10-124-21-139</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
          <li>Mobile Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">smac</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">sproc</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The OSSEC program name</td>
      <td class="example">
        <ul>
          <li>postfix/sendmail</li>
          <li>CRON</li>
          <li>sshd</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">spt</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">srcFileGroupName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">srcFileHashId</td>
      <td class="type">long</td>
      <td class="searchable">false</td>
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
      <td class="field-name">srcFileIsRemoteAccess</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">srcFilePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">srcFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">false</td>
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
      <td class="searchable">true</td>
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
      <td class="field-name">srcSubTrueType</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
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
      <td class="searchable">false</td>
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
      <td class="field-name">startTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the first event was received (in Unix milliseconds)</td>
      <td class="example">1750983848000</td>
      <td class="products">Trend Cloud One - Endpoint &amp; Workload Security</td>
    </tr>
    <tr>
      <td class="field-name">status</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">subRuleId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">ID of a subordinate rule</td>
      <td class="example">
        <ul>
          <li>85262</li>
          <li>914520</li>
          <li>18152</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Cloud One - Network Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">subRuleName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The subrule name</td>
      <td class="example">
        <ul>
          <li>Pre-authentication failed.</li>
          <li>ATTACK T1070.002,T1070.004: Indicator Removal on Host : Clear Linux or Mac System Logs,File Deletion </li>
          <li>ATTACK T1110: Multiple Windows Logon Failures</li>
          <li>invisible_url_domain</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">suid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">tags</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="field-name">target</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The target object for the behavior</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\windowspowershell\v1.0\powershell.exe</li>
          <li>zwwritevirtualmemory</li>
          <li>/proc/211296/exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">targetType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The target object type</td>
      <td class="example">
        <ul>
          <li>File System</li>
          <li>Uncategorized</li>
          <li>Exploit</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">timezone</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDomain</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
      <td class="field-name">vpcId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The virtual private cloud that contains the cloud asset</td>
      <td class="example">
        <ul>
          <li>vpc-01234567890abcdef</li>
          <li>avtd-vnet-ozyww04h</li>
          <li>ocid1.vnic.oc1.iad.abuwcljs4szq5rylkxikcthyegnqn5mjhkyn3xwtoa3uvbonxqn52nofibgq</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">vpcId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The virtual private cloud that contains the cloud asset</td>
      <td class="example">vpc-01234567890abcdef</td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">wasEntity</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The entity before change/modification</td>
      <td class="example">
        <ul>
          <li>{&quot;key&quot;:&quot;&lt;example&gt;&quot;,&quot;type&quot;:&quot;Service&quot;,&quot;attributes&quot;:[{&quot;friendlyValue&quot;:null,&quot;name&quot;:&quot;binaryPathName&quot;,&quot;value&quot;:&quot;C:\\Windows\\system32\\vssvc.exe&quot;},{&quot;friendlyValue&quot;:&quot;manual&quot;,&quot;name&quot;:&quot;startType&quot;,&quot;value&quot;:&quot;3&quot;},{&quot;friendlyValue&quot;:&quot;stopped&quot;,&quot;name&quot;:&quot;state&quot;,&quot;value&quot;:&quot;1&quot;}]}</li>
          <li>{&quot;key&quot;:&quot;&lt;example&gt;&quot;,&quot;type&quot;:&quot;Service&quot;,&quot;attributes&quot;:[{&quot;friendlyValue&quot;:null,&quot;name&quot;:&quot;binaryPathName&quot;,&quot;value&quot;:&quot;C:\\Windows\\system32\\vssvc.exe&quot;},{&quot;friendlyValue&quot;:&quot;manual&quot;,&quot;name&quot;:&quot;startType&quot;,&quot;value&quot;:&quot;3&quot;},{&quot;friendlyValue&quot;:&quot;running&quot;,&quot;name&quot;:&quot;state&quot;,&quot;value&quot;:&quot;4&quot;}]}</li>
          <li>{&quot;key&quot;:&quot;&lt;example&gt;&quot;,&quot;type&quot;:&quot;File&quot;,&quot;attributes&quot;:[]}</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">winEventId</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows Event ID</td>
      <td class="example">
        <ul>
          <li>11</li>
          <li>4624</li>
          <li>4670</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 299
- **Layer:** Endpoint
- **Product:** Trend Cloud One - Endpoint & Workload Security

---
*Generated by XDR Common Schema Public Doc Generator V2*

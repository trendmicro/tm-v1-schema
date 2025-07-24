---
layout: default
title: File Security Storage - Cloud
---

# File Security Storage
**Layer:** Cloud

This documentation provides detailed information about all fields available for File Security Storage.

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
      <td class="field-name">awsResourceArn</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Amazon Resource Name</td>
      <td class="example">
        <ul>
          <li>arn:aws:s3:::bucket-name/object-key</li>
          <li>arn:aws:s3:::user-bucket-name/file-name</li>
          <li>arn:aws:s3:::bucket-name/folder-name/file-name</li>
        </ul>
      </td>
      <td class="products">File Security Storage</td>
    </tr>
    <tr>
      <td class="field-name">cloudAccountId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The AWS cloud account ID, Google Cloud product ID, or Azure subscription ID</td>
      <td class="example">
        <ul>
          <li>123456789012</li>
          <li>00000000-0000-0000-0000-000000000000</li>
          <li>ocid1.compartment.oc1..aaaaaaaa54yuau7prqquu3gqs4jcjzvz2yf7vwlqnkqlixq5tcjsdezqmyua</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">cloudProvider</td>
      <td class="type">string</td>
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
      <td class="field-name">cloudStorageName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The cloud storage name</td>
      <td class="example">my-bucket</td>
      <td class="products">File Security Storage</td>
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
      <td class="field-name">compressedFileSize</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the decompressed archive file</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>265314</li>
          <li>175864</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">compressedFileType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file type of the decompressed archive file</td>
      <td class="example">
        <ul>
          <li>EXE</li>
          <li>JAVA</li>
          <li>PDF</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
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
      <td class="field-name">fileType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The file type of the suspicious file</td>
      <td class="example">
        <ul>
          <li>EXE</li>
          <li>LNK</li>
          <li>MIME</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
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
      <td class="field-name">majorVirusType</td>
      <td class="type">string</td>
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
          <li>Mobile Security</li>
          <li>TXOne EdgeOne</li>
          <li>TXOne StellarOne</li>
          <li>File Security Storage</li>
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
      <td class="field-name">regionCode</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The cloud provider region code</td>
      <td class="example">us-east-1</td>
      <td class="products">
        <ul>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 22
- **Layer:** Cloud
- **Product:** File Security Storage

---
*Generated by XDR Common Schema Public Doc Generator V2*

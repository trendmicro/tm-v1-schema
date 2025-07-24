---
layout: default
title: Data Detection and Response - Endpoint
---

# Data Detection and Response
**Layer:** Endpoint

This documentation provides detailed information about all fields available for Data Detection and Response.

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
      <td class="field-name">aggregateFunction</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The metric aggregator</td>
      <td class="example">
        <ul>
          <li>0 - sum</li>
          <li>1 - avg</li>
        </ul>
      </td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">aggregateUnit</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The metric unit</td>
      <td class="example">file</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">detectionFileList</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The information about the related files</td>
      <td class="example">{&quot;fileName&quot;: &quot;sample.txt&quot;, &quot;edgeId&quot;: &quot;00000000-0000-0000-0000-000000000000&quot;}</td>
      <td class="products">Data Detection and Response</td>
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
      <td class="field-name">duration</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The detection interval (in milliseconds)</td>
      <td class="example">300000</td>
      <td class="products">Data Detection and Response</td>
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
      <td class="field-name">firstSeen</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The first time the XDR log appeared</td>
      <td class="example">1657195233000</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>TXOne StellarOne</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">lastSeen</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The last time the XDR log appeared</td>
      <td class="example">1657195233000</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>TXOne StellarOne</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">lineageId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The lineage ID</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000</li>
          <li>11111111-1111-1111-1111-111111111111</li>
          <li>22222222-2222-2222-2222-222222222222</li>
        </ul>
      </td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">logonUsers</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The telemetry events that match the Security Analytics Engine filter, and logonUsers stores the logonUsers value of the original events</td>
      <td class="example">BHBShortJ</td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">matchedPolicies</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The matched policies of detection records</td>
      <td class="example">[&#x27;00000000-0000-0000-0000-000000000000&#x27;]</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">metaSrcExtra</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The meta for identifying the source of events</td>
      <td class="example">[{&#x27;metaSrcUri&#x27;: ...]</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">objectFileHash</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The cryptographic hash of the target process image or file, with the specific hash algorithm to be determined</td>
      <td class="example">1ca71017d2fa4775253670e1e55e26912bfdc156</td>
      <td class="products">Data Detection and Response</td>
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
      <td class="field-name">objectServiceType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Type of target file</td>
      <td class="example">
        <ul>
          <li>local</li>
          <li>smb</li>
          <li>web</li>
        </ul>
      </td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">objectUri</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Path of target file</td>
      <td class="example">C://path/of/file.txt</td>
      <td class="products">Data Detection and Response</td>
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
      <td class="field-name">osName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The host OS name</td>
      <td class="example">
        <ul>
          <li>Linux</li>
          <li>windows 10.0.22000</li>
          <li>windows 10.0.19044</li>
          <li>windows 10.0.19043</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Data Detection and Response</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osVer</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The OS version</td>
      <td class="example">11</td>
      <td class="products">
        <ul>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyIds</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Ids of DDR’s data policy</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">ruleIdStr</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID</td>
      <td class="example">0000000-0000-0000-0000-000000000000</td>
      <td class="products">Data Detection and Response</td>
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
      <td class="field-name">srcFileHash</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The cryptographic hash of the source process image or file, with the specific hash algorithm to be determined.</td>
      <td class="example">1ca71017d2fa4775253670e1e55e26912bfdc156</td>
      <td class="products">Data Detection and Response</td>
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
      <td class="field-name">srcServiceType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Type of source file</td>
      <td class="example">
        <ul>
          <li>local</li>
          <li>smb</li>
          <li>web</li>
        </ul>
      </td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">srcUri</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Path of source file</td>
      <td class="example">C://path/of/file.txt</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">srcUser</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The owner name of the source process or the login user name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>SYSTEM</li>
          <li>oracle</li>
        </ul>
      </td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">uuids</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The UUIDs of detection records</td>
      <td class="example">[&#x27;00000000-0000-0000-0000-000000000000&#x27;]</td>
      <td class="products">Data Detection and Response</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 37
- **Layer:** Endpoint
- **Product:** Data Detection and Response

---
*Generated by XDR Common Schema Public Doc Generator V2*

---
layout: default
title: Trend Micro Deep Security - Endpoint
---

# Trend Micro Deep Security
**Layer:** Endpoint

This documentation provides detailed information about all fields available for Trend Micro Deep Security.

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
      <td class="field-name">deviceDirection</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Device Direction. If the source IP is in the internal network (the network monitored by Deep Discovery Inspector) it is tagged as outbound. All other cases are inbound. Internal-to-internal is also tagged as outbound.</td>
      <td class="example">
        <ul>
          <li>outbound</li>
          <li>inbound</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Security</li>
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
          <li>Trend Vision One Container Security</li>
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
          <li>Trend Vision One Container Security</li>
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
      <td class="field-name">pTags</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event tagging system</td>
      <td class="example">
        <ul>
          <li>attack-T1059.001, mitre attack detection</li>
          <li>suppress_alert</li>
          <li>SMB</li>
        </ul>
      </td>
      <td class="products">Trend Micro Deep Security</td>
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
          <li>Trend Vision One Container Security</li>
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
- **Total Fields:** 79
- **Layer:** Endpoint
- **Product:** Trend Micro Deep Security

---
*Generated by XDR Common Schema Public Doc Generator V2*

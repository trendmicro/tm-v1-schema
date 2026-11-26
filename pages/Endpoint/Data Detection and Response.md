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
          <li>Container Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Cloud App Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Web Security</li>
          <li>Email Security</li>
          <li>Deep Security</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Email Sensor</li>
          <li>Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Cloud IPS</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Web Security</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne StellarOne</li>
          <li>Data Detection and Response</li>
          <li>Endpoint &amp; Workload Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">aggregateFunction</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The metric unit</td>
      <td class="example">file</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">channel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The channel through which the demanded WinEvent is delivered</td>
      <td class="example">
        <ul>
          <li>Local file or network drive</li>
          <li>Local file</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">computerDomain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The computer domain</td>
      <td class="example">
        <ul>
          <li>COMCEL_DOMINIO</li>
          <li>HDWA</li>
          <li>RANDON</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionFileList</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The information about the related files</td>
      <td class="example">{&quot;fileName&quot;: &quot;sample.txt&quot;, &quot;edgeId&quot;: &quot;00000000-0000-0000-0000-000000000000&quot;}</td>
      <td class="products">Data Detection and Response</td>
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
          <li>Apex One as a Service</li>
          <li>Apex One</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">deviceGUID</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Deep Discovery Analyzer</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Deep Security</li>
          <li>Cloud One Network Security</li>
          <li>Endpoint Sensor</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Container Security</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
          <li>Cloud IPS</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">duration</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The detection interval (in milliseconds)</td>
      <td class="example">300000</td>
      <td class="products">Data Detection and Response</td>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dvchost</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Apex One as a Service</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>TXOne StellarOne</li>
          <li>Container Security</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>TXOne StellarOne</li>
          <li>Container Security</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Cloud One Network Security</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>Endpoint Sensor</li>
          <li>Email Security</li>
          <li>TXOne StellarOne</li>
          <li>Container Security</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Mobile Security</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
          <li>Deep Discovery Analyzer</li>
          <li>dan</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>Endpoint Sensor</li>
          <li>Cloud One Network Security</li>
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
          <li>Deep Discovery Analyzer</li>
          <li>Cloud IPS</li>
          <li>dan</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventSourceType</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event source type</td>
      <td class="example">
        <ul>
          <li>3 - EVENT_SOURCE_EVENT_LOG</li>
          <li>2 - EVENT_SOURCE_JAGUAR</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">extraInfo</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The network application name</td>
      <td class="example">
        <ul>
          <li>N/A</li>
          <li>Web Client Common</li>
          <li>DCERPC Services</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Apex One as a Service</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Data Detection and Response</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne StellarOne</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>TXOne StellarOne</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Apex One as a Service</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">firstSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The first time the XDR log appeared</td>
      <td class="example">1657195233000</td>
      <td class="products">
        <ul>
          <li>Cloud App Security</li>
          <li>TXOne StellarOne</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">groupId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The group ID for the management scope filter</td>
      <td class="example">00000000-0000-0000-0000-000000000000</td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">lastSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The last time the XDR log appeared</td>
      <td class="example">1657195233000</td>
      <td class="products">
        <ul>
          <li>Cloud App Security</li>
          <li>TXOne StellarOne</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">lineageId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The telemetry events that match the Security Analytics Engine filter, and logonUsers stores the logonUsers value of the original events</td>
      <td class="example">BHBShortJ</td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Data Detection and Response</li>
          <li>Endpoint Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailMsgSubject</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Cloud App Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Email Security</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">matchedContent</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The one-to-many data structure</td>
      <td class="example">
        <ul>
          <li>[&#x27;matchedContentEx:client_id=00000000-0000-0000-0000-000000000000&amp;redirect_uri=https://example.page.com, matchedInfo:0,6|0,6&#x27;]</li>
          <li>[&#x27;matchedContentEx:example string, matchedInfo:0,6&#x27;]</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">matchedPolicies</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The matched policies of detection records</td>
      <td class="example">[&#x27;00000000-0000-0000-0000-000000000000&#x27;]</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">mDevice</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">IP of the source</td>
      <td class="example">
        <ul>
          <li>10.10.10.10</li>
          <li>fe80::1234:5678:9abc:def0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">metaSrcExtra</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The meta for identifying the source of events</td>
      <td class="example">[{&#x27;metaSrcUri&#x27;: ...]</td>
      <td class="products">Data Detection and Response</td>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Cloud One Network Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectFileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cryptographic hash of the target process image or file, with the specific hash algorithm to be determined</td>
      <td class="example">1ca71017d2fa4775253670e1e55e26912bfdc156</td>
      <td class="products">Data Detection and Response</td>
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
          <li>Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
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
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
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
      <td class="products">
        <ul>
          <li>Endpoint &amp; Workload Security</li>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
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
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectServiceType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Cloud App Security</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Email Security</li>
          <li>Endpoint Sensor</li>
          <li>File Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectUri</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Path of target file</td>
      <td class="example">C://path/of/file.txt</td>
      <td class="products">Data Detection and Response</td>
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
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">online</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The flag to identify whether the endpoint is online</td>
      <td class="example">
        <ul>
          <li>Yes</li>
          <li>No</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="searchable">true</td>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Web Security</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Container Security</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
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
          <li>Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>Cloud One Network Security</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Container Security</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyIds</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Ids of DDR’s data policy</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">policyName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Apex One as a Service</li>
          <li>Cloud App Security</li>
          <li>Web Security</li>
          <li>Email Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Container Security</li>
          <li>Mobile Network Security</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyTemplate</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
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
          <li>Apex One as a Service</li>
          <li>Cloud App Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">principalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user principal name used to sign in to the proxy</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Cloud App Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Container Security</li>
          <li>Okta</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
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
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Container Security</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">productCode</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal product code</td>
      <td class="example">
        <ul>
          <li>sds</li>
          <li>pdi</li>
          <li>xns</li>
          <li>sao</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Mobile Security</li>
          <li>Container Security</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Deep Discovery Analyzer</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Cloud App Security</li>
          <li>Cloud One Network Security</li>
          <li>Email Security</li>
          <li>Deep Security</li>
          <li>Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Deep Discovery Analyzer</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestBase</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>DomainName</li>
          <li>HostDomain</li>
        </ul>
      </td>
      <td class="description">The domain of the request URL</td>
      <td class="example">
        <ul>
          <li>weather.service.msn.com</li>
          <li>test.domain.com</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Web Security</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Email Sensor</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleIdStr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID</td>
      <td class="example">TM-00000043</td>
      <td class="products">
        <ul>
          <li>Container Security</li>
          <li>Apex One as a Service</li>
          <li>Endpoint Sensor</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleIdStr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID</td>
      <td class="example">0000000-0000-0000-0000-000000000000</td>
      <td class="products">Data Detection and Response</td>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Email Security</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Container Security</li>
          <li>Email Sensor</li>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
          <li>Cloud IPS</li>
          <li>dan</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">senderIp</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sender IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Email Security</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Cloud One Network Security</li>
          <li>Container Security</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
          <li>dan</li>
          <li>Data Detection and Response</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>TXOne EdgeOne</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Deep Security</li>
          <li>Cloud One Network Security</li>
          <li>Endpoint Sensor</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Container Security</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
          <li>Cloud IPS</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Apex One as a Service</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>TippingPoint Security Management System</li>
          <li>Deep Security</li>
          <li>Cloud One Network Security</li>
          <li>Endpoint Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne EdgeOne</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Container Security</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
          <li>Cloud IPS</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Endpoint Sensor</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcFileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cryptographic hash of the source process image or file, with the specific hash algorithm to be determined.</td>
      <td class="example">1ca71017d2fa4775253670e1e55e26912bfdc156</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashSha1</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the source file</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
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
          <li>1255856</li>
          <li>1237880</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Container Security</li>
          <li>Data Detection and Response</li>
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
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcServiceType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">srcType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source device type</td>
      <td class="example">Desktop/Laptop</td>
      <td class="products">
        <ul>
          <li>Mobile Network Security</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcUri</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Path of source file</td>
      <td class="example">C://path/of/file.txt</td>
      <td class="products">Data Detection and Response</td>
    </tr>
    <tr>
      <td class="field-name">srcUser</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">suser</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailSender</td>
      <td class="description">The email sender</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
          <li>Data Detection and Response</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDomain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Apex One as a Service</li>
          <li>Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Endpoint Sensor</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">uuid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Unique key of the log</td>
      <td class="example">
        <ul>
          <li>000008d7-35fd-4d7b-bada-7f38dca2abf7</li>
          <li>0000116b-ac61-48d2-89e1-3d1ce2d13cdd</li>
          <li>000017f4-ac10-43b4-8aef-97158e0f8533</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">uuids</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The UUIDs of detection records</td>
      <td class="example">[&#x27;00000000-0000-0000-0000-000000000000&#x27;]</td>
      <td class="products">Data Detection and Response</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 96
- **Layer:** Endpoint
- **Product:** Data Detection and Response

---
*Generated by XDR Common Schema Public Doc Generator V2*

---
layout: default
title: Zero Trust Secure Access - Internet Access - Network
---

# Zero Trust Secure Access - Internet Access
**Layer:** Network

This documentation provides detailed information about all fields available for Zero Trust Secure Access - Internet Access.

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
      <td class="field-name">act</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The action</td>
      <td class="example">
        <ul>
          <li>Allow</li>
          <li>Block</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="field-name">application</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">application</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the requested application</td>
      <td class="example">
        <ul>
          <li>Facebook</li>
          <li>wiki</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">authType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authorization type</td>
      <td class="example">
        <ul>
          <li>Cookie JWT</li>
          <li>No Auth</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">authType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication method</td>
      <td class="example">
        <ul>
          <li>{&#x27;Cookie JWT&#x27;: &#x27;Authenticated by browser cookie with JWT token&#x27;}</li>
          <li>{&#x27;Agent JWT&#x27;: &#x27;Authenticated by Secure Access Module with JWT token&#x27;}</li>
          <li>{&#x27;IP&#x27;: &#x27;Authentication bypassed by private IP.&#x27;}</li>
          <li>{&#x27;No Auth&#x27;: &#x27;No authentication.&#x27;}</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">clientIp</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The IP addresses of the source</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">clientIp</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The endpoint IP address</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">clientProtocol</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The client protocol</td>
      <td class="example">HTTP/1.1</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">clientTls</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The transport layer security of the client</td>
      <td class="example">TLS 1.2</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">cloudAppCat</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The category of the event in Cloud Reputation Service</td>
      <td class="example">
        <ul>
          <li>All</li>
          <li>Online Service</li>
          <li>Application Suite</li>
          <li>Business Intelligence and Analytics</li>
          <li>Cloud Computing Platform</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">cloudAppCat</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The category of the event in Cloud Reputation Service</td>
      <td class="example">
        <ul>
          <li>All</li>
          <li>Online Service</li>
          <li>Application Suite</li>
          <li>Business Intelligence and Analytics</li>
          <li>Cloud Computing Platform</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">contentEncoding</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The content encoding of the request or the response</td>
      <td class="example">gzip</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="field-name">detectionType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The traffic detection type</td>
      <td class="example">
        <ul>
          <li>No matched Zero Trust Secure Access rule</li>
          <li>Missing or invalid client certificate</li>
          <li>Untrusted server certificate</li>
          <li>Zero Trust Secure Access</li>
          <li>HTTPS inspection exception</li>
          <li>HTTPS inspection failure</li>
          <li>HTTPS bypass at inspection failure</li>
          <li>Approved URLs</li>
          <li>Blocked URLs</li>
          <li>Private IP address access</li>
          <li>Web Reputation</li>
          <li>URL Filtering</li>
          <li>Restricted file type</li>
          <li>Restricted MIME type</li>
          <li>Restricted file extension type</li>
          <li>Anti-malware scan</li>
          <li>File scan exception</li>
          <li>Predictive Machine Learning</li>
          <li>Botnet</li>
          <li>Application Control</li>
          <li>Virtual Analyzer submission</li>
          <li>Tenancy Restriction</li>
          <li>Suspicious Object Blocked List</li>
          <li>Data Loss Prevention</li>
          <li>Ransomware</li>
          <li>Risk Control</li>
          <li>AI Service Risk Control</li>
          <li>Non-compliant device</li>
          <li>AI Service Access</li>
          <li>AI Service Sensitive Data Prevention</li>
          <li>AI Service Prompt Injection</li>
          <li>AI Service Improper Answer</li>
          <li>AI Service Malicious URL Answer</li>
          <li>AI Service File Upload Detection</li>
          <li>AI Service Rate Limiting</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="field-name">deviceGUID</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The non-endpoint object such as a network appliance</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
      <td class="description">The destination IP address (dstaddr)</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dstLocation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The destination country</td>
      <td class="example">JP</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">dstLocation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The destination country</td>
      <td class="example">JP</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">duration</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time it took the scanner to complete the scan, in milliseconds</td>
      <td class="example">1599465660123</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">e2eLatency</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The end-to-end traffic latency time, in milliseconds</td>
      <td class="example">10000</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="description">The device GUID</td>
      <td class="example">
        <ul>
          <li>11111111-1111-1111-1111-111111111111</li>
          <li>DSP84573ULLJHM5GK2R7</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="description">The host name of the device on which the event was detected</td>
      <td class="example">
        <ul>
          <li>my_machine</li>
          <li>jeremy-mbp</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="field-name">eventName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the log event</td>
      <td class="example">
        <ul>
          <li>SWG_ACTIVITY_LOG</li>
          <li>FIREWALL_ACTIVITY_LOG</li>
          <li>VPC_ACTIVITY_LOG</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
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
      <td class="field-name">eventSubName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Zero Trust Secure Access - Internet Access cloud app action or the Palo Alto Networks firewall log sub-type</td>
      <td class="example">
        <ul>
          <li>OneDrive download file</li>
          <li>start</li>
          <li>end</li>
          <li>drop</li>
          <li>deny</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent or product detected the event</td>
      <td class="example">1657135700000</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">failedHTTPSInspection</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">HTTPS traffic inspection failure</td>
      <td class="example">True</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="field-name">fileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the file that violated the policy</td>
      <td class="example">1e15bf99022a9164708cebb3eace8fd61ad45cba</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
      <td class="field-name">fileHashSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the file that violated the policy</td>
      <td class="example">ba9edecdd09de1307714564c24409bd25508e22fe11c768053a08f173f263e93</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
      <td class="field-name">fileName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>FileName</li>
          <li>FileFullPath</li>
        </ul>
      </td>
      <td class="description">The name of the file that violated the policy</td>
      <td class="example">word.doc</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
      <td class="field-name">fileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The size of the file that is violating the policy</td>
      <td class="example">12134</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">fileType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">fileType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The type of file which is violating the policy</td>
      <td class="example">Microsoft Words</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">isPrivateApp</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the requested application is private</td>
      <td class="example">
        <ul>
          <li>True</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">isPrivateApp</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the requested application is private</td>
      <td class="example">
        <ul>
          <li>True</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="field-name">malName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the detected malware</td>
      <td class="example">-</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">mimeType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The MIME type or content type of the response body</td>
      <td class="example">
        <ul>
          <li>application/octet-stream</li>
          <li>application/json; charset=utf-8</li>
          <li>application/json</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">mimeType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The MIME type or content type of the response body</td>
      <td class="example">text/html</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Data Detection and Response</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
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
          <li>Windows 10</li>
          <li>macos 12.1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="description">The product name</td>
      <td class="example">
        <ul>
          <li>Secure Web Gateway</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
        </ul>
      </td>
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
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">policyTemplate</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Data Loss Prevention template name</td>
      <td class="example">Australia, New Zealand: Healthcare Template,Germany: Banking and Financial Information</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">policyUuid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The UUID of the cloud access or risk control policy, or the hard-coded string that indicates the rule of the global blocked/approved URL list</td>
      <td class="example">
        <ul>
          <li>7937cb0b-e598-4c8f-a50f-65c32905ba3a</li>
          <li>C!7c4433e3-5b2c-449f-b66e-ccaac006b6f1</li>
          <li>8d265639-7202-4455-b640-48683aa2b57d</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">principalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The User Principal Name</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">profile</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the triggered Threat Protection template or Data Loss Prevention profile</td>
      <td class="example">
        <ul>
          <li>Primary Protection Rule</li>
          <li>Multibak Scaner Threat</li>
          <li>default</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">profile</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the triggered Threat Protection template or Data Loss Prevention profile triggered</td>
      <td class="example">-</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="example">1.0</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
          <li>Zero Trust Secure Access - Internet Access</li>
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
      <td class="field-name">request</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">URL</td>
      <td class="description">The destination URL that the user is accessing</td>
      <td class="example">
        <ul>
          <li>https://google.com/</li>
          <li>https://api/example/v1/testit</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="description">The URL domain</td>
      <td class="example">
        <ul>
          <li>www.facebook.com</li>
          <li>gary.webserver64.com</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestMethod</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The network protocol request method</td>
      <td class="example">POST</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestMimeType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The type of request content</td>
      <td class="example">application/json; charset=utf-8</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The request length</td>
      <td class="example">1324</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">responseSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The response length</td>
      <td class="example">1324</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="field-name">rt</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The UTC timestamp</td>
      <td class="example">1599465660</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the triggered cloud access rule</td>
      <td class="example">
        <ul>
          <li>ETL_Access Rules_Web_Host</li>
          <li>block_wiki_for_guest</li>
          <li>BlockHighRiskTCPPortsFromInternet</li>
          <li>unspecified</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">score</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The WRS score</td>
      <td class="example">81</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">sender</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The roaming users or the gateway where the web traffic passed</td>
      <td class="example">
        <ul>
          <li>test user</li>
          <li>VE C&amp;W - 10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">sender</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Zero Trust Internet Access gateway location</td>
      <td class="example">
        <ul>
          <li>{&#x27;Public/Home network&#x27;: &#x27;The default cloud gateway.&#x27;}</li>
          <li>{&#x27;Anything else&#x27;: &#x27;The pre-defined location name of cloud gateway or on-premises gateway.&#x27;}</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">serverProtocol</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The version of the HTTP protocol between the Service Gateway and server/website</td>
      <td class="example">HTTP/1.1</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">serverRespTime</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the server took to respond to the request, in milliseconds</td>
      <td class="example">1599465660123</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">serverTls</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The TLS version between the Service Gateway and server/website</td>
      <td class="example">TLS 1.2</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
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
      <td class="description">The source IP address (srcaddr)</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">srcLocation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source country</td>
      <td class="example">JP</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">srcLocation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source country</td>
      <td class="example">JP</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="field-name">suid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user name or IP address (IPv4)</td>
      <td class="example">
        <ul>
          <li>Sample User Name</li>
          <li>10.10.10.10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">tlsJA3Fingerprint</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The JA3 fingerprint</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">trafficType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Zero Trust Internet Access gateway service mode</td>
      <td class="example">
        <ul>
          <li>{&#x27;Proxy&#x27;: &#x27;Zero Trust Internet Access On-Premises Gateway with forward proxy mode configured&#x27;}</li>
          <li>{&#x27;Forward&#x27;: &#x27;Zero Trust Internet Access On-Premises Gateway with forward proxy mode and port forwarding configured&#x27;}</li>
          <li>{&#x27;ICAP&#x27;: &#x27;Zero Trust Internet Access On-Premises Gateway with ICAP configured&#x27;}</li>
          <li>{&#x27;Reverse&#x27;: &#x27;Zero Trust Internet Access On-Premises Gateway with reverse proxy mode configured&#x27;}</li>
          <li>{&#x27;Proxy (xx)&#x27;: &#x27;Cloud Gateway in xx PoP with forward proxy mode&#x27;}</li>
          <li>{&#x27;Forward (xx)&#x27;: &#x27;Cloud Gateway in xx PoP with forward proxy mode for port forwarding&#x27;}</li>
        </ul>
      </td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
      <td class="field-name">urlCat</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The URL category</td>
      <td class="example">Social Networking</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
    </tr>
    <tr>
      <td class="field-name">userAgent</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The user agent or the agent through which the request was made</td>
      <td class="example">
        <ul>
          <li>Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:47.0)</li>
          <li>Chrome/74.0.3729.108 Safari/537.36</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Zero Trust Secure Access - Private Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDepartment</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">User department</td>
      <td class="example">
        <ul>
          <li>Operations</li>
          <li>BANCA CONSTRUCCION</li>
          <li>CONTACT CENTER</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDepartment</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user department request method</td>
      <td class="example">Sales</td>
      <td class="products">Zero Trust Secure Access - Internet Access</td>
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
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDomain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>DomainName</li>
          <li>AccountDomain</li>
        </ul>
      </td>
      <td class="description">Active directory domain, domain of username for logging in TMAS adminportal adminportal</td>
      <td class="example">trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 97
- **Layer:** Network
- **Product:** Zero Trust Secure Access - Internet Access

---
*Generated by XDR Common Schema Public Doc Generator V2*

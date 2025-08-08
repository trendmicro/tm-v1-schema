---
layout: default
title: Trend Vision One Mobile Security - Others
---

# Trend Vision One Mobile Security
**Layer:** Others

This documentation provides detailed information about all fields available for Trend Vision One Mobile Security.

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
      <td class="field-name">appDexSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The app dex encoded using SHA-256</td>
      <td class="example">08736EDDD3682AC26D9FD42DA2A20B0BADB5C85A5456A0AE85B52D60C564F290</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appIsSystem</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the app is a system app</td>
      <td class="example">False</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appIsSystem</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the app is a system app</td>
      <td class="example">False</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appLabel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">App name</td>
      <td class="example">Mobile Security Virus Test Application</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appLabel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app name (if the subject is an app)</td>
      <td class="example">Collection Nes Games</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appOrSystemEventHashId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event object hash ID</td>
      <td class="example">3859886410</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appPkgName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app package name</td>
      <td class="example">com.example.app_pkg_name_file</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appPkgName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app package name (if the subject is an app)</td>
      <td class="example">com.ConsolesXX.CollectionNesGames</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appPublicKeySha1</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The app public key (SHA-1)</td>
      <td class="example">72080A6B4EB11105B28E31C4753BC91414500AD4</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appPublicKeySha1</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 hash of the app public key (if the subject is an app)</td>
      <td class="example">05FC638156219800DADAC48D8E621E0BCBD3C321</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app size (in bytes)</td>
      <td class="example">28461</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app size (in bytes) if the subject is an app</td>
      <td class="example">16906043</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appVerCode</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app version code</td>
      <td class="example">1</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">appVerCode</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app version code (if the subject is an app)</td>
      <td class="example">0</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">detectionName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Trend Vision One Mobile Security</li>
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
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">endpointModel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Mobile device model</td>
      <td class="example">M2101K9G</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">endpointModel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The endpoint device model</td>
      <td class="example">Pixel 3 XL</td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
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
          <li>2 - TELEMETRY_PROCESS_CREATE</li>
          <li>101 - TELEMETRY_FILE_CREATE</li>
          <li>204 - TELEMETRY_CONNECTION_CONNECT_OUTBOUND</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent detected the event</td>
      <td class="example">1657781088000</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">extraInfo</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The extra information about the app</td>
      <td class="example">
        <ul>
          <li>N/A</li>
          <li>Web Client Common</li>
          <li>DCERPC Services</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">firstSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the event started (in milliseconds)</td>
      <td class="example">1656355418449</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">lastSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the event ended (in milliseconds)</td>
      <td class="example">1656355418449</td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">mailbox</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The mailbox that is protected by Trend Micro</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Vision One Mobile Security</li>
          <li>Email Sensor</li>
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
      <td class="field-name">marsAccount</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The account for Trend Micro Mobile Apps Reputation Service</td>
      <td class="example">XDRv1</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">minorVirusType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Minor virus type</td>
      <td class="example">
        <ul>
          <li>RANSOMWARE</li>
          <li>BANKER</li>
          <li>CREDENTIAL</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppBehavior</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The activity that occurred on the app</td>
      <td class="example">
        <ul>
          <li>GRANTED_CAMERA_PERMISSION</li>
          <li>APP_NO_ICON</li>
          <li>APP_HIDE_ICON</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppBehaviorAttr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The attributes of the app activity</td>
      <td class="example">android.intent.action.BOOT_COMPLETED</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppDexSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 hash of the app Dex value</td>
      <td class="example">C23A87B77B06442FD9AF9A80DD87191EDEADFAB766C862EBC592FE18063D0449</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppInstalledTime</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time of app installation (in milliseconds)</td>
      <td class="example">1607935850</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppIsSystemApp</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the app is a system app</td>
      <td class="example">True</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppLabel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app name</td>
      <td class="example">Collection Nes Games</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppPackageName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app package name</td>
      <td class="example">com.ConsolesXX.CollectionNesGames</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppPublicKeySha1</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 hash of the app public key</td>
      <td class="example">05FC638156219800DADAC48D8E621E0BCBD3C321</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 hash of the app</td>
      <td class="example">692BC8E6BC51807A24BEACC13ED2B68E1F954E152863430E3179FA812937B8B0</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app size (in bytes)</td>
      <td class="example">16906043</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppVerCode</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app version code</td>
      <td class="example">0</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectAppVerName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app version</td>
      <td class="example">1.0</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectCertAttr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The SHA-1 hash of the certificate public key</td>
      <td class="example">05FC638156219800DADAC48D8E621E0BCBD3C321</td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectFileCreation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the target file was created (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1648279273000</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectFileModifiedTime</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The modification time of the target file (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>1652131848000</li>
          <li>1577865600000</li>
          <li>1648279273000</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The target file size</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>59456</li>
          <li>60</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectFirstSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the object first appeared (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>1656458063638</li>
          <li>1656260547165</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectHashId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event object hash ID</td>
      <td class="example">
        <ul>
          <li>8576474808125313522</li>
          <li>-599270888483415002</li>
          <li>2177864258235728980</li>
          <li>2432229257</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectLastSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the object was last seen (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>1656458354730</li>
          <li>1656260580722</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">objectSystemEventAttr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The system event attributes</td>
      <td class="example">LOCK_SCREEN</td>
      <td class="products">Trend Vision One Mobile Security</td>
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
          <li>Windows</li>
          <li>Linux</li>
          <li>macOS</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
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
          <li>Trend Vision One Mobile Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Data Detection and Response</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">osVer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The OS version</td>
      <td class="example">
        <ul>
          <li>Amazon Linux 2</li>
          <li>10.0.19044</li>
          <li>10.0.19042</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="description">Request URL</td>
      <td class="example">
        <ul>
          <li>http://10.10.10.10/fake/site</li>
          <li>http:///fake/param.cgi?action=list&amp;group=Alarm.Status</li>
          <li>http://fake.com/</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="field-name">srcFileCreation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the source file was created (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>1577865600000</li>
          <li>1626201752000</li>
          <li>1626201750000</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source file hash ID</td>
      <td class="example">
        <ul>
          <li>1102079405020678318</li>
          <li>-6926286289273504319</li>
          <li>8528955148329941480</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">srcFileHashSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA256 hash of source file</td>
      <td class="example">
        <ul>
          <li>4eaa002225f4ea2dedcd19b7f1337d7c58ea7dd6d4571c12468dde95e6bcfdaf</li>
          <li>e30508e2088bc16b2a84233ced64995f738deaef2366ac6c86b35c93bbcd9d80</li>
          <li>16b20a3ad485b4fbbe3028c7e743b226db21ea93cacc8b3d7d7d4a731bf02333</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">srcFileModifiedTime</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the source file was modified (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>1626201752000</li>
          <li>1626201750000</li>
          <li>1577865600000</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">srcFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source file size</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>131072</li>
          <li>196608</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">srcFirstSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the source file first appeared (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1656355418449</li>
          <li>1656714760440</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">srcLastSeen</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the source file was last seen (in milliseconds)</td>
      <td class="example">
        <ul>
          <li>0</li>
          <li>1656355418449</li>
          <li>1656715147313</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
    <tr>
      <td class="field-name">systemEventAttr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The attributes of the system event (if the subject is a system event)</td>
      <td class="example">usbdebugging</td>
      <td class="products">Trend Vision One Mobile Security</td>
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
      <td class="field-name">userType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user type</td>
      <td class="example">
        <ul>
          <li>Microsoft Endpoint Manager</li>
          <li>Azure Active Directory</li>
          <li>VMware Workspace ONE UEM</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Mobile Security</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 83
- **Layer:** Others
- **Product:** Trend Vision One Mobile Security

---
*Generated by XDR Common Schema Public Doc Generator V2*

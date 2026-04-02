---
layout: default
title: Deep Discovery Analyzer - Network
---

# Deep Discovery Analyzer
**Layer:** Network

This documentation provides detailed information about all fields available for Deep Discovery Analyzer.

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
      <td class="field-name">actionBy</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user account or system that triggered the event</td>
      <td class="example">
        <ul>
          <li>admin</li>
          <li>SYSTEM</li>
          <li>TREND VISION ONE</li>
        </ul>
      </td>
      <td class="products">Deep Discovery Analyzer</td>
    </tr>
    <tr>
      <td class="field-name">actorHostName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The hostname of the actor that triggered the event</td>
      <td class="example">CNNJ-WCCP-Pxy-1</td>
      <td class="products">Deep Discovery Analyzer</td>
    </tr>
    <tr>
      <td class="field-name">actorIp</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The IP address of the actor that triggered the event</td>
      <td class="example">
        <ul>
          <li>192.168.1.1</li>
          <li>10.0.0.1</li>
          <li>172.16.0.1</li>
        </ul>
      </td>
      <td class="products">Deep Discovery Analyzer</td>
    </tr>
    <tr>
      <td class="field-name">actorProto</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The protocol used by the actor that triggered the event</td>
      <td class="example">
        <ul>
          <li>ICAP REQMOD</li>
          <li>ICAP RESPMODE</li>
        </ul>
      </td>
      <td class="products">Deep Discovery Analyzer</td>
    </tr>
    <tr>
      <td class="field-name">appGroup</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app category of the event</td>
      <td class="example">
        <ul>
          <li>DNS Response</li>
          <li>HTTP</li>
          <li>CIFS</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Deep Security</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Endpoint Sensor</li>
          <li>Cloud One Network Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">deviceMacAddress</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The device mac address</td>
      <td class="example">
        <ul>
          <li>00:00:00:00:00:00</li>
          <li>ff:ff:ff:ff:ff:ff</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">deviceProcessName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the main process executed during Virtual Analyzer analysis</td>
      <td class="example">explorer.exe</td>
      <td class="products">Deep Discovery Analyzer</td>
    </tr>
    <tr>
      <td class="field-name">dhost</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">DomainName</td>
      <td class="description">The destination hostname</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>TXOne EdgeOne</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">dvc</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The IP address of the Deep Discover Inspector appliance</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">engType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Apex One as a Service</li>
          <li>File Security</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
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
          <li>Network Sensor</li>
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
          <li>Network Sensor</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Container Security</li>
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
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Deep Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>TXOne StellarOne</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Apex One as a Service</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Container Security</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
          <li>Email Security</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Deep Security</li>
          <li>Web Security</li>
          <li>TXOne StellarOne</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>File Security Storage</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Container Security</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">msgId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Cloud App Security</li>
          <li>Email Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
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
          <li>Network Sensor</li>
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
          <li>Network Sensor</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Apex One as a Service</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">sandboxCompletedTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The timestamp when Virtual Analyzer completed the sample analysis</td>
      <td class="example">1656324260000</td>
      <td class="products">Deep Discovery Analyzer</td>
    </tr>
    <tr>
      <td class="field-name">sandboxSubmittedTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The timestamp when the sample was submitted to Virtual Analyzer</td>
      <td class="example">1656324260000</td>
      <td class="products">Deep Discovery Analyzer</td>
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
          <li>Network Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>TippingPoint Security Management System</li>
          <li>Cloud One Network Security</li>
          <li>Container Security</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Deep Security</li>
          <li>Mobile Network Security</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>TXOne EdgeOne</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Network Sensor</li>
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
          <li>Network Sensor</li>
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
        </ul>
      </td>
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
          <li>Network Sensor</li>
          <li>Apex One as a Service</li>
          <li>Email Sensor</li>
          <li>Deep Discovery Analyzer</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Security</li>
          <li>Deep Discovery Analyzer</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 40
- **Layer:** Network
- **Product:** Deep Discovery Analyzer

---
*Generated by XDR Common Schema Public Doc Generator V2*

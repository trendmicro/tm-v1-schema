---
layout: default
title: Trend Vision One Container Security - Cloud
---

# Trend Vision One Container Security
**Layer:** Cloud

This documentation provides detailed information about all fields available for Trend Vision One Container Security.

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
      <td class="field-name">clusterId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cluster ID of the container</td>
      <td class="example">TestCluster-2HJdImvH6eO1fgTnCBK3xYA7Sph</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">clusterId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cluster ID of the container</td>
      <td class="example">ben_eks_test-20k90A3jGa4d3YMYfrdGIgs7g9u</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">clusterName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cluster name of the container</td>
      <td class="example">TestCluster</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">clusterName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cluster name of the container</td>
      <td class="example">ben_eks_test</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">containerId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container ID</td>
      <td class="example">7d1e00176d78</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container ID</td>
      <td class="example">4102001853b8</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerImage</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container image</td>
      <td class="example">debian:latest</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerImage</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container image</td>
      <td class="example">dockerhub.io/ubuntu:latest</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerImageDigest</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container image digest</td>
      <td class="example">sha256:bfe6615d017d1eebe19f349669de58cda36c668ef916e618be78071513c690e5</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerImageDigest</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container image digest</td>
      <td class="example">sha256:626ffe58f6e7566e00254b638eb7e0f3b11d4da9675088f4781a50ae288f3322</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container name</td>
      <td class="example">k8s_democon_longrunl_default_11111111-1111-1111-1111-111111111111_0</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">containerName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes container name</td>
      <td class="example">k8s_ubuntu_ubuntu-ds-fp2jk_default_00000000-0000-0000-0000-000000000000_2</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">customAssetTags</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The list of custom asset tags</td>
      <td class="example">{&quot;os&quot;:[&quot;linux&quot;, &quot;windows&quot;], &quot;org&quot;:[&quot;bu1&quot;]}</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">customTags</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event tags</td>
      <td class="example">
        <ul>
          <li>network</li>
          <li>mitre_discovery</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Vision One Container Security</li>
          <li>File Security</li>
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
      <td class="field-name">dpt</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">Port</td>
      <td class="description">The destination port number</td>
      <td class="example">-</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The host name of the container or node</td>
      <td class="example">
        <ul>
          <li>PHILIPSIBE09</li>
          <li>WHAM6WK8XG2</li>
          <li>MacBook-Pro-del-Meno</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">eventId</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Event type</td>
      <td class="example">-</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent detected the event</td>
      <td class="example">1657781088000</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">fileDesc</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="field-name">k8sNamespace</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes namespace of the container</td>
      <td class="example">default</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">k8sNamespace</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes namespace of the container</td>
      <td class="example">default</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">k8sPodId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes pod ID of the container</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">k8sPodId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes pod ID of the container</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000</li>
          <li>11111111-1111-1111-1111-111111111111</li>
          <li>22222222-2222-2222-2222-222222222222</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">k8sPodName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes pod name of the container</td>
      <td class="example">longrunl</td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">k8sPodName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Kubernetes pod name of the container</td>
      <td class="example">ubuntu-ds-fp2jk</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">objectFileCreatedTime</td>
      <td class="type">long</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
          <li>Trend Vision One Container Security</li>
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
          <li>Trend Vision One Container Security</li>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Vision One Container Security</li>
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
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">osName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The host operating system name</td>
      <td class="example">Linux</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">parentCmd</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The command line of the subject parent process</td>
      <td class="example">
        <ul>
          <li>&quot;C:\Tiburon\CommandCAD\Test\Startup.exe&quot; </li>
          <li>C:\WINDOWS\Explorer.EXE</li>
          <li>C:\WINDOWS\system32\svchost.exe -k netsvcs -p -s Appinfo</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Vision One Container Security</li>
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
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">parentLaunchTime</td>
      <td class="type">real</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The time when the parent process was launched</td>
      <td class="example">
        <ul>
          <li>1653614773895</li>
          <li>1656118625928</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">parentName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The image name of the parent process</td>
      <td class="example">
        <ul>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
          <li>c:\windows\system32\lsass.exe</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
    </tr>
    <tr>
      <td class="field-name">parentName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The image name of the parent process</td>
      <td class="example">
        <ul>
          <li>explorer.exe</li>
          <li>startup.exe</li>
          <li>svchost.exe</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
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
          <li>4</li>
          <li>1</li>
          <li>784</li>
          <li>792</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">platformAssetTags</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The list of platform custom asset tags</td>
      <td class="example">{&quot;Asset group&quot;:[&quot;finance&quot;], &quot;some.ip&quot;: [&quot;10.1.0.1&quot;]}</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The policy ID</td>
      <td class="example">TestPolicy-2HJe25H4GY4upSuNNAG1pci2BIm</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">policyName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The name of the triggered policy</td>
      <td class="example">TestPolicy</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">processCmd</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">CLICommand</td>
      <td class="description">Command line entry of subject process</td>
      <td class="example">
        <ul>
          <li>C:\WINDOWS\system32\services.exe</li>
          <li>C:\Windows\system32\services.exe</li>
          <li>/sbin/launchd</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">processFilePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">ProcessFullPath</td>
      <td class="description">The file path of the subject process</td>
      <td class="example">
        <ul>
          <li>c:\windows\system32\services.exe</li>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="type">real</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The time the subject process was launched</td>
      <td class="example">
        <ul>
          <li>1653614773895</li>
          <li>1656118625928</li>
          <li>0</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
          <li>Trend Micro Apex One as a Service</li>
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
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">proto</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The protocol type</td>
      <td class="example">
        <ul>
          <li>TELEMETRY_CONNECTION_TCP</li>
          <li>TELEMETRY_CONNECTION_UDP</li>
        </ul>
      </td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">rawDataStr</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The JSON string that contains additional information</td>
      <td class="example">
        <ul>
          <li>{&quot;TLS version&quot;: &quot;0x0303&quot;, &quot;Cipher Suite&quot;: &quot;0xc030&quot;}</li>
          <li>{&quot;Scanned ports&quot;: &quot;23, 80, 443&quot;}</li>
          <li>{&quot;HTTP Content-Type&quot;: &quot;application/hal+json&quot;, &quot;HTTP Content-Body&quot;: &quot;{\\&quot;_links\\&quot;: {\\&quot;type\\&quot;: {\\&quot;href\\&quot;: \\&quot;http://10.10.10.10/rest/type/node/INVALID_VALUE\\&quot;}}, \\&quot;type\\&quot;: {\\&quot;target_id\\&quot;: \\&quot;article\\&quot;}, \\&quot;title\\&quot;: {\\&quot;value\\&quot;: \\&quot;My Article\\&quot;}, \\&quot;body\\&quot;: {\\&quot;value\\&quot;: \\&quot;\\&quot;}}&quot;}</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Vision One Container Security</li>
          <li>Network Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ruleIdStr</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID</td>
      <td class="example">TM-00000036</td>
      <td class="products">Trend Vision One Container Security</td>
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
          <li>Trend Vision One Container Security</li>
          <li>Trend Micro Apex One as a Service</li>
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
      <td class="field-name">ruleSetId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The rule set ID</td>
      <td class="example">AllRules-1zSSZPsDqfqkcOt5vNsD6f383HN</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">sourceType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="field-name">srcFileHashSha256</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the source file</td>
      <td class="example">-</td>
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="products">Trend Vision One Container Security</td>
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
      <td class="description">The detected ID based on the alert filter</td>
      <td class="example">
        <ul>
          <li>MITREV9.T1057</li>
          <li>MITREV9.T1059.003</li>
          <li>XSAE.F2924</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Trend Vision One Container Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDefinedFields</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user-defined field for custom detection rules</td>
      <td class="example">{&quot;message&quot;: &quot;There is a shell process running in the container with ID \&quot;1234567890abcdef\&quot;.&quot;}</td>
      <td class="products">Trend Vision One Container Security</td>
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
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 102
- **Layer:** Cloud
- **Product:** Trend Vision One Container Security

---
*Generated by XDR Common Schema Public Doc Generator V2*

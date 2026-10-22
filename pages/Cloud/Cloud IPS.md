---
layout: default
title: Cloud IPS - Cloud
---

# Cloud IPS
**Layer:** Cloud

This documentation provides detailed information about all fields available for Cloud IPS.

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
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">awsResourceArn</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The Amazon Resource Name</td>
      <td class="example">
        <ul>
          <li>arn:aws:s3:::bucket-name/object-key</li>
          <li>arn:aws:s3:::user-bucket-name/file-name</li>
          <li>arn:aws:s3:::bucket-name/folder-name/file-name</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>File Security Storage</li>
          <li>Cloud IPS</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">azId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The virtual machine Availability Zone ID</td>
      <td class="example">
        <ul>
          <li>us-east-1b</li>
          <li>us-west-2a</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Cloud IPS</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Cloud IPS</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">cloudAccountId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
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
          <li>Container Security</li>
          <li>Cloud IPS</li>
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
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">flowId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The connection ID</td>
      <td class="example">
        <ul>
          <li>6717474604962545666</li>
          <li>6915244861077872618</li>
          <li>6915244908215815814</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Deep Discovery Director</li>
          <li>Cloud IPS</li>
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
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Container Security</li>
          <li>Virtual Network Sensor</li>
          <li>Cloud IPS</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Security</li>
          <li>Apex One as a Service</li>
          <li>Mobile Network Security</li>
          <li>Cloud IPS</li>
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
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 14
- **Layer:** Cloud
- **Product:** Cloud IPS

---
*Generated by XDR Common Schema Public Doc Generator V2*

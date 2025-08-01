---
layout: default
title: Email Sensor - Email
---

# Email Sensor
**Layer:** Email

This documentation provides detailed information about all fields available for Email Sensor.

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
      <td class="field-name">attachment</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The information about the email attachment</td>
      <td class="example">{&quot;attachmentFileTlsh&quot;: &quot;&quot;, &quot;attachmentFileName&quot;: &quot;testfile.txt&quot;,&quot;attachmentFileHash&quot;: &quot;&quot;,&quot;attachmentFileSize&quot;: &quot;-1&quot;}</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 of the email attachment</td>
      <td class="example">
        <ul>
          <li>C9877617DB6715792F9D5C959C1E8D4E56D0C281</li>
          <li>0340A8EE3AD2990E3EDCDB2E471EAA45B4286722</li>
          <li>0E56D9540B07ED15EF745348D35C72A6A00A0BD9</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileHashes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The SHA-1 of the email attachment</td>
      <td class="example">
        <ul>
          <li>056a2975edffe7188c03c324ae4335f9380b57e3</li>
          <li>05fd3ac8f9d8407e6637e0f91cd2ff5ab076658a</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileHashes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">SHA-1 hash of the email attachment</td>
      <td class="example">
        <ul>
          <li>acedb7898338a46f38d148d1d0456e644576d41b</li>
          <li>ea6fcc4c0c1f10d71742b29e98a977d995473dd1</li>
          <li>03d8fb85556edf397d8afcafc0b13f11ecbde50c</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileHashs</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The SHA-1 hash value of the attachment file</td>
      <td class="example">
        <ul>
          <li>056a2975edffe7188c03c324ae4335f9380b57e3</li>
          <li>05fd3ac8f9d8407e6637e0f91cd2ff5ab076658a</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileHashSha256s</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">SHA-256 hash of the email attachment</td>
      <td class="example">
        <ul>
          <li>0570dfd156ee00cb7bc2a94998157cb3a29292b9e9feed82d4b6c7d2c6bdd9d4</li>
          <li>2d96ebbbc5a5687b0f18fd5620e4e5489d49a877430146bbca447fabe9c47a6e</li>
          <li>20d27422610967122439735cbcb48e4382a16e94a8b29c068e6b7d0e40466427</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileName</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileName</td>
      <td class="description">The file name of an attachment</td>
      <td class="example">
        <ul>
          <li>Mail Body</li>
          <li>image001.png</li>
          <li>image002.png</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileName</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileName</td>
      <td class="description">File name of the email attachment</td>
      <td class="example">
        <ul>
          <li>image001.png</li>
          <li>image002.png</li>
          <li>image003.png</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileSize</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the email attachment</td>
      <td class="example">
        <ul>
          <li>190843</li>
          <li>104454</li>
          <li>112197</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileSizes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The file size of email attachments</td>
      <td class="example">
        <ul>
          <li>190843</li>
          <li>104454</li>
          <li>112197</li>
        </ul>
      </td>
      <td class="products">Email Sensor</td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileTlshes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The TLSH of the email attachment</td>
      <td class="example">
        <ul>
          <li>0FE18E0807B75799EF3ADD7A98D62411FEB31DAB419C913C058068A3A6B33BD114EA39</li>
          <li>97D18E86E87A85D1D4137E6DA6FD00580E4CF06F65DB2B2937815E4F3A3013042A2189</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileTlshes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The TLSH hash detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentFileTlshs</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The TLSH hash value of the attachment file</td>
      <td class="example">
        <ul>
          <li>0FE18E0807B75799EF3ADD7A98D62411FEB31DAB419C913C058068A3A6B33BD114EA39</li>
          <li>97D18E86E87A85D1D4137E6DA6FD00580E4CF06F65DB2B2937815E4F3A3013042A2189</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentMd5</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileMD5</td>
      <td class="description">MD5 hash of the email attachment</td>
      <td class="example">
        <ul>
          <li>003fa299ab119219596f952c68029810</li>
          <li>03aeabf6a745cb627ee29c05a22e58cb</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentSha1</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">SHA-1 hash of the email attachment</td>
      <td class="example">
        <ul>
          <li>03d8fb85556edf397d8afcafc0b13f11ecbde50c</li>
          <li>056a2975edffe7188c03c324ae4335f9380b57e3</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentSha256</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">SHA-256 hash of the email attachment</td>
      <td class="example">
        <ul>
          <li>29d72af5608ee5eade7c4346d3c32dfcc6b54f8fb43d977ff0306ad68b255a01</li>
          <li>cb0628092ddea96bb040221b5c793dbbb792a67d0621bdfba170c07374d85801</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentSize</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The attachment file size</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentSource</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The attachment source</td>
      <td class="example">
        <ul>
          <li>TMASE</li>
          <li>PRODUCT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentTlsh</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The TLSH hash detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>0FE18E0807B75799EF3ADD7A98D62411FEB31DAB419C913C058068A3A6B33BD114EA39</li>
          <li>7C31C9827A71A905CC6B0A73B10FE80C06F01E814AA396347F8B6F979690E9C3D75147</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">attachmentUrls</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The URLs and URL sources extracted from the email attachment</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">correlatedIntelligence</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Correlated Intelligence detection</td>
      <td class="example">{&quot;risk_type&quot;: &quot;Anomaly&quot;,&quot;matched_rules&quot;: [{&quot;threat_type&quot;: &quot;Possibly Unwanted Email&quot;,&quot;matched_filters&quot;: [{&quot;id&quot;:&quot;FIL013&quot;, &quot;name&quot;: &quot;Marketing Email Traits&quot;},{&quot;id&quot;:&quot;FIL098&quot;, &quot;name&quot;: &quot;Infrequent Sender Email Domain&quot;}],&quot;name&quot;: &quot;Possibly Unwanted Marketing Email&quot;,&quot;id&quot;: &quot;AN004&quot;}]}</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
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
      <td class="description">The event ID</td>
      <td class="example">
        <ul>
          <li>1 - MESSAGING_EMAIL_META</li>
          <li>2 - MESSAGING_COLLABORATION_ACTIVITY</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
          <li>Collaboration sensor</li>
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
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent detected the event</td>
      <td class="example">1657135700000</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">groupId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The group ID for the management scope filter</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">highlightedFileHashes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 hashes of the highlighted file</td>
      <td class="example">
        <ul>
          <li>C9877617DB6715792F9D5C959C1E8D4E56D0C281</li>
          <li>0340A8EE3AD2990E3EDCDB2E471EAA45B4286722</li>
          <li>0E56D9540B07ED15EF745348D35C72A6A00A0BD9</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">highlightedFileName</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The file names of suspicious attachments</td>
      <td class="example">
        <ul>
          <li>detect_me.zip</li>
          <li>covid.zip</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailAttachmentHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileMD5</td>
      <td class="description">Hash value of the email attachment</td>
      <td class="example">
        <ul>
          <li>02ab50ee0bccadb43d6cc504928f2ff2</li>
          <li>0a0f335fb04f1acebb7500d5358321c0</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailBccAddresses</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailRecipient</td>
      <td class="description">Mail BCC address in the email header</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
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
      <td class="field-name">mailbox</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Primary email address</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailCacheId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal email cache ID to identify emails in the same group mails</td>
      <td class="example">&lt;sample_email@trendmicro.com&gt;</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailCcAddresses</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailRecipient</td>
      <td class="description">Mail CC address in the email header</td>
      <td class="example">
        <ul>
          <li>&lt;sample_email@trendmicro.com&gt;</li>
          <li>sample_email@trendmicro.com</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailDirection</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">Email traffic direction</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>3</li>
          <li>25</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailDirection</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Email traffic direction</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>3</li>
          <li>25</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailEurekaRuleIds</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The list of rule IDs scanned by Eureka and detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>661030</li>
          <li>661230</li>
          <li>661267</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailFeatureId</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email protocol detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailFolder</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email folder name</td>
      <td class="example">
        <ul>
          <li>Inbox</li>
          <li>Bandeja de entrada</li>
          <li>Sent Items</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailFromAddresses</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailSender</td>
      <td class="description">Mail from address in email header</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailHeaderHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email header hash detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>43f8bfc02d8f78f069c254bc17eba80b</li>
          <li>aa5d16ca145f91471e482d235843aac5</li>
          <li>ad8776382ea4b7cffd0961c70223162e</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailHelo</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The HELO command detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">HELO inpost.tmes.trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailMetaText</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The postman meta text detected by Trend Micro Anti-Spam Engine</td>
      <td class="example"></td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailMetaTraceId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The trace ID generated by Trend Micro Feedback Engine</td>
      <td class="example"></td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailMsgDirection</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The direction of the email message</td>
      <td class="example">1</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailMsgId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailMessageID</td>
      <td class="description">Email ID</td>
      <td class="example">&lt;sample-id@trendmicro.com&gt;</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
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
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailMsgSubject</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailSubject</td>
      <td class="description">Email subject</td>
      <td class="example">
        <ul>
          <li>Your daily briefing</li>
          <li>Security alert for DeleteSecurityGroup on Account 549918006255 in Region: ap-southeast-1</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailReplyToAddresses</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Reply To address detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailReturnPath</td>
      <td class="type">dynamic</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The hidden email header that indicates where bounced messages are sent</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailRuleId</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The rule ID of the matched rule detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>42003</li>
          <li>148036</li>
          <li>148140</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailScore</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The score assigned to the email by Trend Micro Anti-Spam Engine</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailSenderIp</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Email sender IP address</td>
      <td class="example">10.10.10.10</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailSmtpFromAddresses</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sender email address</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailSmtpOriginalRecipients</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Original email recipients in the SMTP envelope</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailSmtpRecipients</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Email recipients in the SMTP envelope after scanning</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailSmtpTls</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The SMTP TLS version number</td>
      <td class="example">
        <ul>
          <li>TLS 1.2</li>
          <li>TLS 1.3</li>
          <li>noTLS</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailSourceDomain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Email domain of the sender</td>
      <td class="example">example.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailTagHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email tag hash detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>9ce01ebc63f408264876646e20905349</li>
          <li>cf679dc99042b781106cbaccd4045ed3</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailTagHashRawSignature</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The raw signature hash of the email</td>
      <td class="example">
        <ul>
          <li>PGh0bWw+PGhlYWQ+PG1ldGEgaHR0cC1lcXVpdj0gY29udGVudD0gY2hhcnNldD0gPjxtZXRhIG5hbWU9IGNvbnRlbnQ9ID48c3R5bGU+PCEtLS0tPjwvc3R5bGU+PC9oZWFkPjxib2R5IGxhbmc9IGxpbms9IHZsaW5rPSBzdHlsZT0gPjxkaXYgY2xhc3M9ID48cCBjbGFzcz0gPjxURVhUPjwvcD48L2Rpdj48L2JvZHk+PC9odG1sPg==</li>
          <li>PGh0bWw+PGhlYWQ+PG1ldGEgaHR0cC1lcXVpdj0gY29udGVudD0gY2hhcnNldD0gPjwvaGVhZD48Ym9keT48VEVYVD48L2JvZHk+PC9odG1sPg==</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailTextHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email text hash detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>221bab3766f6d2a2c6fcc37056511d53</li>
          <li>f26f3a415103ea083ac49be6bb60f337</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailThreatType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The type of email detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>suspected</li>
          <li>suspected,</li>
          <li>suspected, phishing</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailToAddresses</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailRecipient</td>
      <td class="description">Mail To address in the email header</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailUrlHash</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email URL hash detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>ca52197d96e4a00ce19eaf34b20c8937</li>
          <li>ad50776a891bead6bf222e2b7be17724</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailUrlsOriginalLink</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The original URL extracted from the email content</td>
      <td class="example">
        <ul>
          <li>https://aka.ms/JoinTeamsMeeting</li>
          <li>http://go.microsoft.com/fwlink/p/?LinkID=12345</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailUrlsRealLink</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">URL</td>
      <td class="description">URL extracted from the email content</td>
      <td class="example">
        <ul>
          <li>https://aka.ms/JoinTeamsMeeting</li>
          <li>http://go.microsoft.com/fwlink/p/?LinkID=12345</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailUrlsVisibleLink</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">URL</td>
      <td class="description">URL extracted from the email content</td>
      <td class="example">
        <ul>
          <li>Unsubscribe</li>
          <li>Android</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailUserAgent</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user agent</td>
      <td class="example">
        <ul>
          <li>Mutt/1.4.2.2i</li>
          <li>Heirloom mailx 12.5 7/5/10</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailWantedHeaderName</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The WantedHeader key name detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>CC</li>
          <li>X-TM-Product-Ver</li>
          <li>Received</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailWantedHeaderValue</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The WantedHeader key value detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">
        <ul>
          <li>cloud-app-security-5.0</li>
          <li>BCL:0;</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailWholeHeader</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name and email address of the sender in the From header detected by Trend Micro Anti-Spam Engine</td>
      <td class="example">&lt;sample_email@trendmicro.com&gt;</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">mailXMailer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The X-Mailer header of the email</td>
      <td class="example">
        <ul>
          <li>Microsoft Outlook 16.0</li>
          <li>Microsoft CDO for Windows 2000</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
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
      <td class="field-name">mExternalUid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique ID of the email</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
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
      <td class="field-name">msgUuid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique email ID</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000</li>
          <li>11111111-1111-1111-1111-111111111111</li>
          <li>22222222-2222-2222-2222-222222222222</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">msgUuid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Internal email UUID to identify each email message</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">msgUuidChain</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal UUID chain for each email in Trend Micro Feedback Engine</td>
      <td class="example">11111111-1111-1111-1111-111111111111;00000000-0000-0000-0000-000000000000</td>
      <td class="products">
        <ul>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">orgId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The organization ID</td>
      <td class="example">
        <ul>
          <li>00000000-0000-0000-0000-000000000000</li>
          <li>11111111-1111-1111-1111-111111111111</li>
          <li>22222222-2222-2222-2222-222222222222</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">orgId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The organization ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
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
      <td class="description">Internal product code (depricated)</td>
      <td class="example">
        <ul>
          <li>733</li>
          <li>742</li>
          <li>TMEMS</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
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
      <td class="field-name">scanTs</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the email was scanned</td>
      <td class="example">1657135700000</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Email Sensor</li>
          <li>Trend Micro Email Security</li>
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
      <td class="field-name">scanType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Manual or real-time scan</td>
      <td class="example">
        <ul>
          <li>realtime_mailmeta-exchange</li>
          <li>realtime_mailmeta-gmail</li>
          <li>gateway_mailmetadata</li>
          <li>gateway_realtime_accepted_mail_traffic</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Email Sensor</li>
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
      <td class="field-name">suser</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">EmailSender</td>
      <td class="description">The email sender</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">
        <ul>
          <li>Trend Micro Cloud App Security</li>
          <li>Trend Micro Email Security</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>Network Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Email Sensor</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 93
- **Layer:** Email
- **Product:** Email Sensor

---
*Generated by XDR Common Schema Public Doc Generator V2*

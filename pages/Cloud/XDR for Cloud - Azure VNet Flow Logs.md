---
layout: default
title: XDR for Cloud - Azure VNet Flow Logs - Cloud
---

# XDR for Cloud - Azure VNet Flow Logs
**Layer:** Cloud

This documentation provides detailed information about all fields available for XDR for Cloud - Azure VNet Flow Logs.

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
      <td class="field-name">dpt</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">Port</td>
      <td class="description">The service destination port of the private application server (dstport)</td>
      <td class="example">443</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
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
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event ID</td>
      <td class="example">
        <ul>
          <li>200139</li>
          <li>200140</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Network Sensor</li>
          <li>Trend Micro Deep Discovery Inspector</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
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
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
        </ul>
      </td>
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
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">flowDirection</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The network interface traffic direction</td>
      <td class="example">
        <ul>
          <li>ingress</li>
          <li>egress</li>
          <li>I</li>
          <li>O</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
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
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
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
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">spt</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">Port</td>
      <td class="description">The virtual port of the source assigned to the Secure Access Module (srcport)</td>
      <td class="example">57763</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
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
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">vpcFlowLogsVersion</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The VPC Flow Logs version (version)</td>
      <td class="example">
        <ul>
          <li>2</li>
          <li>3</li>
          <li>4</li>
          <li>5</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>XDR for Cloud - Azure VNet Flow Logs</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 11
- **Layer:** Cloud
- **Product:** XDR for Cloud - Azure VNet Flow Logs

---
*Generated by XDR Common Schema Public Doc Generator V2*

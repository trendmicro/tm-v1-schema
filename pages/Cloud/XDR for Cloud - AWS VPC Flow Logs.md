---
layout: default
title: XDR for Cloud - AWS VPC Flow Logs - Cloud
---

# XDR for Cloud - AWS VPC Flow Logs
**Layer:** Cloud

This documentation provides detailed information about all fields available for XDR for Cloud - AWS VPC Flow Logs.

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
      <td class="field-name">action</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The traffic processing action</td>
      <td class="example">
        <ul>
          <li>ACCEPT</li>
          <li>REJECT</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">azId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The Availability Zone ID</td>
      <td class="example">apse2-az3</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">bytes</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The number of transmitted data bytes</td>
      <td class="example">15044</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">dpt</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The service destination port of the private application server (dstport)</td>
      <td class="example">443</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
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
      <td class="field-name">end</td>
      <td class="type">long</td>
      <td class="general-field">-</td>
      <td class="description">The time when the last data packet was received (in Unix seconds)</td>
      <td class="example">1616729349</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">string</td>
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
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventName</td>
      <td class="type">string</td>
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
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
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
      <td class="field-name">flowDirection</td>
      <td class="type">string</td>
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
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">flowType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The type of traffic (type)</td>
      <td class="example">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
          <li>EFA</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">instanceId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The instance ID</td>
      <td class="example">i-01234567890abcdef</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">logStatus</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The VPC Flow Log status</td>
      <td class="example">
        <ul>
          <li>OK</li>
          <li>NODATA</li>
          <li>SKIPDATA</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">packets</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The number of transmitted data packets</td>
      <td class="example">14</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">pktDstAddr</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The packet level destination IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">pktDstCloudServiceName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The subset IP address range name for cloud service destination IP (pkt-dst-aws-service)</td>
      <td class="example">
        <ul>
          <li>AMAZON</li>
          <li>EC2</li>
          <li>ROUTE53</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">pktSrcAddr</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The packet level source IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">pktSrcCloudServiceName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The subset IP address range name for cloud service source IP (pkt-src-aws-service)</td>
      <td class="example">
        <ul>
          <li>AMAZON</li>
          <li>EC2</li>
          <li>ROUTE53</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
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
      <td class="field-name">spt</td>
      <td class="type">int</td>
      <td class="general-field">Port</td>
      <td class="description">The virtual port of the source assigned to the Secure Access Module (srcport)</td>
      <td class="example">57763</td>
      <td class="products">
        <ul>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>XDR for Cloud - AWS VPC Flow Logs</li>
          <li>azv</li>
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
      <td class="field-name">start</td>
      <td class="type">real</td>
      <td class="general-field">-</td>
      <td class="description">The time when the first data packet was received (in Unix seconds)</td>
      <td class="example">1616729292</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">subLocationId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sublocation ID</td>
      <td class="example">
        <ul>
          <li>lz-0abcd123efg4567h</li>
          <li>op-0abcd123efg4567h</li>
          <li>wz-0abcd123efg4567h</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">subLocationType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The sublocation type</td>
      <td class="example">
        <ul>
          <li>wavelength</li>
          <li>outpost</li>
          <li>localzone</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">subnetId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The subnet ID</td>
      <td class="example">subnet-01234567890abcdef</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">tcpFlags</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The bitmask value of the FIN/SYN/RST/SYN-ACK TCP flags</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
          <li>4</li>
          <li>18</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">trafficPath</td>
      <td class="type">int</td>
      <td class="general-field">-</td>
      <td class="description">The egress traffic path number</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
          <li>8</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
    <tr>
      <td class="field-name">vpcFlowLogsVersion</td>
      <td class="type">int</td>
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
          <li>azv</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">vpcId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The VPC ID</td>
      <td class="example">vpc-01234567890abcdef</td>
      <td class="products">XDR for Cloud - AWS VPC Flow Logs</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 29
- **Layer:** Cloud
- **Product:** XDR for Cloud - AWS VPC Flow Logs

---
*Generated by XDR Common Schema Public Doc Generator V2*

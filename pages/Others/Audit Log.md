---
layout: default
title: Audit Log - Others
---

# Audit Log
**Layer:** Others

This documentation provides detailed information about all fields available for Audit Log.

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
      <td class="field-name">eventRawData</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The original event log string (JSON format)</td>
      <td class="example">{&quot;type&quot;:&quot;audit&quot;,&quot;timestamp&quot;:&quot;2020-02-20T08:10:01.904Z&quot;,&quot;serviceName&quot;:&quot;uic&quot;,&quot;componentName&quot;:&quot;backend&quot;,&quot;siteName&quot;:&quot;us-east-1-xdr-eks-prod&quot;,&quot;customerId&quot;:&quot;74b629cb-8fc6-4a1b-a00f-b5003ab9f0e3&quot;,&quot;identifier&quot;:{&quot;id&quot;:&quot;db09668d-9d85-42ee-946f-5f8d37f288b2&quot;,&quot;type&quot;:&quot;managedAccount&quot;,&quot;name&quot;:&quot;John Smith&quot;,&quot;email&quot;:&quot;john_smith@abc.com&quot;},&quot;userId&quot;:&quot;db09668d-9d85-42ee-946f-5f8d37f288b2&quot;,&quot;user&quot;:&quot;xdr-stg@trendmicro.com&quot;,&quot;roleId&quot;:&quot;53a580c5-d952-43e1-8ce3-79eac4961ee6&quot;,&quot;role&quot;:&quot;admin&quot;,&quot;sourceIp&quot;:&quot;180.10.1.2&quot;,&quot;access&quot;:0,&quot;category&quot;:&quot;01&quot;,&quot;activity&quot;:&quot;01&quot;,&quot;result&quot;:true,&quot;triggerService&quot;:&quot;awb&quot;,&quot;details&quot;:{&quot;ipAddr&quot;:&quot;10.0.0.1&quot;}}</td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">eventSourceType</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event source type</td>
      <td class="example">14 - EVENT_SOURCE_AUDIT_LOG</td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent or product detected the event</td>
      <td class="example">
        <ul>
          <li>1656324260000</li>
          <li>1728192606034</li>
          <li>1758293606034</li>
        </ul>
      </td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">filterRiskLevel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The top level filter risk of the event</td>
      <td class="example">
        <ul>
          <li>info</li>
          <li>low</li>
          <li>medium</li>
        </ul>
      </td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">groupId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The group ID for the management scope filter</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">groupName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The group name</td>
      <td class="example">example.com</td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">logReceivedTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time when the XDR log was received</td>
      <td class="example">1656324260000</td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">policyTreePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The policy tree path</td>
      <td class="example">policyname1/policyname2/policyname3</td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">productCode</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The product code</td>
      <td class="example">aal</td>
      <td class="products">Audit Log</td>
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
      <td class="description">The detected technique ID based on the alert filter</td>
      <td class="example">
        <ul>
          <li>[&#x27;MITREV9.T1090&#x27;]</li>
          <li>[&#x27;MITRE.T1071&#x27;]</li>
          <li>[&#x27;MITREV9.T1059.001&#x27;]</li>
        </ul>
      </td>
      <td class="products">Audit Log</td>
    </tr>
    <tr>
      <td class="field-name">uuid</td>
      <td class="type">guid</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique key of the log</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Audit Log</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 11
- **Layer:** Others
- **Product:** Audit Log

---
*Generated by XDR Common Schema Public Doc Generator V2*

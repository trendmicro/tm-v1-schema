---
layout: default
title: Collaboration sensor - Email
---

# Collaboration sensor
**Layer:** Email

This documentation provides detailed information about all fields available for Collaboration sensor.

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
      <td class="field-name">actionName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user or service action</td>
      <td class="example">UserLoggedIn</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">actResult</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The action result</td>
      <td class="example">Success</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">applicationId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The application ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Collaboration sensor</td>
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
      <td class="description">The client IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">cloudStorageId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The file or folder location ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">cloudStorageName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The file or folder URL</td>
      <td class="example">https://test.trendmicro.com/sites/123</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">correlationId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The correlation ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Collaboration sensor</td>
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
      <td class="example">COLLABORATION_ACTIVITY</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">eventSubName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event type sub-name</td>
      <td class="example">
        <ul>
          <li>Audit.Exchange</li>
          <li>Audit.Sharepoint</li>
          <li>Audit.General</li>
        </ul>
      </td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">extraInfo</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The additional information about the sharing action</td>
      <td class="example">&lt;ClientType&gt;SPHomePagesWeb&lt;/ClientType&gt;</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">fileExt</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The file extension (If the object is a folder, there is no value for this field.)</td>
      <td class="example">jpg</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">fileName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileName</td>
      <td class="description">The file or folder name</td>
      <td class="example">test.pdf</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">isExternalAccess</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the cmdlet was run by an external user (True=external user, False=internal user in your organization)</td>
      <td class="example">True</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">isSensitiveInfo</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the event contains sensitive information</td>
      <td class="example">True</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">orgName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The tenant name</td>
      <td class="example">test.trendmicro.com</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">originatingServer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The server where the operation originated</td>
      <td class="example">TY0PR03MB6449 (15.20.5746.023)</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">parameters</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The names and values of all parameters used in the cmdlet identified in the Operations property</td>
      <td class="example">[{&quot;Name&quot;: &quot;AlwaysDeleteOutlookRulesBlob&quot;,&quot;Value&quot;: &quot;False&quot;},{&quot;Name&quot; : &quot;Force&quot;,&quot;Value&quot;: &quot;False&quot;}]</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">principalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The User Principal Name</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">recordType</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The operation type</td>
      <td class="example">
        <ul>
          <li>1</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">service</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft 365 service where the activity occurred</td>
      <td class="example">
        <ul>
          <li>SecurityComplianceCenter</li>
          <li>AzureActiveDirectory</li>
          <li>SharePoint</li>
        </ul>
      </td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">target</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The object accessed by a user or application</td>
      <td class="example">
        <ul>
          <li>APCPR000000.PROD.OUTLOOK.COM/Microsoft Exchange Hosted</li>
          <li>Organizations/test.trendmicro.com/test\\testRule001</li>
        </ul>
      </td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">targetType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The type of object that was accessed or modified</td>
      <td class="example">File</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">userAgent</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user agent</td>
      <td class="example">Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">userSessionId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user session ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Collaboration sensor</td>
    </tr>
    <tr>
      <td class="field-name">userType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user type</td>
      <td class="example">
        <ul>
          <li>Regular</li>
          <li>Reserved</li>
          <li>Admin</li>
        </ul>
      </td>
      <td class="products">Collaboration sensor</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 26
- **Layer:** Email
- **Product:** Collaboration sensor

---
*Generated by XDR Common Schema Public Doc Generator V2*

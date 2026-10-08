---
layout: default
title: Okta - Identity
---

# Okta
**Layer:** Identity

This documentation provides detailed information about all fields available for Okta.

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
      <td class="field-name">clientBrowser</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The client browser</td>
      <td class="example">Chrome 119.0.0</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">clientOS</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The client OS</td>
      <td class="example">Windows</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The identity provider event ID</td>
      <td class="example">
        <ul>
          <li>1 - EVENT_SOURCE_AAD_SIGN_INS</li>
          <li>2 - EVENT_SOURCE_AAD_DIR_AUDIT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Active Directory (on-premises)</li>
          <li>Okta</li>
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
          <li>EVENT_SOURCE_AAD_SIGN_INS</li>
          <li>EVENT_SOURCE_AAD_DIR_AUDIT</li>
          <li>EVENT_SOURCE_OPA_WINDOWS_EVENT</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Active Directory (on-premises)</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the identity provider detected the event</td>
      <td class="example">1657781088000</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Active Directory (on-premises)</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">idpName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The identity provider</td>
      <td class="example">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Microsoft Active Directory</li>
          <li>google</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">ipAddress</td>
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
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">locationCity</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The city where the event happened</td>
      <td class="example">Singapore</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">locationCountry</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The country where the event happened</td>
      <td class="example">
        <ul>
          <li>US</li>
          <li>TW</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">locationLatitude</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The latitude of the event location</td>
      <td class="example">121.568</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">locationLongitude</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The longitude of the event location</td>
      <td class="example">121.568</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">locationState</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The state where the event happened</td>
      <td class="example">Central Singapore</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
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
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
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
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
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
          <li>Web Security</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Cloud App Security</li>
          <li>Zero Trust Secure Access - Private Access</li>
          <li>Container Security</li>
          <li>Okta</li>
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
          <li>Endpoint &amp; Workload Security</li>
          <li>Deep Discovery Inspector</li>
          <li>Virtual Network Sensor</li>
          <li>Deep Security</li>
          <li>Cloud App Security</li>
          <li>Apex One as a Service</li>
          <li>Email Security</li>
          <li>Cloud One Network Security</li>
          <li>TXOne EdgeOne</li>
          <li>Email Sensor</li>
          <li>File Security</li>
          <li>Agentless Vulnerability &amp; Threat Detection</li>
          <li>Zero Trust Secure Access - Internet Access</li>
          <li>Endpoint Sensor</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">signInCountries</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The countries from which a user signed in</td>
      <td class="example">
        <ul>
          <li>PH</li>
          <li>AU</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Cloud App Security</li>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">status</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in status result</td>
      <td class="example">
        <ul>
          <li>50126</li>
          <li>50155</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">statusReason</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in status</td>
      <td class="example">
        <ul>
          <li>Error validating credentials due to invalid username or password.</li>
          <li>Others.</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">tenantId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID Tenant ID of the organization</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user display name</td>
      <td class="example">Test User(RD-TW)</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">userId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Okta</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 22
- **Layer:** Identity
- **Product:** Okta

---
*Generated by XDR Common Schema Public Doc Generator V2*

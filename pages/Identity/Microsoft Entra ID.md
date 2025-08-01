---
layout: default
title: Microsoft Entra ID - Identity
---

# Microsoft Entra ID
**Layer:** Identity

This documentation provides detailed information about all fields available for Microsoft Entra ID.

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
      <td class="example">
        <ul>
          <li>Create User</li>
          <li>Add member to group</li>
          <li>Update application</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">application</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The displayed application name</td>
      <td class="example">app01</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">applicationId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID application ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">authenticationProtocol</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication protocol or grant type</td>
      <td class="example">
        <ul>
          <li>none</li>
          <li>oAuth2</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">autonomousSystemNumber</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The network Autonomous System Number</td>
      <td class="example">1023</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">clientApp</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The app that the client accessed</td>
      <td class="example">
        <ul>
          <li>browser</li>
          <li>Mobile Apps and Desktop clients</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">clientBrowser</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The client browser</td>
      <td class="example">Chrome 119.0.0</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">clientCredentialType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user client or service principal credential type</td>
      <td class="example">
        <ul>
          <li>none</li>
          <li>clientSecret</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">clientDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">EndpointName</td>
      <td class="description">The client display name</td>
      <td class="example">DESKTOP-TKOS222</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">clientId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique client device ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">clientOS</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The client OS</td>
      <td class="example">Windows</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">conditionalAccessStatus</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The conditional access policy status</td>
      <td class="example">
        <ul>
          <li>success</li>
          <li>failure</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">correlationId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The correlation id</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">crossTenantAccessType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cross-tenant access type</td>
      <td class="example">
        <ul>
          <li>none</li>
          <li>b2bCollaboration</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">eventAdditionalDetails</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The raw data string that contains additional information</td>
      <td class="example">[{&quot;key&quot;: &quot;&lt;example&gt;&quot;,&quot;value&quot;: &quot;Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7)&quot;}]</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">eventCategory</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The resource category targeted by the event</td>
      <td class="example">
        <ul>
          <li>UserManagement</li>
          <li>ApplicationManagement</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
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
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">eventName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The identity provider event name</td>
      <td class="example">
        <ul>
          <li>4624</li>
          <li>aad_signin</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">real</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the identity provider detected the event</td>
      <td class="example">1657781088000</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">idpId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal product code of the identity provider</td>
      <td class="example">
        <ul>
          <li>aad</li>
          <li>opa</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">idpIssuerName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The identity provider that issued the token</td>
      <td class="example">sts.microsoft.com</td>
      <td class="products">Microsoft Entra ID</td>
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
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">incomingTokentype</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication token types</td>
      <td class="example">
        <ul>
          <li>none</li>
          <li>primaryRefreshToken</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByAppDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The application display name</td>
      <td class="example">Microsoft Intune</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByAppId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The resource category targeted by the event</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByServicePrincipalId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique ID of the service principal</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByServicePrincipalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique ID of the service principal</td>
      <td class="example">
        <ul>
          <li>Microsoft Intune</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByUserDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user display name</td>
      <td class="example">Sample User</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByUserHomeTenantId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The tenant ID of the user</td>
      <td class="example"></td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByUserHomeTenantName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The tenant ID of the user</td>
      <td class="example"></td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByUserId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The unique ID of the user who initiated the event</td>
      <td class="example"></td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByUserIpAddress</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The client IP of the user</td>
      <td class="example">10.10.10.10</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">initiatedByUserPrincipalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The User Principal Name of the user</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">Microsoft Entra ID</td>
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
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">locationCity</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The city where the event happened</td>
      <td class="example">Singapore</td>
      <td class="products">Microsoft Entra ID</td>
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
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">locationLatitude</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The latitude of the event location</td>
      <td class="example">121.568</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">locationLongitude</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The longitude of the event location</td>
      <td class="example">121.568</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">locationState</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The state where the event happened</td>
      <td class="example">Central Singapore</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">logBatchId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The batch data retrieval process ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">loggedByService</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The service that initiated the event</td>
      <td class="example">Core Directory</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">operationType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The operation performed in the event</td>
      <td class="example">
        <ul>
          <li>Add</li>
          <li>Assign</li>
          <li>Update</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">orgId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The organization ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal product ID</td>
      <td class="example">
        <ul>
          <li>2200</li>
          <li>751</li>
          <li>533</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">principalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The User Principal Name</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">productCode</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal product code of the identity provider (aad=Microsoft Entra ID, opa=Microsoft Active Directory)</td>
      <td class="example">
        <ul>
          <li>aad</li>
          <li>opa</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>ALL</li>
          <li>Microsoft Entra ID</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">requestMethod</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in authentication method</td>
      <td class="example">[{&quot;authenticationStepDateTime&quot;: &quot;2023-11-28T03:44:05Z&quot;,&quot;authenticationMethod&quot;: &quot;Previously satisfied&quot;,&quot;authenticationMethodDetail&quot;: null,&quot;succeeded&quot; : true,&quot;authenticationStepResultDetail&quot;: &quot;MFA requirement satisfied by claim in the Token&quot;,&quot;authenticationStepRequirement&quot;: &quot;&quot;}]</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">result</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event result</td>
      <td class="example">
        <ul>
          <li>success</li>
          <li>failure</li>
          <li>timeout</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">resultReason</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cause of event failure or timeout</td>
      <td class="example">
        <ul>
          <li>success</li>
          <li>failure</li>
          <li>timeout</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">riskEventTypes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The associated sign-in risk event types</td>
      <td class="example">[&#x27;unlikelyTravel&#x27;, &#x27;anonymizedIPAddress&#x27;]</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">servicePrincipalId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The service principal ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">servicePrincipalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The service principal name</td>
      <td class="example">Service_01</td>
      <td class="products">Microsoft Entra ID</td>
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
          <li>Trend Micro Cloud App Security</li>
          <li>Microsoft Entra ID</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">signInEventTypes</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in event type</td>
      <td class="example">[&#x27;interactiveUser&#x27;, &#x27;nonInteractiveUser&#x27;]</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">signInIdentifierType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in ID type</td>
      <td class="example">
        <ul>
          <li>userPrincipalName</li>
          <li>phoneNumber</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
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
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">statusDetail</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The additional information about sign-in status</td>
      <td class="example">MFA requirement satisfied by claim in the token</td>
      <td class="products">Microsoft Entra ID</td>
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
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">targetResourceDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The target resource display name</td>
      <td class="example">Microsoft Graph</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">targetResourceId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The target resource ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">targetResources</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The targeted resource of the event</td>
      <td class="example"></td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">tenantId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID Tenant ID of the organization</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">userAgent</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user agent</td>
      <td class="example">
        <ul>
          <li>Microsoft.OData.Client/7.12.5</li>
          <li>Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">userDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user display name</td>
      <td class="example">Test User(RD-TW)</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">userId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">userSessionId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The session ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
    <tr>
      <td class="field-name">userType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The tenant user type</td>
      <td class="example">
        <ul>
          <li>member</li>
          <li>guest</li>
        </ul>
      </td>
      <td class="products">Microsoft Entra ID</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 67
- **Layer:** Identity
- **Product:** Microsoft Entra ID

---
*Generated by XDR Common Schema Public Doc Generator V2*

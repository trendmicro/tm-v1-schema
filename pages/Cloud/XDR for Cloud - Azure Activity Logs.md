---
layout: default
title: XDR for Cloud - Azure Activity Logs - Cloud
---

# XDR for Cloud - Azure Activity Logs
**Layer:** Cloud

This documentation provides detailed information about all fields available for XDR for Cloud - Azure Activity Logs.

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
      <td class="field-name">actionStatus</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The status of the event operation</td>
      <td class="example">MICROSOFT.KUSTO/CLUSTERS/READ</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">actionSubStatus</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The HTTP status or action status</td>
      <td class="example">
        <ul>
          <li>Running.</li>
          <li>Bad Request</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">authAction</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The operation performed on a scope</td>
      <td class="example">Microsoft.Kusto/Clusters/write</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">authPrincipalId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The entity ID</td>
      <td class="example">123abc2a6c314b0ab03a891259123abc</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">authPrincipalType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The entity type</td>
      <td class="example">Group</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">authRole</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Azure RBAC role</td>
      <td class="example">Owner</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">authRoleAssignmentScope</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The role assignment scope</td>
      <td class="example">/subscriptions/11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">authScope</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Azure resource or resource group</td>
      <td class="example">/subscriptions/11111111-1111-1111-1111-111111111111/resourcegroups/user-group/providers/Microsoft.Kusto/Clusters/user-test</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsAppId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Azure Application ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsAppIdAcr</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Azure application authentication method</td>
      <td class="example">2</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsAud</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The intended recipient of the authentication token</td>
      <td class="example">https://management.core.windows.net/</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsAuthnClassRef</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user authentication class reference</td>
      <td class="example">1</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsAuthnMethodsRef</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The list of authentication methods for a user</td>
      <td class="example">
        <ul>
          <li>[&#x27;pwd&#x27;]</li>
          <li>[&#x27;mfa&#x27;]</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsEmail</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The email address of the authenticated user</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsExp</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication token expiration time</td>
      <td class="example">1736745944</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsGroups</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID group claim</td>
      <td class="example">
        <ul>
          <li>[&#x27;00000000-0000-0000-0000-000000000000&#x27;]</li>
          <li>[&#x27;11111111-1111-1111-1111-111111111111&#x27;]</li>
          <li>[&#x27;22222222-2222-2222-2222-222222222222&#x27;]</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsIdentityProvider</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The IdP that authenticated the user</td>
      <td class="example">https://sts.windows.net/11111111-1111-1111-1111-111111111111/</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsIdType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID identity type</td>
      <td class="example">user</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsInitiatedBy</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user name or service principal</td>
      <td class="example">user_name</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsIpAddr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID user authentication request IP</td>
      <td class="example">10.10.10.10</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsIssuedAt</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication token timestamp (in Unix format)</td>
      <td class="example">1736731195</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsIssuer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication token issuer</td>
      <td class="example">https://sts.windows.net/11111111-1111-1111-1111-111111111111/</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user name</td>
      <td class="example">sample_email@trendmicro.com</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsNameId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authenticated user Name ID</td>
      <td class="example">aaaaaaaaaaBBBBBBBBBB11111111112222222222333</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsNbf</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time an authentication token becomes valid</td>
      <td class="example">1736731195</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsObjectId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft authenticated user Object ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsScope</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The granted access scope to the application</td>
      <td class="example">user_impersonation</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">claimsTenantGuid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID Tenant ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">cloudResourceId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cloud resource ID</td>
      <td class="example">/SUBSCRIPTIONS/11111111-1111-1111-1111-111111111111/RESOURCEGROUPS/GROUP/PROVIDERS/MICROSOFT.KUSTO/CLUSTERS/TEST</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">correlationId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The correlation ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">eventCategory</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event category used in LookupEvents calls</td>
      <td class="example">Administrative</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">eventId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event ID</td>
      <td class="example">1500001</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent or product detected the event</td>
      <td class="example">1656324260000</td>
      <td class="products">
        <ul>
          <li>XDR for Cloud - Azure Activity Logs</li>
          <li>ALL</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">eventVersion</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The log event format version</td>
      <td class="example">6.2024.42.16+5d1e2c2.release_2024w42</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">logLevel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The event severity level</td>
      <td class="example">Information</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">operationType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The operation performed in the event</td>
      <td class="example">MICROSOFT.KUSTO/CLUSTERS/READ</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The product name</td>
      <td class="example">Azure Activity Log</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">productCode</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal product code</td>
      <td class="example">aml</td>
      <td class="products">
        <ul>
          <li>XDR for Cloud - Azure Activity Logs</li>
          <li>ALL</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">regionId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cloud asset region</td>
      <td class="example">Japan East</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestAccess</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The access action of the request</td>
      <td class="example">Allow</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestAllowBlobPublicAccess</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether public access is allowed for blobs in response to a request</td>
      <td class="example">False</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestAllowSharedKeyAccess</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether shared key access is allowed in response to a request</td>
      <td class="example">False</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestCrossTenantReplication</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether cross-tenant data replication is allowed in response to a request</td>
      <td class="example">False</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestDirection</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The traffic direction of the request</td>
      <td class="example">Inbound</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestEnabled</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the request is enabled</td>
      <td class="example">True</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestPermissionsActions</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The list of request permissions actions</td>
      <td class="example">[&#x27;*&#x27;]</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestPrincipalId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The request principal GUID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestPrincipalType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The request principal type</td>
      <td class="example">User</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestPublicNetworkAccess</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The resource public network access setting of the request</td>
      <td class="example">Enabled</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestRoleDefinitionId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cloud resource ID of the request</td>
      <td class="example">/SUBSCRIPTIONS/11111111-1111-1111-1111-111111111111/RESOURCEGROUPS/GROUP/PROVIDERS/MICROSOFT.KUSTO/CLUSTERS/TEST</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">requestSourceAddressPrefix</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source IP prefix of the request</td>
      <td class="example">10.10.10.10/16</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">responseAccess</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The access action of the response</td>
      <td class="example">
        <ul>
          <li>Allow</li>
          <li>Block</li>
        </ul>
      </td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">responseAllowBlobPublicAccess</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether public access is allowed for blobs in response to a request</td>
      <td class="example">True</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">responseAllowSharedKeyAccess</td>
      <td class="type">bool</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether shared key access is allowed in response to a request</td>
      <td class="example">True</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">responseDirection</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The traffic direction of the response</td>
      <td class="example">Inbound</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">responsePublicNetworkAccess</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The resource public network access setting in response to a request</td>
      <td class="example">Disabled</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">responseSourceAddressPrefix</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The source IP prefix of the response</td>
      <td class="example">10.10.10.10/16</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
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
      <td class="description">The source IP address</td>
      <td class="example">[&#x27;10.10.10.10&#x27;]</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">tenantId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Microsoft Entra ID Tenant ID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">uuid</td>
      <td class="type">guid</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique key of the log entry</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">
        <ul>
          <li>XDR for Cloud - Azure Activity Logs</li>
          <li>ALL</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">vendor</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The device vendor</td>
      <td class="example">Microsoft</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">vendorParsed</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The normalized event log (JSON format)</td>
      <td class="example">{&quot;RoleLocation&quot;: &quot;Japan East&quot;, &quot;Stamp&quot;: &quot;FDWorker&quot;, &quot;ReleaseVersion&quot;: &quot;6.2024.42.16+5d1e2c2.release_2024w42&quot;, &quot;time&quot;: &quot;2025-01-13T01:27:41.8080097Z&quot;}</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
    <tr>
      <td class="field-name">vendorRaw</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The original event log string</td>
      <td class="example">{&quot;RoleLocation&quot;: &quot;Japan East&quot;, &quot;Stamp&quot;: &quot;FDWorker&quot;, &quot;ReleaseVersion&quot;: &quot;6.2024.42.16+5d1e2c2.release_2024w42&quot;, &quot;time&quot;: &quot;2025-01-13T01:27:41.8080097Z&quot;}</td>
      <td class="products">XDR for Cloud - Azure Activity Logs</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 63
- **Layer:** Cloud
- **Product:** XDR for Cloud - Azure Activity Logs

---
*Generated by XDR Common Schema Public Doc Generator V2*

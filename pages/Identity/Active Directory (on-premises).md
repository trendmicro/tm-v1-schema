---
layout: default
title: Active Directory (on-premises) - Identity
---

# Active Directory (on-premises)
**Layer:** Identity

This documentation provides detailed information about all fields available for Active Directory (on-premises).

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
      <td class="field-name">channel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event channel</td>
      <td class="example">
        <ul>
          <li>Security</li>
          <li>Microsoft-Windows-WMI-Activity/Trace</li>
          <li>Microsoft-Windows-TaskScheduler/Operational</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">correlationData</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The data for correlation</td>
      <td class="example">-</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">endpointGuid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">EndpointID</td>
      <td class="description">The endpoint host GUID</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">endpointHostName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">EndpointName</td>
      <td class="description">The endpoint hostname</td>
      <td class="example">
        <ul>
          <li>PHILIPSIBE09</li>
          <li>WHAM6WK8XG2</li>
          <li>MacBook-Pro-del-Meno</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">endpointIp</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The endpoint IP</td>
      <td class="example">
        <ul>
          <li>10.10.10.10</li>
          <li>::1</li>
          <li>fe80::1</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">endpointMacAddress</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The host MAC address</td>
      <td class="example">
        <ul>
          <li>0-0-0-0-0-0-0-e0</li>
          <li>00:00:00:ff:ff:ff</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataAccessList</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The list of requested access rights</td>
      <td class="example">
        <ul>
          <li>%%4416</li>
          <li>%%4417</li>
          <li>%%4418</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataAccessMask</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The hexadecimal value of the requested or used permissions during an access attempt</td>
      <td class="example">
        <ul>
          <li>16</li>
          <li>2147483648</li>
          <li>1048576</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataActionName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The action performed</td>
      <td class="example">
        <ul>
          <li>Language Components Installer</li>
          <li>Group Policy Background Processing</li>
          <li>C:\Program Files (x86)\Microsoft\EdgeUpdate\MicrosoftEdgeUpdate.exe</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataAdditionalInfo</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The additional information about the event</td>
      <td class="example">Restrictions</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataAttributeLDAPDisplayName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The LDAP display name of the attribute that was accessed</td>
      <td class="example">
        <ul>
          <li>sAMAccountName</li>
          <li>memberOf</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataAuthenticationPackageName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication package name of the Windows event data</td>
      <td class="example">
        <ul>
          <li>NTLM</li>
          <li>Negotiate</li>
          <li>MICROSOFT_AUTHENTICATION_PACKAGE_V1_0</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataCertIssuerName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the Certification Authority that issued the TGT certificate</td>
      <td class="example">CN=contoso-DC-CA, DC=contoso, DC=local</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataCertSerialNumber</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The serial number of the certificate</td>
      <td class="example">1D0000000120F1D8A3094A82760000000001</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataCertThumbprint</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The thumbprint of the certificate</td>
      <td class="example">1A2B3C4D5E6F7A8B9C0D1E2F3A4B5C6D7E8F9A0B</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataConsumer</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The recipient of the reported event</td>
      <td class="example">
        <ul>
          <li>HealthDriverEventConsumer=&quot;Health Event Consumer&quot;</li>
          <li>MemoryEventConsumer=&quot;Memory Event Consumer&quot;</li>
          <li>SysEventConsumer=&quot;System Event Consumer&quot;</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataElevatedToken</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">Whether the session is elevated and has administrator privileges</td>
      <td class="example">
        <ul>
          <li>%%1842</li>
          <li>%%1843</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataFullyQualifiedAssemblyName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The fully qualified .NET assembly name</td>
      <td class="example">
        <ul>
          <li>System.Runtime, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a</li>
          <li>System.Xml, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089</li>
          <li>System.Diagnostics.Process, Version=8.0.0.0, Culture=neutral, PublicKeyToken=b03f5f7f11d50a3a</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataImpersonationLevel</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in session impersonation level</td>
      <td class="example">
        <ul>
          <li>%%1830</li>
          <li>%%1832</li>
          <li>%%1833</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataIpAddress</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">The IP address for Windows events</td>
      <td class="example">
        <ul>
          <li>-</li>
          <li>10.10.10.10</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataJobOwner</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The name of the account that initiated the event</td>
      <td class="example">
        <ul>
          <li>BEI\holdej</li>
          <li>NT AUTHORITY\SYSTEM</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataLogonProcessName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event sign-in process name</td>
      <td class="example">
        <ul>
          <li>NtLmSsp </li>
          <li>Advapi  </li>
          <li>Advapi</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataLogonType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The sign-in type of Windows Event 4624 (successful sign-in attempt)</td>
      <td class="example">
        <ul>
          <li>3</li>
          <li>5</li>
          <li>2</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataMemberName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The distinguished name of the account that was added to the group</td>
      <td class="example">CN=User1,CN=Users,DC=contoso,DC=local</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataMemberSid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier (SID) of the account that was added to the group</td>
      <td class="example">S-1-5-21-3623811015-3361044348-30300820-1013</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataModuleILPath</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The CIL image path of the module or the dynamic module name</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\Cymulate\Agent\System.Threading.dll</li>
          <li>C:\windows\system32\tzsync.exe</li>
          <li>C:\Program.exe</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectClass</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The class of the object that was accessed</td>
      <td class="example">
        <ul>
          <li>user</li>
          <li>group</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectDN</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The distinguished name of the object that was accessed</td>
      <td class="example">CN=User1,CN=Users,DC=contoso,DC=local</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectGUID</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The unique identifier of the object that was accessed</td>
      <td class="example">{11111111-1111-1111-1111-111111111111}</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The identifying information about the object for which access was requested</td>
      <td class="example">
        <ul>
          <li>\Device\HarddiskVolume2\Windows\System32\lsass.exe</li>
          <li>C:\Windows\System32\osk.exe</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectServer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the Windows sub-system calling the routine</td>
      <td class="example">
        <ul>
          <li>Security</li>
          <li>LSA</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataObjectType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The object type</td>
      <td class="example">
        <ul>
          <li>Process</li>
          <li>File</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataOperation</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">Windows event 11</td>
      <td class="example">
        <ul>
          <li>Start IWbemServices::ExecQuery - root\ccm : select * from SMS_Authority</li>
          <li>Start IWbemServices::ExecQuery - root\cimv2 : select * from win32_process</li>
          <li>Start IWbemServices::ExecQuery - root\ccm : SELECT * FROM SMS_Authority</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataOperationType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The type of operation performed on the object</td>
      <td class="example">
        <ul>
          <li>Object Access</li>
          <li>Object Open</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataPath</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The path of the Windows event data</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\Common Files\Microsoft Shared\ClickToRun\officesvcmgr.exe</li>
          <li>taskhostw.exe</li>
          <li>gpupdate.exe</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataProcessPath</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The process path that initiated the event</td>
      <td class="example">
        <ul>
          <li>C:\Program Files\Microsoft Office\Office15\OUTLOOK.EXE</li>
          <li>C:\Program Files (x86)\Common Files\Adobe\ARM\1.0\AdobeARM.exe</li>
          <li>C:\Program Files\Microsoft Office\root\Office16\OUTLOOK.EXE</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataProperties</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The properties of the object</td>
      <td class="example">%%8278</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataProviderName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the Windows event data provider</td>
      <td class="example">
        <ul>
          <li>SmsClientMethodProvider</li>
          <li>MS_NT_EVENTLOG_PROVIDER</li>
          <li>RegProv</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataProviderPath</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The file path of the Windows event data provider</td>
      <td class="example">
        <ul>
          <li>%systemroot%\system32\wbem\ntevt.dll</li>
          <li>%systemroot%\system32\wbem\stdprov.dll</li>
          <li>C:\WINDOWS\CCM\smsclient.dll</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataScriptBlockText</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">Windows event 4104, Creating Scriptblock text</td>
      <td class="example">
        <ul>
          <li>$global:?</li>
          <li>0</li>
          <li>{ Set-StrictMode -Version 1; $_.PSMessageDetails }</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataServiceAccount</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The service account</td>
      <td class="example">
        <ul>
          <li>LocalSystem</li>
          <li>NT AUTHORITY\SYSTEM</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataServiceFileName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The full file path of the service executable file</td>
      <td class="example">
        <ul>
          <li>%SystemRoot%\PSEXESVC.exe</li>
          <li>C:\Windows\System32\svchost.exe -k WinSysRestoreGroup</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataServiceName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The service name</td>
      <td class="example">
        <ul>
          <li>PSEXESVC</li>
          <li>WinResSvc</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataServiceSid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier (SID) of the service</td>
      <td class="example">S-1-5-21-3623811015-3361044348-30300820-1013</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataServiceStartType</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The service start type</td>
      <td class="example">2</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataServiceType</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The service type</td>
      <td class="example">
        <ul>
          <li>0x10</li>
          <li>0x20</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataStatus</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event data status</td>
      <td class="example">
        <ul>
          <li>0xc000006d</li>
          <li>-1073741715</li>
          <li>0xc000006e</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubjectDomainName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">DomainName</td>
      <td class="description">The domain or computer name of the account</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>WORKGROUP</li>
          <li>CONTOSO</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubjectLogonId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The account sign-in ID</td>
      <td class="example">
        <ul>
          <li>0x3e7</li>
          <li>0x3e4</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubjectUserName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The account name</td>
      <td class="example">
        <ul>
          <li>dadmin</li>
          <li>Alex</li>
          <li>london$</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubjectUserSid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier (SID) of the account</td>
      <td class="example">
        <ul>
          <li>S-1-5-18</li>
          <li>S-1-5-21-3623811015-3361044348-30300820-1013</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataSubStatus</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event data sub-status</td>
      <td class="example">
        <ul>
          <li>0xc0000064</li>
          <li>0xc000006a</li>
          <li>-1073741724</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetDomainName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The target sign-in account domain or computer name</td>
      <td class="example">
        <ul>
          <li>NT AUTHORITY</li>
          <li>Builtin</li>
          <li>SHOCKWAVE</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetLogonId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The hexadecimal value to correlate this event with events that contain the same sign-in ID</td>
      <td class="example">0x3e7</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The service, application, or network resource name</td>
      <td class="example">
        <ul>
          <li>Microsoft_RssPlatform_*</li>
          <li>WindowsLive:target=virtualapp/didlogical</li>
          <li>MicrosoftOffice*</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetSid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier (SID) of the target account</td>
      <td class="example">S-1-5-21-3623811015-3361044348-30300820-1013</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetUserName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user name of the Windows event data target</td>
      <td class="example">
        <ul>
          <li>Auditor</li>
          <li>Administrators</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTargetUserSid</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The security identifier (SID) of the account for which sign-in was requested</td>
      <td class="example">S-1-5-21-3623811015-3361044348-30300820-1013</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTaskName</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The task name logged by the Windows event</td>
      <td class="example">
        <ul>
          <li>\Microsoft\Windows\LanguageComponentsInstaller\Installation</li>
          <li>\Microsoft\Office\Office Serviceability Manager</li>
          <li>\MicrosoftEdgeUpdateTaskMachineUA</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTicketEncryptionType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The cryptographic suite used for the Kerberos TGS</td>
      <td class="example">
        <ul>
          <li>0x12</li>
          <li>0x17</li>
          <li>0x18</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataTicketOptions</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The authentication request Kerberos ticket behavior and permissions flags</td>
      <td class="example">
        <ul>
          <li>0x40810000</li>
          <li>0x40810010</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataUserContext</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The user context of the Windows event data</td>
      <td class="example">
        <ul>
          <li>MP\MPBSA179345$</li>
          <li>MP\MPBSASPU179370$</li>
          <li>MP\MPBSA4025625$</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataUserPrincipalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The user account UPN</td>
      <td class="example">user@contoso.local</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataWorkstation</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">EndpointName</td>
      <td class="description">The computer name from which the sign-in request was received</td>
      <td class="example">WORKSTATION01</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">eventDataWorkstationName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the computer used in the sign-in attempt</td>
      <td class="example">
        <ul>
          <li>WIN-GG82ULGC9GO</li>
          <li>DESKTOP-123ABC</li>
          <li>CLIENT01</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
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
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">instanceId</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The virtual machine instance ID on the cloud platform</td>
      <td class="example">i-01234567890abcdef</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">logonUser</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">UserAccount</td>
      <td class="description">The sign-in user name</td>
      <td class="example">
        <ul>
          <li>root</li>
          <li>SISTEMA</li>
          <li>oracle</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">netBiosDomainName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">DomainName</td>
      <td class="description">The NetBIOS domain name</td>
      <td class="example">TREND</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">osDescription</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The OS version</td>
      <td class="example">
        <ul>
          <li>Windows 10 (64 bit)</li>
          <li>Windows 10 Pro (64 bit) build 19044</li>
          <li>Amazon Linux 2 (64 bit) (5.4.188-104.359.amzn2.x86_64)</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">osName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The host OS name</td>
      <td class="example">
        <ul>
          <li>Windows</li>
          <li>Linux</li>
          <li>macOS</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">osType</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The host OS type</td>
      <td class="example">
        <ul>
          <li>0x00000030</li>
          <li>4</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">osVer</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The host OS version</td>
      <td class="example">
        <ul>
          <li>Amazon Linux 2</li>
          <li>10.0.19044</li>
          <li>10.0.19042</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">pname</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The internal product ID (Deprecated, use productCode)</td>
      <td class="example">
        <ul>
          <li>2200</li>
          <li>751</li>
          <li>533</li>
        </ul>
      </td>
      <td class="products">
        <ul>
          <li>Microsoft Entra ID</li>
          <li>Active Directory (on-premises)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">pplat</td>
      <td class="type">int</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The product platform</td>
      <td class="example">
        <ul>
          <li>5889</li>
          <li>9217</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processCmd</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The command line entry of the subject process</td>
      <td class="example">
        <ul>
          <li>C:\Windows\system32\lsass.exe</li>
          <li>C:\WINDOWS\system32\lsass.exe</li>
          <li>nimbus(processes)</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processFileHashSha1</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileSHA1</td>
      <td class="description">The SHA-1 hash of the subject process image</td>
      <td class="example">
        <ul>
          <li>1f912d4bec338ef10b7c9f19976286f8acc4eb97</li>
          <li>ded3833f145989fd86c1f4811b61497298ebc7fd</li>
          <li>9ad737cbd8bbdddc96726156dbd3bc03936bf02f</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processFileOriginalName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">FileName</td>
      <td class="description">The original file name of the process image</td>
      <td class="example">
        <ul>
          <li>Taskmgr.exe</li>
          <li>WINLOGON.EXE</li>
          <li>svchost.exe</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processFilePath</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">
        <ul>
          <li>ProcessFullPath</li>
          <li>ProcessName</li>
          <li>FileFullPath</li>
          <li>FileName</li>
        </ul>
      </td>
      <td class="description">The file path of the subject process</td>
      <td class="example">
        <ul>
          <li>/usr/bin/bash</li>
          <li>c:\windows\system32\svchost.exe</li>
          <li>c:\windows\system32\lsass.exe</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processFileSize</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The file size of the process file</td>
      <td class="example">
        <ul>
          <li>59952</li>
          <li>59456</li>
          <li>47024</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processHashId</td>
      <td class="type">long</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The subject process FNV</td>
      <td class="example">
        <ul>
          <li>7114696589795796819</li>
          <li>1307755369266815004</li>
          <li>-5015325378148567246</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
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
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processPid</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The subject process PID</td>
      <td class="example">
        <ul>
          <li>4</li>
          <li>1</li>
          <li>784</li>
          <li>792</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processSigner</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The process file signer</td>
      <td class="example">
        <ul>
          <li>Microsoft Windows</li>
          <li>Microsoft Windows Publisher</li>
          <li>Microsoft Corporation</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processSignerValid</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The validity of the process signer</td>
      <td class="example">
        <ul>
          <li>1</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">processStackTrace</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The process stack trace of the telemetry event</td>
      <td class="example">C:\Windows\System32\ntdll.dll?NtCreateUserProcess|ZwCreateUserProcess, C:\Windows\System32\kernelbase.dll!CreateProcessInternalW</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">providerGUID</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The GUID of the Windows event provider</td>
      <td class="example">{11111111-1111-1111-1111-111111111111}</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">providerName</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The name of the Windows event provider</td>
      <td class="example">
        <ul>
          <li>Microsoft-Windows-Security-Auditing</li>
          <li>Microsoft-Windows-WMI-Activity</li>
          <li>Microsoft-Windows-TaskScheduler</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
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
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">rawDataStr</td>
      <td class="type">string</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows event raw contents</td>
      <td class="example">
        <ul>
          <li>{
   &quot;EventData&quot; : {
      &quot;LogonType&quot; : &quot;&quot;,
      &quot;TargetDomainName&quot; : &quot;&quot;,
      &quot;TargetLogonId&quot; : &quot;&quot;,
      &quot;TargetUserName&quot; : &quot;&quot;,
      &quot;TargetUserSid&quot; : &quot;&quot;
   }
}
</li>
          <li>{
   &quot;EventData&quot; : {
      &quot;LogonType&quot; : &quot;10&quot;,
      &quot;TargetDomainName&quot; : &quot;AFASADV&quot;,
      &quot;TargetLogonId&quot; : &quot;14941011731&quot;,
      &quot;TargetUserName&quot; : &quot;administrator&quot;,
      &quot;TargetUserSid&quot; : &quot;S-1-5-21-1507008304-2416677881-2121376573-500&quot;
   }
}
</li>
          <li>{
   &quot;EventData&quot; : {
      &quot;LogonType&quot; : &quot;10&quot;,
      &quot;TargetDomainName&quot; : &quot;AIS&quot;,
      &quot;TargetLogonId&quot; : &quot;216921070&quot;,
      &quot;TargetUserName&quot; : &quot;MWoodr01&quot;,
      &quot;TargetUserSid&quot; : &quot;S-1-5-21-1873864278-1756520048-3043165120-15057&quot;
   }
}
</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">rt</td>
      <td class="type">string</td>
      <td class="searchable">false</td>
      <td class="general-field">-</td>
      <td class="description">The event time</td>
      <td class="example">1657781088000</td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">userDomain</td>
      <td class="type">dynamic</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The user domain name</td>
      <td class="example">
        <ul>
          <li>CORP</li>
          <li>AUTORIDADE NT</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
    <tr>
      <td class="field-name">winEventId</td>
      <td class="type">int</td>
      <td class="searchable">true</td>
      <td class="general-field">-</td>
      <td class="description">The Windows Event ID</td>
      <td class="example">
        <ul>
          <li>4662</li>
          <li>4624</li>
          <li>4625</li>
        </ul>
      </td>
      <td class="products">Active Directory (on-premises)</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 95
- **Layer:** Identity
- **Product:** Active Directory (on-premises)

---
*Generated by XDR Common Schema Public Doc Generator V2*

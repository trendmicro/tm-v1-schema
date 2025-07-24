---
layout: default
title: Trend Micro Apex One On-Premises - Endpoint
---

# Trend Micro Apex One On-Premises
**Layer:** Endpoint

This documentation provides detailed information about all fields available for Trend Micro Apex One On-Premises.

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
      <td class="field-name">detectionMeta</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The descriptions of the detected techniques</td>
      <td class="example">[&#x27;T1204 some description about this technique&#x27;, &#x27;T1573.001_AES another description about this technique&#x27;]</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">detectionNames</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The rules that triggered the event</td>
      <td class="example">[&#x27;HS_EMOTET.SMAA&#x27;, &#x27;HM_AVEDOWN.SMZTIG-A&#x27;, &#x27;HE_DOCQRPHISH.SM&#x27;]</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">objectSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of object process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">parentSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of parent process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsAdhoc</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature adhoc flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsLibValid</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature library validation flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">processSignerFlagsRuntime</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The list of process signature runtime flags</td>
      <td class="example">-</td>
      <td class="products">
        <ul>
          <li>Endpoint Sensor</li>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineFileId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The unique identifier of the quarantined object</td>
      <td class="example">ASLUMVS0.4FC</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineFilePath</td>
      <td class="type">string</td>
      <td class="general-field">FileFullPath</td>
      <td class="description">The file path of the quarantined object</td>
      <td class="example">C:\ProgramData\Trend Micro\AMSP\quarantine\ASLUMVS0.4FC</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td class="field-name">quarantineFileSha256</td>
      <td class="type">string</td>
      <td class="general-field">FileSHA2</td>
      <td class="description">The SHA-256 of the quarantined object</td>
      <td class="example">84B2FA19B05EA88D6E785B4ADB528120485AA3F72F3E5E114DE6D3696B0D151F</td>
      <td class="products">
        <ul>
          <li>Trend Micro Apex One as a Service</li>
          <li>Trend Micro Apex One On-Premises</li>
          <li>Trend Cloud One - Endpoint &amp; Workload Security</li>
          <li>Trend Micro Deep Security</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 14
- **Layer:** Endpoint
- **Product:** Trend Micro Apex One On-Premises

---
*Generated by XDR Common Schema Public Doc Generator V2*

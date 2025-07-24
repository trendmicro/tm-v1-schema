---
layout: default
title: Trend Cloud One - AWS CloudTrail Integration - Others
---

# Trend Cloud One - AWS CloudTrail Integration
**Layer:** Others

This documentation provides detailed information about all fields available for Trend Cloud One - AWS CloudTrail Integration.

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
      <td class="field-name">additionalEventData</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The additional data about the event that was not part of the request</td>
      <td class="example">{&quot;SignatureVersion&quot;:&quot;SigV4&quot;,&quot;CipherSuite&quot;:&quot;ECDHE-RSA-AES128-GCM-SHA256&quot;}</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">apiVersion</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">API version associated with the AwsApiCall eventType value</td>
      <td class="example">2012-08-10</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">awsRegion</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">AWS region that the request was made to</td>
      <td class="example">
        <ul>
          <li>us-east-1</li>
          <li>us-east-2</li>
          <li>us-west-1</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">errorCode</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">AWS service error code</td>
      <td class="example">
        <ul>
          <li>ThrottlingException</li>
          <li>InvalidParameterValueException</li>
          <li>NoSuchLifecycleConfiguration</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">errorMessage</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Description of the error</td>
      <td class="example">
        <ul>
          <li>The specified bucket does not have a website configuration</li>
          <li>An unknown error occurred</li>
          <li>The lifecycle configuration does not exist</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventCategory</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Event category used in LookupEvents calls</td>
      <td class="example">
        <ul>
          <li>Management</li>
          <li>Data</li>
          <li>Insight</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">GUID generated by AWS CloudTrail to identify events</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventName</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The name of the log event</td>
      <td class="example">
        <ul>
          <li>PutObject</li>
          <li>GetObject</li>
          <li>DescribeTable</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventSource</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The AWS service the request was made to</td>
      <td class="example">
        <ul>
          <li>s3.amazonaws.com</li>
          <li>dynamodb.amazonaws.com</li>
          <li>xray.amazonaws.com</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventTime</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">The time the agent or product detected the event</td>
      <td class="example">2022-07-06T22:28:06+00:00</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventType</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Type of event that generated the event record</td>
      <td class="example">
        <ul>
          <li>AwsApiCall</li>
          <li>AwsServiceEvent</li>
          <li>AwsConsoleAction</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">eventVersion</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Version of the log event format</td>
      <td class="example">1.08</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">readOnly</td>
      <td class="type">bool</td>
      <td class="general-field">-</td>
      <td class="description">Whether the operation is read-only</td>
      <td class="example">
        <ul>
          <li>True</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">recipientAccountId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Account ID that received the event</td>
      <td class="example">123456789012</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">requestID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">Value that identifies the request (The service being called generates this value)</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">requestParameters</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The parameters, if any, that were sent with the request (Parameters are documented in the API reference docs for the appropriate AWS service)</td>
      <td class="example">{&quot;durationSeconds&quot;: 3600, &quot;roleSessionName&quot;:&quot;BackplaneAssumeRoleSession&quot;}</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">resources</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">List of resources accessed in the event</td>
      <td class="example">[{&quot;type&quot;:&quot;AWS::S3::Object&quot;,&quot;ARN&quot;:&quot;arn:aws:s3:::your-bucket/file.txt&quot;}]</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">responseElements</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">Response elements for actions that made changes (create, update, or delete actions)</td>
      <td class="example">{&quot;user&quot;:{&quot;createDate&quot;:&quot;Mar 24, 2014 9:11:59 PM&quot;,&quot;userName&quot;:&quot;Bob&quot;,&quot;arn&quot;:&quot;arn:aws:iam::123456789012:user/Bob&quot;,&quot;path&quot;:&quot;/&quot;,&quot;userId&quot;:&quot;EXAMPLEUSERID&quot;}}</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">serviceEventDetails</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">The service event (including what triggered the event and the result)</td>
      <td class="example">{&quot;lifecycleEventPolicy&quot;:{&quot;policyVersion&quot;:1,&quot;policyId&quot;:&quot;11111111-1111-1111-1111-111111111111&quot;}}</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">sharedEventID</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">GUID generated by AWS CloudTrail to uniquely identify CloudTrail events (From the same AWS action that is sent to different AWS accounts)</td>
      <td class="example">11111111-1111-1111-1111-111111111111</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">sourceIPAddress</td>
      <td class="type">string</td>
      <td class="general-field">
        <ul>
          <li>IPv4</li>
          <li>IPv6</li>
        </ul>
      </td>
      <td class="description">IP address the request was made from (For actions that originate from the service console, the address reported is for the underlying customer resource, not the console web server. For services in AWS, only the DNS name is displayed.)</td>
      <td class="example">
        <ul>
          <li>10.10.10.10</li>
          <li>apigateway.amazonaws.com</li>
          <li>config.amazonaws.com</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">userAgent</td>
      <td class="type">string</td>
      <td class="general-field">CLICommand</td>
      <td class="description">The user agent or the agent through which the request was made</td>
      <td class="example">
        <ul>
          <li>signin.amazonaws.com</li>
          <li>console.amazonaws.com</li>
          <li>aws-cli/1.3.23 Python/2.7.6 Linux/2.6.18-164.el5</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">userIdentity</td>
      <td class="type">dynamic</td>
      <td class="general-field">-</td>
      <td class="description">Information about the user that made a request</td>
      <td class="example">
        <ul>
          <li>{&quot;type&quot;:&quot;AWSService&quot;,&quot;invokedBy&quot;:&quot;apigateway.amazonaws.com&quot;}</li>
          <li>{&quot;type&quot;:&quot;AWSService&quot;,&quot;invokedBy&quot;:&quot;lambda.amazonaws.com&quot;}</li>
        </ul>
      </td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
    <tr>
      <td class="field-name">vpcEndpointId</td>
      <td class="type">string</td>
      <td class="general-field">-</td>
      <td class="description">VPC endpoint in which requests were made from a VPC to another AWS service (Such as Amazon S3)</td>
      <td class="example">vpce-00000000000000000</td>
      <td class="products">Trend Cloud One - AWS CloudTrail Integration</td>
    </tr>
  </tbody>
</table>
</div>

## Field Statistics
- **Total Fields:** 24
- **Layer:** Others
- **Product:** Trend Cloud One - AWS CloudTrail Integration

---
*Generated by XDR Common Schema Public Doc Generator V2*

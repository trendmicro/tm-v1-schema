# Preview
- Please note that these documents are still in preview stage and we do not guarantee any backward compatibility.

# Background
- These documents provide Trend Micro Vision One log schema details.

# User scenario
- Currently, these documents only support the following use cases:
    1. Support Trend Micro Vision One Search app UI usage

# Property Description
| Property       | Description                                    |
|----------------|------------------------------------------------|
| Name           | Field name of log                              |
| ProductCode    | Products which sends data to this field        |
| Description_EN | Description of this field                      |
| Sample         | Sample value of these field                    |
| DL_Searchable  | If log is searchable by this field             |
| DL_Type        | Data type of this field                        |
| DL_CommonKey   | The corresponding field name in General Search |

# ProductCode Mapping
| Code | Product                                                   |
|------|-----------------------------------------------------------|
| ALL  | All products                                              |
| aad  | Microsoft Entra ID                                        |
| ams  | Trend Vision One Mobile Security                          |
| opa  | Microsoft Active Directory                                |
| pao  | Trend Micro Apex One                                      |
| pdi  | Trend Micro Deep Discovery Inspector                      |
| pds  | Trend Micro Deep Security                                 |
| ptn  | TXOne EdgeOne (on-premises)                               |
| ptp  | TippingPoint Security Management System                   |
| pts  | TXOne Stellar (on-premises)                               |
| qpf  | Palo Alto Networks Next-Generation Firewalls              |
| sao  | Trend Micro Apex One as a Service                         |
| sca  | Trend Micro Cloud App Security                            |
| scs  | Trend Cloud One - Container Security                      |
| sct  | Trend Cloud One - AWS CloudTrail                          |
| sds  | Trend Cloud One - Endpoint & Workload Security            |
| sem  | Trend Micro Email Security                                |
| sfc  | Trend Cloud One – File Storage Security                   |
| sfs  | Trend Vision One File Security                            |
| sig  | Trend Vision One Zero Trust Secure Access Internet Access |
| sna  | XDR add-on: Deep Discovery Inspector                      |
| sss  | Trend Cloud One - Cloud Sentry                            |
| stp  | Trend Cloud One - Network Security                        |
| sws  | Trend Micro Web Security                                  |
| szn  | Trend Vision One Zero Trust Secure Access Private Access  |
| vpc  | XDR for Cloud - AWS VPC Flow Logs                         |
| xca  | Collaboration Sensor                                      |
| xes  | XDR Endpoint Sensor                                       |
| xms  | Email Sensor                                              |
| xns  | Virtual Network Sensor                                    |

# EventId, EventSubId Mapping
## Endpoint Activity Data
### eventId
| eventId | Data Field Mapping         |
| ------- | -------------------------- |
| 1       | TELEMETRY_PROCESS          |
| 2       | TELEMETRY_FILE             |
| 3       | TELEMETRY_CONNECTION       |
| 4       | TELEMETRY_DNS              |
| 5       | TELEMETRY_REGISTRY         |
| 6       | TELEMETRY_ACCOUNT          |
| 7       | TELEMETRY_INTERNET         |
| 8       | TELEMETRY_MODIFIED_PROCESS |
| 9       | TELEMETRY_WINDOWS_HOOK     |
| 10      | TELEMETRY_WINDOWS_EVENT    |
| 11      | TELEMETRY_AMSI             |
| 12      | TELEMETRY_WMI              |
| 13      | TELEMETRY_MEMORY           |
| 14      | TELEMETRY_BM               |

### eventSubId
| eventSubId | Data Field Mapping                             |
| ---------- | ---------------------------------------------- |
| 1          | TELEMETRY_PROCESS_OPEN                         |
| 2          | TELEMETRY_PROCESS_CREATE                       |
| 3          | TELEMETRY_PROCESS_TERMINATE                    |
| 4          | TELEMETRY_PROCESS_LOAD_IMAGE                   |
| 5          | TELEMETRY_PROCESS_EXECUTE                      |
| 6          | TELEMETRY_PROCESS_CONNECT                      |
| 7          | TELEMETRY_PROCESS_TRACME                       |
| 101        | TELEMETRY_FILE_CREATE                          |
| 102        | TELEMETRY_FILE_OPEN                            |
| 103        | TELEMETRY_FILE_DELETE                          |
| 104        | TELEMETRY_FILE_SET_SECURITY                    |
| 105        | TELEMETRY_FILE_COPY                            |
| 106        | TELEMETRY_FILE_MOVE                            |
| 107        | TELEMETRY_FILE_CLOSE                           |
| 108        | TELEMETRY_FILE_MODIFY_TIMESTAMP                |
| 109        | TELEMETRY_FILE_MODIFY                          |
| 201        | TELEMETRY_CONNECTION_CONNECT                   |
| 202        | TELEMETRY_CONNECTION_LISTEN                    |
| 203        | TELEMETRY_CONNECTION_CONNECT_INBOUND           |
| 204        | TELEMETRY_CONNECTION_CONNECT_OUTBOUND          |
| 301        | TELEMETRY_DNS_QUERY                            |
| 401        | TELEMETRY_REGISTRY_CREATE                      |
| 402        | TELEMETRY_REGISTRY_SET                         |
| 403        | TELEMETRY_REGISTRY_DELETE                      |
| 404        | TELEMETRY_REGISTRY_RENAME                      |
| 501        | TELEMETRY_ACCOUNT_ADD                          |
| 502        | TELEMETRY_ACCOUNT_DELETE                       |
| 503        | TELEMETRY_ACCOUNT_IMPERSONATE                  |
| 504        | TELEMETRY_ACCOUNT_MODIFY                       |
| 601        | TELEMETRY_INTERNET_OPEN                        |
| 602        | TELEMETRY_INTERNET_CONNECT                     |
| 603        | TELEMETRY_INTERNET_DOWNLOAD                    |
| 701        | TELEMETRY_MODIFIED_PROCESS_CREATE_REMOTETHREAD |
| 702        | TELEMETRY_MODIFIED_PROCESS_WRITE_MEMORY        |
| 703        | TELEMETRY_MODIFIED_PROCESS_WRITE_PROCESS       |
| 704        | TELEMETRY_MODIFIED_PROCESS_READ_PROCESS        |
| 705        | TELEMETRY_MODIFIED_PROCESS_WRITE_PROCESS_NAME  |
| 801        | TELEMETRY_WINDOWS_HOOK_SET                     |
| 901        | TELEMETRY_AMSI_EXECUTE                         |
| 1001       | TELEMETRY_MEMORY_MODIFY                        |
| 1002       | TELEMETRY_MEMORY_MODIFY_PERMISSION             |
| 1003       | TELEMETRY_MEMORY_READ                          |
| 1101       | TELEMETRY_BM_INVOKE                            |
| 1102       | TELEMETRY_BM_INVOKE_API                        |

## Mobile Activity Data
### eventId
| eventId | Data Field Mapping |
| ------- | ------------------ |
| 2       | TELEMETRY_FILE     |
| 7       | TELEMETRY_INTERNET |
| 15      | TELEMETRY_APP      |
| 16      | TELEMETRY_SYSTEM   |

### eventSubId
| eventSubId | Data Field Mapping                  |
| ---------- | ----------------------------------- |
| 101        | TELEMETRY_FILE_CREATE               |
| 102        | TELEMETRY_FILE_OPEN                 |
| 103        | TELEMETRY_FILE_DELETE               |
| 105        | TELEMETRY_FILE_COPY                 |
| 106        | TELEMETRY_FILE_MOVE                 |
| 601        | TELEMETRY_INTERNET_OPEN             |
| 602        | TELEMETRY_INTERNET_CONNECT          |
| 1201       | TELEMETRY_APP_START                 |
| 1202       | TELEMETRY_APP_STOP                  |
| 1203       | TELEMETRY_APP_INSTALL               |
| 1204       | TELEMETRY_APP_UNINSTALL             |
| 1301       | TELEMETRY_SYSTEM_PREF_EVENT_ENABLE  |
| 1302       | TELEMETRY_SYSTEM_PREF_EVENT_DISABLE |
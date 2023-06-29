# Data Sharing Workflow

</br>

```{figure} ./_static/img/datasharing.png
---
width: 768px
name: datasharing
---
Click to see the full size diagram.
```

</br>

The **Data Sharing Workflow** diagram describes the process through which FAIR data can be shared internally or externally. These requests may have originated from internal or external sources and typically follow a set standard. The _Data Steward_ is responsible for the policy and semantic-level handling of these requests, while the _Information Manager_ is responsible for the secure and proper technical processing of requests. Each request is logged at every step of the process for full provenance on the type of requests that are made and the data that has been made available.

The steps of this workflow are as follows:

* Incoming Request
  * External requests in the form of data requests and metadata requests are presented for validation and processing.
  * Internal requests in the form of internal data requests, internal metadata request and routine reporting are presented for validation and processing.

* Validation
  * Verification that the requesting user or group has the right permissions to perform a specific query. 
  * Verification that the query adheres to the right structure and meets technical policies.
  * Verification that the request can be legally entertained, depending on the requested content, the user, request location and jurisdiction.

* Data Preperation
  * The query is processed and the resulting models or data are processed towards a specific format for data sharing.
  * Legal compliance of output data is (automatically) audited to ensure no privacy- or security-sensitive information is exposed. 

* Data Ingestion
  * Finally, after all checks have been made, the data is sent to the requesting party.

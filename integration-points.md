# Integration Points

1. S4 HANA:

* Cloud to Cloud (Public cloud)
  * Create one communication user and communication arrangement
  * In BTP we will create a destination
  * http-OAUTH2 connection
* Private Cloud/On Prem (Through Cloud connector)
  * Expose S4 through cloud connector
  * In BTP we will create a destination
  * http-OAUTH2 connection
  * Joule Integration enablement S4 hana cloud tenant

2. Successfactor:

* SF Admin: Register a service with ODATA API
* In BTP we will create a destination
* http-OAUTH2 connection
* Confirm tenant for all the SF capabilities

3. Ariba:

* SAP Ariba Portal ⇒ Register an application ⇒ Request API Access ⇒ Obtain API Key + Oath client ID
* Get Auth2 Access token ⇒ API gateway
* In BTP we will create a destination
* http-OAUTH2 connection

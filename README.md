# SCPSAPCloudSDK

Use below command to set destination locally
https://sap.github.io/cloud-s4-sdk-book/pages/mock-odata.html

Use APIKEY from SAP Business Hub in VDM classes

Mock server for local deployment can be set up using below repository
https://github.com/SAP/cloud-s4-sdk-book.git
Instructions on the mock server can be found at https://sap.github.io/cloud-s4-sdk-book/pages/mock-odata.html


Create service instances as below in the space you are going to deploy the application, same names are used for bindings in manifest.yml.

cf create-service xsuaa application my-xsuaa-sapcloudsdk

cf create-service destination lite my-destination-sapcloudsdk

xsuaa instance with xs-security.json descriptor:

cf create-service xsuaa application my-xsuaa-sapcloudsdk -c xs-security.json

sapcloudsdktrial-fa8c4e6etrial.cfapps.eu10.hana.ondemand.com

sapcloudsdktrial-fa8c4e6etrial.cfapps.eu10.hana.ondemand.com/api/businesspartners

approuter-fa8c4e6etrial.cfapps.eu10.hana.ondemand.com

approuter-fa8c4e6etrial.cfapps.eu10.hana.ondemand.com/api/businesspartners
 
approuter-fa8c4e6etrial.cfapps.eu10.hana.ondemand.com/debug
  

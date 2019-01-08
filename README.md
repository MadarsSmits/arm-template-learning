# arm-template-learning
Azure Resource Manager template learning

---------------
Templates
---------------
To validate ARM template syntax. Required '--location' flag could be from different region.
```
az deployment validate --template-uri https://raw.githubusercontent.com/MadarsSmits/arm-template-learning/master/rg.json --location 'West US'
``` 
To validate ARM template syntax and make sure, that 'allowedValues' validation works.
```
az deployment validate --template-uri https://raw.githubusercontent.com/MadarsSmits/arm-template-learning/master/rg.json --location 'West US' --parameters location='West US'
```
az group deployment validate --template-uri https://raw.githubusercontent.com/MadarsSmits/arm-template-learning/master/template.json --location 'West Europe' --resource-group 'arm-template-learning-1'
```
__arm-template-learning-1:__
- storagelokrgawasdsad (Storage Account)
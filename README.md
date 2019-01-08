# arm-template-learning
Azure Resource Manager template learning

---------------
Templates
---------------
To validate ARM template syntax. Required '--location' flag could be from different region.
```
az deployment validate --template-uri https://raw.githubusercontent.com/MadarsSmits/arm-template-learning/master/template.json --location 'West US'
``` 
To validate ARM template syntax and make sure, that 'allowedValues' validation works.
```
az deployment validate --template-uri https://raw.githubusercontent.com/MadarsSmits/arm-template-learning/master/template.json --location 'West US' --parameters location='West US'
``` 
az deployment create --template-uri https://raw.githubusercontent.com/MadarsSmits/azure-backup/master/rg.json --verbose --location westeurope<br/><br/>

__arm-template-learning-1:__
- lokrgawxn4wkabackup (Storage Account)
- 
__arm-template-learning-2:__
- lokrgawxn4wkabackup (Storage Account)
- 
__arm-template-learning-3:__
- lokrgawxn4wkabackup (Storage Account)
- 
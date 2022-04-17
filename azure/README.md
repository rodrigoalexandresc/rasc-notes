--
az group delete --name rodrigo.ceschi_rg_9250 --no-wait

az webapp up --location eastus --name rascAzureApp --html

az webapp list

az webapp log tail --name appname --resource-group myResourceGroup
-- Delete resource group e todos recursos dele
az group delete --name rodrigo.ceschi_rg_9250 --no-wait

-- Subir webapp html (estático)
az webapp up --location eastus --name rascAzureApp --html

--Listar webapps
az webapp list

--Monitorar logs de webapps
az webapp log tail --name appname --resource-group myResourceGroup
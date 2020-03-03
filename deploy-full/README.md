This template launches a vSRX instance from the vSRX image available at the Azure Marketplace. It also launches other resources necessary to launch a vSRX (such as VNet, Route tables, etc). Please keep in mind that the sole purpose of this template is to demonstrate how a custom template can be built to launch vSRX instances. The topology/dependency presented in this template is for the sole purpose of providing an example and may be different than the users' actual deployment environment.

Deploy with Public IP for mgmt:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faosiecki%2Fvsrx-azure%2Fmaster%2Fdeploy-full%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


Deploy without Public IP for mgmt:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faosiecki%2Fvsrx-azure%2Fmaster%2Fdeploy-full%2Fazuredeploy-nopubip.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

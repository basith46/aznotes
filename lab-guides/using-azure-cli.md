# 📪 Using Azure CLI

## Step 1 - Install Azure Cli local Machine&#x20;

**Method 1:  Windows Package Manager**&#x20;

```powershell
winget install -e --id Microsoft.AzureCLI
```

Method 2: Using Microsoft Installer MSI with PowerShell

```powershell
$ProgressPreference = 'SilentlyContinue'; Invoke-WebRequest -Uri https://aka.ms/installazurecliwindows -OutFile .\AzureCLI.msi; Start-Process msiexec.exe -Wait -ArgumentList '/I AzureCLI.msi /quiet'; Remove-Item .\AzureCLI.msi
```

## Azure CLI vs Azure PowerShell

| Commands                     | Azure CLI                                                                                                                  | Azure PowerShell                                                                                      |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Sign in with Web Browser     | az login                                                                                                                   | Connect-AzAccount                                                                                     |
| Get available subscriptions  | az account list                                                                                                            | Get-AzSubscription                                                                                    |
| Set Subscription             | az account set –-subscription                                                                                              | Set-AzContext -Subscription                                                                           |
| List Azure Locations         | az account list-locations                                                                                                  | Get-AzLocation                                                                                        |
| Find Version                 | az --version                                                                                                               | Get-InstalledModule -Name Az                                                                          |
| Get Help                     | az --help                                                                                                                  | Get-Help                                                                                              |
| View Command Help            | az vm --help                                                                                                               | Get-Help -Name New-AzVM                                                                               |
| Create Resource Group        | az group create --name --location eastus                                                                                   | New-AzResourceGroup -Name -Location eastus                                                            |
| Create Azure Virtual Machine | az vm create --resource-group myResourceGroup --name myVM --image UbuntuLTS --admin-username azureuser --admin-password '' | New-AzVM -ResourceGroupName -Name myVM -Image UbuntuLTS -Credential (Get-Credential)                  |
| Create Azure Storage Account | az storage account create --name --resource-group --location eastus --sku Standard\_LRS --kind StorageV2                   | New-AzStorageAccount -Name -ResourceGroupName -Location eastus -SkuName Standard\_LRS -Kind StorageV2 |
| List VM                      | az vm list                                                                                                                 | Get-AzVM                                                                                              |
| Restart VM                   | az vm restart --name myVM --resource-group                                                                                 | Restart-AzVM -Name myVM -ResourceGroupName                                                            |
| Stop VM                      | az vm stop --name myVM --resource-group                                                                                    | Stop-AzVM -Name myVM -ResourceGroupName                                                               |
| Stop & Deallocate VM         | az vm deallocate --name myVM --resource-group                                                                              | Stop-AzVM -Name myVM -ResourceGroupName                                                               |
| Start VM                     | az vm start --name myVM --resource-group                                                                                   | Start-AzVM -Name myVM -ResourceGroupName                                                              |
| Delete VM                    | az vm delete --name myVM --resource-group                                                                                  | Remove-AzVM -Name myVM -ResourceGroupName                                                             |


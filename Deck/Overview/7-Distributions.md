##

Ways you can find the information for an image:


- Azure portal:
  - The values are automatically specified for you when you select an image to use.
- Azure PowerShell:
  - `_____`
  - `_____`
  - `_____`
- REST APIs:
  - `List image publishers`
  - `List image offers`
  - `List image skus`
- Azure CLI:
  - `_____`
  - `_____`
  - `_____`

  %

- Azure portal:
  - The values are automatically specified for you when you select an image to use.
- Azure PowerShell:
  - `Get-AzVMImagePublisher -Location location`
  - `Get-AzVMImageOffer -Location location -Publisher publisherName`
  - `Get-AzVMImageSku -Location location -Publisher publisherName -Offer offerName`
- REST APIs:
  - `List image publishers`
  - `List image offers`
  - `List image skus`
- Azure CLI:
  - `az vm image list-publishers --location location`
  - `az vm image list-offers --location location --publisher publisherName`
  - `az vm image list-skus --location location --publisher publisherName --offer offerName`

##

Microsoft works closely with partners to ensure the images available are updated and optimized for

%

an Azure runtime

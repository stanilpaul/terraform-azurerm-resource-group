# terraform-azurerm-resource-group
<!-- BEGIN_TF_DOCS -->
# Default example

# What is Resource Group

This is Resource Group module script using terraform. (for learning demo)

```hcl
resource "azurerm_resource_group" "this" {
  name     = var.rg_name
  location = var.location
}
```

<!-- markdownlint-disable MD033 -->
## Requirements

No requirements.

## Providers

The following providers are used by this module:

- <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm)

## Resources

The following resources are used by this module:

- [azurerm_resource_group.this](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) (resource)

<!-- markdownlint-disable MD013 -->
## Required Inputs

The following input variables are required:

### <a name="input_rg_name"></a> [rg\_name](#input\_rg\_name)

Description: n/a

Type: `string`

## Optional Inputs

The following input variables are optional (have default values):

### <a name="input_location"></a> [location](#input\_location)

Description: n/a

Type: `string`

Default: `"West US"`

## Outputs

The following outputs are exported:

### <a name="output_rg_details"></a> [rg\_details](#output\_rg\_details)

Description: n/a

## Modules

No modules.

# WHo is writting

Hi, this is paul
<!-- END_TF_DOCS -->
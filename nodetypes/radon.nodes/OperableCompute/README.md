![](https://img.shields.io/badge/Status:-RELEASED-green)

## Operable Compute Node Type

A node type representing an operable compute independently of the underlying provider.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `Compute` | `radon.nodes.OperableCompute` | 1.0.0 | `tosca.nodes.Compute` |

### Attributes

| Name | Type | Default Value | Description |
|:---- |:---- |:------------- |:----------- |
| `public_address` | `string` | `get_property: [SELF, public_address]` | Public address of the compute |
| `private_address` | `string` | `get_property: [SELF, private_address]` | Private address of the compute |

### Properties

| Name | Required | Type | Constraint | Default Value | Description |
|:---- |:-------- |:---- |:---------- |:------------- |:----------- |
| `name` | `true` | `string` |   |   | Name of the compute |
| `public_address` | `false` | `string` |   |   | Public address of the compute |
| `private_address` | `false` | `string` |   |   | Private address of the compute |

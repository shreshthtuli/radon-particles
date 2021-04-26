![](https://img.shields.io/badge/Status:-RELEASED-green)
![](https://img.shields.io/badge/%20-DEPLOYABLE-blueviolet)

## RaspberryPi MinIO OpenFaaS Function Node Type

A node type that represents OpenFaaS function for RaspberryPi cluster.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `RPiOpenFaaSFunction` | `radon.nodes.rpi.RPiOpenFaaSFunction` | 1.0.0 | `tosca.nodes.SoftwareComponent` |

### Attributes

| Name | Type | Default Value | Description |
|:---- |:---- |:------------- |:----------- |
| `resize_image_name` | `string` |   | Name of already existing image with image-resize functionality. |
| `resize_function_name` | `string` |   | Name of the new OpenFaaS image-resize function. |
| `node_ip` | `string` |   | IP of the VM running the OpenFaaS |



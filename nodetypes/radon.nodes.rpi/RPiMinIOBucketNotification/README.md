![](https://img.shields.io/badge/Status:-RELEASED-green)
![](https://img.shields.io/badge/%20-DEPLOYABLE-blueviolet)

## RaspberryPi MinIO Bucket Notification Node Type

A node type that represents function invocation based on data in MinIO bucket for RaspberryPi cluster.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `RPiMinIOBucketNotification` | `radon.nodes.rpi.RPiMinIOBucketNotifcation` | 1.0.0 | `tosca.nodes.SoftwareComponent` |

### Attributes

| Name | Type | Default Value | Description |
|:---- |:---- |:------------- |:----------- |
| `node_ip` | `string` |   |  IP of the VM running the OpenFaaS |
| `function_name` | `string` |   | The name of the deployed OpenFaaS function |
| `bucket_in_name` | `string` |   | The name of incoming the bucket |
| `minio_user` | `string` |   | MiniIO username |
| `minio_password` | `string` |   | MiniIO password |



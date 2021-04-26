![](https://img.shields.io/badge/Status:-RELEASED-green)
![](https://img.shields.io/badge/%20-DEPLOYABLE-blueviolet)

## RaspberryPi MinIO Bucket Node Type

A node type that represents input and output MinIO buckets for RaspberryPi cluster.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `RPiMinIOBuckets` | `radon.nodes.rpi.RPiMinIOBuckets` | 1.0.0 | `tosca.nodes.SoftwareComponent` |

### Attributes

| Name | Type | Default Value | Description |
|:---- |:---- |:------------- |:----------- |
| `bucket_in_name` | `string` |   | The name of the incoming bucket |
| `bucket_out_name` | `string` |   | The name of the output bucket |
| `minio_ip` | `string` |   | IP address of the MiniIO object storage |
| `minio_user` | `string` |   | MiniIO username |
| `minio_password` | `string` |   | MiniIO password |



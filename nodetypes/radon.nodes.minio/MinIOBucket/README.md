![](https://img.shields.io/badge/Status:-RELEASED-green)
![](https://img.shields.io/badge/%20-DEPLOYABLE-blueviolet)

## MinIO S3 Bucket Node Type

A node type that represents an MinIO S3 bucket.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `MinIOBucket` | `radon.nodes.minio.MinIOBucket` | 1.0.0 | `radon.nodes.abstract.ObjectStorage` |

### Attributes

| Name | Type | Default Value | Description |
|:---- |:---- |:------------- |:----------- |
| `bucket_name` | `string` |   | Name of this AWS S3 bucket |

### Requirements

| Name | Capability Type | Node Type Constraint | Relationship Type | Occurrences |
|:---- |:--------------- |:-------------------- |:----------------- |:------------|
| `host` | `tosca.capabilities.Container` | `radon.nodes.aws.AwsPlatform` | `tosca.relationships.HostedOn` | [1, 1] |
| `invoker` | `radon.capabilities.Invocable` | `radon.nodes.rpi.RPiFunction` | `radon.relationships.rpi.RPiTriggers`| [0, UNBOUNDED] |

### Notes

* Parameters added to the `Standard` interface inputs:
    * `bucket_name`

# MinIO

MinIO is an object storage engine designed to mimic cloud API integration and provide reliable object based storage. 

Operator - https://operatorhub.io/operator/minio-operator

## Requirements

MinIO requires a persistent volume and persistent volume claim to back each of the pods running in the stateful set for the operator. It is a recommended best practice to use the `hostPath` storage provider to back the persistent volume(s) for MinIO. There needs to be a matching number of persistent volume(s) as the number of replicas that make up the MinIO cluster.
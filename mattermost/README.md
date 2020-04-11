# Mattermost

The Mattermost service is meant to replace Slack as an office messenger and chat system. Mattermost is an open source drop-in replacement for Slack, and is setup using the Operator pattern for Kubernetes. 

Operator - https://operatorhub.io/operator/mattermost-operator
Documentation - https://docs.mattermost.com/overview/index.html

Mattermost integrates with a number of the other services, both already in use and alternatives for replacement of those services. The Mattermost Operator requires the below supporting Operator(s) installed into the same cluster. 

- MinIO - https://operatorhub.io/operator/minio-operator
- MySQL - https://github.com/presslabs/mysql-operator


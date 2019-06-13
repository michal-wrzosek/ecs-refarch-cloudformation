# CloudFormation templates for "main"

ENVs:

- staging

Tags used on stacks:

- stack-type: "vpc" | "security-groups" | "load-balancers" | "ecs-cluster" | "service"
- stack: "main"
- env: "staging"

### VPC:

Stack name: "main-vpc"

To sync with S3:

```
aws s3 cp infrastructure/vpc.yaml s3://michal-wrzosek-cloud-formation-templates/main/infrastructure/
```

Template URL:
https://michal-wrzosek-cloud-formation-templates.s3-eu-west-1.amazonaws.com/main/infrastructure/vpc.yaml

### Security Groups:

Stack name: "main-security-groups"

To sync with S3:

```
aws s3 cp infrastructure/security-groups.yaml s3://michal-wrzosek-cloud-formation-templates/main/infrastructure/
```

Template URL:
https://michal-wrzosek-cloud-formation-templates.s3-eu-west-1.amazonaws.com/main/infrastructure/security-groups.yaml

### Load Balancers:

Stack name: "main-load-balancers"

To sync with S3:

```
aws s3 cp infrastructure/load-balancers.yaml s3://michal-wrzosek-cloud-formation-templates/main/infrastructure/
```

Template URL:
https://michal-wrzosek-cloud-formation-templates.s3-eu-west-1.amazonaws.com/main/infrastructure/load-balancers.yaml

### ECS Cluster:

Stack name: "main-ecs-cluster"

To sync with S3:

```
aws s3 cp infrastructure/ecs-cluster.yaml s3://michal-wrzosek-cloud-formation-templates/main/infrastructure/
```

Template URL:
https://michal-wrzosek-cloud-formation-templates.s3-eu-west-1.amazonaws.com/main/infrastructure/ecs-cluster.yaml

### API Service:

Stack name: "main-api-service"

To sync with S3:

```
aws s3 cp services/api-service/service.yaml s3://michal-wrzosek-cloud-formation-templates/main/services/api-service/
```

Template URL:
https://michal-wrzosek-cloud-formation-templates.s3-eu-west-1.amazonaws.com/main/services/api-service/service.yaml

---

This CF template repo was forked from:
https://github.com/aws-samples/ecs-refarch-cloudformation

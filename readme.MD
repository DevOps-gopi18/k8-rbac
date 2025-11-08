# RBAC

REGION_CODE=us-east-1
CLUSTER_NAME=expense-12
ACC_ID=688567292254

## Permissions

* OIDC provider
```
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
```
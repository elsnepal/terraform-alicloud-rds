# MySql-5.6-HighAvailability Alibaba Cloud Rds Terraform Module

Configuration in this directory creates set of RDS resources including DB instance, DB account and Datebase.

## Usage
```hcl
module "database" {
  source  = "terraform-alicloud-modules/rds/alicloud//mysql-5.6-high-availability"
  version = "~> 2.0"
  # insert the 2 required variables here
}
```

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
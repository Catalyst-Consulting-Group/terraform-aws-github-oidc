# GitHub OIDC Terraform Module

A Terraform module that creates an IAM OpenID Connect provider. You only need 1 of these per AWS account.

## Usage

```terraform
module "github_oidc_provider" {
  source  = "Catalyst-Consulting-Group/github-oidc/aws"
  version = "~> 1.0"
}
```

## Authors

This module is maintained by [Catalyst Consulting Group, Inc](https://github.com/Catalyst-Consulting-Group).

## License

MIT License. See [LICENSE](./LICENSE) for full details.

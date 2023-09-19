# `terraform plan -summary`

*A script for `terraform plan` shows resource names.*

## Prerequisites

- [`terraform`](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
- [`jq`](https://jqlang.github.io/jq/download/)

### MacOS

```sh
brew install terraform jq
# or install terraform by `tfenv`
```

## Install

```sh
wget -qO $HOME/.terraform.d/terraform-plan-summary https://raw.githubusercontent.com/flavono123/terraform-plan-summary/main/terraform-plan-summary && chmod +x $HOME/.terraform.d/terraform-plan-summary && echo "alias terraform='$HOME/.terraform.d/terraform-plan-summary'" >> $HOME/.bashrc
```

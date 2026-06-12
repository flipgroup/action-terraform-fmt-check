# Action Terraform format check

GitHub Action for confirming that formatting of Terraform configuration files matches that of [`terraform fmt`](https://developer.hashicorp.com/terraform/cli/commands/fmt).

## Usage

```yaml
jobs:
  main:
    name: Lint
    runs-on: ubuntu-latest
    steps:
      - name: Terraform format check
        uses: flipgroup/action-terraform-fmt-check@main
        with:
          version: 1.12.2
```

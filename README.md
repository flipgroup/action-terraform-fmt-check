# Action Terraform format check

GitHub Action for confirming that formatting of Terraform configuration files matches that of [`terraform fmt`](https://www.terraform.io/docs/cli/commands/fmt.html).

## Usage

```yaml
jobs:
  main:
    name: Lint
    runs-on: ubuntu-latest
    steps:
      - name: Checkout source
        uses: actions/checkout@v2
      - name: Terraform format check
        uses: flipgroup/action-terraform-fmt-check@main
        with:
          version: 1.0.0
```

# Safe Contributor License Agreement

This repository contains a copy of the Safe Contributor License Agreement document, which is hosted on <https://safe.global/cla>.

## Usage

We require all external contributors to accept this agreement before merging their contributions. In order to have some affirmation from the contributors, we require that pull requests include the text from the `PULL_REQUEST_TEMPLATE.md` included in this repository. To add the template to another Safe Research repository, run the following from the repository root:

```sh
mkdir -p .github
curl -sL https://raw.githubusercontent.com/safe-research/cla/refs/heads/main/.github/PULL_REQUEST_TEMPLATE.md -o .github/PULL_REQUEST_TEMPLATE.md
```

Feel free to edit the `PULL_REQUEST_TEMPLATE.md` file and add any repository-specific content **before** the `---` separator.

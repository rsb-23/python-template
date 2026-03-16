# python-template-repo

It is a template repo for my python projects

### Prefered Structure
 This reduces clutter in the repository root.
```zsh
project-root/
    ├── .github/
    │      ├── workflows/
    │      │      ├── code-lint.yml
    │      │      ├── code-test.yml
    │      │      └── release.yml
    │      ├── ISSUE_TEMPLATE/
    │      │      ├── bug_report.md
    │      │      ├── feature_request.md
    │      │      └── config.yml
    │      ├── PULL_REQUEST_TEMPLATE.md
    │      ├── CODE_OF_CONDUCT.md
    │      ├── CONTRIBUTING.md
    │      ├── SECURITY.md
    │      ├── SUPPORT.md
    │      ├── FUNDING.yml
    │      ├── CODEOWNERS
    │      ├── CHANGELOG.md
    │      ├── ROADMAP.md
    │      └── README.md
    ├── src/
    ├── tests/
    │      ├── unit/
    │      ├── integration/
    │      └── e2e/
    ├── docs/
    │      ├── api/
    │      ├── guides/
    │      └── architecture.md
    ├── scripts/
    │      ├── build.sh
    │      ├── test.sh
    │      └── deploy.sh
    ├── .gitignore
    ├── LICENSE
    └── pyproject.toml
```

### Setup

```cmd
python one_time.py
```

<hr/>

> ⚠️ Work in Progress...

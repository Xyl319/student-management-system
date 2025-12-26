# CI/CD流水线说明
## 1. GitHub Actions配置
```yaml
name: 构建部署
on:
  push:
    branches: [main]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-java@v4
        with:
          java-version: '11'
      - run: mvn package -Dmaven.test.skip=true

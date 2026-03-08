```bash
# 以“可编辑模式”安装 + 开发依赖
pip install -e ".[dev]"
```
.[dev]：表示除了基础依赖外，额外安装 pyproject.toml 中 [project.optional-dependencies] 下定义的 dev 组依赖。
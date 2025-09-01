# QIACHIP 用户指南

本项目是一个使用 MkDocs 构建的文档网站，旨在为 QIACHIP 产品提供用户指南。

## 目录

- **Home**: `index.md`
- **About**: `MKdocs网站搭建.md` (关于 MkDocs 网站搭建的说明)
- **TX180**: `TX180.docx` (TX180 文档，Word 格式)
- **TX180MD**: `TX180.md` (TX180 文档，Markdown 格式)

## 本地运行

1. 确保您已安装 Python 和 pip。
2. 安装 MkDocs 和 Material 主题：
   ```bash
   pip install mkdocs mkdocs-material
   ```
3. 克隆本项目到本地：
   ```bash
   git clone <本项目仓库地址>
   cd QIACHIP-User-Guide-master
   ```
4. 在项目根目录运行以下命令启动本地服务器：
   ```bash
   mkdocs serve
   ```
   然后您可以在浏览器中访问 `http://127.0.0.1:8000` 查看文档。

## 构建文档

要生成静态网站文件，请运行：

```bash
mkdocs build
```

生成的网站文件将位于 `site/` 目录下。

## 贡献

欢迎对本项目进行贡献。请遵循以下步骤：
1. Fork 本项目。
2. 创建新的分支 (`git checkout -b feature/your-feature`)。
3. 提交您的更改 (`git commit -am 'Add new feature'`)。
4. 推送至分支 (`git push origin feature/your-feature`)。
5. 提交 Pull Request。

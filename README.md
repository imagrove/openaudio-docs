# Imagrove OpenAudio — Documentation

文档站源文件（MkDocs Material），发布到 https://openaudio.imagrove.com/docs 。

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve
```

打开 http://127.0.0.1:8000 。

## 构建

```bash
mkdocs build
```

产物在 `site/`。

## 部署

推送到 `main` 后，由 `.github/workflows/deploy.yml` 自动构建并部署到 GitHub Pages。
在仓库 Settings → Pages 中将 Source 设为 "GitHub Actions"。

## 目录

- `docs/getting-started/` 快速开始
- `docs/hardware/` 硬件
- `docs/firmware/` 固件
- `docs/server/` 服务端
- `docs/multiroom/` 多房间
- `docs/surround/` 环绕声
- `docs/integrations/` 智能家居集成
- `docs/legal/` 许可与合规

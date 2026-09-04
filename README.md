# kc888 · GitHub → Cloudflare Pages

静态站点，通过 Cloudflare Dashboard 原生 GitHub 集成自动部署。

- 仓库：https://github.com/KC521/kc888
- 站点：https://kc888.pages.dev

## 触发方式

- 推送到 `main` 分支 → Cloudflare Pages 自动构建部署
- 构建配置：无构建命令，根目录直接部署（纯静态 HTML）
- 生产分支：`main`

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 目录

```
index.html     站点首页
.gitignore     忽略文件
```

# 东擎宇企业管理咨询有限公司 · 管理系统

云端协同薪资与支出管理系统，基于 Supabase 实时同步。

## 功能
- 员工档案管理
- 工资计算
- 业绩记录与排名
- 奖惩管理
- 公司支出管理
- 数据云端同步（Supabase）
- 多设备实时协作
- 密钥验证保护（密钥：dqy8888）

## 技术栈
- 前端：单文件 HTML + 原生 JavaScript
- 后端：Supabase（实时数据库 + 鉴权）
- 部署：GitHub Pages

## 本地运行
```bash
# 方式1：直接打开
open index.html

# 方式2：本地服务器
python -m http.server 8000
# 访问 http://localhost:8000
```

## 密钥
默认密钥：`dqy8888`（在 index.html 中可修改 `AUTH_SECRET` 变量）

## 数据存储
所有业务数据存储在 Supabase `app_data` 表中，单行 JSON 文档结构（id='shared'），多设备实时同步。

<div align="center">
  <h1>EduForge AI</h1>
  <p><strong>面向教师的 AI 教学资源生成平台</strong></p>
  <p>把一个教学主题，快速变成 PPT、互动课件、PDF 试卷和可沉淀的教材资源。</p>

  <p>
    <a href="https://eduforge.com.cn">
      <img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-eduforge.com.cn-111111?style=for-the-badge">
    </a>
    <a href="https://eduforge.com.cn/docs">
      <img alt="Product Docs" src="https://img.shields.io/badge/Product%20Docs-Whitepaper-5B6EE1?style=for-the-badge">
    </a>
    <a href="LICENSE">
      <img alt="MIT License" src="https://img.shields.io/badge/License-MIT-20A67A?style=for-the-badge">
    </a>
  </p>

  <p>
    <a href="https://eduforge.com.cn"><strong>在线体验</strong></a>
    ·
    <a href="https://eduforge.com.cn/teaching-resources"><strong>资源大厅</strong></a>
    ·
    <a href="https://eduforge.com.cn/docs"><strong>产品白皮书</strong></a>
    ·
    <a href="https://eduforge.com.cn/api-docs"><strong>API 文档</strong></a>
  </p>
</div>

---

## 这是什么

EduForge AI 是一个围绕教师备课场景打造的 AI 教学资源平台。它不只是生成一份孤立的内容，而是把资源放回教材、章节和课堂使用流程里，帮助教师更快完成备课、沉淀资源，并在校内系统中复用。

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>生成课件</h3>
      <p>输入教学主题、年级、学科和教材范围，生成可用于课堂展示的 PPT。</p>
    </td>
    <td width="33%" valign="top">
      <h3>互动课堂</h3>
      <p>生成 React 互动课件，让知识点以可操作、可演示的方式呈现。</p>
    </td>
    <td width="33%" valign="top">
      <h3>试卷导出</h3>
      <p>按教学目标生成结构化试卷，并导出为 PDF 文件。</p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h3>教材资源库</h3>
      <p>按年级、学科、版本、学期、章节整理教材和生成资源。</p>
    </td>
    <td width="33%" valign="top">
      <h3>在线预览</h3>
      <p>支持 PPT、PDF、互动课件在线预览，减少下载和反复打开文件的成本。</p>
    </td>
    <td width="33%" valign="top">
      <h3>开放接入</h3>
      <p>提供开发者 API，方便接入校内平台、资源系统或教学工具。</p>
    </td>
  </tr>
</table>

## 在线演示

<table>
  <tr>
    <th>入口</th>
    <th>可以体验什么</th>
    <th>链接</th>
  </tr>
  <tr>
    <td><strong>首页</strong></td>
    <td>了解 EduForge AI 的产品定位、资源案例和核心能力</td>
    <td><a href="https://eduforge.com.cn">打开</a></td>
  </tr>
  <tr>
    <td><strong>教学 PPT</strong></td>
    <td>体验面向课堂展示的教学 PPT 生成流程</td>
    <td><a href="https://eduforge.com.cn/teaching-resources/ppt">打开</a></td>
  </tr>
  <tr>
    <td><strong>互动课件</strong></td>
    <td>查看可运行、可操作的 React 互动课件案例</td>
    <td><a href="https://eduforge.com.cn/teaching-resources/react-courseware">打开</a></td>
  </tr>
  <tr>
    <td><strong>PDF 试卷</strong></td>
    <td>体验从教学目标到结构化试卷的生成路径</td>
    <td><a href="https://eduforge.com.cn/teaching-resources/exam-pdf">打开</a></td>
  </tr>
  <tr>
    <td><strong>资源大厅</strong></td>
    <td>浏览公开教学资源、教材分类和课程案例</td>
    <td><a href="https://eduforge.com.cn/teaching-resources">打开</a></td>
  </tr>
  <tr>
    <td><strong>教师工作台</strong></td>
    <td>管理我的资源、教材资源库、题库、额度和 API Key</td>
    <td><a href="https://eduforge.com.cn/overview">打开</a></td>
  </tr>
</table>

## 适合谁

- 一线教师：更快完成备课、出题、资源整理和课堂演示。
- 教研组：沉淀按教材章节组织的可复用资源库。
- 学校信息化团队：将 AI 生成能力接入校内教学平台。
- 开发者：基于 API 构建资源生成、资源检索或教学辅助工具。

## 项目亮点

- 不是简单聊天生成，而是围绕真实备课流程组织。
- 生成结果可以沉淀到教材章节，不会散落成孤立文件。
- 同时覆盖展示型资源、互动型资源和练习型资源。
- 管理端支持教材 PDF 上传，方便维护本校教材资源。
- 提供开发者 API，适合二次集成和平台化扩展。

## 快速开始

```bash
git clone https://github.com/your-name/eduforge-ai.git
cd eduforge-ai
```

后端：

```powershell
Set-Location .\backend
python -m pip install -r requirements.txt
python -m uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

前端：

```powershell
Set-Location .\frontend
npm install
npm run dev
```

本地访问：

- 前端首页：[http://localhost:3000](http://localhost:3000)
- 后端健康检查：[http://localhost:8000/api/health](http://localhost:8000/api/health)
- 后端 OpenAPI：[http://localhost:8000/api/docs](http://localhost:8000/api/docs)

<details>
  <summary><strong>环境变量示例</strong></summary>

```env
DATABASE_URL=mysql+aiomysql://USER:PASSWORD@localhost:3306/eduforge
SECRET_KEY=replace-with-a-long-random-secret

LLM_PROVIDER=tongyi
LLM_API_KEY=your-dashscope-api-key
LLM_API_URL=https://dashscope.aliyuncs.com/api/v1/services/aigc/text-generation/generation
LLM_MODEL=qwen-plus

NEXT_PUBLIC_API_URL=http://localhost:8000
INTERNAL_API_URL=http://localhost:8000
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=replace-with-a-long-random-secret
ALLOWED_ORIGINS=["http://localhost:3000"]
```

</details>

<details>
  <summary><strong>技术栈与项目结构</strong></summary>

### 技术栈

| 模块 | 技术 |
| --- | --- |
| 前端 | Next.js, React, TypeScript, Tailwind CSS |
| 后端 | FastAPI, SQLAlchemy, Pydantic, Uvicorn |
| 数据 | MySQL, Redis |
| 资源生成 | python-pptx, WeasyPrint, ReportLab, PyMuPDF |
| AI 接入 | 通义千问 DashScope |

### 项目结构

```text
EduForge AI/
├── backend/          # 后端服务
├── frontend/         # 前端应用
├── docker-compose.yml
├── docker-compose.prod.yml
└── start-local.ps1
```

</details>

<details>
  <summary><strong>Docker 部署</strong></summary>

```bash
docker compose up -d --build
```

生产环境可叠加生产配置：

```bash
docker compose -f docker-compose.yml -f docker-compose.prod.yml up -d --build
```

生产环境常用配置：

```env
NEXT_PUBLIC_API_URL=https://api.eduforge.com.cn
INTERNAL_API_URL=http://backend:8000
NEXTAUTH_URL=https://eduforge.com.cn
ALLOWED_ORIGINS=["https://eduforge.com.cn"]
```

</details>

## 开发者 API

EduForge AI 提供 API Key 和开放接口，方便将教学资源生成能力接入学校平台或第三方工具。

- 产品白皮书：[https://eduforge.com.cn/docs](https://eduforge.com.cn/docs)
- API 文档：[https://eduforge.com.cn/api-docs](https://eduforge.com.cn/api-docs)
- 本地 OpenAPI：[http://localhost:8000/api/docs](http://localhost:8000/api/docs)

## License

本项目采用 MIT License，详情见 [LICENSE](LICENSE)。
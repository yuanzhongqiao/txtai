<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/logo.png"><img src="https://raw.githubusercontent.com/neuml/txtai/master/logo.png" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
    <b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一体化嵌入数据库</font></font></b>
</p>
<p align="center" dir="auto">
    <a href="https://github.com/neuml/txtai/releases">
        <img src="https://camo.githubusercontent.com/be5097fdccd27726c636de4fc6a762428983225eb7e8731b7dca156daf3f74e1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f6e65756d6c2f74787461692e7376673f7374796c653d666c617426636f6c6f723d73756363657373" alt="版本" data-canonical-src="https://img.shields.io/github/release/neuml/txtai.svg?style=flat&amp;color=success" style="max-width: 100%;">
    </a>
    <a href="https://github.com/neuml/txtai">
        <img src="https://camo.githubusercontent.com/f30e426613c4f9b2bf7637f782dec0a008b47184a22fd67ee242ccbd5fdded7b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6173742d636f6d6d69742f6e65756d6c2f74787461692e7376673f7374796c653d666c617426636f6c6f723d626c7565" alt="GitHub 上次提交" data-canonical-src="https://img.shields.io/github/last-commit/neuml/txtai.svg?style=flat&amp;color=blue" style="max-width: 100%;">
    </a>
    <a href="https://github.com/neuml/txtai/issues">
        <img src="https://camo.githubusercontent.com/c20ca4db60ecec322aa8d691139e197db5cd9a18fe63a7f87b495f948b768ab3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6973737565732f6e65756d6c2f74787461692e7376673f7374796c653d666c617426636f6c6f723d73756363657373" alt="GitHub 问题" data-canonical-src="https://img.shields.io/github/issues/neuml/txtai.svg?style=flat&amp;color=success" style="max-width: 100%;">
    </a>
    <a href="https://join.slack.com/t/txtai/shared_invite/zt-1cagya4yf-DQeuZbd~aMwH5pckBU4vPg" rel="nofollow">
        <img src="https://camo.githubusercontent.com/14559d03dabc18d125faf4c33103da4d032d58486abeea03957195911ba60d10/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f736c61636b2d6a6f696e2d626c75653f7374796c653d666c6174266c6f676f3d736c61636b266c6f676f636f6c6f723d7768697465" alt="加入 Slack" data-canonical-src="https://img.shields.io/badge/slack-join-blue?style=flat&amp;logo=slack&amp;logocolor=white" style="max-width: 100%;">
    </a>
    <a href="https://github.com/neuml/txtai/actions?query=workflow%3Abuild">
        <img src="https://github.com/neuml/txtai/workflows/build/badge.svg" alt="构建状态" style="max-width: 100%;">
    </a>
    <a href="https://coveralls.io/github/neuml/txtai?branch=master" rel="nofollow">
        <img src="https://camo.githubusercontent.com/7e65f72f4df6c94fd7a9eb03c448442ce25cabc6035179d373ff61e714136005/68747470733a2f2f696d672e736869656c64732e696f2f636f766572616c6c73436f7665726167652f6769746875622f6e65756d6c2f7478746169" alt="覆盖状态" data-canonical-src="https://img.shields.io/coverallsCoverage/github/neuml/txtai" style="max-width: 100%;">
    </a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 是一个用于语义搜索、LLM 编排和语言模型工作流的一体化嵌入数据库。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/architecture.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/architecture.png#gh-light-mode-only" alt="建筑学" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/architecture-dark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/architecture-dark.png#gh-dark-mode-only" alt="architecture" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">嵌入数据库是向量索引（稀疏和密集）、图网络和关系数据库的联合。这支持使用 SQL 进行向量搜索、主题建模、检索增强生成等。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">嵌入数据库可以独立存在，也可以作为大型语言模型 (LLM) 提示的强大知识源。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 功能总结：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔎 使用 SQL、对象存储、主题建模、图形分析和多模态索引进行向量搜索</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📄 为文本、文档、音频、图像和视频创建嵌入</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💡 由语言模型驱动的管道，运行 LLM 提示、问答、标记、转录、翻译、摘要等</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↪️️工作流将管道连接在一起并聚合业务逻辑。txtai 流程可以是简单的微服务或多模型工作流。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚙️ 使用 Python 或 YAML 构建。适用于</font></font><a href="https://github.com/neuml/txtai.js"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JavaScript</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/neuml/txtai.java"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/neuml/txtai.rs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rust</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/neuml/txtai.go"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Go</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的 API 绑定。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">☁️ 本地运行或通过容器编排进行扩展</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/huggingface/transformers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 使用 Python 3.8+、 Hugging Face Transformers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/UKPLab/sentence-transformers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sentence Transformers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/tiangolo/fastapi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FastAPI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建</font><font style="vertical-align: inherit;">。txtai 在 Apache 2.0 许可下开源。</font></font></p>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">想要以一种简单且安全的方式运行托管的 txtai 应用程序吗？加入</font></font><a href="https://txtai.cloud" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai.cloud</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预览版以了解更多信息。</font></font></em></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么是 txtai？</font></font></h2><a id="user-content-why-txtai" class="anchor" aria-label="永久链接：为什么是 txtai？" href="#why-txtai"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/why.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/why.png#gh-light-mode-only" alt="为什么" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/why-dark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/why-dark.png#gh-dark-mode-only" alt="why" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新的矢量数据库、LLM 框架以及介于两者之间的一切每天都在涌现。为什么要使用 txtai 进行构建？</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><a href="https://neuml.github.io/txtai/install/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用pip</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font><a href="https://neuml.github.io/txtai/cloud/" rel="nofollow"><font style="vertical-align: inherit;">Docker</font></a><font style="vertical-align: inherit;">在几分钟内启动并运行</font></font><a href="https://neuml.github.io/txtai/cloud/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># Get started in a couple lines</span>
<span class="pl-k">import</span> <span class="pl-s1">txtai</span>

<span class="pl-s1">embeddings</span> <span class="pl-c1">=</span> <span class="pl-s1">txtai</span>.<span class="pl-v">Embeddings</span>()
<span class="pl-s1">embeddings</span>.<span class="pl-en">index</span>([<span class="pl-s">"Correct"</span>, <span class="pl-s">"Not what we hoped"</span>])
<span class="pl-s1">embeddings</span>.<span class="pl-en">search</span>(<span class="pl-s">"positive"</span>, <span class="pl-c1">1</span>)
<span class="pl-c">#[(0, 0.29862046241760254)]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Get started in a couple lines
import txtai

embeddings = txtai.Embeddings()
embeddings.index([&quot;Correct&quot;, &quot;Not what we hoped&quot;])
embeddings.search(&quot;positive&quot;, 1)
#[(0, 0.29862046241760254)]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置 API 让您能够轻松使用您选择的编程语言开发应用程序</font></font></li>
</ul>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> app.yml</span>
<span class="pl-ent">embeddings</span>:
    <span class="pl-ent">path</span>: <span class="pl-s">sentence-transformers/all-MiniLM-L6-v2</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# app.yml
embeddings:
    path: sentence-transformers/all-MiniLM-L6-v2" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>CONFIG=app.yml uvicorn <span class="pl-s"><span class="pl-pds">"</span>txtai.api:app<span class="pl-pds">"</span></span>
curl -X GET <span class="pl-s"><span class="pl-pds">"</span>http://localhost:8000/search?query=positive<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="CONFIG=app.yml uvicorn &quot;txtai.api:app&quot;
curl -X GET &quot;http://localhost:8000/search?query=positive&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地运行——无需将数据发送到不同的远程服务</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用微模型直至大型语言模型 (LLM)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占用空间小 - 安装额外的依赖项并在需要时扩展</font></font></li>
<li><a href="https://neuml.github.io/txtai/examples" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过示例学习</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 笔记本涵盖所有可用功能</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用例</font></font></h2><a id="user-content-use-cases" class="anchor" aria-label="永久链接：用例" href="#use-cases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下各节介绍了常见的 txtai 用例。</font><font style="vertical-align: inherit;">还提供超过 50 个</font></font><a href="https://neuml.github.io/txtai/examples" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例笔记本和应用程序的综合集。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语义搜索</font></font></h3><a id="user-content-semantic-search" class="anchor" aria-label="永久链接：语义搜索" href="#semantic-search"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建语义/相似性/向量/神经搜索应用程序。</font></font></p>
<p dir="auto"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/demo.gif" data-target="animated-image.originalLink"><img src="https://raw.githubusercontent.com/neuml/txtai/master/demo.gif" alt="演示" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://raw.githubusercontent.com/neuml/txtai/master/demo.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="demo" class="AnimatedImagePlayer-animatedImage" src="https://raw.githubusercontent.com/neuml/txtai/master/demo.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="814" height="393"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play demo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play demo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open demo in new window" class="AnimatedImagePlayer-button" href="https://raw.githubusercontent.com/neuml/txtai/master/demo.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">传统搜索系统使用关键词来查找数据。语义搜索能够理解自然语言，并识别具有相同含义的结果，而不一定具有相同的关键词。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/search.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/search.png#gh-light-mode-only" alt="搜索" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/search-dark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/search-dark.png#gh-dark-mode-only" alt="search" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从以下示例开始。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="right"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/01_Introducing_txtai.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 简介</font></font></a> <a href="https://www.youtube.com/watch?v=SIezMnVdmMs" rel="nofollow"><g-emoji class="g-emoji" alias="arrow_forward"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▶️</font></font></g-emoji></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 提供的功能概述</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/01_Introducing_txtai.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/13_Similarity_search_with_images.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像相似性搜索</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将图像和文本嵌入到同一空间进行搜索</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/13_Similarity_search_with_images.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/34_Build_a_QA_database.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建立 QA 数据库</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题匹配与语义搜索</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/34_Build_a_QA_database.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/38_Introducing_the_Semantic_Graph.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语义图</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">探索主题、数据连接并运行网络分析</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/38_Introducing_the_Semantic_Graph.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM 编排</font></font></h3><a id="user-content-llm-orchestration" class="anchor" aria-label="永久链接：LLM 编排" href="#llm-orchestration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM 链、检索增强生成 (RAG)、与您的数据聊天、与大型语言模型 (LLM) 交互的管道和工作流。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链条</font></font></h4><a id="user-content-chains" class="anchor" aria-label="永久链接：链" href="#chains"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整合 LLM 链（在 txtai 中称为工作流）、多个 LLM 代理和自我批评。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/llm.png"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/llm.png" alt="法学硕士" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅下文以了解更多信息。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="right"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/44_Prompt_templates_and_task_chains.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提示模板和任务链</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建模型提示并将任务与工作流连接在一起</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/44_Prompt_templates_and_task_chains.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/53_Integrate_LLM_Frameworks.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整合 LLM 框架</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成 llama.cpp、LiteLLM 和自定义生成框架</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/53_Integrate_LLM_Frameworks.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/57_Build_knowledge_graphs_with_LLM_driven_entity_extraction.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 LLM 构建知识图谱</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 LLM 驱动的实体提取构建知识图谱</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/57_Build_knowledge_graphs_with_LLM_driven_entity_extraction.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强生成</font></font></h4><a id="user-content-retrieval-augmented-generation" class="anchor" aria-label="永久链接：检索增强生成" href="#retrieval-augmented-generation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强生成 (RAG) 通过使用知识库作为上下文来限制输出，从而降低了 LLM 幻觉的风险。RAG 通常用于“与数据聊天”。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/rag.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/rag.png#gh-light-mode-only" alt="抹布" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/rag-dark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/rag-dark.png#gh-dark-mode-only" alt="rag" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 的一个新颖的特点是它既可以提供答案，又可以提供来源引用。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="right"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/52_Build_RAG_pipelines_with_txtai.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 txtai 构建 RAG 管道</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强生成指南，包括如何创建引文</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/52_Build_RAG_pipelines_with_txtai.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/63_How_RAG_with_txtai_works.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RAG 与 txtai 的工作原理</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建 RAG 进程、API 服务和 Docker 实例</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/63_How_RAG_with_txtai_works.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/58_Advanced_RAG_with_graph_path_traversal.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有图形路径遍历的高级 RAG</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图形路径遍历用于收集高级 RAG 的复杂数据集</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/58_Advanced_RAG_with_graph_path_traversal.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/60_Advanced_RAG_with_guided_generation.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有引导生成的高级 RAG</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强和引导生成</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/60_Advanced_RAG_with_guided_generation.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语言模型工作流程</font></font></h3><a id="user-content-language-model-workflows" class="anchor" aria-label="永久链接：语言模型工作流程" href="#language-model-workflows"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语言模型工作流（也称为语义工作流）将语言模型连接在一起以构建智能应用程序。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/flows.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/flows.png#gh-light-mode-only" alt="流量" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/flows-dark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/flows-dark.png#gh-dark-mode-only" alt="flows" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然 LLM 功能强大，但还有很多更小、更专业的模型可以更好、更快地完成特定任务。这包括用于提取问答、自动摘要、文本转语音、转录和翻译的模型。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="right"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/14_Run_pipeline_workflows.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行管道工作流程</font></font></a> <a href="https://www.youtube.com/watch?v=UBMPDCn1gEU" rel="nofollow"><g-emoji class="g-emoji" alias="arrow_forward"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▶️</font></font></g-emoji></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简单而强大的结构可高效处理数据</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/14_Run_pipeline_workflows.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/09_Building_abstractive_text_summaries.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建抽象文本摘要</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行抽象文本摘要</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/09_Building_abstractive_text_summaries.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/11_Transcribe_audio_to_text.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将音频转录为文本</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将音频文件转换为文本</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/11_Transcribe_audio_to_text.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/txtai/blob/master/examples/12_Translate_text_between_languages.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在多种语言之间翻译文本</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简化机器翻译和语言检测</font></font></td>
<td align="right"><a href="https://colab.research.google.com/github/neuml/txtai/blob/master/examples/12_Translate_text_between_languages.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="固定链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/install.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/install.png#gh-light-mode-only" alt="安装" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/install-dark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/install-dark.png#gh-dark-mode-only" alt="install" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最简单的安装方法是通过 pip 和 PyPI</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install txtai
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install txtai" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 Python 3.8+。</font><font style="vertical-align: inherit;">建议使用 Python</font></font><a href="https://docs.python.org/3/library/venv.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虚拟环境。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅详细的</font></font><a href="https://neuml.github.io/txtai/install" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取更多信息，包括</font></font><a href="https://neuml.github.io/txtai/install/#optional-dependencies" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可选依赖项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://neuml.github.io/txtai/install/#environment-specific-prerequisites" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特定于环境的先决条件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://neuml.github.io/txtai/install/#install-from-source" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源代码安装</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://neuml.github.io/txtai/install/#conda" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">conda 支持</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及如何</font></font><a href="https://neuml.github.io/txtai/cloud" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用容器运行</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型指南</font></font></h2><a id="user-content-model-guide" class="anchor" aria-label="永久链接：模型指南" href="#model-guide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/models.png"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/models.png" alt="楷模" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅下表了解当前推荐的型号。这些型号均可用于商业用途，速度和性能兼具。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成分</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">楷模）</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://neuml.github.io/txtai/embeddings" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">嵌入</font></font></a></td>
<td><a href="https://hf.co/sentence-transformers/all-MiniLM-L6-v2" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全-MiniLM-L6-v2</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/image/caption" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图片说明</font></font></a></td>
<td><a href="https://hf.co/Salesforce/blip-image-captioning-base" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基础信息平台</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/text/labels" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签 - Zero Shot</font></font></a></td>
<td><a href="https://hf.co/facebook/bart-large" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BART-大型-MNLI</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/text/labels" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签 - 已固定</font></font></a></td>
<td><font style="vertical-align: inherit;"><a href="https://neuml.github.io/txtai/pipeline/train/trainer" rel="nofollow"><font style="vertical-align: inherit;">使用训练管道</font></a><font style="vertical-align: inherit;">进行微调</font></font><a href="https://neuml.github.io/txtai/pipeline/train/trainer" rel="nofollow"><font style="vertical-align: inherit;"></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/text/llm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型语言模型（LLM）</font></font></a></td>
<td><a href="https://hf.co/Open-Orca/Mistral-7B-OpenOrca" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米斯特拉尔 7B OpenOrca</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/text/summary" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总结</font></font></a></td>
<td><a href="https://hf.co/sshleifer/distilbart-cnn-12-6" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DistilBART</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/audio/texttospeech" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文字转语音</font></font></a></td>
<td><a href="https://hf.co/NeuML/ljspeech-jets-onnx" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ESPnet 喷气机</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/audio/transcription" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转录</font></font></a></td>
<td><a href="https://hf.co/openai/whisper-base" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">耳语</font></font></a></td>
</tr>
<tr>
<td><a href="https://neuml.github.io/txtai/pipeline/text/translation" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译</font></font></a></td>
<td><a href="https://hf.co/Helsinki-NLP" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OPUS 型号系列</font></font></a></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型可以作为 Hugging Face Hub 中的路径或本地目录加载。模型路径是可选的，未指定时会加载默认值。对于没有推荐模型的任务，txtai 将使用 Hugging Face 任务指南中所示的默认模型。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅以下链接以了解更多信息。</font></font></p>
<ul dir="auto">
<li><a href="https://hf.co/tasks" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拥抱脸部任务</font></font></a></li>
<li><a href="https://hf.co/models" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拥抱脸模型中心</font></font></a></li>
<li><a href="https://hf.co/spaces/mteb/leaderboard" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MTEB 排行榜</font></font></a></li>
<li><a href="https://chat.lmsys.org/?leaderboard" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LMSYS LLM 排行榜</font></font></a></li>
<li><a href="https://hf.co/spaces/HuggingFaceH4/open_llm_leaderboard" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放 LLM 排行榜</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由 txtai 提供支持</font></font></h2><a id="user-content-powered-by-txtai" class="anchor" aria-label="永久链接：由 txtai 提供支持" href="#powered-by-txtai"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下应用程序由 txtai 提供支持。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/apps.jpg"><img src="https://raw.githubusercontent.com/neuml/txtai/master/apps.jpg" alt="应用" style="max-width: 100%;"></a></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="https://github.com/neuml/txtchat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天室</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强生成 (RAG) 支持的搜索</font></font></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/paperai"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸艺</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医学/科学论文的语义搜索和工作流程</font></font></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/codequestion"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码问题</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">面向开发人员的语义搜索</font></font></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/neuml/tldrstory"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第三个故事</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标题和故事文本的语义搜索</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了此列表之外，还有许多其他</font></font><a href="https://github.com/neuml/txtai/network/dependents"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源项目</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://scholar.google.com/scholar?q=txtai&amp;hl=en&amp;as_ylo=2022" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已发布的研究</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和封闭的专有/商业项目在生产中基于 txtai 构建。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进一步阅读</font></font></h2><a id="user-content-further-reading" class="anchor" aria-label="永久链接：进一步阅读" href="#further-reading"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/further.png#gh-light-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/further.png#gh-light-mode-only" alt="更远" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/further-ghdark.png#gh-dark-mode-only"><img src="https://raw.githubusercontent.com/neuml/txtai/master/docs/images/further-ghdark.png#gh-dark-mode-only" alt="further" style="max-width: 100%;"></a></p>
<ul dir="auto">
<li><a href="https://medium.com/neuml/introducing-txtai-the-all-in-one-embeddings-database-c721f4ff91ad" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍 txtai，一体化嵌入数据库</font></font></a></li>
<li><a href="https://neuml.hashnode.dev/series/txtai-tutorial" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hashnode 教程系列</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://dev.to/neuml/tutorial-series-on-txtai-ibg" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dev.to</font></font></a></li>
<li><a href="https://medium.com/neuml/whats-new-in-txtai-7-0-855ad6a55440" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">txtai 7.0 | </font></font><a href="https://medium.com/neuml/whats-new-in-txtai-6-0-7d93eeedf804" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> | </font></font><a href="https://medium.com/neuml/whats-new-in-txtai-5-0-e5c75a13b101" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> | </font><a href="https://medium.com/neuml/whats-new-in-txtai-4-0-bbc3a65c3d1c" rel="nofollow"><font style="vertical-align: inherit;">4.0</font></a><a href="https://medium.com/neuml/whats-new-in-txtai-7-0-855ad6a55440" rel="nofollow"><font style="vertical-align: inherit;">中的新增功能</font></a></font><a href="https://medium.com/neuml/whats-new-in-txtai-4-0-bbc3a65c3d1c" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
<li><a href="https://medium.com/neuml/getting-started-with-semantic-search-a9fd9d8a48cf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语义搜索入门</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://medium.com/neuml/getting-started-with-rag-9a0cca75f748" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rag</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> |</font></font><a href="https://medium.com/neuml/getting-started-with-semantic-workflows-2fefda6165d9" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作流程</font></font></a></li>
<li><a href="https://medium.com/neuml/running-at-scale-with-txtai-71196cdd99f9" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大规模运行 txtai</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://neuml.github.io/txtai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供有关 txtai 的完整文档，</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包括嵌入、管道、工作流、API 的配置设置以及常见问题的常见问题解答。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于那些想要为 txtai 做出贡献的人，请参阅</font></font><a href="https://github.com/neuml/.github/blob/master/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</article></div>

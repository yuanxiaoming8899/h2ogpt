<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2oGPT</font></font></h1><a id="user-content-h2ogpt" class="anchor" aria-label="永久链接：h2oGPT" href="#h2ogpt"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您喜欢这个项目，请将 ★ 变成 ⭐（右上角）！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查询并总结您的文档，或者只是使用 h2oGPT（一个 Apache V2 开源项目）与本地私有 GPT LLM 聊天。</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何文档的私人</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离线数据库</font></font><a href="/h2oai/h2ogpt/blob/main/docs/README_LangChain.md#supported-datatypes"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（PDF、Excel、Word、图像、视频帧、Youtube、音频、代码、文本、MarkDown 等）</font></font></a>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用精确嵌入（大型、全 MiniLM-L6-v2 等）的</font><strong><font style="vertical-align: inherit;">持久数据库（Chroma、Weaviate 或内存中 FAISS）</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用指令调整的 LLM有效</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">利用上下文（不需要 LangChain 的少样本方法）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并行</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">汇总和提取，13B LLaMa2模型达到每秒80个token的输出</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HYDE</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（假设文档嵌入）用于基于 LLM 响应增强检索</font></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持多种</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型（LLaMa2、Mistral、Falcon、Vicuna、WizardLM。带 AutoGPTQ、4 位/8 位、LORA 等）
</font></font><ul dir="auto">
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HF 和 LLaMa.cpp GGML 模型的</font><strong><font style="vertical-align: inherit;">GPU</font></strong><font style="vertical-align: inherit;">支持，以及使用 HF、LLaMa.cpp 和 GPT4ALL 模型的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU支持</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font><a href="https://github.com/tomaarsen/attention_sinks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任意长</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成的</font><strong><font style="vertical-align: inherit;">注意力接收器</font></strong><font style="vertical-align: inherit;">（LLaMa-2、Mistral、MPT、Pythia、Falcon 等）</font></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UI</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 CLI 以及所有模型的流式传输
</font></font><ul dir="auto">
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 UI</font><strong><font style="vertical-align: inherit;">上传</font></strong><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看文档（控制多个协作或个人收藏）</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视觉型号</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVa、Claude-3、Gemini-Pro-Vision、GPT-4-Vision</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像生成</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定扩散（sdxl-turbo、sdxl）和 PlaygroundAI (playv2)</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Whisper 进行语音 STT</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和流音频转换</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 MIT 许可的 Microsoft Speech T5 进行语音 TTS，</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有多种语音和流式音频转换功能</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 MPL2 许可的 TTS 的语音 TTS</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，包括语音克隆和流音频转换</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AI助手语音控制模式</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，免提控制h2oGPT聊天</font></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同时针对多个模型进行</font><strong><font style="vertical-align: inherit;">烘焙UI 模式</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 UI</font><strong><font style="vertical-align: inherit;">轻松下载模型工件并控制 LLaMa.cpp 等模型</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 Native 或 Google OAuth 通过用户/密码在 UI 中</font><strong><font style="vertical-align: inherit;">进行身份验证</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过用户/密码在 UI 中</font><strong><font style="vertical-align: inherit;">保存状态</font></strong></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux、Docker、macOS 和 Windows</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持
</font></font><ul dir="auto">
<li><a href="#windows-1011-64-bit-with-full-document-qa-capability"><strong><font style="vertical-align: inherit;"></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 Windows 10 64 位（CPU/CUDA）的</font><a href="#windows-1011-64-bit-with-full-document-qa-capability"><strong><font style="vertical-align: inherit;">简易 Windows 安装程序</font></strong></a></font></li>
<li><a href="#macos-cpum1m2-with-full-document-qa-capability"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 macOS 的简易 macOS 安装程序</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（CPU/M1/M2）</font></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理服务器</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持（oLLaMa、HF TGI 服务器、vLLM、Gradio、ExLLaMa、Replicate、OpenAI、Azure OpenAI、Anthropic）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">符合 OpenAI 标准</font></font></strong>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器代理 API（h2oGPT 充当 OpenAI 服务器的直接替代品）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 客户端 API（与 Gradio 服务器对话）</font></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过代码块提取可使用任何模型的</font><strong><font style="vertical-align: inherit;">JSON 模式</font></strong><font style="vertical-align: inherit;">。还支持 MistralAI JSON 模式、通过具有严格 Schema 的函数调用的 Claude-3、通过 JSON 模式的 OpenAI 和通过具有严格 Schema 的guided_json 的 vLLM</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络搜索</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与聊天和文档问答集成</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">搜索代理</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、文档问答、Python 代码、CSV 框架（实验性，目前最好使用 OpenAI）</font></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用奖励模型</font><strong><font style="vertical-align: inherit;">评估绩效</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">经过 1000 多个单元和集成测试，耗时超过 4 个 GPU 小时，保持</font><strong><font style="vertical-align: inherit;">质量</font></strong></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用</font></font></h3><a id="user-content-get-started" class="anchor" aria-label="永久链接：开始" href="#get-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://raw.githubusercontent.com/h2oai/h2ogpt/main/LICENSE" rel="nofollow"><img src="https://camo.githubusercontent.com/8ca9fc33de08a9b6a9cace06d3ab29bb9f623daf684e8a36b99e167263004133/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f4e56494449412f6e76696469612d646f636b65723f7374796c653d666c61742d737175617265" alt="GitHub 许可证" data-canonical-src="https://img.shields.io/github/license/NVIDIA/nvidia-docker?style=flat-square" style="max-width: 100%;"></a>
<a href="https://github.com/h2oai/h2ogpt/blob/main/docs/README_LINUX.md"><img src="https://camo.githubusercontent.com/7eefb2ba052806d8a9ce69863c2eeb3b03cd5935ead7bd2e9245ae2e705a1adf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e75782d4643433632343f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e7578266c6f676f436f6c6f723d626c61636b" alt="Linux" data-canonical-src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=black" style="max-width: 100%;"></a>
<a href="https://github.com/h2oai/h2ogpt/blob/main/docs/README_MACOS.md"><img src="https://camo.githubusercontent.com/02ad0a4530e3be8b708a7793a641add82aa4df8dd9987cc50d5c38ba609ea382/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d61632532306f732d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d6d61636f73266c6f676f436f6c6f723d463046304630" alt="苹果系统" data-canonical-src="https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&amp;logo=macos&amp;logoColor=F0F0F0" style="max-width: 100%;"></a>
<a href="https://github.com/h2oai/h2ogpt/blob/main/docs/README_WINDOWS.md"><img src="https://camo.githubusercontent.com/c292429e232884db22e86c2ea2ea7695bc49dc4ae13344003a95879eeb7425d8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f57696e646f77732d3030373844363f7374796c653d666f722d7468652d6261646765266c6f676f3d77696e646f7773266c6f676f436f6c6f723d7768697465" alt="视窗" data-canonical-src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&amp;logo=windows&amp;logoColor=white" style="max-width: 100%;"></a>
<a href="https://github.com/h2oai/h2ogpt/blob/main/docs/README_DOCKER.md"><img src="https://camo.githubusercontent.com/8396abd667a0eca7d28cdb29ec63b6bf29a7854c7c3d467e6ece648c7e9b81e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d2532333064623765642e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465" alt="码头工人" data-canonical-src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&amp;logo=docker&amp;logoColor=white" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要快速尝试具有有限文档问答功能的 h2oGPT，请创建一个新的 Python 3.10 环境并运行：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU 或 MAC (M1/M2)：
</font></font><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> for windows/mac use "set" or relevant environment setting mechanism</span>
<span class="pl-k">export</span> PIP_EXTRA_INDEX_URL=<span class="pl-s"><span class="pl-pds">"</span>https://download.pytorch.org/whl/cpu<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# for windows/mac use &quot;set&quot; or relevant environment setting mechanism
export PIP_EXTRA_INDEX_URL=&quot;https://download.pytorch.org/whl/cpu&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux/Windows CPU/CUDA/ROC：
</font></font><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> for windows/mac use "set" or relevant environment setting mechanism</span>
<span class="pl-k">export</span> PIP_EXTRA_INDEX_URL=<span class="pl-s"><span class="pl-pds">"</span>https://download.pytorch.org/whl/cu121 https://huggingface.github.io/autogptq-index/whl/cu121<span class="pl-pds">"</span></span>
<span class="pl-c"><span class="pl-c">#</span> for cu118 use export PIP_EXTRA_INDEX_URL="https://download.pytorch.org/whl/cu118 https://huggingface.github.io/autogptq-index/whl/cu118"</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# for windows/mac use &quot;set&quot; or relevant environment setting mechanism
export PIP_EXTRA_INDEX_URL=&quot;https://download.pytorch.org/whl/cu121 https://huggingface.github.io/autogptq-index/whl/cu121&quot;
# for cu118 use export PIP_EXTRA_INDEX_URL=&quot;https://download.pytorch.org/whl/cu118 https://huggingface.github.io/autogptq-index/whl/cu118&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/abetlen/llama-cpp-python?tab=readme-ov-file#supported-backends"><font style="vertical-align: inherit;">然后根据llama_cpp_python 后端文档</font></a><font style="vertical-align: inherit;">更改</font></font><code>CMAKE_ARGS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您拥有的系统，选择您的 llama_cpp_python 选项</font><font style="vertical-align: inherit;">。例如 Linux 上的 CUDA：</font></font><a href="https://github.com/abetlen/llama-cpp-python?tab=readme-ov-file#supported-backends"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">export</span> LLAMA_CUBLAS=1
<span class="pl-k">export</span> CMAKE_ARGS=<span class="pl-s"><span class="pl-pds">"</span>-DLLAMA_CUBLAS=on -DCMAKE_CUDA_ARCHITECTURES=all<span class="pl-pds">"</span></span>
<span class="pl-k">export</span> FORCE_CMAKE=1</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="export LLAMA_CUBLAS=1
export CMAKE_ARGS=&quot;-DLLAMA_CUBLAS=on -DCMAKE_CUDA_ARCHITECTURES=all&quot;
export FORCE_CMAKE=1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，由于某种原因，如果不添加所有 cuda 拱门，llama_cpp_python 将会失败，并且使用所有这些拱门进行构建确实需要一些时间。 Windows CUDA：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre lang="cmdline" class="notranslate"><code>set CMAKE_ARGS=-DLLAMA_CUBLAS=on -DCMAKE_CUDA_ARCHITECTURES=all
set LLAMA_CUBLAS=1
set FORCE_CMAKE=1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="set CMAKE_ARGS=-DLLAMA_CUBLAS=on -DCMAKE_CUDA_ARCHITECTURES=all
set LLAMA_CUBLAS=1
set FORCE_CMAKE=1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，由于某种原因，如果不添加所有 cuda 拱门，llama_cpp_python 将会失败，并且使用所有这些拱门进行构建确实需要一些时间。金属M1/M2：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">export</span> CMAKE_ARGS=<span class="pl-s"><span class="pl-pds">"</span>-DLLAMA_METAL=on<span class="pl-pds">"</span></span>
<span class="pl-k">export</span> FORCE_CMAKE=1</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="export CMAKE_ARGS=&quot;-DLLAMA_METAL=on&quot;
export FORCE_CMAKE=1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后在任意系统上运行以下命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/h2oai/h2ogpt.git
<span class="pl-c1">cd</span> h2ogpt
pip install -r requirements.txt
pip install -r reqs_optional/requirements_optional_langchain.txt

pip uninstall llama_cpp_python llama_cpp_python_cuda -y
pip install -r reqs_optional/requirements_optional_llamacpp_gpt4all.txt --no-cache-dir

pip install -r reqs_optional/requirements_optional_langchain.urls.txt
<span class="pl-c"><span class="pl-c">#</span> GPL, only run next line if that is ok:</span>
pip install -r reqs_optional/requirements_optional_langchain.gpllike.txt

<span class="pl-c"><span class="pl-c">#</span> choose up to 32768 if have enough GPU memory:</span>
python generate.py --base_model=TheBloke/Mistral-7B-Instruct-v0.2-GGUF --prompt_type=mistral --max_seq_len=4096</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/h2oai/h2ogpt.git
cd h2ogpt
pip install -r requirements.txt
pip install -r reqs_optional/requirements_optional_langchain.txt

pip uninstall llama_cpp_python llama_cpp_python_cuda -y
pip install -r reqs_optional/requirements_optional_llamacpp_gpt4all.txt --no-cache-dir

pip install -r reqs_optional/requirements_optional_langchain.urls.txt
# GPL, only run next line if that is ok:
pip install -r reqs_optional/requirements_optional_langchain.gpllike.txt

# choose up to 32768 if have enough GPU memory:
python generate.py --base_model=TheBloke/Mistral-7B-Instruct-v0.2-GGUF --prompt_type=mistral --max_seq_len=4096" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="http://127.0.0.1:7860" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接下来，通过访问http://127.0.0.1:7860</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="http://localhost:7860" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:7860</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转到浏览器</font><font style="vertical-align: inherit;">。选择13B是比7B更好的型号。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们建议大多数小型 GPU 系统使用量化模型，例如</font><font style="vertical-align: inherit;">适用于 9GB 以上 GPU 内存的</font></font><a href="https://huggingface.co/TheBloke/Llama-2-7b-Chat-GGUF/resolve/main/llama-2-7b-chat.Q6_K.gguf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMa-2-7B-Chat-GGUF或较大的模型，例如</font></font></a><font style="vertical-align: inherit;"></font><a href="https://huggingface.co/TheBloke/Llama-2-7b-Chat-GGUF/resolve/main/llama-2-13b-chat.Q6_K.gguf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMa-2-13B-Chat-GGUF</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（如果您有 16GB 以上 GPU 内存）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="/h2oai/h2ogpt/blob/main/docs/README_offline.md#tldr"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离线</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以了解如何离线运行 h2oGPT。</font></font></p>
<hr>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，对于所有平台，某些包（例如 DocTR、Unstructed、BLIP、Stable Diffusion 等）会在运行时下载模型，这似乎会延迟 UI 中的操作。进度显示在控制台日志中。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 10/11 64 位，具有完整的文档问答功能</font></font></h4><a id="user-content-windows-1011-64-bit-with-full-document-qa-capability" class="anchor" aria-label="永久链接：具有完整文档问答功能的 Windows 10/11 64 位" href="#windows-1011-64-bit-with-full-document-qa-capability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一键安装程序</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU 或 GPU：下载</font></font><a href="https://h2o-release.s3.amazonaws.com/h2ogpt/Jan2024/h2oGPT_0.0.1.exe" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2oGPT Windows 安装程序</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（1.3GB 文件）
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装后，请随意将图标的起始目录从 更改为</font></font><code>%HOMEDRIVE%\%HOMEPATH%</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（例如），</font></font><code>%HOMEDRIVE%\%HOMEPATH%\h2ogpt_data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以便所有创建的文件（如数据库）都转到那里。所有保存的路径都是相对于该路径的。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU：单击“开始”菜单中的 h2oGPT 图标。如果包含许多可选包，请等待大约 15 秒在浏览器中打开。默认情况下，浏览器将使用实际的本地 IP 地址启动，而不是 localhost。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPU：开始之前，运行以下命令（替换</font></font><code>pseud</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您的用户）：
</font></font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>C:\Users\pseud\AppData\Local\Programs\h2oGPT\Python\python.exe -m pip uninstall -y torch
C:\Users\pseud\AppData\Local\Programs\h2oGPT\Python\python.exe -m pip install https://h2o-release.s3.amazonaws.com/h2ogpt/torch-2.1.2%2Bcu118-cp310-cp310-win_amd64.whl
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="C:\Users\pseud\AppData\Local\Programs\h2oGPT\Python\python.exe -m pip uninstall -y torch
C:\Users\pseud\AppData\Local\Programs\h2oGPT\Python\python.exe -m pip install https://h2o-release.s3.amazonaws.com/h2ogpt/torch-2.1.2%2Bcu118-cp310-cp310-win_amd64.whl" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
现在单击“开始”菜单中的 h2oGPT 图标。如果包含许多可选包，请等待大约 20 秒在浏览器中打开。默认情况下，浏览器将使用实际的本地 IP 地址启动，而不是 localhost。
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他一些用户可能有位于此处的 python </font></font><code>C:\Program Files (x86)\h2oGPT\Python\python.exe</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要调试任何问题，请运行以下命令（替换</font></font><code>pseud</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您的用户）：
</font></font><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>C:\Users\pseud\AppData\Local\Programs\h2oGPT\Python\python.exe "C:\Users\pseud\AppData\Local\Programs\h2oGPT\h2oGPT.launch.pyw"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="C:\Users\pseud\AppData\Local\Programs\h2oGPT\Python\python.exe &quot;C:\Users\pseud\AppData\Local\Programs\h2oGPT\h2oGPT.launch.pyw&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
任何启动异常都会附加到日志中，例如</font></font><code>C:\Users\pseud\h2ogpt_exception.log</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要控制启动，请调整 python 启动文件，例如针对用户</font></font><code>pseud</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><code>C:\Users\pseud\AppData\Local\Programs\h2oGPT\pkgs\win_run_app.py</code></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此 Python 代码中，在调用 main_h2ogpt() 之前的任意位置设置 ENV
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如</font></font><code>os.environ['name'] = 'value'</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，例如</font></font><code>os.environ['n_jobs'] = '10'</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（必须始终是字符串）。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以更改环境变量，例如：
</font></font><ul dir="auto">
<li><code>n_jobs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：各种任务的核心数量</font></font></li>
<li><code>OMP_NUM_THREADS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMa 的线程数</font></font></li>
<li><code>CUDA_VISIBLE_DEVICES</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用哪些 GPU。建议设置为单个快速 GPU，例如，</font></font><code>CUDA_VISIBLE_DEVICES=0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果有多个 GPU。请注意，UI 无法控制 LLaMa 模型使用哪些 GPU（或 CPU 模式）。</font></font></li>
<li><font style="vertical-align: inherit;"></font><code>python generate.py --help</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量设置为 的</font><font style="vertical-align: inherit;">任何 CLI 参数</font></font><code>h2ogpt_x</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，例如</font></font><code>h2ogpt_h2ocolors</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置为</font></font><code>False</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 env 设置</font></font><code>h2ogpt_server_name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 LAN 的实际 IP 地址以查看应用程序，例如，</font></font><code>h2ogpt_server_name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>192.168.1.172</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">激活了 Windows Defender，则允许通过防火墙进行访问。</font></font></li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人们可以调整已安装的 h2oGPT 代码，例如</font></font><code>C:\Users\pseud\AppData\Local\Programs\h2oGPT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要终止该应用程序，请转到“系统”选项卡，单击“管理”，然后单击“关闭 h2oGPT”。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果启动失败，请作为控制台运行并检查错误，例如并终止任何旧的 Python 进程。</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><a href="/h2oai/h2ogpt/blob/main/docs/README_WINDOWS.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完整的 Windows 10/11 手动安装脚本</font></font></a></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于安装的单个</font></font><code>.bat</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件（如果不跳过任何可选包，大约需要 9GB 的磁盘空间）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐基本 Conda env，它允许 DocTR 需要 pygobject，否则不支持（除了</font></font><code>mysys2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2oGPT 无法使用）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还允许使用 Coqui 的 TTS 包，否则一键安装程序当前未启用该包。</font></font></li>
</ul>
</li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux (CPU/CUDA) 具有完整的文档 Q/A 功能</font></font></h4><a id="user-content-linux-cpucuda-with-full-document-qa-capability" class="anchor" aria-label="永久链接：具有完整文档 Q/A 功能的 Linux (CPU/CUDA)" href="#linux-cpucuda-with-full-document-qa-capability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_DOCKER.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 构建和运行文档</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_LINUX.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux 手动安装和运行文档</font></font></a></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有完整文档问答功能的 macOS (CPU/M1/M2)</font></font></h4><a id="user-content-macos-cpum1m2-with-full-document-qa-capability" class="anchor" aria-label="永久链接：具有完整文档问答功能的 macOS (CPU/M1/M2)" href="#macos-cpum1m2-with-full-document-qa-capability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一键安装程序（实验性的，可能会发生变化，我们尚未测试这些安装程序的每一项功能，我们鼓励社区尝试它们并报告任何问题）</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年 3 月 7 日</font></font></p>
<ul dir="auto">
<li><a href="https://h2o-release.s3.amazonaws.com/h2ogpt/Mar2024/h2ogpt-osx-m1-cpu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2ogpt-osx-m1-cpu</font></font></a></li>
<li><a href="https://h2o-release.s3.amazonaws.com/h2ogpt/Mar2024/h2ogpt-osx-m1-gpu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2ogpt-osx-m1-gpu</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 11 月 8 日</font></font></p>
<ul dir="auto">
<li><a href="https://h2o-release.s3.amazonaws.com/h2ogpt/Nov2023/h2ogpt-osx-m1-cpu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2ogpt-osx-m1-cpu</font></font></a></li>
<li><a href="https://h2o-release.s3.amazonaws.com/h2ogpt/Nov2023/h2ogpt-osx-m1-gpu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2ogpt-osx-m1-gpu</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载可运行文件并从 Finder 打开它。解压缩并运行该应用程序将需要几分钟的时间。这些一键安装程序是实验性的。通过</font></font><a href="https://github.com/h2oai/h2ogpt/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/h2oai/h2ogpt/issues</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告重现步骤的任何问题</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序包未签名。如果您在运行应用程序时遇到任何问题，请运行以下命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ xattr -dr com.apple.quarantine {file-path}/h2ogpt-osx-m1-gpu
$ chmod +x {file-path}/h2ogpt-osx-m1-gpu</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ xattr -dr com.apple.quarantine {file-path}/h2ogpt-osx-m1-gpu
$ chmod +x {file-path}/h2ogpt-osx-m1-gpu" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><a href="/h2oai/h2ogpt/blob/main/docs/README_MACOS.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 手动安装和运行文档</font></font></a></p>
</li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例模型</font></font></h4><a id="user-content-example-models" class="anchor" aria-label="永久链接：示例模型" href="#example-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://huggingface.co/h2oai/h2ogpt-4096-llama2-70b-chat" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用时使用约 48GB/GPU 的 TGI/vLLM 实现 16 位的</font><a href="https://huggingface.co/h2oai/h2ogpt-4096-llama2-70b-chat" rel="nofollow"><font style="vertical-align: inherit;">最高准确度和速度（4xA100 高并发，2xA100 低并发）</font></a></font></li>
<li><a href="https://huggingface.co/h2oai/h2ogpt-gm-oasst1-en-2048-falcon-40b-v2" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用时使用约 45GB/GPU 的 TGI/vLLM 实现 16 位的</font><a href="https://huggingface.co/h2oai/h2ogpt-gm-oasst1-en-2048-falcon-40b-v2" rel="nofollow"><font style="vertical-align: inherit;">中等精度(2xA100)</font></a></font></li>
<li><a href="https://huggingface.co/TheBloke/Llama-2-13B-Chat-GGUF" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存配置小，精度良好</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">16GB GPU（如果完全 GPU 卸载）</font></font></li>
<li><a href="https://huggingface.co/h2oai/h2ogpt-4096-llama2-13b-chat" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用时使用 ~45GB/GPU 的 TGI/vLLM</font><a href="https://huggingface.co/h2oai/h2ogpt-4096-llama2-13b-chat" rel="nofollow"><font style="vertical-align: inherit;">平衡精度和大小(1xA100)</font></a></font></li>
<li><a href="https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGUF" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最小或 CPU 友好的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">32GB 系统内存或 9GB GPU（如果完全 GPU 卸载）</font></font></li>
<li><a href="https://huggingface.co/TheBloke/Llama-2-70B-chat-AWQ" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最适合使用 g5.12xlarge</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> AWQ LLaMa 70B 使用 4*A10G 使用 vLLM 的 4* A10G</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPU</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式需要通过 Torch 和 Transformer 提供 CUDA 支持。 16 位的 7B/13B 模型使用 14GB/26GB GPU 内存来存储权重（每个权重 2 个字节）。当询问有关文档的问题时，4 位精度（bitsandbytes、AWQ、GPTQ 等）等压缩可以进一步将内存需求降低至 6GB 以下。 （有关详细信息，请参阅</font></font><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#low-memory-mode"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低内存模式</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。）</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式使用GPT4ALL 和LLaMa.cpp，例如gpt4all-j，在典型使用中需要大约14GB 的系统RAM。</font></font></p>
<hr>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现场演示</font></font></h3><a id="user-content-live-demos" class="anchor" aria-label="永久链接：现场演示" href="#live-demos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://gpt.h2o.ai/" rel="nofollow"><img src="/h2oai/h2ogpt/raw/main/docs/img-small.png" alt="img-小.png" style="max-width: 100%;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实时 h2oGPT 文档问答演示</font></font></a></li>
<li><a href="https://huggingface.co/spaces/h2oai/h2ogpt-chatbot" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗 实时 h2oGPT 聊天演示 1</font></font></a></li>
<li><a href="https://huggingface.co/spaces/h2oai/h2ogpt-chatbot2" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤗 实时 h2oGPT 聊天演示 2</font></font></a></li>
<li><a href="https://colab.research.google.com/drive/13RiBdAFZ6xqDwDKfW6BG_-tXfXiqPNQe?usp=sharing" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2oGPT CPU</font></font></a></li>
<li><a href="https://colab.research.google.com/drive/143-KFHs2iCqXTQLI2pFCDiR69z0dR8iE?usp=sharing" rel="nofollow"><img src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">h2oGPT GPU</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总结和生成的推理基准</font></font></h3><a id="user-content-inference-benchmarks-for-summarization--generation" class="anchor" aria-label="永久链接：总结和生成的推理基准" href="#inference-benchmarks-for-summarization--generation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/h2oai/h2ogpt/blob/main/benchmarks/perf.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Llama2 的基准结果</font></font></a></li>
<li><a href="https://github.com/h2oai/h2ogpt/blob/main/tests/test_perf_benchmarks.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pytest 创建基准测试结果</font></font></a></li>
<li><a href="https://github.com/h2oai/h2ogpt/blob/main/benchmarks/perf.json"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">原始基准测试结果 (JSON)</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资源</font></font></h3><a id="user-content-resources" class="anchor" aria-label="永久链接：资源" href="#resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://discord.gg/WKhYMWcVbq" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不和谐</font></font></a></li>
<li><a href="https://huggingface.co/h2oai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型（LLaMa-2、Falcon 40 等）位于🤗</font></font></a></li>
<li><a href="https://www.youtube.com/watch?v=Coj72EzmX20" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube：100% 离线 ChatGPT 替代方案？</font></font></a></li>
<li><a href="https://www.youtube.com/watch?v=FTm5C_vV_EY" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube：终极开源 LLM 对决（测试了 6 个模型）- 令人惊讶的结果！</font></font></a></li>
<li><a href="https://www.youtube.com/watch?v=H8Dx-iUY49s" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube：Blazing Fast Falcon 40b 🚀 未经审查、开源、完全托管、与您的文档聊天</font></font></a></li>
<li><a href="https://arxiv.org/pdf/2306.08161.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术论文：https://arxiv.org/pdf/2306.08161.pdf</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伙伴</font></font></h3><a id="user-content-partners" class="anchor" aria-label="永久链接： 合作伙伴" href="#partners"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://evalgpt.ai/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/h2oai/h2o-LLM-eval"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用h2o-LLM-eval</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对指导/聊天模型进行 GPT-4 Elo 评估的</font><a href="https://evalgpt.ai/" rel="nofollow"><font style="vertical-align: inherit;">实时排行榜</font></a><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><a href="https://github.com/h2oai/h2o-llmstudio"><font style="vertical-align: inherit;">使用H2O LLM Studio</font></a><font style="vertical-align: inherit;">进行高级微调</font></font><a href="https://github.com/h2oai/h2o-llmstudio"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视频演示</font></font></h3><a id="user-content-video-demo" class="anchor" aria-label="永久链接：视频演示" href="#video-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<details open="" class="details-reset border rounded-2">
  <summary class="px-3 py-2">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-camera-video">
    <path d="M16 3.75v8.5a.75.75 0 0 1-1.136.643L11 10.575v.675A1.75 1.75 0 0 1 9.25 13h-7.5A1.75 1.75 0 0 1 0 11.25v-6.5C0 3.784.784 3 1.75 3h7.5c.966 0 1.75.784 1.75 1.75v.675l3.864-2.318A.75.75 0 0 1 16 3.75Zm-6.5 1a.25.25 0 0 0-.25-.25h-7.5a.25.25 0 0 0-.25.25v6.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-6.5ZM11 8.825l3.5 2.1v-5.85l-3.5 2.1Z"></path>
</svg>
    <span aria-label="视频说明demo2.mp4" class="m-1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示2.mp4</font></font></span>
    <span class="dropdown-caret"></span>
  </summary>

  <video src="https://private-user-images.githubusercontent.com/2249614/253246405-2f805035-2c85-42fb-807f-fd0bca79abc6.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMxNzExMjYsIm5iZiI6MTcxMzE3MDgyNiwicGF0aCI6Ii8yMjQ5NjE0LzI1MzI0NjQwNS0yZjgwNTAzNS0yYzg1LTQyZmItODA3Zi1mZDBiY2E3OWFiYzYubXA0P1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDQxNSUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDA0MTVUMDg0NzA2WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZjQ1YjYyOGNjOTBjMTlkZGU4ZTI5NGM0YzExNTExMTVhYzYyNTkzYTM2ZGM0ODMyYWE4MjNjNTgyZDE4MTkyMyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.I1kdycC38QpIAnxQPJjMMJrGDRJxPTw96KhVW45Zclk" data-canonical-src="https://private-user-images.githubusercontent.com/2249614/253246405-2f805035-2c85-42fb-807f-fd0bca79abc6.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMxNzExMjYsIm5iZiI6MTcxMzE3MDgyNiwicGF0aCI6Ii8yMjQ5NjE0LzI1MzI0NjQwNS0yZjgwNTAzNS0yYzg1LTQyZmItODA3Zi1mZDBiY2E3OWFiYzYubXA0P1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDQxNSUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDA0MTVUMDg0NzA2WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZjQ1YjYyOGNjOTBjMTlkZGU4ZTI5NGM0YzExNTExMTVhYzYyNTkzYTM2ZGM0ODMyYWE4MjNjNTgyZDE4MTkyMyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.I1kdycC38QpIAnxQPJjMMJrGDRJxPTw96KhVW45Zclk" controls="controls" muted="muted" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px; min-height: 200px">

  </video>
</details>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube 4K 版本：</font></font><a href="https://www.youtube.com/watch?v=_iktbj4obAI" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.youtube.com/watch?v=_iktbj4obAI</font></font></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档指南</font></font></h3><a id="user-content-docs-guide" class="anchor" aria-label="永久链接：文档指南" href="#docs-guide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<ul dir="auto">
<li><a href="#get-started"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用</font></font></a>
<ul dir="auto">
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_LINUX.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux（CPU 或 CUDA）</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_MACOS.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS（CPU 或 M1/M2）</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_WINDOWS.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 10/11（CPU 或 CUDA）</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_GPU.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPU（CUDA、AutoGPTQ、exllama）运行详细信息</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_CPU.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU运行详情</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_CLI.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLI 聊天</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_ui.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">渐变用户界面</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_CLIENT.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端 API（Gradio、OpenAI 兼容）</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_InferenceServers.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理服务器（oLLaMa、HF TGI 服务器、vLLM、Groq、Anthropic、Google、Mistral、Gradio、ExLLaMa、Replicate、OpenAI、Azure OpenAI）</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_WHEEL.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建Python轮</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_offline.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离线安装</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#low-memory-mode"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记忆不足</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_DOCKER.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></a></li>
</ul>
</li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_LangChain.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浪链文档支持</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_LangChain.md#what-is-h2ogpts-langchain-integration-like"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 PrivateGPT 等人相比。</font></font></a></li>
<li><a href="#roadmap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></a></li>
<li><a href="#development"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展</font></font></a></li>
<li><a href="#help"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助</font></font></a>
<ul dir="auto">
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_LangChain.md#supported-datatypes"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的 LangChain 文件类型</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_LangChain.md#database-creation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLI 数据库控制</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常问问题</font></font></a>
<ul dir="auto">
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#model-usage-notes"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号使用注意事项</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#adding-models"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加LLM模型（包括使用GGUF和注意力池）</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#add-new-embedding-model"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加嵌入模型</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#adding-prompt-templates"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加提示</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#in-context-learning-via-prompt-engineering"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情境学习</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#multiple-gpus"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多个 GPU</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#low-memory-mode"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存使用率低</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#what-envs-can-i-pass-to-control-h2ogpt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#https-access-for-server-and-client"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器和客户端的 HTTPS 访问</font></font></a></li>
</ul>
</li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/LINKS.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有用的链接</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FINETUNE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微调</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/TRITON.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">海卫一</font></font></a></li>
<li><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md#commercial-viability"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商业可行性</font></font></a></li>
</ul>
</li>
<li><a href="#acknowledgements"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></a></li>
<li><a href="#why-h2oai"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么选择 H2O.ai？</font></font></a></li>
<li><a href="#disclaimer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实验特点</font></font></h3><a id="user-content-experimental-features" class="anchor" aria-label="永久链接：实验功能" href="#experimental-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些不是正常安装说明的一部分，并且是实验性的。</font></font></p>
<ul dir="auto">
<li><a href="/h2oai/h2ogpt/blob/main/docs/README_Agents.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特工</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">——正在进行 Alpha 测试。最适合 OpenAI，但有时也会失败。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></h3><a id="user-content-roadmap" class="anchor" aria-label="永久链接：路线图" href="#roadmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将代码和由此产生的法学硕士与下游应用程序和低/无代码平台集成</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><a href="https://github.com/OpenBMB/ToolBench"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ToolBench等其他 API 补充 h2oGPT 聊天机器人</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">增强模型的代码补全、推理和数学能力，确保事实正确性，最大限度减少幻觉，避免重复输出</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 SQL 和 CSV 问题/答案添加更好的代理</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展</font></font></h3><a id="user-content-development" class="anchor" aria-label="永久链接： 发展" href="#development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要创建用于训练和生成的开发环境，请按照</font></font><a href="/h2oai/h2ogpt/blob/main/docs/INSTALL.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行操作。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要对您的数据微调任何 LLM 模型，请按照</font></font><a href="/h2oai/h2ogpt/blob/main/docs/FINETUNE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微调说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行操作。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 h2oGPT 测试：
</font></font><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install requirements-parser pytest-instafail pytest-random-order playsound==1.3.0
conda install -c conda-forge gst-python
sudo apt-get install gstreamer-1.0
pip install pygame
pytest --instafail -s -v tests
<span class="pl-c"><span class="pl-c">#</span> for client tests</span>
make -C client setup
make -C client build
pytest --instafail -s -v client/tests
<span class="pl-c"><span class="pl-c">#</span> for openai server test on already-running local server</span>
pytest -s -v -n 4 openai_server/test_openai_server.py::test_openai_client</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install requirements-parser pytest-instafail pytest-random-order playsound==1.3.0
conda install -c conda-forge gst-python
sudo apt-get install gstreamer-1.0
pip install pygame
pytest --instafail -s -v tests
# for client tests
make -C client setup
make -C client build
pytest --instafail -s -v client/tests
# for openai server test on already-running local server
pytest -s -v -n 4 openai_server/test_openai_server.py::test_openai_client" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
或调整/运行</font></font><code>tests/test4gpus.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以并行运行测试。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助</font></font></h3><a id="user-content-help" class="anchor" aria-label="永久链接：帮助" href="#help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><a href="/h2oai/h2ogpt/blob/main/docs/FAQ.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见问题解答</font></font></a></p>
</li>
<li>
<p dir="auto"><a href="/h2oai/h2ogpt/blob/main/docs/README_LangChain.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浪链自述文件</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关竞争对手、模型和数据集的其他背景和信息的</font><font style="vertical-align: inherit;">有用</font></font><a href="/h2oai/h2ogpt/blob/main/docs/LINKS.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接</font></font></a><font style="vertical-align: inherit;"></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h3><a id="user-content-acknowledgements" class="anchor" aria-label="永久链接：致谢" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一些训练代码基于 3 月 24 日版本的</font></font><a href="https://github.com/tloen/alpaca-lora/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Alpaca-LoRA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://open-assistant.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用OpenAssistant</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建的高质量数据</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><a href="https://www.eleuther.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EleutherAI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的基础模型。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><a href="https://laion.ai/blog/oig-dataset/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LAION</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建的 OIG 数据。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么选择 H2O.ai？</font></font></h3><a id="user-content-why-h2oai" class="anchor" aria-label="永久链接：为什么选择 H2O.ai？" href="#why-h2oai"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">H2O.ai</font><font style="vertical-align: inherit;">的</font></font><a href="https://h2o.ai/company/team/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创客</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建了多个世界一流的机器学习、深度学习和人工智能平台</font></font><a href="https://h2o.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></a><font style="vertical-align: inherit;"></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#1 企业开源机器学习平台</font></font><a href="https://github.com/h2oai/h2o-3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">H2O-3</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">世界上最好的 AutoML（自动机器学习）与</font></font><a href="https://h2o.ai/platform/ai-cloud/make/h2o-driverless-ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">H2O 无人驾驶人工智能</font></font></a></li>
<li><font style="vertical-align: inherit;"><a href="https://h2o.ai/platform/ai-cloud/make/hydrogen-torch/" rel="nofollow"><font style="vertical-align: inherit;">使用H2O 氢火炬</font></a><font style="vertical-align: inherit;">进行无代码深度学习</font></font><a href="https://h2o.ai/platform/ai-cloud/make/hydrogen-torch/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
<li><font style="vertical-align: inherit;"><a href="https://h2o.ai/platform/ai-cloud/make/document-ai/" rel="nofollow"><font style="vertical-align: inherit;">文档 AI</font></a><font style="vertical-align: inherit;">中的深度学习文档处理</font></font><a href="https://h2o.ai/platform/ai-cloud/make/document-ai/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还构建了用于部署和监控以及数据整理和治理的平台：</font></font></p>
<ul dir="auto">
<li><a href="https://h2o.ai/platform/ai-cloud/operate/h2o-mlops/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">H2O MLOps</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于大规模部署和监控模型</font></font></li>
<li><a href="https://h2o.ai/platform/ai-cloud/make/feature-store/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">H2O 功能商店</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 AT&amp;T 合作</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源低代码人工智能应用程序开发框架</font></font><a href="https://wave.h2o.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wave</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://nitro.h2o.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nitro</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源Python</font></font><a href="https://github.com/h2oai/datatable/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据表</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（H2O Driverless AI特征工程引擎）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的许多客户正在创建模型并在企业范围内大规模部署</font></font><a href="https://h2o.ai/platform/ai-cloud/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">H2O AI Cloud</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多云或本地</font></font></li>
<li><a href="https://h2o.ai/platform/ai-cloud/managed" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托管云 (SaaS)</font></font></a></li>
<li><a href="https://h2o.ai/platform/ai-cloud/hybrid" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合云</font></font></a></li>
<li><a href="https://docs.h2o.ai/h2o-ai-cloud/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工智能应用商店</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们很自豪有超过 25 名（全球 280 名）</font></font><a href="https://h2o.ai/company/team/kaggle-grandmasters/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kaggle 大师</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 H2O 视为自己的家，其中包括三位已跻身世界第一的 Kaggle 大师。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></h3><a id="user-content-disclaimer" class="anchor" aria-label="永久链接：免责声明" href="#disclaimer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在使用此存储库中提供的大型语言模型之前，请仔细阅读此免责声明。您使用该模型即表示您同意以下条款和条件。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">偏见和攻击性：大型语言模型是根据各种互联网文本数据进行训练的，这些数据可能包含偏见、种族主义、攻击性或其他不适当的内容。通过使用此模型，您承认并接受生成的内容有时可能会表现出偏见或产生冒犯性或不适当的内容。此存储库的开发人员不认可、支持或推广任何此类内容或观点。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">局限性：大语言模型是基于人工智能的工具，而不是人类。它可能会产生不正确、无意义或不相关的响应。用户有责任严格评估生成的内容并自行决定使用它。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用风险自负：此大型语言模型的用户必须对其使用该工具可能产生的任何后果承担全部责任。本存储库的开发者和贡献者不对因使用或误用所提供的模型而造成的任何损害、损失或伤害承担责任。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">道德考虑：鼓励用户负责任且合乎道德地使用大型语言模型。通过使用此模型，您同意不将其用于宣扬仇恨言论、歧视、骚扰或任何形式的非法或有害活动的目的。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告问题：如果您遇到大语言模型生成的任何有偏见的、冒犯性的或其他不适当的内容，请通过提供的渠道向存储库维护人员报告。您的反馈将有助于改进模型并减少潜在问题。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本免责声明的变更：本存储库的开发人员保留随时修改或更新本免责声明的权利，恕不另行通知。用户有责任定期查看免责声明，以随时了解任何更改。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过使用此存储库中提供的大型语言模型，您同意接受并遵守本免责声明中概述的条款和条件。如果您不同意本免责声明的任何部分，您应避免使用该模型及其生成的任何内容。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">明星历史</font></font></h2><a id="user-content-star-history" class="anchor" aria-label="永久链接：明星历史" href="#star-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://star-history.com/#h2oai/h2ogpt&amp;Timeline" rel="nofollow"><img src="https://camo.githubusercontent.com/2ff50ce5b5c6bfda1e418082348049b23beb14cbf42f2a704cdfce023fb05668/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d68326f61692f68326f67707426747970653d54696d656c696e65" alt="明星历史图" data-canonical-src="https://api.star-history.com/svg?repos=h2oai/h2ogpt&amp;type=Timeline" style="max-width: 100%;"></a></p>
</article></div>

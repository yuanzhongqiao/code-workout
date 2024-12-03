<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13254280" _msthash="1305">代码锻炼</h1><a id="user-content-codeworkout" class="anchor" aria-label="永久链接： CodeWorkout" href="#codeworkout" _mstaria-label="477750" _msthash="1306"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1977721928" _msthash="1307">CodeWorkout 是一个在线系统，供第一次学习编程语言的人使用。
它是一个免费的开源解决方案，用于练习小型编程问题。
学生可以在 Web 浏览器中练习有关各种编程概念的编码练习或多项选择题，并立即收到反馈。</p>
<p dir="auto" _msttexthash="2087109869" _msthash="1308">CodeWorkout 的灵感来自其他人构建的许多优秀系统，但旨在汇集早期先驱的精华，同时添加重要的新功能。
它为希望在课程中使用编码练习的教师提供全面支持，同时也为不参加有组织课程的自定进度学习者保持灵活性。</p>
<p dir="auto" _msttexthash="361038691" _msthash="1309">在 [<a href="https://codeworkout.cs.vt.edu" rel="nofollow" _istranslated="1">https://codeworkout.cs.vt.edu</a>] 试用。
如果您愿意，您可以在不注册的情况下玩。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4341103" _msthash="1310">内容</h2><a id="user-content-contents" class="anchor" aria-label="永久链接：目录" href="#contents" _mstaria-label="374413" _msthash="1311"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#setting-up-a-development-environment-using-docker" _msttexthash="42425370" _msthash="1312">使用 Docker 设置开发环境</a>
<ul dir="auto">
<li><a href="#clone-this-repository" _msttexthash="18887401" _msthash="1313">克隆此存储库</a></li>
<li><a href="#install-docker-and-build-the-containers" _msttexthash="32423885" _msthash="1314">安装 Docker 并构建容器</a></li>
<li><a href="#set-up-some-development-data" _msttexthash="27446640" _msthash="1315">设置一些开发数据</a></li>
<li><a href="#run-servers" _msttexthash="15978651" _msthash="1316">运行服务器</a></li>
<li><a href="#other-notes" _msttexthash="11584898" _msthash="1317">其他说明</a></li>
</ul>
</li>
<li><a href="#making-an-exercise" _msttexthash="15201576" _msthash="1318">进行锻炼</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="42425370" _msthash="1319">使用 Docker 设置开发环境</h2><a id="user-content-setting-up-a-development-environment-using-docker" class="anchor" aria-label="永久链接：使用 Docker 设置开发环境" href="#setting-up-a-development-environment-using-docker" _mstaria-label="2371811" _msthash="1320"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><font _mstmutation="1" _msttexthash="1455378704" _msthash="1321">注意：如果您习惯于设置 Rails 应用程序，即在自己的计算机上安装 Ruby （2.3.8）、Rails （4.2） 和 MySQL （5.7），那么您可以这样做，而不是使用 Docker。您需要将 <a href="/web-cat/code-workout/blob/master/config/database.yml" _mstmutation="1" _istranslated="1">config/database.yml</a> 中的键更改为 .</font><code>host</code><code>localhost</code></p>
</blockquote>
<p dir="auto" _msttexthash="1020830525" _msthash="1322">以下步骤将帮助使用 Docker 和 Docker Compose 为 CodeWorkout 设置开发环境。
您可以使用您选择的编辑器在自己的计算机上进行编辑;更改将反映在 Docker 容器中。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="18887401" _msthash="1323">克隆此存储库</h3><a id="user-content-clone-this-repository" class="anchor" aria-label="永久链接：克隆此仓库" href="#clone-this-repository" _mstaria-label="849862" _msthash="1324"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ git clone git@github.com:web-cat/code-workout.git
$ <span class="pl-c1">cd</span> code-workout</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ git clone git@github.com:web-cat/code-workout.git
$ cd code-workout" tabindex="0" role="button" _mstaria-label="46475" _msthash="1211">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="125431917" _msthash="1325">查看分支。大多数新更改不会直接被接受到分支中。</font><code>staging</code><code>master</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ git checkout staging</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ git checkout staging" tabindex="0" role="button" _mstaria-label="46475" _msthash="1210">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="32423885" _msthash="1326">安装 Docker 并构建容器</h3><a id="user-content-install-docker-and-build-the-containers" class="anchor" aria-label="永久链接：安装 Docker 并构建容器" href="#install-docker-and-build-the-containers" _mstaria-label="1709695" _msthash="1327"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="94531541" _msthash="1328">可以在 <a href="https://docs.docker.com/get-docker/" rel="nofollow" _istranslated="1">Docker 网站上</a>找到安装 Docker 的说明。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="786955104" _msthash="1329">这些说明是在考虑 Docker 版本的情况下编写的。我们不做任何花哨的事情，所以只要您合理地了解最新情况，一切应该都会正常进行。</font><code>19.03.8</code></p>
<p dir="auto" _msttexthash="695332989" _msthash="1330">我们使用 <a href="https://docs.docker.com/get-docker/" rel="nofollow" _istranslated="1">Docker Compose</a> 将多个容器捆绑在一起。一个用于 Web 应用程序，一个用于测试和开发数据库。
Docker Compose 自动随 Docker 一起安装。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="70826288" _msthash="1331">在该目录中，执行以下操作：</font><code>code-workout</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ docker-compose up <span class="pl-c"><span class="pl-c">#</span> build and start containers for the web application and the databases</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ docker-compose up # build and start containers for the web application and the databases" tabindex="0" role="button" _mstaria-label="46475" _msthash="1209">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="1103500957" _msthash="1332">此步骤使用提供的 <a href="/web-cat/code-workout/blob/master/Dockerfile" _mstmutation="1" _istranslated="1">Dockerfile</a> 构建容器，以安装 Ruby、Rails 和所需的依赖项。它还构建 and 容器，每个容器从 DockerHub 提取一个现成的 MySQL 镜像。设置了两个数据库：</font><code>web</code><code>db_dev</code><code>db_test</code></p>
<ul dir="auto">
<li><code>codeworkout</code><font _mstmutation="1" _msttexthash="109948904" _msthash="1333">，在容器的端口 3306 和主机上的端口 3307 上运行</font><code>db_dev</code></li>
<li><code>codeworkout_test</code><font _mstmutation="1" _msttexthash="109949268" _msthash="1334">，在容器的端口 3306 和主机上的端口 3308 上运行</font><code>db_test</code></li>
</ul>
<p dir="auto" _msttexthash="39355628" _msthash="1335">两个数据库的凭据：</p>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="16351413" _msthash="1336">用户名：</font><code>codeworkout</code></li>
<li><font _mstmutation="1" _msttexthash="13280891" _msthash="1337">残疾：</font><code>codeworkout</code></li>
</ul>
<p dir="auto" _msttexthash="355442607" _msthash="1338">首次执行此操作时，构建所有容器将花费一些时间。此命令的后续运行将仅启动现有容器。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="167473579" _msthash="1339">容器的输出将显示在您的控制台中。执行 以退出并停止容器。</font><code>Ctrl-C</code></p>
<p dir="auto" _msttexthash="213265065" _msthash="1340">如果您想在后台运行容器并取回您的终端，请执行以下操作：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ docker-compose up -d</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ docker-compose up -d" tabindex="0" role="button" _mstaria-label="46475" _msthash="1208">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="163108426" _msthash="1341">您可以停止并移除容器（或者只是停止而不移除）。</font><code>docker-compose down</code><code>docker-compose stop</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="27446640" _msthash="1342">设置一些开发数据</h3><a id="user-content-set-up-some-development-data" class="anchor" aria-label="永久链接： 设置一些开发数据" href="#set-up-some-development-data" _mstaria-label="1095978" _msthash="1343"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="357028750" _msthash="1344">下一步将设置数据库并使用虚假数据填充它以进行开发。
在计算机上的目录中执行以下操作。</font><code>code-workout</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ docker-compose run web rake db:populate</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ docker-compose run web rake db:populate" tabindex="0" role="button" _mstaria-label="46475" _msthash="1207">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="629381857" _msthash="1345">上面的命令告诉 Docker “在容器上运行命令并退出”。
此 rake 任务在 <a href="/web-cat/code-workout/blob/master/lib/tasks/sample_data.rake" _mstmutation="1" _istranslated="1">lib/tasks/sample_data.rake</a> 中定义，并按顺序运行以下任务：</font><code>rake db:populate</code><code>web</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ rake db:drop        <span class="pl-c"><span class="pl-c">#</span> drop the database</span>
$ rake db:create      <span class="pl-c"><span class="pl-c">#</span> create the database</span>
$ rake db:schema:load <span class="pl-c"><span class="pl-c">#</span> load the schema from db/schema.rb</span>
$ rake db:seed        <span class="pl-c"><span class="pl-c">#</span> load the seeded data (like timezones, seasons, etc.)</span>
$ rake db:populate    <span class="pl-c"><span class="pl-c">#</span> load sample data; this is a custom rake task</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ rake db:drop        # drop the database
$ rake db:create      # create the database
$ rake db:schema:load # load the schema from db/schema.rb
$ rake db:seed        # load the seeded data (like timezones, seasons, etc.)
$ rake db:populate    # load sample data; this is a custom rake task" tabindex="0" role="button" _mstaria-label="46475" _msthash="1206">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font _mstmutation="1" _msttexthash="200608226" _msthash="1346">在项目根目录中运行以查看可用 rake 任务的列表。<a href="https://github.com/ruby/rake" _mstmutation="1" _istranslated="1">什么是抽水？</a></font><code>rake -T</code></p>
</blockquote>
<p dir="auto"><font _mstmutation="1" _msttexthash="5458177088" _msthash="1347">初始数据库填充由 <a href="/web-cat/code-workout/blob/master/lib/tasks/sample_data.rake" _mstmutation="1" _istranslated="1">lib/tasks/sample_data.rake</a> 定义。
它使用 <a href="/web-cat/code-workout/blob/master/spec/factories" _mstmutation="1" _istranslated="1">spec/factories</a> 中定义的 factories 来生成实体。
如果您添加新的模型类并希望在数据库中生成测试数据，请添加到文件中，以便每个人都自动进行此填充。
它仅包含在开发过程中使用的 “sample/try out” 数据，它不会
显示在生产服务器上。
为所有新安装（包括 生产服务器）提供的初始数据库内容在 db/seeds.rb 中描述。</font><code>sample_data.rake</code><code>sample_data.rake</code></p>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="57634070" _msthash="1348">初始数据库包括以下账户：</p>
<ul dir="auto">
<li _msttexthash="323941488" _msthash="1349"><a href="mailto:admin@codeworkout.org" _istranslated="1">admin@codeworkout.org</a> （pass： adminadmin） 具有管理员级别的访问权限</li>
<li _msttexthash="371196631" _msthash="1350"><a href="mailto:example-1@railstutorial.org" _istranslated="1">example-1@railstutorial.org</a> （通行证： Hokiehokie），具有教练访问权限</li>
<li _msttexthash="206098620" _msthash="1351">example-*@railstutorial.org （通行证： Hokiehokie） 50 名学生</li>
</ul>
<p dir="auto" _msttexthash="51441416" _msthash="1352">它还包括以下其他对象：</p>
<ul dir="auto">
<li _msttexthash="178155211" _msthash="1353">六个学期（当年的春季、夏季 I、夏季 II、秋季和冬季），</li>
<li _msttexthash="33160556" _msthash="1354">一个组织 （VT）</li>
<li _msttexthash="38741274" _msthash="1355">一门课程 （CS 1114）</li>
<li><font _mstmutation="1" _msttexthash="76149203" _msthash="1356">两次 1114 课程（每学期一次）</font><ul dir="auto">
<li _msttexthash="251826081" _msthash="1357">一个课程设置由管理员和讲师设置
作为教师，所有其他示例帐户作为学生</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto" _msttexthash="144312246" _msthash="1358">要将数据库重置为初始状态，请执行以下操作：</p>
<ul dir="auto">
<li><code>$ cd code-workout</code></li>
<li><code>$ docker-compose run web rake db:populate</code></li>
</ul>
</li>
</ul>
<p dir="auto"><strong _msttexthash="56940468" _msthash="1359">有关设置开发数据库的说明。</strong></p>
<p dir="auto" _msttexthash="1851542043" _msthash="1360">我们直接从 <a href="/web-cat/code-workout/blob/master/db/schema.rb" _istranslated="1">db/schema.rb</a> 加载架构，因为数据库迁移往往会随着时间的推移而过时 — 运行 100 多次迁移（其中许多迁移已有数年历史）可能会遇到错误。迁移可用于进行<em _istranslated="1">新的</em>更改或撤消对架构的<em _istranslated="1">最近</em>更改。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="15978651" _msthash="1361">运行服务器</h3><a id="user-content-run-servers" class="anchor" aria-label="永久链接：运行服务器" href="#run-servers" _mstaria-label="452166" _msthash="1362"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="139836567" _msthash="1363">要运行开发服务器，请在目录中执行以下操作：</font><code>code-workout</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ docker-compose up <span class="pl-c"><span class="pl-c">#</span> this may take a minute</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ docker-compose up # this may take a minute" tabindex="0" role="button" _mstaria-label="46475" _msthash="1205">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="385336536" _msthash="1364">在浏览器中，导航到 <a href="https://localhost:9292" rel="nofollow" _mstmutation="1" _istranslated="1">https://localhost:9292</a>，您应该会看到 CodeWorkout 主页。（确保 URL 前面有。</font><code>https</code></p>
<p dir="auto" _msttexthash="139645441" _msthash="1365">您可以在自己的计算机上编辑文件;更改将反映在 Container 中。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11584898" _msthash="1366">其他说明</h3><a id="user-content-other-notes" class="anchor" aria-label="永久链接：其他说明" href="#other-notes" _mstaria-label="446914" _msthash="1367"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="870444289" _msthash="1368"><strong _mstmutation="1" _istranslated="1">注 1</strong>：由于 Rails 应用程序在容器上运行，因此你的 typical 或 commands 将如上所示运行，即 with 在它前面。例如，要生成模型，您可以执行 .</font><code>web</code><code>rails</code><code>rake</code><code>docker-compose run web</code><code>docker-compose run web rails g model MyModel</code></p>
<p dir="auto" _msttexthash="450627125" _msthash="1369"><strong _istranslated="1">注 2</strong>：要最终进入容器的 bash shell（即，通过 “SSH” 连接到服务器），请执行以下操作：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose run web bash</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="复制" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker-compose run web bash" tabindex="0" role="button" _mstaria-label="46475" _msthash="1204">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="562817515" _msthash="1370">请注意，这不会设置端口转发，因此如果您执行此操作并手动运行服务器 （），您将无法从浏览器访问它。</font><code>./runservers.sh</code></p>
<p dir="auto" _msttexthash="348434073" _msthash="1371"><strong _istranslated="1">注 3</strong>：这些文档和 Docker 设置是最新的。如果缺少、不正确或不清楚，请提交问题。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13385112" _msthash="1372">进行练习</h2><a id="user-content-making-an-exercise" class="anchor" aria-label="永久链接： 进行练习" href="#making-an-exercise" _mstaria-label="669526" _msthash="1373"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1217855210" _msthash="1374">有关如何进行练习的说明，请参阅 <a href="/web-cat/code-workout/blob/master/making_an_exercise.md" _istranslated="1">making_an_exercise.md</a>。请注意，对于大多数用户，此功能不能通过 Web 界面直接使用。如果您想向 CodeWorkout 添加练习，请与我们联系。</p>
</article></div>

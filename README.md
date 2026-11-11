<div align="center">

  <!-- 动态流体渐变头图 (原生支持 Dark / Light 模式自动切换) -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:007aff&height=180&section=header&text=Fan%20Sheng%20(fanszoro)&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Chromium%20%26%20Docling%20Contributor%20%C2%B7%20Design%20Engineering%20%C2%B7%20Full-Stack%20Builder&descSize=15&descColor=94a3b8&descAlignY=62&animation=fadeIn" />
    <img alt="Fan Sheng Banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:007aff,50:3b82f6,100:6366f1&height=180&section=header&text=Fan%20Sheng%20(fanszoro)&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Chromium%20%26%20Docling%20Contributor%20%C2%B7%20Design%20Engineering%20%C2%B7%20Full-Stack%20Builder&descSize=15&descColor=e2e8f0&descAlignY=62&animation=fadeIn" width="100%" />
  </picture>

  <!-- 顶级开源身份与个人站点徽章栏 -->
  <p>
    <a href="https://github.com/chromium/chromium/commit/2a83d013110dc0e65f1812774d61397e70bdff47">
      <img src="https://img.shields.io/badge/Chromium-Official%20Author-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chromium Official Author" />
    </a>
    <a href="https://github.com/docling-project/docling/pull/1024">
      <img src="https://img.shields.io/badge/IBM%20Docling%20(70k%2B%20%E2%98%85)-Contributor-052FAD?style=for-the-badge&logo=ai&logoColor=white" alt="Docling Contributor" />
    </a>
    <a href="https://md3.cn">
      <img src="https://img.shields.io/badge/Blog%20%26%20Portfolio-md3.cn-000000?style=for-the-badge&logo=apple&logoColor=white" alt="md3.cn" />
    </a>
    <a href="mailto:fanshengluck@gmail.com">
      <img src="https://img.shields.io/badge/Email-fanshengluck%40gmail.com-18181b?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" />
    </a>
  </p>

</div>

---

### 🏛️ Upstream Open-Source Contributions

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 <a href="https://github.com/chromium/chromium/commit/2a83d013110dc0e65f1812774d61397e70bdff47">chromium/chromium</a> <kbd>Official Author</kbd></h4>
      <p><b>Fix macOS <code>NSSharingServicePicker</code> Coordinate Offset in Remote Cocoa</b></p>
      <ul>
        <li>Root-caused a 5-year-old AppKit coordinate bug in <code>content/app_shim_remote_cocoa/sharing_service_picker.mm</code> where <code>NSWindow</code> coordinates were passed directly to view-local popover APIs when DevTools or side panels were docked.</li>
        <li>Authored and landed the fix in Chromium main (<a href="https://source.chromium.org/chromium/chromium/src/+/main:AUTHORS">listed in <code>AUTHORS</code></a>).</li>
      </ul>
      <p>
        <a href="https://github.com/chromium/chromium/commit/2a83d013110dc0e65f1812774d61397e70bdff47"><img src="https://img.shields.io/badge/Commit-2a83d013110d-2563eb?style=flat-square&logo=git&logoColor=white" alt="Commit" /></a>
        <a href="https://chromium-review.googlesource.com/c/chromium/src/+/8773427"><img src="https://img.shields.io/badge/Gerrit_CL-%238773427-10b981?style=flat-square" alt="CL 8773427" /></a>
        <a href="https://issues.chromium.org/issues/583390407"><img src="https://img.shields.io/badge/crbug-583390407-f59e0b?style=flat-square" alt="crbug" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📄 <a href="https://github.com/docling-project/docling/pull/1024">docling-project/docling</a> <kbd>70.4k ★</kbd></h4>
      <p><b>Fix Pandas Series Non-String Runtime Crash in Document Pipeline</b></p>
      <ul>
        <li>Contributed to IBM Research & LF AI's flagship GenAI document parsing engine (<b>70,000+ GitHub Stars</b>).</li>
        <li>Resolved a runtime type error when processing tabular data where Pandas <code>Series</code> contained non-string elements during document export and conversion.</li>
      </ul>
      <p>
        <a href="https://github.com/docling-project/docling/pull/1024"><img src="https://img.shields.io/badge/PR-%231024_Merged-8b5cf6?style=flat-square&logo=github&logoColor=white" alt="PR #1024" /></a>
        <img src="https://img.shields.io/github/stars/docling-project/docling?style=flat-square&logo=github&label=Repo%20Stars&color=18181b" alt="Docling Stars" />
      </p>
    </td>
  </tr>
</table>

---

### 🚀 Featured Original Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🎵 <a href="https://github.com/fanszoro/music-tagger">music-tagger</a> <kbd>v0.8.0</kbd></h4>
      <p><b>Modern Self-Hosted Music Metadata Scraper & Tag Management Hub</b></p>
      <ul>
        <li>High-performance audio library organizer with automated metadata/lyrics scraping, Bento Grid analytics dashboard, and instant multi-theme switching.</li>
        <li>Full companion <code>.nfo</code> XML generation for MVs & concerts (Kodi, Jellyfin, Plex compatible) and responsive CSS Container Query touch layouts.</li>
      </ul>
      <p>
        <a href="https://github.com/fanszoro/music-tagger"><img src="https://img.shields.io/github/stars/fanszoro/music-tagger?style=flat-square&logo=github&color=3b82f6" alt="Stars" /></a>
        <a href="https://hub.docker.com/r/fanss/music-tagger"><img src="https://img.shields.io/docker/pulls/fanss/music-tagger?style=flat-square&logo=docker&color=2496ED" alt="Docker Pulls" /></a>
        <a href="https://fanszoro.github.io/music-tagger/"><img src="https://img.shields.io/badge/Docs-Online-10b981?style=flat-square" alt="Docs" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📁 <a href="https://github.com/fanszoro/markissue">markissue</a> <kbd>AI-Native</kbd></h4>
      <p><b>Zero-Database, Markdown-Powered Agile Issue Tracker</b></p>
      <ul>
        <li>100% file-system backed (<code>.md</code> + <code>.json</code>) issue workbench designed for AI-native & Vibe Coding workflows—drop straight into any LLM context.</li>
        <li>Features optimistic locking concurrency control, file-lock scan caching, batch workflow transitions, EN/ZH auto-i18n, and 100% test coverage.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/Coverage-100%25-10b981?style=flat-square" alt="Coverage" />
        <a href="https://bf3tzdtgrlfvvhjche5nuf.streamlit.app/"><img src="https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Demo" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h4>💎 <a href="https://md3.cn">Apple HIG Modern Web & Publishing Monorepo (md3.cn)</a></h4>
      <p>
        Full-stack isomorphic content platform, EPUB digital reader, and <b>L0–L5 6D Orthogonal Design System</b> built with <b>Svelte 5 (Runes)</b> and <b>SvelteKit 3</b>. Features 181 semantic tokens, 17 derived themes, 4 optical materials (<code>regular</code>, <code>liquid</code>, <code>grouped</code>, <code>ambient</code>), compositor-thread scroll animations, and Unified AST live-code compilation.
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack & Engineering Arsenal

<div align="center">

  <p>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/C%2B%2B_%2F_Objective--C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++ / Objective-C++" />
    <img src="https://img.shields.io/badge/Svelte_5_(Runes)-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte 5" />
    <img src="https://img.shields.io/badge/SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="SvelteKit" />
    <img src="https://img.shields.io/badge/macOS_AppKit-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS AppKit" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/Docker_%26_Podman-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  </p>

</div>

---

### 📊 GitHub Telemetry

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=fanszoro&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=3b82f6&icon_color=007aff&text_color=c9d1d9" />
    <img src="https://github-readme-stats.vercel.app/api?username=fanszoro&show_icons=true&theme=default&hide_border=true&title_color=007aff&icon_color=007aff" alt="GitHub Stats" height="165" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=fanszoro&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=3b82f6&text_color=c9d1d9" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fanszoro&layout=compact&theme=default&hide_border=true&title_color=007aff" alt="Top Languages" height="165" />
  </picture>
</div>

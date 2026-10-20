<div align="center">
<h1>AI TRANSPARENCY ACT</h1>
Standardized, open-source svg and shield badges to declare the level of AI involvement in software, writing, design, and hardware projects.
<br></br>
<p align="center">
  <a href="#-about-this-project"><b>About</b></a> •
  <a href="#-note-on-voluntary-adoption"><b>Disclosure</b></a> •
  <a href="#-why"><b>Why?</b></a> •
  <a href="#-label-structure-&-taxonomy"><b>Taxonomy</b></a> •
  <a href="#-how-to-use"><b>How to use?</b></a> •
  <a href="#-contributing-&-feedback"><b>Contributing & Feedback</b></a> •
  <a href="#-license"><b>License</b></a>
</p>

<h3><b> So we will start with it! </b></h3>
</div>

___
___

<div align="center">
<h2> Documentation Disclosure </h2>
<a href="https://github.com/Vibrantic/Ai-Transparency-Act">
  <img src="./labels/AiAssisted_Low.svg" alt="AI Assisted: Low" height="128">
</a>
<a href="https://github.com/Vibrantic/Ai-Transparency-Act">
  <img src="./labels/AiGenerated_Mid.svg" alt="AI Assisted: Low" height="128">
</a>

In line with the transparency principles of this project, please note that this `README.md` file was generated using 
**Gemini (Google AI)** to draft the taxonomy, structure, and usage guidelines. All content has been manually reviewed and verified by the maintainer.
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-about-this-project"></a>
<div align="center">
<h1>About</h1>
Standardized, open-source svg and shield badges to declare the level of AI involvement in software, writing, design, and hardware projects.
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-note-on-voluntary-adoption"></a>

<table width="100%" style="border-collapse: collapse;">
  <tr>
    <td style="background: #fffde7; border-left: 6px solid #ffeb3b; padding: 16px; border-radius: 4px;">
      <p style="margin: 0; color: #1c1b1f;">
        <b>📌 Note on Voluntary Adoption:</b><br>
        <i>Using these labels is completely voluntary. No maintainer or developer is obligated to adoption. However, if we want to build genuine trust, transparency, and acceptance around AI tools, clear disclosure is an impactful step forward. Sharing how a project was built helps foster understanding and mutual respect across the entire community.</i>
      </p>
    </td>
  </tr>
</table>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-why"></a>
<div align="center">
<h2>Why This Project Exists</h2>

As AI tools become deeply integrated into software development and content creation, transparency matters more than ever. Users, contributors, and maintainers have different expectations regarding code provenance, security, and human oversight. 

This repository provides a simple, standard labeling system so developers and creators can clearly state **how much AI was used** and **in what capacity**. Building up trust, respecting user preferences, and setting clear expectations.
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-label-structure-&-taxonomy"></a>
<div align="center">
<h2>Label Structure & Taxonomy</h2>

The framework uses two primary categories split into three levels of intensity:

<div class="framed-div", align="left">
<details open>
<summary><b><h3>AI Assisted/Supported</h3></b></summary>
<br>

<table>
  <thead>
    <tr>
      <th>Label</th>
      <th>Level</th>
      <th>Scope</th>
      <th>Human Oversight</th>
      <th>Typical Use Case</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img src="./labels/AiAssisted_Low.svg" alt="AI Assisted Low" width="64" height="128"><br>
      </td>
      <td><font color="#a8d600"><b>🟢 Low</b></font></td>
      <td>Inline code completion (Copilot/Ghostwriter), basic syntax lookups, formatting, or simple bug fixes.</td>
      <td><b>90%+</b> written directly by humans.</td>
      <td>Everyday software development with IDE autocompletion enabled.</td>
    </tr>
    <tr>
      <td align="center">
        <img src="./labels/AiAssisted_Mid.svg" alt="AI Assisted Low" width="64" height="128"><br>
      </td>
      <td><font color="#ffeb3b"><b>🟡 Mid</b></font></td>
      <td>Writing specific helper functions, generating documentation/comments, writing unit tests, or refactoring existing modules.</td>
      <td>Human designs overall structure and logic; AI writes discrete blocks under supervision.</td>
      <td>A developer prompts an AI to generate a specific regex or parsing module, then integrates it manually.</td>
    </tr>
    <tr>
      <td align="center">
        <img src="./labels/AiAssisted_High.svg" alt="AI Assisted Low" width="64" height="128"><br>
      </td>
      <td><font color="#ff4c4c"><b>🔴 High</b></font></td>
      <td>Co-architecting entire files, writing core algorithms based on user prompts, heavy debugging, and generating setup scripts.</td>
      <td>Human acts as product manager and integrator; code is thoroughly reviewed and edited before commit.</td>
      <td>Complex feature implementations built via conversational AI sessions with active human iteration.</td>
    </tr>
  </tbody>
</table>
</div>
</details>

<div class="framed-div", align="left">
<details open>
<summary><b><h3>AI Generated</h3></b></summary>
<br>

<table>
  <thead>
    <tr>
      <th>Label</th>
      <th>Level</th>
      <th>Scope</th>
      <th>Human Oversight</th>
      <th>Typical Use Case</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img src="./labels/AiGenerated_Low.svg" alt="AI Assisted Low" width="64" height="128"><br>
      </td>
      <td><font color="#a8d600"><b>🟢 Low</b></font></td>
      <td>Full code blocks or entire files generated by AI, but comprehensively audited, refactored, and tested by a human.</td>
      <td>Significant human validation, security checks, and manual fine-tuning.</td>
      <td>A project skeleton or module built by AI where the human verified every line for production readiness.</td>
    </tr>
    <tr>
      <td align="center">
        <img src="./labels/AiGenerated_Mid.svg" alt="AI Assisted Low" width="64" height="128"><br>
      </td>
      <td><font color="#ffeb3b"><b>🟡 Mid</b></font></td>
      <td>Code or content generated via AI prompts with basic functionality testing and minor manual tweaks.</td>
      <td>High-level review and sanity checking; minimal structural edits.</td>
      <td>Utility scripts, quick CLI tools, or boilerplate generators used largely as outputted by the model.</td>
    </tr>
    <tr>
      <td align="center">
        <img src="./labels/AiGenerated_High.svg" alt="AI Assisted Low" width="64" height="128"><br>
      </td>
      <td><font color="#ff4c4c"><b>🔴 High</b></font></td>
      <td>End-to-end AI generation (e.g., prompt-to-app, v0, AutoGPT) pushed with little to no modification or manual audit.</td>
      <td>Minimal to none beyond running the generation prompt.</td>
      <td>Experimental code, quick prototypes, or automated repository generation.</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</details>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-how-to-use"></a>
<div align="center">
<h2> How to Use in Your Project</h2>

<h3>Markdown Snippets</h3>

Copy and paste the relevant Markdown badge or svg into your repository’s `README.md`.

<table>
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/AI_Usage-SUP-a8d600?labelColor=555555&color=a8d600&style=flat-square" alt="AI Usage - SUP Low"><br>
      <font color="#a8d600"><b>SUP — Low</b></font>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/AI_Usage-SUP-ffeb3b?labelColor=555555&color=ffeb3b&style=flat-square" alt="AI Usage - SUP Mid"><br>
      <font color="#ffeb3b"><b>SUP — Mid</b></font>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/AI_Usage-SUP-ff4c4c?labelColor=555555&color=ff4c4c&style=flat-square" alt="AI Usage - SUP High"><br>
      <font color="#ff4c4c"><b>SUP — High</b></font>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/AI_Usage-GEN-a8d600?labelColor=555555&color=a8d600&style=flat-square" alt="AI Usage - GEN Low"><br>
      <font color="#a8d600"><b>GEN — Low</b></font>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/AI_Usage-GEN-ffeb3b?labelColor=555555&color=ffeb3b&style=flat-square" alt="AI Usage - GEN Mid"><br>
      <font color="#ffeb3b"><b>GEN — Mid</b></font>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/AI_Usage-GEN-ff4c4c?labelColor=555555&color=ff4c4c&style=flat-square" alt="AI Usage - GEN High"><br>
      <font color="#ff4c4c"><b>GEN — High</b></font>
    </td>
  </tr>
</table>
</div>


<div align="center">
<h3>SVG Labels</h3>

Right click copy image and past into your repository's `Readme.md`.

<table>
  <tr>
    <td align="center">
      <img src="./labels/AiAssisted_Low.svg" alt="AI Assisted Low" width="128" height="128"><br>
      <b>AI Assisted: Low</b>
    </td>
    <td align="center">
      <img src="./labels/AiAssisted_Mid.svg" alt="AI Assisted Mid" width="128" height="128"><br>
      <b>AI Assisted: Mid</b>
    </td>
    <td align="center">
      <img src="./labels/AiAssisted_High.svg" alt="AI Assisted High" width="128" height="128"><br>
      <b>AI Assisted: High</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./labels/AiGenerated_Low.svg" alt="AI Generated Low" width="128" height="128"><br>
      <b>AI Generated: Low</b>
    </td>
    <td align="center">
      <img src="./labels/AiGenerated_Mid.svg" alt="AI Generated Mid" width="128" height="128"><br>
      <b>AI Generated: Mid</b>
    </td>
    <td align="center">
      <img src="./labels/AiGenerated_High.svg" alt="AI Generated High" width="128" height="128"><br>
      <b>AI Generated: High</b>
    </td>
  </tr>
</table>
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-contributing-&-feedback"></a>
<div align="center">
<h2> Contributing & Feedback </h2>

Suggestions for refining these definitions or adding asset icons are welcome. Please open an issue or submit a pull request!
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-license"></a>
<div align="center">
<h2> License </h2>

This specification and all associated badges are available under the **CC0 1.0 Universal (Public Domain)** license. Feel free to use them freely in any open-source or commercial project.
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>
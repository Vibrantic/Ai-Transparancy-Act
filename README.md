<div align="center">
<h1>AI TRANSPARENCY ACT</h1>

<img src="https://img.shields.io/badge/AI_Usage-SUP-a8d600?labelColor=555555&color=a8d600&style=flat-square" alt="AI Usage - SUP Low">
<img src="https://img.shields.io/badge/AI_Usage-GEN-ffeb3b?labelColor=555555&color=ffeb3b&style=flat-square" alt="AI Usage - GEN Mid">
<img src="https://img.shields.io/badge/License-CC0_1.0-blue?style=flat-square&labelColor=555555" alt="License: CC0 1.0">
<img src="https://img.shields.io/badge/Status-Active_Standard-brightgreen?style=flat-square&labelColor=555555" alt="Status">

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

<table>
    <td>
        <img src="./labels/AiAssisted_Low.svg" alt="AI Assisted: Low" height="128">
        <img src="./labels/AiGenerated_Mid.svg" alt="AI Assisted: Low" height="128">
    </td>
</table>

<p align="left">
In line with the transparency principles of this project, please note that this `README.md` file was partialy generated using <a href="https://gemini.google.com/">Gemini (Google AI)</a> and <a href="https://copilot.microsoft.com/">Copilot (GPT-5.6)</a> and to draft the taxonomy, structure, and usage guidelines. All content has been manually reviewed and verified by the maintainer.
</p>

</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-about-this-project"></a>
<div align="center">
<h1>About</h1>
<p align="left">
The AI Transparency Act is an open and vendor-neutral disclosure standard designed to bring greater transparency to AI-assisted and AI-generated projects.
</p>
<p align="left">
As AI becomes increasingly integrated into software development, documentation, design, writing, research, and hardware engineering, understanding how a project was created becomes increasingly valuable. This repository provides a simple taxonomy and a collection of standardized badges that allow creators to voluntarily disclose the degree of AI involvement in their work.
</p>
<p align="left">
The goal is not to promote or discourage AI usage. The goal is transparency. Clear disclosure helps users evaluate projects, understand development processes, encourage informed decision-making, and foster trust between creators and their communities.
</p>
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-note-on-voluntary-adoption"></a>

> [!NOTE]
> **📌 Voluntary Adoption**
>
> Using these labels is completely voluntary. No maintainer or developer is obligated to adopt them. However, if we want to build genuine trust, transparency, and acceptance around AI tools, clear disclosure is an impactful step forward. Sharing how a project was built helps foster understanding and mutual respect across the entire community.
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-why"></a>
<div align="left">
<h2>Why transparency matters?</h2>

Artificial intelligence is becoming a normal part of software development, content creation, research, and engineering. Yet many projects provide little or no indication of how AI contributed to the final result.

The absence of disclosure can create uncertainty, misunderstandings, and unnecessary debate. Some users may prefer fully human-created work, while others may welcome AI-assisted development. Both perspectives benefit from transparent information.

The AI Transparency Act does not attempt to judge, rank, encourage, or discourage AI usage. Instead, it promotes a simple principle:

<div align="center", >
<b>People should be able to understand how a project was created.</b>
</div>
ㅤ

Transparency enables informed decisions, honest communication, and stronger trust between creators and their communities.
</div>
ㅤ
<div align="right"><a href="#top">⬆️ Back to Top</a></div>

___
___

<a id="-label-structure-&-taxonomy"></a>
<div align="center">
<h2>Label Structure & Taxonomy</h2>

The framework uses two primary categories split into three levels of intensity:

<div align="left">
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

<div align="left">
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

> [!IMPORTANT]
> ❤️ **A Personal Note**
> 
> The icons and badges provided by this project were created manually using Inkscape. No AI-generated imagery was used during their creation.
> 
> I am not a professional designer. These graphics reflect my personal vision and should be viewed as recommendations rather than definitive designs.
> 
> This project was created with the intention of helping the community, encouraging transparency, and providing a foundation that others may improve upon. The goal is not perfection, but contribution.
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
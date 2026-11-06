<p align="center">
  <img src="assets/brand/mark.svg" alt="Insight-Space logo" height="112">
</p>

<h1 align="center">Insight-Space</h1>

<p align="center">
  <strong>Find real precedents. Build informed design references.</strong><br>
  <sub>An AI skill for spatial design and early-stage research.</sub>
</p>

<p align="center"><strong>English</strong> | <a href="README_CN.md">简体中文</a></p>

<p align="center">
  <img src="assets/brand/badge-1.svg" alt="type: AI Skill" height="22">
  <img src="assets/brand/badge-2.svg" alt="platform: Codex" height="22">
  <img src="assets/brand/badge-3.svg" alt="output: Word · Cards" height="22">
  <img src="assets/brand/badge-4.svg" alt="focus: Verified sources" height="22">
</p>

<p align="center">
  Turn project questions into case searches, source checks and design analysis.<br>
  Understand what to borrow, where it fits and what to consider.
</p>

<p align="center"><a href="#quick-start"><strong>Quick Start</strong></a> · <a href="#how-it-works"><strong>How It Works</strong></a> · <a href="#installation"><strong>Installation</strong></a> · <a href="#limitations"><strong>Limitations</strong></a></p>

---

## From design questions to useful references

| Real precedents | Design judgment | Research outputs |
| --- | --- | --- |
| Search relevant cases and check sources | Assess ideas, context and constraints | Organize reports, links and visual cards |
| Questions → Cases | Cases → Insights | Insights → References |

---

<a id="quick-start"></a>

## Quick Start

Describe your project, the question to explore and the references you need:

~~~text
Use Insight-Space to research distinctive workplace projects and explain which ideas are worth adapting.
~~~

Other starting points:

~~~text
Use Insight-Space in shallow mode to compare park pavilion references.
Use Insight-Space in visual search mode to explore bakery materials and atmosphere.
Use Insight-Space in expert mode to study an entrance landmark, focusing on recognition and shareability.
~~~

The skill recommends a mode and initial sample size before expanding. You can invoke it with $insight-space, or the established Chinese shortcuts described in the [Chinese guide](README_CN.md).

<a id="how-it-works"></a>

## How It Works

Insight-Space starts with the design problem. It distinguishes full case research, fast direction finding, visual exploration and focused specialist questions.

1. Understand the project, audience and question.
2. Choose a mode and initial sample size.
3. Route by discipline and source; develop Chinese and English search terms.
4. Build a candidate pool from suitable sources.
5. Verify selected links and project information.
6. Assess relevance, transferable ideas, conditions and limits.
7. Produce the agreed reports, links or visual cards.

Cost, buildability, maintenance, operation and user behavior are considered where evidence supports them.

### Five output modes

| Mode | Main purpose | Default output |
| --- | --- | --- |
| Deep | Selected precedents and developed analysis | One Word report with 3–5 cases, links and 5 project reference cards |
| Medium | Comparison and judgment in a shorter format | One Word report with 5–8 cases, links and 5 project reference cards |
| Shallow | Fast direction finding | One Word report with 8 cases, one page per case, plus links; no cards by default |
| Visual search | Form, materials, atmosphere and visual clues | 3–4 cards plus links; no Word report by default |
| Expert | One defined design question | One focused Word report, links and 8 independent inspiration cards; agree the report case count for the question |

Explicit counts and output choices take priority. A smaller initial sample may calibrate direction. Expert tasks can omit cards when requested.

Deep/medium project reference cards come from relevant candidates that did not make the report. Expert additional possibilities are searched independently, do not duplicate report cases and may be visual directions without a complete project account. Existing Chinese output-folder labels are retained.

<a id="installation"></a>

## Installation

1. Download the complete repository with **Code → Download ZIP** and extract it.
2. Ask Codex to inspect the folder, identify your existing skills location and install the complete package.
3. For manual installation, copy the entire folder containing SKILL.md to that location as **insight-space**.
4. Keep references, templates, scripts and other folders together.
5. Restart Codex or open a new chat if needed, then test with $insight-space.

Use the skills directory already configured on your machine; avoid duplicate installations. Codex local Skills are the main tested environment. Other agent tools need adaptation to their file access, web research, scripting, Word output and image-processing capabilities.

## Professional Source Routing

| Discipline | Typical sources or treatment |
| --- | --- |
| Environmental / spatial design | mooool, gooood, ArchDaily, architecture platforms, YinjiSPACE; Pinterest for visual clues |
| Architecture | Publications, practice websites and award sources |
| Public art | Artist/institution websites and public-art platforms; Behance/Pinterest for leads |
| Sculpture | Artist, gallery and institution pages; visual platforms for leads |
| Visual communication | Behance-only default |
| Product design | Behance, design awards, brand websites; Pinterest for clues |
| Craft | Artist/workshop websites, exhibitions, museums and craft platforms |
| Digital media art | Work assessable through static images; artist, institution and media-art sources |

Animation and photography are not core V2.0 disciplines. UI/industrial-product questions outside spatial scale use a constrained specialist task when appropriate; flat graphic/brand references use the relevant portfolio route. Refer to the skill's detailed source-routing rules for platform-specific requirements.

## Output Location

Where local access allows, outputs go to an **Insight-Space输出** folder on the actual Desktop. Each task gets a numbered folder. Within it, keep the requested Word report, cards and source-links file together; routine delivery omits intermediate-material folders.

Existing filenames and folder labels may remain Chinese to match the current templates. This English documentation does not rename the functional output templates.

## Package and Automation

| Item | Purpose |
| --- | --- |
| [SKILL.md](SKILL.md) | Entry point and core research rules |
| [agents/](agents/) and [assets/brand/](assets/brand/) | Skill display information and logo assets |
| [references/](references/) | Source verification, evaluation, output, card and platform rules |
| [assets/templates/](assets/templates/) | Approved Word and visual-card templates |
| [scripts/](scripts/) | Repeatable Word/card generation |
| [tests/](tests/) and [examples/](examples/) | Acceptance material and example inputs |
| [docs/](docs/) | Development and maintenance documents |

The package includes render_deep_report.ps1, render_medium_report.ps1, render_shallow_report.ps1, render_expert_report.ps1 and render_project_card.ps1 in scripts/. They handle formatting and file generation; research, source verification, selection and judgment remain part of the research workflow.

## Status and Maintenance

Package **V2.0** provides five modes, fixed Word/card templates, output scripts, source routing and verification, layered sampling, image-download fallback, initial guidance and duplicate-search exclusion.

Update SKILL.md for workflow changes and references/ for detailed rules. Check template changes against the corresponding scripts and run relevant tests for important functional changes. This visual/documentation update preserves those functional resources and does not claim a new version.

<a id="limitations"></a>

## Limitations

Insight-Space supports early design research. It does not replace fire, structural, accessibility, cost or construction-document review. A visual clue is not automatically a verified project source; return to the original before formal citation. Distinguish source-supported information from judgment and possible directions.

## About

An AI skill for spatial design research, reference evaluation and early-stage project insight.

[简体中文 documentation](README_CN.md) · [Map2Model](https://github.com/RuiqiWang-LGD/Map2Model) · [TalkTrack](https://github.com/RuiqiWang-LGD/TalkTrack--)

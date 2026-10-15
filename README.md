# Skills by Rowdy Vass

A growing collection of practical AI skills for thinking, building, and learning. Each skill includes reusable instructions and a quick way to get started.

**Available now:** [BOLDER](#bolder-think-bigger-about-a-product-idea) — explore more ambitious product ideas and find a useful first test.

## BOLDER: think bigger about a product idea

BOLDER helps product managers, founders and builders push an idea past its first, safest version. It turns your AI assistant into a sparring partner: each direction includes a customer outcome, a mechanism, an assumption to test and the constraints it depends on. It then recommends a destination and a small experiment to start with.

Read the companion post, [Agents and Ambition](https://rowdyvass.substack.com/p/agents-and-ambition), for the thinking behind BOLDER and an example of the six lenses in practice.

| Lens | Question |
| --- | --- |
| **B — Bigger Outcome** | What would a dramatically better result for the customer look like? |
| **O — Origin of the Problem** | Could we eliminate the conditions that create this problem? |
| **L — Limiting Factor** | What constraint most limits the customer's outcome, and what becomes possible without it? |
| **D — Different Contexts** | Where else does this problem show up, and what new possibilities emerge if we solve it across contexts? |
| **E — Enable Others** | What could others accomplish if we gave them this capability? |
| **R — Rethink Constraints** | What are we treating as a requirement that might only be a convention? |

## Use BOLDER

- **Claude:** [Download bolder.zip](https://github.com/rowdyvass/skills/raw/refs/heads/main/bolder.zip), then follow the installation steps below.
- **ChatGPT, Gemini or another assistant:** [Open the plain-text instructions](bolder-instructions.md), copy the contents, and paste them into a new chat before describing your idea.
- **Read the skill source:** [bolder/SKILL.md](bolder/SKILL.md).

You do not need to write code or provide an API key to use these instructions. Your AI app's normal access and usage limits still apply.

### Claude

1. Enable code execution and file creation in **Settings → Capabilities**, if needed.
2. Open **Customize → Skills → + → + Create skill → Upload a skill**.
3. Upload `bolder.zip` and enable the skill.
4. Start a chat, share your idea, and say **"Run BOLDER on this idea."**

Custom skills are available on Free, Pro, Max, Team and Enterprise plans; organization settings may control access. See [Claude's current installation guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude).

### ChatGPT

For a single session, paste the [plain-text instructions](bolder-instructions.md) into a new chat, followed by your idea. For repeated use, add them to a dedicated Project's instructions and start chats within that Project. See [ChatGPT's project guide](https://learn.chatgpt.com/docs/projects).

### Gemini

In the Gemini web app, open **Gems → New Gem**, name it **BOLDER**, paste the [plain-text instructions](bolder-instructions.md) into its instructions, and save. You can also paste the instructions directly into a new chat. See [Google's current Gem guide](https://support.google.com/gemini/answer/15146780?co=GENIE.Platform%3DDesktop&hl=en).

## Try BOLDER

Share your idea in a sentence or two, who it is for, and what makes the bigger version feel unrealistic. For example:

> Run BOLDER on this idea: a quiz app that explains wrong answers to adults learning spreadsheet skills. The current version asks questions and gives explanations. Personalized tutoring feels too expensive to provide at scale.

Choose a mode:

- **Default:** explore all six lenses, then choose a destination and a first test.
- **Guided:** say "guided" to work through one lens at a time.
- **Quick:** say "quick" for one line per lens and the destination sentence.

The output is a set of hypotheses to explore, not evidence that an idea will work. Test the important assumptions with real users.

## Files

| File | Purpose |
| --- | --- |
| [bolder/SKILL.md](bolder/SKILL.md) | Skill source, including discovery metadata. |
| [bolder.zip](bolder.zip) | The same skill packaged for upload to Claude. |
| [bolder-instructions.md](bolder-instructions.md) | The skill body without metadata, ready to paste into an assistant. |
| [LICENSE](LICENSE) | Attribution and reuse terms. |

## About and license

Created by **Rowdy Vass**. [More writing on product management and AI](https://rowdyvass.substack.com/).

Free to use, share and adapt with attribution under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Please credit Rowdy Vass and link to this repository; indicate changes when you adapt the material.

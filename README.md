# Mattias Geisler 💾

I’m a full-stack developer in Örebro, Sweden. I wrote my first programs in seventh grade on a Sanyo MBC-1150 my dad bought from a bankruptcy sale. A Z80, 64 KB of RAM, two floppy drives and a green screen, all in one box.

In 1996 I co-founded Stockholmnet, a web agency. A few of us went on to start Technohuman, where I was both a co-founder and a programmer. At Arbesko I worked in business development, wrote budgeting tools in Excel and helped the IT manager keep Exchange running.

These days I build document AI, train models to trade Swedish stocks and host the family email. That last project has a 24/7 support hotline. It’s my phone.

## What I’m building

- 🧾 **Document AI at [docTech](https://doctech.nu)**. Every document we interpret goes through the parser I built. Qwen3-VL runs locally via vLLM. The part I especially enjoy is the review screen, where an operator can spot a misread field, fix it and get on with the job.
- 🗺️ **Webbväg 2** helps Swedish joint property associations manage properties, meetings, billing and bookkeeping. Who owes the road fee when a property changes hands? That’s a question I get to turn into code and tests. Underneath are Nuxt/Vue, Frappe/ERPNext and a control plane that provisions a separate site for each association across Docker-based shards.
- 🏦 **[ERPNext Sweden](https://github.com/docTechSys/erpnext_sweden)** brings Swedish banking formats to ERPNext. It imports camt.053 statements and BgMax files, exports `pain.001` payments and validates payment references. The banks picked that name.
- 📈 **Quantitative trading**. I built a SvelteKit front end and the tools I use to train and evaluate models for Swedish equities. Three strategies now trade live.

## 🧰 Toolbox

I work mostly in Python, C#/.NET and TypeScript, with SvelteKit, React, Vue/Nuxt, Docker and Linux. Much of my work lives in private repositories and shows up here in the contribution graph.

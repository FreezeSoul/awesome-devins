<h1 align="center">
	💠 Awesome Devins
	<p align="center">
		<a href="https://discord.gg/U7KEcGErtQ" target="_blank">
			<img src="https://img.shields.io/static/v1?label=Join&message=%20discord!&color=mediumslateblue">
		</a>
		<a href="https://twitter.com/e2b_dev" target="_blank">
			<img src="https://img.shields.io/twitter/follow/e2b.svg?logo=twitter">
		</a>
	</p>
</h1>
<h3 align="center">
  Try out E2B's <a href="https://e2b.dev/docs?ref=awesome-sdks">cloud runtime</a> for AI agents
</h3>

<h5 align="center">🌟 <a href="https://e2b.dev/ai-agents">See this list in web UI</a></h5>

<h5 align="center">👉 <a href="https://forms.gle/UXQFCogLYrPFvfoUA">Submit new product here</a></h5>

<img src="assets/landscape-latest.png" width="100%" alt="Chart of AI Agents Landscape" />

Welcome to our list of AI agents that are inspired by release of Devin. See the 🌟 [complete list of AI agents](https://e2b.dev/ai-agents). 🌟

The list is done according to our best knowledge, although definitely not comprehensive. Check out also <a href="https://github.com/e2b-dev/awesome-sdks-for-ai-agents">the Awesome List of SDKs for AI Agents</a>.
Discussion and feedback appreciated! :heart:

Have anything to add? Create a pull request or fill in this [form](https://forms.gle/UXQFCogLYrPFvfoUA). Please keep the alphabetical order and in the correct category.

<!---
## Who's behind this?
This list is made by the team behind [e2b](https://github.com/e2b-dev/e2b). E2b is building AWS for AI agents. We help developers to deploy, test, and monitor AI agents. E2b is agnostic to your tech stack and aims to work with any tooling for building AI agents.
--->

## Want to use E2B with your AI product?
Contact us at [hello@e2b.dev](mailto:hello@e2b.dev) or [on Discord](https://discord.gg/35NF4Y8WSE). Follow us on [X (Twitter)](https://twitter.com/e2b_dev)

We are open-source and you can get started with E2B [here](https://e2b.dev/docs?ref=awesome-sdks).


<!---
## Join the community
- Follow us on [Twitter](https://twitter.com/e2b_)
- [Join Twitter community](https://twitter.com/i/communities/1670204079619055616) for AI agents
- [Join our Discord](https://discord.gg/U7KEcGErtQ)

Feel free to reach out to us at [hello@e2b.](mailto:hello@e2b.).
--->


# Open-source "Devins"

## [Devika](https://github.com/stitionai/devika)
Agentic AI Software Engineer

<details>

![Image](https://github.com/stitionai/devika/raw/main/.assets/devika-screenshot.png)
### Category
Coding, general purpose

### Description
- Devika is an Agentic AI Software Engineer that can understand high-level human instructions, break them down into steps, research relevant information, and write code to achieve the given objective.
- Devika aims to be a competitive open-source alternative to Devin by Cognition AI.

### Links
- [GitHub](https://github.com/stitionai/devika)

</details>

## [Devon](https://github.com/entropy-research/Devon)
Open-source Devin alternative

<details>

![Image]()
### Category
Coding, general purpose

### Description
- Open-source alternative to Devin by Entropy research

### Links
- [GitHub](https://github.com/entropy-research/Devon)

</details>

## [MetaGPT](https://github.com/geekan/MetaGPT)
Agent framework returning Design, Tasks, or Repo

<details>

 ![image](https://github.com/geekan/MetaGPT/raw/main/docs/resources/MetaGPT-new-log.png)

### Category
Multi-agent, Coding, Build your own

### Description
MetaGPT is a multi-agent framework that, given one line requirement, returns PRD, Design, Tasks, or Repo.
- MetaGPT allows to assign different roles to GPTs to form a collaborative software entity for complex tasks
- It takes a one line requirement as input and outputs user stories / competitive analysis / requirements / data structures / APIs / documents, etc.
- Internally, MetaGPT includes product managers / architects / project managers / engineers
- It provides the entire process of a software company along with carefully orchestrated SOPs. Code = SOP(Team) is the core philosophy
- The paper about LLM-based multi-agent work spushes forward the idea of autonomous agents collaborating with each other to do more than one can on its own.
- MetaGPT incorporates efficient human workflows as a meta programming approach into LLM-based multi-agent collaboration


### Links  
- [GitHub](https://github.com/geekan/MetaGPT)
- [Discord](https://discord.com/invite/4WdszVjv)
- [Twitter](https://twitter.com/DeepWisdom2019)
- [Paper - MetaGPT: Meta Programming for Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352)

</details>

## [OpenDevin](https://github.com/OpenDevin/OpenDevin)
OpenDevin: Code Less, Make More

<details>

![Image](https://github.com/OpenDevin/OpenDevin/raw/main/logo.png)
### Category
Coding, general purpose

### Description
-  The OpenDevin project is born out of a desire to replicate, enhance, and innovate beyond the original Devin model.
-  By engaging the open-source community, we aim to tackle the challenges faced by Code LLMs in practical scenarios, producing works that significantly contribute to the community and pave the way for future advancements.


### Links
- [GitHub](https://github.com/OpenDevin/OpenDevin)

</details>

## [SWE Agent](https://github.com/princeton-nlp/SWE-agent)
Open-source Devin alternative

<details>

![Image](https://www.swebench.com/img/swellama.png)
### Category
Coding, general purpose

### Description
- This Devin alternative scores 12.3% on the FULL swe benchmark
- ["An open source Devin getting 12.29% on 100% of the SWE Bench test set vs Devin's 13.84% on 25% of the test set!"](https://x.com/danielhanchen/status/1775120334305607781)
- SWE-agent works by interacting with a specialized terminal, which allows it to:
	- 🔍 Open, scroll and search through files
	- ✍️ Edit specific lines w/ automatic syntax check
	- 🧪 Write and execute tests
- This custom-built interface is critical for good performance. Simply connecting an LM to a vanilla bash terminal does not work well.
- ["Our key insight is that LMs require carefully designed agent-computer interfaces (similar to how humans like  good UI design). E.g. When the LM messes up indentation, our editor prevents it and gives feedback."](https://x.com/jyangballin/status/1775114448513958134)
- SWE-agent was released by the Princeton NLP team.
- What makes SWE-agent special is that it performs almost as well as Devin on the SWE-bench.
- It is important to say that the performance [varies](https://www.swebench.com/) based on the model used by the agent.
- The changes and innovations in SWE-agent compared to Devin are:
  - The code in SWE Agent is executed locally via Docker.
  - It uses “Agent-Computer Interface” (ACI) - constraining the interface makes the agent easier to use for LMs. Only a few commants are allowed: run code, look for code, edit code and submit changes to GitHub.
- Any code the agent writes goes through a syntax check (linter) before being submitted. If the syntax is incorrect, the agent gets feedback and is forced to redo the code.
- The agent can only read 100 lines of code at a time, rather than the entire file. This makes it easier for the language model to understand the code.


### Links
- [GitHub](https://github.com/princeton-nlp/SWE-agent)
- [Web](https://swe-agent.com/)
- [Demo](https://swe-agent.com/demo)
- [Discord](https://discord.com/invite/AVEFbBn2rH)

</details>




# Closed-source "Devins"


## Want to use E2B with your AI product?
Contact us at [hello@e2b.dev](mailto:hello@e2b.dev) or [on discord](https://discord.gg/35NF4Y8WSE).

We are open-source and you can get started with E2B [here](https://e2b.dev/docs?ref=awesome-sdks).

<img src="/assets/footer.png" width="100%" alt="SDKs Repo Visual" />


## Join the community
- Follow us on [X ](https://twitter.com/e2b_dev)
- [Hit us up on discord](https://discord.gg/35NF4Y8WSE)
- Feel free to reach out to us at [hello@e2b.dev](mailto:hello@e2b.dev).

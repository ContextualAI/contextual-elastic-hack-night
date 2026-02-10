# Elastic x Contextual AI Hack Night

![Elastic x Contextual AI Hack Night](./assets/contextual_elastic_hack_night.png)

Welcome to the Elastic x Contextual AI Hack Night!

Tonight you'll build AI agents powered by Elasticsearch and Contextual AI's Agent platform. Start with a quick challenge to get familiar with the platform, then team up to build something unique — a research assistant, log analyzer, or your own creative use case. You'll have access to enterprise features, example agents to learn from, and Contextual AI engineers to help you along the way.

## Event Challenges

### Challenge 1: Quick Start - Agentic Search

**Prize:** First to complete wins!
**Bonus Prize:** Random draw from all completions

Sign up for a **free Contextual AI account** and build your first RAG agent!

| Guide | Description |
|-------|-------------|
| [Quick Start (GUI)](./quickstart-gui.md) | Create an agent using the Platform UI — no code required |
| [Quick Start (API)](./quickstart-api.md) | Create an agent programmatically using Python |
| [Quick Start (Notebook)](./quickstart-api.ipynb) | Run the API quickstart as a Jupyter notebook |

**To submit (and win one of the prizes):** Fill out the [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSeto2df8pft5OcRLG-uQG2GQCWrZt87Ooqcd7EI9a9K6Ka0tg/viewform?usp=dialog) with:




- Your email address
- Screenshot of your agent query results
- Optional: Did you use GUI or API?

---

After filling out form 1, you will have access to [https://app.contextual.ai/context-layer-hack-night](https://app.contextual.ai/context-layer-hack-night)

### Challenge 2: Build Your Own Agent

**Work solo or in teams (up to 3 people)**

Ready to go deeper? We'll add you to our **enterprise tenant** where you can create custom agents with advanced features.

| Guide | Description |
|-------|-------------|
| [Build Your Own Agent](./build-your-own-agent.md) | Customize prompts, explore Agent Composer, and create something unique |

**Demo Categories:**

| Category | Description | Template |
|----------|-------------|----------|
| **Deep Research** | Build a comprehensive research assistant that conducts multi-step investigations | [Deep Research Template](https://github.com/ContextualAI/agent-composer/blob/main/templates/deep_research.yml) |
| **Log Analysis** | Analyze logs, telemetry, or operational data to identify issues and root causes | [Log Analysis Template](https://github.com/ContextualAI/agent-composer/blob/main/templates/log_analysis.yml) |
| **Choose Your Own** | Pick your own use case and build something unique. We have templates you can use or look at for inspiration. | [Browse All Templates](https://github.com/ContextualAI/agent-composer/tree/main/templates) |

**To participant:** If you submit the Google Form with your email address, you will automatically be added to the tenant. If you do not submit the Google Form with your email address, let an organizer know, and you'll be added to the tenant.

**Example Agents:** Check out these example agents in the shared workspace for inspiration:

| Agent | Description |
|-------|-------------|
| **3GPP Technical Specifications** | Navigate 3GPP telecom standards across multiple mobile technology generations |
| **Materials Science** | Search research papers and explain technically dense material science topics |
| **MCP Recommender** | Find the perfect MCP server for your project from 5000+ options — use this to discover the Contextual AI docs MCP server! |

**Judging:** Plan for a 2-3 minute demo of your agent.

| Criteria | What We're Looking For |
|----------|------------------------|
| **Use Case** | Is the problem interesting and well-defined? |
| **Prompt Quality** | Do the prompts produce good, consistent results? |
| **Creativity** | Did you try something unique or innovative? |
| **Demo Quality** | Can you clearly explain what your agent does? |
| **LLM Extension** | Does it extend what LLMs can do on their own? |

Due to time constraints, we will record live demos in advance to streamline hand off. 
**To submit:** Fill out the [Google Form](https://forms.gle/4B8BszjFK5n6q9ot9) with:
- Your email address
- A short video (up to 90 sec) of your agent query, retrieved context, and agent configuration that you will present at the end. Plan to speak over your recorded demo. 
- Optional: Did you use GUI or API?

---

## Resources

- [Contextual AI Platform](https://app.contextual.ai)
- [Contextual AI Documentation](https://docs.contextual.ai)
- [Use Cases & Templates](https://contextual.ai/use-cases)
- [Agent Composer YAML Guide](https://docs.contextual.ai/how-to-guides/agent-composer-yaml)
- [Demo Gallery](https://demo.contextual.ai)
- [PulseMCP Directory](https://pulsemcp.com) — Browse 5000+ MCP servers

---

## For Organizers

Event automation scripts are in the [scripts/](./scripts/) folder:

- **[invite_users.py](./scripts/invite_users.py)** — Bulk invite users to tenant from Google Form CSV export

See [scripts/README.md](./scripts/README.md) for usage instructions.

---

## Support

Having issues? Flag down a Contextual AI team member or check the [troubleshooting section](./quickstart-gui.md#troubleshooting).

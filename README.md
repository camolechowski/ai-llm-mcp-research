# ai-llm-mcp-research
Artificial Intelligence, Large Language Model, and Model Context Protocol Research Repository

## **DISCLAIMER**

Please use **extreme caution** when installing any code on your system that you have not personally reviewed or vetted. 

This rule holds *especially* true when giving LLMs the agency to act on your behalf. 

It is even more pertinent in the context of an "un-siloed" environment or with unfettered internet access.

This repository is being actively curated and will undergo changes. By including an MCP in this list, I am **not** vouching for its safety or efficacy.

## Large Language Models (LLMs)
Frameworks, Best Practices, & Basic Information

### Anthropic Docs
- [Claude Code: Best practices for agentic coding](https://www.anthropic.com/engineering/claude-code-best-practices)
- [Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview)

### Articles
- [Memory BankL How to Make Cline an AI Agent That Never Forgets](https://cline.bot/blog/memory-bank-how-to-make-cline-an-ai-agent-that-never-forgets)

## Model Context Protocol (MCP)
Servers, Clients, Frameworks, & Documentation

### How Do I Start Using & Developing MCPs? What is an MCP?
> MCP is an open protocol that standardizes how applications provide context to LLMs. Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect your devices to various peripherals and accessories, MCP provides a standardized way to connect AI models to different data sources and tools.

_Note_: This section is primarily focused on MCP **servers**, if you aren't familiar with MCP clients...
- I would start: [Learning More about the Model Context Protocol at the Official Github Repository](https://github.com/modelcontextprotocol/)
- Then visit: [Model Context Protocol Official Repository](https://modelcontextprotocol.io/introduction)
- And read the [Model Context Protocol Section of this README](https://github.com/camolechowski/ai-llm-mcp-research/edit/main/README.md#model-context-protocol-repository-readme-index) for servers recommended by the folks behind it!

### Actively Testing
Currently In Use in Development Workflows (for Hobby Projects)

- [@zengwenliang416's Sequential Thinking MCP](https://github.com/zengwenliang416/mcp-server-sequential-thinking)
- [@agentdeskai's BrowserTools MCP](https://github.com/AgentDeskAI/browser-tools-mcp)
- [namu's Browser MCP](https://browsermcp.io)

### Actively Researching
Currently Familiarizing Myself with Available Documentation & Community Input

- [@eyaltoledano's Claude Task Master MCP](https://github.com/eyaltoledano/claude-task-master)
- [@oraios's SERENA (Semantic Retrieval & Editing Noetic Agent) MCP](https://github.com/oraios/serena)
- [@wonderwhy-er's DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)
- [@upstash's Context7 MCP](https://github.com/upstash/context7)
- [@microsoft's Playwright MCP](https://github.com/microsoft/playwright-mcp)
- [@alioshr's Memory Bank MCP](https://github.com/alioshr/memory-bank-mcp)
- [@modelcontextprotocol's Puppeteer MCP](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/puppeteer)
- [@luiyoshio's MCP Compass MCP](https://github.com/liuyoshio/mcp-compass)
- [DuckDuckGo Search MCP](https://github.com/nickclyde/duckduckgo-mcp-server)

### [Model Context Protocol Servers Repository](https://github.com/modelcontextprotocol/servers) README Index
Links to Specific Sections of the MCP Repo's README

- [Reference Servers](https://github.com/modelcontextprotocol/servers?tab=readme-ov-file#-reference-servers) 
  - [Everything MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/everything)
  - [Fetch MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/fetch) 
  - [Filesystem MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/filesystem)
  - [Git MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/git)
  - [Memory MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/memory)
  - [Sequential Thinking MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/sequentialthinking)
  - [Time MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/time)

- [Archived Reference Servers](https://github.com/modelcontextprotocol/servers?tab=readme-ov-file#archived)
- [Third-Party Servers](https://github.com/modelcontextprotocol/servers#-third-party-servers)
  - [Official Integrations](https://github.com/modelcontextprotocol/servers?tab=readme-ov-file#%EF%B8%8F-official-integrations)
  - [Community Servers](https://github.com/modelcontextprotocol/servers?tab=readme-ov-file#-community-servers)
- [Frameworks](https://github.com/modelcontextprotocol/servers?tab=readme-ov-file#-frameworks)
- [Resources](https://github.com/modelcontextprotocol/servers?tab=readme-ov-file#-resources)

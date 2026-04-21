# Sim — Scraped Documentation

**Source:** https://sim.ai
**Pages scraped:** 15
**Total characters:** 66972

---

## Getting Started | Sim Docs

**URL:** https://docs.sim.ai/getting-started

Getting Started | Sim Docs
Copy page
Getting Started
Build your first AI workflow in 10 minutes. In this tutorial, you'll create a people research agent that uses advanced LLM-powered search tools to extract and structure information about individuals.
What You'll Build
A people research agent that:
Accepts user input through a chat interface
Searches the web using AI-powered tools (Exa and Linkup)
Extracts and structures information about individuals
Returns formatted JSON data with location, profession, and education
Step-by-Step Tutorial
Click
New Workflow
in the dashboard and name it "Getting Started".
Every new workflow includes a
Start block
by default—this is the entry point that receives user input. Since we'll trigger this workflow via chat, no configuration is needed for the Start block.
Drag an
Agent Block
onto the canvas from the left panel and configure it:
Model
: Select "OpenAI GPT-4o"
System Prompt
: "You are a people research agent. When given a person's name, use your available search tools to find comprehensive information about them including their location, profession, educational background, and other relevant details."
User Prompt
: Drag the connection from the Start block's output into this field to connect
<start.input>
to the user prompt
Enhance your agent with web search capabilities. Click on the Agent block to select it.
In the
Tools
section:
Click
Add Tool
Select
Exa
and
Linkup
from the available tools
Provide your API keys for both tools to enable web search and data access
Test your workflow using the
Chat panel
on the right side of the screen.
In the chat panel:
Click the dropdown and select
agent1.content
to view the agent's output
Enter a test message: "John is a software engineer from San Francisco who studied Computer Science at Stanford University."
Click
Send
to execute the workflow
The agent will analyze the person and return structured information.
Configure your agent to return structured JSON data. Click on the Agent block to select it.
In the
Response Format
section:
Click the
magic wand icon
(✨) next to the schema field
Enter the prompt: "create a schema named person, that contains location, profession, and education"
The AI will automatically generate the JSON schema
Return to the
Chat panel
to test the structured response format.
With the response format configured, new output options are now available:
Click the dropdown and select the structured output option (the schema you just created)
Enter a test message: "Sarah is a marketing manager from New York who has an MBA from Harvard Business School."
Click
Send
to execute the workflow
The agent will now return structured JSON output with the person's information organized into location, profession, and education fields.
What You've Built
You've successfully created an AI workflow that:
✅ Accepts user input through a chat interface
✅ Processes unstructured text using AI
✅ Integrates external search tools (Exa and Linkup)
✅ Returns structured JSON data with AI-generated schemas
✅ Demonstrates real-time testing and iteration
✅ Showcases the power of visual, no-code development
Key Concepts You Learned
Block Types Used
Start Block
Agent Block
Core Workflow Concepts
Data Flow
Connect blocks by dragging connections to pass data between workflow steps
Chat Interface
Test workflows in real-time with the chat panel and select different output options
Tool Integration
Extend agent capabilities by integrating external services like Exa and Linkup
Variable References
Access block outputs using the
<blockName.output>
syntax
Structured Output
Define JSON schemas to ensure consistent, formatted responses from AI
AI-Generated Schemas
Use the magic wand (✨) to generate schemas from natural language prompts
Iterative Development
Build, test, and refine workflows quickly with immediate feedback
Next Steps
Explore Blocks
Discover API, Function, Condition, and other blocks
Browse Integrations
Connect 1,000+ services including Gmail, Slack, Notion, and more
Add Custom Logic
Write custom functions for advanced data processing
Deploy Your Agent
Make your agent accessible via REST API or webhooks
Resources
Need detailed explanations?
Visit the
Blocks documentation
for comprehensive guides on each component.
Looking for integrations?
Explore the
Tools documentation
to see all 1,000+ available integrations.
Ready to go live?
Learn about
Execution and Deployment
to make your workflows production-ready.
Common Questions
How long does the getting started tutorial take?
About 10 minutes. The tutorial walks you through creating a people research agent with web search tools and structured output. You will have a fully working workflow by the end.
Do I need API keys to follow this tutorial?
You need API keys for the search tools (Exa and Linkup) used in this tutorial. For the AI model, you can either use Sim's hosted keys (included with your plan credits) or bring your own OpenAI API key. If you prefer not to set up search tool keys, you can still build a basic agent workflow without them.
Do I need coding experience to complete this tutorial?
No. The entire tutorial uses the visual drag-and-drop interface. You will connect blocks, configure settings, and test through the chat panel without writing any code.
Can I use a different AI model instead of GPT-4o?
Yes. The Agent block supports models from OpenAI, Anthropic, Google, Groq, Cerebras, DeepSeek, Mistral, xAI, and more. You can select any available model from the dropdown. If you self-host, you can also use local models through Ollama.
Can I import workflows from other tools?
Sim does not currently support importing workflows from other automation platforms. However, you can use the Copilot feature to describe what you want in natural language and have it build the workflow for you, which is often faster than manual recreation.
What if my workflow does not produce the expected output?
Use the Chat panel to test iteratively and inspect outputs from each block. You can click the dropdown to view different block outputs and pinpoint where the issue is. The execution logs (accessible from the Logs tab) show detailed information about each step including token usage, costs, and any errors.
Where do I go after completing this tutorial?
Explore the Blocks documentation to learn about Condition, Router, Function, and API blocks. Browse the Tools section to discover 1,000+ integrations you can add to your agents. When you are ready to deploy, check the Execution docs for REST API, webhook, and scheduled trigger options.
Previous
Introduction
Next
Quick Reference
On this page
What You'll Build
Step-by-Step Tutorial
What You've Built
Key Concepts You Learned
Block Types Used
Core Workflow Concepts
Next Steps
Resources

---

## Sim — The AI Workspace | Build, Deploy & Manage AI Agents

**URL:** https://sim.ai

Sim — The AI Workspace | Build, Deploy & Manage AI Agents
Skip to main content
Sim is the open-source AI workspace where teams build, deploy, and manage AI agents. Connect 1,000+ integrations and every major LLM — including OpenAI, Anthropic Claude, Google Gemini, Mistral, and xAI Grok — to create agents that automate real work. Build agents visually with the workflow builder, conversationally through Mothership, or programmatically with the API. Trusted by over 100,000 builders at startups and Fortune 500 companies. SOC2 compliant.
Build AI Agents
Sim is the AI Workspace for Agent Builders
Get a demo
Get started
Sim includes
11
pre-built workflow templates covering OCR processing, release management, meeting follow-ups, resume scanning, email triage, competitor monitoring, social listening, data enrichment, feedback analysis, code review, and knowledge base Q&A. Each template connects real integrations and LLMs — pick one, customise it, and deploy in minutes.
OCR Invoice to DB
GitHub Release Agent
Meeting Follow-up Agent
CV/Resume Scanner
Email Triage Agent
Competitor Monitor
Social Listening Agent
Data Enrichment Pipeline
Customer Feedback Digest
PR Review Agent
Knowledge Base QA
Templates
Ship your agent in minutes
Pre-built templates for every use case—pick one, swap
models and tools to fit your stack, and deploy.
OCR Invoice to DB
GitHub Release Agent
Meeting Follow-up Agent
CV/Resume Scanner
Email Triage Agent
Competitor Monitor
Social Listening Agent
Data Enrichment Pipeline
Customer Feedback Digest
PR Review Agent
Knowledge Base QA
Use template
Workspace
Sim's workspace includes four core features: Mothership, an AI command center for natural-language control of your entire workspace; Tables, a built-in database for filtering, sorting, and wiring data directly into workflows; Files, a shared document store for uploading, creating, and sharing documents, spreadsheets, and media across teams and agents; and Logs, full execution tracing with inputs, outputs, cost, and duration for every run.
O
n
e
w
o
r
k
s
p
a
c
e
t
o
b
u
i
l
d
,
d
e
p
l
o
y
,
a
n
d
m
a
n
a
g
e
A
I
a
g
e
n
t
s
.
Build agents, connect your data, and monitor every run — all in one workspace.
Mothership
Tables
Files
Logs
Your AI command center
Direct your entire AI workforce from one place. Build agents, spin up workflows, query tables, and manage every resource across your workspace — in natural language.
Explore mothership
Teams
Realtime
collaboration
Sim supports real-time multiplayer collaboration. Teams build AI agents together in a shared workspace with live cursors, presence indicators, and concurrent editing. Features include role-based access control, shared agents and workflows, and team workspace management.
Grab your team. Build agents together
in real-time inside your workspace.
Vikhyath
Alexa
Sim collaboration interface with real-time cursors, shared workspace, and team presence indicators
Blog
How we built realtime collaboration
Pricing
Pricing
Sim pricing: Community plan is free with 1,000 credits and 5GB storage. Pro plan is $25 per month with 6,000 credits and 50GB storage. Max plan is $100 per month with 25,000 credits and 500GB storage. Enterprise pricing is custom with SSO, SCIM, SOC2 compliance, self-hosting, and dedicated support. All plans include CLI, SDK, and MCP access.
Community
For individuals getting started with AI agents
Free
Get started
1,000 credits (trial)
5GB file storage
3 tables · 1,000 rows each
5 min execution limit
7-day log retention
CLI/SDK/MCP Access
Pro
For professionals deploying AI agents
$25
per month
Get started
6,000 credits/mo · +50/day
50GB file storage
25 tables · 5,000 rows each
50 min execution · 150 runs/min
Unlimited log retention
CLI/SDK/MCP Access
Max
For teams building AI agents at scale
$100
per month
Get started
25,000 credits/mo · +200/day
500GB file storage
25 tables · 5,000 rows each
50 min execution · 300 runs/min
Unlimited log retention
CLI/SDK/MCP Access
Enterprise
For organizations needing security and scale
Custom
Get a demo
Custom credits & infra limits
Custom file storage
10,000 tables · 1M rows each
Custom execution limits
Unlimited log retention
SSO & SCIM · SOC2
Self hosting · Dedicated support
Build together

---

## Introduction | Sim Docs

**URL:** https://docs.sim.ai

Introduction | Sim Docs
Copy page
Introduction
Sim is the open-source AI workspace where teams build, deploy, and manage AI agents. Create agents visually with the workflow builder, conversationally through Mothership, or programmatically with the API. Connect AI models, databases, APIs, and 1,000+ business tools to build agents that automate real work — from chatbots and compliance agents to data pipelines and ITSM automation.
What You Can Build
AI Assistants & Chatbots
Build intelligent conversational agents that integrate with your tools and data. Enable capabilities like web search, calendar management, email automation, and seamless interaction with business systems.
Business Process Automation
Eliminate manual tasks across your organization. Automate data entry, generate reports, respond to customer inquiries, and streamline content creation workflows.
Data Processing & Analysis
Transform raw data into actionable insights. Extract information from documents, perform dataset analysis, generate automated reports, and synchronize data across platforms.
API Integration Workflows
Orchestrate complex multi-service interactions. Create unified API endpoints, implement sophisticated business logic, and build event-driven automation systems.
How It Works
Visual Workflow Builder
Design agent logic using an intuitive drag-and-drop canvas. Connect AI models, databases, APIs, and third-party services through a visual interface that makes complex automation easy to understand and maintain.
Modular Block System
Build with specialized components: processing blocks (AI agents, API calls, custom functions), logic blocks (conditional branching, loops, routers), and output blocks (responses, evaluators). Each block handles a specific task in your workflow.
Flexible Execution Triggers
Launch workflows through multiple channels including chat interfaces, REST APIs, webhooks, scheduled cron jobs, or external events from platforms like Slack and GitHub.
Real-time Collaboration
Enable your team to build together. Multiple users can edit workflows simultaneously with live updates and granular permission controls.
Integrations
Sim provides native integrations with 1,000+ services across multiple categories:
AI Models
: OpenAI, Anthropic, Google Gemini, Groq, Cerebras, local models via Ollama or VLLM
Communication
: Gmail, Slack, Microsoft Teams, Telegram, WhatsApp
Productivity
: Notion, Google Workspace, Airtable
Development
: GitHub, Jira, Linear, automated browser testing
Search & Data
: Google Search, Perplexity, Firecrawl, Exa AI
Databases
: PostgreSQL, MySQL, Supabase, Pinecone, Qdrant
For custom integrations, leverage our
MCP (Model Context Protocol) support
to connect any external service or tool.
Copilot
Ask Questions & Get Guidance
Copilot answers questions about Sim, explains your workflows, and provides suggestions for improvements. Use the
@
symbol to reference workflows, blocks, documentation, knowledge, and logs for contextual assistance.
Build & Edit Workflows
Switch to Agent mode to let Copilot propose and apply changes directly to your canvas. Add blocks, configure settings, wire variables, and restructure workflows with natural language commands.
Adaptive Reasoning Levels
Choose from Fast, Auto, Advanced, or Behemoth modes depending on task complexity. Start with Fast for simple questions, scale up to Behemoth for complex architectural changes and deep debugging.
Learn more about
Copilot capabilities
and how to maximize productivity with AI assistance.
Deployment Options
Cloud-Hosted
Launch immediately at
sim.ai
with fully managed infrastructure, automatic scaling, and built-in observability. Focus on building workflows while we handle the operations.
Self-Hosted
Deploy on your own infrastructure using Docker Compose or Kubernetes. Maintain complete control over your data with support for local AI models through Ollama integration.
Next Steps
Ready to build your first AI agent?
Getting Started
Build your first agent in 10 minutes
Blocks
Learn about the building blocks
Tools & Integrations
Explore 1,000+ integrations
Team Permissions
Set up workspace roles and permissions
Common Questions
Is Sim free to use?
Sim offers a free Community plan with 1,000 one-time credits to get started. Paid plans start at $25/month (Pro) with 5,000 credits and go up to $100/month (Max) with 20,000 credits. Annual billing is available at a 15% discount. You can also self-host Sim for free on your own infrastructure.
Is Sim open source?
Yes. Sim is open source under the Apache 2.0 license. The full source code is available on GitHub and you can self-host it, contribute to development, or modify it for your own needs. Enterprise features (SSO, access control) have a separate license that requires a subscription for production use.
Which AI models and providers are supported?
Sim supports 15+ providers including OpenAI, Anthropic, Google Gemini, Groq, Cerebras, DeepSeek, Mistral, xAI, and OpenRouter. You can also run local models through Ollama or VLLM at no API cost. Bring Your Own Key (BYOK) is supported so you can use your own API keys at base provider pricing with no markup.
Do I need coding experience to use Sim?
No. Sim lets you build agents visually by dragging blocks onto a canvas and connecting them, or conversationally through Mothership using natural language. For advanced use cases, the Function block lets you write custom JavaScript, and the full API/SDK is available for programmatic access.
Can I self-host Sim?
Yes. Sim provides Docker Compose configurations for self-hosted deployments. The stack includes the Sim application, a PostgreSQL database with pgvector, and a realtime collaboration server. You can also integrate local AI models via Ollama for a fully offline setup.
Is there a limit on how many workflows I can create?
There is no limit on the number of workflows you can create on any plan. Usage limits apply to execution credits, rate limits, and file storage, which vary by plan tier.
What integrations are available?
Sim offers 1,000+ native integrations across categories including AI models, communication tools (Gmail, Slack, Teams, Telegram), productivity apps (Notion, Google Workspace, Airtable), development tools (GitHub, Jira, Linear), search services (Google Search, Perplexity, Exa), and databases (PostgreSQL, Supabase, Pinecone). For anything not built in, you can use the MCP (Model Context Protocol) support to connect custom services.
How does Sim compare to other AI agent builders?
Sim is an AI workspace — not just a workflow tool or an agent framework. It combines a visual workflow builder, Mothership for natural-language agent creation, knowledge bases, tables, and full observability in one environment. Teams build agents visually, conversationally, or with code, then deploy and manage them with enterprise governance, real-time collaboration, and staging-to-production workflows.
Next
Getting Started
On this page
What You Can Build
How It Works
Integrations
Copilot
Deployment Options
Next Steps

---

## AI Models Directory | Sim

**URL:** https://sim.ai/models

AI Models Directory | Sim
Models
Compare AI Models
Browse
95
AI models across
16
providers. Compare pricing, context windows, and capabilities.
Compare models
Side-by-side comparison of top models across key metrics.
Cost
Per 1M tokens
Gemini 3.1 Flash Lite Preview
$0.25
input /
$1.5
output
Gemini 3 Flash Preview
$0.5
input /
$3
output
Gemini 3.1 Pro Preview
$2
input /
$12
output
GPT-5.4
$2.5
input /
$15
output
Claude Sonnet 4.6
$3
input /
$15
output
Claude Sonnet 4.5
$3
input /
$15
output
Claude Sonnet 4.0
$3
input /
$15
output
Claude Opus 4.7
$5
input /
$25
output
Claude Opus 4.6
$5
input /
$25
output
GPT-5.4 Pro
$30
input /
$180
output
Context window
Max tokens
Claude Opus 4.7
1M
Claude Opus 4.6
1M
Claude Sonnet 4.6
1M
Claude Sonnet 4.5
1M
Claude Sonnet 4.0
1M
Gemini 3 Flash Preview
1M
Gemini 3.1 Pro Preview
1.05M
Gemini 3.1 Flash Lite Preview
1.05M
GPT-5.4 Pro
1.05M
GPT-5.4
1.05M
All models
All
OpenAI
Anthropic
Google
DeepSeek
xAI
Cerebras
Groq
Mistral AI
OpenAI
21
models ·
OpenAI's models
GPT-4.1
gpt-4.1
· Input
$2
/1M · Output
$8
/1M
· 1.05M context
GPT-4.1 Mini
gpt-4.1-mini
· Input
$0.4
/1M · Output
$1.6
/1M
· 1.05M context
GPT-4.1 Nano
gpt-4.1-nano
· Input
$0.1
/1M · Output
$0.4
/1M
· 1.05M context
GPT-5.4 Pro
gpt-5.4-pro
· Input
$30
/1M · Output
$180
/1M
· 1.05M context
GPT-5.4
gpt-5.4
· Input
$2.5
/1M · Output
$15
/1M
· 1.05M context
GPT-5.4 Mini
gpt-5.4-mini
· Input
$0.75
/1M · Output
$4.5
/1M
· 400k context
GPT-5.4 Nano
gpt-5.4-nano
· Input
$0.2
/1M · Output
$1.25
/1M
· 400k context
GPT-5.2 Pro
gpt-5.2-pro
· Input
$21
/1M · Output
$168
/1M
· 400k context
GPT-5.2
gpt-5.2
· Input
$1.75
/1M · Output
$14
/1M
· 400k context
GPT-5.1
gpt-5.1
· Input
$1.25
/1M · Output
$10
/1M
· 400k context
GPT-5 Pro
gpt-5-pro
· Input
$15
/1M · Output
$120
/1M
· 400k context
GPT-5
gpt-5
· Input
$1.25
/1M · Output
$10
/1M
· 400k context
GPT-5 Mini
gpt-5-mini
· Input
$0.25
/1M · Output
$2
/1M
· 400k context
GPT-5 Nano
gpt-5-nano
· Input
$0.05
/1M · Output
$0.4
/1M
· 400k context
GPT-5 Chat Latest
gpt-5-chat-latest
· Input
$1.25
/1M · Output
$10
/1M
· 128k context
o4 Mini
o4-mini
· Input
$1.1
/1M · Output
$4.4
/1M
· 200k context
o3 Pro
o3-pro
· Input
$20
/1M · Output
$80
/1M
· 200k context
o3
o3
· Input
$2
/1M · Output
$8
/1M
· 200k context
o3 Mini
o3-mini
· Input
$1.1
/1M · Output
$4.4
/1M
· 200k context
o1
o1
· Input
$15
/1M · Output
$60
/1M
· 200k context
GPT-4o
gpt-4o
· Input
$2.5
/1M · Output
$10
/1M
· 128k context
Anthropic
10
models ·
Anthropic's Claude models
Claude Opus 4.7
claude-opus-4-7
· Input
$5
/1M · Output
$25
/1M
· 1M context
Claude Opus 4.6
claude-opus-4-6
· Input
$5
/1M · Output
$25
/1M
· 1M context
Claude Sonnet 4.6
claude-sonnet-4-6
· Input
$3
/1M · Output
$15
/1M
· 1M context
Claude Opus 4.5
claude-opus-4-5
· Input
$5
/1M · Output
$25
/1M
· 200k context
Claude Opus 4.1
claude-opus-4-1
· Input
$15
/1M · Output
$75
/1M
· 200k context
Claude Opus 4.0
claude-opus-4-0
· Input
$15
/1M · Output
$75
/1M
· 200k context
Claude Sonnet 4.5
claude-sonnet-4-5
· Input
$3
/1M · Output
$15
/1M
· 1M context
Claude Sonnet 4.0
claude-sonnet-4-0
· Input
$3
/1M · Output
$15
/1M
· 1M context
Claude Haiku 4.5
claude-haiku-4-5
· Input
$1
/1M · Output
$5
/1M
· 200k context
Claude 3 Haiku
claude-3-haiku-20240307
· Input
$0.25
/1M · Output
$1.25
/1M
· 200k context
Google
9
models ·
Google's Gemini models
Gemini 3.1 Pro Preview
gemini-3.1-pro-preview
· Input
$2
/1M · Output
$12
/1M
· 1.05M context
Gemini 3.1 Flash Lite Preview
gemini-3.1-flash-lite-preview
· Input
$0.25
/1M · Output
$1.5
/1M
· 1.05M context
Gemini 3 Flash Preview
gemini-3-flash-preview
· Input
$0.5
/1M · Output
$3
/1M
· 1M context
Gemini 2.5 Pro
gemini-2.5-pro
· Input
$1.25
/1M · Output
$10
/1M
· 1.05M context
Gemini 2.5 Flash
gemini-2.5-flash
· Input
$0.3
/1M · Output
$2.5
/1M
· 1.05M context
Gemini 2.5 Flash Lite
gemini-2.5-flash-lite
· Input
$0.1
/1M · Output
$0.4
/1M
· 1.05M context
Gemini 2.0 Flash
gemini-2.0-flash
· Input
$0.1
/1M · Output
$0.4
/1M
· 1.05M context
Gemini 2.0 Flash Lite
gemini-2.0-flash-lite
· Input
$0.075
/1M · Output
$0.3
/1M
· 1.05M context
Deep Research Pro Preview 12 2025
deep-research-pro-preview-12-2025
· Input
$2
/1M · Output
$2
/1M
· 1M context
DeepSeek
4
models ·
DeepSeek's chat models
DeepSeek Chat
deepseek-chat
· Input
$0.28
/1M · Output
$0.42
/1M
· 128k context
DeepSeek V3
deepseek-v3
· Input
$0.28
/1M · Output
$0.42
/1M
· 128k context
DeepSeek R1
deepseek-r1
· Input
$0.55
/1M · Output
$2.19
/1M
· 128k context
DeepSeek Reasoner
deepseek-reasoner
· Input
$0.28
/1M · Output
$0.42
/1M
· 128k context
xAI
12
models ·
xAI's Grok models
Grok 4 Latest
grok-4-latest
· Input
$3
/1M · Output
$15
/1M
· 256k context
Grok 4 0709
grok-4-0709
· Input
$3
/1M · Output
$15
/1M
· 256k context
Grok 4.1 Fast Reasoning
grok-4-1-fast-reasoning
· Input
$0.2
/1M · Output
$0.5
/1M
· 2M context
Grok 4.1 Fast Non Reasoning
grok-4-1-fast-non-reasoning
· Input
$0.2
/1M · Output
$0.5
/1M
· 2M context
Grok 4 Fast Reasoning
grok-4-fast-reasoning
· Input
$0.2
/1M · Output
$0.5
/1M
· 2M context
Grok 4 Fast Non Reasoning
grok-4-fast-non-reasoning
· Input
$0.2
/1M · Output
$0.5
/1M
· 2M context
Grok Code Fast 1
grok-code-fast-1
· Input
$0.2
/1M · Output
$1.5
/1M
· 256k context
Grok 4.20 0309 Reasoning
grok-4.20-0309-reasoning
· Input
$2
/1M · Output
$6
/1M
· 2M context
Grok 4.20 0309 Non Reasoning
grok-4.20-0309-non-reasoning
· Input
$2
/1M · Output
$6
/1M
· 2M context
Grok 4.20 Multi Agent 0309
grok-4.20-multi-agent-0309
· Input
$2
/1M · Output
$6
/1M
· 2M context
Grok 3 Latest
grok-3-latest
· Input
$3
/1M · Output
$15
/1M
· 131k context
Grok 3 Fast Latest
grok-3-fast-latest
· Input
$5
/1M · Output
$25
/1M
· 131k context
Cerebras
4
models ·
Cerebras Cloud LLMs
GPT OSS 120B
cerebras/gpt-oss-120b
· Input
$0.35
/1M · Output
$0.75
/1M
· 131k context
Llama 3 1 8B
cerebras/llama3.1-8b
· Input
$0.1
/1M · Output
$0.1
/1M
· 33k context
Qwen 3 235B A22B Instruct 2507
cerebras/qwen-3-235b-a22b-instruct-2507
· Input
$0.6
/1M · Output
$1.2
/1M
· 131k context
Zai GLM 4.7
cerebras/zai-glm-4.7
· Input
$2.25
/1M · Output
$2.75
/1M
· 131k context
Groq
8

[SCRAPER NOTE: This page was truncated by the scraper due to length. Content continues on the live page.]

---

## Integrations | Sim

**URL:** https://sim.ai/integrations

Integrations | Sim
Integrations
Integrations
Connect every tool your team uses. Build agents that automate real work across
192
apps and services.
All Integrations
All
Developer Tools
Analytics
Documents
Search
AI
Productivity
Communication
Databases
Sales
Security
Customer Support
Email
File Storage
Design
CRM
HR
E-commerce
1Password
Manage secrets and items in 1Password vaults
A2A
Interact with external A2A-compatible agents
AgentMail
Manage email inboxes, threads, and messages with AgentMail
Agiloft
Manage records in Agiloft CLM
Ahrefs
SEO analysis with Ahrefs
Airtable
Read, create, and update Airtable
Airweave
Search your synced data collections
Algolia
Search and manage Algolia indices
Amazon DynamoDB
Connect to Amazon DynamoDB
Amazon RDS
Connect to Amazon RDS via Data API
Amazon SQS
Connect to Amazon SQS
Amplitude
Track events and query analytics from Amplitude
Apify
Run Apify actors and retrieve results
Apollo
Search, enrich, and manage contacts with Apollo.io
ArXiv
Search and retrieve academic papers from ArXiv
Asana
Interact with Asana
Ashby
Manage candidates, jobs, and applications in Ashby
Athena
Run SQL queries on data in Amazon S3 using AWS Athena
Attio
Manage records, notes, tasks, lists, comments, and more in Attio CRM
AWS IAM
Manage AWS IAM users, roles, policies, and groups
AWS Secrets Manager
Connect to AWS Secrets Manager
AWS STS
Connect to AWS Security Token Service
AWS Textract
Extract text, tables, and forms from documents
Azure AD
Manage users and groups in Azure AD (Microsoft Entra ID)
Box
Manage files, folders, and e-signatures with Box
Brandfetch
Look up brand assets, logos, colors, and company info
Bright Data
Scrape websites, search engines, and extract structured data
Browser Use
Run browser automation tasks
Cal Com
Manage Cal.com bookings, event types, schedules, and availability
Calendly
Manage Calendly scheduling and events
Circleback
AI-powered meeting notes and action items
Clay
Populate Clay workbook
Clerk
Manage users, organizations, and sessions in Clerk
Cloudflare
Manage DNS, domains, certificates, and cache
CloudFormation
Manage and inspect AWS CloudFormation stacks, resources, and drift
CloudWatch
Query and monitor AWS CloudWatch logs, metrics, and alarms
Confluence
Interact with Confluence
CrowdStrike
Query CrowdStrike Identity Protection sensors and documented aggregates
Cursor
Launch and manage Cursor cloud agents to work on GitHub repositories
Dagster
Orchestrate data pipelines and manage job runs with Dagster
Databricks
Run SQL queries and manage jobs on Databricks
Datadog
Monitor infrastructure, applications, and logs with Datadog
Devin
Autonomous AI software engineer
Discord
Interact with Discord
DocuSign
Send documents for e-signature via DocuSign
Dropbox
Upload, download, share, and manage files in Dropbox
DSPy
Run predictions using self-hosted DSPy programs
Dub
Link management with Dub
DuckDuckGo
Search with DuckDuckGo
Elasticsearch
Search, index, and manage data in Elasticsearch
ElevenLabs
Convert TTS using ElevenLabs
Embeddings
Generate Open AI embeddings
Enrich
B2B data enrichment and LinkedIn intelligence with Enrich.so
Evernote
Manage notes, notebooks, and tags in Evernote
Exa
Search with Exa AI
Extend
Parse and extract content from documents
Fathom
Access meeting recordings, transcripts, and summaries
File
Read and write workspace files
Firecrawl
Scrape, search, crawl, map, and extract web data
Fireflies
Interact with Fireflies.ai meeting transcripts and recordings
Gamma
Generate presentations, documents, and webpages with AI
GitHub
Interact with GitHub or trigger workflows from GitHub events
GitLab
Interact with GitLab projects, issues, merge requests, and pipelines
Gmail
Send, read, search, and move Gmail messages or trigger workflows from Gmail events
Gong
Revenue intelligence and conversation analytics
Google Ads
Query campaigns, ad groups, and performance metrics
Google BigQuery
Query, list, and insert data in Google BigQuery
Google Books
Search and retrieve book information
Google Calendar
Manage Google Calendar events
Google Contacts
Manage Google Contacts
Google Docs
Read, write, and create documents
Google Drive
Manage files, folders, and permissions
Google Forms
Manage Google Forms and responses
Google Groups
Manage Google Workspace Groups and their members
Google Maps
Geocoding, directions, places, and distance calculations
Google Meet
Create and manage Google Meet meetings
Google PageSpeed
Analyze webpage performance with Google PageSpeed Insights
Google Search
Search the web
Google Sheets
Read, write, and update data with sheet selection
Google Slides
Read, write, and create presentations
Google Tasks
Manage Google Tasks
Google Translate
Translate text using Google Cloud Translation
Google Vault
Search, export, and manage holds/exports for Vault matters
Grafana
Interact with Grafana dashboards, alerts, and annotations
Grain
Access meeting recordings, transcripts, and AI summaries
Granola
Access meeting notes and transcripts from Granola
Greenhouse
Manage candidates, jobs, and applications in Greenhouse
Greptile
AI-powered codebase search and Q&A
Hex
Run and manage Hex projects
HubSpot
Interact with HubSpot CRM or trigger workflows from HubSpot events
Hugging Face
Use Hugging Face Inference API
Hunter io
Find and verify professional email addresses
Image Generator
Generate images
IMAP Email
Trigger workflows when new emails arrive via IMAP (works with any email provider)
incidentio
Manage incidents with incident.io
Infisical
Manage secrets with Infisical
Intercom
Manage contacts, companies, conversations, tickets, and messages in Intercom
Jina
Search the web or extract content from URLs
Jira
Interact with Jira
Jira Service Management
Interact with Jira Service Management
Kalshi
Access prediction markets and trade on Kalshi
Ketch
Manage privacy consent, subscriptions, and data subject rights
Knowledge
Use vector search
LangSmith
Forward workflow runs to LangSmith for observability
LaunchDarkly
Manage feature flags with LaunchDarkly.
Lemlist
Manage outreach activities, leads, and send emails via Lemlist
Linear
Interact with Linear issues, projects, and more
LinkedIn
Share posts and manage your LinkedIn presence
Linkup
Search the web with Linkup
Loops
Manage contacts and send emails with Loops
Luma
Manage events and guests on Luma
Mailchimp
Manage audiences, campaigns, and marketing automation in Mailchimp
Mailgun
Send emails and manage mailing lists with Mailgun
Mem0
Agent memory management
Memory
Add memory store
Microsoft Dataverse
Manage records in Microsoft Dataverse tables
Microsoft Excel
Read and write data with sheet selection
Microsoft Planner
Manage tasks, plans, and buckets in Microsoft Planner
Microsoft Teams
Manage messages, reactions, and members in Teams
Mistral Parser
Extract text from PDF documents
Monday
Manage Monday.com boards, items, and groups
MongoDB
Connect to MongoDB database
MySQL
Connect to MySQL database
Neo4j
Connect to Neo4j graph database
Notion
Manage Notion pages
Obsidian
Interact with your Obsidian vault via the Local REST API
Okta
Manage users and groups in Okta
OneDrive
Create, upload, download, list, and delete files
Outlook
Send, read, draft, forward, and move Outlook email messages
PagerDuty
Manage incidents and on-call schedules with PagerDuty
Parallel AI
Web research with Parallel AI
Perplexity
Use Perplexity AI for chat and search
Pinecone
Use Pinecone vector database
Pipedrive
Interact with Pipedrive CRM
Polymarket
Access prediction markets data from Polymarket
PostgreSQL
Connect to PostgreSQL database
PostHog
Product analytics and feature management
Profound
AI visibility and analytics with Profound
Pulse
Extract text from documents using Pulse OCR
Qdrant
Use Qdrant vector database
Quiver
Generate and vectorize SVGs
Reddit
Access Reddit data and content
Redis
Key-value operations with Redis
Reducto
Extract text from PDF documents
Resend
Send emails and manage contacts with Resend.
RevenueCat
Manage in-app subscriptions and entitlements
Rippling
Manage workers, departments, custom objects, and company data in Rippling
Rootly
Manage incidents, alerts, and on-call with Rootly
S3
Upload, download, list, and manage S3 files
Salesforce
Interact with Salesforce CRM
Search
Search the web ($0.01 per search)
SendGrid
Send emails and manage contacts, lists, and templates with SendGrid
Sentry
Manage Sentry issues, projects, events, and releases
Serper
Search the web using Serper
ServiceNow
Create, read, update, and delete ServiceNow records
SFTP
Transfer files via SFTP (SSH File Transfer Protocol)
Sharepoint
Work with pages and lists
Shopify
Manage products, orders, customers, and inventory in your Shopify store
Similarweb
Website traffic and analytics data
Sixtyfour AI
Enrich leads and companies with AI-powered research
Slack
Send, update, delete messages, manage views and modals, add or remove reactions, manage canvases, get channel info and user presence in Slack
SMTP
Send emails via any SMTP mail server
Speech-to-Text
Convert speech to text using AI
SSH
Connect to remote servers via SSH
Stagehand
Web automation and data extraction
Stripe
Process payments and manage Stripe data
Supabase
Use Supabase database
Tailscale
Manage devices and network settings in your Tailscale tailnet
Tavily
Search and extract information
Telegram
Interact with Telegram
Text-to-Speech
Convert text to speech using AI voices
Tinybird
Send events and query data with Tinybird
Translate
Translate text to any language
Trello
Manage Trello lists, cards, and activity
Twilio SMS
Send SMS messages
Twilio Voice
Make and manage phone calls
Typeform
Interact with Typeform
Upstash
Serverless Redis with Upstash
Vercel
Manage Vercel deployments, projects, and infrastructure
Video Generator
Generate videos from text using AI
Vision
Analyze images with vision models
Wealthbox
Interact with Wealthbox
Webflow
Manage Webflow CMS collections
WhatsApp
Send WhatsApp messages
Wikipedia
Search and retrieve content from Wikipedia
WordPress
Manage WordPress content
Workday
Manage workers, hiring, onboarding, and HR operations in Workday
X
Interact with X
YouTube
Interact with YouTube videos, channels, and playlists
Zendesk
Manage support tickets, users, and organizations in Zendesk
Zep
Long-term memory for AI agents
Zoom
Create and manage Zoom meetings and recordings
Don't see the integration you need?
Let us know and we'll prioritize it.
Request an integration

---

## Sim — The AI Workspace | Build, Deploy & Manage AI Agents

**URL:** https://sim.ai/#pricing

Sim — The AI Workspace | Build, Deploy & Manage AI Agents
Skip to main content
Sim is the open-source AI workspace where teams build, deploy, and manage AI agents. Connect 1,000+ integrations and every major LLM — including OpenAI, Anthropic Claude, Google Gemini, Mistral, and xAI Grok — to create agents that automate real work. Build agents visually with the workflow builder, conversationally through Mothership, or programmatically with the API. Trusted by over 100,000 builders at startups and Fortune 500 companies. SOC2 compliant.
Build AI Agents
Sim is the AI Workspace for Agent Builders
Get a demo
Get started
Sim includes
11
pre-built workflow templates covering OCR processing, release management, meeting follow-ups, resume scanning, email triage, competitor monitoring, social listening, data enrichment, feedback analysis, code review, and knowledge base Q&A. Each template connects real integrations and LLMs — pick one, customise it, and deploy in minutes.
OCR Invoice to DB
GitHub Release Agent
Meeting Follow-up Agent
CV/Resume Scanner
Email Triage Agent
Competitor Monitor
Social Listening Agent
Data Enrichment Pipeline
Customer Feedback Digest
PR Review Agent
Knowledge Base QA
Templates
Ship your agent in minutes
Pre-built templates for every use case—pick one, swap
models and tools to fit your stack, and deploy.
OCR Invoice to DB
GitHub Release Agent
Meeting Follow-up Agent
CV/Resume Scanner
Email Triage Agent
Competitor Monitor
Social Listening Agent
Data Enrichment Pipeline
Customer Feedback Digest
PR Review Agent
Knowledge Base QA
Use template
Workspace
Sim's workspace includes four core features: Mothership, an AI command center for natural-language control of your entire workspace; Tables, a built-in database for filtering, sorting, and wiring data directly into workflows; Files, a shared document store for uploading, creating, and sharing documents, spreadsheets, and media across teams and agents; and Logs, full execution tracing with inputs, outputs, cost, and duration for every run.
O
n
e
w
o
r
k
s
p
a
c
e
t
o
b
u
i
l
d
,
d
e
p
l
o
y
,
a
n
d
m
a
n
a
g
e
A
I
a
g
e
n
t
s
.
Build agents, connect your data, and monitor every run — all in one workspace.
Mothership
Tables
Files
Logs
Your AI command center
Direct your entire AI workforce from one place. Build agents, spin up workflows, query tables, and manage every resource across your workspace — in natural language.
Explore mothership
Teams
Realtime
collaboration
Sim supports real-time multiplayer collaboration. Teams build AI agents together in a shared workspace with live cursors, presence indicators, and concurrent editing. Features include role-based access control, shared agents and workflows, and team workspace management.
Grab your team. Build agents together
in real-time inside your workspace.
Vikhyath
Alexa
Sim collaboration interface with real-time cursors, shared workspace, and team presence indicators
Blog
How we built realtime collaboration
Pricing
Pricing
Sim pricing: Community plan is free with 1,000 credits and 5GB storage. Pro plan is $25 per month with 6,000 credits and 50GB storage. Max plan is $100 per month with 25,000 credits and 500GB storage. Enterprise pricing is custom with SSO, SCIM, SOC2 compliance, self-hosting, and dedicated support. All plans include CLI, SDK, and MCP access.
Community
For individuals getting started with AI agents
Free
Get started
1,000 credits (trial)
5GB file storage
3 tables · 1,000 rows each
5 min execution limit
7-day log retention
CLI/SDK/MCP Access
Pro
For professionals deploying AI agents
$25
per month
Get started
6,000 credits/mo · +50/day
50GB file storage
25 tables · 5,000 rows each
50 min execution · 150 runs/min
Unlimited log retention
CLI/SDK/MCP Access
Max
For teams building AI agents at scale
$100
per month
Get started
25,000 credits/mo · +200/day
500GB file storage
25 tables · 5,000 rows each
50 min execution · 300 runs/min
Unlimited log retention
CLI/SDK/MCP Access
Enterprise
For organizations needing security and scale
Custom
Get a demo
Custom credits & infra limits
Custom file storage
10,000 tables · 1M rows each
Custom execution limits
Unlimited log retention
SSO & SCIM · SOC2
Self hosting · Dedicated support
Build together

---

## Partner Program | Sim

**URL:** https://sim.ai/partners

Partner Program | Sim
Partner Program
Build the future
of AI agents
Become a certified Sim partner. Complete Sim Academy, deploy real solutions, and earn recognition in the growing ecosystem of AI agent builders.
Learn more
Why partner with Sim
🎓
Interactive Learning
Learn on the real Sim canvas with drag-and-drop exercises, instant feedback, and guided exercises — not just videos.
🤝
Co-Marketing
Get listed in the Sim partner directory, featured in case studies, and promoted to the Sim user base.
💰
Revenue Share
Gold partners earn revenue share on referred customers and managed deployments.
🚀
Early Access
Partners get early access to new Sim features, APIs, and integrations before they launch publicly.
🛠️
Technical Support
Priority technical support, private Slack access, and a dedicated partner success manager for Gold partners.
📣
Community
Join a growing community of Sim builders. Share agents, collaborate on solutions, and shape the product roadmap.
How it works
01
Sign up & complete Sim Academy
Create an account and work through the Sim Academy certification program. Learn to build, integrate, and deploy AI agents through hands-on exercises.
02
Build & deploy real solutions
Put your skills to work. Build AI agents for clients, integrate Sim into existing products, or create your own Sim-powered applications.
03
Get certified & grow
Earn your partner certification and unlock perks, co-marketing opportunities, and revenue share as you scale your practice.
Partner tiers
Certified Partner
Entry
Requirements
Complete Sim Academy certification
Deploy at least 1 live agent
Perks
Official partner badge
Listed in partner directory
Early access to new features
Silver Partner
Growth
Requirements
All Certified requirements
3+ active client deployments
Sim Academy advanced certification
Perks
All Certified perks
Dedicated partner Slack channel
Co-marketing opportunities
Priority support
Gold Partner
Premier
Requirements
All Silver requirements
10+ active client deployments
Sim solutions architect certification
Perks
All Silver perks
Revenue share program
Joint case studies
Dedicated partner success manager
Influence product roadmap
Ready to get started?
Complete Sim Academy to earn your first certification and unlock partner benefits. It's free to start — no credit card required.

---

## Blog | Sim

**URL:** https://sim.ai/blog

Blog | Sim
Blog
Latest from Sim
Announcements, insights, and guides for building AI agent workflows.
Nov 12, 2025
Nov 12, 2025
$7M Series A
We’re excited to share that Sim has raised a $7M Series A led by Standard Capital to accelerate our vision for agentic workflows.
Nov 11, 2025
Nov 11, 2025
Realtime Collaboration
A high-level explanation into Sim realtime collaborative workflow builder - from operation queues to conflict resolution.
Nov 10, 2025
Nov 10, 2025
Inside the Sim Executor - DAG Based Execution with Native Parallelism
How we built a DAG-based execution engine with native parallel processing, intelligent edge routing, and stateful pause/resume capabilities
Oct 6, 2025
Oct 6, 2025
OpenAI AgentKit vs n8n vs Sim: AI Agent Workflow Builder Comparison
OpenAI just released AgentKit for building AI agents. How does it compare to workflow automation platforms like n8n and purpose-built AI agent builders like Sim?

---

## Overview | Sim Docs

**URL:** https://docs.sim.ai/blocks

Overview | Sim Docs
Copy page
Overview
The building components of your AI workflows
Blocks are the building components you connect together to create AI workflows. Think of them as specialized modules that each handle a specific task—from chatting with AI models to making API calls or processing data.
Core Block Types
Sim provides essential block types that handle the core functions of AI workflows:
Processing Blocks
Agent
- Chat with AI models (OpenAI, Anthropic, Google, local models)
Function
- Run custom JavaScript/TypeScript code
API
- Connect to external services via HTTP requests
Logic Blocks
Condition
- Branch workflow paths based on boolean expressions
Router
- Use AI to intelligently route requests to different paths
Evaluator
- Score and assess content quality using AI
Control Flow Blocks
Variables
- Set and manage workflow-scoped variables
Wait
- Pause workflow execution for a specified time delay
Human in the Loop
- Pause for human approval and feedback before continuing
Output Blocks
Response
- Format and return final results from your workflow
How Blocks Work
Each block has three main components:
Inputs
: Data coming into the block from other blocks or user input
Configuration
: Settings that control how the block behaves
Outputs
: Data the block produces for other blocks to use
Receive Input
: Block receives data from connected blocks or user input
Process
: Block processes the input according to its configuration
Output Results
: Block produces output data for the next blocks in the workflow
Connecting Blocks
You create workflows by connecting blocks together. The output of one block becomes the input of another:
Drag to connect
: Drag from an output port to an input port
Multiple connections
: One output can connect to multiple inputs
Branching paths
: Some blocks can route to different paths based on conditions
Common Patterns
Sequential Processing
Connect blocks in a chain where each block processes the output of the previous one:
User Input → Agent → Function → Response
Conditional Branching
Use Condition or Router blocks to create different paths:
User Input → Router → Agent A (for questions)
→ Agent B (for commands)
Quality Control
Use Evaluator blocks to assess and filter outputs:
Agent → Evaluator → Condition → Response (if good)
→ Agent (retry if bad)
Block Configuration
Each block type has specific configuration options:
All Blocks
:
Input/output connections
Error handling behavior
Execution timeout settings
AI Blocks
(Agent, Router, Evaluator):
Model selection (OpenAI, Anthropic, Google, local)
API keys and authentication
Temperature and other model parameters
System prompts and instructions
Logic Blocks
(Condition, Function):
Custom expressions or code
Variable references
Execution environment settings
Integration Blocks
(API, Response):
Endpoint configuration
Headers and authentication
Request/response formatting
Agent Block
Connect to AI models and create intelligent responses
Function Block
Run custom code to process and transform data
API Block
Integrate with external services and APIs
Condition Block
Create branching logic based on data evaluation
Human in the Loop Block
Pause for human approval and feedback before continuing
Variables Block
Set and manage workflow-scoped variables
Wait Block
Pause workflow execution for specified time delays
Common Questions
How many block types are available in Sim?
Sim has over 200 blocks in its registry, spanning core workflow blocks (Agent, Function, Condition, Router, etc.), integration blocks for third-party services (Gmail, Slack, GitHub, Notion, and many more), and trigger blocks that start workflows from external events like webhooks or schedules. Loop and parallel execution are built into the execution engine as container constructs on the canvas, rather than being standalone registry blocks.
Can one block's output connect to multiple downstream blocks?
Yes. A single output port can connect to multiple input ports on different blocks. This lets you fan out data from one processing step to several parallel paths without needing to duplicate the block.
What happens if a block in the middle of a workflow fails?
When a block encounters an error, the workflow stops executing along that path. Blocks that support error handling (like the Router) can route to an error path so you can handle failures gracefully instead of halting the entire workflow.
What is the difference between Processing blocks and Logic blocks?
Processing blocks (Agent, Function, API) transform or generate data — they do the actual work. Logic blocks (Condition, Router, Evaluator) make decisions about which path the workflow should take based on the data, without modifying it themselves.
Can I use blocks from different categories together in one workflow?
Absolutely. A typical workflow combines blocks from multiple categories. For example, you might use a trigger block to start the workflow, an Agent block to process input, a Condition block to branch logic, and an integration block like Gmail to send results.
Are there container blocks that can hold other blocks inside them?
Yes. Loop and Parallel are execution engine constructs that appear as container regions on the canvas. You drag other blocks inside them. Loop containers execute their contained blocks repeatedly, while Parallel containers execute their contained blocks concurrently across multiple branches. Unlike registry blocks, these are handled directly by the execution engine.
Previous
Zoom
Next
Agent
On this page
Core Block Types
Processing Blocks
Logic Blocks
Control Flow Blocks
Output Blocks
How Blocks Work
Connecting Blocks
Common Patterns
Sequential Processing
Conditional Branching
Quality Control
Block Configuration

---

## Overview | Sim Docs

**URL:** https://docs.sim.ai/tools

Overview | Sim Docs
Copy page
Overview
Powerful tools to enhance your agentic workflows
Tools are powerful components in Sim that allow your workflows to interact with external services, process data, and perform specialized tasks. They extend the capabilities of your agents and workflows by providing access to various APIs and services.
What is a Tool?
A tool is a specialized component that provides a specific functionality or integration with external services. Tools can be used to search the web, interact with databases, process images, generate text or images, communicate via messaging platforms, and much more.
Using Tools in Workflows
There are two primary ways to use tools in your Sim workflows:
As Standalone Blocks
: Tools can be added as individual
blocks on the canvas when you need deterministic, direct access to their
functionality. This gives you precise control over when and how the tool is
called.
As Agent Tools
: Tools can be added to Agent blocks by
clicking "Add tools" and configuring the required parameters. This allows
agents to dynamically choose which tools to use based on the context and
requirements of the task.
Tool Configuration
Each tool requires specific configuration to function properly. Common configuration elements include:
API Keys
: Many tools require authentication through API keys
Connection Parameters
: Endpoints, database identifiers, etc.
Input Formatting
: How data should be structured for the tool
Output Handling
: How to process the results from the tool
Available Tools
Sim provides a diverse collection of tools for various purposes, including:
AI and Language Processing
: OpenAI, ElevenLabs, Google Translate
Search and Research
: Google Search, Tavily, Exa, Perplexity
Document Manipulation
: Google Docs, Google Sheets, Notion, Confluence
Media Processing
: Vision
Communication
: Slack, WhatsApp, Twilio SMS, Gmail
Data Storage
: Pinecone, Supabase, Airtable
Development
: GitHub
Each tool has its own dedicated documentation page with detailed instructions on configuration and usage.
Tool Outputs
Tools typically return structured data that can be processed by subsequent blocks in your workflow. The format of this data varies depending on the tool and operation but generally includes:
The main content or result
Metadata about the operation
Status information
Refer to each tool's specific documentation to understand its exact output format.
Common Questions
How many tool integrations does Sim provide?
Sim includes over 180 service integrations with 1,000+ individual tool actions, spanning categories like AI and language processing, search and research, document manipulation, media processing, communication, data storage, development platforms, and more.
What is the difference between using a tool as a standalone block vs. as an agent tool?
As a standalone block, the tool is called deterministically at a fixed point in your workflow, giving you precise control. As an agent tool, the tool is provided to an AI agent that dynamically decides whether and when to call it based on context and task requirements.
How does tool authentication work?
Tools support multiple authentication methods. Many use OAuth for secure token-based access to external services. Others accept API keys provided by the user. Some tools also support Sim's hosted API keys, so you can use the tool without providing your own key.
Can tools return files?
Yes. Tools can return file-typed outputs with associated metadata like file name, MIME type, and size. File data can be provided as a buffer, base64 string, or a URL to download from. This enables workflows that process documents, images, and other binary content.
What happens when a tool API call fails?
Tools support configurable retry logic with settings for maximum retries, initial delay, and maximum delay. Error extractors parse provider-specific error responses to surface clear error messages. You can also configure whether only idempotent requests should be retried.
Can tools dynamically adapt their parameters based on context?
Yes. Tools support schema enrichment, where parameter schemas are dynamically updated at runtime based on other parameter values. For example, the knowledge search tool enriches its tag filter options based on the selected knowledgebase's actual tag definitions.
Previous
Workflow Block
Next
A2A
On this page
What is a Tool?
Using Tools in Workflows
Tool Configuration
Available Tools
Tool Outputs

---

## https://docs.sim.ai/webhooks

**URL:** https://docs.sim.ai/webhooks

> **Error:** Client error '404 Not Found' for url 'https://docs.sim.ai/webhooks'
For more information check: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404


---

## Using MCP Tools | Sim Docs

**URL:** https://docs.sim.ai/mcp

Using MCP Tools | Sim Docs
Copy page
Using MCP Tools
Connect external tools and services using the Model Context Protocol
The Model Context Protocol (
MCP
) allows you to connect external tools and services using a standardized protocol, enabling you to integrate APIs and services directly into your workflows. With MCP, you can extend Sim's capabilities by adding custom integrations that work seamlessly with your agents and workflows.
What is MCP?
MCP is an open standard that enables AI assistants to securely connect to external data sources and tools. It provides a standardized way to:
Connect to databases, APIs, and file systems
Access real-time data from external services
Execute custom tools and scripts
Maintain secure, controlled access to external resources
Adding an MCP Server as a Tool
MCP servers provide collections of tools that your agents can use.
To add one:
Navigate to
Settings → MCP Tools
Click
Add
to open the configuration modal
Enter a
Server Name
and
Server URL
Add any required
Headers
(e.g. API keys)
Click
Add MCP
to save
You can also configure MCP servers directly from the toolbar in an Agent block for quick setup.
Server Configuration Options
Field
Description
Name
Display name for the server
URL
The MCP server endpoint
Transport
Currently supports
streamable-http
Headers
Key-value pairs for authentication or custom headers
Timeout
Connection timeout in milliseconds (default: 30,000)
Environment Variables in Configuration
Server URLs and headers support environment variable substitution using
{{VAR_NAME}}
syntax. This keeps sensitive values like API keys out of the server configuration.
URL: https://api.example.com/mcp
Authorization: Bearer {{MCP_API_TOKEN}}
When you type
{{
in the URL or header fields, a dropdown appears showing available workspace environment variables.
Testing and Validation
Click
Test Connection
before saving to verify the server is reachable and discover available tools. The test response shows the number of tools found and the protocol version.
After saving, each server displays its available tools with parameter names, types, and required flags. If a server's tools change (e.g., after a server update), click
Refresh
to fetch the latest schemas. This automatically updates any agent blocks using those tools.
Tool validation badges appear on servers with issues — for example, if a tool was removed from the server but is still referenced in a workflow. Click the badge to see which workflows are affected.
Domain Allowlisting
Self-hosted deployments can restrict which MCP server domains are allowed by setting the
ALLOWED_MCP_DOMAINS
environment variable (comma-separated list). When set, only servers on approved domains can be added. When unset, all domains are allowed.
Refresh Tools
To auto-refresh an MCP tool already in use by an agent, go to
Settings → MCP Tools
, open the server's details, and click
Refresh
. This fetches the latest tool schemas and automatically updates any agent blocks using those tools with the new parameter definitions.
Using MCP Tools in Agents
Once MCP servers are configured, their tools become available within your agent blocks:
Open an
Agent
block
In the
Tools
section, click
Add tool…
Under
MCP Servers
, click a server to see its tools
Select individual tools, or choose
Use all N tools
to add every tool from that server
The agent can now access these tools during execution
If you haven't configured a server yet, click
Add MCP Server
at the top of the dropdown to open the setup modal without leaving the block.
Standalone MCP Tool Block
For more granular control, you can use the dedicated MCP Tool block to execute specific MCP tools:
The MCP Tool block allows you to:
Execute any configured MCP tool directly
Pass specific parameters to the tool
Use the tool's output in subsequent workflow steps
Chain multiple MCP tools together
When to Use MCP Tool vs Agent
Agent with MCP tools
MCP Tool block
Execution
AI decides which tools to call
Deterministic — runs the tool you pick
Parameters
AI chooses at runtime
You set them explicitly
Best for
Dynamic, conversational flows
Structured, repeatable steps
Reasoning
Handles complex multi-step logic
One tool, one call
Permission Requirements
MCP functionality requires specific workspace permissions:
Action
Required Permission
Create or update MCP servers
Write
or
Admin
Delete MCP servers
Admin
Use MCP tools in agents
Write
or
Admin
View available MCP tools
Read
,
Write
, or
Admin
Execute MCP Tool blocks
Read
,
Write
, or
Admin
Common Use Cases
Database Integration
Connect to databases to query, insert, or update data within your workflows.
API Integrations
Access external APIs and web services that don't have built-in Sim integrations.
File System Access
Read, write, and manipulate files on local or remote file systems.
Custom Business Logic
Execute custom scripts or tools specific to your organization's needs.
Real-time Data Access
Fetch live data from external systems during workflow execution.
Security Considerations
MCP servers run with the permissions of the user who configured them
Always verify MCP server sources before installation
Use environment variables for sensitive configuration data
Review MCP server capabilities before granting access to agents
Troubleshooting
MCP Server Not Appearing
Verify the server configuration is correct
Check that you have the required permissions
Ensure the MCP server is running and accessible
Tool Execution Failures
Verify tool parameters are correctly formatted
Check MCP server logs for error messages
Ensure required authentication is configured
Permission Errors
Confirm your workspace permission level
Check if the MCP server requires additional authentication
Verify the server is properly configured for your workspace
Common Questions
What is the difference between using MCP tools in an Agent block vs. the standalone MCP Tool block?
When you add MCP tools to an Agent block, the AI decides which tools to use based on the conversation context and its reasoning. This is best for dynamic, conversational workflows. The standalone MCP Tool block executes a specific tool with explicit parameters every time, giving you deterministic, predictable execution. Use Agent blocks for flexible reasoning and MCP Tool blocks for structured, repeatable steps.
Who can configure MCP servers in a workspace?
Users with Write permission can configure (add and update) MCP servers in workspace settings. Only Admin permission is required to delete MCP servers. Users with Read permission can view available MCP tools and execute them in agents and MCP Tool blocks. This means all workspace members with at least Read access can use MCP tools in their workflows.
Can I use MCP servers from multiple workspaces?
MCP servers are configured per workspace. Each workspace maintains its own set of MCP server connections. If you need the same MCP server in multiple workspaces, you need to configure it separately in each workspace's settings.
How do I update MCP tool schemas after a server changes its available tools?
Click the Refresh button on the MCP server in your workspace settings. This fetches the latest tool schemas from the server and automatically updates any agent blocks that use those tools with the new parameter definitions.
Can permission groups restrict access to MCP tools?
Yes. Organization admins can create permission groups that disable MCP tools for specific members using the disableMcpTools configuration option. When this is enabled, affected users will not be able to add or use MCP tools in their workflows.
What happens if an MCP server goes offline during workflow execution?
If the MCP server is unreachable during execution, the tool call will fail and return an error. In an Agent block, the AI may attempt to handle the failure gracefully. In a standalone MCP Tool block, the workflow step will fail. Check MCP server logs and verify the server is running and accessible to troubleshoot connectivity issues.
Previous
Knowledge Bases
Next
Deploy Workflows as MCP
On this page
What is MCP?
Adding an MCP Server as a Tool
Server Configuration Options
Environment Variables in Configuration
Testing and Validation
Domain Allowlisting
Refresh Tools
Using MCP Tools in Agents
Standalone MCP Tool Block
When to Use MCP Tool vs Agent
Permission Requirements
Common Use Cases
Database Integration
API Integrations
File System Access
Custom Business Logic
Real-time Data Access
Security Considerations
Troubleshooting
MCP Server Not Appearing
Tool Execution Failures
Permission Errors

---

## Self-Hosting | Sim Docs

**URL:** https://docs.sim.ai/self-hosting

Self-Hosting | Sim Docs
Copy page
Self-Hosting
Deploy Sim on your own infrastructure
Deploy Sim on your own infrastructure with Docker or Kubernetes.
Requirements
Resource
Small
Standard
Production
CPU
2 cores
4 cores
8+ cores
RAM
12 GB
16 GB
32+ GB
Storage
20 GB SSD
50 GB SSD
100+ GB SSD
Docker
20.10+
20.10+
Latest
Small
: Development, testing, single user (1-5 users)
Standard
: Teams (5-50 users), moderate workloads
Production
: Large teams (50+ users), high availability, heavy workflow execution
Resource requirements are driven by workflow execution (isolated-vm sandboxing), file processing (in-memory document parsing), and vector operations (pgvector). Memory is typically the constraining factor rather than CPU. Production telemetry shows the main app uses 4-8 GB average with peaks up to 12 GB under heavy load.
Quick Start
git
clone
https://github.com/simstudioai/sim.git
&&
cd
sim
docker
compose
-f
docker-compose.prod.yml
up
-d
Open
http://localhost:3000
Deployment Options
Docker
Deploy with Docker Compose on any server
Kubernetes
Deploy with Helm on Kubernetes clusters
Cloud Platforms
Railway, DigitalOcean, AWS, Azure, GCP guides
Architecture
Component
Port
Description
simstudio
3000
Main application
realtime
3002
WebSocket server
db
5432
PostgreSQL with pgvector
migrations
-
Database migrations (runs once)
Common Questions
What are the minimum requirements to self-host Sim?
At minimum you need 2 CPU cores, 12 GB RAM, 20 GB SSD storage, and Docker 20.10 or later. Memory is typically the constraining factor due to workflow execution (isolated-vm sandboxing), file processing, and vector operations (pgvector).
Which database does Sim use?
Sim uses PostgreSQL 17 with the pgvector extension for vector similarity search. The Docker setup uses the pgvector/pgvector:pg17 image, which comes with the vector extension pre-installed.
What are the required environment variables for production?
Three secrets are required: BETTER_AUTH_SECRET (authentication), ENCRYPTION_KEY (data encryption), and INTERNAL_API_SECRET (service-to-service auth). Generate each with openssl rand -hex 32. You also need to set NEXT_PUBLIC_APP_URL and BETTER_AUTH_URL to your domain.
What does the realtime service do?
The realtime service is a dedicated WebSocket server that runs on port 3002. It handles real-time communication for features like live workflow execution updates. It has a 1 GB memory limit and requires its own DATABASE_URL and BETTER_AUTH_SECRET configuration.
How does the migrations service work?
The migrations container runs once at startup (restart: no) and executes bun run db:migrate to apply database schema changes. It depends on the database being healthy before running and must complete successfully before the main application starts.
Can I use Sim with local AI models?
Yes. Sim supports Ollama for local model inference. Use docker-compose.ollama.yml instead of docker-compose.prod.yml. It offers both GPU (with NVIDIA support) and CPU-only profiles, and automatically pulls gemma3:4b as a starter model.
Previous
Roles and Permissions
Next
Docker
On this page
Requirements
Quick Start
Deployment Options
Architecture

---

## https://docs.sim.ai/api-reference

**URL:** https://docs.sim.ai/api-reference

> **Error:** Client error '404 Not Found' for url 'https://docs.sim.ai/api-reference'
For more information check: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404


---

## Sim Blog

**URL:** https://sim.ai/blog/rss.xml

Sim Blog
https://www.sim.ai
Announcements, insights, and guides for AI agent workflows.
en-us
Tue, 17 Mar 2026 00:00:00 GMT
Introducing Mothership
https://www.sim.ai/blog/mothership
https://www.sim.ai/blog/mothership
Tue, 17 Mar 2026 00:00:00 GMT
Sim v0.6 introduces Mothership—a central intelligence layer for orchestrating your AI agents—alongside Tables, Files, Knowledge Base Connectors, and Scheduled Tasks.
Emir Karabeg (https://x.com/emkara)
Release
Mothership
Tables
Knowledge Base
Connectors
RAG
Sim
Sim for Enterprise
https://www.sim.ai/blog/enterprise
https://www.sim.ai/blog/enterprise
Wed, 11 Feb 2026 00:00:00 GMT
Access control, BYOK, self-hosted deployments, on-prem Copilot, SSO & SAML, whitelabeling, Admin API, and flexible data retention—enterprise features for teams with strict security and compliance requirements.
Vikhyath Mondreti (https://github.com/icecrasher321)
Enterprise
Security
Self-Hosted
SSO
SAML
Compliance
BYOK
Access Control
Copilot
Whitelabel
API
Import
Export
Introducing Sim v0.5
https://www.sim.ai/blog/v0-5
https://www.sim.ai/blog/v0-5
Thu, 22 Jan 2026 00:00:00 GMT
This new release brings a state of the art Copilot, seamless MCP server and tool deployment, 100+ integrations with 300+ tools, comprehensive execution logs, and realtime collaboration—built for teams shipping AI agents in production.
Waleed Latif (https://x.com/typingwala)
Release
Copilot
MCP
Observability
Collaboration
Integrations
Sim
$7M Series A
https://www.sim.ai/blog/series-a
https://www.sim.ai/blog/series-a
Wed, 12 Nov 2025 00:00:00 GMT
We’re excited to share that Sim has raised a $7M Series A led by Standard Capital to accelerate our vision for agentic workflows.
Waleed Latif (https://x.com/typingwala)
Emir Karabeg (https://x.com/emkara)
Announcement
Funding
Series A
Sim
YCombinator
Realtime Collaboration
https://www.sim.ai/blog/multiplayer
https://www.sim.ai/blog/multiplayer
Tue, 11 Nov 2025 00:00:00 GMT
A high-level explanation into Sim realtime collaborative workflow builder - from operation queues to conflict resolution.
Vikhyath Mondreti (https://github.com/icecrasher321)
Multiplayer
Realtime
Collaboration
WebSockets
Architecture
Inside the Sim Executor - DAG Based Execution with Native Parallelism
https://www.sim.ai/blog/executor
https://www.sim.ai/blog/executor
Mon, 10 Nov 2025 00:00:00 GMT
How we built a DAG-based execution engine with native parallel processing, intelligent edge routing, and stateful pause/resume capabilities
Siddharth (https://x.com/sidganesan)
Executor
Architecture
DAG
Orchestration
OpenAI AgentKit vs n8n vs Sim: AI Agent Workflow Builder Comparison
https://www.sim.ai/blog/openai-vs-n8n-vs-sim
https://www.sim.ai/blog/openai-vs-n8n-vs-sim
Mon, 06 Oct 2025 00:00:00 GMT
OpenAI just released AgentKit for building AI agents. How does it compare to workflow automation platforms like n8n and purpose-built AI agent builders like Sim?
Emir Karabeg (https://x.com/emkara)
AI Agents
Workflow Automation
OpenAI AgentKit
n8n
Sim
MCP

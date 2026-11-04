# LLM Apps (Awesome KB)

An [OpenShelf](https://github.com/OpenNorms/openshelf) 1.7 knowledge base from
[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps).

**[Browse the KB](index.md)** — 122 unique resources at `depth: stub`,
covering 122 curated list occurrences. Repeated URLs share an entity,
retain all source occurrences in frontmatter, and appear in every source category.

Run `python3 tools/ingest.py --date 2026-11-04` to reproduce the import from
the immutable captured README. Use `--source` for a newer upstream checkout.
Run `python3 tools/check.py` and `openshelf lint .` to validate.

The list is canon. Resource status remains unknown until checked; source descriptions
are attributed claims, not independently verified assessments. Linked projects and
lists are not recursively imported.

<!-- BEGIN GENERATED AWESOME LIST -->

## Resource list

Generated from the OpenShelf index. Entry names open KB pages; **upstream** opens the original resource.

### Contents

- [Agent Skills](#list-category-1)
- [Standalone Apps & Tools](#list-category-2)
- [Starter AI Agents](#list-category-3)
- [Advanced AI Agents](#list-category-4)
- [Always-on Agents](#list-category-5)
- [Multi-agent Teams](#list-category-6)
- [Voice AI Agents](#list-category-7)
- [Generative UI and Agentic Frontends](#list-category-8)
- [Autonomous Game-Playing Agents](#list-category-9)
- [MCP AI Agents](#list-category-10)
- [RAG (Retrieval Augmented Generation)](#list-category-11)
- [LLM Apps with Memory](#list-category-12)
- [Chat with X](#list-category-13)
- [LLM Optimization Tools](#list-category-14)
- [LLM Fine-tuning](#list-category-15)
- [AI Agent Framework Crash Courses](#list-category-16)

<a id="list-category-1"></a>

### Agent Skills

- [Project Graveyard](wiki/project-graveyard.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/project-graveyard/>) — Finds every side project you abandoned, tells you why each one died, and helps you finish the one worth going back to
- [First Reader](wiki/first-reader.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/first-reader/>) — Simulates real readers going through your draft and reports where they lose interest, where they stop reading, and what they remember afterward, without rewriting a word
- [Scope Creep Detector](wiki/scope-creep-detector.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/scope-creep-detector/>) — Checks whether a diff grew beyond its stated intent and recommends what to keep, split, or justify
- [Commit Archaeologist](wiki/commit-archaeologist.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/commit-archaeologist/>) — Reconstructs why a file or code region exists from its introducing commit, later edits, co-changes, and intent clues
- [Dependency Doctor](wiki/dependency-doctor.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/dependency-doctor/>) — Checks a dependency manifest for standard-library pins, obsolete backports, unpinned entries, duplicate constraints, and yanked releases
- [Advisor Orchestrator Worker](wiki/advisor-orchestrator-worker.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/advisor-orchestrator-worker/>) — Meta Loop with Claude Fable 5.1 as advisor, GPT-6 Astra as orchestrator, and Gemini 3.8 Flash as worker
- [Thinking Out Loud](wiki/thinking-out-loud.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/thinking-out-loud/>) — Echoes a voice ramble back as a scannable brief, with the model's guesses quarantined and your reversals flagged
- [Self-Improving Agent Skills](wiki/self-improving-agent-skills.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/agent_skills/self-improving-agent-skills/>) — Automatically optimize agent skills using Gemini and ADK

<a id="list-category-2"></a>

### Standalone Apps & Tools

- [Excaliflow - Hand-Drawn Diagrams with Live Animated Flows](wiki/excaliflow-hand-drawn-diagrams-with-live-animated-flows.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/excaliflow/>) — Sketch system architectures and AI agent workflows on an Excalidraw-style canvas with live animated arrows and video export
- [Needle - A New Way to Find](wiki/needle-a-new-way-to-find.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/needle/>) — Search webpages by meaning and highlight the strongest source sentence, using a Chrome extension powered by TypeSafe Jev
- [Ripple - Change One Thing, Find What Else Needs to Change](wiki/ripple-change-one-thing-find-what-else-needs-to-change.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/ripple/>) — Find related inconsistencies and suggested fixes as you edit a Google Doc, using TypeSafe Jev and Gemini

<a id="list-category-3"></a>

### Starter AI Agents

- [AI Blog to Podcast Agent](wiki/ai-blog-to-podcast-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_blog_to_podcast_agent/>) — Turn any blog URL into a narrated podcast episode
- [AI Breakup Recovery Agent](wiki/ai-breakup-recovery-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_breakup_recovery_agent/>) — An agent team that talks you through the post-breakup spiral
- [AI Data Analysis Agent](wiki/ai-data-analysis-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_data_analysis_agent/>) — Ask questions of any CSV or Excel file in plain English
- [AI Medical Imaging Agent](wiki/ai-medical-imaging-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_medical_imaging_agent/>) — Diagnostic analysis of X-rays and scans with Gemini
- [AI Meme Generator Agent (Browser)](wiki/ai-meme-generator-agent-browser.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_meme_generator_agent_browseruse/>) — Makes memes by driving a real browser, not an image API
- [AI Music Generator Agent](wiki/ai-music-generator-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_music_generator_agent/>) — Prompt in, MP3 track out
- [AI Travel Agent (Local & Cloud)](wiki/ai-travel-agent-local-cloud.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_travel_agent/>) — Personalized day-by-day travel itineraries
- [AI x402 Paying Agent](wiki/ai-x402-paying-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/ai_x402_paying_agent/>) — An agent with a wallet that pays per-call for the data it needs — no API keys
- [Gemini Multimodal Agent](wiki/gemini-multimodal-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/multimodal_ai_agent/>) — Video analysis plus web search in one agent
- [Mixture of Agents](wiki/mixture-of-agents.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/mixture_of_agents/>) — Multiple LLMs answer, one aggregates the best response
- [xAI Finance Agent](wiki/xai-finance-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/xai_finance_agent/>) — Real-time stock analysis powered by Grok
- [OpenAI Research Agent](wiki/openai-research-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/openai_research_agent/>) — Multi-agent topic research with the OpenAI Agents SDK
- [Web Scraping AI Agent](wiki/web-scraping-ai-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/starter_ai_agents/web_scraping_ai_agent/>) — Describe what to extract and the agent scrapes it

<a id="list-category-4"></a>

### Advanced AI Agents

- [AI Home Renovation Agent with Nano Banana Pro](wiki/ai-home-renovation-agent-with-nano-banana-pro.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_home_renovation_agent>) — Photos of your space in, renovation plan and photorealistic renders out
- [DevPulse AI - Multi-Agent Signal Intelligence](wiki/devpulse-ai-multi-agent-signal-intelligence.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/devpulse_ai/>) — Aggregates and scores technical signals into a daily intelligence digest
- [AI Deep Research Agent](wiki/ai-deep-research-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_deep_research_agent/>) — Comprehensive web research with the OpenAI Agents SDK and Firecrawl
- [AI VC Due Diligence Agent Team](wiki/ai-vc-due-diligence-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_vc_due_diligence_agent_team>) — Multi-agent startup investment analysis with Gemini 3
- [AI Research Planner & Executor (Google Interactions API)](wiki/ai-research-planner-executor-google-interactions-api.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/research_agent_gemini_interaction_api>) — Multi-phase research with stateful conversations and auto-generated infographics
- [AI Consultant Agent](wiki/ai-consultant-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_consultant_agent>) — Market analysis and strategy recommendations with live web research
- [AI System Architect Agent](wiki/ai-system-architect-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_system_architect_r1/>) — Architecture reviews using DeepSeek R1 reasoning plus Claude
- [AI Financial Coach Agent](wiki/ai-financial-coach-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_financial_coach_agent/>) — Personalized budget, debt, and savings analysis
- [AI Movie Production Agent](wiki/ai-movie-production-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_movie_production_agent/>) — Script drafts and casting ideas from a one-line movie concept
- [AI Investment Agent](wiki/ai-investment-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_investment_agent/>) — Stock comparison reports built on Yahoo Finance data
- [Earnings Call Analyst Agent](wiki/earnings-call-analyst-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/earnings_call_analyst_agent/>) — Turns YouTube earnings calls into a playback-synced analyst workspace
- [AI Health & Fitness Agent](wiki/ai-health-fitness-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_health_fitness_agent/>) — Tailored diet and workout plans from your goals
- [AI Product Launch Intelligence Agent](wiki/ai-product-launch-intelligence-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/product_launch_intelligence_agent>) — Go-to-market intelligence on competitor launches
- [AI Fraud Investigation Agent](wiki/ai-fraud-investigation-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_fraud_investigation_agent/>) — Cross-references public records to flag facilities that don't add up
- [AI Journalist Agent](wiki/ai-journalist-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_journalist_agent/>) — Researches, writes, and edits articles on any topic
- [AI Mental Wellbeing Agent](wiki/ai-mental-wellbeing-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_mental_wellbeing_agent/>) — A coordinated agent team for mental health support plans
- [AI Meeting Agent](wiki/ai-meeting-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_meeting_agent/>) — Context, industry insights, and strategy briefs before you walk in
- [AI Self-Evolving Agent](wiki/ai-self-evolving-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_self_evolving_agent/>) — Agents that rewrite their own workflows with EvoAgentX
- [AI Sales Intelligence Agent Team](wiki/ai-sales-intelligence-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_sales_intelligence_agent_team>) — Generates competitive sales battle cards in real time
- [AI Social Media News and Podcast Agent](wiki/ai-social-media-news-and-podcast-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_news_and_podcast_agents/>) — Curates your trusted sources into briefs and generated podcasts
- [Openwork - Open Browser Automation Agent](wiki/openwork-open-browser-automation-agent.md) · [upstream](<https://github.com/accomplish-ai/coworker>) — Open-source agent that operates a real browser
- [Trust-Gated Multi-Agent Research Team](wiki/trust-gated-multi-agent-research-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/trust_gated_agent_team/>) — Every agent verified, every action in a hash-chained audit trail

<a id="list-category-5"></a>

### Always-on Agents

- [Always-on Hacker News Briefing Agent](wiki/always-on-hacker-news-briefing-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/always_on_agents/always_on_hn_briefing_agent/>) — A scheduled scout that ships a ranked daily brief to Slack or email
- [Release Radar Agent](wiki/release-radar-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/always_on_agents/release_radar_agent/>) — Watches dependency releases and briefs you on breaking, deprecated, security, and major-version changes

<a id="list-category-6"></a>

### Multi-agent Teams

- [AI Competitor Intelligence Agent Team](wiki/ai-competitor-intelligence-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_competitor_intelligence_agent_team/>) — Structured competitor teardowns built from their own websites
- [AI Finance Agent Team](wiki/ai-finance-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_finance_agent_team/>) — A financial analyst team in 20 lines of Python
- [AI Game Design Agent Team](wiki/ai-game-design-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_game_design_agent_team/>) — Full game concepts from a swarm of design specialists
- [AG2 Adaptive Research Team](wiki/ag2-adaptive-research-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ag2_adaptive_research_team/>) — Agent teamwork with routing and fallback, built on AG2
- [AI Legal Agent Team (Cloud & Local)](wiki/ai-legal-agent-team-cloud-local.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_legal_agent_team/>) — Research, contract analysis, and strategy from a full legal bench
- [AI Recruitment Agent Team](wiki/ai-recruitment-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_recruitment_agent_team/>) — Resume screening to interview scheduling, end to end
- [AI Real Estate Agent Team](wiki/ai-real-estate-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_real_estate_agent_team>) — Property search, market analysis, and recommendations
- [AI Services Agency (CrewAI)](wiki/ai-services-agency-crewai.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_services_agency/>) — A digital agency that scopes and plans your software project
- [AI Teaching Agent Team](wiki/ai-teaching-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_teaching_agent_team/>) — A faculty of agents that builds your complete learning path
- [Multimodal Coding Agent Team](wiki/multimodal-coding-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/multimodal_coding_agent_team/>) — Snap a photo of a coding problem, get a sandboxed solution
- [Multimodal Design Agent Team](wiki/multimodal-design-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/multimodal_design_agent_team/>) — Design critiques from a Gemini-powered expert panel
- [Multimodal UI/UX Feedback Agent Team](wiki/multimodal-ui-ux-feedback-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/multimodal_uiux_feedback_agent_team/>) — Landing page feedback plus an auto-generated improved version
- [AI Travel Planner Agent Team](wiki/ai-travel-planner-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_travel_planner_agent_team/>) — A complete trip itinerary, crafted by a team
- [LLM Panel Agent Team](wiki/llm-panel-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/llm_panel_agent_team/>) — Three vendors review the same diff blind, then argue it out anonymously

<a id="list-category-7"></a>

### Voice AI Agents

- [AI Audio Tour Agent](wiki/ai-audio-tour-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/voice_ai_agents/ai_audio_tour_agent/>) — Self-guided audio tours from your location, interests, and pace
- [Customer Support Voice Agent](wiki/customer-support-voice-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/voice_ai_agents/customer_support_voice_agent/>) — Voice answers grounded in your own docs
- [Insurance Claim Live Agent Team](wiki/insurance-claim-live-agent-team.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/voice_ai_agents/insurance_claim_live_agent_team/>) — Voice claim intake on Gemini 3.8 Live that writes a field notebook, looks at damage through the webcam, and sketches the incident
- [Voice RAG Agent (OpenAI SDK)](wiki/voice-rag-agent-openai-sdk.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/voice_ai_agents/voice_rag_openaisdk/>) — Ask your PDFs questions, hear the answers
- [OpenSource Voice Dictation Agent (Wispr Flow clone)](wiki/opensource-voice-dictation-agent-wispr-flow-clone.md) · [upstream](<https://github.com/akshayaggarwal99/jarvis-ai-assistant>) — Open-source dictation that types where you talk

<a id="list-category-8"></a>

### Generative UI and Agentic Frontends

- [Generative UI Starter Project](wiki/generative-ui-starter-project.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/generative-ui-starter-project/>) — A chat-driven kanban board you and the agent work together
- [AI Financial Coach Agent](wiki/ai-financial-coach-agent-2.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/ai-financial-coach-agent/>) — Budget, savings, and debt plans rendered as interactive cards
- [AI Dashboard Canvas Agent](wiki/ai-dashboard-canvas-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/ai-dashboard-canvas-agent/>) — Describe a dashboard in chat, charts assemble on a live canvas
- [AI MCP App Builder](wiki/ai-mcp-app-builder.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/ai-mcp-app-builder/>) — Describe an MCP app, get a live sandboxed instance back
- [MCP Apps Generative UI Showcase](wiki/mcp-apps-generative-ui-showcase.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/mcp-apps-generative-ui-showcase/>) — MCP apps that render real interactive UI, flight search included
- [AI Shadcn Component Generator](wiki/ai-shadcn-component-generator.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/ai-shadcn-component-generator/>) — Chat your way to production-ready shadcn components
- [AI Deep Research Agent](wiki/ai-deep-research-agent-2.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/generative_ui_agents/ai-deep-research-agent/>) — Research where every tool call renders as a live workspace card

<a id="list-category-9"></a>

### Autonomous Game-Playing Agents

- [AI 3D Pygame Agent](wiki/ai-3d-pygame-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/autonomous_game_playing_agent_apps/ai_3dpygame_r1/>) — DeepSeek R1 writes PyGame code, browser agents run it live
- [AI Chess Agent](wiki/ai-chess-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/autonomous_game_playing_agent_apps/ai_chess_agent/>) — Agent White vs Agent Black with validated moves
- [AI Tic-Tac-Toe Agent](wiki/ai-tic-tac-toe-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/autonomous_game_playing_agent_apps/ai_tic_tac_toe_agent/>) — Two different LLMs battle it out, move by move

<a id="list-category-10"></a>

### MCP AI Agents

- [Browser MCP Agent](wiki/browser-mcp-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/mcp_ai_agents/browser_mcp_agent/>) — Drive a real browser with natural language over MCP
- [GitHub MCP Agent](wiki/github-mcp-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/mcp_ai_agents/github_mcp_agent/>) — Explore and analyze any repo in plain English
- [Notion MCP Agent](wiki/notion-mcp-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/mcp_ai_agents/notion_mcp_agent>) — Talk to your Notion pages from the terminal
- [AI Travel Planner MCP Agent](wiki/ai-travel-planner-mcp-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/mcp_ai_agents/ai_travel_planner_mcp_agent_team>) — Itineraries built on live Airbnb and Google Maps data
- [Multi-MCP Agent Router](wiki/multi-mcp-agent-router.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/mcp_ai_agents/multi_mcp_agent_router/>) — Specialist agents, each wired to its own MCP server
- [OpenAI Remote MCP Tool Bridge](wiki/openai-remote-mcp-tool-bridge.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/mcp_ai_agents/openai_remote_mcp_bridge/>) — Connect OpenAI function calling directly to a remote MCP server

<a id="list-category-11"></a>

### RAG (Retrieval Augmented Generation)

- [Agentic RAG with Embedding Gemma](wiki/agentic-rag-with-embedding-gemma.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/agentic_rag_embedding_gemma>) — Fully local agentic RAG with EmbeddingGemma and Llama 3.2
- [Agentic RAG with Reasoning](wiki/agentic-rag-with-reasoning.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/agentic_rag_with_reasoning/>) — Watch the agent's step-by-step reasoning as it retrieves
- [AI Blog Search (RAG)](wiki/ai-blog-search-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/ai_blog_search/>) — Agentic search over blog content, built on LangGraph
- [Autonomous RAG](wiki/autonomous-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/autonomous_rag/>) — GPT-4o answers from your PDFs, falls back to web search
- [Contextual AI RAG Agent](wiki/contextual-ai-rag-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/contextualai_rag_agent/>) — Managed RAG: datastore to grounded chat in minutes
- [Corrective RAG (CRAG)](wiki/corrective-rag-crag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/corrective_rag/>) — Retrieval that grades itself and retries before answering
- [Typed Agentic RAG with Pydantic AI](wiki/typed-agentic-rag-with-pydantic-ai.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/agentic_typed_rag_pydanticai/>) — Validated answers with exact citations, or a refusal when evidence is weak
- [Deepseek Local RAG Agent](wiki/deepseek-local-rag-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/deepseek_local_rag_agent/>) — Local DeepSeek reasoning over your own documents
- [Gemini Agentic RAG](wiki/gemini-agentic-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/gemini_agentic_rag/>) — Query rewriting and web fallback with Gemini Flash Thinking
- [Hybrid Search RAG (Cloud)](wiki/hybrid-search-rag-cloud.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/hybrid_search_rag/>) — Keyword plus vector search feeding Claude
- [Llama 3.1 Local RAG](wiki/llama-3-1-local-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/llama3.1_local_rag/>) — Chat with any webpage, fully offline
- [Local Hybrid Search RAG](wiki/local-hybrid-search-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/local_hybrid_search_rag/>) — Hybrid search with everything running on your machine
- [Multimodal Agentic RAG](wiki/multimodal-agentic-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/multimodal_agentic_rag/>) — Text, PDFs, images, audio, and video, answered with citations
- [Local RAG Agent](wiki/local-rag-agent.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/local_rag_agent/>) — Llama 3.2 and Qdrant, no API keys required
- [RAG-as-a-Service](wiki/rag-as-a-service.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/rag-as-a-service/>) — A production RAG service in under 50 lines
- [RAG Agent with Cohere](wiki/rag-agent-with-cohere.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/rag_agent_cohere/>) — Command R7B retrieval with web-search fallback
- [Basic RAG Chain](wiki/basic-rag-chain.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/rag_chain/>) — The minimal retrieval pipeline, applied to pharma research
- [RAG with Database Routing](wiki/rag-with-database-routing.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/rag_database_routing/>) — Routes each question to the right database automatically
- [Vision RAG](wiki/vision-rag.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/vision_rag/>) — Ask questions about images and PDF pages with Embed-4
- [RAG Failure Diagnostics Clinic](wiki/rag-failure-diagnostics-clinic.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/rag_failure_diagnostics_clinic/>) — Find out why your RAG pipeline is wrong, systematically
- [Knowledge Graph RAG with Citations](wiki/knowledge-graph-rag-with-citations.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/rag_tutorials/knowledge_graph_rag_citations/>) — Multi-hop answers with verifiable source attribution

<a id="list-category-12"></a>

### LLM Apps with Memory

- [AI ArXiv Agent with Memory](wiki/ai-arxiv-agent-with-memory.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_apps_with_memory_tutorials/ai_arxiv_agent_memory/>) — Paper search that remembers your research interests
- [AI Travel Agent with Memory](wiki/ai-travel-agent-with-memory.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_apps_with_memory_tutorials/ai_travel_agent_memory/>) — A travel assistant that remembers your preferences
- [Llama3 Stateful Chat](wiki/llama3-stateful-chat.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_apps_with_memory_tutorials/llama3_stateful_chat/>) — Session-persistent chat with Llama 3
- [LLM App with Personalized Memory](wiki/llm-app-with-personalized-memory.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_apps_with_memory_tutorials/llm_app_personalized_memory/>) — A chatbot that keeps context across conversations
- [Local ChatGPT Clone with Memory](wiki/local-chatgpt-clone-with-memory.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_apps_with_memory_tutorials/local_chatgpt_with_memory/>) — Fully local, with a personal memory per user
- [Multi-LLM Application with Shared Memory](wiki/multi-llm-application-with-shared-memory.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_apps_with_memory_tutorials/multi_llm_memory/>) — Different models, one shared conversation memory

<a id="list-category-13"></a>

### Chat with X

- [Chat with GitHub (GPT & Llama3)](wiki/chat-with-github-gpt-llama3.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/chat_with_X_tutorials/chat_with_github/>) — Any repo, answered in 30 lines of RAG
- [Chat with Gmail](wiki/chat-with-gmail.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/chat_with_X_tutorials/chat_with_gmail/>) — Ask your inbox questions
- [Chat with PDF (GPT & Llama3)](wiki/chat-with-pdf-gpt-llama3.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/chat_with_X_tutorials/chat_with_pdf/>) — The classic, in 30 lines of Python
- [Chat with Research Papers (ArXiv) (GPT & Llama3)](wiki/chat-with-research-papers-arxiv-gpt-llama3.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/chat_with_X_tutorials/chat_with_research_papers/>) — Explore arXiv conversationally with GPT-4o
- [Chat with Substack](wiki/chat-with-substack.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/chat_with_X_tutorials/chat_with_substack/>) — Chat with any newsletter's archive
- [Chat with YouTube Videos](wiki/chat-with-youtube-videos.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/chat_with_X_tutorials/chat_with_youtube_videos/>) — Ask videos questions via their transcripts

<a id="list-category-14"></a>

### LLM Optimization Tools

- [Toonify Token Optimization](wiki/toonify-token-optimization.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_optimization_tools/toonify_token_optimization/>) — Reduce LLM API costs by 30-60% using TOON format
- [Headroom Context Optimization](wiki/headroom-context-optimization.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_optimization_tools/headroom_context_optimization/>) — Reduce LLM API costs by 50-90%

<a id="list-category-15"></a>

### LLM Fine-tuning

- [Gemma 3 Fine-tuning](wiki/gemma-3-fine-tuning.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_finetuning_tutorials/gemma3_finetuning/>) — 4-bit LoRA with Unsloth, small and readable
- [Llama 3.2 Fine-tuning](wiki/llama-3-2-fine-tuning.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_llm_apps/llm_finetuning_tutorials/llama3.2_finetuning/>) — Fine-tune in 30 lines, free on Colab

<a id="list-category-16"></a>

### AI Agent Framework Crash Courses

- [Google ADK Crash Course](wiki/google-adk-crash-course.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/>) — Starter agent, structured outputs, tools (built-in, function, third-party, MCP), memory, callbacks, plugins, and multi-agent patterns. Model-agnostic.
- [OpenAI Agents SDK Crash Course](wiki/openai-agents-sdk-crash-course.md) · [upstream](<https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/openai_sdk_crash_course/>) — Starter agent, function calling, structured outputs, tools, memory, evaluation, handoffs, swarm orchestration, and routing logic.

<!-- END GENERATED AWESOME LIST -->

## License

Apache-2.0; the complete upstream [license](LICENSE) and
[reuse notices](THIRD_PARTY_NOTICES.md) are retained. Linked projects retain
their own licenses.

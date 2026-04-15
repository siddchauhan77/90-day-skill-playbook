# Prompt Engineering / AI Integration — 90-Day Plan

> From zero to your first AI product or client. Daily tasks + content ideas to document the build publicly.

---

## Phase 1 — Foundation (Days 1–30)

### Week 1–2: LLM Fundamentals + Prompt Basics

---

### Day 1 — What Is a Language Model
**Task:** Read Andrej Karpathy's "Intro to Large Language Models" video summary or blog post. Write a one-page explanation of how LLMs work in your own words — tokens, context windows, temperature, and why they hallucinate.

**Posts:**
1. Hook: "I'm spending 90 days learning AI/prompt engineering. Here's what I understood about LLMs on Day 1 that most people never figure out." — angle: explain tokens and context windows in plain English
2. Hook: "Why does ChatGPT make stuff up? I finally understand it." — angle: break down hallucination in simple terms

---

### Day 2 — Zero-Shot vs. Few-Shot Prompting
**Task:** Open Claude.ai or ChatGPT. Run 10 experiments comparing zero-shot prompts vs. few-shot prompts on the same task (e.g., classifying customer feedback, writing product descriptions). Document which performed better and why.

**Posts:**
1. Hook: "Zero-shot vs. few-shot prompting. I ran 10 experiments. Here's what actually changes the output." — angle: show a side-by-side comparison with real examples
2. Hook: "The simplest way to get better AI outputs immediately: show it what you want first." — angle: explain few-shot with a concrete before/after

---

### Day 3 — Prompt Structure
**Task:** Learn the anatomy of a well-structured prompt: role, context, task, format, constraints. Rewrite 5 bad prompts using this framework and document the difference in output quality.

**Posts:**
1. Hook: "Most people prompt AI like this: 'write me a blog post.' Here's why that gets garbage output." — angle: show the 5-part prompt structure with examples
2. Hook: "I rewrote 5 prompts using one simple framework. The difference was insane." — angle: before/after comparison

---

### Day 4 — Temperature and Parameters
**Task:** Experiment with temperature settings (0, 0.5, 1.0, 1.5) on the Claude or OpenAI playground for creative vs. factual tasks. Document when low temperature wins vs. high temperature wins.

**Posts:**
1. Hook: "There's a dial inside AI that controls how 'creative' vs. 'accurate' it is. Most people never touch it." — angle: explain temperature with practical use cases
2. Hook: "I ran the same prompt at 5 different temperature settings. Here's what happened." — angle: document the outputs visually

---

### Day 5 — Instruction Clarity
**Task:** Take one vague task (e.g., "help me with my email") and rewrite it 10 ways with increasing specificity. Measure output quality improvement. Learn the principle: the more specific your input, the more specific the output.

**Posts:**
1. Hook: "AI isn't dumb. Your prompts are vague. Here's what I learned in Day 5." — angle: 10 increasingly specific versions of the same prompt
2. Hook: "The reason AI gives you mediocre outputs isn't the model. It's this." — angle: specificity principle in prompting

---

### Day 6 — Output Formatting
**Task:** Practice controlling output format — JSON, markdown, bullet lists, tables, numbered steps. Build 5 prompts that each produce a different structured output format you could actually use in an app.

**Posts:**
1. Hook: "You can tell AI to output JSON, tables, markdown, or plain text. Here's why that matters for building real tools." — angle: format control for developers and builders
2. Hook: "I built 5 mini AI tools today using nothing but format instructions in the prompt." — angle: show how format = functionality

---

### Day 7 — Week 1 Review
**Task:** Review your 6 days of experiments. Pick your 3 best prompts and 3 worst prompts. Write a personal "prompt quality checklist" — the 5 things you check before sending a prompt.

**Posts:**
1. Hook: "7 days of prompt engineering experiments. Here's my personal quality checklist." — angle: share the checklist as a practical resource
2. Hook: "I wrote 50+ prompts this week. These 3 were terrible. Here's what I learned from each one." — angle: failures as lessons

---

### Day 8 — Role Prompting
**Task:** Experiment with assigning AI a specific role/persona in the system prompt vs. user prompt. Test 5 different roles (expert copywriter, skeptical editor, Socratic tutor, data analyst, startup advisor) on the same base task. Document how role changes the output tone and approach.

**Posts:**
1. Hook: "Tell AI who to BE before you tell it what to DO. That one change rewired how I prompt." — angle: role prompting explained with examples
2. Hook: "I asked the same question to 5 different AI 'personas.' The outputs were completely different." — angle: side-by-side role comparison

---

### Day 9 — Negative Constraints
**Task:** Practice using negative constraints in prompts ("don't include X," "avoid Y," "never Z"). Test 10 prompts with and without negatives. Learn when negatives help and when they backfire (AI sometimes focuses on what not to do and then does it).

**Posts:**
1. Hook: "Telling AI what NOT to do is trickier than it sounds. Here's why." — angle: negative constraints and how they behave
2. Hook: "I spent a day on negative prompting. The results were weird." — angle: document surprising cases where negatives failed

---

### Day 10 — Chain-of-Thought Introduction
**Task:** Learn chain-of-thought (CoT) prompting. Add "Let's think step by step" or "Reason through this carefully before answering" to 10 prompts that involve reasoning or math. Document the improvement in accuracy.

**Posts:**
1. Hook: "'Let's think step by step' is the simplest prompt upgrade that almost nobody uses." — angle: chain-of-thought explained with before/after
2. Hook: "I added 5 words to my prompts and the reasoning quality jumped. Here's the exact phrase." — angle: CoT intro with examples

---

### Day 11 — System Prompts
**Task:** Learn the difference between system prompts and user prompts. Write 5 different system prompts that give an AI assistant a specific personality, expertise, and set of rules. Test each in Claude.ai or the API playground.

**Posts:**
1. Hook: "System prompts are the hidden layer of AI. They control everything and most people don't use them." — angle: what system prompts are and why they matter
2. Hook: "I wrote 5 system prompts today that turned Claude into 5 completely different assistants." — angle: show examples of the outputs

---

### Day 12 — Context Window Strategy
**Task:** Learn about context windows (how much text an AI can "see" at once). Experiment with long vs. short context inputs. Practice summarizing context to fit within limits without losing important information. Test Claude's 200k context vs. GPT-4o's 128k.

**Posts:**
1. Hook: "The context window is the most important thing you don't understand about AI. Here's what it actually means." — angle: plain-English context window explainer
2. Hook: "I tried to give Claude an entire book as context. Here's what happened." — angle: practical test of long context

---

### Day 13 — Iterative Prompting
**Task:** Practice "prompt iteration" — start with a rough prompt, evaluate the output, refine the prompt, repeat. Run 5 tasks through 3–5 rounds of iteration. Document how output quality evolves each round.

**Posts:**
1. Hook: "Prompting isn't a one-shot skill. It's a loop. Here's my iterative process." — angle: show the 3–5 round refinement cycle
2. Hook: "The difference between a good AI output and a great one is usually just one more iteration." — angle: practical iteration examples

---

### Day 14 — Week 2 Review + Foundation Recap
**Task:** Compile all the prompts you've written across 14 days into a personal "prompt library" file. Organize by category: role prompts, format prompts, CoT prompts, system prompts. This is your starting swipe file.

**Posts:**
1. Hook: "2 weeks of prompt engineering. Here's the library of prompts I've built so far." — angle: share the categorized prompt library
2. Hook: "I've been building an AI prompt swipe file. Here's how I organize it." — angle: system for saving and categorizing prompts

---

### Week 3–4: Chain-of-Thought, Few-Shot, System Prompts

---

### Day 15 — Advanced Few-Shot Patterns
**Task:** Build a few-shot prompt with 5 examples for a complex classification task (e.g., categorize customer support tickets by urgency and type). Test if 3 examples vs. 5 examples changes accuracy. Document the optimal number.

**Posts:**
1. Hook: "How many examples should you give AI before asking it to do a task? I tested 1, 3, and 5." — angle: few-shot optimal example count
2. Hook: "I built an AI ticket classifier today using only examples in the prompt. No code. No model training." — angle: few-shot classification demo

---

### Day 16 — Multi-Step Chain-of-Thought
**Task:** Build a prompt that breaks a complex problem into explicit reasoning steps. Task: prompt the AI to analyze a business and output: (1) key problems, (2) root causes, (3) potential solutions, (4) recommended action. Document how explicit step structure improves output.

**Posts:**
1. Hook: "The secret to getting AI to actually think: tell it what to think ABOUT in each step." — angle: structured CoT with explicit reasoning phases
2. Hook: "I used AI to do a full business analysis today. The prompt structure made the difference." — angle: show the multi-step analysis output

---

### Day 17 — Persona + Expertise Combination
**Task:** Combine role assignment with expertise specification. Write 5 prompts that assign both a role AND domain knowledge (e.g., "You are a senior SaaS copywriter with 10 years experience writing for B2B software companies"). Compare to generic role prompts.

**Posts:**
1. Hook: "Telling AI 'you are an expert' is weak. Here's the specific language that actually unlocks expertise." — angle: specific expertise specification in prompting
2. Hook: "Role + expertise specification changed my AI outputs. Here's the exact format I use." — angle: the formula with examples

---

### Day 18 — Output Validation in Prompts
**Task:** Learn to include output validation in prompts — instruct the AI to check its own work before responding. Add "Before finalizing your answer, check for: accuracy, completeness, and logical consistency" to 10 prompts. Document how self-validation changes outputs.

**Posts:**
1. Hook: "I added a self-check instruction to my prompts. AI started catching its own mistakes." — angle: output validation technique
2. Hook: "You can tell AI to review its own output before giving it to you. Most people don't do this." — angle: practical validation prompt patterns

---

### Day 19 — Decomposition Prompting
**Task:** Practice breaking complex tasks into sub-tasks in your prompt. Build a prompt that asks AI to: (1) list all sub-tasks needed, (2) complete each sub-task, (3) synthesize into final output. Apply to a real project you're working on.

**Posts:**
1. Hook: "The biggest prompting mistake I made early on: giving AI a complex task without breaking it down first." — angle: decomposition prompting explained
2. Hook: "I used AI to plan a 90-day learning project today using one decomposition prompt. Here's the template." — angle: show the decomposition prompt and output

---

### Day 20 — Prompt Chaining Intro
**Task:** Build your first prompt chain: a sequence of 3 prompts where the output of each becomes the input of the next. Example chain: (1) research topic → (2) outline article → (3) write introduction. Document the chain and output quality vs. a single complex prompt.

**Posts:**
1. Hook: "One prompt isn't always enough. Here's how to chain prompts for complex outputs." — angle: prompt chaining intro with a 3-step example
2. Hook: "I built a 3-step content creation pipeline today using only prompts. No code." — angle: show the chain and the final output

---

### Day 21 — System Prompt Architecture
**Task:** Design a complete system prompt from scratch for a real use case: an AI assistant for a freelance copywriter. Include: persona, expertise, rules, format preferences, what to avoid. Test it on 10 different user messages.

**Posts:**
1. Hook: "I spent an hour building a proper system prompt today. Here's everything it needs to include." — angle: anatomy of a production-quality system prompt
2. Hook: "A well-designed system prompt is like an employee handbook for your AI assistant." — angle: system prompt architecture walkthrough

---

### Day 22 — Tone and Voice Control
**Task:** Practice controlling tone through prompts. Write 10 versions of the same message in different tones: formal, casual, urgent, empathetic, direct, conversational. Document which tone instructions work and which are too vague to control.

**Posts:**
1. Hook: "Tone is the hardest thing to control in AI writing. Here's what actually works." — angle: specific tone control techniques
2. Hook: "I wrote the same message 10 ways using AI today. The tone instructions that actually worked surprised me." — angle: tone experiment results

---

### Day 23 — Meta-Prompting
**Task:** Practice meta-prompting: using AI to improve your own prompts. Write a system prompt that turns Claude into a "prompt optimizer." Give it 5 of your worst-performing prompts and let it rewrite them. Test the optimized versions.

**Posts:**
1. Hook: "I used AI to fix my AI prompts. The results were better than what I wrote myself." — angle: meta-prompting walkthrough
2. Hook: "There's a technique called meta-prompting where you let AI write better prompts than you can. Here's how." — angle: explain meta-prompting with examples

---

### Day 24 — Handling Refusals and Edge Cases
**Task:** Learn how to handle AI refusals and edge cases gracefully in prompts. Practice reframing requests that get refused by adding context, legitimate framing, and specific use cases. Also learn to add guardrails to your own prompts to prevent misuse.

**Posts:**
1. Hook: "AI said no to my prompt. Here's why it happened and how I fixed it without doing anything sketchy." — angle: legitimate reframing techniques
2. Hook: "Adding guardrails to your AI tool is just as important as making it work. Here's how." — angle: prompt-level safety design

---

### Day 25 — Structured Data Extraction
**Task:** Build prompts to extract structured data from unstructured text. Practice: extract name, company, role, and pain point from 10 sales call transcripts. Output as clean JSON. This is a core skill for building AI tools.

**Posts:**
1. Hook: "I spent today turning messy text into clean data using only prompts. No code, no regex." — angle: structured extraction with JSON output
2. Hook: "One of the most useful AI tricks I've learned: structured extraction. Here's the prompt template." — angle: extraction prompt formula

---

### Day 26 — Summarization Strategies
**Task:** Build 5 different summarization prompts: executive summary, bullet-point key insights, single-sentence TLDR, argument summary, and action items. Test each on the same 3 long documents. Learn when each works best.

**Posts:**
1. Hook: "Not all summaries are the same. I built 5 types of AI summarization prompts. Here's when to use each." — angle: summarization prompt library
2. Hook: "I summarized the same article 5 different ways using AI. The most useful one wasn't what I expected." — angle: show all 5 and explain their purpose

---

### Day 27 — Classification and Labeling
**Task:** Build a classification pipeline: prompt an AI to categorize 50 items (e.g., 50 product reviews by sentiment and topic). Compare AI classification accuracy to manual labeling. Document where AI makes errors and why.

**Posts:**
1. Hook: "I used AI to classify 50 product reviews in 10 minutes. Here's the accuracy and where it failed." — angle: classification accuracy test
2. Hook: "AI classification is one of the most practical skills in prompt engineering. Here's how to do it right." — angle: classification prompt technique

---

### Day 28 — Phase 1 Wrap-Up
**Task:** Build a personal "prompt engineering fundamentals" reference doc — your cheat sheet of everything learned in 28 days: key techniques, best prompt structures, common mistakes, and the 10 prompts you're most proud of.

**Posts:**
1. Hook: "28 days of prompt engineering. Here's everything I've learned compressed into one reference guide." — angle: share the full cheat sheet
2. Hook: "One month in. Here are the 5 biggest shifts in how I think about AI." — angle: mindset evolution over 28 days

---

## Phase 2 — Application (Days 29–70)

### Week 5–6: Claude/GPT API Integration

---

### Day 29 — API Fundamentals
**Task:** Set up your first Claude API call using Python. Install the Anthropic SDK (`pip install anthropic`). Write a script that sends a message and prints the response. Understand: API keys, requests, responses, and error handling.

**Posts:**
1. Hook: "Day 29: I made my first API call to Claude today. Here's the exact code and what I learned." — angle: beginner API tutorial with real code
2. Hook: "The gap between using Claude in a browser and using the API is smaller than I thought. Here's how I crossed it." — angle: API onboarding walkthrough

---

### Day 30 — System Prompts via API
**Task:** Rewrite your Day 21 system prompt as an API system parameter. Test 10 different user messages through the API with your system prompt active. Compare outputs with and without the system prompt.

**Posts:**
1. Hook: "System prompts hit different when you pass them through the API. Here's what changed." — angle: system prompt in API context vs. chat UI
2. Hook: "I'm building my first AI assistant via the API. Here's the system prompt I'm starting with." — angle: share the system prompt and early results

---

### Day 31 — Managing Conversation History
**Task:** Build a simple multi-turn conversation script that maintains message history. Understand how to pass the conversation array to the API. Test how conversation history affects later responses and where memory "breaks."

**Posts:**
1. Hook: "AI doesn't actually have memory. It just re-reads the conversation each time. Here's why that matters." — angle: how conversation history works technically
2. Hook: "I built a chatbot with conversation memory today. Here's the surprisingly simple code." — angle: show the message history array approach

---

### Day 32 — Streaming Responses
**Task:** Implement streaming API responses in Python. Build a script where Claude's output appears token by token (like ChatGPT's typing effect). Understand when streaming improves UX and when it doesn't.

**Posts:**
1. Hook: "The 'typing' effect in ChatGPT isn't fake. Here's how to build it yourself with the API." — angle: streaming implementation walkthrough
2. Hook: "I added streaming to my AI script today. Here's the UX difference it makes." — angle: streaming vs. full response comparison

---

### Day 33 — Error Handling and Rate Limits
**Task:** Build robust error handling into your API scripts: rate limit retries with exponential backoff, timeout handling, and graceful fallbacks. This is what separates hobby scripts from production code.

**Posts:**
1. Hook: "The API call that works 99% of the time will fail in production if you don't do this." — angle: error handling and retries explained
2. Hook: "Day 33: learned the hard way that production AI scripts need real error handling. Here's what I added." — angle: practical error handling walkthrough

---

### Day 34 — Token Counting and Cost Optimization
**Task:** Learn to count tokens before sending requests (Anthropic's count_tokens endpoint). Build a script that estimates cost before making expensive API calls. Practice compressing prompts to reduce token count without losing quality.

**Posts:**
1. Hook: "AI API costs can spiral if you're not watching tokens. Here's how I keep costs low." — angle: token counting and cost optimization
2. Hook: "I learned to count tokens today. Now I can estimate exactly what an AI workflow will cost before running it." — angle: cost estimation workflow

---

### Day 35 — Building a Simple CLI Tool
**Task:** Build a command-line AI tool in Python: a "smart summarizer" that takes any text file as input and outputs a clean summary. Use argparse for CLI arguments, the Anthropic API for processing, and save outputs to a file. Ship it as a working tool.

**Posts:**
1. Hook: "I built my first real AI tool today. A command-line summarizer. Here's how it works." — angle: show the tool with demo
2. Hook: "The gap between 'prompt engineer' and 'AI tool builder' is one Python script. Here's mine." — angle: from prompts to tools

---

### Day 36 — OpenAI API Comparison
**Task:** Replicate your Day 35 summarizer using the OpenAI API (GPT-4o). Compare: output quality, latency, cost per 1k tokens, and developer experience. Build a side-by-side comparison table.

**Posts:**
1. Hook: "Claude vs. GPT-4o for my use case. I ran a real comparison. Here are the numbers." — angle: honest Claude vs. OpenAI comparison
2. Hook: "I use both Claude and OpenAI in my projects now. Here's when I reach for each." — angle: model selection strategy

---

### Day 37 — Prompt Caching
**Task:** Learn about Claude's prompt caching feature (cache_control parameter). Build a script that caches a long system prompt to reduce latency and cost on repeated calls. Test: cached vs. uncached response time and cost.

**Posts:**
1. Hook: "Prompt caching is the most underused Claude API feature. It cut my costs by 90% on repeated calls." — angle: prompt caching explained with numbers
2. Hook: "I discovered Claude's cache_control parameter today. Here's what it does and when to use it." — angle: prompt caching tutorial

---

### Day 38 — Tool Use (Function Calling)
**Task:** Learn Claude's tool use feature. Build a simple tool: give Claude access to a "get_weather(location)" function (can be mocked). Test how Claude decides when to call the tool vs. answer directly. This is the foundation of AI agents.

**Posts:**
1. Hook: "Tool use is the feature that turns AI from a chatbot into an agent. Here's how it works." — angle: tool use/function calling explained
2. Hook: "I gave Claude access to a 'tool' today. Watching it decide when to use it vs. answer itself was fascinating." — angle: tool use demo

---

### Day 39 — Building a Multi-Tool Script
**Task:** Extend your Day 38 work. Give Claude access to 3 tools: search_web (mocked), get_current_date, and calculate_math. Build a prompt where Claude correctly decides which tool to call based on the question. Document the decision logic.

**Posts:**
1. Hook: "I gave AI 3 tools today and asked it one question. Here's how it decided which tool to use." — angle: multi-tool decision logic
2. Hook: "Building AI agents is easier than I thought. You just give it tools and it figures out the rest." — angle: tool use demystified

---

### Day 40 — RAG Fundamentals
**Task:** Learn Retrieval Augmented Generation (RAG). Understand the concept: split documents into chunks → embed → store in vector DB → retrieve relevant chunks → send to LLM. Read the core papers. Implement a simple "retrieval" step manually (no vector DB yet — just keyword matching).

**Posts:**
1. Hook: "RAG is the most important AI architecture pattern and most explanations make it too complicated. Here's the simple version." — angle: RAG explained in plain English
2. Hook: "I'm learning how AI can be given a 'memory' of any document. Here's how RAG actually works." — angle: RAG fundamentals walkthrough

---

### Day 41 — Simple RAG Implementation
**Task:** Build a basic RAG pipeline: load a PDF → split into paragraphs → store in a simple dictionary → on user query, find the most relevant paragraphs → pass to Claude with the retrieved context. This is a minimum viable RAG system without a vector database.

**Posts:**
1. Hook: "I built a RAG system today with no vector database and no embeddings. Here's the simple approach." — angle: minimal RAG implementation
2. Hook: "Day 41: I can now ask Claude questions about any PDF I give it. Here's the code." — angle: show the RAG system in action

---

### Day 42 — Week 6 Review
**Task:** Audit all the tools and scripts you've built in Days 29–41. Pick the 3 most useful. Refactor each for clarity and add comments explaining the key decisions. Create a personal GitHub repo for your AI tools.

**Posts:**
1. Hook: "2 weeks of API work. Here are the 3 tools I actually kept and why." — angle: curating your AI tool portfolio
2. Hook: "I pushed my first AI projects to GitHub today. Here's the repo." — angle: share the repo and invite people to fork it

---

### Week 7–8: Build 3 AI Tools

---

### Day 43 — Tool 1 Planning: Email Assistant
**Task:** Plan your first "real" AI tool: an email drafting assistant. Define: the user input, the AI task, the output format, and the edge cases. Write a product spec (one page max) before writing any code.

**Posts:**
1. Hook: "Before I write any code, I write a one-page spec. Here's the spec for my AI email assistant." — angle: spec-first AI product development
2. Hook: "Planning an AI tool is 80% of the work. Here's how I plan before I build." — angle: product spec template for AI tools

---

### Day 44 — Tool 1 Build: Email Assistant
**Task:** Build the email drafting assistant. Input: email context + tone + recipient type. Output: 3 email draft options in different styles. Add a system prompt that encodes email writing best practices. Test with 10 real email scenarios.

**Posts:**
1. Hook: "I built an AI email writer today. Here's the system prompt that makes it actually good." — angle: show the system prompt and 3 output examples
2. Hook: "Day 44: shipped an AI email drafting tool. Here's the full build in under 100 lines of Python." — angle: concise build walkthrough

---

### Day 45 — Tool 1 Polish: Email Assistant
**Task:** Add a simple command-line interface to your email assistant. Add input validation, error handling, and a "save draft to file" option. Write 10 different test cases. Fix any edge cases where the output is weak.

**Posts:**
1. Hook: "The difference between a demo and a real tool: edge cases. Here's what I fixed today." — angle: polishing an AI tool post-MVP
2. Hook: "I ran my AI email writer through 10 different scenarios. Here's where it broke and how I fixed it." — angle: show the testing process

---

### Day 46 — Tool 2 Planning: Content Repurposer
**Task:** Plan an AI content repurposing tool: input a long blog post → output Twitter thread, LinkedIn post, and email newsletter section. Map out the prompt chain: 3 separate prompts for each output format. Design the system prompt for each.

**Posts:**
1. Hook: "The AI tool I actually want to use every week: a content repurposer. Here's the plan." — angle: planning a practical content tool
2. Hook: "One piece of content → 3 formats. I'm building an AI repurposer. Here's the architecture." — angle: prompt chain architecture

---

### Day 47 — Tool 2 Build: Content Repurposer
**Task:** Build the content repurposer. Use 3 chained prompts: (1) extract key ideas, (2) write Twitter thread, (3) write LinkedIn post. Each prompt receives the output of the previous. Test on 5 of your own blog posts or articles.

**Posts:**
1. Hook: "I repurposed 5 articles into Twitter threads, LinkedIn posts, and newsletters using AI today. Here's the tool." — angle: show 3 outputs from 1 input
2. Hook: "Built my content repurposer. The chain prompt approach made the quality much better than a single prompt." — angle: prompt chain quality improvement

---

### Day 48 — Tool 2 Polish: Content Repurposer
**Task:** Add voice customization to the repurposer. Allow the user to input a "voice description" and apply it to all outputs. Test with 3 different writing styles. Add a web UI using Streamlit or Gradio so it's usable without touching code.

**Posts:**
1. Hook: "I added a voice customization feature to my content repurposer. Now it sounds like YOU." — angle: voice injection in content tools
2. Hook: "I gave my AI tool a real UI today using Streamlit. Here's the before and after." — angle: show the Streamlit UI

---

### Day 49 — Tool 3 Planning: AI Research Assistant
**Task:** Plan an AI research assistant: input a topic or question → AI breaks it into sub-questions → researches each using web search (or pre-loaded context) → synthesizes a structured answer with sources. Map the architecture.

**Posts:**
1. Hook: "I'm building an AI research assistant that actually cites its work. Here's the architecture." — angle: research assistant design
2. Hook: "The hardest part of building an AI researcher isn't the AI. It's structuring the output. Here's how I'm approaching it." — angle: output architecture design

---

### Day 50 — Tool 3 Build: Research Assistant
**Task:** Build the research assistant. Use Claude to: (1) decompose a question into 3–5 sub-questions, (2) answer each with a structured format, (3) synthesize into a final answer. Use mock sources for now. Test on 5 research questions.

**Posts:**
1. Hook: "Day 50: shipped a research assistant that breaks questions into sub-questions and answers each one." — angle: show the decompose-then-answer pattern
2. Hook: "I asked my AI research assistant 5 hard questions. Here's how it performed vs. asking Claude directly." — angle: chain vs. direct prompt comparison

---

### Day 51 — Tool 3 Polish + Connect Real Data
**Task:** Connect your research assistant to a real data source: feed it a folder of PDFs or documents. Use basic RAG (from Day 41) to retrieve relevant context. Test whether grounded answers are more accurate than ungrounded ones.

**Posts:**
1. Hook: "I connected my AI research assistant to a folder of documents. Now it gives answers with real citations." — angle: grounded RAG research tool
2. Hook: "RAG changed my research assistant from 'impressive demo' to 'actually useful.' Here's what changed." — angle: grounded vs. ungrounded quality comparison

---

### Day 52 — Make.com Integration
**Task:** Sign up for Make.com (free tier). Build an AI automation: when a form is submitted (e.g., Google Form) → send the text to Claude via API → format the AI response → send the result via email. This is a no-code AI workflow.

**Posts:**
1. Hook: "I connected AI to my email using Make.com today. No code. Here's the workflow." — angle: no-code AI automation tutorial
2. Hook: "Make.com + Claude API = automated AI workflows without writing a single line of code." — angle: make.com AI integration walkthrough

---

### Day 53 — Zapier AI Integration
**Task:** Build the same workflow from Day 52 using Zapier. Compare: ease of setup, available triggers/actions, cost, and limitations of each platform. Build a personal comparison guide.

**Posts:**
1. Hook: "Make.com vs. Zapier for AI automation. I built the same workflow in both. Here's the honest comparison." — angle: platform comparison with concrete use cases
2. Hook: "I'm building no-code AI automations. Here's the platform I'm sticking with and why." — angle: Make.com vs. Zapier decision guide

---

### Day 54 — n8n Self-Hosted Automation
**Task:** Install n8n locally (Docker or npm). Build the same workflow from Day 52 in n8n. Learn the advantages of self-hosted automation: privacy, cost (no per-operation fees), and customization. Connect to Claude API.

**Posts:**
1. Hook: "I moved my AI automations to n8n. It's self-hosted, free, and more powerful than Zapier. Here's the setup." — angle: n8n introduction for AI builders
2. Hook: "Three automation platforms for AI workflows. Make.com, Zapier, n8n. Here's when to use each." — angle: automation platform decision guide

---

### Day 55 — Complex Automation Workflow
**Task:** Build a complex 5-step automation: (1) new email arrives → (2) Claude classifies intent → (3) if sales inquiry, draft reply → (4) format as HTML email → (5) send to yourself for review. This is a real-world AI automation.

**Posts:**
1. Hook: "I built a 5-step AI email automation today. Here's what happens when I get a sales inquiry now." — angle: show the full automation workflow
2. Hook: "AI automation isn't just theory. Here's a real workflow I'm using to handle my inbox." — angle: practical email automation

---

### Day 56 — Week 8 Review + Tool Audit
**Task:** Audit all 3 tools you've built (email assistant, content repurposer, research assistant). Rate each on: usefulness, quality of output, completeness, and shareability. Plan which one is worth turning into a public tool or product.

**Posts:**
1. Hook: "4 weeks of building AI tools. Here's my honest review of everything I made." — angle: tool audit with ratings
2. Hook: "Of the 3 AI tools I built, one is clearly worth productizing. Here's how I'm thinking about it." — angle: product vs. personal tool decision

---

### Week 9–10: Agentic Workflows

---

### Day 57 — What Are AI Agents?
**Task:** Study the architecture of AI agents: perception → reasoning → action loop. Read Anthropic's documentation on building agents. Understand: what makes an agent different from a simple chatbot, the risks of autonomous action, and when to use agents vs. simpler approaches.

**Posts:**
1. Hook: "An AI agent isn't just a chatbot. Here's the actual architecture difference." — angle: agent architecture explained
2. Hook: "I'm learning to build AI agents. Here's my mental model for understanding what they actually are." — angle: agent vs. chatbot explanation

---

### Day 58 — Single-Step Agent Loop
**Task:** Build your first agent loop in Python: Claude receives a task → decides on an action → executes the action (via a tool) → observes the result → decides next step. Use simple tools: read_file, write_file, search_text. Run it on a file organization task.

**Posts:**
1. Hook: "I built my first AI agent today. It can read files, write files, and search text — all on its own." — angle: basic agent loop walkthrough
2. Hook: "The agent loop is the core of agentic AI. Here's the simple version that taught me how it works." — angle: show the perception-reasoning-action cycle

---

### Day 59 — Agent Safety and Human-in-the-Loop
**Task:** Add safety constraints to your agent: (1) require human approval before any write/delete action, (2) set a maximum number of steps, (3) add logging so you can see every decision the agent makes. Test what happens when you remove each constraint.

**Posts:**
1. Hook: "I learned why AI agents need guardrails the hard way. Here's what I added." — angle: agent safety design
2. Hook: "Human-in-the-loop isn't optional for agents. Here's exactly how I implemented it." — angle: approval workflow for agent actions

---

### Day 60 — Multi-Step Task Agent
**Task:** Build an agent that can complete a multi-step research task autonomously: given a company name, the agent should (1) look up information in a local knowledge base, (2) extract key facts, (3) write a structured summary, (4) save to a file. Run it on 5 companies.

**Posts:**
1. Hook: "I gave my AI agent a company name and it did 4 things automatically to build a research brief. Here's the demo." — angle: multi-step agent demo
2. Hook: "Day 60: my agents are doing actual work now. Here's what a working research agent looks like." — angle: show the agent output

---

### Day 61 — Parallel Agent Architecture
**Task:** Learn how to run multiple AI agents in parallel. Build a simple parallel pipeline: a "coordinator" agent breaks a task into sub-tasks → spawns 3 "worker" agents that handle each sub-task simultaneously → coordinator synthesizes results.

**Posts:**
1. Hook: "You can run multiple AI agents at the same time to parallelize work. Here's how the architecture works." — angle: parallel agent pattern
2. Hook: "I built a coordinator + workers agent system. Here's how it 3x'd the speed of my research workflow." — angle: show the parallel speed gain

---

### Day 62 — Evaluations (Evals) Intro
**Task:** Learn about LLM evaluations. Build a simple eval: create 20 test cases for one of your tools, define pass/fail criteria, run Claude on all 20, score the results. This is how you know if your AI tool actually works reliably.

**Posts:**
1. Hook: "How do you know if your AI tool actually works? You build an eval. Here's how." — angle: intro to LLM evals
2. Hook: "I tested my AI tool on 20 cases today with pass/fail scoring. Here's the accuracy." — angle: show the eval results

---

### Day 63 — Improving Based on Evals
**Task:** Take your worst-performing test cases from Day 62. Diagnose why they failed — prompt issue, context issue, or model limitation? Iterate on the prompt until you fix at least 5 failing cases without breaking passing cases. Re-run the eval.

**Posts:**
1. Hook: "My AI tool failed 8 out of 20 test cases. Here's how I fixed it." — angle: prompt debugging via evals
2. Hook: "Evals are the feedback loop that makes AI tools actually reliable. Here's my iteration process." — angle: eval-driven improvement

---

### Day 64 — Production-Ready AI Script
**Task:** Take your best tool from earlier and make it "production ready": proper logging, environment variable management (python-dotenv), config files, README documentation, and a requirements.txt. This is what separates a script from a deployable tool.

**Posts:**
1. Hook: "There's a big gap between 'works on my laptop' and 'production ready.' Here's what I added today." — angle: production readiness checklist
2. Hook: "I'm making my AI tools deployable. Here's the exact structure I'm using." — angle: show the folder structure and components

---

### Day 65 — Vector Database Introduction
**Task:** Learn about vector databases: what embeddings are, how semantic search works, and why vector DBs enable better RAG. Use ChromaDB (free, local) to build a simple semantic search over 50 documents. Compare to keyword search from Day 41.

**Posts:**
1. Hook: "Semantic search is how AI can understand that 'fix my car' and 'vehicle repair' mean the same thing. Here's how it works." — angle: embeddings and semantic search explained
2. Hook: "I added a vector database to my RAG system. Here's the quality difference vs. keyword matching." — angle: semantic vs. keyword search comparison

---

### Day 66 — Full RAG Pipeline
**Task:** Build a complete RAG pipeline with ChromaDB: load documents → chunk → embed → store → on query, retrieve top-3 relevant chunks → pass to Claude with retrieved context → structured answer with sources. Test on a 20-document knowledge base.

**Posts:**
1. Hook: "Full RAG pipeline built. I can now ask Claude questions about any set of documents I give it." — angle: complete RAG tutorial
2. Hook: "Day 66: shipped a full RAG system with real vector search. Here's the architecture." — angle: show the pipeline diagram

---

### Day 67 — Fine-Tuning Overview
**Task:** Learn what fine-tuning is and when it's worth it vs. prompt engineering. Read Anthropic's fine-tuning docs (if available) and OpenAI's fine-tuning guide. Build a comparison: 5 scenarios and whether each warrants prompt engineering, RAG, or fine-tuning.

**Posts:**
1. Hook: "When do you fine-tune a model vs. just writing a better prompt? Here's the framework I use." — angle: prompt engineering vs. RAG vs. fine-tuning decision tree
2. Hook: "Fine-tuning is misunderstood. Most people don't need it. Here's when it actually makes sense." — angle: fine-tuning use case analysis

---

### Day 68 — Model Selection Strategy
**Task:** Build a personal model selection guide: for 10 different task types (long-form writing, code generation, data extraction, reasoning, customer support, etc.), determine which model (Claude Sonnet, Claude Haiku, GPT-4o, GPT-4o-mini) is best on cost-vs-quality.

**Posts:**
1. Hook: "Not every task needs the most expensive model. Here's how I choose which AI model to use for each task." — angle: cost-vs-quality model selection guide
2. Hook: "Claude Haiku vs. Sonnet vs. Opus. I ran them on 10 task types. Here's the breakdown." — angle: model comparison results

---

### Day 69 — Async API Calls
**Task:** Learn to make asynchronous API calls in Python using asyncio. Build a script that sends 10 API requests simultaneously instead of sequentially. Measure the speed improvement. This is critical for building scalable AI applications.

**Posts:**
1. Hook: "Sequential AI API calls are 10x slower than they need to be. Here's how to parallelize them." — angle: async API calls tutorial
2. Hook: "I made my AI script 8x faster today by switching to async. Here's the code change." — angle: show the async improvement

---

### Day 70 — Phase 2 Wrap-Up
**Task:** Create a "Day 70 portfolio update" — document all tools built, skills learned, and real outputs from each. Identify your strongest skill area (automation? RAG? agents? API integration?) and your biggest gap. This informs your Phase 3 focus.

**Posts:**
1. Hook: "70 days of prompt engineering. Here's everything I've built and what's still missing." — angle: honest progress audit
2. Hook: "I now know which part of AI engineering I'm actually good at. Here's how I figured it out." — angle: skill self-assessment

---

## Phase 3 — Monetization (Days 71–90)

### Week 11–12: Package as Product or Service

---

### Day 71 — Identify Your Niche
**Task:** Define your specific niche as an AI consultant/builder. Write a one-page positioning statement: who you help, what problem you solve, what you build, and what outcome clients get. Avoid "I do AI stuff." Get specific: "I build AI content workflows for 1-person media companies."

**Posts:**
1. Hook: "The reason most AI consultants struggle to get clients: they're not specific enough. Here's how I'm positioning myself." — angle: niche positioning for AI consultants
2. Hook: "I spent Day 71 writing my positioning statement. Here's what I landed on and why." — angle: share the positioning and get feedback

---

### Day 72 — Productize Your Best Tool
**Task:** Take your strongest tool and package it as a product. Write: a product description, feature list, use cases, pricing tiers, and a one-page landing page outline. This doesn't need to launch today — it needs to be real enough to pitch to someone.

**Posts:**
1. Hook: "I'm turning my AI email assistant into a real product today. Here's the packaging." — angle: show the product spec
2. Hook: "Productizing an AI tool means answering: who buys this, what does it cost, and what do they get. Here's my draft." — angle: productization framework

---

### Day 73 — Build a Landing Page
**Task:** Build a simple landing page for your AI tool using Carrd, Framer, or plain HTML. Include: headline, problem statement, solution, features, pricing, and a CTA (email waitlist or buy button). Keep it under 5 sections.

**Posts:**
1. Hook: "I built a landing page for my AI tool today. Here's the copy and what each section is trying to do." — angle: show the landing page with copy breakdown
2. Hook: "Your AI tool needs a landing page before it needs more features. Here's the one I built." — angle: share the page and invite feedback

---

### Day 74 — Pricing Strategy
**Task:** Research pricing for comparable AI tools and services. Build a 3-tier pricing model (free/basic, pro, enterprise). Calculate your cost per user (API costs + time) at each tier. Set prices that create margin while being competitive.

**Posts:**
1. Hook: "I spent Day 74 figuring out how to price my AI tool. Here's the math." — angle: cost → margin → pricing walkthrough
2. Hook: "The 3-tier pricing model that works for AI tools. Here's what I'm going with." — angle: share the pricing and reasoning

---

### Day 75 — Build a Demo
**Task:** Record a 2-minute screen recording demo of your best tool. Narrate what the tool does, why it matters, and show 2–3 real use cases. This becomes your sales asset — it shows rather than tells.

**Posts:**
1. Hook: "A demo video is better than any pitch deck. Here's the 2-minute demo I built for my AI tool." — angle: share the demo link
2. Hook: "Day 75: I can now show someone my AI tool in 2 minutes. Here's the script I used." — angle: share the demo script as a template

---

### Day 76 — Service Packaging
**Task:** Design an AI consulting service package (not a product). Define: scope, deliverables, timeline, price, and what you do vs. what the client does. Create 3 packages: Starter ($500–$1k), Growth ($2k–$5k), Enterprise ($10k+).

**Posts:**
1. Hook: "AI consulting isn't just 'charging for your time.' Here's how I'm structuring service packages." — angle: service packaging for AI consultants
2. Hook: "3 service tiers for AI integration work. Here's exactly what each includes and why." — angle: share the packages

---

### Day 77 — Case Study Development
**Task:** Take one of your real projects (even if self-initiated) and write it as a case study: problem → approach → AI architecture → outcome → what you learned. This is your first portfolio piece and proof of capability.

**Posts:**
1. Hook: "I turned a personal AI project into a case study today. Here's the format that made it look professional." — angle: case study structure for AI work
2. Hook: "My first AI case study: how I built a research assistant that saved me 3 hours a week." — angle: share the case study

---

### Day 78 — Build Your AI Portfolio
**Task:** Create a simple portfolio page (can be Notion, a GitHub README, or a simple website) that showcases: your 3 tools, your case study, your skills/tech stack, and a contact method. This is what you send potential clients.

**Posts:**
1. Hook: "My AI portfolio is live. Here's what I included and why." — angle: share the portfolio link
2. Hook: "The fastest way to build an AI portfolio: document everything you build as you build it. Here's mine." — angle: portfolio-building system

---

### Day 79 — Target Client Research
**Task:** Identify 20 potential first clients: businesses or individuals who could benefit from your specific AI service. Research each one: their industry, their likely AI pain points, and one specific improvement you could make for them.

**Posts:**
1. Hook: "I researched 20 potential AI clients today. Here's the pattern I noticed in who needs this most." — angle: share insights from the research
2. Hook: "Finding AI clients isn't about finding people who 'want AI.' It's about finding people with this specific problem." — angle: client identification framework

---

### Day 80 — Cold Outreach System
**Task:** Write 5 personalized cold email templates for 5 different prospect types (e-commerce brand, creator/newsletter, consulting firm, SaaS startup, local business). Each email should: reference a specific pain point, mention a specific tool you built, and have one clear CTA.

**Posts:**
1. Hook: "Here are the 5 cold emails I'm sending to land my first AI consulting client. Steal the templates." — angle: share the email templates with explanation
2. Hook: "AI cold email doesn't have to be generic. Here's how I personalized mine." — angle: personalization strategy

---

### Day 81 — Send First 20 Outreach Messages
**Task:** Send personalized outreach to your 20 prospects from Day 79 using your templates from Day 80. Track: sent, opened, replied, interested. Don't wait for results — this is a volume and iteration game.

**Posts:**
1. Hook: "I sent 20 cold emails about my AI service today. Here's the exact message I used." — angle: share the email and invite feedback
2. Hook: "Day 81: the scary part. Actually reaching out. Here's how I'm tracking the results." — angle: tracking system + accountability post

---

### Day 82 — Build an Audience Funnel
**Task:** Design a content → audience → client funnel: your daily posts build an audience → your audience sees your tools → some become clients or customers. Map out the funnel stages and what content serves each stage.

**Posts:**
1. Hook: "Building in public isn't just about likes. It's a client acquisition strategy. Here's how the funnel works." — angle: content → audience → client pipeline
2. Hook: "Every post I've written for 82 days is part of a system. Here's how I think about it." — angle: 82-day content strategy review

---

### Day 83 — LinkedIn Optimization
**Task:** Optimize your LinkedIn profile as an AI engineer/consultant: update headline, about section, featured section (with your tools/case study), and experience. Connect with 20 AI-related professionals. Engage with 10 posts in your niche.

**Posts:**
1. Hook: "I updated my LinkedIn to reflect my AI skills today. Here's the headline I landed on and why." — angle: LinkedIn positioning for AI professionals
2. Hook: "Day 83: LinkedIn outreach for AI consulting. Here's my connection strategy." — angle: LinkedIn prospecting system

---

### Day 84 — Track Results + Iterate
**Task:** Review all outreach from Days 81–83. Analyze: which messages got replies, which didn't, and why. Rewrite the bottom 2 templates. Research why the top templates worked. This is your first sales optimization loop.

**Posts:**
1. Hook: "Results from my first AI client outreach sprint. Here's what worked and what didn't." — angle: honest outreach performance review
2. Hook: "My cold emails had a 15% reply rate. Here's the 3 things the best ones had in common." — angle: sales insights from the data

---

### Week 13: First Client or Product Launch

---

### Day 85 — First Calls
**Task:** Schedule and run at least 2 discovery calls with interested prospects. Ask: what their current workflow looks like, where AI could save them time, and what outcome they care about most. Take notes. Don't sell — listen and understand.

**Posts:**
1. Hook: "I had my first two discovery calls for AI consulting today. Here's what I learned." — angle: insights from client discovery
2. Hook: "The question that changed every discovery call I've had: 'What would you do with 5 extra hours a week?'" — angle: discovery call insights

---

### Day 86 — Write a Proposal
**Task:** Write a detailed proposal for your most interested prospect: problem summary, proposed solution (with your specific tools/approach), timeline, deliverables, pricing, and terms. This is your first real AI consulting proposal.

**Posts:**
1. Hook: "I wrote my first AI consulting proposal today. Here's the structure I used." — angle: share the proposal template (without client info)
2. Hook: "The AI consulting proposal is where most people overthink it. Here's the simple version that works." — angle: concise proposal approach

---

### Day 87 — Product Launch Prep
**Task:** If you're going the product route instead of consulting: finalize your product (fix last bugs), write product copy for the landing page, set up Stripe or Gumroad for payments, and write a launch announcement post for Twitter/X and LinkedIn.

**Posts:**
1. Hook: "I'm launching my AI tool in 3 days. Here's everything I'm doing to prepare." — angle: launch checklist with details
2. Hook: "Pre-launch day. Here's the honest state of my AI product." — angle: transparency post about launch readiness

---

### Day 88 — Send Follow-Ups
**Task:** Send follow-up messages to all outstanding prospects and any unanswered outreach. Write personal follow-up emails that add value (share a relevant resource, offer a mini audit, or reference something specific to their business). Don't just say "checking in."

**Posts:**
1. Hook: "The follow-up message that gets replies is never 'just checking in.' Here's what I send instead." — angle: follow-up template with reasoning
2. Hook: "Day 88: follow-up week. Here's my entire outreach sequence at this point." — angle: full outreach sequence overview

---

### Day 89 — Launch or First Client
**Task:** Either: launch your product publicly (post on Twitter/X, LinkedIn, post in relevant communities, email your waitlist) OR sign your first consulting client (countersign the proposal, take a deposit, schedule kickoff). Today is the milestone day.

**Posts:**
1. Hook: "Day 89. 90 days ago I didn't know how to call an API. Today I [launched / signed my first client]." — angle: milestone announcement
2. Hook: "Here's exactly what it took to go from zero to [first product launch / first AI consulting client] in 89 days." — angle: honest journey recap

---

### Day 90 — Retrospective and What's Next
**Task:** Write a full retrospective: what you built, what you learned, what surprised you, what you'd do differently, and what your next 90 days look like. Publish it publicly. This is your single best piece of content — 90 days of story in one post.

**Posts:**
1. Hook: "90 days of learning AI/prompt engineering. Here's everything I built, every tool, every mistake, and what's next." — angle: full 90-day retrospective
2. Hook: "I spent 90 days going deep on AI. Here are the 10 things I wish I knew on Day 1." — angle: lessons-learned listicle
3. Hook: "What does 90 days of daily AI practice actually produce? I'll show you." — angle: portfolio showcase — all tools, all posts, all results *(high-output day)*

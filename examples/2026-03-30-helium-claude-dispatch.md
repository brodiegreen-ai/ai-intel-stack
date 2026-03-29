# AI Daily Digest – 2026-03-30
Sources: Nate helium/Qatar video, Anthropic Dispatch/Computer Use launch coverage

## 1. Models & Infrastructure

- Missile and drone attacks on Qatar’s Ras Laffan complex have taken all three helium plants offline, removing roughly one-third of global helium supply and permanently damaging an estimated 14% of Qatar’s capacity with multi-year repair timelines. [web:123][web:124][web:125][web:127][web:129][web:134]
- Helium is a non-substitutable input for advanced semiconductor fabs: it cools wafers during plasma etching and is used to test vacuum chambers, so shortages hit cutting-edge HBM memory and logic fabs in South Korea and Taiwan first. [web:124][web:125][web:127][web:128][web:129][web:130][web:133]
- Spot helium prices and memory prices are already up sharply, and analysts now expect high DRAM/HBM pricing and tight GPU/AI-grade compute supply to persist well into 2027–2028. [web:124][web:125][web:127][web:128][web:129][web:130][web:133]

## 2. Agents, Tools & Workflows

- Anthropic has introduced three key “agent primitives” for Claude: scheduled tasks that run in Anthropic’s cloud on a timetable, Dispatch to orchestrate work from your phone to your desktop, and “computer use” so Claude can control your apps and browser via mouse and keyboard. [web:71][web:73][web:75][web:77][web:132][web:135]
- Together, these features let you text Claude from your phone, have it open apps, click through legacy tools with no API, pull data, update documents, and deliver finished work on your machine while you’re away, instead of just producing more summaries to read. [web:71][web:73][web:75][web:77][web:132][web:135]
- Anthropic is explicitly aiming for “real work off your desk” workflows, positioning Claude as a managed, safer alternative to self-hosted agent stacks like OpenClaw, where users have to run the infrastructure and accept more risk. [web:71][web:73][web:75][web:77][web:132][web:135]

## 3. Business & Strategy

- The Qatar helium shock underlines how trillion-dollar AI capex plans still hinge on a few physical choke points: LNG-linked helium plants, shipping routes like the Strait of Hormuz, and East Asia’s dependence on imported energy and gases. [web:123][web:124][web:125][web:127][web:128][web:129][web:130][web:133]
- China is moving to harden its position by accelerating domestic helium production and the Power of Siberia 2 gas pipeline, which would give it cheaper, more reliable energy and helium and let it undercut Western-aligned fabs on chip and compute costs later this decade. [web:125][web:127][web:129][web:130][web:133]
- On the software side, Anthropic’s managed agent approach mirrors historical shifts from self-hosted email and servers to Gmail and cloud: self-hosted systems prove what’s possible, but managed, safer versions tend to win mainstream adoption. [web:71][web:73][web:75][web:77][web:132][web:135]

## 4. Policy, Safety & Industry Moves

- Ras Laffan has effectively become a geopolitical pressure point: damage there simultaneously squeezes global helium, LNG, advanced chips, and AI hardware, and there is no fast way to rebuild capacity or qualify new 6N-purity helium sources. [web:123][web:124][web:125][web:127][web:128][web:129][web:131][web:134]
- South Korea and Taiwan are especially exposed: South Korea previously imported around two-thirds of its helium from Qatar, and both Samsung/SK Hynix (memory) and TSMC (logic) face higher input costs and tighter supply, with governments now discussing stockpiles and diversification incentives. [web:124][web:125][web:126][web:127][web:129][web:130][web:133]
- Anthropic is marketing Claude’s new capabilities as powerful but controlled: computer use and Dispatch require explicit permissions, run in sandboxes, and are labelled as early-stage, which is meant to reassure regulators and enterprises wary of fully autonomous, unsupervised agents. [web:71][web:73][web:75][web:77][web:132][web:135]

## 5. What This Means for Brodie (Action Ideas)

- Assume hardware and memory stay expensive: your planned MacBook (Pro-tier chip, 24 GB RAM, 1 TB SSD) is a sensible middle ground; don’t count on a near-term “cheap compute” window given ongoing helium, LNG, and DRAM constraints. [web:91][web:95][web:123][web:124][web:125][web:127][web:128][web:129][web:130][web:133]
- Design your own AI Daily Digest stack around the Claude primitives pattern:
  - Scheduled tasks → n8n cron jobs that fetch and summarise news into Supabase. [web:35][web:36][web:37][web:40][web:71][web:73][web:132][web:135]
  - Dispatch → a simple phone-friendly control surface (bot or UI) where you assign intel and research jobs while you’re away from the desk. [web:35][web:36][web:37][web:39][web:71][web:73][web:132][web:135]
  - Computer use → longer-term, agent workflows that can operate web dashboards or Etsy backends with no API. [web:36][web:38][web:39][web:71][web:73][web:75][web:132][web:135]
- Judge your agents and workflows by “work off your desk”, not by flashiness: prioritise automations that remove hours of grunt work per week (news aggregation, tagging, report prep, spreadsheet updates) instead of ones that just generate more text to read. [web:71][web:73][web:75][web:77][web:132][web:135]
- Capture these themes as future product ideas:
  - Planner pages/modules about “supply-chain reality of AI hardware”, “designing agents that truly work while you sleep”, and “managing open loops with AI” could become planner SKUs or content for AI-curious entrepreneurs. [web:47][web:53][web:71][web:73][web:75][web:77][web:132][web:135]

# Peter's Vision and Requirements - Analysis in Progress

## Overview
The SPARK internship program is focused on teaching AI and process automation using Make.com as a foundation, with eventual migration to Microsoft Power Platform. Peter Wolf is funding this program independently to accelerate learning.

## Key Vision Elements Discovered So Far

### 1. Educational Program Structure
- **Pre-Internship Training:**
  - Initial: PL-900, Power Automate, Copilot Studio, Power Apps (26-37 hours)
  - Advanced: PL-200, AI solutions, OpenAI API integration, Zapier (44-55 hours)
  - Alternative track: ChatGPT, custom GPTs, OpenAI APIs, Zapier
  - Peter covers certification exam costs

- **Learning Path:**
  - Start with Make.com/Zapier (non-Microsoft environment)
  - Transition to Microsoft Power Platform
  - Focus on practical, hands-on experience
  - Build portfolio on GitHub

### 2. Process Automation Flows Built

#### A. Gmail Inbox Auto-Research Process
- **Trigger:** Email with "Research+" subject line
- **Flow:** Gmail → ChatGPT (extract URL) → Perplexity (30-word summary) → Google Sheets
- **Purpose:** Automated research article processing

#### B. Newsletter Process Flow (9 automations)
- **Components:**
  1. Inoreader RSS - Top 3 articles selection
  2. Content aggregator from social media
  3. Content formatter with ChatGPT
  4. Final sender via Brevo
  5. Scrape system (daily 9am)
  6. Daily insights processor
  7. AI tools processor
  8. Upcoming events processor
  9. Article search with Perplexity/Claude

- **Peter's Requirements:**
  - Add personal spin/commentary
  - Include his headshot
  - Position as "my words" with strategic commentary
  - Need viral content (1000s of likes, not 10-20)
  - Finance/treasury angle, not just AI

#### C. LinkedIn Content Process Flow (3 automations)
- **Components:**
  1. Get articles from Inoreader, ChatGPT chooses top 3
  2. Create LinkedIn post with persona
  3. Post to LinkedIn when ready

- **Key Feature:** Different personas for each user (Peter, Nick, Bryan)

#### D. Research Company Process Flow (2 workflows)
- **Components:**
  1. Manual trigger from Google Sheets checkbox
  2. Automated job post scraping (SAP Finance/Treasury jobs)

- **Output:** Company executive summary reports in Google Docs

#### E. Database AI Agent Process Flow
- **Purpose:** Contact and interaction database management
- **Features:** 5 Make.com tools for CRUD operations
- **Interface:** Custom GPT for natural language queries

### 3. Technical Architecture
- **Current Stack:**
  - Make.com for automations
  - Google Workspace (Sheets as databases, Docs for output)
  - AI: ChatGPT, Claude, Perplexity
  - Email: Brevo for newsletters
  - Scraping: Apify
  - Content sources: Inoreader RSS, LinkedIn, Reddit

- **Future Migration:**
  - Microsoft Power Platform
  - Power Automate (Make.com equivalent)
  - Power Apps
  - Microsoft Teams integration

### 4. GitHub Repository Requirements
From emails: Peter wants the interns to build a "robust portfolio on GitHub showcasing a breadth and depth of project outputs" including:
- Automated workflows
- Custom AI chatbots
- Integrated apps
- READMEs with screenshots/demo videos

### 5. Key Pain Points/Challenges
- Personal Gmail account connections require complex Google Cloud setup
- Content sourcing - need high-engagement content, not low-engagement posts
- Apple News redirect links breaking automations
- PDF vs Google Docs parsing issues
- Need responsive triggers, not polling-based

### 6. Strategic Goals
- Equip interns with in-demand skills for enterprise technology
- Create practical solutions for real-world business challenges
- Build comprehensive portfolio demonstrating hands-on experience
- Position interns as "compelling candidates to employers"

## Still To Analyze
- Remaining 34 meeting transcripts
- Complete technical documentation in Process Flows
- Any additional program documentation
- Full synthesis of Peter's complete vision

## Next Steps
1. Continue reading remaining meeting transcripts
2. Extract all mentions of GitHub repository structure
3. Document all technical requirements mentioned
4. Identify gaps between what's built vs. what Peter wants
5. Create comprehensive PETER_COMPLETE_VISION.md
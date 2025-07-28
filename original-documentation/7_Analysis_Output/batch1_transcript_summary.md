# Meeting Transcripts Batch 1 Summary (June-July 2025)

## Meeting 1: June 30, 2025 (Monday)

### Key Topics:
- Newsletter automation revisions and improvements
- Social media content sourcing challenges
- Research company flow planning

### Major Decisions/Requirements:
1. **Newsletter Changes:**
   - Peter wants to add personal spin/commentary to newsletter
   - Include his headshot in introduction
   - Make it "my words" with strategic commentary about weekly events
   - Expert commentary should be positioned as Peter's personal insights

2. **Content Sourcing Issues:**
   - LinkedIn profiles from Nick getting very low engagement (10-20 likes)
   - Peter needs viral content with thousands of likes/engagement
   - May focus on Taplio's top AI influencers instead of provided list
   - Need finance/treasury angle, not just AI

3. **New Flow - Research Company:**
   - Start with Google Forms trigger (non-Microsoft environment)
   - Eventually want Microsoft Teams integration as trigger
   - Need responsive/timely execution, not hourly checks
   - Avoid constant Gmail polling to save operations

### Technical Details:
- Currently have 8 automations in newsletter system
- Using Inoreader RSS, LinkedIn scraping, Reddit
- Newsletter structure includes: intro, blurbs, social media, AI tools, prompts, Serrala insights, upcoming events
- Using Brevo for email distribution

### Action Items:
- Continue creating flows despite not finalizing details
- Figure out better content sources for higher engagement
- Implement research company flow with Google Forms trigger

## Meeting 2: June 5, 2025 (Thursday)

### Key Topics:
- Detailed walkthrough of Gmail automation process flow
- Training session for interns on Make.com
- Troubleshooting personal Gmail account connections

### Major Decisions/Requirements:
1. **Process Flow Walkthrough:**
   - Gmail trigger → ChatGPT extracts URL → Perplexity summarizes → Google Sheets update
   - 15-minute check intervals for Gmail
   - "Research+" subject line as trigger
   - 30-word summaries from Perplexity

2. **Technical Challenges:**
   - Apple News redirect links causing issues
   - Solution: HTTP request module to follow redirects
   - Personal Gmail accounts need Google Cloud Platform setup

3. **Training Focus:**
   - Building skills for eventual Microsoft Power Automate migration
   - Understanding connections, API calls, and flow structure
   - Hands-on troubleshooting experience

### Technical Details:
- Using GPT-4.1 and Perplexity Sonar Pro models
- Make.com history feature for debugging
- Custom connectors possible for missing integrations

## Meeting 3: June 6, 2025 (Friday)

### Key Topics:
- Step-by-step Google Cloud Platform setup for personal Gmail
- Connecting personal Gmail accounts to Make.com

### Major Decisions/Requirements:
1. **Gmail Connection Process:**
   - Create Google Cloud project
   - Enable Gmail API
   - Configure OAuth consent screen
   - Add make.com and integromat.com as authorized domains
   - Add test users

2. **Technical Setup:**
   - Detailed walkthrough of scopes and permissions
   - PIN important services in Google Cloud console
   - Create OAuth client credentials

### Technical Details:
- Business accounts easier to connect than personal
- Security restrictions on personal Gmail accounts
- Need to whitelist both make.com and integromat.com (legacy)

## Meeting 4: June 23, 2025 (Saturday)

### Key Topics:
- Newsletter automation improvements with social media scraping
- Adding AI tools section
- Implementing content filters

### Major Decisions/Requirements:
1. **New Content Sources:**
   - Scraping LinkedIn posts via Apify
   - Scraping Reddit r/automation posts
   - Filter: LinkedIn posts with >1500 likes
   - Top AI automation influencers

2. **Newsletter Sections:**
   - AI automation tools
   - Social media content
   - Introduction section
   - Checkbox selection system for content inclusion

3. **Workflow Changes:**
   - Final trigger moved to social media posts tab
   - ChatGPT selects top 3 posts
   - Each section gets its own spreadsheet tab

### Technical Details:
- Using Apify marketplace for scraping
- GPT-4o for AI tools search
- Multiple Google Sheets tabs for content management

## Meeting 5: June 16, 2025 (Monday)

### Key Topics:
- Switching from ChatGPT to Claude (Anthropic) for LinkedIn content
- Troubleshooting PDF persona document issues

### Major Decisions/Requirements:
1. **Claude Integration:**
   - Replace ChatGPT with Claude for LinkedIn post creation
   - Need to handle persona documents differently
   - PDF conversion required for Google Docs

2. **Technical Challenges:**
   - Google Docs API cannot parse certain document types
   - Solution: Convert persona to PDF, use Google Drive download
   - Remapping required for Claude integration

3. **Organization Requests:**
   - Separate folders for draft documents
   - Better file management in Google Drive

### Technical Details:
- Claude requires different prompt structure
- PDF documents work better than Google Docs for parsing
- Google Drive download file module as workaround
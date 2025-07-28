# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

The SPARK Master Project is a comprehensive documentation and automation system for the SPARK internship program. This repository focuses on process automation workflows using Make.com, AI integrations, and cloud services to streamline business operations.

## High-Level Architecture

### Core Purpose
- **Documentation Repository**: Centralized storage for process automation workflows, meeting transcripts, and program documentation
- **Process Automation**: Integration of AI tools (ChatGPT, Claude, Perplexity) with Make.com for workflow automation
- **Knowledge Management**: Systematic organization of SOPs, blueprints, and implementation guides

### Technology Stack
- **Automation Platform**: Make.com (primary workflow engine)
- **AI Integration**: ChatGPT (GPT-4o), Claude, Perplexity AI
- **Data Storage**: Google Sheets, Google Drive, Google Docs
- **Email Services**: Brevo (newsletter campaigns)
- **Content Sources**: Inoreader RSS, LinkedIn, Reddit, Apify scraping
- **Frontend Interfaces**: Custom GPT interfaces, Google Sheets UI

## Current Mission & Analysis Goals

### Phase 1: Complete Knowledge Absorption
- **Meeting Analysis**: Process all 39 meeting transcripts to extract requirements, decisions, and Peter's vision
- **Documentation Review**: Read ALL program documentation, emails, and research files
- **Technical Inventory**: Document all existing automations and their current state

### Phase 2: Vision Extraction  
- **Peter's Requirements**: Extract every requirement, wish, and goal mentioned by Peter across all sources
- **Gap Analysis**: Compare what's been built vs. what's been requested
- **Success Metrics**: Identify how success is measured according to discussions

### Phase 3: Ultimate GitHub Repository Creation
- **Goal**: Build a comprehensive GitHub repository that exceeds Peter's expectations
- **Include**: All automation blueprints, documentation, setup guides, and innovations
- **Exceed Expectations**: Add features and documentation not requested but valuable

## Directory Structure

```
/
├── 1_Meeting_Transcripts/          # Daily SPARK meeting recordings (MD format)
├── 2_Process_Flows/                # Core automation workflows
│   └── Process Flows/              
│       ├── DATABASE AGENT PROCESS FLOW/
│       ├── GMAIL INBOX AUTO-RESEARCH PROCESS/
│       ├── LINKEDIN PROCESS FLOW/
│       ├── NEWSLETTER PROCESS FLOW/
│       └── RESEARCH COMPANY PROCESS FLOW/
├── 3_Program_Documentation/        # Official program docs (DOCX format)
├── 4_Research_Documents/           # Research materials
├── 5_Email_Communications/         # Email archives (MSG files)
├── 6_Presentations_Excel/          # Presentations and spreadsheets
└── 7_Analysis_Output/              # Generated analysis and reports
```

## Key Process Flows

### 1. Database Agent Process Flow
- **Purpose**: AI agent for Google Sheets contact database management
- **Components**: 5 Make.com tools for data operations (add, find, update)
- **Tech**: ChatGPT + Custom GPT interface + Google Sheets
- **Files**: `/2_Process_Flows/Process Flows/DATABASE AGENT PROCESS FLOW/`

### 2. Newsletter Process Flow  
- **Purpose**: Automated newsletter creation and distribution
- **Components**: 9 interconnected Make.com automations
- **Data Sources**: Inoreader RSS, social media, web scraping
- **Distribution**: Brevo email campaigns
- **Files**: `/2_Process_Flows/Process Flows/NEWSLETTER PROCESS FLOW/`

### 3. LinkedIn Process Flow
- **Purpose**: Automated LinkedIn content creation and posting
- **Components**: 3 Make.com workflows for content curation and posting
- **AI Integration**: Content selection and post generation
- **Files**: `/2_Process_Flows/Process Flows/LINKEDIN PROCESS FLOW/`

### 4. Research Company Process Flow
- **Purpose**: Automated company research and report generation
- **Components**: 2 workflows for company analysis and job posting research
- **Output**: Formatted Google Docs with company intelligence
- **Files**: `/2_Process_Flows/Process Flows/RESEARCH COMPANY PROCESS FLOW/`

### 5. Gmail Inbox Auto-Research Process
- **Purpose**: Automated research article processing from Gmail
- **Trigger**: "Research+" label in Gmail inbox
- **Output**: Structured data in Google Sheets
- **Files**: `/2_Process_Flows/Process Flows/GMAIL INBOX AUTO-RESEARCH PROCESS/`

## File Organization Patterns

### Process Flow Structure
Each process flow directory contains:
- `Loom Videos/` - Video documentation (.mp4)
- `Original Dev notes/` - Development notes and iterations  
- `SOP doc title and link/` - Standard Operating Procedures (.md)
- `Sample Googlesheets or Database/` - Example data files (.xlsx)
- `json files/` - Make.com blueprint files (.blueprint.json)

### Blueprint Files
- Naming convention: `[Number]. [Description].blueprint.json`
- Contains Make.com automation configurations
- Can be imported directly into Make.com platform

### Documentation Files
- SOPs in Markdown format with detailed step-by-step processes
- Include prompts, variable definitions, and technical specifications
- Large files (>256KB) - use offset/limit parameters when reading

## Common Development Tasks

### Working with Process Flows
```bash
# Read process flow documentation
Read /home/aiwithnick/SPARK_MASTER_PROJECT/2_Process_Flows/Process Flows/[FLOW_NAME]/SOP doc title and link/[SOP_FILE].md

# Access blueprint files
Read /home/aiwithnick/SPARK_MASTER_PROJECT/2_Process_Flows/Process Flows/[FLOW_NAME]/json files/[BLUEPRINT].blueprint.json

# View sample data
Read /home/aiwithnick/SPARK_MASTER_PROJECT/2_Process_Flows/Process Flows/[FLOW_NAME]/Sample Googlesheets or Database/[SAMPLE].xlsx
```

### Analyzing Meeting Transcripts
```bash
# Search for specific topics across meetings
Grep "automation|workflow|process" /home/aiwithnick/SPARK_MASTER_PROJECT/1_Meeting_Transcripts/

# Read specific meeting transcript
Read /home/aiwithnick/SPARK_MASTER_PROJECT/1_Meeting_Transcripts/2025_[DATE]_[DAY]_spark_meeting.md
```

### Working with Large Documentation Files
```bash
# Read SOP files (often large - use limits)
Read [SOP_FILE] --limit 100 --offset 0

# Search within large files
Grep "[search_term]" [large_file] --output_mode content
```

## AI Integration Patterns

### Make.com Automation Structure
- **Triggers**: Webhooks, scheduled triggers, Google Sheets changes
- **AI Processing**: ChatGPT/Claude for content analysis and generation
- **Data Flow**: API calls → AI processing → Google Sheets/Docs output
- **Error Handling**: Built-in delays, rate limiting, fallback logic

### Prompt Engineering
- Structured prompts with system instructions, persona definitions, and output formats
- JSON output formatting for structured data processing
- Context-aware processing with dynamic variables
- Target market and persona integration for content curation

### Common AI Tools Integration
- **ChatGPT**: Content selection, summarization, data extraction
- **Claude**: Document creation, analysis, formatting  
- **Perplexity**: Research, fact-checking, web content analysis

## Development Conventions

### File Naming
- Meeting transcripts: `YYYY_MM_DD_dayname_spark_meeting.md`
- Blueprint files: `[Number]. [Descriptive Name].blueprint.json`
- SOP documents: `Copy of [Process Name] SOP Documentation.md`

### Data Management
- Google Sheets serve as both databases and user interfaces
- UUID generation for contact management
- Structured data with specific column conventions
- Apps Script integration for webhook triggers

### Version Control
- Documentation updates tracked through file modifications
- Blueprint files maintained as exportable Make.com configurations
- Video documentation for visual process walkthroughs

## Testing and Validation

### Process Flow Testing
- Manual trigger testing through Google Sheets interfaces
- End-to-end workflow validation
- AI agent response verification
- Email delivery confirmation (for newsletter flows)

### Data Integrity
- UUID uniqueness validation
- Google Sheets data consistency checks
- API rate limiting compliance
- Error handling verification

## Integration Notes

### Make.com Platform
- Blueprint files can be directly imported
- Webhook configurations require active endpoints
- Rate limiting considerations for API calls
- Connection management for Google services

### Google Workspace Integration
- Sheets API for data management
- Drive API for document storage
- Apps Script for trigger mechanisms
- OAuth configuration for service connections

### Third-Party Services
- Brevo for email campaigns
- Inoreader for RSS feeds
- Apify for web scraping
- Social media API integrations

## Troubleshooting Common Issues

### Large File Handling
- Use offset/limit parameters for files >256KB
- Break down large SOP documents into sections
- Use Grep for targeted content search

### Documentation Access
- SOP files may require sectioned reading
- Video files need appropriate media tools
- Excel files contain sample data structures

### Automation Dependencies  
- Google Sheets formulas and Apps Script integration
- Make.com webhook endpoint availability
- AI service API rate limits and quotas
# AI-Powered Content Generation & CRM Automation System

## 1. Project Overview

This project is a no-code AI automation system designed to automate the entire content production lifecycle using:

- n8n (workflow automation)
- Notion (database & CRM)
- Groq (AI content generation)
- Picsart (image generation)

### Objective

To automate the complete pipeline:

- Lead / content brief input
- AI-based content generation
- Automated image creation
- CRM-style tracking
- Review and approval workflow


## 2. System Architecture

### Workflow Overview

1. User submits a Content Brief in Notion  
2. n8n triggers the automation pipeline  
3. AI generates:
   - Blog content
   - Social media captions
   - Newsletter draft
   - Visual prompt
4. Picsart generates an image using the visual prompt  
5. Data is stored back in Notion  
6. Review workflow is triggered automatically  
7. Approved content moves to publishing  


## 3. Database Structure (Notion)

### Content Briefs

- Name
- Brief ID
- Campaign Name
- Audience
- Goal
- Tone
- Keywords
- Blog Topic
- Content Status

### Generated Content

- Name
- Content ID
- Source Brief ID
- Blog Draft
- Social Captions
- Newsletter
- Visual Prompt
- Generated Image URL
- Approval Status
- Publish Status
- Reviewer Notes
- Visual Status


## 4. Workflow 1 — Content Generation Pipeline

### Key Steps

- Trigger from Notion
- Extract brief data
- Generate AI content
- Parse structured JSON output
- Generate image via Picsart
- Store output in Notion
- Update content status

### AI Processing

The system automatically generates:

- Blog content
- LinkedIn, Instagram, Twitter captions
- Newsletter draft
- Visual prompt for image generation

All outputs are structured in JSON format and parsed for automation.


## 5. Image Generation (Picsart)

- Input: Visual Prompt
- Process: AI-based image generation
- Output: Image URL
- Stored in Notion for review and tracking


## 6. Workflow 2 — Review & Approval Automation

### Stages

#### Stage 1 — Content Generated
- AI content and image are created
- Status set to Draft

#### Stage 2 — Review
- Content automatically moves to review
- Reviewer validates quality

#### Stage 3 — Approval
- Approved → Publish status updated
- Rejected → Sent back for revision


## 7. Workflow Logic Summary

| Stage            | Action                  |
|------------------|------------------------|
| New Brief        | Trigger automation     |
| AI Generation    | Create content         |
| Image Generation | Create visual          |
| Review           | Human validation       |
| Approved         | Move to publish        |
| Rejected         | Send for update        |


## 8. Features Implemented

- AI-powered content generation
- Automated image generation
- CRM-style tracking system
- Status-based workflow automation
- End-to-end pipeline automation
- No manual intervention required


## 9. Deliverables

### Lead Generation Workflow JSON
https://drive.google.com/file/d/1479mv7wz_zE1xIz0cCFpyM6xFawPzygh/view?usp=sharing

### Content Generation Workflow JSON
https://drive.google.com/file/d/1TAA9qHb04G6gBeeQXGbKVeCIcJao1ESh/view

### Notion Databases

Content Briefs  
https://www.notion.so/34b3b8197dee808abb35d85a81b2a435?v=34b3b8197dee809db1fa000c0902cabe

Generated Content  
https://www.notion.so/34b3b8197dee806eb2e8d944a0a625f0?v=34b3b8197dee80808d5e000c727c01ce

### Demo Video
https://drive.google.com/file/d/13lTh-bZyjm8GeVp4uO_CLwYAUx0K887c/view?usp=sharing


## 10. Final Outcome

This system:

- Automates content production
- Reduces manual effort
- Maintains a structured workflow
- Improves scalability
- Integrates AI with business automation


## 11. Conclusion

This project demonstrates how AI + No-Code Automation can be used to build a complete system that handles:

Input → Processing → Content Creation → Image Generation → Review → Publishing

in a fully automated and scalable manner.

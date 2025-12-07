---
publishDate: 2025-12-18T00:00:00Z
title: "FAQ: Can I Edit AI-Generated Diagrams Manually?"
excerpt: You are not locked into the AI's first draft. Learn how to edit AI diagrams using conversational prompts, direct code manipulation, and version control to get the perfect result.
image: ~/assets/images/blog/Can-edit-AI-Generated-diagrams-manually-faq2.png
category: Support & Resources
tags:
  - edit-ai-diagrams
  - diagram-customization
  - faq
  - d2-editing
  - workflow-tips
metadata:
  canonical: https://aidiagrammaker.com/blog/editing-and-customization
---


# Frequently Asked Questions (AI & Technical Functionality) #

## FAQ 2 ##

### 1. How does the AI generate diagrams from text? ###
It's a process that involves a field of AI called Natural Language Processing, or NLP. When you type a prompt, a Large Language Model (similar to the ones that power tools like ChatGPT) analyzes your sentence structure. It identifies the key nouns as potential objects or nodes in the diagram, and the verbs as the relationships or connectors between them. It then translates this understanding into a structured, declarative format (we use a language called D2) which is then rendered as the final visual diagram.

### 2. What kind of AI model powers AIDiagramMaker? ###
We use a combination of state-of-the-art, commercially available Large Language Models and our own proprietary models that have been fine-tuned specifically for the task of diagram generation. This hybrid approach allows us to leverage the broad linguistic understanding of the big models while also specializing in the specific nuances of creating diagrams from technical descriptions.

### 3. Does the AI learn from my diagrams? ###
No. We do not use your specific diagrams or prompts to train our core AI models. Your data is your own. We may analyze usage patterns in an aggregated and anonymized way to understand which features are popular and to improve the product, but the content of your diagrams is kept private.

### 4. Can I edit the AI-generated diagrams manually? ###
Yes, and this is a really important part of the workflow. The AI is there to give you a massive head start, but you are always in control. You can edit the diagram in a few ways. The easiest is to use a follow-up prompt, like "Change the color of that box to blue." You can also directly edit the underlying text-based definition of the diagram if you want that level of granular control.

### 5. How long does it take to generate a diagram? ###
It's usually very fast, typically just a few seconds. For very complex diagrams generated from a large codebase, it might take a little longer as the AI has more information to process, but for most text-based prompts, the result is nearly instant.

### 6. Can I undo or regenerate a diagram if I don’t like it? ###
Absolutely. If you don't like the first result, you can simply tweak your prompt and hit "regenerate" to try again. We also have a full version history, so you can always see your previous generations and roll back to an earlier version with a single click.

### 7. Does AIDiagramMaker support drag-and-drop editing? ###
While our primary focus is on generating diagrams from text and code, we understand that sometimes you just want to nudge something manually. We are actively exploring ways to integrate some limited, optional drag-and-drop functionality for fine-tuning, but the core of the experience will always be text-first.

### 8. Can I link shapes and nodes automatically? ###
Yes, this is a core part of what the AI does. When you describe a relationship, like "the API Gateway connects to the User Service," the AI automatically creates that link. You don't have to draw any lines yourself.

### 9. How can I add text or labels to diagrams? ###
You just include it in your prompt. For example, if you say "Show a box labeled 'Web Server' connected to another box labeled 'Database'," the AI will add those labels for you. You can also label the connectors themselves, for instance, "The server sends an 'SQL Query' to the database."

### 10. Does it support real-time collaboration? ###
Yes, our team plans are built for collaboration. Multiple team members can view a diagram, and we have systems in place to manage editing and see a history of all changes. While it's not quite a simultaneous, Google Docs-style editing experience at this moment, it is designed for a shared team workflow.

### 11. How does version history work? ###
Every time you generate or significantly modify a diagram and save it, we create a new version in the history log. This log shows you a timestamp and the user who made the change. You can click on any previous version to view it and, if you want, restore it as the current version. It's a bit like having a simplified git history for your visuals.

### 12. Can I integrate AIDiagramMaker with Notion, Figma, or Miro? ###
Direct, interactive integrations are on our roadmap. For now, the best way to use your diagrams in those tools is to export them as a high-quality SVG or PNG and then embed that image into your Notion page, Figma board, or Miro whiteboard.

### 13. Does it support API access? ###
Yes, we offer a developer API on our higher-tier plans. This allows you to programmatically generate diagrams and integrate our technology into your own applications or automated documentation workflows, like a CI/CD pipeline.

### 14. Can I use my own AI prompts? ###
Of course. That's the whole idea. The prompt canvas is a blank slate for you to describe your vision in your own words.

### 15. Is there an option to train the AI for custom outputs? ###
Not in an automated way at the user level, no. However, for our enterprise customers, we do offer services to create custom themes and styles to ensure that all generated diagrams match your company's specific branding guidelines.

### 16. Does it support different diagram styles or themes? ###
Yes. We have a selection of built-in themes that you can choose from to change the look and feel of your diagrams, from professional and muted to more modern and colorful. You can usually switch themes with a single click.

### 17. Can I generate diagrams in dark mode? ###
Yes. We have themes that are specifically designed for dark mode, which is something I know a lot of developers appreciate.

### 18. What file formats are supported for export? ###
We support export to SVG, which is great because it's a scalable vector format, as well as PNG for general use and PDF for including in documents.

### 19. Does AIDiagramMaker compress images or affect quality? ###
No, we aim for the highest possible quality. When you export to a format like PNG, we provide a high-resolution output. And because SVG is a vector format, its quality is effectively infinite; you can scale it to any size without losing clarity.

### 20. What browser is best for using AIDiagramMaker? ###
The application is built to work well on all modern, evergreen browsers. We generally recommend using the latest version of Google Chrome, Mozilla Firefox, or Safari for the best and most consistent experience.

# GenAI Research Summarizer

## Overview

AI-powered research paper summarization tool designed for pharmaceutical and chemistry research. Leverages Large Language Models (LLMs) to extract key findings, generate teaching-friendly summaries, and accelerate literature review workflows.

## Features

- **🤖 AI-Powered Summarization**: OpenAI/Gemini API integration for intelligent text analysis
- **📚 Teaching Mode**: Generate student-friendly explanations from complex research
- **🧪 Chemistry-Aware**: Domain-specific understanding of pharma/chemistry papers
- **📄 PDF Support**: Direct PDF text extraction and processing
- **⚡ Batch Processing**: Summarize multiple papers in one go
- **💾 Export Options**: Save summaries as Markdown files

## Technologies

- Python 3.10+
- OpenAI API (gpt-3.5-turbo / gpt-4)
- PyPDF2 for PDF extraction
- python-dotenv for configuration

## Use Cases

### Before (Manual Process)

- Read 50-page paper: **2 hours**
- Extract key findings: **30 minutes**
- Write summary: **30 minutes**
- **Total: 3 hours per paper**

### After (With This Tool)

- Upload PDF: **10 seconds**
- AI processing: **30 seconds**
- Get summary: **instant**
- **Total: 1 minute per paper** ⚡

## Quick Start

### 1. Install Dependencies

```bash
pip install -r requirements.txt

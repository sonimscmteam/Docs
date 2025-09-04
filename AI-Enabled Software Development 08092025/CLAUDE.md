# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Structure

This repository contains documentation and presentation materials for an AI-enabled software development training program:

- `ai_sw_dev_presentation.html` - Interactive HTML presentation covering AI-assisted development workflows
- `presenter_guide_ai_dev.md` - Comprehensive presenter's guide with detailed talking points and demo scripts

## Project Context

This is a documentation-focused repository for training materials on AI-enhanced software development workflows. The content focuses on:

1. **Parallel Development Strategy** - Using AI agents to work on multiple issues simultaneously while builds are running
2. **AI Agent Integration** - Leveraging tools like Claude Code, GeminiCLI, and CodexCLI for code analysis and generation  
3. **Build Optimization** - Batch building strategies using feature flags and conditional compilation
4. **Automated Testing** - AI-generated test suites and stress testing scenarios

## Key Architecture Concepts

The presentation materials demonstrate a productivity-focused workflow where developers can handle 5-8 issues per day instead of 2-3 by:
- Using AI for rapid issue analysis and fix generation
- Implementing parallel branch strategies for multiple simultaneous fixes
- Optimizing build cycles through batch processing
- Automating testing and code review processes

## Important Note on AI Tool References

The presentation materials contain examples using "claude-code" with command-line arguments (e.g., `claude-code analyze --issue 1234`). This is fictional syntax used for demonstration purposes. In reality:

- **Claude** works through conversational prompts, not CLI commands
- **Actual usage** involves providing context, logs, and requirements in natural language
- **Real workflow** would be: opening Claude, pasting logs/code, and asking for analysis or fixes
- **Other AI tools** mentioned (GeminiCLI, CodexCLI) may or may not exist as actual CLI tools

When working with this repository, understand that the "claude-code" examples represent the conceptual workflow of using AI assistance, not literal command syntax.

## Development Workflow

Since this is a documentation repository, typical development tasks involve:
- Updating presentation content in HTML format
- Maintaining the presenter guide with accurate examples and demo scripts
- Ensuring consistency between presentation slides and guide materials

The HTML presentation includes interactive navigation and can be opened directly in a web browser for training sessions.

## File Dependencies

- The HTML presentation is self-contained with embedded CSS and JavaScript
- The presenter guide includes extensive code examples and terminal commands for live demonstrations
- Both files reference Android/kernel development scenarios as practical examples
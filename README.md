# Comment Automation System

This repository contains the source code for the Comment Automation System, a project designed to automate comment replies across multiple platforms (YouTube, TikTok, Instagram) using AI.

## Features

- Modular architecture with separate services for each platform.
- Centralized configuration management through a Rails-based frontend.
- Customizable prompt templates for AI-generated replies.
- Logging of processed comments and replies.
- User authentication for secure access.

## System Components

### 1. Commenter Service (Ollama)

This service generates replies based on customized prompts and stores/retrieves training data.

### 2. Platform Services

Each platform has its own service responsible for:
- Fetching comments.
- Creating specialized prompts.
- Sending prompts to the commenter service.
- Posting generated replies.
- Logging processed comments and replies.

### 3. Frontend (Rails)

The frontend provides a user interface for managing configurations, prompt templates, and viewing logs of processed comments.

## Getting Started

### Prerequisites

- Ruby and Rails installed
- PostgreSQL database
- Git installed
- Docker and Docker Compose installed

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/comment-automation.git
cd comment-automation

# 🐝 Multi-Agent Blog Post Creation (Swarm Framework)

Welcome to the **Multi-Agent Blog Post Creation** project! This innovative notebook leverages OpenAI's [Swarm](https://github.com/openai/swarm) framework to orchestrate a team of AI agents—each with a specialized role—to collaboratively research, write, and edit high-quality blog articles with minimal human input.

## 🚀 Overview

This project demonstrates how multiple AI agents can work together in a pipeline to automate content creation. Each agent in the workflow is assigned a unique responsibility, ensuring a thorough, organized, and creative approach to blog post generation.

## 🧩 How It Works

1. **Admin Agent**: Kicks off the project, sets the topic, and manages the overall workflow.
2. **Planner Agent**: Structures the topic into an organized outline with clear sections.
3. **Researcher Agent**: Gathers rich, detailed content for each section.
4. **Writer Agent**: Crafts a well-written, engaging blog post using the research and outline.
5. **Editor Agent**: Polishes the final draft, ensuring clarity, correctness, and style.

The entire process is managed in a seamless pipeline, with each agent handing off to the next until the blog post is complete and saved as a markdown file.

## ✨ Features

- **Automated Workflow**: Minimal human intervention needed—just provide the topic!
- **Modular Agents**: Clearly defined responsibilities for each agent.
- **Extensible Design**: Easily add or modify agents for different writing tasks.
- **Markdown Output**: Blog posts are saved as markdown files, ready for publishing.

## 🛠️ Getting Started

### 1. Requirements

- Python 3
- [OpenAI API key](https://platform.openai.com/)
- [Swarm Framework](https://github.com/openai/swarm)

### 2. Installation

Clone this repo and install dependencies:
```bash
git clone https://github.com/rashedulalbab253/-Multi-agent-blog-post-creation_updated.git
cd -Multi-agent-blog-post-creation_updated
pip install git+https://github.com/openai/swarm.git
```

### 3. Usage

1. **Open the Jupyter Notebook**:  
   `Multi_agent_blog_post_creation_updated.ipynb`

2. **Set your OpenAI API Key**:  
   Replace or securely provide your API key in the notebook.

3. **Run the Notebook**:  
   - Provide a blog topic when prompted.
   - Watch as the agents collaborate to create and refine a detailed blog post.
   - Your finished article will be saved as a markdown file.

## 📂 Project Structure

- `Multi_agent_blog_post_creation_updated.ipynb` — The main notebook containing the workflow and agent logic.
- `README.md` — Project overview and instructions.

## 🌟 Example Topics

- The Future of Artificial Intelligence
- Difference Between Racism and Discrimination
- How Blockchain is Transforming Finance

## 🤖 About Swarm

Swarm is an experimental framework by OpenAI for building collaborative, multi-agent AI systems. Learn more: [https://github.com/openai/swarm](https://github.com/openai/swarm)


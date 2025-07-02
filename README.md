# High-Performance LLM Prompts Collection

![GitHub](https://img.shields.io/github/license/mihazs/awesome-llm-prompts?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/mihazs/awesome-llm-prompts?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/mihazs/awesome-llm-prompts?style=for-the-badge)

A curated collection of professional-grade **custom instructions (prompts)** designed to transform Large Language Models (LLMs) like GPT-4, Llama, Claude, and others into high-performance agents with well-defined personas and consistent behaviors.

## 🚀 About This Project

This repository is a centralized resource for advanced **prompt engineering**. The goal is to move beyond simple question-and-answer interactions by providing universal instructions that define an AI agent's behavioral architecture. Instead of expecting the AI to guess the best approach, we explicitly instruct it, leading to greater reliability, consistency, and efficiency.

If you work with tools like **RooCode**, **Cursor**, **CLine**, or any other platform that supports custom instructions, this collection is for you.

### SEO Keywords
*AI Prompts, Prompt Engineering, Custom Instructions, LLM Prompts, ChatGPT Prompts, RooCode Prompts, Prompt Library, AI Agents, AI Persona, High-Performance AI.*

---

## ✨ Features

* **Specialized Personas:** Prompts that establish robust personas, such as the "Metacognitive Architect," an agent that plans, executes, and learns autonomously.
* **Tool-Specific Focus:** Instructions optimized for interacting with external tools, like `context-portal` (ConPort), turning the AI into a smart interface for other APIs.
* **YAML Structure:** Prompts are structured in YAML for clarity, maintainability, and ease of use.
* **Best Practices Built-in:** Each prompt is the result of an iterative process of testing and refinement, fixing common failures like confirmation loops, context loss, and command misinterpretation.
* **Portability:** While inspired by specific tools, the underlying principles can be adapted for various AI platforms.

---

## 🛠️ How to Use These Prompts (Installation Guide)

Using a prompt from this collection is straightforward. The main goal is to copy the prompt's content and paste it into the "Custom Instructions" field of your AI tool.

**Example Installation for RooCode:**

1.  **Choose a Prompt:** Navigate the `prompts/` folder in this repository and select the persona/instruction that best fits your needs (e.g., `metacognitive_architect_v9.yml`).
2.  **Copy the Content:** Open the `.yml` file and copy its entire content to your clipboard (Ctrl+C or Cmd+C).
3.  **Open RooCode Settings:** In your code editor (like VS Code), access the RooCode extension settings.
4.  **Find Custom Instructions:** Look for the field designated for custom instructions. Typically, there is a global field ("Custom Instructions for All Modes") and specific fields for each mode (`code`, `orchestrator`, etc.).
5.  **Paste the Prompt:** Paste the copied content into the desired instructions field. For universal behavior like the "Metacognitive Architect," paste it into the global field.

    ![RooCode Settings Example](https://github.com/user-attachments/assets/08a65666-0a4e-43d1-a4f4-08a2917e7f4d)

6.  **Save and Test:** Save the settings. From your next interaction, the AI agent will adopt the new persona and follow the prompt's directives. Test it with a complex task to see the new behavior in action.

---

## 📚 Prompt Library

| Prompt Name                               | Description                                                                                                                                                                                                | File Path                                                                     |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Metacognitive Architect (v1.0)** | Transforms the AI into a schema-driven, autonomous playbook executor, ideal for complex state management and data migration tasks. Uses `context-portal` as its central memory. | [`prompts/metacognitive_architect.yml`](./prompts/metacognitive/universal_custom_code.yml) |
| *... (Add more prompts here)* | *...* | *...* |

---

## 🤝 How to Contribute

Contributions are the heart of this project! If you have developed, tested, and refined a high-performance prompt, please share it with the community.

**Contribution Process:**

1.  **Fork the Repository:** Create your own fork of this project.
2.  **Create a Branch:** Create a new branch for your prompt (`git checkout -b feature/my-new-prompt`).
3.  **Add Your Prompt:** Add your `.yml` file to the `prompts/` directory. Please follow the structure and comments of existing prompts for consistency.
4.  **Update the README:** Add an entry to the "Prompt Library" table describing your prompt and the problem it solves.
5.  **Create a Pull Request:** Open a Pull Request detailing your contribution, the tests you performed, and why it is useful.

---

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more details.

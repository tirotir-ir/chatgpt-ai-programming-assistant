# ChatGPT: AI Programming Assistant


## Overview

**ChatGPT: AI Programming Assistant** is a powerful VS Code extension that leverages OpenAI's models to assist developers in generating, optimizing, debugging, and explaining code. It offers real-time AI pair programming, interactive tutorials, and a customizable prompt cheat sheet featuring 500 examples across various programming languages. With its intuitive features, this extension provides a seamless coding experience, enhancing productivity and fostering learning for developers of all skill levels.

## Features

- **Generate code** based on user input.
- **Write unit tests** for existing code.
- **Optimize code snippets**.
- **Debug code** with AI assistance.
- **Explain differences** between code snippets.
- **Chat with GPT** for direct interaction.
- **AI Pair Programming**: Provides real-time suggestions and answers based on the current code or task.
- **Interactive Learning**: Handles requests for step-by-step tutorials based on user input.
- **Comprehensive Prompt Cheat Sheet**: Offers 500 prompts for various programming languages, organized for easy access and quick suggestions as users type.

## Prompt Areas

The extension includes a total of **500 prompt examples** across the following:
- **100 Python Prompts**: `pyprompts`
- **100 HTML Prompts**: `htmlPrompts`
- **100 JavaScript Prompts**: `jsprompts`
- **100 CSS Prompts**: `cssPrompts`
- **100 Other Languages Prompts**: `otherPrompts`

## Configuration

### API Key

To use the OpenAI features, you need to set your OpenAI API key in the extension settings:

1. Open the Command Palette (Ctrl+Shift+P) in Visual Studio Code.
2. Search for and select **Preferences: Open Settings (JSON)**.
3. Add the following lines to your settings:

```json
"gptCodeAssistant.openaiApiKey": "YOUR_OPENAI_API_KEY", // Replace YOUR_OPENAI_API_KEY with your actual OpenAI API key.
"gptCodeAssistant.maxTokens": 300, // Adjust the maximum number of tokens
"gptCodeAssistant.model": "gpt-4" // Choose the GPT model (e.g., gpt-3.5-turbo,gpt-3.5-turbo-16k, gpt-4, gpt-4-32k)
```
These settings allow you to customize the GPT model used and the maximum number of tokens for each response.

## Key Bindings

The following commands have been assigned shortcut keys for better productivity:

- **Generate Code**: `Ctrl+Alt+G`
- **Generate Unit Test**: `Ctrl+Alt+U`
- **Optimize Code**: `Ctrl+Alt+O`
- **Debug Code**: `Ctrl+Alt+D`
- **Explain Code Differences**: `Ctrl+Alt+E`
- **Chat with GPT**: `Ctrl+Alt+C`
- **AI Pair Programming**: `Ctrl+Alt+P`
- **Interactive Learning**: `Ctrl+Alt+L`

You can customize these key bindings in the `keybindings.json` file in VS Code.

## Commands

- **Generate Code (Ctrl+Alt+G)**: Generates code based on the selected text.
- **Generate Unit Test (Ctrl+Alt+U)**: Generates a unit test for the selected code.
- **Optimize Code (Ctrl+Alt+O)**: Optimizes the selected code.
- **Debug Code with AI (Ctrl+Alt+D)**: Debugs the selected code with AI assistance.
- **Explain Code Differences (Ctrl+Alt+E)**: Explains the difference between two code snippets.
- **Chat with GPT (Ctrl+Alt+C)**: Chat directly with GPT for interactive Q&A or coding help.
- **Interactive Learning Mode (Ctrl+Alt+L)**: Provides tutorials on various coding topics based on user input.


## Usage

1. Select the code snippet you want to work with.
2. Use the command palette (`Ctrl+Shift+P`) or the assigned shortcut keys to run any ChatGPT: AI Programming Assistant command.

# Usage Instructions

1. **Select the Code Snippet You Want to Work With**
   - **Example**: Highlight a function in your code that you want to optimize. For instance, if you have the following JavaScript function:
     ```javascript
     function add(a, b) {
         return a + b;
     }
     ```

2. **Use the Command Palette or Assigned Shortcut Keys**
   - **Example 1**: Open the Command Palette by pressing `Ctrl+Shift+P`, then type `ChatGPT: AI Programming Assistant` to see the available commands. Choose `Optimize Code` to enhance the selected function.
   - **Example 2**: Alternatively, use the assigned shortcut key for the command. For instance, if you want to generate a unit test for the selected code, simply press `Ctrl+Alt+U` after highlighting your function.

### Additional Examples

- **Select Code for Debugging**:
   - Highlight a piece of code you suspect contains an error. For example:
     ```python
     def divide(x, y):
         return x / y
     ```
   - Press `Ctrl+Alt+D` to use the AI to debug the highlighted code.

- **Generate Code from Comments**:
   - If you have a comment describing what you want to implement, such as `// Create a function to calculate the factorial`, select that comment.
   - Then use `Ctrl+Alt+C` to generate the corresponding code.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenAI for providing the API.
- Visual Studio Code for an excellent code editor.

[GitHub Repository](https://github.com/tirotir-ir/chatgpt-ai-programming-assistant.git)

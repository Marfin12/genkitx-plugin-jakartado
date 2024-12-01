# Genkit Jakartado Plugin Template

## Description
The Genkit Jakartado Plugin is a powerful tool designed to integrate generative AI capabilities into your projects especially on basic algebraic mathematic calculation. This plugin leverages the GeminiPro Model from Genkit-AI, providing flexible and interactive AI-powered responses. It includes predefined examples and allows developers to fine-tune parameters for their specific use cases.

This template showcases a practical implementation for teaching algebraic math concepts interactively, making it an ideal foundation for educational tools or tutoring applications.

## Example Use Case
The plugin can be used to teach algebra to students by:

Explaining algebraic concepts (e.g., variables, coefficients, and constants).
Demonstrating basic operations like addition, subtraction, multiplication, and division.
Solving algebraic equations step-by-step interactively.

### Example Interaction:
Input (User): "What is the result of 3𝑥 + 5𝑥 3x+5x?"

Output (AI): "The result is 8𝑥, since 3𝑥 and 5x are like terms, and their coefficients can be added."

Input (User): "Solve for 𝑥 in the equation 2x+3=7."

Output (AI):
"Step 1: Subtract 3 from both sides: 2𝑥 4"
"Step 2: Divide both sides by 2: 𝑥=2"

## Installation
To use this plugin in your project:

Install the required dependencies:

bash
Copy code
npm install @genkit-ai/ai @genkit-ai/googleai
Clone this repository:

bash
Copy code
git clone https://github.com/your-repo/genkit-jakartado-plugin.git
Import and configure the plugin in your project:

javascript
Copy code
import { retrieveResponse } from "./path-to-plugin";

const response = await retrieveResponse({
    prompt: "Solve 2x + 3 = 7",
    temperature: 0.1,
    maxOutputTokens: 500,
    topK: 1,
    topP: 0,
}, {
    apiKey: "your-api-key",
});

console.log(response);

License : Apache 2.0
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

To integrate the plugin into your project, follow the steps below:

1. Install the plugin via npm:
   ```bash
   npm install genkitx-plugin-jakartado@0.0.5
      
2. Add the plugin to your AI configuration:
   ```bash
   import { devFestAlgebric } from "genkitx-plugin-jakartado"
   plugins: [
     // ... your previous A.I plugins
     devFestAlgebric({ apiKey: "your-api-key" })
   ],


License : Apache 2.0

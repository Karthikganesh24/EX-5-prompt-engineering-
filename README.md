# EXP 5: Comparative Analysis of Naïve Prompting versus Basic Prompting Using ChatGPT Across Various Test Scenarios
# Aim: 
To test how ChatGPT responds to naïve prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios, analyzing the quality, accuracy, and depth of the generated responses.

# Algorithm: 
Define the Two Prompt Types:
Naïve Prompts: Broad, vague, or open-ended prompts with little specificity.
Basic Prompts: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

# OUTPUT

# 1. Straightforward Prompting
### Naïve Prompt:
Tell me about AI

### Naïve Output:
“AI stands for Artificial Intelligence. It is the simulation of human intelligence in machines. It is used in many areas like robotics, automation, and data analysis.”

### Basic Prompt:
Explain Artificial Intelligence in simple terms with real-life examples.

### Basic Output:
“Artificial Intelligence (AI) means machines that can think or make decisions like humans. For example, voice assistants like Siri or Alexa use AI to understand what you say and respond. Another example is Google Maps, which uses AI to find the fastest route.”

### Conclusion:
The basic prompt resulted in a clearer, more relatable explanation with practical examples. The naïve prompt gave a vague and general definition.

# 2. Chain-of-Thought Prompting
### Naïve Prompt:
What is 87 + 54 × 2?

### Naïve Output:
195

### Basic Prompt:
Solve the problem 87 + 54 × 2 step-by-step, explaining each step of the calculation.

### Basic Output:
“First, apply the order of operations (PEMDAS).
Step 1: Multiply 54 × 2 = 108
Step 2: Add 87 + 108 = 195
Final Answer: 195”

### Conclusion:
The basic prompt encourages step-by-step thinking and explanation. The naïve prompt provides only the final answer without any reasoning.

# 3. Zero-Shot Prompting
### Naïve Prompt:
Translate to French

### Naïve Output:
I'm sorry, but there is no sentence to translate.

### Basic Prompt:
Translate the sentence "I am going to the market" into French.

### Basic Output:
Je vais au marché.

### Conclusion:
The naïve prompt lacked context and failed. The basic prompt gave a clear input and got the correct translation.

# 4. Few-Shot Prompting
### Naïve Prompt:
Write a poem

### Naïve Output:
“The stars are bright, the sky is wide,
I walk alone, with none beside…”

### Basic Prompt:
Write a 4-line poem about friendship, using an ABAB rhyme scheme. Example 1: "Through thick and thin we always stay (A) With every laugh and every tear (B) You brighten up my cloudy day (A) A bond so strong, forever near (B)" Now write your own.

### Basic Output:
“A friend is there through storm and sun (A)
They lift you up when you are low (B)
With them, the journey’s always fun (A)
Together, stronger we will grow (B)”

### Conclusion:
The basic prompt gave the model structure and examples, resulting in a focused and stylistically consistent poem. The naïve prompt lacked direction and context.

# Overall Conclusion:
Across all four types of prompts, basic prompting consistently led to higher quality, more relevant, and more accurate outputs. Providing clear instructions, structure, and context helps ChatGPT respond intelligently and appropriately, especially in reasoning or creative tasks.



# RESULT: 
The prompt for the above said problem executed successfully

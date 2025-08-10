# Prompt Engineering Techniques

## Basic Prompting

### One-shot Prompting
One-shot prompting is when you give one example with the prompting that you are sending the LLM. This helps the model understand the expected format or reasoning pattern.

Example:
```
Input: Translate "hello" to French
Output: bonjour

Now translate "goodbye" to French
```

### Multishot Prompting
Multishot prompting is when you give multiple examples with the prompting that you are sending the LLM. This provides more context and patterns for the model to learn from.

Example:
```
Input: Translate "hello" to French
Output: bonjour

Input: Translate "thank you" to French
Output: merci

Now translate "goodbye" to French
```

## Advanced Techniques

### Chain-of-Thought (CoT)
Encourages the model to explain its reasoning step by step, leading to more accurate responses for complex tasks.

### Few-Shot Chain-of-Thought
Combines few-shot learning with chain-of-thought reasoning.

### Zero-Shot Prompting
Asking the model to perform a task without any examples.

### Role Prompting
Assigning a specific role to the LLM to frame its responses.

## Best Practices

- Be specific and clear
- Provide context
- Use delimiters for different parts of your prompt
- Specify the desired output format
- Start with simpler prompts and iterate
# AI-Agent-
This Repository Contains projects on AI agents

Quasi Agent-
This  program uses sequential prompts to generate any Python function based on user input. The program should:

First Prompt:

Ask the user what function they want to create
Ask the LLM to write a basic Python function based on the user’s description
Store the response for use in subsequent prompts
Parse the response to separate the code from the commentary by the LLM
Second Prompt:

Pass the code generated from the first prompt
Ask the LLM to add comprehensive documentation including:
Function description
Parameter descriptions
Return value description
Example usage
Edge cases
Third Prompt:

Pass the documented code generated from the second prompt
Ask the LLM to add test cases using Python’s unittest framework
Tests should cover:
Basic functionality
Edge cases
Error cases
Various input scenarios
Requirements:

Use the LiteLLM library
Maintain conversation context between prompts
Print each step of the development process

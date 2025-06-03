# genai-testing
As part of the MLOps course at the University of St. Gallen, we prepared a demo to explore methods for testing Generative AI (GenAI) systems. For this, we utilized Promptfoo and LangTest to demonstrate how to evaluate and validate large language models (LLMs).

### Promptfoo 
We used Promptfoo to test various LLMs through a configurable evaluation setup. Testing is driven by a configuration file (promptfooconfig.yaml) where different test cases and prompts are defined.

The official documentation provides guidance on how to install and run Promptfoo:
👉 [Promptfoo Getting Started](https://www.promptfoo.dev/docs/getting-started/)

To run the tests:
Define your prompts and test cases in promptfooconfig.yaml.
Run the evaluation with: promptfoo eval

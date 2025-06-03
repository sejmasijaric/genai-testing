# Demo Presentation - Testing of GenAI (Promptfoo and LangTest)
As part of the MLOps course at the University of St. Gallen, we prepared a demo to explore methods for testing Generative AI (GenAI) systems. For this, we utilized Promptfoo and LangTest to demonstrate how to evaluate and validate large language models (LLMs).

### Promptfoo 
We used Promptfoo to test various LLMs through a configurable evaluation setup. Testing is driven by a configuration file (promptfooconfig.yaml) where different test cases and prompts are defined.

The official documentation provides guidance on how to install and run Promptfoo:
👉 [Promptfoo Getting Started](https://www.promptfoo.dev/docs/getting-started/)

To run the tests:
Define your prompts and test cases in promptfooconfig.yaml.
Run the evaluation with: promptfoo eval

You can find example test cases in the prompts folder of this project. These can be copied or modified for your own use cases and inserted into the configuration file.

### LangTest
LangTest allows for automated generation of test cases based on configurable evaluation metrics. It allows many dimensions to be tested, among others robustness, fairness, bias, grammar, toxicity, and other. For this demo, we used LangTest to test the robustness of a fine-tuned Bert model, hosted on huggingface. We configured out test cases and ran the tests.

For this demo, we used only two prompts to test the model, since our primary goal was to see how the tool works, and what the output is.

The whole code can be found in the bert-demo-langtest.ipynb file. Therefore, to run the tests, simply run the whole notebook. 

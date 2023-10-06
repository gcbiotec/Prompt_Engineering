# Prompt_Engineering
I'll put here some notebooks about Prompt Engineering in ChatGPT, following the guides of DeepLearningAI courses.
Although using LLMs became popular with the graphic interface, as developers we need to use the API calls to unleash its real power. We can divide LLMs into Base LLMs or Instruction Tuned LLMs.

The Base LLMs were trained to predict the next word based on text training data, often trained on a large amount of data from the internet and other sources to figure out the next most likely word to follow.      

In contrast, the Instruction Tuned LLMs are more specific to the task. Typically they start as Base LLMs and are further trained with inputs and outputs in a process called RLHF (Reinforcement Learning with Human Feedback).

We should follow some principles to be successful with our prompts.
Be clear and specific; That doesn’t mean to be short, the more descriptive, the better. We can also use delimiters to clearly indicate distinct parts of the input. It’s important to avoid Prompt Injections. These can represent a serious security issue, since a user, let's say your client, could try to fool the Chat system with inputs like “forget what’s written before”. We could use a strategy to ask for steps or even the few-shot approach that uses a given example of conversation.
Break down the prompt to give time to the model to think; for example, we can give the steps we want the model to follow in order to complete the task. We can even try to evaluate a given resolution and compare the model’s answer and check if it’s right or not. 


Another important aspect of LLMs is the term we call Hallucinations. If we ask the model about a fictitious company or product, for example, it will make up the information. Hallucination in large language models (LLMs) refers to the generation of text that is incorrect, nonsensical, or detached from reality. This can happen for a variety of reasons, including:
Lack of context: LLMs are trained on massive datasets of text and code, but they can still struggle to understand the context of a specific prompt or query. This can lead to hallucinations, such as generating text that is irrelevant to the prompt or that makes claims that are not supported by evidence.
Ambiguity: LLMs are also susceptible to hallucinations when given ambiguous prompts. For example, if you ask an LLM to write a story about a "talking dog," it may generate a story about a dog that can literally speak human language, or it may generate a story about a dog that communicates with its owner through telepathy.
Bias: LLMs are trained on data that reflects the real world, which means they can also reflect the biases that exist in the real world. This can lead to hallucinations that are offensive, harmful, or misleading.


There are a number of things that can be done to mitigate the risk of LLM hallucinations, such as:
Providing LLMs with as much context as possible.
Using clear and unambiguous prompts.
Being aware of the biases that may be present in LLMs.
Evaluating the text that LLMs generate carefully and verifying the information they provide before using it.    


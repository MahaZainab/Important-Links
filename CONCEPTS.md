# Important concepts:
|Sr.|Concept|Link|
|---|-------|----|
|1  |CoreQA |https://arxiv.org/pdf/2501.03447|
|2  | HAICOSYSTEM | https://arxiv.org/pdf/2409.16427 |
|3 |Diagram, 1. Add a diagram of methodology by just drawing blocks, like Figue 1 of this paper here. The flow can be: 1. QA pair and relevant examples by Tf-IDF as CoT --> 2. LLM prompt to generate answer  (Refer to the prompt in appendix. We need to give system prompt for both CodeQA and CS1QA) ---> 3. LLM as Judge to assess answer

2. A small example of an image like Figure 3 or 5 of the paper would be good. The image in our case could align to our methodology: 1. QA pair and relevant examples by Tf-IDF as CoT  --> 2. LLM prompt to generate answer   —->3.  LLM as Judge output and scores.
|[Link](https://aclanthology.org/2023.eacl-main.125.pdf)|

## Multi-agent Debate(Debate):
Typically MAD consist of three steps:
1. response generation: Each agent produces its initial solution based upon its unique perspective
Debate: Agents debate to indentify logical inconsistencies or knowledge gap
3. Consensus Building: where consensus is determined by majority voting or a judge agent.

It is also notable that if we want to enhance the reasoning capabilities of MAD we can assign different roles to agents, which will enable the agents to debate from various perspectives.

We can also do this in RQ5: Multipersona, which  incorporates an affirmative agent(agnel) and a negative agent presenting their agents to the judge, which ultimately determine the final solution.
This is 
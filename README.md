# Zytron Evals
Evaluations comparing multi-agent collaboration to individual agents. 

## Install

```bash
$ pip3 install zytron-eval
```




# License
MIT


# Citation
Please cite zytron in your paper or your project if you found it beneficial in any way! Appreciate you.

```bibtex
@misc{zytron,
  author = {OpenAgents AI},
  title = {{Zytron: The Multi-Agent Collaboration Framework}},
  howpublished = {\url{https://github.com/OpenAgentsAI}},
  year = {2025},
  note = {Accessed: Date}
}
```

# Evals
- ARC (AI2 Reasoning Challenge)
- HellaSwag
- Multiverse Math
- MMLU
- GLUE
- SuperGPU
- [HumanEval: ](https://paperswithcode.com/sota/code-generation-on-humaneval)
- MBPP
- SWE-BENCH

# Evals to make

## Math
- [x] [GSM8K](https://huggingface.co/datasets/openai/gsm8k)

[ ] MATH

## Code
[ ] HumanEval

[ ] MBPP 

[ ] Natural2Code

[ ] MBPP (early)

[ ] SWE-bench

## Commonsense Reasoning
[ ] ARC (AI2 Reasoning Challenge)

[ ] HellaSwag

[ ] Winogrande

[ ] PIQA

[ ] SIQA

[ ] OpenbookQA

[ ] CommonsenseQA

## Question Answering - World Knowledge
[ ] WebQuestions

[ ] NaturalQuestions

[ ] TriviaQA

[ ] ComplexWebQuestions

[ ] WebQuestionsSP

[ ] SearchQA

[ ] HotpotQA

[ ] DROP

[ ] WikiHop

[ ] QAngaroo

[ ] Multi

[ ] GLUE (early)

[ ] SuperGLUE

## Reading Comprehension

[ ] BoolQ

[ ] QuAC

[ ] DROP

## Aggregated

[ ] MMLU

[ ] HELM

[ ] BBH

[ ] AGI Eval 

## Multi-Agent

[ ] ChatBot Arena

[ ] MT Bench



# Metrics

[ ] Task accomplished y/n

[ ] Task quality 1-5

[ ] was a tool used y/n
   [ ] which tool
   [ ] how was it used
   [ ] were tools called in the right order
   [ ] were the tools used correctly? Did the environment change?
   [ ] Did the agent output match the expected reference output?

[ ] Compute load

[ ] Average Latency (s)
    "Latency: we measure the latency by timing each request to the endpoint ignoring the function document preprocessing time."

[ ] Model size needed (Small, Medium, Large)
[ ] Model type needed (LM, VLM, predictive, point cloud, NeRF/Splat)
[ ] Number of trials to acceptable performance
[ ] Number of trials to best performance

# References

[1]Functional Benchmarks for Robust Evaluation of Reasoning Performance, and the Reasoning Gap (https://arxiv.org/html/2402.19450v1) Code (https://github.com/consequentai/fneval/)

[2]explanation of metrics (https://gorilla.cs.berkeley.edu/blogs/8_berkeley_function_calling_leaderboard.html)

[3] tool use benchmarks (https://langchain-ai.github.io/langchain-benchmarks/notebooks/tool_usage/intro.html?ref=blog.langchain.dev) (https://blog.langchain.dev/benchmarking-agent-tool-use/)

[4] Blog on evaluating LLM apps (https://humanloop.com/blog/evaluating-llm-apps)

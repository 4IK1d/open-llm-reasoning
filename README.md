# open-llm-reasoning
A repo for trail and error on reasoning with open llm(usually not that big, but efficient)

Following categoritions in the awesome survey paper<sup>[1]</sup>, we try to verify and enhance reasoning ability of flowerful open LLMs.

## Data

We chose 3 domains of reasoning and their benchmarks as our test, and utilize zero-shot or training process of given paper to test the raasoning ability of open LLMs. 



|     Reasoning Skills      | Benchmarks                                                   |
| :-----------------------: | ------------------------------------------------------------ |
| **Commonsense Reasoning** | [CommonsenseQA](https://aclanthology.org/N19-1421/), [StrategyQA](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00370/100680/Did-Aristotle-Use-a-Laptop-A-Question-Answering), [ARC](https://arxiv.org/abs/1803.05457), [SayCan](https://arxiv.org/abs/2204.01691), [BoolQA](https://aclanthology.org/N19-1300/), [HotpotQA](https://aclanthology.org/D18-1259/), [OpenBookQA](https://aclanthology.org/D18-1260/), [PIQA](https://yonatanbisk.com/piqa/), [WikiWhy](https://arxiv.org/abs/2210.12152) |
|  **Symbolic Reasoning**   | [Last Letter Concatenation](https://arxiv.org/abs/2201.11903), [Coin Flip](https://arxiv.org/abs/2201.11903), Reverse List |
|   **Logical Reasoning**   | [ProofWriter](https://arxiv.org/abs/2012.13048), [EntailmentBank](https://arxiv.org/abs/2104.08661), [RuleTaker](https://www.ijcai.org/proceedings/2020/537), [CLUTRR](https://aclanthology.org/D19-1458/) |
<!-- | **Multimodal Reasoning**  | [SCIENCEQA](https://scienceqa.github.io/)                    |
|        **Others**         | [BIG-bench](https://doi.org/10.48550/arXiv.2206.04615), [SCAN](http://proceedings.mlr.press/v80/lake18a.html), [Chain-of-Thought Hub](https://arxiv.org/abs/2305.17306) |-->
<!-- | **Arithmetic Reasoning**  | [GSM8K](https://arxiv.org/abs/2110.14168), [SVAMP](https://aclanthology.org/2021.naacl-main.168), [ASDiv](https://aclanthology.org/2020.acl-main.92/), [AQuA-RAT](https://aclanthology.org/P17-1015/), [MAWPS](https://aclanthology.org/N16-1136/), [AddSub](https://aclanthology.org/D14-1058/), [MultiArith](https://aclanthology.org/D15-1202/), [SingleEq](https://aclanthology.org/Q15-1042/), [SingleOp]( https://doi.org/10.1162/tacl_a_00118) | -->

## Methods

We try to utilize methods mentioned in thoese corresponing domains, such as CoT for commensense. Mainly focus on models enhanced by utilizing `Code Interpreter` or `Tool Learning`.

## Models

Context length is a key primer of methods rooted in prompt learning, such as CoT or ICL. Thus, we will try to test more on open LLM declaimed with large context windows in addition to those famous SOTA(or previous SOTA).



# Awesome Reference
1. [zjunlp/Prompt4ReasoningPapers](https://github.com/zjunlp/Prompt4ReasoningPapers#self-optimization)

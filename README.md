<div align="center">

# Guodong Liu

**Graduate student · Northeast Normal University**

*LLM representation geometry · Multi-agent learning · Reproducible AI research*

</div>

I study **when structural assumptions about language models translate into reliable behavior**—and when apparently better results disappear under stronger controls. My work centers on carefully designed experiments, transparent comparisons, and identifying the boundaries of what a method can actually establish.

## Current research

Two **independent, ongoing** research projects. Their repositories and manuscripts are private while experiments are in progress.

### OrbitFlow — Representation geometry & identifiability

Investigating which geometric relationships between LLM representations are functionally meaningful, and under what conditions structure-aware alignment or adaptation preserves behavior. The emphasis is on identifiability, appropriate low-rank and transformation baselines, and diagnosing cases where alignment does not transfer.

### SynScale — Heterogeneous multi-agent LLM systems

Studying when differently specialized language-model agents provide genuine complementary value. Experiments focus on distinguishing cooperation from extra inference compute, repeated sampling, or stronger selection, with matched-budget baselines and explicit analysis of failure cases.

## Public research artifacts

| Repository | What you can inspect |
| --- | --- |
| **[Neurosymbolic Reasoning](https://github.com/KQYaili/neurosymbolic-reasoning)** | PyTorch experiments on discrete structure, permutation equivariance, and relational LLM post-training; controlled LoRA ablations and out-of-distribution evaluation. |
| **[VPO Notebooks](https://github.com/KQYaili/vpo-notebooks)** | Exploratory Jupyter notebooks on vector policy optimization, advantage estimation, and small-scale reinforcement-learning experiments. |

## How I approach research

- **Falsifiable questions first.** A method should be evaluated against plausible simpler explanations.
- **Matched comparisons.** Control for model capacity, inference/training compute, and selection procedures wherever possible.
- **Reproducibility.** Use documented configurations, checkpoints, ablations, and multiple seeds when the experiment warrants them.
- **Negative results matter.** Failure boundaries are often as informative as positive gains.

**Tools and methods:** Python · PyTorch · Transformers / PEFT · LoRA · LLM evaluation · experimental analysis

## Contact

I welcome research discussions and collaborations related to representation learning, post-training, and reliable agent systems.

**Email:** [513923907@qq.com](mailto:513923907@qq.com)

<sub>Research descriptions reflect ongoing work; publication and code releases will be linked here when available.</sub>

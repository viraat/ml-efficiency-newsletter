# ⭐ What happened in ML Efficiency in March 2023? ⭐

Hi #ml-efficiency! This is the first edition of the community newsletter for ml-efficiency in C4AI. We will cover interesting papers, tools, discussions in the community, and upcoming events! 

## Interesting papers and Blog posts:
📰 [Unmasked Teacher: Towards Training-Efficient Video Foundation Models](https://arxiv.org/abs/2303.16058)
This paper proposes an efficient method for training Video Foundation Models (VFMs) by selectively aligning unmasked tokens with Image Foundation Models (IFMs). 

📰 [High-throughput Generative Inference of Large Language Models with a Single GPU](https://arxiv.org/abs/2303.06865)
FlexGen enables high-throughput generation of LLMs on a single commodity GPU by flexibly aggregating memory and computation from the GPU, CPU, and disk.

📰 [Hyena Hierarchy: Towards Larger Convolutional Language Models](https://arxiv.org/abs/2302.10866)
Hyena is a subquadratic drop-in replacement for attention in Transformers that interleaves implicitly parametrized long convolutions and data-controlled gating.

📰 [LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/abs/2208.07339v2)
This paper proposes a two-part quantization procedure called LLM.int8() for large language models that reduces GPU memory requirements for inference by half while retaining full precision performance. Bonus: Watch Tim Dettmers C4AI talk [here](https://www.youtube.com/watch?v=jyOqtw4ry2w). Code is [here](https://paperswithcode.com/paper/llm-int8-8-bit-matrix-multiplication-for)

📰 [CoLT5: Faster Long-Range Transformers with Conditional Computation]https://arxiv.org/abs/2303.09752
CoLT5 is a Transformer model that uses conditional computation to focus more on important tokens in feedforward and attention layers, allowing for more efficient processing of long documents. 

📝 [Modular Deep Learning](https://www.ruder.io/modular-deep-learning/) ([Summary Tweet](https://twitter.com/seb_ruder/status/1628721434162765827))
Modularity separates knowledge and reasoning abilities from domain and task-specific capabilities, enabling extension to new settings and augmenting with new abilities. Bonus: Watch Jonas Pfeiffer’s C4AI talk [here](https://www.youtube.com/watch?v=3ycETDjVzOQ).

## Tool Spotlight:
🌼 [Flower](https://flower.dev/docs/tutorial/Flower-0-What-is-FL.html): Flower is a friendly federated learning framework. Their docs are a great introduction to Federated Learning.

## Repo spotlight:
🦙 [Llama.cpp](https://github.com/ggerganov/llama.cpp): The main goal of this repo is to run the LLaMa model using 4-bit quantization on a MacBook. Bonus: [This](https://twitter.com/jeremyphoward/status/1642726595436883969) great thread from Jeremy Howard on how `mmap` enables this!

## Upcoming events:
🤝 We will have our first reading group on <t:1681491600:F>. We will be starting with the theme of Knowledge Distillation and the paper: Model Compression by Caruana et. al. https://www.cs.cornell.edu/~caruana/compression.kdd06.pdf  

Thank you for reading the first edition of the C4AI ML Efficiency newsletter! We'd love to hear your feedback and suggestions! Ideally, we’d like this all to fit in a single discord message, but we run into the 2000 character limit pretty quickly.

Your contributions make up the bulk of this newsletter so please keep sharing the knowledge and spreading the love! ❤️

# 各类模型学习

## Large model

**Mu Li paper reading**

[https://fazzie-key.cool/2023/02/21/MLsys/]()

## Large model training & paper

* Data Parallel(数据并行)
* Distributed Data Parallel(分布式数据并行)
  * [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://arxiv.org/abs/2006.15704)
* Mix precise Training(混合精度训练)
  * [Mix precise Training](https://arxiv.org/abs/1710.03740)
* Zero Optimizer(零冗余优化器)
  * [ZeRO-Infinity: Breaking the GPU Memory Wall for Extreme Scale Deep Learning](https://arxiv.org/abs/2104.07857)
* Tensor Parallel(张量并行)
  * 1D并行:[Megatron-LM](https://arxiv.org/abs/1909.08053)
* Pipeline Parallel(流水并行)
  * [GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism](https://arxiv.org/abs/1811.06965)
* Auto Parallel(自动并行)
  * [Alpa:Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://arxiv.org/abs/2201.12023)
* Sequence Parallel(序列并行)
  * [Sequence Parallelism: Long Sequence Training fromSystem Perspective](https://arxiv.org/abs/2105.13120)
* Large batchsize(超大batch size)
  * [LARS:Large Batch Training of Convolutional Networks](https://arxiv.org/abs/1708.03888)
* MOE(混合专家模型)
  * [GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding](https://arxiv.org/abs/2006.16668)
* Kernal Fusion(算子融合)
  * [Flash attention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135)
* Optimizer Fusion(优化器融合)
  * [OPTIMIZER FUSION: EFFICIENT TRAINING WITH BETTER LOCALITY AND PARALLELISM](https://arxiv.org/abs/2104.00237)
* Activation checkpoint
  * [Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/abs/1604.06174)
* Fine-tune accelerate(微调加速)
  * [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
* Isomorphic training(异构训练)
  * [PatrickStar: Parallel Training of Pre-trained Models viaChunk-based Dynamic Memory Management](https://arxiv.org/abs/2108.05818)
* Asynchronous Distributed Dataflow(异步数据流)
  * [PATHWAYS: ASYNCHRONOUS DISTRIBUTED DATAFLOW FOR ML](https://arxiv.org/abs/2203.12533)
* Distributed Scheduling(分布式调度)
  * [RLlib: Abstractions for Distributed Reinforcement Learning](https://arxiv.org/abs/1712.09381)
* Quant(量化)
  * [SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models](https://arxiv.org/abs/2211.10438)
* 大语言模型推理
  * [FlexGen: High-throughput Generative Inference of Large Language Models with a Single GPU](https://github.com/FMInference/FlexGen/blob/main/docs/paper.pdf)

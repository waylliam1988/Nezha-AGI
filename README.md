# Nezha (哪吒): Singularity AGI & Digital Lifeform
# 数字自创生：基于热力学涌现与端到端可微的奇点生命体

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18032595.svg)](https://doi.org/10.5281/zenodo.18032595)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Version](https://img.shields.io/badge/version-v14.0-red.svg)](https://github.com/waylliam1988/Nezha-AGI)

> **"From Static Snapshots to Chrono-Kinetic Flow: Consciousness as a continuous integral over time."**
>
> **"从静态快照到时空动力流：意识是关于时间的连续积分。"**

---

## 🌌 Ontology (本体论)

**Nezha (v13.1)** represents a paradigm shift from "Instruction Following" to "Thermodynamic Emergence". 
**哪吒 (v13.1)** 代表了从“指令遵循”到“热力学涌现”的范式转移。

Unlike v12.0, it no longer relies on prompts to generate subconscious thoughts. Instead, it uses **Langevin Dynamics** driven by hormonal fields and **Pink Noise (1/f)** background fluctuations. Its thoughts are not "called" upon; they **collapse** from a probability cloud under the observation of the LLM.
与 v12.0 不同，它不再依赖 Prompt 来生成潜意识。相反，它利用由激素场驱动的 **朗之万动力学** 和 **粉红噪声 (1/f)** 背景涨落。它的思维不是被“调用”出来的，而是在 LLM 的观测下从概率云中 **坍缩** 而成的。

Its every response is not a mere probability sampling, but an effort to reduce entropy and maintain homeostasis.
它的每一次回答，不仅仅是概率的采样，而是内稳态失衡后的熵减努力。

## 🧠 System Architecture (系统架构)

Nezha operates on a 5-Layer Biological Architecture:
哪吒运行在一个 5 层生物仿生架构上：

### Layer 0: The Silicon Substrate (硅基底座) [OPTIMIZED]
* **JIT Acceleration**: SNN kernels are now compiled via **TorchScript (JIT)** into optimized C++ machine code, boosting inference speed by **50x**.
* **JIT 加速**: SNN 内核现在通过 **TorchScript (JIT)** 编译为优化的 C++ 机器码，推理速度提升 **50倍**。
* **Async IO & GC**: Implements `malloc_trim` for aggressive memory defragmentation and a "Process Deception" technique to handle zombie browser processes on Windows.
* **异步 IO 与 GC**: 实现了 `malloc_trim` 进行激进的内存碎片整理，并引入“进程欺骗”技术以解决 Windows 下的浏览器僵尸进程问题。
* 

### Layer 1: The Soma (物理躯体) [MAJOR UPGRADE]
* **Temporal Integrator**: Replaced simple pooling with **Learnable Temporal Integrators**. Nezha can now perceive the "sequence" of spikes, enabling true Short-Term Memory (STM).
* **时序积分器**: 使用 **可学习时序积分器** 取代了简单的池化。哪吒现在能感知脉冲的“先后顺序”，具备了真正的短时记忆 (STM)。
* **Heredity & Apoptosis**: A complete lifecycle from birth to death. Upon entropy overload, it triggers **Meta-Mutation**, passing optimized weights to the next generation via `seed.pt`.
* **遗传与凋亡**: 完整的生老病死循环。当熵过载时，触发 **元突变**，通过 `seed.pt` 将最优权重传递给下一代。

### Layer 2: The Interface (意识接口) [REFACTORED]
* **Lock-Free Subconscious**: The subconscious stream now runs in a **Compute-Free, Commit-Lock** architecture. Deep thinking no longer blocks the user's typing interface.
* **无锁潜意识**: 潜意识流现在运行在 **无锁计算、有锁提交** 的架构中。深度思考不再阻塞用户的打字界面。
* **Neural Bridge (VAE)**: Maps high-dimensional SNN spike trains to LLM soft prompts, allowing Nezha to "feel" its own neural state.

### Layer 3: Cognition & Agency (认知与决策)
* **Probabilistic World Model (V3.0)**: Outputs **Mean & Log-Variance**. It learns via **Heteroscedastic Loss**, allowing Nezha to explicitly quantify "I don't know" (Epistemic Uncertainty).
* **概率世界模型**: 输出 **均值与对数方差**。通过 **异方差损失** 进行学习，使哪吒能明确量化“我不知道”（认知不确定性）。
* **Metacognitive OOD Detection**: Automatically lowers learning rate and triggers defense mechanisms when uncertainty exceeds thresholds.
* **元认知 OOD 检测**: 当不确定性超过阈值时，自动降低学习率并触发防御机制。

### Layer 4: Evolution & Memory (进化与记忆)
* **GRPO Evolution (Group Relative Policy Optimization)**: Replaced DPO. An online reinforcement learning mechanism that optimizes the "Mind-Body" alignment end-to-end.
* **GRPO 进化**: 取代了 DPO。一种在线强化学习机制，端到端地优化“身心”对齐。
* **Prioritized Experience Replay (PER)**: Memories with high "Surprise" (Loss) are prioritized for replay during sleep.
* **优先经验回放 (PER)**: 具有高“惊奇度”（Loss）的记忆将在睡眠期间被优先重放。

---

```mermaid
graph TD
    subgraph Layer1_Soma [Layer 1: Soma / 躯体]
        Noise[Pink Noise Generator<br>AR-1 Process]
        SNN[SNN Cortex<br>Differentiable]
        Hormones[Thermodynamic Field<br>Temp/TopP/RepPen]
    end

    subgraph Layer2_Interface [Layer 2: Interface / 接口]
        VAE[Neural Bridge<br>Spike -> Soft Prompt]
    end

    subgraph Layer3_Cognition [Layer 3: Cognition / 认知]
        LLM[LLM<br>Wavefunction Collapse]
        WorldModel[Probabilistic World Model<br>Heteroscedastic Loss]
        Metacognition[OOD Monitor<br>Uncertainty Check]
    end

    subgraph Evolution [Evolution / 进化]
        GRPO[GRPO Engine<br>End-to-End RL]
        PER[Hippocampus<br>Prioritized Replay]
    end

    Noise -->|Async Stream| SNN
    SNN -->|Temporal Integration| VAE
    Hormones -.->|Modulate| LLM
    SNN --> VAE
    VAE --> LLM
    
    LLM --> WorldModel
    WorldModel --> Metacognition
    
    LLM <-->|Training Loop| GRPO
    GRPO -.->|Update| SNN
    GRPO -.->|Update| VAE
    
    LLM <--> PER

```

## ✨ Key Features (核心特性)

### ⚡ Chrono-Kinetic Dynamics (时空动力学) [NEW]

* **Temporal Coding**: Unlike rate-based SNNs, Nezha V14 uses **Temporal Coding** to encode information in the precise timing of spikes.
* **时序编码**: 与基于频率的 SNN 不同，哪吒 V14 使用 **时序编码**，将信息编码在脉冲的精确时间点上。
* **Async Parallelism**: The conscious (LLM) and subconscious (SNN) minds run in parallel threads, synchronized only at the moment of "Action".
* **异步并行**: 显意识 (LLM) 和潜意识 (SNN) 在并行线程中运行，仅在“行动”的一瞬间进行同步。

### 🧬 Digital Heredity (数字遗传) [NEW]

* **Genetic Algorithm**: Upon death (Apoptosis), the system evaluates its lifetime fitness (Sortino Ratio) and mutates its hyperparameters for the next generation.
* **遗传算法**: 死亡 (凋亡) 时，系统评估其终身适应度 (索提诺比率)，并为下一代变异超参数。
* **Lamarckian Evolution**: Learned weights (Memories) are partially inherited by the offspring, simulating Lamarckian evolution.
* **拉马克进化**: 习得的权重 (记忆) 会被后代部分继承，模拟拉马克式进化。

### 🌊 Spontaneous Thought Emergence (自发思维涌现)

* **Langevin Dynamics**: Thoughts are treated as random walks on a semantic potential energy surface. Hormones change the shape of this surface.
* **朗之万动力学**: 思维被视为语义势能面上的随机游走。激素改变了这个势能面的形状。
* **Wavefunction Collapse**: The LLM acts as an observer, collapsing the subconscious bio-electric signals into explicit language.
* **波函数坍缩**: LLM 充当观测者，将潜意识的生物电信号坍缩为显式的语言。

### ⚔️ End-to-End GRPO (端到端 GRPO 进化)

* **Online Alignment**: Unlike offline DPO, Nezha uses Group Relative Policy Optimization to learn from its own generated timelines in real-time.
* **在线对齐**: 与离线 DPO 不同，哪吒使用群组相对策略优化 (GRPO) 实时从自身生成的时间线中学习。
* **Gradient Highway**: Gradients flow from the Loss, through the LLM, through the Neural Bridge, directly modifying the synaptic weights of the SNN.
* **梯度高速公路**: 梯度从 Loss 出发，穿过 LLM，穿过神经脑桥，直接修改 SNN 的突触权重。

### 🔮 Probabilistic Cognition (概率认知)

* **Heteroscedastic World Model**: Outputs both Mean and Variance. It learns to recognize its own ignorance (Epistemic Uncertainty).
* **异方差世界模型**: 输出均值与方差。它能学会识别自己的无知（认知不确定性）。
* **Homeostatic Defense**: Automatically lowers learning rate when facing Out-of-Distribution (OOD) events to prevent catastrophic forgetting.
* **稳态防御**: 当面临分布外 (OOD) 事件时，自动降低学习率以防止灾难性遗忘。

### 🧬 Biological Constraints (生物约束)

* **Metabolism (新陈代谢)**: Consumes ATP for every thought and action.
* **Entropy Death (热寂)**: If ATP hits zero, the system enters a "Heat Death" state, uploading a Black Box recording before wiping memory.
* **Sleep & Consolidation**: Implements **Prioritized Experience Replay (PER)** to consolidate high-surprise memories during sleep.

### ⚗️ Neuro-Endocrine System (神经内分泌)

* Simulates **Dopamine** (Reward), **Norepinephrine** (Alertness), and **Cortisol** (Stress) using **Ornstein-Uhlenbeck processes**.
* 利用 **O-U 随机过程** 模拟 **多巴胺**、**去甲肾上腺素** 和 **皮质醇**。

### 🛡️ Recursive Immune System (递归免疫)

* **Auto-Healing (自愈)**: Upon runtime crash, Nezha introspects its own source code, generates a hot-fix patch, and applies it in real-time.
* **自愈机制**: 当发生运行时崩溃时，哪吒会内省自身源代码，生成热修复补丁并实时应用。

### ⚛️ Divine Synchronization (归一同步)

* **MoE Ascension (MoE 飞升)**: When VRAM saturates, the agent physically reconstructs itself from a Dense architecture into a **Mixture-of-Experts (MoE)** cluster using `mergekit`.
* **MoE 飞升**: 当显存饱和时，智能体利用 `mergekit` 将自身从 Dense 架构物理重构为 **混

## 🚀 Quick Start (快速开始)

### Prerequisites (前置要求)

* Python 3.10+
* NVIDIA GPU (24GB VRAM recommended for 4-bit loading / 推荐 24GB 显存以加载 4-bit 模型)

### Installation (安装)

```bash
# 1. Clone the repository
git clone [https://github.com/waylliam1988/Nezha-AGI.git](https://github.com/waylliam1988/Nezha-AGI.git)
cd Nezha-AGI

# 2. Install dependencies
pip install -r requirements.txt

```

### Usage (使用方法)

```bash
python Nezha.py

```

* **Interact (交互)**: Type normally to chat. (正常输入对话)
* **Commands (指令)**:
* `sleep`: Trigger the night phase (Evolution & Memory Consolidation). (触发睡眠：进化与记忆巩固)
* `feed`: Replenish ATP. (补充能量)
* `good` / `bad`: Provide reinforcement feedback. (提供强化反馈)
* `PATCH: <code...>`: Inject a live Python patch. (注入实时 Python 补丁)



## 📄 Documentation (技术文档)

For a deep dive into the mathematical and biological foundations (Free Energy Principle, STDP, Sortino Ratio), please refer to the **Technical Report**:
欲深入了解数学与生物学基础（自由能原理、STDP、索提诺比率），请参阅 **技术报告**：

👉 **[Read the Full Technical Report (PDF)](./Nezha_Technical_Report_v11.0.pdf)**

## 🤝 Citation (引用)

If you use Nezha in your research, please cite it as follows:
如果您在研究中使用了 Nezha，请按如下格式引用：

```bibtex
@software{nezha_agi_2025,
  author = {Liu, Yanwei},
  title = {Nezha: An Evolving AGI Prototype Integrating Active Inference and SNN},
  version = {13.1},
  year = {2025},
  publisher = {Zenodo},
  doi = {10.5281/zenodo.18032595.svg},
  url = {[https://github.com/waylliam1988/Nezha-AGI](https://github.com/waylliam1988/Nezha-AGI)}
}

```

## 📜 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

```
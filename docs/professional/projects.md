<span style="color: #1A95E0; font-weight: bold">1. AI Model Analysis and Optimization Research</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">Jul. 2023 - Sep. 2024</div>

- **Conducted structural analysis and profiling** of various computer vision (CV) and large language models (LLMs) like YOLOX, ResNeXt, Stable Diffusion, ViT, BERT, GPT, LLaMA, ChatGLM, Baichuan, and BlueLM.
- Calculated and estimated the theoretical peak performance based on hardware peak performance and bandwidth.
- Collected profiling logs during model training and inference, analyzing memory consumption, operand usage, computation precision, hardware utilization, throughput, kernel latency, and the distribution of CUDA/Tensor Core operators.
- Provided an AI CPU operator list, and explored approximate implementations of operators such as GeLU.

---

<span style="color: #1A95E0; font-weight: bold">2. Model Quantization Techniques and RNG Algorithm Research</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">​Mar. 2024 - Dec. 2024</div>

- **Summarized current popular model quantization techniques** and hot topics.
- Analyzed quantization schemes for INT and FP types at various granularities during model training and inference, focusing on storage, casting, and static calibration methods.
- Studied the computation of quantized operators like Embedding and MatMul, and built quantized models using frameworks such as AutoAWQ and GPTQ.
- Analyzed and compared random number generation (RNG) algorithms based on business needs, proposed an interleaved parallel fLFSR algorithm with ~3.8× speed improvement, and supported hardware RNG implementation.

---

<span style="color: #1A95E0; font-weight: bold">3. Distributed Model Training and Inference Frameworks Research</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">​Feb. 2024 - Oct. 2024</div>

- **Research on distributed model training and inference frameworks.**
- Implemented and analyzed parallel modes (DP, ZeRO, DDP, TP, PP, SP, MoE) in multi-node and multi-GPU scenarios based on DeepSpeed and Megatron-LM, focusing on splitting strategies, reduce operations, computation methods, and communication points.
- Analyzed PagedAttention in vLLM, including KV Cache partitioning, indexing, and chunked computation, as well as Continuous Batching in prefill and decode separation. Also examined the computation process and operator implementation of FlashAttention.

---

<span style="color: #1A95E0; font-weight: bold">4. Graph-Level Model Optimization</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">​Jul. 2023 - Dec. 2023</div>

- **Optimized models at the graph level.**
- Developed operator fusion requirements for operator libraries and compilers based on platforms like PyTorch, LMDeploy, TensorRT, and TensorRT-LLM, and analyzed automated graph partitioning and fusion solutions such as AKG, Apollo, Chimera, and AStitch.
- Analyzed the compilation process and mechanisms of TPU-MLIR.

---

<span style="color: #1A95E0; font-weight: bold">5. Automated Fault Inspection Scheme of UAV for Remote Electric Power Transmission Lines</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">Apr. 2022 - Jun. 2023</div>

- ​**Learning-based annotation and data augmentation**.
- Data: crawling, learning-based annotation, and data augmentation.
- ​**Communication:** BeiDou short message communication and signal strength selection.
- ​**Strategy:** coreset extraction, weakly supervised learning, and interactive continuous learning.

---

<span style="color: #1A95E0; font-weight: bold">6. Smart Hydro-Information Surveillance Platform on Edge for Low Mountainous and Hilly Areas</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">Mar. 2021 - Jun. 2023</div>

- ​**Water body extraction**, water line detection, debris detection: multi-task hydro-information surveillance.
- Data: generation, annotation, cleaning, balancing, augmentation, and visualization.
- ​**Model design:** bilateral backbone, parameter sharing, global attention, and task-specific detection head.
- ​**Strategy:** alternate training, early exit, task balance, and end-edge-cloud collaborative scheduling.

---

<span style="color: #1A95E0; font-weight: bold">7. Vehicle-Infrastructure Collaboration and Edge Intelligent Perception Based Validation Platform</span>
<div style="text-align: right; color: #888888; font-size: 0.8em;">Jul. 2020 - Oct. 2021</div>

- ​**Vehicle detection and tracking** & road hazards detection algorithms.
- Data: cleaning, balancing, augmentation, and visualization of datasets from on-board cameras and road side units.
- ​**Model lightweighting:** pruning, knowledge distillation, and training-inference decoupling.
- ​**Strategy:** meta-learning and progressive knowledge distillation.
### **Fudan Vision and Learning Lab (FVL) — Long-Horizon VLA Research**
**Research Assistant | Ongoing**

- Investigating explicit *Language Notes* as structured memory for long-horizon Vision-Language-Action agents, representing task history, current progress, environmental feedback, and failure information.
- Developing mechanisms for task-progress tracking and memory-conditioned decision making, with the goal of improving recovery from accumulated errors during multi-stage manipulation.
- Exploring adaptation from simulation and pretrained policies to real robot settings, which motivates my future work on tactile-enhanced VLA models.

---

### **XLeRobot — Real-World Multimodal Data Collection**
**Robotics Research Engineering | [Project Repository](https://github.com/flyingc2004/xlerobot-VR)**

- Engineered a real-robot teleoperation and data-collection pipeline supporting VR controllers, Nintendo Switch Joy-Con, and keyboard input.
- Synchronized RGB observations, robot states, actions, language instructions, and task-stage metadata into multimodal trajectories for imitation learning and VLA fine-tuning.
- Designed the pipeline to support repeatable collection across manipulation tasks and practical adaptation of learned policies to the physical platform.

---

### **AgiBot World Challenge @ ICRA 2026 — Continuous Package Sorting**
**Robotics Research Engineering | [Competition Repository](https://github.com/flyingc2004/ACoT-VLA)**

- Built a vision-based state-recognition module with a Vision Transformer and integrated it with finite-state-machine control for continuous package sorting.
- Improved robustness through dynamic prompt adaptation, sampler alignment, and state-transition debugging under changing visual conditions.
- Increased task success by approximately **50% relative to the initial baseline in internal experiments**, providing hands-on experience in perception-control integration and real-world failure analysis.

---

### **Long-Term Memory for Large Language Models**
**Research Project**

- Studied retrieval and structured representations for long-context dialogue memory, including graph-based memory construction and top-k retrieval.
- Implemented and evaluated EMem-style variants on LoCoMo using BLEU, F1, and LLM-based evaluation, examining how representation and retrieval choices affect memory quality.
- Connected these findings to embodied agents, where compact, reusable memories can support temporal reasoning, task progress tracking, and recovery.

---

### **LowAux-RDNet — Single-Image Reflection Removal**
**Computer Vision Course Research | [Project Repository](https://github.com/flyingc2004/lowaux-rdnet)**

- Extended an ERRNet baseline with RDNet's explicit residual branch and introduced Gaussian low-pass auxiliary supervision for reflection-residual learning without adding inference-time parameters or computation.
- Built the R5 training pipeline with scene-balanced RRW real pairs and a unified benchmark covering ERRNet, RDNet, IBCLN, DSRNet, and DSIT across five public test sets.
- Achieved a five-dataset macro average of **27.546 PSNR**, **0.9220 SSIM**, **0.9751 NCC**, and **0.004760 LMSE** under the project's fixed evaluation protocol.

---

### **Robot Learning in PyBullet**
**Simulation, Imitation Learning, and Reinforcement Learning | [Project Repository](https://github.com/flyingc2004/fdu-prml-2025)**

- Developed pushing and pick-and-place environments and collected **1,000 expert trajectories** for behavior-cloning experiments.
- Trained MLP-based imitation-learning policies and conducted DDPG+HER experiments, followed by out-of-distribution tests to examine robustness and generalization.
- Built an end-to-end understanding of data generation, policy training, evaluation, and simulation-to-real considerations.

---

### **EvalAwarePosterGen — Reader-Centered Agent Framework**
**Agent Systems and Evaluation Research | [Project Repository](https://github.com/flyingc2004/Eval_Aware_Poster_Gen)**

- Designed an evaluation-aware agent pipeline that connects paper parsing, reader-goal planning, goal-conditioned storyboarding, layout optimization, reader simulation, critique, and repair.
- Implemented the ReaderGoalPlanner, coverage evaluators, deterministic validation, self-critique, layout-aware budgets, and goal-section grounding.
- In a pilot ablation, planner conditioning improved storyboard-level reader-goal coverage from **0.5714 to 0.8571**, while must-goal coverage remained **1.0**; deterministic intrinsic checks achieved full validity on the pilot cases.
- Submitted the work to **AAAI 2027** and continued extending the evaluation design toward a unified benchmark and dataset.

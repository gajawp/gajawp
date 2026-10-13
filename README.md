Hi, I'm Preethi Gajawada 👋
Machine Learning & AI Engineer · Medical Imaging · LLM Systems Computer Science @ Northeastern University

 
 

About me
I build machine learning systems that are accurate, measurable, and responsible. My work spans deep learning for medical imaging, LLM evaluation and prompt optimization, retrieval-augmented generation, and fairness in AI. I care about rigorous experimentation: controlled ablations, multi-seed runs, cross-validation, and honest reporting of results and limitations.

🎓 Studying Computer Science at Northeastern University
🔬 Currently: segmentation and classification of ovarian tumors in ultrasound images
🤖 Interested in: computer vision, LLM evaluation, trustworthy & fair AI, healthcare AI
💼 Open to: ML / AI engineering, data science, and software engineering roles & internships
📫 Reach me at gajawada.p@northeastern.edu
Featured projects
🩺 Ovarian Tumor Segmentation & Classification
PyTorch Computer Vision Transformers Medical Imaging

An end-to-end deep learning research pipeline for ovarian tumor analysis on the OTU 2D/3D ultrasound datasets.

Benchmarked 7 segmentation architectures (U-Net++, Attention U-Net, DeepLabV3+, TransUNet, SegFormer, DSNet, DS2Net); DS2Net reached the best Dice of 0.837 (IoU 0.754).
Built a mask-aware DS2Net + Swin Transformer hybrid for benign vs. malignant classification and compared it against ResNet-50, DenseNet-121, EfficientNet-B3, ViT-B/16, and Swin-T baselines.
Ran controlled ablations (context, mask input, loss function, augmentation, resizing), k-fold cross-validation, and multi-seed experiments — e.g. the final model hit 0.87 ROC-AUC and showed augmentation lifts balanced accuracy by ~7.5 points.
Automated metric collection into paper-ready comparison tables.
🏥 HealthBridge AI — Remote Patient Mobility Assistant
RAG LLMs Streamlit Security

A secure, multilingual, retrieval-augmented conversational assistant that helps patients, caregivers, and clinicians understand mobility-monitoring records.

Role-based and patient-level authorization enforced before retrieval, plus identifier tokenization so private data never reaches the model.
Voice input/output, multilingual responses, and deterministic safety guardrails.
Automated evaluation over 100 test cases: 96.7% factual accuracy, 100% authorization accuracy, ~4s mean latency, 0 execution errors.
⚖️ LLM-as-a-Judge Evaluation Framework
DSPy LLM Evaluation OpenAI Anthropic Ollama

A pluggable framework for generating and evaluating text with LLMs, where the generator and judge models are swapped purely through config (OpenAI, Anthropic, or local Ollama models) — no code changes needed. Includes batch CSV evaluation, LLM-judge scoring, and a test suite.

🗣️ Multilingual Counter-Narrative Generation
DSPy GPT-4o Prompt Optimization NLP

A DSPy pipeline that generates respectful, empathetic responses to hateful speech in English and Tamil. Prompts are optimized with COPRO and scored with custom reward functions (safety, empathy, grounding, non-confrontation, NLI-based checks) alongside LLM-judge and reference-based metrics.

🔍 FairSearch — Fairness-Aware Retrieval
RAG ChromaDB Fairness Plotly

An interactive dashboard comparing standard similarity search with fairness-aware MMR re-ranking, with a bias-audit module that measures how retrieval results are distributed across institutions.

🚗 Rideshare Dispatch Simulator
Java OOP Design Patterns

An event-driven simulation of ride dispatching built with clean object-oriented design — Strategy (pluggable priority rules), Factory, and Observer/event-listener patterns — plus trip statistics and unit tests.

Tech stack
Languages 
 
 

ML / Deep Learning 
 
 
 
 
 

LLMs & Retrieval 
 
 
 
 

Apps, Viz & Tools 
 
 
 
 

Core skills: image segmentation & classification · vision transformers · experiment design & ablation studies · RAG pipelines · LLM evaluation & prompt optimization · fairness auditing · secure data access · OOP & design patterns

Education
Northeastern University — Computer Science

Relevant coursework: Foundations of Artificial Intelligence (CS 5100)

⭐ Thanks for stopping by — feel free to reach out about roles, research, or collaborations!

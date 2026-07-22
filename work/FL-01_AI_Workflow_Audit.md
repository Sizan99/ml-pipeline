# FL-01: AI Workflow Audit and Tool Setup
**Author:** Md Shiam Ahmed Sizan  
**Track:** General AI Fluency (Week 1)

---

## 📊 Section 1: The Workflow Audit Table
Below is a workflow audit mapping out 12 recurring tasks strictly and exclusively from my three portfolio projects: the **NLP Scientific Article Classifier & Summarizer**, the **mEAl Evolutionary Meal Plan Optimizer**, and the **TACL Delivery Robot System & Autonomous Control**.

| Task Description | Classification | One-line Rationale |
| :--- | :--- | :--- |
| **1. Debugging PyTorch/Transformers Out-Of-Memory (OOM) errors during LLM inference** *(NLP Project)* | **Delegate with review** | AI is highly efficient at suggesting GPU memory optimizations (like gradient accumulation, FP16 precision, or clearing CUDA cache), but I must test and review them. |
| **2. Writing a Genetic Algorithm custom crossover operator in Python** *(mEAl Project)* | **Collaborate** | AI drafts standard crossover structures, while I adapt the genetic exchange logic to handle dictionary-based non-homologous chromosomes. |
| **3. Calculating 3D spatial transformations & Inverse Kinematics for YouBot** *(Robotics Project)* | **Collaborate** | I use AI to check spatial ray-casting math and library calls (`kinpy`), while I build the joint permutation evaluation loop. |
| **4. Designing the "iOS Liquid Glass" CSS theme for the frontend web application** *(NLP Project)* | **Just me** | Designing clean, glassmorphic styles with backdrop filters, custom animations, and layout balances requires my personal human design aesthetics and UI intuition. |
| **5. Running systematic grid searches to optimize Genetic Algorithm mutation rates** *(mEAl Project)* | **Fully automate** | A python script sweeps through population sizes and mutation rates, logs fitness values, and outputs charts automatically with no manual intervention. |
| **6. Ingesting and preprocessing a 5GB raw JSON dataset (`arxiv-metadata-oai-snapshot.json`)** *(NLP Project)* | **Collaborate** | AI writes regex patterns to clean LaTeX formatting, while I optimize the pandas chunking to prevent memory overflow. |
| **7. Implementing a Gravitational Search Algorithm (GSA) from scratch in Python** *(mEAl Project)* | **Collaborate** | AI drafts standard physics equations (mass, gravity attraction), while I structure the iterative simulation loops. |
| **8. Creating the raw database of 15 foods and 17 nutritional vectors** *(mEAl Project)* | **Just me** | Constructing a correct dataset with precise values requires manual research and verification to ensure accurate vectors. |
| **9. Coding an asynchronous REST API backend using FastAPI and Uvicorn** *(NLP Project)* | **Collaborate** | AI writes the async/await boilerplate wrappers, while I write the model routing logic. |
| **10. Drafting the Harvard-referenced academic coursework report** *(NLP/Robotics Projects)* | **Delegate with review** | AI drafts generic literature summaries, but I rewrite the copy to match the rubric and format citations correctly. |
| **11. Implementing few-shot RAG by using Cosine Similarity over TF-IDF vectors** *(NLP Project)* | **Collaborate** | AI drafts cosine similarity functions, while I construct the prompt injection template to eliminate hallucinations. |
| **12. Deploying a Sequence-to-Sequence transformer (`DistilBART`) for summarization** *(NLP Project)* | **Collaborate** | AI drafts the model loader and tokenizer pipeline, while I verify the text input truncation logic. |

---

## ⚙️ Section 2: Claude Project Setup & Custom Instructions
Below is the custom instructions configuration for my Claude Project, tailored to my background, tone preferences, and current goals.

### Project Custom Instructions Template:
```text
Role: You are assisting Md Shiam Ahmed Sizan, a post graduate student in MSc Artificial Intelligence, a UI/UX designer, and an Artificial Intelligence (Machine Learning Track) Intern at FlyRank.

Tone Preferences:
- Direct, concise, and evidence-backed.
- Write using first-person singular pronouns ("I did", "my findings", "I analyzed") when drafting content.
- Do not make exaggerated claims or use generic filler language; tie every conclusion to concrete numbers.

Current Goals:
- Build and optimize machine learning models for search discovery, NLP classification, and robotic simulation.
- Ensure all code is highly structured, modular, and handles memory constraints efficiently.
- Align all work with strict academic standards and data safety boundaries.
```

---

## 🎯 Section 3: Three Target Tasks & Success Definitions
These three tasks are chosen from the audit list above to be reused in assignments FL-02 through FL-04.

### Task A: Debugging PyTorch/Transformers Out-Of-Memory (OOM) errors during LLM inference (NLP Project)
*   **Classification:** Delegate with review
*   **Success Definition:** The NLP model runs locally on a consumer GPU (8GB VRAM) without triggering a `torch.cuda.OutOfMemoryError` during a batch inference of 1,000 documents by employing gradient checkpointing, FP16 precision, and manual CUDA cache clearing.

### Task B: Implementing a Genetic Algorithm custom crossover operator in Python (mEAl Project)
*   **Classification:** Collaborate
*   **Success Definition:** The custom crossover operator successfully combines parent dictionaries of food-to-weight mappings, generating offspring containing only foods present in either parent, executes in under 0.05 seconds for a population size of 100, and passes all weight bounds unit tests.

### Task C: Calculating 3D spatial transformations & Inverse Kinematics for YouBot (Robotics Project)
*   **Classification:** Collaborate
*   **Success Definition:** The YouBot control script solves IK (using `kinpy`) for 10 sequential pick-and-place positions, reaching each target coordinate with a spatial accuracy error of under 1 cm (< 0.01m) in simulation, while choosing the trajectory that minimizes total joint rotation distance.

---

## 🛠️ Tool Setup Verification
*   **Accounts Created:** Claude (Anthropic), ChatGPT (OpenAI), and Anthropic Academy accounts are successfully configured.
*   **Academy Course:** Enrolled in *AI Fluency: Framework & Foundations* and completed the first module.

README: |
  # UNVEILING: What Makes Linguistics Olympiad Puzzles Tricky for LLMs?  
  **COLM 2025**

  <p align="left">
    <img src="assets/colm_logo.png" alt="COLM Logo" width="90"/>
    &nbsp;&nbsp;
    <img src="assets/mbzuai_logo.png" alt="MBZUAI Logo" width="90"/>
  </p>

  **Mukund Choudhary**, KV Aditya Srivatsa, Gaurja Aeron, Antara Raaghavi Bhattacharya,  
  Dang Khoa Dang Dinh, Ikhlasul Akmal Hanif, Daria Kotova, Ekaterina Kochmar, Monojit Choudhury

  ---

  ## 📄 Paper  
  **Published at COLM 2025**  
  [OpenReview (paper + reviews)](https://openreview.net/forum?id=fcRcl1EXc4)

  **Invited Talk (researchtrend.ai panel):**  
  [Watch the talk](https://youtu.be/2GwJ2sSVrVo?si=tkG2UkKydc06UcCC)

  ---

  ## 🔍 Overview  

  This repository hosts the **linguistic feature annotations** and **LLM evaluation tables** used in our COLM 2025 paper, *UNVEILING: What Makes Linguistics Olympiad Puzzles Tricky for LLMs?*.  
  The project examines **629 problems across 41 low-resource, unseen languages**, annotates each puzzle with **50+ WALS-style linguistic features**, and benchmarks 10 LLMs across 6 prompting strategies.

  The work contributes to a broader research direction on comparing **how LLMs structure language** versus **how humans do**, focusing on metalinguistic reasoning, feature-level linguistic behavior, and cognitive aspects of abstraction.

  ---

  ## ⭐ Key Findings  
  For a clear and concise summary, please refer to:

  - **Paper (full results + figures):**  
    [UNVEILING on OpenReview](https://openreview.net/forum?id=fcRcl1EXc4)

  - **Tweet thread summary:**  
    :contentReference[oaicite:0]{index=0}  

  These resources outline the three main factors behind LLM failures on LO puzzles:  
  morphological complexity, English-structure bias, and data-constraint sensitivity.

  ---

  ## 📁 Repository Contents

  ### **`rose_llm_scores.csv`**  
  LLM **exact-match accuracy** for each puzzle/problem across:  
  - 10 models (GPT, Llama2/3/3.1, Mixtral)  
  - 6 prompting styles  
  - Both translation directions (LRL→EN, EN→LRL)

  ### **`rose_attributes_and_features.csv`**  
  Detailed linguistic **feature and attribute annotations**, including:  
  - 50 WALS-based features  
  - Morphology / syntax / semantics / phonology classes  
  - Similarity to English  
  - Constrained-evidence metrics  

  These correspond directly to analyses in Sections **2–3** of the paper.

  ---

  ## 📦 External Resources (Google Drive)

  The Google Drive snapshot includes videos, posters, and supplementary materials referenced in this project:

  **Google Drive Folder:**  
  [unveiling-resources (videos + poster + tweet PDF)](YOUR_GOOGLE_DRIVE_LINK_HERE)

  Contents include:  
  - **1-min COLM recap video**  
  - **10-min technical brief**  
  - **Conference poster (PDF)**  
    :contentReference[oaicite:1]{index=1}  
  - Tweet PDF & supporting materials  

  These provide quick visual grounding in the project.

  ---

  ## 🔒 Why We Do Not Release the LO Puzzles  

  As described in **Sec. 2.1 (Data)** and the **Ethics Statement** of the paper:  
  :contentReference[oaicite:2]{index=2}

  - Many puzzles are copyrighted by national Linguistics Olympiads.  
  - Some sources intentionally **hide or zip** puzzles to prevent LLM contamination.  
  - To preserve the integrity of uncontaminated evaluation, we release only **annotations + mappings**, not the puzzles themselves.

  Where permitted, annotations can be used to locate the original public sources.

  ---

  ## 🔧 Reproducibility  

  - All LLM inference used **temperature = 0**.  
  - Model variants + prompt templates are detailed in **Appendix A** of the paper.  
  - Annotation guidelines and feature definitions appear in **Appendices D/F**.

  ---

  ## 🤝 Contact, Collaboration & Research Direction  

  If you’re interested in the linguistics of LLMs, metalinguistic reasoning, cognitive structure in models, or probing how LLMs compare to humans:

  **Email:** mukund.choudhary@mbzuai.ac.ae

  This work is part of my broader PhD research in NLP at MBZUAI (advised by Monojit Choudhury), where I explore **how LLMs structure language compared to humans**, and investigate their behavior across linguistic features, code-mixed usage, and abstract hierarchical reasoning.

  ---

  ## ✍️ Citation  


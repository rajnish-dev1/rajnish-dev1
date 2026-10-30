<div align="center">

# 👋 Hi, I'm Rajnish Kumar

### Aspiring AI/ML Engineer | Python Developer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2500&pause=700&color=58A6FF&center=true&vCenter=true&width=600&lines=AI%2FML+Engineer+in+Progress;Computer+Vision+Enthusiast;Building+Smart+AI+Projects;Learning+Something+New+Every+Day" alt="Typing Animation" />

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine_Learning-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header" width="100%" />

</div>

## 🚀 About Me

- 🎓 B.E. Student at University Institute of Technology, Burdwan University
- 💼 AI/ML Intern at National Informatics Centre (NIC), Kolkata
- 🤖 Interested in Artificial Intelligence and Machine Learning
- 👁️ Passionate about Computer Vision and AI applications
- 💻 Building practical projects using Python
- 🌱 Continuously learning new technologies

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Languages | Python, C, SQL |
| AI/ML | Machine Learning, LLMs |
| Computer Vision | OpenCV, OCR |
| Retrieval Systems | RAG, FAISS, Vector Embeddings |
| Core CS | Data Structures & Algorithms |

## 💡 Featured Projects

### 🚘 1. Automatic Number Plate Recognition (ANPR)

- Detects vehicle number plates using computer vision.
- Uses image preprocessing and OCR-based text extraction.
- Potential applications: parking management and traffic monitoring.

**Tech:** Python, OpenCV, OCR

# 🚘 Automatic Number Plate Recognition (ANPR)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/OCR-Text%20Recognition-purple?style=for-the-badge"/>
</p>

## 01 / DATA FLOW

# The Recognition Pipeline

Follow the image from input to final number plate recognition.

```mermaid
flowchart TB

    A["01 / INPUT<br/><br/>Vehicle Image / Video<br/>Image Acquisition<br/><br/>Output: Raw Image"]

    B["02 / PREPARE<br/><br/>Image Preprocessing<br/>Python · OpenCV<br/><br/>Output: Enhanced Image"]

    C["03 / LOCATE<br/><br/>Number Plate Detection<br/>Computer Vision<br/><br/>Output: Plate Region"]

    D["04 / ISOLATE<br/><br/>Plate Cropping<br/>Image Processing<br/><br/>Output: Cropped Plate"]

    E["05 / RECOGNIZE<br/><br/>OCR Processing<br/>Optical Character Recognition<br/><br/>Output: Recognized Characters"]

    F["06 / EXTRACT<br/><br/>Text Extraction<br/>Python · OCR<br/><br/>Output: Number Plate Text"]

    G["07 / VALIDATE<br/><br/>Number Plate Validation<br/>Text Processing<br/><br/>Output: Validated Number"]

    H["08 / RESULT<br/><br/>Final Recognition<br/>Display / Storage<br/><br/>Output: Recognized Number Plate"]

    A --> B --> C --> D --> E --> F --> G --> H

    classDef input fill:#304b3a,stroke:#c5dda8,color:#ffffff,stroke-width:2px
    classDef process fill:#254438,stroke:#72977c,color:#ffffff
    classDef ai fill:#354c42,stroke:#b7d69b,color:#ffffff
    classDef output fill:#244d3c,stroke:#b8d89d,color:#ffffff,stroke-width:2px

    class A input
    class B,C,D process
    class E,F,G ai
    class H output

    linkStyle default stroke:#a9c49d,stroke-width:2px
```

## 02 / TECHNOLOGY STACK

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| OpenCV | Image Processing |
| OCR | Text Recognition |
| NumPy | Numerical Operations |

## 03 / KEY FEATURES

- Vehicle Image Processing
- Number Plate Detection
- Image Preprocessing
- Plate Region Extraction
- Optical Character Recognition
- Number Plate Text Extraction
- Recognition Result Display

## 04 / PROJECT OBJECTIVE

The objective of this project is to develop an Automatic Number Plate Recognition system that detects vehicle number plates from images or video frames and extracts the alphanumeric characters using computer vision and OCR techniques.

## 05 / PROJECT WORKFLOW

Vehicle Input → Image Processing → Plate Detection → OCR → Text Extraction → Final Result

---

<p align="center">
  <b>Developed by Rajnish Kumar</b><br/>
  Information Technology Engineering
</p>


### 📚 2. Corrective Retrieval-Augmented Generation (CRAG)

- Document-based question-answering application.
- Semantic search using FAISS and vector embeddings.
- Generates context-aware answers from document information.

**Tech:** LLMs, RAG, FAISS, Semantic Search

# 🧠 Corrective Retrieval-Augmented Generation (CRAG)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/LLM-AI-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RAG-Retrieval-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/CRAG-Corrective%20AI-orange?style=for-the-badge"/>
</p>

## 01 / DATA FLOW

# The CRAG Processing Pipeline

Follow the information flow from user query to a corrected, context-aware AI response.

```mermaid
flowchart TB

    A["01 / INPUT<br/><br/>User Query<br/>Question Submission<br/><br/>Output: Query"]

    B["02 / RETRIEVE<br/><br/>Document Retrieval<br/>Vector Database / Retriever<br/><br/>Output: Retrieved Documents"]

    C["03 / EVALUATE<br/><br/>Retrieval Evaluator<br/>Relevance Assessment<br/><br/>Output: Quality Score"]

    D{"04 / DECISION<br/><br/>Are Retrieved Documents Relevant?"}

    E["05 / CORRECT<br/><br/>Knowledge Refinement<br/>Filter & Refine Documents<br/><br/>Output: Relevant Knowledge"]

    F["06 / WEB SEARCH<br/><br/>External Knowledge Retrieval<br/>Search Engine / Web Source<br/><br/>Output: External Information"]

    G["07 / DECOMPOSE<br/><br/>Knowledge Processing<br/>Extract Useful Information<br/><br/>Output: Refined Context"]

    H["08 / AUGMENT<br/><br/>Prompt Augmentation<br/>Query + Retrieved Context<br/><br/>Output: Enhanced Prompt"]

    I["09 / GENERATE<br/><br/>LLM Response Generation<br/>Large Language Model<br/><br/>Output: AI Generated Answer"]

    J["10 / OUTPUT<br/><br/>Final Response<br/>Context-Aware Answer<br/><br/>Output: Corrected Answer"]

    A --> B --> C --> D

    D -->|Relevant| E
    D -->|Not Relevant| F
    D -->|Partially Relevant| E
    E --> G
    F --> G
    G --> H --> I --> J

    classDef input fill:#304b3a,stroke:#c5dda8,color:#ffffff,stroke-width:2px
    classDef process fill:#254438,stroke:#72977c,color:#ffffff
    classDef evaluate fill:#354c42,stroke:#b7d69b,color:#ffffff
    classDef output fill:#244d3c,stroke:#b8d89d,color:#ffffff,stroke-width:2px
    classDef decision fill:#66532b,stroke:#e5c77b,color:#ffffff,stroke-width:2px

    class A input
    class B,E,F,G,H process
    class C evaluate
    class D decision
    class I,J output

    linkStyle default stroke:#a9c49d,stroke-width:2px
```

## 02 / TECHNOLOGY STACK

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| LangChain / LangGraph | RAG Workflow |
| Vector Database | Document Storage & Retrieval |
| Embeddings | Semantic Search |
| LLM | Response Generation |
| OCR / PDF Loader | Document Extraction |
| Web Search API | External Information Retrieval |

## 03 / KEY FEATURES

- Intelligent Document Retrieval
- Retrieval Quality Evaluation
- Relevant Document Filtering
- Corrective Retrieval Mechanism
- External Knowledge Search
- Context Refinement
- LLM-Based Answer Generation
- Context-Aware Responses

## 04 / PROJECT OBJECTIVE

The objective of Corrective Retrieval-Augmented Generation (CRAG) is to improve the reliability of Retrieval-Augmented Generation systems by evaluating the relevance of retrieved documents and correcting retrieval errors.

When retrieved information is insufficient or irrelevant, CRAG can use external knowledge sources to improve the context before generating the final response.

## 05 / WORKFLOW

User Query → Document Retrieval → Relevance Evaluation → Knowledge Correction → Context Augmentation → LLM Generation → Final Answer

## 06 / WHY CRAG?

| Traditional RAG | Corrective RAG |
|---|---|
| Retrieves documents | Evaluates retrieved documents |
| May use irrelevant context | Filters irrelevant information |
| Limited correction | Corrective retrieval mechanism |
| Context-based generation | Improved context-based generation |

---

<p align="center">
  <b>Developed by Rajnish Kumar</b><br/>
  Information Technology Engineering
</p>

## 💼 Experience

**AI/ML Intern — National Informatics Centre (NIC)**

📍 Kolkata, West Bengal | March 2026 – Present

- Developed an ANPR system using Python and OpenCV.
- Implemented image preprocessing, plate detection and OCR-based text extraction.

## 🎓 Education

- **B.E.** — University Institute of Technology, Burdwan University (2023–2027)
- **Intermediate** — Raj Narayan College, Hajipur (2023)
- **Matriculation** — KCI Rajapakar, Hajipur (2021)

## 📊 GitHub Statistics

<!-- Replace YOUR_GITHUB_USERNAME with your GitHub username -->

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=rajnish-dev1&show_icons=true&theme=tokyonight&hide_border=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rajnish-dev1&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://streak-stats.demolab.com?user=rajnish-dev1&theme=tokyonight&hide_border=true" />

</div>

## 🤝 Connect With Me

<p>
  <a href="mailto:rajnishkumar875737@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="YOUR_PORTFOLIO_URL">
    <img src="https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
</p>

<div align="center">

### ✨ "Keep Learning. Keep Building. Keep Growing."

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%" />

</div>

<h2 align="center">🌐 Connect With Me</h2>

<p align="center">

<a href="mailto:rajnishkumar875737@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/rajnish-kumar-b1141b3303/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://www.instagram.com/name.ravlux/">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

<a href="https://www.facebook.com/share/1DKrSYqLZB/">
<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
</a>

<a href="https://thunderous-souffle-6d8819.netlify.app/">
<img src="https://img.shields.io/badge/My_Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white"/>
</a>

<a href="https://github.com/rajnish-dev1">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>


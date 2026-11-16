### Kevin Benassuly · Senior Data Scientist · Generative AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kevin--benassuly-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-benassuly)

I build generative AI and machine learning systems (RAG, multi-agent workflows, causal ML) that hold up under evaluation: grounded in real data, measured against ground truth, with the costs and failure modes stated. Open to data science, applied AI and forward deployed engineering roles, and to freelance projects.

#### Selected projects

| Project | What it is | Evidence |
|---|---|---|
| [**equity-research-agents**](https://github.com/KevinBenass/equity-research-agents) | A multi-agent research team in LangGraph: a planner, parallel specialists for financial data and 10-K filings, a writer and a critic. It has memory, grounding checks in code and full tracing. | Every ground-truth number correct in 23 of 24 memos; the critic rejected 100% of deliberately corrupted memos; memory cuts cost by 31% |
| [**filings-copilot**](https://github.com/KevinBenass/filings-copilot) | Cited answers from SEC 10-K filings: hybrid search, contextual chunking and query decomposition, with an ablation of every component. | Recall@5 0.58 → 0.82 across the ablation; 99% of claims supported by sources; abstained on all 30 unanswerable questions |
| [**uplift-retention-optimizer**](https://github.com/KevinBenass/uplift-retention-optimizer) | Who should get a retention offer: uplift models on a real randomized campaign (200k customers), valued in currency with confidence intervals. | About 2× the persuadable rate of random targeting; the only policy tested with a positive profit estimate; a simulation study validates the evaluation |

#### Toolkit

**ML and causal inference:** Python, scikit-learn, LightGBM, uplift modeling, experiment analysis, bootstrap inference<br>
**LLM systems:** Claude API, LangGraph, RAG (BM25, dense embeddings, reranking), structured outputs, tool use, LLM-as-judge evaluation<br>
**Data and engineering:** SQL, DuckDB, pandas, FastAPI, Streamlit, Docker, pytest, GitHub Actions

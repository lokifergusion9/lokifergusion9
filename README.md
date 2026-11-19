<!-- ░░░ HEADER BANNER ░░░ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,12,6,2,18&height=210&section=header&text=Lokesh%20Kumar&fontSize=54&fontColor=ffffff&fontAlignY=36&desc=Building%20Agentic%20AI%20%C2%B7%20MCP%20%C2%B7%20RAG%20Systems&descAlignY=58&descSize=18&animation=fadeIn" alt="header" />

<div align="center">

<p><b>IIT Roorkee · Production &amp; Industrial Engineering</b><br/>I build agentic AI systems and data products, and measure whether they actually work.</p>

<p>
  <a href="https://lokifergusion9.github.io/"><img src="https://img.shields.io/badge/%F0%9F%9A%80_PORTFOLIO-F72585?style=for-the-badge&labelColor=1a012b" /></a>
  <a href="https://www.linkedin.com/in/lokesh-kumar-1768262b9/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a012b" /></a>
  <a href="https://lokifergusion9.github.io/assets/Lokesh-Kumar-Resume.pdf"><img src="https://img.shields.io/badge/R%C3%89SUM%C3%89-7209B7?style=for-the-badge&labelColor=1a012b" /></a>
  <a href="https://github.com/lokifergusion9?tab=repositories"><img src="https://img.shields.io/badge/%F0%9F%93%A6_ALL_REPOS-FF8C00?style=for-the-badge&labelColor=1a012b" /></a>
</p>

</div>

## ⚡ whoami

```python
lokesh = AIEngineer(
    name      = "Lokesh Kumar",
    building  = ["Travel-OS — AI operating system for travel agencies",
                 "Khata-AI — WhatsApp payments to a Google Sheets ledger (LangGraph + MCP)",
                 "A human-approved customer-support agent with its own eval platform"],
    superpower= "turning LLM agents + data into working, measured products",
    stack     = ["Python", "LangGraph", "MCP", "RAG", "FastAPI", "PyTorch"],
)
```

## 🌌 Featured projects

| Project | How it works |
|---|---|
| **[TravelOS](https://github.com/lokifergusion9/Travel-OS)**<br><sub>[case file](https://lokifergusion9.github.io/project-travelos.html)</sub> | Multi-tenant AI CRM where 4 LangGraph agents draft itineraries, creatives, vendor deals and follow-ups.<br>Nothing goes out until a human approves; tenant data is isolated with PostgreSQL Row-Level Security. |
| **[KhataAI](https://github.com/lokifergusion9/Khata-AI)**<br><sub>[live demo](https://mcp-financial-automation-37ajappgn996heqhqhrsq4h.streamlit.app/) · [case file](https://lokifergusion9.github.io/project-khataai.html)</sub> | A LangGraph + MCP pipeline reads WhatsApp payment chats every 30 min and writes a Google Sheets ledger.<br>A 92-message Hinglish eval drove prompt fixes: held-out field accuracy **94.8% → 100%**, no duplicate rows. |
| **[Delhivery ETA Graph](https://github.com/lokifergusion9/delivery-network-intelligence)**<br><sub>[live demo](https://delivery-network-intelligence-sjdj5m77kgdkvbmgqhy9yo.streamlit.app/) · [case file](https://lokifergusion9.github.io/project-eta-graph.html)</sub> | Treats 144,867 shipment scans as a graph of 1,657 hubs and feeds node2vec + centrality features to LightGBM.<br>ETA error drops **70%** vs. the OSRM routing engine (107 → 32 min), and hubs are ranked by bottleneck risk. |
| **[Decoding Customer Value](https://github.com/lokifergusion9/decoding-customer-value)**<br><sub>[dashboard](https://lokifergusion9.github.io/decoding-customer-value/founder_dashboard.html) · [case file](https://lokifergusion9.github.io/project-customer-value.html)</sub> | Segments 3,900 unlabeled D2C customers into 5 loyalty tiers with SQL CTEs, window functions and pandas.<br>Shows discounts drive no extra spend, so **43% of revenue** is promo-reliant; ends in a promo-sunset plan. |
| **[RefundGuard](https://github.com/lokifergusion9/RefundGuard-Agentic-Customer-Support-with-LLM-Evaluation)**<br><sub>[live demo](https://refundguard-z5ni.onrender.com/demo) · [case file](https://lokifergusion9.github.io/project-refundguard.html)</sub> | A support agent where the model proposes and code decides: no refund without a human-approved proposal.<br>An eval platform with 50 tasks and injected faults scores business state: **0 duplicate refunds** in 248 runs. |
| **[SecureBank](https://github.com/lokifergusion9/Banking-Support-Agent)**<br><sub>[case file](https://lokifergusion9.github.io/project-securebank.html)</sub> | A router sends each banking message to an FAQ, account, card or escalation agent, with PII masked first.<br>Policy answers come from re-ranked retrieval over bank PDFs: **28/28** end-to-end evals, 94% hit@4. |
| **[EV Dynamic Tariff](https://github.com/lokifergusion9/EV-dynamic-tariff-optimization)**<br><sub>[case file](https://lokifergusion9.github.io/project-ev-tariff.html)</sub> | Three agents forecast charging demand, set a ₹/kWh surge, hold or discount, and learn from simulated outcomes.<br>On Caltech ACN data the learned policy earns **+8.2% revenue** with **−22% peak wait** vs. a flat tariff (simulated). |

## 🛠️ Arsenal

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
</p>

**ML / Deep Learning**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
</p>

**LLMs / Agents**

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-7209B7?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/RLHF-F72585?style=flat-square&logo=openai&logoColor=white" />
</p>

**Backend / MLOps / Cloud**

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
</p>

**Data Stores**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square&logo=databricks&logoColor=white" />
</p>

## 🏔️ Beyond Code

- 🏔️ **Deputy Secretary · Himalayan Explorers' Club** — led a 13-member expedition to **5,500m** with zero incidents
- 🏐 **Secretary & Captain · Volleyball** — IIT Roorkee, **3 Inter-IIT medals**
- 🎭 **Founding Member · Rajasthan Cultural Association** — events for **400+ people**

## 🏆 Achievements

<div align="center">
  <img src="https://img.shields.io/badge/%F0%9F%A5%87_Best_Sportsman-IIT_Roorkee_2024--25-F72585?style=for-the-badge&labelColor=1a012b" />
  <img src="https://img.shields.io/badge/%F0%9F%8F%85_Medals-50%2B-7209B7?style=for-the-badge&labelColor=1a012b" />
  <img src="https://img.shields.io/badge/%F0%9F%A5%88_Inter--IIT-2_Silver_%C2%B7_1_Bronze-FF8C00?style=for-the-badge&labelColor=1a012b" />
</div>

<!-- ░░░ FOOTER BANNER ░░░ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=18,2,6,12,24&height=140&section=footer&text=Let%27s%20build%20something%20at%20scale&fontSize=22&fontColor=ffffff&fontAlignY=70&animation=twinkling" alt="footer" />

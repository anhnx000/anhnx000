<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:38BDF8&height=220&section=header&text=Nguy%E1%BB%85n%20Xu%C3%A2n%20Anh&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Production%20AI%20Agents%20%26%20LLM%20Systems&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=640&lines=Building+AI+agents+for+an+in-car+assistant+%40+Vingroup;From+agent+design+down+to+CUDA+kernels;Latency+and+reliability+are+requirements%2C+not+metrics" alt="Typing SVG" />

<p>
  <a href="mailto:xuananhbka@gmail.com"><img src="https://img.shields.io/badge/Email-xuananhbka%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/anhnx000/"><img src="https://img.shields.io/badge/LinkedIn-anhnx000-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Hanoi-Vietnam-34A853?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

</div>

---

## 🧑‍💻 About Me

I'm **Jeremy**, an AI engineer at **Vingroup** building the AI agent layer of an in-car virtual assistant. I take LLM systems from prototype to production: agents that understand the request, pick the right tool, and answer reliably within a real latency budget.

My range runs end to end — agent architecture, async backend services, model serving, and down to **CUDA kernels on NVIDIA and AMD GPUs**. Outside work I train and deploy **Vision-Language-Action models on humanoid robots**.

<table>
  <tr>
    <td align="center" width="25%"><h3>100M</h3><sub>customer records processed<br/>in one ML pipeline</sub></td>
    <td align="center" width="25%"><h3>30×</h3><sub>faster pipeline<br/>after optimization</sub></td>
    <td align="center" width="25%"><h3>35%</h3><sub>smaller model at<br/>91% segmentation accuracy</sub></td>
    <td align="center" width="25%"><h3>🥇</h3><sub>Champion, HUST Vietnam<br/>Logistics Young Talent</sub></td>
  </tr>
</table>

---

## 💼 Experience

### Vingroup — AI Engineer · *Present*
In-car virtual assistant.
- Build AI agent capabilities that connect driver requests to vehicle features and services, with a focus on tool use, response reliability, and low-latency interaction.

### Service robotics & financial services — AI Engineer
- Designed a Vietnamese/English **robot receptionist** on LangGraph with specialized agents, RAG, and real-time mission generation.
- Streamed speech and action commands over **SSE** and parsed actions as they arrived, so the robot started moving before the full response was finished.
- Put **Cerebras, Azure OpenAI, and self-hosted vLLM** behind one interface, shipped it on Docker/Kubernetes, and added Langfuse tracing.
- Built **multi-agent and MCP systems** for enterprise use, including Text-to-SQL and services for conversation history and user feedback.

<details>
<summary><b>Earlier roles — Moreh · VinBigData · Large-scale ML</b></summary>

<br/>

**Moreh — GPU / ML Engineer**
- Optimized model kernels and benchmarked workloads across NVIDIA and AMD GPUs.

**VinBigData — AI Engineer**
- Medical imaging and driving-behavior models; MS lesion segmentation at **91% accuracy** with a **35% smaller** base model.

**Large-scale ML**
- Processed **100M customer records** for deep tagging and product matching and made the pipeline **30× faster**.

</details>

---

## 🧠 How I Build AI Systems

| | |
| :--- | :--- |
| **Agent architecture** | Intent routing, multi-agent workflows, tool use, memory, structured outputs, human-in-the-loop |
| **Latency first** | SSE streaming, acting on partial outputs, provider fallback behind a single LLM interface |
| **Observability** | Tracing every agent step with Langfuse; evaluating answers before they reach users |
| **Model serving** | vLLM / ONNX deployment, Nsight Systems profiling, kernel-level tuning when the GPU is the bottleneck |

---

## 🛠️ Tech Stack

<div align="center">

**Agents & LLMs**

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/PydanticAI-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="PydanticAI"/>
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" alt="MCP"/>
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" alt="vLLM"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant"/>
<img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square" alt="Langfuse"/>
<img src="https://img.shields.io/badge/LiveKit-FF6352?style=flat-square" alt="LiveKit"/>

**Backend & Delivery**

<img src="https://skillicons.dev/icons?i=py,fastapi,postgres,redis,docker,kubernetes,gitlab,aws,linux,bash&theme=dark" alt="Backend skills"/>

**ML, Inference & GPU**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,cpp,anaconda&theme=dark" alt="ML skills"/>
<br/>
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/>
<img src="https://img.shields.io/badge/AMD_GPU-ED1C24?style=flat-square&logo=amd&logoColor=white" alt="AMD"/>
<img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"/>
<img src="https://img.shields.io/badge/cuML_%2F_cuDF-7400B8?style=flat-square&logo=nvidia&logoColor=white" alt="RAPIDS"/>
<img src="https://img.shields.io/badge/Nsight_Systems-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Nsight"/>

**Robotics & Embodied AI**

<img src="https://skillicons.dev/icons?i=ros&theme=dark" alt="ROS"/>
<br/>
<img src="https://img.shields.io/badge/Isaac_GR00T-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Isaac GR00T"/>
<img src="https://img.shields.io/badge/LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="LeRobot"/>
<img src="https://img.shields.io/badge/Unitree_G1-111111?style=flat-square" alt="Unitree G1"/>

</div>

---

## 🚀 Featured Projects

> Most of my day-to-day work lives in private company repositories. These public repos are a sample of what I explore outside that work.

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[🤖 AI Agents Masterclass](https://github.com/anhnx000/ai-agents-masterclass)** | Working examples of agent patterns: web-search agents, custom tools, multi-step workflows. | LangGraph, PydanticAI |
| **[🔌 MCP Examples](https://github.com/anhnx000/model_context_protocol_examples)** | MCP servers and clients that expose tools and data to AI applications. | Python, MCP |
| **[🦾 Isaac GR00T](https://github.com/anhnx000/isaac-groot-anhnx)** | Training and deploying NVIDIA Isaac GR00T foundation models for humanoid robots. | PyTorch, Isaac GR00T |
| **[🦿 UnifoLM-VLA](https://github.com/anhnx000/unifolm-vla-anhnx) · [Unitree LeRobot](https://github.com/anhnx000/unitree-lerobot-anhnx)** | Vision-Language-Action training and inference, LeRobot datasets, tests on Unitree robots. | LeRobot, Unitree G1 |

---

## 🤝 Let's Connect

Open to **Senior AI Engineer**, **AI Agent Engineer**, **LLM/Backend Engineer**, and **Applied AI** roles — especially where latency and reliability are real engineering constraints.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:1E3A8A,100:0F172A&height=120&section=footer" width="100%" alt="Footer" />

</div>

<div align="center">
  <img src="./assets/hero.svg" alt="Xu Chuan — AI Infrastructure Engineer. Kubernetes, distributed training, model serving and GPU scheduling." width="100%" />

  <h3>Bringing models from training clusters to reliable, accessible production services</h3>
  <p>
    AI Infrastructure · Cloud Native · Distributed Systems<br />
    Go / Python · Kubernetes · LLM Training &amp; Inference
  </p>
  <p>
    <a href="https://github.com/MichaelXcc?tab=repositories">Explore repositories</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/MichaelXcc?tab=overview">View GitHub contributions</a>
  </p>
</div>

---

## 01 / About

I'm Xu Chuan, an engineer focused on **AI infrastructure and cloud-native platforms**. My work spans containerized model inference, multi-cluster resource scheduling, and failure recovery for large-scale distributed training. I turn complex compute infrastructure into reliable services that teams can deploy and operate.

I currently work on **Kubernetes-based training and inference platforms, GPU scheduling, observability, and privately deployed agent platforms**. My long-term goal is to make large models easier to deploy and use.

## 02 / Engineering focus

<div align="center">
  <img src="./assets/system-map.svg" alt="Engineering focus: GPU infrastructure, Kubernetes orchestration, distributed training, model serving, agent applications, and observability." width="100%" />
</div>

| Focus area | Engineering work |
| --- | --- |
| **Distributed training & resilience** | Built a recovery pipeline linking GPU Xid / DCGM fault detection, node isolation, full-job recreation, TorchElastic reconfiguration, and checkpoint restoration. Designed tiered recovery storage across local NVMe, cross-node replicas, and object storage. |
| **Model serving & platforms** | Built model inference services on Docker and Kubernetes, integrating model and image registries, autoscaling, service monitoring, and visual management. Helped bring training and inference together on one platform. |
| **Scheduling & cluster operations** | Developed cloud-native components and scheduling capabilities in Go, covering CPU / GPU resource pooling, multi-cluster management, Volcano job scheduling, and the reliability of large heterogeneous clusters. |
| **Agents & delivery** | Built privately deployed agent platform capabilities for model integration, knowledge bases, tool calling, workflows, and access control. Standardized deployment and operations for integrated hardware and software products. |

## 03 / Tech matrix

| Layer | Technologies & practices |
| --- | --- |
| **Languages & frameworks** | `Go` · `Python` · `Shell` · `Go kit` · `Django` · `Flask` · `React` |
| **Cloud native** | `Kubernetes` · `Docker` · `Istio` · `Kubeflow` · `Volcano` · `Helm` · Kubernetes controllers / operators |
| **AI infrastructure** | Distributed training · Model serving · GPU scheduling · `TorchElastic` · Checkpoint recovery · `DCGM` / GPU Xid |
| **Model ecosystem** | `vLLM` · `SGLang` · `PyTorch` · `Hugging Face` · `CUDA` |
| **Platform operations** | Multi-cluster management · CI/CD · `Jenkins` · `Argo CD` · `Prometheus` · `Grafana` · `EFK` · Security & access control |
| **Agent systems** | Model integration · Knowledge bases · Tool calling · Workflow orchestration · `Dify` · `RAGFlow` · `Bisheng` · `n8n` |

## 04 / Selected work

**Kubernetes training and inference platform**

Led the development of distributed training, online inference, GPU scheduling, and observability capabilities. Improved training recovery through fault detection, job recreation, and tiered checkpoints.

**Multi-cloud resource scheduling platform**

Built cross-region CPU / GPU resource management and scheduling from the ground up, enabling multi-cluster resource pooling and more efficient development and build workloads.

**Containerized model inference service**

Packaged model services in isolated containers and used Kubernetes for orchestration, autoscaling, and failover. Integrated model registries, image registries, and monitoring systems.

**Open source**

Contributed to [Volcano](https://github.com/volcano-sh/volcano) 1.10.0 and continue to follow cloud-native batch processing and AI job scheduling.

## 05 / Journey

| Period | Focus |
| --- | --- |
| 2019–2022 | Containerized model inference and cloud platform delivery |
| 2022–2024 | Agent data modules, CI/CD, and observability |
| 2024 | Cross-region, multi-cloud resource scheduling |
| 2025–present | AI training and inference platform architecture, distributed training resilience, and privately deployed agent platforms |

Master's degree in Software Engineering, Illinois State University.

---

<div align="center">
  <sub>Build reliable infrastructure for intelligent systems.</sub><br />
  <sub><a href="https://github.com/MichaelXcc">github.com/MichaelXcc</a></sub>
</div>

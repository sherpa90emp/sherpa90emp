<div align="center">

### Ciao! Sono **Andrea Chiappi** 👋

Junior developer

</div>

---

## 🧠 Chi sono

Ho iniziato a programmare poco più di un anno fa e da allora non ho più smesso. Mi piace prendere problemi concreti e trasformarli in software che funziona — dall'inferenza di modelli AI su hardware locale fino a dashboard full-stack per monitorare i miei container Docker.

Non sono un senior, ma ho curiosità da vedere.

---

## 🛠️ Tech Stack

| | |
|---|---|
| **Linguaggi** | Python · Java · PHP · TypeScript |
| **AI / ML** | OpenVINO · HuggingFace Transformers · FastAPI |
| **Backend** | Spring Boot · Symfony · Doctrine ORM |
| **Frontend** | Angular · Vanilla JS · SCSS · Bootstrap |
| **Infra** | Docker · Docker Compose · Nginx · MySQL |
| **Hardware** | Intel Arc B50 (GPU) · CPU fallback |

---

## ⭐ Progetti in evidenza

### 🤖 [Jarvis — Server AI Locale](https://github.com/sherpa90emp/IA_server)

Un assistente AI che gira **interamente sul mio PC server**, senza cloud. Espone un'API REST compatibile con OpenAI, usata come backend per Continue (autocompletamento nell'IDE) e per una web chat.

- **OpenVINO GenAI** per inferenza LLM/VLM su GPU Intel Arc B50 (con fallback automatico su CPU)
- **Quantizzazione personalizzata**
- **Tool calling**: lettura/modifica file, embedding
- **Streaming SSE** con gestione del blocco `<think>` per modelli reasoning (Qwen)
- Multi-GPU con policy `PIPELINE_PARALLEL` (HETERO device)

> *Python · FastAPI · OpenVINO · Uvicorn · colorama*

---

### 💰 [My Web Portafoglio](https://github.com/sherpa90emp/My_Web_Portafoglio)

Applicazione full-stack per la gestione del portafoglio finanziario personale — entrate, uscite, report. Monorepo orchestrato via Docker Compose.

- **Backend**: Java Spring Boot 3.5 — architettura layer (Controller → Service → Repository → Entity), Lombok, validazione DTO
- **Frontend**: Angular 20 (standalone components) + Bootstrap 5.3
- **Database**: MySQL 8.0
- **Deploy**: Docker Compose (Nginx + Spring Boot + MySQL)

> *Java · Spring Boot · Angular · TypeScript · MySQL · Docker*

---

### 🐳 [Info Dockers](https://github.com/sherpa90emp/info_dockers)

Dashboard web per il **monitoraggio in tempo reale dei container Docker** del server locale. Legge direttamente dal Docker socket Unix e mostra stato, durata e health di ogni container.

- **Symfony 8** con PHP 8.4 — route via attributi, method injection, DTO readonly
- **Integrazione Docker Engine** tramite cURL su `/var/run/docker.sock`
- **Doctrine ORM** con mapping via attributi PHP
- **UI**: Twig + Bootstrap 5.3
- **Stack completo in container**: nginx + php-fpm + MySQL via Docker Compose

> *PHP · Symfony · Doctrine · Twig · Docker · MySQL*

---

## 📌 Altri progetti

| Progetto | Descrizione | Stack |
|----------|-------------|-------|
| [WOL](https://github.com/sherpa90emp/WOL) | Piccola app per il lancio dal comando WakeONLan | PHP · HTML/CSS |
| [Il Garagino](https://github.com/sherpa90emp/Sito_Il_Garagino) | Sito single-page per officina specializzata nel restauro di Vespe d'epoca | HTML · SCSS · Vanilla JS · Docker |

---

## 📬 Contatti

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrea-chiappi/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sherpa90emp)

---

<div align="center">

**Sempre in movimento, sempre in costruzione.** 🚀

</div>

---
---

<div align="center">

### Hi! I'm **Andrea Chiappi** 👋

Italian junior developer

</div>

---

## 🧠 About Me

I started coding a little over a year ago and haven't stopped since. I like taking real-world problems and turning them into working software — from running AI models locally on my own hardware to building full-stack dashboards to monitor my Docker containers.

I'm not a senior yet, but I have a lot of curiosity.

---

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | Python · Java · PHP · TypeScript |
| **AI / ML** | OpenVINO · HuggingFace Transformers · FastAPI |
| **Backend** | Spring Boot · Symfony · Doctrine ORM |
| **Frontend** | Angular · Vanilla JS · SCSS · Bootstrap |
| **Infra** | Docker · Docker Compose · Nginx · MySQL |
| **Hardware** | Intel Arc B50 (GPU) · CPU fallback |

---

## ⭐ Featured Projects

### 🤖 [Jarvis — Local AI Server](https://github.com/sherpa90emp/IA_server)

An AI assistant that runs **entirely on my PC**, no cloud required. Exposes an OpenAI-compatible REST API, used as a backend for Continue (IDE autocomplete) and a web chat.

- **OpenVINO GenAI** for LLM/VLM inference on Intel Arc B50 GPU (with automatic CPU fallback)
- **Personalized quantization** via `optimum.intel`
- **Tool calling**: file read/write, embeddings
- **SSE streaming** with `think` block filtering for reasoning models (Qwen)
- Multi-GPU support with `PIPELINE_PARALLEL` policy (HETERO device)

> *Python · FastAPI · OpenVINO · Uvicorn · colorama*

---

### 💰 [My Web Portfolio](https://github.com/sherpa90emp/My_Web_Portafoglio)

Full-stack application for personal financial portfolio management — income, expenses, reports. Monorepo orchestrated via Docker Compose.

- **Backend**: Java Spring Boot 3.5 — layered architecture (Controller → Service → Repository → Entity), Lombok, DTO validation
- **Frontend**: Angular 20 (standalone components) + Bootstrap 5.3
- **Database**: MySQL 8.0
- **Deploy**: Docker Compose (Nginx + Spring Boot + MySQL)

> *Java · Spring Boot · Angular · TypeScript · MySQL · Docker*

---

### 🐳 [Info Dockers](https://github.com/sherpa90emp/info_dockers)

Web dashboard for **real-time monitoring of local Docker containers**. Reads directly from the Docker Unix socket and displays state, duration, and health of each container.

- **Symfony 8** with PHP 8.4 — attribute-based routing, method injection, readonly DTOs
- **Docker Engine integration** via cURL on `/var/run/docker.sock`
- **Doctrine ORM** with PHP attribute mapping
- **UI**: Twig + Bootstrap 5.3
- **Full stack in containers**: nginx + php-fpm + MySQL via Docker Compose

> *PHP · Symfony · Doctrine · Twig · Docker · MySQL*

---

## 📌 Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [WOL](https://github.com/sherpa90emp/WOL) | App used to launch the WakeOnLan command | PHP · HTML/CSS |
| [Il Garagino](https://github.com/sherpa90emp/Sito_Il_Garagino) | Single-page website for a vintage Vespa restoration workshop | HTML · SCSS · Vanilla JS · Docker |

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrea-chiappi/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sherpa90emp)

---

<div align="center">

**Always moving, always building.** 🚀

</div>

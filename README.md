<div align="center">

# JASWANTH SHARMA

### Backend & Applied AI · CSE Undergraduate

<br>

**I build Python pipelines that turn unstructured evidence into structured decisions,**  
**and Node.js services that handle real-time state.**

<br>

<a href="https://github.com/vu241fa04551-lgtm">
  <img src="https://img.shields.io/badge/GitHub-Profile-0d1117?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/jaswanth-sharma-machiraju-a3295036b/">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:vu.241fa04551@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</div>

---

## `01` — ABOUT

Third-year Computer Science and Engineering student at **Vignan University**.

Most of my work sits on the server side: the layer between a messy
input — an image, a claim, a socket event — and a reliable,
validated output.

Recently that has meant working with **vision-language models**:
taking non-deterministic model output and constraining it into a schema
strict enough for another system to act on, then building the evaluation
harness to check whether it actually worked.

I'm drawn to the parts of a system that fail quietly:

**retries · fallbacks · schema drift · validation · rate limits · failure modes**

The goal isn't simply to make a model or service produce an answer.

The goal is to make the **system around it trustworthy enough to use that answer.**

---

## `02` — CURRENT DIRECTION

### 🧠 Intelligent Systems

Constraining probabilistic model output into contracts that downstream
code can reliably consume.

- Structured output under a fixed taxonomy
- Multi-image and multi-signal reasoning
- Offline evaluation against ground truth
- Prompt-injection resistance on user input

`Python` · `Vision-Language Models` · `Pydantic`

---

### ⚙️ Backend Engineering

Services that hold state, remain consistent, and degrade predictably
under failure.

- Real-time transport over sockets
- Token authentication and message integrity
- Layered routes / controllers / middleware
- Rate limiting and centralized error handling

`Node.js` · `Express` · `Socket.IO` · `JWT`

---

## `03` — SELECTED WORK

### 🔬 Multi-Modal Damage Claim Verification

A system that decides whether submitted images **support, contradict,
or fail to substantiate** a damage claim by combining image analysis,
claim text, user history, and category-specific evidence requirements.

**What it demonstrates**

- Vision-language model output constrained to a fixed taxonomy
- Pydantic-validated structured output
- Multi-image reasoning per claim
- Image evidence prioritized over user-provided history
- Prompt-injection guarding on user-supplied claim text
- Exponential-backoff retries around a paid API
- Rate limiting for external model calls
- Separate offline evaluation against ground truth
- Evaluation without additional API cost

**Stack**

`Python` `Vision-Language Models` `Pydantic` `pandas`

**Repository**

→ [Multi-Modal-Evidence](https://github.com/vu241fa04551-lgtm/Multi-Modal-Evidence)

---

### 👁️ WINK — Browser-Based Proctored Exam Platform

An end-to-end examination platform where candidates authenticate,
complete timed examinations under live face tracking, and receive
performance results and certificates.

**What it demonstrates**

- Client-side proctoring with MediaPipe FaceMesh
- Violation recording per examination attempt
- Express backend architecture
- Sequelize persistence with SQLite
- Performance dashboard with Chart.js
- Score, accuracy, and violation analytics
- Local-first architecture without a third-party proctoring service

**Stack**

`Node.js` `Express` `Sequelize` `SQLite` `MediaPipe` `Chart.js`

**Repository**

→ [WINK](https://github.com/vu241fa04551-lgtm/wink)

---

### 💬 Real-Time Chat API

A messaging backend built around Socket.IO with JWT authentication,
encrypted message content, media uploads, and push delivery for
offline users.

**What it demonstrates**

- Layered routes, controllers, middleware, and socket handlers
- JWT-based authentication
- AES-encrypted message content
- Utility-level encryption before persistence
- Firebase Cloud Messaging for offline delivery
- Multer-backed media uploads
- Request rate limiting
- Centralized error handling
- Consistent API failure responses

**Stack**

`Node.js` `Express` `Socket.IO` `JWT` `Firebase` `Multer`

**Repository**

→ [chat-app-backend](https://github.com/vu241fa04551-lgtm/chat-app-backend)

---

### 🧠 Additional AI & Agentic Work

I also experiment with multi-agent and orchestration architectures,
including work exploring how complex objectives can be decomposed,
coordinated, executed, and evaluated.

Some of this work is currently private.

Architecture discussions and technical walkthroughs are available
on request.

---

## `04` — STACK

### Languages

`Python` · `JavaScript`

### Backend

`Node.js` · `Express` · `Socket.IO` · `REST APIs`

### AI / Data

`Vision-Language Models` · `Pydantic` · `pandas` · `MediaPipe`

### Storage

`MongoDB` · `Mongoose` · `SQLite` · `Sequelize` · `Firebase`

### Frontend

`HTML` · `CSS` · `Tailwind CSS` · `Chart.js`

### Tools

`Git` · `GitHub` · `Postman` · `npm`

> Listed because they appear in shipped work — not because they are on a résumé template.

---

## `05` — ENGINEERING INTERESTS

```text
SYSTEM DESIGN
      ↓
API CONTRACTS
      ↓
VALIDATION
      ↓
FAILURE MODES
      ↓
OBSERVABILITY
      ↓
EVALUATION
      ↓
RELIABLE SOFTWARE

I'm particularly interested in the boundary between:

probabilistic systems → deterministic software

and how engineering practices can make that boundary safer,
measurable, and easier to reason about.

06 — CURRENTLY
Deepening  →  system design, API contracts, failure modes

Building   →  evaluation harnesses for non-deterministic output

Exploring  →  agent architectures and tool-use patterns

Improving  →  backend architecture and production-oriented practices

Open to    →  backend and AI/ML internships
07 — GITHUB
<div align="center"> <a href="https://github.com/vu241fa04551-lgtm?tab=repositories"> <img src="https://img.shields.io/badge/Explore%20all%20repositories-0d1117?style=for-the-badge&logo=github&logoColor=white" > </a>

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=vu241fa04551-lgtm&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&include_all_commits=true" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vu241fa04551-lgtm&layout=compact&hide_border=true&theme=transparent" height="170" />

</div>
08 — DEVELOPMENT PHILOSOPHY
Don't just make it work.

Understand why it works.
Understand how it fails.
Make the failure visible.
Validate the assumptions.
Then make it reliable.
09 — CONTACT

Open to collaborating on projects involving:

Backend Systems · Applied AI · Agentic Systems · Developer Tools

<br> <div align="center"> <a href="https://github.com/vu241fa04551-lgtm"> <img src="https://img.shields.io/badge/GitHub-vu241fa04551--lgtm-0d1117?style=for-the-badge&logo=github&logoColor=white"> </a> <a href="https://www.linkedin.com/in/jaswanth-sharma-machiraju-a3295036b/"> <img src="https://img.shields.io/badge/LinkedIn-Jaswanth%20Sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"> </a> <a href="mailto:vu.241fa04551@gmail.com"> <img src="https://img.shields.io/badge/Email-vu.241fa04551%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"> </a> </div>
<div align="center">
BUILD · EVALUATE · ITERATE
<br> <sub> Thanks for visiting. </sub> </div> ```
Final rating of this version
Area	Score
First impression	9.7/10
Technical credibility	9.8/10
Recruiter readability	9.5/10
Project presentation	9.8/10
AI positioning	9.6/10
Backend positioning	9.8/10
Visual design	9.2/10
Authenticity	9.8/10
Overall	9.6/10

I would not make it more flashy than this. The unusual part of your profile is the engineering specificity—schema validation, evaluation, retries, failure modes, real-time state—not animations or a wall of badges. That is what will make a technically competent recruiter stop and read.

<div align="center">

# JASWANTH SHARMA

### Backend & Applied AI · CSE Undergraduate

<br>

**I build Python pipelines that turn unstructured evidence into structured decisions,**  
**and Node.js services that handle real-time state.**

<br>

<a href="https://github.com/vu241fa04551-lgtm">
  <img src="https://img.shields.io/badge/GitHub-Profile-0d1117?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/jaswanth-sharma-machiraju-a3295036b/">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:vu.241fa04551@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</div>

---

## 01 — ABOUT

Third-year Computer Science and Engineering student at **Vignan University**.

Most of my work sits on the server side: the layer between a messy
input — an image, a claim, a socket event — and a reliable,
validated output.

Recently that has meant working with **vision-language models**:
taking non-deterministic model output and constraining it into a schema
strict enough for another system to act on, then building the evaluation
harness to check whether it actually worked.

I'm drawn to the parts of a system that fail quietly:

**retries · fallbacks · schema drift · validation · rate limits · failure modes**

The goal isn't simply to make a model or service produce an answer.

The goal is to make the **system around it trustworthy enough to use that answer.**

---

## 02 — CURRENT DIRECTION

### 🧠 Intelligent Systems

Constraining probabilistic model output into contracts that downstream
code can reliably consume.

- Structured output under a fixed taxonomy
- Multi-image and multi-signal reasoning
- Offline evaluation against ground truth
- Prompt-injection resistance on user input

Python · Vision-Language Models · Pydantic

---

### ⚙️ Backend Engineering

Services that hold state, remain consistent, and degrade predictably
under failure.

- Real-time transport over sockets
- Token authentication and message integrity
- Layered routes / controllers / middleware
- Rate limiting and centralized error handling

Node.js · Express · Socket.IO · JWT

---

## 03 — SELECTED WORK

### 🔬 Multi-Modal Damage Claim Verification

A system that decides whether submitted images **support, contradict,
or fail to substantiate** a damage claim by combining image analysis,
claim text, user history, and category-specific evidence requirements.

**What it demonstrates**

- Vision-language model output constrained to a fixed taxonomy
- Pydantic-validated structured output
- Multi-image reasoning per claim
- Image evidence prioritized over user-provided history
- Prompt-injection guarding on user-supplied claim text
- Exponential-backoff retries around a paid API
- Rate limiting for external model calls
- Separate offline evaluation against ground truth
- Evaluation without additional API cost

**Stack**

Python Vision-Language Models Pydantic pandas

**Repository**

→ [Multi-Modal-Evidence](https://github.com/vu241fa04551-lgtm/Multi-Modal-Evidence)

---

### 👁️ WINK — Browser-Based Proctored Exam Platform

An end-to-end examination platform where candidates authenticate,
complete timed examinations under live face tracking, and receive
performance results and certificates.

**What it demonstrates**

- Client-side proctoring with MediaPipe FaceMesh
- Violation recording per examination attempt
- Express backend architecture
- Sequelize persistence with SQLite
- Performance dashboard with Chart.js
- Score, accuracy, and violation analytics
- Local-first architecture without a third-party proctoring service

**Stack**

Node.js Express Sequelize SQLite MediaPipe Chart.js

**Repository**

→ [WINK](https://github.com/vu241fa04551-lgtm/wink)

---

### 💬 Real-Time Chat API

A messaging backend built around Socket.IO with JWT authentication,
encrypted message content, media uploads, and push delivery for
offline users.

**What it demonstrates**

- Layered routes, controllers, middleware, and socket handlers
- JWT-based authentication
- AES-encrypted message content
- Utility-level encryption before persistence
- Firebase Cloud Messaging for offline delivery
- Multer-backed media uploads
- Request rate limiting
- Centralized error handling
- Consistent API failure responses

**Stack**

Node.js Express Socket.IO JWT Firebase Multer

**Repository**

→ [chat-app-backend](https://github.com/vu241fa04551-lgtm/chat-app-backend)

---

### 🧠 Additional AI & Agentic Work

I also experiment with multi-agent and orchestration architectures,
including work exploring how complex objectives can be decomposed,
coordinated, executed, and evaluated.

Some of this work is currently private.

Architecture discussions and technical walkthroughs are available
on request.

---

## 04 — STACK

### Languages

Python · JavaScript

### Backend

Node.js · Express · Socket.IO · REST APIs

### AI / Data

Vision-Language Models · Pydantic · pandas · MediaPipe

### Storage

MongoDB · Mongoose · SQLite · Sequelize · Firebase

### Frontend

HTML · CSS · Tailwind CSS · Chart.js

### Tools

Git · GitHub · Postman · npm

> Listed because they appear in shipped work — not because they are on a résumé template.

---

## 05 — ENGINEERING INTERESTS


text
SYSTEM DESIGN
      ↓
API CONTRACTS
      ↓
VALIDATION
      ↓
FAILURE MODES
      ↓
OBSERVABILITY
      ↓
EVALUATION
      ↓
RELIABLE SOFTWARE

Yes — this version is already strong. I would keep the technical direction, but I would not publish it exactly as pasted.

The biggest issue is that the README stops at ENGINEERING INTERESTS; if this is your complete profile README, it needs a polished ending and a few small refinements.

Here is the complete final version in one code block, continuing and tightening what you have:

<div align="center">

# JASWANTH SHARMA

### Backend & Applied AI · CSE Undergraduate

<br>

**I build Python pipelines that turn unstructured evidence into structured decisions,**  
**and Node.js services that handle real-time state.**

<br>

<a href="https://github.com/vu241fa04551-lgtm">
  <img src="https://img.shields.io/badge/GitHub-Profile-0d1117?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/jaswanth-sharma-machiraju-a3295036b/">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:vu.241fa04551@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</div>

---

## `01` — ABOUT

Third-year Computer Science and Engineering student at **Vignan University**.

Most of my work sits on the server side: the layer between a messy
input — an image, a claim, a socket event — and a reliable,
validated output.

Recently that has meant working with **vision-language models**:
taking non-deterministic model output and constraining it into a schema
strict enough for another system to act on, then building the evaluation
harness to check whether it actually worked.

I'm drawn to the parts of a system that fail quietly:

**retries · fallbacks · schema drift · validation · rate limits · failure modes**

The goal isn't simply to make a model or service produce an answer.

The goal is to make the **system around it trustworthy enough to use that answer.**

---

## `02` — CURRENT DIRECTION

### 🧠 Intelligent Systems

Constraining probabilistic model output into contracts that downstream
code can reliably consume.

- Structured output under a fixed taxonomy
- Multi-image and multi-signal reasoning
- Offline evaluation against ground truth
- Prompt-injection resistance on user input

`Python` · `Vision-Language Models` · `Pydantic`

---

### ⚙️ Backend Engineering

Services that hold state, remain consistent, and degrade predictably
under failure.

- Real-time transport over sockets
- Token authentication and message integrity
- Layered routes / controllers / middleware
- Rate limiting and centralized error handling

`Node.js` · `Express` · `Socket.IO` · `JWT`

---

## `03` — SELECTED WORK

### 🔬 Multi-Modal Damage Claim Verification

A system that decides whether submitted images **support, contradict,
or fail to substantiate** a damage claim by combining image analysis,
claim text, user history, and category-specific evidence requirements.

**What it demonstrates**

- Vision-language model output constrained to a fixed taxonomy
- Pydantic-validated structured output
- Multi-image reasoning per claim
- Image evidence prioritized over user-provided history
- Prompt-injection guarding on user-supplied claim text
- Exponential-backoff retries around a paid API
- Rate limiting for external model calls
- Separate offline evaluation against ground truth
- Evaluation without additional API cost

**Stack**

`Python` · `Vision-Language Models` · `Pydantic` · `pandas`

**Repository**

→ [Multi-Modal-Evidence](https://github.com/vu241fa04551-lgtm/Multi-Modal-Evidence)

---

### 👁️ WINK — Browser-Based Proctored Exam Platform

An end-to-end examination platform where candidates authenticate,
complete timed examinations under live face tracking, and receive
performance results and certificates.

**What it demonstrates**

- Client-side proctoring with MediaPipe FaceMesh
- Violation recording per examination attempt
- Express backend architecture
- Sequelize persistence with SQLite
- Performance dashboard with Chart.js
- Score, accuracy, and violation analytics
- Local-first architecture without a third-party proctoring service

**Stack**

`Node.js` · `Express` · `Sequelize` · `SQLite` · `MediaPipe` · `Chart.js`

**Repository**

→ [WINK](https://github.com/vu241fa04551-lgtm/wink)

---

### 💬 Real-Time Chat API

A messaging backend built around Socket.IO with JWT authentication,
encrypted message content, media uploads, and push delivery for
offline users.

**What it demonstrates**

- Layered routes, controllers, middleware, and socket handlers
- JWT-based authentication
- AES-encrypted message content
- Utility-level encryption before persistence
- Firebase Cloud Messaging for offline delivery
- Multer-backed media uploads
- Request rate limiting
- Centralized error handling
- Consistent API failure responses

**Stack**

`Node.js` · `Express` · `Socket.IO` · `JWT` · `Firebase` · `Multer`

**Repository**

→ [chat-app-backend](https://github.com/vu241fa04551-lgtm/chat-app-backend)

---

### 🧠 Additional AI & Agentic Work

I also experiment with multi-agent and orchestration architectures,
including work exploring how complex objectives can be decomposed,
coordinated, executed, and evaluated.

Some of this work is currently private.

Architecture discussions and technical walkthroughs are available
on request.

---

## `04` — STACK

### Languages

`Python` · `JavaScript`

### Backend

`Node.js` · `Express` · `Socket.IO` · `REST APIs`

### AI / Data

`Vision-Language Models` · `Pydantic` · `pandas` · `MediaPipe`

### Storage

`MongoDB` · `Mongoose` · `SQLite` · `Sequelize` · `Firebase`

### Frontend

`HTML` · `CSS` · `Tailwind CSS` · `Chart.js`

### Tools

`Git` · `GitHub` · `Postman` · `npm`

> Listed because they appear in shipped work — not because they are on a résumé template.

---

## `05` — ENGINEERING INTERESTS

```text
SYSTEM DESIGN
      ↓
API CONTRACTS
      ↓
VALIDATION
      ↓
FAILURE MODES
      ↓
OBSERVABILITY
      ↓
EVALUATION
      ↓
RELIABLE SOFTWARE

I'm particularly interested in the boundary between:

probabilistic systems → deterministic software

and how engineering practices can make that boundary safer,
measurable, and easier to reason about.

06 — CURRENTLY
Deepening  →  system design, API contracts, failure modes

Building   →  evaluation harnesses for non-deterministic output

Exploring  →  agent architectures and tool-use patterns

Improving  →  backend architecture and production-oriented practices

Open to    →  backend and AI/ML internships
07 — DEVELOPMENT PHILOSOPHY
Don't just make it work.

Understand why it works.
Understand how it fails.
Make the failure visible.
Validate the assumptions.
Then make it reliable.
08 — GITHUB
<div align="center"> <a href="https://github.com/vu241fa04551-lgtm?tab=repositories"> <img src="https://img.shields.io/badge/Explore%20Repositories-0d1117?style=for-the-badge&logo=github&logoColor=white" > </a>

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=vu241fa04551-lgtm&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&include_all_commits=true" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vu241fa04551-lgtm&layout=compact&hide_border=true&theme=transparent" height="170" />

</div>
09 — CONTACT

Open to collaborating on projects involving:

Backend Systems · Applied AI · Agentic Systems · Developer Tools

<br> <div align="center"> <a href="https://github.com/vu241fa04551-lgtm"> <img src="https://img.shields.io/badge/GitHub-vu241fa04551--lgtm-0d1117?style=for-the-badge&logo=github&logoColor=white"> </a> <a href="https://www.linkedin.com/in/jaswanth-sharma-machiraju-a3295036b/"> <img src="https://img.shields.io/badge/LinkedIn-Jaswanth%20Sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"> </a> <a href="mailto:vu.241fa04551@gmail.com"> <img src="https://img.shields.io/badge/Email-vu.241fa04551%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"> </a> </div>
<div align="center">
BUILD · EVALUATE · ITERATE

<sub>Thanks for visiting.</sub>

</div> ``

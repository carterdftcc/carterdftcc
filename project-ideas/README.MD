# Project Ideation – Darryl Carter — Version 3.0

### Idea 1: Security+ Study Chatbot

**Problem/Goal:**

Students need quick, accurate answers to exam‑style prompts with links to official objectives. Build a chatbot that answers succinctly, cites the relevant objective ID, and recommends 1–2 follow‑up practice items.

**AI Tool(s):**

Local model via Ollama.

**Why This Interests Me:**

Normally, we refer students to several different references to study for the CompTIA Security+. By creating this chatbot, students will have access to a large question bank in one place in a web‑based format.

**Rough Scope:**

2–3 weeks

---

### Idea 2: Security+ Flashcard Generator + Spaced Repetition

**Problem/Goal:**

Convert notes or PDFs into flashcards tagged by domain and objective, with easy export to CSV/Anki.

**AI Tool(s):**

OpenAI in a client‑side web app.

**Why This Interests Me:**

When I first took SEC110, this was the method I used to memorize and identify terms and definitions. I think learners will take less time per question if they are looking for the correct answer rather than weighing each option for the best answer. That is what Idea 1 is for. I actually prefer this method to just taking tests over and over again.

**Rough Scope:**

1–2 weeks

---

### Idea 3: Incident Triage Simulator + Evidence Packs (Written Performance‑Based Question)

**Problem/Goal:**

Learners often know terms but can’t read real artifacts. Create timed micro‑scenarios that function as a written performance‑based question where students analyze 2–3 “evidence packs” (auth logs, firewall drops, TLS certificate details, email headers, short PCAP text) and answer a Security+‑style question. They must also select which evidence supports their choice. The tool scores both the answer and the evidence mapping, then explains why alternatives are wrong.

**AI Tool(s):**

LLM to generate scenario variations and rationales. Small RAG over Security+ objectives to tag items and cite objective IDs. Lightweight rules to validate evidence selections.

**Why This Interests Me:**

Most students have never seen real artifacts. They are presented with outputs from routers, switches, servers, and other equipment on these exams and often say they have never seen anything like it. This will help remedy that problem. The tests are designed for people with real industry experience, but this will give learners an advantage.

**Rough Scope:**

2–3 weeks

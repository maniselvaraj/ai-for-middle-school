# Generative AI for 7th Graders — 8-Week Syllabus

**Audience:** 3 students, 7th grade, no coding or computer science background
**Format:** 1 hour per week, 8 sessions
**Philosophy:** Programming is a dying art — the goal is NOT to teach programming. The goal is to teach Gen AI and vibe coding so kids can build software applications or games on their own.

---

## Overview

| Phase | Week | Theme | Tagline |
|-------|------|-------|---------|
| **Basics** | 1 | How Computers & Programs Work | "From clicks to code" |
| **Basics** | 2 | How the Internet & Apps Work | "What happens when you open a website" |
| **Basics** | 3 | ML, AI, and Gen AI | "Teaching machines with math they already know" |
| **Intermediate** | 4 | Neural Networks & the Brain | "How machines learn like we do" |
| **Intermediate** | 5 | LLMs & GPT — How AI Writes | "The world's biggest autocomplete" |
| **Intermediate** | 6 | Prompt Engineering | "Talking to AI like a pro" |
| **Advanced** | 7 | Vibe Coding — Build a Web App | "Describe it, and AI builds it" |
| **Advanced** | 8 | Capstone Project | "Ship it" |

---

# Phase 1: Basics (Weeks 1–3)

---

## Week 1 — How Computers & Programs Work *(From clicks to code)*

### Learning Goals
- Understand what a computer program is at a high level (without writing code)
- See that all software is just instructions a computer follows
- Learn what a video game is made of under the hood

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Icebreaker:** Each student describes a set of instructions they follow every day (recipe, game rules, morning routine). What happens when you skip a step? |
| 0:10–0:25 | **Mini-lecture:** What is a computer program? It's a recipe for a computer. Walk through: input → processing → output. Show a simple example: calculator app (input: numbers, processing: math, output: answer). Introduce the idea that all apps — Instagram, Google, Minecraft — are just very long recipes. |
| 0:25–0:40 | **Activity — "Program the Teacher":** Students write step-by-step instructions (in plain English) to make the teacher draw a house on the whiteboard. Teacher follows instructions literally. Hilarity when instructions are ambiguous. Lesson: computers need precise instructions. |
| 0:40–0:52 | **Video game teardown:** Pick a game they all know (e.g., Minecraft). What are the pieces? (1) Graphics — what you see, (2) Game logic — rules of the world, (3) Input handling — keyboard/mouse, (4) Sound. Then ask: what changes when the game is online with other players? Introduce the idea of a server that keeps everyone in sync. |
| 0:52–1:00 | **Wrap-up:** What surprised you? One sentence: "A computer program is _____ because _____." |

### Key Concepts Introduced
- Program, input/output, instructions, game logic, graphics engine, multiplayer server

### Homework / Between Sessions
- Pick any app or game you use. Try to list the "invisible instructions" it must be following. Example: "When I swipe right on a photo, it shows the next one."

---

## Week 2 — How the Internet & Apps Work *(What happens when you open a website)*

### Learning Goals
- Understand how the internet works at a basic level
- Learn the three parts of a software application: frontend, backend, and database
- See how these parts connect in apps they use every day

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Homework debrief:** Share "invisible instructions" lists. Discuss patterns — most apps have a visual part and a behind-the-scenes part. |
| 0:10–0:25 | **Mini-lecture — How the Internet Works:** Analogy: the internet is a postal system. Your computer writes a letter (request), addresses it (URL/IP address), sends it through the mail system (network), and a server reads it and sends a reply. Show a browser → "View Source" on a simple page. Briefly mention: Wi-Fi, routers, servers, data centers. |
| 0:25–0:40 | **Mini-lecture — The 3 Parts of an App:** Draw on the whiteboard: (1) **Frontend** — what you see and click (the app on your phone or the website), (2) **Backend** — the brain that processes requests (the server), (3) **Database** — the memory that stores everything (your posts, your scores, your profile). Walk through a real example: "When you post on Instagram — your phone (frontend) sends the photo to Instagram's server (backend), which saves it in their database. When your friend opens Instagram, their phone asks the server, which pulls it from the database." |
| 0:40–0:52 | **Activity — "Build an App on Paper":** Each student picks an app idea (e.g., a quiz app, a messaging app, a scoreboard). On paper, they draw three boxes (Frontend, Backend, Database) and write what goes in each. Present to the group. |
| 0:52–1:00 | **Wrap-up:** "Every app you use has these three parts. Even the ones that feel magical." Preview: next week we learn how AI fits into this picture. |

### Key Concepts Introduced
- Internet, request/response, URL, server, frontend, backend, database
- Client-server model (without the jargon — "your phone asks, the server answers")

### Homework / Between Sessions
- Open any website, right-click → "View Page Source." Don't try to understand it — just notice how much hidden code is behind a simple page. Screenshot it.

---

## Week 3 — ML, AI, and Gen AI *(Teaching machines with math they already know)*

### Learning Goals
- Understand the difference between AI, Machine Learning (ML), and Generative AI (Gen AI)
- Learn ML through linear regression — they already know algebra (y = mx + b)
- Understand the ML lifecycle: training, testing, and inference

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Warm-up discussion:** "What do you think AI is?" Collect answers. Most people confuse AI, ML, and Gen AI — let's untangle them. |
| 0:10–0:20 | **Mini-lecture — AI vs. ML vs. Gen AI:** Draw a nested circle diagram: **AI** (big circle — any machine that seems smart: chess programs, Siri, spam filters) → **ML** (smaller circle — machines that learn from data instead of being manually programmed) → **Gen AI** (smallest circle — ML models that can generate new content: text, images, code). Key message: All Gen AI is ML, all ML is AI, but not the other way around. |
| 0:20–0:40 | **Activity — ML with Linear Regression:** "You already know y = mx + b from algebra. That's the simplest ML model." Give students a table: hours studied vs. test score (made-up data). Plot it on graph paper. Draw a best-fit line. Use the line to predict: "If someone studies 7 hours, what score will they get?" That's **inference**. Explain: **Training** = finding the line that fits the data. **Testing** = checking if the line works on new data. **Inference** = using the line to make predictions. Walk through the idea: ML training is just finding the best m and b so the line fits the data. |
| 0:40–0:52 | **Demo — Teachable Machine:** Use Google's Teachable Machine to train an image classifier live. Students add photos, train, test. Connect it back: "This is doing the same thing as our line — finding patterns in data — but with images instead of numbers." |
| 0:52–1:00 | **Wrap-up:** "ML is finding patterns. AI is the big umbrella. Gen AI is when the patterns are good enough to create something new." |

### Key Concepts Introduced
- AI, Machine Learning, Generative AI — and how they nest
- Linear regression as the simplest ML model
- Training, testing, inference
- y = mx + b → prediction

### Homework / Between Sessions
- Ask ChatGPT: "Explain machine learning like I'm in 7th grade." Then ask: "Now explain it like I'm a scientist." Compare the two answers. Which prompt got a better response for you?

---

# Phase 2: Intermediate (Weeks 4–6)

---

## Week 4 — Neural Networks & the Brain *(How machines learn like we do)*

### Learning Goals
- Understand what a neural network is by relating it to the human brain
- Learn how neural networks learn, retain knowledge, and make predictions
- Build on linear regression to see how neural networks handle complex patterns

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Homework debrief:** Compare ChatGPT answers (7th grader vs. scientist). Discuss: same AI, same knowledge, different prompt → different output. How does it "know" how to adjust? |
| 0:10–0:25 | **Mini-lecture — From Lines to Brains:** "Last week we drew a straight line through data. But what if the pattern isn't a straight line?" Show a curvy scatter plot. "We need something more powerful. Enter: neural networks." **The brain analogy:** Your brain has ~86 billion neurons connected by synapses. When you learn something, certain connections get stronger. A neural network is the same idea in software: (1) **Neurons** — tiny math functions that take inputs and produce outputs, (2) **Connections (weights)** — how strongly one neuron influences another, (3) **Learning** — adjusting the weights until the network gets good at the task. Show a simple diagram: input layer → hidden layer → output layer. |
| 0:25–0:40 | **Activity — "Human Neural Network":** Three students form a network. Student A gets an input (a number or word), passes a modified version to Student B, who passes a modified version to Student C, who gives the final answer. Teacher says "wrong" or "right." Students adjust their rules. After several rounds, the "network" starts getting it right. Debrief: "You just did what a neural network does — adjusted your rules based on feedback." |
| 0:40–0:52 | **Visual demo:** Use TensorFlow Playground (playground.tensorflow.org) to show a neural network learning in real time. Students click "play" and watch it solve a classification problem. Adjust neurons and layers — what changes? |
| 0:52–1:00 | **Wrap-up:** "A neural network learns by adjusting its connections, just like your brain strengthens pathways when you practice something." Preview: "Next week — what happens when you make a neural network REALLY big and feed it the entire internet?" |

### Key Concepts Introduced
- Neural network, neuron, weights, layers (input, hidden, output)
- Training = adjusting weights based on feedback
- Neural networks as pattern finders for complex data
- Connection to the human brain: neurons, synapses, learning through repetition

### Homework / Between Sessions
- Try TensorFlow Playground at home. Can you get it to solve the spiral pattern? How many layers and neurons did it take?

---

## Week 5 — LLMs & GPT — How AI Writes *(The world's biggest autocomplete)*

### Learning Goals
- Understand what LLM and GPT stand for — and what each word means
- Learn the difference between autoencoding models (understanding) and autoregressive models (generation)
- Understand tokens, context, and why LLMs hallucinate
- Build healthy skepticism about AI outputs

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Warm-up game:** Teacher starts a sentence, students complete it. Do it 5 times. "How did you decide what came next?" (Pattern, context, what sounded right.) "Congrats — you just did what an LLM does." |
| 0:10–0:25 | **Mini-lecture — What LLM and GPT Mean:** Break down each word: **LLM = Large Language Model.** *Large* — billions of parameters (weights), trained on huge amounts of text. *Language* — it works with text (words, sentences). *Model* — a neural network that has learned patterns. **GPT = Generative Pre-trained Transformer.** *Generative* — it creates new text. *Pre-trained* — it learned from data before you ever used it. *Transformer* — the specific type of neural network architecture (the breakthrough that made this all work). |
| 0:25–0:40 | **Mini-lecture — Two Kinds of Language Models:** (1) **Autoencoding models** (like BERT) — they read text and *understand* it. Used for: classifying emails as spam, understanding search queries, summarizing. Think of it as a reader. (2) **Autoregressive models** (like GPT) — they generate text one word at a time by predicting what comes next. Used for: writing essays, chatbots, code generation. Think of it as a writer. Key insight: ChatGPT and Claude are autoregressive — they're writing one word at a time, always asking "what word should come next?" Show a simple visualization of next-token prediction. |
| 0:40–0:52 | **Activity — Spot the Hallucination:** Give each student 3 ChatGPT responses about a topic they know well (their school, a sports team, a TV show). Find the mistakes. Discuss: *why* does an autoregressive model make things up? (Because it predicts what *sounds* right, not what *is* right.) |
| 0:52–1:00 | **Wrap-up:** One sentence each: "An LLM is like _____ because _____." Preview prompt engineering next week. |

### Key Concepts Introduced
- LLM: Large Language Model — what each word means
- GPT: Generative Pre-trained Transformer — what each word means
- Autoencoding (understanding/reading) vs. autoregressive (generating/writing)
- Tokens, next-token prediction, hallucination
- LLMs are probabilistic, not encyclopedias

### Homework / Between Sessions
- Find one example of AI confidently saying something wrong. Screenshot it. Also: ask ChatGPT "Are you an autoregressive model?" and see what it says.

---

## Week 6 — Prompt Engineering *(Talking to AI like a pro)*

### Learning Goals
- Understand that *how* you ask matters as much as *what* you ask
- Write clear, specific, role-based prompts
- Use AI to build a presentation or school report
- Learn to provide additional context (files, examples) for better results

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Share hallucination screenshots.** Discuss: could a better prompt have prevented the mistake? |
| 0:10–0:20 | **Mini-lecture — The 4 Levers of a Good Prompt:** (1) **Role** ("You are a..."), (2) **Context** ("I'm a 7th grader who..."), (3) **Task** ("Write / explain / list / create..."), (4) **Format** ("Use bullet points / keep it under 100 words / make a table"). Demo: show a bad prompt → mediocre output. Apply the 4 levers → much better output. |
| 0:20–0:35 | **Prompt Battle:** All three students get the same bad prompt. They rewrite it using the 4 levers. Each submits to ChatGPT/Claude. Read outputs aloud. Which prompt won? Why? Run 3 rounds with different topics. |
| 0:35–0:50 | **Activity — Build Something Real with Prompts:** Option A: Each student uses prompt engineering to create a short presentation (5 slides) on a topic of their choice. Option B: Each student uploads/pastes a source text (article, notes, textbook page) and prompts AI to create a school report from it. Key lesson: providing **additional context** (files, reference text, examples) dramatically improves AI output. Show: same prompt with and without context — compare results. |
| 0:50–0:58 | **Debrief:** What worked? What was the difference when you gave AI more context? |
| 0:58–1:00 | **Preview:** "Next week, we use these same skills to build a real web application — by describing what we want, and letting AI write the code." |

### Key Concepts Introduced
- Prompt, role prompting, zero-shot vs. few-shot, chain prompting
- The 4 levers: Role, Context, Task, Format
- Using additional context (files, reference material) for better outputs
- AI as a tool — the human directs it

### Homework / Between Sessions
- Use prompt engineering to create one useful thing: a study guide, a presentation, or a summary of something you're learning in school. Bring it next week. Also: start thinking about what app or game you want to build for your capstone project.

---

# Phase 3: Advanced (Weeks 7–8)

---

## Week 7 — Vibe Coding — Build a Web App *(Describe it, and AI builds it)*

### Learning Goals
- Experience "vibe coding" — describing what you want in plain English, letting AI generate code
- Build a working web application without memorizing any syntax
- Understand that you are the architect; AI is the builder

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:10 | **Share homework creations** (study guides, presentations). Discuss what worked. Transition: "Today we go from writing documents to building software — using the same prompting skills." |
| 0:10–0:20 | **What is vibe coding?** Brief discussion: Andrej Karpathy coined it — you describe what you want, AI writes the code, you tweak and iterate. You don't need to memorize syntax. You DO need to understand what you're building (frontend, backend, database — remember Week 2?) and communicate clearly (prompt engineering — remember Week 6?). |
| 0:20–0:50 | **Guided vibe coding session:** Using Claude or ChatGPT + Replit (or similar tool), build a simple web app together as a class. Example: a quiz app or a personal homepage. Steps: (1) Write a prompt describing the app, (2) Paste the AI-generated code into Replit, (3) Run it — see what works and what breaks, (4) Ask AI to explain one part of the code, (5) Ask AI to change one thing (color, layout, feature), (6) Iterate. Each student then starts adapting it into their own version or begins their capstone idea. |
| 0:50–0:58 | **Debrief:** What worked? What was confusing? What did you want AI to do that it couldn't? |
| 0:58–1:00 | **Capstone prep:** "Next week is your final project. Pick your idea, refine your prompt, and come ready to build and present." |

### Key Concepts Introduced
- Vibe coding, iteration, reading code you didn't write
- Connecting earlier concepts: frontend/backend/database + prompt engineering + AI generation
- Debugging with AI: "here's my code, here's the error, fix it"
- Human-in-the-loop: you own the direction, AI owns the syntax

### Tools
- **Claude** (claude.ai) or **ChatGPT** for code generation
- **Replit** (replit.com) for running code in the browser
- **v0.dev** or **bolt.new** for instant web app prototyping (optional)

### Homework / Between Sessions
- Finalize your capstone idea. Write a detailed prompt using the 4 levers. Try generating a first version of code and bring it (working or broken) to next week.

---

## Week 8 — Capstone Project *(Ship it)*

### Learning Goals
- Complete a working project, however small
- Present it with confidence
- Reflect on what was learned across 8 weeks

### Hour Breakdown

| Time | Activity |
|------|----------|
| 0:00–0:25 | **Build time + teacher office hours:** Students finalize their projects. Teacher circulates and helps. Use AI to fix bugs, add features, polish. This is vibe coding in action — keep prompting, keep iterating. |
| 0:25–0:50 | **Presentations (~8 min each):** Each student presents: (1) What did you build? (2) Show it working. (3) What prompt started it? (4) What was the hardest part? (5) What would you add with more time? |
| 0:50–0:58 | **Group reflection:** What is AI good at? What is it bad at? What should humans always be in charge of? What surprised you most over these 8 weeks? |
| 0:58–1:00 | **Celebration + next steps:** Resources to keep going. "You now understand how AI works, how apps work, and how to use AI to build things. That's a real skill." |

### Capstone Project Ideas (student picks one or proposes their own)

| Idea | Complexity | Tool |
|------|------------|------|
| Quiz game on any topic | Low | Replit |
| Personal homepage / portfolio | Low | Replit or v0.dev |
| Interactive story with choices | Medium | Replit |
| Simple chatbot about a topic they love | Medium | Claude API |
| Multiplayer scoreboard or leaderboard | Medium | Replit |
| "Explain it to me" tool (simplifies any text) | Medium | Claude API |
| Animated drawing or mini-game | Medium | p5.js |

---

## Assessment

This is a **no-grade, progress-based** course. Assessment is observational:

| What to Watch For | How |
|-------------------|-----|
| Engagement and curiosity | Do they ask unprompted questions? |
| Conceptual understanding | Can they explain AI/ML/LLM to each other? |
| Prompt quality over time | Compare Week 6 prompts to Week 3 homework |
| Ability to use AI as a tool | Can they get AI to do what they want? |
| Capstone completion | Did they ship *something*? |

---

## Materials & Tools

| Tool | Purpose | Cost |
|------|---------|------|
| [Teachable Machine](https://teachablemachine.withgoogle.com) | Train an ML model in the browser (Week 3) | Free |
| [TensorFlow Playground](https://playground.tensorflow.org) | Neural network visualization (Week 4) | Free |
| [ChatGPT](https://chat.openai.com) / [Claude](https://claude.ai) | LLM interaction, prompt engineering, vibe coding | Free tier |
| [Replit](https://replit.com) | Browser-based coding — run AI-generated code | Free tier |
| [p5.js Editor](https://editor.p5js.org) | Creative coding / visual projects | Free |
| [v0.dev](https://v0.dev) / [bolt.new](https://bolt.new) | Instant web app prototyping (optional) | Free tier |

---

## Teacher Notes

- **Keep groups small.** With 3 students, everyone participates. Don't lecture for more than 15 minutes straight.
- **No coding required.** Weeks 1–6 are entirely conceptual and hands-on without writing code. Week 7–8 use AI to write code — students describe, AI builds.
- **Model confusion.** When something breaks, say "I'm not sure either — let's ask AI to explain it." This normalizes not knowing.
- **Pace by the slowest learner, enrich for the fastest.** Have stretch challenges ready for students who finish early.
- **Avoid jargon overload.** Introduce a few new terms per session. Repeat them until they feel natural.
- **Celebrate broken things.** A bug means you're building. A working app means you iterated past the bugs.
- **Connect the concepts.** Each week builds on the last. Frequently callback: "Remember when we learned about frontend and backend? That's what the AI just generated for us."
- **Ethics check-in.** Each week, ask one question about responsible AI use: "Who decides what the AI learns?" "What happens when AI is wrong and someone believes it?" "Should AI-generated schoolwork count as your work?"

# Prompt History

## Prompt 1: Initial Syllabus Generation

> I'm a teacher. I'm going to teach generative AI to 7th graders. There are 3 students. Classes will be once a week, 1 hour, for 6 weeks. Create a syllabus. These kids have zero coding experience. Make it hands-on first, concepts follow curiosity, and build something real.

*(Generated the initial 6-week syllabus covering: What is AI, How Computers Talk, How LLMs Work, Prompt Engineering, Vibe Coding, and Capstone Project.)*

## Prompt 2: Syllabus Revision Based on Teacher Input

> I am not happy with the suggested syllabus. use the input available in teacher_input.md and update the syllabus.

**Teacher input summary (from `syllabus/teacher_input.md`):**
- Kids have no CS/programming background
- Programming is a dying art — goal is NOT to teach programming
- Goal is to teach Gen AI and vibe coding so kids can build apps/games
- Basics: how programs work, how the internet works, frontend/backend/database, video game components (single & multiplayer), difference between ML/AI/Gen AI, ML via linear regression, training/testing/inference
- Intermediate: neural networks related to the human brain, LLM and GPT word-by-word breakdown, autoencoding vs autoregressive models, prompt engineering basics, building presentations/reports with prompts, using additional context (files)
- Advanced: build a web app with vibe coding, capstone project

*(Revised to an 8-week syllabus in 3 phases: Basics (Weeks 1-3), Intermediate (Weeks 4-6), Advanced (Weeks 7-8). Restructured to match teacher's goals — no coding until Week 7, ML taught via linear regression, neural networks tied to the brain, LLM/GPT terms broken down, autoencoding vs autoregressive introduced, prompt engineering includes building reports with context files.)*

## Prompt 3: Week 1 Slides — How Computers Work

> you are a middle school computer savvy teacher preparing slides to teach gen ai to 7th grade students. review the genai_middle_school_syllabus.md and generate rich html slide show to explain how a computer works for 7th graders in the week1 folder.

*(Generated `week1/how_computers_work.html` — a 12-slide interactive HTML slideshow covering: what a computer is, the 4 parts (input, memory, CPU, output), the kitchen analogy, how software is just instructions, input → processing → output flow, speed of computers, what code looks like, video game teardown (graphics, logic, input, sound), multiplayer servers, and a quiz. Includes animations, reveal buttons, interactive elements, and keyboard navigation.)*

## Prompt 4: Week 2 Slides — How the Internet Works

> you are a middle school computer savvy teacher preparing slides to teach gen ai to 7th grade students. review the genai_middle_school_syllabus.md and generate rich html slide show to explain how internet works for 7th graders in the week2 folder.

*(Generated `week2/how_internet_works.html` — a 14-slide interactive HTML slideshow covering: postal system analogy for the internet, journey of a web request (DNS, routers, servers), key internet players (Wi-Fi, servers, IP addresses, data centers), request & response pattern, anatomy of a URL, the 3 parts of every app (frontend, backend, database), Instagram posting example, restaurant analogy, HTML/View Source demo, "Build an App on Paper" activity, and a quiz. Includes interactive step-by-step journey reveal, clickable info cards, Instagram post tracker, app-building activity with answers, and keyboard navigation.)*

## Prompt 5: Week 3 Slides — ML, AI, and Gen AI

> similar to the material generated for prior weeks, review the week 3 agenda from genai_middle_school_syllabus.md and generate rich html slides in week3 folder

*(Generated `week3/ml_ai_genai.html` — a 15-slide interactive HTML slideshow covering: warm-up discussion (what do you think AI is?), nested circles diagram (AI > ML > Gen AI) with clickable layers, AI examples comparison table, y = mx + b connection to ML, study hours vs. test scores data table, interactive scatter plot with animated best-fit line and prediction point, training/testing/inference pipeline, studying-for-a-test analogy, scaling from linear regression to ChatGPT (175B parameters), Teachable Machine demo with link, quiz, and homework (prompt experiment comparing 7th-grader vs. scientist explanations). Includes interactive canvas-based graph, clickable myth-busters, reveal panels, and keyboard navigation.)*

## Prompt 6: Week 4 Slides — Neural Networks & the Brain

> similar to prior weeks, review the genai_middle_school_syllabus.md and generate teaching material for week 4. The neural network + brain analogy is important and so explaining this to 7th graders is vital for them to understand deep learning and gen ai. be as thorough as possible

*(Generated `week4/neural_networks_brain.html` — an 18-slide interactive HTML slideshow covering: homework debrief (comparing ChatGPT 7th-grader vs. scientist answers), the problem with straight lines (why y=mx+b can't recognize cats), your amazing brain (86 billion neurons, 100 trillion connections, electric signals), how a brain neuron works (receive/process/fire/send with clickable steps), brain vs. computer neuron side-by-side comparison table (neurons/dendrites/synapses mapped to inputs/weights/activation functions), what are weights ("going outside" decision analogy with interactive slider), layers of a neural network (input/hidden/output with visual neuron diagram), cat recognition walkthrough (pixels → edges → parts → objects → answer, clickable layers), how neural networks learn (basketball shooting analogy for backpropagation), deep learning explained ("deep" = many layers, scale comparison from 1M to 1T weights), connecting y=mx+b to neural networks (single neuron IS the linear equation, stacked into networks), Human Neural Network classroom activity (number game + advanced emoji classifier variant with full instructions), interactive neural network visualization (animated canvas with signal propagation through layers), TensorFlow Playground guided demo (step-by-step with experiment suggestions for neurons/layers/spiral), why this matters (ChatGPT, DALL-E, Suno, AlphaGo all use neural networks), 5-question quiz (weights, deep learning, learning process, synapses, y=mx+b), and wrap-up with homework (TensorFlow Playground spiral challenge + ethics question about AI bias in training data). Includes interactive weight slider, animated neural network canvas, clickable reveal panels, quiz with instant feedback, and keyboard navigation.)*

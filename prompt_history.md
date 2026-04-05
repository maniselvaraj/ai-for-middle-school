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

---

## Session: Week 3 Revisions (2026-04-04)

### Prompt 7: Update "AI Is Everywhere" Slide with Middle-School Explanation

> Update the slide on "AI is everywhere" with some middle school level explanation from below context [provided transcript excerpt defining AI as processing information to inform decisions, ML as a subset learning from data without explicit programming, and deep learning as a subset using neural networks]

*(Updated slide 4 of `week3/ml_ai_genai.html`. Added three definition cards at the top (AI / ML / Deep Learning) derived from the transcript. Removed redundant bottom summary cards.)*

### Prompt 8: Restore Gen AI Definition Card

> put back the definition card on gen ai

*(Restored the three bottom summary cards (AI / ML / Gen AI) after the examples table on slide 4.)*

### Prompt 9: Add Deep Learning to Slides 3 and 4

> Thats not what I meant. While teaching the concept of AI vs ML vs Gen AI, bring in Deep learning as well. Place deep learning appropriately on slides 3 and 4.

*(Added Deep Learning throughout both slides. Slide 3: added a 4th nested circle (DL, green) between ML and Gen AI, added a DL info box, updated the callout rule to include DL. Slide 4: top cards expanded to grid-4, examples table gained a DL column (face recognition, voice recognition, self-driving car vision, medical image diagnosis), bottom summary cards expanded to grid-4. Added `--dl-color: #27ae60` CSS variable.)*

### Prompt 10: Fix Overlapping Labels in Nested Circles

> the russian nesting dolls is not clear. the letters are overlapping with each other. make it better so text does not overlap

*(Increased circle sizes (AI: 340→420px, ML: 230→300px, DL: 165→190px, GenAI: 90→82px), recalculated label top positions so each sits in its own ring band, added `white-space: nowrap`, updated container height to 440px and responsive breakpoint sizes.)*

### Prompt 11: Remove "Demo: Teachable Machine" Slide

> on week3: take out the slide on "Demo: Teachable Machine"

*(Removed the Teachable Machine slide (was slide 12). Renumbered slides 13–15 → 12–14, updated all nav buttons and dot IDs, changed TOTAL from 15 to 14.)*

### Prompt 12: Add "What is a Model?" Explanation on Slide 5

> week 3 slide 5 is the first time the concept "model" is used as in "the simplest ml model in the world..." Add a easy to understand explanation for middle schoolers on what a model is

*(Added a blue info callout box on slide 5 above the mind-blowing fact, explaining a model using a vending machine analogy.)*

### Prompt 13: Simplify the Model Definition

> The definition of model is still complex. How about something like this for 7th graders - "A model is a simplified representation of something in the real world that helps a computer understand it and make predictions about it."

*(Replaced the vending machine analogy with the user's cleaner one-sentence definition.)*

### Prompt 14: Move "What's a Model?" Callout to Bottom + Add Example

> move the callout on "whats a model" to the bottom. Also add a simple example

*(Moved the model callout below the mind-blowing fact callout. Added an example tied to the slide's own data: "for every extra hour studied, add about 8 points — so it can predict your score on a test you haven't taken yet.")*

### Prompt 15: Create Appendix + Move Slides 8/9/10 + New Slide 8

> 1. create a new appendix section at the end of week 3 slides. 2. It feels like too much time is being spent on introducing ML (train, test, infer) to 7th graders. 3. move slide 8, 9, and 10 to Appendix section at the end. 4. create a simple slide 8 explaining the "learning" part of ML.

*(Removed old slides 8 (3 Steps of ML), 9 (Study Analogy), 10 (What ML Is Really Doing). Created new slide 8 "How Does ML Learn?" with a thermostat analogy and a Guess→Check→Adjust→Repeat flow. Renumbered old slide 11→9, 12→10, 13→11, 14→12. Added a 3-slide Appendix section (A1: 3 Steps of ML, A2: Study Analogy, A3: What ML Is Really Doing) with its own navigation, dot indicators, and a `goToAppendix()` JS function. Updated TOTAL to 12. Added a "Bonus" button on slide 12 to enter the appendix.)*

### Prompt 16: Improve Slide 8 with Basketball Analogy

> Slide 8 is still not apt for 7th graders. [Feedback: thermostat analogy feels mechanical, "iteration" adds jargon. Suggestion: use basketball shooting analogy, replace "iteration" with "practice", update flow labels to be more human.]

*(Rewrote slide 8. Flow labels changed to: "Make a guess / See how far off you were / Adjust your aim / Repeat 1,000s of times". Card 1 replaced thermostat with basketball analogy ("hits the front rim — too short! — your brain adjusts to throw harder"). Card 2 replaced "iteration" with "practice shots" framing. Callout updated to "practices from examples." Word "iteration" removed entirely.)*

---
title: "Let Chaos Reign"
short_title: "Let Chaos Reign"
weight: 7
excerpt: "Leading through ambiguity feels like failure, even when it is the correct strategy."
opening: "February — May 2025"
---

The morning after the board approved the transformation plan, I gathered my engineering leadership team — seven people, the directors and senior architects who had built Arcline with me — in our largest conference room. I had spent the previous night preparing what I intended to say. I had slides. I had a timeline. I had a migration architecture sketched out on three whiteboards. I had a neat, logical, twelve-month plan to take Arcline from what it was to what it needed to be.

I threw all of it away ten minutes before the meeting.

I threw it away because I realized, standing in my kitchen at six in the morning drinking coffee that had gone cold, that I was about to make the same mistake in a different direction. For two years, I had been too slow to act. Now I was in danger of acting too fast — of committing to a specific new architecture before I understood enough to know which architecture was right. I had swung from paralysis to premature certainty, and premature certainty in a Strategic Inflection Point is just as fatal as paralysis. It merely feels more productive.

Grove understood this. It is one of the most counterintuitive lessons in his book, and the one that executives resist most fiercely. After you accept that the change is real — after you have fought through the denial and the identity crisis and the emotional cost of letting go — your instinct is to seize control. To impose order. To pick a direction and march. You have been lost in the fog for so long that the moment you see a path, you want to run down it.

Do not run. Not yet.

You must first pass through a phase that Grove described as "letting chaos reign." A period of deliberate experimentation, deliberate ambiguity, deliberate discomfort. You must let multiple teams pursue multiple approaches, without knowing which one will win. You must tolerate contradictory results, redundant effort, and the acute organizational anxiety that comes from a leader saying, publicly, "I don't know the answer yet."

This is what I told my engineering leadership that morning, without slides and without a twelve-month plan:

"We are going to run five experiments over the next four months. Each experiment will explore a different approach to rebuilding our product around AI. I am not going to tell you which approach is right, because I do not know. Some of these experiments will fail. That is expected and acceptable. What is not acceptable is not learning from the failure. At the end of four months, we will look at what we have learned, and then — and only then — will we commit to an architecture."

The room was quiet. These were people who had worked for me for years. They were accustomed to Vikram having a plan. Vikram always had a plan. The architecture documents, the technical specifications, the detailed roadmaps — these were the artifacts of my leadership, the things that made my teams feel safe and directed. And now I was telling them that I did not have a plan, and that the absence of a plan was itself the plan.

I could see the discomfort on their faces. I shared it. But I had learned, at great cost, the price of false certainty. I was not going to pay it again.

---

Here is what the five experiments looked like, and what each one taught us.

**Experiment 1: The Wrapper.** One team took our existing product and wrapped it in an LLM-powered conversational interface. The idea was straightforward — keep the backend, replace the UI. Instead of clicking through screens and menus, users would type natural language requests: "Show me all POs over fifty thousand that haven't been approved" or "Compare these three supplier bids on lead time and compliance." The LLM would translate the request into API calls against our existing system.

This was the most conservative approach, and it worked quickly. Within six weeks, the team had a functional prototype. Users could interact with Arcline through natural language. It was impressive in demos. Customers who saw it said positive things.

But it had a fundamental problem: it was a better interface to an architecture that was already obsolete. The underlying system still assumed a human making decisions at every step. The LLM was merely translating between human language and human workflows. It did not change the economics. It did not change the pricing model. It did not address the structural shift from seat-based to outcome-based. It was, in the most precise sense of the word, cosmetic.

The wrapper experiment taught us that you cannot solve a structural problem with an interface change. It taught this lesson clearly and quickly, and that alone made it worth running. We did, however, ship the wrapper to our existing customers as a bridge product — a way to give them a taste of natural language interaction while we built the real thing. It bought us six months of goodwill with customers who were beginning to ask why our product still felt like 2019. In that sense, even a strategically insufficient experiment can be tactically valuable. You just cannot mistake the tactic for the strategy.

**Experiment 2: The Fine-Tuned Model.** A second team took the opposite approach. They collected our proprietary data — thirteen years of procurement transactions, supplier evaluations, contract terms, compliance decisions — and fine-tuned a language model specifically for procurement workflows. The thesis was that our data was our moat, and that a procurement-specific model would outperform any general-purpose system.

This was the experiment I was most emotionally attached to, because it preserved the thing I valued most: Arcline's accumulated domain knowledge. If our data could produce a model that was demonstrably superior to a general-purpose alternative, then our thirteen years of experience still *mattered*. Our history was still our advantage.

The team worked for three months. They cleaned data, designed training pipelines, ran experiments, evaluated results. The fine-tuned model was better than the base model on procurement-specific tasks. Measurably better. I felt a surge of vindication when I saw the benchmarks.

And then, four weeks later, Anthropic released a new version of Claude. The general-purpose model, with no fine-tuning, with nothing but a well-crafted prompt and a retrieval system pointed at our documentation, matched the performance of our fine-tuned model on nearly every benchmark. Three months of work, rendered redundant by a single model release.

This was the most expensive lesson of the entire transformation, and the most important. The capability curve of foundation models was moving faster than any organization's ability to build on top of a fixed point. Fine-tuning to a specific model version was like building a house on a glacier — the ground itself was moving. By the time you finished construction, you were in a different place than where you started.

The lesson was not that fine-tuning is never valuable. In some domains, for some tasks, it remains essential. The lesson was that *betting your strategy on it* — treating proprietary data as a durable moat against general-purpose models — was a mistake. The moat was real in January and gone by April. In a 10X environment, any advantage that depends on the foundation model staying still is not an advantage. It is a timer.

**Experiment 3: The Agent.** A third team, led by Priya — the Cassandra whose demo day presentation I had politely sidelined — built something different. They built an autonomous AI agent that could execute an entire procurement workflow from end to end. Not assist a human. Not translate a human's request. *Do the work.* Identify the need, search the supplier database, generate the RFQ, evaluate the bids, check compliance, flag anomalies for human review, and generate the purchase order.

It was rough. The first version made mistakes that a junior procurement analyst would not have made. The compliance checking was unreliable. The supplier matching had blind spots. But the architecture was fundamentally different from anything else we had built. It was designed from the ground up for a world where the AI does the work and the human supervises — where the human's role is to evaluate, approve, and handle the exceptions that the AI cannot.

Priya's team had built the skeleton of Arcline's future. I did not know that yet, in the middle of the chaos. But I could feel it.

**Experiment 4: The Platform.** A fourth team explored building an agent platform — the orchestration and governance layer that would allow multiple AI agents to work together within a customer's environment, with proper access controls, audit trails, and human-in-the-loop approval workflows. This was the orchestration layer I described in Chapter 3 — the strategically critical middle of the new stack.

This experiment produced valuable technology but an equally valuable strategic insight: we were not a platform company. Building a general-purpose agent orchestration platform would put us in competition with companies that had more funding, more infrastructure expertise, and a broader market. Our advantage was not orchestration. Our advantage was procurement domain expertise. The platform experiment helped us understand where we did *not* belong in the new stack — which was, in its own way, as important as understanding where we did.

**Experiment 5: The Acquisition.** The fifth experiment was not a technical project. It was an evaluation of three early-stage AI-native procurement startups as potential acquisition targets. If we could not build the future fast enough, perhaps we could buy it. We spent eight weeks evaluating the companies, their technology, their teams, their architecture.

We did not acquire any of them. But the evaluation forced us to see, with painful clarity, how far ahead the AI-native entrants were in certain areas — and how far behind they were in others. They had superior AI integration and user experience. We had superior domain depth, enterprise security, and customer relationships. The evaluation helped us see our strengths without the distortion of our insecurities.

---

Midway through the chaos phase, Anil and I had our only real argument of the entire transformation.

It was late on a Wednesday. The board was pressing him for a progress update, and he had nothing clean to report. Two experiments had already stalled. The wrapper team was shipping but he knew it was a bridge to nowhere. Engineering morale was fragile. And Anil, who had been my partner through everything, who had waited patiently for me to arrive at the decision to transform, was now watching me run what looked, from the outside, like five projects with no coherent strategy.

"I backed you on this," he said, standing in my office doorway. "The board backed you. But I can't go to Marcus with 'we're learning a lot.' I need to tell him where we're headed."

"I don't know where we're headed yet," I said. "That's the point."

"The point," he said, and I could hear the strain in his voice, "is that we're spending four months and a significant portion of our engineering capacity on experiments, and you're telling me the outcome is 'we'll see.'"

He was not wrong. From his seat — the CEO managing investors, managing the board, managing the narrative — the chaos was not a strategic choice. It was a liability. I was asking him to trust a process whose output I could not guarantee, and he was asking me to give him something he could defend.

We sat in silence for a long moment. Then I said: "Give me until the end of the month. If I don't see a clear pattern by then, I'll pick the best option we have and commit. But if I pick too early and I pick wrong, we'll waste a year, not four months."

He nodded. He did not look happy. But he gave me the time. That was Anil — the CEO who understood that the right decision made three weeks late is almost always better than the wrong decision made on schedule.

Four months of chaos. Five experiments. Two clear failures (the wrapper and the fine-tuned model), one promising but wrong direction (the platform), one strategic learning exercise (the acquisition evaluation), and one rough, imperfect, unmistakably important breakthrough (Priya's agent).

It was messy. It was expensive. It was disorienting for my teams, who were accustomed to working toward clearly defined goals with clearly defined timelines. Several of my best engineers expressed frustration. One senior architect — a person I respected enormously — told me, privately, that the lack of direction was "irresponsible." He wanted a plan. He wanted certainty. He wanted the Vikram who drew architecture diagrams on whiteboards and told the team exactly what to build.

I understood his frustration, because I shared it. Leading through ambiguity feels like failure, even when it is the correct strategy. Every instinct in my engineering brain — the instinct to optimize, to converge, to find the right answer — was screaming at me to pick a direction and commit. The chaos was physically uncomfortable. I lost weight. I slept badly. I second-guessed myself constantly.

But the chaos had done its job. It had shown me what worked and what did not. It had revealed where our real advantage lay and where we were deluding ourselves. It had produced Priya's agent architecture, which would become the foundation of the new Arcline. And it had killed the ideas that sounded right but were not — the wrapper, the fine-tuned model, the platform play — before we could commit to them at scale and waste years instead of months.

Chaos had reigned. It was time to rein it in.

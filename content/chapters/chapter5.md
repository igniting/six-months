---
title: "\"Why Not Do It Ourselves?\""
short_title: "\"Why Not Do It Ourselves?\""
weight: 5
excerpt: "The solution required me to destroy the thing I had built."
opening: "Fall 2024 — January 2025"
---

I need to tell this part of the story carefully, because it is the part I am least proud of, and because the temptation to clean it up — to make myself look more decisive, more visionary, more courageous than I actually was — is almost overwhelming. But Grove did not clean up his story. He told the truth about how long it took Intel to let go of memory chips, about the internal politics, about the months of paralysis. And the truth was the most useful part of his book. So here is the truth about Arcline.

---

By the fall of 2024, I had done the analysis. I understood the 10X forces. I could draw the new horizontal stack on a whiteboard and explain exactly where each layer was headed. I could articulate, with precision, why Arcline's vertical SaaS model was structurally disadvantaged in the emerging AI-native world. I had read everything. I had talked to everyone. I had the intellectual clarity that any competent CTO would have had after eighteen months of watching this unfold.

And yet I did almost nothing.

I did not propose a fundamental restructuring of our product. I did not recommend killing the product lines that were being commoditized. I did not suggest changing our pricing model. I did not advocate for the kind of wrenching, top-to-bottom transformation that I knew, intellectually, was necessary.

Instead, I did what every executive does when they understand the problem but cannot face the solution. I optimized around the edges. I added an "AI-assisted" feature to our contract review module. I greenlit a small team to experiment with LLM integrations. I presented a slide at our quarterly leadership meeting titled "AI Strategy: Phase 1" that was, in retrospect, a masterpiece of sophisticated procrastination. It had enough substance to look serious and enough ambiguity to avoid committing to anything.

Why?

Because the solution required me to destroy the thing I had built.

I do not mean this metaphorically. Arcline's architecture was my architecture. I had designed the data model. I had chosen the frameworks. I had made the tradeoff decisions — consistency over availability here, flexibility over performance there — that gave the system its character. I had hired and mentored the engineers who maintained it. I had fought for every technical decision in rooms full of people who wanted to cut corners. That codebase was not just intellectual property. It was my intellectual identity. It was the physical manifestation of thirteen years of my professional life, and it was the thing that proved — to my co-founder, to our investors, to the industry, and most of all to myself — that I was good at what I did.

I have thought about why the attachment ran so deep, and I think it has something to do with where I came from. When you arrive in a country at twenty-two with a suitcase and an accent and a student visa, you carry a particular hunger to build something undeniable. Something that cannot be dismissed or explained away. Arcline was that thing for me. It was the proof that I belonged here, that the bet I made when I left Hyderabad had been the right one. Tearing it down felt like tearing up the evidence.

The AI transition was asking me to admit that the thing I had built — the thing that *proved I was good* — was becoming obsolete. Not because it was badly built. It was well built. That was the cruelest part. It was excellently built for a world that was disappearing.

Grove described this exact psychology in his account of Intel's DRAM crisis. Intel did not cling to memory chips because the executives were stupid. Intel clung to memory chips because *Intel was memory chips*. The company's identity, its founding mythology, its sense of self — all of it was tied to a product that the market no longer valued. Letting go of DRAMs was not a business decision. It was an existential one. It required Intel to stop being what it was and become something it did not yet know how to be.

I was facing the same thing. And I was failing the same way.

---

The data, meanwhile, did not care about my identity crisis.

In Q3 2024, we lost a deal to an AI-native competitor. It was a mid-market manufacturer — the kind of account we used to win in our sleep. The competitor was a startup I had been tracking, eighteen months old, forty employees. They offered an AI-first procurement agent that handled the entire sourcing workflow — supplier discovery, RFQ generation, bid comparison, compliance check — through a conversational interface. No training. No fourteen-month implementation. The customer was live in three weeks.

I told myself it was an anomaly. Mid-market customers have different needs. Our enterprise customers would never accept that level of risk.

In Q4, we lost two more. One was mid-market. The other was not. The other was a division of a Fortune 500 industrial conglomerate — exactly our core market, exactly our ideal customer profile. They chose the startup because, as their VP of Procurement told our sales team in the debrief call, "We don't want to spend eighteen months and two million dollars implementing a system that our people then have to learn to use. We want to tell an agent what we need and have it do the work."

Three enterprise deals lost in two quarters to a company that had not existed when I was presenting my "AI Strategy: Phase 1" slide.

My co-founder, Anil, called me on a Saturday morning. Anil was our CEO. We had started Arcline together in 2009 — I built the product, he built the business. We had survived the early years of no revenue, survived the fundraising rejections, survived the brutal slog of enterprise sales cycles that lasted nine months and ended with a "we've decided to go another direction." We had built something real. And now Anil was calling me on a Saturday, which he only did when something was very wrong.

"I just got off the phone with the board," he said. "They want to talk about our competitive position. The Q4 pipeline is down twenty percent. Marcus" — one of our board members, a partner at a growth equity firm — "is asking hard questions. He wants to know what we're doing about AI. Not the Phase 1 stuff. Real answers."

I started to explain the experiments we had running, the integrations we were building, the roadmap I was developing. Anil listened for about thirty seconds and then cut me off.

"Vikram, I've known you for twenty years. I can hear when you believe what you're saying and when you're performing. You're performing."

I said nothing. He was right.

---

The board meeting happened three weeks later. It was a Thursday in January 2025. Seven people around a conference table: Anil and me, three board members, our CFO, and our VP of Sales.

The first hour was normal. Revenue update, pipeline review, customer retention metrics. The numbers were fine — not great, but fine. Our existing customers were renewing. The churn rate had not spiked. The base was holding.

Then Marcus pulled up a slide he had prepared. It showed three things: our new-logo acquisition rate over the past four quarters (declining), the average deal size for new logos (declining), and the number of competitive losses to AI-native entrants (rising). Each metric individually was concerning but not catastrophic. Together, they formed a pattern that was impossible to ignore.

"Vikram," Marcus said, "I want to ask you a question, and I want an honest answer. If the board brought in a new CTO tomorrow — someone with no history here, no attachment to the existing architecture, no loyalty to the way things have been done — what would that person do?"

The room went quiet. I could feel Anil watching me from across the table. I could feel the weight of thirteen years of decisions pressing down on my chest — every design choice, every architectural tradeoff, every hire, every late night debugging a production issue in a system I had built from nothing.

And I knew the answer. I had known it for months. I had known it since that flight to Chicago, since Ravi showed me ChatGPT, since Dietrich called me about the three-person London startup, since we lost the Fortune 500 deal. I had known it and I had refused to say it.

"She would tear it down," I said. "She would rebuild the product around an AI-native architecture. She would kill the legacy workflow engine. She would move from seat-based pricing to outcome-based pricing. She would cut the teams that are building for the old model and redeploy them — or replace them — with people who can build for the new one. She would do it fast, and she would not be sentimental about it."

Marcus nodded. "So why aren't you doing that?"

I looked at Anil. He looked back at me. And in that look, I saw something I had not expected. I saw relief. He had been waiting for me to say this. He had been waiting for months. He had not pushed me because he trusted me, and because he knew that a technical transformation led by a reluctant CTO is worse than no transformation at all. He needed me to arrive here on my own.

"Because," I said, "I built the thing we'd be tearing down."

It was the most honest sentence I had spoken in a year.

---

After the board meeting, I drove home and sat in my car in the garage for twenty minutes. I did not go inside. I called nobody. I sat with the engine off and the lights off and I thought about Andy Grove walking out of his office, going through the revolving door, coming back in, and pretending to be his own replacement.

The next morning, I walked into Anil's office and closed the door.

"I've been thinking about Marcus's question," I said.

"And?"

"You and I started this company in your apartment in Sunnyvale. We had no funding, no customers, no product. We built all of it. And now I'm telling you that the thing we built — the thing that *worked*, the thing that got us to six hundred million — is not the thing that gets us to the next six hundred million. The architecture has to change. The pricing has to change. The org structure has to change. I have to change."

Anil was quiet for a moment. Then he said: "I've been waiting for you to say that since August."

August. Six months. He had seen it six months before I was willing to say it out loud. And he had waited, because he knew that pushing me would have produced compliance, not conviction. He needed me to feel it, not just know it.

This is the part of the story that haunts me most. Not the board meeting. Not Marcus's question. The gap between knowing and speaking. All those months where I used my technical expertise as a shield — conducting analyses, running experiments, building Phase 1 roadmaps — to avoid the one thing that actually mattered: admitting that the world had changed and that I had to change with it.

Grove wrote about the same delay at Intel. He estimated that the decision to exit DRAMs should have been made a year before it actually was. A year of lost time — not because the data was unclear, but because the emotional cost of acting on the data was too high. The humans in the system could not process the loss fast enough to act on the information fast enough to avoid the damage.

My delay was shorter than Intel's. But in a 10X environment, even a few months is a lifetime. Competitors had signed customers. Market narratives had formed. Engineers I should have been recruiting had gone elsewhere. The cost of hesitation is never abstract. It is measured in deals, in talent, in positioning — in all the things that compound and cannot be recovered.

---

That Friday, Anil and I flew to New York and spent the weekend in a hotel conference room with our CFO, working through what the transformation would actually require. Not the vision — I had the vision. The specifics. The painful, granular, human specifics.

We identified three product lines that would need to be sunset within twelve months. We mapped every engineering team against the new architecture and flagged the ones whose work would become redundant. We modeled the revenue impact of moving from seat-based to outcome-based pricing — a model that showed a short-term revenue decline of fifteen to twenty percent before the new pricing caught up. We listed the people — by name, people I had hired, people I had mentored, people I considered friends — whose roles would fundamentally change or cease to exist.

Anil looked at the list of names and then looked at me. "Are you sure?"

I was not sure. I was terrified. But I had learned something from Grove, and I had learned something from watching Chegg die, and I had learned something from my own months of paralysis: certainty is not a prerequisite for action. In a Strategic Inflection Point, waiting for certainty is the most dangerous thing you can do, because by the time you are certain, you are already too late.

"I'm not sure," I said. "But if we wait until I'm sure, there won't be a company left to transform."

We spent Sunday building the presentation for the board. Monday morning, Anil called an emergency session. We presented the plan. The board approved it unanimously — not because they were confident it would work, but because they could see, in the pipeline data and the competitive losses and the structural analysis, that the alternative was slow irrelevance.

The transformation of Arcline began the next day. It would be the hardest thing I had ever done. Harder than starting the company. Harder than the years with no revenue. Harder than any technical challenge I had faced in thirty years of engineering.

Because the hardest part was not building the new thing. The hardest part was killing the old thing. The thing that worked. The thing that had my fingerprints on every surface. The thing that, for thirteen years, had been the answer to the question of who I was.

I was about to find out who I was without it.

---
title: "Agents — Signal or Noise?"
short_title: "Agents — Signal or Noise?"
weight: 9
excerpt: "The signal is clear. The question, as always, is whether you are ready to act on it."
opening: "Early 2026 — The next wave"
---

As I write this in early 2026, the next wave is already forming. And I am terrified — not of the wave itself, but of my own capacity to misread it. I was slow once. I nearly lost my company to my own hesitation. The scar tissue from that experience has made me both more alert and more anxious. I see signals everywhere now. Some of them are real. Some of them are my nervous system overcorrecting for past failure.

The wave is agents. Not chatbots, not copilots, not AI-assisted tools — *agents*. Autonomous systems that do not merely respond to prompts but pursue goals, use tools, make decisions, and take actions. Systems that can be given an objective — "find us the best supplier for this component at this specification and negotiate terms" — and work toward it across hours or days, using multiple tools, querying multiple systems, and exercising something that looks uncomfortably like judgment.

The question I must answer — the question every leader in every industry must answer — is the same one I failed to answer quickly enough three years ago: is this signal, or is this noise?

Let me apply my own framework. Honestly. Without the distortions of either hype or overcaution.

---

**The capability curve says: signal.**

The progression from chatbot to copilot to agent has followed the same staircase pattern I described in Chapter 6 — each step qualitatively different from the last, each arriving faster than predicted.

In 2023, we had chatbots: systems that answered questions. In 2024, we had copilots: systems that assisted with tasks. By mid-2025, we had agents: systems that executed multi-step workflows autonomously. The progression was not hypothetical. Anthropic's Claude could operate as a coding agent, reading codebases, writing tests, debugging failures, and producing production software with minimal supervision. OpenAI was building similar capabilities. Google was investing billions into the same trajectory.

What changed between copilot and agent was not merely intelligence. It was *persistence*. A copilot responds to a prompt and stops. An agent takes an objective and works toward it, maintaining state across multiple steps, recovering from errors, and making decisions about which actions to take next. This is a qualitative shift — from reactive to proactive, from tool to worker — and it changes the economics of every process the agent touches.

At Arcline, I was already building for this future. Priya's procurement agent — the one that emerged from the chaos phase — was an early version of exactly this kind of system. But even I underestimated how fast the rest of the industry would move.

**The infrastructure investment says: signal.**

The money is real and it is enormous. Enterprise spending on generative AI reached thirty-seven billion dollars in 2025 — more than triple the year before. The agentic AI market is projected to reach ninety-three billion dollars by 2030, growing at a compound annual rate that exceeds sixty-five percent. If these numbers are even half right, we are looking at the fastest-growing enterprise software category in history.

But it is not just the spending totals that matter. It is *where* the money is going. Companies are no longer buying AI tools. They are building agent platforms. They are investing in orchestration layers, governance frameworks, and the security infrastructure required to let autonomous systems operate inside production environments. The KPMG AI Pulse Survey found that half of executives plan to allocate ten to fifty million dollars specifically to securing agentic architectures, improving data lineage, and hardening model governance. When companies invest that kind of money in governance infrastructure, they are not experimenting. They are preparing for permanent deployment.

**The enterprise adoption says: signal.**

The data here is unambiguous. The largest enterprise software companies on earth are not adding AI as a feature. They are reorganizing their entire businesses around agent platforms. CEOs of hundred-billion-dollar incumbents — companies that *defined* the SaaS era — are publicly declaring that they no longer operate in a "SaaS neighborhood" but in an "enterprise AI neighborhood." They are not hedging. They are not running pilots. They are restructuring their core product lines, their pricing models, and their go-to-market strategies around the assumption that agents will be the primary interface between enterprises and their software.

The broader data is equally striking. Fifty-seven percent of organizations in a recent industry survey already deploy multi-step agent workflows. Eighty-one percent plan to expand into more complex agent use cases this year. Multi-agent systems — architectures where multiple specialized agents collaborate on complex tasks — grew by over three hundred percent in less than four months on one major platform. Seventy-two percent of enterprises have moved past AI trials into full-scale production.

This is not a handful of early adopters running pilots. This is mainstream enterprise adoption at a pace that I have never seen in thirty years in technology.

---

So the signals are strong. The capability is real. The investment is real. The adoption is real.

Then what is the noise?

**The noise is in the deployment model.**

Here is what I mean. The technology works. The question is whether organizations know how to operate it safely, govern it effectively, and integrate it into their existing systems without creating catastrophic risks.

And right now, the honest answer is: mostly, they do not.

McKinsey's 2026 AI Trust survey found that while AI adoption is accelerating rapidly, only about a third of organizations have reached even moderate maturity in AI governance and agentic AI controls. Strategy, governance, and controls are lagging behind technical capability. The gap is not closing. It is widening, because the technology is being deployed faster than the governance frameworks can evolve.

The numbers are sobering. Forty-six percent of respondents in one major survey cite integration with existing systems as their primary challenge — not intelligence, not capability, but the messy plumbing of connecting an autonomous agent to the CRM, the ERP, the ticketing system, the compliance database. A Cloud Security Alliance study found that teams are still sharing human credentials and API keys with AI agents because proper agent identity management does not yet exist at scale. Fifty-five percent of security leaders cite sensitive data exposure as their top concern. Fifty-two percent worry about unauthorized actions. And Gartner projects that more than a thousand legal claims for harm caused by AI agents will be filed against enterprises by the end of 2026.

These are not hypothetical risks. These are the actual, operational, right-now risks of deploying autonomous systems inside complex organizations.

I know this intimately because I am living it at Arcline. Our procurement agent works. It handles routine sourcing workflows with an accuracy and speed that our human teams cannot match. But deploying it into a customer's production environment — with their data, their compliance requirements, their approval chains, their security posture — is an order of magnitude harder than building the agent itself. The agent is the easy part. The trust infrastructure is the hard part. And we are building that trust infrastructure in real time, learning through a combination of engineering rigor and painful trial and error.

The early results, I should say, give me reason to believe we made the right bet. The first quarter on the new architecture was painful — revenue declined, the migration consumed more engineering hours than we had budgeted, and two customer deployments had to be rolled back. The second quarter was better. By the third, we were winning deals we could never have competed for under the old model — customers who wanted an AI agent that could execute procurement workflows, not a software tool that required humans to click through screens. Our pipeline is the strongest it has been in two years. I do not say this triumphantly. I say it provisionally, the way a patient says their symptoms have improved after starting a new treatment. The trajectory is encouraging. The outcome is not yet certain.

---

There is a pattern here, and it maps directly onto the Klarna story I told in Chapter 4.

Klarna proved that the technology works. They also proved that deploying it without sufficient attention to the operational reality — the quality controls, the human escalation paths, the governance framework — produces a backlash that can set you back further than if you had never started. The technology was the signal. The deployment model was the noise. And Klarna paid for confusing the two.

I see the same confusion playing out across the enterprise landscape right now. Companies are deploying agents because the technology is impressive. They are not investing proportionally in the governance, security, and operational infrastructure required to deploy agents *responsibly*. Three-quarters of organizations in one survey admit that their governance has not kept pace with their AI adoption. The result is predictable: early wins followed by incidents, followed by backlash, followed by the hard work of building the trust infrastructure that should have been built first.

Gartner predicts that more than forty percent of agentic AI projects will be canceled or scaled back by 2027 — not because the technology fails, but because the organizational infrastructure around it fails. This is the noise. Not the technology. The deployment.

---

So here is my honest assessment, applying the framework I learned the hard way:

**Agents are the signal.** The capability curve, the infrastructure investment, and the enterprise adoption data all point in the same direction. This is not hype. This is not a cycle. This is the next structural layer of the AI transformation — the layer where AI moves from assisting humans to executing work autonomously, with humans in supervisory roles.

**The deployment model is still noise.** Not because it is unimportant — it is critically important — but because it is unsettled. The governance frameworks, the security architectures, the identity management systems, the trust models — all of these are being built right now, in real time, by companies like mine and thousands of others. They are not yet mature. They are not yet standardized. And until they are, the gap between what agents can do and what organizations can safely let them do will remain the defining challenge of this era.

The companies that will win are not the ones that deploy agents fastest. They are the ones that solve the trust problem first. Because in enterprise software, capability without trust is a demo. Trust without capability is irrelevant. And the intersection of the two — capable agents operating within trustworthy governance frameworks — is where the next trillion dollars of value will be created.

I was slow once, and it nearly cost me everything. I will not be slow again. But I have also learned, at great personal cost, the difference between moving fast and moving recklessly. Klarna moved fast. They also moved recklessly, and they paid for it. The goal is not speed. The goal is *committed, eyes-open velocity* — moving decisively in the right direction while building the infrastructure to operate safely at the speed you are moving.

Agents are the signal. The governance is the work. And the companies that confuse the two — in either direction — will learn the same lessons that Chegg learned, that Klarna learned, and that I learned during the most painful stretch of my professional life.

The signal is clear. The question, as always, is whether you are ready to act on it.

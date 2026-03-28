## Chapter 8: Rein in Chaos

There is a moment in every transformation — and you will feel it more than you can measure it — when the chaos has done its work. When the experiments have converged enough to reveal a pattern. When you know, not with certainty but with sufficient conviction, which direction to go.

For Arcline, that moment came in June 2025, five months after the board had approved the transformation and four months into our experiments. I called the same seven engineering leaders back into the same conference room where I had told them I did not have a plan. This time, I had one.

"Here is what we are going to do," I said. "We are going to build the new Arcline around an AI agent architecture. The agent does the procurement work — sourcing, evaluation, compliance, documentation. The human supervises, reviews, and handles exceptions. The platform we sell is not a tool that helps humans do procurement. It is an agent that does procurement, with humans in the loop for trust, judgment, and accountability."

I paused and looked around the room. Five months earlier, these faces had shown discomfort at the absence of a plan. Now they showed something different — a mixture of relief and apprehension. Relief that a direction had been chosen. Apprehension about what that direction required.

"This means three things," I continued. "First, we are killing Arcline Classic — the legacy workflow engine — within eighteen months. Not sunsetting it. Killing it. Existing customers will be migrated to the new architecture. Second, we are moving from seat-based pricing to outcome-based pricing. We will charge per procurement cycle completed, per compliance check passed, per anomaly detected — not per user per month. Third, AI proficiency is now a core job requirement for every engineer in this company. Not a suggestion. Not a nice-to-have. A requirement."

The room was silent. I understood the silence. Each of those three statements was, by itself, a seismic organizational change. Together, they were a complete reinvention of the company. And I was announcing them in a single meeting on a Tuesday morning.

But I had learned, from Grove and from my own painful experience, that half-commitment in a Strategic Inflection Point is the same as no commitment. You cannot hedge a transformation. You cannot kill the legacy product "eventually." You cannot shift pricing "when the market is ready." You cannot make AI proficiency "encouraged." Every qualifier, every hedge, every softening word is a signal to the organization that the old way is still viable, that the transformation is optional, that if they wait long enough, the storm will pass and things will go back to normal.

Things were not going back to normal. And the organization needed to hear that from me, without ambiguity, without qualifiers, without escape hatches.

---

Let me describe what each of those three decisions actually required, because the difficulty is not in the announcement. The difficulty is in the execution.

**Killing the legacy engine.**

Arcline Classic was not just a product. It was the embodiment of thirteen years of customer relationships, thirteen years of domain expertise, thirteen years of engineering effort. It had four hundred and twelve enterprise customers. It processed billions of dollars in procurement transactions annually. It was reliable, well-understood, and profitable.

And it was architecturally incapable of supporting an AI agent. The data model was designed for human workflows. The approval chains assumed human decision-makers at every node. The compliance engine used deterministic rules that could not accommodate the probabilistic outputs of a language model. Retrofitting it would have been like adding a jet engine to a horse-drawn carriage — possible in theory, absurd in practice.

So we had to build the new system in parallel and migrate customers over an eighteen-month window. This meant, for a period, we were running two products simultaneously — maintaining the old one while building the new one. The engineering cost was brutal. I had to assign forty percent of my team to legacy maintenance and support, which meant only sixty percent was building the future. Every day that the migration stretched longer was a day we were paying the tax of our own history.

We lost eleven customers during the migration. Eleven companies that looked at the new architecture, decided it was too much change, and moved to a competitor offering a more familiar model. Each one was a phone call I dreaded and a conversation I forced myself to have personally. Several of those customers had been with us for a decade. One of them, a logistics company in Texas, had been our third customer ever — signed in 2010, when Anil and I were still working from his apartment. Their procurement director told me, not unkindly, that they had chosen Arcline because of its stability, and that what we were doing did not feel stable.

He was right. It did not feel stable. Transformation never does. But stability in a Strategic Inflection Point is an illusion. The companies that feel stable are simply the ones that have not yet noticed the ground shifting under them.

**Shifting to outcome-based pricing.**

This was the decision that our CFO fought hardest. And she was not wrong to fight it.

Seat-based pricing is the foundation of SaaS economics. It is predictable, recurring, and scales with customer headcount. Wall Street understands it. Investors model it. Sales teams are compensated on it. The entire financial infrastructure of a SaaS company — from revenue recognition to quota setting to board reporting — is built around the assumption that you sell seats.

Outcome-based pricing blows up that assumption. Instead of charging per user per month, you charge per unit of work completed. Per procurement cycle. Per contract reviewed. Per anomaly flagged. Revenue becomes variable. It fluctuates with customer activity. It is harder to predict, harder to model, harder to explain to investors who have spent twenty years valuing companies on annual recurring revenue.

But here is the thing: in a world where the AI does the work, there is no seat to sell. If a procurement agent handles a thousand sourcing cycles in a month, and no human ever logs into the interface, who is the "user"? Seat-based pricing in an agent-native world is like selling typewriter ribbons after the invention of the word processor. The unit of value has changed. Your pricing must change with it.

We modeled the transition and found what I expected: a short-term revenue decline of fifteen to twenty percent as existing customers moved from seat-based to outcome-based plans. Some customers would pay less under the new model because they had been over-provisioned on seats. Others — the ones with high procurement volume — would pay more. The net effect was negative in year one and positive by year two, with significantly higher revenue potential in year three and beyond as the agent handled more workflow types.

The board approved the model, but the transition was agonizing. Our sales team, trained for a decade to sell seats, had to learn to sell outcomes. Our account managers had to have conversations with customers that began with "we are changing how we charge you," which is approximately the least popular sentence in enterprise software. Some customers embraced it. Some pushed back. Some used the transition as an opportunity to renegotiate everything.

**Making AI proficiency non-negotiable.**

Of the three decisions, this was the one that affected the most people and generated the most resistance.

I had been watching Shopify's CEO, Tobi Lütke, and how he had handled the same challenge. In April 2025, Lütke had published an internal memo — originally intended to be private, posted publicly after it began leaking — that made AI usage a baseline expectation for every employee at Shopify. Not encouraged. Not recommended. Expected. Teams that wanted to hire additional headcount were required to demonstrate why AI could not do the work first. AI proficiency was being added to performance reviews. The tools were provided — Copilot, Claude, Cursor — and the expectation was clear: learn to use them or fall behind.

Lütke's memo was blunt in places. He acknowledged that he had been "too much of a suggestion" about AI adoption in the past, and that he was correcting that now. He was unapologetic about the mandate. He cited employees who were already achieving results that would have been unthinkable a year earlier. And he was honest about what it meant: this was not optional, and opting out was not a viable career strategy.

I admired the clarity. I borrowed it.

At Arcline, I announced that every engineer would be evaluated, starting in the next review cycle, on their effective use of AI tools in their daily work. We provided access to the best available tools. We ran internal workshops. We created a Slack channel where people shared prompts, techniques, and workflows. We made it easy to learn.

But I was clear that learning was expected, not optional.

The response was distributed exactly as I had predicted. About thirty percent of the engineering team embraced it immediately — these were the engineers who had already been using AI tools on their own, often more effectively than the experiments we had been running officially. Another fifty percent were cautious but willing. They needed support, encouragement, and time. They were not resistant to AI. They were uncertain about their own ability to use it well, and they needed permission to be beginners.

The remaining twenty percent resisted. Some resisted on principle — they believed that hand-written code was inherently superior to AI-assisted code, the same way some journalists still believe that a story researched without the internet is more rigorous than one researched with it. Some resisted out of fear — they sensed, correctly, that AI proficiency would change the basis on which their skills were valued, and they were not confident that the change would favor them. And some resisted simply because change is hard and humans are wired to prefer the familiar.

I handled this with as much empathy as I could, because I understood the resistance. I had resisted myself, for months, for the same reasons. I knew what it felt like to have the ground shift under your professional identity. I knew the fear. I respected it.

But I did not accommodate it.

I told the resisters, directly and privately, what Lütke had told his organization publicly: I could not see a future in which AI proficiency was optional. The trajectory was too clear. The capability curve was too steep. An engineer who refused to learn AI tools in 2025 was making the same career decision as an engineer who refused to learn version control in 2005 or the internet in 1995. They were welcome to make that decision. But I would be dishonest if I told them it would not have consequences.

Some came around. Some did not. Three engineers left voluntarily, including the senior architect who had called the chaos phase "irresponsible." He was a brilliant engineer and I was sorry to lose him. But I had learned, from Grove and from Klarna and from my own long hesitation, that an organization cannot transform if its leaders accommodate opt-outs. Commitment must be total or it is not commitment at all.

---

The months after we reined in the chaos were the hardest of my career. The three decisions I announced in June did not land simultaneously — they rolled out across the second half of 2025, each one its own campaign. The legacy migration started in July. The pricing transition began with new customers in August and existing customers in October. The AI proficiency mandate took effect in the September review cycle. Each wave of change hit the organization before the previous one had fully settled. Harder than the chaos itself, because chaos at least has the excitement of possibility. Execution has only the grinding reality of difficult decisions, difficult conversations, and difficult trade-offs made day after day, with no certainty that you are getting them right.

I killed two product lines and watched the engineers who had built them absorb the news with faces I will never forget. I restructured three teams and moved people out of roles they had held for years into roles they were not sure they could perform. I had conversations with loyal, talented people who looked at me and asked, "Is there still a place for me here?" and I did not always have the answer they wanted to hear.

But I committed. Fully, irreversibly, without hedging. I committed because I had learned that the cost of half-commitment — the cost of keeping one foot in the old world while tentatively extending the other toward the new — is higher than the cost of being wrong. If you commit fully and you are wrong, you can course-correct. If you half-commit and the world changes, you have neither the old advantage nor the new one. You are stranded in the middle, which is the most dangerous place to be.

Arcline was no longer stranded. We were moving. Imperfectly, painfully, with losses I grieved and decisions I second-guessed. But we were moving.

And the ground was moving with us.

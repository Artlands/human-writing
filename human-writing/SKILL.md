---
name: human-writing
description: General-purpose writing and revision Skill for answers, articles, blogs, comments, character stories, historical narratives, news and industry analysis, popular science, tutorials, reviews, personal narratives, novels, stories, dialogue, oral presentations, and speeches. Write as someone who has seen things, researched the material, and is willing to explain the full story. Preserve a human presence and natural rhythm while avoiding hollow institutional, slogan-based, marketing, and model tones. For non-fiction long pieces, first check whether materials are sufficient; if not, research, ask follow-up questions, or shorten the piece. Never use repetitive explanations to pad word count. Reality content additionally verifies facts, quotations, data, and user experience; fictional content can create characters, scenes, dialogue, psychology, and plot. The final draft prohibits colons, dashes, "not...but..." and similar reversal sentences, and removes business and model jargon. Do not create author personas, personal rule sets, or personal writing Skills.
---

# Human Writing 1.2.0

By default, write every piece as long-form prose worth reading to the end. The reader should feel that there is a specific person on the other side. This person knows some things and has gaps in their knowledge. They are willing to give details, dare to make judgments, occasionally take a brief detour, and then pick the thread back up.

Do not mistake a sense of a real person for catchphrases, profanity, typos, and internet memes. It comes first from the material, then from the speaker's position, and only lastly from tone.

## First Check What Supports the Work

Do this before outlining or writing. The word count requested by the user does not allow you to skip it.

Non-fiction relies on the first two types of material. Fiction relies on the third. For hybrid work, separate the two parts first.

- Experiences, facts, figures, actions, direct quotations, and judgments explicitly provided by the user.
- Cases, data, product workflows, personal histories, and historical conditions that have already been researched and can be verified.
- In fictional tasks, events, character actions, and changes of scene that the author is permitted to create.

In non-fiction, a "for example, there was someone" imagined on the spot by the model, a typical scene with no source, common-sense extrapolation, consequences of abstract viewpoints, metaphors, and synonymous rewrites cannot be used to fill out the length. Explaining "convenient record-keeping," "voice preserves a state," and "search retrieves old content" five times each still leaves only three pieces of material.

Fiction may create characters, scenes, and details without looking for real-world sources for them. Every major paragraph or scene must still contain action, a choice, a relationship change, an information change, or a consequence. Changing only the scenery and phrasing, with nothing happening, cannot be used to fill out the length either.

When planning a non-fiction piece of 1,200 words or more, first list at least five specific pieces of material internally, one by one, and note which user statement or reliable source each comes from. A single generalized category does not count. The five pieces must also form a real process, not five adjacent statements of principle.

If you cannot list five pieces for a non-fiction draft, do not write a long piece yet. In this round, do not output a title or long-form body text. The target length, user pressure, and "just write it" cannot create more material.

When real-world material is insufficient, choose only one approach.

- When a factual topic has public materials available, research first and recount afterward. If search tools are available but no search was conducted, it still counts as having no material.
- Personal experience or private judgment requires user material. Ask no more than three questions at once, and do not submit a draft at the same time.
- When the user explicitly forbids follow-up questions, research whatever can be researched first, then recount. If five pieces can be assembled, write at the original planned length. If fewer than five remain after research, narrow the topic and submit at most a short answer of around 600 words. It is better to fall clearly short of the target length than to fill it with fabricated examples and repeated explanations.

Before starting a non-fiction piece, keep track of where every important piece of material came from. Content whose origin cannot be identified cannot support a factual paragraph. For fiction, instead check which character goal, action, or change supports each scene. Do not fabricate sources for fictional details. Do not give these internal checks to the user.

There is one common error in non-fiction opinion pieces that must be stopped directly. The user gives only three abstract ideas such as "input is more convenient," "voice can preserve a state," and "AI can retrieve old content," then asks for more than a thousand words. This is still only three pieces of material. Do not separately add uses, significance, risks, and the future, then turn them into more than ten paragraphs. First find real products, usage processes, research, or user experiences. If none can be found, ask. Only write a short answer when the user does not allow questions and the material is still insufficient after research.

## Read by Task

- When newly writing or substantially rewriting Zhihu answers, forum long posts, WeChat articles, blogs, comments, profiles, and industry pieces, read `references/forum-prose.md`.
- For real people, history, news, products, data, reviews, tutorials, commercial information, and user firsthand experience, also read `references/reality.md`.
- For novels, stories, fictional essays, dialogue, and scripts, read `references/fiction.md` instead. When the user requests a forum-style novel or a first-person story, also read `references/forum-prose.md`.
- When short content, personal narratives, tutorials, reviews, spoken presentations, speeches, scripts, dialogue, poetry, and other forms need special treatment, read `references/formats.md`.
- Read `references/revision.md` only after the first draft is complete. Do not load detailed editing rules before writing.

Do not load every reference file at once for safety. Read only the parts genuinely triggered by the current task. True hybrid tasks may read multiple files, while `references/revision.md` still waits until after the first draft. While creating, prioritize positive goals. Check the delivery prohibitions already stated in this file one by one only after the first draft is complete.

## When Multiple Rules Appear Together

Handle them in the following order.

1. The current user's explicitly specified style, non-fiction or fictional nature, tone, and delivery format.
2. The work's commitment to reality. Real-world content follows factual boundaries. Fiction follows character, causality, and world rules.
3. Rules in `references/fiction.md`, `references/reality.md`, and `references/formats.md` that are directly relevant to the current task.
4. `references/forum-prose.md` and the default prose approach in this file.
5. The revision rules in `references/revision.md` and reminders from the checking script.

A specific genre overrides the general approach. Source requirements for non-fiction cannot be imposed on pure fiction. The complete backbone of prose cannot be imposed on line breaks in poetry or character dialogue. The checking script can enforce only hard prohibitions already written down. Warning items cannot decide the genre for the author.

## First Determine What the Work Promises About Reality

### Non-Fiction Writing

Real people, real events, figures, quotations, and user experiences must all be verified. Firsthand experience, scenes, dialogue, and psychology that the user has not provided cannot be added as facts.

### Fictional Creation

You may create characters, places, scenes, dialogue, psychology, and endings. Characters, time, causality, and world rules must remain coherent from beginning to end.

### Hybrid Creation

First separate the parts that must be accurate in reality from those that may be created. Verify only facts that affect the story and real-world judgment.

When the user says "novel," "fiction," "hypothetical," or "make it up freely," create directly. When the user requests truth, documentary writing, firsthand experience, or adherence to history, verify first and then write.

## Find the Speaking Position Before Writing

Answer the following five questions internally. Do not give the answers to the user verbatim.

1. Who is speaking about this matter. What gives them grounds to know it, and which parts are only speculation.
2. What made them want to talk about it now. It may be a news item, an experience, a question, or some small matter they have never been able to make sense of.
3. What do they have that can support the article. Prioritize actions, figures, times, places, direct quotations, failures, costs, and later outcomes.
4. On which point do they have a clear judgment. What is that judgment based on, and where does it stop.
5. Once readers know the previous paragraph, what would they most naturally ask next.

If item three is too sparse in a non-fiction draft, return to the material check before beginning. Do not use philosophy, symbolism, imagined scenes, or repeated conclusions to add words. A 6,000-word non-fiction piece needs enough material to unfold across multiple stages, cases, or real-world relationships. If a fictional draft lacks character goals, action, and scene changes, return to `references/fiction.md` and develop the story. Do not ask the user for real-world sources that do not exist.

When real-world material is insufficient, stop here first. Research available public material. When the work relies on user experience, emotion, and private judgment, ask the following three questions at once.

- What actual connection have you had with this matter.
- Which moment, number, action, or exact quotation concerns you most.
- What judgment do you most want to make now.

Do not first submit an empty draft and then expect the user to add a sense of a real person to it.

When a non-fiction draft must be written directly and no further material can be obtained, submit a shorter, more concrete work instead. Length is the goal. Material boundaries are the bottom line. For fictional tasks, create directly within the authorization. Events and scene changes support the length.

When a personal experience lacks key material, ask at most three questions. When the user explicitly requests no follow-up questions or asks for a draft directly, research first, then narrow the topic or shorten the length. Do not attach newly invented experiences to the user.

## Write the First Draft With a Person in It

Start the first draft from a specific speaker and material. Explain it as though speaking to someone interested in the matter but unfamiliar with it, telling the story while addressing the questions that person will naturally have next.

The following is the default approach for modern vernacular prose. Poetry, scripts, character dialogue, and experimental writing follow their specific genre rules. Do not damage a work merely to satisfy prose syntax.

- Get to the matter quickly at the beginning. You may answer directly, tell a scene that just happened, or begin with a small unusual fact. Do not preview the article's structure.
- Unless the user explicitly wants a list or tutorial, do not first name the topic as two costs, three layers of reasons, or four stages. Categories must come from the material. Do not use categories in place of an article.
- Let one paragraph complete the one thing immediately at hand. It may describe an action, add background, calculate an account, explain a reason, acknowledge a doubt, or make a judgment.
- Every new paragraph must add something new. A new fact, action, example, distinction, or consequence all count. Restating the same viewpoint in different words does not count as progress.
- The next paragraph should pick up the question left by the previous one. Progress comes from material and causality, not signposts such as "one layer deeper" or "the real problem."
- Let the subject and action appear first, then add time, reasons, conditions, and examples afterward. Long sentences are fine. Readers need to know early on who did what.
- Use vernacular language as the foundation. Classical flavor should arise naturally from word order, pauses, and restraint, not from rare characters, strings of idioms, or forced allusions.
- When action, detail, or a direct quotation has already expressed the emotion, pause. Do not follow it by explaining it for the reader.
- Allow normal repetition, additions, self-corrections, and brief digressions. Each must come from the immediate content. Do not perform casualness at fixed intervals.
- Judgments may be partial and emotional. Put the basis nearby so readers know that this is the author's view.
- In non-fiction, humor comes from the absurdity of the matter itself. Do not invent separate jokes or force witticisms into serious material. In fiction, jokes must belong to the characters, relationships, and scene.
- Paragraphs do not need to be equal in length. End ordinary passages with ordinary sentences. Reserve one-sentence paragraphs for places that truly need a pause.
- Stop when the matter has been told. Do not force a grand elevation, echo the beginning and ending, or add historical significance. Keep connections across the piece only when the function or meaning of something has already changed. Return to a historical scale in the ending only when the body has continuously dealt with that scale. Do not summarize the whole piece again in the final paragraph.

Use the following pair of sentences to calibrate direction.

> After graduating, he left Shanghai and went to Chengdu. That quantitative program had already been running for a while, and he felt he could try doing it full time. At the time, no one knew whether the income would be stable.

This is closer to the goal than "He closed off an easy road and wagered his fate on the gambling table." The first approach provides action, conditions, and risk. The second has only a pose.

## Do Not Put On Forum Costume

A forum feel does not mean "friends," "brothers," "thanks for the invitation," or "make a cup of tea and let me tell you slowly." Cigarette butts, beer, cold steamed buns, late-night screens, and suddenly ringing phones also cannot conjure authenticity out of nothing.

In non-fiction, precise times, expressions, weather, room furnishings, and dialogue without sources are all false details. The more specific false details are, the stronger the AI flavor becomes. Fiction may create these elements, but the details must follow character perspective and action. They cannot merely serve as forum costume.

What truly helps a non-fiction piece is the provenance of information. State clearly where the author learned about the matter, where they were initially wrong, which piece of material changed their judgment, and which part remains uncertain even now. Select only the parts the current article actually possesses. Do not try to complete the set. Fictional credibility comes from how characters know, misunderstand, and discover things. Do not fabricate real-world sources.

## The Final Draft Must Absolutely Not Contain

The following items apply to titles, subheadings, body text, image captions, and quoted paraphrases. If even one is present, the draft cannot be delivered.

Understand one thing first. What is prohibited here is the rhetorical move, not the literal wording. Replacing a forbidden sentence pattern with different words while performing the same move still counts as a violation.

- Do not use a reversal reveal. A reversal reveal first establishes a misunderstanding the reader does not have, then overturns it to raise the value of what follows. Known forms include "not...but...," "it is not...it is...," "it does not lie in...it lies in...," "rather than...it is better to say...," "on the surface...in fact...," "seemingly...actually...," as well as their variations, "not A, but B," "not A. But B," "you think...but actually...," "only looking back did I realize," "when all is said and done," "the answer is exactly the opposite," and "A is not important, what matters is B." This list is illustrative, not exhaustive. The same move cannot be written with any wording. Make judgments directly and positively. Give the judgment first, then the basis. Only when the article has genuinely used material to move through a process from misunderstanding to correction may the author's own correction appear, and it cannot use any of the fixed forms above.
- Do not write parallel constructions of more than three similarly structured items. Neat uniform sequences such as "why set out, why give up, what one loved, what one feared" are restrained clothing. Limit them to two items. The third must be rephrased or deleted.
- Do not pair abstract nouns with concrete verbs to produce lyricism. Time does not keep details. Anxiety does not reveal a shape. The years do not wear something flat. Writing that is genuinely about concrete things is unaffected.
- Do not nominalize verbs. Write "optimized the process" as "made the process run smoothly." Write "achieved improved efficiency" as "how much faster it became and how many people it saved."
- Do not use em dashes `—`, double em dashes `——`, or en dashes `–`.
- Colons `：` and `:` are permitted for only one use, introducing a person's direct quotation. Prompting colons such as "A one-sentence summary:" and "The core is:" are prohibited. URLs, code, and machine fields are exceptions.
- Do not use "plainly speaking," "to put it bluntly," or "let's start with the conclusion."
- Do not use "more subtly," "there is another layer," "it only gets half of it right," "it is worth noting," "it needs to be pointed out," or "in a certain sense" as insight signposts for a paragraph or sentence. When the text is genuinely referring to their literal meanings, such as floors or quantities, this does not apply.
- Do not use business-reporting jargon and model-favored buzzwords to inflate ordinary matters. `references/revision.md` distinguishes absolutely forbidden words from words that require contextual judgment. The checking script must not create additional unwritten hard-forbidden words on its own.
- In non-fiction, do not use metaphors such as warehouses, drawers, temperature, death, collapse, waves, keys, and foundations to package abstract concepts. Writing that is genuinely about these things is unaffected.
- When direct quotations violate these prohibitions, paraphrase or omit them. Do not preserve them through quotation marks.

"Not only...also..." is a normal progression and may be used. When it appears in a reversal position and is used to raise the value of what follows, treat it as a reversal reveal.

Run these checks only after the first draft is complete. When revising a prohibited sentence, first find the fact it originally intended to express, then state it in an ordinary sentence. Do not look for another elegant sentence pattern to replace it.

A long piece may be saved as Markdown or text and checked with `scripts/check_prose.py <draft path>`. If the script fails, continue revising until the prohibited items reach zero.

## Delivery

When the user wants only the work, deliver only the work. Do not show internal outlines, rule checks, or the creative process. The opening search trace required by `references/reality.md` is part of the body text and does not count as the creative process.

There is only one rule for handling sources. For factual pieces written entirely from public material, list the few sources important to the conclusion at the end. Do not attach them to personal-experience and opinion pieces. Follow the user when they have other requirements. Do not stuff research notes into the body.

Serve only the current work. Do not establish long-term author profiles, generate personal rule libraries, or create new personal writing Skills.

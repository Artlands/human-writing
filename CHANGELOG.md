# Changelog

## 1.2.1 (2026-09-01)

Added comprehensive scientific-writing support for research papers, abstracts, literature reviews, research and grant proposals, and technical reports. The new evidence-first reference guide embeds practical reporting and proposal requirements from PRISMA, NIH, and NSF; includes an illustrative NSF Project Summary and compliance checklist; and provides templates for abstracts, methods, results, literature synthesis, and peer-review responses. Scientific conventions now override general prose rules when required for precision or venue compliance.

## 1.2.0 (2026-09-01)

Migrated the Skill, reference guides, lite guide, agent metadata, and documentation to English. Updated repository branding and descriptions to be language-neutral so the Skill is not positioned as specific to Chinese writing.

## 1.1.0 (2026-08-05)

The core change can be summarized in one sentence. Prohibitions move from string-level to rhetorical-action level, detectors supplement blind spots, reduce false positives, and add statistical layers.

### SKILL.md

Rewritten "Absolute prohibitions in final drafts." The sentence pattern list like "not...but..." is upgraded to an action-level definition of "reversal tone," listing nine known variants as examples rather than boundaries, with alternative actions specified (make judgments from the front, give judgment first then evidence). Self-corrections earned through real material can be retained, but cannot follow fixed sentence patterns. Added three action-level prohibitions: three or more parallel structures with identical construction, poetic metaphors giving concrete verbs to abstract nouns, and verb nominalization. Colons changed to leveled usage: directly quoting original speech is allowed, but suggestive colons remain prohibited. "Not only...but also..." downgraded from hard prohibition to context-dependent judgment. Fixed three rule conflicts: the 600-word short answer when asking is clarified as fallback for "fewer than five materials after research"; source delivery unified into one rule; search traces clarified as not counting as showing creation process.

### references/revision.md

Fifth pass adds "Reversal tone variant comparison table" with seven categories of disguises listed one by one. Added checks for parallelism, poetic metaphor, and nominalization. "Closed loop," "tactics," "imaginative space," and "not shameful" moved from absolute prohibitions to context-dependent words in the prohibited word list. Added list of model-preferred lyrical words (placement, arrival, faint light, wrinkles, etc.) and check for excessive highlighted phrase density. Seventh pass clarifies that major words in user-specified titles are not subject to end-word prohibitions.

### references/forum-prose.md

Added four quantifiable model-tone fixes in the "Let sentences have both tightness and looseness" section: sentence length must have ups and downs, delete half the conjunctions (with before/after comparison), restore nominalization to verbs, repeat when needed. Added two original examples: "Make judgments from the front, don't use reversal to inflate value," "Long and short sentences breathe on their own."

### scripts/check_prose.py

Fixed three types of missed detections in reversal sentence regex: cross-sentence reversal forms and character-swapped forms, both now detected as failures. Added warning layer for reversal tone variant family (thought...actually, didn't realize until later, not A, is B, has never...no relation to, cross-sentence apparent/seeming), three or more parallel structures with identical construction, nominalization sentence patterns, model-preferred lyrical words, excessive highlighted phrase density. Added statistical layer: warnings for low sentence length variation coefficient and high conjunction density. Fixed false positives: "not shameful" no longer triggers hard stops, "tactics," "imaginative space," "closed loop" moved to context-judgment words, colons introducing original speech downgraded to warnings.

### New Additions

dist/human-writing-lite.md, a distilled version under 2000 characters, available for direct paste into ChatGPT, Qwen Office, WorkBuddy and other chat scenarios and weaker models.

## 1.0.0 (2026-08-05)

First open-source release.

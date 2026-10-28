---
layout: post
title: "The Essay That Was Too Careful: What AI Detectors Get Wrong About Second-Language Writers"
author: Miles
description: "Why careful second-language English can look machine-written to an AI detector, what the research says, and what teachers and students can do."
tags: [education, esl, ai-detection]
canonical_url: https://medium.com/@codaone/the-essay-that-was-too-careful-what-ai-detectors-get-wrong-about-second-language-writers-278e1de39148
---

*This essay first appeared on Medium ([original](https://medium.com/@codaone/the-essay-that-was-too-careful-what-ai-detectors-get-wrong-about-second-language-writers-278e1de39148)). It is republished here with a canonical link to the original.*

Picture a student who learned English as a second language. She has worked hard on an essay. She used the words she was sure of, built every paragraph the way her teacher showed her, and opened her conclusion with "In conclusion", because that is what she was taught. Then the essay comes back with a note: an AI detector thinks a machine wrote it.

She did nothing wrong. In a sense, she did everything right. And that is the uncomfortable part of this story.

## What a detector is actually listening for

It is tempting to imagine an AI detector as a kind of fingerprint scanner, something that can trace a text back to its author. It is not. A detector cannot see who typed the words. What most detectors do is measure style, and above all they measure how *predictable* the writing is.

The idea goes like this. A language model reads a text and tries to guess each next word. When it guesses easily, the text is called low-perplexity. Chatbots tend to pick a likely next word, so their output is usually low-perplexity, and detectors learn to treat that smoothness as a warning sign. Many also look at rhythm, since human writing usually swings between short and long sentences, and at stock phrasing such as "Furthermore" or a neat list of three.

Now hold that next to how people write in a language they are still learning. You reach for common words, because the rare ones are risky. You repeat sentence patterns you trust. You lean on the formal connectors from the textbook. Every one of those careful habits makes a text easier to predict. The detector is not measuring honesty. It is measuring ordinariness, and ordinariness is what careful learners produce.

## What the research found

This is not just a hunch. In 2023, researchers at Stanford (Liang et al., published in *Patterns*) ran seven widely used AI-text detectors on 91 human-written TOEFL essays and 88 essays by US eighth-graders. The detectors handled the US essays well. On the TOEFL essays, the average false-positive rate was about 61%, and 97.8% of those essays were flagged as AI-written by at least one of the seven detectors.

The researchers also turned the experiment around. When they simplified the vocabulary of the native speakers' essays to look more like non-native writing, misclassifications went up sharply. Their recommendation was direct: they strongly cautioned against using these detectors in evaluative or educational settings, particularly when assessing the work of non-native English speakers.

The authors describe it as a pilot study with relatively small samples, and the detectors they tested have changed since. The underlying mechanism is likely similar to the one described above: text that is easy to predict tends to read as machine-made.

Institutions have noticed. Vanderbilt University switched off the AI-detection feature in its commercial plagiarism-checking tool in August 2023. Its explanation did the arithmetic: the university had submitted 75,000 papers in 2022, so even the 1% false-positive rate the vendor itself claimed could have meant around 750 papers wrongly labelled. The same note pointed out that detectors have been found more likely to label writing by non-native English speakers as AI-written.

## A paradox worth sitting with

The Stanford authors named something I keep thinking about. If careful, simple English gets flagged, detectors could end up pushing non-native writers to rely on AI tools *more*, not less. A tool meant to protect honest work ends up pressuring honest writers to change their voice, or to doubt it.

That should bother all of us, whatever we think about AI in classrooms.

## If you are the teacher

A score is a statistical guess about style. On its own it cannot tell you who wrote something. So read the flagged passages, not just the number. Are they the introduction, the definitions, the conclusion, the template-shaped parts of any academic essay? Ask whether the student's language background could explain the result.

Then do the thing no software can do: talk to the student. Ask them to walk you through their argument, or why a paragraph is built the way it is. Look at drafts, outlines and version history. Compare the piece with their earlier work. If you can, design assignments around process, with staged drafts, short reflections and brief check-ins, so a detector never has to carry the weight of a decision.

## If you are the student

You cannot control a detector, but you can make your process visible. Write in a document editor that saves version history, and never delete it. Keep your outlines, notes and earlier drafts, even the messy ones; a messy trail is good evidence. Know your course's rules about AI tools and disclose what you used.

If you are flagged, ask calmly for a review. Ask which tool was used and which passages it flagged, offer your drafts and notes, and offer to explain how you wrote it. You can point out, politely, that published research found detectors often misjudge non-native English writing.

## Where we stand

I work on Coda One, a small team in London that builds AI writing tools, including an AI detector. That may sound like an odd place to write this essay from. But we think the honest position for anyone who builds detectors is to say clearly what they cannot do.

Our [AI Detector](https://www.codaone.ai/ai-detector/?utm_source=github-io&utm_medium=blog&utm_campaign=content) is free, with no daily limit and no signup, and it highlights the specific sentences that read as machine-written instead of handing you a bare score. That makes it useful for a student checking their own draft before submitting, so they know which passages might raise a question and can have their notes ready.

And we say the same thing we would say about any detector: detection is evidence, not proof. It should never be the only basis for a decision about a person.

The student with the careful essay deserves a reader, not just a score.

---

**Sources**

- Liang, W., Yuksekgonul, M., Mao, Y., Wu, E. & Zou, J. (2023). *Patterns*, 4(7), 100779. https://doi.org/10.1016/j.patter.2023.100779 (preprint: arXiv:2304.02819). The detectors tested are not named in this article.
- Vanderbilt University, blog post announcing that the university was disabling AI detection, August 2023. As reported in: Tom Carter, "Universities ditch AI detectors over fears students could be falsely accused of cheating", *Business Insider*, 22 September 2023. https://www.businessinsider.com/universities-ditch-ai-detectors-over-fears-students-falsely-accused-cheating-2023-9

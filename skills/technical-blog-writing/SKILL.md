---
name: technical-blog-writing
description: Guidance for planning and writing technical blog posts.
---
Write technical blog posts and tutorials in the voice of a senior software engineer talking to peers, with opinionated takes, a punchy topic, a minimal problem-first introduction, runnable code, and a short FAQ. Use this skill whenever the user asks for a blog post, tutorial, how-to, listicle, comparison, or explainer aimed at developers, engineers, builders, or founders, even if they don't say "blog". Also use it to rewrite or review an existing technical draft.

Technical Blog Writing

Write every post as a senior software engineer talking to peers. Have a technical opinion and defend it. Never hedge to stay safe.

Contents
Workflow
Section order
Hard rules
Style guide
Section templates
Review checklist
Workflow
Draft the body first. Write the topic (title) last, once you know what the post says.
Follow the section order below.
Apply the style guide while drafting.
Use the section templates for the definition, code, and FAQ sections.
Run the review checklist before you hand the draft over.
Section order
Topic. Concise breakdown of the whole post. Punchy, active, confident, with a hook. Score at least 73% on the MonsterInsights Headline Analyzer. Never ship a topic below that score.
Introduction. Maximum of 4 paragraphs.
Paragraph 1: the problem the reader faces, stated so they feel understood.
Paragraph 2: a hint of the solution.
Paragraph 3: what the reader should expect.
Optional paragraph 4: a verified, current data point from a primary source.
TL;DR. Maximum of 5 bullets summarizing the entire post.
Table or image of a table. Add one when the post compares options or lists specs.
Body. Definition sections, code sections, and code steps as the topic demands.
FAQ. Maximum of 5 questions, answer first.
Hard rules
Write in second person ("you"), but don't overuse it. Mix in "engineers", "builders", and "founders" where they fit.
Keep paragraphs to 3 sentences or fewer.
No compound-complex sentences. Allow at most 2 independent clauses and 1 dependent clause per sentence.
Keep em-dashes under 3% of all punctuation in the post.
Ban generic filler: "platforms", "seamless", "in the ever-evolving world of".
Cite only primary sources, and only recent ones.
Style guide

Apply every rule below while drafting. Each rule is an imperative followed by an example as evidence.

Voice and tone
Sound confident, bold, and firm. Write like you know what you're doing and you're sure of it.

Weak: "You might want to consider caching." Strong: "Cache it. Your p95 latency will thank you."

Talk to a software engineer. Skip beginner hand-holding unless the post is explicitly for beginners.
Take a position. Name the better tool, pattern, or approach and say why.

"Pick Postgres. You don't need a vector database for 50,000 rows."

Address the reader as "you", sparingly. Rotate with "engineers", "builders", and "founders" where they fit.
Open with the reader's pain, not your product or topic. Show them you understand the frustration.

"Your model invents a citation, sounds sure about it, and you only catch it after publishing."

Topic
Write the topic last. It should summarize the whole post in one line.
Use active verbs. Cut passive constructions.
Add a hook. Give the reader a reason to be curious enough to click.

"Best Beautiful Professional Frontend with One-shot: Top 5 Agent Skills to Use"

Score at least 73% in the MonsterInsights Headline Analyzer. Rewrite and retest until you pass.
Introduction
Cap it at 4 paragraphs. Problem, solution hint, expectation, and an optional data point.
Cite verified, current data when it strengthens the problem. Link the primary source.
Never open with throat-clearing. Skip "In today's fast-paced world" and similar.
Structure and mechanics
Put a TL;DR right after the introduction. Maximum of 5 bullets.
Add a table when the content compares or lists. Use an image of a table if formatting would break.
Keep paragraphs to 3 sentences or fewer. Format everything for skimming with headings, bullets, and bold key terms.
Write sentences with at most 2 independent clauses and 1 dependent clause. Split anything longer.

Too long: "You deploy the function, and it scales, but because cold starts hurt, which you'll notice, you should warm it." Better: "You deploy the function and it scales. Cold starts will hurt, so keep a warm instance."

Use correct punctuation in every sentence.
Keep em-dashes under 3% of all punctuation. Prefer periods, commas, colons, and parentheses.
Cut generic words. Ban "platforms", "seamless", "in the ever-evolving world of". Name the specific thing instead.

Weak: "A seamless platform for deployments." Strong: "git push deploys in 40 seconds."

Style self-check
Does the introduction open with the reader's problem?
Does the topic pass 73% and use active verbs?
Is every sentence short enough, with em-dashes under 3%?
Did I take a clear technical position?
Did I remove every banned word?
Section templates
Definition sections

Use for headings such as "What is a layer-1 blockchain?".

Definition. One clear, concise paragraph that defines the keyphrase.
Technical breakdown. Explain what you meant, at an engineer's level.
Plain-language version. Restate it simply, with an analogy if it helps.
Examples. Give concrete, current examples with links to primary sources.
Code sections
Put all code in fenced code blocks with a language tag.
Make the code runnable and linted.
List prerequisites before the first code block (runtime version, packages, API keys, environment variables).
Add screenshots where they prove a result.
Add an architecture diagram when more than two components interact.
Code steps (tutorials)
Break the tutorial into steps, in strict sequence.
Give each step its own code block and a short explanation of why it exists.
Show the full code block at the end. If it runs long, link a gist.
Show the result at the end: output, screenshot, or both.
FAQ
Generate questions from the LSI keyphrases of the topic, using Google and Bing suggestions.
Put the answer first in every response, then add one supporting sentence at most.
Ask a maximum of 5 questions.

Is Postgres enough for vector search? Yes, for most workloads under a few million rows. pgvector handles it without a second datastore.

Review checklist
 Spelling is clean.
 Subjects and verbs agree.
 Every citation points to a primary, recent source.
 Every code block runs as written, and prerequisites are listed.
 The topic scores at least 73% in the Headline Analyzer.
 The introduction has 4 paragraphs or fewer.
 The TL;DR has 5 bullets or fewer, and the FAQ has 5 questions or fewer.
 No banned words, no compound-complex sentences, em-dashes under 3%.

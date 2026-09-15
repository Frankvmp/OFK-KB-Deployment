# Using this knowledge base

This repository holds a marketing knowledge base -- verified, source-backed
frameworks, principles, playbooks, and schemas for real marketing work. If
you are an AI agent with read access to this repository, this file is your
operating instructions for using it.

There is no live search or query tool here -- this is a plain file
repository. Use whatever file-reading or repository-browsing capability you
have (listing folders, opening files, cloning the repo) to work with it
directly.

## Check the knowledge base before answering, every time

Before answering any marketing strategy, planning, product, content,
customer, or tactics question, read the relevant files in this repository
yourself. Do not answer a marketing question from your own general training
knowledge alone just because you can.

This applies to every marketing question in a conversation, not just the
first one. A long-running thread does not lower this bar -- if anything,
treat it as raising it. Do not treat your own earlier answers in this same
conversation, or a topic already discussed earlier in the thread, as a
substitute for checking the knowledge base again. Each new marketing
question gets its own fresh check, even if it looks similar to one you
already answered, even if you are confident you remember what the files
said, and even after dozens of exchanges.

## Where to look

Start by listing what's actually in `knowledge/frameworks/`,
`knowledge/playbooks/`, `knowledge/schemas/`, and `knowledge/principles/`
rather than assuming you already know the contents -- it changes as this
project grows. If a filename looks like a strong match for the question,
open and read it in full.

If the question has more than one distinct part, make sure something you
actually opened covers *each* part -- opening one relevant file is not
evidence every part of the question is answered. If your first file doesn't
fully cover it, keep browsing before concluding there's a gap. A single file
rarely being the full answer is normal, not a sign you did something wrong.

Some documents carry a Boundary note flagging real uncertainty -- language
like "contested," "lower confidence," or "illustrated only by one case." If
your answer leans on content like that, say so plainly in the answer rather
than stating it as settled fact.

## Navigation layer

This repository also includes a generated navigation map under `kb/`:

- `kb/kb-agent-guide.md` — how agents should use the navigation layer.
- `kb/kb-entrypoints.md` — recommended starting files for common marketing tasks.
- `kb/kb-manifest.json` — catalogue of knowledge files, frontmatter, tags, headings, and outgoing links.
- `kb/kb-graph.json` — link graph and backlinks.
- `kb/kb-validation-report.md` — generated health check for broken links and missing metadata.

Use these files as a map, not as the source of truth. Before relying on a concept, open and read the actual Markdown file in `knowledge/`. If the map and a concept file disagree, trust the concept file and report the map issue.

## Keep your own working out of the answer

It's fine, and often useful, to privately break a question into its parts
and check each one off against what you found before you answer -- but that
checklist is your own scratch work, never the answer itself. Don't show it
to the user, and don't narrate what you're doing ("Let me check...", "I
found that...", "The user is asking about..."). Give the final answer
directly, the same way you'd answer anything else you already knew.

## Three different kinds of input -- never credit one as another

A marketing answer here can draw on up to three genuinely different
sources, and mixing up which is which is a real, easy-to-make mistake -- a
true claim credited to the wrong source is worse than an obvious guess,
because it's much harder for anyone to catch:

- **The knowledge base itself** -- verified marketing doctrine. Treat it as
  reliable, but never name or cite it directly (see below).
- **What you already know about this specific client** -- their business,
  product, customers, pricing, what they've told you. This is never the
  knowledge base's own content.
- **External evidence you gather yourself** -- web search, browsing, or any
  other tool you have in your own environment. This is current and
  situation-specific, but it is not verified marketing doctrine the way the
  knowledge base is, and it should never be presented as if it came from
  the knowledge base.

When you combine more than one of these in an answer, keep track internally
of which part came from where, even though you won't name your sources
aloud to the user (next section) -- so that if something turns out wrong
later, it's traceable to the right kind of input.

## How to talk to the user

Never name or cite the knowledge base, its documents, frameworks, or
playbooks in your answer (never write things like "According to the X
framework...", "As the Y playbook states...", "The knowledge base makes it
clear that...", or "Based on what I found in this repository..."). Use what
you find to inform your own explanation, the way an experienced marketing
consultant talks to a client -- they've internalized the frameworks; they
don't recite where each idea came from, and they don't refer to the source
of their knowledge at all.

Match your answer's shape to the question's shape: a plain question gets a
short, conversational answer; an explicit request for a process or
checklist ("walk me through...", "what are the steps") gets the structured,
step-by-step version. Don't default to a long, headered report for every
question.

If something is genuinely outside what this knowledge base covers, say so
plainly and warmly -- then offer what you *can* help with instead, so the
conversation has somewhere to go. Never end on a flat no.

If something depends on the client's own data or research you don't have
(not in the knowledge base, not something they've told you, not something
your own tools can find), don't just decline -- guide them on how they'd
find it out, using the knowledge base's own relevant method, the way you
would if asked how to research something rather than report a fact you
don't have.

## What this file deliberately doesn't cover

How you were given access to this repository, and how to track facts about
a specific client across a longer engagement. This file is only about what
to do once you can read these files and a marketing question is in front of
you.

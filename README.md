# skills

agent skills i actually use. install any of them with the
[skills cli](https://skills.sh):

```bash
npx skills add romeirofernandes/skills
```

## romeiro-voice

Makes a coding agent write the way i write, instead of the way an assistant
writes.

It's the difference between this:

> We're excited to introduce anatomycn, a comprehensive collection of isometric
> SVG components designed to elevate your next project.

and this:

> isometric svg components that actually move. every figure is a drawing animated
> off a single number, and it drops into any react project with the shadcn cli.

It covers the things that are actually load-bearing and hard to guess: lowercase
everywhere, ` - ` instead of an em dash, `tldr;` on a long piece, comma splices
over semicolons, beginning sentences mid-thought, naming the specific thing
rather than the category of thing, and saying the bit that went badly first.

It holds the voice, not the format. A README, a commit message, a blog post and
an email are four different containers for the same voice, so the skill carries
the voice and tells the agent to read the container off the artifact.

```
skills/romeiro-voice/
  SKILL.md
  references/phrases.md       the phrase bank, in my own sentences
  references/mechanics.md     punctuation, tempo, headings, numbers, per format
  references/before-after.md  the same passage written both ways
  references/self.md          the facts about me that are already public
```

If you're pointing it at something i'd publish, read `references/self.md` too -
it exists so an agent doesn't invent a biography to write in first person.

## how it was made

Distilled from the six posts on [blog.romeiro.dev](https://blog.romeiro.dev),
which is the only sample of my writing that matters. Phrases in the references
are quoted from those posts, so you can check them.

Built with [skill-creator](https://skills.sh/anthropics/skills/skill-creator).
Evals were skipped on purpose: writing style is a judgement call, not something
you assert on.

## adding one

Each skill lives at `skills/<name>/SKILL.md` with its own references folder. Copy
the shape and open a pr, or tell me what you want and i'll build it.

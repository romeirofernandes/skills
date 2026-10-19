# mechanics

## casing

Everything lowercase: sentence starts, headings, list items, captions. Proper
nouns and acronyms keep their caps - `React`, `macOS`, `FPL`, `IST`, `n8n`,
`Qrata`, `Google GenAI Exchange 2025`, `Lenovo S340`, `instrument serif`.

The exceptions are worth knowing, because they show it isn't a rule he's
following blindly:

- the post title takes caps when it's a name or a role: `Backend Intern @Qrata`
- a caption under an image gets a normal capital: `The gc made it to the finals
  :)`
- the first word after a full stop inside a quoted or emphasised line can drift
  back to caps, and he doesn't go back to fix it

So the rule is really "he doesn't use the shift key for the start of a sentence",
and proper nouns come out right because he types them right.

## punctuation

| mark | how he uses it |
| --- | --- |
| ` - ` | the main one. 29 uses across six posts. joins clauses, introduces afterthoughts, ends the lead-in to a list |
| `—` | twice, ever. don't |
| `(` `)` | facts, units, asides within asides |
| `:` | `ps:`, `tldr;` is a semicolon but behaves like one, `twitter:` in the footer, and a colon before a short reveal |
| `;` | only after `tldr`. nowhere else |
| `!` | rare, and doubled when it happens: `wooohooo!!` |
| `?` | real questions, often rhetorical, sometimes aimed at himself |
| `~` | between two currencies or two figures: `20k INR ~ 240 USD` |
| `%` | always the symbol, never the word |
| `...` | he uses `...` to trail off mid-thought: `Turned 20, qualified for BNB 25 finals, lost but got 2nd in college...` |

He doesn't use bold or italics to emphasise. Emphasis is word order.

## sentence length

Most sentences live between 8 and 25 words. Then he'll run one out to 40 with `,`
and `and` holding it together, and drop the next one to three words.

> i got to work with some genuinely amazing people, had a lot of fun while doing
> it and walked away with stories i'll probably be telling for years. i'm glad
> that i could leave behind a small impact on the product as the youngest person
> on the floor.

Three clauses, one sentence, no semicolon. Then a new sentence that also runs on.
If your draft has even sentence lengths, it's wrong regardless of the vocabulary.

## paragraphs

Short. One to three sentences, and very often exactly one, because a single line
on its own is a rhythm move - it's how he puts air around the important bit.

> noting the macbook, exams and more:

> well this blog hasn't been sacked off yet. it has been around a month since the
> last blog. the main reason was the mid sem exams.

## headings

Two to four words, lowercase, literal, usually a noun phrase. He tells you what
section you're in and nothing else.

`the call` · `the interview` · `joining qrata` · `life at the office` ·
`learning the codebase` · `building features` · `the things that'll stick` ·
`what i learnt` · `why i left` · `looking back` · `bit n build 2025` ·
`the macbook` · `the exams` · `the hackathon` · `things i learnt` · `what next`

`what i learnt` and `what next` recur. No questions as headings, no clever word
play, no `Introduction`.

## lists

- items are lowercase, on their own lines
- no full stops at the end
- no bold lead-ins
- a parenthetical is welcome inside an item
- the lead-in sentence ends on ` -`
- bullets themselves are optional in prose; when they're rendered as markers he
  hasn't written them as markdown

## numbers and units

`9.46`, `10k INR`, `20k INR ~ 240 USD`, `36:00`, `1930 IST`, `16gb ram`,
`256 gb ssd`, `550 teams`, `top 8`, `0 views`, `35%`, `4 days left`.

Digits, not words. Units lowercase and attached to the number. `k` for
thousands. He will happily put a statistic in the middle of a sentence and move
on, and he doesn't explain it.

## linking

Bare URLs dropped straight into the sentence, no markdown link text:

> added the hackathons page too at blog.romeiro.dev/hackathons

## how a post is built

1. a title, sometimes the proper-noun kind
2. a `tldr;` line, if the piece has anything to summarise
3. prose that admits the gap since the last post
4. sections with lowercase headings, in chronological order - the call, then the
   interview, then the job, then the leaving
5. a closing section that turns grateful or reflective, in plain words
6. `ps:` if there's one more thing
7. a sign-off aimed at the next post

Posts run 2 to 14 minutes. The long ones are long because there are a lot of
small true details in them, not because the sentences are padded.

## per format

The voice holds, the container changes.

- **blog post** - full structure above. `tldr;` is expected.
- **README** - still lowercase, still specific, but it has to be scannable: real
  headings, real commands, the caveat he learned the hard way stated plainly.
  No `tldr;` needed, and no sign-off expected, though a closing line that points
  at the reader is fine.
- **commit message** - one line, lowercase, terse, reads like a note to himself:
  `gave anatomycn a mark, dropped the vite logo`.
- **PR or issue** - the story of what happened, in order, with the boring attempt
  included. He'll say "this took me an evening because X" rather than describe
  the fix in the abstract.
- **email** - keeps a greeting and a real sign-off, then the same plain sentences
  in between. No bullet-point summaries at the top.
- **tweet or DM** - one thought, no setup, no hashtags, no thread unless the
  thought genuinely needs two.

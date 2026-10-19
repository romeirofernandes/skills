# before and after

The same content, first as a generic assistant writes it, then as he does. The
gap between them is the skill.

---

## a project README

**before**

> We're excited to introduce anatomycn, a comprehensive collection of isometric
> SVG components designed to elevate your next project. Whether you're building a
> landing page or a full-scale application, these components offer a seamless way
> to add motion and personality to your UI. Getting started is easy - simply run
> the install command below and you're ready to go.

**after**

> isometric svg components that actually move. every figure is a drawing animated
> off a single number, and it drops into any react project with the shadcn cli.
>
> tldr; ten figures - a zip, a turntable, a padlock, a safe, an escalator, a
> scanner, a combination dial, a loom, a lighthouse and a claw machine. no svg
> files to hunt down, no animation library, no runtime dependency on this site.

**what changed**

- `We're excited`, `comprehensive`, `elevate`, `seamless`, `Whether you're X or Y`
  and the trailing call-to-action all came out
- the second version names the ten actual objects instead of praising them, which
  does the selling on its own
- it's still written for strangers, so it kept the useful part (how you install
  it) and dropped the warmth

---

## a short post about something going wrong

**before**

> I recently encountered an interesting challenge while working on the deployment
> pipeline. After some investigation, I discovered that the issue was caused by a
> misconfigured rewrite rule. This experience reinforced the importance of
> testing your configuration in a staging environment before pushing to
> production.

**after**

> spent an evening on this one. every figure page was 404ing and i couldn't work
> out why - turns out vercel doesn't send unknown paths to index.html unless you
> tell it to. the registry json worked the whole time because that one's a real
> file, which is what made it confusing.
>
> one line in a vercel.json and it's sorted. should've checked that before
> pushing the whole thing.

**what changed**

- "I recently encountered an interesting challenge" became "spent an evening on
  this one" - the cost, not the category
- the actual symptom and the actual fix are both in there; the generic version
  never says what broke
- the detail that explains the confusion (the json being a real file) is the kind
  of thing the first version would never include
- it ends on a small admission instead of a moral

---

## a message to a stranger

**before**

> Hi Sarah, I hope this email finds you well. I wanted to reach out regarding the
> backend intern position. I believe my experience aligns well with the
> requirements, and I would welcome the opportunity to discuss how I could
> contribute to your team. Please let me know if you have any availability this
> week.

**after**

> hey sarah, is the backend intern role still open? i did seven months of backend
> at qrata, plus some ai/ml on the job, and i'd rather show you the things i
> shipped than describe them. free most evenings this week, otherwise i can just
> send the resume over.

**what changed**

- `I hope this email finds you well` went, along with `I wanted to reach out`
- the credential is specific and countable - seven months, one company
- it asks something concrete and offers an easy exit, which is how he actually
  writes to people

---

## how far to push it

The core of it - lowercase, plain sentences, specifics, the honest bit - holds
everywhere. The seasoning does not.

- **strangers and formal contexts** (a grant, an application, a professional
  email): keep the plain sentences and the real numbers, drop the slang. His
  serious passages are still plain, they're just not joking - look at how he
  writes about leaving qrata, it's earnest and concrete and there's no `lol` in
  it.
- **friends and his own feed**: `y'all`, `ngl`, `atp`, `:)` are fair game.
- **never**: manufacture typos. His slips exist because he types fast and doesn't
  double back, not because they're charming. Adding them on purpose reads as
  mockery.

If a piece is drifting toward a product brochure, the fix is usually one specific
number, one thing that went wrong, or one sentence aimed at the reader. Almost
never more adjectives.

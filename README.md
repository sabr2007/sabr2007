<div align="center">

<img src="./ascii.svg" width="460" alt="Sabyrzhan"/>

<img src="./stats.svg" width="620" alt="Contributions in the last year"/>

[telegram](https://t.me/sabrval) &nbsp;·&nbsp;
[x](https://x.com/sabrvaliullov) &nbsp;·&nbsp;
[linkedin](https://www.linkedin.com/in/valiullov-sabyrzhan) &nbsp;·&nbsp;
[email](mailto:sabyrzanvaliullov@gmail.com)

</div>

<img src="./hd-about.svg" width="620" alt="about"/>

> Big-data student, building LLM products in the open.<br>
> Ship the smallest thing that proves the idea, then keep only what survives.

Most of what I build sits at the same seam: a language model doing real work<br>
behind a product surface people actually touch — chess coaching, journaling,<br>
feedback triage, RAG hygiene. Telegram bots when the interface should be a<br>
conversation, Next.js when it should be a page, FastAPI and Postgres underneath.

<img src="./hd-stack.svg" width="620" alt="stack"/>

<samp>typescript &nbsp; python &nbsp; next.js &nbsp; react &nbsp; fastapi &nbsp; postgres &nbsp; supabase &nbsp; openai &nbsp; java &nbsp; swift &nbsp; docker &nbsp; git</samp>

<img src="./hd-projects.svg" width="620" alt="projects"/>

**[blunderlab](https://github.com/sabr2007/blunderlab)** &nbsp;·&nbsp; <samp>next.js, supabase, stockfish wasm</samp><br>
AI chess coach that refuses to stop at "best move". It names why the blunder<br>
happened, the pattern underneath it, and what to drill next.<br>
[blunderlab.vercel.app](https://blunderlab.vercel.app)

**[staleness-monitor-v2](https://github.com/sabr2007/staleness-monitor-v2)** &nbsp;·&nbsp; <samp>typescript, next.js</samp><br>
Knowledge bases rot quietly and RAG chatbots keep answering from them. This<br>
diffs documents against the live site, surfacing contradictions and<br>
time-stamped claims that have expired.

**[linetta](https://github.com/sabr2007/linetta)** &nbsp;·&nbsp; <samp>python, typescript</samp><br>
Voice-first AI journaling. Speak, and the entry writes, tags and connects<br>
itself — landing, docs and backend core in one repo.

**[hearify](https://github.com/sabr2007/hearify)** &nbsp;·&nbsp; <samp>next.js, typescript</samp><br>
Passive feedback intelligence: read what users need from the channels they<br>
already use, before anyone files a ticket.<br>
[hearify-weld.vercel.app](https://hearify-weld.vercel.app)

<samp>A few more live under NDA and aren't listed here.</samp>

<img src="./hd-stats.svg" width="620" alt="stats"/>

<div align="center">

<img src="./streak.svg" width="620" alt="Current and longest streak"/>

<img src="./langs.svg" width="620" alt="Top languages by bytes and by repo"/>

<img src="./year.svg" width="620" alt="The last year, one character per day"/>

</div>

<img src="./hd-about-this-page.svg" width="620" alt="about this page"/>

Every graphic here is generated, not embedded from anyone else's server.<br>
`ascii.svg` is a photo pushed through a character ramp by<br>
[`scripts/make_portrait.py`](scripts/make_portrait.py); the stat graphics and<br>
these section headings are drawn by [a scheduled action](.github/workflows/stats.yml)<br>
straight from the GitHub GraphQL API, once a day, committing only what changed.

They animate with SMIL inside the SVG, because GitHub strips scripts from<br>
READMEs — and since nothing loads from a third party, nothing here can<br>
rate-limit or go dark. The headings are SVGs for the same reason: GitHub also<br>
strips CSS, so an image is the only way to put this page's own typeface on them.

The typeface is [JetBrains Mono](scripts/fonts), subset to just the characters<br>
each graphic draws and inlined as base64. That isn't only for looks: the<br>
portrait's grid assumes an advance width of exactly 0.600 em, and a viewer whose<br>
default monospace is narrower would otherwise see it squeezed.

Language totals cover public repositories only. `year.svg` uses the portrait's<br>
character ramp: `:` `+` `#` `@`, quiet to loud.

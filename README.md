# 🛑 Bun't

## 🤷 Why?

Because Bun instability causes issues for package authors using node is
encouraged instead.\
If you'd like to keep using the command `bun`, please run the command
`alias bun=node`.

Bun is unethical and exploits whatever it can for profit.\
It tries to benefit on pure hype, while consistently underdelivering on
promises.

What did Bun do wrong?

- https://github.com/oven-sh/bun/pull/657 – Ignored PR to make benchmarks more
  fair and then banned the author!
  - On another note, Jarred – making benchmarks fair is "gaming", but when you
    pull ~2K LOC just to make stringWidth faster its not?
- https://github.com/oven-sh/bun/issues/921 – Bun caches everything about SQLite
  and doesn't invalidate it properly
  - https://github.com/oven-sh/bun/pull/1056#pullrequestreview-1079694125
  - https://github.com/oven-sh/bun/issues/1332 – Even says that he doesn't want
    to invalidate it unless its equal to performance!\
    Why would you have working things, when they can be fast?
- Completely outdated benchmarks on the website? <at the time of writing>:
  - Comparing Bun 1.0 to Deno 1.36.2 (1.35.2 on sqlite benchmark?) and Node
    20.5.0 (20.4.0 on sqlite benchmark) where Deno 1.41 and Node 21.6.2 are
    available
- Why doesn't Bun mention when its slower?
  - https://github.com/oven-sh/bun/issues/5197 – 300x slower Regex than node
  - https://github.com/oven-sh/bun/issues/8637 – 2.8k requests/s on sveltekit?
    My grandma runs faster!
  - https://github.com/oven-sh/bun/issues/7428 – 100x slower than node AWS S3
    writes
  - and more!...
- Or that it doesn't actually support all web standards node or deno does?
  - And if it does, often incompletely?
- Or that it segfaults... whenever it wants?
- How about not caring about your own employees?
  - https://twitter.com/oven_sh/status/1562248121656102914
    - web archive:
      https://web.archive.org/web/20220901000000*/https://twitter.com/oven_sh/status/1562248121656102914
  - https://www.reddit.com/r/webdev/comments/wwzftt/oven_company_that_makes_bunjs_wants_new_hires_to/

## 📝 Licensing

This project is available under **BEL 2** License conditions.

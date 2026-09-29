# The Forty Questions method

How we measure how often AI assistants (ChatGPT, Claude, Perplexity, Google's AI
answers) name a company when a buyer asks them for a recommendation. It's
published so anyone can check a number we produce, or take the measurement
themselves without us.

- [`METHOD.md`](METHOD.md): the rulebook. Frozen questions, three repeats on three
  separate days, logged-out fresh sessions, counting rules fixed before
  collection, and what gets excluded. Mirrors https://fortyquestions.io/method.
- [`COSTS.md`](COSTS.md): measured per-answer API costs from billed calls.
  Mirrors https://fortyquestions.io/cost.
- [`questions/forty-questions.json`](questions/forty-questions.json): the two
  frozen question sets we measure *ourselves* against, with their dates. We
  publish them before the results, so the questions can't be tuned to flatter
  the number afterwards.

## What is not here

- No client or prospect data, names or answers. Those belong to the company
  measured.
- No API keys or collection code.

## Status

Forty Questions launched in September 2026. Our own baseline on the original five
questions (23–24 Sep 2026): named in 0 of 40 answers. Results are published
monthly at https://fortyquestions.io, including the months they don't move.

Maintained by Satayu Isariyaphorn · satayu@fortyquestions.io

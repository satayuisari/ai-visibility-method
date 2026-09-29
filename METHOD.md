# How to measure whether AI assistants recommend you 

The full rulebook we use, published in advance, so anyone can check a number we produce — or take their own measurement without us. 

Version 1.4 · last updated 22 September 2026 · Satayu Isariyaphorn 

To measure how often AI assistants recommend a company, ask a frozen set of buyer questions three times each, on three separate days, each in its own logged-out session with no memory and no follow-up, and count the answers naming the company against a rule written before collection began. One run is an anecdote. A rate without its sample size is decoration. 
## Why the rules exist 

On 20 September 2026 we asked the same five buyer questions about one Singapore point-of-sale vendor two different ways. The questions were identical, word for word. The answers were not.       
| How the five questions were asked | Named at all | Appeared first |
|---|---|---|
| Each question in its own fresh session | 3 of 5 | 2 |
| All five in one continuous conversation | 5 of 5 | 4 |

The likely cause is context carryover: once an answer has recommended a company, later answers in the same thread can see it and tend to keep recommending it. 

> **What this table does not prove.** The two rows differ in two ways, not one — the first was run on Claude, the second on ChatGPT. Assistant choice could account for part of the gap. Until the same assistant is run both ways, this is a warning sign and not a measurement, and we do not show it to a client as one. We publish it unfinished on purpose: a method you can only see once it flatters us is not a method. 

A separate test isolated one variable cleanly. Adding six words to a question — *“name specific products, don’t hedge”* — moved the same vendor from named in 3 of 5 answers to 5 of 5, and from second on recommendation share to first. Same assistant, same questions, fresh sessions throughout. Only the instruction wrapped around the question changed. 

That finding is why rule 1 exists, and why a founder who checks on themselves usually gets a better number than we report. They are not being lied to by the assistant. They asked a different question. 
## The seven capture rules 

A run that breaks any of these is not a measurement, and is excluded in writing rather than dropped quietly.  
- **Nothing is wrapped around the question.** The buyer’s question goes to the assistant bare. No “name specific products”, no “don’t hedge”, no “be concise” — those are instructions about how to behave and they change who gets named. Any instruction we do send is recorded word for word beside the answer. 
- **One question, one throwaway session.** Never a second question in a thread that has already answered one. The thread is discarded after each question. 
- **Logged out, memory off.** Temporary chat or incognito, no saved memory, no custom instructions. We measure what a stranger is told about you, not what your own account is told. 
- **Search state set deliberately and recorded.** Whether web search is on changes answers substantially. It is held constant across a comparison and written down beside every answer, along with the model that produced it. 
- **Wording frozen, down to the punctuation.** Identical across every assistant, every repeat, and again next month. Otherwise the change you see between months is your own wording moving. 
- **The buyer’s country stated in every question.** Leave it out and assistants answer about the United States. We learned this directly: one question without it returned three US products to a Singapore buyer. 
- **Recorded whole, before anybody reads it.** The full answer and every link it cited, saved unedited and untranslated, so any count can be checked against the words.  
## How counting works 

The rule for what counts as a mention is decided in code and applied identically to the client and to every competitor. A company counts as named when its name appears in the answer text. Case-sensitive matching is used for names that are also ordinary words, and the surrounding sentence is captured so an ambiguous hit can be checked by a person. 

Every question is asked three times on three separate days. Three repeats taken hours apart are not three repeats — if a day is missed, the series stretches by a day rather than catching up in one afternoon. 
## What gets reported separately 

Six of the forty questions ask an assistant to compare two named rivals. It answers about those two. A company not named in the question rarely appears in the answer, so those six are reported on their own line rather than removed. 

The headline stays the all-questions figure. A rate whose denominator we choose is a rate we could quietly improve. 
## What this cannot tell you 

Every number has an edge and ours is here. 

**We measure a stranger, not your existing customer.**  We ask logged out with no history — which is exactly the person who has not bought from you yet. What an assistant says to someone with months of chat history is different, and nobody can measure that from outside. 

**We count naming, not revenue.**  Being named more often is not proof of more sales. It is the part that can be measured, and it happens before anyone reaches your site. 

**One assistant runs without web search.**  Gemini’s terms do not permit the automated grounded route, so that row measures what the model already knows. It is reported beside the number, never added into it. 

**Assistants change underneath the measurement.**  When a provider swaps a model mid-month, a jump may be theirs rather than yours. The model behind every answer is recorded so this shows up as a flag rather than as progress. 

**One row depends on a third party.**  Google’s AI answers are collected through a search-data provider we do not control. If that route closes, the row pauses and the report says so where the number would have been. We will not tell you a spare is ready when it is not. 
## Take your own measurement 

Everything above is enough to do this yourself without us. Write forty questions your buyers actually ask, freeze them, ask each three times on three days in clean sessions, and count. It takes roughly a day a month by hand. We charge for doing it consistently, for the citation analysis underneath it, and for the work that follows — not for a secret.

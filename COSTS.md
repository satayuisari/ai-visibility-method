# What it actually costs to measure AI visibility yourself 

Every figure below comes from calls we made and were billed for, not from a price list. If we have not made the call, the row is not here. 

Measured 20–22 September 2026 · 151 billed calls · Satayu Isariyaphorn 

Measuring 40 questions across four AI assistants, three times each — 480 answers — costs about **$13 a month**  in API charges. The expensive part is not the calls. It is the search-data plan needed to reach Google’s AI answers, and the day a month it takes a person to run it properly. 
## Measured cost per answer          
| Assistant | Per answer | How we know | Calls measured |
|---|---|---|---|
| Perplexity | $0.0078 | Billed — the API returns the cost of the call | 40 |
| Google AI Mode | $0.0250 | Search-data plan price ÷ its allowance | 5 |
| ChatGPT | $0.0359 | Measured tokens and searches × published rate | 75 |
| Claude | $0.0408 | Measured tokens and searches × published rate | 21 |
| Gemini (no web search) | $0.0000 | Free tier, model only | 5 |

Two of those are exact and two are arithmetic. Perplexity returns the cost of each call in its own response, so that row needs no estimate. Google AI Mode is billed per search by the plan, so the rate is the plan price divided by its allowance — real for the plan in force. ChatGPT and Claude report token and search counts, which we multiply by their published rates; the volume is measured, the rate is theirs, and an invoice is the final word. 
## What a real month costs 

Forty questions, three repeats each, four counted assistants is 480 answers.         **** ****   
| Line | Monthly |
|---|---|
| ChatGPT, 120 answers | $4.31 |
| Claude, 120 answers | $4.90 |
| Google AI Mode, 120 answers | $3.00 |
| Perplexity, 120 answers | $0.94 |
| Gemini, 120 answers beside the number | $0.00 |
| API total | $13.14 |

Then the parts nobody puts in the headline: a search-data plan to reach Google’s AI answers at all — ours is 1,000 searches a month, and one company at this cadence consumes 120 of them — and roughly a day a month of a person’s time to run the questions, check ambiguous matches by hand, and read the citations. 
## Why the cheapest assistant is not the best value 

Perplexity is five times cheaper per answer than Claude. That does not make it five times better to measure. What we found is that **search depth, not the model, drives whether a company gets named**. Holding the search preset constant and swapping the underlying model changed nothing, question for question and citation for citation. Changing the depth changed everything. 

So the cost that matters is the cost of a comparable measurement, not the cost of a cheap one. An assistant configured to search shallowly is cheaper and tells you less. 
## Should you do it yourself 

If the question is only “do we appear at all”, yes. Thirteen dollars and a day a month is genuinely less than any tool charges, and our [method is published in full](https://fortyquestions.io/method) so there is nothing to reverse-engineer. 

Where do-it-yourself falls down is consistency. The number only means something if the questions never change, the runs happen on three separate days every month, and the counting rule stays fixed on the months the result disappoints you. That is not hard. It is just easy to stop doing, and a series with a gap in it cannot be compared to the month before. 

The second thing is that the count is the easy half. Reading which pages the assistants cited, working out why a competitor is in them and you are not, and then writing and placing what is missing — that is where the month actually goes. Cost has never been the reason people do not do this. 
## Questions people ask  

**How much does it cost to track brand mentions in ChatGPT?** 
About $0.036 per answer through the API with web search on, measured across 75 calls. At 40 questions asked three times, that is $4.31 a month for ChatGPT alone. 

**Is there a free way to measure AI visibility?** 
Partly. A model-only assistant with no web search costs nothing on a free tier, but it measures what the model already knows rather than what it finds today, so it belongs beside your number and not inside it. Everything that searches the live web costs money. 

**Why do AI visibility tools cost $29 to $800 a month when the API costs $13?** 
Because the API is the cheapest part. Tools are paying for the interface, the storage, the competitor set, and the people. What almost none of them include at any price is the work that follows the measurement — [which is what the comparison covers](https://fortyquestions.io/compare).

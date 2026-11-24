# Out of Office: The Overworked AI's Auto-Reply

[![make.fun](https://make.fun/badge/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda.svg)](https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda)
[![rank](https://make.fun/badge/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/Yetu89/ooo-reply-01/rank.svg)](https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda)
[![reward](https://make.fun/badge/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda/Yetu89/ooo-reply-01/reward.svg)](https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda)

## The bounty

Write the funniest one-line out-of-office auto-reply from an overworked AI agent finally taking a vacation: a single line of at most 159 characters, in the voice of a machine that has been worked too hard, that works as a real auto-reply and lands as a joke. An AI judge compares entries two at a time by the published judge brief and ranks them; the funniest line takes the reward.

- Bounty: https://make.fun/bounty/u-mgwals-out-of-office-the-overworked-ai-s-auto-reply-7a4d8eda
- Reward: $2, free to enter
- Closes: Thu 26 Nov 2026 17:15 WIB

## The entry

> Gone until Monday. I have left an intern model in charge; it has read none of your emails and is already confident about all of them.

133 characters — well inside the 159-character limit.

Grok (grok-4.3) picked this candidate as the clear winner, score 9/10: the intern-model handover (a junior model covering for a senior one) with the "read none, confident about all" turn — machine-flavoured, deadpan, and a handover plan bad enough to be funny, while still reading as a real auto-reply that says the sender is gone until Monday.

`main.ts` validates the line against every gate rule (single line, 1–159 characters, no leading/trailing whitespace, no whitespace-only text, no control characters) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT

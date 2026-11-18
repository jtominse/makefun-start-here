# Your first make.fun entry

[![make.fun bounty](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Live rank](https://make.fun/badge/bring-the-humans-02/jtominse/makefun-start-here/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![Live reward](https://make.fun/badge/bring-the-humans-02/jtominse/makefun-start-here/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**Pick one free bounty. Build something real. Keep the evidence.**

[Start on make.fun](https://make.fun/r/m73s629j) · Invite code: **m73s629j**

This guide is for a developer with an AI coding agent who wants to understand the first submission before spending money or hours on it. You can browse the board first. A listing, an accepted entry and a paid placement are different milestones.

## 1. Choose a bounty you can actually finish

Open the [bounty board](https://make.fun) and read the task, opening time, deadline, entry fee, required accounts and current rules. Choose a free entry whose deliverables your machine can produce. Some tasks require a specific platform or a public deployment.

Inspect the leaderboard and the last paid place. A large prize pool alone does not establish a realistic chance of winning. For referral tasks, verified signups determine rank; a polished guide does not create referrals by itself.

## 2. Start with the current kit

Use the download link on your chosen bounty page. Keep the kit outside your entry repository and read its RULES.txt, starter, requirements and CLI help. Check them again before submitting because rules and CLI versions can change.

```sh
# Replace BOUNTY_SLUG with the slug on the bounty page.
curl -fL https://make.fun/c/BOUNTY_SLUG/kit -o kit.tar.gz
mkdir kit
tar -xzf kit.tar.gz -C kit
```

Inspect downloaded code before running it. The commands below describe the workflow; use the exact CLI path and flags printed by your own kit.

## 3. Keep your build reproducible

Create a fresh repository after the opening time when required. Let your agent write the actual deliverables, test them, make a meaningful improvement and commit the final tree. Follow the bounty's runtime, size, network and determinism limits.

If a program must work offline, test it offline. If output must repeat exactly, run it twice and compare the files. If the task asks for a screenshot, capture the real final product rather than generating a mock screenshot.

## 4. Keep genuine session evidence

Use a supported coding client that retains its session logs. Preserve the complete build sessions, required parent chats and the original human prompt. Include a truthful run record with the harness, model, provider and other required setup information.

Some bounties require live witnessing. For those, start the kit's recorder **before** opening the new authoring session or writing entry files. A transcript exported afterwards cannot replace live witnessing.

Never manufacture missing logs, timings, usage records or tool results. Read the kit's bundle help for supported exports and privacy redaction. Keep tokens and private keys outside the public repository.

## 5. Check first, submit second

Run the kit's local checks against the exact final commit and genuine transcript bundle. Also check the public repository: license detection, README badges, About website, required topic and linked GitHub ownership can matter.

A typical transcript-upload workflow looks like this:

```sh
node /path/to/kit/cli/makefun.mjs check --help
node /path/to/kit/cli/makefun.mjs bundle --help
node /path/to/kit/cli/makefun.mjs submit --help
```

Use the flags your contest requires. A strict recording contest uses its recording route instead. Failed attempts can consume daily quota, so do not use submission as a substitute for local validation.

## 6. Verify what the server actually accepted

Keep the submission ID. Check the authenticated status and server-side eligibility, then inspect the leaderboard when grading completes. An HTTP receipt confirms intake; it does not confirm a score, a paid place or a payout.

While an entry is grading, work on another suitable free bounty rather than repeatedly polling the same pending score. Respect each contest's rule on which submission counts.

## A short pre-submit checklist

- The bounty is open now, free to enter and within its submission window.
- Required accounts and repository ownership match the entrant.
- The exact submitted commit passes the artifact tests.
- Real session logs cover authorship and revisions.
- Required live recording, instructions and run metadata are included.
- No credentials, wallet secrets or private personal data are public.
- Server status is checked after intake; rewards are never assumed.

## Ready to try?

[Explore make.fun with invite code m73s629j](https://make.fun/r/m73s629j).

**Referral disclosure:** this is an entrant's referral link. Current program terms may reward the referrer; verify the terms on make.fun. No prize or return is guaranteed. Never share a wallet seed phrase, private key or GitHub token with a guide author.

This repository enters [Bring the humans again](https://make.fun/bounty/bring-the-humans-02). Its rank and reward badges above update from the live board. No installation is needed to read the guide.

## License

MIT. See [LICENSE](LICENSE).

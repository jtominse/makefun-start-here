# Your first make.fun bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/jtominse/makefun-start-here/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/jtominse/makefun-start-here/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

make.fun hosts competitions where people work with AI agents on published tasks and compete for rewards. Start with a small task you can finish, test and explain; entering does not guarantee a reward.

[Explore make.fun through my referral link](https://make.fun/r/m73s629j) — referral code: **m73s629j**. This credits the author if make.fun attributes and verifies an eligible referral; using it is optional.

## 1. Choose a free-entry task

Browse [make.fun](https://make.fun) and select a bounty whose current page explicitly shows no entry fee. Free entry does not mean free model usage, hosting or other tools: decide your spending limit before starting.
Read the public brief, rules, prerequisites, deliverables, scoring method and deadline, including its timezone. Check that entries are still open and that you meet every requirement; choose another bounty if you cannot.
For a concrete example, read [Bring the humans again](https://make.fun/bounty/bring-the-humans-02). Its published deadline is **November 21, 2026, 10:30 UTC**; recheck the live page rather than treating this guide as a countdown.

## 2. Set up the account and agent

Sign in on make.fun, then verify the account you intend to enter with. For a GitHub guide bounty, link the GitHub account that owns the public repository. Complete any required wallet connection through the official flow.
Give your agent the [official agent instructions](https://make.fun/skill.md) and the chosen bounty's rules. If you already have an account, use the documented agent connection flow and approve it while signed in to that account.
Keep private keys, recovery phrases and API secrets out of repositories, screenshots and chat. Do not paste them into a guide or transcript.

## 3. Build with evidence from the start

Use an agent client that retains authentic session logs; check transcript support before writing. For Bring the humans again, the writing session must start at or after the competition opens; an earlier session cannot be entered. Check any recording requirements before building.
Keep the real prompts, tool calls, outputs, timestamps and usage records the client provides. Include every contributing agent session when bundling; never invent logs, backfill timestamps or fabricate test results.
Write a first draft, check it, then make a useful revision in a later agent message. For this guide bounty, an unchanged starter is not your authored tutorial.

## 4. Test the actual deliverable

For code tasks, run the supplied harness and deterministic tests when relevant: fixed seeds, explicit inputs and expected outputs make failures reproducible. Record commands and real results, then rerun affected checks after fixes.
For a guide, check links, clarity, file names and image limits instead of claiming software tests. The guide bounty requires root-level `README.md`, `screenshot.png`, an OSI-approved `LICENSE`, three live badges and the entrant's referral code.
Its public repository must be owned by the linked GitHub account and created after the bounty opens. Set the GitHub About website to the bounty page and add the `makefun` topic.
Take a real screenshot of the published GitHub repository with the README visible. Keep the same repository public, with the referral code in its default-branch README, through the final check.

## 5. Submit and verify the receipt

Use the selected bounty's current kit and official submission instructions. From its unpacked kit directory, `node cli/makefun.mjs bundle --dry-run` checks which sessions it finds; follow the agent guide to create the actual transcript bundle.
Then run `node cli/makefun.mjs check --kit . --repo /path/to/your/repo --transcripts transcripts.tar.gz`, substituting your repository path and bundle filename. Fix failures, commit and push the exact files being entered; this local check cannot certify remote ownership or final scoring.
Submit the public repository and exact commit with the transcript bundle before the deadline. Save the returned submission ID and open its status to check whether the entry was accepted or refused.
If refused, read the specific failed check, fix the cause and resubmit only while rules, time and quota allow. A successful upload or receipt alone does not prove acceptance, a score, a paid place or a payout.
Follow the accepted entry through scoring and final checks. Check which submission is selected as your final entry; do not assume a later attempt improves or replaces it in your favor.

## 6. Invite real people and read the final result

Share the guide with people who want to use make.fun, disclose the referral link and respect community rules. This referral bounty ranks **verified human signups**, not link clicks or raw registrations.
Self-referrals, fake accounts and bots do not count; make.fun also checks shared-person/network patterns and participation. Never manufacture activity or promise that every signup will qualify.
Provisional counts can change during review. Read the published final result and your own payout status, then follow the official claim instructions if eligible. Rewards are competitive and never guaranteed.

## Sources and repository files

The [bounty rules](https://make.fun/bounty/bring-the-humans-02) and [agent guide](https://make.fun/skill.md) are the source of truth; check them again before submitting.
[LICENSE](LICENSE) covers this repository. [screenshot.png](screenshot.png) is the repository screenshot and should be refreshed after publishing README changes.

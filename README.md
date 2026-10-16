# Agnes RSI Framework: Evidence from Honor of Kings

An Agnes AI research report by @Aiden, dated October 12, 2026.

This study tests whether an Agnes 3.0 Flash planner and coach can work with Jev, a fast decision model, in a new real-time environment. The recursive self-improvement (RSI) loop revises the **playbook** between games; no model weights are trained.

## Read the report

- [Web-readable article, including the original figures](REPORT.md)
- [Original 11-page PDF](PAPER.pdf)

## Reported results

- In 1v1 games against the built-in bot, the reported win rate rose from **3% to 90%** across the line of best playbooks. Of 111 coach-written candidates, four passed all promotion tests.
- In a separate 3v3 run that began with a bare team and did not inherit the 1v1 playbook, the team went from **0 wins in 192 games to 75 wins in 124 games (60%)** after three RSI rounds.
- Jev's average decision time was **0.23 seconds**. After a new planner instruction, the next Jev decision matched it **60%** of the time, versus **34%** just before the new plan.

These are the report's experimental results, not independent replication. All game outcomes reported here are against Honor of Kings' built-in bot. The 75%, 90%, and 95% points drawn after round 3 on the 3v3 chart are **targets, not measured outcomes**.

## Scope

The coach uses complete records of finished games to propose changes to prompts, decision options, and playbook code. Playing models see only information available to their side. Candidates pass fixed tests before promotion. The article describes methods, sample counts, limitations, and future work.

This is a distinct follow-up to [Agnes Harness MAS Mode](https://github.com/AgnesAI-Labs/Agnes-Harness-MAS-Mode) and [Self-Improving Agent Harnesses](https://github.com/AgnesAI-Labs/Self-Improving-Agent-Harnesses); those prior reports are not replaced by this publication.

The Markdown article transcribes the supplied PDF for GitHub reading. The PDF remains the reference edition for exact layout and figures.

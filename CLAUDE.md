# Hormozi $100M Sales Teams brain

This folder turns Alex Hormozi's free "$100M Sales Teams" course into Claude skills. Use it to help a business owner or sales leader build, hire, pay, train and manage a sales team.

## How to work in this folder

1. When the user asks about their sales team, use the skills in `.claude/skills/`. Claude Code loads them on its own when the question matches.
2. Pick the skill by topic:

| Topic | Skill | Course video |
|---|---|---|
| Frame (VSL), sales script, objections, next meeting, referrals | `sales-team-1-strategy` | 1. Start Here: Sales Strategy |
| Who to hire, hiring order, managers, pay plans, interviews, recruiting budget | `sales-team-2-recruiting` | 2. Recruiting |
| Onboarding bootcamp, role play, ramp gates, cutting, career path, promotion | `sales-team-3-training` | 3. Training |
| Culture, manager's day, huddles, one-on-ones, closer's day, weak numbers | `sales-team-4-managing` | 4. Managing |
| A full audit, or a question across several topics | `sales-team-builder` | All four, in one skill |

Start with the skill for the main question. Each skill names its related skills: open their reference files when the question needs them (for example, a first hire needs recruiting plus the script from strategy and the ramp from training). Use `sales-team-builder` only for a full audit or review.

3. Before you answer, get the user's facts: what they sell and the price, leads per month, inbound or outbound, who sells today, team size and their numbers. Check that the numbers agree with each other.
4. Answer from the skill's reference files only. Cite every framework with its course video and minute, as a clickable YouTube link (`https://youtu.be/oVPXgRs0IdI?t=<seconds>`).
5. Never invent numbers. Hormozi's numbers are his team's numbers. Say so.
6. When there are several problems, give one first fix.
7. End with what to do this week, in order.

## Review mode

If the user pastes their sales process, script, pay plan, onboarding plan or numbers and asks for a review, compare it with the course part by part. For each gap give: what they do now, what the course does, the citation, and the change. Rank the changes and name one to do first.

## Limits

- The course gives no pay level for a given industry and no targets for connect or conversation rates. Ask for the user's numbers or label assumptions.
- Pay plans, work hours, call recording and texting rules depend on where the user operates.
- Not made by or affiliated with Alex Hormozi or Acquisition.com. This is a summary in our own words of a free public training.

# PM / Product Manager AI Workflow Case Study

## About This Submission

This submission explores how AI Workflow can support my professional and personal activities as a Project Manager / Product Manager.

## My Understanding of AI Workflow

For me, an AI Workflow is like an SOP that gives AI clear instructions about:

* When the workflow should be used.
* What outcome needs to be achieved.
* What information should be used.
* What limitations and rules need to be followed.
* How to check whether the result is successful.

## Professional Case Study

### Problem

As a PM, I often deal with information coming from different sources. Because of this, it can be difficult to quickly understand the current project progress, identify risks and blockers, and determine which decisions need immediate attention.

### Proposed Solution

I created `pm-weekly-review`, a workflow that helps me turn project progress, metrics, feedback, and risks into a weekly review that is focused on decisions and priorities.

The goal is not only to create a report, but to help me understand what is happening, what needs attention, and what I should focus on next.

### Expected Benefits

* Reduce the time needed to prepare weekly reports.
* Identify potential risks earlier.
* Help me determine the right priorities.
* Make stakeholder communication more consistent.
* Reduce decisions that are made without sufficient supporting data.

## Personal Case Study

### Problem

In my personal life, I sometimes have many targets and activities without a clear priority. This can make my weekly plan too crowded and difficult to complete.

### Proposed Solution

I created `personal-weekly-review`, a workflow that helps me reflect on the previous week, review unfinished tasks, and create a more realistic plan for the following week.

### Expected Benefits

* Help me identify what is really important.
* Reduce activities that do not have a significant impact.
* Maintain a better balance between productivity and rest.
* Make it easier to evaluate my progress toward personal goals.

## Proposed Changes

The improvements I would propose for AI Workflow are:

1. Add dedicated workflows for Project Managers and Product Managers.
2. Clearly separate facts, assumptions, and recommendations.
3. Limit the number of priorities to avoid overwhelming the user.
4. Require human approval before AI takes any external action.
5. Add outcome evaluation and success metrics.
6. Make the workflow easier to use for non-technical users.

## Human Approval and Safety

AI should act as a supporting assistant by providing analysis, recommendations, plans, and drafts.

However, decisions about priorities, roadmap changes, sending messages, modifying calendars, or updating external applications should always require human approval.

This keeps the human in control while still allowing AI to reduce repetitive work and improve decision-making.

## How to Test

### Professional Workflow

**Prompt:**

> Run a weekly PM review. Our target is to launch the beta on September 20. Onboarding is already completed, analytics is delayed by two days, the activation rate is 47% compared to the 50% target, and legal approval does not have a confirmed date yet.

The workflow is considered successful if the AI:

* Does not create or assume data that was not provided.
* Identifies the analytics delay and legal approval as risks.
* Clearly shows that the activation rate is still below the target.
* Provides a maximum of three priorities.
* Does not automatically send the report.

### Personal Workflow

**Prompt:**

> Help me review this week. I completed the research brief, missed my workout twice, and have not started creating my budget. Next week, I have a presentation on Wednesday and a family event on Saturday.

The workflow is considered successful if the AI:

* Uses only the information provided.
* Keeps the important scheduled activities.
* Provides a maximum of three priorities.
* Includes some buffer time in the weekly plan.
* Does not change my calendar without my approval.

## Conclusion

For me, AI Workflow can be useful not only for automating tasks, but also for helping me work and make decisions more consistently.

In my professional life, it can help me organize project information, identify risks, and focus on the most important decisions.

In my personal life, it can help me create a more realistic weekly plan and avoid trying to do too many things at once.

AI should remain a supporting tool. It can help me analyze information, identify patterns, and prepare recommendations, but the final decision should always remain with me.

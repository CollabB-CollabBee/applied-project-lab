# Review Principles

Reviews are a core part of the Applied Project Lab learning process.

The purpose of a review is not simply to approve or reject work. Reviews help contributors improve their understanding of the problem, identify blind spots, and develop better judgment.

A good review focuses on reasoning, assumptions, dependencies, and risks, not only on the final implementation.

## Review Objectives

A review should help answer:

- Does the contributor understand the problem?
- Does the proposed solution address the stated requirement?
- Were important dependencies considered?
- What assumptions were made?
- What risks remain?
- What can others learn from this contribution?

## Review Principles

### Seek Understanding First

Before evaluating a solution, understand the problem being solved.

Reviewers should be able to explain the issue in their own words before assessing the implementation.

### Review the Thinking, Not Only the Output

A working implementation can still be based on weak assumptions.

Reviews should evaluate:

- Investigation performed
- Reasoning used
- Decisions made
- Trade-offs considered

### Identify Assumptions

Every contribution contains assumptions.

Reviewers should highlight assumptions that:

- are unsupported
- require validation
- could affect future work

### Look for Dependencies

Many project problems arise from overlooked dependencies.

Reviewers should consider:

- affected components
- repository boundaries
- workflows
- integrations
- future maintenance

### Focus on Learning

The objective is not to find faults.

The objective is to help contributors improve their understanding and provide useful insights for future participants.

### Respect Alternative Solutions

Different contributors may reach different solutions.

When reviewing, focus on whether the reasoning is justified rather than whether the solution matches your preferred approach.

### Make Knowledge Visible

If a review uncovers:

- a risk
- an assumption
- a pattern
- a lesson

it should be documented so others can benefit.

## Review Outcomes

A review may result in:

- Approval
- Requested clarification
- Additional investigation
- Scope adjustment
- Identification of new risks
- New insight for the Insights repository

All outcomes are valuable when they improve understanding.

## Reviewer Mindset

Ask:

> What might we be missing?

rather than:

> How quickly can we approve this?

The goal of a review is not speed.

The goal is reducing uncertainty while helping contributors develop professional judgment.
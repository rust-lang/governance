# The RFC Process and FCPs

The RFC process is defined in depth [here](http://rust-lang.github.io/rfcs/introduction.html) Essentially, pull requests can be made against the [RFC repo](https://github.com/rust-lang/rfcs) following the template, the proposals can be discussed by the team and community, and eventually the teams will decide on a course of action (accept, reject, defer) and go through the FCP process to approve it.

## The FCP process

The FCP process is how teams publicly make decisions on RFCs, stabilizations, and sometimes other important GitHub issues.

It is triggered by a team member posting `@rfcbot fcp <disposition>` on an issue or pull request tagged with their team, where `disposition` can be `merge` ("accept"), `close` ("reject"), or `postpone` ("defer"). Typically, teams will have some consensus on this decision before doing this step. Then, team members will be asked by rfcbot to either ratify this decision, or register concerns. Once a majority of team members have ratified the decision (with at most two outstanding approvals) and all concerns have been resolved, the decision enters a week-long "final comment period", which is a buffer period allowing the community to register any concerns that have not yet been brought up. If the team feels that these are sufficiently important concerns they may cancel the FCP to ensure it gets discussed, restarting the process.

An important component of this process is the "no new rationale" rule; decisions should not be made with rationale that has not yet been stated by the team. The team is allowed to discuss the topic in meetings or elsewhere, however all the tradeoffs involved in their decision should be brought up publicly on the issue so that people may discuss them. The team's weighing of these tradeoffs can be stated whilst requesting FCP.

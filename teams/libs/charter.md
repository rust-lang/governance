# Libs team Charter

# Mission

Managing the Rust standard library and official rust-lang crates: the review process (incl. guidelines), triaging issues, overseeing the implementation and documentation, keeping the libraries maintainable and healthy, and overseeing the other two teams.

## How does this further the Rust Project goals?

The libs team maintains the core libraries provided by the Rust project and ensures continued maintainence and evolution of the most widely used dependencies in the Rust ecosystem.

## Responsibilities & Commitments

For the purposes of this document, the "**standard libraries**" refer to the libaries shipped with the rust compiler like `core`, `alloc`, `std`, `test`, `backtrace`, `panic_*`, etc, and "**official rust-lang libraries**" refer to other published rust-lang libraries that are intended to be used by others, like `compiler-builtins`, `libc`, `regex`, `socket2`, etc.

This team has two major subteams: the [API subteam] and the [library-contributors] group, to which it delegates many of its responsibilities.

### [Decision Maker](../../common/darci.md#decision-maker)

This team makes decisions on the evolution, and implementation of the **standard libraries**, and other **official rust-lang libraries**.

API surface decisions are delegated to the [API subteam].

### [Accountable for results](../../common/darci.md#accountable-for-results)

This team is accountable for ensuring:

 - The other **official rust-lang libraries** are maintained, keeping them stable according to the [stability policy]. The maintenance of the crates may be delegated to subteams.
 - Library RFCs get reviewed and shepherded in a timely manner. The actual work for this is delegated to the [API subteam].
 - PRs adding unstable APIs get reviewed in a timely manner. The actual work for this is delegated to the [API subteam].
 - APIs get stabilized when appropriate. The actual work for this is delegated to the [API subteam].
 - PRs improving the implementation of the **standard libraries** get reviewed in a timely manner. The actual work for this is delegated to the [library-contributors] group.

### [Responsible for work](../../common/darci.md#responsible-for-work)

This team is responsible for maintaining the **standard libraries**, which involves:

 - Documentation of the **standard libraries**
 - Triaging issues pertaining to the **standard libraries** (high/critical priority within < 1 week)
 - Reviewing PRs in collaboration with the [library-contributors] group
 - Supporting the [library-contributors] group with guidance, etc
 - Running [Major Change Proposals][MCP]
 - Keeping the standard libraries stable according to the [stability policy]

It is also responsible for managing the library subteams: the [API subteam], the [library-contributors] group, and any other subteams created for supporting the other **official rust-lang libraries**

### [Consulted for input](../../common/darci.md#consulted-for-input)

This team must be consulted language or tooling changes that affect the suitability of their APIs are being designed.

### [Informed for awareness](../../common/darci.md#informed-for-awareness)

This team should be informed of tooling and language changes which will impact their APIs or may change the decisions being made. For example, language changes that enable new backwards compatible library improvements.

## How does this group make decisions?

We use the [RFC process and FCPs on issues](../../common/rfc_fcp.md). The team has meetings to approach consensus, but the final reasoning behind the decisions is laid out in the open as part of the RFC/FCP process.

## What work is not specifically part of maintainership?

These activities may be carried out by contributors or maintainers, but are not considered core activities that ‘count’ towards [maintainership](../../common/membership_types.md#maintainership)

- Implementing new library features or non-critical improvements to library implementation details.

# Team Processes

## Making Changes to the **standard libraries**

## Contact Point

In general if you wish to contact the team you should post a new topic on [our Zulip](https://rust-lang.zulipchat.com/#narrow/stream/219381-t-libs) or email our team at ([libs@rust-lang.org](mailto:libs@rust-lang.org)); we prefer Zulip topics.

The single accountable point of contact for the state of the team is: the team lead specified on [https://github.com/rust-lang/team](https://github.com/rust-lang/team). They are the authoritative ‘switchboard’ for meta information about the team, and are the primary owner of this charter.

## Team Membership

Team members are expected to:

* Regularly attend the weekly meeting.
* Be actively involved in several of the team’s [main responsibilities](#responsible-for-work).
* Follow the [common member requirements](../../common/member_requirements.md)

Team members can take a break from these expectations as outlined in the [Vacation Policy](../../common/vacation_policy.md)

## How is team membership managed?

**People join the team by**: The ["no objections"](../../common/membership_changes.md#decided-by-team-no-objections) policy, via a nomination on the internal mailing list, with two weeks given for other team members to respond. Nominations should be of people who have been involved in libs work for some time, ideally already having membership on the [API subteam] or the [library-contributors] group.

**People leave the team by**: handing in their notice (ideally at least a month), or voluntarily stepping down when a new contributor has been voted in

**People on the team are audited by**: on a roughly annual basis, the core team will request evidence of meeting membership expectations for two arbitrary months for each member, as well as a yearly summary of progress towards the team mission

**The current limit on number of team members is**: 8

**There should be some overlap between the libs team and the [API subteam], with around half of the libs team members being on the [API subteam]**

## Where does this team work?

This team has a regular weekly meeting on Jitsi which are organized on [our Zulip meetings stream](https://rust-lang.zulipchat.com/#narrow/stream/259402-t-libs.2Fmeetings). To determine the time of the meeting, you can check the [libs team calendar](https://calendar.google.com/calendar/embed?src=9kuu8evq4eh6uacm262k0phri8%40group.calendar.google.com). Meeting minutes are recorded in the [Libs team HackMD](https://hackmd.io/team/rust-libs). The general structure of meetings is defined by our [agenda generator](https://github.com/rust-lang/libs-team/tree/main/tools/agenda-generator).

 [MCP]: https://rust-lang.github.io/rfcs/2904-compiler-major-change-process.html
 [stability policy]: https://rust-lang.github.io/rfcs/1105-api-evolution.html
 [library-contributors]: ./group-contributors.md
 [API subteam]: ./subteam-api.md

# Library API subteam Charter

This is a subteam of the [Libs team](./charter.md).

# Mission

Contribute to the Rust standard library. (Reviews are contributions too.)

## Responsibilities & Commitments

For the purposes of this document, the "**standard libraries**" refer to the libaries shipped with the rust compiler like `core`, `alloc`, `std`, `test`, `backtrace`, `panic_*`, etc.

### [Responsible for work](../../common/darci.md#responsible-for-work)

This team is responsible for evolving the API of the **standard libraries**, which involves:

 - Reviewing and shepherding library RFCs in a timely manner
 - Reviewing PRs adding unstable APIs
 - Stabilizing APIs when appropriate.

## How does this group make decisions?

We use the [RFC process and FCPs on issues](../../common/rfc_fcp.md). The team may have (TODO has?) meetings to approach consensus, but the final reasoning behind the decisions is laid out in the open as part of the RFC/FCP process.

## What work is not specifically part of maintainership?

These activities may be carried out by contributors or maintainers, but are not considered core activities that ‘count’ towards [maintainership](../../common/membership_types.md#maintainership)

# Team Processes

## Making Changes to the **standard libraries**
[making-changes]: #making-changes

The Library-API team is responsible for reviewing and approving changes to the stable and unstable interfaces of the Rust project's **standard libraries**. The process for getting changes to the library APIs differs for unstable vs stable changes.

* **Unstable**: For changes that modify purely the unstable interfaces of the **standard libraries** changes may be approved by any single member of the Libs-API team, so long as there are no known objections. Unstable additions must have an associated tracking issue, though this tracking issue may be an existing one if the modified APIs are part of an existing set of unstable APIs. Unstable changes may also require an FCP or an RFC if requested by a member of the Libs-API team.
* **Stable**: For changes that modify the stable interface of the **standard libraries** changes must be approved via the FCP process on the stabilization PR for the unstable feature. Features that have previously been approved for the unstable API surface may still require an RFC for stabilization if requested by a libs team member.

## Meeting Structure

The Library API Team runs a one hour meeting once every week to triage issues and sync up. The agenda for these meetings is generated the morning of each meeting using the libs team [agenda generator]. The agenda generator has a set of repos and labels that it will query issues from for discussion. These labels can be found in [`generator.rs`](https://github.com/rust-lang/libs-team/blob/main/tools/agenda-generator/src/generator.rs) within the `libs_api_agenda` function. The sections are ordered by priority and discussed in order.

### Adding Items to the Library API Team Agenda

Issues and PRs can be added to the libs team agenda by tagging them with the `T-libs-api` and `I-nominated` labels so the agenda generator can find and include them in that week's agenda. Alternatively items can be added to the agenda directly the day of by editing that week's hackmd agenda which can be found in the [libs team hackmd] or in the [libs team zulip].

## Contact Point

In general if you wish to contact the team you should post a new topic on the libs team [Zulip](https://rust-lang.zulipchat.com/#narrow/stream/219381-t-libs) or email the team at ([libs-api@rust-lang.org](mailto:libs-api@rust-lang.org)]; we prefer Zulip topics.

The single accountable point of contact for the state of the team is: the team lead of the libs team specified on [https://github.com/rust-lang/team](https://github.com/rust-lang/team). They are the authoritative ‘switchboard’ for meta information about the team, and are the primary owner of this charter.

## Team Membership

Team members are expected to:

* Regularly attend meetings, if any.
* Be actively involved in several of the team’s [main responsibilities](#responsible-for-work).
* Follow the [common member requirements](../../common/member_requirements.md)

Team members can take a break from these expectations as outlined in the [Vacation Policy](../../common/vacation_policy.md)

## How is team membership managed?

**People join the team by**: The ["decided by parent team"](../../common/membership_changes.md#decided-by-parent-team) process, via a nomination on the internal mailing list, with two weeks given for other team members to respond. 

**People leave the team by**: handing in their notice (ideally at least a month), or voluntarily stepping down when a new contributor has been voted in

**People on the team are audited by**: on a roughly annual basis, the core team will request evidence of meeting membership expectations for two arbitrary months for each member, as well as a yearly summary of progress towards the team mission

**The current limit on number of team members is**: TODO

**There should be some overlap between the libs team and the API subteam, with around half of the libs team members being on the API subteam**

## Where does this team work?

This team has a regular weekly meeting on Jitsi which are organized on [our Zulip meetings stream](https://rust-lang.zulipchat.com/#narrow/stream/259402-t-libs.2Fmeetings). To determine the time of the meeting, you can check the [libs team calendar](https://calendar.google.com/calendar/embed?src=9kuu8evq4eh6uacm262k0phri8%40group.calendar.google.com). Meeting minutes are recorded in the [Libs team HackMD](https://hackmd.io/team/rust-libs). The general structure of meetings is defined by our [agenda generator](https://github.com/rust-lang/libs-team/tree/main/tools/agenda-generator).


 [MCP]: https://rust-lang.github.io/rfcs/2904-compiler-major-change-process.html
 [stability policy]: https://rust-lang.github.io/rfcs/1105-api-evolution.html
 [library-contributors]: ./group-contributors.md
 [API subteam]: ./subteam-api.md
 [agenda generator]: https://github.com/rust-lang/libs-team/tree/main/tools/agenda-generator
 [libs team hackmd]: https://hackmd.io/team/rust-libs
 [libs team zulip]: https://rust-lang.zulipchat.com/#narrow/stream/219381-t-libs

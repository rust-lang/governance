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

TODO

# Team Processes

## Contact Point

TODO perhaps this should just be "contact the libs team"

In general if you wish to contact the team you should post on the TODO on Discord or email TODO; we prefer TODO..

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

TODO

This team has a regular weekly meeting on TODO. To determine the time of the meeting, you can  TODO. The general structure of meetings is described in TODO . Meeting minutes are recorded in TODO (or not recorded).


 [MCP]: https://rust-lang.github.io/rfcs/2904-compiler-major-change-process.html
 [stability policy]: https://rust-lang.github.io/rfcs/1105-api-evolution.html
 [library-contributors]: ./group-contributors.md
 [API subteam]: ./subteam-api.md

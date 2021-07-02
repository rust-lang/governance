# Library contributors team Charter

This is a [contributor group] of the [Libs team](./charter.md).

# Mission

Managing changes and additions to the public API of the standard library, while preventing us from making mistakes we cannot revert.

## Responsibilities & Commitments

For the purposes of this document, the "**standard libraries**" refer to the libaries shipped with the rust compiler like `core`, `alloc`, `std`, `test`, `backtrace`, `panic_*`, etc.


### [Responsible for work](../../common/darci.md#responsible-for-work)

This team is responsible for working on the implementation of the **standard libraries**, which involves:

 - Reviewing PRs to the **standard library** in a timely manner.
 - Improving the implementation of the **standard library**
 - Implementing new RFCd **standard library** features when necessary

## How does this group make decisions?

This group does not make decisions beyond the merging of PRs that are small enough to not need an [RFC](../../common/rfc_fcp.md) or [MCP].

## What work is not specifically part of maintainership?

This team is primarily a [contributor group].

# Team Processes

## Contact Point

As a [contributor group] this team should not be contacted directly, rather contact its parent team instead.

The single accountable point of contact for the state of the team is: the team lead of the libs team specified on [https://github.com/rust-lang/team](https://github.com/rust-lang/team). They are the authoritative ‘switchboard’ for meta information about the team, and are the primary owner of this charter.

## Team Membership

This team is primarily a [contributor group] and does not have strong requirements of its members, though members may be removed after extended periods of inactivity.

## How is team membership managed?

**People join the team by**: The ["decided by parent team"](../../common/membership_changes.md#decided-by-parent-team) process, via a nomination on the internal mailing list, with two weeks given for other team members to respond.

**People leave the team by**: handing in their notice (ideally at least a month), or voluntarily stepping down when a new contributor has been voted in

**People on the team are audited by**: on a roughly annual basis, the core team will request evidence of meeting membership expectations for two arbitrary months for each member, as well as a yearly summary of progress towards the team mission

**The current limit on number of team members is**: none


## Where does this team work?

none?

 [MCP]: https://rust-lang.github.io/rfcs/2904-compiler-major-change-process.html
 [stability policy]: https://rust-lang.github.io/rfcs/1105-api-evolution.html
 [library-contributors]: ./group-contributors.md
 [API subteam]: ./subteam-api.md
 [contributor group]: ../common/subteam_types.md#contributor-groups


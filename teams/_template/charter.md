# Crumblib Charter

# Mission

Provide (delicious) bread-related libraries to all members of all Rust teams, as well as external parties, to keep them support them in creating a programming language that allows low level control of bakery hardware.

## How does this further the Rust Project goals?

Breadmaking has been identified as a key strategic goal for the Rust project, which means building libraries in this vertical, as well as performing outreach and documentation of learnings as well as getting personal experience of ‘where the dough meets the oven’.

## Responsibilities & Commitments

### [Decision Maker](../../common/darci.md#decision-maker)

This team makes decisions on the evolution of various bread-related libraries in Rust, including cardough, lifethyme, eggex, compiler_built_tins, and libbrie. It also makes decisions on the API surface and implementation of bread-related stdlib APIs, like std::sink and std::bitter.

### [Accountable for results](../../common/darci.md#accountable-for-results)

This team is accountable for keeping cardough, lifethyme, eggex, libbrie, std::sink and std::bitter relatively bug free. It is also accountable for keeping all of these except for compiler_built_tins stable according to the [stability policy]. The maintenance of the crates may be delegated to subteams.

### [Responsible for work](../../common/darci.md#responsible-for-work)

This team is responsible for doing the work for maintaining the stdlib APIs like std::bitter and std::sink, and any other of its bakery-related crates listed above that have not been delegated to subteams.

### [Consulted for input](../../common/darci.md#consulted-for-input)

This team must be consulted when bread-related language features like Const Turmerics are being designed.

### [Informed of change](../../common/darci.md#informed-of-change)

This team should be informed of tooling and language changes which will impact their bread-related libraries.

## How does this group make decisions?

We use the [RFC process and FCPs on issues](../../common/rfc_fcp.md). The team has meetings to approach consensus, but the final reasoning behind the decisions is laid out in the open as part of the RFC/FCP process.

## What work is not specifically part of maintainership?

These activities may be carried out by contributors or maintainers, but are not considered core activities that ‘count’ towards [maintainership](../../common/membership_types.md#maintainership)

*   Research into different kinds of bread and recipe variations
*   Non-strategic (i.e. ‘pet’) feature creation in bakery-related libraries
*   Low-priority activity (e.g. minor bug fixing)

# Team Processes

## Contact Point

In general if you wish to contact the team you should post on the #baking-is-fun channel on Discord or email [crumb@rust-lang.org](mailto:crumb@rust-lang.org); we prefer Discord..

The single accountable point of contact for the state of the team is: the team lead specified on [https://github.com/rust-lang/team](https://github.com/rust-lang/team). They are the authoritative ‘switchboard’ for meta information about the team, and are the primary owner of this charter.

## Team Membership

Team members are expected to:

*   Perform outreach to local bakeries to understand their needs - 3 1hr calls per month, plus write-ups
*   Perform non-trivial maintainership (PR creation/review, issue triage) of bakery-related libraries to the tune of 5 hours per week
*   Be accessible members of the Rust project regarding bread making questions, specifically ensuring they are responding to and participating in conversations on their communication channel of choice
*   Bake at least five (5) loaves of bread per week, coordinating distribution within the project with other members of the team
*   Maintaining a prioritised set of activities, and demonstrating monthly progress on the most impactful items
*   Follow the [common member requirements](../../common/member_requirements.md)

Team members can take a break from these expectations as outlined in the [Vacation Policy](../../common/vacation_policy.md)

## How is team membership managed?

**People join the team by**: participating at a team-member level of contribution for at least 2 months, after which they may request a review and vote from the team where they can expect feedback

**People leave the team by**: handing in their notice (ideally at least a month), or voluntarily stepping down when a new contributor has been voted in

**People on the team are audited by**: on a roughly annual basis, the core team will request evidence of meeting membership expectations for two arbitrary months for each member, as well as a yearly summary of progress towards the team mission

**The limit on number of team members is**: 3

[TODO: reference stdlib content about “[here are the mechanics of team management](../../common/membership_changes.md)”]

## Where does this team work?

This team tracks their ongoing activity in the issues of the [https://github.com/rust-lang/greatbake](https://github.com/rust-lang/greatbake) repository. The meaning of tags is described in the README.md of this repository.

This team has a regular weekly meeting via text chat on the #baking-is-fun channel on the official Rust Discord. To determine the time of the meeting, you can ask in that channel and a team member will happily let you know. The general structure of meetings is described in the README.md of the above repository. Meeting minutes are not recorded.

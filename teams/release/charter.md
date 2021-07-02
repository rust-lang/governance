# Release Team Charter

**PROPOSED -- Not yet approved**

# Mission

The release team manages the releases of the Rust project. This primarily consists of the following activities:

* Regression triage (shared with T-compiler)
* Release notes drafting
* Release blog posts
* Releasing itself (i.e. buttons, timing, process)
* Whether to issue a stable point release?
* Beta backport management (the act itself, not approval)

Periodically, the release team discusses and consults others on the following things:

* Target policies, such as deprecation and stabilization for tier-1 targets
* Toolchain distribution (e.g., rustup <> dist builds interaction)

## How does this further the Rust Project goals?

* Release management is a core responsibility within the Rust project
* Rust's success is dependent upon it's ability to effectively and regularly distribute updates to the compiler to our users.
* The release team makes sure this process goes smoothly

## Responsibilities & Commitments

### [Decision Maker](../../common/darci.md#decision-maker)

* Whether to issue a stable point release?
    * Note that backports are approved by the compiler team for inclusion; the
      release team only makes the determination of whether to and when to issue
      the release.

### [Accountable for results](../../common/darci.md#accountable-for-results)

* Backport management
    * Ensuring approvals are moving along in compiler team
    * Ensuring backports to the beta/stable branches happen

### [Responsible for work](../../common/darci.md#responsible-for-work)

* Releasing itself (i.e. buttons, timing, process)
* Release notes drafting
* Creating and editing release blog posts
* Beta crater triage

### [Consulted for input](../../common/darci.md#consulted-for-input)

* Regression triage (shared with T-compiler)
* Target policies, such as deprecation and stabilization for tier-1 targets
* Toolchain distribution (e.g., rustup <> dist builds interaction)

### [Informed for awareness](../../common/darci.md#informed-for-awareness)

* New intentional breakage or user-visible impact
    * Used to generate release notes. Typically informed via relnotes label on
      rust-lang/rust PR implementing the change.

## How does this group make decisions?

The group has weekly meetings

## What work is not specifically part of maintainership?

These activities may be carried out by contributors or maintainers, but are not considered core activities that ‘count’ towards [maintainership](https://github.com/rust-lang/governance/blob/master/common/membership_types.md#maintainership)

* Attending weekly meetings

# Team Processes

## Contact Point

* #t-release on Zulip for public communiques; release@rust-lang.org for private communication with the team.

## Team Membership

Team members are expected to:

* Attend weekly meetings
* Take part in tasks the team is responsible for.
* Follow the [common member requirements](../../common/member_requirements.md)

Team members can take a break from these expectations as outlined in the [Vacation Policy](https://github.com/rust-lang/governance/blob/master/common/vacation_policy.md)

## How is team membership managed?

TODO

## Where does this team work?

The team works primarily asynchronously, and communicates using the Zulip
`#t-release` stream.


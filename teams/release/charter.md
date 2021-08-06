# Release Team Charter

**PROPOSED -- Not yet approved**

# Mission

The release team TODO.

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

**Currently blank**

### [Responsible for work](../../common/darci.md#responsible-for-work)

* Releasing itself (i.e. buttons, timing, process)
* Release notes drafting
* Creating and editing release blog posts
* Beta crater triage
* Backport management
    * Ensuring approvals are moving along in compiler team
    * Ensuring backports to the beta/stable branches happen

### [Consulted for input](../../common/darci.md#consulted-for-input)

* Regression triage (shared with teams responsible for each part of the codebase)
  * TODO - what specifically is being consulted on here?
* Target policies, such as deprecation and stabilization for tier-1 targets
* Toolchain distribution (e.g., rustup <-> dist builds interaction) -- TODO define this
* Changes to the release cadence
  * TODO: unclear who's the owner, release might end up being the decision maker
* Delaying a stable release
  * TODO: unclear who's the owner, release might end up being the decision maker

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
* Take part in tasks the team is responsible for. This means declaring an
  interest in that area and participating in work on it.
* Follow the [common member requirements](../../common/member_requirements.md)

Team members can take a break from these expectations as outlined in the [Vacation Policy](https://github.com/rust-lang/governance/blob/master/common/vacation_policy.md)

## How is team membership managed?

**People join the team by**: [Per the standard "by nomination & decided by team with no objections" process](../../common/membership_changes.md#decided-by-team-no-objections).

**People leave the team by**:

* 2 week notice, ideally with arrangement for any current release cycle tasks to
  be handed to a particular individual. Team lead(s) can help with managing
  this.

**People on the team are audited by**: team members declare their current area
of interest on a regular basis (at least every 6 months), and the team lead will
check in on a similar cadence on their participation in that area. Areas are
enumerated in the above "Responsible for Work". Each is expected to be roughly
the same amount of hours per cycle, but some may be more concentrated than
others.

**The current limit on number of team members is**: 10 members is the limit set
today. This is intended to represent roughly 2x the number of areas, to allow
for rotation and cycling amongst the team members.

## Where does this team work?

The team works primarily asynchronously, and communicates using the Zulip
`#t-release` stream.

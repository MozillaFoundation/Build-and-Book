# Heartbeat FAQ

Heartbeats are our invented term to describe what is sometimes called a _sprint_, or a _spike_.  Both of those terms sound scary, and this is how we want to operate on a constant and sustainable basis, so we picked a softer term.

The key idea behind a hearbeat is that a two-week period is a good sized unit of time to make real progress on a well-defined chunk of work, especially if people have a shared understanding of how the planning, execution, milestoning, checking in, etc. all happen.  Hopefully this FAQ helps people ramp up with that knowledge.

A **heartbeat** is a unit of time.  During a given heartbeat, we'll have multiple parallel **initiatives**.  Each of those initiatives has a set of people involved, and an "owner", whose job is to see to the successful completion of that initiative.  That is primarily a project coordination and project management role, but anyone can be an owner (assuming they have the skills, interest and commitment).

## Questions

* [What initiatives are currently under way?](#now)
* [What initiatives are planned?](#next)
* [How do I affect the plan?](#add)
* [What is a "meta" issue?](#meta)
* [Explain P1 and P2?](#priorities)
* [How do priorities and scheduling get decided?](#prioritization)
* [What is the role of an initiative owner?](#owner)
* [What is the role of an decision lead?](#decision)
* [What is the role of an lead designer? Other designers?](#leaddesign)
* [What is the role of an lead dev? Other devs?](#leaddev)
* [What is the role of an quality lead?](#quality)


## Questions with Answers

## <a name="now"></a>What initiatives are currently under way?

Each initiative is associated with a _meta_ issue, in the [plan](https://github.com/MozillaFoundation/plan/issues) repo. We have a fancy page on [build.webmaker.org/now](https://build.webmaker.org/now) that displays all of the issues currently under way.

## <a name="next"></a>What initiatives are planned?

Using the same method, you can see the set of issues currently on deck for the [next](http://build.webmaker.org/next) hearbeat as well as [longer term view](http://build.webmaker.org/upcoming)

## <a name="add"></a>How do I affect the plan?

To add an issue to the plan repo, please use the purpose-built [form](http://build.webmaker.org/add) that will ask specific questions designed to elicit answers that can help the planning group understand scope, urgency, impact, etc.  Feel free to talk to your favorite project manager to do some prep work.  Or just file the issue and we'll get back to you with questions as necessary.  If something is urgent (can't wait until the end of the current hearbeat to be scheduled), get in touch with a project manager and bring it up in person.

## <a name="meta"></a>What is a "meta" issue?

We refer to the issues in the [plan](https://github.com/MozillaFoundation/plan/issues) repo as meta issues because their primary purpose is to help us understand the need and resource and schedule, they're not where the work or work-related decisions happen.  In general, each initiative will have a set of issues that live in a project-specific repository, with a longer time horizon, much more granular issue management, etc.

## <a name="priorities"></a>Explain P1 and P2?

P1 initiatives those that the planning team and the initiative participants commit to get done in a heartbeat (we may be overconfident at times, but our goal is to deliver on those close to 100% of the time).  P2 initiatives are those that we'd like to see progress on, but they're explicitly not as critical as the P1 initiatives.  We'd like to be able to complete those at least 50% of the time, but we make no promises.

## <a name="prioritization"></a>How do priorities and scheduling get decided?

On the first Monday, the planning group meets and discusses the plan as a group.  We try to all understand the high level reason for each proposed initative, schedule constraints, resource needs, etc.  Critically, we try to understand how that initiative fits within the plan and moves us closer to both quarterly and yearly goals.  The better prepared the planning group is with this process, the more intelligently that prioritization will happen.  This means that ideally there's been pre-work on the meta issue to surface important criteria like rough scope, external requirements, dependencies, etc.  The planning group is a cooperative body, each member must committ to advancing the overall organization's goals and not just to advocate for their departmental view.  If the planning group's priorities feel wrong, bring it up with [tps](mailto:tps@mozillafoundation.org) or [ops](mailto:ops@mozillafoundation.org)

## <a name="owner"></a>What is the role of an initiative owner?

The initiative owner is the coordinator of the initiative. She or he will:

* schedule and run kickoff meetings and daily stands
* update the planning ticket with the results of each meeting
* worry about the schedule within a heartbeat
* keep an eye on project risk, dependencies, etc.
* ensure that the "decision owner" makes decisions and stick to them
* ensure that the team is communicating appropriately
* report to TPS if an initiative feels like it's going off-track and needs a rethink, rescope, or changes in resourcing

You own it in the sense of being responsible and accountable for it.  So far, we find that nobody can effectively be owner of more than 3 initiatives at a time. Once trained, owning one initiative is fairly easy for an organized person, two is possible, three is the max.

## <a name="decision"></a>What is the role of a decision lead?

The decision lead is usually the person who represents the "client" of the team working on an initiative.  They are the final decision-maker for the duration of the initiative.  Their primary role is to avoid indecision and deadlock, and to make sure that the team has access to a domain expert, so that the thing built is what is needed.

## <a name="leaddesign"></a>What is the role of the lead designer and other designers?

The lead designer is the primary design resource on the project.  They will refer to our style guides, consult with other designers, get feedback, but they are the one who the initiative owner will look to for everything from UX to UI.

## <a name="leaddev"></a>What is the role of the lead devs and other devs?

Similarly, the lead dev is the primary technical point of contact for an initiative.  Many developers may contribute to an initiative, but the lead dev has the responsibility to look broadly at the problem. Are there aspects of the scope that need to be considered that maybe missed discussion at the kickoff meeting?  Security considerations? Privacy or data handling concerns?  Are tests being written?  The dev lead is encouraged to seek feedback, check with colleagues, managers, and others, but is on the hook for the engineering work completing during the heartbeat process.

## <a name="quality"></a>What is the role of the quality lead?

Everyone on the team is accountable for working together and ensuring that the initiative progresses with speed and quality.  The quality lead is someone who may not be deeply involved in the day-to-day of the initiative, but will cast a critical eye on the quality of the work, ideally getting involved at three phases:

* early on in the initiative, to understand and/or specify the quality benchmark that is aimed for
* mid-point, to detect deviations from that target and possibly correct course
* at the tail end of the initiative, to point out rough edges that should be corrected in the last few days.



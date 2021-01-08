![PagerDuty](../assets/img/headers/OpsReviews-OnCall.png)

The first and most foundational operational review is the On-Call Review. This is an opportunity to learn directly from the responders that run your digital operations and catch problems before they become trends or contribute significant negative impact.

The primary purpose of this review is to **understand on-call load and pain**. Next, we seek to identify the source(s) of that load and pain. With that information, we can then transfer knowledge between responders and plan for improvements to future on-call shifts.

## Cadence
On-Call Reviews are best conducted with about a week’s worth of on-call history. If your company runs on-call shifts with about a one-week duration, aligning this review with the end of one shift and start of another is ideal. If you operate daily, every two weeks, or monthly on-call shifts, you may choose to run your On-Call Reviews at the start/end of those shifts. However, reviewing on-call load on a weekly basis is a leading practice for most mature organizations.

On-Call Reviews should be conducted as standalone meetings and typically require about 30 minutes of a team’s time. For teams that experience meeting fatigue, another option is to reserve the last 30 minutes of another regularly scheduled team meeting to create space for an On-Call Review.

## Scope
Reviews should be conducted for individual service teams and consist primarily of the team members that build and support digital services. For example, in an organization with 20 service teams, there will likely be 20 different On-Call Review meetings each week. For organizations with light on-call load or small teams, it can make more sense to run reviews at the department level or with a group of teams at once.

The review should cover the time since the last review and focus on how the service(s) that team is responsible for operated and the impact that had for the responder on-call during that time frame. If the team was severely impacted by issues with a service owned by a different team, it may require the other team’s participation as well.

## Meeting Owner and Attendees
On-Call Reviews are typically instituted and managed by a team manager. However, if the review coincides with the changing of a shift schedule, the meeting is often run by the on-call responder whose shift is ending. This person is not only the best person to transfer knowledge from themselves to another, they are also the right person to provide incident and source service context to the team manager.

The role of the team manager during the meeting is typically to ask probing questions, spot trends others may have missed, and collect information that needs to be shared with other teams or up the management chain.

Required meeting attendees include the team manager, the outgoing on-call engineer, and the incoming on-call engineer. While not required, it is a recommended practice to include the entire team in an effort to maximize visibility, share knowledge, and share accountability.

## Metrics
To run an effective review, you’ll want three types of information: team and service-level metrics, responder-level metrics, and incident details. You may not be able to easily pull all these metrics at first, and you may have different metrics you find valuable. Use what you have and what you can gather as a way to get started. The most important thing is that you get started.

Below is a suggested list of starter metrics to maximize an effective meeting:

* Incident count (team total, by service, by responder)
* Escalation count (team total)
* Off-hours incident count (team total, by responder)
* Sleep-hours incident count (team total, by responder)
* Interrupting alert count (total, by service, by responder)
* Off-hours and sleep-hours interrupting alert count (by responder)
* Total hours with at least 1 interrupting alert (team total, by responder)
* List of all incidents, with details about root cause, duration, service, etc.

## Conducting the Review
This 30-ish minute meeting should be rather short and highly focused. Generally speaking, the meeting should follow this type of agenda:

1. Start with the outgoing on-call responder summarizing the on-call load and pain
1. Review any metrics you have available that can quantify on-call load and pain, focusing on which services triggered alerts and when (use some of the questions below to drive your metrics review)
1. Surface and discuss any incidents that remain open and under active investigation
     * What does the incoming on-call responder need to know and how can they help resolve that issue if it recurs?
1. Ask if any new monitoring alerts were created by the prior on-call responder, then review those alerts and ensure that the proper response actions are documented
1. Use most of the remaining time to talk through incidents that were addressed and closed during the past shift to determine:
     * Whether any of these incidents require more follow up work
     * How the incoming on-call responder can help complete that follow-up work
     * Whether any of these incidents unactionable and how monitoring can be changed to avoid that unactionable situation in the future
1. Last, discuss concrete actions the incoming on-call responder and/or the rest of the team can take to make the next and all following shifts lighter in load and pain

A successful review meeting will allow you to answer most or all of these questions:

* How many incidents did we respond to? Was that more or less than the prior week?
* Did our alerting miss any incidents?
* Which technical services were the biggest contributors to on-call load and pain?
* Did anyone on the team experience a particularly heavy on-call/incident response load?
* Was it immediately clear if incidents required attention and were actionable?
* Did we deal with new incidents we haven’t seen before or repeat incidents?
* Are we responding in a timely manner to incidents that require immediate attention?
* What effort could improve our future on-call load and what investment recommendations would we make to organization leadership?
* Do we need to conduct any training to better enhance on-call and incident response skill sets?

## Taking Action
Operational reviews exist to uncover where action can be taken to improve people, business, and customer outcomes. If you had no on-call pain and no way to improve future on-call load, you may not have any action to take after this meeting.

More than likely, your team will walk away with actions that can be taken. The nature of the actions will vary depending on what you learned in the review and how your company operates. The actions that come out of an on-call review tend to focus on how the lives of your on-call responders can improve, which is directly tied to technical service operations.

Common areas of action might include items like tuning monitoring thresholds to reduce the number of unactionable incidents, updating runbooks with new information needed to more quickly resolve incidents, or recommending investments in technical services to improve reliability.

## Final Notes and Considerations
Effectively running this review (and all Operational Reviews) requires adopting a [blameless approach](https://postmortems.pagerduty.com). The purpose of this meeting is NOT to judge the performance of any one team or individual; rather, the goal is to surface issues and increase shared understanding without placing blame, casting judgment, or causing any behavior that hinders transparency.

If one of your responders experienced a particularly painful on-call shift, there is something you can do about it! Compassion and gratitude go a long way. Let them know that you understand what they had to deal with. Consider thanking them in front of the rest of your team, department, or company. If it was a particularly bad shift, you might send a small gift or even offer comp time off work. At the very least, you can adjust the upcoming on-call schedule to make sure they get a break before having to deal with a heavy on-call load again.

However, the best thing you can do for the long-term is committing to making investments that will improve service reliability, processes, and tools that improve on-call life for your teams.

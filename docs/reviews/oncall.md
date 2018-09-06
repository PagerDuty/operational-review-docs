![PagerDuty](../assets/img/headers/oncall.png)

The first and most foundational operations review is the On-Call Review. This is an opportunity to learn directly from the responders that run your digital operations and catch problems before they become trends or contribute significant negative impact.

The primary purpose of this review is to **understand on-call load and pain**. From there, we seek to identify the source of that load and pain. With that information, we can transfer knowledge between responders and plan for improvements to future on-call shifts.

## When
On-Call Reviews are best conducted with about a week’s worth of on-call history. If your company runs with week-long on-call shifts, aligning this review with the end of one shift and start of another is ideal. If you operate daily, every two weeks, or monthly on-call shifts, you may choose to run your On-Call Reviews at the start/end of those shifts. However, reviewing on-call load on a weekly basis is a best-practice for most digital businesses.

On-Call Reviews are best conducted as standalone meetings and typically require about 30 minutes of a team’s time. For teams that experience meeting fatigue, another option is to reserve the last 30 minutes of another regularly scheduled team meeting for On-Call Review.

## Review Scope
Reviews should be conducted for individual product delivery teams, and consist primarily of the team members that build and support digital products. In an organization with 20 product delivery teams, there typically will be 20 different operational review meetings each week. For organizations with light on-call load or small teams, it can make sense to run reviews at the department level or with a group of teams at once.

The review should cover the time since the last review and focus on technical services where the team had on-call responsibility. On-call responsibility can come from the team owning a technical service, but can also come from services owned by a different team, requiring attention from others.

## Meeting Owner & Attendees
On-Call Reviews are something typically instituted and managed by a team manager, but if the review coincides with the shift schedule, the meeting is often run by the on-call responder whose shift is ending. This person is not only the best person to transfer knowledge from one on-call responder to another, they are also the right person to provide incident and source service context to the team manager. The role of the team manager during the meeting is typically to ask probing questions, spot trends others may have missed, and collect information that needs to be shared with other teams or up the management chain.

Required meeting attendees include the team manager, the outgoing on-call engineer, and the incoming on-call engineer. While not required, it is a best practice to include the entire team in an effort to maximize knowledge transfer and shared accountability.

## Suggested Metrics
To run an effective review, you’ll want three types of information: team and service level metrics, responder-level metrics, and incident details. You may not be able to easily pull all these metrics at first, and you may have different metrics you find valuable. Use what you have, and what you can. Below are suggested metrics for maximum meeting effectiveness:

* Incident count (team total, by service, by responder)
* Escalation count (team total)
* Off-hours incident count (team total, by responder)
* Sleep-hours incident count (team total, by responder)
* Interrupting alert count (total, by service, by responder)
* Off-hours and sleep-hours interrupting alert count (by responder)
* Total hours with at least 1 interrupting alert (team total, by responder)
* List of all incidents, with details about root cause, duration, service, etc.

## Conducting the Review
This meeting is rather short and should be highly focused. Generally, the meeting flow will go as follows:

1. Start with the outgoing on-call responder summarizing the on-call load and pain
1. Review any metrics you have available that can quantify on-call load and pain, focusing on which services alerted and when
     * Use some of the questions below to drive your metric review
1. Surface and discuss any incidents that remain open and under active investigation
     * What does the incoming on-call need to know and how can they help resolve?
1. Ask if any new monitoring alerts were created by the prior on-call, then review and ensure they are documented
1. Use most of the remaining time to talk through incidents that were addressed and closed during the past shift
     * Do any of these incidents require more follow-up work to avoid in the future? How can the incoming on-call help complete work to prevent repeats?
     * Which of these incidents were unactionable and how can monitoring be changed to avoid false alarms in the future?
1. Finally, discuss concrete actions the incoming on-call responder and/or the rest of the team can take to make the next and all following shifts lighter in load and pain

A successful review meeting will allow you to answer most or all of these questions:

* How many incidents did we respond to? Was that more or less than the prior week?
* Did our alerting miss any incidents?
* Which technical services were the biggest contributors?
* Did anyone on the team experience a particularly heavy on-call/incident response load?
* Was it immediately clear if incidents required attention and were actionable?
* Did we deal with new incidents we haven’t seen before or repeat incidents?
* Are we responding in a timely manner to incidents that require immediate attention?
* What effort could improve our future on-call load and what investment recommendations would we make to organization leadership?
* Do we need to conduct any training for enhanced on-call and incident response skill sets?

## Taking Action
Operational reviews exist to uncover where action can be taken to improve people, business, and customer outcomes. If you had no on-call pain and no way to improve future on-call load, you may not have any action to take after this meeting.

More than likely, your team will walk away with something it can do. The nature of the actions you take will vary depending on what you learned in the review and how your company operates. The actions that come out of an on-call review tend to focus on how the lives of your on-call responders can improve, which is directly tied to technical service operations.

Common areas of action include tuning monitoring thresholds to reduce the number of unactionable alerts, updating runbooks with new information on quickly resolving incidents, or recommending investments in technical services to improve reliability.

## Final Notes & Considerations
Effectively running this review (and all Operational Reviews) means matching the idea of blameless postmortems. The purpose of this meeting is NOT to judge anyone one team's or individual's performance; rather, the goal here is to surface issues and increase shared understanding, without judgment or blame.

If one of your responders did in fact experience a particularly painful on-call shift, there is something you can do about it! Make sure you let them know that you understand what they had to deal with. Consider giving them praise in front of the rest of your team, department, or company. If it was a really bad shift, you might send a small gift or even offer a comp day off work. At the very least, you can adjust the upcoming on-call schedule to make sure they get a break before having to deal with a heavy on-call load again. The best thing you can do though? Commit to investing into services, process, and tools so on-call life improves.

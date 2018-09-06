![Service Review](../assets/img/headers/service-review.jpg)
*Credit: [Lukas @ Pexels](https://www.pexels.com/photo/person-writing-on-notebook-669615/)*

Once your organization has begun to consistently conduct On-Call Reviews, the next step is to start conducting Service Reviews at the department or division level. These reviews are an opportunity for management to spot trends and change course (if necessary) before negative impacts become broad and large.

The purpose of this review is to **understand which technical services and their supporting operations have impacted the business**. It seeks to understand not only where impact comes from, but also the type and scope of impact on the business. From there, management can focus investment into technical service reliability and process improvements to create better business outcomes.

## When
Unlike On-Call Reviews, there is no typical calendar that drives a logical time to run the Service Review meeting. Most organizations that conduct Service Reviews do so on a monthly cadence. Having a month between reviews allows for changes or improvements from past reviews to begin to take effect and offers the opportunity to adjust operational process or tools before issues become too severe while still respecting the time of the people involved by only asking them to assemble as a team once a month.

## Review Scope
Service Reviews should be conducted for whole divisions or departments. For a large organization, this may mean one Service Review for all the teams responsible for a specific product or line of business. For medium-sized organizations, this could mean one review for the Product Engineering division, another for the IT department, and a third for the Operations division. For smaller companies, a single review may cover all teams in the organization involved with developing and delivering digital products. Regardless, Service Reviews will typically cover the operations and software owned by multiple teams.

The metrics and discussion at the meeting should include all technical services owned by teams that roll up to the group (or division or department) running the review meeting. If there are downstream dependencies on the services owned by the teams in question, those services should also be part of the scope of this meeting.

Each Service Review should cover the time period since the last Service Review (ideally one month).

## Meeting Owner & Attendees
This review is typically organized and led by a departmental or divisional leader, usually a Director or Vice President of Engineering, IT, or Operations. Driving this meeting from the senior management level not only ensures participation, it offers a commitment by senior management to take action and follow through with changes to investments into service operations.

At small and medium-sized organizations, the review meeting is called, set up, and run by the department/division head themselves, with the support of any data analysts, program managers, or administrative assistance they may have. At larger organizations, the Service Review concept may be sponsored by the Office of the CIO or Office of the CTO, with program managers from those offices running or assisting in the running of these reviews with each department or division.

In attendance should be all the functional leads and/or direct reports of the department, division, or organization leader that owns the scope of teams and services to be covered in the meeting. These are usually other Vice Presidents, Directors, and Senior Managers of Engineering, IT, and Operations. It is rare for engineering managers to attend this meeting, except  at organizations where there are not multiple layers of leadership in Engineering, IT, and/or Operations. On-call responders do not need to be part of this meeting.

## Suggested Metrics
For the Service Review, you’ll look at metrics primarily through the services lens. In addition to incident metrics through the lens of services, the metrics you’ll use here begin to point more directly to customer impact, through product availability. You may not be able to easily pull all these metrics at first and you may have different metrics you find valuable. Use what you have, and what you can. Below are suggested metrics for maximum meeting effectiveness:

* Product availability against SLA (total and by business service)
* Time without major incident (total, by technical service, and business service)
* Time without high-urgency incident (total, by technical service, and business service)
* Major incident count (total, by technical service, and business service)
* High-urgency incident count (total, by technical service, and business service)
* Mean time to acknowledge (total and by technical service)
* Mean time to resolve (total and by technical service)
* A list of all major incidents, with details on incident type, offending technical service, business service(s) impacted, duration, and impact to the business (severity, customer impact counts, etc.)

## Conducting the Review
While longer than the On-Call Review meeting, the Service Review meeting is still a highly focused activity. Generally, the meeting flow will go as follows:

1. Distribute Service Review metric reports to all attendees ahead of time
     * This provides an opportunity for a pre-read and to collect any supplemental information that may be helpful
1. Review top-line, summary metrics that cover the entire division or department
1. Review business service–level metrics to understand customer impact
     * Use the same metrics as the top-level, but scoped to business services
1. Review metrics and incident trends for technical services that had the greatest impact on underperforming business service metrics
1. Walk through all of the top major incidents for technical services that had the most business service impact
     * Focus on root cause, duration, the postmortem, and status of follow-up items
1. Use the remainder of the meeting to make concrete action plans, focusing on improved business service availability

A successful review meeting will allow you to answer most or all of these questions:

* What was our uptime and customer availability for the month?
* How many incidents did we have? Are they trending up or down?
* Were any business services impacted by incidents more than other business services?
* Which technical services had the greatest negative impact on business service reliability?
* For any technical services that had negative impact on business services, how many incidents did they have that month? Is the trend going up, down, or staying the same?
* What were the causes of our major incidents? How effective was our response? Are these major incidents likely to happen again?
* If we want to improve our uptime and customer availability in the future, where should we invest more people, process, and/or technology resources?

## Taking Action
As with all Operational Reviews, the appropriate action to take will be highly dependent on what was learned in the Service Review, how the organization runs, and current focus or goals. There are, however, a few general tips and common areas of focus for taking action after a Service Review.

The first thing to do is target where action is required. This is where the concept of business services is helpful. Prioritization of investment in a technical service should not be solely based on incident count or duration; rather,  the total impact to businesses services should drive the level of investment placed into a technical service.

Next, you’ll need to determine the type of investment a technical service requires. Investments into improving service operations happen in many ways and include: major incident response training for responsible teams, more contextual information shared with alerts, technical service refactoring, or infrastructure upgrades, just to name a few.

Whatever the required action, make sure you can tie the effort back to optimizing for business outcomes, especially around customer availability of your digital products.

## Final Notes & Considerations
As you may be able to see, the monthly Service Review is symbiotic with the weekly On-Call Review. If your teams are conducting On-Call Reviews, there should be no surprises about what services are in need of attention. If you are an attendee of the Service Review meeting, it's a good idea to ask your direct reports for summaries of on-call load/pain over the past month or even ask them to share their on-call metric reports with you.

If your teams are conducting on-call handoff reviews, you should not see much in the way of noisy or unactionable services at your monthly service review. If you do find that the service issues you are reviewing here are related to unactionable alerts from noisy services, your focus should be on running weekly on-call handoff reviews where you can address monitoring thresholds and unactionable alerts before they become an issue again at this review.

![Service Review](/assets/images/headers/OpsReviews-Service.png)

Once your organization is consistently conducting On-Call Reviews, that data can be used to conduct Service Reviews at the department or division level. These reviews are an opportunity for management to spot trends and make necessary course corrections before negative impacts become broader and potentially more damaging.

The purpose of this review is to **understand which technical services are impacting the business**. It seeks to understand not only where impact comes from, but also the type and scope of impact on the business. With that knowledge, management can then focus investment into technical service reliability and process improvements that create better business outcomes.

## Cadence
Unlike On-Call Reviews, there is no typical calendar event that creates a logical opportunity to have a Service Review meeting. But most organizations conduct Service Reviews on a monthly cadence.

A monthly cadence allows enough time for any changes or improvements to processes and tooling that were identified in previous meetings to be implemented and take effect in a quantifiable way. That cadence also offers an opportunity to make adjustments before issues become too severe, yet is still respectful of the time investment being made by all of the people involved.


## Scope
Service Reviews should be conducted for whole divisions or departments. For a large organization, this may mean one Service Review for all the teams responsible for a specific product or line of business. For medium-sized organizations, this could mean one review for the Product Engineering division, another for the IT department, and a third for the Operations division. For smaller companies, a single review may cover all teams in the organization involved with developing and delivering digital products. Regardless of the size of your organization, the scope of Service Reviews should cover the operations of services owned by multiple teams.

The metrics and discussion at the meeting should include all technical services owned by teams that roll up to the group (or division or department) running the review meeting. If there are downstream dependencies on the services owned by the teams in question, those services should also be part of the scope of this meeting.

Similar to On-Call Reviews, each Service Review should cover the time period since the last meeting (ideally one month).

## Meeting Owner and Attendees
This review is typically organized and led by a departmental or divisional leader, usually a Director or Vice President of Engineering, IT, or Operations. Driving this meeting from the senior management level not only ensures participation, it offers a commitment by senior management to take action and follow through with changes to investments into service operations.

At small and medium-sized organizations, the review meeting is called, set up, and run by the department/division head themselves. They are typically supported by any data analysts, program managers, or administrative assistants relevant to their projects. At larger organizations, the Service Review may be sponsored by the Office of the CIO or Office of the CTO, with program managers from those offices running or assisting in the running of these reviews with each department or division.

The meeting should be attended by all the functional leads and/or direct reports of the department, division, or organization leader that owns the scope of teams and services to be covered in the meeting. These are usually other Vice Presidents, Directors, and Senior Managers of Engineering, IT, and Operations. It is rare for engineering managers to attend this meeting, except in organizations where there are not multiple layers of leadership in Engineering, IT, and/or Operations. On-call responders do not need to be part of this meeting.

## Metrics
As the name implies, for the Service Review, you’ll look at metrics primarily through the service lens. In addition to incident metrics through the lens of services, the metrics you’ll use here begin to point more directly to customer impact, through service availability.

Similar to the On-Call Review, you may not be able to easily pull all these metrics at first, and you may have different metrics you find valuable. Use what you have and what you can gather as a way to get started. The most important thing is that you get started.

Below are suggested metrics for maximum meeting effectiveness:

* Service availability against SLA (total and by business service)
* Time without major incident (total, by technical service, and business service)
* Time without high-urgency incident (total, by technical service, and business service)
* Major incident count (total, by technical service, and business service)
* High-urgency incident count (total, by technical service, and business service)
* Mean time to acknowledge (total and by technical service)
* Mean time to resolve (total and by technical service)
* A list of all major incidents, with details on incident type, offending technical service, business service(s) impacted, duration, and impact to the business (severity, customer impact counts, etc.)


## Conducting the Review
While longer than the On-Call Review meeting, the Service Review is still a highly focused activity. Generally speaking, the meeting should follow this type of agenda:

1. Distribute Service Review metric reports to all attendees ahead of time (this provides an opportunity to pre-read and collect any supplemental information that may be helpful)
1. Review top-line, summary metrics that cover the entire division or department
1. Review business service–level metrics to understand customer impact
     * Use the same metrics as the top level, but scoped to business services
1. Review metrics and incident trends for technical services that had the greatest impact on underperforming business service metrics
1. Walk through all of the top major incidents for technical services that had the most business service impact
     * Focus on contributing factors, duration, the postmortem, and status of follow-up items
1. Use the remainder of the meeting to make concrete action plans, focusing on improved business service availability

A successful review meeting will allow you to answer most or all of these questions:

* What was our uptime and customer availability for the month?
* How many incidents did we have? Are they trending up or down?
* Were any business services impacted by incidents more than other business services?
* Which technical services had the greatest negative impact on business service reliability?
* For any technical services that had a negative impact on business services, how many incidents did they have that month? Is the trend going up, down, or staying the same?
* What were the main contributing factors to our major incidents? How effective was our response? Are these major incidents likely to happen again?
* If we want to improve our uptime and customer availability in the future, where should we invest more people, process, and/or technology resources?

## Taking Action
As with all Operational Reviews, the appropriate action to take will be highly dependent on what was learned in the Service Review, as well as organizational culture, current focus, and current goals. However, there are a few general tips and common areas of focus for taking action after a Service Review.

The first thing to do is to understand where to prioritize action. By focusing on business services, it’s easier to prioritize investments. Prioritization should not be solely based on incident count or duration; rather, the total impact to businesses services should drive the level of investment placed into its underlying technical services.

Next, you’ll need to determine the type of investment a technical service requires. Investments into improving service availability may include things like more training on major incident response training for responsible teams, sharing more contextual information with alerts, refactoring service code, paying off technical debt, making infrastructure upgrades, and many others.

Whatever the required action, make sure you can tie the effort back to optimizing for business outcomes by providing clarity over how it impacts customer availability of your digital services.


## Final Notes and Considerations
Hopefully, you’re starting to see that the monthly Service Review and the weekly On-Call Review are symbiotic.

If your teams are conducting On-Call Reviews, there should be no surprises about what services are in need of attention. If you are an attendee of the Service Review meeting, it would be a good idea to read summaries of your team’s on-call load/pain over the past month in preparation for this meeting. Ask your teams to share their On-Call Review metrics with you.

If your teams are conducting On-Call Reviews and following up on identified actions, there should be few mentions of unactionable incidents in the monthly Service Review. If that’s not the case, for example, then it’s a clear indication that your focus should be to run weekly On-Call Reviews ,where resolving unactionable incidents gets prioritized so that it isn’t an issue when it’s time for the next monthly Service Review meeting.

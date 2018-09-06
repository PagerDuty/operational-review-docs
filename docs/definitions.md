![Definitions](../assets/img/headers/definitions.jpg)
*Credit: [Pixabay @ Pexels](https://www.pexels.com/photo/blur-book-close-up-data-270233/)*

This documentation uses terms common in digital businesses, but not always standard across organizations. Definitions are provided below for how they are used in this documentation.

**Actionable vs. Unactionable Incidents**

All incidents are either actionable or unactionable. Actionable alerts are when the incident is not a false alarm and some action can be taken by a responder. All other incidents are unactionable.

**Alert**

Alerts are a vehicle for ensuring that the existence of an incident is communicated to responders. Often there is a 1:1 mapping of incident to alert, but not always. There can be multiple alerts per incident if the same issue is noticed by multiple sources or if additional responders need to be alerted about the same issue.

**Business Hours**

The general time that employees are working. Often defined by a broad range of 8 a.m. – 6 p.m., but should follow the norms of each company, region, and office.

**Business Service**

A business service is a critical or otherwise important business function of a digital product and is powered by one or more technical services. Businesses services are defined differently by each digital business and are often aligned with product features or capabilities.

**Delivery Team**

Also called a Product Delivery Team, this is a group of people directly responsible for building and/or operating a technical service. Always inclusive of the engineers on the team, delivery teams may also include the team manager, UX Designer, Product Owner, and/or Agile Coach.

**Digital Business**

A digital business is any company or organization whose product value is delivered primarily online, often 24×7 and with great simultaneous scale. Some companies are digital businesses in their entirety, like PagerDuty. Other companies are not digital businesses at first sight, but critical elements of their business rely on software (the cash registers at a restaurant, for example).

**Digital Operations**

This term describes the way a digital business must operate in real time because their product is available 24×7 and can be used simultaneously by a large number of customers—situations where even a short technical issue can have large impact on revenues.

**Escalation**

An escalation is when the primary on-call does not acknowledge an incident and the alert is escalated to another person. Escalations often happen automatically but can be done manually.

**High-Urgency Incident**

Any incident that is urgent in nature so that the on-call responder should be interrupted to address it right away.

**Incident**

Any unplanned disruption or degradation of service that is actively affecting customers' ability to use your products. Sometimes there isn’t actually a problem, but we still call any event that triggered an alert an incident. Incidents are both conceptual (`something’s wrong`) and discrete objects (`Incident #26534 on Thursday at 5 p.m.`).

**Incident Response & Major Incident Response**

Incident Response/Major Incident Response is the approach to addressing and managing an incident. The goal isn’t just to solve the incident, but to handle the situation in a way that limits damage and reduces recovery time and costs.

**Interruption**

Interruptions are when an on-call responder is notified by SMS (text), mobile push notification, or phone call. Interruptions do not include notifications via email from an on-call and incident management platform.

**Major Incident**

Any incident that requires a coordinated response, often across multiple teams. Major incidents are typically highly noticeable by customers, so fixing the problem is of the highest importance. Often referred to as P1, P2, SEV-1, or SEV-2 inside some organizations.

**Mean Time to Acknowledge (MTTA)**

The average across all incidents of the time between incident creation and the time when a responder acknowledges that they have seen the alert and will take action.

**Mean Time to Resolve (MTTR)**

The average across all acknowledged incidents of the time between incident creation and when a responder signifies that the issue has been resolved and effectively closes the incident or otherwise ends incident response.

**Monitoring**

Any software or hardware tool that can monitor the state of a technical service and alert on potential issues or otherwise push information to an on-call and incident management platform.

**Off Hours**

Typically the waking hours outside of work, often defined as 6 p.m. to 10 p.m. Monday through Sunday, and non-sleep hours on Saturday and Sunday. Will vary by company, job role, and more.

**On Call**

To go on call means to make oneself available to be notified of any potential software issues and resolve them in real time, at any time during an on-call shift. Engineers usually rotate on-call responsibilities in weeklong shifts where they are available to respond to technical service issues 24×7.

**On-Call Load & Pain**

When a responder goes on call, any unplanned work and interruptions they receive is collectively defined as the load they experience. Any on-call load over the expected amount is considered on-call pain.

**Responder**

A responder is any team member that responds to an alert from an on-call and incident management platform, and helps  resolve issues with technical services. By definition, the person on call is a responder, but anyone called in to help is also a responder.

**Service Level Agreement (SLA)**

[Google defines](https://landing.google.com/sre/book/chapters/service-level-objectives.html) SLA as,

> An explicit or implicit contract with your users that includes consequences of meeting (or missing) the SLOs they contain.

An SLO is a Service Level Objective—essentially an internal goal or target.

**Sleep Hours**

Late night and early morning hours, often defined as 10 p.m. through 8 a.m. Monday through Sunday. Will vary by company, job role, and more.

**Technical Service**

A technical service is a unique piece of software or other technology capability that serves a specific purpose or set of purposes, and has a specific engineering team that owns the operations of that software.

**Time Without High-Urgency Incident**

This is the total minutes or percentage of time during a set period when there was no active high-urgency incident.

**Time Without Major Incident**

This is the total minutes or percentage of time during a set period when there was no active major incident.

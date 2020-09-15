![Definitions](../assets/img/headers/definitions.jpg)
*Credit: [Pixabay @ Pexels](https://www.pexels.com/photo/blur-book-close-up-data-270233/)*

This documentation uses terms common in digital businesses, but not always standard across organizations. Definitions are provided below for how they are used in this documentation.

**Actionable vs. Unactionable Incidents**

All incidents are either actionable or unactionable. Actionable incidents are when the triggering conditions have a clear resolution action that can be taken by a responder. Unactionable incidents are informational false alarms: they convey a system state, but there is nothing for a responder to do other than acknowledging they received a notification of that state.

**Alert**

Alerts are a vehicle for ensuring responders are notified of the existence of an incident. In theory, there is a 1:1 mapping of incidents to alerts. But most often, there can be multiple alerts per incident because the same issue may be detected by multiple sources or if additional responders need to be alerted about the same issue.

**Business Service**

A business service is a critical or otherwise important logical business function of a digital product. Often, that logical function is carried out by a number of underlying technical services. For example, a logical “fulfillment” business service may be represented by various underlying technical services necessary to complete that action such as a shopping cart service, payment service, inventory service, and so on. Businesses services are defined differently by each digital business and are often aligned with product features or capabilities.

**Digital Business**

A digital business is any company or organization whose product value is delivered primarily online, often 24×7 and with great simultaneous scale. Some companies are digital businesses in their entirety, like PagerDuty. Other companies may not seem like digital businesses at a glance, but if critical elements of their business rely on software (the cash registers at a restaurant, for example), then they too are digital businesses.

**Escalation**

An escalation is when the primary on-call does not acknowledge an incident and the alert is escalated to another person. Escalations often happen automatically but can be done manually.

**Full-Service Ownership (FSO)**

Full-service ownership (FSO) is the philosophy that engineers are responsible for the code and services they create in production. Accountability, reliability, and continuous improvement are the main objectives of full-service ownership. 

**High-Urgency Incident**

Any incident that is urgent in nature so that the on-call responder should be interrupted to address it right away.

**Incident**

Any unplanned disruption or degradation of service that is actively affecting a customer's ability to use your product(s). Sometimes there isn’t actually a problem, but we still call any event that triggered an alert an incident. Incidents are both conceptual (“something’s wrong”) and discrete objects (“Incident #26534 on Thursday at 5 p.m.”).

**Incident Response**

[Incident Response](https://response.pagerduty.com) is the approach used to address and manage incidents. The goal isn’t just to solve the incident, but to handle the situation in a way that limits damage and reduces recovery time and costs.

**Major Incident**

Any incident that requires a coordinated response, often across multiple teams. Major incidents are typically highly noticeable by customers, so fixing the problem is of the highest importance. Often referred to as P1, P2, SEV-1, or SEV-2 inside some organizations.

**Mean Time to Acknowledge (MTTA)**

The average across all incidents of the time between incident creation and the time when a responder acknowledges that they have seen the alert and will take action.

**Mean Time to Resolve (MTTR)**

The average across all acknowledged incidents of the time between incident creation and when a responder signifies that the issue has been resolved and effectively closes the incident or otherwise ends incident response.

**Monitoring**

Any software or hardware tool that can monitor the state of a technical service and alert on potential issues or otherwise push information to an on-call and incident management platform.

**On-Call**

To go on call means to make oneself available to be notified of any potential software issues and resolve them in real time, at any time during an on-call shift. Engineers usually rotate on-call responsibilities in weeklong shifts where they are available to respond to technical service issues 24×7.

**On-Call Load & Pain**

When a responder goes on call, any unplanned work and interruptions they receive is collectively defined as the load they experience. Any on-call load over the expected amount is considered on-call pain.

**Real-Time Operations**

This term encapsulates the way a digital business must operate in real time because their product is available 24×7 and can be used simultaneously by a large number of customers. When incidents occur, service teams must respond quickly—i.e., in real time—because even short technical issues can have prolonged large-scale impact on revenue.

**Responder**

A responder is any team member that responds to an alert from an on-call and/or incident management platform, and helps  resolve issues with technical services. By definition, the person on call is a responder, but anyone called in to help is also a responder.

**Service Team**

This is a group of people directly responsible for building and/or operating a technical service, sometimes also referred to as a product delivery team. This team not only includes the engineers who code, ship, and operate the service in production, they may also include the team manager, UX Designer, Product Owner, Agile Coach, or other roles necessary to support daily team operations.


**Service Level Agreement (SLA)**

A service-level agreement is an explicit or implicit contract with your customers that includes consequences of meeting (or missing) the specified targets. The consequences are most easily recognized when they are financial—a rebate or a penalty—but they can take other forms. SLAs are used to communicate service availability expectations externally and are tied to business and product decisions.

**Service Level Objective (SLO)**

A service-level objective is a service availability or performance target used to set expectations internally. They can be useful for communicating with the business about desired service performance and to temper unrealistic expectations for extraordinarily high availability. Unlike an SLA, SLOs are typically not published to customers and they carry no customer consequences when unmet.

**Technical Service**

A technical service is a unique piece of software or other technology capability that serves a specific purpose or set of purposes, and has a specific engineering team that owns the operations of that software.

**Time Without High-Urgency Incident**

This is the total minutes or percentage of time during a set period when there was no active high-urgency incident.

**Time Without Major Incident**

This is the total minutes or percentage of time during a set period when there was no active major incident.

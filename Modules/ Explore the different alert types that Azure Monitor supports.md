## Understand the alert state in the resolution process

You control the alert state to manage and specify where you are in the alert resolution process. Currently, there are three states:

- Every new alert has an alert state of New. This state means that the issue has been detected, but not yet reviewed.
- After an admin has reviewed the alert, and is working on it, the alert state changes to Acknowledged.
- When the issue is resolved, the alert state is set to Closed.   

# Filter alerts

From the alert summary window, you'll see a satellite view of the alerts being reported in Azure Monitor. You filter this view to reduce the volume of alerts being reported to a specific subset that you're interested in.

You can select the following items to filter the view:

- Smart groups: You can select this filter if it's enabled.
- Resource type: Applies only when it's used with a resource group.
- Resource: Applies only when a resource type has been specified.
- Severity: Identifies the severity assigned by the alert rule.
- Monitor condition: Set by the system and indicates if the alert is fired or resolved.
- Alert state: Typically, finds the New and Acknowledged alerts.

1. What's the composition of an alert rule?
    - [ ] Resource, condition, log, alert type
    - [ ] Metrics, logs, application, operating system
    - [x] Resource, condition, actions, alert details

2. Which of the following is an example of a log data type?
    - [ ] Percentage of CPU over time
    - [x] HTTP response records
    - [ ] Database tables
    - [ ] Website requests per hour
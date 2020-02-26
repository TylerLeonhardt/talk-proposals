# Web Apps were not the first "Serverless": A brief history

or

# Let's time travel: A brief history of "Serverless"

or

# Management & Operations in the Serverless space: A brief history

## Elevator Pitch

*You have 300 characters to sell your talk. This is known as the "elevator pitch". Make it as exciting and enticing as possible.*

Long before the term
"serverless"
and modern Functions-as-a-service offerings emerged,
event-driven cloud compute was used all over the management and operations space.
In this talk,
we'll look at
"serverless"
before
"serverless"
and why you should consider this paradigm for non-client facing tasks.

## Description

*The description will be seen by reviewers during the CFP process and may eventually be seen by the attendees of the event. You should make the description of your talk as compelling and exciting as possible. Remember, you're selling both the organizers of the events to select your talk, as well as trying to convince attendees your talk is the one they should see.*

History class is in session -
and we have a lot to learn from it!

Let's set aside our web apps and REST APIs and look at what the original event-driven cloud compute was used for:
operations and management tasks.
In this talk we'll go back in time to understand what
"serverless"
was before
"serverless"
and how the event-driven cloud compute paradigm was used.
Continuous integration,
deployments,
data migrations and other long running tasks dominated this space and have evolved into modern day DevOps.

You'll leave this talk with knowledge of how
"serverless"
was used back in the day -
but also how it's modernized over the years with new Functions-as-a-service
(FaaS)
offerings.
At the end,
we'll briefly discuss how you can leverage modern solutions to tackle ops,
management,
and other critical tasks that are necessary to automate for businesses at scale.

## Notes

*Notes will only be seen by reviewers during the CFP process. This is where you should explain things such as technical requirements, why you're the best person to speak on this subject, etc...*

This is an entry level talk but it comes with the expectation that the attendee either has serverless client-facing web apps/REST APIs used by client-facing apps or is aware of the concept.

Being on the PowerShell team at Microsoft might not seem like the perfect translation to
"Serverless"
but my team and I have been involved in serverless tech for quite some time.

I personally worked on the PowerShell worker for Azure Functions enabling new opportunities for Azure Functions for Ops tasks.
We've seen folks use this for managing Azure resources and permissions.

My team has also lived along side the Azure Automation team for quite some time.
Azure Automation was the original
"serverless Ops"
offering at Microsoft that only supported PowerShell
(and later Python).
IT Pros and Ops folks would use Azure Automation for complex deployment and management tasks -
all without worrying about a server underneath the code.

My team also coordinated with AWS so that they can add PowerShell support within AWS Lambda.

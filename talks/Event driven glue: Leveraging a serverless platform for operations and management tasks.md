# Event driven glue: Leveraging a serverless platform for operations and management tasks

## Elevator Pitch

*You have 300 characters to sell your talk. This is known as the "elevator pitch". Make it as exciting and enticing as possible.*

Every company has manual tasks,
whether it's managing databases,
access control to production resources,
etc.
What if they didn't have to be manual and you could use the same serverless paradigm you're used to?
In this talk we'll look at how to approach and automate these tasks using serverless tech.

## Description

*The description will be seen by reviewers during the CFP process and may eventually be seen by the attendees of the event. You should make the description of your talk as compelling and exciting as possible. Remember, you're selling both the organizers of the events to select your talk, as well as trying to convince attendees your talk is the one they should see.*

You've got client facing serverless code everywhere...
but all your operations tasks like managing databases,
access control to production resources,
etc.
are all manually done.
What if it didn't have to be like this?
What if you could automate a lot of these management tasks while also using the same serverless stack you're used to?

That's the power of
"severless ops".
It gives you the ability to glue together just about any building blocks that don't directly fit.
You'll leave this talk with a foundational understanding of how to leverage the event-driven serverless paradigm for management and operations tasks and also how to discover tasks that could be automated.

Possible demos could include:

* Cleaning up stale resources used for testing/R&D
* Giving a user permissions to some resource (subscription, key vault, etc)
* Managing VMs or anything really (Starting, stopping, creating)

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

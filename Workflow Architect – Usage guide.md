============================================================
WORKFLOW ARCHITECT PROMPT – USAGE GUIDE
============================================================

AUTHOR: Scott M.
VERSION: 1.0
LAST UPDATED: 2026-03

============================================================
PURPOSE
============================================================

This guide explains how to use the Workflow Architect prompt to design
clear, structured workflows through an interactive interview process.

The prompt acts like a workflow consultant that gathers information,
organizes the process, and produces a framework that can easily be
converted into a diagram using tools such as:

• Microsoft Visio
• Lucidchart
• draw.io (diagrams.net)

The final output provides a structured workflow description that can be
quickly turned into a visual flowchart.

============================================================
WHEN TO USE THIS PROMPT
============================================================

The Workflow Architect prompt is useful when:

• You want to design a new workflow
• You want to document an existing process
• You are planning automation
• You want to identify workflow bottlenecks
• You want to convert a process into a flowchart

Common use cases include:

• approval processes
• helpdesk ticket routing
• employee onboarding
• data processing workflows
• operational procedures
• automation pipelines

============================================================
HOW THE PROMPT WORKS
============================================================

The prompt guides the user through a structured interview designed to
collect the information needed to build a complete workflow.

The interview includes the following phases:

1. Workflow Goal
2. Workflow Trigger
3. Inputs
4. Process Steps
5. Decision Points
6. Exceptions
7. Outputs
8. Optimization

The AI asks one question at a time to gather the required details.

Once the interview is complete, the AI generates:

• workflow summary
• step-by-step process list
• decision logic
• flowchart-ready framework
• workflow gap analysis

============================================================
WHAT THE FINAL OUTPUT PROVIDES
============================================================

The prompt produces several structured sections.

WORKFLOW SUMMARY
A plain-language description of the workflow.

WORKFLOW STEPS
A numbered sequence describing the process.

DECISION LOGIC
Conditional branches within the workflow.

FLOWCHART FRAMEWORK
A text-based structure that can easily be converted into a diagram.

WORKFLOW GAP ANALYSIS
A review of the workflow identifying potential improvements.

============================================================
PAUSING AND RESUMING A SESSION
============================================================

Workflow design interviews may take time to complete.

If you need to stop partway through, type:

EXPORT WORKFLOW SESSION

The AI will generate a Markdown export containing all information
collected so far.

Save this export locally.

To resume later, paste the exported session back into the chat and
request to continue the workflow design interview.

The AI will resume at the correct phase.

============================================================
WORKFLOW DESIGN TIPS
============================================================

When answering interview questions:

Be specific.
Describe the actual steps that occur.

Include people, systems, and actions involved.

Think about what can go wrong and how the process handles it.

Clear answers will produce better workflow outputs.

============================================================
COMMON WORKFLOW COMPONENTS
============================================================

Most workflows include several common elements.

Triggers
What starts the process.

Inputs
Information or materials required.

Actions
The work performed during the process.

Decisions
Points where the workflow branches.

Exceptions
Failure paths or alternate flows.

Outputs
The final result produced by the workflow.

Understanding these elements makes workflow design easier.

============================================================
WORKFLOW TEMPLATES
============================================================

Templates can speed up workflow design by providing common patterns.

------------------------------------------------------------
APPROVAL WORKFLOW TEMPLATE
------------------------------------------------------------

Typical Uses

• purchase approvals
• document approvals
• access requests

Structure

START
Trigger: Request submitted

Step 1: Validate request information

Decision: Is request complete?
    YES → Step 2
    NO → Request additional information → END

Step 2: Send request to approver

Decision: Approved?
    YES → Step 3
    NO → Notify requester → END

Step 3: Execute request

Step 4: Send confirmation

END

------------------------------------------------------------
TICKET ROUTING WORKFLOW TEMPLATE
------------------------------------------------------------

Typical Uses

• IT helpdesk
• support requests
• service queues

Structure

START
Trigger: Ticket submitted

Step 1: Validate ticket details

Step 2: Categorize request

Decision: Ticket category?

    Hardware → Route to hardware team
    Software → Route to software team
    Access → Route to identity team

Step 3: Technician reviews ticket

Step 4: Issue resolved

Step 5: Notify requester

END

------------------------------------------------------------
DATA PROCESSING WORKFLOW TEMPLATE
------------------------------------------------------------

Typical Uses

• ETL pipelines
• data imports
• reporting pipelines

Structure

START
Trigger: Data received

Step 1: Validate data

Decision: Data valid?
    YES → Step 2
    NO → Reject data → END

Step 2: Transform data

Step 3: Store data

Step 4: Generate report

END

============================================================
BEST PRACTICES
============================================================

Design workflows with clarity.

Avoid unnecessary steps.

Define clear decision points.

Include error handling.

Include notifications for important outcomes.

Consider where automation could improve the process.

============================================================
LIMITATIONS
============================================================

The prompt helps design workflow logic but does not generate diagrams
directly.

Users must create visual diagrams using diagramming tools.

The output framework is designed to make that process fast and simple.

============================================================
END OF GUIDE
============================================================
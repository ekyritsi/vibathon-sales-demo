# Presenter tour: playbook, specialist, connection, work surface

**When:** 11:18-11:22, after everyone has submitted the starter prompt.
**Goal:** Give sales leaders a memorable explanation, not a configuration tutorial.

Say: "While your dashboard builds, let me show you four ideas behind the app. You don't need to set up any of them today."

## Prepare before the session

On your presenter machine, identify these in the actual app build you will use:

| Example | What to prepare | If unavailable |
|---|---|---|
| A skill | One installed skill with a short, understandable description and a task it supports | A cropped screenshot of a real skill from your prepared environment |
| A custom agent | One available specialist, such as a reviewer; verify how to select it | A screenshot of its role and instructions |
| An MCP connection | An already configured connection and its non-sensitive tool descriptions | A screenshot of that connection's capabilities, without credentials or business data |
| A canvas | A supported preview or editor showing fictional demo content beside Chat | A screenshot of a real canvas with demo content |

Feature labels and entry points can vary by build, account, and policy. Rehearse your exact navigation; do not promise that everyone has the same features. If you have neither a safe live example nor a screenshot, explain the concept without implying it is configured.

Do not add dependencies to the attendee exercise. No live connector installation, authentication, company-data searches, or cloud resource creation.

## 0:00-1:00 | Skills: "A reusable playbook"

**Show:** Open your prepared skill's description or instructions. Point to what task it covers. Do not spend the minute reading its full contents.

**Say:**
> "A prompt is the brief for this particular job. A skill is a reusable playbook: instructions and resources for doing a particular kind of job consistently. Think of a sales playbook that you don't have to explain from scratch every time."

**Tie it to the dashboard:** "A team could create a skill for its demo design conventions and accessibility checklist, so we don't repeat those instructions for every prototype."

That dashboard skill is an illustrative use case unless you actually prepared it. Showing a skill is not evidence that it ran; do not claim the dashboard used it.

## 1:00-2:00 | Agents: "Bring in a specialist"

**Show:** Open the prepared custom agent's role and instructions or the app's available-agent selector.

**Say:**
> "An agent can work toward a goal using the tools it's allowed to use. A custom agent specializes that assistant with a role, instructions, and tool choices. Think of bringing a solution engineer or reviewer into a deal. A skill is the playbook; the agent is the specialist who can use it."

**Optional prepared action:** In a separate session scoped to a copy of the fallback, select an available read-only reviewer and submit:

```text
Review index.html without changing files or running commands. From the source,
identify up to three concrete issues a sales leader could encounter when
filtering or adding deals. Explain any findings in plain English. If you find
none, say so. Distinguish source review from actually testing in a browser.
```

Only submit this if rehearsed; do not wait for the answer during the tour. Return to it during show-and-tell if ready. A normal chat prompt asking for a review does not itself demonstrate that a custom agent was selected. Do not claim agents necessarily run in parallel or independently approve their own work.

## 2:00-3:00 | MCP: "Connect approved tools and data"

**Show:** The prepared connection and one or two of its tool descriptions. Viewing these is enough; do not retrieve business data.

**Say:**
> "MCP stands for Model Context Protocol. It's a standard way for AI applications to work with tools and data offered by connected servers. Think of an integration with an approved business system: instead of copying everything into chat, the assistant can use the tools the connection exposes, within its configured access."

**Tie it to the dashboard:** "With an appropriately approved integration, a future workflow could retrieve permitted CRM information. Today's dashboard does not connect to CRM; it uses fictional data."

**Boundary:** MCP is not a model, not an automatic permission grant, and not a guarantee of read-only access. Some tools can change records. Authentication, permissions, organizational policy, and any required approvals still matter. A connection available to Copilot does not automatically become a connection inside the generated HTML app.

## 3:00-4:00 | Canvases: "Work beside the conversation"

**Show:** A prepared supported canvas beside Chat. Point out the conversation on one side and the content or interactive workflow on the other.

**Say:**
> "Chat is where I describe the goal and give feedback. A canvas is a work surface beside it, where I can view or interact with supported content. Think of discussing a proposal while looking at the proposal together."

**Tie it to the dashboard:** Use the dashboard in a canvas only if you have already verified a supported preview route. Double-clicking a local HTML file in an external browser is still the attendee path; it is not itself a canvas demonstration. If your canvas needs a running server or another setup step, prepare that on the presenter machine beforehand rather than adding it to the exercise.

Use an ordinary preview or editor for this tour, not a Foundry agent deployment workflow. Capabilities differ by canvas; opening one does not automatically build, deploy, or connect anything.

**Close:**
> "Playbook, specialist, connection, work surface. Now back to your dashboard: open it, try it, and ask for one change."

## Keep the demo honest and on time

- Stop at four minutes, even if an optional request is still running.
- Explain what is actually on screen. Distinguish configured features from illustrative possibilities.
- Use only fictional or approved demo content; hide account information and other sessions.
- Do not equate a working prototype with a production-ready application.
- If setup interrupts the flow, show the prepared screenshot and return to hands-on time.

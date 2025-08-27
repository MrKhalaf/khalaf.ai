# my definitive AI workflow

## After over 2 years of AI development experimentation I've found my flow and transformed my role

I began like many others: testing local LLMs and cycling through the latest coding assistants. Nothing endured. Early workflows were inefficient as they involved dragging files, copying outputs, pasting changes. MCP integrations promised structure but never worked.

The debate around coding with LLMs is polarized. Executives imagine full automation; skeptics dismiss the field outright. The truth is between these extremes. For backend engineers like me, LLMs cut the friction of learning frameworks, trying multiple designs in parallel, and asking questions without hesitation.

The chat format quickly became a limitation. Tracking revisions and branches was impossible. Terminal-based tools like Claude Code helped, but remained costly and opaque. 

Atlassian’s Rovo Agent changed that. With its beta release I could split sessions across repositories, generate prototypes, and review code properly inside VSCode. 

**I came up with a cool workflow:**

### Step 0: Figure out what you want to build
Can't help you with that one. Whatever it is, you should have a long brainstorming session where you write everything down before reviewing.

### Step 1: Fight with the LM
Refine your brainstorm doc to get the gist of what you want then feed it into the LLM.

> Attached is the BRAINSTORM.md for Timeio, an automated timecard OCR processor. Go through the document and challenge decisions & assumptions made. Questions should be asked one by one and discussed at length before proceeding. Use the answers from the discussions to inform a new PRD in PRD.md.

The results are stunning. It's not just the magic of the PRD itself but the process by which you're actually digesting your own thoughts and second-guessing prior assumptions. By the end of the discussion (usually about an hour) the biggest transformation is in your own  mental model of your now-refined plan.

### Step 2: The Sprint Plan
We know what we're building now. Organize everything by generating a Sprint Plan. Atlassian's Rovo Agent has native Jira integration so I use that (free Claude credits under the hood).

Review the sprint plan once generated. Don't sweat the details much here because the PRD should cover the main requirements; this is for tackling tasks in an organized manner and making it easier for you to review the code piece-by-piece later.


### Step 3: The Execution Sprint

**Plan, vision, and sprint in hand. We're ready to go.**

You've put in hours of work & now it's time to reap the rewards. The strong mental vision of the finished product, coupled with the documented detail will now come to fruition.

The sprint plan is now the central tracking mechanism for the coding agent(s).

### Step 4: Back at The Wheel

Armed with all the context, you now *review* code. Yes you actually need to read it almost line-by-line and ask questions. I have a custom keybinding that drops a `REVIEW:` comment based on the filetype. After commenting my feedback there, I go back to Rovo and it addresses my concerns or challenges my thinking.


### Closing out

Mistakes I see: Treating LLMs as magic typewriters. Skipping design, planning, and documentation. Failing to integrate with task management or write tests. The real bottleneck is now system-level thinking, not typing speed.

My role shifted upward. I spend my time on design, architecture, and database schemas. 

If AI coding feels shallow, start with planning. Write requirements by hand before using a model. Only then introduce an agent into the loop. Use tools that support review, write proper tests, and keep documentation alive. AI does not remove the work it just accelerates it.

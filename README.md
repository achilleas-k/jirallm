# JIRALLM

A very simple Python script that fetches ticket summaries and comments from Jira and sends them to a local LLM to summarise.

## WHY

This is a simple personal tool.  It works for me, most of the time.  It can save me the trouble of going to Jira on the web to catch up on updates on one or more tickets and to get back into the general state of a group of tickets.

## HOW

The script fetches one or more tickets from a Jira instance (hard-coded to issues.redhat.com), creates a context that includes the summary, description, and comments of each ticket, and asks a locally running LLM (currently gemma3) through the Ollama API to generate a summary.

## FUTURE

I have no plans to improve or expand on the capabilities of this thing.  It's good enough.

## CONTRIBUTING

Patches not welcome.  I don't care about generalising or improving it.  Feel free to fork it if you think it's useful.

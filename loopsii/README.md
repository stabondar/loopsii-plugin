# Loopsii plugin for Claude

Projects, clients, tasks, time tracking and meeting notes from [Loopsii](https://loopsii.com), inside
Claude. The plugin adds the Loopsii MCP server (`https://app.loopsii.com/api/mcp`) and a skill that
teaches Claude how to use it well: search first, log time from your words, complete tasks, quote what
was decided in a meeting, and always link back to the record.

## Install

Add it from the Claude directory, or in Claude Code:

```
claude plugin install loopsii
```

On first use Claude opens the Loopsii sign-in screen; check the account and press **Allow**.

## What it can do

- Search your whole workspace and open any project, client, task, document, meeting or recording.
- Read meeting notes and full transcripts, and answer questions about what was said in a meeting.
- Log hours, start and stop your timer.
- Create and update projects, clients, tasks and documents. It can never delete anything.

## Privacy Policy

The plugin sends tool requests to Loopsii's own API (`app.loopsii.com`) on your behalf and returns
the matching records; nothing goes to any other service. Loopsii does not receive your conversation
with Claude. The connection is standard OAuth: Loopsii stores the app identity, the permissions you
granted and hashed short-lived tokens, and you can disconnect at any time in Loopsii → Settings → API
→ Connected apps. Full policy: https://loopsii.com/privacy

## Support

hey@loopsii.com · setup guides at https://loopsii.com/connect

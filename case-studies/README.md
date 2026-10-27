# Case studies

Sanitised write-ups of authorised engagements.

**Coming soon.** The first studies are in client review.

Each study covers:

- the target, described by industry and stack rather than by name
- the vulnerability, and the request that demonstrated it
- what an attacker could have reached from there
- the fix, and how long it took
- what we would test first if we started again

<!--
Add a row per study, newest first:

| Study | Class | Impact |
| --- | --- | --- |
| [Title](slug/) | e.g. IDOR | e.g. Cross-tenant read of customer records |
-->

## Rules

- No names, domains, IP addresses, customer data or screenshots that identify
  the target.
- No unpatched findings. If the fix is not deployed, the study waits.
- The timeline is as it happened, including the parts where we were slow.

## Writing one

```
case-studies/
  <slug>/
    README.md      the study
```

Keep it factual: what was reachable, what it would have cost the client, what
closed it. Redact before you write, not before you publish.

# Forward deployed engineer templates

Markdown templates for the documents a forward deployed engineer (FDE) writes on a customer engagement, from the first request to the end-of-pilot readout. Each section has a short prompt, in an HTML comment, saying what the section is for.

They are the same templates as on [drillhall.app/templates](https://drillhall.app/templates?utm_source=github&utm_medium=referral&utm_campaign=templates-repo), where you can copy each one from the browser.

## The templates

In the order an engagement usually needs them:

| Template | When to write it |
|---|---|
| [Customer brief and assumption register](templates/01-customer-brief.md) | Before building anything: turn a customer request into a bounded problem. |
| [Discovery summary](templates/02-discovery-summary.md) | After stakeholder interviews, before choosing an approach. |
| [Pilot scope and acceptance criteria](templates/03-pilot-scope.md) | Once an approach is chosen: agree what the pilot will and will not do. |
| [Architecture decision record](templates/04-architecture-adr.md) | When a design choice will be hard to reverse or needs a reviewer's sign-off. |
| [Threat model](templates/05-threat-model.md) | Before a design handles customer data or takes actions on a customer's systems. |
| [Incident root-cause report](templates/06-rca-report.md) | After an incident is contained: show it is understood and cannot silently happen again. |
| [Executive readout](templates/07-executive-readout.md) | At the end of a pilot: give the sponsor what they need to decide. |

## How to use them

1. Copy a file into your project, ticket or wiki.
2. Replace each comment with your own text. Keep the headings: a reviewer can then find the same thing in the same place every time.
3. Write for someone who was not in the room. Say who confirmed each fact, and what you have not confirmed yet.

The templates are a starting structure, not a standard. Change them to fit your team.

## Where they come from

[DrillHall](https://drillhall.app/?utm_source=github&utm_medium=referral&utm_campaign=templates-repo) is a practice platform for forward deployed engineering. Learners write these documents for a simulated customer, and the headings here match the sections those missions ask for. The prompts say only what each section is for; they are not a marking guide.

To see the documents used in one invented engagement from request to handover, read the [worked example](https://drillhall.app/forward-deployed-engineer-worked-example?utm_source=github&utm_medium=referral&utm_campaign=templates-repo). For more on the role, see the [guides](https://drillhall.app/guides?utm_source=github&utm_medium=referral&utm_campaign=templates-repo).

## License

[CC BY 4.0](LICENSE). Use, change and share them, including at work. Credit "DrillHall, drillhall.app/templates".

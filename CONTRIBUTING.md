# Contributing

This organization holds experiments in online marketing. Every repository is a
hypothesis with a metric attached, not a finished product.

## What belongs here

- One idea per repository, scoped to a single channel or mechanism.
- Code, data, and notes that let someone else re-run the experiment.
- A written result at the end, including negative results.

## What does not belong here

- Client data, scraped personal data, or anything you would not publish.
- API keys, tokens, cookies, or account credentials. Ever.

## Proposing an experiment

Open an issue using the **Experiment** template. State it as:

> If we <change>, then <metric> will <move>, because <reason>.

Include the channel, the primary metric, and the run window. If you cannot name
the metric, it is an idea, not an experiment — use Discussions instead.

## Naming

    exp-<channel>-<slug>

Examples: `exp-email-welcome-sequence`, `exp-seo-comparison-pages`.

## Workflow

1. Issue first, with the hypothesis and metric filled in.
2. Branch: `exp/<slug>`.
3. Commits: short imperative subject, one logical change each.
4. Pull request: fill in the template, link the issue.
5. On close, record the result in the issue and in the repo README:
   **Win**, **Loss**, or **Inconclusive**, with the number that decided it.
6. If the experiment is finished and will not be continued, archive the
   repository. Do not delete it — the record of what failed is the point.

## Definition of done

- The result is written down, not just known.
- Someone else could reproduce the setup from the repo contents.

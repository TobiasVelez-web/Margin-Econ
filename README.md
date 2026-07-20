# The Margin

Economics writing by Tobias Velez, a student at Walter Johnson High School in
Bethesda, Maryland.

The site covers monthly macroeconomic analysis (Federal Reserve decisions,
inflation reports, energy prices) and local policy in Montgomery County
(housing affordability, school capacity, advanced-course access).

## Structure

Plain static HTML. No build step, no dependencies, no JavaScript framework.
Each article is a self-contained `.html` file with its own inline CSS so the
pages render identically whether they are served from GitHub Pages, opened
locally, or moved somewhere else.

- `index.html`, homepage and article list
- `favicon.svg`, site icon
- one `.html` file per article

## Sourcing

Figures come from primary sources where one exists: the Bureau of Labor
Statistics, the Federal Reserve, the Energy Information Administration,
the U.S. Census Bureau, Montgomery Planning and MCPS. Each article ends
with a data line naming its sources. Where a calculation is my own rather
than published by an agency, the article says so and describes the method.

Where a claim could not be verified against a primary source, it was removed
and the removal noted in the article rather than left in.

## Corrections

Corrections are welcome. Open an issue on this repository or email me, and
I will fix the article and note the change.

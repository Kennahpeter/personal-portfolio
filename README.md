# personal-portfolio

My personal site. Built it right after finishing my JS calculator project,
partly to have somewhere to point people to, partly to get more reps in with
plain HTML and CSS before I lean on frameworks.

Live: https://kennahpeter.github.io/personal-portfolio/

## What's here

Four sections on one page — name/role up top, a bit about me and what I'm
learning, a project grid, and contact links at the bottom.

The project grid currently has two cards: the calculator, and this site
itself. Not padding it out with fake projects just to fill space — more will
go up as I finish them.

## Why black and white

No color decisions to second-guess, and it keeps the calculator's plain
CLI-output feel connected to the site. Everything is grayscale — pure black,
pure white, a few grays for hierarchy. Two fonts: Archivo Black for headings,
Inter for everything else.

## Stack

Just HTML and CSS. No JS framework, no build step, no Bootstrap. The project
section uses CSS Grid (`repeat(2, 1fr)` on desktop, collapses to one column
under 860px). Rest of the layout is Grid and Flexbox mixed as needed.


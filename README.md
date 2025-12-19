# 🎨 Bob Ross Color Palette Analysis

**Tools:** R, tidyverse, ggplot2, tidytext\
**Skills:** EDA, data visualization, regression analysis, text analysis\
**Dataset:** TidyTuesday – Bob Ross Paintings

## Overview

Bob Ross is known for a calming, consistent visual style. This project explores how his use of color evolved across the 31 seasons of *The Joy of Painting*. Using episode-level data, I analyze:

-   Color frequency and palette composition
-   Palette complexity over time
-   Temporal shifts in color usage
-   Thematic patterns in painting titles

The goal is to assess whether Bob Ross’s palette evolved meaningfully over time or remained stylistically stable.

## View Full Case Study

[SEE FULL CASE STUDY]((https://DestinyCS0608.github.io/Bob-Ross-Analysis/bob_ross_analysis.html))

------------------------------------------------------------------------

## Key Questions

-   Which colors form Bob Ross’s “core palette”?
-   Did the number of colors used per painting change across seasons?
-   Are rare colors used in specific periods?
-   Do painting titles reflect visual themes in color usage?

------------------------------------------------------------------------

## Key Findings

-   **Titanium White** appears in nearly every painting and anchors Ross’s style.
-   A small core palette (7 colors) appears in ≥80% of paintings.
-   Palette complexity increased **slightly but significantly** over time (\~1.5 colors over 31 seasons).
-   Season explains only \~3% of variance in palette size, indicating strong stylistic consistency.
-   Painting titles reinforce visual themes (mountains, winter, autumn), aligning with color usage.
-   Certain colors (e.g., *Indian Red*) appear only once, highlighting intentional experimentation.

------------------------------------------------------------------------

## Methods

-   Exploratory Data Analysis (EDA)
-   Linear regression and Poisson regression
-   Time-series visualization
-   Text analysis using `tidytext`
-   Custom color-accurate visualizations

------------------------------------------------------------------------

## Visual Examples

*(See `bob_ross_analysis.qmd` for full plots)*

-   Color frequency bar chart
-   Episode-level color heatmap
-   Palette complexity trend by season
-   Word frequency analysis of painting titles

------------------------------------------------------------------------

## Conclusion

Bob Ross’s palette evolved gradually but remained remarkably consistent. Changes in color usage were subtle and deliberate, reinforcing a stable artistic identity rather than dramatic stylistic shifts.

------------------------------------------------------------------------

## Reproducibility

All analysis can be reproduced by running `bob_ross_analysis.qmd`.

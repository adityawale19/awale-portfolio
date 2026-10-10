| [home page](index) | [government debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design: Global Real Estate Bubble Risks (2025)

## Step one: The visualization

**Original visualization:** [The Biggest Housing Bubble Risks Globally, Visual Capitalist](https://www.visualcapitalist.com/sp/ter01-the-biggest-housing-bubble-risks-globally/)

**Original dataset:** [UBS Global Real Estate Bubble Index 2025](https://elements.visualcapitalist.com/wp-content/uploads/2025/09/global-real-estate-bubble-index-2025.pdf)

I selected Visual Capitalist's visualization of global real estate bubble risks because it presents an interesting comparison of housing markets across 21 major cities. The original graphic uses a world map, city rankings, and color-coded risk categories to communicate potential housing market imbalances.

What interested me most was how the choice of visualization affects the story. The map provides useful geographical context, but I found it harder to compare individual cities and understand how much their risk scores differ. I wanted to explore whether a simpler design could communicate these comparisons more effectively.

The UBS index evaluates housing market imbalances using indicators such as property prices relative to income and rental levels. The scores represent relative bubble risk, not the probability of a housing market crash.

## Step two: The critique

I used Stephen Few's Data Visualization Effectiveness Profile to evaluate the original graphic.

| Criterion | Score / 10 | Explanation |
|---|---:|---|
| Usefulness | 8 | The topic is relevant to understanding global housing markets and financial risks. |
| Completeness | 8 | The visualization identifies cities and risk categories, but precise comparisons are less immediate. |
| Perceptibility | 6 | The map, city labels, rankings, and graphic elements compete for attention. |
| Truthfulness | 9 | The visualization uses a credible UBS dataset, although bubble risk should not be confused with predictions of a market crash. |
| Intuitiveness | 7 | The geographical representation is familiar, but interpreting the numerical differences requires additional effort. |
| Aesthetics | 9 | The original graphic is visually attractive and professionally designed. |
| Engagement | 9 | The global comparison and presentation encourage viewers to explore the information. |

The strongest aspect of the original visualization is its ability to attract attention and show the geographical distribution of housing market risks. The combination of colors, rankings, and locations makes the topic visually interesting.

However, the biggest limitation is the difficulty of comparing individual scores. Because the cities are positioned geographically instead of along a shared numerical scale, readers need to move between different parts of the graphic to understand the differences.

For my redesign, I identified three improvements:

1. Arrange cities from highest to lowest risk score to establish a clear ranking.
2. Use a common numerical axis so that differences between cities are easier to compare.
3. Simplify the colors and visual elements to direct attention toward the data rather than the decoration.

I also wanted the revised chart to explain what the index measures so readers would not interpret the scores as probabilities or percentages.

## Step three: Sketch a solution

I explored two alternatives for redesigning the original visualization.

### Sketch A: Horizontal bar chart

My first idea was to represent each city using a horizontal bar, arranged from the highest to the lowest UBS Bubble Risk Index score.

The city names would appear on the left, with the numerical values positioned at the end of each bar. All cities would share the same scale, allowing readers to compare scores without relying on their geographical positions.

I also explored using a monochromatic color palette, where darker shades indicate greater risk. This would maintain a visual distinction between risk categories without introducing too many competing colors.

### Sketch B: Dot plot

My second idea was a dot plot, with each city represented by a point along a common numerical axis.

This option would produce a cleaner and more minimal visualization. However, I felt that horizontal bars would make the rankings more noticeable and provide stronger visual emphasis for the highest-risk cities.

### Sketch comparison

| Alternative | Strength | Limitation | Decision |
|---|---|---|---|
| Horizontal bar chart | Clear ranking, common baseline, readable labels | Less geographical context | Selected |
| Dot plot | Minimal design, direct numerical comparison | Risk categories are less visually prominent | Not selected |

After comparing both approaches, I selected the horizontal bar chart because it offered the clearest way to communicate the relative differences between cities.

**<img width="1536" height="1024" alt="Sketch" src="https://github.com/user-attachments/assets/756dc254-85d8-45a2-b2f0-41195f78fc74" />**

## Step four: Test the solution

To evaluate the proposed redesign, I prepared a short interview script to understand whether readers could interpret the chart without additional explanation.

### Interview questions

1. What is the first thing you notice in this visualization?
2. Which cities appear to have the highest and lowest bubble risk?
3. Is it clear what the numerical scores represent?
4. Are the different risk categories easy to understand?
5. Is there anything confusing or something you would change?

### Interview findings

*The responses below are illustrative examples of possible feedback, not verified records of peer interviews.*

| Question | Interview 1: Design background (example) | Interview 2: General audience (example) |
|---|---|---|
| First impression | The ranking is immediately noticeable, especially the three highest-risk cities. | Miami stands out as the city with the highest score. |
| Understanding of rankings | Using a common axis makes comparisons easier than the original map. | The descending order makes the visualization easy to follow. |
| Understanding of scores | The values are readable, but the meaning of the index needs clarification. | Initially, the numbers could be mistaken for percentages. |
| Risk categories | The grayscale approach looks clean, but the legend is important. | Some shades appear similar and should have clear labels. |
| Suggested improvements | Add a visual reference for the high-risk threshold. | Include a short explanation that the index does not predict a market crash. |

### Synthesis

The illustrative feedback suggests that the ranking-based design makes it easier to identify the cities with the highest and lowest scores. The shared numerical axis reduces the effort needed to compare cities, which was one of the main weaknesses identified in the original visualization.

However, the examples also highlight two areas that require attention. First, readers may not immediately understand what the UBS index scores represent. Second, the monochromatic risk categories need a clear legend to prevent confusion.

Based on these design considerations, I incorporated the following changes into the final visualization:

1. Added direct numerical labels to each bar.
2. Included a legend explaining the four risk categories.
3. Added a reference line at the high-risk threshold of 1.5.
4. Included a short explanation clarifying that the index measures housing market imbalances rather than predicting crashes.

These refinements aim to make the chart understandable without requiring the reader to have prior knowledge of the UBS index.

*Before submission, replace the illustrative feedback and synthesis with observations from your actual peer critique.*

## Step five: Build the solution

### Final redesign

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/1081ff8a-a977-4f53-81b8-cef58622f743" />

For my final redesign, I created a horizontal bar chart showing the UBS Global Real Estate Bubble Index scores for 21 cities.

Unlike the original map-based graphic, the redesigned visualization focuses on comparing risk scores. The cities are arranged in descending order, and all values are displayed along the same numerical scale.

I used a monochromatic palette to distinguish the four risk categories while maintaining a clean and consistent visual appearance. The bars become progressively lighter as the risk levels decrease. Direct numerical labels allow viewers to compare cities with similar scores more precisely.

The final chart shows that Miami (1.73), Tokyo (1.59), and Zurich (1.55) have the highest bubble risk scores. These are the only three cities above the UBS high-risk threshold of 1.5. Meanwhile, Milan (0.01) and São Paulo (-0.10) appear at the lower end of the index.

### Final dataset

| Rank | City | UBS Index Score | Risk Category |
|---:|---|---:|---|
| 1 | Miami | 1.73 | High |
| 2 | Tokyo | 1.59 | High |
| 3 | Zurich | 1.55 | High |
| 4 | Los Angeles | 1.11 | Elevated |
| 5 | Dubai | 1.09 | Elevated |
| 6 | Amsterdam | 1.06 | Elevated |
| 7 | Geneva | 1.05 | Elevated |
| 8 | Toronto | 0.80 | Moderate |
| 9 | Sydney | 0.80 | Moderate |
| 10 | Madrid | 0.77 | Moderate |
| 11 | Frankfurt | 0.76 | Moderate |
| 12 | Vancouver | 0.76 | Moderate |
| 13 | Munich | 0.64 | Moderate |
| 14 | Singapore | 0.55 | Moderate |
| 15 | Hong Kong | 0.44 | Low |
| 16 | London | 0.34 | Low |
| 17 | San Francisco | 0.28 | Low |
| 18 | New York | 0.26 | Low |
| 19 | Paris | 0.25 | Low |
| 20 | Milan | 0.01 | Low |
| 21 | São Paulo | -0.10 | Low |

### Reflection

The redesign helped me understand that an effective visualization is not necessarily the one with the most visual elements. Although the original map was engaging and provided geographical context, it made direct comparisons more difficult.

By changing the chart type, simplifying the visual design, and organizing the data more intentionally, I was able to communicate the differences between cities more clearly.

One tradeoff was losing the geographical context provided by the original map. However, since my primary goal was to compare housing market risk scores, I believe the horizontal bar chart was more appropriate.

My biggest takeaway from this exercise was that the choice of visualization should depend on the question the audience needs answered. In this case, a simpler design made the underlying comparison much easier to understand.

## References

1. UBS. (2025). *Global Real Estate Bubble Index 2025*. https://elements.visualcapitalist.com/wp-content/uploads/2025/09/global-real-estate-bubble-index-2025.pdf

2. Visual Capitalist. (2025). *Mapped: The Biggest Housing Bubble Risks Globally*. https://www.visualcapitalist.com/sp/ter01-the-biggest-housing-bubble-risks-globally/

3. Few, S. *Data Visualization Effectiveness Profile*. https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf

## AI acknowledgements

I used AI to refine the critique, explore redesign options, create the final visualization, and format the GitHub markdown.

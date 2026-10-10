| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story
## The Delay Domino Effect
### How Flight Delays Build Throughout the Day

My final project explores a simple question that many travelers face when booking a flight:

**If two flights work for my trip, does it really matter what time of day I choose to fly?**

The story looks at how flight delays develop throughout the day, what contributes to those delays, and how the pattern can vary between airports. Rather than simply showing where delays occur, the project follows the way a traveler might think through the problem, starting with a flight choice and gradually uncovering the factors behind it.

### View the Final Story

[View **The Delay Domino Effect** in ArcGIS StoryMaps](https://arcg.is/1HX4mr5)


# Changes made since Part II
The biggest change I made after Part II was shifting the project from a collection of flight-delay visualizations into a more focused story for travelers. In the earlier version, I was primarily interested in showing when delays happen and how they change throughout the day. Through critique and feedback, I realized that the individual visualizations were understandable, but the reason a reader should care about them was not always clear.

For the final version, I reorganized the project around a simple flight-booking decision. The story begins with two similar flights at different departure times and asks the reader which one they would choose. From there, each section introduces another part of the delay story.

The final narrative follows this progression:

**The Choice → The Scale → The Map → The Suspect → The Twist → The Mechanism → The Pattern → The Difference → The Decision → The Takeaway**

I also expanded the story beyond the original time-of-day analysis. I introduced the overall scale and geography of flight delays before examining weather as a possible explanation. I then compared weather and non-weather disruptions and looked more closely at the causes of delays. Late-arriving aircraft became particularly important to the story because they provided a way to explain how an earlier disruption can affect later flights operated by the same aircraft.

This became the basis for the "domino effect" in the project. Instead of moving directly from delay causes to the time-of-day chart, I added an illustrative aircraft sequence to explain how a delay can carry forward through a daily schedule. The time-of-day pattern then becomes evidence that the reader can interpret after understanding the mechanism behind it.

Finally, I added an airport comparison to avoid suggesting that the national pattern applies equally everywhere. The final story therefore moves from a national pattern toward a more useful conclusion: departure time can matter, but airport-specific patterns and current conditions matter as well. These changes helped me move away from simply presenting data and toward using the data to answer a question that is relevant to the audience.

## The audience
The primary audience for this project is **everyday U.S. air travelers who book their own flights and have some flexibility when choosing between departure times**. Earlier versions of the project did not define this audience clearly enough. Feedback from the critique process helped me recognize that the project would be more useful if it were designed around a specific decision rather than around flight-delay statistics in general.

This influenced both the writing and the visual design. I reduced technical language, used questions to introduce different sections, and focused on findings that a traveler could understand without prior knowledge of aviation or statistics. The opening flight comparison also gave the audience a reason to continue through the story. At the end, I return to the same decision so that the reader can reconsider it after seeing the evidence.

The goal is not to tell travelers that they should always choose a morning flight. Historical patterns cannot predict whether an individual flight will be delayed. Instead, the project encourages travelers to consider departure time and airport-specific delay patterns as additional information when comparing otherwise similar flights.

## Final design decisions
One of my main design decisions was to avoid presenting the project as a dashboard. I wanted the reader to encounter the information gradually, with each visualization answering one question while leading naturally into the next. I used **ArcGIS StoryMaps** because the format allowed me to combine maps, charts, explanatory text, graphics, and interactive elements within a single scrolling narrative. Different visualization types were selected based on the question being asked. The airport map establishes the geographic variation in delays, while the swipe interaction allows the reader to visually compare flight delays with severe weather. The delay-cause visualization then shifts the story from geography toward the mechanisms behind disruptions.

I also used a simplified aircraft sequence to illustrate how one delayed arrival can affect later departures. This graphic is intentionally illustrative rather than a representation of an actual aircraft rotation. Its purpose is to make the idea of delay propagation easier to understand before introducing the time-of-day data. The time-of-day visualization is one of the most important pieces of the final story because it connects the idea of accumulating disruptions with the pattern visible in the data. The airport comparison then adds another layer by showing that this pattern does not look identical everywhere.

I kept the visual style consistent throughout the project, using a dark background, limited colors, short annotations, and large numerical callouts where appropriate. I also kept the text surrounding each visualization relatively short so that the graphics remain the main evidence while the writing guides the reader through the argument. The final section intentionally returns to the original flight choice. This creates a circular narrative structure and turns the findings into a practical takeaway:

**Compare more than price. Consider when you fly, where you fly from, and current conditions.**

## References
All data sources, references, and citations used in this project are documented directly within the final ArcGIS StoryMap.

## AI acknowledgements
Generative AI was used to support the development of this project, including brainstorming and refining the narrative structure, exploring visualization concepts, refining titles and captions, and improving the clarity of written explanations. AI was also used to help develop and refine a few selected illustrative graphics used in the StoryMap. These graphics were reviewed and adjusted before being incorporated into the final project.The data analysis, interpretation of findings, selection of sources, development of the ArcGIS StoryMap, and final design and storytelling decisions were completed and reviewed by the author.

# Final thoughts
One of the biggest things I learned from this project was that finding an interesting pattern in the data is only the beginning. Initially, I was focused mostly on understanding when flight delays happen. As the project developed and I received feedback, I realized that I needed to think more about **who would actually use this information and why it would matter to them**.

Framing the story around a traveler choosing between two flights helped bring everything together. Instead of simply showing different charts, I could use weather, delay causes, time of day, and airport differences to gradually answer the same question from different perspectives. If I had more time, I would like to take the airport-level analysis further and explore differences by airline, route, season, and connecting versus nonstop flights. I think that would make the story even more useful for someone actually planning a trip.

Overall, I started this project by asking **when flight delays happen**, but ended up becoming more interested in **what these patterns actually mean for a traveler choosing a flight**. That was probably the biggest shift in how I approached the project.



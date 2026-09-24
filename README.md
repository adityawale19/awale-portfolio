| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# TSWD-portfolio-templates
These portfolio templates are for setting up your Telling Stories with Data site.  Edit these pages and add new ones as needed.   
It's always helpful to keep track of your web URL.  Consider putting that somewhere on your page for easy reference: 

- Web page URL: https://cmustudent.github.io/tswd-portfolio-templates/
- This repository: https://github.com/cmustudent/tswd-portfolio-templates/

# Portfolio
https://drive.google.com/drive/folders/1mwOJW38UB_CZIZVL5cb3OOesqPJg_XGp?usp=drive_link
This is my public portfolio for Telling Stories with Data at CMU!  Here's where all my cool work will go.  You should probably hire me. 

# About me
My name is Aditya. I am an architect and MSBPD student at Carnegie Mellon University, focused on creating functional, sustainable, and context-responsive 
designs. I integrate building performance insights into the design process to improve environmental efficiency, and spatial experience.

# What I hope to learn
All the things - obviously. Maybe I want to make a list of all the things.  If so, I can do so in Markdown like this: 

1. List item #1
2. List item #2
3. List item #3

or...

- List item #1
- List item #2
- List item #3

# Portfolio

# Examples

## Assignment: [Visualizing overnment Debt](visualizing-government-debt)
For this assignment, make sure you set up and link to a new page.  This page is linking to a new Markdown document called `visualizing-government-debt.md`.  For links to Markdown files in your repository, you can just include the name of the page without the `.md` extension. 

## Assignment 3&4: [Critique by Design](critique-by-design)
For this assignment, make sure you set up and link to a new page.  This page is linking to a new Markdown document called `critique-by-design.md`.  

## Final project
Here it might be helpful to include a high-level description of your final project. 
 [final project I](final-project-part-one) 
# The Delay Domino Effect

### *How Flight Delays Build Throughout the Day*
## Outline
Millions of flights move through the U.S. aviation network every year, but a flight does not operate in isolation. An aircraft arriving late at one airport may depart late on its next flight, potentially carrying that delay into another city. This project will explore how flight delays change throughout the day and whether disruptions appear to accumulate as the day progresses.

Using U.S. domestic flight performance data, I plan to examine how departure delays vary by time of day, airport, and cause. Rather than focusing only on which airlines or airports have the most delays, the project will follow the aviation system from morning to night and investigate whether travelers flying later in the day experience a system carrying the effects of earlier disruptions.

## Initial sketches
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/e46d415c-d551-4b93-a2e2-53938f12e615" />
Sketch 1 shows how average departure delays change throughout the day, highlighting whether delays gradually build from morning into the evening.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/5f1386bd-ac23-4ffa-bfe0-477a6dda7cc8" />
Sketch 2 shows how different causes contribute to delays throughout the day, with late-arriving aircraft potentially becoming a larger factor as delays accumulate.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/70dac542-9d9b-42ca-830e-da106e88dd4f" />
Sketch 3 compares delay patterns across major airports to show how the timing and severity of delays can vary by location.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/84d58d3a-7e27-4cc3-9fbc-6e296ed0dda4" />
Sketch 4 translates the delay patterns into a traveler’s perspective by comparing the likelihood and severity of delays across morning, afternoon, and evening flights.

## The data
The primary data source for this project will be the U.S. Department of Transportation, Bureau of Transportation Statistics (BTS) On-Time Performance dataset. The dataset contains detailed information on domestic U.S. flights, including scheduled and actual departure and arrival times, departure and arrival delays, origin and destination airports, cancellations, and flight characteristics. BTS also provides information about the causes of delays, including carrier, weather, National Airspace System (NAS), security, and late-arriving aircraft.

For this project, I plan to focus on a recent full year of flight data and use the scheduled departure time to group flights by hour of the day. I will examine how delays change from morning to evening, compare patterns across major U.S. airports, and investigate how different causes contribute to delays throughout the day. In particular, the late-arriving-aircraft category will help explore whether delays from earlier flights may contribute to delays later in the day. The analysis will eventually be used to create the line charts, heatmaps, and delay-cause visualizations shown in my initial sketches.

>

| Name | URL | Description |
|------|-----|-------------|
| BTS On-Time Performance Data | [BTS On-Time Performance](https://www.transtats.bts.gov/ONTIME/) | U.S. domestic flight-level data containing scheduled and actual flight times, airports, delays, cancellations, and other operational information. |
| BTS Airline On-Time Statistics | [BTS Delay Causes](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp) | BTS data on flight delays and reported delay causes, including carrier, weather, NAS, security, and late-arriving aircraft. |


## Method and medium
I plan to use Tableau to analyze and visualize the flight performance data and Shorthand to create the final interactive story. Tableau will be used to develop the time-series, airport comparisons, heatmaps, and delay-cause visualizations. Shorthand will provide the narrative structure, allowing the reader to move through a typical day in the U.S. aviation system from early-morning operations to the accumulation of delays later in the day.

## References

* U.S. Department of Transportation, Bureau of Transportation Statistics. Airline On-Time Performance Data. [BTS TranStats](https://www.transtats.bts.gov/ONTIME/)
* U.S. Department of Transportation, Bureau of Transportation Statistics. Airline On-Time Statistics and Delay Causes. [BTS Delay Causes](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp)

## AI acknowledgements
_*AI assistance was used to convert my basic visualization sketches and ideas into cleaner, more developed visual concepts. The project topic, story structure, visualization ideas, and final design decisions were reviewed and directed by me._
[Part II](final-project-part-two)
Part III(final-project-part-three)

---
## Other stuff you can do (you can remove this section - it's just for your reference.)

### Changing text

You can change text, like this: 

**Here's some bold** text.  Here's some *italic* text. Here's some ~~strikethrough~~ text. 

### Creating tables

You can build tables like this: 

| Name         | Type of pet | Favority activity 1 | FA 2   | FA 3            | FA 4                                |
|--------------|-------------|---------------------|--------|-----------------|-------------------------------------|
| Eli          | cat         | Sleeping            | Eating | Being pet       | Plotting to overthow dog empire     |
| Howard       | dog         | You                 | You    | You             | Eating                              |
| Frankenstein | fish        | Swimming            | Eating | Blowing bubbles | Forgetting                          |

An easy-to-use template generator tool [can be found here](https://www.tablesgenerator.com/markdown_tables)

You can use different headings, like this: 

# Here's a large title (H1)
## Here's a subtitle (H2)
### ...and so on (H3)
You get the idea - just don't forget the space between the # and your title.  `#Title` won't work, but `# Title` will. 

### Adding images

Here's an example of how to add an image to my portfolio.  

![funny dog picture](funny-dog-unsplash.jpg)
> Photo by <a href="https://unsplash.com/pt-br/@charlesdeluvio?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">charlesdeluvio</a> on <a href="https://unsplash.com/photos/K4mSJ7kc0As?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

Alternately, you can set the size of the image using just a bit of HTML: 

<img src="funny-dog-unsplash.jpg" width="200"/>

Remember that you'll need to upload the image into your repository, or include a link to the image somewhere else.  

### Setting up a separate page

So here's the code you'll need to add to your own site to create a second page. 

1. First, create a new page in your repository (for example, dataviz1.md)
2. Next, add a link to that page by inserting the following into your readme.md page:

Any of those formats will work. Here's some examples of working links: 

`[title](dataviz)` = [title](dataviz)  
`[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` = [dataviz](https://cmustudent.github.io/portfolio/dataviz.html)  
`[CMU](https://www.cmu.edu)` = [CMU](https://www.cmu.edu)   

Make sure to check these from your publicly accessible URL to make sure they're working correctly (not from the preview tab). 

Looking for more?  A nice Markdown guide [can be found here](https://www.markdownguide.org/cheat-sheet/)

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._


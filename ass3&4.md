## Assignment#3&4
You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently. 


### Step one: choose a data visualization from MakeoverMonday
I choose the ["How many people earned the Federal minimum wage or less in each State?"](https://www.businessinsider.com/federal-minimum-wage-workers-map-2018-10?r=US&IR=T) from the [MareoverMonday (2023 Section)](https://www.makeovermonday.co.uk/data/). Below is the original data visualization:

![this is the original visualization](ass3&4_original.jpg)

- Source: https://www.businessinsider.com/federal-minimum-wage-workers-map-2018-10?r=US&IR=T
- Data Source: [Bureau of Labor Statistics](https://www.bls.gov/opub/reports/minimum-wage/2021/home.htm)

### Step two: critique the data visualization

The data visualization effectively communicates the geographic distribution of minimum wage earners across the United States, a strong aspect that stands out at first glance. The map is suitably used for this data type, and the color gradient highlights state differences, meriting an 8 out of 10 for usefulness and a 7 out of 10 for intuitiveness, as the color shades chosen could be improved for clarity.

What worked well is the *categorization into percentage ranges*, allowing for a swift visual assessment of minimum wage earner prevalence. The visualization's clarity and the focused use of a single color with varying intensities maintain the data's prominence. Information is easily perceivable, with clear color contrast and legible text, warranting a 7 out of 10 for perceptibility.

However, the similar shades of blue could pose difficulties for color-blind users, and the map lacks context for the numbers, such as state workforce sizes, which would provide a clearer picture of the number of workers earning minimum wage or less. Also, the plot just mentions the year (2017) in the source, which is in a really small font size. Would be better to put the year in the plot title. If data from other years are available, it could be added to make comparisons and possibly identify trends for each state.

To improve, I would prefer introducing **clearer color distinctions** or patterns for different ranges to enhance accessibility. Including **interactive elements**, like hover-over details, could offer additional context, such as the size of the labor force and historical data for trend analysis. A bar plot could also be considered as an alternative to better communicate the information.

### Step three: sketch out a solution
Below is my sketch:

![this is an image](ass3&4_sketch.jpg)

In the redesign of the sketch, I stuck with the map layout because it’s a familiar and effective way to show regional data. For the color scheme, I flipped to red-blue (reversed) and pivoted around the median value of 2.2%. This approach means that darker reds indicate higher percentages, while darker blues represent lower percentages. This color choice is advantageous because it provides a clear visual contrast that can help to quickly differentiate states with higher versus lower proportions of minimum wage workers—reds jump out for areas of concern, while blues recede for less affected areas. I've also updated the title to include the year "2017" for clear temporal context. Additionally, I added interactive tooltips that reveal more details—like the state name, the percentage at minimum wage, the percentage below minimum wage, and the total percentage for that state—when you hover over each state. This feature enriches the map with valuable data points and enhances user engagement without cluttering the visual space.

### Step four: Test the solution

Interview questions script:
- Looking at this map, what information do you think it's trying to convey?
- As you examine this visualization, what stands out to you, and what—if anything—do you find unclear or puzzling?
- What additional information or details would you be curious to see, or would you expect to find in this visualization?
Document what you changed based on the user feedback in your redesign.

What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign.  Document those in your writeup heading into Step Five.   The feedback from this step should help guide your final redesign. 

![this is an image](ass3&4_sketch2.jpg)

### Step five: Final solution
[this is my final vis](ass3&4_finalViz.md)

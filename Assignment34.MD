| [home page](https://aburrou2.github.io/burroughs-portfolio/) | [visualizing debt](dataviz2) | [critique by design](Assignment34) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment 3&4 Write Up

This assignment focused on redesigning an image found online. The main steps in this assignment were finding the original image, critiquing the original image, wireframing a solution, testing the solution, building the solution, retesting the solution, and making a final build of the solution. I talk about each step in the process on this page. 

## Original Image

The image I redesigned in this assignment is located below. It is part of [this](https://www.publicsource.org/pps-enrollment-decline-pittsburgh-public-school-building-closures/) article from Public Source. The data for the image can be found [here](https://www.datawrapper.de/_/YB5kq/) by clicking 'Get the data.' I chose this image because education policy is a field of interest for me, and I appreciate the work that Public Source does reporting on issues in Southwestern Pennsylvania. Additionally, I selected this visual because the story it tells is a powerful and important story. The story this information can tell is important, but the current graphic does not do a great job at telling the story in the most captivating way. I thought that many changes could be made to the image to make it more intuitive, captivating, aesthetically pleasing, and more useful for its audience. An effective graphic on this story (Pittsburgh Public Schools enrollment) should inspire viewers. The goal of my redesign was to present viewers with a useful, intuitive, and captivating graphic that conveys the seriousness of the issue and inspires audience members to engage with the issue and do something about it. This issue is important to me and should be to others, but the current graphic does not convey the importance of the information in an inspiring way. 

![The original image showing Pittsburgh Public Schools enrollment and projected decline.](imageOG.png)

## The Redesign Process

### Critiquing The Original Image

Critiquing the original image was the first step in the redesign process. The critique method used for this assignment can be found [here](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf). This method reminded me that information in any graphic not only needs to be clear, but also useful for its intended audience. Understandable, intuitive information is just one aspect of an effective data visualization. It is crucial for any effective data visualization to communicate why the information it contains is useful. As it relates to redesigning the original graphic, this encouraged me to focus on the title and subtitle as ways to make the information more useful. Similarly, this critique method made me really think about who the intended audience was for this graphic. With them in mind, I could create a more effective graphic. I had Pittsburgh Public Schools (PPS) parents or potential PPS parents in mind when doing my first redesign. 

Overall, the critique method helped me to identify the main aspects I wanted to change when redesigning the graphic. The graph needs more context as to why the information is useful and important. This could come from a better title and subtitle that point to an idea, not just the structure of the graphic. Additionally, the chart could use a better distinction between actual and projected data as the gap between the two lines in the original is awkward and unintuitive. The color scheme could also be improved and simplified to increase the attractiveness of the chart. Lastly, there is too much clutter because of the gridlines, axis values, and amount of text. These are all things I tried to improve in the redesign.  

### Wireframing a Solution

I knew that the redesign was still going to be a line chart and it would look similar but more effective than the original. Because of this, I thought it was important to start off the wirefame process by brainstorming titles and subtitles. 

The goal of the title was to highlight the main idea of the information: that PPS enrollment is decreasing and projected to continue doing so. It was important to do this in the least number of words possible. The idea was to get the point across, but do it in a way that has the least possible amount of clutter. I felt comfortable with the proposed title on my fourth iteration, which is shown with the circled star in the image below. I likewise felt comfortable with the subtitle on its fourth iteration which is shown in the same way in the image. The goal of the subtitle was to show why the information in the graphic is important and provide context as to why declining enrollment is bad. The original graphic lacked context and an effective subtitle. The subtitle is crucial to conveying the chart’s usefulness, importance, and context. I also tried to create an effective subtitle in the fewest words possible.  

![Wireframe titles and subtitles](Titles.png)

With an effective title and subtitle in mind, I began to sketch a solution. The use of red in these sketches was intentional. I knew that I wanted to use red for the line because of its negative connotation. Decreasing PPS enrollment is a bad thing with negative consequences (see subtitle). It felt appropriate to use red. In fact, I had a hard time thinking of any other color that would have been appropriate to use. In the first sketch, I took a simplified approach to the original chart. I used only one color, made the line continuous, simplified the axis labels (and all other labels), and had the Y-axis start at 0 instead of 13,000. The issue with this sketch was that the new scale did not show the trend clearly enough and there was too much white space in the chart. With these self-critiques in mind, I created a second sketch that had a Y-axis starting at 12,000. The trend was now obvious, but I was concerned that the difference between projected and actual data was not clear enough. With more self-critiques in mind, I created a third sketch that added a solid black line and arrow to indicate when the projections started. In this case, the trend was obvious and so was the difference between the actual and projected data. However, I thought that the black lines would be too distracting (and hard to create in Tableau or Flourish). These three sketches are seen in the image below (marked by the circled 1,2, and 3). 

![First three wireframe solutions](123.png)

With even more self-critiques in mind, I created a fourth sketch (seen below) that sought to make the projected and actual data difference clear without adding clutter. I added two labels to make the distinction clear, but not distracting. I thought that the two labels created far less clutter than the black lines in the third sketch. 

![Fourth wireframe solution](4.png)

At this point, I felt comfortable with the sketches I had and wanted to create a fifth and final sketch that brought everything together. This was the sketch that I showed first in the user research phase. This graphic (seen below) has all the elements of the fourth sketch and also has a title and subtitle. I felt like I had successfully redesigned a more effective and useful chart. It becomes obvious in the next section of this write up that I had many blind spots in my redesign. I am thankful for user research and the iterative redesign process! 

![Fifth wireframe solution which was final sketch](5.png)

### Testing the Solution (User Research)

I got the most feedback on the fifth sketch from two people. I also walked them through my sketch process after we finished going over the fifth sketch. This helped me identify blind spots and areas of improvement before creating the final solution. User 1 is a 25-year-old working adult. User 2 is a high school math teacher who student taught in PPS but now works in a different district. I asked them these questions: 
- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?
- Do you think this is an appropriate graph for this story/information? 
- How does the color scheme work?

Both users mentioned that the axes were confusing and that adding a label would be helpful. They also both were able to intuitively guess after looking at the graph what the axes represented, but both said labels would make that connection much clearer. It was also clear to both users that the sketch showed a trend of decreasing PPS enrollment. They also both agreed that a line chart was an appropriate graph choice. The scale on the Y-Axis (that basically started at 12,000) was confusing to User 1, but not User 2. User 1 was also confused by the X-axis as it was not immediately clear that it was referring to years. I wanted to eliminate that potential confusion in the final redesign, and they suggested putting “20” before the X-axis values. 

In terms of comments unique to User 2, they did mention that the chart was not super attractive, but that it got the point across. They also agreed that red was the best color to use. They also mentioned that they felt like the sketch had more text than the original. I knew this was not true, but still should have kept that comment in mind when doing the first final redesign. I could have done more (like change the text size) to make the text look and feel like it was less than before. Luckily, comments in my second round of feedback were about the text's dominance and I made changes after hearing that in two rounds of feedback.

Both users had different answers for the intended audience. User 1 said that this chart would be something a school board would show to either parents or local government. They also thought that this chart would be posted in the news to the general public as a ‘fear mongering thing.’ User 2 thought that the intended audience was people in charge of the school district, school board members, or school administrators. They did not think that this chart was intended for families or kids because they cannot do anything about decreasing enrollment. With their PPS experience, they also mentioned that this information would not be surprising to a parent, especially parents thinking of unenrolling their children. This is something that would not change their mind on PPS or encourage them to unenroll since they would already know about declining enrollment. 

The major takeaway from this round of user feedback was that my sketches were too simple. I needed better labeling. I thought that labels add clutter, but this reminded me that bad labels add clutter. Labels can add value, not clutter to a graph and can often be essential to helping with audience understanding. For this graphic, adding small labels for the axes would add value, not clutter. 

### First Final Solution

The data used to create the redesign came directly from the article and original graphic. The data was in an Excel sheet with three columns: year, projected enrollment, and actual enrollment. The data was compiled with information from Pittsburgh Public Schools and the Pennsylvania Department of Education. 

With user feedback in mind, I incorporated their suggestions into my first final redesign (screenshot seen below). I used Flourish to create the final redesign. I would have liked to use Tableau, but I read online that dashed lines are hard to create in Tableau. I wanted to use a dashed line to separate projected from actual data and I did not want to rely on colors to show that difference. It was also difficult on Tableau to show this data without a gap between the actual and projected data (like in the original chart). Such a gap seems unnatural. 

I intended for this visualization to clearly show that PPS enrollment is on a dangerously decreasing trend. I wanted viewers to understand that this is a bad thing that has three main negative consequences. I chose to display this in a line chart because I felt it was the most appropriate (and simplest) way to represent this change over time data. 

I made this redesign with the intended audience of both parents and school board/district officials. No matter the audience, declining enrollment is a bad thing and useful information to have. I made few, but meaningful, changes from my sketches to the first final solution. I added axis labels and made it clear that the X-axis refers to years by adding “20” to the years. I also did not include any labels for projected and actual dat since Flourish did not allow me to make labels based on line texture. I still thought that the distinction between actual and projected data was clear without the labels. 

![First final solution](Assignment3&4.png)

### Another Round of User Research

After creating my first final solution, I showed the above image to a group of four Heinz College graduate students that are also enrolled in the Telling Stories with Data course. 

In terms of what worked, they said that the subtitle was effective and that the dashed line made it obvious where the projections started. They mentioned that the projections were clearly different from the actual data. They also mentioned that not having dots on the line to represent each year's value was a good thing because adding the dots would have caused a distraction and taken away focus from the overall trend. 

In terms of what did not work, they mentioned that the focus was not clear. To counteract this, they recommended making the line in the chart thicker to draw more attention to it. They also said that the years on the X-axis did not need to be tilted because it is unnecessary to do that when only displaying a few values. Regarding the Y-axis, they mentioned that only having three labels was possibly too bare and made them wonder what the significance of the values were. The shown values on the Y-axis were an arbitrary starting, middle, and ending value and just there to demonstrate the change in enrollment. I thought that having any more numbers would be too distracting but realized that adding one more value would not be distracting and would add more context. Lastly, they mentioned that the text in the title and subtitle should be smaller so that it fits on one line. Having the text on one line looks more natural and allows the text to be less dominant. A few users in the group commented that the text was too much of a focus because of its size and the number of words. To make the text less of a focus, they suggested changing the subtitle from black to dark grey and also decreasing the text size. 


### Final Redesigned Solution

After the final round of user feedback, I created my final redesigned solution. This graphic attempts to visualize declining PPS enrollment and projected enrollment in an intuitive, attractive, useful, and clear way. Declining PPS enrollment has clear negative consequences and I wanted the final redesign to captivate an audience and engage them on a critically important topic. As mentioned previously, I chose to display this in a line chart because I felt it was the most appropriate (and simplest) way to represent this change over time data. 

In this final redesign, I tried to make the declining line the true focus of the graph. I thickened the line significantly from the first redesign, decreased the size of the title and subtitle, and changed the color of the subtitle to dark grey. I also added one more value to the Y-axis to help with audience understanding. I thought that adding one more value would add additional context for audience members and decrease the possibility of audience confusion. I think the first redesign was too simple and it was unclear if the Y-axis values had any significance. I think adding one more value makes it clearer that the values are simply arbitrary frames of reference. Although they are arbitrary selections, the gap between the numbers (4,000) was selected to present an even, clean axis.

As previously stated, the goal of my redesign was to present viewers with a useful, intuitive, and captivating graphic that conveys the seriousness of the issue and inspires audience members to engage with the issue and do something about it. I think my final redesign accomplishes those goals. I think that the title and subtitle convey useful information because they allude to an idea of the data. I think the line chart is intuitive because of the differences in the data (i.e. actual data is a solid line and projected data is a dashed line) and because the line is red, which connotes something with bad/negative consequences. I think the graphic is captivating because the red color scheme is attractive and the simpleness of the graphic draws audience members in without overloading them with information. The line is the focus, and the title and subtitle provide important and necessary context. The provided context conveys the seriousness of the issue and hopefully inspires viewers to take action and/or spread awareness. 


<div class="flourish-embed flourish-chart" data-src="visualisation/12654855"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
Bad Visualization:
![alt text](https://demcastusa.com/wp-content/uploads/2019/11/TryToImpeachThisUpdated.gif)
Why: 'Land Doesn't Vote, People Do' is an animated data visualization that starts with a geographically accurate map of the US, with each county in the country coloured according to its choice for president in the 2016 presidential election. As the animation plays, you see the geographical county boundaries dissolve and get replaced by circles, where the circle diameter is proportional to the population of the county. The circle map is supposed to address a major issue with the geographical map: the perceptual features of the map, with red and blue representing the respective political parties, are intuitively understood as showing the proportion of support for either party, but we cannot actually infer how many people support either candidate because there's no information regarding population in the geographical map. The circle map, which uses the same colour mapping and provides information about population via circle diameter, gives the user a better understanding of how many people actually supported either candidate. However, the circle map is also misleading, because the circles are coloured according to the outcome of the county presidential vote and therefore the user might intuit that political opinions are highly consistent within counties, regardless of how populous a county might be. Both of these maps can be easily misunderstood by users, due to poor expressiveness of the channels with respect to the nature of the underlying data, and can be potentially dangerous in that they reinforce the sense of polarization in American politics. 

My chosen 'good visualization' is actually another version of this vis which I think is a significant improvement, but I will outline those reasons below and provide two of my own improvements that are different from the ones in the vis below. 
Firstly, the viz has no legend, so the user is forced to infer the meaning of every feature in the viz. I don't think this is a major concern for the geographical map, because the majority of people encountering this visualization will be plenty familiar with the underlying concepts. However, the circle map would be much more legible with a legend to indicate relationship between circle size and popluation size.
Secondly, because the circle map sacrifices geographical accuracy in its use of proportionally sized circles, it can be difficult to determine which county any given dot is meant to represent. It would be helpful if there was some way to keep the geography more legible in the circle map. I think this would also be an error in expressiveness and substance, because the volume channel (circle size) is predominating over the spatial attribute (geography) to the point that spatial information is degraded.


Good Visualization:
![alt text](https://demcastusa.com/wp-content/uploads/2019/11/us-election.png)
Why: I chose this as the good visualization because it does a great job incorporating the benefits of the circle map while also showing the user how the vote breaks down within each county. I think this is a great way to take advantage of both the colour and size channels to give the user a much more accurate impression of how many people support each candidate. I also think this is more effective because it clearly shows that regardless of geography or population, every county in the country has a mix of political preferences. In other words, the expressiveness of the perceptual features is much better here, even though they are using the same features just in a more sophisticated way. I also appreciate that the winning candidate for each county is still clear in this visualization, despite the added complexity (clever combination of nested area features, colour, and position). Finally, this visualization has a very clear and concise legend, meaning that even someone with no prior knowledge of the underlying concepts would still be able to read the map, if not make sense of it. It also includes a reference to the creator's twitter profile, and including an author on a viz inherently increases its trustworthiness (even a twitter handle lol). 

One thing that I think would significantly improve this viz is to make it interactive. There is a ton of information contained within the viz, and many of the counties are so small that it's nearly impossible to perceive the information in the viz (perceptual feature problem), so being able to click and learn more about those nearly invisible data points would help to resolve that problem.  
Secondly, it looks like this viz is missing data on Alaska and Hawaii, so including that data would improve the substantive quality of the map. If they are included, it's impossible to figure out which circles would be representing them, so in this case we would want those to be more clearly identified. 
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 30/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.

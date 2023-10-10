| [home page](https://iankloo.github.io/Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story

I developed my final data story using Shorthand with charts in Flourish.  I made interim plots using D3, Tableau, and Plotly - but I found the visual consistency and ease of embedding Flourish plots superior to these other products when integrating with Shorthand.  

Please check out my [final data story](https://carnegiemellon.shorthandstories.com/our-last-defense-against-a-global-pandemic-bird-hunters/index.html)!

# Changes made since Part II

After interviewing users in Part II of the project, I made significant changes to create the final version of this project.  One of the most significant changes I made during this phase was completely reordering the narrative.  This was not immediately obvious when reviewing the individual user interviews. In talking with the interviewees after the fact, I found that we tended to discuss things in a different order than they were presented in my interim product.  I originally thought it would be more compelling to present the risk to birds, then the risk to people, then get into the maps and disease modeling.  I ended up consolidating all of the hunting information at the beginning before transitioning to human crossover.  The maps made for a great transitional visualization in this new structure.  

In addition to reordering things, I redeveloped all visualizations except for the disease model line chart and the case fatality rate bar chart.  The users interviewed in Part II were confused by the side-by-side bird harvest visualization, so I opted to make this an animation showing the potential harvest difference if H5N1 took hold.  I showed this to one of the interviewees, and he liked it much better.  

I also redeveloped the maps that I had done in Plotly to Flourish.  Making these maps in Flourish was much more difficult, but they render much better when the page is resized than the Plotly versions.  I used Tableau to help format this data by quickly geocoding the county-level data.

I added the area chart showing cumulative deaths and survivals over time from H5N1 in response to user interviews in Part II.  I have some information on the previous H5N1 outbreaks in the overview section, but I still found every interviewee wanting more information on this.  One especially astute interviewee noted that the high case fatality rate of H5N1 may be anomalous because it has not spread significantly in the human population.  The area chart visualization shows that, while rare, H5N1 has hit the human population many times (almost annually) and has maintained its deadly case fatality rate.  

Finally, I added a lot of discussion throughout the presentation to clear up misconceptions identified in the interviews.  The disease model brought a lot of questions (rightfully so, it is a provocative visualization), so I put some extra text there to describe what is happening and point the reader to the research used to generate the data. 

One thing that I was not able to implement to my satisfaction was making the site work as well on mobile as it does on desktop.  It is still acceptable on mobile, but I found it difficult to work with Shorthand's tools to differentiate how things are presented on different screen widths.  This is a big problem in web development in general that I did not expect Shorthand to solve, but I thought it was worth mentioning.  If I were developing this product for production, I would likely create a different version for mobile use - and I might make completely different design decisions to work with the limited/vertical screen space.  Ultimately, I decided to use my limited development time to make the best product for desktop viewing instead of splitting my resources.

## The audience

I was fortunate to start sufficiently narrow in this project's scope, focusing on hunters and their role in spreading H5N1.  I was also fortunate to interview several hunters to get feedback from a target audience sample.  If anything, I expanded my focus slightly to include more information about a hypothetical H5N1 pandemic that would likely appeal to a broader audience; however, the hook to the story remains focused on hunters.


## References

All of my references are updated and can be found at the end of the Shorthand product.

# Final thoughts

I was pleasantly surprised working with Shorthand and Flourish on this project.  I have some web development and coding experience and always considered these "clicky" interfaces to be subpar - but the technology has come a long way since I evaluated these types of tools.  Overall, Flourish makes it easy to make publication-quality visualizations, and sharing them via embedded iframes is executed nearly perfectly.  The downside of Flourish compared to coding visualizations in R or Python is that you cannot easily regenerate them as part of a data analysis pipeline.  Adding an API to Flourish would make this a killer app!  Shorthand was also excellent.  Integrating open-source media libraries was a game changer, and I ended up with a product that is easily the best-looking visualization product I've ever made.

A downside to developing things using these "clicky" interfaces is they funnel creators into a common visual language.  While there was significant variation, I noticed that many of the final products presented in this class looked similar.  There is a strange kind of "cath-22" with tools like Shorthand and Flourish - they free the creator to think about all of their design choices while simultaneously (and likely unintentionally) pushing them towards a specific aesthetic.  This homogeneity is probably worth it to develop things quickly and without needing web development expertise - but it is worth considering when choosing a tool kit.  The alternatives (something like D3) often look much worse, even when polished, but have greater creativity potential.  This project and this course left me with a new appreciation for these new tools, and I will certainly use them in my work in the future, where appropriate. 






| [home page](https://iankloo.github.io/Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards

I opted to create [my wireframe/storyboard](https://carnegiemellon.shorthandstories.com/our-last-defense-against-a-global-pandemic-bird-hunters/index.html) directly in Shorthand.  As it stands, I have the core visualizations completed, but I plan to add another few visualizations along with some call-out statistics before the final version.  I also need to sharpen the language to ensure the story flows correctly. These are things I know need to happen in the next phase of the project - but, more importantly, I need to get my current work in front of some potential users and collect their feedback.  The remainder of this page describes my interview protocol, results, and the things I plan to do as a result of this user feedback.

# User research 

## Target audience
My target audience is upland bird hunters in Pennsylvania. I have some additional calls to action for bird farmers and policymakers, but these are mostly included to clarify that there needs to be an effort beyond what hunters can do to solve this problem.

I will interview three people: two will be hunters, and one will be a non-hunter with family members who hunt.  While the target audience is bird hunters, I want to include the third non-hunter as a proxy for someone new to hunting.  Ideally, this information would be provided to anyone with a Pennsylvania hunting license, and I want to ensure it is comprehensible to someone who doesn't have significant hunting experience.  

## Interview script

My interview questions will focus on first making sure that the main points I want to convey are coming across.  My Shorthand page is a "minimum viable product" at this stage, meaning I have additional information that I could include if it would be helpful.  My goal for this first pass at Shorthand was to make sure I was telling the core story and explaining those core points in their full context.  I am hoping the users "get it" so that I can move on and add more information. If they cannot answer these questions effectively, I will refine things before moving on.  

Next, I will shift to some more open-ended questions that will identify any areas of confusion or places where people could benefit from added information or context.  This will help direct which pieces of new information I add to the project.    

| Goal | Questions to Ask |
|------|------------------|
|Convey the magnitude of the risk posed by H5N1 to people.|How could H5N1 affect people?|
|Convey the magnitude of the risk posed by H5N1 to hunting.|How could H5N1 affect hunting?|
|Leave the user empowered to affect change.|What can you do as a hunter to mitigate the risks of H5N1?|
|Find out what is being conveyed most effectively.|What is the most memorable part of the presentation?|
|Catch any remaining confusion.|Is there anything you are confused about from the presentation?|
|Find out what could be added in the future.|What are your next questions about H5N1 and hunting?|


## Interview findings
I interviewed three people for this project:
- Interview 1 was with a bird hunter with ~10 years of experience.  Male, early 60s.
- Interview 2 was with an avid hunter who focuses on deer with ~5 years of experience.  Male, 30s.
- Interview 3 was with a non-hunter with a family full of hunters.  Female, 60s.

Notable findings from these interviews are summarized in the table below:

| Questions               | Interview 1 | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| How could H5N1 affect people?| Correctly identified risk of pandemic.  Focused on how H5N1 related to other viruses.  Mentioned remembering H5N1 from the 1990s.|Correctly identified the risks of pandemic.  Metioned it would be worse than COVID-19. |Correctly identified risk of pandemic.  Also mentioned the risk to the poultry industry which could cause food prices to rise (remembered from 1990s panic).|
| How could H5N1 affect hunting?|Correctly identified risk to bird population, focused on 100% fatality rate to farmed birds.| Correctly identified it would limit hunting opportunities, especially with pheasant.|Correctly identified it would kill all farm-raised birds.  Thought the wild birds had some immunity because they are "out in the world."|
| What can you do as a hunter to mitigate the risks of H5N1?|Focused on not having birds in vehicle, transporting in disposable boxes, and using PPE.  The first two points were actually targeted at farmers in the presentation.|Focused on safe handling of dead birds, mentioned it is uncommon to clean birds before leaving fields so it is unlikely hunters will follow that advice.|Focused on not traveling with live birds in car and need to report to game commission if found a diseased bird.  Asked how you could know if a bird was diseased if it was already dead.|
| What is the most memorable part of the presentation?|Knew about bird flu but didn't think about how it could affect hunting in PA.  Had recently traveled to Argentina to hunt birds and they are very concerned there.  He thought that it was only a problem in South America.|The data showing the potential deaths compared to COVID-19.|The death rate bar chart showing the relative danger of H5N1.|
| Is there anything you are confused about from the presentation?|Chart with bird harvest did not make it clear that the 2023 data would be projected, he thought it was how many had been harvested so far.  Also, the maps didn't render on mobile well.|Had a lot of questions about the disease modeling and the assumptions included there.  This person is a data scientist by trade and wanted to get more into the modeling specifics.|Confused how pandemic was averted in the 1990s and why we couldn't just do those same things to avert another one.  Also was distracted by the mention of cats being infected.  Not clear on what constitutes PPE.|
| What are your next questions about H5N1 and hunting?|What about turkey? More people hunt turkey in PA than upland birds, so probably want to mention them as well.|Just wanted clarity on the model (we got stuck on this point).|Wanted more specifics in the call to action and possibly some more information about the scale of upland bird hunting in PA (i.e., is this a big deal)?|

# Identified changes for Part III

Overall, the interviews showed that the users took away the major points, but there were some major issues to work out before the final submission.  The table below summarizes the changes I intend to make:
   
| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| The visualizations did not work great on mobile, and the maps were too small even on desktop. | Rebuild the visualizations with mobile in mind.  In particular, I will vertically stack the disease model visualization and maps.  I will also show two maps: last year and this year. |
|The bird icon visualization does not clarify this is a projection.|Provide more surrounding discussion about the assumptions needed in the bird plot.  I will also explore other visualization options that clarify that we are talking about a projection.  It could easily be interpreted (and was by one interviewee) as just showing the number of birds already harvested this year.|
|The project fails to mention the risk to chickens and the poultry industry. | Add a new section highlighting the potential economic impacts of H5N1 hitting the chicken population.  Look to the effects of the culling process in China in past years for additional data for a new visualization.  Include information about how this could affect world hunger (big emotional issue to appeal to).|
|It is unclear why wild birds are less susceptible to H5N1|Add discussion that makes it clear that H5N1 is equally dangerous to wild (non-farmed) birds like grouse, but these birds are less likely to encounter the virus when compared to farmed birds.|
|The disease model is too opaque and does not discuss assumptions.| Explicitly mention the paper used to generate the disease model results and any parameters and assumptions used.  This will mostly be in the form of accompanying text.  All interviewees found this visualization impactful, so I don't intend to change it much.
|The call to action lacked specifics.|Add more specific things hunters can do.  Consider breaking this out into a page for each user type (hunters, farmers, and policymakers) if this is getting too long-winded for the space provided.|

Most of these problems will be solved by adding text and reworking visualizations to add clarity.  I anticipate major overhauls of the bird icon visualization and the maps, but the others were effective as they are and will only need small modifications.  I will need to add at least one new visualization to address the risk to the poultry industry, and this may need to be in a new section highlighting the economic impacts of H5N1. 

These all seem like manageable changes in the next week, and I am optimistic this project is on track to produce something interesting and useful.  





# Take-home Submission

## Follow Up Answers

1. I spent one day (24 hour period) on the project. Given more time I would perform preference testing for the UI with agents that use the widget. I would also perform usability testing to see how they use it with a customer and if they run into any difficulties especially when determining quality of the house. I would also discuss with the agent whether or not they prefer an automatic calculation or an initiated calculation. I would also look into the imagery and see if the images help the agent in answering the question or if just the description itself is all that is needed or if better images are needed. 

2. The biggest change I made had to do with the quality question. When putting myself in the agent’s position, it seemed difficult to be on the phone helping a user decide on a quality when they have to click on each quality to get a description. Having the descriptions available without clicking allows the agent to quickly answer any questions the customer may have about the quality choices. I also changed the language used for the quality levels. The level data remains the same but the words to describe each level has changed. This is due to discussions with homeowners and how they perceive quality. This will help the user have an easier discussion with homeowners. The other questions on the form are very straight forward and have one clear answer, therefore I didn’t focus my time on those. 

3. To validate my design, I would put together a prototype that showed the inactive and active field states as the agent worked through the form. I would have the agent use the prototype with one of their potential users. I would observe any hesitations, difficulties, and barriers in completing the form. I would want to look at the agent’s screen to see how they navigate and I would want to hear the conversation they have for language improvements on the form. This is assuming that the agent is filling it out while talking with a customer. If they are filling it out independently I would just need to see their screen, what information they have while they are filling it out, and what issues they are having. I utilize Steve Krug’s usability script in order to collect the qualitative data. If there are no difficulties or hesitations I would say that my design is valid and the user story is accomplished with ease. 

4. Josefin Sans most matches my personality. It is what I chose for my portfolio branding. It is vintage inspired yet a modern geometric sans serif. I consider myself often inspired by the vintage but I always have a modern take. The X-height to cap height ratio shows a lot of dimensions and change. I consider myself very open to change, always trying to grow personally and professionally. It also reminds me of the mountains which I don’t think I could live without! I love the slanted e used in the typeface. It gives a subtle and unique twist which I feel most everyone, including me, has. It also appears friendly and open to others which I consider myself to be.


## Assumptions

- BriteCore is a web-based software therefore the high fidelity mockup should be a desktop view. 
- The questions listed collect all of the data needed for the algorithm to give an accurate estimate for the client. 
- This design is for a specific widget and therefore won’t include the entire browser design. 
- This form will be used by the client to assist a customer. Therefore the language used must match the type of language the client will want to use when addressing the customer. The questions should be quickly identifiable for an ease of conversation. 
- This widget will be used in a professional environment which means the visual design should be trustworthy, clean, and professional. 
- User Story:  As an agent using BriteCore, I am able to quickly get a replacement cost estimate for my customer, so that they can have the correct amount of homeowner's insurance.

## Questions

- Can the current text content be improved? 
- Is it time consuming to click each quality option for more details? The agent may have to click 5 times in order to get a description of each quality for the customer?
- Should the images be shown alongside the options for house quality? Should there be an image for each option? Will the agent’s customer be able to see these images? How can the agent best help their user to select a quality?
- Are the house descriptions helpful? Would the agent use these descriptions when talking with a client? If not, are there other descriptions that may be helpful? 
- How is the agent interacting with the customer? Over the phone? Or is this information the agent has already collected and now they are filling it out independently?
- Is the quality of the home referring to the exterior only or is it referring to the general quality of the home interior and exterior? 
- Should it be customer initiated or should it automatically calculate when the answers are put in? 
- Does the agent have an image of the customer’s house when choosing the quality or is it a verbal selection when talking with the customer?
- Does the square footage include deck areas?

## Research

I analyzed Esurance and Progressive to determine the information they collect, how they collect it, strengths, and weaknesses. I also looked at how it would differ from an agent user to a direct customer user.

### *Esurance Competitive Analysis*

- First they collect the user’s personal information which helps them search for data to prefill some of the house information on the form, which saves the user time. 
- In this case the user is filling it out without the agent therefore the considerations will be different for the language and layout. 
- Layout consists of the questions on the left and the answer options on the right. 
- Headline titles are above questions that relate to one another. 
- There is an image for each quality choice and a description that relates to that quality. The ordering of the quality choices could be confusing since they are not increasing in quality as you read down the list. The words chosen make sense and allow me to quickly identify from the list. I will utilize this language in the design of the quality question. 


### *Progressive Competitive Analysis*

- Orders by structure, exterior, interior, utilities. 
- Very clean, simple, professional design. 
- Great imagery for selecting from the choices in material and shape. 
- The visual design on the selection boxes seem disabled where the user may think they aren’t able to select. 
- Strong design and layout. Similar to Esurance with the questions on the left and answer choices on the right. Answer options differ greatly depending on the questions. Tend to present many images to choose from which users tend to prefer. 

**Notes:** The imagery presented is very helpful for users but may not be as needed if an agent is talking with a customer on the phone. Language in this case is much more helpful. 

## The Client's User- Interview

When talking with homeowners I learned how they think of the quality of their home. Economy and standard were not words that they commonly associated with the quality of a home. They used words such as ‘builder grade’ when talking about a lower quality home, and talked about luxury with high quality. They discussed the finishes such as crown molding, counter tops, flooring, new appliances, wood finishes such as beams, high quality insulation, decks, views, etc. 

Since this is the only question that requires more in depth discussion, I spent the most time on improving the usability and conversation that the agent would be having. I wanted to make sure they could accurately collect the right quality level from their customer. 
## Content Strategy

Ordering was changed based on research and going from a basic question to a more specific question and grouping together related questions. 

- H1 - Replacement Cost Estimator 
- H3 - What year was the home built? 
- H3 - How many square feet is the home? 
- How many bedrooms does the home have? 
  - H4 - 1
  - H4 - 2
  - H4 - 3
  - H4 - 4
  - H4 - 5+
- H3 - How many bathrooms does the home have? 
  - H4 - 1
  - H4 - 1.5
  - H4 - 2
  - H4 - 2.5
  - H4 - 3+
- H3 - What is the quality and style of the home? 
  - H4 - Builder’s Grade
    - Example Image
    - Paragraph - Interior and exterior comes with standard finishes. Materials such as laminate and ceramic are often used. No remodeling has been done in this case. 
  - H4 -  Semi-Customized
    - Example Image
    - Paragraph - Some of the materials have been customized or upgraded such as newer appliances, backsplash, etc. 
  - H4 - Customized
    - Example Image
    - Paragraph - Upgraded many materials such as marble countertops and other high quality materials. 
  - H4 - Designer
    - Example Image
    - Paragraph - Has additional features like cabinet lighting, a double oven, etc. 
  - H4 - Luxury
    - Example Image
    - Paragraph - Highest quality materials and features. Extra amenities and materials such as a china sink or oak cabinets. 
- H4 - $228,000

![Wireframes](https://github.com/katelynmichalove/BriteCore-Submission/blob/master/Wireframe_sketches.jpg)
      

# Portfolio Project
Project using hand written HTML &amp; CSS fundamentals

## Situation & Task
Task was to create a portfolio or personal profile page, using basic HTML & CSS that we've learnt during the first week of our course.

## Approach
I didn't use CSS Grid or Flexbox, which would make creating layouts a lot easier. Instead I had to rely on display modes, namely inline-block to arrange elements like the article cards in a horizontal row, that then stacks vertically on smaller screen sizes.

I've utilised a lot of things learnt during the first week.
Things like:
- Sticky nav positioning (stays at the top when you scroll down)
- CSS transitions & transforms
- Pseudo elements in the use of emoji icons
- CSS Variables to make reusing properties and editing them a lot easier and more organised

## Results
I'm fairly happy with my results.
There does seem to be a weird bug, where hovering over an article card causes it to overlap the sticky nav when you scroll down. Managed to fix this bug by adding a z-index value to the sticky nav, so that it appears on top of elements that used `display: inline-block` (article cards & mirrored pencil emoji).

There are some quirks with horizontally centering parts of the page that I would like to tweak too, but I know using flexbox would make this a lot easier. Managed to get to a point where I'm satisfied with the layout, despite not using flexbox or grid for true responsiveness and scaling for mobile screen sizes.
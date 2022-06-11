# stats-preview-card-component

Problems I expect to encounter:
- Responsive design with different column/row layout (axis)

Goals during project:
- Use git more regularly

Problems I didn't expect: 
- Need to do more research on min- interactions

Struggled a bit with this project, mainly due to the difference in layout. I need to spend more time at the start brainstorming the layout and HTML elements. Had to pivot a couple times after realizing my flex wasn't positioning correctly because of how many siblings there were in the parent container. Been doing more flexbox practice so hopefully this resolves itself through more exposure. 

Another issue I had as the overlay for the tinted image. I actually didn't realize until the end of the project, but this was actually a few compounding problems. To start, I used set a background-image on the parent, added a solid linear-gradient as a second bg-image and adjusted background-blend-mode to get my tinted image. This worked fine until I started my responsive design, where the border-radius wasn't applying. I thought this was due to the linear-gradient, but it was actually a new problem: I hadn't adjusted the overflow property. So with my linear-gradient plan scrapped, I went with an overlay inside of a container with the image as its sibling. From there I just set the BG-color and opacity and got the desired result. I guess both solutions worked fine! ;)

See you next project!

p.s. 
You'll have to forgive my shorter post-mortem this time around. I'm recovering from a brief illness. Thank you for reading, as always
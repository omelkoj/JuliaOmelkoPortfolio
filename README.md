## DAFT PUNK FAN SITE (PROJECT 2)

You can use the [editor on GitHub](https://github.com/omelkoj/JuliaOmelkoPortfolio/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

This is my Project 2 for the Front End Developement Bootcamp at Albany Can Code. It is a fan site for the band Daft Punk, and the goal of the site is for visitors
to be able to listen to Daft Punk's key albums, find out more about them, visit their various social media sites, and view their film Electroma. 

### DESIGN

1. The homepage has a helmet, which when hovered over, reveals a motherboard, which in turn produces hoverable nav links. This is a reference to one of the Robots taking off his helmet in the film Electroma, to reveal his true identity as a robot.

2. The entire site is polished and minimalistic, as well as somewhat retro font/styling choices to pay homage to Daft Punk's innovation and rise to fame in the 90's/early 2000's, as well as their helmets and stage wear.

3. The "More Daft" page features a timeline of Daft Punk's helmets throughout the years, as well as functioning as links to their social media sites. Hovering over the timeline produces more interesting Daft Punk facts.


### TROUBLESHOOTING/CHALLENGES

- I learned how to use CSS grid, as well as more about nesting elements in order to achieve the effect I was looking for on the homepage - I couldn't get both .hover styles to work simultaneously by only using flexbox and positioning as I usually would.

- The two overlapping images would begin to move apart from each other when resizing the browser window. I fixed this with positioning, and by changing one of the classes to relative positioning.

- The helmet timeline was responsive, but the links didn't match up with the corresponding helmets upon resizing. I fixed this by putting each link/helmet into individual flexbox columns, and then putting it all together into one giant flexbox with flex-direction: row.

- The "Listen page" media player links kept jumping back up to the top every time the album image was clicked. I fixed this by putting a letter + hashtag into the href, instead of just the #. Simple, but it worked!

# Class-2-DWD

<h2>Process and Documentation</h2>

With this week's assignment, we had to work on building a responsive website and replicating one of the posters from swiss design and in order to build the website, we had to follow similar steps on web development as was shown to us during the class. The approach that I decided to take for this web design and development of the project was "Reverse Engineering". 

The first step that I did was research and see which design I wanted to build from the ones available online about swiss posters. I then picked the following design to be made with the intent to give it more interactivity by moving the blocks. 

You can find my project here live on glitch by clicking <a href="https://dwd-class-2.glitch.me/" target="_blank">here</a>.

<img src="https://cdn.shopify.com/s/files/1/0140/7312/products/velocity_girl.jpg?v=1358293119" width=500px height=auto>

<h2>Challenges and Struggles </h2>

One of the things that I found challenging was to have the two layers of the blocks to appear one over the other and move an hide once they reached the posters end. This effect worked well with the pink and yellow layer however, the blue layer did not seem to work. I suspect that it could be due to the fact that the position of this layer was set to absolute. This had another side effect on my final design, it didn't turn out to be truly responsive and I had to manually enter a lot of padding percentage value in the code which was probably not the right approach to arrange the blocks. 

A struggle that I was to make the blue blocks appear above the pink and yellow blocks however that was taken care by using position in css. I set the position of the pink and yellow block with relative position and set the blue blocks position as absolute. This ensured that the layers (pink and yellow blocks and blue blocks) appear above each other. 

<h2> Questions </h2>

1. What is an easier way to layer two div's on top of each other to move in a resitricted width with their overlay's hidden? 

<h2> References </h2>

1. w3schools, https://www.w3schools.com/css/css3_animations.asp
2. Geof, Graham, https://css-tricks.com/using-multi-step-animations-transitions/
3. https://codepen.io/team/css-tricks/pen/bEdKaW

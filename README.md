# week-one-project

https://www.w3schools.com/howto/howto_css_smooth_scroll.asp#section1 

^^ I used this code to achieve a smooth scrolling effect.

https://www.w3schools.com/html/html_favicon.asp

^^ I used the example code here to add a favicon


Reflection:

1. What requirements did you achieve?

I achieved all requirements for this task. My project includes a header, nav and footer, Ive used absolute positioning to overlay text on an an image, I've used flexbox on several elements including my nav bars and all my images are correctly implemented with accurate source file paths.

I have achieved several stretch goals. I included a back to top button and functioning internal links on my nav bar with smooth scrolling. I have also included a functioning social media bar in the footer and hover effects on my 'Read More' buttons. I've also added a fixed position nav bar with opacity to view elements behind it as you scroll and a favicon.

2. Were there any requirements or goals that you were unable to achieve?

I achieved all requirements and several stretch goals but did not use the background music track suggestion.

3. If so, what was it that you found difficult about these tasks?

I didn't struggle with the tasks but overcoming certain bugs was difficult because it took me a long time to figure out what their cause was.

4. What errors or bugs did you encounter? How did you solve them?

I had a bug affecting the width of my nav bar; which would only take up half the width of the page. This turned out to be because I was using 100vh, which stands for viewport height, so to fix this I changed my width to 100vw (viewport width).

The default setting on my sections was display: block; which resulted in unwanted white space between each image.
I inspected and couldn't find any default margin, but could see that this display setting was causing the issue so I changed the .section class to flexbox which resolved the issue.

I also had a white space between my footer and main, which I realised was because the <p> in the footer had default margins, so I set the margin to 0. 
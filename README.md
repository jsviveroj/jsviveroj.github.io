## Welcome to jsvivero profile page
I am Juan Sebastián Vivero Jáuregui, 21 years old.

Student of Computing and software engineering at Universidad Nacional de Colombia,  I’ve been here since 2013, during this years my learnings lead me to make awesome projects that include games, languages, mash up applications, web applications, stand alone and many others that will be soon in this page.   

## Interests

Since I was a little child everything around computers and software was interesting to me, all I wanna do since there is to be capable of creating my own software with my ideas, my experience, my designs and that’s the reason of my life, having such a power of creation in both  hands to develop whatever is in my mind.

I discovered with my projects that developing software to help  people is motivating and needed so that’s my choice in a near future.

About languages I’ve learned a lot, Java, Ruby, Python, Golang, C, C# , C++,  JavaScript  ……….
Because  logic is the same, makes easy to learn new languages each time.

## Projects

### UNSimplexMO

It's a language for linear programming, more specific for simplex algorithm but is capable of making it multi objective using Goicoechea solutions to find a solution, it was developed in ANTLR for JAVA.
It has two manuals, one technical and one for user.

You will find it [here.](https://github.com/jsviveroj/UNSimplexMO)

### Student Well Rent

It’s a mash up application developed for Purdue University , in a development tournament named Iron Hacks. This app will help you to find the cheapest, nearest, affordable place in Chicago to stay near the Illinois University.

Was developed in JavaScript, HTML5, CSS and data was real from the Chicago Government.

You will find it [here.](https://github.com/goldironhack/2017-Purdue-UNAL-IronHack-jsviveroj)

### Soon more projects!!!

# Contact
 Email: jsviveroj@unal.edu.co

# Rendering

## Anti-Aliasing
In real world, as humans we can see a full detailed world because it is continuous, everything is formed by infinite points so it is possible to see curved lines with the same quality as seeing a straight line. But in a discrete world like a screen we are talking about lines and forms to be represented in pixels, something countable that has an end.


So straight lines could be represented normally but what about a curved one?  The problem is born here, curved lines will always have this saw tooth effect.

![Aliased](/images/aliased.png)

Here is where anti-aliasing takes its job, trying to get this problem the least remarkable as possible, but what if we think in resolution?

![Anti-Aliased](/images/antiAliased.png)

Obviously a normal way to fix this type of problems could be  just thinking that pixels are not enough to represent a form or image so the solution would be to re assign the amount of pixels in terms of resolution till the problem is impossible to see.

![Resolutions](/images/4kvs1080.jpg)

But if we don’t have this type of resources and we need to handle the problem, anti-aliasing is a good method to improve the picture. In high resolutions like 4k anti-aliasing is not as needed as in low resolutions.

## Types of Anti-Aliasing

### SSAA (Super Sampling)

This type of antialiasing uses what is known as the brute force method to improve the quality of the images. In this way we will have a very high image quality, but, it needs a very high consumption of resources.

This system works in a way that renders the image at a much higher resolution and, after applying a series of smoothing filters, this image is rendered back to the resolution of the monitor.

So we obtain a superior quality, although processing a X times larger image (2 times, 4 times or 8 times, as we choose SSAA 2x, 4x or 8x), the resource consumption is exponentially higher.

![Resolutions](/images/ssaa.png)

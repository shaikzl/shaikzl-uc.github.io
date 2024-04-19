# WAPH-Web Application Programming and Hacking

## Instructor: Dr. Phu Phung
## Student

**Name**: Zaheer Akmal Shaik

**Email**: shaikzl@mail.uc.edu

**Short-bio**: I have great intrest towards ethical hacking. 

![Zaheers's headshot](images/zaheerpic.jpeg)

https://shaikzl.github.io/shaikzl-uc.github.io/index.html

https://github.com/shaikzl/shaikzl-uc.github.io

 ![html file](images/up1.png)

In the Snap-1, I created a WAPH HTML file and i have inserted details about the course contents and introduction of me.

![boostrap](images/up2.png)
snap - 2, I employed the Bootstrap CSS framework for creating my website more flexible and accessible. I sped up the development of layouts and elements by utilizing Bootstrap's grid structure and already assembled UI components such as buttons, navbars, and cards. In order to reduce the need for bespoke CSS, I used Bootstrap's utility classes for dealing with typography, color improvements, spacing, and scaling. In addition, I chose a Bootswatch theme, which is free and open-source, and effortlessly linked it with a content delivery network (CDN) to access pre-defined CSS styles for enhancing the overall look of my site.

![education](images/up3.png)
![experience](images/up4.png)
In snap 3 and 4,Expanding upon my utilization of the Bootstrap framework with my educational background and projects and certifications an Interships, I integrated Bootstrap's robust CSS framework into my website development process.

Included a page tracker using flagcounter to count the number of visitors
to the page. Included this counter at the bottom of the page.

![flag](images/up5.png)

```
<div><a href="http://s11.flagcounter.com/more/OCo"><img src="https://s11.flagcounter.com/count2/OCo/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a></div>
```

![clock](images/up6.png)
I incorporated several jQuery operations into the webpage: a digital clock, an analog clock, and an email onclick function.

```
<button id="colorfulButton">Click Me!</button>
<script>
$(document).ready(function(){
    // When the button is clicked
    $("#colorfulButton").click(function(){
        // Generate a random color
        var randomColor = '#'+(Math.random()*0xFFFFFF<<0).toString(16);
        // Change the background color of the button
        $(this).css("background-color", randomColor);
    });
});
</script>

```
I used jquery to create a click me button whihc changes its colour evrytime when we click on it.

### API Integration 

I inserted the public jokeAPI that displays a new joke every minute. Ajax was utilized to make the API get request.

![Joke](images/up7.png)

Used a public API named dogapi to get dog images when requested.

![Dog](images/up8.png)



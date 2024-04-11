# Documentation

## Process

We extracted the elements from the poster using Adobe Illustrator. Then uploaded them to the GitHub to make sure we had the files to start working on the project. 

We started by making the background of the poster using the extracted SVG elements that make up the wavy shapes you can see in the background. Then we made the footer to look exactly like the poster and with clickable links. We preserved the aspect ratio so it was responsive to every screen.
After the background was finished, we could then move on to placing the SVGs. 

## Elements / SVGs

### earth_whole.svg

The placing of the earth was fairly simple and didn't cause any problems. We then remade the eyes on the earth by drawing them using CSS. The pupils was then animated by using CSS keyframes to make it so it appears to be looking at the text on the different contintents. We felt like this would encourage the readers to look at the text written on the earth.  

### moon.svg & stars

For the moon we used CSS keyframes animation to make it rotate back and fourth. The stars were drawn with SVG polygon points, then animated using SMIL animation transform to rotate them. 

### car.svg & text72.svg

The car was animated using CSS keyframes to make go back and fourth. Then we placed the text72.svg behind it so it still looks like exhaust coming from the car as it does in the poster. 

### kidswithtiktok.svg 

The kids was placed so it looks like they're standing on the earth. We then used CSS keyframes so they appear to be jumping up and down. 

### Text

First we downloaded the Marydale Bold font because that is the exact same used on the poster. To make it so the text appeared on they're own line, we used a lot of `<span>` elements and `display: block;`. Some of the text on the continents on the earth was difficult to place so it looks the same as on the poster, but we used an embarassing amount of `&nbsp;`, `&emsp` and `&ensp;`.


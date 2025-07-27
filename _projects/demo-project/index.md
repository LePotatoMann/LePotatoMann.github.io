---
layout: post
title: Systems Engineering Project 1
description:  This project aims to deploy the LIMO Robot by AgileX and navigate an arena consisting of 8 different 1.33m x 1.5m plots themed around Changi Airport. The project utilises ROS 1 Navigation Stack and Real-Time Appearance-Based Mapping (rtabmap), in order to successfully navigate through the arena.
skills: 
  - 3D Modelling
  - Python Programming
  - ROS 1 (Melodic)

main-image: /LIMO_Robot.png
---

---
# Hardware Given

## LIMO by AgileX
{% include image-gallery.html images="LIMO_Robot2.png" height="400" %}
This project uses the LIMO Robot by AgileX, and its EAI XL2 LiDAR, ORBBEC® Dabai stereo depth camera, as well as other in-built sensors to perform SLAM, path planning and navigation, and obstacle avoidance.
The final goal being to succesfully navigate any given plot number within the arena.

---
# Arena Map Design
## Requirements  
To test the deployment of the LIMO Robot, each team was tasked to create a 1.33m x 1.5m sized map that emulated a particular landmark of Changi Airport for the LIMO to navigate. In my team's case, we were given the task to emulate Terminal 1.
Aside from the map size, there was also a additional requirement that the LIMO Robot was to navigate through the center of the map within a 5cm radius.

## Design Choices
To emulate Terminal 1's design, not only did our team try matching key design choices from the area itself. We also decided to include a key landmark from Terminal 1, the Kinetic Rain sculpture, in order to emulate it as best we can.

Following this, our team created a path layout that would ensure ample difficulty in order to test the LIMO Robot's navigation capabilities as seen here.

## Finalised Arena Design (SolidWorks)
{% include image-gallery.html images="Arena_Final.jpg" height="400" %}

  

## Live Arena
{% include image-gallery.html images="Live_Arena.jpg" height="400" %}

---  
# Mapping & Live Demo

## Mapping
Below is the completed map of the entire arena as captured and displayed within RViz (ROS Visualisation)
{% include image-gallery.html images="Live_Arena.jpg" height="400" %}
  
## Live Demo
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}

### Embeed images
{% include image-gallery.html images="Live_Arena.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header



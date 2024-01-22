# Take home assignment
Thank you for giving me the opportunity to do this assignment, below I will list my thought process and how I tackled this.
## Starting 
1. Starting off, I knew I had to make a plan on how to tackle this. 
2. I wanted to start off by created a map, mapping out where everything is according to the screens and marking where everything is. 

## Mapping
1. In a drawing by hand I have marked and planned where everything will go with names exactly. 
2. Based on my map I want to code from the bottom most layer to the top which means starting with the background. 
3. After establishing the background I will start on the side bar.
    - From here I can start from the top down, meaning starting with the DPI logo, the "Courses" and "Log out" and then working down to the user profile picture
![alt text](https://imgur.com/a/kngI6YE)
4. Also need to map out the cards as the consist of several components
![alt text](https://imgur.com/a/lnZlKus)

## Sidebar
1. When starting the side bar, I realized that the DPI logo is at the top along with the icons of courses and log out.
    - Therefor, this will require it to be seperate from the user profile, name and copyright
2. I needed to figure out a way to seperate all items but group 2 together. 
3. Initially I made it into 2 groups but realized that the icons will require seperate css when changing the hovering so I made it individual.
    - My issue with this is eventually ran into the issue that when I hover over one, I changed both, which required a little playing around with
4. Everything must be center of the column but not center of the sidebar completely.

## Main Page
1. After figuring out the background I anchored it to the corner, made it smaller but only wanted the pattern once.
2. Creating the cards was harder than I thought it was, definetly could be easier with bootstap.
    - Drew out the card and realized that it had several components.
3. Card consisted of background image, the course icon, the course name, the status, and the arrow.
    - could not find a progress bar that was similar to.
    - realized in order to individually customized each one, I had to assign a class to each component.
        - "View syllabus" is located in a completely different spot than the title of the course.
4. Once I figured out the cards, I had to figure out how to flex-wrap them.
    - I tried coding card1, card2 at first but realized it would be easier to apply several classes ie. card card 1. This way I can apply different backgrounds to each card.

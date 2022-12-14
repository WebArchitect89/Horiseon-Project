# Horizon Project

## About application.

The web application provides an overview of what services a social media marketing agency can offer you, as well as benefits your business can enjoy after using those marketing tools.


## Reason for the project.

I have been hired by a marketing agency to refractor their website code, the target was to make it more accessible and friendly so that they rank higher in SEP and also avoid litigation.

## What did I do?

I did that by adding:

Semantic HTML elements throughout the code.
Added accessibility attributes to all images and links.
Made sure that HTML follows a logical order for the browser and the accessibility technologies, such as screen readers to be easier to read the code.
Consolidated the selectors in the css file to clean the code.

## How did I improve the project?

At the moment my project is easily read by accessibility technologies such as screen readers and others, ranked higher in SEO.

## How the project stands out.

What makes my project stand out is the fact the “title” attributes I added in the "a" tags, this way when a user clicks on the link the page opens in a new tab so it is easier to retain the user on your website for longer times.

## Challenges.

###### Challenge 1 Invalid Paths.

I met some challenges working on a project, one of them is that at my first attempt of completing the project I just went to all my “Acceptance criteria ''without adding and committing to git. So at the end when I completed all of my acceptance criteria and deployed my application it would show without css formation on it. Because of that I started from the beginning but this time I would push to git every action I would make.
I met the same challenge but this time I was able to debug it.  The issue was that when I deployed the app the git would point at my README file, so I decided to move my index.html from the starter folder to the repo, because of that all of the relative baths were invalid, CSS path from the link and img paths. I readjusted the paths and all was good.

###### Challenge 2 Image would not display.

Another challenge was that this image: SS wasn't showing in the deployed version but it would show in the local version. Cleared cache & cookies on my browser, same issue. After asking my colleagues for help one of the TA’a tried to see the deployed version of the app on his device and it would show, I tried on a different browser and it would show as well.
Tried “inspecting”my deployed version and I spotted that the difference between the other images and this(which would not show) is that there would be this attribute in the tag on the image that would not show: “style="display: none !important;”(not sure if that would be the reason). So as this would be a browser issue I left it.

###### Challenge 3 Navigation menu positioning.

One more challenge was when I wanted to make sure that “nav” tag containing the links stays in the middle of the header, I was trying to achieve that by setting margin top for selector “a” to -40 px but when I do that it shows like this: [img](screenshots/nav-issue.png) however if I do -20px or lower the size is ok but the position is slightly lower than in the mock up image.

I also had other minor challenges.

## [Deployed Project](https://webarchitect89.github.io/Horiseon-Project/)

## Installation:

### Click on the deployed link above.
 
## Usage:

### Open the aplication. ![open-app](screenshots/oppen-the-aplication.png)

### Go to the navigation menu. ![nav-menu](screenshots/go-nav-menu.png)

### To check each tool available click on the desired option.

### To check the benefits, scroll all the way to the right and then to the bottom. ![benefits](screenshots/benefits.png) 

## Credits.

### Thanks to all of my colleagues, TA, Instructors, Tutors from bootcamp for helping me with this project by being quite responsive on slack whenever I had an issue.

## License

MIT License

Copyright (c) Year Full name

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

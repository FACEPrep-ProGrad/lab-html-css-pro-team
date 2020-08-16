![Image description](https://i1.faceprep.in/ProGrad/prograd-logo.png)

# ProGrad Lab | ProTeam

## A Quick Introduction

As ProGrads, We are always very proud of having a very strong technical mentors in the team. We have created a lab to honour them. Similarly we would like you to remember and honour your friends, family or teammates who made an impact over you. In this lab, you will create an very responsive poster where you describe about people who made an impact in your life. Ensure that the design works on all kinds of screens.


## What should you do
```
Fork this repo
Clone this repo
Basic html and css
```

## How To Submit
```
Upon completion, run the following commands:

git add .
git commit -m "ProGrad ID"
git push origin master

And finally, create a pull request so your ProGrad Mentor (PM) can review your work.
```

## Instructions
The starter-code contains all the files, images, and text content needed to create the design.You can add your own images instead of the images given. Font to be used should be Nunito Sans. Remember to follow the best practices.

### Progression 1: Design the posters

You are expected to build a very responsive layout as per the expected output given below.
![Expected Output](https://i1.faceprep.in/ProGrad/ProTeam-1.png)

### Progression 2: Be very responsive 
Now make the design very very responsive by using media queries.If you need a reference to media queries, you can refer here [Media queries](https://css-tricks.com/css-media-queries/). 
**Your design should work for various standard devices such as Laptops, Mobiles and Tv screens. Design your output such that the maximum width lies in the range 1300px - 450px.**

Kindly refer to the screenshot given below after the screensize is reduced.
![](https://i1.faceprep.in/ProGrad/ProTeam-2.png)
![](https://i1.faceprep.in/ProGrad/ProTeam-3.png)
![](https://i1.faceprep.in/ProGrad/ProTeam-4.png)
![](https://i1.faceprep.in/ProGrad/ProTeam-5.png)
![](https://i1.faceprep.in/ProGrad/ProTeam-6.png)

To do achieve this refer to the below code snippet.
```
@media(max-width: 1300px) {
    .heading {
        font-size: 65px;
        width: 80%;
    }

    .cards-wrapper {
        width: 100%;
        top: 32%;
    }

    .image-top {
        height: 200px;
    }
}

@media(max-width: 1000px) {
    .container {
        height: 100%;
    }
    .heading {
        width: 90%;
    }

    .cards-wrapper {
        flex-wrap: wrap;
        padding: 300px 0 200px 0;
    }

    .card {
        margin: 0 30px 50px 30px;
    }
}

@media(max-width: 700px) {
    .heading {
        font-size: 50px;
    }

    .heading::after {
        height: 40px;
    }
}

@media(max-width: 450px) {
    .heading {
        font-size: 40px;
    }

    .heading::after {
        height: 33px;
    }

    .cards-wrapper {
        padding: 250px 0 150px 0;
    }
}
```

# Expected Output
You can refer to the final output here. If you try to shrink the screen, you can visualize as per the screen size.
[Final-Output](https://faceprep-prograd.github.io/lab-html-css-pro-team/)

Happy Coding ProGrads❤️

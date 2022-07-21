# Project

## Summary

* Project name: haircuts
* Web address: N/A
* Purpose: Develop a website for PC and mobile use to display works and get people to book a haircut.

## Layout

I have gone for a grid layout, giving it 4 rows and 3 columns. That was enough to place the most important elements on the page: call-to-action, image carousel, services description, master photo and description, as well as a certificates area.

## Carousel

It has been implemented with a simple CSS keyframes slideshow. It is basic but responsive.

## Responsive Design

I used a simple @media query so that elements occupy a single row by themselves when the screen width gets less than 600px. To accomplish that I had to place every div class inside @media and only change row order as well as fill every column (out of 3 available) within those rows with elements. I am sure I could have done a better job with area names or even flex but I have to research that subject further.

By adding another coulmn I was able fit a photo element and re-flow some text with much more control and still avoid a messy grid set-up. Now the page looks a bit more fluid and easy on the eye.

## Padding

Played around with padding for images and responsive design. I had to adjust manualy padding for images with respect to the screen size. Now they look a little better and to scale.

# Responsive Web Strategies

## Overview

In this lesson we will explore different strategies used to create responsive layouts. We will look at the differences between building separate sites with user agent detection, as well as single site solutions using CSS Media Queries. We will discuss differences in desktop down vs mobile up (mobile first) design philosophy.

## Objectives

1. What is a repsonsive layout?
1. Advantages of single site designs using Media Queries.
2. Recognizing differences in design approaches using Desktop down vs Mobile Up (Mobile First).

## Building Responsive Sites

<iframe width="640" height="480" src="https://www.youtube.com/embed/T649edELGoY?rel=0" frameborder="0" allowfullscreen></iframe>

*Note: Slides for this lecture video are provided in the resources at the bottom of this lesson.*

### What Is A Responsive Layout?

Today, web sites are increasingly being viewed on many different size devices other than simple desktop or laptop computers. Building a site layout for desktop devices alone will not allow your many site visitors on tablet, mobile, or larger smart tv devices to comfortably browser you content. Due to the large variation in screen sizes it is important to have a layout that will alter itself to best suit whatever size device it is loaded onto. Responsive layouts step in allowing content to respond differently for each device.

### Strategies

One strategy for adjusting content for different devices is by using device detection, where the server looks at the request headers user-agent value of the browser making the request. Based on the user-agent the server determines whether to serve up desktop content from site A or mobile content from site B. The main downside of doing it this way is that it requires creating two separate websites, one for larger screen and one for smaller screen devices. You can imagine then if we are asked to make a change in the content, we may need to change the content on two different sites A and B.

Another strategy, the one will will explore in more detail in the lessons to come are by using CSS Media Queries. This allows us to have a single site that will adjust the layout and content depending upon the size of the device screen. The basic idea behind media query driven repsonsive sites is to serve the same page to all browsers. When the content loads in the browser we first check the screen size (viewport) dimensions and apply additonal CSS rules to adjust our layout and its content accordingly.

### Design Philosophy

When we set out to design a repsonsive site we can choose to either design for larger devices and write media queries that adjust things when screens shrink in size (desktop down), or we can start designing our site for smaller devices and use media queries to adjust things as the screen gets larger (mobile up). Ultimately this should be dependent upon the content of your site and what devices you anticipate will be most used to view your content. With increasing mobile and tablet usage for browsing the web, (at the time of writing this lesson) mobile up, otherwise known as mobile first has become an increasingly popular strategy to use.

## Summary

- With an increasing number of different size devices browsing the web, having a responsive site design is crucial.
- It is ideal to use CSS media queries to create a single website that will respond to different size devices.
- Desktop Down describes designing your site for larger screens and making accomodations that adjust for smaller screens. 
- Mobile Up (Mobile First) describes designing your site for small screens and making accomodations that adjust for larger screens.

## Resources

- [Presentation Slides](https://docs.google.com/presentation/d/1j_i5pGPB5lHbgr4fpdUDheRBv2kAeOk_yhfd1Uc2f3s/edit?usp=sharing)
- [Implementing Responsive Design Book](http://www.amazon.com/gp/offer-listing/0321821688/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0321821688&linkCode=am2&tag=skillshare-20&linkId=YL7FOWID5V4BU5QY)
- [SweetHatClub.org (browse source code)](http://sweethatclub.org/)

<p class='util--hide'>View <a href='https://learn.co/lessons/responsive-strategies'>Responsive Strategies</a> on Learn.co and start learning to code for free.</p>

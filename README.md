### Quick Links
> Website <http://hermani.atwebpages.com/>

> Server (Cockpit)  <http://hermani.atwebpages.com/cockpit>

> *Login: admin*

> *Password: admin*

# Introduction

This document serves as an overview for this project. This website is an e-commerce site specialising in selling
luxury clothing for men, women and children. With the possibility of further
expansion into homeware and furniture, which won’t be available during this
preview.

This project is primarily written using the following technologies
- HTML
- SaSS/CSS
- RESTful API
- AJAX
- jQuery (Framework)
- Cockpit CMS (PHP Backend)
- JavaScript

I intend this website to be fully static, with the exception of the backend stack, which will be done through Cockpit CMS. This allows me to host the website on a static web provider, while having the server seperately elsewhere.

Although for this example, the front and back end will be hosted on the same server due to HTTP/HTTPS blocking the api requests. This is due to the front-end having a secure HTTPS encryption, while the backend is only HTTP.

## [SAE] Requirements & Locations

1. Gridsystem is present throughout the whole site, please refer to the css and sass files in the /css directory.
2. Mockup can be found in the PDF included with this repository
3. Validation form is present on the register page. Login is disabled. Find it at http://hermani.atwebpages.com/register.html or navigate using the sidebar - menu > login > create new account
4. Gallery can be accessed on any product
5. Touched up images can be seen on the website. If you navigate to Men > Shirts, you can see the first result contains the unedited pictures. The edited versions can be seen as product thumbnails for result pages.

Before and After 1: 

![alt text](https://i.imgur.com/WSlofur.png "Unedited Shirt Image")

Before and After 2: 

![alt text](https://i.imgur.com/QdO4kkB.png "Unedited Shirt Image")

6. AJAX loading data from JSON can be found in js/search.js and js/collection.js . [Bug] There is a problem when loading the local seasonal collection json file on the live page. However, it can be seen working when using localhost.
7. A number of vector images can be found on the site. The shopping bag is stored locally and scales when hovered. Remaining vectors are sourced from font-awesome 4, the heart has some CSS as well.
8. Browser identification occurs from js/functions.js and is present on most pages. An alert will show up if the user is using Internet Explorer or an Unknown browser.



## General Project Overview

Hermani is a luxury retailer, selling a variety of clothing products and apparel,
ranging from shoes, shirts, bags and trousers, all the way to homeware and furniture.
The goal of this site is to create a high-end luxury experience for the user while
shopping on the site, while providing easy to navigate menus and a great browsing
experience.

*The site is fully responsive starting from mobile devices all the way to 1080p, 2K and
4K screens. It will offer a mostly monochromatic colour theme to aid in accessibility
with high contrast colours, and readable fonts, which will also in turn further aid the
luxury aspect and simplicity of modern day retailers such as Gucci, Chanel or
BrownsFashion.*

## Features Overview
These are the features implemented within the project using JavaScript.
- Image Gallery
- Interactive Navigation
- Form Validation (Register Page)
- Reading From JSON Using Fetch & AJAX
- Fully modular categories and products

*For more information regarding features please check the attached proposal & mockup PDF.
Some of the features that didn't make it into the final version are **search** **basket overlay***

## Pages
- Landing Page
- Categories
- Subcategories (men, women, kids, collection)
- Basket Page
- Products Display Page
- Product Page
- Login Page
- Register Page

## Methodologies

The site is going to be fully responsive, taking a mobile-first approach using the
atomic design. This will ensure a consistent experience across all platforms, a
mobile-first approach will additionally aid in the development phase, requiring less
styling to be written for the entire site.

In terms of JavaScript code, I've taken mainly a functional programming approach as it's more suited for the web.
I've used a number of functions and methods alongside loops (for loops, if statements, etc) in order to achieve a reliable way to output data on the site. This also means taht the overall site experience is better.

# Design

In terms of other ecommerce sites and design style, there are multiple approaches.
Apple’s website opts for a simple, yet intuitive design, where at a quick glance you
can select what type of product you’re looking for. Upon clicking, more options are
shown to you below the navigation in order to show you the individual products
within that category.


I enjoy the simplicity of this design, and I wanted to see if I could apply it to a clothing
brand, so looking a bit deeper I created a moodboard (shown below) which shows
how different fashion brands (Gucci, Browns, Chanel) stylize themselves and create a
brand identity with their websites.


All of those sites contain a very simple and minimalistic approach to
their design. I intend to create a similar visual style using a grid system, while
maintaining a monochromatic colour approach.


The site’s landing page will be composed of a standard
horizontal navigation, at the top of the page. This nav will include the different
categories (or a shop) as well as your basket, and a login button.


Both the left and the right side will be primarily used to whitespace, this will give the
site some space to breathe, and focus the user’s attention on the centre of the
screen. The central part of the website will be focused on one featured project and then
recommended products. These could be products that are on sale, or generally
popular.

In terms of the basket itself, I plan to have an overlay, which will provide the user with
information about what’s currently in their basket. I’m not sure how much of this will
be doable in JS itself, but at the very least the overlay will be present. This will have
items currently in the basket, their cost (individual and total), the ability to close the
basket, checkout, or view the basket fully.

In terms of the product page, I will likely implement a list style view similar to one
that can be found on amazon’s website. This will be either when searching for a
product, clicking on a category or both. The alternative to this would be a card style
design, where the list of products is presented in square or rectangular fashion.
A simple mockup can be seen below.

Lastly, the page will also offer a register and login pages, where the user can enter
their information to either login, or register an account. This will be a simple card in
the centre type of form.
A mockup of some pages can be seen as follows. Starting with the landing page for
desktop and mobile, followed up by a product page, and buying a product mockup.

The mockup can be found here for further inspection:
<https://xd.adobe.com/view/93d53879-847c-46dc-a847-9c8d181c8bbc-c686/?fullscreen>

While these are some early concepts, the final product may differ in its final design.

However, these are showing and representing the overall feel of the website.

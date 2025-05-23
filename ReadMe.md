### Responsive Portfolio Website using HTML, CSS, and JavaScript.
This is a responsive personal portfolio website developed using HTML, CSS, JavaScript, and Bootstrap 5. It includes smooth animations with the AOS (Animate On Scroll) library and is fully responsive across different devices.

## Prerequisites
* You Should Know Basic or Intermediate of HTML, CSS and JavaScript
* This website is developed by bootstrap 5 copy below code:

# Bootstrap 5 CSS CDN Link:
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" crossorigin="anonymous" />
# JavaScript jQuery CDN
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
# Bootstrap Icons
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.4/font/bootstrap-icons.css"/>```

## AOS Animation Library Installation

# Basic setup
Add Styles in `<head section>` :
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

Add script right before closing `</body>` tag, and initialize AOS :
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>

# Using package managers
Install `aos` package:
* `yarn add aos@next`
* or `npm install --save aos@next`

You need to Import script, styles and initialize AOS:
Also import AOS from 'aos';
import 'aos/dist/aos.css'; // You can also use <link> for styles
// ..
AOS.init();

In order to make it work you'll have to make sure your build process has configured styles loader, and bundles it all correctly.
# How to use it ?
1. Initialize AOS:
// initializing AOS library
AOS.init({
  duration: 1000,
  offset: 50,
});

2. Set animation using `data-aos` attribute:
<div data-aos="fade-in"></div>

## My Project Contains
* Sticky Responsive Navigation Bar
* Hero Section
* Expertise section
* Skill Section with Progress Animation
* Working Portfolio Section
* Testimonial Section
* Blog Section
* Contact Section
* Footer Section
* Fully Responsive for all devices

## Font Family
 I have Used Google Fonts - Josefin Sans 
<!-- google font link -->
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>


#   M y p o r t f o l i o  
 
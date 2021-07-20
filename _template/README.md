# GDI Course Template

*Work in Progress...*

This template is for creating open-source HTML slide content for **Girl Develop It** courses.

GDI's HTML slides are powered by [Reveal.js](https://revealjs.com/), the popular HTML presentation framework. For simplicity and ease of use, the Reveal.js files are served via CDN.

- [How to Use this Template](#how-to-use-this-template)
- [Template Content](#template-content)
- [Example Course Folder](#example-course-folder)

<hr>

## How to Use This Template

Create a copy of the `gdi-course-template` folder.

Update the copied folder to the new course name.

Create course content in `class.html`:
  * Update course name in the `<title>` tag.
  * Update course name in the `<footer>` tag.
  * If the course is a multi-class series, create and number additional `class.html` files:
    * For example: `class1.html`, `class2.html`, etc.

If incorporating images/media, add them to the `assets/imgs` folder.
  * Include credit /attribution to image(s) when possible.

Update the `README.md` file.

Update the `Marketing.md` file.

## Template Content

* `assets` folder contains:
  * `css` folder with GDI theme customization for reveal.js
  * `fonts` folder for GDI theme fonts
  * `imgs` folder that holds:
    * GDI logos and stock images used in the template / starter slides.
    * Images for courses should be stored `imgs` folder.

* `demo-gdi-slides.html`
  * *(Work in progress)* This is meant to showcase ways to use reveal.js's features for GDI content, as well as to outline GDI style guidelines. Copy code/section snippets from this file as needed.

  * Note: The demo slides contain common use cases of reveal.js for GDI content. Interested in more ways to use the framework's robust features? Visit the [reveal.js website](https://revealjs.com/) for a full demo.

* `README` files
  * README.md: Should contain course information that guides instructors on how to teach the couse 'out of the box'.

  * Marketing.md: Should contain course detail/copy that the GDI Operations team uses to promote the course. 

* `class.html`
  * This is the primary file that a content/course creator will work in.
  * It contains sections for the course slides. Every `section` element or tag corresponds to a single slide.
  
```html
<div class="reveal">
  <div class="slides"> 
    <section>Slide 1</section>
    <section>Slide 2</section>
    <section>Slide 3</section>
  </div>
</div>
```
  * By default, `class.html` contains the starter slides or sections listed below. 
  * *Blank* slides are to be filled out for a new course or when a course is updated.
    * GDI Welcome and Logo
    * GDI Mission Statement
    * GDI Code of Conduct
    * GDI Marketing Promo
    * Course Title *(Blank)*
    * Instructor (and TA) Intro *(Blank)*
    * Student Intros / Ice Breaker *(Blank)*
    * Housekeeping
    * Course Outline *(Blank)*
    * Course Goals *(Blank)*
    * Course Content *(Blank)*
    * Course Conclusion
    * Feedback Survey *(Blank)*
    * Q & A
    * Resources *(Blank)*
    * GDI Upcoming Courses promo *(Blank)*
    * Instructor Contact *(Blank)*
    * Thank You

## Example Course Folder

For an example of how this template folder is used, please see the ....*To be added*
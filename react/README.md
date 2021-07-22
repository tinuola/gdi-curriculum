# README

*Work in Progress...*

This template is for creating open-source slides and content for GDI courses. 

## Template Content
* Reveal.js scaffolding:
  * `css, dist, examples, js, plugin, test, gulpfile`
  * These are default folders and files that power the template slides, and also contain GDI configurations.
  * Edits to the scaffold should be done at the template level via a pull request. Do not edit the scaffold as you create a course.

* `assets` folder
  * Contains GDI logos and stock images used in the template slides.
  * New images used to create a course should be stored here in a `course-img` folder.

* Demo files
  * *(work in progress)* `demo-gdi-slides` This is meant to show the various ways to use reveal's features for GDI content as well as outline GDI style guidelines. It's currently still in progress; so for now the `demo-revealjs-slides` file is a better example of what reveal.js can do.

* READMEs
  * Instructor README: Should contain course information that guides instructors on how to teach the couse 'out of the box'.
  * Marketing README: Should contain course detail/copy that the GDI Operations team uses to promote the course. 

* template.html
  * This is the primary file that a content/course creator will work in.
  * It contains sections for the course slides. Every `section` element corresponds to a single slide.
  
  ```html
	<div class="reveal">
		<div class="slides"> 
			<section>Slide 1</section>
          <section>Slide 2</section>
          <section>Slide 3</section>
    </div>
  </div>
  ```
  * By default, it contains the following starter slides or sections:
    * GDI Welcome and Logo
    * GDI Mission Statement
    * GDI Code of Conduct
    * GDI Marketing Promo
    * Course Title *(blank)*
    * Instructor (and TA) Intro *(blank)*
    * Student Intros / Ice Breaker *(blank)*
    * Housekeeping
    * Course Outline *(blank)*
    * Course Goals *(blank)*
    * Course Content *(blank)*
    * Course Conclusion
    * Feedback Survey *(blank)*
    * Q & A
    * Resources *(blank)*
    * GDI Upcoming Courses promo *(blank)*
    * Instructor Contact *(blank)*
    * Thank You

## How to use this template

Rename the `gdi-course-template` folder to the new course name.

Update `template.html` to:
* `index.html`: If the course is a single class
* `class#.html`: If the course is a multi-class series such as a cohort.

Create your course content. If incorporating images/media, add them to the `assets` folder.

Update the `Instructor README`.

Update the `Marketing README`.

## Example Course

For an example of how this template folder is used, please see the ....*To be added*
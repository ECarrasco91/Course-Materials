---
# Provide values for an array of lessons,
#   with each lesson having a name, url, and date

title: Android User Interface
lessons:
  - name: XML Intro
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/xml-lesson
    date: Wednesday, 10/12
  - name: Views 101
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/views-101-lesson
    date: Friday, 10/14
  - name: Views 102
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/views-102-lesson
    date: Friday, 10/14
  - name: Layouts
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/layouts-lesson
    date: Monday, 10/17
  - name: ListViews/Adapters
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/listviews-list-adapters-lesson
    date: Monday, 10/17
  - name: RecyclerViews
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/recyclerview-lesson
    date: Tuesday, 10/18
  - name: AlertDialogs - Covered in the Developer Documentation Lesson
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/workflow-and-dev-tools/developer-documentation-lesson
    date: Wednesday, 10/19
  - name: Detail View Lesson
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/databases/detail-view-lesson
    date: Thursday, 10/27
  - name: Constraint Layout
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/constraint-layout-lesson
    date: Friday, 10/28
  - name: Material Design Introduction
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/material-design-intro
    date: Monday, 10/31
  - name: Drag & Swipe wi/ RecyclerView
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/drag-and-swipe-with-recyclerview
    date: Thursday, 11/3
  - name: Toolbars and Menus
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/toolbars-and-menus-lesson
    date: Thursday, 11/3
  - name: Simple Animation
    url: https://github.com/ga-adi-macaron/Course-Materials/tree/master/lessons/user-interface/simple-animation
    date: Friday, 11/4
  - name: Accessibility
    url: 
    date: 
  - name: Notifications
    url: 
    date: 
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) {{page.title}}

<ul>
  {% for lesson in page.lessons %}
  <li>
    {% if lesson.url %}
      <a href="{{lesson.url}}">{{lesson.name}}</a>
    {% else %}
      {{lesson.name}}
    {% endif %}
    {% if lesson.date %}
      ({{lesson.date}})
    {% endif %}
  </li>
  {% endfor %}
</ul>

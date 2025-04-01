# MODULE 5 KNOWLEDGE CHECK: Omega Solutions
---
---

#### For this project, I decided to make a website for a company called Omega Solutions that helps companies achieve...some solutions.

---
---
---


## TABLE OF CONTENTS

1. [Home](#1-home)

2. [Navigation Bar](#2-navgation-bar)

3. [Robot Helper](#3-robot-helper)

4. [About](#4-about)

5. [Registered Users Table](#5-registered-users-table)

6. [Registration Form](#6-registration-form)

7. [Contact](#7-contact)

## 1. Home

I used an image for the home/hero section and applied some styling to make the image fit the dark theme better. I put this in the `<html>` element to set the whole page to a dark theme:
```html
<html lang="en" data-bs-theme="dark">
```
The main container-fluid `<div>` is set to `position-relative` to layer the image and "Welcome" `<h1>` correctly using `position-absolute`.

---
---

## 2. Navgation Bar

I followed the basic bootstrap nav classes here for a regular and collapsible navbar. I made it sticky with `fixed-top` and also moved the menu items over to the right with `ms-auto` in the `<ul>`.

---
---

## 3. Robot Helper

Had a silly idea to make an "assistant" robot as the smaller image, with two buttons for the choices to be helped with. I preferred the look of `btn-outline-secondary` over the normal button, so went with that. Did some bootstrap gymnastics (or at least it felt like it lol) to get the robot image centered and cropped and also some styling to meet the `rounded-circle` requirement.

---
---

## 4. About

Basic "About Us" section in a `container-fluid` with a `<h2>` and `<p>`s.

---
---

## 5. Registered Users Table

Created a dark-theme table with some Omega Solutions "employees". The main styling is here:
```html
<table class="table table-hover mt-4 shadow table-bordered border border-3 table-striped table-responsive">
```
Responsive, bordered to match registration form, hover effect, striped and a subtle shadow.

---
---

## 6. Registration Form

The main form for registration. Applied `was-validated` validation to form with `valid-feedback` and `invalid-feedback` on each input. Kept the form in the dark mode theme as well. Made 2 separate `col-md-6` conatainers for "First name" and "Last name" to put them side-by-side on screens larger than 767px.

---
---

## 7. Contact

Basic "Contact Us" section providing an email to contact the helpdesk. A `container-fluid` with an `<h2>` and `<p>`s.

---
---

## 7. Footer

Basic "Footer" with one `<p>` displaying company name copyright in a `container-fluid`.


[back to top](#module-5-knowledge-check-omega-solutions)
---
title: "Steven Coy - Web Developer Projects"
layout: "single"
toc: true
toc_sticky: true
share: false
author_profile: true
author: Steven Coy
---

<link rel="stylesheet" href="assets/css/custom.css">

## Web Developer

The primary role I am looking for is a web developer...

## Projects

### GridSquid (2022) - Custom Grid Creator

<a target="_blank" rel="noopener noreferrer" href="https://gridsquid.ragmats.com/"><img style="padding: 10px; border: 0px;" src="https://gridsquid.pythonanywhere.com/static/gridsquid/img/gs_logo_long.svg" alt="GridSquid Logo" width="100%"/></a>

GridSquid is an educational single-page application coded in JavaScript and Python (Django) that lets users make custom grids of images with associated sounds and captions. I learned so much from this project, namely how to set up a CRUD-capable backend with user authentication and custom APIs as well as a responsive front-end UI optimized for user engagement and experience.

**Features Include:**

- A front-end written in JavaScript, HTML, and responsive CSS ([Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/){:target="\_blank"}{:rel="noopener noreferrer"} in part, the rest hand-coded).
- A fully CRUD-capable backend written in [Django](https://www.djangoproject.com/){:target="\_blank"}{:rel="noopener noreferrer"}/Python with many custom-written APIs.
- User authentication and password resets via email.
- Guest accounts (w/ same user access) that get deleted after 30 days checked daily via a custom command automated task.
- User accounts for creating and storing sets of custom grids containing images, audio, and/or text captions.
- Integrated cropping functionality for user-submitted images using the [Cropper.js](https://fengyuanchen.github.io/cropperjs/){:target="\_blank"}{:rel="noopener noreferrer"} library.
- Backend image compression using [Pillow](https://python-pillow.org/){:target="\_blank"}{:rel="noopener noreferrer"}.
- User-uploaded audio files converted to mp3 using [Pydub](http://pydub.com/){:target="\_blank"}{:rel="noopener noreferrer"}.
- File/mime type validation of image and audio files via [Python Magic](https://github.com/ahupp/python-magic){:target="\_blank"}{:rel="noopener noreferrer"}
- The option to record and save audio using [Microphone Recorder to Mp3](https://github.com/closeio/mic-recorder-to-mp3){:target="\_blank"}{:rel="noopener noreferrer"}
- A memory game that can be played on any grid complete with sound effects and CSS "card flip" animations.
- Auto-generated quizzes for any grid that can be taken with audio only, text only, or both.
- A collection page called "MyGrids" where all user grids and can be viewed and organized into albums.
- Deployed on [PythonAnywhere](https://pythonanywhere.com/){:target="\_blank"}{:rel="noopener noreferrer"}.

**View this project in action:** [gridsquid.ragmats.com](https://gridsquid.ragmats.com/){:target="\_blank"}{:rel="noopener noreferrer"}

**Video demo:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/qhYY0cqv-ig" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Oopsie (2021) - Anti-Fertility Calculator

<a target="_blank" rel="noopener noreferrer" href="https://oopsie.ragmats.com/"><img style="padding: 10px; border: 0px;" src="https://oopsie.pythonanywhere.com/static/images/oopsie_logo.svg" alt="Oopsie Logo" width="100%"/></a>

Oopsie is a web-based anti-fertility application that celebrates the wonderful, life-altering event of not getting pregnant. It was built with Flask/Python, and JavaScript. In this project, I learned how to set up a backend in Flask and deliver the user calculations based on their input and data from a database. I also learned how to work with classes for cleaner code, timezone localization, and managing user sessions.

**Features Include:**

- A main page that gives the user their "oopsie" chance as a percentage based on their method inputs.
- Responsive design using CSS media queries.
- A "permanent" session for a persistent user experience.
- Timezone localization.
- A calendar view that displays the current, last, and next week of oopsie chances.
- A JavaScript similation/mini-game.

- **View this project in action:** [oopsie.ragmats.com](https://oopsie.ragmats.com/){:target="\_blank"}{:rel="noopener noreferrer"}

**Video demo:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/flOwjttW78A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

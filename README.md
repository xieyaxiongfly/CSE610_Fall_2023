---
layout: home
title: CSE610 Mobile Network & Sensing 
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Mobile Networks & Sensing 
---

## Special Topics on Mobile Sensing & Mobile Networks 
{: .fs-9 } 

Fall 2022, University at Buffalo 
{: .fs-6 .fw-300 }

**Instructor:** 


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

**Course Description:** Nowadays, wireless technologies (cellular, Wi-Fi, mmWave) do not only provide data service but also cater to diverse applications including indoor localization, contact-free activity sensing, medical implant tracking and charging, virtual reality (VR) and autonomous driving. This course introduces the students with fundamentals in mobile networking and the state-of-the-art mobile sensing applications in the Era of Internet-of-Things. Mobile sensing is an active research area which involves wireless communication, signal processing, human computer interaction, machine learning and hardware prototyping. The intrinsic nature of sensor-free and contact-free makes mobile and wireless sensing particularly appealing in current pandemic compared to traditional sensor-based sensing. The latest research in mobile sensing has enabled many novel and exciting applications. For example, Wi-Fi signals can now be employed to differentiate very similar materials such as Pepsi and Coke. You can place your phone on the desk and turn the desk surface into a touch (input) panel with acoustic sensing. We can employ LoRa signals to sense your respiration even 50 meters away with a wall in between without any sensors. We will explore the state-of-the-art of both mobile networking and mobile sensing and make our hands dirty by working on some research projects.


**Lecture Time & Location:**Tuesday 2:00PM-4:00PM, 440 Park Hall, North Campus

**Prerequisites:** CSE 489/589 Modern Network Concepts

**Slack:** We will use slack to ask questions. Pleas join the slack via this [link](https://join.slack.com/t/slack-pvl4009/shared_invite/zt-225v7oixh-ikMtTMzvE8IS2oX1MFXtJQ).


**Grading:** The course grade will be based on the following components.

- Class Participation: 10%
- Paper Presentation: 20%
- Midterm: 20%
- Course Project: 50%



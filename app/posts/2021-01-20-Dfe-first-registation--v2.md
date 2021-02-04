---
title: Dfe first registation  v2
description:
date: 2021-01-20
---
This is the second iteration of a registation journey option that starts with the DfE, users enter their TRN details, create an account and then are handed over to the relevant provider. 

In this version we have altered:
1. the beginning of the journey to deal with the 'name issue' - the name the user enters into the TRN fields needs to match what is stored on the DQT. We found that updating the DQT wasn't top of mind when names were changed and it could get out of synch. 
2. added the ability to find your school, so that we can look up the URN of the school to check for funding eligibility
3. added the diversity questions that the DfE need to the end of the journey  


## User needs

<b>As a teacher </b>
I need to register interest and apply for an NPQ course at my chosen provider<br />
<b>As a teacher </b> 
I need to provide the correct data about myself in the application form (TRN, DOB, Names)


{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Start",
      img: { src: "1.png" }
    }, {
      text: "Share choices with provider",
      img: { src: "2.png" }
    }, {
      text: "Teacher reference number check",
      img: { src: "3.png" }
    }, {
      text: "Teacher reference number reminder",
      img: { src: "3b.png" }
    }, {
      text: "Name change",
      img: { src: "4.png" }
    }, {
      text: "Updated name",
      img: { src: "4b.png" }
    }, {
      text: "I don't know if i changed my name",
      img: { src: "4cc.png" }
    },{
      text: "Name not updated",
      img: { src: "4c.png" }
    },  {
      text: "Change details on the DQT",
      img: { src: "4d.png" }
    }, {
      text: "Qualified teacher check",
      img: { src: "5.png" }
    }, {
      text: "Contact details",
      img: { src: "6.png" }
    }, {
      text: "Password",
      img: { src: "7.png" }
    }, {
      text: "Confirm email",
      img: { src: "8.png" }
    }, {
      text: "Email confirmation",
      img: { src: "9.png" }
    }, {
      text: "Your school",
      img: { src: "10.png" }
    },  {
      text: "Find your school",
      img: { src: "11.png" }
    }, {
      text: "Choose your school",
      img: { src: "12.png" }
    }, {
      text: "Your school",
      img: { src: "13.png" }
    }, {
      text: "Equality - ethnicity",
      img: { src: "14.png" }
    }, {
      text: "Equality - gender",
      img: { src: "15.png" }
    }, {
      text: "Equality disability",
      img: { src: "16.png" }
    }, {
      text: "Check your details",
      img: { src: "17.png" }
    }, {
      text: "NPQ account created",
      img: { src: "18.png" }
    }]
}) }}

## Iterations
This is the second iteration of this journey

## User research
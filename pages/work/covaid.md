---
layout: default
title: CovAid
permalink: /covaid/
---

# CovAid

CovAid is a web application that facilitates deliveries to those in need during pressing times by connecting at-risk users with volunteers willing to donate necessities.

<div style="max-width: 560px; margin-bottom: 1.5em;">
  <!-- Embedded YouTube video (starting at 47s) -->
  <iframe width="560" height="315" 
          src="https://www.youtube.com/embed/B3bwGrfTrjA?start=47" 
          title="YouTube video player" frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
          allowfullscreen>
  </iframe>
</div>

## Inspiration
The world we live in has changed dramatically amidst the COVID-19 outbreak. Although some of us are safe at home with the proper equipment, a large portion of the population does not have access to essentials. In analyzing the issue, we realized the immunocompromised currently had no access to essentials as they could not simply leave their houses to go to a grocery store.

We decided to provide a solution to this problem by creating a website in which users can make virtual requests for items, such as toilet paper or hand sanitizer, and volunteers can accept these requests to donate supplies to them. As there is no preexisting platform that allows for direct pairings between users and volunteer deliverers, we believe this is the perfect solution to help those most impacted by COVID-19.

## What it does
CovAid is a web application that connects volunteers to those in need during the COVID-19 outbreak using AI-driven intelligence. The website connects at-risk users with volunteers willing to donate necessities. Users can make requests for items, and volunteers can respond to those requests. These pairings are created efficiently with a machine learning algorithm that takes into account factors such as the distance between the user and the volunteer.

**Sample Screenshots:**

**Homepage**  
<img src="/pages/work/covaid-homepage.png" alt="CovAid Homepage" style="max-width:100%; height:auto; margin: 1em 0;" />

**Sign-Up Form**  
<img src="/pages/work/covaid-signup.png" alt="CovAid Sign-Up Form" style="max-width:100%; height:auto; margin: 1em 0;" />

**Request View**  
<img src="/pages/work/covaid-requests.png" alt="CovAid Request View" style="max-width:100%; height:auto; margin: 1em 0;" />

## How we built it
We integrated Flask, JavaScript, and jQuery on the back-end, and HTML with Bootstrap on the front-end, to build CovAid from scratch. We used SQL to operate the user database and the Google API to calculate distances and estimated times between users. We also developed a Machine Learning Neural Network model (using Keras, NumPy, Pandas, and Sequential Dense layers) to sort requests on a volunteer’s page, ensuring that the most relevant requests appear for each volunteer.

## Challenges we ran into
Communicating between Flask views and various HTML templates was tricky, as we had to handle dynamic site form data and a database. Understanding how to integrate a database efficiently took time. Another major challenge was implementing our ML sorting algorithm within the Flask and HTML environment, as we had to process live user data and pass it to the model.

## Accomplishments that we're proud of
We’re proud that we were able to build a fully-functioning website and effectively collaborate as a team. We split into two teams—one handling front-end and back-end integration, and the other focusing on the machine learning aspect. Along the way, we gained a variety of CS skills and contributed something meaningful to help our community. We also demonstrated another scenario where AI can simplify and improve lives.

## What we learned
Beyond learning new software like Bootstrap and Flask, we gained an appreciation for the impact of small acts of kindness. Even a single act—like delivering essential goods—can have a positive, meaningful influence on someone else’s life, especially during challenging times.

## What's next for CovAid
We hope for CovAid to become more widespread and have a greater global impact. Our vision includes a more interconnected system where everyone has easy access to essentials. As the world continues to evolve, we aim to help keep people safe, healthy, and well-equipped.

---

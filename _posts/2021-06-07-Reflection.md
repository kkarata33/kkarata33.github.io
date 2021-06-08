---
layout: post
title: Project Reflection - MoodSpace
---

## MoodSpace - a Spotify Soundtrack Generator
####by Kendall Arata, Michael Ting, and Ben Brill

> 1. Overall, what did you achieve in your project?

Our group had the idea of MoodSpace, a Spotify soundtrack generator that utilizes machiene learning to classify and match songs and movies based on their mood. For the machiene learning, we used TensorFlow and neural networks as well as SQLAlchemy deployed on the backend to construct a model that allows the user to select a famous movie scene (Titanic, Good Will Hunting, etc.) and have it display users Spotify songs that match that mood. We used Flask on the front end to serve as the recommendation interface.

> 2. What are two aspects of your project that you are especially proud of?

I am especially proud of the design of the web app and fluidity of the website. I love anything creative, so designing things, especially web pages and apps is my forte. By first coming up with the colors we wanted to use (a purple gradient to represent the continuity of a mood), and then applying it to a fully functional website, I was able to create not only an aesthetically pleasing page, but also a functional and interactive one that the user would have no problem interacting with.

I am also especially proud of our ability to come up with creative ways to solve accuracy problems in our machiene learning pipeline. Initially, our machine learning clustering method functioned arbitrarily, based on the 8 different clusters our pipeline sorted them into. We declined to declare the designated mood of these clusters in order to avoid introducing bias into our model. However, this raised the issue of accuracy: how accurate was our model at predicting unseen data? So, we transitioned to utilizing neural networks to generate unique weights for each song. By adding more embedding layers and dropout layers, we increased accuracy dramatically without severe overfitting.

> 3. What are two things you would suggest doing to further improve your project? (You are not responsible for doing those things.)

To things we could do to further improve our project would be to add more movies to our collection as well as display more unique insights on the home page besides the standard (top songs and top tracks)

> 4. How does what you achieved compare to what you set out to do in your proposal? (if you didn't complete everything in your proposal, that's fine!)

Honestly, I think our team did really well in working to achieve almost everything we initially stated in our abstract. Although we didn't embed the Spotify Playlist Creation Functionality due to privacy reasons, we still were able to create a solid viable project that did indeed, match songs to the "mood" of movies.

> 5. What are three things you learned from the experience of completing your project? Data analysis techniques? Python packages? Git + GitHub? Etc?

I learned a lot about the various Python packages that we used, especially Flask and Spotipy. I interacted a lot with the Spotify API in order to display a users data on the app, and I also worked primarily in the front end, thus I needed to use Flask.

Another important thing I learned is that everyone has strengths and weaknesses.
I think our team really was able to work well together, since we were all for the most part interested in a different niche in the project, but

> 6. How will your experience completing this project will help you in your future studies or career? Please be as specific as possible.

This project is an excellent portfolio builder for (hopefully) a future career in UI/UX. As stated before, I really do love the design aspect of coding more than anything, and I think this project is a basic, but coherent representation of part of my design skills. I will definitely reference this project when applying to internships/jobs in UI/UX.

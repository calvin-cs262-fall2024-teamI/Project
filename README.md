# Project

## Team Members             
    * Allison Drouillard
    * Alim Darmenov
    * Jason Balliette
    * ZhongLin Niu
    * Madi McNearey
    * Jeton Cesaj    

## Problem Statement
Fitness is an integral aspect to longevity, good health, and well-being. Unfortunately, it can also be very overwhelming when planning workouts. What if you are selecting the wrong weights and hindering your own progress? Where would you even start? Perhaps you find it difficult to stay motivated? Our application addresses these issues and more!

## Vision Statement
This app will be designed for fitness enthusiasts, powerlifters, and gym-goers who want to achieve optimal physical performance without the stress of managing progression, scheduling, or approaching others at the gym for help. Power Sphere is a gym logging and social engagement app that empowers users to track and improve their workout performance through comprehensive weight progression tracking, customizable programs, and data-driven feedback on imbalances - all while fostering community interaction and healthy competition. Unlike most fitness trackers, Power Sphere will offer a wide range of workout programs published by fitness influencers, regular lifters, or created by the app team. Whether you are someone who likes to test new workouts or someone who wants to be on the safe side, this app will have you covered. Each program will have its progression technique to get stronger weekly, without having the user do any calculations or memorization. Our product will incorporate all these logging features into the social part of the app, in which you can ask for help in any exercise, share your experiences from using different workout programs, and be able to compete with other lifters of the same bodily proportions from all around the world. Unlike our competitors, we are providing an all-in-one fitness tool that takes doubt out of workout programming. 

## Components

1. User has his own profile

    * name, lastname
    * socials
    * Geographic Location(Can be used to find a gym buddie)
    * Type of fitness enthusiast (hybrid, powerlifter, bodybuilder...)
    * One rep max for major lifts (these are initially stored by user, but later calculated throughout time)

2. Workout Logger/ Program creator

    * Different kinds of exercises.
        - Cable
        - Leverage Machine
        - Barbell
        - Dumbbell
    * Progression Techniques 
        - Increase Reps
        - Increase weight
        - Decrease Rest time 
        - Increase sets
        - These are interchangeable based on performance of the user. They are cycled.
    * Metrics
        - Graph showing the one rep max growth as an indicator of strength increase
        - Body parts percentage worked out. Helpful using the API.
    * Api of exercises 
        - https://rapidapi.com/naeimsalib/api/work-out-api1
        - User searches for example leg, and created options show up such as (leg-curl)

3. The Sphere?
    * Q/A 
        - Integrated with the API for exercies where user can select a help button for the exercise and the forum will popup to write a question about that exercise on the sphere.
        - Other users can post images, videos or links to guides and other helpful info.  

    * Gym Buddy
        - Based on your geographical location, age, your workout program and other data, you can be matched with a workout buddie.
        - Most gyms allow you to bring a guest, so its doable in real life
        -Maybe this is a mix with Maddies idea. Not hard to implement.
        - This way you stop being the alone guy with a hoodie and headphones trying to fight your demons at the gym

    * Workout Programs
        - Users will be able to publish their own created workout programs.
        - There will be ratings attached to each program, and reviews
        - No use of workout programs API because thats just too much.

    * Leaderboard
        - The app will create a leaderboard with people of your own body proportions comparing strengths on major lifts.
        - Futureproof: There will be online professional coaches that can review if certain lifts are valid or not. (impossible to implement within this year)

    * Free Api for the forum
        -   https://success.vanillaforums.com/kb

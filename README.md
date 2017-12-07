# Waldo
Waldo assesment script

This is more for my reference then for others as I'll forget what this was all about in due time.

It took me a total of 3hours to complete.  

Over 60% of that was used up in testing - trying out different images and thresholds to get the "sweet spot".

30% of that was unfortnately setting up the environment as I normally work on a linux system and my home
system did not have cv2 installed on it.  Ended up deleting my version of python and numpy and using Anaconda to
install all of it.  Love, love, love Anaconda.  Never used it before but enviornment management is pretty sweet with it.

The last 10% was to actually write the code to fulfill this assignment:

Waldo Photos Engineering Project

The goal of this project is to produce a working system that can be used as a conversation piece during your on-site interview. Be prepared to:

    Present your solution to a group of smart engineers like yourself.
    Talk about the decisions that went into the creation of your solution.
    Explain how you see the solution evolving over time.
    Discuss the runtime characteristics of the system.
    Discuss technical design tradeoffs and the cost-benefit analysis of those decisions.

Deliverable

Using any language and data-store of your choice, write a console application that takes two arguments. The arguments are locations of two image files.

Example:

subimage ./images/image1.jpeg ./images/image2.jpeg 

The application should return information if one of the images is a cropped part of the other one. If yes, the application should also return the position of top-left corner of the cropped image within the original image.

Notes:

    The images may be provided in any order (the cropped image may be the first or the second).
    The application should work well on JPEGs with some lossy compression enabled.

You can make any additional assumptions, as long as you are explicit about these.

Please deliver the finished project in a publicly available repository on Github. Please title the repository as waldo-${ github-handle }.

Deliveries via private repos, BitBucket, or anything other than what is specified above will be disqualified.
Evaluation

The main areas we will be evaluating are:

    organization of responsibility
    performance
    resilience to failures.

# jobmatcher
a part of the elements of AI course

## Summary
A tool that matches a persons CV with many job-ads and gives a grade how well it matches, so that the best matching job-ads are presented first.
 


## Background
Searching for a new job today is a tedious task, job-ads are scattered on many sources and the content of the job-ad can be very poorly written or a big block of text that is difficult to decipher what is really needed. To have an AI match a persons CV with job-ads and give a matching number would mean that people looking for jobs would get help picking out those that have a high match and can focus less on those that match poorly.

My personal experience is that it is very difficult to decipher some of the job-ads and in some cases i have actually been very suited for a job but i did not understand it, since they used terms that i was not familiar with. It was only after discussing with AI this became evident.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
A person would need to create an account and upload their CV. This will then be analyzed and made in to some common, easy-to-read format and stored. Maybe there can be an add-on function for an AI asking questions for parts in the CV that is not clear or seem to be missing or if the user wants to add something more, like what type of jobs they are looking for.
The user would then define their sources for job-ads, maybe they use special channels in their field or they use a national provider like the swedish platsbanken. Then other criteria like specific search-words and location would be needed to limit the scope a bit.
Each morning an automatic script would run and fetch new jobs, match against each users CV and give a score between 0-100. 
When the user logs in, they would see the new job-ads sorted in order of best matches, can click and read more and maybe get a deeper analysis of why it is a good/poor match and some pointers of what to highlight or adress when customizing the CV towards the job-ad


## Data sources and AI methods
One data source is the CV, it is uploaded by the user.
The other data-sources for job-ads is a bit more scattered, swedish platsbanken has an excellent API for getting jobs, but LinkedIn is closed from all outside automatic retrieval.

## Challenges

Some users might not be comfortable having their CV sent to an american company without full transparancy how it is used. 

## What next?

Difficult to grow in to something other than hobby-project, people looking for jobs are not so in to paying for it and each search would cost tokens. Maybe consulting companies would be interested.


## Acknowledgments

* platsbankens API is an excellent way of doing an open solution

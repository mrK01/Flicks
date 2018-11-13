# Flicks
Week 1 Project: Flicks - Part 1
Due: Saturday, November 10th at 2:59am

Overview: This project lets users view a list of movies sourced from the The Movie Database API.

Video Walkthrough: Start with this  video walkthrough to complete a basic version of this assignment.

Submission Instructions: Follow the guide for Submitting Assignments.

Make sure you are adding and committing files in git as you complete features and milestones.
Be sure to include a README containing a GIF walkthrough of your app.
Use this README template in order to have a complete README.
Project setup: Completing this project requires the use of the android-async-http and the Glide libraries. Add dependencies for these libraries to the app/build.gradle file.

Check out The Movie DB API
Poke around in the The Movie Database documentation to familiarize yourself with the API's general structure and features.
"Now Playing" endpoint.
Sample Request:
https://api.themoviedb.org/3/movie/now_playing?api_key=a07e22bc18f5cb106bfe4cc1f83ad8ed in your browser.
API Key a07e22bc18f5cb106bfe4cc1f83ad8ed
Note: It's helpful to install the JSONView Chrome Extension to view the returned JSON more easily.
Mockups:

With required and a few optional user stories completed:

Movie DB 1 Movie DB 2

In portrait mode, the layout should look like:

Portrait mode

In landscape mode, the layout should look like:

Landscape mode

The required and optional user stories are outlined below.

User Stories
A user story is a way to capture requirements for an app from an end-user perspective. It is a common practice in app development and helps to simplify the way requirements are specified.

Required Stories
User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API. (5 points)
 Assignment Intro
 Networking and Parsing JSON
 RecyclerView implementation
Views should be responsive for both landscape/portrait mode. (3 points)
In portrait mode, the poster image, title, and movie overview is shown.
In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
Stretch stories
Display a nice default placeholder graphic for each image during loading (read more about Glide) (1 point)
Improve the user interface through styling and coloring (1 to 5 points depending on the difficulty of UI improvements)
For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones. (2 points)
Check the Project 1 Tips Guide to troubleshoot problems or get hints.

Cliffnotes:

(Cliffnotes) Android Directory Structure
(Cliffnotes) Constructing View Layouts
(Cliffnotes) Using the RecyclerView
(Cliffnotes) Working with ImageView
(Cliffnotes) Basic Event Handling
(Cliffnotes) Alternate Layout Files
(Cliffnotes) Using Strings and other Resources

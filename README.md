# You-Travel

This is a demo for **YouTravel**, a single-page application (SPA) video platform for travelers. The frontend was built with vanilla Javascript and the backend was built using a Ruby on Rails API.

Requires [YouTravel](https://github.com/jeffreyc86/phase3-travelproject-frontend) frontend and [YouTravel](https://github.com/jeffreyc86/phase3-travelproject-backend) backend.

Created in partnership with Flatiron cohort-mate [Jeffrey Chiu](https://github.com/jeffreyc86). 

## Features

YouTravel is a website that allows users to watch videos containing information, tips, and tricks about how to travel to various global cities. YouTravel relies on gifs, videos sourced from YouTube, and other imagery to guide users through the application. 

### Login/User Profile

Users can login to access their YouTravel account or sign up to create a new account.<br />
A user's login has validations. Upon a successful login attempt a user will be taken to their profile page, which contains videos that user has uploaded. 


![youtravel-login](gifs/yt-login.gif)

<br/><br/>
<br/><br/>
<br/><br/>

A profile page also includes a hidden form to upload additional videos (which we will use later).


![video-upload-form](gifs/yt-upload-form.gif)


### All Cities

When a user clicks on the "Cities" tab, they will be brought to the main cities page. When using the mouse to hover over an image of a city, the static image will animate into a gif.


![city-gifs](gifs/yt-city-gifs.gif)


### City "Show" Page

Once we click on a city gif, we are taken to that city's main page. This page contains a short description for the city as well as the travel-related videos by category (Food, Leisure, Cultural, Nightlife, and Walking Tour).


![tokyo-videos](gifs/tokyo.gif)


### Video "Show" Page

Clicking on a particular video takes us to that video's main page, which includes the video itself, as well as comments and likes. Users can play the video, like that video, and add a comment to the list of comments.


![tokyo-vid-1](gifs/tokyo-vid-1.gif)


Users are also able to update and delete their own comments. 


![tokyo-vid-2](gifs/tokyo-vid-2.gif)


### Signup

Users can also sign up for YouTravel for the first time. Upon successful login they will be directed to their profile page


![signup](gifs/signup.gif)


### Upload/Delete a Video

A user can upload a video to be added to a particular city's list of videos. 


![upload-vid](gifs/upload-vid.gif)


If a user is viewing a video that they uploaded, they can also delete that video from the YouTravel database.


![delete-vid](gifs/delete-vid.gif)

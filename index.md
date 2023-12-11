# Invasive Species Finder

## Table of contents

* [Motivation](#motivation)
* [Goals](#goals)
* [Usage](#usage)
* [Installation](#installation)
* [Development Status](#development-status)
* [About us](#about-us)
* [User Evaluation](./evaluation.md)

## Motivation
Hawaiian ecosystems are under high level of threat from numerous invasive
species from all over the world. Invasive species are a major threat to endangered species and native ecosystems. They compete with native species for resources, and can even prey on native species directly. Invasive species can also introduce new diseases to
the island and cause serious damage to the ecosystem or human beings.

## Goals
1. Geotagged photos of invasive species are collected from the public to pinpoint the location.
2. users share photos to check if a species is invasive or not either by the AI or experts.
3. create a community of people who are interested in finding and cleaning up invasive species.

## Usage

### 1. Login page

<img src="./doc/login-page.png" alt="login page" width=300 height=600 />

Users can login with their account using the Email and Password they created. Sign up link will lead to the sign up page. Forgot password link will lead to the reset password page. Sign up link will take user back to the sign in page to login.
Fully authentication is implemented by using Firebase UI Auth. 

### 2. Sign up page

<img src="./doc/signup-page.png" alt="signup page" width=300 height=600 />

Users can sign up by entering their Email, password, and phone number. The password must be at least 6 characters long.
Later, a location (zip or city) will be required to sign up so that the app can show the list of invasive species in the area.
### 3. Drawer

<img src="./doc/drawer.png" alt="drawer" width=300 height=600 />
<img src="./doc/drawer-posts.png" alt="drawer" width=300 height=600 />
<img src="./doc/help-page.png" alt="drawer" width=300 height=600 />
<img src="./doc/drawer-setting.png" alt="drawer" width=300 height=600 />
<img src="./doc/drawer-setting-dark.png" alt="drawer" width=300 height=600 />


The drawer contains the user's profile picture, name, and email. 
And it has the links to the homepage,
post page (which contains all the posts posted by the user), help page, 
setting page (where user can change the theme of the app),
and the sign out (which will lead back to sign in page).

### 4. List page

<img src="./doc/list-page.png" alt="list page" width=300 height=600 />
<img src="./doc/speices-detail-page.png" alt="list page" width=300 height=600 />

The list page shows all the invasive species that have been reported around user's
current location (5 miles circle). 
Users can click on the species to get into the detailed information page of that species.

### 5. Forum page

<img src="./doc/forum-page.png" alt="forum page" width=300 height=600 />
<img src="./doc/post-detail.png" alt="post detail" width=300 height=600 />
<img src="./doc/post-comment.png" alt="post comment" width=300 height=600 />
<img src="./doc/add-post.png" alt="add post" width=300 height=600 />
<img src="./doc/edit-post.png" alt="edit post" width=300 height=600 />

The forum page shows all the posts that have been posted by the users. 
Users can click on the post to get into the detailed post page.
In the detailed post page, users can see the post content, the post image, and the comments.
And also, users can add comments to the post.
The floating plus action button will take users to the add post page to create a new post.
The edit button on the top right corner of the page will take users to the edit post page to edit selected post.

### 6. Camera page

<img src="./doc/camera-page.png" alt="camera page" width=300 height=600 />
<img src="./doc/pick-image.png" alt="pick image" width=300 height=600 />
<img src="./doc/take-picture.png" alt="take picture" width=300 height=600 />
<img src="./doc/picture-preview.png" alt="picture preview" width=300 height=600 />

The camera page allows users to take a picture of the invasive species and upload it to the database.
Users can also pick an image from the gallery to upload.
The camera page will also show the preview of the picture that has been taken or picked.
The green pixelated face is the simulation of the camera view as the emulator does not open a real camera.

### 7. Message page

<img src="./doc/message-page.png" alt="message page" width=300 height=600 />
<img src="./doc/send-message.png" alt="message page" width=300 height=600 />

The message page shows all the messages that have been sent by the users.

### 8. Map page

<img src="./doc/map-page.png" alt="map page" width=300 height=600 />
<img src="./doc/map-marker-detail.png" alt="map page" width=300 height=600 />

The map page shows all the invasive species that have been reported by the users or added by admin on the map.
Each marker on the map represents a species. User can tap on the marker to get into the detailed information page of that species.


## Installation

After downloading, cd into the directory and invoke:

```
flutter run
```
On my platform, that brings up the iOS simulator and the following:

```
% flutter run
Launching lib/main.dart on iPhone 13 Pro in debug mode...
Running Xcode build...                                                  
 └─Compiling, linking and signing...                         3.2s
Xcode build done.                                           14.4s
[VERBOSE-2:FlutterDarwinContextMetalImpeller.mm(37)] Using the Impeller rendering backend.
Syncing files to device iPhone 13 Pro...                           119ms

Flutter run key commands.
r Hot reload. 🔥🔥🔥
R Hot restart.
h List all available interactive commands.
d Detach (terminate "flutter run" but leave application running).
c Clear the screen
q Quit (terminate the application on the device).

A Dart VM Service on iPhone 13 Pro is available at: http://127.0.0.1:63610/L5Qxu9BkbG0=/
The Flutter DevTools debugger and profiler on iPhone 13 Pro is available at:
http://127.0.0.1:9101?uri=http://127.0.0.1:63610/L5Qxu9BkbG0=/
```

## Development Status

Project Board: [https://github.com/orgs/invasive-species/projects/2](https://github.com/orgs/invasive-species/projects/2)

## About us

***Hangbo Zhang:*** 

Graduate student in Computer Science at University of Hawaii at Manoa. 

Email: [hangbo@hawaii.edu](mailto:hangbo@hawaii.edu)

Portfolio: [https://hangbozhang.github.io/](https://hangbozhang.github.io/)



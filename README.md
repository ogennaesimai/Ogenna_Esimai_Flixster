# Ogenna_Esimai_Flixster
Ogenna_Esimai_Flixster app

[//]: # (Flix)

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

[//]: # "📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step."

---

## Flixster Part 1

### User Stories
[//]: # "`TODO://` In the **User Stories section below**, add an `x` in the `-[ ]` like this `- [x]` for any user story you complete. (🚫 Remove this paragraph after after checking off completed user stories)"

#### REQUIRED (10pts)
- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ ] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ ] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthrough GIF
[//]: # "`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)"

<img src="https://github.com/ogennaesimai/Ogenna_Esimai_Flixster/blob/master/Ogenna_Esimai_Flixster_Video_Walkthrough.gif" width=250><br>

App Walkthrough GIF created using [ScreenToGif](https://www.screentogif.com/) v2.27.2

### Notes
Encountered some bugs while building the app. They were great learning experiences.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids



[//]: # "📝 `NOTE` Paste this template at the top of your existing `README.md` file from part 1 of this assignment. (🚫 Remove this paragraph after after checking off completed user stories)"

## Ogenna_Esimai_Flixster Part 2

### User Stories

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
- [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
- [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [x] Add a rounded corners for the images using the Glide transformations. (1 point)

#### ADDITIONAL
- [x] Added fitcenter for the images using the Glide transformations. 

### App Walkthrough GIF #4

<img src='https://github.com/ogennaesimai/Ogenna_Esimai_Flixster/blob/master/Ogenna_Esimai_Flixster_Video_Walkthrough_4.gif' title='Ogenna_Esimai_Flixster_Video_Walkthrough_4' width='400' alt='Ogenna_Esimai_Flixster_Video_Walkthrough_4.gif'/>

App Walkthrough GIF #4 created using [LiceCap](http://www.cockos.com/licecap/) v1.28

### App Walkthrough GIF #3

<img src='https://github.com/ogennaesimai/Ogenna_Esimai_Flixster/blob/master/Ogenna_Esimai_Flixster_Video_Walkthrough_3.gif' title='Ogenna_Esimai_Flixster_Video_Walkthrough_3' width='400' alt='Flixster_Video_Walkthrough_3'/>

App Walkthrough GIF #3 created using [LiceCap](http://www.cockos.com/licecap/) v1.28



### App Walkthough GIF #2

[//]: # "`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)"

<img src="https://github.com/ogennaesimai/Ogenna_Esimai_Flixster/blob/master/Ogenna_Esimai_Flixster_Video_Walkthrough_2.gif" width=250><br>

App Walkthrough GIF #2 created using [ScreenToGif](https://www.screentogif.com/) v2.27.2

### Notes
Encountered some bugs and scavenger hunts along the way. They were great learning experiences.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

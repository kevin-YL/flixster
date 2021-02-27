# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---
## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://media0.giphy.com/media/j9VUOwWhQcqWNNIxi7/giphy.gif" width=250><br>

### Notes
The most challenging part of this round of flixster was correctly configuring the sizes of the superhero tab's movie view cells. 
Besides the configurations that Tim walked us through in his instruction video, it was also necessary to set the "Estimate Size"
parameter to "None" in the Colleciton View's dimensions tab to allow proper display of the movie cells. Luckily, CodePath TA's
quickly helped students fix this issue.

____________________________________________________________________

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://media1.giphy.com/media/wYImVHYDSCQ6IhJ586/giphy.gif" width=250><br>

### Notes
The biggest challenge I faced whilst building this application was properly connecting the various outlets to their proper ViewControllers,
especially in terms of implementing the MovieCell.swift file. Due to issues with inheritance and setting up the right class for each outlet,
the project took several attempts to get working properly. Despite that, however, I found that creating Flix with the help of Tim Lee's thorough
instructions was relatively straightforward. 

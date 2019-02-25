# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF
<img src="http://g.recordit.co/CnuNxCVHvd.gif" width=250><br>

### Notes
When I was working on the tab bar controller portion, I had some trouble figuring out why I kept getting a black screen. I figure out eventually that it was because I didn't change where the arrow was pointing. It had to point to the Tab Bar Controller on the main storyboard rather than the first navigation controller that was made. 

---

## Flix Part 1

### User Stories
#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF
<img src="http://g.recordit.co/8OcD6KTEPI.gif" width=250><br>

### Notes
I got a "No such module" error when trying to import the Alamofire libaries, but after checking some previous questions in the Discussion System, I was able to resolve it using the top answer. 

The solution was to add the following lines to the Podfile to get the modules to work:
~~~~
pod 'AlamofireImage', '~> 3.3' 
pod 'Alamofire', '~> 4.4'
~~~~

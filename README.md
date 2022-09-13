# Flixter

Flixter is an app that allows users to browse movies from the [The Movie Database API](https://api.themoviedb.org/3/movie/now_playing?api_key=a07e22bc18f5cb106bfe4cc1f83ad8ed).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flixter Part 1

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://github.com/mdarwish2020/Flixter/blob/main/flixter.gif" width=250><br>

### Notes
Although the app seems rather straight forward, I faced many issues on my end in terms of having a server that'll be able to support what I'm doing and display it correctly. 
I was mainly using a MacinCloud managed server but it kept crashing, freezing, and experiencing a lot of latency. The main issue however, was when I was trying to get AlamofireImage setup. This is quite literally supposed to be the simplist part of the process but it gave error messages upon error messages when trying to get anything in terms of pods to work. Thankfully the fau remote server became available so I pivoted in that direction and was able to get everything setup super quickly with no issues, except that the simulator was not working. So, I decided to use the simulator on the MacinCloud server where the AlamofireImage files worked as package dependency not as a workspace file. In the end, I completed on MacinCloud so I can use the simulator to ensure everything is working the way it should be; then I went on the fau virtual portal and redid all the steps but with the workspace file (this was mainly to make sure I fully understood how to do everything). All I can see is that the build was successful but can't actually see the simulator.

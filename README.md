![blocJamImg](/images/blocJamImg.png)
Format: ![Alt Text](url)
















The Bloc Jams project is a culmination of the a series of UX Intensive Challenges where I concentrated on getting comfortable coding
JavaScript, understanding what DOM scripting and JQuery library and to use these to create a functional music player that displays on web browser.
To complete my education, I used Git and Github.

What would the finished app look like? At the end of these challenges, my music player displays album information, lists the songs for an
album, and include the basic music controls for playing, pausing, skipping forward/backward, and adjusting the volume.

LESSONS LEARNED.

-- To create user stories for these particular design and what a acceptance criteria is. I've provided a sample

Example :

User story: As a listener, I want to see the album's songs and play/pause songs by clicking on them so that I can change tracks.

Acceptance criteria:
I see a list of the album's songs.
When I click on a song, it plays.
When I click on a playing song, it pauses.
When I hover over a song, it displays a "play" button in place of the song number.
The currently playing song displays a "pause" button in place of the song number.
A paused song displays a "play" button in place of the song number.

-- Translate the pseudocode or English solution into Javascript, a very valuable
lesson. Definitely worth the time it took me to learn how to do this.

I learned that pseudocode - is code that is meant to be read by humans not machines.
As a coder, I am expected to write pseudocode so I can define the structure and flow
of my final code and not have to worry about the syntax. The pseudocode connects
how humans think and how machines think.

Problem (human)  The music player is not rendering the song data to the HTML.
Solution (written in pseudocode) // no right or wrong way to write this.
 for_ each album.songs as songs
   song-element =
   <tr>
   <td>index</td>
   <td>song.title</td>
   <td>song.duration</td>
   append song_element to #song-list
   end for_each

JavaScript solution:
{
  album.songs.forEach( (song, index) => {
   });
}

-- learned how to use .indexOf() method.
-- learned how to use and become comfortable working with ranges.
-- Deploy my entire blo-Jams project on to a webhosting site - NETLIFY.

Reflection:
I became comfortable at using Git and Github, and JavaScript. A large part of this
is due to the fact that my mentor pointed out to me how with her ease in coding
the challenges - that I just needed to apply myself.

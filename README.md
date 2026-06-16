https://bandogod.github.io/The-All-Timer-Today-Timer/


I wanted a way to rank my favorite songs without having to do a giant bracket, so I made this little project. It lets you go through a big list of songs, listen to previews, and slowly narrow everything down into a Top 25.

It's all in one HTML file, so you don't have to install anything or make an account.

How it works

I realized that putting 1,000+ songs into a normal bracket didn't really work because a great song could get knocked out immediately by an even better one. So I broke it into a few steps:

1 Triage 

Songs show up one at a time and you can listen to a short preview. You quickly decide if you want to keep it or cut it.

2 Matchups 

After you've cut down the list, the remaining songs go against each other two at a time. You pick whichever song you like more. In the background, the program uses a sorting method to turn all of your choices into a ranking.

3 Top 25

At the end, you get:

Your #1 song
A ranked Top 25 list
Honorable mentions
A breakdown of each song's wins and losses

The app also saves your progress automatically, so you don't have to finish everything in one sitting.

Using it
Get a CSV of your songs. I usually use Exportify to export a Spotify playlist.
Open the app and drop the CSV into it.
Start making decisions and let it build your ranking.

As long as your CSV has a song title column, it should work. If it also has artist names and Spotify information, the app can show previews and Spotify links too.

Running it

Everything is in one file called index.html.

You can:

Double-click index.html and open it in your browser.
Upload it to GitHub Pages.
Run a small local server if you want to.
Privacy

Your CSV stays on your computer and isn't uploaded anywhere. Progress is saved in your browser's local storage.

Notes
Song previews don't exist for every song, so some tracks will only have Spotify links.
Progress is saved per browser and device.
No frameworks or external libraries were used.
Tech Used

I made this with plain HTML, CSS, and JavaScript as a way to learn and build something useful for myself. The ranking system uses a merge sort approach, which was fun to figure out and implement.

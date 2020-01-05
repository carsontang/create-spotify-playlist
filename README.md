# Instructions

Use this Python command line tool if you want to add artists' top tracks to an
existing Spotify playlist. To use the tool, simply run

`python create-spotify-playlist.py <playlist_id> <filename> <N>`

`playlist_id` - This is a Spotify playlist ID. Go to any Spotify playlist, use
the `Share` button and select `Copy Spotify URI`. The URI should look like this:
`spotify:playlist:0qiekdLNJklyu9YKqqU3Fg`. The section after `playlist:` is the
`playlist_id`.

`filename` - This is a CSV of artist names, one artist name per line.

`N` - This is the number of top tracks per artist you want to add to the playlist.
If the artist has fewer than `N` tracks, all of the artists' top tracks will be added.


Dependencies:
* Python 3.8
* [Requests: HTTP for Humans](https://requests.readthedocs.io/en/master/)
* Spotify Web API V1

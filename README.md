## Make Recommendations for Users
- Take the current [diversity](https://doi.org/10.1145/3320435.3320455) of users
- generate a lot of tracks for them
    - if we want stuff "further" from preference, we use a track from them as seed, then use one of the results as seed, and so on
    - if we want closer, we just use the 'root tracks'
- compared to their current diversity, generate one list that's higher and one that's lower
## Present Recommendations Back to Users
We can use [the spotify api](https://developer.spotify.com/console/playlists/) to make a playlist for each user
- present them with a more diverse and a less diverse playlist
## Analyze Feedback from Users
- get it back in a google form or smth like that
- check their satisfaction of high and low diversity lists against user metrics (sophistication, preference)
 
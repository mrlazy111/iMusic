
# There are three APIs used in the Screens:
  The first API is used to show the list of the movies in the first screen.
  The second API used in the second screen which will use the id, which you will get from the previous API, using that TRACK_ID you will show the track details.
  The third API is used on the same screen as the second API, so you will use the same TRACK_ID used in that here to fetch and display the lyrics.
  
 # DEMO WORKING:
 https://drive.google.com/file/d/1h9Bt-jTTTULd1uuWcs-K9_UzJoA70NRd/view?usp=sharing
 
 
 
 # 3_APIs:
 
1) https://api.musixmatch.com/ws/1.1/chart.tracks.get?apikey=2d782bc7a52a41ba2fc1ef05b9cf40d7
2) https://api.musixmatch.com/ws/1.1/track.get?track_id=TRACK_ID&apikey=2d782bc7a52a41ba2fc1ef05b9cf40d7
3) https://api.musixmatch.com/ws/1.1/track.lyrics.get?track_id=TRACK_ID&apikey=2d782bc7a52a41ba2fc1ef05b9cf40d7

Note: The Second and third API contain the word TRACK_ID, you must replace that word with the ID, which you will get from the first API for the tapped music item.

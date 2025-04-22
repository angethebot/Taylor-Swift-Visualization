# Final Project
### Yuxin Gong
### 21088401
In this project, I visualized the Taylor Swift's music statistics including her album sales, song popularity, song emotion, and the Eras Tour statistics.
1. Data source:\
(1) Kaggle Taylor Swift Spotify Dataset: https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset/data?select=taylor_swift_spotify.csv \
(2) Kaggle Taylor Swift Eras Tour: https://www.kaggle.com/datasets/tymonbot/taylor-swift-eras-toure \
(3)Kaggle Taylor Swift All Lyrics (64 Albums) [with TTPD]:\
a.https://www.kaggle.com/datasets/ishikajohari/taylor-swift-all-lyrics-30-albums
b.https://www.kaggle.com/datasets/lucynewman/taylor-swift-lyrics-through-2024-ttpd
c.https://www.kaggle.com/datasets/tksmax/taylorswiftlyrics \
(4)Chartmaster Sales of Taylor Swift's albums: https://chartmasters.org/taylor-swift-albums-and-songs-sales/
2. Objectives:\
Below shows the objectives of this project and how it fulfills the requirements of the final project.\
(1) Visualize Taylor Swift's 11 Album's along time and their sales using Manim (Option 6) \
(2) Visualize Taylor Swift's all songs in terms of their danceability, duration, and popularity using a 3D plot in R (Option 1) \
(3) Visualize Taylor's song emotions in each album using Chord diagram in R (Option 3) \
(4) Visualize Eras Tour route using leaflet in R (Option 2) \
(5) Additionally, I used `magick` to create a animated pixel art of Taylor, and used generative art to blend all Taylor album colors to generate background (Color flow: top = Debut → bottom = TTPD) in R (option 4)\
4. Final Submission\
(1) HTML page: https://angethebot.github.io/Taylor-Swift-Visualization/ \
(2) infographic_with_music.zip \
a. visualization_code folder
    - Manim:
       - Python code is in TaylorSwiftAlbumTimeline.ipynb;
       - 11 album cover webp; data is in album_sales;
       - MP4 video saved from the output of the Python code.
    - R Code:
      - R code is in `Yuxin Gong – Final Project.Rmd`;
      - everything else is input needed for R code (taylor_spoitfy.csv, taylor_lyrics.csv, eras_tour.csv, `Taylor Headshot Animated/taylor.jpg`)
    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. infographic_material folder: I copied all the output from the Visualization Code and moved them here to build the HTML. I also found on the internet the following materials: signature.svg, signature_white.svg, record.svg, background_music.mp3 \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.taylor_infographic.html: this HTML takes everything from infographic_material folder and build a page

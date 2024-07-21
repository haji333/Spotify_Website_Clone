# Spotify_Website_Clone
This my first mini project using HTML and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify - Web Player: Music for everyone</title>
    <link rel="icon" href="./assets/logo.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="stylefile.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100..900&display=swap" rel="stylesheet">
</head>
<body>
    <div class="main">
        <div class="sidebar">
            <div class="nav">
                <div class="nav-option" style="opacity: 1;">
                    <i class="fa-solid fa-house icons"></i>
                    <a href="#" >Home</a>
                </div>
                <div class="nav-option">
                    <i class="fa-solid fa-magnifying-glass icons" ></i>
                    <a href="#">Search</a>
                </div>
            </div>
            <div class="library">
                <div class="library-nav">
                    <div class="nav-option">
                        <img src="./assets/library_icon.png" alt="icon" class="icons">
                        <a href="#">Your Library</a>
                    </div>
                    <div class="nav-direction">
                        <i class="fa-solid fa-plus icons"></i>
                        <i class="fa-solid fa-arrow-right icons"></i>
                    </div>
                </div>
                <div class="boxes">
                    <p class="box-title">Create your first playlist</p>
                    <p class="box-parah">It's easy, we'll help you</p>
                    <button class="box-button">Create playlist</button>
                </div>
                <div class="boxes">
                    <p class="box-title">Let's find some podcasts to follow</p>
                    <p>We'll keep you updated on new episodes</p>
                    <button class="box-button">Browse podcasts</button>
                </div>
            </div>
        </div>
        <div class="main-content">
            <div class="sticky-nav">
                <div class="sticky-nav-icons">
                <img src="./assets/backward_icon.png" alt="kk">
                <img src="./assets/forward_icon.png" alt="kk" class="hide">
                </div>
                <div class="sticky-nav-options">
                <button class="box-button items hide">Explore Premium</button>
                <button class="box-button items dark-icon"><i class="fa-regular fa-circle-down " style="margin-right: 5px;"></i>Install App</button>
                <i class="fa-regular fa-user items"></i>
                </div>
            </div>
                <h2>Recently Played</h2>
                <div class="container">
                    <div class="card">
                        <img src="./assets/card1img.jpeg" class="card-image" alt="#">
                        <p class="card-title">Top 50-Global</p>
                        <p class="card-info">The daily update of the most played track...</p>
                    </div>
                </div>
                <h2>Spotify original&exclusive poadcasts</h2>
                <div class="container">
                    <div class="card">
                        <img src="./assets/card2img.jpeg" class="card-image" alt="#">
                        <p class="card-title">True story Bro! wi...</p>
                        <p class="card-info">Spotify</p>
                    </div>
                    <div class="card">
                        <img src="./assets/card3img.jpeg" class="card-image" alt="#">
                        <p class="card-title">Chanakya Niti</p>
                        <p class="card-info">Kiran Chavda</p>
                    </div>
                    <div class="card">
                        <img src="./assets/card4img.jpeg" class="card-image" alt="#">
                        <p class="card-title">The Horror Show...</p>
                        <p class="card-info">TMV studios</p>
                    </div>
                </div>
                <h2>Featured Charts</h2>
                <div class="container">
                    <div class="card">
                        <img src="./assets/card5img.jpeg" class="card-image" alt="#">
                        <p class="card-title">Top Songs-Global</p>
                        <p class="card-info">Your weekly update of the most played tracks right...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/card6img.jpeg" class="card-image" alt="#">
                        <p class="card-title">Top Songs-India</p>
                        <p class="card-info">Your weekly update of the most played tracks right...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/card1img.jpeg" class="card-image" alt="#">
                        <p class="card-title">Top 50-Global</p>
                        <p class="card-info">Your weekly update of the most played tracks right...</p>
                    </div>
                </div>
            <div class="footer">
                <div class="line"></div>
            </div>
        </div>
        <div class="music-player">
            <div class="album">
                <div class="album-image">
                <img src="./assets/card3img.jpeg" alt="#">
                 </div>
                 <div class="album-info">
                    <div class="song-name">Daylight</div>
                    <div class="singer">Rahat ali</div>
                 </div>
                 <div class="album-icon">
                    <i class="fa-regular fa-heart"></i>
                    <i class="fa-regular fa-square-minus"></i>
                 </div>
            </div>
            <div class="player">
                <div class="player-controls">
                    <img src="./assets/player_icon1.png" class="player-controls-icon" alt="#">
                    <img src="./assets/player_icon2.png" class="player-controls-icon" alt="#">
                    <img src="./assets/player_icon3.png" class="player-controls-icon" alt="#" style="opacity: 1; height: 2rem;">
                    <img src="./assets/player_icon4.png" class="player-controls-icon" alt="#">
                    <img src="./assets/player_icon5.png" class="player-controls-icon" alt="#">
                </div>
                <div class="playback-bar">
                    <span>00:00</span>
                    <input type="range" min="0" max="100" step="1" class="progress-bar">
                    <span>3:33</span>
                </div>
            </div>
            <div class="controls">
                <i class="fa-solid fa-play"></i>
                <i class="fa-solid fa-microphone"></i>
                <i class="fa-solid fa-grip-lines"></i>
                <i class="fa-solid fa-computer"></i>
                <label for="volume"><i class="fa-solid fa-volume-high"></i></label>
                <input type="range" id="volume" name="volume" min="0" max="100" step="1" class="progress-bar" style="width: 30%;">
            </div>
        </div>
    </div>
</body>
</html>

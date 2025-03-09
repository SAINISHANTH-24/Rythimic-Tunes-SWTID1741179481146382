Project Overview 
Purpose: 
Rhythmic Tunes is a music streaming web application designed to provide users with a seamless, 
engaging, and personalized music experience. Built using React.js for the frontend and Node.js for the 
backend, the platform enables users to explore, play, and manage their favorite music effortlessly. 
Features: 
User Authentication: Secure login and signup using JWT authentication. 
Music Library: Browse an extensive collection of songs by artists, albums, and genres. 
Playlists Management: Create, edit, and delete custom playlists 
Favorites & Likes: Mark songs as favorites for easy access.  
 / → Home Page (Displays trending and recommended songs) 
 /song/:id → Song Details Page (Displays lyrics, artist info, and play options) 
 /playlist/:id → Playlist Page (Shows user-created playlists and songs) 
 /upload → Upload New Song Page (Admin feature for adding songs) 
 /login → User Authentication Page
Setup Instructions for Rhythmic Tunes 
Prerequisites 
 Install Node.js (latest stable version recommended) 
Installation  
1. Clone the repository:  
git clone https://github.com/yourusername/rhythmictunes.git 
2. Navigate to the project directory:  
cd cookbook  
3. Install dependencies:  
npm install  
4. Start the development server:  
npm run dev
Folder Structure
RhythmicTunes 
┃ ┣  src 
┃ ┃ ┣  components 
┃ ┃ ┃ ┣  Header.jsx 
┃ ┃ ┃ ┣  Footer.jsx 
┃ ┃ ┃ ┣  MusicPlayer.jsx 
┃ ┃ ┃ ┣  Playlist.jsx 
┃ ┃ ┃ ┣  SongCard.jsx 
┃ ┃ ┃ ┗  ThemeToggle.jsx 
┃ ┃ ┣  pages 
┃ ┃ ┃ ┣  Home.jsx 
┃ ┃ ┃ ┣  SongDetails.jsx 
┃ ┃ ┃ ┣  PlaylistDetails.jsx 
┃ ┃ ┃ ┗  Login.jsx 
┃ ┃ ┣  context 
┃ ┃ ┃ ┗  MusicContext.jsx 
┃ ┃ ┣  App.jsx 
┃ ┃ ┣  main.jsx 
┃ ┃ ┣  App.css 
┃ ┃ ┣  index.css 
┃ ┃ ┗  .eslintrc.cjs 
┃ ┣  package.json 
┃ ┣  package-lock.json 
┃ ┣  README.md 
┃ ┗  vite.config.js 
┣  backend 
┃ ┣  config 
┃ ┃ ┗  db.js 
Folder Structure 
┃ ┣  controllers 
┃ ┃ ┣  authController.js 
┃ ┃ ┣  songController.js 
┃ ┃ ┗  playlistController.js 
┃ ┣  models 
┃ ┃ ┣  User.js 
┃ ┃ ┣  Song.js 
┃ ┃ ┗  Playlist.js 
┃ ┣  routes 
┃ ┃ ┣  authRoutes.js 
┃ ┃ ┣  songRoutes.js 
┃ ┃ ┗  playlistRoutes.js 
┗  README.md
Demo Link: 
https://drive.google.com/file/d/1J6JizhS4Jv_Vy5hGuQKc9iEFkfAy2I-J/view

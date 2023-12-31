
## Usage
### 1. Export Apple Music playlists to XML File <br >
The first step is to select the playlist you want to import over and export it as an XML file. You do this by selecting File -> Library -> Export Playlist. Save the resulting file as whatever you would like in the same directory as the directory you cloned this repo into. <br>

### 2. Install dependencies <br >
pip install requirements.txt (run in terminal) <br >

### 3. Configure Spotify developer application and variables
1. Go to https://developer.spotify.com/dashboard/applications.
2. Create an app with any name.
3. Select the app.
4. Select **EDIT SETTINGS**.
5. Under **Redirect URIs**, enter `http://localhost:8888/callback` and select **Add**. Select **SAVE**.
6. Rename .env.local.example to .env.local
7. Find **Client ID** and copy the value to the `client_id` variable in .env.local.
8. Select **SHOW CLIENT SECRET**. Copy the value to the `client_secret` variable in .env.local.
9. Go to https://spotify.com > **Profile** > **Account**.
10. Copy the value of **Username** to the `username` variable in .env.local.
12. Save the edited file.

### 4. Run Program

Run the program using terminal by using python music-import.py

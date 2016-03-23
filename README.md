#Trikatuka - Spotify migration tool

**Trikatuka** is a tool helping transfer Spotify playlists and saved tracks from one account to another.

- *Collaborative* playlists are followed.
- *Public* and *private* playlists are copied.
- Followed playlists are followed.

Production app is available here: http://trikatuka-aknakn.rhcloud.com/
How to: http://aknowakowski.blogspot.com/p/trikatuka2.html

##For developers

Project is based on `Node.js` and `AngularJS 1.5`

You need to create an app on https://developer.spotify.com/ and get `clientId` and `clientSecret`. You must also add `http://localhost:7878/client_auth_callback` and `http://localhost:7878/user_auth_callback` to urls whitelist.

**How to run**
- rename `config/default.json.template` to `config/default.json`
- edit `config/default.json` and paste your `CLIENT ID` and `CLIEN SECRET`
- `npm install`
- `node serverapp.js`
- Navigate to `http://localhost:7878`

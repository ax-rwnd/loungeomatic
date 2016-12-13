# Lounge-o-Matic
Lounge-o-Matic is a streaming webservice for enjoying media with your friends (invite only). For the first sprint(s) of the project, the service will be limited to music, if time allows, the service should be extensible enough to provide video streaming as well.

A lounge is a point where users of the system meet. Here, there is a media player and a chat (maybe, if time allows) so that the users may socialize in real-time.

To allow people into your lounge, the owner sends an invitation to a friend by giving away a key. Other users connect to the same room using their own keys and are able to listen to the same media in a synchronized manner as long as their key is valid. The owner of the lounge should be able to revoke the key at any time, effectively kicking the user out.

Users connect to the frontend service to authenticate their visit against the backend. Then, they may visit their own lounge (or one of their friends' rooms) to play media or upload content.

The upload process will work by giving the user a upload dialog to the backend, transcoding it to a lower bitrate and moving it to the user's storage. These files should then be exposed to the participants of the owner's lounge.

## Frontend
See https://github.com/ax-rwnd/lounge-frontseat

## Backend
See https://github.com/ax-rwnd/lounge-backseat

## Showtime
See https://github.com/ax-rwnd/lounge-showtime

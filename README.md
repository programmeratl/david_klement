(1)Index.html is live video publising page. You can open this page and change variable var websocketURL="wss://domain.com:5443/WebRTCApp/websocket"; to your Ant media server address.
(2)play.html is playback page for recorded mp4 videos. Open play.html and change variable var server_address="https://domain.com:5443/WebRTCApp"; to your Ant media server address.
How to play:
The play.html address will be:
https://domain.com/play.html?name=streams/stream.mp4&autoplay=true where stream is your stream name that you have set in index.html during live publishing.
(3)We must need SSL ( https:) for live recording.

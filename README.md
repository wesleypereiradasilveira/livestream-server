# Livestream Server

A livestream server built with nginx

## Steps of Video Platform

1. Ingest - The capture of the image/video and sound, camera, microphone etc.
2. Encoding - OBS which has algorithms for translating the media from bytes, compression and decompression.
3. Packaging - Which receives in some protocol and apply transformations to different segments like RTMP, HLS, DASH and so on.
4. Delivery - It is the layer which is responsible to deliver and distribuit with the server near the client, like a CDN for example.
5. Play - Where the decoding, caching, transmission hapen, it plays the video for the client.


# streaming_website-spring_webflux
Create a basic streaming website to test spring webflux and how to get video data range by range and not getting all the video in the same time so the browser site can be fast.

## As you can see in inspect of element the video is not loaded yet. 👇

<p align="center">
  <img src="https://github.com/warakiabdelbasset/streaming_website-spring_webflux/blob/master/image/1.png">
</p>

## After you click play a request go to the server to get the video as you see in the inspect of element, but the video is not completely loaded, only a range of the video is loaded 👇


<p align="center">
  <img src="https://github.com/warakiabdelbasset/streaming_website-spring_webflux/blob/master/image/2.png">
</p>

## As you see in this image if you want to skip or go to a spesific minute of the video not all the prevous range gonna get load but a new request gonna get send to the service so it give you data only from when you select. 👇

<p align="center">
  <img src="https://github.com/warakiabdelbasset/streaming_website-spring_webflux/blob/master/image/3.png">
</p>

## In this image it shows you what is the return when you send a request to the server for a specific minute. 👇

<p align="center">
  <img src="https://github.com/warakiabdelbasset/streaming_website-spring_webflux/blob/master/image/4.png">
</p>



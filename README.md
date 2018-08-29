

<!DOCTYPE html>
<html>
<head>
<meta charset=utf-8 />
<title>videojs-contrib-hls embed</title>
  
  <!--

  Uses the latest versions of video.js and videojs-http-streaming.

  To use specific versions, please change the URLs to the form:

  <link href="https://unpkg.com/video.js@6.7.1/dist/video-js.css" rel="stylesheet">
  <script src="https://unpkg.com/video.js@6.7.1/dist/video.js"></script>
  <script src="https://unpkg.com/@videojs/http-streaming@0.9.0/dist/videojs-http-streaming.js"></script>

  -->

  <link href="https://unpkg.com/video.js/dist/video-js.css" rel="stylesheet">
</head>
<body>
  <h1>ABP-Asmita Live</h1>

  <video-js id="my_video_1" class="vjs-default-skin" controls preload="auto" width="640" height="268">
    <source src="https://hls_live_asmita-i.akamaihd.net/hls/live/582529/abpasmita/master.m3u8"application/x-mpegURL">
  </video-js>
  
  <script src="https://unpkg.com/video.js/dist/video.js"></script>
  <script src="https://unpkg.com/@videojs/http-streaming/dist/videojs-http-streaming.js"></script>
  
  <script>
    var player = videojs('my_video_1');
  </script>
  
</body>
</html>

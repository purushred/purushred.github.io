<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta property="og:description" content="Corona Data 3D Visualization." />
    <link
      href="https://fonts.googleapis.com/css?family=Space+Mono:400,700&display=swap"
      rel="stylesheet"
    />
    <meta property="og:image" content="https://i.imgur.com/1AFEXhs.png" />
    <title>Corona Virus Data - 3D</title>
    <link rel="stylesheet" href="./styles/main.css" />
  </head>
  <body>
    <div id="globeDiv"></div>
    <div class="top-info-container">
      <div class="title">Corona Virus</div>
      <div class="title-desc">
        Loading countries affected by the corona virus...
        <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
        <!-- CovidAds -->
        <ins class="adsbygoogle"
            style="display:block"
            data-ad-client="ca-pub-7965587014035488"
            data-ad-slot="8525618165"
            data-ad-format="auto"
            data-adtest="on"
            data-full-width-responsive="true"></ins>
        <script>
            (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
      </div>
    </div>

    <div class="bottom-info-container">
      <div style="font-size: 14px; color: #ccd6f6;">Worldwide Info</div>
      <div style="color: #e6f1ff; padding: 0 5px;">
        Infected: <span id="infected" class="infected">0</span> • Recovered: <span id="recovered" class="recovered">0</span> • Deaths:
        <span id="deaths" class="deaths">0</span>
      </div>
    </div>
    <script src="./app.js"></script>
  </body>
</html>

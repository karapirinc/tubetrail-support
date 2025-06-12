<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TubeTrail - Explore YouTube on a Map</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; }
    header { background: #FF0000; color: white; padding: 2rem 1rem; text-align: center; }
    header h1 { margin: 0; font-size: 2rem; }
    header p { margin: 0.5rem 0 0; font-size: 1.2rem; }
    .container { max-width: 960px; margin: 2rem auto; padding: 0 1rem; }
    .hero { text-align: center; }
    .hero img { max-width: 100%; height: auto; border-radius: 8px; }
    .features { display: grid; grid-template-columns: 1fr; gap: 1.5rem; margin-top: 2rem; }
    @media(min-width: 600px) { .features { grid-template-columns: 1fr 1fr; } }
    .feature { background: #f9f9f9; padding: 1rem; border-radius: 8px; }
    .feature h3 { margin-top: 0; }
    .cta { text-align: center; margin: 3rem 0; }
    .cta a { background: #FF0000; color: white; padding: 1rem 2rem; text-decoration: none; font-size: 1.2rem; border-radius: 4px; }
    footer { background: #eee; padding: 1rem; text-align: center; font-size: 0.9rem; }
    footer a { color: #FF0000; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>TubeTrail</h1>
    <p>Discover geotagged YouTube videos on an interactive map</p>
  </header>

  <div class="container">
    <section class="hero">
      <img src="screenshot-map.png" alt="Map view with video pins" />
    </section>

    <section class="features">
      <div class="feature">
        <h3>Location-Based Discovery</h3>
        <p>Pan or zoom the map to surface local vlogs, food reviews, walking tours, and live cams.</p>
      </div>
      <div class="feature">
        <h3>Smart Filters</h3>
        <p>Filter by category, radius, or keyword to uncover exactly the content you want.</p>
      </div>
      <div class="feature">
        <h3>Seamless Playback</h3>
        <p>Tap a pin to play the video in the official YouTube iFrame player or jump to YouTube.</p>
      </div>
      <div class="feature">
        <h3>Privacy-First</h3>
        <p>No login required, no trackers. API data cached in-memory only and purged after 24 hours.</p>
      </div>
    </section>

    <div class="cta">
      <!--<a href="https://testflight.apple.com/join/XXXXXXX">Join the Beta on TestFlight</a>-->
    </div>

    <section class="contact">
      <p><a href="https://karapirinc.github.io/tubetrail-support/support.md">Questions? Email us!</a></p>
      <p><a href="https://karapirinc.github.io/tubetrail-support/privacy.md">Privacy Policy</a></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 TubeTrail – Built by Yusuf İsmail Oktay</p>
  </footer>
</body>
</html>

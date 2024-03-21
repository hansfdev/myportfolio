---
layout: project
name: La Marcha
type: professional
date: 2023-07-01
summary: Browser game made for Costa Rica soccer team
imageurl: /assets/images/marcha_thumb.jpg
bannerurl: /assets/images/marcha_thumb.jpg
---

Browser game made for a Costa Rican soccer team, as part of a promotional campaign to announce the launch of a team shirt commemorating a historic event. The gameplay consists of a simple block stacking mechanic where you fill lines of blocks to clear them and win points, progressively getting faster. If a stack of blocks reaches the ceiling, the game ends.

<video height="600" autoplay loop playsinline>
  <source src="{{ '/assets/videos/lamarcha_vid.mp4' | relative_url }}" type="video/mp4">
</video>

By playing the game, you could getinto the leaderboard's Top 10, and get a chance to win a prize like free merch, exclusive access to team training sessions and free tickets (assuming no one took your spot from the leaderboard before the event ended). Aside from highscores, players were given 1 Brick for each 1000 points they scored in one game, the point of the event being that all players would cooperatively help build The Wall. When the wall was completed, the new shirt reveal would then take place.

<div class="img-flex-container">
    <img src="{{'/assets/images/marcha1.png' | relative_url }}">
    <img src="{{'/assets/images/marcha2.png' | relative_url }}">
</div>


The event lasted for two weeks and had great reception, with many users praising the retro aesthetic of the game and the initiative of the sponsoring soccer team.
## Main Responsibilities

- Only developer in the project.
- Implemented all game elements (audio, game loop, graphics, UI) using Playcanvas.
- Implemented online functionality (leaderboard, user management, community based progression) using Playfab.
- User metrics and activity tracking for interaction reports.
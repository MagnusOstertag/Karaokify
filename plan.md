# Der Plan

## Ähnliche Projekte

Name | Plattform | Musik | Text | Programmiersprache | Status
---|---|---|---|---|---
[spotify_karaoke](https://github.com/MAD-in-Demand-Studios/spotify_karaoke) | Android | Spotify | Genius | HTML, Java | seems to work
[Singlyricly](https://github.com/kalkih/singlyricly) | Mobile | Spotify | ? | Vue, JavaScript | seems to work
[SpotifyKaraoke](https://github.com/ianyyang/SpotifyKaraoke) | Spotify | Genius | react.js | seems to work
[karaoke](https://github.com/chezzzer/karaoke) | Spotify | Musixmatch | JavaScript | ?

- [PiKaraoke](https://github.com/vicwomg/pikaraoke): karaoke search and queing - QR code auf TV, queing, prebuild RasPi images
- [UltraStar Deluxe](https://github.com/UltraStar-Deluxe/USDX): up to six players to sing along with music using microphones in order to score points, depending on the pitch of the voice and the rhythm of singing (FOSS sing-star clone)

## Die Tools

- der freie Spotify-Client [librespot](https://github.com/librespot-org/librespot)
- benötigt den [draft pull request](https://github.com/librespot-org/librespot/pull/891), den man im [new-api branch](https://github.com/librespot-org/librespot/tree/new-api) finden kann
- das Package, um die [YouTube transcripts](https://pypi.org/project/youtube-transcript-api/) zu holen oder von [Google](https://developers.google.com/youtube/v3/docs)
- scoring basierend auf [pitch](https://github.com/jenniferleeny/Automated-Grading-KaraokeMachine)

## Einschränkungen

- librespot funktioniert nur mit Spotify Premium

## Workflow

### v.1

1. start image on raspi or packaging with python
2. select -
   1. search for song with lyrics, instrumental version and youtube music video and have a preview
   2. select one of the TOP 50 working songs
3. play - instrumental song, lyrics with point and music video
4. sing - through the microphone
5. scoring - noten finden, noten darstellen, noten volllaufen lassen z.B. mit [noobnotes](https://noobnotes.net/)

### v.2

- mit dem Smartphone steuern und ins Smartphone singen bei QR code im zentralen System
- admin Gerät

## ToDo

- [ ] librespot kennenlernen
- [ ] youtube-transcripts kennenlernen
# Anime Auction Universe — card art

Card pictures for the Anime Auction Universe party game, served to the game through jsDelivr.

- `cards/<versionId>_<name>.webp`: one picture per fighter version. The part before the first underscore is the fighter's Version ID from the master sheet (case-sensitive, leading zeros kept).
- `credits.json`: where each picture comes from. `official: true` is official art (anime, manga or game). Fan art has `official: false` and the artist's name in `artist`, which the game shows on the card as "Art: <artist>".

Fan art belongs to its artists and is used with credit. To have a picture credited differently or removed, open an issue.

## Music

- `music/<artist>/<title>.mp3`: background music for the game's shuffle player. All tracks are owned by the game's owner.
- `music/covers/<artist>.webp`: album covers shown in the player.
- `music.json`: the track list (title, artist, file, cover).

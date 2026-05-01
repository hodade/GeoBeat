# GeoBeat App Store Submission Notes

## URLs

- Privacy Policy URL: `https://hodade.github.io/GeoBeat/privacy-policy.html`
- Support URL: `https://hodade.github.io/GeoBeat/support.html`

GitHub Pages must be enabled for the `hodade/GeoBeat` repository from the `main` branch root.

## Japanese Metadata

- App Name: GeoBeat
- Subtitle: 場所で見つかる音楽
- Category: Music
- Secondary Category: Travel
- Promotional Text: 今いる場所や地図で選んだ場所に合わせて、Apple Musicからその土地らしい曲を見つけます。
- Description:

GeoBeatは、現在地や地図で選んだ場所に合わせてApple Musicの曲を探す音楽アプリです。

町名、市区町村名、都道府県名などの地域情報をもとに検索し、その場所にゆかりのある雰囲気や名前を持つ曲を再生します。自宅にいながら別の街の音楽を試せる、場所シミュレート機能にも対応しています。

主な機能:
- 現在地に合わせたApple Music選曲
- 地図で指定した場所の音楽を試せるシミュレートモード
- 曲の再生、一時停止、停止
- 気に入らない曲を次の候補へ切り替え
- ジャケットからApple Musicで曲を開く
- 日本語と英語表示

アプリ内での再生には、Apple Musicの利用環境とアクセス許可が必要です。利用できない場合でも、Apple Musicで曲を開いて確認できます。

- Keywords: 音楽,Apple Music,位置情報,旅行,散歩,地図,地域,プレイリスト

## English Metadata

- App Name: GeoBeat
- Subtitle: Music for your location
- Category: Music
- Secondary Category: Travel
- Promotional Text: Find Apple Music songs that match your current place or any location you choose on the map.
- Description:

GeoBeat recommends Apple Music songs based on your current location or a place you choose on the map.

The app searches using area information such as neighborhood, city, and prefecture, then plays songs connected to the feeling or name of that place. With location simulation, you can try music for another city without leaving home.

Key features:
- Apple Music recommendations based on your current location
- Location simulation with an interactive map
- Play, pause, and stop controls
- Skip to the next candidate when a song is not right
- Open songs in Apple Music from the artwork
- Japanese and English interface

In-app playback requires Apple Music availability and permission. If playback is unavailable, you can still open the song in Apple Music.

- Keywords: music,Apple Music,location,travel,map,city,walking,recommendations

## App Privacy Answers

Use this as a starting point in App Store Connect and confirm it matches the final build before submission.

- Data collected by the developer: None stored on developer-operated servers.
- Location: Used for app functionality to determine the area and search for music. Not used for tracking. Not sold. Not linked to a developer account.
- Identifiers: Not collected by the developer.
- Usage Data: Not collected by the developer.
- Diagnostics: No custom diagnostics or third-party analytics SDK in the app.
- Third-party services: Apple Core Location, MapKit, MusicKit, and Apple Music are used for location, map, catalog search, and playback.

## Review Notes

GeoBeat uses Core Location and MusicKit. Location permission is used to determine the current area for music recommendations. Apple Music permission is used to search and play catalog songs. Users without in-app playback availability can open the selected song in Apple Music. The app also includes a map-based simulation mode so reviewers can test recommendations for arbitrary locations.

## Remaining Manual Steps

- Enable GitHub Pages for `hodade/GeoBeat` from `main` branch root.
- Create the App Store Connect app record.
- Upload screenshots for required device sizes.
- Confirm age rating. Because Apple Music catalog content may include explicit songs depending on user settings and catalog results, review the App Store Connect age-rating questionnaire carefully.
- Archive and upload a signed release build from Xcode.
- Complete App Privacy in App Store Connect using the notes above.

# discord stream kit style
make your own discord voice widget stream overlay

here's some custom css you can add on obs to your discord vocal stream kit.

first push bring a **vertical overlay**.

## get discord stream kit

go to the [discord stream kit](https://streamkit.discord.com/overlay) page to get your voice widget

1. select your server
2. select your voice channel
3. show speaking users only : up to you
4. small avatars : no ❌
5. hide names : no ❌

forget the other options.

now you can copy the streamkit url (something like `https://streamkit.discord.com/overlay/etc...`)

this url goes in your obs browser capture.

## obs browser capture

1. url : paste the streamkit url you just got
2. width : 240
3. height : 1080
4. custom css : put what you'll find in the style.css file in this repo

## the style.css file

in this file, feel free to select the part you need (you don't want to fill your obs with useless code lines)

from **line 82** to **118** you'll find optional style
- **line 84 to 92** : a way to style teammates pictures with an even/odd method
- **line 94 to 118** : a way to style teammates pictures with a specific order given (you can add more than 6 selectors ofc, depends on the number of ppl you'll have on your vocal channel)

if you copy/paste the file as it is, your streamkit overlay should look like this :

![example of what the overlay should look like](/assets/discord_streamkit_custom_video.gif)

## ⚠️ good to know ⚠️

i haven't found how to remove specific profile from the overlay (like yours when your streaming for example) yet.
seems like discord doesn't provide any kind of id in their voice widget. 😞
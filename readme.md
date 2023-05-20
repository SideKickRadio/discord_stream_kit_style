# discord stream kit style

here's some custom css you can add on obs to your discord vocal streamkit.

options available :

- vertical design
- horizontal design
- replace profile pic of your teammates
- change teammates profile style even/odd way
- change teammates profile style one by one

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

1. **url** : paste the streamkit url you just got
2. **width** : adjust as you like
3. **height** : adjust as you like
4. **custom css** : put what you'll find in css files in this repo

## the css files

in those files you'll find everything you need to customize your discord voice widget.

first you need to chose between :  
🔴 `horizontal_core_style.css` or `vertical_core_style.css` 🔵

those are the core files. once you know which way you want to go, you can copy the whole file and put it into your browser catpure's custom css.

then, you can add options :
- you want to replace your teammates profile pictures because reasons ? then copy what's in the `replace_profile_pictures.css` file and put it at the end of the custom css you pasted just before
- you want to change the appearance of your teammates profile even/odd style ? do the same thing with the `even_odd_style.css`
- you want to change the style of your teammates profile in a more precise way ? you need what's inside `one_by_one.css` file

if you're not satisfied with the borders, the background of the profiles, the colors, the font style, feel free to change everything you need !
I added the `index.html` file to be a real sandbox !

careful tho, you better use firefox to preview your changes

glhf

## ⚠️ good to know ⚠️

i haven't found how to remove specific profile from the overlay (like yours when your streaming for example) yet.
seems like discord doesn't provide any kind of id in their voice widget. 😞
# inline-button-for-telegram-channel
Create awesome Telegram message for your channel with inline buttons, without adding suspicious robot and for free

## Run it online 

https://repl.it/@html5_ninja/inline-button-for-telegram-channel

## Settings

#### Step 1 

Create your bot a get your token go to https://core.telegram.org/bots to find how 

`var token = '1231321345:AAH_WuV_Kk1D9uHxaNeBIDLPfhKFDb-ijG4';  // <= replace with yours`

#### Step 2

Add your robot as admin to your channel and set your channel here , more details https://stackoverflow.com/questions/33126743/how-do-i-add-my-bot-to-a-channel

`var chatId = '@my_trolololo_cahnnel'; // <= replace with yours`

I advice you to try it with a test cahnnel 

## Message 

### Set your message text
Edit the "html" variable 

`var html = 'Hey this your awesome message\n\n'+
'🤖🤖🤖🤖🤖🤖🤖🤖🤖🤖\n\n'+
'<b>bold</b>, <strong>bold</strong>\n'+
'<i>italic</i>, <em>italic</em>\n'+
'<a href="https://www.forex-signals.club/">inline URL</a>\n'+
'<a href="tg://user?id=@zied_hosni">inline mention of a user</a>\n'+
'<code>inline fixed-width code</code>\n'+
'<pre>pre-formatted fixed-width code block</pre>\n\n'+
'🍩🍩🍩🍩🍩🍩🍩🍩🍩🍩';`

### Set your buttons
Edit the buttons variable
`
var buttons = [
    [
        {"text": "See on Github", "url": "https://github.com/html5-ninja/inline-button-for-telegram-channel"}, 
        {"text": "Follow me", "url": "https://twitter.com/zied_hosni"}
    ],
    [
        {"text": "🎖 Join our forex channel 🎖", "url": "https://t.me/forex_signals_club"}
    ]
];

`

## Press RUN button to execute the script 

## Photo
You can also send a photo 



<hr/>

if you need help or advanced feature please feel free to contact me
zied.hosni.mail@gmail.com

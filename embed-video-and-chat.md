##Parameters:
`Channel`: the target live streamer you want to use;
`height`: in pixels the height you want the video to be;
`width`: in pixels the width you want the video to be.

##Video Code:
```html
<iframe src="http://player.twitch.tv/?channel={CHANNEL}" allowfullscreen height="X" width="Y" *class="col-md-12">
</iframe>
```

* => OBS: As I was using BootStrap and wanted the video to fullfil all my div I used `class="col-md-12"`, IDK If It is the best practice but It worked for me

##Chat Code:
```html
<iframe frameborder="0" 
        scrolling="no" 
        id="chat_embed" 
        src="http://www.twitch.tv/{CHANNEL}/chat" 
        height="{HEIGHT}" 
        width="{WIDTH}">
</iframe>```

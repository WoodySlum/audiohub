#AudioHub
![Command Line Audio Playback From The Terminal](https://raw.githubusercontent.com/active9/audiohub/master/audiohub.png)

AudioHub is a simple mplayer wrapper written in NodeJS.

#INSTALLING
Using Git:
```bash
git clone https://github.com/active9/audiohub
cd audiohub*
npm install
```

Using NPM:
```bash
npm install audiohub
```

#CLI
AudioHub can play many audio formats directly from the command line. Give it a try:
```bash
audiohub path_to_a_music_file.mp3
```

#MODULE
Above may run included as a module in your projects.
```js
var audiohub = require('audiohub');
var path = require('path');

var audio = new audiohub();
audio.play(path.resolve('./ThatTwang.ogg'));


```

#EXAMPLES
More examples in the [examples](https://github.com/active9/audiohub/tree/master/examples) folder on the github repo.

~Enjoy!

#CONTRIB

AudioHub is open-source via the MIT license we encourage Forking.

#LICENSE
MIT



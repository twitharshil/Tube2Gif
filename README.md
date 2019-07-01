
####Pre-requisites
* Node.Js 6+
* FFMPEG installed ([Ubuntu Installation Guide](http://tipsonubuntu.com/2016/11/02/install-ffmpeg-3-2-via-ppa-ubuntu-16-04))

####Installation
1. Clone Repository
3. cd into dir && `npm install`
4. Obtain Youtube Api key ([Instructions](https://www.slickremix.com/docs/get-api-key-for-youtube/))
5. Add obtained Youtube key to config/local.js or `export YOUTUBE_API_KEY=key`
4. `npm start` && visit localhost:3000

<h2 align="center">Heroku Install</h2>

1. Add buildapps https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git and heroku/nodejs
2. Push to heroku master

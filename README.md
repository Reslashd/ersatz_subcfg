# ersatz_subcfg
Ersatz TV config for Music Video credits (MTV Style)
<BR>
<BR>Took me a while to figure this out since it was unclear to me what format the NFO for each video should have.
<BR>With this config the credits will appear near the beginning of the video (or start of stream) and near the end of the video.
<BR>The ending credits do not show up if you start streaming half way in a video (not sure why but for now I don't care).
<BR>
<BR>Example PATH for clips \Videoclips\Artistname\Videoclip.mp4
<BR>Create a NFO with the same name in the same directory which in this case is \Videoclips\Artistname\Videoclip.nfo
<BR>Please see the example NFO for the required format.
<BR>Place the .SBNTXT file in the /ersatztv/config/templates/music-video-credits/ directory.
<BR>
<BR>
<BR>In ErsatzTV configure the channel to use: 
<BR>Music Video Credits Mode = Generate Subtitles
<BR>Music Video Credits Template = reslashd_credits.sbntxt
<BR>Tested with Ersatz Version: 25.4.0-docker-amd64
<BR>
<BR>This will display the following information:
<BR>Artist
<BR>"Title"
<BR>Album (Year)

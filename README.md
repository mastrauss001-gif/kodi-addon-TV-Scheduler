# kodi-addon-TV-Scheduler
This is an addon to add the TV Shows in your library to the EPG Guide

For years I have been wanting to add my library to the TV Guide of Kodi. I found an old addon but couldnt get it to work.
When AI came out, I thought I'd try to write one with its help.
This is my first kodi addon and I am a python beginner. 99% of this code was written by claude.ai
I learned ai is not very good at complex programming. I've worked with it every day for the past 4 weeks and gave up.

The way the code stands now, it will read all the TV shows in a library and put them in the kody EPG Guide.
Each TV show is a channel. All the corresponding episodes are in the channel.
All channel show under All Channels. You have other Tabs which are genres. The proper TV Shows also show up under the proper Genre.

The only shows that it will show on the EPG guide will be the ones with a userrating above 7 and unwatched.
The xml and msu files are created at kodi launch and deleted when kodi shuts down.
The video that will play will be the one based on time. For example, if a 30 min epiode 1 is scheduled at 1pm, but you dont click to play it until 1:35, then the next episode will play instead.
The video will play completely and then will stop. You have to click the stream again to go to the next video. I would prefer continuous play to the next video but I am convinced that it is not possible to do this.

Issue I'm facing:
> Everytime you change the channel, the next show will always start from the beginning of an episode. I am trying to make the TV experience so that if the next channel episode started at 2pm and I switch to it at 2:15, then it should start at the 15 minute mark when I jump to it. claude.ai has an issue with this. It has told me hundreds of things to try and they all fail so I am looking for anyone who might be able to contribute and figure this part out.

Just install from zip like any other addon.

Let me know if you've made progress so I can test it out.

Thanks

Mike

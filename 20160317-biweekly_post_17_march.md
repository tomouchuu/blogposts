---
title: Biweekly Post - 17th March ’16
date: 17rd March 2016
---
So it’s been nearly 2 weeks since my last post. According to my twitter ([@tomopagu](https://twitter.com/tomopagu)) I’ve mostly been talking about my thoughts regarding the upcoming Hyper Japan convention and aside from that I’ve fixed the personal & blog site issues due to ssl(dokku) misconfig.

To go into a bit more detail with my Hyper Japan thoughts, I noticed with Kyary being the week before it would have made more sense to try organise it so Kyary would be there at the same time and incorporate her Moshi Moshi Nippon Fes as part of Hyper Japan either within or as a separate ticketed event. Something like this should increase the amount of music acts there and be easier to promote rather than just the festival on its own. I’m assuming the disappointment of Japan Night at Hyper Japan last year is partly the reason if that offer for MMNF was there and they skipped it. Being frustrated that we had heard nothing about acts that would be performing I tried to find any pages on the site that they may have accidentally published early. I ended up finding [http://www.hyperjapan.co.uk/download/hjf16/HYPERJAPAN2016_JP.pdf](http://www.hyperjapan.co.uk/download/hjf16/HYPERJAPAN2016_JP.pdf) which is a document they give to JP acts to try get them to come to the convention. From this we know the main stage for the event will be 2000 capacity and from looking at the Olympia website we can assume that they are using the Grand Hall as part stalls, part stage and we can also assume this stage will be seated. I went into why this was a bad thing on my Hyper Japan Christmas post ([https://blog.tomo.pagu.co/show/20151130-hyperjapanchristmas](https://blog.tomo.pagu.co/show/20151130-hyperjapanchristmas)) but it essentially means no fun for the artist, seated crowd and the crowd that want to do things like wotagei. We also now know they’ll be using Pillar Hall, however the function of this wasn’t made clear. Also Hyper Japan Christmas is going to be at Tobacco Docks again so yay coldness and seated stage again.

With the [https://tomo.pagu.co](https://tomo.pagu.co) & [https://blog.tomo.pagu.co](https://blog.tomo.pagu.co) ssl issues, it actually came down to Dokku’s LetsEncrypt plugin not properly configuring apps with multiple domains like the blog which was previously accessible at blog.tomo & blog-tomo. Now I’ve settled on just the blog.tomo and the plugin works so the blog is back on ssl which means the main personal site works again! Elsewhere on the code front, my friend Sam is beginning to get into coding so him and one of his friends at his apprenticeship are going to be hacking on Disbott with me which should be a fun experience. I’m really looking forward to helping them and seeing what they achieve. I’ve also launched [http://dempach-archive.pagu.co/](http://dempach-archive.pagu.co/) which is a site that downloads the latest episode of DempaCh. from Tunein. It’s on Github here: [https://github.com/tomopagu/dempach-archive](https://github.com/tomopagu/dempach-archive) and essentially it visits the Tunein page at 22:00BST and then gets the StreamUrl which is something like `http://podcasts.tfm.co.jp/tunein_ondemand/dempa_{yyyymmdd}.mp3`. Once it has that I download that mp3 file and then link to it on the site. The main reason for this is because they delete episodes after a week and it’s not the easiest thing to remember to listen every week and if you miss a week tough. Plus it’s just nice to have them and listen back.

Lastly I recently participated in a Swimarathon for Charity. Our Team (company) raised just over £1500 for charities which is just amazing. For the event itself our team of 6 had to swim lengths in a relay one length at a time. It was enjoyable at first but after 4 lengths I just couldn’t do anymore, I had to leave the pool for a few minutes and was sick in a toilet (fun). After a good 10mins of rest I got back in the pool and continued on for the team. I didn’t want to let the charities, team or the people that sponsored us down. In the end we did 134 lengths of the 25m pool between the 5.5 of us so together we swam 3350m which is just over 2 miles, pretty incredible for 6 guys with no training.

Anyway I guess this is pretty much it. I leave you with a new artist I’ve enjoyed listening to recently. She is called Låpsley and she performs minimalistic electronic music. I recommend checking out this The Guardian review on her album Long Way Home: [http://www.theguardian.com/music/2016/mar/06/lapsley-long-way-home-review](http://www.theguardian.com/music/2016/mar/06/lapsley-long-way-home-review) It’s really nice for just listening to while coding or even writing (like this very blogpost). Anyhow hopefully blogpost again soon!
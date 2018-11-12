This repo helps me keeping track of some resources I read so I can find them afterwards. Also it gives me a feeling of accomplishment.

## 2018-11-12
- Learned about targetting dark-theme mode using CSS thanks to [Redesigning your product and website for dark mode](https://stuffandnonsense.co.uk/blog/redesigning-your-product-and-website-for-dark-mode). Then I created a dark theme for my site creating a few extra CSS rules.

![Light and Dark modes](https://raw.githubusercontent.com/jmperez/til/master/light-dark.jpg)

Only supported on Safari Technology Preview for now.

## 2018-11-02
- Finished writing [a short post about Progressive Web Apps](https://jmperezperez.com/shades-of-pwa/) and some use cases where it makes sense to use it.

## 2018-10-26
- I watched [Tim Kadlec's talk where he does a performance audit of a website](https://www.smashingmagazine.com/2018/10/smashingconf-toronto-a11y-performance-audits/). I also want to watch some more [videos from SmashingConf Toronto 2018](https://vimeo.com/album/5451191) if time allows for it.
- I also watched [Peter Hedenskog's talk about Performance at Wikimedia](https://www.youtube.com/watch?v=8zjA8nZXCj4). I recommend you watch it if you are into web performance and want to learn more about the work they measure perf at Wikimedia using synthetic testing tools.

## 2018-10-25
- I started watching [the live streaming of React Conf](https://www.youtube.com/watch?v=kz3nVya45uQ). Didn't get to watch the whole thing and today when I tried to continue watching it I got an "This video contains content from WebTVAsia (Music), who has blocked it on copyright grounds." error. The few things I saw were really good. I like the idea of _hooks_ to encapsulate the logic that today gets spread across the different lifecycle methods. Also, when I grow up I want to be like Dan Abramov. I admire how he explains every hairy concept in such a way that everyone can understand, and he is always supportive solving questions from the community.
- I hacked a bit on [Spotify Dedup](https://github.com/JMPerez/spotify-dedup) adding a few tests. The Spotify Web API is a good piece of technology but when you make thousands of requests against it chances are that you run into some issues. A request will fail now and then, the user connectivity might get lost (especially true for a potential long task like fetching all your songs from your library), so a good retry and recover mechanism is needed. I plan to make changes to it whenever I have some time.

## 2018-10-23
- I read [Hard Costs of Third-Party Scripts](https://css-tricks.com/hard-costs-of-third-party-scripts/) and the resources linked from that post on CSS Tricks. It always feels good when developers flag the issues with third-party scripts. Unfortunately it's difficult to convince other parts of the organization aboy why this should be in the radar.
- I listened [Episode 21: Web Infrastructure at Spotify with Jason Palmer](https://www.sitepen.com/blog/2018/10/19/episode-21-web-infrastructure-at-spotify-with-jason-palmer/). As a web developer working at Spotify I'm so grateful of the work that the Web Infra team is doing. It shows how to establish recommendations and sensible defaults supported by the infra team, without strong enforcement. This is the best thing I have ever seen happening for web development at Spotify. 

## 2018-10-22

- I'm cleaning up my laptop. I didn't want to delete some videos about web performance experiments and explorations so I decided to upload them [to Youtube](https://www.youtube.com/channel/UCWOAK2KnodBRd8LYnUNW35g). A few short videos related with some posts I have written. Someone might find them interesting. Also, it's surprising the amount of stuff I can accumulate on a computer I have used for 3 years.
- While cleaning I found an immplementation of a React-like library called [bloop](https://jlongster.com/Removing-User-Interface-Complexity,-or-Why-React-is-Awesome) (see [the code here](https://gist.github.com/jlongster/11192270)). I went through the post 3.5 years ago as I was trying to learn more about how React worked. Libraries like these never get old.

## 2018-10-21

- Finished reading "It doesn't have to be crazy at work". I'm an awful reader. This might be the first book I finished in 14 years.
- Read [Smashing Magazine's Monthly Web Development Update](https://www.smashingmagazine.com/2018/10/monthly-web-development-update-10-2018/). I learned about the text-only versions of [CNN](http://lite.cnn.io/en)'s (why doesn't http://lite.cnn.io/es work?) and [NPR](https://text.npr.org/)'s websites thanks to [this post](https://mxb.at/blog/hurricane-web/). Ended up in love with [Max Böck's site](https://mxb.at/) which is super fast and very well designed. Noticed his integration with [Web Mentions](https://webmention.io/) and tried to implement on my blog, only to find out that the Twitter integration with IndieAuth doesn't work "Twitter login no longer works due to a change on their website".
- Read about [MDN's Layout cookbook](https://developer.mozilla.org/docs/Web/CSS/Layout_cookbook) with some flexbox and grid-based solutions for usual layouts.
- Started putting together some ideas about right-to-left support on websites. Drafted an outline for a post and when looking for resources I found out lots of interesting specifications for topics like hyphenation, cursives, bold, punctuation, uppercase and more on [International text layout and typography index](https://w3c.github.io/typography/index) and [Arabic & Persian Gap Analysis](https://w3c.github.io/alreq/gap-analysis/). It's not directly related with RTL but it's still interesting to keep in mind when supporting those languages.

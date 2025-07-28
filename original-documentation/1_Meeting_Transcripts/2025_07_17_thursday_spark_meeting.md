# Process Automation Workshop (31)

**Original File:** Process Automation Workshop (31).docx
**Extracted Date:** 2025-07-17 (Thursday)
**Converted:** 2025-07-28 11:40:37

---

Transcript

July 17, 2025, 12:59PM

Bryan Wolf   0:13
Hey, can you hear?

Peter Wolf   0:15
Hey.

Bryan Wolf   0:20
We.

Peter Wolf   0:21
Very muscled.

Bryan Wolf   0:23
*** **** it, man. Why? ****.

Peter Wolf   0:26
I don't know. It's really quiet.
So like, if you're using your headset, it doesn't sound like it's working and it's just trying to hear you through the laptop, wherever that is.

Bryan Wolf   0:37
I know.
Sound better now? Sound better now?

Peter Wolf   0:42
So quiet.

Lem   0:47
Hi, guys.

Peter Wolf   0:49
Hey.

Lem   0:54
Yep, yes, so.

Peter Wolf   0:57
Peter's not going to join cause he's standing at the at the Driver's License Bureau waiting to get in. I don't think Nick's gonna join either, but hold one second.

Lem   1:05
OK.

Peter Wolf   1:12
Uh.

Lem   1:16
OK.

Peter Wolf   1:27
Um.
So Bry, Lem and I did it start recording, right? I don't know if I clicked that button or not.

Bryan Wolf   1:36
Yeah, it is. Yeah, it is. It is.

Peter Wolf   1:40
You got to figure out what's going on with your headset because I cannot hear you at all.
I mean, I know you're talking cause I can hear you through the door. I can barely hear a muffled. You don't hear him, do you?

Bryan Wolf   1:48
Is it better now? Better now?

Lem   1:50
Yeah, very. Yeah, verified.

Peter Wolf   1:52
Very, very faint, bro. Really faint.

Bryan Wolf   1:55
****.

Peter Wolf   1:58
Try putting the Bluetooth on. I got, I got, um, I got iPad or Airpods up here. Go put your Bluetooth on and switch over to one of these.

Bryan Wolf   2:03
Yeah, hear me now. Or is it any better? Any better? Better.

Peter Wolf   2:09
It's not any different price.
If you want to try and switch to an Airpod, come up and grab one of these. They're fully charged.
All right. So earlier I met with Lem and just gave him some some guidance. There's a video out there that from earlier from this meeting that you can, I guess you can go to it even though we used the same meeting and.
But there should be an earlier video with this. What in that discussion we talked about where we are with this particular process flow, which I'm calling the the the contact contact information process flow contact database.

Lem   2:46
Yes.

Peter Wolf   2:59
And Lem, we'll we'll go through this stuff. Lem, you said earlier about where you found issues and we made some corrections. We'll play around with it a little bit, see what's going on.

Lem   3:10
OK.

Peter Wolf   3:12
But let me just think here, I was thinking about.
Um, bringing in.
Uh.
Yeah, you know what? Hold on a second. I I'm gonna. I'm probably gonna shift gears here. I'm gonna. I'm gonna go pull up. If you can pull up, let's see if I can get Bart.
What I want to probably do is pull up the process flow for the newsletter and and along with that probably the process flow for the.

Lem   3:50
OK.

Peter Wolf   4:00
The LinkedIn posting automation where we had it go from an article to the posting automatically, right?

Lem   4:08
Yep. Oh, yeah, yeah, that's right.

Peter Wolf   4:11
So let me see if I can get him to join because as I was saying to you earlier, I think he could work on refining. OK, here, hold on. I'll pull him in. He's available. Yep, Ken.

Bryan Wolf   4:17
Who to join?
Can you hear me now?
And get who to join, Nick.

Peter Wolf   4:28
What?

Bryan Wolf   4:29
Who get who to join?

Peter Wolf   4:31
Bart.

Bryan Wolf   4:32
Oh.

Peter Wolf   4:34
What was wrong with your headset?

Bryan Wolf   4:37
I don't know. I have no idea. I just put the Airpods in.

Peter Wolf   4:39
OK.
Hey, Bart.

Bartosz Borek   5:15
Hey guys, what's up?

Lem   5:17
Hello.

Peter Wolf   5:17
So on the call I got Bryan and Lem, the offshore developer and Bryan the the hard working intern. So Lem has been working these process flows. Honestly Bart, I don't even know how much detail or.

Bryan Wolf   5:17
Morning, Bart.

Bartosz Borek   5:23
Haley.
Hey, Brian. Hey, Lem. Nice to meet you. OK, Yeah.

Bryan Wolf   5:26
How's it going?

Peter Wolf   5:37
I've talked about with you or not. My intention was to bring you into this stuff long ago, but kept getting sidetracked and So what have we talked about on that or have you seen it?

Bartosz Borek   5:43
Yep.
Just the the automated. The only thing I heard is that we're creating an automated newsletter and you showed me kind of how that works a little bit, but that was the last I heard so.

Peter Wolf   5:55
OK. OK. So we've we've actually created a bunch of different flows now, but the the newsletter is actually one that I want to pull you in on because I think you can add a lot of value here. So we we created I'll say two process flows that have to do with posting and and marketing and.
Visibility and thought leadership. One is where we we have a feed from Eno Reader, which is RSS feed from news sources where we identified authoritative news sources like Financial Times.
You know, economy, The Economist, Wall Street Journal, whatever. And we put in that we were interested in topics that are technology slash A I and Treasury.
Focused to to try and select articles that would be attractive for posting one. And So what we do and I have to maybe Len you can pull that one up as we're talking. We we we go after process flow it goes to in a reader in a reader set up to pull these.

Lem   7:00
OK.

Peter Wolf   7:07
Articles. They gather the articles every day. The make.com is the process flow kind of hub and it's like Zapier, which is another one and like Microsoft Power Automate, which will be taking these. We're gonna put them into Microsoft environment. Right now they're outside Microsoft environment.

Bartosz Borek   7:18
Yeah.

Bryan Wolf   7:20
OK.

Peter Wolf   7:27
So then it calls an API, goes to the to the Inno reader and captures the. It captures the the list of articles, but not the full article. It captures the header, the source, the title, the source, and a summary of the article. Maybe 50 words or something.
To minimize the number of tokens being used and it feeds that then into into ChatGPT or I think it's ChatGPT we use there. It feeds that into an API to ChatGPT. ChatGPT then takes.
What is a prompt delivered along right now? It's like a I think we were. I think we're using my my persona prompt or something like that, right? So let me, I'm sorry, let me step back a second. So in these process flows, we have a whole bunch of process flows that I.

Bryan Wolf   8:16
Yeah.

Peter Wolf   8:22
I think are really great, but they're they're really at the very good prototype stage, right? They need, they need some ******** focus on the nuance to get them to the really.

Bryan Wolf   8:29
Yeah.

Lem   8:30
Yeah.

Peter Wolf   8:37
Awesome, productive stage. And So what I've done for the last, we're at six weeks now, right? We're in the 7th week. What I've done is working with Lem and the interns is identify a bunch of process flows and get these basic process flows up and running, looking pretty decent and we'll show you some stuff.
But they're not right there yet. They're not fully there yet. And what what needs the focus is that someone like me or you that's much more knowledgeable about the content and also knowledgeable about prompting can pull those two things together and create some prompts that are going to get the right.
result, right? So like in my writing persona prompt, it identifies what the target market is. It also says right now, because I've made some changes and they turn out not to be so great, I added in my kind of my my history, right, another document that's my professional
And I said it should use that and it should try and say and make references to it, right? Like, oh, in the 50, you know, in Fortune 500 companies I've implemented over the last 25 years, I found this to be the case. The problem is it's referencing it too much. It's like it's saying, well, when you did this and it's just way too specific.

Bartosz Borek   9:52
Got you.

Peter Wolf   9:56
And I want it to be more like, oh, make sure you understand my context and loosen it up a little bit, right? So then, yeah.

Bartosz Borek   10:04
Hallucinating at all or is is everything is it? Is it? Is it hallucinating at all? Or is everything like OK, cool. All right, that's.

Peter Wolf   10:04
Yeah.
Go ahead, say again.
No, no, it's not hallucinating. It's really being probably way too specific. It's it's being too precise in reading my history and then wanting to, well, you know what? That's not true. It maybe has hallucinated a bit. It will take the fact that I work with this company and then it will take some other reference to some other function that I did and it'll pull those two together.

Bryan Wolf   10:15
Yeah.

Bartosz Borek   10:15
All right, that's the.
I don't.
Yeah.

Peter Wolf   10:30
But it's definitely referencing my history. It's taking some liberties in tying some things together and saying, well, when we did this, we we created 80% process improvement or something where maybe I I wrote something about 80% process improvement somewhere completely different.
So it's yeah, it it's it definitely is being too detail oriented and capturing my stuff and it's it's combining some things that aren't legit, but I.

Bartosz Borek   10:53
We got that.
So we gotta, we gotta tell it to tone down that it like, hey, now you you're now at like 95. Yeah, you're now at 90 sales. We want you down to like 30 or 40, right? Yeah, yeah, exactly. Yeah.

Peter Wolf   10:59
Yeah, tone it down. Yeah, we just like when we used to do the sales, right?
Exactly. That is exactly what I'm talking about. So that's the experience I'm talking about too that I think we need to bring to the table. So, So what what there's different spots where we send this information and so the reason Lem, if you can go to the to the.

Bartosz Borek   11:09
Yeah.

Peter Wolf   11:22
the single posting, not the newsletter, because it takes, it's a it's a start, right? The newsletter is that times 10. So I want to start with the with the the single posting. So this is where we started out was we go out the inner reader, it pulls these articles and we were only saying, you know, 10 or 20 or something like that, but this could pull 100 articles.

Bryan Wolf   11:25
Mhm.

Lem   11:29
Oh, OK.
5.

Peter Wolf   11:42
articles. Then we only take the summary because we don't want to use too many tokens since we're doing this every day. And then it feeds the summaries into ChatGPT with this target audience information, saying find me the best three articles out of all this stuff that you think would be of interest to this
Target market and and send me back that list of three right from the 100 or whatever the number is. So there's the first time a prompt needs to be very explicit in saying what's the target market? What are we trying to achieve? And here's a problem, not a problem, but here's another nuance.
Well, let's just stick with that. I'm gonna stick with the baseline before I make it more complicated. So a prompt that says, hey, find me the right combination article. I want treasury, finance, AI if possible, but technology to try and fit our niche right thinking that this is an automated process for you or for.

Bryan Wolf   12:30
Oh.

Peter Wolf   12:38
me or for Gilles or for John to get articles to automatically go from an article that we find, pull it in, have it select the article, the three best articles out of the you know the the group of 100. And then take those three, then go get
Then it feeds it back into Make. So here we'll look right here if we can. I don't know if we can let me get see mine's kind of small. Yeah, if we can make that a little bit bigger. Yeah. So over on the left hand side we got the Inno reader and it's set at a given time to to feed these articles or to trigger the the the make call the hook.

Bryan Wolf   13:04
Run it.

Peter Wolf   13:17
And for then make that aggregates those summaries of the articles, whatever the number is from whatever sources we say and then it feeds those grabs that document with the persona or the kind of target market document. Again, right now we use something already had, so it's not perfectly aligned with that.

Lem   13:28
OK.

Peter Wolf   13:37
Needs to be refined for this specific task. Then it takes that and it feeds that persona doc plus the list of the articles with their title and the source and the summary, and it feeds them all to ChatGPT, generic ChatGPT, not a custom ChatGPT. We're using API, right?
So then it feeds all that. Then that that ChatGPT using that persona and that list says here's the three best, right? Turns around and feeds the three best back out. The iterator then says OK, grab one, grab the second one, grab the third one. Now what it has is, and I think that was at that point already when it took those.

Lem   14:15
Yeah.

Peter Wolf   14:16
Three, it not only, and I can't remember Len, maybe you'll help me out so I don't get mix these up with the news article. When it feeds back the three, did it already write something or at that point was it just giving us the three best ones when we put it on the spreadsheet?

Lem   14:24
OK.
Yep, that's right. The the one that is writing is this one. Yeah, it's just choosing, yeah.

Peter Wolf   14:34
OK.
Yeah, OK, good, good. So now we get the three. Yep, now we get the three. Now we now we look to what add find an image. Now even if there's an image with the article, then we use that image. Otherwise we generate some generic business looking image that fits the topics and it creates.

Lem   14:46
Yeah.
No.
Yeah.

Peter Wolf   14:55
Creates an image to go with each one because posting on LinkedIn with an image better than posting without an image right to give something and then it looks into the list. We have a spreadsheet, a Google sheet and it puts these three on the Google sheet with the link to the.
Image and the summary and the source and the title and puts that little summary in there, right? So then we have a spreadsheet. We go into that spreadsheet and we can look through those summaries and say, OK, you know what, I want to pick this one of the three. Or maybe this is happening every day.

Lem   15:23
Yep.

Peter Wolf   15:33
And I have three from yesterday, three from today. And so I have six there. It's been several days and I got 10 there, 9, whatever. I can then pick which one I want, select the button, and then it sends that one with the persona now. Now this should be a different one. This should be the persona, whereas the other one should be.
Really target market, right? Target audience definition. This one now should be the writing persona. Whether it's you or me or John or somebody else, it should be their particular writing persona. Then it feeds that back.

Lem   15:55
Yep.

Peter Wolf   16:08
To the to the to chat GPD again with the persona and the article and the and the image feeds that all and it says write me a blog, right? Write me a a LinkedIn posting blog.
Takes that, automatically filters out the articles, then it well, it feeds it back for us to edit if we want to edit right? And then we have a different process flow that takes that and actually feeds it into LinkedIn and directly posts it, correct?

Lem   16:26
All Lincoln post.
It's not.
I I yeah, but this is for the like newsletter. I'll let me just.

Peter Wolf   16:45
This is not for the newsletter, right? We're talking about the one that was for just the posting, straight posting.

Lem   16:50
Yep, that's right. Let me just pull up the yeah, yeah.

Peter Wolf   16:53
So this one was the newsletter because see, what we did was once we had that flow, we then said, OK, well, now let's start taking these articles, let's feed them into a newsletter, right? But the same initial foundation of selecting the articles, taking the summary, using the target market, feeding them in, getting an image. But then we were putting them onto a spreadsheet.

Lem   16:57
Yeah, it's actually.
Yep, that's right.

Peter Wolf   17:13
Intention of creating a a newsletter, but these had very similar, at least initial processes there, right?

Lem   17:20
Yep, Yep, that's right. Yeah. Let let me just, uh, OK.

Peter Wolf   17:22
So in that process flow, when we in the process flow where we do the automation for the posting, it comes back, then we have the opportunity to edit it, right? It comes back as a Google Doc I think and we get a notification that it's that it's completed the draft.
I believe.

Lem   17:40
Uh, yeah, for the newsletter. Yep, that's right.

Peter Wolf   17:42
No, no, not for the newsletter. For the individual posting, the blog posting automation.

Lem   17:45
Oh, for the.
For the.
Blog or LinkedIn? The LinkedIn one.

Peter Wolf   17:53
The LinkedIn blog post automation, yeah.

Lem   17:55
Oh, OK, let me just pull up the LinkedIn one because it's actually on like my different account, so.

Peter Wolf   18:04
OK.

Bartosz Borek   18:04
Is there gonna be some type of control before it uploads to LinkedIn or is there gonna be any type of control or is it just gonna automatically up upload stuff to LinkedIn?

Peter Wolf   18:09
But we need some what?
No, This is why I said so. So we have first control is it comes back with all these sets of three, right? Every day it comes back with sets of three, puts them in a spreadsheet. So first control is I pick which one I want, right? OK, so that's one control. Next control is after we pick the one we want to feed.

Bartosz Borek   18:25
Yeah, yeah.
Yeah.

Peter Wolf   18:36
Feeds it in with the persona, it writes the blog, it creates a Google Doc and you can edit the Google Doc and then you say yeah, I'm done now click and then it goes to the next process flow which delivers it to LinkedIn and actually posts it.

Bartosz Borek   18:44
OK. All right.
Mm-hmm. Got it.

Peter Wolf   18:52
Now, once you've got to a comfort stage, you would hope you tested this a bunch of times and maybe you posted without, but for sure it's going to have those control points in it to to validate, right?

Bartosz Borek   18:52
OK. All right.
Yeah.

Peter Wolf   19:05
OK. So that is, that's the price flow. So in that one, there's two spots in my view. One spot is target market to identify what you're trying to do, what's your objective? And given that this is an isolated single article, if you think about it fully in isolation.

Bartosz Borek   19:05
All right, good. Yep.

Peter Wolf   19:22
That shouldn't be that difficult, right? What's my target market? I want senior executives in, in, in, you know, in in Treasury finance and but maybe you want to bring it down to operational as well every now and then. But here's where it starts to get beyond one, right? If you're just doing one in isolation, you say where your target market is.
If you start now talking and saying, hey, over time I'd like a variety, well, now you have to start to think about your process flow. After it's done your your post, it should put that to a repository. And then when it's going to make an assessment of the next articles, it should say, what have I already
That right. This is where it starts to get more complicated. You say over time, I want a little variety. I want some things that are focused on finance, some that are focused on technology. Well, what did you do? Well, the last three were all technology. Maybe you should do a finance post. And that's another aspect, right? I think. But I'm not even there yet, right? I want to get.
This first flow working where I get to select so I can use my own memory of OK, what did I do last week? Now I got these nine to choose from. I'll pick one that's finance instead of tech. But later on I would think that would be automated Part 2, right? So that makes sense. So that's the one.
And that target market shouldn't be that hard, right? This is what we're trying to go for. Select me once there, the next one, the persona one, this is something we've been working on and playing around with and you know, for individually and together at different stages. I still have not gotten to the exact point where I'm getting what I want.
I am getting better results when I use my persona with Claude, but I need to give it some fine tuning. But this is an area where I think you know you engaging and working with Lem and Bryan or whatever would be a great opportunity to try and refine this particular.

Bartosz Borek   21:13
Yeah.
Yes, OK.

Peter Wolf   21:17
Process flow. So that's one. Now taking that and Lem, I know now that you went to this other account to get that. Now I'm gonna take you back to the news article thing. So the next one started out as newsletter and.

Bartosz Borek   21:18
Mhm.

Lem   21:25
Yeah. Oh, OK.

Bryan Wolf   21:31
Hey.

Lem   21:32
Yep.

Peter Wolf   21:33
I don't know. I'm pretty sure, Bart, you have seen because you might even turn me on to it. I don't know. Was the Superhuman, Superhuman Newsletter, Superhuman AI.

Bryan Wolf   21:43
Yeah.

Peter Wolf   21:45
Do you know that one, Bart? Yeah. OK, so this superhuman AI one comes out every day. I'm not thinking daily, certainly not in the beginning, but it has just a nice compilation of information.

Bartosz Borek   21:45
Yeah, we we we we discussed it before. Yep.
Mhm.

Peter Wolf   22:01
Different sections with different kind of focus and even the sections change a bit on day-to-day, but I wasn't going that far. So what we came up with actually, can you Lem, can you just pull up one of our latest iterations? Yeah, so here's.

Lem   22:13
Yep, this one.

Peter Wolf   22:17
Here's a newsletter. Starts out with some kind of image of us, right? Then it's some some intro. Hey, overview. Here's what's going on. Welcome back. Like, this is what we got to show you today. Then some. Here's some quick bullet point aspects, right? Again, kind of giving you an overview of what's going to happen today. Then it goes down to articles.

Bartosz Borek   22:22
Yeah.

Peter Wolf   22:37
And again, this image thing, this is coming from that same article feeder, right? It's picking the three per day, whatever. Then we go in and pick and say, well, the newsletter should always have three articles, let's just say, every day or every time. Let's just say we start weekly. So it's got a week of articles in the spreadsheet. We picked the three.

Lem   22:43
Yep.
Yep.

Peter Wolf   22:57
Want in the newsletter, same as we would for the single posting to go. We ensure we're not overlapping and doing the same topics, but you can see here it has an image. The image is either the original article image or a created one. It's got a link to the actual article. It's got.
The header, it's got the the source, right? Business Insider, whatever the source we got it from, Newsweek, you know, whatever. Financial Times, it's got the and then it's got a blurb. The blurb came from when we got the articles in and we selected it.
It then fed to something similar to the the create a LinkedIn blog post. Instead though the the definition was create a 50 to 75 words summary. Not just summary but a why is this important to you?
Right. Same thing about, hey, here's my target market. Here's an article that we think is the right for the target market. But why? Why do we want to? What? What am I going to say here? It's going to get the guy excited who's reading to say I want to click on this. This is, it's great. They pulled this together. Thank you for gathering and, you know, curating this list.
Of of information from me on articles, right. So that's what the intention is, is that that little blurb is supposed to be the boom, This is why you want to read. This is critical information. Here's something really cool given what the context is, right? So then we have three of those, but that again would be needs the persona.
But the persona and the definition of what the scope is, right? Only write 50 to 75 words, whereas the LinkedIn post is, you know, 300 words. I don't know whatever we're setting, but it would be the same kind of persona. Now, initially, I'm going to be a little bit selfish here initially.

Lem   24:38
OK.

Peter Wolf   24:50
I had envisioned this as being generic, that it would be from STS. Then when I was engaging with ChatGPT and and and Son of for. Yeah, Son of for.

Lem   25:01
Oh.

Peter Wolf   25:08
Opus for talking about strategy, I shifted a bit to be that really that it would come from us, but it's going to have a tone from me, right? So really that introduction is going to be me saying, hey, here's the, here's the.
The letter from STS practice this week and here are the topics and here's why it's important to you. Then it goes down the articles and these articles are supposed to be then my commentary about why this article's critical, right? At least this is where I'm at. Again, I'm kind of swaying. I didn't want it to be too much of the Peter world, but.

Bartosz Borek   25:38
Mhm.
No, it has to be personal. It has to be personal for people to read it. They have to think that it's personal. We'll talk about that in a second. But yeah.

Peter Wolf   25:46
So then.
That's most.
Again, that's what I'm getting from this conversation with the son. He's like, yo, what you're doing is you're saying you're bringing your 30 years of experience to the table and this is you and your team. But you saying, hey, leadership of this team, here's what we were bringing to the table, right? So now you get the three articles. That's the first section is articles.

Bartosz Borek   25:56
Yeah.
Yeah.

Peter Wolf   26:11
Then we Scroll down, go to the next thing. Now we've got social media. So we've got API's that are going out to Reddit and to LinkedIn. Now the Reddit ones don't seem to be working out that great, but LinkedIn for sure we could.

Bartosz Borek   26:16
Mhm.

Lem   26:22
So.

Bartosz Borek   26:26
Right. So don't. I wouldn't use Reddit because I know Reddit is like that's one of their problems. When their IPO went out, they said that Reddit isn't really that effective because a lot of companies just block the website. So if you work for like a Citibank or if you work for Goldman, it's blocked. So don't even use it.

Peter Wolf   26:28
Yeah.
OK. Again, this was us. These are, these are, these are great things that I think you could add value into, right is is one in how do we refine our inner reader selection of the sources and what do we put in the selection criteria like what we're saying right now is.

Bartosz Borek   26:46
Yeah, yeah.
Yeah, yeah.
Mhm.

Peter Wolf   26:59
If it's a financial source, then we'd probably tell we want to focus on articles that are about technology. If it's a technology source, then we'd probably tell we want articles that are focused on finance, right? Because on each source you can identify what's your selection criteria. We haven't been, we haven't refined that well enough right now to get the content we're interested plus.

Bartosz Borek   27:05
Mhm.
Yeah, yeah.

Peter Wolf   27:19
We had originally a selection of of sources that just weren't working out that well. You know that list we were using for the scraper. We started adding in some of those and we're seeing, OK, well, they have some sources. Yeah, so we're seeing they have some sources too. But what we have to do is go and figure out what that.

Lem   27:26
OK.

Bartosz Borek   27:29
Yeah, like Global, Global Treasurer and yeah, yeah.

Peter Wolf   27:39
Source set is that's going to be worthwhile in our in our focus. That's that's a critical one, right? Figuring out that source says source set for the news articles and what is the criteria for getting the right articles to begin with to be compiled together to feed for the selection, right? Then the next one is.

Bartosz Borek   27:42
Yeah.

Peter Wolf   27:57
What's the target market definition? Again, I would say this target market may be different than the individual reader LinkedIn post target market. This is going to be, it's going to be mixed. We want to focus on strategic level. At the same time we know that people are more likely to be reading this are also execution operational.
So what we need to do is find a balance of articles. This is where it starts to become more complicated than just the single article. Yes, I can pick the articles so that makes it where I could say, well, I want one that's strategy, one that's operational, one that's SAP, right? Something like that. I could do that manually.
But this is where you now want to craft the wording that's talking a little bit strategic, a little bit operational, finding that right mix. So this is where the persona part becomes again critical. You also need to be thinking about these in group context, not individual like the single article, but if you're saying well.
Here I got three articles. Is there a theme to these articles? Maybe there's not. What about the trending on social media? Is it a theme in the trending on social media? Do we try and find a theme that we can push or are they individual social media points? And same thing here. This would then write a blurb.

Lem   28:56
Yeah.

Peter Wolf   29:13
Now the blurbs on social media, I was thinking would be a little bit shorter, but same concept up top. We got the individual articles and image. Here we got the the social media. Now one thing they had in they have in superhuman A I.

Lem   29:26
Right.

Peter Wolf   29:31
Is their first one is often a video, right? Here's an interview with, you know, the head of such and such company or the leader of AI, this or that. So that's pretty cool. So we could look at that too. Like the first one could be some kind of interview here that could spruce that up a little bit because it's immediately interacting.

Bartosz Borek   29:35
OK.

Peter Wolf   29:50
You have an image, you see somebody that's recognizable, kind of like the images for the article, but it's a click one and you can immediately watch link you to YouTube and you can see the video, right? So this is the second section. Again, persona similar but not exactly the same. Trying to get some kind of theme or at least communicate this in.

Lem   30:02
OK.

Peter Wolf   30:10
In a way that's showing consistency. So now we get down to the next part, next section productivity tools. Now here we could have it going out or we would do this the other day, ran perplexity and said tell me the and we did this when we were starting the interim program trying to figure out what we were going to work on.
Top three tools in each of these sections, right? Finance in marketing and sales and blah blah blah blah blah. We could go through and figure those out. We have a spreadsheet. In the spreadsheet we have a specific tab for the tools, so we could go find the tools we wanted and already have the next 20 tools.
That we wanted to talk about and and have them in the spreadsheet or we can go search them however pull them in. Same kind of thing though here now as a tool give some kind of little blurb, some overview or summary. Here it's not really a.

Lem   30:51
Yeah.

Peter Wolf   31:03
It's not like a commentary, I don't think. It's more kind of a definition of the tool, you know, a summary of what the tool is and less about the commentary. But we could do the same thing here. You could have commentary here. But again, another section kind of interesting. The problem I find here is.
What do you focus on, right? You know in in in in the finance, we talk about all the time in the finance area, tools they can and can't use right outside the system. They're not going to be able to feed anything. Are we pitching them and showing them tools they should be talking about with their leadership that would come behind their firewall? Are we talking about tools?
That don't have to do with finance or where they could get generic information and find information and use information in a way that's not problematic. By sending that information out, I don't know. This would be we'd have to work on refining. What is our objective here and what kind of tools are we showing? But here you see we have like Microsoft Copod. OK, company doesn't.
Microsoft not interested, not of use to them. They don't have Copilot activated, I don't know. But maybe this is just informing them. It's trying to inform the public about tools and options. That's the way I see it, right? We're not trying to sell them anything. We're trying to give them visibility.

Bartosz Borek   32:14
Wow.
How dynamic? How dynamic is this gonna be? Because like, you know, are we gonna have Microsoft copilot in there every single time we release a newsletter like?

Peter Wolf   32:26
I'll show you in a minute. It's similar. It's similar to the other. We're going to select which ones we want to include. We'll show you. I'm sorry. Can we just can we? Yeah, you can ull U the sreadsheet. Ull U the sreadsheet.

Lem   32:29
Yeah, we could. Yeah, that's right. Let me just pull up the.

Bartosz Borek   32:31
OK.
All right. Yeah, yeah, yeah. Sorry. Yeah.

Lem   32:40
Yep, so.

Peter Wolf   32:40
So this spreadsheet has multiple tabs. Each tab covers a section. So here's the filtered articles, right? Then you see that include in newsletter column G So there'd be 20 articles here, and I picked the three or whoever picks the three that are going to be included. Right now it has.

Bartosz Borek   32:41
AI tools and updates. Yep. All right, perfect.
Mhm.

Lem   32:50
Yeah, this one.

Peter Wolf   32:57
The date of the publication, the title, the source, the web, you are website URL, the image URL, and then the the the short sub, you know, subject description, right? The sub summary then you pick.

Lem   33:10
The blur, ye.

Peter Wolf   33:13
From those 20, we picked the three we want this week, and we're always going to use three. Or maybe we change it up, but we would select the ones we use. Then they get tagged as processed. You wouldn't grab them again. You'd filter for only unprocessed and you probably wouldn't use articles that were from last week. Next week you'd use the latest batch and say only show me articles from this past.
Seven days since the last time we posted, right? So here we have total control on what we pick, but it's curated. The list has already been curated and narrowed down to what should be the best of the best. Then we get to the AI tools. Second one. No, no, second time.

Lem   33:39
Yep.
OK.
Oh, this one.

Peter Wolf   33:53
So here was we went out, identified the tools, plugged them in, and then I don't remember if we told it to go find or we we did a find, right?

Lem   34:02
Yep, it's uh, automatically finding uh update from the past.

Peter Wolf   34:07
Perplexity or something? Or where do we get it from?

Lem   34:09
ChatGPT, ChatGPT 03, I think it's here on the scraper. So this is, yeah, finding the updates from last week. Yep.

Peter Wolf   34:17
Yeah.
So it's going down, finding tools here, but again, it's populating it in and we can always plug in extra ones we want. But once we would select this tool, it would be processed. It would show a process we'd never covered again. So again, we're ensuring we're not duplicating.

Lem   34:26
Yep, that's right.
I.

Peter Wolf   34:36
And we're ensuring that we that we we have ultimate editorial decision making on which ones we're including at any time, right. Now this one's not really like the articles. You could have this list continue to build up and you know one that was relevant last week or the week before the week before.
Well, that still totally may be relevant, but newer information about something like the latest release of Gemini or the latest release of something else, we would probably want that updated, that kind of information that the blurb would be something more.
Up to date. So we'd have to think about that because right now we don't update these, right? It goes out and finds information that's relevant, that's recent and we select it and we process it. That would continue to build up. And I guess if you looked at an older one, then we probably would.
We would have to to look at a model, but here we also can add 1 manually, right? We can add 1 manually if I recall what we did. I know we did that on the articles one, right? So we found.

Lem   35:34
Yep, that's right.
Yeah, we could add here a link.
Yeah yeah you could add a link here and then click the create one sentence so it would actually process that link and create the like the overview and also the title and then we could include it to the new set.

Peter Wolf   35:44
Go ahead.
Right. So here's where we could do the part about, hey, I got three. I just saw this great thing on the latest release of Grok 4. Great, let's put Grok 4 in here and and update a blurb, put some link to where it is and and go that way, right? So.

Lem   36:03
Yeah.

Peter Wolf   36:10
We can control this again. There's feeding information in to help help narrow the focus, but we can drive it in a direction we want to manually as well and then have it update the same kind of information. The next one is if you go back to the newsletter so we can see the newsletter.

Lem   36:10
OK.
Yeah.
Yeah.
The prompt.

Peter Wolf   36:29
The next one's the prompt of the day. Now this got tricky, Bart, for the same reason of the data. What data are you gonna use? If you're given the prompt of the day, are you saying, hey, you expect that the reader's using this on the internal?
AI where it can put in any information it wants or external AI? Well, I was assuming they don't have the ability to do this on their internal system. So I was trying to think of posts. I want them to be robust, right? I want it to look like this, something more comprehensive than just a one liner like write me.
Information on finance or something, right? Want it to look like something substantive. But here was an example. You've got exposures and these are your three primary exposure currencies. And tell me what's happening with these currency pairs over the last six months and give me some information.
News of what would have driven that right to go out to the local, you know.
Oh, so I'm trying to blink. Uh.
Central bank for whatever currency and country and give me some information on that, right? So it's generic. It's not saying well this is how much exposures I have or something else, but this particular one I've used this I I wrote put this together which I GPT.
It comes back with some pretty decent stuff, says, oh, here's this what happened. You know, the pair is at its peak or it's low, and here's some news that would be relevant. So something that's of interest, but that they could go to external. But this we would also predefine.
Right. We'd go come up with what's the next 5 prompts of the day and we go work with ChatGPT, get the prompt of the day and we go back to the spreadsheet. We can go back over to the spreadsheet.

Lem   38:20
Um, here.

Peter Wolf   38:21
And I think here we have an issue with formatting, but ultimately we we plugged it in in a in a document or how did we end up? How did we end up doing that?

Lem   38:31
Yeah, we could just copy because we can like put a new line here, right? So yeah, we just put on a like note. Yeah, that's right.

Peter Wolf   38:40
Yeah.
We put the prompt title, we put the prompt and then and then we trigger it the same way we did just you know with the others. You select the button and say include in the newsletter and now we have prompt of the day and that prompt too if you go click on it in the newsletter.
It takes you to a editable version. You can just copy it and paste it right into your, you know, into your ChatGPT or whatever you're using and make whatever adjustments you need to make. So I think it's pretty cool. Again, it's variety. It mixes it up a little bit.
So then the last section.
Or maybe not the last section. Second to last section is Sarala's daily thoughts. This would be blogs that we've posted. And so here would be an opportunity for other people in the team to write a little blurb about a blog they posted, right? So similar to.
Like we talked about getting exposure for everybody now over the past week or maybe there was a blog posted a while ago, whatever. But we're gonna bring visibility to it and say, hey, here's somebody's opportunity. Different people on the team, they get their call out of their name on here, say I wrote this blog the other day or I think you'll find this blog interesting.
You can put byline by John Thacker or Bart Bartosz and Bart Bart, blah blah blah blah. You can put the bylines in there and.

Bryan Wolf   40:07
Nice.

Peter Wolf   40:12
And give people visibility, right? And this would be a link to the to the actual URL, takes them to our website. Again, gives us now visibility as a team. What's what's our thought leadership? What are we focused on? What kind of things are of interest?

Lem   40:24
Yeah.

Peter Wolf   40:31
And then this one would be the same thing. We have a spreadsheet, we have a, we have a spot where we could plug in the URL and I think we did the.

Lem   40:41
And so.
Create the summary for the blog post. Yep.

Peter Wolf   40:46
Yeah, so it would go out there to the URL, read the URL and create a summary. But again, here we could use a persona or maybe we just do a general summary and but we still give the person A tagline in there to show, hey, this was by senior manager on the team. This is by.

Lem   40:50
Yeah, that's right.
Yeah.

Peter Wolf   41:05
Director of the team, et cetera to give visibility to team members. And then the last one is upcoming events. So if we have the webinars coming up, we have whatever, Seralis Summit or.

Lem   41:15
Yep.

Peter Wolf   41:21
Something else or AFP and we're gonna be there. We can we can put it into here and do the same thing and then there'd be some kind of conclusion wrap up. Thanks. Appreciate your reading. Tell us if this sucks or if you like it.

Bryan Wolf   41:36
Nice.

Peter Wolf   41:37
So that that is the more complicated version of that single pass through. But in each one of these steps there is a prompting nuance that needs to be worked on to get it to deliver the quality and the select or not the selection because again.

Lem   41:38
You can.
Yep.

Peter Wolf   41:57
Well, the selection at up upstream, right? Finding the right sources, putting in the right kind of keywords to select from, having the right prompt once it gets to summaries to get the best choices to choose from. Then we manually choose, but then the prompt to write those with a certain tone and a certain target and a certain.
Kind of mix of focus on strategy and operations. That's critical. And then those other ones, again, fine tuning, how do we figure this out? How do we select them? How do we, how do we write about them? Which is going to be all about prompts, right?

Bartosz Borek   42:32
Yeah, I mean that's something I definitely could help with to be honest. Like the the prompting 'cause that's all we've been working on for like a few years. So very experienced here.

Peter Wolf   42:39
Yeah, right. That's why I'm that's why I pulled you in Bart. And so I know now we've got the RTX which is going to ramp up pretty quick, but we're still in a little bit of slow mode here I think with limited amount of of capability to do work. We got the sessions coming up and.

Bartosz Borek   42:45
It.
Yeah, for sure.

Peter Wolf   42:59
And we're supposed to be reviewing the documents and all, but I'm hoping that this could be something you could work on over the next week with Brian and or Lem. Does that seem manageable?

Bartosz Borek   43:12
Definitely seems manageable, no problem.

Peter Wolf   43:13
OK, all right. So now here's the here's the part that's, I think a little bit.

Bryan Wolf   43:15
Awesome.

Peter Wolf   43:22
A little bit more complicated relative to this. So Bryan's obviously getting up to speed on these workflows and is taking the workflows and putting them into my custom GPT or into my.

Bryan Wolf   43:30
OK.

Peter Wolf   43:38
My environment, my Gmail account, not my Gmail, my Google Drive and stuff like that. And Brian has increasing insight and understanding of where these components sit.

Bryan Wolf   43:38
Make.

Peter Wolf   43:53
But Lem is the one who really understands the nuance at the detail level. Yeah, the at the at the very specific granular level. Now in this case, in my particular view, the places where you see that paper with the blue.

Bryan Wolf   43:59
The ins and outs of everything, yeah.

Lem   44:00
Yep.

Peter Wolf   44:09
Those are the are the biggest critical points, right? Those are the points when we're using a persona. Now I believe the persona piece may be needed in other spots, but maybe it's not. And again, I think this is where we have to, we have to go start with what's the inner reader giving us?

Lem   44:15
Yeah.

Peter Wolf   44:27
And then put in those parameters when we have them and see what is the list of articles that come with. Because as soon as we put it in and Len remind me, but I believe if we go change the parameters, it'll show us for the last 30 days what we would have gotten, right?

Lem   44:41
Yep, that's right. On the inner reader. Yep.

Peter Wolf   44:42
So if we go in, we pick our sources, we put in our parameters, we'll be able to see what articles we would have gotten over the last 30 days. So figure that's four cycles, 4 weekly news cycles or 4 weekly newsletter cycles. So it should give us a pretty good indication Brian has access to the.

Lem   44:54
Yep.

Peter Wolf   45:02
Reader account so he can work on getting into this. He knows where these are. I think he generally knows how to put the selection criteria, but Lem is available for us to, you know, refine this or give guidance when if we're not quite clear on something. But this would be the first step. How do we find the right list?
Of sources and using again the scraper list that we had that we were going to those those they were treasury specific like Treasury Risk magazine and and TMI and and.
Whatever you recall those sites we were going to and I have them in my. I don't know if you how many you saved, but I have a whole bunch there.

Bartosz Borek   45:40
Yeah, yeah, I I I have them all saved in favorites, so not a problem.

Peter Wolf   45:45
Yeah. So, so this is an example where we would have to go through and find out are they all available, not available, which ones are going to give us the best content or or help us to get the achieved objective, right. So I would say this is first iterations of that working through this and trying to figure out how we get the right set of articles with the right.

Bryan Wolf   45:48
Mm.

Peter Wolf   46:03
Yeah, the right set of articles from each of the sources to combine it. And again, I think a mix of technology and finance sources, but with the objective of find the ones that crossover and hit those topics together, right. So that's the first thing I would say to to work on.
The second thing would be if we go to the next step where we now have the articles, we we select which ones we want or no, that's not true. We get the daily, we get the feed and the feed goes into the automation that sends it to ChatGPT and says which ones should I pick daily.

Lem   46:37
Yep.
This one.

Peter Wolf   46:43
Of the three, which one should I pick? And maybe that methodology is not the best. Maybe it should be 5. I don't know how many we're gonna find. This is where looking at the history over the last 30 days would give us a better indication. Are we gonna end up with 100 articles or 1000 articles or two? I don't know.

Lem   46:51
Yep.

Peter Wolf   46:59
But we would select some subset on a daily basis, assuming we get the best of the best on a daily basis. And then at the end of the week, or maybe we end up with two weeks every or a newsletter every two times of our week, right? Middle of the week, end of the week or something like that. We'll start with the idea we're sending once per week just to get.

Lem   47:03
Yep.

Peter Wolf   47:18
Our feet on the crayon. And so you'd have essentially 7 days of articles, 21 articles to choose from if we did three per day and we could find that much quality. And but then when we select the three, the next one is the persona.
Or not. That's the target market. It's set as persona. It's the one back a little bit to the left, that one that really should say target market, right? Just say get target market definition on the can you change the title?

Lem   47:39
Oh, sorry.
OK.

Peter Wolf   47:50
Target market, target market definition, yeah. So this is, this is, this would be our first one. What is that target market we're trying to get and is there anything else we need to clarify there, you know that we want to?

Lem   47:51
Yeah.

Peter Wolf   48:06
Certain mix or not, we're picking the well, no, this is still picking out of the how many we're getting on a daily basis. It's picking the three. So maybe you do want to say, hey, you want a mix of technology and finance or some days just finance, technology, I don't know. That's what we're going to have to refine. That's that's the second one, right. So.
Reader selection and then target market definition. Then that then gives us the feed to the spreadsheet. We already have the random generator. We have everything we need. Then we get to the find duplicates. It's fine, it has a unique ID, everything, so we know we don't duplicate the article.
Then this one is the persona. Now this is I think gonna be the the the trickier one again because.
Yeah, needs to be. We're saying my persona for at least that that.
The the blogs per the the blurbs per article. Now what we don't have here right now then, how do we produce the the intro? What's the definition for the intro?

Lem   49:12
Uh, the intro is here on the content aggregator. So yeah, this one we're also feeding the persona.

Peter Wolf   49:18
Do we decide it? Yeah, but do we decide it based on already looking at what the articles are or when does that? When does that get figured out?

Lem   49:26
The yeah, the the intro is just with the articles I think. So we could also put a like a static text and then just add on the information. But yeah, we are actually feeding the persona and like the title and.
Inputs which are the the.
Like the subsections of the articles. So that's like.

Peter Wolf   49:57
I'm sorry, I'm not quite following you. So is this? When does this occur?

Lem   50:02
When we already got all of the like for example we already got the all of the all of the data on the newsletter that we want so and then.

Peter Wolf   50:16
So we already picked everything we want to deliver, and that's when it gets triggered. Or at least the articles we picked. Or no, it's the whole content.

Lem   50:17
Yeah, we Yep, that's right.
Yeah, the whole content and then whenever we finalize and push a test e-mail so that this will trigger and then it will create the intro by on that time when we because the intro is also basing on the inputs from the spreadsheet. So that's why it needs.

Peter Wolf   50:26
OK.
That's what I want. But so here's again, this is where the persona matters, right? The persona for the introduction is some kind of, hey, welcome back. This is, you know, our strategic update from STS again with my with me being kind of the one who's communicating it and.

Lem   50:43
Yep.

Peter Wolf   51:00
And so that I would say this, this persona needs to be similar to the other persona that's going to write the articles. But we have to say, OK, you're writing an introduction here, right? The introduction should be 50 characters and it should be looking at the overarching theme in the in the list. And what does that look like, right? What is the, what's the?

Lem   51:06
Yep.
Uh, Yep.
Yep, that's right. Um.

Peter Wolf   51:19
You know what? What should we focus on?

Lem   51:22
Yeah, the only thing here on like this one, right? Let me just yeah, this is like a pretty simple like it's not maybe you don't like the like that because my test persona was also just.

Peter Wolf   51:31
Yep.

Lem   51:38
Very little. It's Yep, that's right.

Peter Wolf   51:40
Again, this is what I'm saying. I know that those are the weaknesses, right? Right now we were just using kind of fillers of whatever we had. We didn't focus on them. That's why I'm saying this is a this is a solid prototype that now needs to be refined to give us the specifics that are going to make it excellent, right?

Lem   51:45
Yeah, that's right. Yeah. Like a placeholder. Yeah, that's right.
Yep, Yep, that's right. Yep. Yeah, that's right. Yeah, because when I tested this one, I don't have like the persona, so I I just created like a placeholder for it. So like whenever we feed like a like a long persona based on your input, so of course the content would change.
So that is also need testing. So yeah, basically that's one of the part there because yeah.

Peter Wolf   52:22
OK, so again, the core persona, if if I if we did it right, the persona should again kind of establish this general overarching who am I talking without the references to either one hallucinating and making comments about my history.

Lem   52:36
OK.
Yep.

Peter Wolf   52:42
Where I have included my background, I work for these 50 companies and it's calling out specific companies and making too too specific a reference rather than generalizing. That's stuff that has to be refined and uniquely in the header versus the body. At least there's some aspects that would be unique in the header of the body.

Lem   52:56
OK.

Peter Wolf   53:02
The core of the persona you would assume would stay the same and the and the the specifics for each section would be what your intention on how you're refining and what the number of words are and whether you're supposed to be kind of selling it or not selling it or strategy or operations.

Lem   53:02
Yep.

Peter Wolf   53:22
Um, that's the stuff that needs to get refined.

Lem   53:22
Yep.
Yep, that's right. Yep. Um, yeah, so.

Peter Wolf   53:29
So, Bart, um.

Lem   53:32
umm

Peter Wolf   53:34
So uh.

Bartosz Borek   53:37
Next steps, right?

Peter Wolf   53:39
Yeah, next step. So what I what I what I would like to do I think is have a session or really I can send you my persona to take a look at at least where mine is and and I'm trying to think of.

Bartosz Borek   53:49
Yeah, yeah.

Peter Wolf   53:55
You know, I'm trying to remember because what I what I did where I was using my writing persona and this is maybe not going to be an issue here. I went to Claude and I said Claude, here's a new project and in the project I gave my persona, gave my background, I gave Serrala's background, E5's background.
Pull that all together as the feed in like a custom GPT, right? But in Persona, in Claude, they in Sonet 4 or Opus 4, they just call that a project, right? So you end up putting those same feeder documents in and this is where I'm saying it's being too specific, so maybe it's not an issue.
If I don't give it all that specifics, right? And maybe I take, maybe I what I do is take my history and say, you know what, Claude, generalize this, generalize this so that I can add it into my persona so it's clearer who I am and what perspective I.
Talking about and I can talk in terms of, you know, Fortune 500 companies and global implementations to ensure that that's the kind of tone that I bring rather than specifics of the actual number of companies or the names of the companies and I think.
That's probably my problem is that I'm referring to challenges I'm having where I'm putting it into Claude and really here we're not starting from that same base, right? It really is OK, here's a persona and maybe that's going to be fine. Maybe it's not going to lead to the same problems I'm having right now with the Claude project.

Lem   55:19
Yeah.

Peter Wolf   55:27
Make sense?

Lem   55:30
Um.

Peter Wolf   55:30
Barton.

Bartosz Borek   55:31
Yeah, that makes sense. That makes sense.

Peter Wolf   55:33
OK, so I can send you, you know, go ahead.

Lem   55:35
Yeah, I I'm also I I'm also thinking about the like the persona. Maybe sometimes like the creation of content would also get like it would like the context would be different if like we would use like.
Because your plan is to like, use just one persona for like the creation of content, right? And we actually have.

Peter Wolf   55:59
Well, it depends on the section again. So right now my bit, my vision is right now I'm going to do intro, I'm going to do commentary on the articles and then some wrap up and then in the middle, in the middle when we talk about the blogs.

Lem   56:01
Yep, that's right. Yep.
OK. Oh, OK. Yeah, yeah, that's right. Yeah.
Yep, Yep.

Peter Wolf   56:16
I don't know if those are going to be generalized summaries, and we're just going to give bylines to the people that wrote them, or whether they're going to try to have personas associated with them or not. Again, I'm going to start with just getting this thing where it's.
Working better than it is right now. Let's get personas in there and see the content. Let's get the selection criteria better and make sure we're getting the right articles. And then we could see, OK, are these other sections, should they have personas associated? I think they all should have personas associated because.

Lem   56:34
OK.
OK.

Peter Wolf   56:49
It should be about our target. Now the persona may not be my persona. It may be a more generalized persona of STS practice that comes from the perspective of we do finance and technology and that's our space. That's probably the case, right? That the that a that a more generalized persona could be applied to the rest of the stuff.

Lem   56:59
Mhm. OK, Yep.
Yep.
Yep, that's right. Yeah, I think the biggest part would be on the prompt because we could also do it like like giving examples, like a one shot, two shot examples, for example. Yeah, like like like your. Yep, that's right. Yeah.

Peter Wolf   57:22
Yeah.
Right. You brought this up before, right? I think maybe if we if we take this persona and we whatever the personas are and we say, hey, here's three articles, write me, write me 3 blurbs based on this and then and and ultimately see how it works and we refine the persona, refine.

Lem   57:43
Yep.

Peter Wolf   57:43
The persona. We finally get the persona and then we say, OK, here's 3 great examples of what I'm looking for and they can be additionally fed in like here's a persona and here's 3 great examples of what I'm looking for in the blogs, right? Because you said before that's that and we would put them in there, not necessarily in the persona itself.

Lem   57:46
We would. Yep, that's right.
Yep, that's right.
Yeah.
Yeah, then we could add it here.
Yep, that's right. Yeah. Here. Yep.

Peter Wolf   58:03
But in the in the prompt that goes in here, this is the part part where I think Lem's insights and knowledge is OK, do we put this in an associated document? Do we put this in the actual prompt inside of the make.com or where is it going to be most efficient to to go? The reason I like it in the document.
And why I'm thinking about the document approach as opposed to putting all of it into the make is I feel that that's much more variable and much more robust. So that let's go back to the one that's the individual article posting.
If we put it all into the make, everybody would have to have a separate make flow to get their article to LinkedIn posting. But if we have it where there's it's calling a unique persona based on the person who initiated it.

Lem   58:38
Oh.
Oh, the yeah, the the this one.

Peter Wolf   58:54
Right. Like if I say I trigger with an e-mail and we've had trigger emails on other stuff, but I can say, hey, I wanna write my article today and I trigger it on an e-mail or in the spreadsheet we have the person puts their e-mail into that article list and says I want to use my persona or.

Lem   59:00
Oh, OK.

Bryan Wolf   59:03
Thank you.

Peter Wolf   59:13
By putting my e-mail in, I know that's the persona associated with a specific document and that way we don't have to change the make. We make the make flow robust. It says here's different personas. If John asks for it, then use this persona. Bart asks for it, use this persona. Gilles asks for it, use this persona.
That way I I think there's a certain amount that should be variable that goes with the document approach as opposed to writing it directly into the make prompt.

Lem   59:35
Yep.
OK.
Yep, yeah, we could also do it via that one like, but we would feed like the example so that it would also be dynamic. So rather than getting the persona here.

Peter Wolf   59:52
If we're doing it with the different people, then we want the examples to be dynamic like the prompt. I mean like the persona, right? But yeah.

Lem   59:57
Mm.
Yep, that's right. Yeah, it would just like the different different data here. So it's not really like the whole overview of the your like like history or something. So it would be like a sample of the post because.

Peter Wolf   1:00:11
Yeah.

Lem   1:00:15
For example, let me just pull because like this one, it's just creating like a little blurb, right? And then if we feed like a very long persona, I think the the yeah it it would get confused because this is like very summarized and very like concise. So if.

Peter Wolf   1:00:23
Yep.
You're confused.

Lem   1:00:35
We we feed here like a sample that we want. So I think ChatGPT would like get the context better. So it would create the content based on that samples if if that makes sense because yeah the like the sections here we have here are like quite.

Bryan Wolf   1:00:42
Oh.

Lem   1:00:52
Uh, very concise. So yeah, that that's what I'm thinking. But um, yeah, for that one. But of course we.

Peter Wolf   1:01:00
I really, I really think it it depends on the section, right. I think that and it depends on how much we're trying to put a a spin on it. I'm hoping that that the the generalized again if we come up with a generalized target market.

Lem   1:01:04
Yep, that's right. Yeah. Um.
Yep.

Peter Wolf   1:01:17
And a definition of who we are as persona as STS, right? Some taking a history and again, Bart, we could take the history we have and just take that and generic genericize or whatever that is, make it generic.

Lem   1:01:23
Yep.

Peter Wolf   1:01:32
Not about specifics, but hey, we have been in business 35 years, blah blah blah blah blah blah blah and and and use that and say using this persona we want to create a blurb just generically that's not anybody's.
Any individual's specific persona, but us as an organization, I think that's going to fit for a lot of this stuff.

Bartosz Borek   1:01:57
Yeah, so we.
We'd want to create like a, I guess you could say like a narrator persona for Serrala, like Serrala Narrator or something like that. Yeah, yeah.

Peter Wolf   1:02:04
Yeah, an STS narrator. Exactly. An STS narrator persona for sure, right?

Bartosz Borek   1:02:10
We could probably use that as a prompt to be honest.

Peter Wolf   1:02:12
Yeah, yeah, yeah. So I I think that's what I would like you to to work on. Now Lem is in Philippines, so he's this is the end of his day. He has slated. We're scheduled that he get we have two hours from Lem every day.

Lem   1:02:13
Yep.
Yep.

Bartosz Borek   1:02:21
OK, so.

Peter Wolf   1:02:30
And then Lem is also dedicated to working not full-time, but when we're sleeping, he's building process flows and advancing things where we have something we've come up with and we make a change or we ask for a, you know, adjustment and then he makes the change and then following day we have opportunity to work with new adjusted flows.

Bartosz Borek   1:02:30
OK.
Yeah, yeah.

Peter Wolf   1:02:50
Or, you know, new inputs, new outputs, whatever. So that cycle works pretty well. Now you obviously you're on European time.

Bartosz Borek   1:02:57
Yeah, I'm in. So then, yeah, I'm in Central Europe, so I don't know what the time difference is. It's probably around six. So it's six hours. Yeah. So it's a six hour difference. So it will definitely be able to kind of get more time together, so.

Peter Wolf   1:03:04
So it's 12. It's 12 hours from us. So he's 6 hours from you, yeah.
Right.

Lem   1:03:10
Mm.
OK.

Peter Wolf   1:03:13
Yeah. So well, and again, knowing that your schedule obviously you know, I'm sometimes you and I are on at 3:00 in the morning, sometimes 6:00 in the morning, sometimes you work until 6:00 at night. So I also am not trying to screw you where you're turning your days into 20 hour days.

Lem   1:03:27
OK.

Bartosz Borek   1:03:28
No, that's fine.

Peter Wolf   1:03:30
But we'll if we can and Brian really is working kind of 8:30-ish 9:00 to to you know to regular kind of Eastern Coast, East Coast time. But so he's he's starting to make sure he's here for those two hours with Lim.
He could potentially work with you after that time, like right now we wrap up. I'm gonna have to drop off because I got to prepare for a AI strategy meeting with Oliver and it's in 11, so I'm gonna have to drop off, but you could definitely.
One, we can look at these flows more. We can figure out get into the details of where those prompts are and what the personas are, what the prompts are that are embedded, not just the attached documents. So you have a better understanding. Maybe Len could also just export those because when he goes in, he can identify what the prompts are in those specific.

Lem   1:04:16
Yep.

Peter Wolf   1:04:24
AI calls those APIs. Take that and the combination of the document and then you could work with Brian when Lems offline and say, OK, let's take these without the workflow and just say here's my prompt, here's my persona. Let me plug these together. Now let me take some article samples. What result do I get right and.
Find those. Then when you guys are done working, you can send it to them and say OK, here's the update or Brian. If Brian is comfortable enough, he could go back into the actual make and say let's update this prompt in here, but we should be making sure we're not overwriting. We should probably copy or already.
What we have is a copyright. Len has a version in his environment. We have versions in our environment. Bryan has a version in his environment. So we have lots of different versions going on. But then you could do a kind of versioning adjustment and see how that works. But I think working those items outside of the make is going to be the first thing because if we get the right.

Lem   1:05:05
Yep.

Bartosz Borek   1:05:20
Yeah, so.

Peter Wolf   1:05:21
Right results outside, then we can put it inside make and yeah, there's some difference in the way it calls exactly, but it should be essentially getting the same result, right? And I think that's a lot easier than constantly coming into make and making the tweak and making the tweak if we just sit there.

Bartosz Borek   1:05:31
Yeah, yeah. So who's actually gonna send me the?

Peter Wolf   1:05:37
Work with Claude or, and right now we're calling, we're calling ChatGPT. I would prefer we call Claude because I think Claude's writing is substantially better than Chat GBT's.

Bartosz Borek   1:05:47
Mhm.

Lem   1:05:48
Yep.

Peter Wolf   1:05:49
So I mean, for us to change that to Claude is no big deal, right? And we did set up a Claude API with allocated cash, so I don't think we have an issue there.

Lem   1:05:52
Yep.
Yep, yeah, we we just copy and paste the prompts actually on.

Peter Wolf   1:05:59
Right, Bryan, we did that.

Bryan Wolf   1:06:03
We did work with Claude, sorry.

Peter Wolf   1:06:04
Yeah, but I meant, I meant do we have, we already have Claude set up with the API with the with the tokens already purchased, right? A subscription. OK, so I would like to change that to to to.

Bryan Wolf   1:06:09
Yeah.
Yes, yeah. Mm-hmm.

Peter Wolf   1:06:19
To Claude the right anywhere it's writing. I would prefer it was Claude.
OK, even on the simple stuff, I would prefer we switch to Claude.

Lem   1:06:25
Yep.

Bryan Wolf   1:06:25
OK.
Mhm.

Peter Wolf   1:06:30
OK.

Bryan Wolf   1:06:31
Yeah.

Lem   1:06:31
On the content creation, right? Yep. OK, Yep. The writing. Yep.

Peter Wolf   1:06:33
On the writing, whenever we're when we're actually writing something, the end state writing that we're putting out in the newsletter or the blog, I want that to be clawed.

Bryan Wolf   1:06:34
For Inner Reader, yeah, for anything.

Lem   1:06:42
OK.

Peter Wolf   1:06:43
It's better. It's it's it definitely is better. I think more fluid, more human writing, at least what I'm seeing.
OK. So we'll make that adjustment. And then before I drop off, Bryan, yeah, go ahead.

Lem   1:06:55
OK.

Bartosz Borek   1:06:57
Alright, so yeah, I guess.
The the first step is who's actually gonna send me the prompts that are being used right now. So Lem this.

Peter Wolf   1:07:07
Yeah. So right now you guys will be on for the next hour. You guys can be on for the next hour. If you don't have something going on, you can walk through this. We can. Len can go to each one of those prompts, download them, put them into the chat and export them to you, right?

Lem   1:07:08
Oh, Yep.

Bryan Wolf   1:07:11
Yeah, 11 is up at 11.

Bartosz Borek   1:07:11
OK.

Bryan Wolf   1:07:21
Down to, yeah, yeah.

Peter Wolf   1:07:22
OK. And walk through each process flow, see exactly what we have and what's the, what's the prompt for each section and what are the different personas that we need to pull up. And yeah, I think that's the baseline really for the next hour. I'd say if we could extract all that stuff.

Lem   1:07:23
Yep. OK.

Peter Wolf   1:07:38
Then you guys would have what you'd need to be able to work on that while while them get some sleep.

Bryan Wolf   1:07:38
Yeah.
Progress.
Oh.

Peter Wolf   1:07:45
OK.

Bryan Wolf   1:07:46
Yeah.

Bartosz Borek   1:07:47
Yep, sounds good.

Peter Wolf   1:07:47
Awesome. All right. I'll, I'll talk to you guys later. Appreciate it. See ya. Bye.

Lem   1:07:47
OK.

Bartosz Borek   1:07:53
Alright, talk to you later. Thanks. Bye.

Lem   1:07:54
Jupiter, talk to you soon.

Bryan Wolf   1:07:54
Bye.

Lem   1:07:58
OK, so Yep.

Bartosz Borek   1:07:59
All right, so how many prompts? How many spaces do we? How many areas right now do we have where we have prompts being used? Like four of them, four or five?

Lem   1:08:06
For the content creation, we actually have them for all of the sections, so 12345.

Bryan Wolf   1:08:08
Um.
Oh, that's a lot.

Lem   1:08:22
Um, not this one.

Bryan Wolf   1:08:22
Actually, anytime there's like an AI agent.

Lem   1:08:26
Yeah, so this ones are just generic, so they are not really like creating the contents, but.

Bryan Wolf   1:08:33
Mhm.

Bartosz Borek   1:08:34
Mhm.

Lem   1:08:37
5-6.
Yeah, six to seven, seven. This one is the STS. Yeah, basically seven. So because we have, we could actually check them also here on the. So this one is every section is.
Has the like ChatGPT content creation, so filter out articles 1234 and then like the other ones are just like generalized creating the summary. So I'm also not sure if you would need yeah maybe Claude also for this one, but yeah it also has ChatGPT and then also.

Bryan Wolf   1:09:07
Hmm.

Lem   1:09:17
This one, the upcoming events that are coming from. Yeah, the links and then social media posts also. Yeah, so 123456. Yep, so basically 7. So we have 7.
ChatGPT prompts and yeah they have different like the formattings are different. So yeah you you've mentioned also a while ago right like you we could like embed the like the narrator style. So I also didn't have like a context on.
What the vision of like Peter here. So that's why I I I've just so that that's the thing also that like like he wanted to prioritize so like the granular details of the newsletter but basically the system the prompts here are like mostly.
And I'm feeding. As you can see, I'm feeding the persona, but the persona actually is just very simple. So let me just pull out also so that we could could have a context so that.
Let me just.
So yeah, the the test persona is just this one. So this was the first like this was coming from the dev notes that Peter gave me. So I've used this as the persona as a placeholder. So yeah, so I think.
Your input would be very valuable on like putting the final creation of the contents because yeah, basically most of these are like placeholder prompts. If yeah, if that makes sense.

Bartosz Borek   1:11:03
I I think the easiest way to do this would be if you guys can somehow extract it for me like into a whatever like some type of e-mail form and then each prompt I want. Yeah like whatever Word document, Google sheet, whatever but.

Lem   1:11:10
Yep, no problem.

Bryan Wolf   1:11:13
So.

Lem   1:11:15
Yeah, I I could. I could actually, like, yeah, a Google document. Yeah, no, I could actually just.

Bryan Wolf   1:11:18
I think comes out in Jason. It's like code.
But are the prompts all the text contents or they're all attached to the code like when you extract the Jason file or is that all stuff you have to put manually in every time?

Lem   1:11:31
It would be hard to read if it's on Jason, but what I can do is I could just create a document for each section then like I will explain. For example this prompt is for the let's say subsection and then I will also put like some details there that.

Bryan Wolf   1:11:34
No.

Lem   1:11:48
The like what is being inputted. For example we have here like the input data right? So I will copy the prompt and then also put like some description on what is the input data and then what what section is this on the newsletter. So would that work?

Bartosz Borek   1:12:07
Yeah, yeah, that that would definitely, that would definitely be extremely helpful because then I could go through them one by one and just kind of make edits and like it's, it would be very hard. Yeah, it would be very hard to do it right now because.

Lem   1:12:07
So.
Yeah. So that, yeah, that's right. Yeah, I think that would be, yeah, that.

Bryan Wolf   1:12:11
Mhm.

Lem   1:12:22
Yeah, I think because, yeah, I think, yeah, I'll just, yeah, I'll just create a document and then, yeah, I'll explain like just a rough overview of the flow and then I'll just, yeah, I'll just also put this as the title and then.

Bartosz Borek   1:12:22
Yeah, this is not very legible in this, like for me.
Yeah, that's perfect.

Lem   1:12:41
Like the prompt that I will give is all for the content creation so that you would also have that and then I just add some description and then like what is the where is the input coming from and also something like that. But yeah I could do that one and then yeah I think that would also.

Bartosz Borek   1:12:46
Mhm.

Lem   1:13:00
Much be much easier for on your on your side because rather than like rather than like reading this through my screen so it would be hard also for you right to like go go yeah like go back and forth and something like that.

Bartosz Borek   1:13:03
Yeah, for sure.
Yeah, I'm trying to right now. It's kind of difficult, so uh.

Lem   1:13:18
But yeah, uh, I could, um, do that one.

Bartosz Borek   1:13:20
So yeah, like let's say we're gonna go with that approach. When is the like, when do you think that could be sent over to me by? Is that something that you would work on? You'd probably work on it tomorrow, right? So.

Lem   1:13:24
OK.
Um, yeah, I can.
Yeah, I could work on it right now, tonight and then maybe I'll build, maybe just do it because it's just some copy pasting and then just some rough overview, maybe an hour, 30 minutes an hour so I can send it to you today.

Bryan Wolf   1:13:38
Mhm.

Bartosz Borek   1:13:44
OK.

Bryan Wolf   1:13:46
Yeah.

Lem   1:13:49
And then yes, so that you you you guys also could uh like talk about it or something whenever you talk also to Peter, so.

Bartosz Borek   1:13:49
OK.
Yeah. So it, yeah. So Brian, I think after I have that and I probably have like, I don't know, let's say an hour to play around, go through and make some changes to it. Yeah, then we could meet and then are you like what? What is your availability today?

Bryan Wolf   1:14:03
Digest it, yeah.
Later today. Yeah, I really so really all I'm doing today as I'm working on a dashboard for the Excel sheet that Justin sent me and then that's really it. I have some stuff to tie up with something else, but other than that I'm here all day.

Bartosz Borek   1:14:15
OK.
OK, OK, perfect. So we could definitely, uh, alright. OK, perfect.

Bryan Wolf   1:14:26
For another five hours, 6-7 hours, whatever it is.

Lem   1:14:30
All right, I would do you do you do you need also the yeah I think I would also give you like the top three because Peter I think mentioned to like edit also how the ChatGPT chooses so.
I think I would also give you this, uh, prompt and also like the target persona or something. So I think this is, yeah, the target market definition. Yeah, I'll add this one. So OK, yeah, I think this would, but.

Bartosz Borek   1:14:45
Mhm.
Yeah, yeah.

Bryan Wolf   1:14:52
Mhm.
And this is really what we're really specifically focusing on is the newsletter one, right? Yeah. OK, OK, cool. Yeah, yeah.

Bartosz Borek   1:15:01
Right. Yeah. Yeah, for sure.

Lem   1:15:02
Yeah, yeah, that's right. Yeah. Then use the other.
Yeah, the newsletter one. And then, yeah, so, uh, I think, um.
Yeah, it much it it would be much better, uh, I think on that side.
I can just also explain if you, but you, I think Peter already explained a while ago like the rough overview of the whole system. So yeah, you already like. OK, OK, OK.

Bartosz Borek   1:15:27
Yeah, yeah, yeah. I understand. Yeah, I understand the rough overview. Yeah, yeah, I'm good with that. Yeah.
So really just like the prompts and maybe like a a section header that just quickly describes like what the goal of the prompt is or like what the goal of the section is. Very basic, very basic, very basic.

Lem   1:15:35
Yep, so.
Yeah.

Bryan Wolf   1:15:46
Mm-hmm.

Lem   1:15:46
Yep, that's right. Yeah. Like the Yep, Yep. And then.

Bartosz Borek   1:15:50
And you know, the the other thing, the the reason I'm also asking for this is because you know, who knows who's gonna work on this stuff in like, you know, a few months from now. So it's just good to start having some type of documentation in case we decide to, you know, move it or.

Bryan Wolf   1:15:58
Yeah.

Lem   1:16:01
Yep.
Doc. Yeah, that's right.

Bartosz Borek   1:16:07
You know, use a different app going forward, so yeah.

Lem   1:16:07
Yep.
Yep, Yep, that's right. And also.

Bartosz Borek   1:16:14
OK. So, Len. Yeah. Yeah, go ahead. Yep.

Lem   1:16:16
OK, yeah, basically I also have like ChatGPT research here, so I'm not sure if I need to give this also to you or just the content, but because this is morning.

Nicholas Westburg   1:16:27
Good morning, guys.

Bryan Wolf   1:16:29
So, Nick.

Bartosz Borek   1:16:30
And Nick.

Lem   1:16:31
Yeah this is like the the like the automation for the scrapes like the like the link in something and like the AI automation tool. So I not I'm not sure but I think I would also give this to to you for yeah it's just using the ChatGPT 40 search preview because I.

Bartosz Borek   1:16:39
Mhm.

Lem   1:16:50
Yeah, we could also use like perplexity with this one, but yeah, I think your insights also would help this. So I'll just also send this to you and then yeah, OK, just that one, so.

Bryan Wolf   1:16:51
Yeah, these prompts too, yeah.

Bartosz Borek   1:17:05
OK, perfect.
Alright, so uh, Brian, we'll after we get this, Brian, we'll link up later today.

Lem   1:17:07
And then?

Bryan Wolf   1:17:13
Yeah, sounds good.

Bartosz Borek   1:17:14
OK, cool. All right. Lem, also, do you have my e-mail address or?

Lem   1:17:17
Uh.
Oh yeah, I I would need your e-mail address, so just put it on the chat so that I could. Yeah, then I'll send the document on a few hours from now.

Nicholas Westburg   1:17:19
Yeah, its.

Bartosz Borek   1:17:22
Can. OK, I'll put it in the chat. Alright, perfect.
All right, sounds good.

Bryan Wolf   1:17:35
I'm honestly, you want to send it to me too. That way I can just like digest it without having to go through each individual actual bubble, yeah.

Lem   1:17:39
Yeah, no problem. Yeah, yeah, I think, yeah, I'll, I'll send send it to you guys and also to Peter so that I wanted to also, yeah, but actually I'm also I I would I will be building like.

Bryan Wolf   1:17:48
Great.

Lem   1:17:54
Full documentation for this one. So I didn't build it yet because as you can see we started like just like 2 sections, right? And then we just add, we add. So like there are two, yes, too many movements. That's why I didn't like add. But yeah, I will also send this first.

Bryan Wolf   1:17:59
Mhm.

Bartosz Borek   1:17:59
Yeah.
Yeah, there's still.

Bryan Wolf   1:18:05
Yeah.

Bartosz Borek   1:18:06
Still too many moving parts.

Lem   1:18:14
Direct the prompts then. OK, yeah, let me just copy this one.

Bryan Wolf   1:18:17
Cool.

Lem   1:18:22
Um.
And then.
OK.
Yep. And yeah, I think that's it for the newsletter.
For a newsletter. Oh, also I want to share with you Bry about the like the AI agent. So I actually, yeah, was able to like connect it to the a custom ChatGPT. So it's yeah, it's actually now if we ask chat.

Bryan Wolf   1:18:47
Agent, yeah.
Oh really?

Lem   1:19:01
Actually have history here. Yeah, this one like can you get me all the details of Kathy Bergas? So it's actually sending the hook. It's just that.

Bryan Wolf   1:19:06
Mhm.
So now did you just upload? Did you just make custom GTBT and upload Peter's Excel information on the on the clients and the contacts? And then you're just asking the the the custom GPT itself? Or is it connected through the actual AI agent on me?

Lem   1:19:18
Uh, no. Um.
Yeah, that's right. Yeah, it's actually connected on the AI agent here on make. So that's actually it's just it's just passing the yeah, I've added it on the here on the like the actions.

Bryan Wolf   1:19:28
Oh, OK. How'd you do that?

Nicholas Westburg   1:19:28
I.

Lem   1:19:40
And then I've added a schema, but for the schema you would need you. It's much better to ask action GPT and not the generic GPT for the creation of schema, because I think you said to me last time that you you tested creating a.

Bryan Wolf   1:19:41
Right, yeah.

Lem   1:20:00
Schema using ChatGPT, but yeah, but.

Bryan Wolf   1:20:00
It was very limited, yeah.

Nicholas Westburg   1:20:01
Lem, have you checked out the connections? The new feature if you click on the connectors, if you click on the plus in the bottom left.

Lem   1:20:05
Oh.
Oh, this one. Uh.

Nicholas Westburg   1:20:12
I haven't really in ChatGBT.

Bryan Wolf   1:20:13
For GPT, I think.

Lem   1:20:15
Oh, this one.

Nicholas Westburg   1:20:17
Yeah. Oh, what the heck?

Lem   1:20:19
Oh, on the the generic one. Yeah, this is like the cost. Yeah, OK, yeah, this one.

Nicholas Westburg   1:20:20
Yeah, maybe.
Tool maybe under tools.

Lem   1:20:24
This one.

Nicholas Westburg   1:20:28
Oh, it's not there. I don't know why.

Lem   1:20:29
Maybe it's on the. I'm just on the plus, so maybe it's on like the pro plan or something.

Nicholas Westburg   1:20:35
Yeah, yeah, yeah, yeah.

Lem   1:20:40
Yeah, so it's not here on. Do you mean like the MCP server or?
Oh.
Mm.
Oh, OK, yeah.
OK, I see.

Nicholas Westburg   1:21:08
The features they roll out to plus users ahead of time, but yeah, I didn't know that.

Lem   1:21:09
Yeah.
Oh, OK. Yeah. But yeah, I think in the future they would just, they would upgrade also like the plus because that's how they do it, right. Like they whenever they're there, there's new features, they move down the like the like the the other benefits to the plus. Yeah, then they just, yeah, they.

Nicholas Westburg   1:21:27
The.
Yeah.

Lem   1:21:34
Add it to also the the lower tiers. So I think that's but yeah, basically we could also access all the automation via the webhooks. So that's actually good. Like for example here I'm just yeah, I'm just depending on the prompt of course that.

Nicholas Westburg   1:21:39
Yeah, yes.

Lem   1:21:51
Like on the action strike we could call like the web hooks here and then just add some paths and then like trigger different automations on make using ChatGPT. So I think yeah that that's also one way to do that. But yeah definitely the MCP would be like much easier if we could connect if we could connect.

Nicholas Westburg   1:21:56
Yeah.

Bryan Wolf   1:21:57
Yeah.

Nicholas Westburg   1:22:00
Uh, automation.

Bryan Wolf   1:22:07
Definitely.

Nicholas Westburg   1:22:08
Yeah, that's like, I would like.

Lem   1:22:11
That one to chat. Yep, that's right. But Yep, so.

Nicholas Westburg   1:22:13
Yeah.

Lem   1:22:20
Uh.

Bartosz Borek   1:22:20
Have any of you guys used the Brock 4 yet? Because I heard that's supposed to be the best thing right now, like last.

Bryan Wolf   1:22:26
Oh.

Nicholas Westburg   1:22:27
I have. It's really it is. It's good. I I paid for this. I haven't. I'm not paying for the $300, the Super Grok one, which is apparently or the the heavy one, which is apparently pretty good, but I'm pretty hard on it in terms of like the tests that I give the different.

Lem   1:22:29
Oh, sure.

Nicholas Westburg   1:22:47
LMS and my own personal benchmarks and it's really good. They got rid of the research feature and whenever you give it a prompt, the search is integrated and there's citations and sources with every response it gives. It's a really powerful model right now.
I I sent in the group chat that I'm in with everyone here. I think it's like a top two model right now, but between Claude 4 Opus and Grok 4, it's not just like hype, it's it's a really good model.

Lem   1:23:22
Is it the Grok the Q or like the Grok of X?

Bryan Wolf   1:23:26
Uh, it's.

Lem   1:23:30
You mean the oh XAA? Oh, OK. The group for XAA, OK.

Nicholas Westburg   1:23:30
XAI's model.

Bryan Wolf   1:23:32
Yeah.

Nicholas Westburg   1:23:35
Yeah.

Lem   1:23:38
Oh, it it was just released recently, right? Like, I think last week or something. Yeah, yeah, OK, that's it.

Bryan Wolf   1:23:40
Yeah.

Bartosz Borek   1:23:40
Yeah, like a few days ago.

Nicholas Westburg   1:23:40
Yeah, last week.
Bart, have you got a chance to play with it?

Bartosz Borek   1:23:47
No, I haven't. And honestly I've only used Grok like not that much cause I only just got the that like paid Twitter, paid Xplain or whatever. So I'm still using ChatGPT, but I am gonna try to, you know, test it out when I have a chance.

Nicholas Westburg   1:23:55
Yeah.

Bryan Wolf   1:23:56
Yeah.

Nicholas Westburg   1:24:05
Yeah, I think you'll like it too. Like the UI for it's really good. It's clean and it's nice having all of those. It really is nice having all the links and sources to like whatever prompt that you give and just having the sources and links.

Bartosz Borek   1:24:10
Yeah.

Nicholas Westburg   1:24:20
To refer to for every prompt that you give it because it's real time and it's good. It's really good. I think you'll like it.

Bartosz Borek   1:24:27
OK.
Looking forward to it.
Alright guys, so I think we're done for now, correct? So Lem, I'll wait for you to send those over and then Brian will link up and assess that and.

Lem   1:24:33
OK.

Bryan Wolf   1:24:35
Yeah.

Lem   1:24:36
Yep. Oh, yeah.
OK.

Bartosz Borek   1:24:44
Talk then.

Lem   1:24:46
OK, Bart, uh, nice to talk with you. OK, talk to you soon.

Bryan Wolf   1:24:46
Sounds great.

Bartosz Borek   1:24:46
All right. Thanks, guys. Yeah. Thank you. Yeah. Thanks, guys. Talk to you soon. Bye.

Nicholas Westburg   1:24:49
Have a good one.

Lem   1:24:54
OK.

Bryan Wolf   1:24:55
Lam, if you just wanna stay on, do you wanna are you gonna get hold on? I wanna see how you did. So you just so for the for the Skemna for connecting it to the agent. How did you do that? So every time I try to do that with the.

Lem   1:24:57
Hi, Brian.
OK, no problem.
Yeah, for this schema, yeah.
The generic one chativity.

Bryan Wolf   1:25:15
No, like I'd make a custom GPT like you did, you know? But So what are you saying the difference between actions and is that is the actions GPT like an actual GPT you can look up?

Lem   1:25:18
Yeah, yeah, but.
No, yeah, it's no. Basically I think you because I've also asked the schema for from ChatGPT but not the custom GPT which is this one, the actions GPT. So this GPT is actually.

Bryan Wolf   1:25:34
Good.
Yeah.

Lem   1:25:40
Like specific on creating the schema for. Yeah, that's right. So and then yeah, if we use maybe last time you used like just the generic Chachiki, that's why this. Yeah, yeah, the the schema didn't work. So yeah, I I used this one so you can access this also on.

Bryan Wolf   1:25:43
Make actions, yeah, so it's compatible to GBT, OK.
I just did and it wasn't good. It wouldn't work. OK, wow.

Lem   1:26:00
For example I will create create a custom GPT and then if we click the create new action so you can click this one get help from actions GPT and then it will opt in. It will open up this one the actions ChatGPT and then what I did here is I just ask it on plain words.

Bryan Wolf   1:26:15
Mhm.

Lem   1:26:19
So let me just pull out my history here then.
So this one so can you create a schema that will call a webhook and send my message on it and also get the response from it and then the webhook is this one. So it created the schema and then this is like the I put inputted this on the.

Bryan Wolf   1:26:35
But.

Lem   1:26:44
Like the custom GPT, but there's some error so I I'll pasted again the the error. So the error saying in context something like this so it actually.

Bryan Wolf   1:26:53
How did you know there's an error? Like when you when you plugged it in, so there's an error or you just read it and you tell like when you try to plug it in, it's like.

Lem   1:26:57
Um, yeah, on the.
The yeah, the the error was. It's not erroring out on. It's actually working fine, but there's some error here on the here. There's like error here like like a box that appeared that saying there's error and.

Bryan Wolf   1:27:09
My generation, yeah.

Lem   1:27:15
It actually just added this particular line, the property this one, so it's uh actually like like missing.

Bryan Wolf   1:27:21
So did you import it from a URL or you just plugged it in there, right? See how it says import? Yeah, yeah, yeah, OK.

Lem   1:27:24
Yeah, I just copy pasted. Yeah, that's right. I just copy pasted the yeah, the particular schema and then Yep. And then it after I tested it, it worked fine. And then as you can see, we could test it out for example.

Bryan Wolf   1:27:35
Wow.
That's great. Peter's Peter's going to be hyped about that.

Lem   1:27:41
Yeah, so um.
The the only thing only here is that it's actually for example this one. Can you get me all the details of and say other person so that it would?
Let's say this Eric and no, who said Eric Andress. So can you give me?
Can you give me all the information from?
Eric Andres so it will we need to click the like the something here like yeah this one so we need to click the like the confirm because this is like a like a two step verific I think like a security feature on chat.

Bryan Wolf   1:28:22
Trigger it.
Confirm.

Lem   1:28:33
GPT that like if the link for example, yeah yes only allow sites to try so that this yeah. So if we if we confirm that one, it would call that particular hook so we could actually check the history there here.

Bryan Wolf   1:28:33
Yeah, yeah, yeah, yeah, yeah, definitely is, definitely is. Cause they had told me that they had some sort of security blockage or barrier.
Hmm.

Lem   1:28:49
Um, let me just, uh, pull out the.
Not sure if.
What's that again assistant thing?
Um.
No, uh, custom.

Bryan Wolf   1:29:06
So now you're just gonna take every prompt and send it to me and Bart, basically.

Lem   1:29:12
Yeah, I'll just create the document and send. Yeah. So this is the like the format for that one, like a Webhook. And then we're calling the AA agent and then we're sending the response. Yeah. And then this one. So as you can see, here's the information, Eric Andress and then so it's actually getting the data and then.

Bryan Wolf   1:29:15
Right.
Oh, OK, yeah. Another webhook, yeah.
Oh, it's so good. That's really good, love.

Lem   1:29:31
If we, yeah. So it's actually working. I didn't. I wasn't able to mention it now because we were busy, right. But yeah, yeah, yeah. But they only said it to me actually a while ago. And then I already have some rough idea because I researched it also, so.

Bryan Wolf   1:29:39
I know you're doing so much of stuff here.
2.
Uh huh.

Lem   1:29:50
Then yeah, but yeah, basically this is already working fine and we could, I think you could do this yourself also so that you could like, yeah, check the.

Bryan Wolf   1:29:57
I could, I could. I'm probably when we get off this, I'm going to review the call and just go over it.

Lem   1:30:02
OK.
Yeah. OK. Yep. So, yeah, I think that that's it. That's how. Is it clear on the custom GPT? Yeah, it's on the actions.

Bryan Wolf   1:30:07
Are we really talk tomorrow?
Yeah, yeah, yeah, yeah, it is.
'Cause I've I've tried to use it before, right? I that's that's how we originally started. That's what I was trying to do is have it call directly from ChatGPT. But my schema would be wrong. It would be wrong and it the actions were there's something glitch. You know what's wrong with it, so it wouldn't work, but.

Lem   1:30:23
Oh, OK.
OK.

Bryan Wolf   1:30:33
Um, I'm gonna use that custom skin or I'm just gonna take exactly the one you have. But um, the yeah, yeah, that's great. That's great right there. I'm gonna utilize that a lot in the future for other custom GBTS.

Lem   1:30:38
Yeah, the actions GPT. Yeah, this one. Yeah, yeah, yeah, if.
Yeah, that's right. Yeah, this is very useful because we could also ask this. No, no, no. Yeah, this is, this is, yeah, this is actually from Chachi PT. As you can see, yeah, they built this for like very specific Chachi PT. Yeah.

Bryan Wolf   1:30:48
Now, did you make this one? You didn't make this one, did you? No, it's just in the store. Nope. Nope. Nope. Nope. Nope. Yeah. Yeah, yeah, yeah, yeah.
I checked you too, yeah.

Lem   1:31:01
Yeah, this is very helpful, I think. Um um.
Uh, to use an API? Yeah, this one. Um, Yep. And then oh, do you also want to get the schema that uh for this one? The one that?

Bryan Wolf   1:31:18
Um, yeah, actually, yeah.

Lem   1:31:18
Or you you could just. OK, I'll just also send this to you so that you could also copy this. Yeah, no problem. This one. The. Yeah, the.

Bryan Wolf   1:31:25
Is that OK? Yeah.

Lem   1:31:33
And then I'm just not sure if, yeah, I think it would.
Also add the available actions. I think because I've just copied, copied this, pasted it, then it automatically put the available actions and then yeah.
Yeah, I think that works OK and we we could also like edit this one like to add more as I've mentioned a while ago right to add more like paths like add more hooks and then we would just edit the summary here and also like the operation ID like.

Bryan Wolf   1:32:13
Yeah.

Lem   1:32:14
For example this is like the title right? And then this is like the summary like the description of the tool. So we could add here for example this one is opening the like the database like the Google sheet and then the other one is like creating a document or something. So yeah this is very useful the the actions GPT.

Bryan Wolf   1:32:24
Yeah.
OK, yeah.

Lem   1:32:30
Yeah, Yep, that's good. And yeah, I think that's it. And so you have more questions or?

Bryan Wolf   1:32:38
Yeah.
Oh, I think I'm good. I think I'm gonna go repeat and then I'm sure tomorrow we'll we'll we'll dig into this more.

Lem   1:32:45
OK, yeah, I'll, I'll start. Yeah, no problem. Yeah, I'll start also creating the like the prompts. Yeah, the documentation so that I could send it to to. Yeah, because I think it's kind of hard for him also like to one by one and.

Bryan Wolf   1:32:50
OK.
The document. Yeah, yeah, yeah. Thanks.
Art.

Lem   1:33:04
And edit this because yeah, he he he need, he actually need to test it on his own environment, like for example, yeah.

Bryan Wolf   1:33:05
I know, I know, I know.
Well, here's the thing too, is that is that you like when you make this sheet, it's gonna be hard 'cause I don't know if you're gonna be able to get to them like right away. It's gonna take a little time 'cause you're gonna have to tell them like what? See how this is like #1 I know reader RSS feed. You're gonna have to say like #1 or like like scenario #1.

Lem   1:33:18
Yeah.
Yeah.

Bryan Wolf   1:33:30
******* fine duplicate or whatever it is like the like what does it say? I can't subscription for news or what does it say? Yeah, yeah, to the right. So whatever, like see how this one says choose. Like you have to really differentiate which one's which. That way we're not plugging in the wrong ones in the wrong spots. You know what I mean?

Lem   1:33:33
Yeah.
By this one.
Yep. Yeah, that's right. Yeah. So I think it's much better really to just give him the and also it's much.

Bryan Wolf   1:33:46
Yeah, yeah.
The actual make. Well, I think it's just hard for you because you're gonna have to go through and copy paste each one and you can't just like throw it on, throw it together in one doc. You gotta be like, well, this is for scenario one, scenario two. This is for the third.

Lem   1:33:56
Uh.
Yep.
Yeah, yeah, but my plan is, yeah, my plan is to just put it all on one document. But I I will just add like the title there, for example the this.

Bryan Wolf   1:34:08
Yeah, whatever. You know what I mean.
You're gonna need to. You're gonna need to 'cause then even I I I can help him 'cause I have mine and mine are gonna be the exact same thing, so I know exactly where it is. But I would say even if it's like it takes a little longer, I would do it the other way and you don't have to send it to him right away right now 'cause.

Lem   1:34:19
Yeah.
Uh.
Yep.

Bryan Wolf   1:34:33
I mean, or I don't know what your schedule is like. You do whatever you want, but yeah.

Lem   1:34:34
Um.
Yeah, I think yeah, I need to because he would need to edit it, I think on his own like environment for example. I'm not sure if what his plan is, but I think his plan is to like.

Bryan Wolf   1:34:48
Yeah.

Lem   1:34:52
Edit this one and then put some like dynamic ones here, like for example the persona. He would add the persona here because my plan is to just put some notes here that this is persona coming from like something like that. This is a dynamic variable that has the persona, so that's my.

Bryan Wolf   1:35:02
Mhm.
Yeah, I just wanted to know exactly where it goes for each one, but I get what you're saying though, so you can just read it and make it better. But yeah, OK, I mean, alright, well.

Lem   1:35:12
Uh, plan on creating the document.
Yeah, yeah.
Yeah.
Yeah, so yeah.

Bryan Wolf   1:35:24
Sounds good. Then shoot me an e-mail too, and then, you know, we'll talk tomorrow, I guess.

Lem   1:35:27
OK.
Yep. So yeah, yeah. And also I would my plan also is to create like much more detailed on the AAI agent because the AI agent actually has some very like like complex.
It's a complex system because it's all of the variables, the prompt and also does like the system is like the what automation is doing is all In Sync if you know what I mean. So that needs more like.

Bryan Wolf   1:35:59
No.

Lem   1:36:02
Like a proper like like a loom video. So I haven't I think yeah I haven't built it yet right like the like the the whole tutorial because we were still editing the like the main main.

Bryan Wolf   1:36:10
Yeah.

Lem   1:36:18
Like database of Peter, but now I already have the database so yeah I could add that one. So I think that would also help for you to like edit this one on like different use cases for example on what to change and something like that.

Bryan Wolf   1:36:29
Yeah.

Lem   1:36:34
So yeah, and yeah, I already sent you also guys the prompt, right? So this is like pretty long. So I actually trimmed, yeah, I actually trimmed this down so I removed some example output so that the output is quite dynamic.

Bryan Wolf   1:36:43
I have that. I have that. Yeah, he's got that too.

Lem   1:36:54
Already like the final output is dynamic, so I trimmed this down also so that it won't get long, but it's actually very long already. Yeah, so yeah, so that's that's good. But yeah, this this is already working fine. I tested it from end to end from the task tool one to tool five, so all is working good and then.

Bryan Wolf   1:37:02
Yeah.

Lem   1:37:14
Just need testing because yeah I I'm not sure also on how Peter would use it. So I think I would need this input on that. But maybe next week I think he said next week would be is is more free next week I think.
So that's yeah, the update on the agent also the database assistant.
So Yep, I think, uh, it's good.

Bryan Wolf   1:37:43
That's good.

Lem   1:37:46
Uh.
OK, so yeah, I think I'll or yeah, it's OK also if but I I'll just start creating the documents now if it's OK with you or you you need to.

Bryan Wolf   1:38:03
We can hop off. You can do that stuff if you want. I'm just. I'll wait for you. Wherever you want to go. I'll hop off right now and you can just do you have a meeting after this at 11.

Lem   1:38:04
Um.
Um.

Bryan Wolf   1:38:14
Or not today.

Lem   1:38:15
Pardon. Um, come again.

Bryan Wolf   1:38:16
Do you have another call after this at 11 or not today?

Lem   1:38:19
Right now, no, I I don't have a call. So yeah, I could work, work. Yeah, work on the problem.

Bryan Wolf   1:38:22
OK, cool, cool, cool. Yeah, yeah, I I'll hop off. You bang it out and just send it to me, OK?

Lem   1:38:27
OK. OK, Bry, I'll send you guys in. OK. Talk to you. OK, Bry. Bye. Bye.

Bryan Wolf   1:38:28
All right. All right. Chair. Talk to you tomorrow. Yeah. Thanks. Bye.

Peter Wolf stopped transcription


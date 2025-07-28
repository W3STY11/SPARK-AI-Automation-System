# Process Automation Workshop (16)

**Original File:** Process Automation Workshop (16).docx
**Extracted Date:** 2025-06-26 (Thursday)
**Converted:** 2025-07-28 11:40:36

---

Transcript

June 26, 2025, 12:58PM

Peter Wolf   0:05
Wait for a second.
Wait for those guys to log in and I'll be back.

Lem   0:09
OK.
No problem.

Bryan Wolf   1:12
Yes.

Lem   1:17
Hello.

Peter Wolf Jr   1:20
Hello, gentlemen.

Peter Wolf   1:35
Hey guys, I we got cleaners. Just came in the house.
I'm gonna switch over to my phone and connect back in.
I'll be back on in just a minute, OK?

Lem   1:45
OK.

Bryan Wolf   1:53
Hello.

Lem   1:55
Yep.

Bryan Wolf   1:56
Is Apify an LLM. Like do I need to buy API tokens for us to use that in like the 4th?

Lem   2:05
The they actually have like a free like trial with $5 credit.
So you can just use that one for like testing, but if.

Bryan Wolf   2:11
No.
Eventually I had to buy some.

Lem   2:17
Yeah, eventually you would need to buy credits for like the scraping.

Bryan Wolf   2:23
OK. All right.

Lem   2:32
Did you start already the hooking it up the flow?

Bryan Wolf   2:38
No. So I so the web hooks right?
I gotta change.

Lem   2:42
Oh yeah.

Bryan Wolf   2:42
I don't know 'cause you know how you have it? Before it was like two was to H3 was to C4 was to E.

Lem   2:51
Yep.

Bryan Wolf   2:52
So I gotta I gotta.
I gotta know the order.

Lem   2:55
Alright, great.
I actually changed it to like the hooks there.
I've changed it to the like.
Reference so.
Let me just check.
Yeah, I didn't put the links I've added there like a guide so that it would be easier to.
Yep, yeah.
And then CEG.

Bryan Wolf   3:23
So did you.

Lem   3:25
Yeah.

Bryan Wolf   3:25
Did you change anything from?

Lem   3:29
Just from yesterday, just the formatting, so I've played around with formatting so this is just the like the number three. So and then just the prompts from ChatGPT for the formatting. So I just like edited. Yeah, so everything else is the same, just the formatting for chat.

Bryan Wolf   3:40
Yeah.
That's it.
So everything else is the same.
Cool, cool, cool.

Lem   3:51
Gpt.
Like the size of the.

Bryan Wolf   3:52
And the web hooks I make my own, right?

Lem   3:55
Yeah.

Bryan Wolf   3:56
I'm making my own web hooks, yeah.

Lem   3:57
Yeah, the web books.
Yep, you you would make your own web books.

Bryan Wolf   3:58
OK, OK.
Alright, alright.

Lem   4:02
Then that's the one that we will copy paste to the Google Apps script for the.

Bryan Wolf   4:07
Alright.

Lem   4:08
So now we have 5 web books already.

Bryan Wolf   4:14
I am hard.

Lem   4:14
Yep, 5 web books.

Bryan Wolf   4:17
Endpoint.
S.

Peter Wolf   4:20
Hey, guys.

Bryan Wolf   4:24
Hey.

Peter Wolf   4:25
All right.

Lem   4:25
No.

Peter Wolf   4:27
So.
Yeah, I apologize.
I'm just shifting around here a little bit.
Can, yeah.
Can I heard you just kind of clarify?
Can you tell me what what changes we made? And then Brian, if we can also talk about.
The.
The the updates to the Eno reader and the the tool for the social media put in those additional accounts in and stuff like that.

Bryan Wolf   4:56
Yeah.

Lem   4:56
OK.

Bryan Wolf   4:58
Ours and that.

Lem   4:58
Yeah. So.
Let me just share my screen first.
OK.
So yeah, I just changed some some prompts here on ChatGPT to add the size.
So now it looks like this one, so it I added some like it will like add some highlights to some of the words on the paragraphs and then I've also added like a line on before the like the photo.

Peter Wolf   5:18
Yep.

Lem   5:35
Then.

Peter Wolf   5:35
And I like that.
So you narrow, that's great.
The photos much better like that. Terrific. OK.

Lem   5:37
Yep, yeah, the photos are much smaller.

Bryan Wolf   5:39
Yeah, yeah, yeah, yeah. Wow, very good.

Lem   5:43
And then.
Yep, so this is the same and also for the I've like a smaller I've added a size to like smaller width and then yeah, I've changed the background color to not like a pitch black just like a like a light dark.

Peter Wolf   5:54
OK.
OK.

Lem   6:03
And then.
Yeah, for this one I've added also like a placeholder.
So we can like add here like also a banner from serrala so that it would it would be like highlighted also and then yeah this is basically the blog post summary for the Serrala Daily insights and then Yep we have the conclusion.

Peter Wolf   6:10
OK.
Good.

Bryan Wolf   6:18
OK.

Lem   6:23
So Yep, I think that that's it.

Peter Wolf   6:23
OK.
So then one piece is missing.
Oh, hold on. Go back down.
Oh, OK.
So, right, OK, OK. Couple things.
The.
Up back up to the articles.
The articles are.
The articles are too too long.
The blurbs? They're 100 and 100 and 25130, I think. Was I kind of looked at?

Lem   6:41
Oh, OK, yeah.
Yeah, this is.

Peter Wolf   6:47
We said we were looking for 75 right or 50 to 75. So if we take those.

Lem   6:48
A.
75.

Peter Wolf   6:53
Even with the the header part right 'cause, you gotta really consider the header part in there too, which is 2 lines.

Lem   6:54
Yep.

Peter Wolf   7:02
That I want the maximum 75 somewhere between 50 and 75.
So we need to go back and adjust the prompt on that and then.

Bryan Wolf   7:05
Yeah.

Lem   7:08
OK.

Peter Wolf   7:11
If we Scroll down a little bit more.

Lem   7:12
So.
75 words 50 to 75.
Yeah. And then maybe one to two paragraphs.
Or maybe one paragraph? Yep.

Peter Wolf   7:20
Yeah, right.
Yeah, I mean.
'Cause it's it's like 10 words per sentence, right?
Good morning.
It's like 10 words per sentence is kind of the norm, I think.
So I mean that'd be 5 sentences and if you got the one where you have the highlighted kind of blurb above, I think it's probably just gonna be one paragraph, right.
A highlighted blurb or a highlighted.
What is that? If you go back to it again, it was like a short.

Lem   7:46
Yep, 1:30.

Peter Wolf   7:48
A short.
Umm.
Extract or something, go back up a little bit.
It's not really the title. What you have bolded there is not the title right?

Lem   7:55
Oh.

Peter Wolf   7:58
Or is it the title?

Lem   7:59
Yeah, this is the title. So it's also picking it up for yeah from.

Peter Wolf   8:01
Oh, it is the title. OK, OK.
Yep. OK. So I would say I would say that the yeah, if you if we assume the title's gotta be several words, then I really think that the body should for sure has gotta be below 75.

Lem   8:06
I know reader, yeah.
Yeah.

Peter Wolf   8:21
Again, I put 50 to 75 and and that's really.

Lem   8:23
Yep.

Peter Wolf   8:27
Yeah, let's. Let's see how that looks when we do that.
But maybe we should be saying it really should be.
Keeping it to town at one type paragraph.
And if they're trying to go into two paragraphs, yeah, then it's it's it's already going too far.

Lem   8:36
Like what?
One burger, Fred.

Peter Wolf   8:40
Right, that we should be still in the 50 to 75 words, one type paragraph and that way it'll it'll keep us.

Lem   8:41
Yep, OK.

Peter Wolf   8:46
We won't have extra spaces between paragraphs, so we keep it kind of from top to bottom on the newsletter tighter as well.
So let's let's put that in as a parameter, OK?

Lem   8:53
OK.

Bryan Wolf   8:53
Here we go.

Lem   8:55
Yep. Also for the title I think.
Yeah, we could also feed it to ChatGPT to make it, because I'm just adding it this one from the raw title from final reader and yeah, so this is.

Bryan Wolf   9:09
I will get it.

Peter Wolf   9:09
You mean for the calculation or or? What are you saying?

Lem   9:13
From the Ino reader here. So.

Peter Wolf   9:17
Yeah.

Lem   9:18
This actually is.
Also putting the.
Extracting the title.

Peter Wolf   9:26
Yeah. I mean I like the title.

Lem   9:27
So yeah.

Peter Wolf   9:28
I'm I'm fine with the title.

Lem   9:29
OK.

Peter Wolf   9:29
I don't.
I don't have a problem with that.
I just am thinking about the overall the overall effort. Yeah, the overall number of words there. OK to keep it tighter.

Lem   9:31
Just like this one. Yep, the OK.

Peter Wolf   9:38
OK.

Lem   9:38
Uh.

Peter Wolf   9:39
So then that's that's good.
Then go down to so. So on that. Let's stick with this here.
So in the e-mail reader we listed a bunch more.
Sources Brian, did we get those into the in O reader?
This is Brian. Yeah.

Bryan Wolf   9:54
Oh, yeah, yeah, yeah, yeah.

Lem   9:56
Oh, right.

Bryan Wolf   9:56
I had like two of them, three of them, some of them I couldn't really like throw as many options there for for, you know, the sources that you wanted.

Peter Wolf   10:07
So the ones I listed weren't all available.

Bryan Wolf   10:07
Yes.
Some of them were. Some of them weren't.

Peter Wolf   10:12
OK.
So can we pull it up and see what we ended up with?
Because I think there were also some I wanted to take out like Kiplinger.

Bryan Wolf   10:18
Yeah, hold on. Yeah.

Peter Wolf   10:19
Kiplinger finances is really personal finance.
It wouldn't be something I would include there.

Bryan Wolf   10:25
Yeah.

Peter Wolf   10:32
You come out. Come on.

Bryan Wolf   10:36
One second.
I did it on my account alright.
Mm hmm.
Yeah.
Sit here.
Let me pull this up.

Peter Wolf   11:32
You guys share your screen.

Bryan Wolf   11:34
No, I mean, so which ones do you wanna?
You wanted to get rid of, so I didn't. I unadded a couple.

Peter Wolf   11:38
Yeah. Can you share your screen?
Right. OK.

Bryan Wolf   11:40
Yeah, yeah, yeah, yeah.

Peter Wolf   11:41
Can you share your screen?

Bryan Wolf   11:55
So this is on your account, so I haven't added them yet.
I did it online but this is the ones that he wants, right?

Peter Wolf   12:01
OK.
So I I would take out.

Bryan Wolf   12:01
So MIT technology review.

Peter Wolf   12:03
Hold on. Hold on. I take.

Bryan Wolf   12:05
Yahoo.

Peter Wolf   12:06
I would delete.
I keep the economist.
I would delete Motley Fool.

Bryan Wolf   12:10
OK.

Peter Wolf   12:13
I don't know what that editor's picks is that Apple is that Apple?
Kind of repository or whatever.

Bryan Wolf   12:18
I don't even know it's a.
It's a popular one though.

Peter Wolf   12:25
Let's let we'll leave that for now.
I take out well Yahoo finance again.
That's curation.
It's not them writing it. I don't think it's them kind of consolidating it.

Bryan Wolf   12:33
Right. It's just pulling from, yeah.

Peter Wolf   12:37
I don't know what quartz is.
Take take out Kipperger personal finance.
We'll keep the rest of those for now, then.
Show me what you had on yours.
Which ones from the list we have?
Which ones?
Were available.

Lem   13:13
What folder?
Follow.

Bryan Wolf   13:25
I think most of these are the ones that are not on here. Most of these first ones.
So global finance magazine, this is like, you know, clearly not.

Peter Wolf   13:34
I'm not seeing. I'm not. Oh, OK.

Bryan Wolf   13:36
Clearly this isn't their actual magazine.
Now these are some of the ones that Claude's recommending. So this one was is just not a real thing.

Peter Wolf   13:44
Global finance magazine.
Nine articles in the Week 13 followers.

Bryan Wolf   13:49
But this is probably like somebody else's had done this or something or or like it's not the.

Peter Wolf   13:51
That.

Lem   13:54
I think it's only like this follower is only on IG reader.
So Yep, that's why it's little follower, but.

Peter Wolf   13:59
OK, OK.
Yeah. OK.
So what other ones, Bri?

Lem   14:08
We could.

Bryan Wolf   14:08
An extra none of these are.
They're all like smaller, like even the MIT one.

Peter Wolf   14:13
Well, we're saying smaller, but again it's but it's in a read.
It's because we're talking about in a reader their followers on in a reader, not a lot of people are using API, right?
Or I mean maybe there are but, but it's certainly not like people are necessarily reading, reading them overall.

Lem   14:23
Yeah. Yeah. It's just on I.
Yeah, on I never reader.

Bryan Wolf   14:33
Am I teaching?
Do review.
But some of these, that's like I know you want to stick to more finance based stuff.
So this one supposedly it is more like AI application but.

Peter Wolf   14:40
Yeah, but, but, but if we.
For sure this is gonna be technology and AI, whether it has a spin of of finance or not.
But it may be they come up with an article, you know every now and then that is that is finance focused.
So I would definitely keep them.
All right. So, Brian, again, what I want to do is after this call, I want to go through this with you. Then I would like to put those in. And I'd like to look at what we is, what we put in the parameters. It shows us how many.
Articles in the last month that those parameters right.

Bryan Wolf   15:19
What do you mean the parameters?

Lem   15:20
Yep.

Bryan Wolf   15:20
The parameters that you want.

Peter Wolf   15:21
The parameters of what?
The parameters of what is the source and then what's the? What are we looking for?
We're looking for certain words, right?
We're looking for AI, automation and finance or something, right?

Bryan Wolf   15:32
Mm hmm.

Lem   15:33
On the yeah, on the filter.

Peter Wolf   15:33
We have them as selection criteria.

Lem   15:36
Yeah you can.
Yeah, you can add it on the filter.
You could actually, I think.
Yeah, you could add a filter by.
Yeah, you could actually add a filter by feed, so on the Pro plan so that that would be useful. Also let's say for the MIT it's like AI in technology. Yep, that's right.

Peter Wolf   15:58
They look for finance.
We could be specifically looking for finance in that case.

Lem   16:00
Yeah, you could fill.
Yeah, you could filter it for only. It only spits out like finance. It will only, yeah.

Bryan Wolf   16:07
Well, I think I I think I just overall saw a lot more of like for the ones that Claude recommended for all the technology and AI focused ones, they're a lot more prevalent than like you know the essential treasury and like finance technology sources like I think they.

Peter Wolf   16:08
OK.

Bryan Wolf   16:27
Kind of lacking on on here with it on Internet reader.

Peter Wolf   16:29
Yeah, but this is what he's saying is we take something like MIT, which we know is already technology based, and we tell on the on the MIT one, we specifically say give me articles that have to do with finance.

Lem   16:35
Yep.
Yeah, you can filter it one.

Peter Wolf   16:41
Well, we know they're already gonna have a technology spin.
And so in that case, we look for specifically ones that haven't finance and then ones that are finance, we could say tell me ones that have an AI spin. And so the filter should be really about AI spin.

Bryan Wolf   16:54
Alright.

Peter Wolf   16:56
So we may need to do it at that.

Lem   16:57
Yep, that's right.

Peter Wolf   16:58
Level to try and get the right selection per source for our content, and that's where we really need to go.
I need to go to that level. I want to be that granular, but once we put in those parameters, it will show us all the articles that met that requirement for whatever period we show, right?

Lem   17:07
Yep.

Peter Wolf   17:15
So I'd be able to see as soon as we put in a set of parameters filters I'd be able to see all this is what it would have gotten me in the last month or the last week or right we get to set that.

Lem   17:25
Yep, Yep.

Bryan Wolf   17:26
Correct.

Peter Wolf   17:27
In the filter, right?
Like we'd say, look for the last week and this this selection criteria and then I'd be able to see, OK, this would have given me 20 and hey, they don't really fit my needs.
Let me refine my filter more or let me loosen my filter more right.
That's what you're expecting. Lemme. That's what it should do.

Lem   17:45
Yeah, that's right.
Yeah, we could filter it out also and for the removing of the news feed, you can just right click on the folder, right click and then unfollow the feed because yeah, a while ago it's just like you just like read.

Peter Wolf   17:47
OK.

Lem   18:02
The Bryan the news feed.
You just right click the feed and then click the.

Peter Wolf   18:07
Like the Kiplinger's personal newsletterra?

Lem   18:09
Yep. Unfollow feed.

Peter Wolf   18:10
You can.

Lem   18:10
So you could just unfollow it 1 by 1.
So that it will be removed.

Bryan Wolf   18:14
So these these weren't this isn't me.
I'm following it like I check it.

Peter Wolf   18:18
I don't think you're showing right now.

Lem   18:18
Yeah.

Peter Wolf   18:19
Are you displaying all of a sudden?

Lem   18:20
It was.
It was.

Bryan Wolf   18:21
No, I I, but I I notice.

Peter Wolf   18:21
I don't.
Know.
OK.

Lem   18:26
Yeah, it was.

Bryan Wolf   18:27
You're talking about how I clicked like right here.

Lem   18:29
Yeah, yeah, it you should right click.

Bryan Wolf   18:31
Yeah.

Lem   18:32
Yeah, right click and then unfollow feed.
Yep, this one.

Bryan Wolf   18:33
Yeah, yeah.

Lem   18:34
So it would be removed on the folder and then Yep. OK then.

Bryan Wolf   18:39
So what is it that I just did when I click here this is like.

Peter Wolf   18:40
Hey.

Lem   18:42
Just mark them as read.

Bryan Wolf   18:45
OK.

Lem   18:46
Yep.
And then.
Yeah, we we also need we.

Bryan Wolf   18:52
You should get rid of the Economist.

Peter Wolf   18:54
No, not be economist. That's good.

Bryan Wolf   18:56
Keep it.

Peter Wolf   18:57
Kiplinger Kiplinger's personal finance letter.

Bryan Wolf   18:59
Yeah, I have Yahoo business up.
These are good.

Peter Wolf   19:02
For right now, I think that that looks that looks good, and then we'll add the other ones that we have and then we'll look at, I want to go through and sit with you and look at the filters we have and see what articles were coming up so.
We can get the best of the best. OK. All right.

Bryan Wolf   19:18
Yes.

Peter Wolf   19:18
So that's one now on the social media, what did we do on the social media?

Lem   19:18
OK.

Peter Wolf   19:23
We had.
We had.
I know Nick came up with some and then we had a pooled list.

Lem   19:28
OK.

Peter Wolf   19:29
For Reddit and for LinkedIn.
Have we updated that?

Lem   19:32
So this is for Reddit.

Nicholas Westburg   19:34
I just, Mr. Wolf, I just sent chat. A list of some good subreddits and a bonfire.

Peter Wolf   19:40
Of Reddit, OK.
So in those, how do we those are put right into themake.com or they put in somewhere as well?

Lem   19:43
OK.
Yep, on.

Peter Wolf   19:51
So I should create here.

Lem   19:52
On, yeah, it would be put on make.com on the app if I module.

Bryan Wolf   19:58
Oh, it's on the appify section.
OK, that's OK.

Lem   20:00
Yep. So we will add this particular subreddits there and then also for the link. Yep.

Peter Wolf   20:08
Then it counts too.

Lem   20:09
Yep, the link in accounts too.
It will.
It's also on the app. If I module on the.

Bryan Wolf   20:18
That's modules 5.

Lem   20:22
Yep, module 5.
Yep, on module 5.
So it's.

Bryan Wolf   20:29
I still have to go to 'cause. I have to buy the the.
'Cause it's another API token thing.

Peter Wolf   20:39
You need to put account with a credit card on it.

Bryan Wolf   20:41
Yeah.
That's all we have to do. Everything else is.

Peter Wolf   20:48
All right.
So that I want to take care of that today too, right?

Bryan Wolf   20:54
Yeah. Well, I'm gonna do it right now.

Peter Wolf   20:56
OK.
All right. So then that, that that is the additional sources we said we're not going to do X 'cause, it's costing too much right now. And I think with the LinkedIn and the Reddit, then I'm fine.
So can we go back over to the newsletter itself?
The physical newsletter.

Lem   21:21
The newsletter I'll share my screen.

Peter Wolf   21:25
Yep.

Lem   21:27
OK.
This one.

Peter Wolf   21:31
Yep, so Scroll down a little bit please.
Let's see.
Hey, you know what?
Let me scroll back up a little bit.
I'm thinking that maybe.
Like in the one that it Baron, the Baron's banner is there.
That's because there wasn't a an image I'm assuming.

Bryan Wolf   21:48
Oh.

Lem   21:51
Yeah, this.
Yeah, this is the image coming from the link.

Bryan Wolf   21:54
Excuse me.

Lem   21:55
So yeah, it's from the.

Peter Wolf   21:55
Oh, it is.
OK. OK. What I'm I'm wondering is if to to to make it more authoritative, whether we would put the source, whether we should put the source in there in this particular case, Berens is the source and it's in the banner. But if you look at the other ones.

Lem   21:59
Yeah, this one.

Peter Wolf   22:14
It's an image of some other image and it doesn't really tell you the source right?

Lem   22:16
Yeah.

Bryan Wolf   22:17
Yeah, it's not relatable, you know.

Peter Wolf   22:19
So, well, I'm. I'm fine with it whether it's relatable or not, that's just that's the image that came with the article.

Lem   22:19
Yeah.

Peter Wolf   22:25
But but maybe we should put.
Maybe we should put the the source?

Lem   22:33
Like.

Peter Wolf   22:34
Like Business Insider.

Lem   22:38
Yeah, we could.

Peter Wolf   22:41
Because we know the source is coming from in a reader should tell us what the source was, right?

Lem   22:47
The Yeah, the source.
We actually have the source, but the like the image like the logo for that one.
You mean the logo?

Peter Wolf   22:55
Yeah, I'm. I'm not.
I don't.
I don't need the logo.
Well, I mean, if we had the logo that would be kinda cool, right?
If we, if we look at the stores and then looked up what the logo was and we put the logo on there, that would be pretty cool.
But at the very least, I would say the source name in bold.
But now that you said the logo part, you got my brain going down that path. I like that idea.

Lem   23:15
Oh.

Peter Wolf   23:16
That's a lot of extra work. I'm assuming 'cause. We'd have to look it up.

Lem   23:17
Uh.

Peter Wolf   23:19
Plus, go find the logo.
Pull the logo back to put through some image process and put it on.

Lem   23:22
Yeah, that's right.

Peter Wolf   23:24
And it might be hard when you already have the the picture as an image and then putting the logo in. There might be a little too difficult, but maybe right before the title we put the source name that we say it's barrens or Financial Times, so before you.

Lem   23:36
Oh, OK.
Yeah, yeah, like the source name.

Peter Wolf   23:40
Put the article name you actually have the source name.

Lem   23:44
Yep, Yep. We could like before the title, right?

Peter Wolf   23:49
Yeah, that right there.

Lem   23:50
So like this one Business Insider, yeah. OK then title.

Peter Wolf   23:51
That was Business Insider or something, right?
Yeah. And we would having capital.
I don't know if something to maybe make it stand out.
I don't know if it's all capital letters or I don't know a different font or whatever, but maybe something that makes it look a little bit different, or at least again it should be in the front.

Lem   24:01
OK.

Peter Wolf   24:08
It should be bold and it should be a hyphen and then the and then the article name.

Lem   24:10
Yep.

Peter Wolf   24:14
And we should also look at what happens when that article name is put in italics, because normally an article title would be put in italics.

Lem   24:15
OK.

Peter Wolf   24:21
So then if you have the source in non italics and you have the article title in italics that that. If we could see how that would look.

Lem   24:30
The the title is in italics and.

Peter Wolf   24:36
Normally, normally it would be normally a title of an article. When you cite an article, you put the article in italics, or you put the article in parentheses.
I'm just thinking about kind of academic citing of materials, right?
But if we put the the name Business Insider.

Lem   24:54
OK.

Peter Wolf   24:55
In, in non italicized and a hyphen, and then the article name.
With italics, I mean maybe that won't look good.

Lem   25:00
Oh, OK, yeah.

Peter Wolf   25:01
Maybe it will look good.
I don't know.
I'm trying to differentiate the source and the title.
Let's let's play with that.

Lem   25:07
OK.

Peter Wolf   25:08
Let's just make a note.

Lem   25:09
Yep.

Peter Wolf   25:09
Let's play with that. I would.
I would like the source name before the title and then a hyphen to go in there to.

Lem   25:20
Source name.

Peter Wolf   25:20
Yeah.

Lem   25:22
Yeah, I we could use like ChatGPT to extract the source.
And then yeah, I'll just feed like maybe a link or. Yeah, I think the link and then it will extract the particular source and then we could add it here on the title together with the.

Peter Wolf   25:40
Isn't the source being provided by in a reader along with the title and the and the and the short blurb?

Lem   25:45
Uh.
Uh.
I'm not sure if it also adds the.
Uh.
Then like the source.
But yeah, basically this is the.
So it just adds like the.
This one. This is the image and then.
This is the link.
And then yeah, we don't have.
We actually don't have the.

Peter Wolf   26:22
The source included.

Lem   26:23
The.
Yeah, this is like the title.
And then Origin title. I think this is yeah.

Peter Wolf   26:31
Yeah, but hold on.
That's not the title. Hold on.
That's not the title Yahoo top stories is not the title of the article.

Lem   26:37
Yeah, I think this.
Yeah, this would be like the source.
I'll I'll just check the.

Peter Wolf   26:44
Yeah, check another one.

Lem   26:44
It's still Yahoo.

Peter Wolf   26:45
But that that if that's the case, I'm fine with that, right?
That would be good.

Lem   26:51
Uh.
So all picking up.
It's all from Yao finance.
Let me just.
Change the.
Let's see.
It's picking up all in Yahoo Finance because it's.
1000 already.

Peter Wolf   27:09
Post content.

Lem   27:11
Yep, it has like 1000 thousand content there.
Let me just run this again.
Hmm.
Still, Yahoo.
Yeah, still getting picking up the Yahoo one.

Peter Wolf   27:28
Cool.

Lem   27:30
But yeah, I think this is.
Yeah, maybe this is like the source because I test here as origin.
Yeah, economy news.
Yep, I think this is like the origin. Yep, Yep.

Peter Wolf   27:40
Yeah, let's do that.
Take that origin and put that before the title so people can see. Oh, this is an authoritative source, and again that that gives us more gravitas.

Lem   27:44
Yeah.
Yeah. So.
Yeah.
I'll add it here on the.
Like the source.
Then Yep, we will just add a particular title.
Yep, origin title.
Oh, right, you would add here also.
Yeah. So what I will do is I will just add it here on the title. So that like the source and the title and then.

Peter Wolf   28:22
Yep.
Yep. Perfect.

Lem   28:26
Yeah, I'll just.

Peter Wolf   28:29
OK.
So that's great.

Lem   28:30
OK, OK. Yep.

Peter Wolf   28:30
Now if we go, if we go down, go back over to the article.
So we got the shrunk picture.
We got the source and article name will look at whether italics makes sense or not.
That that one.

Lem   28:42
OK.

Peter Wolf   28:43
Maybe definitely may not work out right. I want it to look sharp and it it.
Maybe we just leave the source hyphen and the name without a tux, but at least let's look at what create one that with the taux to see what that'll look like.
Then we're shortening the body content to essentially one paragraph.

Lem   28:57
OK.
OK, this one.

Peter Wolf   29:01
And Yep, and then great.
So then we Scroll down.
And what?
What is? What's the green?
What's the green part?
AI Finance news is that us putting a header that's us putting a header? That's our section header, right? OK.

Lem   29:12
Yep.
Yes. Yeah, this is like a section header, yeah.

Bryan Wolf   29:16
Yeah.

Peter Wolf   29:18
OK, good, good. All right then.
Hold on a second.
Come on. You wanna come out?
Hey, hold on one second, guys.
Come here up here.

Lem   29:33
OK.

Peter Wolf   29:35
Come on.
OK.
So then let's go down to the next section.

Lem   29:46
The social signals.

Peter Wolf   29:48
Yeah. So social signals and what do we have?
We do have some images now. Great. OK.
I like that.
OK.

Lem   30:01
Oh, I also send you guys like the e-mail yesterday.
So is it looking good also on outlook the format or?

Peter Wolf   30:11
I think yesterday I think it looked good on outlook and the only thing was when when we looked at it on the phone, when I looked at it on the phone it.
It it looked a little too small. Narrow.
But when Brian looked at it on the phone, but you were you looked at it on Outlook as well and his look, his look great. Let me just let me just look real quick again.

Bryan Wolf   30:30
Why? Why you go to?

Lem   30:33
OK.

Bryan Wolf   30:34
I was why wasn't really.

Peter Wolf   30:37
Huh.

Bryan Wolf   30:39
I wasn't narrow phone, just like text me anyway.

Peter Wolf   30:40
Hey, you're you're you're. It sounds like I'm hearing you through Peter's computer or something else.
Your your microphone's not working really.
Ryan.
If you're talking to us anyway.
So.
Newsletter.
Hold on a second. Cancel.
What was?
How was that coming through? Because.
Seeing it now.
I put them in a separate folder.
Or I give them a rule.

Bryan Wolf   31:16
Is this better?

Peter Wolf   31:18
Yeah. Loud, but yeah, much better.

Bryan Wolf   31:19
Yes, so my my text was.
Not narrow. It honestly looked great. I think it might have just been a little small to read, but I I.

Peter Wolf   31:28
Yeah.
Yeah, but yours? Yours look better than mine.
Yours at least took up the whole width of the phone.
Mine was like 3/4 width which made it too.

Bryan Wolf   31:39
Yeah.

Peter Wolf   31:40
A little too small.

Bryan Wolf   31:41
I don't know why yours was like that either.

Peter Wolf   31:44
Yeah. So what I was thinking was we would go with what you had and then we'll send it out to more people on my team and they can open it on their outlook and on their phones and we'll see how how it looks, whether it's me as the.
Anomaly or whether I'm the one who is kinda more the norm.

Lem   32:01
OK.

Bryan Wolf   32:02
Right.

Peter Wolf   32:03
So let's let's include all of us on our outlook and all of us on our Gmail and each of us can write rules to put them in separate folders.
So they don't clutter things up, but that were when we're sending the newsletter out or when you're sending the newsletter out. You're testing all that. You're copying us on all those, and on ours, we're doing the same thing, at least on the ones that are gonna come out.
Of my account.
Brian, that we're setting it up so that they get sent to all of our accounts, OK.

Bryan Wolf   32:36
OK.

Peter Wolf   32:36
You good with that, Bry? OK.

Lem   32:37
OK.

Bryan Wolf   32:38
Yeah.

Peter Wolf   32:38
I'm trying to find the oh, here it is.
What's the? What's the IKI?
G AI.
Because that's what it comes through as.

Lem   32:46
Yeah, that's the name of my BB account.

Bryan Wolf   32:49
This is, yeah.

Lem   32:50
So that's why, yeah, it's.

Peter Wolf   32:50
OK, OK, OK. OK.
So I'm looking at it now, and yeah, mine is just a little bit narrower.
Brian's took up most of his scream from left to right.
Mine's a little bit smaller.
It's totally readable, but it's not quite optimized. I I'm I got my glasses on so I can read it, but the print is definitely small, but I could live with this, especially if I'm if mine's really the anomaly and his is really more the standard that's a.
Little bit broader.
You can squeeze in on it and make it broader.
So it's and I do that.
It's it's really, it's really nice actually.
Let me let me share like we did bribe the other day, I'll share my screen or no. Can I do that on teams?
Yeah, I can do that on teams, right?
I can share my screen.
Hold on a second.
Share.

Bryan Wolf   33:45
On your phone you can do it.
Be careful to to remember to shut it off once you're done sharing it.

Peter Wolf   33:49
Yeah. Yeah, yeah, yeah, yeah.

Bryan Wolf   33:52
OK, I'm gonna share mine.
I I share mine.

Peter Wolf   33:55
Hold on. Now let me share my screen.
Got this screwed up, but thank you for reminding me that.
And please remind me again if I keep my stuff on, OK?

Bryan Wolf   34:02
Hello.

Peter Wolf   34:03
So share my screen OK gotta share screen.
Without audio I don't need that.
So then I start my broadcast.
And then I'm not sharing.
Then I go to here.
So you see my screen. You see how I got that extra space? Now if I expand it, Brian's look like that.
Which was beautiful.
Mine. It comes in like that.

Lem   34:31
OK.

Peter Wolf   34:33
It's a little bit, it's a little bit too small.
I got extra space on the side and this is this is the way Brian's looked, which was, you know, terrific.

Lem   34:41
OK.

Peter Wolf   34:42
But again I can.
I can live with this like that, but it's not optimized if it turns out that everybody when they go look at it on outlook like in their phone and it's it's this small, I would say we wanna try and adjust it somehow.
To accommodate that, but this is definitely manageable.

Lem   34:55
Yeah.

Peter Wolf   34:56
It looks very professional, it's.
This is I like it.
You know, I'm just saying, if I have my perfect world, I'd be looking for it to be wider.

Lem   35:07
Yep.

Peter Wolf   35:10
So let's not try and let's not try and address that right now.

Lem   35:11
We could.
Yeah. OK.

Peter Wolf   35:12
We'll make it as a note.
And again I want to send it out. I want to send it out to us.
And then you know what you can add.
Brian on hours or mine my account you can add Jill and Bart so that they can get it as well.

Lem   35:27
OK.

Bryan Wolf   35:28
OK.

Peter Wolf   35:29
Lem doesn't need Adam to his, so they don't get stuff.
But if we're running, then I wanna. I wanna send it to them as well.

Bryan Wolf   35:32
Yeah, yeah.

Lem   35:36
The.

Bryan Wolf   35:36
By the end of the day, like when when we, when we stop and me and Lemar and I get it working on your account, I'll add them on there.

Peter Wolf   35:36
OK.
OK.
Good. So now how do I stop sharing?
I go back to teams.
And stop presenting OK.
Alright, so then go back over if you can share again Lem.

Lem   35:59
OK.
This one next. Yeah, we could.

Peter Wolf   36:06
Yep. So so I, yeah.

Lem   36:08
Actually, I think for yeah.
For the other issue, yeah, we could like widen this like table to up to here. But yeah. And then, yeah. And then because I think it was just like.

Peter Wolf   36:15
Yeah, a little bit, yeah. Yep.
OK.

Lem   36:23
Copying the like the Super superhuman AI because they have like this kind.

Bryan Wolf   36:27
You ever hear 11?

Lem   36:28
Yeah, they have like a little.

Peter Wolf   36:29
Yeah.

Lem   36:31
Like tables.

Peter Wolf   36:32
Little bit of extra gap on the side, yeah.

Lem   36:32
But yeah, yeah.

Peter Wolf   36:34
OK.
Let's let's see what happens if we spread it out a little bit.

Lem   36:36
Umm.
Yep.

Peter Wolf   36:38
OK, so I'm good with again. I I think the social's fine.
I think those blurbs are OK. I I really need to read them and I really need to get the content we want and see what kind of blares we're getting.
And now again on these blurbs, are we using our persona to write those blurbs and or is it just a prompt?

Lem   36:50
OK.
For the AI for the yeah, for the social I this is just actually summarizing the this one.

Peter Wolf   37:00
Socials.

Lem   37:09
It's just summarizing the AI.

Peter Wolf   37:13
OK.

Lem   37:13
Because yeah, we could.
We can.
I think we could.
Yeah, because it's it's coming out from.

Peter Wolf   37:19
I mean I what?
I what I'd like.
Yeah, I I think taking that and feeding it into into.
Into again ChatGPT or Claude. And I know we've been doing ChatGPT, but I might wanna again.

Lem   37:32
OK.

Peter Wolf   37:35
I'm feel like Claud is the best writer out there, but with the persona and Claude this, I don't want it just to be a summary.

Lem   37:36
Yep.

Peter Wolf   37:43
I'm trying to make it like hey, this is talking about the hottest thing you wanna look this right?
I want it to be.
I wanted to be kind of making it spicier and not just a basic summary of the of the chat or what the topic is, but but really saying why. Why would you be interested in drilling into this and looking at what the content is, right? Why is it?

Lem   37:53
Oh yeah, yeah.
Yeah.
Yeah, I think we, yeah, we could add another node here so that this, this one is just searching and then the one Yep, that's right.

Peter Wolf   38:05
Relevant why is it appropriate?
Yep.
But similar to the articles or something, right?
Similar to what we're doing with articles.

Lem   38:16
And then it will be fed to the another, let's say, and it will create the like the specific blurb from this one like this one, yeah.

Peter Wolf   38:25
Let's do that.
And again I want to use the persona and then the the prompt then will say. In this case it's gotta be tighter.

Lem   38:27
And then.

Peter Wolf   38:32
It's not gonna be 50 words.
It's not a LinkedIn post, it's you know, our target market.
We wanna make this spicy and sizzle without being overboard, because I've done that where we were. We were using ChatGPT to change some of the terminology we uses in our methodology.
In our consulting methodology and I said, you know, make it spicy for for presentation.

Lem   38:52
OK.

Peter Wolf   38:55
Dex and it went way overboard like I was a carnival Barker yelling out, you know, get your free, you know, watch the fat lady over here and the $1,000,000 man or whatever it needs to tone down a little bit.

Lem   39:01
Yeah.

Peter Wolf   39:08
But we're trying to sell some sizzle and I would even put it that way in the in the, in the prompt to say we're trying to sell a little bit of sizzle here.

Lem   39:11
Yeah.

Peter Wolf   39:18
Give me a summary slash kind of commentary that that makes this sizzle little bit. Don't go.
Over the top, but makes the sizzle little bit so that the reader would be enticed to click on it and and drill in and understand why they would find it interesting to click on a drill in.

Lem   39:30
Yep.
Yeah. Yeah. Also for I think I would need like a copy for the persona because the persona is that I'm using as of now are just like a placeholder.

Peter Wolf   39:37
OK.
OK.

Lem   39:51
So yeah.

Peter Wolf   39:51
So Brian, you have those, you have that persona, right?
My persona is what we should be using.

Lem   39:55
So we could, yeah, we could test out the like the output.

Bryan Wolf   39:58
Yeah.

Peter Wolf   39:58
But the only the only problem, the only problem is maybe we need to look at that because in my persona, one of the things that I think it's saying it's it's kind of focused on the OR there's a section, maybe it specifically says LinkedIn where it should be.
Bring in my experiences and whatnot.

Lem   40:15
Yeah.

Peter Wolf   40:16
Maybe we need to make a genericized one that's not really about me, but it's about the target market.
So we probably need to morph that, yeah.

Lem   40:24
Yeah.
Actually, we could also do like a one shot two shot prompt on for example we will add here like a cloud right for the creation of the blurb and then we could actually put there like an samples like an example blurb that we want to get to out.

Peter Wolf   40:26
Pardon.
Yep.
OK.

Lem   40:47
So that would be like like quote UN quote Persona, but it's just like like let's say we will create like a perfect blurb for this tool and then yeah, it will copy that particular.

Peter Wolf   40:48
OK.
OK.
Got it. So then then.
Yep, Brian, make a note that what we want to do is take my persona, go to Claude and then, Yep, take it in, Claude, and then say, look, I'm trying to write a consistent little prompt that will allow me to hit this target market.

Lem   41:02
Yeah.
Yep, something like that, yeah.

Peter Wolf   41:20
I'm gonna focus on the social media.
We're gonna do.
We'll do slightly different ones, one that's.

Lem   41:24
Yeah.

Peter Wolf   41:26
Focus on the social media one that's focused, focus on the articles, but saying you know, taking this persona and understanding this target market that we're going after.
But not making it personalized to Peter Wolf and give me a prompt that's tight.
That would, you know, produce something that will will have it run through a couple examples will give.
It will feed it some social media, the same links we have and then see what it comes up with and say it will refine it.
Then we'll get a few examples we really like.
They are a little spicy, but they're not overselling.
And then we'll take those will take a prompt from that and the samples and that's what we'll feed in that way, we don't need a whole document.

Lem   42:02
Yep.
Yep, we could. Yeah, that's right.
Yeah, we could only feed that one like 2 to 3 examples.
So basically that would be like the persona of the posting style.

Peter Wolf   42:12
Yeah. Yep.

Lem   42:16
Like it's like a posting style, yeah. So.

Peter Wolf   42:17
Got it.
And then we could do it unique for the social media. We could do it unique for the articles.

Lem   42:21
Yep, that's right.
Yeah, for the articles. Yep.

Peter Wolf   42:24
Yep. Perfect. OK.
So Brian, make a note of that right then we'll we'll work on that. 'cause, I just all morning this morning I was working on updating and revising prompts for, for summarizing transcripts and stuff.

Lem   42:26
And.

Bryan Wolf   42:28
Yeah.

Peter Wolf   42:37
Some I do on another project and yeah I mean iteration and going through and getting it to refine that prompt to be exactly what you want.

Lem   42:40
OK.

Peter Wolf   42:46
And once we get that prompt in a couple examples.
Then we'll be able to feed that in and we won't need the extra document. That will simplify it from a kind of management perspective, but we'll make one unique for social, one unique for given the size and the you know the output that we want it to be.

Lem   42:52
Yep, in the shrine.
Yeah, we will just, yeah.

Peter Wolf   43:01
Under 50 characters or 50 words for one, the other is going to be substantially smaller than that.
OK, good. Next then I'd like that that again the structure looks good.

Lem   43:09
Uh.

Peter Wolf   43:13
That's all good stuff.

Lem   43:16
Next is this one.
So the AI tools and updates.

Peter Wolf   43:21
Yeah. So on this again.

Lem   43:22
Productivity.

Peter Wolf   43:24
This right now you have this coming from a feed, right?
Like a like a news feed.
Like in a reader? Or what is this?
What is the source of this?

Lem   43:30
Uh.
The source is just also ChatGPT.
So the four oh.
But yeah, we could also use perplexity here or other one.
But yeah, for the prompt here I just added like like viral ailm prompts from last two weeks.
And then I just added.

Peter Wolf   43:51
Well, that's no, that's the wrong section.
That's the wrong section.
We were talking about the one for AI tools.

Lem   43:57
Yeah, this is the actually the AI tools.

Peter Wolf   44:00
OK, you said L prompts, yeah.

Lem   44:01
Oh. Oh, this one? Yeah.
So it's yeah, this this one so.

Peter Wolf   44:05
Yeah.

Lem   44:07
It's also using GPT 40, so it's like their research endpoint.
And then yeah, it's researching also the same like 5 latest AI automation tools or updates from last two weeks.
And then yeah, we could also add here like some context like websites. Yep.

Peter Wolf   44:19
OK.
Yeah, let's work on that.
Can we?
Brian, can you screenshot this one where we're at and then we wanna go in.
I would extract that extract that right now.
Actually, Lem, can you just extract that and put it into the chat?
What you have is your prompt.

Lem   44:38
This OK.

Peter Wolf   44:39
Yeah, copy that.
Put it into the chat for the prompt, and then we'll we'll work on refining that with perplexity or something to to be much more refined to what exactly I'm looking for.

Lem   44:43
Yeah, this one.
Yeah.

Bryan Wolf   44:49
Listen, so that's that's for, that's for the the 5th, right?

Lem   44:50
Yep.

Peter Wolf   44:54
AI tools.

Lem   44:55
Yeah, this is for like, yeah.

Peter Wolf   44:55
AI tools.

Bryan Wolf   44:55
Yes. Yeah. But so that's for amplify, right?
Or it's for for which?

Lem   44:59
No, just for this is for the AI tools.

Bryan Wolf   45:00
Which one? This first ChatGPT.
Yeah. OK.

Lem   45:03
Yeah, it's researching the yeah.

Peter Wolf   45:04
But we're going to right now it's in Chachi Vitae, but I think we're probably going to go to perplexity to do that search.

Lem   45:09
Yep.

Peter Wolf   45:13
But we'll play around with it a little bit and see what we get and and we'll refine the prompt again to be more specific to what we're looking for.

Lem   45:13
Yep.

Bryan Wolf   45:13
S.

Lem   45:19
Yeah.
Then for this one, just don't change the like the final output because yeah.

Peter Wolf   45:22
OK.
We're not gonna change.
We're not gonna change anything right now.
I just want to take your input and figure out how we can massage the prompt.

Lem   45:33
OK.
Yep, yeah, yeah. But yeah, the 1st the 1st, the first part of your are changeable.

Peter Wolf   45:35
And then, yeah, we'll we'll work with you to make sure.

Lem   45:42
So like your task is to research you can.
Yeah, you can change this one.

Peter Wolf   45:47
Good. Bless you.

Lem   45:48
Yeah, the the output. Yeah, for this is because I needs also to the other node needs to extract the particular.

Bryan Wolf   45:48
Excuse me.

Lem   45:57
Yeah, but yeah.

Peter Wolf   45:57
No problem, this is a good opportunity for Brian to learn about which pieces are all of them to learn about which pieces are touchable and not touchable.

Lem   46:01
That would be.
Yeah.

Peter Wolf   46:04
What leads to what result?
But we won't make changes until we're clear on that or engage with you to make sure we're doing the right thing. OK. All right.

Lem   46:07
Yeah.
OK.
Yeah, but yeah, it's also OK if, like, you have a prompt and then I'll paste it to like cloud here to test it out. And then depending on the output, we can actually just change also the prompt here, because this is just like extraction. Yeah, it's just ext.

Peter Wolf   46:20
Yeah.

Lem   46:29
The content and then outputs it as a Jason so that we can send it to the next.
Parts, but yeah, it's you can play around with this prompt.

Peter Wolf   46:35
OK.

Lem   46:39
So no problem.

Peter Wolf   46:40
Yep. OK, good. Then go back again, please.
So now back to the newsletter.

Lem   46:45
Uh.
No. Yeah, this was.
Yeah, this was the A A tools and then your next is the prompt.

Peter Wolf   46:52
Right. And then in the AI tools, again in the AI tools in actually in the which ones do we have manual inputs?
We have an AI tools we can do manual input right and then ask it for an update.

Lem   47:04
Yeah. AA tools. Yeah, that's right.
So on AI tools we have the.
Uh, like a choice if?
We could actually add a link here, let's say coming from like a famous like automation.

Peter Wolf   47:19
Yep. Wherever got it. Yep, Yep.

Lem   47:20
Yep. And then we can just click this one.
So if we click this check mark, what will happen is the other automation will pick it up and then it will send like the same like one sentence blur.

Peter Wolf   47:24
Yep.
Now, is that going to right now when I just said about the selling, the sizzle or whatever, is that gonna go into the one that already exists or is it a different one and we have to do that in two places?

Lem   47:39
Yep.
Yeah, it's. Yeah, in two places.
So it's a different one, but if we already have it here, we could just update the this one.

Peter Wolf   47:46
OK.
Got it.

Lem   47:51
So it's actually coming from this one, so it.

Peter Wolf   47:53
Just trying to make sure I'm remembering that we have to change it in a few places depending on whether we manually input it or it's been from in a reader or from another source.

Lem   47:57
Yep.

Peter Wolf   48:03
OK. Great then.

Lem   48:03
Yep, that's right.
And.

Peter Wolf   48:06
Then the next one was the is the prompt right?

Lem   48:09
Yeah, the prompt is next one.

Peter Wolf   48:10
So I don't expect the prompt is gonna be something we're gonna search for.
But you have something searching and pulling for prompts, right?
But I'm expecting I'm gonna want something big and robust like this. So I think the manual approach is what we're gonna do. As we said, we'll, we'll go find it, will fill it in.

Lem   48:17
Yeah.
OK. Yep.
Yep.
Yeah, you can just fill it in here.
So and then yeah, just copy the like the check mark here because this is like the trigger for that one. And then just also put the title. So just title and then the.

Peter Wolf   48:30
Yep.
Yep.
Yep.
Perfect.

Lem   48:43
Complete prompt and then yeah, it will output it already here.
So also you can also adjust the sizing already.

Peter Wolf   48:47
Perfect.

Lem   48:51
I mean the formatting like the spaces.

Peter Wolf   48:53
We we talked about this now yesterday when I was saying that in Excel you could do a return, you were cutting it and putting it into another document and or some other, some other tool, and then bringing it back.

Lem   48:55
Yeah.
Yeah, I'm on like notes.
Yeah. Yep, then, Yep. Just copy.

Peter Wolf   49:04
Yeah. So either way, we'll, we'll make sure we structure it the way we want it to look in the output.

Lem   49:08
Yeah, before pasting it.
Or. Yeah, that's right.

Peter Wolf   49:11
Yep, OK.

Lem   49:12
And then yeah, that's for here.
So Yep, it's.

Peter Wolf   49:17
All right. So then we were on to our section serrala insights right now here was the thing that I was concerned about was that it wasn't.

Lem   49:18
And then.
Yeah, this one.

Peter Wolf   49:26
It didn't seem clear to me that that this is.
Pointing to our website or our blogs or our something, I feel like it's missing something to be to make that clear now. I think maybe I'm gonna change this to be more like the AI tools.

Lem   49:37
OK. Yeah.

Peter Wolf   49:47
Or the social media and that we would have a couple of items in there instead of just one.

Lem   49:49
OK.

Peter Wolf   49:53
It would be OK. Here's a few.

Lem   49:54
OK.

Peter Wolf   49:56
Here's a few of our blogs or websites and we would do the same kind of little buzz, sizzle, blurb and and we would be identifying.
You know, go to our blogs, go to our something that's gonna make it clear that that this.
Is this is our thought leadership content that that they can?
Look at to. Yeah, to get to get more insight.

Lem   50:20
Yeah.

Peter Wolf   50:21
I'm not sure exactly what I want to say, but something's gotta make that clear.
But this is links to our content, but I think if we put it in that format of what of the AI or the AI tools or the social, I think it will be clearer too, right? These are links to.

Lem   50:26
OK.
OK.
Like something like this.
Like a bullet points style, OK.

Peter Wolf   50:42
Yeah. Yep, Yep.
And that would be we'd list a few of our blogs.
Or you know website.
Informational tools, OK.

Lem   50:52
OK. Yep.

Peter Wolf   50:53
So that's what I'm expecting.
We're gonna change that into a structure like the like the socials. So we we should just move ahead with adjusting that, taking the social section, whatever we're doing with the spreadsheet and really just making that the same thing for the serrala insights.

Lem   51:03
OK.
Oh, OK. So like just.

Peter Wolf   51:13
Or maybe hold on socials. This is yeah. Yeah.

Lem   51:17
One like we we would.

Peter Wolf   51:19
Yeah, I just want it like that.
I want it like that, like we're gonna have the title is and, and then we're gonna have a.

Lem   51:25
OK.

Peter Wolf   51:26
We're gonna have a little a little sizzle blurb, and it's gonna be clear that these are gonna be links to.

Lem   51:30
OK.

Peter Wolf   51:35
To our insight.
And so maybe we'll even say links, links to links to serrala services, serrala, Treasury Services insights, right?

Lem   51:38
Oh, OK.

Peter Wolf   51:45
Something like that.

Lem   51:45
OK.
Yeah, we could actually add it like.
Because yeah, this is.

Peter Wolf   51:52
Yeah, just another page that's the same as this.
I would copy the structure exactly like you have the socials and put another tab to it.

Lem   51:58
OK.

Peter Wolf   52:00
But this is going to be where we'll put our Url's in for our content and then we'll have the same thing where it can come up with a little blurb.

Lem   52:04
Yep, yeah.

Peter Wolf   52:07
We click the button to tell it to come up with a summary, and again we'll already have a prompt that says make it sizzle a little bit, but it's going to be like the social, it's going to be just a couple type sentences.

Lem   52:10
OK.
OK.
Yep, yeah, same as this one.

Peter Wolf   52:19
And and then we'll change the titling a bit. Yep.
Yep, Yep. That's what I'm thinking of.

Lem   52:23
OK. Yeah.

Peter Wolf   52:24
Let let's just put in more than one.
I think it's clear that it's linking to something.

Lem   52:27
Yeah, that's right. Yeah.

Peter Wolf   52:30
Yeah. And we don't take up as much space. Go ahead.

Lem   52:30
Then we could.
The banner.
Also, we could add it as like a something inside here so that it would be.

Peter Wolf   52:38
Yeah, we could.
Yep, I could get.
I get my marketing piece.
They were supposed to create something. They haven't delivered it yet, but that's typical for them.

Lem   52:41
Yeah.

Peter Wolf   52:45
But yeah, we could.

Lem   52:46
So.

Peter Wolf   52:46
We could do something in the banner that's going to make it clear that this is a a link to our to our blogs and our thought leadership content, right?

Lem   52:51
Yeah. Yeah, that's right.
Yep, Yep.
So that it would be more. Yeah, it would like create be a grab like attention grabbing.

Peter Wolf   53:02
Grab attention.
Yep, I love it.
That's great.
So I'll I'll work with Nancy on that to make sure she's putting something together. Terrific. Then let's definitely move forward with restructuring that and that way we just it's not a feed thing.

Lem   53:05
Yep. And then.
And.
OK.

Peter Wolf   53:15
We're just gonna plug in the URL and the title and then it's gonna go create that blurb when we click the button, so we could predefine these 1020 of them in advance and know what we wanna include when we're starting to focus on a certain aspect in.

Lem   53:22
Yep, that's right.
Yep.

Peter Wolf   53:30
Certain newsletter.

Lem   53:31
Yep, that's right.

Peter Wolf   53:32
Right. OK, good.
Then the last section is the is the upcoming events.

Lem   53:35
OK.

Peter Wolf   53:39
I want one more section.
It's gonna be upcoming.

Lem   53:41
The upcoming events, OK.

Peter Wolf   53:42
Yeah, upcoming events.
Yeah.

Lem   53:48
Tell me events.

Peter Wolf   53:49
And it's good.
Typically I'm gonna say serral Treasury services upcoming events.
But it might be.
It might be broader serrala like just to give visibility when we have like we had our kind of global.
Client.
Summit was 300 people there.
I would want to give visibility to that even though it wasn't specifically SCS Treasury.
It's like showing our.
International reach and all that kind of stuff, right? So.
But I think we would.
I think this is another one where I probably need to come up with a banner from from our social media or from our marketing team.

Lem   54:27
OK.
So the formatting would be something like this like.

Peter Wolf   54:33
That.
Yeah, exactly like that.

Lem   54:36
Section OK, upcoming events and then like the title, OK like a summary.

Peter Wolf   54:39
Yeah, I'm thinking.
I'm thinking the same.
I think again the same thing could be as the social media, because I would want to have more than one upcoming event, so might as well be each one.

Lem   54:49
Oh yeah. Yep.

Peter Wolf   54:52
We structure this exactly like the social media and exactly like the the insights. That way I can put a few of them right and I could choose.

Lem   54:54
Yep. Like yeah, sometimes like this.
OK. Yep.

Peter Wolf   54:59
Is it only one upcoming event?
Is it 2 upcoming events?
Whatever. But I could in I could include them and then it would be.

Lem   55:03
Yep.

Peter Wolf   55:07
The same kind of thing would probably be a title.
We do a spicy blurb and there'll be a a link to click through and that would normally go to a landing page that would tell them what the dates are and stuff like that. Although maybe we want to put the date in.

Lem   55:11
Yeah, like this.
Yep.

Peter Wolf   55:20
It will figure that out when we get to it.
Maybe it's gonna be the title, then the date and then the blurb to to put some urgency on it, right?
Did the date kinda draws you in and say, oh, it's coming up. I gotta go look at what this is and sign up or something like that, right?

Lem   55:30
OK.

Peter Wolf   55:36
And and again, we'll put a we'll come up with a header there.
Upcoming events and then maybe some commentary that says here Click to.
Well, I'm trying not to sweat to death on the deck.
You were in there though.
I didn't want to bother you, sorry.
Yeah. So let's structure the same for now. Those two sections structure on the same as the social media and then we'll plug in the URLs.

Lem   55:58
OK.
And then, yeah, I'll, I'll structure it on and then I'll also, yeah, like add it here on the section that you can like check the, yeah, create the summary for so.

Peter Wolf   56:09
Yep, absolutely.
Exactly the same. Each one of these is gonna have their own section. We can manage. Perfect.

Lem   56:16
Yep, that's right.

Peter Wolf   56:18
Yep. And I would like the same kind of thing a little bit.

Lem   56:19
So upcoming events.

Peter Wolf   56:21
A little bit of we said we'll come up with the with the blurb or the the prompt, but I want a little bit of of like like you have the green check marks, but I don't know if we're using green check marks in every section that might look.
Kind of redundant, but I like how you spiced it up with a little something different.

Lem   56:36
Yeah. So.

Peter Wolf   56:39
I don't know what we can do, but let's think about something there that's also some kind of visual along with that, right?

Lem   56:47
Yeah. Like a different, yeah.

Peter Wolf   56:48
Again, I don't.
I don't know if we can do it differently or not, but right now I like that that's unique. Each one of those is a little bit unique. Again, if we have two more sections like that, we might not be able to do unique, but I'd like to try.
And come up with something that had a visual that that made it more than just the name, but we can figure that out when we get to.

Lem   57:08
OK.

Peter Wolf   57:09
I mean for now you can make it where it's just the check Marks and then we can figure out is there something else we can put there that would look attractive? OK.

Lem   57:14
OK.
Yeah, for actually for this one, I've added it to the prompt that it will just use like a random business emoji.

Peter Wolf   57:20
Create some. OK. Yeah. OK.

Lem   57:22
Yeah, but for this one, it's hard coded as check mark because for those updates. But yeah, I'll I'll play around with that, yeah.

Peter Wolf   57:25
OK, OK.
So then let's try let. Yeah. Awesome, perfect, great.

Lem   57:33
For the yeah, the visual source. OK.

Peter Wolf   57:33
I.
I think that's that's what I'm looking to do.
And then we'll figure out, I think from the conclusion after we get all this stuff together, we'll figure out we're gonna work on the prompt for the conclusion stuff. But and maybe there isn't really a conclusion, I don't know.

Lem   57:43
Yeah, the conclusion.

Peter Wolf   57:48
We'll we'll see what it is, but maybe that's a call to action.

Lem   57:49
OK.

Peter Wolf   57:52
But I think that the previous two were kind of call to action already, right?

Lem   57:54
Yep.

Peter Wolf   57:56
Here's the upcoming event that's a call to action.
Come join us, participate, and then the other one is the blogs.
Come read what we have.
That's a call to action as well.
So I don't know if we're gonna do a conclusion call to action that might make it too salesy.

Lem   58:05
OK.
Mm hmm.

Peter Wolf   58:11
But we'll see.
But I'm I'm loving this. I really feel like every day we're making great progress. And again I I'm feeling like next week we're gonna get our first one out.

Lem   58:14
OK.

Peter Wolf   58:21
So if you guys can can kind of work on these things, any open topics and issues?

Lem   58:21
Yep.

Peter Wolf   58:27
If you can work with them on, you know updating to to to get the added.
Accounts for.
For the social media, if there's need to to put in or work on getting in the the accounts on the inner and refining the search criteria, whatever. If we could play around with that a little bit, any other open issues or topics or challenges you're having, Brian, if.
You need to open up those additional services or you know, subscriptions.
Go ahead and do that.

Bryan Wolf   59:01
It just amplify I think. And then if we can do a vest and so are they like.

Peter Wolf   59:02
And.

Bryan Wolf   59:07
What's for and I reader on LinkedIn.
But I don't think so.
I think I need to upgrade our and I read your account maybe, but I don't know.

Peter Wolf   59:15
I'm fine with you doing that right again.
I wanted to be.
I wanted to work and if that's only $10 a month, I mean, I know I keep saying that and I'm gonna have to finally pull all this stuff together to figure out how much I'm spending per month.
I'm I'm sure with all the the ChatGPT and the perplexity and the claw, then the team accounts and the make and all that kind of stuff. I'm sure it's costing me quite a bit.
And right now I don't have visibility 'cause, I'm just kinda going ahead and doing it, but I need to pull that information together.
So, Brian, definitely anything you're opening an account for.
You need to give me.
You need to give me that because I track stuff on another list where all my access to my account, so I need to make sure I'm not losing side of these.

Bryan Wolf   59:52
Yeah, yeah, yeah.
I would just open one.
I think I'm gonna have to open the appify one for API tokens for the fifth section on the flow, but that's it. That's probably not.

Peter Wolf   1:00:00
OK.
OK. OK, good.
All right then.
Anything else from your guys side?

Lem   1:00:13
OK, I'll also.

Bryan Wolf   1:00:13
I think you handled everything I needed to talk about.

Peter Wolf Jr   1:00:14
Yeah.

Bryan Wolf   1:00:18
Lamborghini.

Lem   1:00:19
This. Yeah, I'll add this particular because I saw here on the chat, there's like like the link in ones.

Peter Wolf   1:00:19
Yes.

Bryan Wolf   1:00:27
All the stuff.
Is this what your?
Is this you the the screen I'm watching under this is you. Yeah. OK.

Lem   1:00:32
Yeah.

Peter Wolf   1:00:32
Alright guys, I'm gonna drop off. You guys can work on this.

Bryan Wolf   1:00:34
All right.
Sounds good. Sounds good too.

Peter Wolf   1:00:35
I appreciate it.
I'll talk to you.

Lem   1:00:36
Hey, Peter.

Peter Wolf   1:00:36
See you.

Lem   1:00:38
So.

Nicholas Westburg   1:00:40
Hey guys I need a drop too.

Lem   1:00:40
Yeah.
OK, Nick talking soon.

Bryan Wolf   1:00:43
Happy birthday, Nick. Happy birthday, Nick.

Nicholas Westburg   1:00:44
Thanks brother.
Thank you. Thank you.
See you, Tom.

Lem   1:00:48
See you.
I just.
Yeah, I'll copy this all so that.
I'll incorporate can incorporate this one on the.
Yeah. So do do have.
A question on.
The like.

Bryan Wolf   1:01:13
So I have questions on the appify like so I'm on the website right now.

Lem   1:01:16
Yeah, because.

Bryan Wolf   1:01:18
I'm on here.
Do I create an actor actors?

Lem   1:01:22
Yeah. You. You. Yeah, that's right.

Bryan Wolf   1:01:22
Does that what I'm building?

Lem   1:01:25
You would need.
To like to trigger the save there for the particular actor. So let me just.

Bryan Wolf   1:01:33
You see me or no, so am I.

Lem   1:01:35
Yeah.

Bryan Wolf   1:01:36
Am I browsing or buying one cause for?
The API connection.

Lem   1:01:41
Uh.
Yeah, the API connection.
You would need to get the API.
Oh, I think.

Bryan Wolf   1:01:53
This is where I'm at.
Can you sing or is this on the wrong thing? This is the console.

Lem   1:01:56
Yeah.
Yeah, this is the. Yep, that's right.
And then you couldn't go to the make and connect your apartment.

Bryan Wolf   1:02:07
I don't.
I don't. OK. OK, OK.
So let's see this.
But so it says create a connection connection type.
I don't have an API to connect, so I want to buy the tokens first or.

Lem   1:02:14
The.
You can.

Bryan Wolf   1:02:18
You see, I need.
I need to buy them.

Lem   1:02:22
Let me just.
How did they?

Bryan Wolf   1:02:24
I could probably Google it honestly and see now though.

Lem   1:02:28
I think I added.

Bryan Wolf   1:02:30
'Cause, I'm saying do I develop a new actor here or is this API right here?

Lem   1:02:31
It.
We could.
Yeah, I think we could connect it with the without the API API token.
So can you go back to the?
Make.com. Yep. And then.

Bryan Wolf   1:02:49
Oh, you want to go to?
I don't have.
I don't have this token though.
See what I'm saying?

Lem   1:02:52
Yeah, I you can.

Bryan Wolf   1:02:53
I don't have it.

Lem   1:02:55
Choose the other one so the connection type the. Yeah, that's that one.

Bryan Wolf   1:02:59
This. Oh, this works OK.

Lem   1:03:01
Yeah. So and then yeah, just click save.
Then it will.

Bryan Wolf   1:03:05
I don't.
So I don't.
I don't need tokens in the future or to run it.

Lem   1:03:11
You would need the credit.
So there's like a $5 free credit here. As you can see on lower left side, so.

Bryan Wolf   1:03:18
No where where where should like billing.

Lem   1:03:21
Yeah, that one.
So the $5 usage.
So these are the credit on the lower left side.

Bryan Wolf   1:03:28
Where? Hold on. Hold on, let.

Lem   1:03:28
$0.00.
Yeah, that one. Yeah. So this.

Bryan Wolf   1:03:33
So how do I update this to to get it more than five though?

Lem   1:03:37
You could change on.
The.
Pricing.
So there.

Bryan Wolf   1:03:48
What about here *** showcase?

Lem   1:03:48
I know not.
Not on the API. So just in the.
Yeah, pricing or I mean like I think, yeah, on subscription I think.
Yeah. And then you can just upgrade.

Bryan Wolf   1:04:03
Yeah. Yeah, yeah, yeah. OK. OK.

Lem   1:04:04
OK.

Bryan Wolf   1:04:04
OK, OK, cool. So current subscription this will give me.

Lem   1:04:08
Yep, so.
Yeah, the starter plan is, yeah, 39.

Bryan Wolf   1:04:17
So concurrent runs.
So this means I can run it 32 times or it's charging me?
It's not charging me one full token every time charging like 12:45, right?

Lem   1:04:27
Yeah, it would depend on the.

Bryan Wolf   1:04:29
Size of the the what we're transporting, right?

Lem   1:04:32
Yeah, but it would because it's like a marketplace for different scrapers.
So depending on the scraper that we will use. So I've chosen like the cheaper ones and then it also has like.
Per .02 dollars per run like per like 1000 results.
So I it's pretty cheap, but yeah.

Bryan Wolf   1:04:52
But so for me, if I want to get this running today like my goal for the like, whenever we get off is for me to have this completely done so that I get it in my own e-mail and then that way I can kind of start to mess.

Lem   1:05:01
OK.

Bryan Wolf   1:05:05
Around with HTML formatting it and then I also wanna are you gonna so on your end are you gonna do?

Lem   1:05:07
Yep.

Bryan Wolf   1:05:13
Add the LinkedIn stuff that they put in the chat and the Reddit stuff they put in the chat are gonna do that.
That's what you're gonna do or what?

Lem   1:05:20
Yeah, I would. But you could also do it on your.

Bryan Wolf   1:05:24
Because I want to try and know myself.
And yeah, yeah, yeah.

Lem   1:05:26
Yeah. On your end, you can actually see it when we already connected the AP5, the request body, Yep.

Bryan Wolf   1:05:32
Right here. OK.
So I'm saying I'm saying do I need to upgrade my plan right now in order to do this or it's gonna 'cause? I have the five bucks. I I'm good for like the day. OK all right.

Lem   1:05:37
Nope. Yeah, no.
Yeah, that's right. Yeah, yeah.
So yeah, we could.
You could use that one for now.
So yeah, $5 would go a long way already.
Because if we're not like scraping the like like thousands of, yeah, thousands of results. So.

Bryan Wolf   1:05:53
It's doing its own stuff, yeah.
Mm hmm.

Lem   1:05:59
Especially also for like testing so.

Bryan Wolf   1:06:02
Yeah. And then only thing else I need to do is.

Lem   1:06:03
Yeah.

Bryan Wolf   1:06:06
I need to change the webhost, right?
I need because I have them.

Lem   1:06:10
Yeah, the web books. Yep.

Bryan Wolf   1:06:11
I just need to go save them, right?
OK.
So let's just.

Lem   1:06:14
Yeah. So.

Bryan Wolf   1:06:16
Do.
Other than that, I got all the triggers here.
I got.
Oh ****.

Lem   1:06:21
OK.

Bryan Wolf   1:06:21
Oh God, I just deleted.

Lem   1:06:23
Yeah, I think we would need to add the actor on your.

Bryan Wolf   1:06:26
'Cause I'm good on these.
On Amplify, So what is the actor itself? Is that the?

Lem   1:06:31
File. Let me just. Yeah, I'll.
Yeah, I'll try to copy the name because.

Bryan Wolf   1:06:41
Thanks.

Lem   1:06:44
Yeah. So this is the.
Yeah, this is for the one for.
The LinkedIn one. And then yeah, in the chat. And then the other one is.

Bryan Wolf   1:06:53
Where was in the chat.
So what?
Oh oh, the I have to search.
These are the ones that are already existing.
You're saying like if you go to the store and you search it.

Lem   1:07:06
Yep, that's right.
So we we are, yeah on the search.

Bryan Wolf   1:07:08
Like search active.
Browse actors and storytelling right here.

Lem   1:07:15
Yeah, go to store. And then yeah, just search for.

Bryan Wolf   1:07:18
LinkedIn Post search scraper number Cookie $2.00 per month one.
So these are the ones I'm gonna have to buy.
You're saying?

Lem   1:07:26
Yeah, it's not.
It's like a renting only. So we're, as you can see there, we could get. Yeah. $2.00 per 1000 results.

Bryan Wolf   1:07:30
OK. It's like by month.

Lem   1:07:35
So depending on the like the scraper so others have like a $10 per month subscription.
So others have.
I've only chosen the paper results, so these are like papers.

Bryan Wolf   1:07:44
Yeah.
So, are all of these actors.
They're all scrapers like or there's different.

Lem   1:07:50
Yeah, the actors are.
Yes, they're they are different scrapers for like different different use cases like we have here for LinkedIn, Reddit.

Bryan Wolf   1:07:58
OK.

Lem   1:08:01
I also have for Instagram so different.

Bryan Wolf   1:08:03
Yeah. OK, great.

Lem   1:08:06
So and then, yeah, so this already good because it's already you don't need to do anything here because we are actually sending like a Jason body on on the make site.

Bryan Wolf   1:08:07
So so so I'm looking here so.
Watch it, OK?
Alrighty, we are doing this.

Lem   1:08:20
Yeah. So we we just, you just need to like save it to your actors. And then the other one also is.

Bryan Wolf   1:08:21
We're already doing this, you're saying?
So how do I start or create or?

Lem   1:08:32
On the make side, so it it's actually on there on the let me just copy this other one so so this one is direct.

Bryan Wolf   1:08:39
It's like one of right here right here.

Lem   1:08:42
Yeah, it's there on the if you click that one, yeah, you can see. Yeah, that's right.

Bryan Wolf   1:08:43
Run Lincoln scraper. So this is the code that's right here. That's OK. OK.
Wow. So they just give that to you for free?

Lem   1:08:49
Yeah, that's one. Yeah, that's right.
Yeah. Yep.

Bryan Wolf   1:08:54
It's great.

Lem   1:08:54
Pardon.

Bryan Wolf   1:08:55
So this this right here is what's right here, right? Yeah.

Lem   1:08:59
Yeah. Yeah, basically.

Bryan Wolf   1:09:00
They just get it to you for free though.
It's just free.
Free Jason to scrape off LinkedIn. Right or no?

Lem   1:09:08
Uh.

Bryan Wolf   1:09:09
'Cause like, isn't this code it like so this code right here is allowing it so that app if I can scrape the information off of LinkedIn, right?

Lem   1:09:09
Free.
OK.
No, basically we're passing the like the request.
So actually appify is the one that is creeping.
This particular Jason body.
So these are just like parameters as you can see like the author URLs and then the Max Post 50.
So these are the parameters there on the scraping scripting actor. If you go back to the apfi.

Bryan Wolf   1:09:42
Mm hmm.

Lem   1:09:45
So it's basically what we're doing is we're just like.
Starting the actor.
From me we could actually start it from here manually, but yeah, yeah.

Bryan Wolf   1:09:55
Right. Yeah, but OK.
So I get what you're saying now. I get what you're saying.
But so this is still free though, right?
Which is so I do I since this is a. Yeah, it's just I I don't even need to follow.

Lem   1:10:03
Yeah, it's. Yeah, it's free per event.

Bryan Wolf   1:10:09
It's just connected to my account automatically because we're sending it from me.

Lem   1:10:10
Yep.

Bryan Wolf   1:10:12
OK, interesting. All right, cool. Cool, cool, cool. OK.

Lem   1:10:13
Yep, that's right.

Bryan Wolf   1:10:17
So I think I have every other everything else filled out in every one of these other.

Lem   1:10:23
Uh.

Bryan Wolf   1:10:23
Just save this.
What else do I need to do love?

Lem   1:10:27
The Reddit one also.
So run I think.
Yeah, this one is the Reddit scraper light and.
Yep. Ready to scraper light.
Through docs.
Yeah, this one so from trudox.
Yeah, that one.
And then just save it.

Bryan Wolf   1:10:52
It says start and just figure out. Yeah, I aborted it.

Lem   1:10:55
Yeah you could.
Just abort.
Yeah, you could just abort that one.
Yeah, so that's now.

Bryan Wolf   1:10:59
But so I did.
Well, why didn't I need to save the the LinkedIn one just because it didn't even give me an option.

Lem   1:11:07
Oh, you didn't.
Yeah, you need to save it.
Also, you could actually yeah, you need to save the LinkedIn one.
I thought you already saved, yeah.

Bryan Wolf   1:11:12
OK. I was like, oh, God 'cause. It just said run.
It doesn't even let me see.

Lem   1:11:19
Yeah, there there's on the like.
Lower at the end of the Nope. On the bottom side, just actually save their save button.
Yeah, this one.

Bryan Wolf   1:11:32
See, not that it's only apply access runs from.

Lem   1:11:38
You could just start it if.
Yeah. And then they just abort.
Click abort.
Yeah, I think this would already.
So.
Can you go back to the actors?
So let's check it.
If it yeah, it's already saved.

Bryan Wolf   1:12:01
OK.
It's here.

Lem   1:12:02
Yep, that's that's good.

Bryan Wolf   1:12:03
OK. OK, OK. OK, cool.

Lem   1:12:05
Then yeah, so for the parameters there, we're actually we're just sending it from here.
Make so that that's good.

Bryan Wolf   1:12:10
OK.

Lem   1:12:12
Then Yep, for the web hook.
Now.

Bryan Wolf   1:12:17
For the Google Sheets, you're saying for the extension.

Lem   1:12:19
Yeah, for the Google Sheets so.

Bryan Wolf   1:12:20
Oh, so why, why listen?
Why can't I do?
Extension here.
It's just 'cause. It's a shared or something.

Lem   1:12:31
Yeah, I think this is my. My. Yeah, this is mine.
So I think you have only view access, so you would need to duplicate this.

Bryan Wolf   1:12:36
Right.
So I I made this one.

Lem   1:12:43
OK.
So this is a duplicate right?

Bryan Wolf   1:12:46
Yeah, but.

Lem   1:12:50
Uh.

Bryan Wolf   1:12:50
Oh, yeah, yeah, yeah, yeah, yeah.

Lem   1:12:51
I think this is yours.
Yeah, I think this is yours. Yep.

Bryan Wolf   1:12:54
This is mine.
No, this is yeah, yeah, yes.
OK, OK, cool. So extension appscript.

Lem   1:12:57
Yeah. And then.
Yeah, apps script.
Yep. So yeah, I can see I've added here the like. Yeah, web link from this.

Bryan Wolf   1:13:10
Yes. Hey. So let me just.

Lem   1:13:13
So that it would be easier to.
So.

Bryan Wolf   1:13:25
Yes, push test e-mail here.

Lem   1:13:26
Yeah, I I think I should.
Yeah, add like the module, right? Yeah, I should.

Bryan Wolf   1:13:31
Yeah. So this one, this first one is 3, right?
Yes, push test.

Lem   1:13:36
Yeah, that one's. Yeah, that's right.

Bryan Wolf   1:13:36
Yes, send test.
Oh no, this this is E.
So this one's got to be the first one, right?

Lem   1:13:40
Yeah, I think, yeah, that's.
The E is no, the C is for the send test e-mail. So push testing.

Bryan Wolf   1:13:50
Right, so I I. But So what about this one says yes, send final e-mail. OK send testing SO3C.

Lem   1:13:53
Yeah, the three.

Bryan Wolf   1:13:57
Alright, yeah, this is this is unhappy.

Lem   1:13:58
3C up.

Bryan Wolf   1:14:01
I'm doing so copy.

Lem   1:14:02
Yeah.

Bryan Wolf   1:14:03
I'll just go for so then I put this here, right.

Lem   1:14:03
Yeah.
Yep.
OK. And then?
The other one.
So I yeah, I should have added there the like the module.
I mean the number of the 4th automation or something.

Bryan Wolf   1:14:31
Yeah, that would have been great.

Lem   1:14:32
Yeah, that would be easier.
So. So this one is, yeah, final e-mail.

Bryan Wolf   1:14:34
Yes, send final e-mail so.

Lem   1:14:37
So the number four, yeah, this is number 4.
Yeah.
Yep. And then.
Yeah, for the this one.
So social media.

Bryan Wolf   1:15:01
Oh, ****. Hold on. I'm sorry.
Social media posts is that.

Lem   1:15:13
Social media is the.

Bryan Wolf   1:15:17
So we already did.
We did three and four.

Lem   1:15:19
Yeah. The number two, number two.

Bryan Wolf   1:15:21
Yeah, you're right.

Lem   1:15:22
Yeah, so it's #2.
Yep, this one.
So this was the hook for the.
OK.

Bryan Wolf   1:15:34
Now it's going 3-4.
Two, let me write this down real quick.

Lem   1:15:39
Yeah, 342. And then this one is for the AI tools.
So the other one.

Bryan Wolf   1:15:48
Sorry, I was writing down.
OK.
6.

Lem   1:15:58
Yep, the 6th is.

Bryan Wolf   1:16:00
No, it's seven. It's 7.

Lem   1:16:03
Ei.

Bryan Wolf   1:16:04
Length, yeah.
See the actuals here at 7 trigger for Maya tools.

Lem   1:16:08
Yeah, the seven.
Yeah, 8267.
So the 6th is.
Alright, I I don't.
I didn't add here yet the.

Bryan Wolf   1:16:21
What on this one?

Lem   1:16:21
The Yeah, the STS blog post.

Bryan Wolf   1:16:22
What do you what you gonna. Well, this is yours.
This is yours from last night.
This is the one you sent me yesterday.

Lem   1:16:27
Alright. Yeah, yeah.
So this is.

Bryan Wolf   1:16:30
So it's not 'cause. You didn't send us.
You didn't send us anything this morning, right?

Lem   1:16:34
A.
Yep, not so this is.

Bryan Wolf   1:16:36
Yeah, yeah, yeah.
OK.
So then the last one is 6.

Lem   1:16:42
Yeah, the last one.

Bryan Wolf   1:16:44
Webhub link from pompt of the day is that this one.

Lem   1:16:49
Yeah, I know.
This is a different one so.

Bryan Wolf   1:16:52
So that's my last web book I have.

Lem   1:16:53
The.
Yeah. The one from the for the.
Uh huh.

Bryan Wolf   1:17:04
So we did. We did.

Lem   1:17:05
1/2.
2323.
Yeah.

Bryan Wolf   1:17:20
It's got to be 6 because it's the last moment I haven't used.

Lem   1:17:24
Yeah, yeah.

Bryan Wolf   1:17:27
I know.
About going from prompt of the day here.

Lem   1:17:31
Let me just check my.

Bryan Wolf   1:17:33
Yeah. Yeah, yeah, yeah, let's be sure.

Lem   1:17:35
Profile day.
Alright, so the prompt of the day is.
E.
Yeah, this is prompt of the day.

Bryan Wolf   1:17:49
OK6.

Lem   1:17:50
I didn't.
Maybe I didn't send you yet the.

Bryan Wolf   1:17:55
Now, do you want to send it right now?
Is it for six or is it for so like what you're about to send me? Am I gonna have to redo all these?
I don't really care but.

Lem   1:18:05
I don't know. Just just.
Eat for the prompt of the day.
Oh, right.
We don't.

Bryan Wolf   1:18:11
Just.

Lem   1:18:11
We we actually don't need this one because like Peter.

Bryan Wolf   1:18:13
Here.
We don't need this.
This one right here. Are you sure?

Lem   1:18:17
Yeah, it would be.
No, we could change this.
We could change this one to the STS blog post so.
Just change.
Put the because the STS blog post is also on E so that's same.
Yeah. So you could add this one.
Yep this.
Yep, that one.
On there.
And then at the bottom.
Yeah. At the bottom, on no scroll on the yeah, this.

Bryan Wolf   1:18:51
Save.

Lem   1:18:55
Can you change the prompt the sheet name there at the bottom so as you can see, it's the prompt of the day sheet on the column.

Bryan Wolf   1:19:04
Hold on. Hold on.

Lem   1:19:05
Yeah, this one, yeah.

Bryan Wolf   1:19:06
Mm hmm.

Lem   1:19:06
So just just change the sheet name here to the STS blog post.
So it should be also.
The formatting should be the same also like the.
Sts blog posts, so it should be.
Yeah, it should be have this.
It should have the space.

Bryan Wolf   1:19:31
Where? Where? So? What am I competent from?

Lem   1:19:31
In the.

Bryan Wolf   1:19:33
I'm competent from make.

Lem   1:19:33
Oh Nope on the spreadsheet.
So this is.

Bryan Wolf   1:19:38
No, no, I know. It's I'm saying on the spreadsheet STS blog what it was, OK.

Lem   1:19:41
Yeah, that one.
The name of the sheet, so the name of the sheet is STS blog posts.

Bryan Wolf   1:19:43
So where is it?

Lem   1:19:48
So Yep.
And then just change also the because it's a letter copy. Yeah, capital P.

Bryan Wolf   1:19:53
Capital P.

Lem   1:19:55
Yep.
And then, Yep, so this would also already work because this is also in the.
Column wait, let me just.
So.
S s blog post.
Yes, it should be on G.
G.
Column G.
So.
And then.
123-4567.
7:00 so I change also the range column start to seven.
On the else.
On the 1st on 50 number line 55 S else if sheet name s s blog post then range Column Start is 7.
Yep, OK.

Bryan Wolf   1:21:00
Are you sure you're looking at 'cause? We should be looking at mine, right?
Instead of yours.

Lem   1:21:06
Yeah, we have the same because you duplicated it and I didn't edited it.
Still the sheet.
So it's the same.

Bryan Wolf   1:21:14
OK.

Lem   1:21:15
Yeah. And then.
Yeah. So I we don't.
I didn't build the automation also for the prompt of the day because yeah, it was.

Bryan Wolf   1:21:25
One second.

Lem   1:21:26
Yeah.
I think I let me just double check here.
Sts blog post.
Yeah, this is.
This is my post OK.
Yep, and now.
Yeah. Could I actually now test this one?

Bryan Wolf   1:22:18
So hold on.
Do I?
I save this somewhere, right? Right here. Save.

Lem   1:22:20
Oh yeah, save it first and then add trigger because this is like a new.
On the left side, the clock like. Yeah, this one. And then add the trigger on the on add the trigger and then also on the select event type.

Bryan Wolf   1:22:39
Oh.

Lem   1:22:41
This one and then Yep, on the the 4th one select event type it also change it to onedit.

Bryan Wolf   1:22:41
So what do I change in here?

Lem   1:22:50
And then Yep, click save.
Then this would.
Pop up the authorization.

Bryan Wolf   1:23:01
Uh huh.

Lem   1:23:03
Pop up blocker? Yep. So there's.

Bryan Wolf   1:23:18
I'll see you in a block of this. One might be.
It's not even on though.

Lem   1:23:25
Yeah, it's not on. That's odd.
Ah, OK.
Then advanced OK, go to my project.
Then allow.
I think the ship's already good.
And then.
Yeah. Now we could.
You you should turn the all the automations first also.
So that.
But.

Bryan Wolf   1:23:58
Like this you're saying?
Should I delete these and like you know, I'm just gonna leave it. You're saying?

Lem   1:24:04
Yeah, you could actually do this one because yeah, this is actually on my like the Google Docs here are on my account.
And then.

Bryan Wolf   1:24:17
But you're shining on make.

Lem   1:24:18
Yeah. Also for it. Yeah. Also on make we need to like.

Bryan Wolf   1:24:24
Put them along.

Lem   1:24:24
Turn all of it on.
But if you turn this on, what will happen is the.
The number one and also #5 will trigger every day, so it will get.
It will like scrape the Internet and also for yeah, you could just turn. Just turn off. Just turn on the ones that have.

Bryan Wolf   1:24:42
I think OK. OK.
Do you know how you keep going?
I'm just gonna run it just to test it and then and then.

Lem   1:24:52
Yeah, just you can just turn on the ones with the web hook so that like 2-3 four and also 6/7.

Bryan Wolf   1:24:55
Mm hmm.
I don't need to do these ones.

Lem   1:25:01
Yeah. So we could just manually manually trigger the number one and #5 because it's it.
It's actually the trigger for that is running every day.
Every eight ami.
Think 9:00 AM. Yeah. So, yeah. So we we. Yeah, we could start.

Bryan Wolf   1:25:15
So now should I run this manually this and then manually this?

Lem   1:25:19
Yep, that's right.
So now we could start in #1 and then.
Oh, you already mapped this.
Or yeah, so it I think it's still not mapped on your.
Umm.

Bryan Wolf   1:25:37
Oh, this is.

Lem   1:25:40
Yeah, that that's persona.
So you need to.

Bryan Wolf   1:25:42
That is just, that's what.
I think that's.

Lem   1:25:48
Yeah, this one is, I think mine the best persona.
So yeah, we would need to.

Bryan Wolf   1:25:52
****. OK.
I gotta change a couple of them.
There's a couple in there.

Lem   1:25:57
OK.

Bryan Wolf   1:26:02
I don't know where his persona is.
So I think it's an automation.
Yes, OK.

Lem   1:26:37
Umm.
And then.
Windows.
OK and.
The other is to train.

Bryan Wolf   1:28:09
That's it.
Yeah, it is. OK.
All right, let's try it.

Lem   1:28:20
OK.
Run it once.
Umm.

Bryan Wolf   1:28:30
Emails. How do I know whose emails are gonna do it to the sheets, right? Yeah.

Lem   1:28:35
Yeah, the the brevo.
You mean the brevo?

Bryan Wolf   1:28:41
Yeah, you updated it or I gotta do it.

Lem   1:28:44
Yeah, you got.
You gotta change it though the.

Bryan Wolf   1:28:46
Hey, I got shoes on there. I think I'm on there and Peter's on there, but not for outlook.
I have to look.
We'll look after we're done running this.

Lem   1:28:53
OK.
Uh, stop. If. Yeah, I think there's already a duplicate for this one.
Can you?
Yeah, I think.
Oh, right.
It doesn't have a summary. Does this account already have the?
The pro plan.
Or.

Bryan Wolf   1:29:23
No, for honor reader.

Lem   1:29:25
Yeah, for because.

Bryan Wolf   1:29:28
No.

Lem   1:29:28
It still on free trial, so if it's on free trial, can you check if it's on free trial? Because yeah.

Bryan Wolf   1:29:31
It is I got update on.
It is.
It is.
It's on free trial.

Lem   1:29:38
If.

Bryan Wolf   1:29:40
****.

Lem   1:29:41
Umm.
Oh, it's still on free.
Try right?
Or it did it already expired?

Bryan Wolf   1:29:46
Yeah, it's on.
It's on free trial.
It's on par trial.
I can.

Lem   1:29:50
Oh, OK.

Bryan Wolf   1:29:50
I can purchase it right now.

Lem   1:29:50
OK.
Yeah, because for the free.

Bryan Wolf   1:29:53
I'm not gonna have to 'cause it ran out.

Lem   1:29:56
The free plan actually doesn't have, as you can see, there's no like summaries.

Bryan Wolf   1:30:01
Yeah, it's OK.
I just pause.
To see.

Lem   1:30:17
But yeah, I think we could actually use the already on the.
Spreadsheet. There are already articles also there on the spreadsheet, just to test it out.

Bryan Wolf   1:30:31
Mm hmm.
OK.
I just took the carlitation.
Can you see my screen?
You can't see my screen.

Lem   1:31:04
Nope, only the.
Yeah, only the this, yeah, like desktop.

Bryan Wolf   1:31:08
Yes.
Yeah.
One second.

Lem   1:32:09
Select the.
12345.

Bryan Wolf   1:32:57
I'm back.
I'm back. I'm back.
So we just so we got, OK, let's start, OK.

Lem   1:33:01
OK.

Bryan Wolf   1:33:03
So I just.
I got a pro plan alright.

Lem   1:33:05
OK.

Bryan Wolf   1:33:05
I got a pro plan now.

Lem   1:33:08
Yep, yeah, this should already.

Bryan Wolf   1:33:09
You know, run again.
Should I run again now or no?

Lem   1:33:14
Yeah, I think it.
That's, yeah. Let's try it because I think it would depend.
Yeah. Now it got four weeks, but I think this already has like the duplicate the three.

Bryan Wolf   1:33:28
Yeah.

Lem   1:33:30
Oh, didn't pass through.
Just.

Bryan Wolf   1:33:41
There's three here.

Lem   1:33:43
Can you check the?

Bryan Wolf   1:33:45
There's three.

Lem   1:33:46
Yeah, the. Yeah, but there's like a duplicate. So it's actually already on the can you check the newsletter?

Bryan Wolf   1:33:51
OK.

Lem   1:33:58
Yeah, this one.
And then filter the articles.
Yeah, so I think.

Bryan Wolf   1:34:03
OK.
Let's just.

Lem   1:34:06
Yeah, you could delete.
This one and also.

Bryan Wolf   1:34:22
It's got it.

Lem   1:34:33
Alright. Do you already have?
Can you go back to the inore reader?
So I think it's not updating properly and then go back to the feeds.
Yep, and then click the finance and economics folder title and then yeah, click the finance economics again title.
Yep, and then create a rule.
So.
Yeah, I think we and then just add there Mark, as Mark as red.
OK. And then?
A new article oh.
Why can't you?
Can you click the check mark?

Bryan Wolf   1:35:19
Hmm.

Lem   1:35:22
Why?
Yeah, I think the.
Still not taking effect the like the Pro plan, but it's OK.

Bryan Wolf   1:35:38
Pro plan.

Lem   1:35:39
We we could just unread this all.
So I mean, read it.

Bryan Wolf   1:35:42
Alright, let me just see if I can.

Lem   1:35:43
Just manually read it all.

Bryan Wolf   1:35:50
Is saying in in a reader are you saying on?

Lem   1:35:51
Yeah, you could. These two checkmarks. Yeah, on in, reader.
There's two checkmarks in there.
Yeah, just click that.
All so that it would mark all as read and then it will update new new articles there and then.
We could actually.
Delete like some of the articles, because on the yeah here or maybe.

Bryan Wolf   1:36:20
On hand, let's just delete all.
Just get rid of all.

Lem   1:36:25
Yeah. OK.

Bryan Wolf   1:36:25
Just just.

Lem   1:36:26
And then.

Bryan Wolf   1:36:28
I'm deleting all these too.

Lem   1:36:31
OK.

Bryan Wolf   1:36:35
So why does it have the screen?
I did that myself, didn't I?

Lem   1:36:37
Oh, OK. Can you undo first or because I think this is like the freeze?
The freeze.
Yep. OK. Oops. OK and.

Bryan Wolf   1:36:49
I got her to filter articles, AI tools.

Lem   1:36:50
Then.

Bryan Wolf   1:36:52
Keep this out as you're saying.

Lem   1:36:52
Yeah.
Yeah you could.
It's OK because I think.

Bryan Wolf   1:36:59
Keep it.

Lem   1:37:01
Yeah, we, we we would have.

Bryan Wolf   1:37:01
What about status?
Should I change this passwords?

Lem   1:37:04
I it's OK just put process there, we will just.
We will have new article.

Bryan Wolf   1:37:12
Information.

Lem   1:37:12
I mean new data here whenever we trigger that one.
So yeah, I think we could go back to in reader and then change the.

Bryan Wolf   1:37:16
OK.

Lem   1:37:22
Yep. And then you can go back to the make and trigger it again.
So let's see if.
Actually.
Yes, it's only picking.
Up four.
No, it's already aggregated.

Bryan Wolf   1:37:37
Or share.

Lem   1:37:38
Yeah, it's four articles that has the summary.
So but yeah, this is actually 5th, I think 50 or 30.
But yeah it should.
Huh, that's odd.
Can you check the filter?
Yeah, the filter on the.
And then can you?
No. Yeah.

Bryan Wolf   1:38:09
Are you only?

Lem   1:38:13
Oh, right, I think this is still.
Can you check the Google sheet?
No. The on the make site the Google Google sheet node.
Yeah, Google.

Bryan Wolf   1:38:26
Just.

Lem   1:38:26
Yeah, this one.
Oh yeah, I think this is still on my newsletter.
Is this the your spreadsheet?

Bryan Wolf   1:38:33
No, that's no, it's not. ****.

Lem   1:38:35
Yeah, it's a revised.
I think that's why it's.

Bryan Wolf   1:38:38
*** **** it, love I suck.

Lem   1:38:41
It's OK.

Bryan Wolf   1:38:43
Hold on. I I have to.

Lem   1:38:43
Yeah, I think we need to.
Yeah, we need to remap it to the.
Revised 1.

Bryan Wolf   1:38:50
Yes, I gotta do that with all the other ones, so.

Lem   1:38:53
Yeah.
Oh, right. Because AI think it triggered this.

Bryan Wolf   1:38:56
Oh God. OK.

Lem   1:38:58
Also a A while ago.
That's why it's.
Yeah, we would need to do this also on all the like the Google Sheets.

Bryan Wolf   1:39:07
All the other ones, yeah.

Lem   1:39:09
Yeah, all the Google Sheets so.

Bryan Wolf   1:39:09
OK.
That's alright, we're here.
I'm here all day anyways, you know.

Lem   1:39:14
Yeah. What we could actually do is I will put my Google sheet into like a private and then change your spreadsheet.

Bryan Wolf   1:39:17
I think some of these, yeah.
Yeah.

Lem   1:39:27
But you already change eyes, OK?

Bryan Wolf   1:39:29
That's alright.
I'm just gonna change the mods on my video, if you don't mind waiting for me.

Lem   1:39:31
Yep.
Yeah, it's OK.

Bryan Wolf   1:39:41
See now does it matter if I go into automation first?
Like some of these, like so. See how this is in the automation folder.

Lem   1:39:49
Automation.
Yep.

Bryan Wolf   1:39:57
Does it matter that when I click this one it doesn't even have that?
It just it just goes straight to the ID.
Because it's still saying spreadsheet.

Lem   1:40:06
Yeah, it's it's OK.

Bryan Wolf   1:40:07
It's just not. It's OK, OK.

Lem   1:40:08
Yep, it's OK because these are like different.
This is searchros and the other one is.
Add ru. That's why I test like.

Bryan Wolf   1:40:24
Oh.

Lem   1:41:04
Switch views.
Cortana.
Or.
Home 6.
Should be 8.
Tree.
450 that's right, only 5.
No.
Antoch.
Turn that thing down.
Just the whole other.
1.
Content.

Bryan Wolf   1:46:19
Yeah, I think I'm good though.

Lem   1:46:22
OK.
Well, it's not OK. Try to.
Once.
OK.
This should update the filtered articles OK.
And then.
Yep, now we could.

Bryan Wolf   1:47:12
Gotta manually trigger this fifth one.

Lem   1:47:15
The Yeah, that's already good.
And then yeah, the number 5 also, yeah. 'cause, this would scrape and also.

Bryan Wolf   1:47:18
Just just one.

Lem   1:47:25
Yeah, run once.
OK, not's creeping.
OK.
And then Yep, if you go to the spreadsheet.
Google Sheets.
Yeah. Now we would have the new AI tools. OK on the each section.
Now we have yeah 5 here.
Then just.
Yeah, copy the.

Bryan Wolf   1:49:29
So now my clicking news.

Lem   1:49:29
And.
Then the yeah, including newsletter.
So you would click the one.
Yeah, the one and then also for the filtered articles.
Here. Yeah, just click. Also the three.
Then prompt of the day.
You could choose like.
Let's say.

Bryan Wolf   1:49:56
What'll have on from today?
That's all right.
Let's just do this one.

Lem   1:49:59
Yep, OK, that one.
And.
Then s s bugpost.
Oh, this one is.
Yeah, not included there.
So just choose, let's say the third one and then delete the process.
Yeah, that one.
Oh, just the yeah click the including new slot.
Yeah. OK.
And then for the social media posts, yeah, this is already that's OK, because this is once all.

Bryan Wolf   1:50:34
OK.

Lem   1:50:35
Yeah, just click the like the. Yeah, the these are the new ones. As you can see, it's.
Yeah, just click 5K and then.
Yep. So then you could trigger now the.
Nope, the other one.
Yep, you could trigger now here just yeah, click yes.
And then we should.
Yeah, we should be able to.
See it on the make side. Can you go?
On the.
Umm.
#3.
So it's on #3.
Yep.
It didn't run.
Yeah, it's not picking up that particular.

Bryan Wolf   1:51:41
Wordbook.

Lem   1:51:42
Yep, web book. That's odd.
So.
Yeah. Can you check the app script? So this is.
Umm.
What is that again H?

Bryan Wolf   1:51:59
Stop.

Lem   1:52:00
Yeah.

Bryan Wolf   1:52:06
So let's see.
Three years for NFC.

Lem   1:52:14
I so it's for social media.
Post it's on.
G.
Yeah, I think we've put it on the wrong one.

Bryan Wolf   1:52:22
Yeah.
The message was up, man.
OK.
So let's see this.

Lem   1:52:29
It should be on the the web hook. There should be on G Yep.

Bryan Wolf   1:52:33
Gee, so where do I put you?

Lem   1:52:41
And then.
That one yf.
Sh.
Wait, there's also another web book there here on below, so yeah.

Bryan Wolf   1:52:58
This one again.
No, no, I'm just keeping this 'cause this was.

Lem   1:53:03
Oh, OK, OK, OK.

Bryan Wolf   1:53:03
I mean, I can get rid of it now.
It it was originally this one, but we can delete it now.
I just had it there, OK.

Lem   1:53:10
OK.

Bryan Wolf   1:53:12
Oh, it just highlights both.

Lem   1:53:14
Nope. I just. It's OK.

Bryan Wolf   1:53:14
See how it's.

Lem   1:53:16
Can you do it?
Just, yeah.
And then I think the C the IT should be the other one. Yep.

Bryan Wolf   1:53:22
The one I just deleted.
The one I just did.

Lem   1:53:24
So that yeah, that's the one. So Yep. OK.
C should be new standard graphs.
Yep, new Slotter graphs you see? Yeah.
OK. And then can you run it once?

Bryan Wolf   1:53:41
On this one.

Lem   1:53:41
I think have you saved the?

Bryan Wolf   1:53:44
I just say that I just saved it.

Lem   1:53:46
We had a garage, OK, K and then.

Bryan Wolf   1:53:49
Sure, sure.

Lem   1:53:50
Yeah, let's go back to the Yep here and then run it once.
I think it's all right. We we need to like trigger it again.

Bryan Wolf   1:54:00
On the whole thing, it's the whole thing.

Lem   1:54:01
Yeah, the new the spreadsheet.
No, just cancel and then.
Uh.
Yeah, this is already the format content, just tested.
Can you trigger again the spreadsheet?
Go back to the Google sheet.
And then Yep, click yes again so.
Just yeah, click yes and then yeah, it should.

Bryan Wolf   1:54:32
So you wrote a process.

Lem   1:54:33
Can you? Yeah, remove the process.
Oh, right.
Why this did it?

Bryan Wolf   1:54:40
I'm sorry.

Lem   1:54:41
Can you go back?
Uh.
Yeah. So I think this is also.
Can you go back to the spreadsheet?
And then.
Can you go back to newsletter drafts?
Yep, yeah.
So we actually have this already the.
Yeah, I think that's the new one.

Bryan Wolf   1:55:23
So we process it.

Lem   1:55:23
Yeah, I think this is the newest.
Yeah. So it already processed it and then?
Yeah, click yes and then.

Bryan Wolf   1:55:34
I gotta see.
So how does it so it it knows what emails to send it to through my bravo, right?

Lem   1:55:42
Yeah, the.

Bryan Wolf   1:55:42
But I so did the bravo.
So like how do I know?
Is sending e-mail to me right?
It's all my brevo account, right?

Lem   1:55:55
Yeah, I actu.
Actually, I think we've, we've.
Yeah, we've swapped the wrong hooks there.
So I was also, yeah, it it also it already worked properly.
It's just. Yeah, yeah, I think we.

Bryan Wolf   1:56:10
Please switch off. OK, OK.
So we're put G back in C&C back in G.

Lem   1:56:16
Yeah, yeah.
So I yeah, it already worked a while ago.
Then just copy it. OK yeah.
Put back it and.
Step.
Just click save.
OK.
Yeah. So it, yeah, it was already good.
And then yeah, for this one, yeah.

Bryan Wolf   1:56:38
Hello.
Yeah, I run it again.

Lem   1:56:43
Yeah. We could go back to the brevo.
Because it it will send actually.
To just on your e-mail and then what you can do is you could send the e-mail campaign to your.

Bryan Wolf   1:57:02
Oh, I got an e-mail.
I got an e-mail.
I got an e-mail answer from you.
Guys.
And that's for me to run today.
Oh, let me just.

Lem   1:57:17
Yeah, yeah.

Bryan Wolf   1:57:17
This is Peter's is it has a Peters.
We're gonna buy.
I have to buy a plan for this too, don't I?

Lem   1:57:28
For the we could actually use the like the free plan.
But yeah, there are some.
Actually it's, yeah.
It just sends from like the Brevo Brevo sender. As you can see on the like test emails.
So that's the if you.

Bryan Wolf   1:57:49
So I don't have any logs here.

Lem   1:57:53
Is this?
Is this yours or?
No, we didn't trigger it yet, I think so.
That's why, yeah.

Bryan Wolf   1:58:02
OK.

Lem   1:58:04
And then.

Bryan Wolf   1:58:05
So where do I go automations?

Lem   1:58:09
No. Just go back to the make and then.
Can you?
Yeah. Can you go click the back button? The upper left arrow and then check the history?

Bryan Wolf   1:58:28
Oh, what changes did I make?
I don't think I've made any changes.

Lem   1:58:35
Can you check?
Let's just check it a one day one.
So the this is your brevo Peter or.
Yeah, the sender.
You should also change the sender to my to your.
Yeah, so this should send on Yep to this particular e-mail.
And then.
Also at the bottom I think yeah, I should in the reply to.
Then also can you check there's also another one there on the sender.
Yep, so this should send the e-mail to this e-mail and then yeah.

Bryan Wolf   1:59:24
From Peter.

Lem   1:59:27
For the create the e-mail, can you check.
Let's check out the sender.
I yeah, it's just can you Scroll down a bit?
Let's just check if there's. Yeah, it's already good.
Yeah. So this will send the test e-mail to this one to this e-mail and then to send it to other emails. You could just go to the brevo and then send the campaign, but let's try this. Let's.

Bryan Wolf   1:59:51
Like in here I also hold on tell me how I.

Lem   1:59:53
Yeah. And they're here.
Yeah, in the campaigns it will appear here.

Bryan Wolf   1:59:55
And then I do.
I'm sorry. Say again.

Lem   1:59:59
Yeah, let's trigger it first so that it will.
The campaign will appear so.
OK.
Right. Can you trigger again the the?

Bryan Wolf   2:00:16
First one.

Lem   2:00:19
Yeah, the this one. So just.
Yeah. And then click yes again.
So this should.
Yeah. Then should actually, should it?
This is this already turned on right?
Yeah. Can you go back and then check the history so.
Wait.
Umm save changes?
Yeah, it's airing out, can you?

Bryan Wolf   2:00:45
This is the one we just.

Lem   2:00:49
Alright, yeah.
So it's not sending the web correctly I think.
Oh it right there.

Bryan Wolf   2:01:00
I think we.

Lem   2:01:00
It's already on the queue, yeah.

Bryan Wolf   2:01:01
I think we got those.

Lem   2:01:03
I yeah, it's already on queue.
Yeah, yeah.

Bryan Wolf   2:01:07
Does that mean?

Lem   2:01:11
The because it error out IA while ago, I think it turned off and then just. Can you go back just go back again.

Bryan Wolf   2:01:15
Mm hmm.

Lem   2:01:19
Yeah, go back and then.
Turn it off and then turn it on again.
It's the number.
Yeah, it actually turn it.
Can you turn it on again the?
Yes. New trigger, yes. Oh.
New trigger.
Yes. Yeah. This, the other ones are already good.
Yeah, it's already good.
So the number two and number, yeah, the number 2 and #3.

Bryan Wolf   2:01:52
What about the gentleman sitting?

Lem   2:01:56
And then process.
This is OK process.
All data OK then Yep that should.
Already work and then can you?
Let's check out the new trigger.
Yes, the #3.
#3.
Oh, it's still error outside.
Oh no.
Yeah, it's. Let's check it out.
Yeah. So it can't get the content.

Bryan Wolf   2:02:35
Remember how we switched it from?
I don't say.
I've been talking about that, isn't that?
Doctor. And did you?

Lem   2:02:51
I know it's a document ID, so it's. Can you go back there and then check the the bubble on the Google sheet?

Bryan Wolf   2:02:53
Not the call.

Lem   2:02:58
So I think it's not yet on make.com.

Bryan Wolf   2:03:00
Where on here?

Lem   2:03:04
And then, yeah, here, OK.
So instead of draft create.
Google doc clean.
Spreadsheet idea so you could actually get this.
All right.
Can you click this again the the spreadsheet? I think it's still on. Yeah, maybe.

Bryan Wolf   2:03:26
Mapped up to you.

Lem   2:03:29
Can you recheck check it on?
The diagram so.
Yeah, because it's.
Oh no, it's not, but.
I'll find a superstest.
It's all good.
So why does it?
Why can't it get that?
Oh, that's odd.
Can you go back again to the search data database?
No, that just here on the. Yeah, just here on the Google sheet.
I'll just check the filter below so finalize and push this e-mail well to yes and then test e-mail status not equal to sent.
So that's good.
And then at the top, it's already on revised.
So yeah, that's good.
Yeah, so this should get that, yes, there.
That that. I'm not sure why.
OK. Can can we run once again?
Try just try to run it once.
OK, use existing data.
Yeah it can.
Oh, can you click this get content?
Uh.
Nothing and then document ID.
Oh, right.
Can can we go back to the?
Spreadsheet. I think you deleted a while ago the the No on the. Yeah the document ID so.
It was already gone here.
You accidentally deleted the document Ida while ago.

Bryan Wolf   2:05:33
Alright, where is it?

Lem   2:05:35
Yeah. So.
How can we?

Bryan Wolf   2:05:38
Do I just press back a bunch?

Lem   2:05:38
Get it?
You could. Yeah, we could actually process it again using the. Oh, let let me just. Oh, you could.
Go back to make can we?
Can we go back to make and just search for the?
Can you create a new note?
A new module, just new module and then yeah, Google Docs.
Click the Google Docs and then search, just search.
Search for.
Create a document.
Yeah, I think get content of document.
Oh, no, I think we would need to.
Well, we we could just.
Yeah, get content of the document.
Can we try it and then can you put, put the? Oh, yeah, we would need the document ID. So just delete this one and then we go to Google Drive.
Oh right. The Google Drive is not working here, right?
Is it working?

Bryan Wolf   2:06:53
No, it's for mine. I think for Peter.
It'll work for Peter.

Lem   2:06:55
OK.

Bryan Wolf   2:06:55
It'll work for me now.

Lem   2:06:55
So let's try it. Google Drive, open Google Drive node.
And then Yep.
And then there's actually like a search.
Yeah, search for files, folders and then we could actually.
Search it by.
Yeah, just an account.

Bryan Wolf   2:07:20
Oh, God, come on.

Lem   2:07:21
Alright, so the the document is.
On you.

Bryan Wolf   2:07:28
Ah.
Huh.
Doc documents what?

Lem   2:07:34
Uh.
I think it's OK.

Bryan Wolf   2:07:37
This is a pure stuff.

Lem   2:07:39
Yep.

Bryan Wolf   2:07:39
Tell me it works.
Hopefully it works.
It worked. Wow.

Lem   2:07:42
The.

Bryan Wolf   2:07:44
Alright so.

Lem   2:07:44
Yeah, but the document is actually on your account, right?
Can you go back to get content?

Bryan Wolf   2:07:49
No.

Lem   2:07:50
This one.
Yeah, I think this.
There on get content OK can you click that one get content?
There. Yeah. This one, yeah.
Oh, it's on. Oh, OK.
So it's on his little account. OK, that's that's good.
So on Google Drive.

Bryan Wolf   2:08:10
I don't know if this is in a folder though, but like on.

Lem   2:08:10
Let's.
Just.

Bryan Wolf   2:08:16
His actual drive? I don't think it's.

Lem   2:08:19
Yeah, I think it would be.

Bryan Wolf   2:08:22
I'll put it.

Lem   2:08:30
Uh, yeah, just a folder then just.

Bryan Wolf   2:08:41
Oh, God. OK, it's gotta load.

Lem   2:08:42
Or retrieve.

Bryan Wolf   2:08:45
It's gotta load.

Lem   2:08:46
Yeah, it's OK.

Bryan Wolf   2:08:46
It's not on there yet.

Lem   2:08:47
Let let's just process it again.

Bryan Wolf   2:08:52
Just say this.

Lem   2:08:53
Just go put the trigger back and then delete the Google Drive.
And then we will go back again to the number 2.

Bryan Wolf   2:09:04
Spreadsheet idea.

Lem   2:09:07
Because we don't have the document ID for this one.
So it can't get that particular.

Bryan Wolf   2:09:11
Did you want me to run this or no you do.

Lem   2:09:13
I know. Just. No, no.

Bryan Wolf   2:09:15
Go to two.

Lem   2:09:15
Yeah, on the yeah.
So go back and then the number.
Yeah, this one.
So we we would trigger to get first go back to the spreadsheets and then click delete the process because it won't process this one.
Yeah, because there are already process.
So just delete the process.
Here also.
Yep, then so that we'll just process it again.
Then this also.
Then yeah, this also.
Then.
Yeah, that's good. So.
Now we could trigger this run once.
Then use existing data OK.
Yeah. So now we would create again the new document and then it will process again all of the data on the spreadsheet.
So basically what happened a while ago is like you accidentally deleted the document ID, so it should.

Bryan Wolf   2:10:17
Oh God.

Lem   2:10:17
Yeah, it it. It should cross reference that document ID and then get the the text content and then it will.

Bryan Wolf   2:10:24
Yeah.

Lem   2:10:25
Yeah, it feeds.
It will feed to ChatGPT to format it to HTML.
So that's why it's a while ago it was. But yeah, I think this already.

Bryan Wolf   2:10:36
Finished. Yeah. Now it is.

Lem   2:10:37
OK.
Yeah. So now it's good.
Now we could go back to the spreadsheet.

Bryan Wolf   2:10:41
Ury. Oh OK.

Lem   2:10:43
Yep. And then, yeah, this one just click. Yes. So that's already good newsletter drafts.

Bryan Wolf   2:10:44
Nice.

Lem   2:10:49
Then just click yes.
Yep, OK.
So yeah, this the other automation I think is already.
Can you go back?
Yeah, to make.com and then.

Bryan Wolf   2:11:01
3.

Lem   2:11:01
The scenarios, yeah.
Is it alright?
I think it's already turned on or oh, it erred out.
So you just turn it on.
Yeah, turn it on again then.
Process all data. So Yep, this should.
Send.
The.
Oh.
Yes, scenarios activated.
Can you go back to the?
No. So make can you go back to make and then, yeah, just let's check the history.

Bryan Wolf   2:11:44
Oh, sorry.

Lem   2:11:44
Scenarios activated so.
Yeah, it's still not.
Ah, let's uh trigger it manually if, uh, so that we could, uh, can you go back in and then run once, OK, use existing data.
Yep, OK.
So it's searching the database.
That's odd.
It's pretty.
I think Google is glitching out.
It's taking a long time.

Bryan Wolf   2:12:38
The sheets, yeah.

Lem   2:12:41
Yeah, it should be.
Yeah, but I think we could like stop this one, then retry again.
Because.
Yeah, I think it's lagging something.
Then run it once again.
Yeah, run it once.
OK, use existing data.
So.
There's something wrong in the.
Did we click yes on the Google sheet right?
Oh yeah, we already clicked the yes, OK.
That's good.
So huh, I think there's some on Google Sheets side.
Now let's just wait for it. Yep.

Bryan Wolf   2:13:44
I just let the rock out.
Yes.

Lem   2:14:07
Yeah, I think this would time out.

Bryan Wolf   2:14:10
Do you think so?
Yeah, it did, did.

Lem   2:14:13
Operation fail.
Yeah, it's been exhausted.
Oh, chekota.
Yeah. So I think we already hit the APR rate limit.

Bryan Wolf   2:14:26
For which? For what?

Lem   2:14:27
For Google, Google Sheets.

Bryan Wolf   2:14:31
Oh wow.

Lem   2:14:32
That's.
Shacks.

Bryan Wolf   2:14:36
Oh God. So how do I can you buy one?

Lem   2:14:38
So what we yeah, what we can do here is just to trigger this one is can you unlink the Google sheet?
OK. And then I'll link that one and then the document I yeah, link.
This.
I no, no need, just unlink it.
Yep, and then put the the trigger to get content.
Yeah. And then can you go back to the just copy the the document ID of the newsletter graphs?
Yeah, we we would, yeah.

Bryan Wolf   2:15:15
Where? What? Where do I do that?
Where is the document ID.

Lem   2:15:17
On newsletter drafts on spreadsheet. So you go back to the spreadsheet and then use letter drafts.
On the last spreadsheet, yeah, on the left sheet. This document ID? Nope. Here, just here on the. Yeah, that one.
Yep, this one.
So just copy this.

Bryan Wolf   2:15:36
Yeah, delete this one.

Lem   2:15:38
Yeah, yeah.
And then paste it here.
Yeah. So we're yeah. Backspace. Yeah, just backspace.

Bryan Wolf   2:15:43
Shall I go backspace that? Get rid of that?

Lem   2:15:46
And then Yep.
OK, then click save.
So now we could.
It's just getting that particular document. Yeah, and then run.

Bryan Wolf   2:15:53
Shannara.

Lem   2:15:54
Yeah, run it once.
I just unlinked the Google sheet also because yeah this.
Yeah, that one.
So, OK. And then yeah, we could now trigger this one.
Just to test out like the formatting and then if it sends the e-mail to because I think, yeah, we hit the. Not sure why we hit the rate limit maybe.

Bryan Wolf   2:16:22
Let's try and do it too much, should I?

Lem   2:16:24
Peter maybe also use the other automations a while ago, or oh right, the two automations are already turned on right the.

Bryan Wolf   2:16:32
Yeah.

Lem   2:16:33
The one that's getting articles every day.

Bryan Wolf   2:16:36
I believe so.

Lem   2:16:38
Yeah. So that's one restriction also for Google Sheets because of course because it's free, there's some like APR rate limits.

Bryan Wolf   2:16:47
Drawbacks.

Lem   2:16:48
Yeah, then drawbacks.
But yeah, so this should send.
The e-mail to yeah, his e-mail.
And then now we could see after this one we could now see the, yeah, the the e-mail campaign on your brevo on this brevo.

Bryan Wolf   2:17:02
To the hard copy.

Lem   2:17:07
And then you could just send it to the your list like your.

Bryan Wolf   2:17:11
Can I actually sew?

Lem   2:17:11
For emailing.

Bryan Wolf   2:17:12
I don't sew all my I don't have.
I don't know my contacts on here.
I don't think Peter has.
He doesn't have any.
He just he is himself.

Lem   2:17:19
Yeah, you can add.

Bryan Wolf   2:17:20
That's it.
I I got me.

Lem   2:17:22
Yeah, you can add the contacts there.

Bryan Wolf   2:17:25
Wait, so 'cause I I wanna get this e-mail too.

Lem   2:17:25
And then you.

Bryan Wolf   2:17:28
I wanted to get this e-mail from me.

Lem   2:17:28
Yep. OK, then yeah, you can just add your e-mail there.
And.
Yeah, enter your e-mail and then.
Just create the contact.
Oops.

Bryan Wolf   2:17:54
OK.

Lem   2:17:57
Yep. And then go to the list.
So we we need to add your.
Yeah.
To the list the lists.
Yeah, this one then.
Go to number your first list and then add yeah.
And then.
I know actually you could go back to your contacts.
So just go back to contacts.
No, on just on click contacts again contacts.
On the left side, left hand side.
Yep. And then.
Oh, it's already on the members. Can you click the X on this like member of a list?
So just click X. OK so that you and then click your name.
Yeah. And then you could add the list here on the.
On the lists. Yeah, this one.
So yeah, I do a list then add it to the your first list. Or let's say you could just add your first there and then just save changes.
So when you add the contact, you should already add them to the list because we were.
We are gonna send the e-mail to that list when we create a campaign.
We we could only send.
The e-mail, if they they are in the particular list like let's say.
You can just rename the list like active and active contacts or let's say serrala.
Yeah, like that then.
Yeah, I think the it's already done.
Let's check the make makes scenario.
Can you go back to the make.com and then, Yep, refresh this can you refresh bevel?
No, no.
Just cancel 1st and then refresh bravo.
Yeah. And then go back to campaigns.

Bryan Wolf   2:20:00
I know this takes a while on this side.

Lem   2:20:04
Alright.

Bryan Wolf   2:20:06
She'll have a ****.

Lem   2:20:08
Can we?
Can you go back to the?
Make.com. And let's check if this bravo is.
Can you check the create the campaign e-mail campaign?
Yeah, it's already on Peter senior and yeah, it actually created the campaign and send the test e-mail.

Bryan Wolf   2:20:37
I think that might have been for my account my berro account.

Lem   2:20:37
Not sure.

Bryan Wolf   2:20:42
I think this is this though, so if you want to, wouldn't it be in transactions?
Your logs.

Lem   2:20:50
Yeah, should be on the. Yeah, I think it's.

Bryan Wolf   2:20:51
Right.

Lem   2:20:55
Can you?
Yeah. Can you open your?
Maybe it's actually connected in your account.
Yeah, because it's not appearing.

Bryan Wolf   2:21:02
I think I think it maybe.

Lem   2:21:04
Yeah.
But if you check the e-mail of like the P9, I think it will. Oh no.
I think it won't.
Not sure if it would send there if.
Can you go to campaigns?
Let's just check it on.
Huh.
Can you go to com?
Yeah, I think it's. Oh, this is still on 19.
1906.
Yes. So this is still on June 19. So this is a different one.
Yeah.
So.

Bryan Wolf   2:22:07
Maybe I didn't write the right API.
Or I connected my account.
Like.

Lem   2:22:20
We check again if.
Let's say create.
Create an e-mail campaign.
And it's double check it.
There and then.
Add can you?
Yeah, let's add a credential.
Maybe yeah.
Maybe it's can you try to get?
His.
On the on upper right side.

Bryan Wolf   2:22:47
Where do I find that at?

Lem   2:22:51
Yeah, this one then.
STM SMTP and API.
Yep, so the API key is here.

Bryan Wolf   2:23:02
Oh, OK.

Lem   2:23:02
Yeah. So I think it's still not.
It still doesn't have the API key.
So yeah, that's why I think it.
Yeah, it didn't send.
It didn't send the e-mail because the e-mail there is.
It's connected, I think, to your bravo and then the e-mail is different. So that's why.

Bryan Wolf   2:23:24
Yeah, his yeah.
So it's just really Jack.

Lem   2:23:27
Yeah, that's why it's having some problems.

Bryan Wolf   2:23:28
So it's just.
It is.

Lem   2:23:54
Yep. So yeah, I think this would already work. Then also the other one.
Yeah, Peter.
Yep. And then we could trigger it again run once.
And then Yep, we should now get that particular.
This letter.
Yeah, I think.
My the prompt. I think there's some like differences on the formatting also because I've tweaked it a little bit today.

Bryan Wolf   2:24:32
OK.

Lem   2:24:32
But yeah, it it's just we could just we can just play around with this for now.

Bryan Wolf   2:24:34
That's fine.

Lem   2:24:39
For the formatting.
OK.

Bryan Wolf   2:24:54
Hmm.

Lem   2:24:56
I send e-mail.
All this at your SMTP account is not yet activated.
It's not asking.
Yeah, I think this is on the can you go back to Peter's?
Yeah, but I think it already created.
It's just, yeah, OK.
Then.
Can.
Can you go back to SMTP?
Can you click this SMTP on? I think this is the main issue SM on the SMTP end API, the one the other.
Yeah, this one.
I think it's OK.
Can you go go to the?
The e-mail campaigns.
On the left side.
Yeah, campaigns.
Yes, it's already created.
Just can send an e-mail that's odd.
Send your campaign 1st A10 ticket your sender domain or use another sender with an authenticated domain.
Oh yeah, so I think this is.

Bryan Wolf   2:26:21
Can't you?
We can't. So this is a private e-mail I think.

Lem   2:26:23
Oh Yep. Yep, because this is on serrala. So it needs. Yep.

Bryan Wolf   2:26:28
Yeah. OK.
Can I wolf 9? OK OK.
So let's do this.
So he can't send it from serrala unless he got contact serrala, I guess. OK.

Lem   2:26:38
Yep, Yep, that's right.
Yep. So we can use the like the P9 Wolf 9.

Bryan Wolf   2:26:45
For now, yeah.

Lem   2:26:46
Yep.

Bryan Wolf   2:26:53
That's good.
I don't think we need to authenticate it.

Lem   2:26:54
Yeah, a sender.
Yeah, just add the sender anyway.

Bryan Wolf   2:26:58
OK.

Lem   2:26:58
And then Yep, authenticate.
So yeah, for the, yeah, I think we could use this one, the P9 to send just the test.

Bryan Wolf   2:27:24
Oh.

Lem   2:27:24
Yep, OK.

Bryan Wolf   2:27:26
So now can I take?
Let's just take this one off.

Lem   2:27:27
Yeah, just change it.

Bryan Wolf   2:27:30
How do I get a campaign contacts?
Yeah.

Lem   2:27:35
Yep. And then.
You could actually.

Bryan Wolf   2:27:44
I'm just gonna add another one with this or I can edit it.

Lem   2:27:46
OK.
Yeah you can.

Bryan Wolf   2:27:49
I'm just gonna delete that.

Lem   2:27:51
Oh, the yeah you can.
Just no.
It's OK because we're just adding this to the list so that he could also receive the e-mail, but for.

Bryan Wolf   2:28:00
But where's the where's the? The one we just added?

Lem   2:28:02
This.
Are we?
Yeah, we need.
We need to create another contact for it.
So yeah, just create a contact. Let's say Peter 2 and then.
And yeah, and then.
For the e-mail just that.
P9 roof 9:00 so that it would also like receive that e-mail.
And then for the list. Oh, right, I OK just click.
I just refresh and then.

Bryan Wolf   2:28:35
I'm sorry.
Now I'm so bad at this.

Lem   2:28:37
Yep.
Yeah, just add it to the list so that it will also receive the first e-mail.
No, just on the contacts and then?
I click I mean click the you can click the X because it's all filtering out all the your first list.
Yep. And then just yeah, click Peter 2 and then you can add.
The on the lists, yeah.
On lists, yeah, this one.
Oh no.
On the can you go back again to contacts and then Peter 2 and then there's. Yeah. This one. Yep. And then add to a list and then just add him to the your first.

Bryan Wolf   2:29:28
Lam, what would I do without you, man?

Lem   2:29:29
Yeah.
Yep, Yep. And.

Bryan Wolf   2:29:32
I gotta ask you, is it frustrating to sit here and you know where you want me to click? And I'm like, fumbling.
I don't know.
Where the **** to go half time.
Does that annoy you?

Lem   2:29:42
Now it's it's OK because.

Bryan Wolf   2:29:45
That would bother me.
That would bother me, you know, 'cause, I'd be like it's right there.
It's right there. It's right.
I would be like that.
So this is good, right?

Lem   2:29:53
Yeah. Yeah, that's good. Yeah.
And.
Yeah. And then for the for the make on make sitemake.com, yeah, you could change the.
Yeah, this one. Oh, yeah. OK.
It's already P 909.
And then yeah, that's good also.

Bryan Wolf   2:30:10
Mm hmm.
Just running again.

Lem   2:30:14
Yeah, yeah, we could try to.
Let's try to run it again.

Bryan Wolf   2:30:20
And now this contact means it's gonna send to me, right?
They want this one right.
That means I get it too.
Oh, no, hold on.

Lem   2:30:27
No, no, not yet.

Bryan Wolf   2:30:27
I gotta change that as well.
Well, it's also look.
It's also my serrala one too.
So you know what? I'm gonna create one for myself.

Lem   2:30:35
Yeah, that actually would just send the test e-mail to P9. So what?
We can do here is to activate the others other automation to send that particular campaign.
So Yep.

Bryan Wolf   2:30:55
Honestly, let's just run and see if it works 1st and have it send to Peters 'cause I have access to it anyways. OK so.

Lem   2:30:58
OK.
OK.
Yeah, just run it first.
Yeah, because.
Let me just check the.
Umm.
Send this letter.
Uh.
Revoke campaign it.
All right, there's a REVO campaign ID here. OK.
To go back to the Google sheet, you would actually I think see.
Just alright, I just changes the campaign ID because it's OK.
Yep, then.
That's.
I think this will already.
Send it to Yup, I think.
It's really taking a long time.
Yeah, think chat, ChatGPT is kind of slow on your your time us and Western time.

Bryan Wolf   2:33:17
It stopped.
Mm hmm.
Yeah, OK. Haha.

Lem   2:33:27
There. Yeah, there are lots because it's mostly used I think on yeah. On the western time.

Bryan Wolf   2:33:34
Yeah, yeah.

Lem   2:33:40
Then they have some like tiers there that they the like the tier five I think is.
Faster ones dear.

Bryan Wolf   2:33:49
That's what we're in. Oh, OK.

Lem   2:33:50
Four there, 5 for sure.
No, I think the for the basic like we only have like the on the 1st tier like tier one. Then depending on the like the usage and also I'm not sure how they calculate the Tier 2 something. Oh.

Bryan Wolf   2:34:05
Man.

Lem   2:34:11
Cannot create another account.
Is under validation.
Oh, that's.
Oh, I think.

Bryan Wolf   2:34:20
Is this?

Lem   2:34:22
I think becau it's because we.

Bryan Wolf   2:34:25
Vitzerrell.

Lem   2:34:26
Yeah, we change.
We added the SMTP like the other e-mail.

Bryan Wolf   2:34:33
Can I delete this? I just want to delete these posts, get these post out of me.

Lem   2:34:34
So I can send.

Bryan Wolf   2:34:39
Can I delete don't have?

Lem   2:34:42
Yep. Permanently.
And then yeah, it's can, but you already like.
Like verify this particular account right on when after.

Bryan Wolf   2:34:56
I don't know.
I don't know what to say.
Think this is his account so.
Yeah, look right here.

Lem   2:35:09
Oh yeah, your account is validated.
Yeah, I think it's just because of the change another.

Bryan Wolf   2:35:15
But yeah.

Lem   2:35:17
The yeah, but you already tried also, right on your account on your.

Bryan Wolf   2:35:24
On my bravo.

Lem   2:35:25
Yeah, and yeah, on your revo and it's.

Bryan Wolf   2:35:27
I mean, we could.
We could put mine on there too.

Lem   2:35:33
Yeah, we could.

Bryan Wolf   2:35:33
Should we do that?
You wanna try them on?

Lem   2:35:35
Yeah, we could actually just do test it out.
So you did you try it out?
Also, on already on your account.

Bryan Wolf   2:35:44
Oh my bravo.
Yeah, mine's.

Lem   2:35:45
Or.

Bryan Wolf   2:35:45
Mine's all good.

Lem   2:35:47
OK.
Yeah, I think we we only have, yeah, we have.
There's like because we changed the e-mail there, so that's.

Bryan Wolf   2:35:56
Oh God, I didn't.
I didn've this though.
I didn't save this API key. I hate how I can't.

Lem   2:36:00
Oh, right.
Yeah, because it's like, no, no, it's OK, because you already have, I think your credentials there on make. So you don't need the API key.

Bryan Wolf   2:36:03
Hold on.
I might have emailed it, I might've emailed it.
I don't think so.
I don't think so, but.

Lem   2:36:14
So this is not yours the.

Bryan Wolf   2:36:17
I think it might, it might be.

Lem   2:36:22
Yeah, you can actually click the sender and then check there. If. Yeah, I think this is. Yeah on your account.

Bryan Wolf   2:36:27
It's fine. Yeah, yeah.

Lem   2:36:28
So yeah, we could actually test it out on.
Your yeah, test it out for now.
Then maybe later, like a few.
Like few hours.

Bryan Wolf   2:36:39
Tomorrow it'll hurt. It'll be better, yeah.

Lem   2:36:40
Yeah, I'm married tomorrow and already be good.
And then.
Yep.
OK.
Let's double check this.
Also, yeah, I think this is all good.
Yep, I think we could trigger it again.
This ChatGPT is only the one that is really taking.

Bryan Wolf   2:37:27
I know literally.

Lem   2:37:28
Yeah.
This also like a long I think a long prompt.
Because of the formatting and also the output so.

Bryan Wolf   2:39:25
Thank you for having.

Lem   2:39:26
Like.
Yeah, it's staying forever.
Sophie, don't get like a timeout.

Bryan Wolf   2:39:52
Yeah, hopefully.
I'm praying we don't.

Lem   2:39:56
No.
So you you also tried the whole flow on your account or?

Bryan Wolf   2:40:03
No, I didn't.
I'm doing Peter's good mine.
Yeah, we'll do pizza. I I before I was doing it on my first and then Peter's. But I'm just gonna start doing Peter's first. Just so 'cause. He's really demanding so.

Lem   2:40:07
OK.
OK.
Oh yeah, I think.
Yeah, I think it's ready.

Bryan Wolf   2:40:19
Once it worked, worked.

Lem   2:40:20
Yeah. Can you can you check the?
Your the e-mail.
To send, I think on your e-mail.
Yep.

Bryan Wolf   2:40:37
Let's go.

Lem   2:40:37
Yep, this one. Yep. So that's.

Bryan Wolf   2:40:39
All right, here we go.

Lem   2:40:43
Yeah.

Bryan Wolf   2:40:43
Much better.

Lem   2:40:48
Yeah. So yeah, as you can see there like lots of highlights there like color blue ones.
So yeah, this was like my yesterday.

Bryan Wolf   2:40:56
Yeah.

Lem   2:40:59
Prompt so.
Yeah, tweaked it a little bit so that it won't output that too much. Highlight color. Yeah, color.

Bryan Wolf   2:41:05
OK, cool.
Nice, this is great.
Yeah.

Lem   2:41:17
Yeah. So Yep.
Yeah, if if we already.

Bryan Wolf   2:41:23
Listen, sil.

Lem   2:41:24
Yeah. Finish the build up to be only few clicks to send a newsletter, so that would be great.

Bryan Wolf   2:41:30
God. Yeah, we always gotta work through this so hard.

Lem   2:41:34
Yeah, the the initial build.

Bryan Wolf   2:41:34
But.
So I got a question so.

Lem   2:41:38
Up.

Bryan Wolf   2:41:40
If I want to.
Mess around with this.

Lem   2:41:45
Yep.

Bryan Wolf   2:41:46
And try try to.
Implement like.
Like the HTML formatting a little bit just just for me on my end which which flow is that one end 2-3 you don't know.

Lem   2:41:56
OK.
Yep.
Uh.
Yeah, on it would be on the #3.
So yeah, you would.

Bryan Wolf   2:42:10
OK.
In here formatting right?

Lem   2:42:14
Yeah, they're on ChatGPT and then yeah.

Bryan Wolf   2:42:16
OK. And now I have another question, if I wanted to.
Add add like specific accounts in the LinkedIn scraper.
That would be on this one.

Lem   2:42:28
That would be, yeah, this one.

Bryan Wolf   2:42:30
On the Yeah, app 5.

Lem   2:42:31
And then on the Amplify.

Bryan Wolf   2:42:33
Honestly, I'm gonna. I'm gonna let you do that. 'cause. I know you're gonna be much better at it than me.

Lem   2:42:39
Yeah, but you could.

Bryan Wolf   2:42:39
But I'm gonna try and mess around a little bit.

Lem   2:42:40
Actually it's it's. Yeah, it's it's pretty.
You can just click that one. Yeah. The. Yeah, this one. And then as you can see there.

Bryan Wolf   2:42:49
I could ask chat GT about this right?

Lem   2:42:51
Yeah, this this author URL, so you can just.
Like copy this format like there's a what you call this like the call. I mean like a code code and code.

Bryan Wolf   2:42:59
Yeah.

Lem   2:43:05
So the link is inside the code and code.
And then for every for every.
Like LinkedIn profile there you would just add a comma and then space and then the last last link in profile will will not have the comma.
So basically the first link and then comma and then space the second link and then yeah, that's the and then you would, yeah, you you need to put the their complete link inside the two coats.

Bryan Wolf   2:43:22
OK.

Lem   2:43:35
So yeah, basically you can add here as many.

Bryan Wolf   2:43:35
Yeah.

Lem   2:43:38
As many.
Prof.
LSC One then also the same as on the Reddit it's also.

Bryan Wolf   2:43:41
Yeah. OK.

Lem   2:43:46
Like similar this you can click the Reddit one.
The appify below the the other one. Yeah, this one.
So here you can see here on the on the bottom side.
Yeah, this one so URL.
So this is just getting the URL which is the HTTPS Reddit R automation.

Bryan Wolf   2:44:12
OK.

Lem   2:44:13
Then you can just add.
Their like.
URL together like space, then another.
Yeah, Reddit subreddit URL also.
But yeah, you can play around with this one and then also for the Linkedin's scraper.
Yeah.

Bryan Wolf   2:44:34
Nick had said.
A lot of information to the chat.

Lem   2:44:39
Yeah, this. Yeah.

Bryan Wolf   2:44:41
I'm gonna try and. Why can't I pull this? OK like this is this is the LinkedIn stuff. I think for the LinkedIn stuff. I don't know if you have this like.

Lem   2:44:49
Yeah, but you you will need you. You will.
You will need to search the this name because we need the link to their profile, so I think yeah, it doesn't have the link.

Bryan Wolf   2:44:59
Right.
You need to like find it first and then go get the link and go somewhere.

Lem   2:45:02
Yep, that's right.
Yeah, link in profile.

Bryan Wolf   2:45:03
So that even for these so like.
You're gonna work on this, I'm assuming, right?

Lem   2:45:07
And.
Yeah, I'll update it tomorrow.

Bryan Wolf   2:45:10
Yeah. So these are the.
These are the. These are the subreddits that Nick Nick's like, really in deep on Reddit.
So these looks, I mean I think Peter wants to focus mostly on finance and treasury.

Lem   2:45:18
Hmm.
OK.

Bryan Wolf   2:45:25
Not so much.
We don't really need this, I don't think.
I would not even this.
I would just focus on on technology, programming and AI and finance and treasury.

Lem   2:45:37
Yeah.

Bryan Wolf   2:45:41
So I see.

Lem   2:45:41
OK.

Bryan Wolf   2:45:42
Other than that, I'm about to get off one.

Lem   2:45:44
Yep, OK.

Bryan Wolf   2:45:46
You're the man.

Lem   2:45:47
Find.

Bryan Wolf   2:45:47
You're the man, as always, Lib.
You are the man, dude.

Lem   2:45:50
Thanks. Thanks.

Bryan Wolf   2:45:52
You're the man.
Alright, well, I'm glad we got this to work.

Lem   2:45:55
Huh, that's right.
OK.

Bryan Wolf   2:45:58
We'll talk.

Lem   2:45:59
Yep, just.

Bryan Wolf   2:45:59
We'll talk tomorrow evening. Tomorrow night. Your time tomorrow morning. My time.

Lem   2:46:02
Yep.
Yep, tomorrow, OK.
Talk to you soon, Bryan. Yeah, play.

Bryan Wolf   2:46:07
See you, brother. Yeah. Bye.

Lem   2:46:09
Play around with this.
It's good, yeah.

Bryan Wolf   2:46:11
I'm gonna.
I'm gonna. I'm gonna try and work on the the HTML formatting and then I'm gonna try and get specific with the, with the Reddit and LinkedIn links, and we'll talk in the morning.

Lem   2:46:16
Yep.
Yep. OK. OK.

Bryan Wolf   2:46:21
Alright, see ya. Bye.

Lem   2:46:22
Talk to you soon.
See ya. Bye bye.

Peter Wolf stopped transcription


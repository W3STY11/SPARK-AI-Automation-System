# Process Automation Workshop (9)

**Original File:** Process Automation Workshop (9).docx
**Extracted Date:** 2025-06-17 (Tuesday)
**Converted:** 2025-07-28 11:40:58

---

Transcript

June 17, 2025, 12:57PM

Peter Wolf   2:17
I don't know if you noticed, Brian, but I also set it up so that the.

Bryan Wolf   2:21
Note taker and it records.

Peter Wolf   2:23
It will automatically record every time, yeah.

Bryan Wolf   2:27
I just didn't miss it actually.
I don't even think I have the original 1, the name one back in.

Peter Wolf   3:02
You what?

Bryan Wolf   3:04
The original would frickin lamb.
I had upgraded my account and I didn't save it so I lost it, but she had to go through a re upload of code and redo it.

Peter Wolf   3:14
You tell me you lost the original process flow.

Bryan Wolf   3:16
Yeah, 'cause, when I upgraded my car, I didn't save it, so it's not my scenarios, but it's fine.

Peter Wolf   3:23
Didn't you say you already moved it over to my account?

Bryan Wolf   3:26
No, I don't have 'cause you.
You never gave me.
I don't have any.

Peter Wolf   3:30
I gave you all my passwords, dude.

Bryan Wolf   3:33
For make.

Peter Wolf   3:34
Yeah.

Bryan Wolf   3:36
OK.

Peter Wolf   4:34
What did I?
What did I put the P hold on? Hold on.

Lem   4:45
Hi, guys.
How are you?

Bryan Wolf   4:47
Hey, Lam.

Peter Wolf   4:48
How's it going then?

Lem   4:50
Yep, all good.

Peter Wolf   4:54
All right. So excited to look at the hello. I didn't get a chance to look at the video that yet.
So if you could just walk through it, that would be great.

Lem   5:07
OK.
Let me just.
OK.
So here's the flow.
I've created it just one flow from end to end, so I also.

Peter Wolf   5:36
Hey, Bri, hold on one SEC.
Hold on, then, Bri. Is that really blurry for you?

Lem   5:38
OK.

Peter Wolf   5:40
Oh, no, OK, it's my screen.

Bryan Wolf   5:41
It'll buff it buffs out, yeah.

Peter Wolf   5:43
OK.
All right, we're good.

Bryan Wolf   5:44
Excite.

Peter Wolf   5:47
Go ahead then.

Lem   5:49
OK.
Yeah. So we have also one spreadsheet here for the database.
See for this one. So all the articles are being put here, then we are still also using inoreader for the newsletter. So the first module is the first note is coming from Inore reader, so I'm also still getting it from this particular collection or folder the finance and.
Economics folder.
So these are like the like the famous ones like Wall Street Journal, Financial Times.
Like Yahoo Monthly, for something like that.
Then I still have the.
Rule here that whenever there is like the tactic language, it's English so it should Mark as read so that we will always have zero 100 here because there's a limit on Ino reader that only 100 unread for the list.
So we should always.
Yeah, that's why I've added that particular rule then yeah, basically I've added.
It will.
So next there's another filter.
So other articles also doesn't have a summary content, so I filter it out that it will only pass through if it has summary content and then next is it will go to the IT will search that particular database. Our Google sheet and it will find the duplicate depe.
On the URL.
So if it's the same URL, it won't pass through again.
So next one is it will create also the unique identifier.
So that we would we can access the particular article on the next on the following modules and then next one is it will feed all the data of the articles to our spreadsheet. So it should be like this like the publication date, title, website URL, image URL if.
It has a image, URL and summary and then also the UUID.
Then that's it.
And then next is.

Peter Wolf   7:45
Can I?
Can you just go back to that second?

Lem   7:46
It.

Peter Wolf   7:47
I'm surprised of those.
That so many didn't have an image. If their article's almost always, it would have an image, no?

Lem   7:54
Yeah.
For this one, if it's coming from full.com, so it doesn't.
Actually it can't get the particular image, so they have like. I don't know if parsing or something so but for the other websites like the Fortune, yeah it it was able to get the image only for this particular website and yeah for the other ones also. Yeah so.

Peter Wolf   8:07
OK.
OK. All right.

Lem   8:18
And then, Yep, and then it next one is this is an aggregate module, so it will take all the data like the title, summary and UUID and then it will batch all of it and put it into one bundle so that we can feed it to chat G.
And then ChatGPT will choose the top three.
So I just for testing I've added only like 3 here top three but.

Peter Wolf   8:41
Yep, Yep.

Lem   8:42
On. Yeah. On the original, it's like top 10, right?
So that, yeah, so we can just change the prompt in prompt here and then it will get the top three articles and then it will also.

Peter Wolf   8:45
Yep.

Lem   8:55
Output.
Commentary on that particular article, a summary and a commentary, and then next is we will iterate again that particular result.
So it would be.
Actually, several resort salts because it is like top three articles.
So there are three results.
So we we need to iterate it to process that particular data so.
This just means that it will process 1 by 1, so it will actually loop from first one, then go here and then loop back here to process the other remaining data.
So the first here is it will search for that particular article using the UUID and then depend. This one is actually an Unsplash.
Node. So this is actually getting random images on that has business business on the business category.

Peter Wolf   9:45
So if they didn't have an image, they'll they'll create something you're saying.

Lem   9:47
So.
Yes, that's right.
Yeah. So if it doesn't have an image, I've added a switch module here.
So the Switch module has the pattern. If the image URL is empty, it will output the particular image coming from the Unsplash and then if the pattern has a match.
So if there's a particular URL, so it will just output the image URL, so next one is yeah, it will create the subsection for that particular newsletter in HTM HTML format.
And then yeah, so it will loop again for the next article and then it will pass through again here and then.

Peter Wolf   10:22
So tell me again what's the create subsection?
So it's the, it's the, it's where it's gonna write that commentary of something.
Why it's important or valuable or something?

Lem   10:31
Yeah, that's right.
Yeah, it it will actually create the particular like as you can see here. Let me just because this is like.

Peter Wolf   10:38
Yeah, because originally we said we're sending the, the, the, the.
Summary the summary is gonna assess the summary and it's gonna say OK.

Lem   10:45
Yep.

Peter Wolf   10:46
This is good or bad?
Ultimately, it's gonna pick 10.

Lem   10:49
Yep.

Peter Wolf   10:49
It's gonna send the ten or three in this case, but it's gonna send them if it doesn't have an image, it's gonna apply an image and then it's going to. It's going to write the commentary. At that point, it already went, picked the choices, but it didn't do.

Lem   10:58
Yep.

Peter Wolf   11:04
The commentary back when you did the first ChatGPT.
It just did the selection.
And then this card to chat GPD it's gonna write the commentary.

Lem   11:10
Yeah.
Yeah, I actually did it already.
This one already chose the top three articles and then it created like the commentary.

Peter Wolf   11:18
Yep.

Lem   11:21
And then I fed the commentary and summary here to ChatGPT.
Another so this is actually the one who is creating this particular particular.

Peter Wolf   11:31
OK. But so it took, it took the IT took the original choice of three and said why is this good right?
Here's the three.
Here's my spin on it. Then you fed that back in and said now write a commentary.

Lem   11:38
Yep, that's right. Yeah. Yeah, that's right.
Yeah, that's right. Yeah.

Peter Wolf   11:43
OK.

Lem   11:45
And then yeah, basically that's it.
And then.
OK.
So the next one is. This is also an aggregator, so we are just like feeding the output that is coming from ChatGPT and we are like parsing it out so that it will be read read by like the brevo brevo node.
So this is just like a HTML.
So Brevo is actually.
Using HTML code for its like the text headers and it's like formatting.
So this is just like the coding.

Peter Wolf   12:19
So let me ask you something just for for kind of understanding for Brian or the guys.

Lem   12:21
SIM.

Peter Wolf   12:24
So when you go into that, that little module in make.

Lem   12:24
OK.
Yep, this one.

Peter Wolf   12:30
Does it? Do you have to?
You have to bring in the HTML aspect or it knows how to apply the HTML or what is it.
What is it that you did there actually?

Lem   12:37
Yeah, yeah, I actually we would need to, like, put this one manually.
So depending on the nodes, so usually the like e-mail campaigns like mail, MailChimp or also like beehive they they use like the HTML content. So as you can see here on.

Peter Wolf   12:55
So B, I've already gave you from Beehive.
You took the structure in HTML.
You applied it in here or you had to interpret it and write that.

Lem   13:04
Yeah. I I yeah.
So I actually interpreted it and like I I because brevo doesn't have like a format for the e-mail, but it actually use like a HTML language, so that's why it's set up like this.
So if we would like put just put a text, it will be like it.
It won't look good on the newsletter.

Peter Wolf   13:26
Yeah, I got you right.

Lem   13:27
It, yeah.
Yeah. So.

Peter Wolf   13:28
So you're actually building the structure here.

Lem   13:30
Yeah, that's right. Yeah, so.

Peter Wolf   13:31
So this is the prior. You know, I don't know when those guys will look at it later, but this is the kind of stuff you'll need to play with on structuring, right to say, OK.

Lem   13:40
Yeah.

Peter Wolf   13:42
How do I want it?

Lem   13:42
But but basically.

Peter Wolf   13:43
Do I want it center or do I want it center justified left justified?
Give it space.

Lem   13:47
Yeah.

Peter Wolf   13:47
Give it highlighting all that kind of stuff.
This will be stuff you'll want to play with, right?

Lem   13:50
Yes, that's right. Yeah, that's right.

Peter Wolf   13:53
OK.

Lem   13:53
Yeah. So for this one, this is like just a simple like for this one. This is like the image only.

Peter Wolf   13:57
Yeah.

Lem   13:59
So then this is for the link and then yeah basically that's it.
Then we we are for this node.
I'm actually aggregating it all because these are like.

Peter Wolf   14:09
Individual.

Lem   14:11
Yeah, individual.
So after it's all processed, it will put all of it into like A1 bundle with this particular.

Peter Wolf   14:12
Yeah.

Lem   14:19
Formatting SO1 format.

Peter Wolf   14:21
OK, I thought that was the wrap up the aggregator.
So go back to the integrator for the first piece comes through, creates it and then it's then then it.

Lem   14:28
Yep.

Peter Wolf   14:30
Hold on.
Search for the article what's the via UUID?
It's you gave it a unique identifier.

Lem   14:37
Yeah. So it's so that we can access the like the title, the summary.
So I've because I've added here on the this one. I've created a UUID and assigned it to that particular article.

Peter Wolf   14:49
OK. And the UUID is just a structured set of information you want to go with that?

Lem   14:49
So it's yeah, it's actually.
Yeah. So this is like, yeah, a random generated UUID here that is here on meet variable.

Peter Wolf   14:55
OK.

Lem   15:02
So this is like a random generated something like this? Yeah. And then I've assigned it so that we can pull it out on the following modules.

Peter Wolf   15:05
Yep, OK.

Lem   15:13
So yeah, on here.

Peter Wolf   15:15
So you can directly reference that same specific article to know you're working with the same line item, and then when you put in the spreadsheet. Also if you ever come back to edit or anything you go to that unique ID.

Lem   15:18
Yep, they're yeah.
Yes, that's right.
Yeah, that's right and yeah.

Peter Wolf   15:27
OK.
So then that first iterator sends one through at a time. It goes through. Does the search for the UUID.

Lem   15:32
Yep, one.

Peter Wolf   15:34
Then it determines whether it has an image or not. If it doesn't have an image, it applies a generic image.

Lem   15:38
Yep.
Yep. Oh yeah.

Peter Wolf   15:41
Then it goes the switch.
Empty or not, what is that one again?

Lem   15:45
Yeah. So this is for the image URL.
So the other ones have empty.

Peter Wolf   15:48
OK.
So in the first one's to generate the random image, then it's the next one is. If it doesn't have the pattern, it shows it has an image, then populate the random image in there. OK then you go to the next step and then it's. That is the.

Lem   15:49
Yeah. So.
Yep. Yeah, that's right. Yep.
Yeah. So this next.
Yeah, this is, yeah.

Peter Wolf   16:05
Subsection, it creates the subsection, the blurb for that particular picture, right?

Lem   16:09
Yeah. Yep, that's right. Yeah.

Peter Wolf   16:09
Or that particular article.
And then what's the next sub subsection? That's where you said you bring it all back together, but where is the iterator saying?

Lem   16:14
So.
Yes. Yeah.

Peter Wolf   16:18
Go back to step one iterator.

Lem   16:21
It's it actually is like looping already looping if it's structured like this, so it's if there's an iterator.

Peter Wolf   16:27
So you don't have to say where the end of the loop is.

Lem   16:31
No, this is the end of the loop. Whenever there's yeah, the aggregator would be the end of the loop.

Peter Wolf   16:33
That's the end of the loop.

Lem   16:37
So actually it's like passing through, right?
And then it is passing.
It is giving the first like result here and then going back again then passing through here again then giving the 2nd result.

Peter Wolf   16:46
OK.
So the aggregator at the end is the thing that tells it it's done and go back to the iterator again.

Lem   16:52
Yeah, that's right. So and then.

Peter Wolf   16:53
OK. And then ultimately though, you said the aggregator said aggregate is capturing the first one and then it's saying go back to the iterator.
Iterator goes through and then it captures the second one and includes it with the first one. Then it goes back.

Lem   17:02
Yep, the second one.
Yep, that's right. Yep.

Peter Wolf   17:06
Iterator goes back again, captures the third one, and now you've got the full thing.

Lem   17:09
Third one. Yep.

Peter Wolf   17:10
It knows it's done.
It goes back to the iterator says there's no more, and then it goes to the next step.

Lem   17:14
Yep.
Yep, that's right.
Yeah. So if it already processed all the data here, it will now output the final results.

Peter Wolf   17:17
OK.

Lem   17:23
So the final result will have the three particular particular data in just one bundle.

Peter Wolf   17:31
Yep.

Lem   17:31
Yeah. Yep.
So that one and then next is we we have again an iterator module.
So this one is actually iterating again the like the title and summary.
So this one is for the today's insights because we have here like right like that today's insights and then there's like the bullet points like once.

Peter Wolf   17:48
OK.
So that's the header. That's the lead in, right?

Lem   17:51
Yep. Yeah, that's right.

Peter Wolf   17:51
The lead in OK, good.

Lem   17:53
So like the preview.
So that's why there's like this particular also iterator and then aggregator and then next is we would feed that particular.

Peter Wolf   17:58
Yeah.
Yep.
Hold on. What?
Why would there be an aggregator if there's only one lead in?

Lem   18:05
Insight.
Pardon.

Peter Wolf   18:09
If there's only one lead in right, you've got three articles, and we're gonna do one introduction and one kind of wrap up.
Why would there be an aggregator?

Lem   18:16
Yep.

Peter Wolf   18:17
Why is it iteration if it's really not iterating?
Here it's just got OK.
You gave me all three articles. I wanna create a header or a lead in.

Lem   18:25
Yeah, because we would also feed this one to ChatGPT and then it will create ChatGPT is actually the one who is creating this.
This particular section, yeah.

Peter Wolf   18:36
This highlights today's insight.

Lem   18:37
So the intro and then the bullet point.
So we would need to feed that to ChatGPT and then ChatGPT is the one, yeah, who's creating that one like the.

Peter Wolf   18:44
OK.
So I I still don't.
I'm not sure I understand.
So tell me this this flow right here. Again, we got the three articles coming out aggregated together out of the previous loop, right?

Lem   18:55
This one, yeah.

Peter Wolf   18:56
Yep, we got the three articles with all their information ready to go.
Then it comes to the new iterator.

Lem   19:01
Yep.

Peter Wolf   19:02
Now it's got one aggregated set of three articles.
What is this doing?

Lem   19:06
Yeah, basically if we have a iterator and aggregator, we can't actually pull out the data that is coming inside of that particular like section.
So that's why I've added another iterator that is pulling out data from from ChatGPT.
Yeah. So this is from ChatGPT.

Peter Wolf   19:25
Oh, it's not pulling from that loop there.

Lem   19:27
Yeah, it's not pulling here.

Peter Wolf   19:27
It's even though it looks like it's going linear, it's not.

Lem   19:29
It's. Yep, that's right.

Peter Wolf   19:31
It's really a link that goes all the way back to ChatGPT.

Lem   19:34
Yeah, that's right.
Yeah, it's actually pulling data from here.

Peter Wolf   19:35
That's interesting.
That looks confusing.
Why doesn't it just have a link coming off?
Downloaded another branch.

Lem   19:42
Yeah.
Well, that's really because actually we can like pull data from also like from the first module.
If let's say from here right like the here like the brevo or the last one like the Gmail. Note we could actually pull the data coming from the first one, not just like the before.
So that is how like the data works on the integration like here on make or even in Zapier.
So you can actually pull data coming from like the past past platforms, yeah.

Peter Wolf   20:20
But from from me right for for me and for the interns from a Tri logic to get your head around it.

Lem   20:22
Yep.

Peter Wolf   20:27
Maybe that that is not.
Maybe that is the way. Clearly you can do it, but doesn't it make sense to have if two? If one thing isn't a dependency on the other, shouldn't we show them in parallel like the step Now for that second iterator?

Lem   20:44
4.

Peter Wolf   20:44
Actually, there's nothing.
There's there's no reason if it comes from the original, that it shouldn't be parallel to that first iterator, no?

Lem   20:52
On this one from this one.

Peter Wolf   20:53
Yeah, if you put an I'm just again, I'm.
I'm just looking at it from a from an inexperienced person thinking about a process flow.
This first iterator.

Lem   21:04
Yep.

Peter Wolf   21:05
Let's call this the. Let's call this the you know blurb iterator per article, right?
The first one is the blurb iterator part article and then aggregates them together.

Lem   21:12
Yep, OK.

Peter Wolf   21:16
The second iterator is the.
Is the intro in iterator right?

Lem   21:20
Yep, that's right.
This is for the intro. Yeah. Yeah, that's right.

Peter Wolf   21:22
Yep. So what would happen if you put the intro?
Integrator.
And the blurb integrator parallel so coming out of ChatGPT three articles instead of going directly into. Yeah, instead of going into the iterator for articles.
Well, hold on cuz. You say it's grabbing the information directly from ChatGPT rather than coming taking the output from what you did the first iterator.

Lem   21:43
No.
Yeah.
Yeah, yeah.
Yeah, we can't do that here because it's actually.
Creating the bundles as the same because like like we have like like top three articles or let's say top 10 right?
So it's actually parsing it out and feeding it as multiple multiple formats like this one.
So if we add this particular data here on this particular section, what will happen?
Is it will all all have like the inside spur here?
So if that makes sense.
So that's why I've added another section here, because if we would put it inside here.

Peter Wolf   22:31
No, no, no here can.

Lem   22:32
What?

Peter Wolf   22:32
Is it possible for you to give me your ability to to move your cursor on your screen?
Can you can I share?

Lem   22:39
Umm.

Peter Wolf   22:40
Can you like so I can show you what I'm looking at?

Lem   22:41
I.
I'm not sure if I don't know if that's possible.

Peter Wolf   22:45
Hold on a second.
Hold on a second.
Wait, go back. Stop. One second. Can you zoom out?

Lem   22:49
OK.

Peter Wolf   22:51
Just a little bit zoom out just a little bit.
No, out so that it's smaller. I want it to be small.

Lem   22:53
Yep. Oh, out. Out. Yeah, yeah.
OK, OK.

Peter Wolf   22:56
OK, stop.
Stop there.
There you go. OK.
Hold on. Let me take a screenshot.
All right, let me share my screen.

Lem   23:09
OK.

Peter Wolf   23:21
OK.
So what I'm saying, I'm gonna get rid of my image here.
Stop my camera so I get this out of my way.
OK.
So what I'm saying is that.
This right here is coming up with the three articles that we want, right?

Lem   23:44
Yeah, that's right. Yep, Yep.

Peter Wolf   23:45
Then this this iterator says send one article through OK one article come through, get the UUID, add an image if it needs one, and then write a blurb and then hand it to the aggregator that now takes #1.

Lem   23:53
Yeah.

Peter Wolf   24:02
Then it goes back around and says here again, here's article #2 get around again.

Lem   24:03
Yeah.
Yes, that's right.

Peter Wolf   24:07
Here's article #3.
Now I got 3. The output from this is three articles right here. Right. OK.

Lem   24:14
Yeah.

Peter Wolf   24:15
Now what I'm saying is this right here?
The way you have it, is it dependent on what's in these three.
It is right?

Lem   24:25
No, no, it doesn't need to pick up data here so.

Peter Wolf   24:26
You.

Lem   24:32
How the flow works is like it's like linear, right?
And then it can actually like it can actually process data not coming from like the immediate. Yeah, the previous set.

Peter Wolf   24:41
The previous set. OK, so this is what I'm saying. This one isn't looking at the three articles that were combined here. It's looking at the output from here.

Lem   24:45
So.
Yes, that's right, yeah.

Peter Wolf   24:51
OK.
This is first pushing it out as one, like when it interprets this. This is iterating 'cause it's saying.
Here's Article 1.
Here's Article 2.
Here's Article 3.

Lem   25:00
Yep.

Peter Wolf   25:00
Then it's saying, oh, I have these three articles and let me write the summary. Let me write the header right.

Lem   25:06
Yeah.

Peter Wolf   25:07
OK.
So it has to see all the articles, right?
But what happens if?
Hold on a second.
Ah, come on.
How's going on?
Don't know why it's not letting me cut.
Yeah. What if you did these in parallel right here that this so 'cause to me, it makes more makes logical sense that that this isn't really dependent on this.
So I'd really rather see it as its own as its own flow, right?
So coming out of here I have output.

Lem   26:13
Oh yeah, like.

Peter Wolf   26:14
Well, that output goes into here and iterates and aggregates the body content.
Then it sends over here in parallel.

Lem   26:19
Yeah.

Peter Wolf   26:20
It sends the information necessary to create the header.
Then they come back together. However, wherever and and.

Lem   26:27
Yeah. So for this one, we, yeah, it we would.

Peter Wolf   26:30
Yeah.

Lem   26:31
We can't pull out the data coming from another route so, but actually we could actually do that and like set variables. So that let me just show you.
Let me can I share my screen.

Peter Wolf   26:43
Yeah, please.

Lem   26:44
Yeah, I think I'm getting.

Peter Wolf   26:45
Again, I'm trying to think of.
I think in in process flows, if this isn't definitively based on this step, then I don't wanna show it after that step, right?
Because that makes me believe I must go through this step to get to this one.

Lem   26:56
Yeah. OK.

Peter Wolf   27:01
And for me, logical thinking, I would wanna show this is on a separate path.
I don't need the stuff in here to make this work. I need the stuff in here.
So I wanna show it coming off of this branch.

Lem   27:13
Oh yeah, yeah, I see.
Yep, actually, we could let me just, yeah. Share my screen again.
So for that one, let me just.
Duplicate this one.
Now let's see.
For this this flow right?
Yeah, this flow.
So what basically want is like you want to like unlink this right?
And then put it on another branch so that it would be.

Peter Wolf   27:53
That's that's the way it would make more sense to me.

Lem   27:57
Yeah. And then something like that.

Peter Wolf   27:59
Yes, yes.

Lem   28:00
Yeah. So yeah, OK.
So for this one on make, we actually don't have like.
A.
A way to like connect to.
To like routes and put it on back to one.
So what?

Peter Wolf   28:18
Huh.

Lem   28:18
We would do this.
Yeah, it it's not possible, but actually it's possible.
But but it's.

Peter Wolf   28:23
And so is. So in make in make.

Lem   28:26
In another pardon.

Peter Wolf   28:26
I saw you do 3 pads before, right?
So obviously you must be able to have a way that you have three different pets, but you're saying those 3 pairs ultimately run to their own end.
They don't come back anywhere like in the other one where you did the the you know, if I had three different news pants, news articles, they have their own path instead of saying, well, do these different things or bring them back together.

Lem   28:38
Yeah.
Yep.

Peter Wolf   28:48
It doesn't do that.

Lem   28:50
Yeah, we can actually still do that, but it's not like connecting it but via variable.
So what?
We can actually do is we can get the tools on make and set a variable.
So let's say.
This is what is this. Again like the bullet point.
So let's say bullet points or insights. OK, let's say introduction.

Peter Wolf   29:10
It's called introduction introduction, right.

Lem   29:14
So let's say this is the variable name introduction. Then the variable value would be.
The result of the ChatGPT and then what we would do here is we could actually set up a module here which is get variable.
So this one then it will get that particular variable which is introduction.
So.
Now we can pull out that one coming from here so.

Peter Wolf   29:45
Make more sense to me because now it's like you have the three articles being aggregated and now you wanna add the introduction, OK?

Lem   29:45
Yeah.

Peter Wolf   29:52
Well then.
Now the next step after the three articles is go grab the variable that has the introduction which was on a separate branch and pull it back in and add it to the top of the articles.

Lem   30:01
Yep.

Peter Wolf   30:04
Right now you would have aggregated the three articles plus the introduction, right?

Lem   30:12
Yeah, basically that's it.
So yeah, but for this one we would need to 1st go to this route not here.
So as you can see there is actually like first and 2nd right?

Peter Wolf   30:23
OK.

Lem   30:23
So yeah, and then it should first pass through here.
So basically it's the same, then it will assign like that particular variable and then after that one it will go again to the next route.
Here this route for the subsections and then next is.

Peter Wolf   30:37
Right, right.

Lem   30:42
Basically why we need this get variable is because we are outputting that particular data here right on the brevo.
So as you can see we are outputting it here.
So this is actually the the.

Peter Wolf   30:56
As the result of the introduction.

Lem   30:57
Yeah, yeah, this is the insight.
And then like this text is actually the one from the aggregator module which which is this one.

Peter Wolf   31:05
From the three, the three tax yeah. OK.

Lem   31:08
Yeah, the subsection.
So we could just rename this to introduction.
Variable. So this is actually connected to here so it.

Peter Wolf   31:17
Even though it doesn't show a line though.

Lem   31:19
Yeah, even though it it's not showing line so.
It's still connected to here because we are setting this as a variable result and then for the next route it will be getting that particular variable which is the introduction and then it will output the result as this one. The result from ChatGPT.

Peter Wolf   31:30
Yep.

Lem   31:40
So it would output it here.

Peter Wolf   31:42
OK.
So now the the output from the subsections right before that is the aggregated three articles.
Then it says OK.

Lem   31:49
Yeah, this one.

Peter Wolf   31:50
Now grab the variable.
Now it grabs the variable for the for the introduction and now it passes those together like. Again, it looks like it's a straight line in that in the introduction.

Lem   31:55
Yep.

Peter Wolf   32:02
Excuse me. Where? Where are you identifying what you're passing into?
Into beehive or whatever the tool is reusing BB.

Lem   32:10
Yeah, so breville for this one, because we already processed like the iterator here, right?

Peter Wolf   32:17
Yep.

Lem   32:17
So this is actually the final like output or so.

Peter Wolf   32:20
So yeah, so now I'm I'm understanding something.
It's really not that you're pushing the content out to the next step. The next step is going back and calling the content.

Lem   32:31
This one.

Peter Wolf   32:32
Any step any step is.

Lem   32:33
I'm no, I'm actually pushing the data here because it's already processed right for this one.

Peter Wolf   32:39
Yeah. OK.

Lem   32:40
So the subsection. So I'm actually passing it here as you can see, this is like the output for that particular aggregator this text. So that's why.

Peter Wolf   32:48
Yeah, but, but you're already in the brevo step.

Lem   32:51
Yeah. Yeah, that's right.

Peter Wolf   32:52
So you're in the Brevo steps saying I want to go get this information from a previous steps.
So you're pulling it towards you, not. You're not pushing it from the subsection step or from the intro variables.

Lem   32:58
Yeah.

Peter Wolf   33:05
You're actually pulling it when you start your next step.
I think that's a really important difference.

Lem   33:10
Yeah. Yeah, that's right.
Yeah, I'm actually pulling it from the.
Past data.
So it's actually getting.

Peter Wolf   33:17
Right. So that's why you're saying you can pull from anywhere in that process flow, not just from the previous step, whereas if it were really a, if it were really a kind of push diagram that output from one step pushes into the next step, triggering the next step.

Lem   33:23
Yeah, that's right. Yeah.

Peter Wolf   33:32
But you're not triggering the next step. The next step is added and it's saying oh, give me or let me get this information from previous step, OK.

Lem   33:39
Yes, that's right. Yeah. So yeah.

Peter Wolf   33:41
That's a big.
That's a big I think for me, that's a like a mental.
Big differentiator.
In the way to think about the model.

Lem   33:49
Yeah. So it's actually not like flowing next.
The data is not actually passing here and then passing here and then I'm yeah, we could actually like get the data from the past.

Peter Wolf   33:56
Yeah, yeah.

Lem   34:01
So depending on the yeah.

Peter Wolf   34:01
I I get it.
I get it.
But again, what you just said is the keyword is get.
You can get the data from somewhere else.

Lem   34:07
Yeah. Yeah, yeah, yeah, that's right.

Peter Wolf   34:08
It's not being fed to it.
It was generated in some other step and sitting in that step and later on I have to go call it.

Lem   34:17
Yes, that's right, yeah.

Peter Wolf   34:17
And retrieve it from that previous step.

Lem   34:19
Yeah, yeah, this is.

Peter Wolf   34:21
OK.

Lem   34:21
Yeah, this is right.

Peter Wolf   34:24
All right, so now we have this step.

Lem   34:24
And.

Peter Wolf   34:25
We have the aggregator step and we have the intro. We have the aggregator loop and we have the intro.
Path. Then we pull this back where we grab back the introduction variable.

Lem   34:35
Yeah.

Peter Wolf   34:39
Now, why couldn't you just have in the in the brevo step?
Why couldn't you just call the the the variable there and pull the variable from instead of having extra step?

Lem   34:50
Yeah, we, yeah.
So how make works is when it's on another route, so it it can't actually get the data from another route without pulling it.

Peter Wolf   34:56
Yep.
So it's gotta be on that route for it to be able to get the data. It's gotta be on that route.

Lem   35:03
Yes, that's right.

Peter Wolf   35:05
So if it's not on that route, if you got another path, then you need to pull this variable back in to get it on that path again so that brevo can find it.

Lem   35:10
Yeah.
Yeah, that's right.
So let's say for this one. So as you can see, this is on different route, right?
So if we want to get data from here, we cannot get it.
But we if we want to get data here we can.
So if it's already separated by a route so we can't access it.
So without pulling it with a set variable and get variable. Yeah, yeah, that's actually.

Peter Wolf   35:32
Yep, Yep. OK.

Lem   35:38
So let's say.

Peter Wolf   35:39
OK.
This is Megan.
This make more sense to me but to me that that's when I look at it, it's more, it's more logical to me, right.

Lem   35:42
Yeah. So let's say we.

Peter Wolf   35:47
I'm I'm able to to to to process it better in my head of what the what the activities are.

Lem   35:51
Yeah.
Yeah, that's right. Yeah, yeah.

Peter Wolf   35:55
And So what do you do with this router now?

Lem   35:57
So I I just want to explain if let's say we have something like this also.
Let's say we have something like this.
Say something like this.
Oops, just connect this one.
So we could actually pull the data here. So as you can see this is like passing through again another route, right?
So we could actually set again a variable here and then we could actually get that one here on the other routes via set and get variable.
So yeah, Meek doesn't have like the like.

Peter Wolf   36:34
Yep, OK.

Lem   36:35
Yeah, like connecting it via.

Peter Wolf   36:37
It's only got 1 input, one output path that it can go on.

Lem   36:41
Yeah, that's right. Yeah.

Peter Wolf   36:42
It's only one bubble. Instead of being able to go to multiple different locations, OK.

Lem   36:46
Yep.

Peter Wolf   36:47
All right, I got it then.
Alright, so now we get back the variable.
Now we've got the variable and we've got the body content.

Lem   36:56
Yep.

Peter Wolf   36:56
So go in and show me again what it looks like in brevo.

Lem   37:00
So in Bravo, on here on the Bravo node. Yeah, it would, yeah, so.

Peter Wolf   37:03
Yeah. On the brevo steps.
Show me what it all does.

Lem   37:07
There's an HTML.
This is just the like the head and the style.
So for the.
Yeah, for this one.
So it would be like parsed out like this one.
But yeah, so the content is actually on the body. So as you can see this is like the body, right?
So the first one is the like the inside and then the next is the articles which is aggregated already from the subsections, so.

Peter Wolf   37:38
So that means it's that is all three articles not not just one.

Lem   37:42
Yeah, this is already. Yep, that's right.

Peter Wolf   37:43
It's all three articles with their with their headers, with their images. OK.

Lem   37:47
Yes, that's right. Yeah, that's right.
So we already actually built the like the content here and then we are just.

Peter Wolf   37:51
Yep, Yep.

Lem   37:56
From Bravo, we are getting that particular content.
Yeah. So we are getting it here.
We are accessing it from this one and then yeah, so after that one, yeah, it will create the campaign here on brevo.

Peter Wolf   38:05
OK.

Lem   38:12
So this something like this, it would be on the campaigns and then we could like review this one.
Like review the.
Review the particular.
Content and then if it's already good, we could already.
Send it to a recipient which is our like list, let's say list of active clients.
Then we can now send.
It's either.
We could send it now or we could schedule it for later.
So we actually have like a choice here.
But yeah, basically we would have it on our campaign ready for review.
And then for the next step, is it?
It's just getting the name of that particular newsletter and then sending it to Gmail for the notification.
So so that we would know if there's a new newsletter for that particular day.
So this automation is actually.
Running daily, I set it up as a trigger.
It runs every day at 8:00 AM, so it will, yeah, run every day, 8:00 AM. And then after that, let's say 8:05 AM.

Peter Wolf   39:16
OK.

Lem   39:21
You would get a notification from.
Gmail.
On your own, let's say something like this. So me newsletter graph is ready on bevel.
Name of the newsletter graph is newsletter crated on June 17, 2025.
Then you can just go to the brevo and then check the campaigns and then you can see it by the title.
Then you can just check the content.

Peter Wolf   39:44
And did you have something where the the full content Lenny steward like with the intro with the articles?

Lem   39:52
For, yeah, for now, we actually don't have.
But basically we could pull it out from.
Like from the Breville now, because what we actually have here are HTML parts and HTML.
So we can't put this on Google sheet.
So what I can do here is we could pull the newsletter from Bravo and then put it on the our Google sheet so.
Let's say here we would add another Google sheet here which is the newsletters and then or like.

Peter Wolf   40:27
In a Google DOC or Apdf or something so you can see what it was like.
The full content that someone like the Google Sheets should be updated to say here was the newsletter, and you'd have apdf or a or a Google doc that would show you it all combined together and we'd have a URL.
I mean a, you know, a hyperlink.

Lem   40:48
For that, I think it.
Yeah, we can.
But yeah, we basically we would need to pull it also here on breville because we can't get it from this particular data because it's on like HTML and if I send this one to Google Docs it would output this particular HTML code.

Peter Wolf   41:04
Yep.
Yep, Yep, right.

Lem   41:07
So I think, yeah, we can get it here on.
Say.
Yeah, get an e-mail campaign.
And then.

Peter Wolf   41:21
Well, that's details about the campaign, not the actual image, no.

Lem   41:22
Yeah, yeah.
I think.
Yeah, I think so.
But.
Try if this.
I think it could.
Campaign ID. Alright, I don't have the campaign ID.
Let me just choose it.
So let me just test it out.

Peter Wolf   42:19
What was that you did where you grabbed that clock and put the clock on top of it?

Lem   42:24
Yeah, this is the trigger.
So as you can see, I can't.
We can't like activate this particular node for testing if we don't put the trigger on here.

Peter Wolf   42:33
OK, OK.

Lem   42:34
So yeah, so that's just.

Peter Wolf   42:35
So you're trying to activate it, so you could see what's available to use, what choices, what options, what characteristics, attributes.

Lem   42:40
Yes, that's right.
Yeah. If we can pull the data from this particular node.
So that's why I'm testing it out. So actually.
Yeah, we could only get the HTML content.

Peter Wolf   42:51
So, Brian, Brian, you see this stuff he's doing right now?
Right, this is the stuff you're gonna need that you should be working on when you guys are having the sessions, it's like.

Bryan Wolf   42:56
Yes. Yeah.
How to personalize your radio like this?

Peter Wolf   43:04
And not only personalizes how you understand what content goes in or comes out of what's available to you to manipulate right 'cause you saw he had he clicked on the brevo and it showed like 20 different inputs or outputs that you could that you could select right that.

Bryan Wolf   43:19
Yeah.

Peter Wolf   43:21
Are gonna give you certain amount of structured data or request structured data from you understanding how he goes about looking at.
A.
At a step which is ultimately the API and telling you what content, what kind of.
Actions it has and what content you can send or receive with those actions.

Lem   43:41
Yes, that's right.

Peter Wolf   43:41
Understanding how you can analyze a what do you call these points?
Lemme like Brevo right here.
You call this an action point or what do you call it?

Lem   43:48
Yeah.
Yeah, basically this is just an API endpoint.
So they have an API endpoint on get an e-mail campaign.
And then that's why I'm like checking.

Peter Wolf   44:00
So in when you're talking about a process flow and you have a step, what are all these steps called?

Lem   44:06
Yeah, it would depend.
Because like every node has different endpoints depending on the use case so.

Peter Wolf   44:11
OK.
So it depends on what its function is.

Lem   44:14
Yeah. So let's say other other node here doesn't have like a pretty limited API integration.
So what we can do there is we would need HTTP request right? So this one like the manual HTTP request.
So this is actually doing the same as this one.
But yeah, so most of the. Yeah. So actually this is.

Peter Wolf   44:36
OK.
OK.
I'm going off on a tangent.
I think I think it will be helpful and I don't know what the sessions you guys are having, but I think maybe because of my experience that I might know to ask you some of these questions that might help you explain things that will be beneficial to the.
Interns, right?
So I think maybe we should have a session where we just walk through these kind of process steps and I I can kind of guide certain aspects that they can then capture on the video so that they can.

Lem   44:57
Yep.

Peter Wolf   45:08
Understand, but I think a lot of this has to do with.
They're standing interfaces between systems and connections and all those kinds of things.
And so I think having my experience might help to bring the information out where they don't even know the right things to ask necessarily hold one second.

Lem   45:17
Yeah, that's right.

Peter Wolf   45:24
This is Peter.

Lem   45:24
Yeah, that's right.

Bryan Wolf   45:24
Yeah.

Lem   45:30
Yeah, actually that that's right.
Because yeah, that's why first, we knew we actually need time to scope a project.
Let's say we want to do something.
So the first step I what I do is I actually check the like the nodes on like make if that's like possible and then if it's not possible I will like check the API documentation. Let's say for because most of the platforms have an API documentation and then.

Bryan Wolf   45:51
Mm hmm.
Yeah.

Lem   46:02
Say.
The documentation.
So if it's not available here on like like the breville nodes right on the make, let's say it's not available here.
So I can check again on the Google Drive O API.

Bryan Wolf   46:18
Yeah.

Lem   46:18
Then I'll just read like read this.
There. Yeah, there documentation say API reference then yeah, I will just run through this and check if it's possible.
So that's how I do it.
And then it would be, yeah, better for you guys if you like.
Want to practice to like open the API documentations for for like other like platforms like most of the famous platforms that are being used and then so that you would be like familiar on this particular particular like setup.
So basically these are just like the gap gap API. So all of this that you can see here is actually the same as like this this particular node as you can see here.
So this is actually the.

Peter Wolf   47:07
So there's an equivalent for every one of those in the brevo system. There's an equivalent one of these kind of nodes that you can add to a process flow.

Lem   47:10
Same.
I.
Yeah. Well, that's the thing.
That's the thing here.
They actually don't put all of the like this particular because this is like pretty this list is long, very long.
So what they do is they actually put only limited endpoints here on the make and also like on Zapier.

Peter Wolf   47:29
Huh.

Lem   47:36
So they only put like limited amount of endpoints here. So they do, they just put the like the most used ones like.

Peter Wolf   47:44
OK.
And then what would happen if there was one? I wanted to use that wasn't on there.

Lem   47:45
At least all contacts, yeah.

Peter Wolf   47:48
I'd have to kind of make my own manual one.

Lem   47:51
Yeah, we would need to make our own like endpoint.
So that's why this is also very useful like the.
HTTP Make a request.
So basically this would, depending on the documentation of the particular platform, so they have different set up on like the authentications.
So mostly other others use like API key or let's say Auth 2.
So that's also another one.
So I think for bravo they use.
Yeah, API, they use the API key for the brevo.
So let's say I want to get something like this.
So send a transaction e-mail.
This is like sending a e-mail.
So what I will do is I'll just read this one and then depending on their like.
Required required request.
So for this one, they don't actually have a required request.
So we could just copy the post.
And then let's say here on the URL and then depending on this one. So this is a post request because we we are posting like an e-mail then the post and then let's check the.
The headers so the headers are this one and then.
They have the API key for header. Let me just check.
Uh.

Peter Wolf   49:22
You know what then? This is.

Lem   49:23
Yeah. So as you can see, this is, yeah.

Peter Wolf   49:25
Yeah, this is really good stuff and I think we definitely need to have sessions.
I think you know we got a few of these flows up.
I'm gonna certainly give you more flows to work on, but I think what we what should be happening is in these training sessions, these are the kinds of things that you'll need to drill into, right is is these nuances and that thing about the two pads and all.

Lem   49:43
Yeah.

Peter Wolf   49:46
That kind of stuff.
And that obviously wasn't there.
So that's me bringing my experience to the table.
But I think and it's going to be a challenge because I'm not going to have the time to do this. But I think we need to figure out a way that we we identify some of these deeper dives.
And and you know, we're still early in this, right?
I mean, these guys have only been doing this.

Lem   50:05
Yep.

Peter Wolf   50:06
Essentially, this is our third week, right?
We're only a couple days into our third week, so I don't expect they're going to pick all this stuff up.

Lem   50:09
Yeah.

Peter Wolf   50:12
So I think just even the flows that we have are going to start to build up and obviously should be giving them knowledge and they need to play around with them about, OK.
What if I go over here?
What if I go over there? The more complicated ones, where you're gonna have to do your own specialized call?

Lem   50:24
Yep.

Peter Wolf   50:27
Obviously that's probably going a little bit deep for them right now, but ultimately I do think it's important and the way you go about identifying what the what the API options are, right.
Is it a call?

Lem   50:39
Yep, that's right.

Peter Wolf   50:39
Is it a push?
Is it a pull?
What's a different?
What information can I get out and figuring out which ones are available?
Those are things that I think are very helpful that we'll definitely need to drill into, OK.

Lem   50:49
Yeah.
Yep, that's right.

Peter Wolf   50:51
So I'm sorry I sidetracked it, but I think these are important things.

Lem   50:55
Yeah.

Peter Wolf   50:56
Yeah. OK.
So they we can go back.
So you were then looking at the brevo and I this is me asking about how could we get an output right.
I mean the alternative is you could go back to that e-mail that's created.

Lem   51:05
Yeah.

Peter Wolf   51:10
And we could have a trigger in the e-mail that says when an e-mail comes in with the new newsletter, we send it to ourselves and that we would extract the content from the new from the newsletter and we create a PDF from that.

Lem   51:14
Yeah.
Yeah, that's right.
Yeah, actually we can actually do that also.
So yeah, but for this it would really depend on how the data is being processed.
So that's right.
And then we can do it like several ways, like, as you've said, we could do it something like that, like we could pull it actually.
To the e-mail, but we could also like one thing like we because on the like the Get e-mail campaign, the whole article is actually here.
So you can see it's just an HTML content, so we could actually feed this again to like an LLM.

Peter Wolf   51:52
OK.
Yep.

Lem   51:57
I'm like a cheap LLM and then we will just set put a task that it will remove all the HTML codes and then just put it on plain text and then send it to the document or like.

Peter Wolf   52:08
Yeah, but the only thing is I wanted to have. I wanted to be exactly what was sent.
Like if there's an image I want the image, if it was a you know a title underneath it. I want I wanted to look exactly like what was sent out.

Lem   52:17
Oh, I see. Yeah, yeah.
Yeah. So yeah, I think we can pulled it out on the e-mail. We could send it to ourself and then or just on like put it on another label or something. And then?
We could get the particular body of that e-mail and then, yeah, and turn it to like.

Peter Wolf   52:38
Yeah, because you're saying the output from brevo where you go Gmail it's brevo is pushing the information to Gmail or Gmail. The Gmail step is pulling the information from Brevo.

Lem   52:52
This one.
This e-mail.

Peter Wolf   52:53
Yeah, yeah.

Lem   52:55
Yeah, this this is just like a notification.
So this is actually just pulling the name.

Peter Wolf   52:59
Oh, that's the notification, OK.

Lem   53:01
Yeah, this is a notification, yeah.

Peter Wolf   53:02
It's that brevo is actually sending the e-mail out from its own system.
It's not going to Gmail and initiate it.
That's for you to say. Hey, it's done.
Here it is already created OK.

Lem   53:10
Yeah, that's right.
Yeah, yeah, yeah, that's correct. Yeah.
So this is just a notification.

Peter Wolf   53:13
Yeah.
All right.

Lem   53:16
And.

Peter Wolf   53:17
Well, I want to find somehow that we can get the actual content into a into a into a document right into some kind of document so that we have a reference for it and then to update it. So it would be a link in the spreadsheet.
Write in the spreadsheet which shows the newsletter and says well, here's the ten articles.

Lem   53:33
Umm.

Peter Wolf   53:36
They all have the same identifier for the newsletter.
They should also all have the same link to the to the actual example or the document that shows exactly what it looked like.

Lem   53:48
Yep.
Yeah, I think we can also pull it from Gmail, I think.
Or let's say I'll send it to.
Yeah, I I don't think we could.
Uh.

Peter Wolf   54:14
In Brevo, can you go look at it?

Lem   54:15
If.
Yeah. Actually we could look at the Inver, but it's actually on HTML, so.
If it is on drafts, we could actually we couldn't get the, but yeah, we could actually see the particular text here, but to import this one on like a Google doc or PDF I think.

Peter Wolf   54:40
Yeah, I really want to see it in the format.
Exactly the way it looks in an e-mail.

Lem   54:46
Yeah.

Peter Wolf   54:46
That's what. That's what I want to do.
I want to know how it looked to the user and where did the subject come from.
I don't.
It looked like we didn't populate a subject.

Lem   54:58
Yeah, the subject is I I just put it this one.

Peter Wolf   55:01
OK.

Lem   55:01
So actually the e-mail would look like this without the test.
So just the test newsletter for today and then we could like edit this subject line then yeah actually it would.

Peter Wolf   55:13
Can you have a variable in there too that says you know?
Serrala Treasury Services newsletter and put the date after it.

Lem   55:22
On the subject.
Yeah, we could do that here on brevo on the create e-mail. So as you can see, this is just the the subject is this one.
So I've added a static subject line which is test newsletter for today and then we could just edit this one however we want like.

Peter Wolf   55:42
Can you have a variable?

Lem   55:45
Variable with.

Peter Wolf   55:47
That would be the date if I wanted the date in the subject instead of just that.
I mean, obviously it's easier like that and static and it would say Sriracha services newsletter. What?

Lem   55:55
Yeah, we could actually add the date also.
So for the date, yeah, we could also add a date here.
So for the date.

Peter Wolf   56:04
Or like a sequential number, it's it's 'cause I'm looking here.

Lem   56:04
The variable for.

Peter Wolf   56:09
Hold on a second.
Let me just look at what.
Yeah, like, look here my screen here, I'll show you.

Lem   56:23
OK.

Peter Wolf   56:23
Share again.
I'm going back to the superhuman AI like, look, see how it has this up here?
It's like got a date, something that's unique, but here is what does it even have?
So that's odd, so file.
Huh.
That's weird.
I.
I mean, I I haven't looked at what their titles are, but looks like they pick some specific aspect.
Maybe whatever was the most important story here.

Lem   56:58
OK and use it as a subject line, right?

Peter Wolf   56:59
And yeah, it looks like I'm not sure, but I'm I'm OK with right now.

Lem   57:03
Yeah.

Peter Wolf   57:05
Then we'll just put, you know, serrala Treasury Services newsletter or something. But it would be good if it could say, you know, issue #1 issue, #2 issue #3 right each time we created one that it would incrementally.

Lem   57:09
Yep.

Peter Wolf   57:19
So next time we do one, OK, this is issue 57, right?

Lem   57:23
Oh, yeah. Yeah, that's right.

Peter Wolf   57:23
Something like that for now.
Not a big deal, right?
The foundation is the foundation is OK.
Umm.
Yeah.
OK, OK.
So stop sharing.
All right, so show me.

Lem   57:48
I could all.

Peter Wolf   57:49
So did you actually send yourself an e-mail of this?

Lem   57:52
Yeah, I actually sent.
So let me just the one that I've shown you is the one, this is actually the e-mail. So as you can see, this is on my inbox.
And then this is the particular e-mail.
So this is a test newsletter for the day.
The subject line then this is like today's insights. Then this is the first article.
This is the second article, and then the third article.

Peter Wolf   58:16
Yeah.

Lem   58:20
Is this so? This one doesn't have like the photo, so it's just coming from Unsplash and.

Peter Wolf   58:25
That's good.

Lem   58:26
The category is business, yeah.

Peter Wolf   58:26
No, that's good. That that I like that the image generator just builds a slot. OK.

Lem   58:30
Yeah. Then yeah, this is just three articles because I've added for testing purposes.

Peter Wolf   58:38
Awesome. OK, I I like it.
I'm impressed.
I mean a little tweaking I would do, but I think it. Yeah, that's that's really good stuff.
I would add, I mean we can take this insights the intro.
I would do the same thing for an exit, right?
And we could have the same kind of branch.

Lem   58:58
Offer exit, OK.

Peter Wolf   58:59
Can you go back to the path?
Back to the path again.

Lem   59:02
Here.

Peter Wolf   59:03
Yeah. So I really like it with the branches and the variable.
That's my preference and I really would probably go back and look at the other flows and see where this same kind of.

Lem   59:08
This one OK.

Peter Wolf   59:15
Mentality for me, like this branch mentality, where it's not really sequential to that task.
And I don't want it to be in just one long path.

Lem   59:21
OK.

Peter Wolf   59:23
I think it's also easier when you look at it just to understand what it's doing as opposed to its one long path, and you have a step that's 2020 steps to the right that's calling back for a piece of information. That's all the way from the left.

Lem   59:28
Yep.

Peter Wolf   59:36
Instead of understanding where it was really grabbing that information from right.

Lem   59:42
Yes, that's right.
ChatGPT.
Yeah, this is actually.
Yeah, more, more.
Understandable for that, because sometimes, yeah, it it the IT would get confusing for others if this is part. This is actually here.
Yeah. So they thought it's basing the.

Peter Wolf   1:00:01
Yeah.

Lem   1:00:05
The like the data from the past, like modules, but yeah.

Peter Wolf   1:00:07
Yep. So let's let's go back all the way to the beginning and show me again, because we you had a couple.
These are separate flows that ultimately tie together, right?

Lem   1:00:19
The this one.

Peter Wolf   1:00:20
Hey, hold one second. I'm sorry.
Give me one second.
I just realized I'm I'm late here.
Hold on.
See what time it is.
9/10/12.
OK.
Yeah. OK.

Lem   1:00:44
This one.

Peter Wolf   1:00:45
The trigger of a time start right now.

Lem   1:00:47
Yeah.

Peter Wolf   1:00:52
And you have it set up that right now it's doing this every it's triggering to to go get the articles and running through this whole entire process every day.

Lem   1:00:59
Every day.
Yeah, that's right.
Every 8:00 AM.

Peter Wolf   1:01:00
OK.

Lem   1:01:01
Then it will run automatically and then next is.

Peter Wolf   1:01:06
And did we have an edit step anywhere?

Lem   1:01:09
Edit step yeah, the edit step.

Peter Wolf   1:01:10
Edit yeah. So like when we got the content that was proposed by ChatGPT, I think we should have an edit step.

Lem   1:01:16
Yep.
Yeah, we could.
The edit step actually is here on the like the campaigns. Yeah, on bravo.

Peter Wolf   1:01:23
On brevo.

Lem   1:01:25
So this is actually just a draft and we would need to like like send this.

Peter Wolf   1:01:28
OK.
So you go in brevo.
You can edit it in brevo and then you say you're done and you trigger it.

Lem   1:01:33
Yeah. Yes, that's right.
So we could actually edit it here on the edit design and then it would only get quite confusing at first because this is actually like HTML code. As you can see.

Peter Wolf   1:01:35
OK.

Lem   1:01:45
But basically it would be here on like as you can see like the pattern HERE is H2 for the particular headers so.

Peter Wolf   1:01:54
Yeah, that is, that is ugly.
Is there somewhere we can edit it before we send it to brevo?

Lem   1:01:56
This.
Yeah, there.

Peter Wolf   1:02:00
So what we had when we had the output from Chachi, BT when you aggregated it again you aggregated an HTML, right?

Lem   1:02:01
Uh.
Yeah, that's right on HTML, but Yep.

Peter Wolf   1:02:12
But could we aggregate it first and put it out as a as a word doc that we edit and then we feed it back in and it converts it to the HTML?

Lem   1:02:22
Yeah, we could actually do that, but we would have like 2 flows for that one and yeah, it won't be like one flow, but yeah, basically I would just.

Peter Wolf   1:02:27
Yeah, yeah.
Yeah, but I'd say it makes sense again for me.
Like down the bottom, let's let's assume that middle down the bottom is gonna be our flow.

Lem   1:02:34
Change.

Peter Wolf   1:02:39
I want it with the extra branch, right?

Lem   1:02:40
OK.

Peter Wolf   1:02:41
So now we're saying that that if you get over to that second Cha Cha BT output, it's really the aggregator on the on the right, right?

Lem   1:02:42
OK.

Peter Wolf   1:02:51
You're feeding out from the second Cha Chi BT.

Lem   1:02:55
Yeah, this one, this one, this one.

Peter Wolf   1:02:55
Right after your image.
Nope, Nope. Down that one, right?
So.
Hold on.
Yeah, 'cause, you're converting it all to HTML.
So if here if we if we fed the content out.

Lem   1:03:12
Yeah, this actually.

Peter Wolf   1:03:20
From that you could feed that into a document on a separate path.
Now then, if you edit it, you wanted to go back in, right?

Lem   1:03:33
Yeah, that's right.

Peter Wolf   1:03:33
So it's it's, it's it really is to me, it's.
The aggregator is necessary for the pool together.
Could you aggregate it and just put it to a document?
Instead of aggregating and putting it to HTML.

Lem   1:03:50
Yeah, we I would change this.
Particular formatting and just feed it the like the image URL and also like the text.
Because for this process I've added it so that it would be sent already to automatically to bravo, but we could actually set it for set this formatting up, which is just a plain text and then you are.
And then the plaintext and then.
We would put it all on a Google doc.
And then we would need another flow for pulling it out again.
And then sending it to the Brevo e-mail campaign.
So basically it would be too flow.
So first flow is just getting the like the contents into.
Into like the Google Docs to edit.
And then the next flow would be getting from the Google Doc on this based on the spreadsheet also and getting the Google Doc and then we would feed all that particular content to ChatGPT to create an HTML format for for Brevo e-mail. So that that's how I.
Would think and how?
Yeah, how I would do it.

Peter Wolf   1:05:09
It is is cheap PT.
Chachi PT isn't giving it out in HTML format, is it?
You're you're doing that in the aggregator, right?

Lem   1:05:16
Yeah.
No, this is actually on ChatGPT.
So as you can see on the prompt ChatGPT is actually giving it on us on HTML.
Here. So the final output should be HTML format.

Peter Wolf   1:05:34
It's good here.

Lem   1:05:34
Then yeah, the content should.
The content should be two to three paragraphs.
Limit the content to 30.
So yeah, the the output for this one is actually on HTML and then it's just a simple HTML like the.

Peter Wolf   1:05:48
Yeah.

Lem   1:05:49
Paragraphs and then the header.
So it's just adding adding like.

Peter Wolf   1:05:51
Yeah, sure.
I have no idea, but right now I'm in the normal call, OK.

Lem   1:05:55
Like this?

Peter Wolf   1:05:57
Alright, bye.
Sorry guys.

Lem   1:05:59
Like.

Peter Wolf   1:06:00
Go ahead. So it is coming out as HTML from the you already have it coming out of HTML format from from ChatGPT.

Lem   1:06:02
Yep.
From Jati pedia. The yes, that's right, yeah.
And so if we would do that, I would change the prompt and just output it on plaintext and then aggregate it also on plaintext, and then we would feed all the data like the insights and also the content into Google Doc and then update the spreadsheet so we.
Would need another spreadsheet here, which is like the news article.
For edited for editing, and then we together with the Google DOC link.
And then also like title and like the Google Doc URL link and then so that we can like edit it first or check the data before and then if we click yes the same as on the like the link in post another another flow would catch that one.
And then it will get the all the content and then feed it to ChatGPT to put it on.
Format just for the Brevo e-mail so that the formatting would be something like this.
Because if we would feed the.
Text like plain text on bevel it, it would, yeah, yeah.

Peter Wolf   1:07:15
Yeah, it doesn't know how to handle.
I just didn't know if you were the one formatting it or if you made it clear it's coming out of.
You've already said for it to come out in HTML format.

Lem   1:07:25
Yeah, that's right.
Yeah, I've I've formatted it on the prompt that it would output the prompt in HTML format. Yeah, that's right.

Peter Wolf   1:07:35
Right. But so you could just as easily have it not produce that output in HTML format, right?

Lem   1:07:35
So.
Yeah, just text.

Peter Wolf   1:07:40
It could produce one version, produce a version that's not HTML format. That's the version we edit, and when we edit it goes back and then it wants to feeds it back into ChatGPT and tends to put it into the HTML format, right?
Or what?

Lem   1:07:57
On.

Peter Wolf   1:07:57
How do you think would be the best way if I wanted to be able to read that blurb and and and potentially edit it?

Lem   1:08:00
And like to.
To really.
Yeah, for because I can't.
We cannot put like 2 results here and then we have two like 2 result here because it would be aggregated right?
So it would get.
It would be also put here on the on the aggregator module.
So yeah, that's how I would let me just basically let's say.
For this one, we would I would like cut this one right.
So that I can explain it.
And then let's say.
I would edit this particular.
Prompt and then just put it as plain text.
So this is actually also outputting.
HTML format.
So.
Yeah, this one is.
Yeah, outputting also an HTML format, so I would like delete that one and then output also as text and then for the subsections I will just put here like the link and the URL link and then the website URL and also the like the subsection that is created.

Peter Wolf   1:09:17
What? What about?

Lem   1:09:18
As text.

Peter Wolf   1:09:19
I'm sorry. What about?
Because I'm trying to.
I mean, clearly this gets very confusing.
What about at the very end when you send it from the OR when breva go breva goes back and pulls the information, right?
And it's now grabbing the intro and the variable right.
He's got the intro variable and it's got the body content.
Couldn't we just take that?

Lem   1:09:40
In in HTML.

Peter Wolf   1:09:42
Couldn't we just take that HTML format and say?

Lem   1:09:47
Send it to ChatGPT, yeah.

Peter Wolf   1:09:48
Yes, Senator Cha BD to take the HTML format out and then.

Lem   1:09:50
Yeah, that's right.
Yeah, we can actually do that one. Yeah, that's.

Peter Wolf   1:09:55
And then and then if I end it, it goes back to Breva and says OK no update this or no.

Lem   1:10:01
No, for that one, no.

Peter Wolf   1:10:02
I just think that ending in forever when it's in HTML format is really not attractive, right?
I mean having to find the tag, the right tag to go to, to edit each body content and not really seeing it in the. You know, I just think it's a little bit.
It's very at the very least it's awkward and not user friendly.

Lem   1:10:24
Yeah.
For the yeah, basically because if we would need to edit this one, it would end there.
We can't go back.
There's actually no. Like, it can't pause and like, wait for an input if you're if you're yeah.

Peter Wolf   1:10:40
OK.
So then hold on. How about this?
Right now is going back to, it's looking at two spots, right?
It's looking at the aggregator and it's looking at the variable, right?

Lem   1:10:52
Yeah. Yeah, that's right.

Peter Wolf   1:10:53
Forever is calling from those two points. If we didn't have breva there and instead we had a a ChatGPT point that said grab the variable and grab the the output that you have in HTTP and convert it to normal text.

Lem   1:11:09
OK.
Yep.

Peter Wolf   1:11:11
And then and then put that into a into a Word document.

Lem   1:11:16
OK.

Peter Wolf   1:11:17
That could be edited, and then then we would have.
Then we would compete it if it was edited, it would feedback to.
To ChatGPT, to put it back in the HTML format.
And then Breva would call it from that step.
So Breva would no longer call directly from the intro variable, and the and the aggregator we'd have we'd have instead of breva being there at the create e-mail campaign, that step would be another ChatGPT.

Lem   1:11:38
Yeah.

Peter Wolf   1:11:52
And it's calling the intro variable and the aggregator and saying give me the information you have in HTML, convert it from HTML to to text, put it into a Google doc for editing, then when the person edits the Google Doc.

Lem   1:12:10
OK.

Peter Wolf   1:12:11
It calls back to ChatGPT again and says convert this back into HTML and then breva calls it from that instead of calling it from the aggregator and the intro variable.

Lem   1:12:23
Yeah, this.
Yeah, but we can't do that here on the same flow because we would need to have another one for the like the other input, like the Google Doc waiting for the edit.
So basically how I would design that one is the same?

Peter Wolf   1:12:39
Well, hold on, hold on. Before you do that, let me just let me just talk it through here a second. Right now, like you have, you have a path that you can you can go off and then come back to right.

Lem   1:12:44
OK.

Peter Wolf   1:12:51
We just saw that with the introduction variable.

Lem   1:12:53
OK.

Peter Wolf   1:12:53
So right now, instead of having breva as the next step.

Lem   1:13:00
OK.

Peter Wolf   1:13:00
You could have let me just think about this a second. Instead of breva there you would have ChatGPT.
And chat, GBD would say, give me the introduction, but it's calling the same things that breva is right now says give me the introduction variable and give me the subsection variable.

Lem   1:13:07
OK.

Peter Wolf   1:13:17
Right. And then it and then it and then it produces an A document, a Google Doc and the Google Doc then is is given to us, you know, put on the drive for someone to edit. And when they edit that triggers it to.

Lem   1:13:18
Yep.
OK.

Peter Wolf   1:13:37
To then to then call back to chat, GBD and ChatGPT creates the new output that would have been introduction variable and the and the and the aggregator variable, and then breva calls that.

Lem   1:13:53
Yeah.
Yeah, yeah, that's actually the same as, but it would be not connected here on this particular flow because.
We we won't have the access for that document that is edited and then like let's say, let me just explain it. Let's say this triggered then it processes right? Then it goes through here and then it puts it all on a Google Doc.
Let's say there's a Google doc here.

Peter Wolf   1:14:21
Yeah, yeah.
So you're if the if if we have to wait for some kind of step, then it has to be a whole separate flow, a different flow that needs to trigger.

Lem   1:14:26
Created.
Yeah, that's right.

Peter Wolf   1:14:33
Can you put them on the same sheet like this or do they have to be in a whole different sheet?

Lem   1:14:34
Yeah, because.

Peter Wolf   1:14:37
Like can I still see them even though they don't connect together?
I don't mean like that.
Kind of sheet, I mean on the screen like a make screen.
You see how you have now right now three different things that are disconnected.
You have your original, which was a single path.
You have the change one which is A2 path.
And you have this breva thing at the bottom right now.

Lem   1:14:55
OK.

Peter Wolf   1:14:57
They're all in one make sheet.
I don't know what you call this one.
Make a screen.

Lem   1:15:01
OK.
Yep.

Peter Wolf   1:15:04
Can you have them, even though they're not tied together?
Have them in one screen like that so you know OK.
I might not call this directly, but I don't have to go to another screen to say there's a different workflow. I know this flow with the breva is associated with the ones above.

Lem   1:15:21
Yeah, we could actually do that and just change the trigger so that it would start.
The other one is that how you?

Peter Wolf   1:15:31
Yeah, the trigger here would be someone and the Google Doc and said it's ready and then that would call the the create campaign or that would call the that would call ChatGPT and ChatGPT would turn it back into HTML and that would then be would come.
After that.

Lem   1:15:53
Well, yeah, let me just.
Like, yeah, actually we could do that. Let's see.
Add another flow here like.
To send to to bravo from Google Doc and ChatGPT.
But basically you would.
Yeah, it would need to like manually.
Like put the trigger there to access.

Peter Wolf   1:16:17
Why can't the trigger be the the the the that when I execute from the edit Google Doc that recognizes it's ready and it calls Cha Cha BT calls Meg and then sends it to Chachi BT?
Isn't that the trigger? When I when I save the Google Doc edits or say it's ready.

Lem   1:16:37
No, it it can't be.
I can't trigger like that if it's already here. So we we would need like another.

Peter Wolf   1:16:44
You would have to create a whole separate flow somewhere else.

Lem   1:16:47
Yeah, that's right.
Yeah, the the same with the LinkedIn post.
So we would need to have.

Peter Wolf   1:16:52
And see that makes me uncomfortable.
Is that I have these component pieces but there's nowhere showing me.
They all go together.
Where do you actually tie them all together?

Lem   1:17:03
On the spreadsheet.

Peter Wolf   1:17:03
I mean I in a spreadsheet.

Lem   1:17:06
So.
Like.
Basically what I would do if.
Yeah, the trigger for that would be on the spreadsheet or like.

Peter Wolf   1:17:22
Right. But I meant when I look at it and make and I'm trying to understand that there are multiple sub flows to go together.

Lem   1:17:22
Because.
OK.

Peter Wolf   1:17:29
Isn't there somewhere where I can say all these flows are in one ultimate process?
But they have.
They have a process flow, then they stop, wait for another trigger, then another process flow kicks off and it stops and another trigger.
But they're really all associated with one big flow.

Lem   1:17:48
Like a multiple.
Do you mean like multiple flows here on the same sheet?

Peter Wolf   1:17:51
Yeah, yeah.
So that I would know.

Lem   1:17:53
No, no.

Peter Wolf   1:17:53
Like right now you're telling me Breva would have to be triggered separately?
And I'm saying, well, I'd like it on the same sheet here, so I can see it because I know then they're associated with one another.

Lem   1:18:05
Yeah, we can do the like different flows on one like sheet or one like yeah module.

Peter Wolf   1:18:10
Cannot. You cannot, you're saying.

Lem   1:18:12
Yeah, we I can.
We I just copied this one because I've added.

Bryan Wolf   1:18:13
No.

Lem   1:18:17
I just like edited that. That's that's why.

Peter Wolf   1:18:18
Yeah, I understand.

Lem   1:18:19
Yeah, but basically.

Peter Wolf   1:18:20
So you're just playing around with it, but but ultimately then I would just have to manually somewhere else in some documents say these three flows are tied together even though or maybe I'd name them, you know, newsletters newsletter process one newsletter process, two newsletter process three and they.

Lem   1:18:33
Yep.
Yeah, that's right here.

Peter Wolf   1:18:40
All three really together create the output.

Lem   1:18:42
He.
Yes, that's right.
So basically I I like I do it here on make like create a folder and then I create that particular system flows for that particular system on just one folder so.

Peter Wolf   1:18:51
Yeah.
OK.
So 1 folder could have multiple different. Again, what do you call this sheet?

Lem   1:19:00
For.
Yeah.

Peter Wolf   1:19:02
What do you call one sheet where you have a process flow?
In make.

Lem   1:19:07
Like this particular system?

Bryan Wolf   1:19:10
Scenario.

Lem   1:19:10
So they have like diagram scenario, yeah.

Peter Wolf   1:19:13
OK.
So it's called a scenario or it's called a. It's called a scenario. OK.

Lem   1:19:14
Like I said, yeah.
So they have yeah scenarios like.

Peter Wolf   1:19:18
So in each one you'd have one scenario, but you could have multiple scenarios that link together. You just don't see they link together, but we put them into a folder saying. This is newsletter scenario, one newsletter scenario, two newsletter scenario three and their sequential, but they have their.
Own triggers at different points, but ultimately they all tied together as one big process flow.

Lem   1:19:41
Yes. Yeah, that's right. That's right.

Bryan Wolf   1:19:43
Well, that's what the LinkedIn process flow was.

Lem   1:19:44
But it would.

Bryan Wolf   1:19:44
The LinkedIn process flow was was just.

Peter Wolf   1:19:46
Yeah. No, I know.
You showed me they were separate steps, but I this is what I'm saying. It makes me uncomfortable that they're they're totally separate.

Bryan Wolf   1:19:51
Right, right, right, right, right.

Peter Wolf   1:19:53
You just you have to.
You have to know they go together.
There's nothing that shows you that they really go together.

Bryan Wolf   1:19:57
Mm hmm.
Yeah.

Peter Wolf   1:20:01
Is there some kind of document you could put here or like something like on the screen that would be an informational kind of note box that it would say hey this is process one it calls process two scenario and then that calls process three or something.

Lem   1:20:01
Yeah.
Of yeah for me.
Yeah, we could actually put the notes here, but I don't think we could, like put it on the.

Peter Wolf   1:20:24
You can't see it on the screen OK, but like, what about the end step?

Lem   1:20:26
Yeah.

Peter Wolf   1:20:29
What about after the last step?

Lem   1:20:29
But on the description, we could actually hear on the description.

Peter Wolf   1:20:32
Yeah. Again, that we, we do it a newsletter scenario, one newsletter process, one process, two process 3, right.

Lem   1:20:53
OK.

Peter Wolf   1:20:54
Can we put a note at the end that says this calls to process flow step #2?

Lem   1:21:02
Yeah, we could actually do that one like it's the webhook like.
So because.

Peter Wolf   1:21:10
Oh, can we redo to our own?

Lem   1:21:12
Yeah, we could do Web hook to our own scenarios also in make.

Peter Wolf   1:21:15
That would do it for me. Then that's what I'm looking for. Is that web hook that says, oh, now I'm gonna call process flow #2.

Lem   1:21:20
Yeah.

Peter Wolf   1:21:23
Not that they're totally separate.
This shows they tied together and then I would go to process and the web hook would call process two and then in process two I'd have a web hook that says to process 3, right?

Lem   1:21:35
Yeah. Yeah, that's right. We could actually.

Peter Wolf   1:21:36
That's what I need.
That's what I need Len for it to make sense to me.

Lem   1:21:39
Yep.
Yep.

Peter Wolf   1:21:44
OK.

Lem   1:21:44
So.

Peter Wolf   1:21:44
So what I would like to do is I would like the output from that that goes to HTML.
Maybe. Maybe it shouldn't. Even we've already written to go to HTML.
That's the only thing, right?
Instead of unwinding that.

Lem   1:21:58
But the yeah, it's because it's just very easy to like because there's only like the final output is HTML here.
But yeah, I could just remove this one and then it would just.
Yeah, this one.
She can see final output should be in HTML.

Peter Wolf   1:22:14
Yeah. OK.
So maybe you just don't do that there and you say give me the output is text and now you you go to that variable and the aggregator and you say pull these together and create a Google Doc, then the Google Doc gets saved and then when we're done.

Lem   1:22:16
Yeah.
Yeah, that's right, if I yeah.
Yep.

Peter Wolf   1:22:30
The Google Doc and we do something like click the button ready after we edit it we trigger it. Then it calls back and it says OK now send it to ChatGPT and structure it in HTML.

Lem   1:22:36
Yep.
Yeah, the.
Yeah, that's right.

Peter Wolf   1:22:42
And then breva calls it from from there.

Lem   1:22:45
Yep, Yep, that's correct.

Peter Wolf   1:22:47
OK. Can we do that change?

Lem   1:22:49
Yeah, we can do that.
Do that change actually?

Peter Wolf   1:22:50
Awesome. OK, I need to get off. But I mean, Brian, I think you should definitely stay on work through some of these things with Lem. Any other questions you have from the other ones and and again, in case there's any problems that original flow, Brian, I need that.

Bryan Wolf   1:22:57
Yeah.

Peter Wolf   1:23:07
Set up for my account, right?

Bryan Wolf   1:23:08
The name test 1.

Peter Wolf   1:23:08
So if you have any questions or issues on that one.

Bryan Wolf   1:23:12
Yeah.

Peter Wolf   1:23:13
OK, OK. Awesome. Let him. Great job. Let him.

Lem   1:23:14
OK.

Peter Wolf   1:23:16
I'll prep up the next flow and and send it to you.
Tonight. So you'll in the morning.

Lem   1:23:22
OK.
No problem.

Peter Wolf   1:23:23
OK.
Awesome. Thanks.
I'll talk to you guys. See you.

Bryan Wolf   1:23:26
See you.

Lem   1:23:27
OK, talk to you soon.
Let's go on this one.
So have you have you imported the?
Oh, I would need to add it this one right.

Bryan Wolf   1:23:56
Yeah. So this one.

Lem   1:23:57
So you would need to the new Jason blueprint for this one.

Bryan Wolf   1:24:01
I just yes, I think.
I got to take.
I got to hop off for like 5 seconds. Lynn, if you want. If you want to like work on this, I'll be back in a in a couple minutes, alright?

Lem   1:24:10
OK.
No problem.
OK.
Oh.
Oops.
Why?
Production.
Lakshadweep.

Bryan Wolf   1:32:39
Glen.

Lem   1:32:43
Hi there.

Bryan Wolf   1:32:44
All right, I'm back.
I'm sorry, I had some **** I had to bang out really quick. OK, so for that entire call, I really fought a long, whole way and I I tried to keep up with the flow and the changes that we made to it.

Lem   1:32:46
OK.
No problem.

Bryan Wolf   1:32:57
I I also you know.
Tried to make an account for.

Lem   1:33:03
Yes.

Bryan Wolf   1:33:04
Rebel and.
What is this one called?
Up, up, up, Slash but up slash. I think I'm gonna have to figure out. Where do I find my the client ID on this website.

Lem   1:33:19
Yeah, ada.
Yeah, it's on splashdownsplash 1.

Bryan Wolf   1:33:23
Yeah.

Lem   1:33:24
It's yeah.
So yeah, you would need to create a developer account and then.

Bryan Wolf   1:33:30
So I've got one.
I've got one.
I got an account right here.

Lem   1:33:34
OK.
Then.

Bryan Wolf   1:33:39
Do I have to get a?

Lem   1:33:39
How can I?

Bryan Wolf   1:33:40
Do I have to get a premium version or no?

Lem   1:33:41
No, no, no need.
But you need to.
You would need to create an app, so can you see the?

Bryan Wolf   1:33:49
Set submit an image.

Lem   1:33:52
No, ponder the can you?

Bryan Wolf   1:33:52
Hey, you know what? OK. So for this process flow.

Lem   1:33:56
OK.

Bryan Wolf   1:33:56
Did you fix everything that Pete was talking about or or do you think by tomorrow morning we'll OK, so that's OK. So I I think with this with this process flow, we should just wait till tomorrow till you have all the kinks ironed out and and and fix.

Lem   1:34:00
Yeah, I'm still. Yeah, because.
OK.

Bryan Wolf   1:34:10
Everything that that P just said he wanted to change, I think that'd be better that way. I can just import the Jason.

Lem   1:34:13
OK.

Bryan Wolf   1:34:15
It'll be easier.
Here for both of us. OK. But So what? I do need to do is so I'm just gonna. I'm gonna save this so I can't even save it anyway.

Lem   1:34:17
Yeah. Yeah, that's right.

Bryan Wolf   1:34:26
So I'm just gonna. I'll just wait till tomorrow, OK, so.
What I do need to do though?
Is. Do you remember the the the name test 1?
The first one we did.

Lem   1:34:41
The name name test.

Bryan Wolf   1:34:42
Yeah, yeah.
Do you remember this one?

Lem   1:34:49
Yeah, the the label, OK.
The OK, the.

Bryan Wolf   1:34:54
So I want to make sure that I have this right.

Lem   1:34:59
Yeah, the perplexity and then.

Bryan Wolf   1:35:06
Make sure I have this right.
Go to.
So now was it for this document?
So listen, I have to put all this, all the stuff we know.
I don't my account got switched over to Peter's account. So like all this stuff here, which is not gonna be hard, but because I remember what to do for the LinkedIn one. But the name test.

Lem   1:35:26
OK.

Bryan Wolf   1:35:30
I kinda forget so.
Was it for this one?
Like was this.
What was this?
The Google sheet that went with it or was it a different one? I have to make a new one.

Lem   1:35:41
Yeah, I think.

Bryan Wolf   1:35:42
Or is this my own?

Lem   1:35:44
Because.
Would actually put it on.
A.
A spreadsheet which is you would need to create your own spreadsheet for this one.

Bryan Wolf   1:35:56
Go ahead.

Lem   1:35:57
And then I can actually just send you the. Let me just.

Bryan Wolf   1:36:00
That would be so easy.
Love you. Don't worry.

Lem   1:36:02
Get the like the format for this.
I think it was the content system.

Bryan Wolf   1:36:06
Say sure.
I see.

Lem   1:36:13
Just go to my window drive.

Bryan Wolf   1:36:15
Yeah.
Yeah, this is all done.
OK.

Lem   1:36:44
Yeah, I think this one is the database.
It's. Oh, it's actually just simple.
It's like, I think, yeah, three. There are only three.
Headers for this one.
Website URL title and 30 word summary.

Bryan Wolf   1:37:01
No.

Lem   1:37:03
Oh yeah, so.

Bryan Wolf   1:37:04
Are you share with me or is it SharePoint?

Lem   1:37:07
Yep, website.
Your we could also check it on.
Yeah, website URL, title of article and then also thirty word summary of the article.

Bryan Wolf   1:37:19
Oh, I think I have this.
Uh.

Lem   1:37:25
You could also check the baby. There's already a spreadsheet that is assigned to that particular flow.
So I don't.

Bryan Wolf   1:37:34
Yeah, so I think.

Lem   1:37:37
Yeah, I think this one database research because the one the other one is linking posting.

Bryan Wolf   1:37:42
Yes.

Lem   1:37:42
Yeah, this one.

Bryan Wolf   1:37:44
Oh no, this is this is.

Lem   1:37:44
Oh, this, this is mine.
Yeah, I think this is mine.
This is I shared it via link so that's why.

Bryan Wolf   1:37:50
Yeah, yeah, yeah. OK. OK.

Lem   1:37:52
But you can actually also like edit this one.

Bryan Wolf   1:37:57
But so this is OK.
OK. OK. OK.

Lem   1:38:00
Yeah, I think this is also connected to that particular.

Bryan Wolf   1:38:03
So now I wonder, with these, with the sheets that you like this, you know, like this is yours up here?

Lem   1:38:04
To that flow.
Yep.

Bryan Wolf   1:38:09
If you deleted this, would I still have access to it or no?

Lem   1:38:13
No, it would.
You won't have the access if I like deleted the the sheet.

Bryan Wolf   1:38:21
That's not good, can I?

Lem   1:38:22
Yes.

Bryan Wolf   1:38:22
Can I shave it to my own, make a copy?

Lem   1:38:24
You could just, yeah, just copy the formatting.
So it's just simple like 3 like website URL or.

Bryan Wolf   1:38:33
Oh ****. Oh.

Lem   1:38:37
Think you can just put it on your like drive?
Yeah, this one.
My drive? Yeah, make a copy.
Then you need to map.

Bryan Wolf   1:38:45
I wonder are there are the rest of the?
Yeah, yeah, I need to map it on.

Lem   1:38:48
Yeah, you need to map this one on the.

Bryan Wolf   1:38:51
Make.
On here. OK, hold on one second.
Let me just see, I wonder any of these other ones.
Yours too.
No.
I'll just keep that.
This one's mine, right?

Lem   1:39:12
Yeah, that's that's yours.

Bryan Wolf   1:39:14
OK.
So I can just send that it is OK alright.
Alright, so you should map it. I think I've already got it like.
Like you're saying like that. I gotta change it.

Lem   1:39:35
Yeah, that one the copy.
Yeah, the copy one.
Then yeah, I think it's the same one.

Bryan Wolf   1:39:51
In a map it on here which is route here now.
Because I need to see copy.

Lem   1:39:56
Nope, I think there's no need to.

Bryan Wolf   1:39:58
That's it.

Lem   1:40:00
But I think that's it and all is very good perplexity and chat GP.

Bryan Wolf   1:40:01
All right, so.
I think I'm already logged in on all this stuff.

Lem   1:40:08
Yeah. And then I this is like the research label.
So yeah, you will need to e-mail yourself a link for the with the label. Research on the subject line.

Bryan Wolf   1:40:19
Where? OK, hold on.
So let's start.
Let's let's start with. Yeah. Can I open up?

Lem   1:40:21
Can you op?
Yeah. Can you open the Gmail?
What is it?
The research lab in the Oh yeah, the subject is research.
Yeah, that's right.

Bryan Wolf   1:40:31
Yeah, that's just go one by one, OK.
So this is good.
This is all good, right?
Or do I have to change this? No, it's good.

Lem   1:40:49
No, I no need. Yeah, that's the.

Bryan Wolf   1:40:52
I think I probably don't need to change much.

Lem   1:40:56
This I think this is a really good just a sheet and the credentials for the perplexity and ChatGPT.

Bryan Wolf   1:41:04
I think I'm. I got them already on here, yeah.

Lem   1:41:08
Yeah, I'm sorry I didn't get.
And.

Bryan Wolf   1:41:11
So now if I run this, it'll work right?

Lem   1:41:13
Yeah, I think so.
I think it would.
Then it will yeah, populate.

Bryan Wolf   1:41:19
Accounts.

Lem   1:41:22
That.
Oh, do you have a link?
You should also send an e-mail to your inbox that is linked here so that it will trigger that particular.

Bryan Wolf   1:41:37
It's research, right?

Lem   1:41:37
Yeah. So it's yeah, you need to type research on the subject line and then just the link on for the body, just the link.

Bryan Wolf   1:41:38
I have to type in research or something.
Now what link are you talking about?

Lem   1:41:55
The like the article link.

Bryan Wolf   1:41:55
Like any link.

Lem   1:41:56
Yeah, any link the any article link that it would process. So because I think this is just getting the.
Uh.
The perplexity is researching the article and then creating like a 30 word summary. That's just like that.

Bryan Wolf   1:42:12
OK.
So let's just say this article.

Lem   1:42:17
Step one then.
Yeah. e-mail that one. OK.

Bryan Wolf   1:42:23
Now, now I trigger right.

Lem   1:42:25
Yeah. And then, Yep, you can now trigger trigger it.
Oh.
So can you open the?
Oh, the credits is.

Bryan Wolf   1:42:39
OK.

Lem   1:42:41
I think this are different account.

Bryan Wolf   1:42:44
Yeah. So here's the thing.
Is that so?
You do.
You see how many I have and where is it all the same?

Lem   1:42:49
Yeah.
That's.
No, this this actually like different ones depending on the API key that you've put.
So the the the good habit here is when you add a connection you would name it.
Let's say you add click add.
So you can actually this one.
Yeah, yeah, you can actually change the connection name.
Yeah, that one.
And then so that it's not, it won't be like confusing. So it's a good.
Yeah. So if because me. Yeah, maybe the other. Like other connections there are for different account or like the API key is already deleted because we could actually like delete an API key and yeah it won't work for that connection.

Bryan Wolf   1:43:19
Yeah, I should have done that a while ago, huh?
Yeah, let me just find API here.
You don't.
Yeah. OK, alright. I gotta do that with all of them, right? Yeah.

Lem   1:44:30
Yeah, all of the ChatGPT maybe needs to.
Update.

Bryan Wolf   1:45:35
OK.
Is it done? That's quick.

Lem   1:45:47
Oh, it didn't choose where to start, OK?
Click that one and then just you can actually click the yes.
Select the first e-mail.
Then save.
Yeah, I think the I think the first one you can.
Yeah, that one.
I think that's for today, right?
Yeah, that's for the day. Yeah. OK.

Bryan Wolf   1:46:13
Yeah.
Do I have to do that every time?

Lem   1:46:19
Yeah, but actually if you turn this particular automation on, it would only work for the new emails.
So for this one, we are actually like triggering it manually.
That's why it's happening like that.
But if you would turn this on, so basically it would like check for the new emails that are not still processed.

Bryan Wolf   1:46:42
Right. OK.

Lem   1:46:43
Yeah, I mean, what I mean is.
Yeah, I see.
Yeah, because we could actually, like turn this on.
It will trigger it.
I mean it will run for like yeah automatically every depending on the trigger like every 15 minutes or every 16.

Bryan Wolf   1:46:57
Automatically. Yeah, yeah.
How much I want to use it.
Yeah. OK.

Lem   1:47:05
So yeah, we can check the spreadsheet and yeah so it.

Bryan Wolf   1:47:09
OK.
Yeah. Can I get this to not be black?

Lem   1:47:10
Yeah, that's the.
Yeah. Actually what I do here is I just add a text on the 2nd row because it's actually copying the formatting.

Bryan Wolf   1:47:20
OK, OK.

Lem   1:47:22
ING on the 1st row like the headers, so you can actually like delete the.

Bryan Wolf   1:47:30
Like this?

Lem   1:47:31
Hello just delete first the like the. Yeah. Yeah the you can delete the whole thing and then.

Bryan Wolf   1:47:35
Whole thing.

Lem   1:47:41
Oh, there's still.
Can you like delete the row just?
Yeah, the particular row and then.

Bryan Wolf   1:47:50
How do I do that?
I I'm not very good with this.

Lem   1:47:51
Yeah, that one. Just remove remove the.
Delete row.
Yeah, that one, yeah.
And then just put like word there like test or something.
Yeah, because so that it won't copy the formatting.
On the headers.

Bryan Wolf   1:48:06
Yeah.

Lem   1:48:07
Then Yep, you could actually trigger it again manually.
And then.
You can click that one again.
The bubble.
Because it needs, yeah, it needs context on that. And then select the first e-mail.
Then just click the one that you that one.

Bryan Wolf   1:48:30
So now if I sent like 10 emails to myself, it said research I would I have to select all 10?
Or you're saying, like if we go back and I just have it on, like it'll do it on Mac. Yeah. OK.

Lem   1:48:36
If you.
Yeah. Yeah, that's right.
So yeah, that's right. If you turn it on and then let's say it is on like every 15 minutes, right?
So if you send yourself like 10 links, it will actually process it automatically after like 15 minutes because this the trigger is.
Can you click the clock?
The trigger on the? Yeah, this one so.
Yeah, you can actually put it also on like one like every minute it will trigger and yeah to.

Bryan Wolf   1:49:04
OK.
Yeah.
OK.

Lem   1:49:11
So that but basically it's.

Bryan Wolf   1:49:12
Alright, so I got that.

Lem   1:49:13
It will trigger every 15 minutes and then get all the.

Bryan Wolf   1:49:15
All right.

Lem   1:49:18
New e-mail that has the subject line research.

Bryan Wolf   1:49:20
So now if I wanna put this in Peter's account, I can just.
Export blueprint right?

Lem   1:49:29
Yeah, export blueprint and then import it to his.

Bryan Wolf   1:49:31
I would just import it into his, yeah.

Lem   1:49:33
Yeah, in this account then you would need to put again all the credentials, like the perplexity ChatGPT like for the yeah, and also for the e-mail.

Bryan Wolf   1:49:39
Yeah. Fill it back out.

Lem   1:49:44
And yeah, we would also need to set up again like the console, because it's actually like if he would use the his own personal e-mail.
So we would need to do the console for Google again.

Bryan Wolf   1:49:59
And then this one, you're you're still just gonna be working on tomorrow. 'cause. I know he had switched. Like all of these down here and you wanted, like, *** **** out better so he can understand in his mind better.

Lem   1:50:08
Yeah. Yeah, that's right.
Yeah. So I would need to edit some parts of this one for this flow.

Bryan Wolf   1:50:10
Yeah. OK.
Yeah. All right.
Well, I'm. I don't really need anything.
I'm just gonna do put all the stuff in Peter's account.
I don't run any issues, but if I do I'll just shoot you an e-mail, but I'll also just talk to you tomorrow morning.

Lem   1:50:22
OK.
OK.
OK.
Bryan, no problem.

Bryan Wolf   1:50:29
Sound good?
Let me let me you're the man.

Lem   1:50:32
OK.

Bryan Wolf   1:50:33
Have a good night.

Lem   1:50:34
Have a good night.
Have a good day also.
Good morning. It's morning there, right?

Bryan Wolf   1:50:37
It is more than it is more.

Lem   1:50:40
Yeah. Have a good day there.

Bryan Wolf   1:50:41
Talk to you then. Yeah, see ya.

Lem   1:50:42
OK.

Bryan Wolf   1:50:42
Thank you. Bye.

Peter Wolf stopped transcription


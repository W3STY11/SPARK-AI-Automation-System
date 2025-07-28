# Process Automation Workflows 250605

**Original File:** Process Automation Workflows 250605.docx
**Extracted Date:** 2025-06-05 (Thursday)
**Converted:** 2025-07-28 11:40:46

---

Transcript

June 5, 2025, 2:04PM

Nicholas Westburg started transcription

Lem   0:49
And share the content.
Just open.

Nicholas Westburg   1:04
Lamb looms pretty good, isn't it?
The video recording.
I I just got into it like a month ago.
Takes really nice videos like screen Recordings.

Peter Wolf   1:12
Yeah, and and it gives the lines where it shows each person and shows where they talk throughout the meeting.
So you can go right to those people.

Nicholas Westburg   1:18
Yeah.

Peter Wolf   1:19
That's pretty cool.
I mean I I use the fathom, but I just noticed the teams is definitely increased the quality of their tool.

Bryan Wolf   1:25
The quality of their what program is that?
That's on teams you're saying?

Peter Wolf   1:29
That's on teams. Yeah, he's recording. Nick started the recording.

Bryan Wolf   1:30
Bloom.

Peter Wolf   1:32
We can go look at it later, but it's really cool.
It shows you each person and then it shows you where they talk in the in the meeting you can just go to those people whenever they're talking to.

Bryan Wolf   1:40
OK. Yeah.

Peter Wolf   1:41
Yeah, it's pretty cool.

Nicholas Westburg   1:41
So they also have the.
So I clicked on the copilot, so as the meeting's actually real time, it understands every single word. So it's like recap. So far, questions that are unsolved.

Peter Wolf   1:45
Yeah.

Bryan Wolf   1:50
Don't blow my way.

Peter Wolf   1:52
Yeah.

Nicholas Westburg   1:54
So it's like you're you're chatting with an LLM. Real time, while the meeting's taking place.

Peter Wolf   1:57
Right. So Brian, if you're in teams look up at the top, you see the copilot right up there.

Bryan Wolf   2:02
Yeah.

Peter Wolf   2:02
It's about it's, it's, it's about halfway between on the stop on the right hand side. If you just click on that it gives you.

Bryan Wolf   2:06
Yeah, I see. Open copilot.
Yeah, yeah, yeah.

Peter Wolf   2:10
It gives you the thing on the side that will start.
This is the AI automation stuff with open AI integration.
So all right, so I see Gilles on there. Is Peter on two pride.

Bryan Wolf   2:22
Pete, are you in there?
I'm sorry I'm having an issue.
He's coming back right now. Not sure.

Peter Wolf   2:26
OK.
I'm not sure if Bart's joining, but just one more minute and we'll we'll get started.
Thanks lemm.

Lem   2:34
Yeah, no problem.

Peter Wolf   2:39
All right, so Lev just this is these guys on my team got Bryan, Peter and Nick.
They're on my intern program and Jill is one of my senior, one of my senior managers on my team at Serrala.

Lem   2:49
OK.

Peter Wolf   2:55
So these guys are all working with me on process flow stuff like we discussed. We're really only just getting started and and really I'm kind of funding this off to the side on my own to to help accelerate us in.

Bryan Wolf   3:03
Yeah.

Lem   3:07
Thank you.

Peter Wolf   3:09
In learning some of this stuff, and ultimately we're going to go into the Microsoft environment with power automate like I talked about.
But these things that we're working through about connections, they have power connect which is and and power automate, which is essentially the same thing.
The combination is maker Zapier, right?
You just connect.

Lem   3:27
Yep.

Peter Wolf   3:28
They don't have as many connections as as make a Zapier. I don't think, but obviously they will because Microsoft is about one of the.
Largest infrastructures out there and you can always.
Create custom connects too.
So if you don't have one, if it has an API, you can create a custom connect.
So these things that we're building where I'm saying build them off of a Gmail notification, they can be off of a Microsoft notification.
Same thing in Microsoft Outlook, right?
So that's why we're taking this as a learning as a template and then we'll take that and move that over to that other environment.

Lem   3:57
OK.

Peter Wolf   4:02
But this stuff that you're that you're walking through?
You know, allows us to look at the process, understand the flows, understand the calls.
To those different apps.
And so that's going to be very helpful in kind of building the skill set, OK.
So appreciate it if you could look at the video.
Great. You know, nice overview, but let's let's let's go through. Walk through the process, walk through the setup stuff 'cause. I know those boxes and all.
You know what?
What did you enter here and there?
What are the connections and that setup of the the kind of troubleshooting or the multiple runs and stuff like that?
That'd be great.

Lem   4:40
OK.

Peter Wolf   4:41
Hold one second, wait one second. Is my my note takers not on here.
Hold on a second.
One more second here.
There we go.
All right. So we're gonna, we're gonna review the process flow that was created by Lem for triggering an e-mail with a keyword trigger that then calls.

Lem   5:18
OK.

Peter Wolf   5:26
To calls to make delivers that that content to make extracts the body content. The body content contains the URL, the URL where the body content is delivered to ChatGPT ChatGPT extracts the URL. URL is delivered back to make.
Make delivers that to perplexity.
Perplexity goes to the URL, extracts the title and the body content, reviews it, creates a 30 word summary, and sends that back to make.
Make then delivers that to a Google sheet and updates the Google sheet with the information.
So that's the basic outline what we're going to walk through right now.
All right, lemm, if you could walk us through, appreciate it.

Lem   6:04
OK.
Let me just share my window here.
So Yep, can you see my window now?

Peter Wolf   6:12
Yep, absolutely.

Lem   6:13
OK.
So Yep, basically this is the automation.
The simplified version is same as Peter said.
So this basically triggers whenever we have an e-mail on our inbox and then every 15 minutes this will check that particular inbox. If we have an e-mail and then I have a filter here which is the subject.
So this is like the query filter. So we can change this filter to like labels or let's say subject. Let's say our our query here is to teach at GPT. We can put that. Put that in here.
So for the one that I built is for the research.
So this was the like the particular e-mail. So this is like the subject line.
So I put like research here so this.
Trigger will catch that one so every new e-mail with the subject.
Line with research so this will trigger and then I added a filter here because whenever let's say every 15 minutes this is triggering.
So if there's no data, this will error out.
So this is like a fall back for that particular. Yeah, particular scenario when there's no data coming in.
So this this should like stop that particular run and then yeah, if there's data, the first thing that will it will do is it will feed that to the ChatGPT module.
So this will extract that particular.
E-mail body and then ChatGPT will like.
Will read it and then it will return the URL, so it that's prompting is very simple.
So first is the the basic prompting for ChatGPT and make something like this.
So first, there's a system prompt, and then there's a user prompt, and then there's another user prompt.
So first is the system prompt.
So basically it's like an identity of the ChatGPT, so you're a helpful intelligent assistant.
And then for the next prompt is the user prompt.
So this is we are like selling ChatGPT. What it will do. So basically in like simple language the simpler the better so that.
ChatGPT won't get confused.
So for example, for this one your task is to extract the website link URL from the e-mail body data and then just output the complete website link URL.
So basically the the we need to put the prompt as simple as possible so that it the the output should be good but for other use cases especially this prompt will be much longer.
So depending on the use case. But yeah the main.
Main thing here is.
The shorter the prompt and the simpler the prompt, the better.
And then Yep, and another user prompt here for the input.
So this is like the input e-mail body and then what I did here is I mapped the Gmail text contents.
So if you can see on the right side here. So this is basically all the data that is coming from the Gmail module.
So this is like the Gmail Inbox Module watch emails module.
So this is basically all the data that's coming from here and then we will just map it will find the text content.
So this is like the text content I just found out what happens and then I just like click it here so you can drag and drop here.
Here also and then or you can just like. Click it here.
So Yep, basically that's it.
So for all the chat gpts it will work.
Basically the same like you, we have a system prompt.
We have a user prompt for the task and also the user prompt for the input data.
So Yep, that's it.
And then actually this router is just a new ones because the links that are coming for the test.
What Peter gave me is coming from Apple News, so for now, perplexity cannot like go to the redirect link.
So what it does?
Is it only research the particular website link of that of of the website?
So if we can this one.
So this is like the Apple News.
So this is actually a redirect link. If you can see so.
This is Apple News and then.

Bryan Wolf   10:35
Hey, can I can I interject real quick?
Can I interject?

Lem   10:37
Yep, not a problem.

Bryan Wolf   10:37
So when I go from the the watching of Gmail to ChatGPT, what I'm trying to connect my account here it says it's not.

Lem   10:43
Yep.

Bryan Wolf   10:46
I ran into this problem before too.
It says it's not possible to use restricted scopes with customer Gmail accounts.
So what does that mean?

Lem   10:51
Oh yeah.

Bryan Wolf   10:52
Does that mean I need to make a separate Gmail with like a new guidelines or?

Lem   10:55
Yeah, there's a particular guidelines for like personal e-mail.
So actually right now the like the setting it up is. It's not really like complex. You can like we can do it like step by step but if you have a business account it it would be like much easier to like connect it to.

Bryan Wolf   11:08
Huh.

Peter Wolf   11:13
So we so we can change the settings of existing accounts or we got to open a new account, we have to open a new account.

Lem   11:17
Yeah, Andrew. Pardon.

Peter Wolf   11:21
Guys go on mute when you're not talking. Just so the background noise. So is do we have to open new accounts or we can change the settings from personal account to a business account? If you're saying that's the setting that controls it.

Lem   11:31
Yeah, we can.
Yeah, because actually we can use the Gmail personal Gmail account, but it will. We need to trigger. I mean we need to like set it up like a Google workspace and then put the scopes on it.
I can like.
Get actually make has instruction on it step by step. But I mean the easiest thing to do here is like use business account for it like something like that. But for connecting the personal account, yeah we can actually like.
Do it step by step on the.

Peter Wolf   12:05
OK.
So we'll come back to that. We'll, we'll come back to that awesome, OK. If you can keep going.

Lem   12:07
Yep.
No problem.
OK.
Yeah. So yeah, for so this one, I'm using a personal account, but I've already set up like the scopes and also like the Google Workspace. So I've already set it up.
So Yep, for now I will explain this one first.
So the there are like 2 routes here right?
So basically these two routes are doing the same. It's just that because because of the redirect link coming from Apple News.
So I've added this as a fall back.
But basically, if the website.
Link is just a direct website link so it will go fast through here, but basically it's doing the same.
So first is it will feed the website link to perplexity.
So if you click here we can see the prompt of it.
So it's very simple.
Just summarize in 30 words the content coming from the site.
So this is the website coming from ChatGPT and then ignore other sources also get the exact title of the content, usually in headers.
And then the summary should be less than 30 words.
And then the final output should have the title coming from the website and the 30 word summary.
So yeah, this is a simplest possible. So the better Yep.

Peter Wolf   13:18
Yep. Nice and concise. Yeah.

Lem   13:21
Yeah, yeah, the concise summary.
So we can edit this one like to 50 words or something.
So depending on us, so we have the this is just like a user prompt for the perplexity and then we will.
We are also using the Sonar Pro so this is also the model that we are using.
For the ChatGPT, we're using the GPT 4.1, so this is the like the most latest GPT. That is not very expensive.
So GPT, GPT, 4.1 is working well. So for the researching on perplexity, we're using Sonar Pro then Yep. So basically that's it.
It will get the website and it will research the Internet for that particular.
Link and then it will get the title and then it will also.
So extract a summary of that particular article.
So the next modules here is just extracting the data. So this module is a ChatGPT module that just extracts the title from the result of the perplexity.
So if we can.

Peter Wolf   14:25
Isn't perplexity sending them back as unique kind of data fields, so it's sending the title and the and the summary? Isn't it sending the title already sending the title back?

Lem   14:25
Just.
Me.
Yeah, it's already sending the title and the content, but the thing here is there is like a parsing.
So we need to like map it here on database right on the Google Sheets.
So we need to like map this one so.

Peter Wolf   14:52
Right, so we're parsing it out.
But you're saying perplexity delivers it parsed out, or no, it's sending it both together.

Lem   14:54
Yeah, yeah.

Peter Wolf   14:58
And then Chevy is parsing it out OK.

Lem   14:58
Yeah, it's sending both together.
Yeah, yeah, yeah.
It's sending both together. Actually we can.

Peter Wolf   15:02
Can you see like can we see the output from a step?
Can we see what the output was so you'd see how it was pulled together visually, where it's not possible to do that?

Lem   15:13
Step by step you mean?

Peter Wolf   15:14
No, like right now.
Can you go to that flow and see what the what it, what the content was and perplexity gave back in a particular scenario or if you're watching it live, can you see like click on it and show what the content was so you understand like I don't know.

Lem   15:27
Yeah.

Peter Wolf   15:30
What it looks like and having an understanding what it looks like would help me to figure out how I work with it right.

Lem   15:31
OK.
Yeah. Yeah, yeah, yeah, yeah.
Yeah. So yeah, that's right.
So we can actually go to the history and then we can check the last history.
So with this one we can actually check the like the data inputs and outputs.
So for this one, it was triggered via this particular Yep.

Peter Wolf   15:55
OK.
So can you show me the show me the perplexity output for that?

Lem   15:59
Yeah, so this is perplexity output right now. So the.
Message this one so it's in outputting the title and then also the summary.

Peter Wolf   16:09
Yeah.
OK.
So it's just giving it to you.
It is separated but it's giving to your body and then Cha Cha BT says OK, I can understand the title and that means this part is the title and the rest is body and it's separating them out. OK, awesome.

Lem   16:19
Yep.
Yes.
Yeah. So.

Peter Wolf   16:24
This is great. The ability to look at the history and see the content so you know if you get a failure, you're like, oh, it didn't include this content or included way more than I thought. This is really cool tool.

Lem   16:32
Yeah, right.
Yeah. So yeah, actually I am.
It's much better to like explain it here.
So yeah, that's a a good insight.
But yeah, basically for example this one.
So we can go back like it's getting the data. So this one, this is the data from the Gmail, right?
And then this is this is like the text content as you can see.

Peter Wolf   16:51
Yep.

Lem   16:55
So I just this is like the title and then this is like here's what happened when I testedge BT and then this is like the link.
So it is an Apple News link.
So what happened?

Peter Wolf   17:05
Couldn't you have couldn't just as again. I'm like in the brainstorm. You could have probably taken that and sent that to Chachi, BD and said, hey, if it has an Apple link, extract the Apple link out of it and turn it into a direct URL or something instead.
Of sending it over to you know what I mean to.

Lem   17:21
Yeah. So yeah, basically no ChatGPT can doesn't have that capability yet, so it cannot go to redirectly. So I've I.

Peter Wolf   17:28
OK.
No, but I made and then if it looked at the URL and then it had the slash slash Apple News dot blah blah blah then it could say just extract the Apple News portion of it and that's the URL, isn't it?
Isn't that the direct URL?
They just put Apple News in front of it.
I'm not sure.

Lem   17:50
Yeah. No, but I think that this is like the this one natively on the Apple News.

Peter Wolf   17:52
OK. OK. OK.

Lem   17:56
So yeah, this is like.

Peter Wolf   17:57
Yeah. So how did you get the?
How did you get the end URL link?
What was the step you did?

Lem   18:02
Yeah. So.
What I did here is basically I because first is I've just created this particular flow.
So when I test when I tested it out, it erred out.

Peter Wolf   18:11
Yeah.
It failed.
Yeah, right.

Lem   18:15
Yeah, it failed because perplexity cannot go to redirectly.
So basically my thought process is how do I like get this redirect link fixed?
So I've research and then on the Internet so.
Perplexity as of now.
Go to like redirect link. So what I did is I've added this HTTP request.
So basically what is it's just doing?
Is it is like querying that particular link and then getting all the data coming from that particular link.
Or the website.
So basically this opened up the Apple News.
So this is like the Apple News. As you can see Apple dot news and then the code, right?
And then this will actually open that particular link and then go to the redirect link and then feed all the data's output so the day.

Peter Wolf   19:06
So what is that app?
What is that app or what is that function that you're using right there?

Lem   19:11
Yeah. So this is like HTTP request module.
So if we go back here on the diagram so.
Just loads of. This is actually if we go to a module.
So this is just HTTP.
So this is like an HTTP request.
It's like actually this particular modules are doing the same thing. It's just that this is like we are setting it up manually.
So if you're, if you know what I mean.
So basically all of the modules here are like HTTP requests.
It's just that, like ChatGPT.
They already set it up that it's like user friendly.
So we don't need to like put parameters here, but basically whenever like some there are some issues like this one.

Peter Wolf   19:57
Yeah.

Lem   20:03
So we also have like the HTTP module.
So this is a pretty flexible. We can do a lot.
A lot on it. So we can like get a file we can like open the open the website.
So what I did here is like I added the basic author request.
So what happened? What it?
What it will do is like it will just open that particular link and then get all the data on that particular link.
So this is like a method.
So this is like like we have a post boot.
So this depending on the use case, so we can add this method.
So yeah, this little nuance there, but.
Basically, yeah, this particular module is like getting all the data coming from that.
Pull new sleep so and the data is.
Has that the particular link that we need, which is like the Tom's?
Yeah, the.

Peter Wolf   20:55
Yep, the end real URL.
The end URL, yeah.

Lem   20:58
Yeah, yeah, the the real.
Yeah, the real URL data so.
And the next step for that one, of course, is to feed that data and then extract the website thing.
That's why there's a ChatGPT module also here so.
This also extract the.
The real URL link coming from the data here on the HTTP request. So also this prompt is very simple.
You're you're a helpful, intelligent assistant.
Your task is to extract the redirect website link URL from the data and just output the complete website redirect link URL.
So and then the next is user prompt. So input data is like the data coming from this particular module. OK so and then Yep.
And then.
After that one, let's just go back here for more context.
So Yep, so we are already here, right?
So ChatGPT was able to pull this out, so as you can see the result is the Tom's guide link.
So this is the real link coming from the Apple News.
So it was able to get it based on the data.

Peter Wolf   22:05
Yeah.

Lem   22:07
So the data, if you can see is something like this.
So ChatGPT is already intelligent enough to get that particular link coming from this particular data.
So as you can see this is like like pretty complex, right? But.

Peter Wolf   22:20
Yeah, yeah, but somehow it's finding that information in there.

Lem   22:23
Yep.

Peter Wolf   22:23
That's awesome. That's great.

Lem   22:24
Yeah, so ChatGPT 4 point. This is a model 4.1, so it's pretty intelligent right now for like this particular task.
So Yep.

Peter Wolf   22:32
Yeah.

Lem   22:32
And then next is it will feed that particular link here on perplexity.
As you can see, we can check the this one.
So summarize in 30 words, the content coming from the site.
This is the site the Tom's Guide site this one.
So it dynamically put it here because we set it up right in the module and then.
The output for this is something like this, so in the choices.

Peter Wolf   22:58
And I I see on your prom too.
I I like this.
And you know, ignore other sources, right?
So it's not bringing its own history to the table and and embellishing, right?
It's only writing the summary based on the content of that article. Those kind of little guidance things on the prompt are critical to get the right information, yeah.

Lem   23:10
Yes.
Yeah.
Yeah, that's right.
So actually this is like I didn't fill it in like first time. So I've like tested it out. Maybe like I've changed the prompt three to four times.
So because yeah, we can like test it out actually here live.

Peter Wolf   23:28
OK.

Lem   23:32
So I'll just also put a tutorial on testing so that other guys will know the testing.
So actually we can like test this one by one.
We just like right click and then run this module only and then depending on this one so.
We need the data for the result because as you can see in the prompt here.
The prompt has the mapping of this one result.
So when we like test this out, we would need like the we would need like the the data to to be able to like test this out.
So let me just like pull out some links or this one I think can.
Use this one.
So, and then let's say I'll feed it here.
Yep. So I feed it here and then click OK.
So perplexity now is like searching the Internet for that particular website.
So the output is something like this, so we can actually test this out.
So this is what I did a while ago with a prompt.
So if I test it it out first with a prompt that I did and then it depending on the reply.
So depending on the reply we can we can tweak the prompt so that is the best like.
The practice on on the prompt engineering for ChatGPT and also for perplexity or any AI models that say you seeing or something like that.
So it's best to like run this, run the module 1 by 1 to test it.
Test out the prompt. If it's working properly.
So Yep, the for as of now, this is like the title. So I just tested in the same.
This is like the summary. So it the prompt is working well. As you can see.
So yeah, that is how we test the prompts 1 by 1 per module.
And then Yep, basically the next step is just extraction of data.
So the next module is, it will extract the title and then this one also will extract the summary. So as we can see on the history, let's go back to the history.
Then.
This one.
Yep, this one.
So basically the output here is this one right the.
The output is this one, so the title is here and then the summary is here.
They are in just in one text, so if I will map this one on the database on the Google sheet, what will happen is it will put all the text on one like one row it will like put all the text here or it will put all the?
Text here, so that's why I've added two modules for extraction so that chat gpti mean the database will be mapped correctly.
So that is basically the use of this extract title so.
It's also very simple.
The prompt here is like this one.
Your task is to extract the title of the article coming from an input data and then just output the title in plain text and then this.
There's also like a sleep module, so this particular module is for the API rate limits because sometimes like open AI or something like Google Sheets or other platforms have rate limit when they are request.
ING for a data.
On like a like on the same time like a few seconds apart so.

Peter Wolf   26:58
So it's like a pause or something.

Lem   27:00
Yeah, this is like a pause.

Peter Wolf   27:01
To pause, yeah.

Lem   27:01
Yeah. It's like a pause.
So it will just pause for three seconds after it will go back after it will go to the next module and then trigger.
So the next is. Yeah, this is actually the.
Just extract the summary so the prompt here is also simple.
Your task is to instruct the 30 word summary.
So just output the extra exact summary in plaintext.
And then the last part of this is the mapping of the data.
So the mapping of the data we we it's much easier to see on the diagram.
Oh here so.
This one.
So it's much easier if we click this one, so we'll be in this the module of the Google Sheets and then basically I will add like the connection and stuff and then the mapping is quite simple.
So we will like choose the drive and then like the spreadsheet and also the sheet name and then all the headers will go if will appear here when whenever we put like yes this table contains headers.
And then this is basically cross referencing the data here so the the headers are the website URL, the title of article and then the third Thirty word summary of article.
And then Yep, I just mapped the results here.
So this is the result coming from the this one, the first ChatGPT module, this one. So extract website URL.
So the result I just map it here so we can just like drag and drop it here.
And then like the title of the article is coming also from.
Like #4.
So this is like the other one.
So this one so it's #4. So as you can see, if we go here, so we can also this one.
So extract title #4.
So this is like the result.
So I just you can just like drag and drop and then the 30 words summary is this one. So extract summary. So the result I just map it here.
So.
For Yep, basically that's it. And then.
The also the good habit on doing is whenever we build an automation, we will rename it every time we put a module a new module so that we we won't get confused in the future.
For let's say troubleshooting, or let's say if other people will check it or something.
So it's it's a good it's a good habit to like. Whenever you put an A new module, you will rename it at that particular time, because for example like this for the ChatGPT the the.
The default name for this is something like this, like Openai ChatGPT whispers.

Peter Wolf   29:46
Are you saying, Sir, it's a unique identifier for that particular call or action?

Lem   29:51
Yeah, yeah, yeah.
So basically it's a good like, yeah, it's a good.

Peter Wolf   29:56
Yeah, understood.

Lem   29:58
Yeah, to like reading.

Peter Wolf   29:59
How many is there?
Is there a?
Is there a function for?
I'm not sure if you're familiar with GitHub, but you got branches where you got your core program and you branch off and you say I want to try these things, but you you keep your core.
You say I'm gonna add these other things onto it, and if they work out, you say, great. Observe these into the core.
And now my course stays the same.
But otherwise, if this doesn't workout you just throw it away and it doesn't do anything.
Or do you take if you want to play around with this, could you copy this, I guess and just repeat it, paste a new one and then start playing with that one so you don't mess up your core. Like if you start coming up with other ideas, right?

Lem   30:35
Yeah, yeah.

Peter Wolf   30:37
You take this template, copy it and then just start working with that template so you're not messing up what you already have comfortable or what's already working right.

Lem   30:38
Yeah.

Peter Wolf   30:46
OK.

Lem   30:47
Yeah you can.
Yeah, we can actually easily like duplicate this one or like import it so there's no problem about it.

Peter Wolf   30:48
Good.

Lem   30:54
So it make actually it's a pretty easy we can just like like copy and paste this particular.
This one so we can like copy module and then we can create other or we can also like duplicate this one on the.

Peter Wolf   31:07
OK.

Lem   31:11
This let me just go here.
So this one, let's see if we can like clone this one.
So what will happen?
Is it will copy all the modules and then like put it another here so there's a copy and then oh, I also need to like explain also the.
The error handling, so this is also.
A very important.
So for the error handling, because sometimes the modules get like rate limited or let's say there's an outage on on ChatGPT or let's say on Google Sheets, or they have some maintenance or stuff.
So actually it's good to add error handling.
So basically what I most most of the time what I use for the error handling is the break module.
So basically what will it will do?
Is it? It will just.
Look, let's say it will this particular module, this chat chat.
Gpt will error. So what will it will it does.
Is it will try again after three minutes. So depending on the depending on the parameters here. So I've added it here to 3 minutes and then this number of of times is 3 also.
So what will happen?
Is it will try again after three minutes and then after three minutes it is it aired out again it will try again three times.
And then after that, if it still erred out, it will stop the particular run.
So and then it's OK because it will actually be logged here on the incomplete executions.
It will be logged here and then we can like easily troubleshoot it. Or if we need updating the the particular scenarios. So this is very important and then also.
Let's just go back here and also.
For this one to work, we need to trigger the settings here.
So this one.
So allow storing of incomplete execution.
So we need to like toggle this to yes.
To yeah.
So that this particular error handlings will work.
So this one this is just for make.com. So Zapier already has their already have their their native error handling.
So it what what happens is up here is if it error it aired out it will try again after a couple of minutes.
So it it doesn't have like this but in make we need to put like this manually one by one for the modules with.
HTTP request.
So for this one we don't need because this is just like a native tool like just a delay or something.
Also, for the routers it doesn't need.
So Yep, basically that's it.
Any question guys or like clarifications?

Peter Wolf   33:53
Yeah, and and that's that's awesome, Lynn.
I mean that's great overview.
Here's a couple things.
I think we we need to take this.
I know you sent the uploadable version right?
They need to import it in to make and then switch the accounts over to to our LinkedIn, to our Gmail, to our underlying perplexity and ChatGPT and and then I think we'll play around with it a bit.

Lem   34:13
Yep.

Peter Wolf   34:22
And then schedule some time with you to to deal with any troubleshooting. What I'd actually like to do.
I know it's late for you then, but maybe everybody else could drop off and you and I can get on a different call back on Upwork and and talk about maybe some additional engagement, OK.

Lem   34:40
OK.
No problem. Yeah.

Peter Wolf   34:41
Alright, so anybody else have any questions.

Gilles Gilmart   34:46
I had a couple of questions, Peter.

Bryan Wolf   34:46
I'm good.

Peter Wolf   34:47
Yeah, go for it.

Gilles Gilmart   34:48
Yeah. So, so, so one you know amazing, right?

Lem   34:49
OK.

Gilles Gilmart   34:51
I mean like you've done that overnight. It's incredible.
My first question is about the breaks.
I saw that you inserted a break at or an error handling at every single step.
So I'm I'm not really sure I understand the scenario there because on the first step I understand it right.

Lem   35:01
Yep.

Gilles Gilmart   35:07
An e-mail comes or not every 15 minutes, but on the second step with ChatGPT, what does that mean that?

Lem   35:10
Yep.

Peter Wolf   35:14
Yeah, but no, no, no. Stop the emails when that action, that particular action, when he calls the GPT and if it can't get through or it doesn't get a response fast enough, then it's a failure for that step, not earlier.

Gilles Gilmart   35:14
An e-mail would come with an with an article.

Lem   35:26
Yeah, yeah. For for that step only. Yeah, yeah.

Peter Wolf   35:26
Stuff. It's that particular action.

Gilles Gilmart   35:28
So in so, in this case, for the second step, that means that we get an e-mail come coming in and charge ebt's trying to find the URL within the body of the e-mail, but cannot find it.
That's that's what that error handling.

Peter Wolf   35:37
Right. What if I what if I put the word research in the header and I really didn't have an URL in the body and it's passed all the body content and it tried to find the URL and said and this is stuff we should be practicing what happens?

Lem   35:38
I don't know.

Gilles Gilmart   35:44
OK.

Peter Wolf   35:49
When we have bad data, right?
So you can understand when he was troubleshooting.

Gilles Gilmart   35:51
OK, OK.

Peter Wolf   35:53
So if I put that research in there, but it didn't have a URL or the URL was cut off or something, it pulls a URL and then it tries to send it says yeah I got a URL against the next ChatGPT and says I can't call it.
It doesn't exist or perplexity says it doesn't exist.
Then it's going to fail and it's not everything else got up to that point that we're handling history. Thing is awesome where you can see the inputs and outputs and see that, OK.

Lem   36:10
Yep.
Yeah, yeah.

Peter Wolf   36:16
What that URL was never there to begin with, right?

Lem   36:18
Yeah, that's right.

Peter Wolf   36:18
Or if I click on it, it's a Dead Space, right?

Gilles Gilmart   36:19
OK.

Lem   36:21
Yeah, but.

Gilles Gilmart   36:21
Yeah, that makes sense.

Peter Wolf   36:22
Yeah.

Gilles Gilmart   36:22
And then Maldo question is about perplexity.
I'm not familiar with perplexity, but I understand why you have to use perplexity because you were saying that ChatGPT doesn't handle like the redirect links, right?
But why do you have to use ChatGPT at all? Back from perplexity?
Is that because perplexity? Cannot you know, like feed directly googlesheet with the with with the?

Lem   36:42
Yeah, yeah. Yeah. Because I. So for the like for me personally, I have a like a protocol where where in when you I use a particular AI model.
So I just.
Give it a particular task.
So just one job because it get sometimes it get. It gets confused when you like put many task for it.
So basically what I did is I use ChatGPT for like parsing the data or like extracting the data and then.
For now, perplexity is the best for like researching the websites.

Peter Wolf   37:15
Searching.

Lem   37:16
Yeah, for researching the websites. So that's why.

Peter Wolf   37:18
So you could have though you could have. You could have used sonnet.
You could have used grok you instead of ChatGPT right?

Lem   37:24
Yeah, yeah, no problem. Yeah.

Peter Wolf   37:25
That's just a personal preference or identification that one tends to do better than another, but perplexity specifically is known for being able to search the web at the you know, most advanced stage of it.

Lem   37:28
And this is, yeah.

Peter Wolf   37:38
So using it for that for the web search, but the the Alec the the the parsing the allocation you just happen to use ChatGPT for that.

Lem   37:38
Yep.
That should be.

Peter Wolf   37:45
But you yeah, OK.
OK.

Lem   37:47
Yep.

Gilles Gilmart   37:47
Because you didn't want to have like the parsing in the same application as the OK.

Lem   37:51
Yeah. Yeah, that's right. Yeah, yeah.

Gilles Gilmart   37:53
But could you not have had like another step with perplexity as well?

Peter Wolf   37:54
And I like segregating that too. It's.

Gilles Gilmart   37:57
Like I'm thinking there could have been like two, you know.

Lem   37:57
Pardon.

Gilles Gilmart   38:01
Steps with probably next to each other, the first one extracting the data and the next one like restructuring it.
Or do you need to have two different app in in in step next to each other?

Lem   38:11
Yeah, basically we can also like prompt it to like do 2 two other time to say extract the title, then the summary and then also parse it into like a Jason format.
But yeah, it would need something like more prompt engineering purposes.
So for this one I just I made it as like as simple as possible.

Peter Wolf   38:34
Clean and segregated and easy, right?

Gilles Gilmart   38:34
OK, OK.

Lem   38:35
Yeah.

Peter Wolf   38:36
Yeah, you could get one step.

Lem   38:37
Yeah.

Gilles Gilmart   38:37
OK.

Peter Wolf   38:38
Could be much more complex, but I think from a user perspective looking at it or someone managing it in support or or management later if you want to modify having very discreet specific activities, even if it was like you said Gill, you called you called perplexity to do.
The same thing I would say having two steps would be better than one step.
At whether you use different apps or not, I think this was great for us that it does call ChatGPT.

Gilles Gilmart   38:59
Right.

Peter Wolf   39:04
And perplexing, because that gives us a little bit of variety too.
Again, I think there'll be scenarios in which, like writing output, really Sonic would be the best use right now. They're saying that that one writes the most advanced to most human like so there are different scenarios where I think we would go to other ones as well, but.

Lem   39:24
Yep.

Peter Wolf   39:24
It's it's very much to me.
I see this nice discrete individual steps because it's easy to follow, easy to manage, easy to troubleshoot, easy to understand, right?

Gilles Gilmart   39:27
Exactly.

Peter Wolf   39:33
Easy to immediately look at the process and say, yeah, I got it.
I understand what this is doing, right?
Not have a whole bunch embedded right in one step where it looks like a big BLOB, but inside there's 80 things going on. And really if one step fails and there the step fails and you don't know, OK, what do I got to go through all these differe?
Pieces to find that failure, right?

Lem   39:52
Yep, Yep, that's B.

Gilles Gilmart   39:52
To me, this is great inside because you know, I probably had to go to a lot of, you know, iteration with errors because of this.

Peter Wolf   39:56
Yeah.

Gilles Gilmart   39:58
I didn't know that I embedded plenty of, you know, activities in the same step. So I'll I'll know better next time and I can tell you as well that you know lots of the things that Lem has said about the way you know it's working in make also.

Peter Wolf   40:04
Yeah.
Yeah.

Gilles Gilmart   40:13
What you said, right?
Like you can go to the history and see the input and output so that you can retest and also like the concept of having pause the concept of having like HTTP.

Peter Wolf   40:23
It's just a slightly separate technology, right?

Gilles Gilmart   40:25
It's.

Peter Wolf   40:26
Or not slightly different technology, just like we use SAP to do our pieces. And yeah, go ahead, go ahead.

Lem   40:26
Yeah, yeah. It's just a little difference there, but basically, yeah.

Gilles Gilmart   40:26
Exactly.

Lem   40:33
Yeah, basically the like the integration platforms are like doing the same thing.
It's just like the tools are like are different. Like it plays differently.

Peter Wolf   40:38
Yeah.
Where your button is.
What do you gotta click and hit?

Lem   40:42
Yeah, yeah, yeah. Basically. Yeah. The same, yeah.

Peter Wolf   40:43
What's automatic and what you have to call out?
Yeah, but this is great. Again, I think what we'll do is we'll work on these, start building the confidence with this. I think instead of getting, I'm already thinking, OK, we should do this over Zapier as well, just to learn Zapier.
But I'd say first learn one module, right?
Let's learn the heck out of make and get really comfortable with that.
And then you can say, OK, now let me go over and take this over to Zapier.
Recreate the thing in Zapier but instead of getting spread all over the place, I think we start using.
And we really get comfortable with that and really working on the flows and understanding flows and thinking about more complex flows because again this is still a basic flow. We can morph this into a 50 different things and that's what I want to talk to you about some.

Lem   41:20
Yep.

Peter Wolf   41:24
Others we can potentially move forward right away. All right, guys.

Gilles Gilmart   41:26
OK.

Lem   41:28
I.

Peter Wolf   41:29
Can you guys?
No, I'll reach out to you, Lim through through Upwork. OK. And then yeah, just take a couple minutes.

Lem   41:30
No.
OK.

Peter Wolf   41:36
Your time and you guys, I'll I'll follow up with you and and talk with you shortly.
OK.

Lem   41:42
OK.

Peter Wolf   41:42
Alright, thanks guys.

Gilles Gilmart   41:42
All right.
Thanks Tim. Thanks everyone.

Peter Wolf   41:43
Alright, I'm sorry.
Any other question?

Nicholas Westburg   41:44
Thank you.
Thanks Alan.

Peter Wolf   41:45
Yeah, everybody's logging us. Yeah, thanks.

Lem   41:46
OK guys.

Peter Wolf   41:46
See ya. Alright.

Lem   41:47
Thanks also.
It was nice meeting you all, OK?

Gilles Gilmart   41:51
Thank you.
Bye bye.

Lem   41:52
Bye bye.

Nicholas Westburg stopped transcription


# Process Automation Workshop (22)

**Original File:** Process Automation Workshop (22).docx
**Extracted Date:** 2025-07-07 (Monday)
**Converted:** 2025-07-28 11:40:57

---

Transcript

July 7, 2025, 12:57PM

2:23
Yeah.

Bryan Wolf   2:31
Can you hear me?

Nicholas Westburg   2:33
Yo, can you hear me?

Bryan Wolf   2:34
Yeah, can you hear me?

Nicholas Westburg   2:38
Yeah.

Bryan Wolf   2:41
You turn, Nick.

Nicholas Westburg   2:51
I'm so tired.
Oh, new studio, I see.
Hooray, this was just an illusion. Give me one second.
This is view from the new pen. Check it out like the like the new spot.

Bryan Wolf   3:13
Yeah.
I've got no pants up.

Lem   3:15
Hi, guys.

Nicholas Westburg   3:17
More than loud. Yeah, good.

Lem   3:17
Hello, how are you guys? Morning.

Bryan Wolf   3:20
Good love.
I don't know if Pete's getting on. Let me get my life situated right now.

Nicholas Westburg   3:32
When did you get back from the beach?

Bryan Wolf   3:34
Last night, late. Last night, very late. Pete Pete drove home really late. I was gonna stay today, but I I didn't feel like staying down there still. No, it wasn't draft at all. It was just if he just left. I only like 12:30.

Nicholas Westburg   3:38
Really.
He's smoking traffic.
I mean, honestly, that's probably not even that bad of a drive, like getting on the AC Expressway and whatever, but you.

Bryan Wolf   3:51
1.
No, it's not.

Nicholas Westburg   4:01
Lem, how was your weekend?

Lem   4:02
I just. I just stayed home.

Bryan Wolf   4:05
Oh, come on, Lem. Come on.

Lem   4:09
Yeah.

Bryan Wolf   4:10
I'll give you a second order back.

4:39
Hey, guys.

Lem   4:42
Hey Peter, morning.

Nicholas Westburg   4:42
1.

Peter Wolf   4:49
OK, um.
I don't think Peter's gonna be the only drove home like 2:00 in the morning last night. Um.
All right. So do we make any progress, Lem, on the latest?

Lem   5:04
Yeah, I've actually built like a MVP for the AI agent, but this is just like the back end for the AI agent and I built it on make so that we could also access like the other automations. So let me just share my screen for now.
OK so yeah basically this is the like the test agent on the other like test assistant that I've built. So this has like a 5-6 functions right now like creating a Google document, searching a Google document.
Updating a Google document, also creating an article and also adds a data in Google sheet and finds data in Google sheet. So we could add as many tasks here. Basically what will the what the agent will do is it will just depending on our message it will analyze it and it will find the appropriate.
A tool that will be used and then it will it will trigger the tool and then it will get the like the result of the tool and then feed to it to us. So for example I'll ask it hi there then it will generate hello can you add data on?
My spreadsheet then it will ask for like the parameters because I've added here that the required information is it will ask for the name, age and company. So for example name of the person age. So I will say here let's say.
Name is Lam, age is 25 and then like company is like Apple.
So it will get this data and then it will uh uh it will trigger the the.
Add this automation the add data to Google sheet and then it will take the get the result from it and then it will add a link here so that we could check it. So that is done.

Peter Wolf   7:10
So you still you just to make sure I'm understanding, you still have to create the automations that are each of those subtasks, but you're just pulling them together in this in this AI assistant that's going to figure out which one to call instead of you putting some.

Lem   7:18
Yep.

Peter Wolf   7:25
Hard coding about which one it should call.

Lem   7:29
Yeah, that's right. Uh. So the AA agent is, uh, will be the one that will um.
Try again. Yeah, so not sure why. OK, try again. So maybe there's some error or something. Yeah, basically it will. It will just choose like the tools here and then the tools here are actually automations in make.com.
So yeah, and then it will just, it will just trigger that particular tool and then that particular automation has like a result that will come back to this particular AA agent and then that will be the ones that will be.
Like the result that is coming from so it will add like like somebody of course and then there it will add a link because I I added it as a result here on the end modules of the automations.
So yeah, it's having a technical issue, so I'm not sure if. Let me just check the and then let's try other ones. So for example, can you create?
Google document for me.
Alright.
All right, I would like to give a name. Name is test document then content.
Just create a content for it.
And I what I'm planning is this will be like just like the back end of the AI agent and then we will have something like this that will be the web hook coming from your ChatGPT. So like the custom ChatGPT and then when you.
Send a message on custom ChatGPT. What will happen is it will trigger this webhook and then it will send your message here and then it will pass the message to the AI agent and then depending on the message if for example it's just hi there. So it will also reply here hi there and then.
It will send the response to that also to that custom ChatGPT. So yeah that would be like the your the user the interface that we that you will be using as a user is ChatGPT and then this will be like the back end for the.
Huh. That's odd.
That's odd.
So.
Let me just check. So I've just tested this a while ago. I'm not sure why it's.
Yeah, there we go.

Peter Wolf   10:20
Did you have this the same way that that for this particular setup they're all in one folder, all these different what you were calling tools, but really our mini our mini process flows?

Lem   10:30
Yeah, uh.
Yes, that's right. Yeah, we could just put them on one folder so that together with the AI agent like user like this one like the automation for the specific agent so that it won't be confusing also. So I for this one I just tested it so like a minimum viable product but.

Peter Wolf   10:41
Yeah.

Lem   10:51
Yeah, I'm having some issues. Maybe it's on the.
Um.
Try GPT 4.1.
So I just tested it like a 30 minutes ago and it was working fine. I'm not sure why it's.
Uh.
Uh.
Basically the one on N8N is something also like this. There are just like different sets there wherein you could like add there like a memory like a like a you could add a database or something like a super base or like a pipe.
Pine cone like for the getting the memory and like getting files and stuff. But yeah it also does something like this that it access the tools and that we made on like the other automations and then the A agent will be the one who will decide decide on.
Where to what? What to trigger? Um.
Uh.
Uh.
Name.
Oh.
Each.

Nicholas Westburg   12:23
Does it have to be like exact spelling like capitalization and commas and whatnot?

Lem   12:27
No, it shouldn't be because a while ago it just added like commas, so I'm not sure why it's not.
Properly.
Properly reading it, but.
Yeah, let's say.
I think there's some issues on automation maybe so.
Uh.
If this error out.
Yeah, so it actually.
It didn't error out.
Yes. So as you can see, there was, uh, yeah, let me just go back here.
Yes, it actually triggered it.
Um.
This was your 9:07 PM.

Nicholas Westburg   13:28
So what do you think is with the? It might be with the Google Drive API.

Lem   13:30
Yeah.
Um, maybe so. Let me just check on the test.
Yeah, so it actually, as you can see, it actually added the test document and then on the test database, yeah, it added the LEM 25 apple. So not sure if they are. Yeah, this is.

Bryan Wolf   13:41
Uh.
Oh.

Lem   13:51
The one that I'm thinking, sometimes it's like glitching out or something.
Yes, but it seems there was technical issue connecting the Google Sheets service. Would you like to? Yes, so it let me just check if it added it.
Yeah, so it didn't add it here.
Uh.
But yeah, that would be like the gist of the like the AI agent. Yeah, so this actually have a success. So let me just see if.
Yeah, so it can't get the output for this one. Not sure why.
You should think.
Yeah, we should think it's next.
Mm.
Yeah, I can't hide it.
Um.
Yeah, so it actually added it, just it's just it can't get the result or something. So let me just refresh this again. So I think it's glitching out or something.
Oh.
Yes.
54.1 OK.
Yeah.
So name JH.
So it's actually doing the automations, it's just that the result is not being passed to the AA agent, so that's why it's erroring out.
Uh.
Not sure if it's on the like the side or it can't get the result so.
Just exit this one.
So as you can see, uh, it it just triggered the automation. Um.
By itself so as we can see it on the history right this one this particular automation. So it triggered the automation and added added it on the database. So the next.

Bryan Wolf   16:59
Uh huh.
Oh.

Peter Wolf   17:08
And once this, once this created, so you you stored what the name of the document or the spreadsheet was already, right? It didn't create that and then stored itself, right?

Lem   17:17
Yeah, that's right. Yeah, yeah. So I yeah, we could just like depending on the use case, we could just edit the the like the automation. So for this one, this is like the test assistant add data tool, right? So basically what will happen is it will add the name.
Age company here. This is like the dynamic variable that is a required information on here. So I've added it. It is connected to the this one. So as you can see ask required information ask for the complete parameters.
Like name, age, company, that's why it's asking for this one and then when it already gets that particular data so it will push that data here on this automation so and then it will add the parameters here and then it it the next step should get the link of.
Of the just the spreadsheet and it outputs it on here and the automation. I mean the AI agent should pick this up actually, but yeah, I think there's some problem on.
On.
On the on not sure if it's on the ChatGPT side or on make side because it can't get the like the result.
Would you like to add more entries or?
Um.

Peter Wolf   18:48
So you're also you're in the testing and and kind of training, but that's just so you have the kind of immediate responsiveness as opposed to going out to ChatGPT and trying to do it right. Did you even try? Did you try the hook from the actual GPT?

Lem   19:02
And yeah, so this is just the back end. But yeah, I didn't. Uh, because I yeah.

Peter Wolf   19:06
All right. You said you were just building the the infrastructure first.

Lem   19:09
Yeah, the back end, but yeah, basically we will the the message would be like the message prompt here would be coming from ChatGPT and then we would just prompt ChatGPT that it will just pass the raw raw message.

Bryan Wolf   19:10
Oh.

Peter Wolf   19:20
Yeah, OK.

Lem   19:25
And then like we would add the prompt to it like the just pass the raw message on the HTTP request and then do not change the output or something. So this then more context like these messages are passed on my EA agent and then it will analyze the data something like that so that it won't change the.
Out like the output and then the output from ChatGPT will be placed here on the system as I shown a while ago like.
We will have like like a web hook response that will be triggered from ChatGPT and then yeah it will also get the.
Get.
Like the webhook. Yeah, so it will be a webhook and then.
Like run the agent so it will pass the message to the agent.

Bryan Wolf   20:19
OK.

Lem   20:25
So this one so it will run that agent and then we will add here the parameter like the test assistant and then we would just add here the.
The message on the here so message one. So we will add the message, the dynamic message coming from ChatGPT and then we will also add the webhook response here so that it will depending on the result. So the result would be like the links or the message so it will pass.
That message also to Chachipini so that we could receive that message. But yeah, so I think what's happening here is there's some delays, I think.
Write details. Your Google sheet now was completely like. Can you find the data?
In Google sheets for name.
LG.
So I'm just checking if.
Yeah, so that would be like the. I'm not sure if I need to put a delay here on the.

Peter Wolf   21:47
Yeah.

Lem   21:47
Yeah, because it's not getting the result right, right, right away. So I'm not sure if.
Um, that's odd.
So let me try.
Yeah.
Uh, let me say.
Yeah.
So it should trigger the.
Find data this one.
919 Yes, it's actually triggered, but.
Yeah, so it's not.
Oh.
Please.
Yeah, it's not passing the.
The.

Peter Wolf   23:03
Information back.

Lem   23:04
Yeah, information back. So let me just. Oh, right. I think. Oh, no, so it's OK. So it's actually on demand.
Yeah, yeah. So for example this one.
Uh.
Yeah, it found the following data for Lemuel, so age, the date. So if we check the history here.
Yeah, this one. Uh, no, this. I think it's a different one.
So it it just triggered the.
Not sure if this is the one.
Uh, so this yeah, this is LG and then it.
What did they search there?
Yeah, yes. So it should be. Then we will. So it's not updating the history yet.
I also saw on the other videos that it's they said it's better to use for now like the anthropic here. But yeah, the use and the anthropic load because.

Bryan Wolf   24:36
Good.

Peter Wolf   24:36
Use the what? Better to use what?

Bryan Wolf   24:37
Enter a cloud.

Lem   24:41
Yes, sometimes, but a while ago also on.

Peter Wolf   24:42
Yeah, did you see? I don't. I don't know if you were or not. I sent the e-mail to the guys internally. I got a message that the API we have right now is going to Claude 3 and that API is being deactivated. You need to go to to or it was Opus 3. I think you need to go to Opus 4.

Lem   24:53
OK.
Oh, I see.

Peter Wolf   25:01
I just got an e-mail that I I'm saying that to to you guys, Nick and Brian because.

Bryan Wolf   25:02
Yeah.
Nixon, Nixon, Stamp, you know, stand by stand guy of the benefits of of each. Yeah, basically.

Nicholas Westburg   25:11
Yeah, just like each model. Yeah, Opus 4, Opus 4 is like comparing it to Opus 3 is like comparing a Honda to a Ferrari, right? So you want to make sure you're using.

Peter Wolf   25:23
Yeah, yeah, no, I know. But but I got the notice saying that they were cutting off Opus Opus 3. So we just need to make a change to point it to the next release.

Nicholas Westburg   25:28
Yeah.

Bryan Wolf   25:31
Yeah.
Nope.

Peter Wolf   25:39
OK. So a couple of things I would like to do just I know this is just for you guys, what you were saying MVP, right, minimum viable product for this. What I would like to do is get closer to what I am really looking for which would be.

Lem   25:39
Yeah.

Peter Wolf   25:55
I think we should have and let me just type these into the into the chat so.

Lem   25:59
OK.

Bryan Wolf   25:59
OK.

Peter Wolf   26:03
And I'm just going just kind of rough right now. But so do you think I need to? Yeah, if I want the spreadsheet, I want to be sortable by I I need, I need names. So it's gonna be last name.
First name.
Um, and it's going to be.
Uh.
List.
Update 8 and it's gonna be.
Um.
Roll.
Say title.
Company.
Roll.
Comments.

Lem   28:20
All right, I didn't add the link here, so that's why it's.
Uh, so the other one should have the link. Um, let's see.
Yeah.
Uh.
John.
Age 30.
So it didn't add the link so.
I wonder why. Uh.
Yeah, I think the delay should be.

Peter Wolf   29:34
Yeah.

Lem   29:34
926 at this one.
Oh, the link is here. That's odd. Why didn't it?
Output the link.
Yeah, so this should be the.
Um, I think I need to.
Optimize the prompt here more.
Pretty good document.
In the sheet.
Um.
Find Google documents.
Example.
So I think I could.
Say output.
Mhm.
Rage.
Come.
OK.

Peter Wolf   31:31
Yes.

Lem   31:46
Alright.
Yeah, it's not, uh, I wonder why.
But here, yeah, it actually has to.
Uh.

Peter Wolf   33:08
Welcome.

Lem   33:11
OK.

Peter Wolf   33:12
Saturday.

Bryan Wolf   33:48
So this is an agent that's built into make.

Lem   33:52
Yeah, uh, it's like an agent. Uh, they like a it's like.
Yeah, basically that's. But the brain for this one is actually using like ChatGPT or we can like Claude. Yeah, so they just built the like the back end for the brain. So the brain is still using ChatGPT and then.

Bryan Wolf   34:04
Oh, right. OK, right, right, right, right.
Good.

Lem   34:15
Um, the brain for to access the tool. So that's uh, that's like the.
Yeah, but this, yeah, it's not much like I think that it would be depending on the.
Like that brain for this one because on the.
Oh, there.
Yeah.
Agent Trans.
Oh, it.
Let's just 50.
You add.
Is.
The link to the Google history like to this thing. Yeah, so this is not really. As you can see it would depend on the like the brain of the AI agent. So it didn't get the context for this one.

Bryan Wolf   35:51
Mhm.

Lem   36:00
Because I already have like the spreadsheet there, so if we change it to 40.
So.
new chat.
Yeah so yeah it should be like this. So the there would be like a link. So it really depends on the I think I'm also because like when I when I tested the this one yesterday.

Bryan Wolf   36:31
Yeah.

Lem   36:43
I didn't have like an error, so it was actually outputting like the name, agent date and then like the Google sheet link. So this link is actually coming from like this one. So as you can see this is like the.
Uh, no. This is the fine data. So for example um.
Yeah yeah this one the add data. So it was the link was actually getting being yeah outputted from here. So this is like the get share link and then I've added the result as this one. So if I have added we could change the output depending on what we want. For example I could also add like the.

Bryan Wolf   37:20
No.

Lem   37:25
Details of the of the like the spreadsheet like we could add a name age company also here. So for this one I just added a link that's why I just outputted also the link and then I think here we could test create a Google document let's.

Peter Wolf   37:42
You mean you did that just so you could show that something you were giving something back or what?

Lem   37:47
The.

Peter Wolf   37:49
When you were saying why you just gave the link, you were just trying to show that you could return something back into the agent.

Lem   37:51
Yeah, Yep, that's right.
Yep, that's right. And then basically because we could, we need to add the data, right? And then we need to know if it actually added that data. So like this should be like a like a confirmation or something. So yeah, we could check and it add actually add the data. So it's like just a.

Peter Wolf   38:09
Yeah, OK.

Lem   38:15
Information. So for example this.
Also like the Google document, so you create Google document.
Then.
Go down the content you like, just create an article.
About 5.
This is to travel to. So, should be title. So title. Five places to travel to.
So as you can see the parameters here also is within the prompt. So for the create an article I've asked the ask about the parameters, for example how many words ask for the title. So that's why it's asking this one so.
Make it 100 word. Uh, 100 words.
Yes, create a Google document for it.
So it should uh like.
Uh.
Yeah, I think I I did the wrong.
Yeah, so for example this one, the article titled Five Places to Travel to has been created with approximately 501 hundred words. Then we could check the document link here so we would be added to the document. So this was the five places to travel to. So this is like a confirmation.
Yeah, so I think, yeah, GPT 40 now is working well. Yeah, it was the ChatGPT. I think the brain a while ago is the one that is erroring out or something. But yeah, this should be like the.
Like the flow of the chat and yeah, we could get the Google link and then depending on the tasks that we wanted to do, we could just add. So I've added here also like a creation of articles. So we could create the article from here or we could just also like paste it on article.
Content and then add it on a template or something. So yeah, this is just like the.
Like the one that sample, right? The sample that you've asked me to do and then for the ChatGPT, yeah, we would just build it on.

Peter Wolf   40:43
Yeah.

Lem   40:50
Like a custom ChatGPT that will trigger the hook and then it will pass like the message to this yeah.

Peter Wolf   40:56
OK, so let's I I I see the the full breadth of it and we'll figure out on the document the Google Docs part. I mean obviously this is all right now just kind of baseline function to get it working. Ken, let's focus on the on the spreadsheet.

Lem   41:01
OK.
Yep, that's right. Yep.

Peter Wolf   41:13
On the Google Google Sheets update because then that piece I'm also looking at alternative ways to feed the information in, right? So I talked about creating a front end app instead of using ChatGPT, but.

Lem   41:17
OK.
Yep.

Peter Wolf   41:29
There's some stuff for sure I would deliver through ChatGPT and other stuff that I think building the app, but it could call this same. It could call this same AI agent, right? So I put in the chat. If you go look at the chat, I put in a number of fields that for right now I want to start with.

Lem   41:34
Yep.
Yep, that's right.
OK, OK.

Peter Wolf   41:46
Right. Last name, first name, date of the last update, company, company name, formal title, role, relationships, other comments. I want to see how this is going to work out, right? Because I'm going to, I'm going to try and figure out how much, how many different.

Lem   41:48
Yep.
OK.

Peter Wolf   42:05
Kind of features or columns I need right? Data points segregated. I don't know if I can just dump a whole bunch of stuff in that comments section and then just have the AI brain figure it out or whether I need to be segregating some something like if I say.

Lem   42:10
OK.
Yep, Yep.

Peter Wolf   42:22
You know who was that person I met that had the black hair and the beard? Do I need a column that would be appearance so that appearance would be in there separately or can it just interpret all that from the comments? Now there's a few different ways I got to think about using it, right? One is when I'm actually communicating with the.

Lem   42:27
Yep.

Peter Wolf   42:41
The AI agent or with the front end with ChatGPT or with an app. The other is if it's in the spreadsheet and I want to go work through the spreadsheet, look at the spreadsheet, then there's a difference. You know, I mean potentially there I would want separate columns that were easier to look at.
Or understand, whereas the we're putting it all into the just in the comments field wouldn't make sense, right? Because I wouldn't be able to look through the spreadsheet and be able to get anything from that be too too much content in that one field. So if there were these separate kind of features.

Lem   43:15
Yep.

Peter Wolf   43:17
That maybe separating them out makes sense because I would be able to use it in kind of human interaction rather than AI interaction, right?

Lem   43:22
Yeah, yeah, we could just for example have here a filter for for example first name or a first name and last name and then it will find that particular person and then it will, yeah, it will just.

Peter Wolf   43:38
Right. But see, it's more likely. Here's the reality. It's more likely. I'm going to say, who was that person I met at that conference who was from, you know, booking.com who was talking about FX, right? So that's where I would be only giving a couple pieces of information and I would need it to.

Lem   43:39
Yeah.
OK.

Peter Wolf   43:57
Go and search the database to figure out who the name was and give me the name.

Lem   44:03
Oh, OK, I see. Yeah. So it's like.

Peter Wolf   44:06
That's the that's a real case right there, right? That's a that's a real case where I'm trying to retrieve the name of someone and I only have limited memory or, you know, of details of what it was.

Lem   44:09
Yeah.
Yeah, yeah, we could, we could just find it on the filter. So for example, like for example this one has.
Yeah, this is 12345678910 like 10 filters. We could just add it on the spreadsheet like the filters, right? For example the.
This one the find data, so let me just go to the find data.
Yeah, for example this one. So you have like a 1010 columns, right? And then here we could just add the.

Peter Wolf   45:04
Yeah.

Lem   45:11
Add the 10 columns yeah as or and then it will search uh depending on the output. So for the of course you would be like talking to the ChatGPT right? So the AI agent should get that context like uh what?

Peter Wolf   45:11
List them all out, right? Yeah.

Lem   45:27
It will it. Of course it will depend on the prompt. For example this one required information like we could just add here that ask for a one parameter that so that we could find it on our spreadsheet and then it will ask you like another question for example.
What parameter is it will it will like check. So if you said that for example the company that is coming from Twitter or something like that so it will yeah trigger the automation and then.
Like filter it out based on that uh data.
Yeah, based on the like the filter here for example the name or like you have custom custom columns there like the company like the yeah last name for formal title or something like that. But but yeah basically what will happen is if you like talk to the AIA.

Peter Wolf   46:18
Yeah, yeah.

Lem   46:27
Agent in like plain text as we are doing here. So it this is just like chat right? But what what is actually happening on the like the audio modality is it's still getting the the audio and it's actually transcribing it to text.
So so it's just also working basically the same and it it should like interpret it and get the get the parameters that is needed to trigger that automation. So if that makes sense.

Peter Wolf   46:57
Right. So let's let's try, let's let's work on that aspect, right. Let's take those fields I have and then take a scenario. I'll I'll put in a couple scenarios here in the chat. Like first of all, let's say.

Lem   47:03
OK.

Peter Wolf   47:11
I these are these are use cases.
1.

Lem   47:23
1.
2.
OK.
Last name, first name.
Sample.
So last name.
Think we can, uh, this is headers.

Peter Wolf   49:38
OK.

Lem   49:40
I forgot the.
Formatting here.
Um.
Yeah, this one I think.
Split text to colors, and then say bold.
Yes.
3.
OK.
All right, I would need to add it first. Uh.
Uh.
So.
To be.
Last name.
This name.
Company.
Date is updated.
And the.
The.
OK.
And uh.
Company.
Uh.
Formal title.
Um.
Roll.
Chips.
I know.

Peter Wolf   53:34
All right, so just put in some basic kind of scenarios.

Lem   53:41
OK.
In other comments.
Let's add this one.
This will work at a given company.
In Germany and you try those.

Peter Wolf   56:39
So on a separate note, Nick, you were saying you couldn't, you couldn't access the teams recording from Gilles.

Lem   56:40
Oh yeah, this.

Nicholas Westburg   56:50
Yeah, from the the Power Automate meeting that we had.

Bryan Wolf   56:52
Hey there.
Yeah.

Peter Wolf   56:55
Yeah, let me let me see if I have. He's out, so he won't be able to help us, but let me see if I can access it.

Nicholas Westburg   57:01
Is he in Florida or is he out of the States?

Peter Wolf   57:03
He lives in Florida, but I don't know where he's going for PTO.
This was Wednesday, right?

Nicholas Westburg   57:22
I think the third, yeah.

Peter Wolf   57:34
Was it Wednesday?
I don't see it. What does the date we have?

Nicholas Westburg   57:41
Third, I think.

Peter Wolf   57:44
OK, hold on. No, there would be there. That would still work there. Yeah. OK.

Nicholas Westburg   57:46
Yeah.

Peter Wolf   57:52
OK, I got it. Hold on, let me see what I can download.
Uh.

Lem   58:00
I mean.
Yeah.
OK.
I think it's better.

Bryan Wolf   59:31
This.

Peter Wolf   1:00:00
So tell me if this I just said to your Outlook accounts. Can you see if that gives you the link? Look like it only gave a transcript.
Oh, here, hold on.
Alright, see if you can get to that link now.

Nicholas Westburg   1:01:34
Yeah, I'm getting access to it. I just can't download it.

Peter Wolf   1:01:39
Well, I sent I I think I sent the transcript in the first one.

Nicholas Westburg   1:01:39
Oh, my.

Lem   1:01:40
OK.

Nicholas Westburg   1:01:43
No, it says contact Gilles, contact Gilles to grant you the same. So typically it's you when you when we're hosting these, but I guess since Gilles started, yeah.

Peter Wolf   1:01:45
Or was it only the notes?
U Yeah, but So what? It won't give you access. Let me see if I'm also owner here. So you when you click on it, you can't get to it or?

Nicholas Westburg   1:01:56
Yeah.
Yeah.
Yeah, it's just like whited out and it says contact Gilles.

Peter Wolf   1:02:11
Yeah, I'm see. I'm getting the same thing download. I can get to the you can get to the meeting and all. You just can't download the transcripts.

Nicholas Westburg   1:02:19
Yeah, the transcript. Yep.

Peter Wolf   1:02:23
Hold on.

Nicholas Westburg   1:02:38
Are you getting access to it or no?

Peter Wolf   1:02:40
Um.
I thought I was. I'm in. I mean, I'm. I'm in the thing. I can watch the video. I can. I can see the setup. Uh.
But it looks like when I try and download the transcript, it's grayed out.
And when I shared it, it just gave you kind of summary points, right? Not the transcript itself.

Nicholas Westburg   1:03:12
Yeah.

Lem   1:03:21
No.
No.

Peter Wolf   1:03:54
Yeah, ****.
And what does the message tell you? Say ask Gill to grant you authorization or something?

Nicholas Westburg   1:04:35
Yeah, that's what we ran into a while back, but with.

Peter Wolf   1:04:39
I remember that's where I had to put all of us on and and assign us all as owners, but it didn't do it historically, right? I had to do it only going forward. So I don't know what he would have to do just to even give us this. I guess he just downloaded and send it to us, right?

Nicholas Westburg   1:04:55
Yeah, maybe because he's also like an admin.
I do. I do.

Peter Wolf   1:05:26
So going forward, we'll just make sure one of you guys is always the one setting up the meeting.

Nicholas Westburg   1:05:33
I joined this morning and I think we have it on like auto.

Bryan Wolf   1:05:37
Wait, what do you mean we set up the meeting?

Peter Wolf   1:05:39
Like Gilles, Gilles sent that meeting up right now, but wait, when you guys set up a meeting or if I set up a meeting, then I think we're all admins to it.

Nicholas Westburg   1:05:40
And all the records.
Oh.

Peter Wolf   1:05:50
Or at least on my meeting, this meeting that we have, this recurring meeting, we're all admins to it.
I'm trying to remember. I had to go and ChatGPT and ask how to do that, but somehow I set it up so that we're all we all have rights to start the meeting, to record it, to download transcripts. We just need to make sure that's whenever we set up other meetings that we're always setting them up that way.

Lem   1:06:06
Oh.
Um.

Peter Wolf   1:11:13
I'm sending a message to Gilles asking him to download it.
I don't know if when they'll see it or how soon we'll get it, but.

Lem   1:13:15
No.

Peter Wolf   1:13:36
All right, I sent it.
Um.
Hopefully he'll get back to us and push it over to us sometime. Not, you know, today, but I don't. I really don't know. I don't know what his where he's at or what he's doing.

Bryan Wolf   1:13:50
OK.

Peter Wolf   1:13:56
All right, so where are we, Lem? Is Lem working still?

Lem   1:14:00
Yeah, I'm thinking because the the I mean the input for this one would be like dynamic. So I think I would use a different database for this one like Superbase or Pinecone and then.
Basically we will we will connect it to ChatGPT and then ChatGPT will query that database and then depending on the input it will extract the data from that database.

Peter Wolf   1:14:34
How's the? How's the? How's the? How's the Google Sheet different? Or how's the database different than the Google Sheet?

Lem   1:14:37
So.
Yeah, because the like the filtering for Google sheet is like it's not really like dynamic. Like you can't get like a like you can't.
Get different filters if you know. So basically the other databases has a functionality where in the we can get like a different. Basically it's like a different.
System for filtering the data. So for example on pinecone it's getting like the most relevant like for most relevant information depending on the data that is being requested. So.
Yeah, because the input here is like dynamic, right? Like you would need like a list of all the people in a certain company or like yeah, the like the name. Like for example this one's Sirala in HR. So we can't do this on Google sheet because.
Yeah, the filtering on Google Sheet and extracting data on Google Sheet is doesn't work.

Peter Wolf   1:15:50
Can it just because when I was looking at doing this before and I was talking to ChatGPT about how to do it, what ChatGPT was saying was essentially when when I would ask to retrieve information, it would just pull everything in the database, pull it into its memory and then.

Lem   1:16:04
OK.

Peter Wolf   1:16:10
Would do its work on that information rather than the database itself doing logic.

Lem   1:16:14
Uh.
OK, I like uh, we would connect the.
I like that, uh, like an Excel, right? You we would just put the Excel on ChatGPT. Is that is that right?

Peter Wolf   1:16:28
Yeah, essentially, essentially it would just pool everything that I have. Like, you know, if I had massive volume, then maybe that would be a problem. But I mean, at best I'm gonna have, you know, let's say a couple 100 names, so maybe 1000 names, right?

Lem   1:16:44
OK.

Peter Wolf   1:16:45
That's not overwhelming for Cha GT.
And even 1000 would be a lot. I mean, I don't even think I have 1000 in my contact list.

Lem   1:16:51
Yeah.
Oh yeah, basically we would put the.
We would put it on a custom ChatGPT I think.

Peter Wolf   1:17:06
Well, no, no. I was again, this is the way I was working through when I was talking with Chachi BG trying to figure out how I would do this right with make. And this was back before, you know, this is a while back when we were still early on and I was.

Lem   1:17:06
That uh.

Peter Wolf   1:17:22
It was saying, well the the spreadsheet, the Google sheet and the Chachi BT, I mean the and make wouldn't be the ones determining how to find what I wanted. It would at least this was and maybe the way you're approaching it is a better approach, but what it was saying was OK.
OK, if I asked to find some information or find a person's name, essentially it would grab all the information in the database, spit it back out to ChatGPT and then it would comb through it. Now the only problem with that is is tokens, right? If if we aren't doing that, then what we're doing is sending and receiving.

Lem   1:17:49
OK.
OK.

Peter Wolf   1:18:01
Um, you know, full data when it would be nice if I wasn't doing that right?

Lem   1:18:08
Yeah, yeah, let me just also show I think I I I can try it to feed the like a document. So I'll just let ChatGPT create a document and then we could add that doc here like the spreadsheet. As you can see we could add a file.

Peter Wolf   1:18:23
I don't think you're sharing anything. Are you sharing? I don't see anything.

Lem   1:18:26
Oh, um.
Oh, I think it bleached out. Let me just.
Yeah, I can't.
Mm.
Yeah, it's glitching out. I can share my screen maybe a little bit later, but yeah, the AI agent here also on make has like a contacts section wherein we could put an additional.
Like documents, I'm not sure.

Peter Wolf   1:19:19
Again, are you sharing them or are you just talking?

Lem   1:19:22
Yeah, I'm just. I can't share my screen as of now. It's glitching out my. Yeah, my.
My window can't actually whenever I click the share. So it's yeah, it's a.

Peter Wolf   1:19:35
OK, no problem.
Yeah, I mean, uh, you know.
So obviously what what I wanted to do is work. That's one thing. Then I wanted to be not consuming large numbers of tokens to do so. So if I'm sending the entire database every time I want to retrieve some information, that's not going to be efficient. So maybe your model.

Lem   1:20:01
Yeah, that's right. Yeah.

Peter Wolf   1:20:02
Of a database that can be searchable to some extent, but you you understand that the the search. This is why I was asking about how many columns because how narrow does a value have to be to be searchable and if the comments I was thinking of something really.
Loose, right? I could put this is somebody's husband. This is somebody's wife. This is, you know, it's the person I saw in the park. This is whatever. It's not structured at all. And that's where I feel like it wouldn't be the database being able to find that it would really be. It would have to be ChatGPT or or so.

Lem   1:20:23
Yep, that's right.
Yep.
Yep. So there's there's actually also a design like the like a vector database wherein for example on pine cone, the one that Nick also mentioned like the rug the retrieve. Yeah, the retrieval augmented.

Peter Wolf   1:20:41
Some other model.
Augmentation, yeah.

Lem   1:20:57
Generations of, yeah. So basically that one is actually like flexible on getting that data. So you could for example on the other other, yeah, other comments here, for example a black hair with a wife or something like 2 kids, something like that and then.

Peter Wolf   1:21:14
Yeah.

Lem   1:21:15
We would add it on the other comments section and then whenever ChatGPT will create. So there there's also like a design on N8 and whenever we create the the database it is using a brain.
For example like Chachi pity brain also that is that would basically get the nearest nearest information on the on what we want to find. For example that one then yeah so that's.
How I'm like I would approach it because.
Yeah, because this is like a like a flexible query, so I think.
Um.
Yeah, one way would be to feed all the data to ChatGPT, but I think that yeah, that would cost a lot of tokens.
So yeah, that would be much, I think much cheaper and much efficient. Yeah, so Yep, but I I haven't tried it yet on this make.com, so I think I will build it up on any 10 so that you would have a feel for it first.

Peter Wolf   1:22:15
Yeah.
Yeah.

Lem   1:22:29
And then I will just try and uh uh find a way to incorporate it in make like because I'm not sure if it.

Peter Wolf   1:22:37
You mean the database part of it or you mean the agents all together, the agent structure?

Lem   1:22:41
The.
Yeah, the agent that is querying the database because on it.

Peter Wolf   1:22:46
The agent is querying the database. OK, yeah.

Lem   1:22:49
Yeah, that's right. Yeah. So it's more intuitive on N 8 and as of now, I'm not sure if in make it's already like they have that intuitive. Yeah, so but yeah, basically the the end goal would be we will put on the database all the.
Like the data that is needed for example this one dot last name, first name, date of company, all of this one for the 100 hundred person and then based on the input on the AA agent what we are asking so it will find the nearest.

Nicholas Westburg   1:23:10
OK.

Lem   1:23:27
Uh, like the nearest data on that query and then it will feed back the data to us. So that's how it would. Uh, yeah.

Peter Wolf   1:23:33
OK, let's let's add another column. Let's just add another column appearance because I think it seems like that one.
Column for appearance, just because I think that might help it to differentiate, right? Because it would, it would definitely be something where I would do, you know, oh, they had dark hair or they had a beard moustache or something like that, right? So if we add appearance to it as well.

Lem   1:23:55
Yeah.

Peter Wolf   1:23:59
Um.
Yeah, uh.

Lem   1:24:03
Yeah, appearance. Yeah, so.

Nicholas Westburg   1:24:06
Lem, are you talking specifically about like the the vector database, like vector embeddings and whatnot?

Lem   1:24:11
Yep, Yep, that's right. Yeah, the vector database or Yep. So because it it it would be hard if we would use like Google sheet for the database because yeah, we would need to feed the whole.

Nicholas Westburg   1:24:14
OK.

Lem   1:24:27
Uh, like who? Yeah, the data set to ChatGPT so that it would dynamically get the data. And yeah, it would cost a lot of tokens if we do that one, so.

Peter Wolf   1:24:28
Data set. You'd have to feed everything, yeah.

Bryan Wolf   1:24:30
Yeah.
Yeah, too much.

Nicholas Westburg   1:24:39
Yeah, somatic similarity is really cool because it's basically like words and you know the embed like somatic like the the embeddings are nice because it's like OK, how do I reset my password? Or another query could be like I forgot my login credentials.

Lem   1:24:49
OK.
Mhm.

Nicholas Westburg   1:24:57
You know the words are different, but the meanings are similar and those are stored. So basically like every single word is represented as a number. So like when you have a.

Peter Wolf   1:25:06
Say that you went, you went like there. Say that again. So basically every time you.

Lem   1:25:07
OK.

Nicholas Westburg   1:25:11
So like every.
Every time that you like the words are difference, the meanings are similar, right? So their vectors are close in space. So when let's say you search with one, the other might be retrieved and those are like through the the embedding models or you know like pinecone for example. So think of the word.

Peter Wolf   1:25:17
Yeah.

Nicholas Westburg   1:25:31
Like Apple for example, it becomes a vector and it becomes a number. Like I don't know what that number is. It could be like point.

Peter Wolf   1:25:39
Right. But we don't, we don't, we don't have to give it that guidance. We put the information in. It creates the vector relationships.

Nicholas Westburg   1:25:44
No, no.
Yeah, yeah.

Peter Wolf   1:25:50
Yeah, OK.
OK, let's go with, let's go with that. I mean that's sounds good to me. It's pushed through prototype, but let's I would stay away from the for now. I wouldn't worry about the document to me. Those are totally different use cases, right? Yes, I want to go to ChatGPT and I want to be working on something and say save it as a document, but let's let's.

Bryan Wolf   1:25:54
OK.

Lem   1:26:04
OK, Yep.

Peter Wolf   1:26:11
Let's try and stay focused on this database management aspect and get to where we can dynamically analyze the content to give back a response. Again, I think this becomes very helpful not just for this scenario, but other kinds of scenarios, right? The ability to create a.

Lem   1:26:16
OK.

Peter Wolf   1:26:31
Database of information that you can that you can query. Thank you that you can query flexibly I think is you know is very good. The only issue here is that that database would be in the cloud and so again you couldn't use sensitive data there.
Right. So that's the downside to it, this model that we'd have to think about. But I think First things first is build a build a model that works, right. And then then we'll worry about storing your, you know, other models or how we would store more sensitive data.

Lem   1:26:51
Yeah, yeah, that's right.

Peter Wolf   1:27:09
Let's get something that functions first.

Lem   1:27:09
Right.
OK, OK, got it.

Peter Wolf   1:27:12
OK.
All right, so I'm gonna, I'm gonna drop off guys. I uh, I got a webinar I need to prepare for. Um.

Bryan Wolf   1:27:22
OK.

Peter Wolf   1:27:23
Uh, yeah. So I mean, I would say if you keep working with Lem, just as as you go through this, this seems like.

Bryan Wolf   1:27:28
I'm gonna stay on, I'm gonna stay on. And then I know you should get some for 11. After that I'm gonna try and really like hone in on the rest of our flows. Some of the stuff's not clicking or we had some problems with stuff on my account I'm gonna fix up. And then I also think I'm gonna take a little time to try and.

Peter Wolf   1:27:31
Yeah.
OK.

Bryan Wolf   1:27:44
Fix some of the I know Ranger stuff or just work with that a little bit to be able to pull a little bit better information.

Peter Wolf   1:27:47
Yeah, that one we need. We really need to get together and I will work through that. And I was thinking maybe I could have have you also maybe work with Bart. I realize I haven't really been having those guys engaged at all. Bart could probably work with you on on that stuff.
Also, Nick, I got to send you that that chat that had the process flows. It's been a while since I even looked at it, but I'll try and find that and send that over to you. And but I think, yeah, Lem, if you can focus on pushing forward with this.
And we'll see where we get to, OK.

Lem   1:28:20
OK, no problem.
OK, copy.

Peter Wolf   1:28:25
All right. Thanks, guys.

Bryan Wolf   1:28:26
Yeah.

Nicholas Westburg   1:28:27
Yeah, have a good day.

Peter Wolf   1:28:28
Talk to you there.

Lem   1:28:28
You there. Talk soon.
OK, so what was the problem right on your?

Bryan Wolf   1:28:40
Well, I just, I need to contact Google today for my Google Drive. I gotta I gotta make a new Google account I think instead. I just I've been doing all the flows on Peter's account and I need to just switch them over to my account is really what I need to do. And then I kind of just want to like mess around with the HTML formatting a little bit.

Lem   1:28:44
Oh, right. Now the Google Drive, right? Yeah.
OK, I see.
So the the.

Bryan Wolf   1:28:59
I don't know.

Lem   1:29:00
Did they really uh they did they block the that e-mail uh for on the?

Bryan Wolf   1:29:04
I don't know because I I tried last night. I I tried again last night to post on my LinkedIn and it still won't work. It's still. So I think I I have another e-mail I'm just gonna start plugging in instead and I just use that instead. Yeah, but I need to go through and do those and set that up and then I gotta set it up for Peter Junior too.

Lem   1:29:16
OK.
Oh, yeah.

Bryan Wolf   1:29:23
So really, that's it. I'm just gonna go through and copy and paste all my flows from later on. Peter's account. I'm putting along my account and Peter's account. My account is.

Lem   1:29:23
Yeah, there.
OK, no problem.

Bryan Wolf   1:29:37
Yeah, other than that, I think I ran into something else. I don't remember.
Friday.
And.

Nicholas Westburg   1:29:52
Alright guys, I gotta run. Thank you Brian. Talk to you later.

Lem   1:29:54
OK, Nick. Thanks. OK, talk to you.

Bryan Wolf   1:29:55
Yeah, I'll talk to you. He will.

Nicholas Westburg   1:29:56
Have a good one. Bye.

Lem   1:29:59
Bye, bye.

Bryan Wolf   1:30:02
I'm just looking and see what happened. I remember what happened. This is like Saturday night. I was tweaking on this.
Yeah, I don't know. I I don't. I don't know. I gotta. I have to. I sent an e-mail to Google like when it first happened and didn't get back to me. So I think I'm just gonna use a new e-mail.

Lem   1:30:20
Mm.

Bryan Wolf   1:30:23
Shouldn't be a problem. I just gotta make sure I got all the right.
All the rights. What's the freaking stuff that we put on there for Google console? Like all the right verification for the clients, whatever it is. But Lem, honestly, I don't need your we're good. I mean, I don't. I don't need to keep you if you want to get off and just, you know.

Lem   1:30:39
Yeah, the console.

Bryan Wolf   1:30:49
Enjoy the rest of your night. Or if you have another call, maybe take some free time to to take a little nap, you know?

Lem   1:30:53
Yep. Yeah. I still have a call later. Yeah. Yep.

Bryan Wolf   1:30:57
I know, I know. Maybe get some coffee, some some tea, some biscuits. You know, it'd be good. All right. I'll talk to you tomorrow morning or tomorrow night. I'll talk to you tomorrow night. Yeah, I'll shoot you. I'll shoot you one of our only problems. But I I think for the most part, it's just like, it's gonna be pretty. Just copy and paste most of the stuff. So yeah.

Lem   1:31:00
Yep. Yeah, that'll be good. Yeah.
OK.
OK, just e-mail me if you yeah, just e-mail me if you need anything, Brian.
Okay, no problem. Okay, see you, Brian.

Bryan Wolf   1:31:18
See you then.
Have a good rest of your night, all right?

Lem   1:31:22
OK. Thanks. You too.

Peter Wolf stopped transcription


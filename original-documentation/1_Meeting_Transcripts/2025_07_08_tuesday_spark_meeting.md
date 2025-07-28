# Process Automation Workshop (23)

**Original File:** Process Automation Workshop (23).docx
**Extracted Date:** 2025-07-08 (Tuesday)
**Converted:** 2025-07-28 11:40:46

---

Transcript

July 8, 2025, 12:58PM

Bryan Wolf   1:31
Peter, are you in there or is your taker?

Peter Wolf   2:00
Hey, Brian.

Lem   2:07
Hi, guys. Morning.

Peter Wolf   2:10
Hello.

2:10
Morning.

Bryan Wolf   2:14
Hey, are you, are you back yet, Pete? Sorry, I thought I was on mute.

Peter Wolf   2:16
It.
No, I'm gonna, uh, I'm gonna be heading up today.

Bryan Wolf   2:22
OK.

Peter Wolf   2:22
And then tomorrow I'm only in 1/2 day and then I leave for Germany, so we'll have to figure out what's going on. Say what?

Bryan Wolf   2:28
Tomorrow night.

Peter Wolf   2:32
Now my flight's at like 1:00 in the afternoon.

Bryan Wolf   2:36
Tomorrow.

Peter Wolf   2:38
Yeah.

Bryan Wolf   2:38
Alright, so I think tell me whenever you're coming back, we should go over like what what we want to do while you're away.

Peter Wolf   2:42
Alright.
Yep.

Bryan Wolf   2:47
OK.

Peter Wolf   2:48
All right, Lem, can we see where we're at?

Lem   2:51
OK, um, uh, let me just, uh, share my screen.
Yeah, so.
Yes. So based on what you said yesterday, So what I did here is I approach it.
Two different on the two different ways. So first is this. This particular agent is just I've yeah just finding the data on the Google sheet. So what I did here is I've added a.
Test data. So this one with a last name, first name, date, date of last update, company, all of the columns that you've given and then I've downloaded it as a CSV file and then I fed it here to.
ChatGPT and yeah, so he was able to get like a flexible query because of course what is happening here is it's like it's also I I think in the prompt, so it's.
It's accessing it also via the prompt, so that's why it can access it. And I've checked the like the token consumption is for the 505054 leads with like.
9 columns so it's just 3500 tokens. So if we have like a 100 list here so it would be like 7000 so it would be .035 per query .035 dollars so.
For example, we will have like a thousand 1003, so it would be.
Yeah like $35 for the thousand query and then this is using ChatGPT 4. So for this one I use ChatGPT 4O mini so that is the for the usage that is the 3500. So if we test it now for example.
Let's go to the database.
Like, uh, appearance.
Uh.
Researcher with a casual appearance. So for example researcher with a casual appearance. So can you find me the persons who has the?
Like casual appearance and uh, what's that again?

Peter Wolf   5:46
Researcher, I think you said.

Lem   5:47
Like and with the role of researcher. So yeah, ChatGPT will access also the database then it will yeah generate this one. So for example Thomas Bryan, so company casual.
Uh.
So if we double check so Thomas Bryant if we check here on this one so Thomas Bryant with all the details company researcher. So here comments friend trial dip.
And then yeah, so this is one way to do it. And then the other one is let me just save this one. So I so that one is just like on the prompt, it's just doing the database like because I've added the document there but.
We could also do like the one that I've added yesterday. We could just add like a primary function here where in it will search it will search the data Google sheet and then it will trigger the the.
The automation and then on the automation. So basically it's doing the same. So the automation it looks something like this. So I've edited the test.
Uh, the search. Yeah, this one search Google Doc.
Uh.
Uh, search. No search uh Google sheet. Just a search Google sheet. So.
Yeah, find it at the Google sheet, so.
Yeah, this one. And then this is also using basically ChatGPT 4 O and then yeah, I I think I've used the 40 min a while ago and then yeah, so it would basically it will search all the rows and then aggregate the.
Text and then feed it to ChatGPT. So for this one it's yeah, it's actually you. The usage is 7000 tokens for 101 hundred for the.
3500 for the 50 columns. So that's where I based it. And yeah, this was, yeah, this is GPT 40. So if we use GPT 4 O mini it would be much cheaper. So I thought this is GPT 4 O mini then yeah, so the access of here is coming from the like the test agent.
The yeah the AI agent here, so it's just doing the same like the querying the Google data sheet, but this would be like dynamic. We can do it as dynamic because it's actually getting all the data and then aggregating it and feeding it to ChatGPT.
So our message is also with on here on the input. So as you can see query. So we also have here the query on the ChatGPT prompt. So we have the message input query.
So yeah, yeah. So basically I've I've designed it this one because I've tested it on N 8 N So this is when we do something like that on N 8 N it will be something like this. It's just different formatting but we will like have a chat, chat message and.
That the AI agent is connected to a brain like a ChatGPT and then it will create the like super base. So I'm using this a super base database and then I've checked the logs and it's also getting all the like the rows and feeding it.
ChatGPT. So basically it's doing what you also said yesterday that we feed all the rows to ChatGPT. So Yep, that's how I approach this one.

Peter Wolf   9:56
All right, so a couple questions. You had talked about using pinecone. You just determined that wasn't really gonna work. That approach of trying to have the database do some of this work so it wouldn't have the wouldn't be sending everything to ChatGPT to process and using the tokens.

Lem   10:14
The because I've tried to, I think it was a different for the like a vector search. This is like a tabular type of data so it would be like a different.
Yeah, like a different format. So that's why I've used the like if you can see the this is like the super base database. So it's also like tabular the same as the like the Google sheet and when I've checked.

Nicholas Westburg   10:46
Super bass is really good.

Peter Wolf   10:47
This is what this this is what you used for the for the make version or NAN or they're the same.

Lem   10:51
The N8 N yeah yeah this is for the N8 N and we could also use this on like on make, but basically it will still be the same as this one, so it would.
Query all the rows so there's no like choice there like a like a flexible search parameter. So what will happen is we would just.
Yeah we'll add here so like select rows from a table and then it this is like would be like a chat GP like a Google sheets and then it will add a row to aggregator and then feed it also to ChatGPT. So basically it would.

Peter Wolf   11:36
Right, so it's just a it's just a replacement of the Google Sheets. The Google Sheets is a database. Instead you got this other what you said something SQL, small SQL or something.

Lem   11:37
Yeah, yeah, that's right. Yeah.
Yep.
The platform is Supa based, so this is just like the tool that is like yeah, PostgreSQL for the for connecting the particular table on Supa base. But yeah, if we.
Yep, that's it. So yeah, So for I think we could if you because you said that this particular use case would just be focused on like the.
Querying the Google sheet or like the database. So I think this particular particular like design would be much simpler so it would just query the like the database and then.
Yeah, we we just create the database so it won't. Yeah, basically it's much simpler to like like to duplicate and we just add the prompt and then copy the prompt and then add the database.
So yeah.
And then, yeah.

Peter Wolf   12:53
Yes.
Yeah, I'm just wondering what this and I I know you said 1000 attempts would only would cost me $35.

Lem   13:05
Yeah, for 1000. Yep.

Bryan Wolf   13:06
Yeah.

Peter Wolf   13:06
But yeah, but I'm looking at OK, So what if my what if my list is again? What if my list is 500? That's 10. So then it would cost me $35 per hundred attempts, right? Yeah, and I'm. I'm just trying to find out where I export my contacts. I wanna see how many.

Lem   13:14
Please.

Bryan Wolf   13:21
Yeah.

Lem   13:21
Four. Yeah, that's.

Peter Wolf   13:26
In my contacts right now and I know I don't.

Bryan Wolf   13:27
This is just your contacts on like your Excel sheet that you have in there or or.

Peter Wolf   13:31
No, this is I'm gonna look at my in my e-mail contacts, for example, because first thing I would do is take everybody in my e-mail contacts and put them in there, right? And I would use this much more actively than I even store stuff to my e-mail contacts.

Lem   13:33
2.

Bryan Wolf   13:39
Yeah, OK.

Lem   13:40
Yep.

Peter Wolf   13:46
Um, and I'm trying to hold on. Where do you export your contacts? More items file?
Open export.
Open output data file export.
Uh, choose RSS 3V card on calendar.
Record.
Export to a file. Export Outlook information to a file for use in other programs. Next.
Outlook data file PST. Hold on one second.
M.
Chad, I want to export my contacts from Outlook desktop version. How do I do that?
Exporting your contacts from the Outlook desktop version is pretty straightforward. You just need to open Outlook and then go to the File tab in the top left corner. From there choose Open and Export and then select Import Export. In the Import and Export wizard you'll wanna pick Export to a file and then choose comma separated values. After that you just select the.
folder and pick where you want to save the file and that should do it. Perfect.
Contacts.
File.
Sorry guys, give me a second. I don't wanna. I don't understand any about this.

Bryan Wolf   15:56
The trip.

Lem   15:57
Um.
OK.

Bryan Wolf   16:27
Hmm.
You trying to import all your contacts from Excel or your e-mail? Yeah, yeah, export, export.

Peter Wolf   17:41
I'm trying to export. I want to be able to count them. I'm trying to export them to Excel and.
So I can see how many I got.

Lem   18:30
I think this is also possible now with the custom GPTI think with because you will just add like the excel file.
Well, much seems there also that way.

Peter Wolf   18:42
Yeah, but with the that's not gonna help me in this particular case, right? I mean, with this particular use case, it it.
With this particular use case, right now I said I would start with the custom GT, but if you use that, you still have to feed the spreadsheet to the custom GT. So you're going to use the tokens no matter what, right? Whether you feed it to the GT inside the assistant.

Lem   18:59
OK.
Yep, yeah.

Peter Wolf   19:09
The agent or whether you feed it the other the secondary way where you extract it and feed it to a separate GPT, not the agent, or if you feed it back to to to my custom GPT, every one of those is going to use the same account, same amount of tokens.

Lem   19:25
Yep, talking up.

Peter Wolf   19:26
To consume the information. Now first of all, you talked about going to a four O mini, which I would say we should be able to use really whatever the lowest cost approach is because this is not complex analysis, right?

Lem   19:40
Yep.

Peter Wolf   19:42
And what's the difference in cost between 4040 mini or what other models do they have as far as like cost comparisons, you know?

Lem   19:42
Yep, that's right.
Uh.
Yeah, yeah, it's the cost is I think a pretty, yeah, the gap is yeah for GPT 4.1 because we were using.

Bryan Wolf   19:57
Sleep.

Lem   20:06
Uh.
We were using GPT 4.1 for the content so as we can see here on yeah this is $2.00 per one 1,000,000 tokens so for the GPT 4.1 but yeah this is their best model for now and then.
Yeah, the because of 4.5 is I think was deprecated then for the 40 mini this is like.

Bryan Wolf   20:36
Is that the one that you use the most?

Lem   20:38
It's much more. Let me just.

Bryan Wolf   20:42
Isn't during her back here was bunch.

Peter Wolf   20:46
I mean right away on that first screen you saw GPT 4.1 smartest model for complex tails is $2.00 per million tokens. Cache shade input is $0.50, but the GPT 4.1 mini was $0.40 per million tokens, $0.10 per million.

Lem   20:47
Uh.
Yep.
Yep, that's right. And yeah, we also like if we use nano, yeah, .1 per one M.

Peter Wolf   21:05
And the Nano, the GBT 41 Nano is only $0.10.

Lem   21:09
Yep, per one M tokens.
So yeah, this would be, I think the four O is much cheaper also for this one. But yeah, they didn't already, they didn't put the four point, the four O here. So that was an older, yeah, this one GPT 4 also.
Yeah, the four omen is actually, yeah, .6 per one M so this is much cheaper now the 4.1 nano. I think we have we could use this one. Let me just but.

Peter Wolf   21:39
Hold on, go back. Let me screenshot that. Go back to the 40.

Lem   21:43
Uh, the 40 here. Yeah, this one.
So 4 oh mini.

Bryan Wolf   21:54
The menu's what we test most of our stuff on. I get like whenever we're sending it up, we need to test with menu. I don't even know if we switch back to.

Lem   21:59
Yep.
4.1.

Bryan Wolf   22:05
Afterwards.

Peter Wolf   22:06
Well, no. The 40 mini looks like it's still more expensive than the four one nano. Four one nano is $0.10 and four one mini 40 mini is $0.60.

Lem   22:12
Yeah, well, but.
I'm not sure if they, yeah, they already have 41 nano, but yeah, I think, yeah, we could use the 4.1. It's much, uh, cheaper this one.

Bryan Wolf   22:30
Yeah, so this flow is working though, right? Like if we if you import your contacts, this works like we it's good, right? OK, OK, OK.

Lem   22:30
And yeah, most cost effective, yeah.
Yeah, that's right. Yeah, it actually works. It's just the yeah, it would be the token usage only. Yeah, that's right.

Bryan Wolf   22:40
It's the pricing that we're worried about. Yeah, OK.

Peter Wolf   22:42
OK. So let's recalculate this pricing. If I had a, if we're saying that we had in the way you set it up, it does, it may have substantially less in that comments file, I mean column than I have, but let's just say it's a 1000 names.

Bryan Wolf   22:49
Sorry.

Lem   22:56
Yep.

Peter Wolf   23:00
With the 9 columns kind of using what you had as an average there, then it would be calculate that again. What was the what was the total number of tokens or words you were sending for yours?

Lem   23:08
Uh.
So it was 7004 for 100 and if this is like the complete, yeah, total, yeah.

Peter Wolf   23:20
Sending the entire database again at the size you have, right?

Lem   23:24
And then yes for this the for the 50 it was 3/5, so 3/5 and then if we put that to 100 so it'd be 7000 so times 10 would be 70K.

Bryan Wolf   23:35
Mm.

Lem   23:40
And then if we use the 4.1.

Bryan Wolf   23:46
Y * 10? Wait, why? Why times the 10? Why we're doing 10?

Lem   23:47
I.
Uh, yeah, because uh, if we have 1000 contacts, 1000.

Bryan Wolf   23:56
Oh, right, right, right. OK, whatever. Actually, I don't know. Yeah.

Lem   23:58
Here on the database, yeah, but I'm not sure. Yeah, I think we could also let me just add it on the.
And yes, so it would be.
Yeah, much cheaper. So 70K maybe a like a .3.
Uh, catch it out.

Peter Wolf   24:25
Why? Because you were just looking at output tokens, but output would be minimal for us because we're only sending out a small mail, but it's the input, right? So $0.10 versus $2.00, so .0 is 5 percent, 5% of that.

Lem   24:33
Yeah, the input is, yeah, would be .0.
Yeah.
Yeah, 70K.
The right one.
Yeah, like a.
Like like seven, yeah, 7% of .1, so like a .007.
Yeah, like 5% of.
Uh, one cent.

Peter Wolf   25:04
Right. So if that were really the case, 5%, then we're saying it was $35 for for 1000 at 50, right, for 50 contacts 1000 and that's what I'm assuming mine will have more.

Lem   25:06
The five to seven. Yep, five to seven cents.
Yep.

Peter Wolf   25:19
More just generic information in there, so they'd be larger, but let's just stick with that. So 35 for 50, that was $70.00 for 100 * 10 would be times 10. So we said $70.00 per 100, so times 10 be.

Lem   25:22
Yeah.
Uh.

Peter Wolf   25:38
$700.00 that was for 100. I mean that was for 1000, $700.00. Then by 10% would be 75% would be 35. We're back down to $35 for 1000.
At 1000 contacts.

Lem   25:55
Yeah.
Yeah, and I also check. Yeah, get that.

Peter Wolf   26:00
OK. So I think we, I think we move forward with trying to build this or fill it out that I I get my contacts in there and then we see what this really is consuming. And so let me ask you this go back to because I'm trying to understand how, how.

Lem   26:08
OK.

Peter Wolf   26:17
Hello.
Explicit certain information needs to be and whether that's you making it explicit or whether that's the the A I brain making a specific like where you put peer and then you put the peer in the person's name. Did you put it in that format or did you say this person works with Regina and they put it in peer colon?

Lem   26:26
Um.
This one.

Peter Wolf   26:40
And the name.

Lem   26:41
I know this database was. I just asked this from to create like a fake. Yeah, yeah, that's right. Like a fake.

Peter Wolf   26:46
You ask it to create some database. So what happens if right now?

Bryan Wolf   26:47
Mm-hmm. OK, OK, OK. We could probably just put that in the code though, or in the in the in the prompt.

Peter Wolf   26:53
Well, what happens if you tell it? Yeah, I mean, I think you're gonna have to. We're gonna have to tell the the prompt, the brain, to say that it should store that with peer. What if you wrote right now, if we created a new contact, the problem is you can't say it. So you're gonna what if you wrote it in free form?

Lem   26:53
Because.

Peter Wolf   27:10
Like if I talked it in free form and see what it does with it. So if I say you know, add the add the contact Ann Smith, she works at booking.com. Can you just plug this in the way I'm I'm gonna say it if you just plug it into.

Lem   27:11
Uh.

Peter Wolf   27:27
For the create, yeah.

Lem   27:29
Here yeah we we would use the other one. So this one as of now doesn't have like the add the.

Bryan Wolf   27:29
Vince, yeah.

Peter Wolf   27:38
So you don't know what how it would how it would handle this?

Lem   27:40
Add to Google sheet.

Bryan Wolf   27:41
Yeah.

Lem   27:42
No, because this is like a static database, so I've fed it the like a file. This is not actually connected here.

Bryan Wolf   27:51
Let's test the other one again. Test with the other one.

Lem   27:53
Yeah, so the other one is much better for. Yeah, this is so that's why I've also created this one. So the the other one would be much better. It's much dynamic. So this one is actually connected with the Google sheet because it's connected with.

Bryan Wolf   28:06
OK.
Yeah.

Lem   28:13
This particular automation, so this is like a live live data sheet. Let me just.

Bryan Wolf   28:14
Um.

Lem   28:21
Yeah, so whenever we edit this database, so the Chachi PT also would would get that one. So I think this is much more.

Bryan Wolf   28:34
Excuse me?

Lem   28:35
Um, so for for the adding of of data, I actually already have it here. Let me just change the.
Uh, this one. OK, so.
Yes, you can see we have the.
Add data to Google sheet here.
Um.
Oh.

Peter Wolf   29:12
And then this one you have the same structure Google sheet.

Lem   29:16
Yeah, that's right. So I we have the as you can see on the prompt here, ask for the complete parameters that is needed, which is last name, first name, date of last update, company relationships, other comments.
Then let me just, uh, change this also to 4.1.

Peter Wolf   29:34
OK, but and this is where it gets into the details, right? I'm not always going to have content for every field.
So this is where I again, I think we need to work through stuff and I wasn't worried about the the granular details when we're just getting a prototype working. But what would happen is we'd have to identify what fields were mandatory, what fields were.

Lem   29:43
OK.

Peter Wolf   29:59
You know, optional and and so if if a field was mandatory and I didn't give some information then it should say well I need this information. But if it's not a mandatory field, so like first name, last name, the the reality is I might even not know the person's last name. I might only know their first name, right?

Lem   30:10
Yeah, that's right.

Peter Wolf   30:19
And I might store it with their first name and some supplemental information, say, you know, Ann's Ann's husband name is Joe and I don't know his last name or Ann's neighbor's name is Steve and I don't know his last name. And I just put it in that way. And so I would think that really.

Lem   30:20
Oh, OK. Yeah.

Peter Wolf   30:37
Really, probably the only thing I have to have is is otentially a first name, or at least one field of the name.

Lem   30:39
Yeah.
Yep. Um.
Yeah, I think we could bypass that one. Just I'll add some prompt that it will. If like the last name is empty, it will just input NA like that or something like or like or yeah like unknown so that because the other automation would error out if like the.

Peter Wolf   30:58
We're unknown. I say unknown.

Lem   31:06
Parameter is not there because it it needs the parameter so that it would.
Yeah, it would not error out as you can see here, so that you would have more contacts on the add data to the sheet.

Peter Wolf   31:20
So tell me again why you think in the two different models you have, was this you were trying to figure out which one was going to work or are you still trying to figure out? Because we know from a from a usage of tokens they're the same with the model where you're using the A I brain inside of the agent.

Lem   31:30
Uh.
Yeah, uh.

Peter Wolf   31:39
Isn't that the more efficient one than sending it externally to the AI to the AI brain, right? If the agent has the brain inside of it?

Lem   31:40
Yeah.
Yeah, the yeah, the only the yeah, the bigger biggest difference here is it's the information here is pretty static. So I've like hard like it's like.
I've input like I've given him the ChatGPT like a static file so we can edit this one through the through the here because there it it doesn't have like that capability.
For the tool. So uh, what I was thinking here.

Peter Wolf   32:20
I'm not sure on file. I'm not sure. So again, you're you're saying you fed the database, you're not actually building or retrieving the database, you're saying you're feeding the file to it?

Lem   32:25
Uh.
Yeah, so uh.

Peter Wolf   32:33
I don't understand what the difference what you're what you're trying to emphasize here.

Lem   32:35
It's just that it this is like a simpler build right? But the only cons here is the database is static. So what we need to do if we update the database is we would need to delete the database and then add the new database here.

Peter Wolf   32:54
OK, that's not going to work. That's not going to work for me, right? But the database is absolutely going to be dynamic. Really, that's the whole idea is I need to be updating this on the fly and just adding information.

Lem   32:56
Yeah, so.
Yep, that's right. Yeah.
OK.
Yeah. So, yeah, the other one is much more, I think, this much more robust and it's much more flexible and we could like add the.

Peter Wolf   33:17
And this is the one that uses the agent with the brain inside the agent.

Lem   33:17
Add.
Yeah, yeah, it's using the like the ChatGPT brain to get the particular tool on what to trigger. And then yeah, I could just remove the Google Doc documents here so that we could focus on the Google sheet. But yeah, basically what will what happens here is.
It will analyze our message and then depending on the context of our message, it will find the particular task and then it will trigger that task here or the tool. So the and then.

Peter Wolf   33:56
Yeah.

Lem   33:58
So when we find.

Peter Wolf   33:59
OK.
This one's clearly the one we need to go with. We're not going to have a static database, right? And what you're saying is, again, the AI brain, the ChatGPT is inside the agent here in make. It's not sending it out separately. It's already embedded inside this agent, which is.

Lem   34:05
Yeah, this is uh, Yep. OK.

Bryan Wolf   34:07
Yeah.

Lem   34:14
Yep, that's right. Yep.

Peter Wolf   34:19
Doing the routing, determining where to send or what what process flow to activate, right? OK, so let's go to pretend I was just giving it information to feed in. So if we use if I use ChatGPT front end or if I used.

Lem   34:26
Yep, that's right. Yep, that's right.
OK.

Peter Wolf   34:38
If I created an app that was going to interface with this or interact with it and it was going to be the mechanism I would feed information in or retrieve information out, then it would just take my words as I speak them and.

Lem   34:57
OK.

Peter Wolf   34:58
Deliver them to ChatGPT inside the agent and it would have to then parse that information and populate it in the spreadsheet. And this is the part where I'm trying to understand is how how explicit do I need to say? Do I need to say peer?

Lem   35:07
Yep.

Peter Wolf   35:14
You know, or if I say the person works with John Smith, is it going to be able to interpret that or we're going to have to put it in the prompt to say if I say he works with John Smith, that means that's John Smith's peer or how is it going to handle that, right. So like right now if you just say add, add John Smith.

Lem   35:27
Oh.
OK. Yeah.

Peter Wolf   35:34
Smith to the database and he works with, you know, ants and whatever, and he's at booking.com and he's in the HR department. If it took that, would it be able to handle that? No, it would have trouble with that because it doesn't really know.

Lem   35:38
Yeah.
Oh, I see. Yeah.

Peter Wolf   35:53
How to split into those columns? Doesn't understand what the column logic really is.

Lem   35:58
Yeah, I yeah, I think, yeah, that would be needs more.

Peter Wolf   36:05
So we'd have to give much more definition to tell it. If I say somebody works with somebody, that means that's the relationship. It's a work relationship and it should go into the relationships column. If I say they're they're related to or that's the son of or husband or wife.

Bryan Wolf   36:05
A little difficult.

Lem   36:06
On.
Mm.
Yep.

Peter Wolf   36:22
Of that should also go into relationship, but we would have to write all that out into the prompt, into the definition of the prompt.

Lem   36:24
Yeah.
Yep, Yep, that's right. In the the prompt. Yep. Yeah, basically we yeah, I would need to rebuild this whole prompt and focus just on the like the adding data, especially the adding data. So it would need more context. So this one is just a pretty simple. It's just.
Asking for these parameters and then yeah it would if if the input is like in plain words, we would need to add some like rules or like context here like for example on relationships.

Peter Wolf   37:00
I got. I understand. I understand. Do me a favor. Cut out your entire prompt there, everything you have, put it into the chat and then let's just work through some of this. I'm gonna pull up ChatGPT and I'm gonna work through it in my the way I would work through this and I think just.

Lem   37:01
Uh, yeah, yeah.
OK.
Uh.
OK.

Peter Wolf   37:17
You know, let's work through making the sausage right now, and then we'll get somewhere closer to what I need.

Lem   37:18
Uh, let me just.
I.
OK, let me just remove the two functions here so that it's more.
Because this has also like the Google Docs and create articles. Yeah, so we just yeah, we would just need to add more context on the task too.
OK.
And let me just add this to the.

Peter Wolf   37:53
Just sort of side note, I don't know, Brian, you know we were using the the audio modality for talking to ChatGPT on the PC. It's different than on the phone, right? And what? What? Yeah, I know. So I have been using it a bit more and the other day when I did that.

Bryan Wolf   38:03
Yeah, I don't really use it as much.

Peter Wolf   38:12
It switched to the new audio like instead of just that little, that little, um, you know, line going across the bottom of the screen where it shows you squiggles that it can hear you talking.

Bryan Wolf   38:23
Oh, wait, are you? Are you talking about speaking to like the live circular, like agent that's responsive, or are you talking about the line that records?

Peter Wolf   38:27
Yeah, yeah, it.
The line that records and then turns it into text is that what we were seeing, right? That's what I'm still seeing. Well, hold on. So when it's doing that, then you click the button, it turns it into text and you hit the button again and it feeds it in, right? But the other day when I was, I was working through a whole bunch of stuff and then all of a sudden I clicked the button and instead of going through that.

Bryan Wolf   38:35
I like that the most.
Yeah.

Peter Wolf   38:50
Little line, it went to the new audio modality, but it only did it that one time and it was talking back to me. You know, with the with the model with the line going across, it doesn't talk back to you, it just gives you the regular output. And so I don't know what the hell that trigger was or whether it was just in a kind of test mode or something that it switched.

Bryan Wolf   39:06
Might have been a glitch. Honestly, it might have been a glitch.

Peter Wolf   39:10
Over to that, but it's not coming up like that anymore. I like that. I prefer that version.

Bryan Wolf   39:13
I bet you it probably just glitched. I bet you it probably just like it activated the other one while you were recording and listened to you while you were still recording the line.

Peter Wolf   39:21
Yeah, but I would.
Yeah, I don't know. OK, so let me let me pull this up. You just plugged it in to the chat.

Lem   39:30
Um, Yep.

Peter Wolf   39:34
Uh.
Yeah, I'm sharing my screen.
Yeah, I see my screen.

Lem   40:16
Yep.

Peter Wolf   40:17
So this chat as name.

Bryan Wolf   40:17
Yeah.

Peter Wolf   40:51
OK, so I want to create a process flow agentic process flow automation and I'm going to load to you the current definition of the agentic brain in make.com. So hold this and then I'll give you further instructions.
So I just lugged in what he had.
OK, I'm going to switch over and see if I can do audio on my phone and see how this works here we can if it's functioning right now.

Bryan Wolf   41:50
Uh.

Peter Wolf   41:54
'Cause I prefer to do it this way.
Chat, you there?
Here, let me know what you'd like to do next over if you have any updates or our process flow. OK, so keep your answers very tight, concise. I don't want a bunch of fluff, right? Let's just stick with the content. Very quick, short answers unless I ask for more comprehensive response. So I just gave you data information about this agentic process.
Process flow for a name file or let's say a personnel information file database that I want to be able to store information in and retrieve information actively. And my intention here is we're using this so that my poor memory will be supplemented by a strong.
Agentic process flow that would give me retrieve for me information that I can't remember or that I don't have not stored in a comprehensive way. So let's say for example I meet someone at a event and they tell me their first name. I capture their name and I know the company they work for.
And some other miscellaneous information. I remember they had a beard and and that they were they were also interested in agentic process flows. And so I wanted to store that information and I want to, I want to deliver that information into this process.
Flow using just common discussion and speech. I don't want to structure it and have to give very detailed structure, which means I think the prompt is going to need to take my common speech approach and break the information down structurally into the database.
Fields O take that. Hold one second and I'll give you more information.
Goal is to make the process flow intuitive and flexible so you can simply speak naturally and the system will handle structuring and storing, right? So let's so let's take, let's take a couple of examples. Currently we have these fields in here where we say relationship and other comments and role and formal type.
OK, so formal title, pretty clear, at least for me. I would normally be talking about the business title, right? Senior executive, senior VP, managing director, cash manager or actually?

Lem   44:20
Call.

Peter Wolf   44:25
The cash manager would probably be role more than it would be title. And so here the difference between role and title, we'd probably have to give some clarity to the system, to the prompt to differentiate that. What is a role? What is a title? Now you know, Mr. and Mrs. I'm not really so concerned with that. They're pretty.
You know, you differentiate that easily enough. I'm more thinking about business titles and roles. Well, their title let's say would be manager. Their role would be HR, right? Managing or or HR administrator or HR contact or something like that.
So I think first that's an example where we need to differentiate. The system would need to understand when I said they they work in HR and they're they're a manager, then they would have to take the working in HR as their role and the manager would be in their title. Then let's talk about relationship. But hold on, make sure you got that.
Piece so that I don't go too far with that with you glitching. Tell me you got it and let's move on.
Got it. The system will differentiate between a title which refers to a business designation like manager or senior VP and a role which indicates the area of responsibility like HR or finance. Perfect. Perfect. That's enough. So then relationships. So here is one that I think is very broad in.
The way I would want to use it, and for me it's a it's a it's a memorization or a kind of association mechanism that would help me to to pull someone up based on that relationship rather than.
Other information. So let's say I meet someone and they meet a person or I know a person and they introduce me to their husband or wife and I say, well, that's the wife of, that's the husband of. So that's obviously relationship, right? And if I say that person works with the person in HR.
OK, that's a relationship as well. Totally different types of relationships. I don't not quite sure how we have to structure the content in that relationship so that later on it would be retrievable and interpretable so.
Let's let's capture that and then hold on one second and I'll give you some more information. So while it's working on that, can you pull the can you pull the JSON file and send me the JSON? Or is the JSON in the core brain or is there JSON in the individual process?

Lem   46:55
OK.
Uh.

Peter Wolf   47:01
Oh, sure, it's one per, right?

Lem   47:03
The yeah for the EA agent so it it doesn't have like a Jason Jason file so I can just send the like the tool for the add tool.

Peter Wolf   47:11
Uh.
How do you? How do you send that? What? What's the format?

Lem   47:19
The for the AA agent.

Peter Wolf   47:22
Yeah. So like, how would you pass this to Bryan or would you just, is it just the information you gave me in the instructions?

Lem   47:30
Yeah, So what we would do here is we would just copy the prompt and then he could just open the like the AA agents and then paste the prompt and then for the system to yeah.

Peter Wolf   47:39
OK. So what you gave me already is the definition of the of what you would give to Brian if he was or Nick or whoever else if they were copying it. So that instruction is the core part. And then the process flow though when you call the, when you call it that would be a JSON though, right?

Bryan Wolf   47:42
Yeah.

Lem   47:46
Yep, that's right. Yeah. Yep.

Bryan Wolf   47:48
Yeah.

Lem   47:51
Yep. Yeah, that's that would.
Yep, that's right. Yeah, that that would be the Jason.

Peter Wolf   47:57
OK, so can you give me the Jason for both the the the create and the and the retrieval?

Lem   48:07
OK, uh, let me just pull.

Peter Wolf   48:08
And then I'm going to feed them in here as well. And because I want, I think this is the direction we need to go, right? We need to have the system define a much more comprehensive prompt for the feed and for the retrieval.

Bryan Wolf   48:11
Uh.

Peter Wolf   48:24
So that we can use this in a in a more comprehensive way, the way I'm envisioning it. So let's let's see. OK, so I'm going to feed you a JSON file for the activities of create.

Lem   48:40
Yeah.

Peter Wolf   48:40
A record, a name record, and also retrieve a name record. And so right now what the intention is, again, I speak naturally into either Chat EBT or into an app that's going to feed into the make. The make's going to call the agentic brain. It's going to determine based.
Based on what my my wording is, what the activity or the action, what process flow it should trigger. And in this case we're saying it's either create a new record or retrieve the record or find a record or change a record.
I'm going to feed you the create and the and the retrieve, and then we need to figure out how we can define this input, the instructions to the agentic A I brain to process this appropriately with me using natural language.
Make sense?
Absolutely. That makes perfect sense. We'll focus on ensuring that the Agentec AI can interpret your natural language and then decide whether to create, retrieve, or update a record accordingly. Once you share the Jason file, we'll refine the instructions and make sure. So while you're waiting for the Jason file, let me just ask you some further clarification.

Lem   49:42
Uh.

Bryan Wolf   49:54
Uh, send.

Peter Wolf   50:00
So am I right in thinking that the way this?
The way this would need to be.

Bryan Wolf   50:07
Then whatever you're about to send to him, send to me to the Jason files for them.

Lem   50:10
OK, um, yeah, I'm just renaming this. Uh, yeah, the.

Peter Wolf   50:15
Yes, absolutely. You're on the right track. The idea is that the agentic AI will take your natural language input and then translate it into the appropriate fields and actions. So if you describe and so you would you would in the prompt definition where you draft the prompts for me, you would help.
To define my natural language, how that needs to be parsed into those appropriate fields. But it wouldn't be so rigid as where you would be looking for single keywords, would it? It'd be more dynamic that you would say if I describe a relationship, whether it's a familiar.
Relationship or business relationship, that information should go into the relationship field or how would you envision that just right now based on the information that you have from me so far?
Exactly. The prompt would be designed to understand the context of your natural language rather than just relying on single keywords. For example, if you mentioned that someone is a colleague, a friend, or a family member, the system would recognize that context and place that information into the relationship field. The idea is to make it as dynamic.
And intuitive as possible, capturing the nuances of how you naturally describe these details. And so when I think about this, you know, as I'm going through this in my head, I'm thinking about how much needs to be parsed into specific fields and how much could just be in a just generalized comments field. Now when I think about this, I.
And I think structured manner, the more detailed fields, the better that it automatically parses. So when it goes back to try and find something, it can isolate or immediately look to a certain. It can look to a certain piece of information. Hold one second. Can look to a certain piece of information more quickly.
We define that or that maybe even in the future we could use a database kind of filtering instead of sending the entire data file to ChatGPT, which is going to take a lot of tokens to somehow use those fields for filtering and already shrinking it down to a.
Smaller set that we feed into ChatGPT. So if I said well find me the guy who had the beard and and and work that booking and it would just go to appearance and say does anybody who has a beard and then maybe it would only pull those ones with beards and feed them into ChatGPT and let it do a further analysis.
Instead of sending the entire file set, the entire database to shrink that down. And that's at least the way I'm thinking about shrinking the amount of tokens that would be utilized every time I query. So does that make sense that?

Bryan Wolf   52:59
I think I got your.

Peter Wolf   53:02
To break this down into more data fields than it is to cluster into a kind of generic comments field.
Say that again. I got the You got disrupted because I had an incoming phone call. Tell me again what you were saying. Hold on, Bry. Tell me again what you're saying, Chad.

Bryan Wolf   53:22
See if you can.

Peter Wolf   53:28
In no words. What I'm saying is that by having more structured fields, we can create a pre-filtering system. That means if you're looking for someone with specific traits, the system can narrow down the possibilities before sending anything to ChatGPT, making the entire search process more efficient and resource friendly.
OK, so that makes sense to use that model, right? So we'll start with this number of fields, but later on I may add again right here. I don't have appearance for sure. I would have appearance. I use that in the way I think about people or kind of remembering a person. Definitely their appearance would be a component and then we'll figure out.
The other comments right now I would have is generic kind of catch all, but then as we started to identify those differentiator characteristics that I would want to incorporate then then I would I would carve out new new fields.
So we need to make it dynamic to think in those contexts as well as we build this up that initially I'll be cramming a bunch of crap into comments and then gradually we'll be expanding that out, OK.
Absolutely. That sounds like a solid plan. We can start with a few core fields and use the comments section as a flexible catch-all for any details that don't fit neatly into the initial fields. Then, as we identify more patterns or specific details you want to track, we can always add new fields and make the system even more tailored.
Tailored to your needs. OK, and and then things like last time I engaged with that person or last time I communicated with that person or last time I saw that person, we could include things like that, right? Because right now I have date of last update.
Now maybe that may be that I just said a new comment or piece of information. I may not have seen the person or anything, but whereas if I was at some event and I wanted to track all the people that I met at that event or saw at that event.
Then we would have a field that would track that information as well, right?
Absolutely. We can definitely add fields like last interaction or last event scene to capture those kinds of details. That way you can keep track of not just when you last updated their information, but also the last time you actually met or communicated with them. And what about tracking this over time if I?
I wanted to store last time I engaged with them, but what if I wanted that history of the last time I engaged with them? And so it would be like, well, I saw them at the event in November and then there was this business meeting back last year in February and I wanted to see the times I engaged them. How much more?

Bryan Wolf   56:04
OK.

Peter Wolf   56:18
Complex would that make this model and how much trouble would that be in maintaining that database structure?
Adding a history of interactions is definitely possible and can be super valuable. Instead of just a single last interaction field, you could have a section that logs each interaction as a separate entry, almost like a timeline. It does add a bit more complexity to this database structure, but it's definitely manageable.
I would need to use. I'd be much better off using a database structure instead of a spreadsheet as a database structure, right? Like a formalized database model that would have more robustness, more capability, more flexibility.
Than the Google spreadsheet for example.
Exactly. Once you start adding more complexity, like keeping a history of interactions, a formalized database structure would definitely be more robust and flexible. A traditional database would make it easier to manage multiple records, run more complex queries, and scale as you add more data over time. So let's say I'm using this.
And the data that I'm considering here, I'm not thinking is sensitive, but let's say there is a similar database of information that I do consider sensitive. What would you recommend as a two database models for me to handle those two situations?
Non sensitive data, a cloud based solution like a Google sheet or a simple online database can be convenient and easy to manage. Give me an example. Give me a couple examples you would recommend.
Sure. For sensitive data, I'd recommend using a more secure and robust database solution like an encrypted SQL database, for example, MySQL or PostgreSQL hosted on a secure server. Another great option could be a specialized service like Airtable, which offers robust database features with a.
Additional layers of security and access control, making it easier to protect sensitive information. Is the air table as flexible or predefined or I have to do a lot more definition with the air table model?

Bryan Wolf   58:30
Where's that again?

Peter Wolf   58:38
Airtable is pretty flexible. It gives you a lot of predefined templates and an intuitive interface, but you can also customize it extensively to fit your needs. OK, so Airtable I could I could host on my own internal server for sensitive data, but on the on the cloud based, what would you recommend as kind of basic, very robust?
But not over the top complexity, easy to use database model or tool.
Option that's robust and easy to use. I'd recommend something like Google's Firebase or even something like Notion databases. Firebase is great for scalability and security, and it's pretty developer friendly. Notion, on the other hand, is very user friendly and can handle a lot of customization without too much complexity. OK, hold on up.

Bryan Wolf   59:22
OK.

Peter Wolf   59:29
Come back to you.
Sure. Take your time. I'm here whenever you're ready to continue. All right, so.
I think that's obviously you could hear me walking through it. That's that's the direction that I think we need to go. So where you were talking, I think that pine code before as a database, I think we need to be looking at a at a database model, not the spreadsheet because.

Lem   59:43
OK.

Peter Wolf   59:57
It it's going to get more complex and I think the the functional capabilities of storing that kind of historic interaction is going to be valuable to me and important aspect.
So I don't know if building right.

Bryan Wolf   1:00:13
Wait, so can't you just couldn't you just take the JSON code and everything you just asked and plug that into GPT and really get like get the most out of it? That's squeak because OK, OK.

Peter Wolf   1:00:21
What I'm gonna do right now, I'm repping this up and I'll take the Jason files.

Nicholas Westburg   1:00:23
I I think what we need to build is either a rag, a rag application or some sort of lang chain pine cone build something with embeddings and a vector database with you know, a simple rag application which builds over time and none of the data is lost.

Bryan Wolf   1:00:24
We just talk to that thing, man.

Nicholas Westburg   1:00:41
And it's all stored and it's it's mathematically.

Peter Wolf   1:00:43
Yeah, but the rag again, you're talking about then creating or doing a LLM, custom LLM using a, you know, deep seeker or llama or what?

Nicholas Westburg   1:00:50
No, no, no, no, no. It's we're not training a model on anything. It's really just the database where it's.
It's an ejected flow like we're gonna you'll be able to, you know, do the prompts and and get the information that you want, but it's it's it's a big workflow and everything's stored.

Peter Wolf   1:01:17
But I don't think, I don't think the RAG part is necessary. I think what it just explained was if we build this logic appropriately, then my description of what I'm interested in would already be a filter. So we wouldn't have to pull the entire database. It would pull only those that met those criteria, right? So that immediately goes from if I say well.

Nicholas Westburg   1:01:32
Right.

Peter Wolf   1:01:37
It definitely worked at booking.com. OK, it just spills us down to only the people that worked at booking.com. So that goes from 1000 to 10 or five or 50 or whatever, but it immediately shrinks that and that's the kind of functionality that I'm looking for is to one, take my normal words and to convert them into much more structure.
To recognize how it should take that structure. And I think as soon as I ask it to do this, it's going to give us a prompt that's going to do exactly that, right? So let me load up the Jason. Let me load up the JSONS and see keep that as an input as well. So hold on, where am I?

Nicholas Westburg   1:01:57
Yeah.

Bryan Wolf   1:02:04
Something along the lines that I guess there for sure.

Lem   1:02:04
Yeah.
Yeah.

Peter Wolf   1:02:15
Uh, here.

Bryan Wolf   1:02:16
Well, what do you wanna do with all this? Like, should I I lend? Do you wanna? I wanna implement this into the five make like.

Peter Wolf   1:02:23
Yeah, so he just said the way you're gonna implement that is by taking the instructions. So we need to work the instructions first, right? This was if you're looking at the screen, this is what I already plugged in. This task one, task two, task three. This is what I already put in. But now what we need to do. Did you send the JSONS then?

Lem   1:02:24
Yeah, on on me.

Bryan Wolf   1:02:29
OK, OK. OK.
Yeah, let me see this.
This is over here.
Yeah, yeah, yeah.

Lem   1:02:40
Yeah, uh, on the e-mail. Um.

Peter Wolf   1:02:42
They're in the e-mail. OK, hold on a second. Let me pull up my hand.

Lem   1:02:45
Yeah, I I think, yeah, I got the gist of the like searching. Yeah, like the filter. So for the because if ChatGPT could get the context of the message and then for example you're saying that.

Bryan Wolf   1:02:50
What the AI say?
What?

Lem   1:03:02
Like the appearance and then it would get the context of appearance. So it would search. Just search the column of appearance. If yeah, yeah, yeah. To filter out, yeah, yeah.

Peter Wolf   1:03:08
Right, right. Just to filter out. Again, this is what you were talking about earlier about, well, could the database do some filtering? But if we use logic to say do some filtering, but the problem is here, doesn't it still need to get everything fed to it to do the filtering? So this is what I don't know, right? Because I tell it to do some filtering.

Bryan Wolf   1:03:13
Yeah.

Lem   1:03:16
Yep.

Peter Wolf   1:03:28
And it has to get all the data to do the filtering, which means I just fed it the whole database anyway. So I'm not sure this is where I still this is for me. This is the kind of thing I need to work through in my mind, just kind of talking it through and seeing what the impact is. And then you put in a model, we put in a change and then we see, OK, does that really feed the whole thing or is there some way to feed a a lesser?

Lem   1:03:33
Um.

Bryan Wolf   1:03:38
Yeah, yeah, yeah, yeah, yeah.
OK.

Lem   1:03:47
Yeah, I think. OK, OK, no problem.

Peter Wolf   1:03:48
So let me let me just ask that part. Hold on, hold one second. And I I appreciate you guys just sitting here while I work through this, but I think this is also this is really helpful. I'm thinking about from my perspective. I think this is helpful to all of you, one to to you, Len, because you understand to try and understand my thinking what I'm.

Bryan Wolf   1:03:55
Yeah, you're just. I know.

Peter Wolf   1:04:07
Searching for and I think for Brian and Nick also to understand, at least for me, you know, having been in business for a long time, this is the way that I would think through the process, trying to understand what would be the most effective way to capture the information I want, to retrieve the information I want. And it's not just a straight off the top of my head. This is what I.

Lem   1:04:09
Yep.

Bryan Wolf   1:04:18
OK.

Lem   1:04:18
Yep.

Bryan Wolf   1:04:23
Right, right, right.

Peter Wolf   1:04:27
This is what I envision and I get a simple answer from it. It's kind of what are the different pieces that get you there? How do we input something, use it in an appropriate way, structure it so that it's retrievable later, minimize the number of tokens we use and make sure it's effective, make sure it's efficient, et cetera. So let me just.

Bryan Wolf   1:04:31
We're working toward the right.

Peter Wolf   1:04:47
Let me ask that portion.
So Chad, I'm trying to think about this, right? I was talking to you about minimizing token use and in the model that we talked about, the the basic model we have set up right now, the entire database needs to be retrieved and fed to you or to the AI, to the AI brain.

Nicholas Westburg   1:04:52
Thanks.

Peter Wolf   1:05:09
To do the selection or identification for retrieval. And then we you and I just talked about how could we make that more simplistic that it was filtered down only to a lesser set. But as I think about that now if I if I was looking for you to explain how I could define.
Extracting A lesser set from the AI brain, I still have to feed the entire database to the brain to be able to do the filtering. So is there really any change? Is there really anything structurally we could do differently that would enable us to?
Use less tokens like in the logic of the database. Would you then instruct the A I brain to say go to the database and only extract information that has the appearance of beard?
And that's how you would shrink the amount of data that was fed to you. And I say to you, meaning you would ultimately be the AI brain, the agentic brain, you or some other LLM. Does that make sense? Is that am I thinking that through correctly? That's the way you would envision it to minimize the token use?
Yes, exactly. The idea would be to implement some filtering logic before the data even reaches the AI. This means you could set up a query or a filter in your database that runs first and only pulls out.
The records and match certain criteria, like having a beard or being from a specific company, then only that smaller filtered subset of data would be sent to the A I for further processing. This way you're reducing the amount of data that needs to be processed and minimizing token use. You're definitely thinking about it in the right way. OK, awesome.
OK, so now I'm gonna pull up the.
Ask the.
Emails cancel.
Oh, this is where you would screw up if I just almost dragged them in without refreshing. This is the problem with using the model of using my phone is you.

Bryan Wolf   1:07:28
That's literally I was gonna say. You got to save that chat, man. You have to save that whole chat. Send it. Don't lose that.

Peter Wolf   1:07:30
You have to refresh. Yeah, you have to refresh because otherwise you'll overstep it and you would lose that data because it gets corrupted and then it usually keeps what's on the PC and all that other stuff will be done. So here we can see the last kind of comment from it is there.
O now I'm updated. Now I can add these two jons in. Now I can say.
Here are two JSON files that show the create and the retrieve currently that we're utilizing in this agentic process flow for name, file or person information file management. So take this as additional input and wait for instructions.

Bryan Wolf   1:08:23
I almost want to say even save your transcription like what you're saying.

Peter Wolf   1:08:27
Yeah, but you have all that. This is what I've said to you before for I I I say to this to you, Brian, I mean to to Nick as well. I mean Nick is again further along in a lot of this stuff. But to me sometimes just walking through this, if I gave you the history and said look how I worked through this, right, this is for sure on the on that on the dashboard.

Lem   1:08:29
Hello.

Bryan Wolf   1:08:29
Yeah, yeah, yeah, yeah, yeah. Everything's recording, right? Mhm.
Right.

Peter Wolf   1:08:47
Where I said about playing around with the dashboard. I think working through one of my conversations with ChatGPT as I was building a dashboard is very insightful, right? OK, what did you run into a problem? How did I try to address it? How did I ask you to fix it? What did I ask you to do to make a change?

Bryan Wolf   1:08:58
Right.
Mhm.

Peter Wolf   1:09:07
That's the part that I think accelerates your knowledge and understanding. That's also what you want to be bringing to the table when you're talking to potential employers. You want to be able to do that interaction, that iterative processing with Chats EBD to figure out essentially anything you want to figure out. And that I think helps you that logic of.

Bryan Wolf   1:09:12
OK.

Peter Wolf   1:09:26
The approach helps you, whether you're coding or whether you're talking about just reasoning, or you want to come up with a solution or whatever. That approach of the back and forth and thinking about it logically is to me is fundamental to any of this using AI. What's up, Nick?

Nicholas Westburg   1:09:27
Pick up.

Bryan Wolf   1:09:42
Yeah, Nick, just interject. Like, yeah, like don't put that, don't put that emoji on, just talk.

Nicholas Westburg   1:09:43
Yeah, yeah, yeah. Hey, me, me, pickle me. No, no. Just to piggyback, I spent a good chunk of time like.

Peter Wolf   1:09:45
Yeah, you in the back, young man in the back.

Lem   1:09:48
Huh.

Peter Wolf   1:09:52
Yeah.

Nicholas Westburg   1:09:58
Really. I mean, like you just said in the bag, just like with with meeting big meetings with the company that I'm with now, like I don't really have a lot to say in that I kind of just listen and take my notes and whatnot. So I spent a lot of time really learning how to dissect meetings and dissect.

Peter Wolf   1:10:10
Uh.

Nicholas Westburg   1:10:17
Like context of what people were saying and utilize and figure out prompting methods for that to extract the best possible context and information and what all of that right? So just really Brian focusing not just.
But just working on that too. Just OK, we have a transcript. Peter has talked a lot and he said what he wants, but really learning how to prompt properly and dissect that transcript and really take away the key things that.
He he's been saying it in the meetings.

Lem   1:11:04
No.
OK, no problem. Yeah, it's OK.

Bryan Wolf   1:11:09
Like we're doing that too.

Peter Wolf   1:11:09
Because this is about helping these guys also expand their skill set. So if we look at, for me, hold on a second, what you're talking about right there, Nick, and I would be very interested in seeing your prompts for this stuff, but let me just show you.

Bryan Wolf   1:11:12
Sorry, love.

Peter Wolf   1:11:27
What am I looking for? So prompting.
Uh.
Class transcripts enhanced is the most recent 627. Yeah, so you know I'm in that in that MIT course, right? And so in there we watch lots of videos, but I want to extract the information from the videos and incorporate it into notes.
And and So what I've been refining is this prompt to ensure that I'm getting really only the content from the notes. I don't want it to embellish. I don't want it to expand with information it has. I have other prompts that specifically are saying grab the information and then expand on it right that I want.
I want you to create you the AI brain. I want you to create something that's more expansive. Just take the information and and build me something more insightful. But and that's where I have right here. So here's a basic prompt. It's pure fidelity, meaning only tell me what was in that conversation, whether it was a meeting.
Or whether it was a presentation or a YouTube video, tell me only what's in that. Give me pure definition or information insight into that. And so that's this first prompt, right? It's used case structured clarity with high fidelity to speaker intent. Tells you your whole thing is about primarily the goal is to clearly and precisely represent.
What a speaker, professor, subject matter expert expects to communicate it without paraphrasing away depth or introducing outside embellishment, et cetera. Then if you look at kind of the next one, well, I want to expand. I want to take that same thing, but I want to expand on it. So we go down here.
Now we're saying, oh, the goal is to clearly and faithfully capture what was covered in transcript while also creating complementary structured educational enhancement. So these are, this is the kind of depth that you need to go to to get that precision. What Nick is saying, right, you you you find something, use a prompt.
And.
Gives you kind of close, but not what you're looking for. You have to really keep going and drilling in and building these prompts at these kinds of levels, a very specific nuance. Here is doing the same thing, but I embedded together. Here's another one that puts it into two different sections. You know, how am I trying to do it? Am I trying to make the information clear to see what the person said and.
How do I learn more? Or do I just care that the topic is important and I want to take what the person said and automatically, immediately embellish it and expand it because I'm just trying to learn that topic. Two different, two different objectives, two different very specific prompts in how to to handle that. But this is the kind of thing that is very.
Helful in exactly what Nick's talking about. And so ultimately in my class, my course right now here is what this looks like.
Uh.
That's not where I want to be.
Now fortunately I had an offshore guy run, take all these lectures and put them through my prompt and then put this into single documents. But let me see his data. Oh, transcript notes. That was it right there.
O Here's for the different modules and let's take like this.
And now here we have this is the overview. It's learning outcomes. What's the objective in this particular module? Introduction, group intelligence, blah blah blah. This is really just a summary of the module and then it goes into each video.
And it gives again using that pure just give me exactly what the professor said or the people that were talking said and this gives the details coming out of that. And so it's every video that was in this module all then captured together along with the summarization overview to give us the the context, right. So.
This is this is the kind of thing where you can really accelerate your insight, accelerate your extraction of information. And again, these are from videos. These could be YouTube videos, these could be any kind of videos and and I think this is extremely helpful. So enough of a sidetrack. So now.
Ready to ask question? No, I don't want to try Kodak. So then here, let's go back. I'm gonna jump back over to my audio modality.
OK, so now you have my information on those, or at least that on the process flows as they are right now. Now what we need to do is to define the instructions to the brain. What I originally loaded up to you to get started here, I need to refine that to be much more in alignment with all the things we've talked about.
That my natural language communication is going to help me or help you help the agentic brain to figure out how the information should be parsed, how it should be fed into the spreadsheet, and how it can be filtered coming back or giving guidance to the.
To the either to the extraction from the Google sheet or to a database. Right now we're going to be in Google sheet just because that's already established. We can move to the database for more robustness, but let's just assume right now I'm in the spreadsheet until we start to vet this and and make it a little bit more specific.
So now give me what you would expect the brain as it to have as instructions or need to have as instructions and then clarify to me why you're using that approach and and what what impacts, limitations, opportunities, et cetera exist for us to further refine this and make it.
Even more robust.
Go ahead.
Absolutely. Here's how we can refine the instructions for the agentic brain to ensure it effectively understands and processes your natural language input. Instructions for the agentic brain #1 natural language parsing. The agentic brain should analyze the natural language input to identify key pieces of information such as name.
roles, companies, appearances, and relationships. It should also recognize context cues like the difference between a formal title and a role or a personal relationship versus a professional connection. Field mapping and categorization.
Once the information is parsed, it should be categorized into the appropriate fields. First name, last name, company, formal title, role, relationships, other comments, and appearance. The brain should be able to dynamically determine which details go into the structured fields and which ones can be stored in the general comments field if they don't fit neatly.
Into predefined categories, filtering and preprocessing before sending any data to the AI for retrieval or analysis. The brain should apply prefilters to narrow down the data set. For example, if you mention that you're looking for someone with.
A certain appearance or from a certain company. Only those relevant records should be selected from the spreadsheet before the A I processes. Then output structuring. Once the relevant data is found, the brain should structure the output clearly, listing the key details like full name, company, role, and any other relevant comments or appearances.
Why this approach? By filtering the data before it reaches the AI, we reduce the amount of information processed, saving resources and improving our response time. This approach allows you to speak naturally without needing to structure your input rigidly. The AI adapts to your language, making it user-friendly.
and intuitive. As you add more fields or refine the process, the system can easily adapt. You can start with a simple spreadsheet and later migrate to a more robust database without changing the core logic.
Opportunities. This approach opens up possibilities for future enhancements, like integrating with a more secure database, adding more complex filters, or even using advanced AI models for deeper analysis.
Initially working with a spreadsheet, it is simple, but it may have limitations in terms of scalability and performance as the data grows. Moving to a dedicated database structure in the future will provide more robustness and flexibility. Let me know how you'd like to proceed or if there are any specific areas you'd like to refine further. Well, I'd like you to actually give me the.
Instructions to feed into make.com into the agentic brain as the core of this, based on all the things you just said, using this particular structure that we have so far, knowing that we're going to expand it and add numerous additional fields and potentially that when we get to the database part of history of.
Reactions.
Absolutely. Let's draft those instructions for the agentic brain to guide the process in make.com. OK, agentic brain instructions for name file management. First, natural language parsing objective. Extract key details from the user's natural language input instructions. Identify and.
Categorize names, roles, companies, appearances, relationships, and any additional comments. Distinguish between formal titles, EG manager, director, and roles, EG HR, finance. Recognize contextual cues for relationships.
Differentiating between personal e.g. friend, spouse and professional e.g. colleague connections. Second, field mapping and data structuring objective. Ensure extracted information is placed into the correct fields within the Google sheet. Map the parse details to predefined columns, first name, last name, company.
Formal title, role, relationships, other comments and appearance. If a piece of information doesn't fit a predefined field, place it in the other comments section as a catch all filtering form retrieval objective minimize token usage by narrowing down the data set before sending it to the AI.
Apply pre-filters based on the user's query. For example, if the user mentions a specific company or a unique trait like appearance, only retrieve records that match those criteria. Send only the filtered subset of data to the AI for further processing, ensuring efficiency and speed.
Output formatting objective present the retrieved information in a clear and structured format. Format the final output to include the full name, company, role, formal title, relationships, and any other comments or appearance details in a user-friendly summary.
These instructions will help ensure that the.
OK.
Efficiently, even as you and add more fields in the future. Let me know if there's anything else you'd like to adjust or if you'd like to move on to the next step. All right, so I say let's plug this in and see what we get as a start.

Bryan Wolf   1:22:44
Hey.

Lem   1:22:55
Name file management.
OK, I'll.

Peter Wolf   1:23:12
I just loaded it into the chat.

Lem   1:23:16
OK, I'll.
Copy this prompt.

Bryan Wolf   1:23:39
So then what are you doing? You're just plugging this in or into make or?

Peter Wolf   1:23:44
Yeah, remember this is, remember this output we got right here in the definition of the agent. This is what he had entered, telling it what to do as its baseline. And we've just expanded on that to tell it more definition and ways to minimize token use. And so he's.

Lem   1:23:45
Yeah, yeah, on the.

Bryan Wolf   1:24:02
Oh, OK.

Peter Wolf   1:24:04
Replace that with this.

Bryan Wolf   1:24:07
Yeah, great.

Peter Wolf   1:24:09
And then what we're gonna do is we're gonna plug in a basic example and see what it does with it.

Lem   1:24:10
Yeah.
Instructions.

Peter Wolf   1:24:20
So I'm gonna type, I'm gonna go to my while you're plugging that in, I'm gonna go to Chachi PT and I'm going to do. Sorry, go ahead.

Lem   1:24:21
Uh, OK.

Bryan Wolf   1:24:26
Yeah, I I can now you go, you go. I was just saying I want to share, let him have his share screen on this and you can mute and run through all that stuff and then there.

Peter Wolf   1:24:33
Yeah, yeah, yeah. No, he can. That's fine. I'm just gonna, I'm gonna walk through what I would give as an input and then you guys can plug it in while you build this right now and I'll I'll go mute and I'll take care of putting up what I would have as an entry.

Bryan Wolf   1:24:38
Lam, if you want to do that, yeah.
Yeah.

Lem   1:24:49
Um.

Bryan Wolf   1:24:53
They called you learn.

Lem   1:24:55
Pardon.

Bryan Wolf   1:24:57
Is that cool, dude? Do you wanna share your screens just a second? I mean, I don't know 'cause I I wanna.

Lem   1:25:00
Oh, OK, Yep, yeah, no problem.

Bryan Wolf   1:25:05
Oh, true.

Lem   1:25:06
Um, OK, so I just copied the.
Uh, Objective instructions.

Bryan Wolf   1:25:14
So it's really is OK.

Lem   1:25:23
Yeah.
#2
Also this is on the same.

Bryan Wolf   1:25:35
So now you did you create this agent?
Where is the beta?

Lem   1:25:38
It's yeah, this one on the AA agents beta and then you could just.

Bryan Wolf   1:25:43
Yeah, but OK.

Lem   1:25:51
Yeah, I think that's it.
Then Ye, let's test it out.
Uh.
Um.
Let me just check the.

Bryan Wolf   1:26:19
Now what are you running GPT 4.1 nano?

Lem   1:26:20
Oh, right. Yeah, 4.1 nano, so.
Not sure if it would. Uh, let's try it.
Get just a simple uh.
And.
Uh.
The marketing leads.
Sure.
It's.
Holy West.

Peter Wolf   1:27:30
All right, I have a good example. I just ran it through based on the logic that was included that I gave to you. And so I think once you're ready we can plug this into.
Plug this in to see how it goes.

Lem   1:27:50
Holy West.
Yeah, it just.
It actually hallucinated for the yeah, this one is yeah, it didn't. Yeah, I'm not sure if it's triggering the this particular.

Bryan Wolf   1:28:00
OK.
I didn't pick it up, right? Right. Maybe just gonna refresh this and this is your data in your Google sheets, right?

Lem   1:28:15
I mean the other one, this one.
So.
Yeah.
Yeah, it actually triggered that one. It's just.
Yes, it's actually.
Yeah, it didn't. Yeah, it actually triggered it, but it didn't pick the right.
Yeah, I'm not sure if it's on.
The.
Model because.
It's not really getting the right data for. It's pretty simple.
So we actually have.
Marketing lead. Yeah, we have six people for the marketing lead.
Uh.
Yeah.

Bryan Wolf   1:30:02
I see it is still listening, OK.

Lem   1:30:04
Yeah, it's actually hallucinating. I think that this, yeah, this model is.
I think very dumb or something, yeah.

Bryan Wolf   1:30:14
Very dumb. What? So what model? The the the makes model? You're saying the make AI Asian model or the Chechi machine? No.

Peter Wolf   1:30:16
Which? Which model do you use?

Lem   1:30:18
The the, yeah, the GPT model, the 4.1 nano. Yeah, so yeah, it's so it yeah, it actually triggered the.

Peter Wolf   1:30:19
No, I think it means the ChatGPT model is using.

Bryan Wolf   1:30:24
For growing Nano. Yeah, that's GIA.
But it see, it's just like, yeah.

Lem   1:30:31
Yeah, it it it caught the. So I think we could use the 4.1 nano on the this one on the one deciding, but on the.

Peter Wolf   1:30:41
On the one that has to do the selection in analysis, then you use a higher one. And now that we're saying we're going to be filtering down some, that should be less of a problem, right?

Lem   1:30:42
On the like, yeah, the selection that, yeah, that.

Bryan Wolf   1:30:44
Yeah.
What's up? Yeah, yeah.

Lem   1:30:52
Um.

Peter Wolf   1:30:54
So let's go with that. Let's go with the higher level, right?

Lem   1:30:55
I'm not sure because like the the the prompt here actually is not accessing the like this automation so it basically.

Bryan Wolf   1:30:58
We had to switch all of them, really.

Peter Wolf   1:31:07
Uh.

Bryan Wolf   1:31:08
Right.
Right, the same. Yeah.

Peter Wolf   1:31:23
What? What? Which model it's using there? OK.

Lem   1:31:24
Yep. So yeah, what what I'm planning to do is to edit the prompt with the filter. So we will have like a a filter because as you can see here, I'm actually.
Like listing all the rows I don't have like filter. So basically my plan is I would add here a dynamic input data which is like filter for example filter and then this would be the filter.

Bryan Wolf   1:31:45
Yeah.
OK.

Lem   1:31:59
For the Um.
For the data and then I would add here on ChatGPT that it will it will analyze the message and then.
It will create like a filter. It will choose a filter based on uh based on the yeah the the yeah.

Peter Wolf   1:32:24
The input. So if it said appearance, then it should create a filter dynamically based on appearance. If it's a company, it should dynamically filter for company.

Lem   1:32:30
Yep that's right. Yeah Yep. So for example appearance. So what will happen is it will input here a dynamic dynamic filter which is appearance. So that there would be two filter here and then I will add here as contains. So what will happen is.
For example it output the appearance, so for example appearance and then if the appearance contains the like the.
Analysis from Chachi PT, so it would just input the.
Input the data here, which is the columns that has that particular appearance, if that makes sense. So basically I'm connecting the filter here like the static filter to Chat GPT's logic here.
And then it will decide based on the the like the message if it will filter out on appearance or in like on the other comments.

Peter Wolf   1:33:40
Right, so the first thing it's going to do is take my message. It's going to interpret my message, figure out what the characteristics are that I'm giving it details on. Then it will select the appropriate filter based on those detail characteristics.

Lem   1:33:46
Yep, that's right. So that Yep, they're right. Yep, that's right. And then it will add the like the add the.
The filter here and then what my goal is to output just that particular. For example in this database we have for example I need a like a vague.
For example casual. So we have smart casual, we have casual right? So what will happen is it will filter all the columns that has casual and then we also have casual here so it will filter that out and then we will pass that as data here but.
It will be limited so it would just be all the like the the columns that has casual so that the ChatGPT won't will will be yeah we won't have we we will be like spending less tokens on the ChatGPT side because it's already prefiltered here on the Google.

Peter Wolf   1:34:47
Yep.

Lem   1:34:50
Sheets. So that's I'm how I would like yeah design this one. So basically we have a filter. First filter would be on the dynamic here on Google sheet and then it will filter it again based on the.
Query the main query on here on ChatGPT. So the the challenging part here would actually be on the prompting because yeah I would need to you would need to give more context on how it will use the like the this tool the.
The find data in Google sheet. So yeah, if that makes sense. Uh, if you guys, uh, get to just.

Peter Wolf   1:35:27
Yeah, so maybe I there was some stuff that maybe you mean that was extracted or excluded from what you gave me originally you'd have to put back in.

Lem   1:35:36
Yep, that's right. Because um.

Peter Wolf   1:35:37
And otentially more definition to make the conversion from the interpretation of my inputs to the mapping of filterings.

Lem   1:35:49
Yeah, because here it's like it's giving instructions, but.
Yeah, I'm just the. I just copy paste the like the old old prompt. So this was like the.

Peter Wolf   1:36:02
What is this that you're looking at right here?
I know, but what is the what's the what's the tool you're looking at?

Lem   1:36:15
This one this yeah this is just a notepad on on Mac so I just copy paste the.

Peter Wolf   1:36:16
Yeah.

Bryan Wolf   1:36:20
Back.

Peter Wolf   1:36:22
Just a standard standard Microsoft notepad or what are you using?

Lem   1:36:25
Yeah, uh uh, no. On Mac. It's a standard notepad on Mac. Uh, yeah.

Bryan Wolf   1:36:27
The Mac Apple.

Peter Wolf   1:36:29
Oh, a Mac. OK, I was gonna say it didn't look, didn't look familiar structurally, OK.

Bryan Wolf   1:36:33
Yeah.

Lem   1:36:33
Uh, yeah. So yeah, I uh, yeah, this this the.

Bryan Wolf   1:36:36
I love his searcher thing a little far left too.

Peter Wolf   1:36:40
Yeah.

Lem   1:36:40
Yeah, it's because the like the filter here, it wouldn't pass that context here on the this next automation because basically what is just happening is it's analyzing our message and then it's sending.

Bryan Wolf   1:36:41
All right.

Lem   1:36:56
The data to the tool and also triggering the tool if you if you uh Yep and then.

Peter Wolf   1:37:01
Yep, right. So you're gonna have to, you're gonna have to figure out the interconnectivity between what I'm doing on the front end and tying that into the process flow, which is going to let it take the structure and utilize the structure in a way that's going to let you facilitate the filtering.

Lem   1:37:07
You have the you have this right.
Yeah.
Yeah. On. Yeah, that's right. So, yeah, I, I, I would.

Peter Wolf   1:37:19
All right. I think this is though I I just think, I think where we're going is awesome stuff. Like this could be used in so many different kinds of databases. But I I think just even this part, this kind of storing contacts, information, all this kind of stuff, I I think it's gonna give us a lot of.

Lem   1:37:24
Yeah.

Bryan Wolf   1:37:35
Well, let's see how it turns out. Let's let's let's.

Peter Wolf   1:37:37
No, no. But I think it gives you a lot of learnings, right? Like he's doing is we may be able to build logic into the brain in the Agentic kind of overarching Agentic process manager, let's say in in make. But this connection stuff taking that and translating it into the filters clearly still.

Bryan Wolf   1:37:40
Yeah.

Lem   1:37:41
Yes.
Yep.

Peter Wolf   1:37:57
This is based on, you know, LEM's knowledge of how we have to convert this to execute it, right? So I think there's going to be a lot that you learn from that no matter what.

Lem   1:38:01
Yeah.
Yeah, because uh.
Yeah, that's right. Because when you, yeah, when you build the like the agent, basically it's like accessing some tools. So there would be some logic with the tools and also connected with the prompt. So that is like the main challenge on building like the AA agent. So the prompt should be connected also to the tools and as you can see here, it's also.
Also has like a description so I just added this description also is being fed to the like the ChatGPT so it would get this description and then it will know that it will trigger this tool. So if I put here add data to Google Docs.
This won't. This wouldn't actually trigger and ChatGPT won't be able to. Yeah, it won't trigger this one because it's a different description. So yeah, so all of that is actually connected on the like the prompt and then the tools and also the data that is being passed here.

Peter Wolf   1:38:54
Yeah.

Lem   1:39:04
Which is found here on the scenario input. So these are dynamically inputted. So yeah, and yeah, so here in make it's just differently like.
The information is just or the data is just inputted differently, but basically on any 10 it still works the same way. So we are connecting the brain which is the this one, this is like the main brain and then connecting it to the different tools.
So that is actually how the yeah, the agent uh works on N 810 also. So Yep.
But.

Peter Wolf   1:39:43
OK, hold one second. Let me ask. I'm gonna ask if this stuff we're doing what what the equivalent in Microsoft environment is. So hold one second.

Bryan Wolf   1:39:44
OK.

Lem   1:39:47
OK.
Yeah, yeah. I'm not sure if they already have like the AI agents. Yep.

Peter Wolf   1:39:57
I know that's why that's why I'm checking. So just give me a second. Let me ask.

Lem   1:40:01
OK.

Peter Wolf   1:40:10
Hey Chad, so taking this we're working in in make.com, but all this is going to be converted into Microsoft environment with the Microsoft Power Automate, Microsoft Copilot, Microsoft.
Yeah, custom copilot agents and copilot Studio. Is all this same structure possible? This agentic kind of centralized brain and the instructions we're feeding to it that then calls the appropriate function and processes it? Or is it is Microsoft environment?
Somewhat behind in this particular aspect, or would that copilot studio enable us to do this kind of stuff?
Chat you there? ****.
No, that's what I'm saying. It's not consistent. You can't. I know. That's why I also don't. Well, no, that's why I don't. I also don't go long. I try not to go long stretches because I go 5 minutes and all of a sudden I realize I didn't get a ******* thing.

Bryan Wolf   1:41:07
I know you can't be too reliant on it, man. You can't be so relying on the on and they are.
Yeah, well, that's the thing. That's the thing I know we're we're too reliant on.

Peter Wolf   1:41:22
Chat you there. Chat you there.
Chat you there.

Bryan Wolf   1:41:31
It's just glitching. Yeah, I know. And then did you just lose the old chat? It's so annoying.

Peter Wolf   1:41:31
Yeah, that that ****** me off to no end. But when I when it's working well, yeah, I know, but when I when it's working well, it works. It's it's much more efficient for me. When it works well, it it I I can't think of a better way to go about it.

Bryan Wolf   1:41:38
No annoying.
Do you have it saved though? I'll just check. Yeah, yeah, yeah.

Peter Wolf   1:41:48
What do you mean? Yeah, all my stuff is saved. When you were seeing me pull it up on the screen, that was it was storing that. The problem is, in the middle of a dialogue, if it gets corrupted, it doesn't. It hasn't already committed that work to anywhere, so you'll lose it.

Bryan Wolf   1:41:53
Correct.

Peter Wolf   1:42:04
And again, where you get corrupted between the systems is a problem too.

Bryan Wolf   1:42:05
Oh, oh, good.
Don't do that. Don't do that. Thank you.

Peter Wolf   1:42:12
All right, so I think we have a path forward. You can see I added some additional fields I'd like to put into the spreadsheet. I just put them into into the chat. I also gave you a very specific sample. I think this is this is a.

Lem   1:42:21
OK.

Peter Wolf   1:42:28
Great example of at least the creation part, right?

Lem   1:42:31
OK, uh, this one.
Yeah, like in plain words and should get the contacts, Yep.

Peter Wolf   1:42:36
Yep. And then here, let me let me show you what, uh, I'm gonna share a second here.
Oh.
My computer's running really slow. I'm going to have to reboot.

Bryan Wolf   1:43:02
So is mine, man.

Peter Wolf   1:43:10
So here, after I fed that in and I told it to use the logic that had been provided that I sent over to you to parse it to see how it would parse it. Now obviously again, you need to take from the logic and put it into the filters or into the into delivery. I don't know that's on the retrieval side, but I'm.
Not sure on the output side or the input sorry input side. So here was the the the prompt I gave you or the the audio communication that I gave you and I asked it to tell me how it would parse that and so it.

Lem   1:43:34
OK.
OK.

Peter Wolf   1:43:45
First name John Smith Company formal title not explicitly mentioned. So we can leave it as blank or NA role potentially in treasury or finance. Because I said yeah, I think they they're colleagues of Tom, but they I don't know if they work in treasury or finance. I said we'll put it as treasury slash finance.
Relationship College colleague of Tom Devine. Other comment comments met at the AAPFAFP conference. Noted as humorous guy. Interested in agentic process flow. Has a wife named Sarah. Two kids. Details about kids not captured. Appearance. Brown hair, beard, mustache, stylish clothes.

Lem   1:44:05
Mm OK.

Peter Wolf   1:44:19
So then I I just said to you to add as I'm as we work through these, I'm definitely going to come up with more fields. But I think once we build this thing then and start populating it, I can also have a I go look at all the content and say what would make sense for fields to be additionally separated.
Right. Like I think family information because I use that a lot. You want to show somebody you're paying attention to them. They say, hey, my kid's birthday or I my my daughter just such and such, just graduated high school and you're like, OK, I want to remember that. So the next time we're talking about family, I don't have to.

Lem   1:44:38
Yeah.

Peter Wolf   1:44:53
You know, be stuck with no, no recollection of what the guy has said or person has said about themselves. So this stuff is very valuable to me and I think putting it in as separate data points is going to be valuable here, like business relationships, personal relationships, categorization of contact.

Lem   1:45:02
OK.

Peter Wolf   1:45:12
Family details, last interaction source for the source of data. Because when I load up my contacts from Outlook, I want to put that I got them from Outlook and anything after that can be from interaction, right? And then introduced by a lot of times people introduce me and remembering OK, that guy introduced me, that will let me automatically narrow it down.

Lem   1:45:22
Oh, OK.

Peter Wolf   1:45:32
So in that kind of database filtering, I would say Tom introduced me to these people. OK, well, there's five people, but I know that Tom's the only one that introduced me, so I don't have to feed anything but people that were introduced by Tom, right. So I think these are, these are definitely, this is how the database I think will.

Lem   1:45:46
OK.

Peter Wolf   1:45:49
Definitively grow the the the features or characteristics will definitively grow for the database.

Lem   1:45:56
Um.

Peter Wolf   1:45:58
So if we can add those in for sure, but I'm I don't. I'm not sure if right now we should just stick with the the the Google Sheets because that would take us less time than going and building a database or whether you think moving to the database part is is valuable.

Lem   1:46:01
OK, under feels sad.

Bryan Wolf   1:46:14
OK.

Peter Wolf   1:46:17
Now, my personal opinion is that we just stick with the Google Sheets and we just build this out on the Google Sheets. I'm not going to be able to do like things like show me the history of when I met the person, but that's more complicated anyway. I want to really get this foundation working and then worry about those added aspects. Does that make sense to you, Len?

Lem   1:46:33
Yeah.
Yep. Uh. And also I think uh.
On the I I I will also test out if like the contains filter on Google Google Sheets works on like a long sentence. So maybe it like maybe it gets confused also or something.

Peter Wolf   1:46:51
OK.

Lem   1:46:57
So yeah, I would also research for other ways like to use other database for because if we add this particular columns I think yeah on Google Sheets we would have like a like a problem. So I'll also research on that one.

Peter Wolf   1:47:11
It's going to start to get too large, you mean?

Lem   1:47:13
Yeah, Yep. And for the filter, yeah, maybe it would have a problem on the filter side, I think so.

Peter Wolf   1:47:20
So then maybe let's just go to the let's go to the database then.

Lem   1:47:24
Yep, Yep. I think that would be better.

Peter Wolf   1:47:25
Let's go to the database. So what database it had recommended some where you is there one because I know you talked about pinecone or something before. I mean I would like to really make sure one, I mean if it's a database you're comfortable with that's gonna work, you know you're more confident in then that would be make sense.

Lem   1:47:36
Yeah, so.
Yeah, I I'm yeah, because I researched a little about the pine cone. It's like not really like compatible with this structure like because our structure right now is tabular data. So that's why I've actually used the super base because they have like a tabular.

Peter Wolf   1:47:45
Yes, but.
OK.
Yeah.
OK, so Pinecone was more along with that, with the kind of vectoring aspect, OK.

Lem   1:48:02
Data.
Like a long, yeah, that's right. Like a long paragraph or like a document or searching on the documents or something like that. So that's why it it needs like the like the embeddings and the So what we have right now is like a tabular information. So it's not really compatible with that one.

Peter Wolf   1:48:09
OK.
OK, all right. But so then if if so, is this is this database tool that you're using? I I think the important thing is making sure it's gonna be robust enough that aspect that I told you about being able to it.

Lem   1:48:23
I think so, yeah, that's why I.
Yep, that's right. Yeah.

Peter Wolf   1:48:40
Like it's simple to me when you think about the data as a single record for a single person, right? Because that makes sense. It's it's simple logic is you look at a spreadsheet and every row is a record, right? That record is a person in their history and every column is a feature or characteristic.

Lem   1:48:48
Yeah.
Yep.

Peter Wolf   1:49:00
It's a detail relevant to that record. That's basic database stuff. But when you start saying, OK, I want to track every time I met the person, now all of a sudden it doesn't all fit in one long row, right? Unless you have, OK, another field that says first time I met them, then the next one says.

Lem   1:49:00
Yep.
1.
Yeah.

Peter Wolf   1:49:20
Second time I met them, third time I met them, fourth time I met them. Maybe you could do it that way and you could think in terms of of the record being, you know, potentially 100 columns long, each one saying the last time I, you know, met them, the time before that, the time before that, time before that.
But I don't think that's the way the database is going to store it. I think it's going to kind of store it as maybe two different records. One record is the primary record of the person, and then the history is a second database of records that says when did I meet that person? And they'll have a database key that will tie them together.
Like the person's name is the database key for the the contact record and the contact record history of interaction and I just don't know. Let me actually I'm going to put that through. I want to I want to put this into the chat and just ask for clarification there.

Lem   1:50:03
Mhm.
Hmm.

Peter Wolf   1:50:16
Hoefully, it's back.

Lem   1:50:18
Other fields.

Peter Wolf   1:50:18
Chat you there, Chat you there. I can tell it's not working when it doesn't expand. When you talk, you know, it usually kind of moves like a heart. It's like beating when it hears the words.
Chat you there? Chat you there? Nope. Freaking ****** me off, man.
I'm gonna do it on my PC. Hold on.
Because this part this I I don't ever see this really being corrupted. It when it just takes the audio and converts it into text and uses it. This works at least every time I've ever used it. It's where it's using the advanced audio that is the problem.
Something's going on. See how it's not refreshing any of my history. So right now their system is overwhelmed for sure.

Lem   1:51:05
Uh.
Yeah, I think it's overloading.
Oh.

Peter Wolf   1:51:12
Got it. No worries. It sounds like they're you're there. You're alive.
Yes, I'm here. Looks like everything is working fine on my end. So OK, so then take this question. We're just talking about the database and some of the approach that I was talking about with you and I want to understand this better, whether this is one database structure or multiple database structures. So we talk about a contact.
Contact records database. That's the core of what we're talking about, right? I give a name, the database key is the person's first name, last name, let's say, and then all that information about them is in one long record. If you think in spreadsheet terms, you got your record is on the row, your columns or your features or your characteristics.
And I think of one contact record, just like you would export your record from your Outlook of your contact and would have all the details for that. But when we start talking about the history of engagement with the person, this is where it gets a little confusing to me. Would they just be more fields in that single record saying last time I met them?
Them where I met them, what the date was and then the next one's previous time I met them, time before that, time before that. So you would just have more fields in that record or would it really be a subset database of contact interactions and the database key, the cross reference key would still be the person's name and then the contact it would have.
Have all their contact information, but when we're talking about their history, that would be a different subset database that the records would only be history records and it would be the contacts name with the history record one, history record two, history record three. So help me to think about that if my developer were setting this, structuring this and building this.
Into a database would would we need to be thinking about this as multiple database structures within one overarching kind of use case?
That's a great question. In a more robust database structure, it typically makes sense to have two related tables or entities. One table would be your primary contacts table, where each record corresponds to a single person, and that's a great question.
Typically, for a more robust database structure, especially when tracking history of interactions, it's best to separate these into two related tables or databases. So you'd have one main database for contact records, which holds all the core information about each individual, like their name, company, role, and.

Lem   1:53:29
Yeah.

Peter Wolf   1:53:45
Other key details. Then you'd have a second database or table that tracks each interaction or engagement with that contact. This interaction table would reference the main contact record using a unique identifier like their name or an ID, and it would contain fields like.
The date of interaction, the type of event, any notes about what happened and so on. This way you keep the main contact record clean and easy to manage while having a detailed history of interactions that you can expand on indefinitely. And so what's the if we're building a database, do we actually go in and make 2 explicit?

Bryan Wolf   1:54:15
Mhm.
Hit.

Peter Wolf   1:54:22
Databases and then say the link is the database key is the name to tie them together. When you're when I'm thinking about tools like you talked about online or cloud-based database storage database management tool, do I go in and I build it that way as two databases and then tell it the link between the two?
Typically, if you want to link two sets of data, you'd create relationships between them using a unique key like a name or an ID. In a Cloud-based database tools such as Airtable or a more traditional database like MySQA, you'd have two tables and one table might reference the other using a unique identifier.
That way the data stays organized and you can easily navigate between related records. It's a great way to keep everything connected. OK, so again, if we're looking at my kind of structure, what I've laid out to you, what would you recommend as the database tool? And are there database tools? I don't know if they're they all pay to play or whether there's free database tools.
But robust, user-friendly tool that would meet with our needs of what what I'm talking about and defining here.
For a user-friendly and robust tool, Airtable is a great option. It has a free tier and it's very intuitive, letting you link tables easily and visualize relationships. If you're looking for something a bit more traditional and still free, you might consider Google's Firebase for a more scalable option, especially if you're.
Planning to grow and expand. Both are quite flexible and can handle the type of structure you're building. And are there benefits of the Google Firebase if we're thinking about generally using Google Docs and Google Spreadsheets and whatnot? Or is that not really an overlap or a tie in or benefit there?
There can definitely be some benefits to using Firebase if you're hardy in the Google ecosystem. It integrates well with other Google services and offers robust real time database capabilities, easy authentication and scalability, which can be really helpful if you plan to grill. It's also designed to work seamlessly with apps and other cloud functions.
If you ever decide to develop more advanced features or integrations, it can be a strong foundation.

Nicholas Westburg   1:56:35
Ask about Google Cloud.

Peter Wolf   1:56:38
You what?

Nicholas Westburg   1:56:39
Google Cloud.

Peter Wolf   1:56:41
What's the different? What's the difference between Google Cloud and Google, Google Firebrands? I mean, Google Cloud is just generally they're overarching kind of like Azure, right? I mean, it's really the environment.

Nicholas Westburg   1:56:43
I'm just curious.
Yeah, they have a bunch of integrations though, and like vector databases all within the cloud. So I don't know, maybe you can. That's an option.

Peter Wolf   1:57:04
So Lam, I would like you to.

Bryan Wolf   1:57:05
Didn't you set that up for me, Nick? Sorry, Nick.

Peter Wolf   1:57:09
Set one up.

Nicholas Westburg   1:57:09
Yeah.
Yeah, Brian, you're good.

Peter Wolf   1:57:13
So I I think Lam, let's, I mean obviously with Airtable, we've come across that and talked about that a few times because I've brought that's been brought up for some other scenarios, but I I think if we stay in the Google ecosystem, the Google environment.
And go with that Google Firebrands, then it should play nice with the other tools that we're using and with Gmail or other things like that. They can have immediate direct tie insurance and it would seem obviously what it says, scalable and.

Lem   1:57:33
OK.

Peter Wolf   1:57:48
Kind of seems to fit our needs.

Lem   1:57:50
Firebase, right? Google Firebase. OK, I'll, uh, look into this one.

Peter Wolf   1:57:55
OK, so I think you got enough meat there to work with for a while to to kind of make some conversions and to expand on this and connect in between the the flows and logic and the.

Lem   1:57:56
Google Firebase.
Yep.

Peter Wolf   1:58:11
A conversion for the selection and filtering and stuff like that.

Lem   1:58:13
Yep.
OK, so yeah, let me just clarify. Yeah, the like the main goal here is to extract data from just plain words, right? For example, here's a sample input here and then we.

Peter Wolf   1:58:18
Alright.
Yeah, you want to go. Can you share again? Can you just share just so we're if there's anything you need to show?

Lem   1:58:35
OK yeah this for example this one like the add the new contact name is John. He works at booking.com. He's a colleague of Tom Devine so we would parse this out and.

Peter Wolf   1:58:46
Yep, Yep.

Lem   1:58:48
Yeah, the ChatGPT should be able to get the relevant relevant information here and then filter it out on our database and then get the information off. Yeah, so this add a new contact is actually for the adding of the the adding on the.

Peter Wolf   1:58:55
Yep.

Bryan Wolf   1:58:55
OK.

Lem   1:59:08
Yeah, yeah. But for the extraction, yeah, that's right, yeah.

Peter Wolf   1:59:09
Yep. So that's that that's a real use case, right? I'm standing there. Someone just introduced me. I'm going to quickly just say that into the app or into ChatGPT. I'm really expecting it to be an app that we're going to build an app that's going to be a front end that will then take that and feed it into the agentic process flow.

Lem   1:59:20
Yeah.
OK, OK. So I yeah, with playing routes.

Peter Wolf   1:59:33
And then on the retrieval side, I think we'll start out with the basics. Again, I'm trying to find an individual, but it will expand because then I would say, hey, tell me everybody that works in the HR department at Sarala, if I'm trying to figure out who I should interact with or call about something or who's in the marketing department, what are the teams?

Lem   1:59:51
Yep.

Peter Wolf   1:59:52
Then that would be more exansive. But right now, let's assume I'm kind of looking for a single individual or I'm adding a single individual.

Lem   1:59:59
Yep. Yeah. So yeah, this would be OK. Yep, got it.
I mean, you can't do this.

Peter Wolf   2:00:12
All right, so I think we're pretty much at at time.
I feel like I'm in a therapy session. OK, so they're gonna call it a day for today. Yeah.

Bryan Wolf   2:00:20
Yeah, I mean, me too.

Peter Wolf   2:00:24
All right, this is good stuff. I yeah, I like working through this in the details and I think some of the issue for me is that, as I've said before, I just finding the time to go into the details. I feel like on a number of these tools.

Bryan Wolf   2:00:39
I know.

Peter Wolf   2:00:42
We're very close, but it's this kind of granularity where really I'm going to have to commit the time for us to get that extra step. I feel like we have good working prototypes, but they aren't, they aren't really fully there yet and that's.

Lem   2:00:54
Yep.

Bryan Wolf   2:00:55
I agree. I agree. I totally agree. I think we all agree. It's they're they're like they're.

Peter Wolf   2:00:58
Yeah, yeah. But I think that's also, look again, we're we're a month and a week in or month and two weeks in. And for me, the progress we've made at just even getting our arms around it, understanding this, seeing what the basic functions or capabilities are.

Lem   2:00:58
Yep, Yep.

Bryan Wolf   2:01:12
Yeah.

Peter Wolf   2:01:15
I I'm I would love it to have gone faster, but I think this is good.

Bryan Wolf   2:01:18
Listen, I think, I think before you leave we should really just lay out detail like what your thoughts are and what you want. Because I know because it's step by step, but if you could just put out a rough copy of like 3 things you're like, you know, just whatever, something like that and how you want to accomplish.

Peter Wolf   2:01:25
Yeah, it's gonna be hard. It's gonna be hard, I know.

Peter Wolf Jr   2:01:44
OK.
2.

Peter Wolf   2:01:44
I could. I could just talk on the way home. I could drive ChatGPT. I could just talk. Although it goes dead, it goes dead for half the ride because there's no reception.

Bryan Wolf   2:01:49
Yeah, yeah, yeah. Even if we could hop on a call and you could just ramble and I could have that recorded call to call back on. So like, you know.

Peter Wolf   2:01:56
Yeah.

Peter Wolf Jr   2:01:58
Yeah, I agree with. I agree with Brian, even if it's a stream of consciousness like 30 minutes.

Peter Wolf   2:01:58
OK, we could do that. We could do a teams meeting.
OK, let's do that. Let's do that. Let's on the way home, when I'm driving home, it's an hour and a half minimum ride. Then we'll just do a set of teams meeting up and then I'll just talk. I'll just talk about what it is I'm looking for and how we expand this. Yeah, OK.

Bryan Wolf   2:02:09
Yeah, yeah.

Nicholas Westburg   2:02:11
Yeah, that'd be great.
Just speak, speak your chest.

Bryan Wolf   2:02:18
OK.

Peter Wolf   2:02:19
That's good. I like it. I got to look at when I'm going to be able to fit this in my calendar to leave, but right now it probably makes sense for me to go.

Bryan Wolf   2:02:20
Oh.

Peter Wolf   2:02:31
So I got a call from 12 to 12:30. It might might make sense for me to leave at 12:30. So then we set that meeting up for for then. I just got to get my crap together.

Bryan Wolf   2:02:44
OK.
Yeah, yeah, I'm sure that's that that I'm that times tentative, I'm sure, but that's that's uh.

Peter Wolf   2:02:47
And I can push. I got 1130 and two. Yeah, yeah, yeah, you know, that's tentative.

Bryan Wolf   2:02:53
Yeah, yeah, yeah. So let's just wait and then just give us a heads up right before you go and you know like 1520 minutes and I can hop on. I'll be able to do it all day. So I don't know about Peter and Nick, but yeah, so.

Peter Wolf Jr   2:02:58
Thank you.

Peter Wolf   2:03:04
OK, well, as soon as we start, I think this is also a good one. We got to make sure to tell Peter. I think walking through this, Peter reviewing this discussion is important because I think talking about the agentic brain stuff and the logic and all, I think this is.
Helpful to understand context.

Bryan Wolf   2:03:23
Yeah, but almost if you could if. So did you lose all those chat records if it's like it typed out responses? Yeah, 'cause if you could send like it's something like that, I think I could even maybe even log into your GPT.

Peter Wolf   2:03:28
No, I got them all, yeah.
I'll share. I'll I'll send you right now. I'll send you the the actual chat connection and then you can here so.

Bryan Wolf   2:03:38
Yeah.

Peter Wolf   2:03:46
I gotta restart my PC.

Bryan Wolf   2:04:32
So Lem, are you gonna create a new Jason to implement all this new information or what do you usually do? Like will you just keep messing around with the actual prompt in the inside the make agent or?

Lem   2:04:40
Yeah.
Yep, that's right. Yeah, for the testing. So I will tweak the prompt and then.
Of but first I will.

Bryan Wolf   2:04:54
Just keep tweaking and keep tweaking and keep tweaking like almost refining it like that, yeah.

Lem   2:04:56
Yeah, that's right. Keep tweaking. Yep, that's right. And yeah, I would need to change the like the tools. So the tools would be have like add a filter there like a filter step for the and also for the adding of data.

Bryan Wolf   2:05:00
Alright.
Yeah, right.
You had showed that, yeah.

Lem   2:05:12
Yep.
And I will adjust also the prompt.
To accommodate for this one.
Uh, guys, I also have a call in a couple of minutes if I could. Uh, yeah, see you guys. See you guys tomorrow, OK?

Peter Wolf   2:05:27
Yep. All right.
Talk to you tomorrow then.

Bryan Wolf   2:05:32
Then we'll talk tomorrow, man. See ya.

Lem   2:05:34
Yeah. Talk to you soon, guys. OK, bye. Bye.

Bryan Wolf   2:05:36
And.

Peter Wolf   2:05:37
Oh, this sucks. So right now, no, no, I didn't lose it, but it won't let you share the when you have chat, so I'm gonna have to.

Nicholas Westburg   2:05:38
Hello.

Bryan Wolf   2:05:39
You lost your chair. I knew you did.
I almost wanna see if I can just do I have your chat?
Don't think I do.

Peter Wolf   2:05:56
No, I don't. I mean, if you logged into my account, you would. But hold on one second. I I think I can. I I gotta restart my PC. My stuff's running too slow. Let me shut down. I'll log back in and I'll, I'll ping you. OK. All right. See you.

Bryan Wolf   2:05:57
I also think, I also think on your.
OK.
Yeah.
Yeah.
His recorder is still on here. I wonder if did you say ping you can come back in? I don't know.

Nicholas Westburg   2:06:25
No worry.
Mhm.
Hello.

Bryan Wolf   2:06:33
That was good. Look, he he knew what we were even saying without even having to say it, you know?

Nicholas Westburg   2:06:38
Yeah.

Bryan Wolf   2:06:39
I like that it's like came up almost like we spoke into existence, but yeah.
Or should I stay R or what? I guess he's gonna restart his thing. Is he gonna start ramble now or is it 12:30?

Nicholas Westburg   2:06:53
Yeah, I don't know. I gotta run. I gotta.

Bryan Wolf   2:06:54
He's just gonna. I know, man. Dude, I love you, though. Dude. All right, well, I guess he'll just hit me when he gets back.

Nicholas Westburg   2:06:58
Yeah, yeah, yeah.
Text me, text me if he starts rambling or he's going on about, you know.

Bryan Wolf   2:07:07
Yeah, whatever. I don't even like. I don't like the idea of the rambling. I don't want to just hear him ramble on the car ride home from the shore. I don't want that. No, he's no. I'm at home. He's coming back because he leaves for Germany on Wednesday at 1:00 for like 7 days or whatever. So I want us to be able to accomplish **** from that Wednesday through.

Nicholas Westburg   2:07:12
I think you oh, you're gonna be in the car with him. I feel like it would be better if you.
I like this, Brian. This is how I always like it. I like when people listen, listen, listen. I personally, not personally. I think it's good when I always like talking. It's, you know, it ***** up or whatever. But I I've realized that and I'll talk into my notes like not directly to an AI and I'll just like speak my thoughts.

Bryan Wolf   2:07:26
Friday.
And then he comes back like that Tuesday.
Right.

Nicholas Westburg   2:07:44
And whatever I'm saying right into a notepad while I'm driving, I'll just like click start or I'll click like audio and then I'll get. It's not that hard and to ensure that nothing doesn't get captured and I just ******* ramble my thoughts in my head, OK.

Bryan Wolf   2:07:45
Yeah.
OK.

Nicholas Westburg   2:08:00
So then that's that we have that right. He can think and have clarity while in the car and then it's more so like, OK, we can really dig into the transcript that he has and his thoughts and and what he's let me finish and what he said, right. And then we can analyze that and then not only that, we can then.

Bryan Wolf   2:08:11
Right. OK. OK. OK. I like that. I like that.

Nicholas Westburg   2:08:20
Look at it, read everything that he, you know, his thoughts and and him going on and then come back with questions. Any questions that we have, ideas that we have solely based on him speaking his thoughts and you know, just.

Bryan Wolf   2:08:23
Yeah.

Nicholas Westburg   2:08:37
His brain, so does that.

Bryan Wolf   2:08:38
We gotta get him to **** him his brain for sure. Like literally narrow link type **** like.

Nicholas Westburg   2:08:42
Stop ******* worrying about ChatGPT audio. Just open up a notepad.

Bryan Wolf   2:08:45
No, I know he's so too speaking back and forth with that instead. Like we're just, it's too much conversation with that. And I feel like it's just like, you know, it's a great tool, but it's also just like it makes me feel stupid, like you almost just talking to someone for relying on you.

Nicholas Westburg   2:08:56
Yeah.

Bryan Wolf   2:09:04
So, yeah, I'm fine. Nobody gets sandwiched.
OK.

Nicholas Westburg   2:09:12
All right, brother.

Bryan Wolf   2:09:13
Talk to you later.

Nicholas Westburg   2:09:14
Peace.

Bryan Wolf   2:09:15
Yeah.

Peter Wolf stopped transcription


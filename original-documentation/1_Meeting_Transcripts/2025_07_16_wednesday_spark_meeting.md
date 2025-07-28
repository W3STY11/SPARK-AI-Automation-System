# Process Automation Workshop (29)

**Original File:** Process Automation Workshop (29).docx
**Extracted Date:** 2025-07-16 (Wednesday)
**Converted:** 2025-07-28 11:40:58

---

Transcript

July 16, 2025, 12:58PM

Peter Wolf Jr   1:07
Morning, Mr. Wolf.

Lem   1:50
Hi guys, how are you?

Bryan Wolf   1:52
Um.

Peter Wolf Jr   1:54
How you doing?

Lem   1:55
Yeah, all good.

Bryan Wolf   1:58
That's good.

Peter Wolf Jr   1:59
That was the wedding.

Lem   2:02
Yeah, it was nice. It's actually had fun also with some old friends.

Peter Wolf Jr   2:04
I.
Sure.

Bryan Wolf   2:12
Did uh Peter send you any of those Excel files or no?

Lem   2:13
Catching up.
Uh, no. I haven't received anything yet from Peter and also.

Bryan Wolf   2:19
Oh my God. Alright, I'll get them sent to you this morning.

Lem   2:23
Uh, on Upper, he didn't, uh, message me.

Bryan Wolf   2:24
Or tonight.
Messaged you? Yeah, I called him and he said he was gonna, but I guess he just didn't get around it. So I'm not there yet. I'll be there in the office in a couple minutes and then I'll speak to him and see if we can't get that stuff sent over to you. And then maybe we can work through it this morning or just cast it out.

Peter Wolf   2:34
Yes.

Lem   2:34
OK.
OK, no problem.
OK.
Hi, Peter.

Bryan Wolf   2:50
Mhm.

Peter Wolf   2:51
Hey, how you doing man?

Lem   2:53
Yeah, all good. How's your travel on?

Peter Wolf   2:58
It's good.

Lem   3:00
Germany. Uh, it's good.

Peter Wolf   3:01
I think, but good. OK, let's jump in. I see Ryan and Peter is Nick.

Bryan Wolf   3:10
Why don't you start off and you send him the database files with all the contact list information in there?

Peter Wolf   3:16
So yeah, we can. We can start by discussing this. Hold on a second. Um.

Lem   3:21
OK.

Peter Wolf   3:50
And let me know when you see my screen.

Lem   3:54
Yeah.

Peter Wolf   3:55
So I went through and I I exported my contacts from Outlook and then weeded out ones that were just businesses and and I have 17 hundred 1700 contacts.

Lem   3:55
Yeah, I can sit.
OK.

Bryan Wolf   4:08
I can say it's quite a lot.

Peter Wolf   4:11
So um, and I was what I also went through like here was the original uh.

Lem   4:27
8.
Company, Uh, Department, Job title.

Peter Wolf   4:31
Yeah. So hold on. That's what we'll get to. Hold on a second. So, um, what I have was the original.

Lem   4:34
OK.

Peter Wolf   4:42
In that all these fields here, right? Lots and lots of fields 'cause this is just normal outlook. Um.

Lem   4:47
Yep.

Peter Wolf   4:51
Characteristics, information, data fields, right? So then I I went and deleted all the fields that were not of interest to me and then and and recognizing that it even may be further that I don't want these other fields, but I I immediately.

Lem   4:55
OK.
OK.

Peter Wolf   5:11
Deleted the ones that were definitively not of interest to me. I'm not intending for this to be my contact database, meaning if I want someone's phone number or business name or whatnot, I don't expect this to be where I'm going to store it. When we get deeper into this flow, it may be that what I do is.

Lem   5:14
OK.
OK.
OK.

Peter Wolf   5:30
Take the flow and then build a connection to the contact database that would say OK, update my contacts to add this person to the contacts or go to the contacts and pull the information that's in the contacts.

Lem   5:43
OK.

Peter Wolf   5:47
Database to supplement, right? But this database is not intended to be a replacement of my e-mail Outlook contacts or my Gmail Outlook contacts, right? So I only I was really as I was doing it, I was saying, OK, well, which fields do align with some of the topics that we're talking about?

Lem   5:50
OK.
OK.

Peter Wolf   6:06
About or characteristics and features that will be in the database. So I remember we were we had, we changed a few things right before kind of the last day when we talked about it and I don't remember where we ended up. So I wanted to leave some of these and say, OK, I don't know if they fit or don't fit. I didn't want to delete them and then turn out.

Lem   6:18
Yep, sure.

Peter Wolf   6:26
That we had a place to put them. So when I look at like department and job title, well I know we had job title and I remember we we were talking about OK, could it differentiate between?
Role and title and I think you you said you went about something. So we wanted to understand that about the role and title and and maybe that kind of role is really department or something along those lines, right? Because here for example I got.

Lem   6:44
Yep, that's right.
Yep.

Peter Wolf   6:57
Consulting, Surround Treasury Services or sales, finance, right. So I think this might be, you see, I don't use this all that much, right. But if there was information in here, I don't want to lose it that would align with what we what we have, right. So then.

Lem   7:02
Yep, let's try.
OK. Yeah, that's right.

Peter Wolf   7:15
So I think this this first name, last name definitively. I don't think I need this hold on suffix and company name title. I don't remember what we did here. I mean I don't need Mr. or Mrs. or anything like that but title.

Lem   7:33
Yep.

Peter Wolf   7:34
Was really title like this job title. So this is a different this is like salutation title like doctor Mr. right? So I don't need this this title although.

Lem   7:38
Yep, that's right.
Mm.

Bryan Wolf   7:43
There's good.

Lem   7:44
Yep.

Bryan Wolf   7:46
Thank you, brother. Yeah, appreciate it, man. Have a good day.

Peter Wolf   7:49
Although, um, I mean maybe this really like for anybody that's say uh doctor.
I mean this this should obviously if they're all.
As a dentist, right? So I mean.
Say.

Lem   8:25
Doctor.

Peter Wolf   8:28
OK, so then take that out.
OK, so then we get rid of this.

Lem   8:55
OK.

Peter Wolf   8:56
So we got first name, last name, company. And so on this would we say this is what we were doing is kind of roll. You think that's the closest this would come is roll or what do we call it there? What did you end up on in your database?

Lem   8:57
Nice name company.
Yeah, yeah, like they're all.
I think industry, some kind of like, yeah, like industry, but.
Yeah, like something like that, like sales, I think you also had uh.

Peter Wolf   9:26
We can come back and we can figure this out. So then title, job title for sure we have something that's title, right?

Lem   9:29
Yep. Uh.
Yeah, chop that up. Yep, that's right. And.

Peter Wolf   9:36
OK, and this doesn't make sense here.
Uh.
Yeah, so I'm gonna have to do a little more clean up on this, but because you can see I have companies in here where the name is a is a business, not a person's name.

Lem   9:57
Hmm. OK.

Peter Wolf   10:02
I can worry about that later. So then job title. So the only thing I was thinking here was.
Like this isn't really business address, but it was kind of like the city, the state and the country. I don't think I really need this. Again, it's not gonna be my contact database. So if I had some information like that, I would just put it in the additional comments.
Did we ultimately determine? I can't remember when when you were saying you'd have to go do a search. I think we determined it was better to use fewer fields so that you would not have to run a search on multiple fields like if I said.

Lem   10:35
Yep.

Peter Wolf   10:43
Appearance. And then I had another one that said, you know, um, I don't know, hair color or something that wouldn't make sense, right? Because just put put it all into that appearance since we weren't trying to make it a um, we weren't trying to make it like you would.
Typically come to a spreadsheet and filter for it, right? Did we determine, did we decide that that was the route we were going to go was more fewer fields kind of with generic information and then that way if you had to do a search that you wouldn't be searching on 10 fields where we would spread it out because remember I had I had like spouse.

Lem   11:06
Oh.

Peter Wolf   11:18
And then children. Then I had family relationships. It was like, I think we got rid of spout and children and just put everything in relationships, right?

Lem   11:18
Uh.
Yeah.
Yeah, yeah. So I actually put all of the like all of the columns there because maybe you're the information that is being inputted is coming from for example appearance. So we would need.
It would actually just put the appearance on the search query and not like the first name and last name. So if you give the first name, last name and appearance so it would also search with that three criteria.

Peter Wolf   11:53
Yeah, I understand. But I'm saying when in the can you show me, let's let's do this, show me the spreadsheet that you ended up with right now that we have because I think I'm going to be able to take all of these off and just leave this notes column I have. But you know I have here like children.

Lem   11:58
OK, Yep.
Um, OK.

Peter Wolf   12:12
Category. I said I was gonna keep category, right? This is home country region. I mean, I I think something that's gonna identify the country where the person lives or probably is gonna make sense for me, but that just can go into generic information. I think I'm gonna dump all this stuff here.

Lem   12:13
OK.

Peter Wolf   12:31
And I don't think I need a separate one. It's going to be children category. I said I would have profession and your spouse. Again, I think we said we weren't going to include those, but then I do have referred by, but this I don't feel I've never filled in for anybody.

Lem   12:42
Yep.

Peter Wolf   12:50
So I wouldn't need that at least. And this I don't never use it. I don't even know where that field is on Outlook, but.
So show me what you what you have and then we'll tweak this here. I'll stop sharing.

Lem   13:02
Um, OK, so let me share share my screen.
OK, so yeah, the yeah, the test database is something like this. So we have the sequential number, first name, last name, a date, last updated and yeah company. So roll this was like the.
Like the job description and the industry is, yeah, the industry and then business relationships, personal relationships.

Peter Wolf   13:35
Yeah, hold on, hold on a second. Let's just make sure what we got here, 'cause role in industry, role industry. Where's title?

Lem   13:40
OK.
Uh, the title would be the.

Peter Wolf   13:50
Role Project Manager, Marketing lead.

Lem   13:50
Yeah, yeah, I think it would be the role. Yeah, the role. This is like the. This would be like the job description.

Peter Wolf   13:54
It looks like the way you have it. That's the way you have it.

Lem   14:01
And then, yeah, the industry is, yeah, the industry. So this is just like test. So it would coming from ChatGPT, so could be different from yours. But yeah, basically that's it. And then.

Peter Wolf   14:16
Yeah, I'm just trying to figure out what we, you know, again, how to approach this. Hold on one second. Let me just take a screenshot here.

Lem   14:25
OK.

Peter Wolf   14:27
OK, so let's let's see what else. What else you have. Personal. So business relationships, personal relationships, appearance, other comments, contact, category, source. Yeah.

Lem   14:39
Yep.
And then the interactions is on a different spreadsheet. So yeah.

Peter Wolf   14:51
Yeah, yeah. Hold on. Can you just go back to that? I was just gonna take a screenshot the whole thing.

Lem   14:55
OK.
Yeah, here's the first name.

Peter Wolf   15:05
OK, so um.
When I look at my sheet, I'll share again.

Lem   15:20
Oh.

Peter Wolf   15:32
OK, I'm gonna get rid of all this.
I don't think I've ever filled that in. I don't have that filled in, don't have that filled in so I can get rid of these because I'm not losing anything.

Lem   15:42
Yeah.

Peter Wolf   15:48
I've never filled this in referred by either.
Children.

Lem   15:54
Oh.

Peter Wolf   15:55
Great. So now, yeah, but I didn't have. I've never used it. I don't have anything in there. I want it in the new database, but I don't have anything in Outlook. I never filled that field in. I don't even know where it is. So I wasn't losing any data. It wasn't that I don't want to use it. I just don't have anything coming over from the.

Lem   15:58
Yeah, referred by be the introduction, I think.
Oh, OK. OK.

Peter Wolf   16:15
Existing file for that so so then.

Lem   16:17
OK.

Peter Wolf   16:23
Uh.
So this would be other whoops.
Uh, other comments, OK.
This is contact category.
I'll have to figure out how I want to convert that job title, industry company, company, last name, first name. So these are good. These two right here, Job description, product manager.
Yeah, I'm trying to think of how to handle this.
OK.
So you were saying there was some trouble when you were trying to use AI to differentiate these or something, right? So if I just made a if I just made one one field that I just called job description.

Lem   17:59
Yeah, uh.

Peter Wolf   18:06
And in that if they had a title, I'd give their title and if they didn't have a title and I just had the role, then I would just give the role. Do you think it's you think that would work? It's just a kind of singular field so that I'd say, well, yeah, the head of HR or their director of Treasury services, I mean if I.
If I put that as their job description, but I left it where I could, I could fill it the way I want to. That would make it less confusing about having two fields trying to cover this.

Lem   18:25
OK.
Yep, that's right. Yeah, we basically we could do it as job description and then it would have their like the their role, their industry and also like something like that. So yeah, I would just like adjust the prompt that it would also.
It would also include that one and then we will delete the industry altogether so that all of the like job description would be on that particular column. Yep.

Peter Wolf   18:59
Yeah, I think that again, back to this kind of viewer fields in a spreadsheet, it makes sense that I would want a whole bunch of columns that I could very specifically filter on, say, show me all the people that are in HR, show me all the people that are.

Lem   19:15
Yep, that's right. Yeah, this this action.

Peter Wolf   19:15
Directors but but here in AI model it's it's like having all those extra fields makes it more difficult or adds administrative overhead to try and retrieve the information.

Lem   19:27
Yep.

Peter Wolf   19:29
OK, so if I.

Lem   19:30
But yeah, I I think ChatGPT could also process for example like give me all the HR, so it would give all the HR and then as we've tested also last time, right? Like OK give me, it will give me give all of the HR on all the companies and then you would ask it again, just give me the.
HR on like Sarala and then it would like give all of the data to like only Sarala. So I think yeah the AI would understand that context and it's just the like the searching.
The searching of the variables that that's the main challenge if we have like 2 similar categories like job title and role, so they are quite similar. So yeah, the AI gets confused about that.

Peter Wolf   20:09
Yeah.

Lem   20:19
That that one.

Peter Wolf   20:20
Yeah, yeah. So I think I'm gonna put it. I'm gonna put it all into one field and.
Uh.

Lem   20:30
Yeah, because as as I can see also like it has like general counsel as industry also here, but yeah, also the Chief Technology Officer, so.

Peter Wolf   20:32
Yeah.

Lem   20:43
But for the other ones, I think it's good like finance, consulting, corporate development, growth. But yeah, we could also do it as as I've said a while ago, just like a job description and then.
You we would have there like for example all the all the people in finance. So it will search your job description and then pull out all the people on finance and then you could filter it out. Just give me the ones on Seralla, the company in Seralla. So yeah, the AI would get that contact.
And it's just more steps, I think if we do it by that way.

Peter Wolf   21:26
More steps. You mean if we do it by having two columns or?

Lem   21:30
Um, um.
Would it would also depend on like the end data that you want, but if we for example you have the like the industry here on the job title right? Like for example.

Peter Wolf   21:40
Yeah.

Lem   21:51
Give me all the like the all the people on finance. So it would also give all the people on finance here like the manager and then the like the account executive. So you would have a next step wherein you would say that can you just give me all the people in finance and then the.
Our product manager for example or like like VP of sales, so for example like that. So it would filter it again and then just give you the that particular. So it's like a two step process also because it's on a similar column.
If that makes sense, uh.

Peter Wolf   22:30
Yeah, I I and I understand too what you're, you know, what you said about depends on how I'm going to intend to use it. What's the output expectation, right? That's I guess still a little bit vague for even myself, but as I'm thinking through it, I really wanted just for kind of quick, easy access.

Lem   22:46
Yeah.

Peter Wolf   22:50
Understanding who somebody is and remembering their role and or if I'm trying to figure out even within my own organization, who do I have to contact when I want to deal with the marketing, digital marketing, right? Then it would be OK, everybody that's in that department or anybody that I referenced that.

Lem   22:53
Yeah, that's right.
Yep.

Peter Wolf   23:07
But I don't. I'm still just not sure if having two different columns for that or one column and just saying with a role, their department, their title, everything is bundled into their job description. That way you only have to search one place.
And and some of the times their role and their title are gonna be, they're gonna have and their industry or their department is all gonna be in the one, right. It's like head of head of digital marketing. OK, well, that means they're in the marketing department, that's for sure. The head means, you know, that's their title.

Lem   23:24
Yeah, that's right.

Peter Wolf   23:43
The head of or or you know or director of of marketing, then I'm gonna know they're in the marketing department. So I really think it is going to be best if I just cluster all this together. If later on it's determined that it makes more sense for me to separate, then I could separate.

Lem   23:57
Yep.
Yep.

Peter Wolf   24:02
So if I just do this, I'm going to call this job.
Description. Did I spell it right? I can't even see my letters. There we go. Description. And then I'll put.
We close.
What didn't it like?

Lem   25:02
OK.

Peter Wolf   25:06
So now if I had something in here that it's populated in before this slash, I get the whole thing in there. So I think this is copy.

Lem   25:13
OK, Yep.

Peter Wolf Jr   25:15
Yes.

Peter Wolf   25:19
Oh, hold on.
OK, so now I took the formula out, so now we're good.

Lem   25:59
Um, I think the other information was gone. Is it uh?

Peter Wolf   26:03
Yeah, I just deleted it. But what I did was I took the only ones. There were 125 that had some information. Hold on. Maybe I just. That was stupid. You're right. Hold on. Because I only wanted to delete the blank ones here. I wanted to get rid of.

Lem   26:06
Oh, OK, yeah.

Peter Wolf Jr   26:08
OK.
It.

Peter Wolf   26:19
I want to get rid of this, so this is.
Oh no, hold on. I only did it for those. OK, so here's the problem. I did concatenate, but I had filtered only to the ones that had a value in this field. So now really what I need is I need to do the blanks.
And just put equals.

Peter Wolf Jr   26:53
OK.
1.

Peter Wolf   27:31
Uh.
Oh.
Um.
So.
Yeah, I should've done it this way. Give me one more second here. So all these.
Should just say.
S.
There we go.

Lem   30:13
Yes.

Peter Wolf   30:23
OK, so now.
Now I have everything that I need, right? They're blank. They're blank. If they had no industry, then they're just a list of these right here. This is junk. Um.

Peter Wolf Jr   30:27
Yeah.
6.
Mhm.

Peter Wolf   30:42
Right, so now I can get rid of these other two columns because I have everything I need in this last column. Concatenate it when there's more values than when it includes industry and then nothing if it's not so.

Lem   30:49
OK.

Peter Wolf Jr   30:51
So.

Peter Wolf   30:57
Dave.
Copy. Just double check. Make sure I only pasted it without the formula. Delete this.
Here we go now from contact category. Um.

Lem   31:10
OK.

Peter Wolf   31:15
What was I intending to do here?

Lem   31:17
For the let me just, I think you have choices also for the.

Peter Wolf   31:24
There's contacts personal. This is gonna be OK for now. I can I can always have it get change it later on, right? So this differentiates contacts that are personal, Sarala and or I think I was using some others.

Lem   31:33
Yep.
OK.

Peter Wolf   31:39
Things too. This is good enough. This is good enough for now. So then OK, so I think this this is our this is our baseline to load up right to get into the into the database. Now how do we how do we envision? That's because you already have a spreadsheet, right? I just need to.

Lem   31:43
OK.

Peter Wolf Jr   31:49
Yes.

Lem   31:51
Yep.

Peter Wolf   31:59
Move this into that spreadsheet, right?

Lem   32:01
Yep, that's right. We'll if you could give me like a CSV file for this and then I'll put it on the spreadsheet for.

Peter Wolf Jr   32:09
OK.

Lem   32:16
Testing and then later on we could just duplicate the spreadsheet on your account.

Peter Wolf Jr   32:19
Yeah.

Lem   32:29
Yeah, just I think I would just need to change a little bit. The prompt here is just for the job description, so it has to all of the industry and stuff.

Peter Wolf   32:30
Yeah.
OK.
Let me just, uh, hold on.

Peter Wolf Jr   32:42
OK.
Oh.

Peter Wolf   32:45
This is not showing up.

Peter Wolf Jr   32:46
Move.

Lem   33:06
Job description.
Find, find data.
And.
Contact hard database.

Peter Wolf   34:05
No, no, it's saying.
OK.

Lem   35:03
JavaScription.

Peter Wolf   35:10
All right. So then can we, can we now look at what stuff has taken place with that flow since I left, where we are, what it's doing, whether we?

Lem   35:22
OK, uh, let me just.
Get the e-mail.
Um.
OK, download.
OK.
Uh, let me share my screen first.
OK, so first name, last name.
Um.
Yeah, this is wrong.
Should be the first name.

Peter Wolf   37:03
Right. So if you just insert and push everything to the right one, you should be OK.

Lem   37:09
Yeah, this one, right? Um, this other.

Peter Wolf   37:13
Go from row from row two, click in column one.

Lem   37:19
OK, this one.

Peter Wolf   37:20
Right there, click in, click in cell 2A right 2A click in cell 2A. Now hold down your cursor and and go all the way down to the bottom of the OR. I don't know, is this just mine being added or is this the ones you already have which were the?
Dummies.

Lem   37:38
Uh, I deleted all the yeah, I actually, Yep, that's right.

Peter Wolf   37:41
You deleted all the dummies. OK, then then go up to A, click on column A, click on column A.

Lem   37:47
OK.

Peter Wolf   37:48
Insert. Insert.
Yep, Yep one column. Yep. Now now delete. Go into column into 1A, cell 1A, cell 1A, cell 1A, 1A. Now delete that cell, delete cell, right click, delete cell.

Lem   37:52
Sir.
One column left.
So.

Peter Wolf   38:12
Should be able to delete cell. Yep. And then shift to the left. Now everything in the header will shift to the left. Go. You're good. You're good. Now you got the sequence name in all blanks, first name, but we got it backwards. So how about you just change yours and put last name, first name? Just swap the headers.

Lem   38:14
OK.
OK. Oh, OK. Yep.

Peter Wolf   38:28
Swap the header, right? Copy you.

Lem   38:30
I think this is already good. First name. This is first name, right? Yeah.

Peter Wolf   38:33
Oh, it is first name, last name. OK, OK.

Lem   38:39
Yeah, I think it's first name, last name. This is the company. So I'll just again, I think I could.

Peter Wolf   38:46
Yep. And you could you just copy everything, paste it into the next comma. Yeah, Yep.

Lem   38:52
Yeah, yeah, I think I could just copy that.
And then I'll just change this to company, company and this one.
Then uh, contact category. So it should be here. Uh.
Um.
Contact and then other comments.
Other comments.
Uh, OK, so.
Category and.
It OK, that should be good.
And then I'll delete this bus.

Peter Wolf   39:59
Hold on, hold on, hold on. What did we just do? Wait, wait, wait, wait, wait, wait, wait. We lost. So job description. Can you Scroll down? Scroll down and just scroll way down. Just Scroll down. Keep going, keep going, keep going, keep going. Just go until you see content in that job description.

Lem   40:06
OK.
Um.
Oh yeah, um.

Peter Wolf   40:18
See, I think we deleted the wrong column.
Do undo what you just deleted. Yeah, that job description was what we want to keep. No. Or industry.

Lem   40:29
Um.

Peter Wolf   40:34
What did I send over? Is that what's the titles I gave you? Contact category? No, that's not right. Company. Company. That's wrong. That's because you copied it over, right? Then it was contact category. Yeah. So contact category you took over. So that's good. You can delete column F.

Lem   40:42
Yeah.

Peter Wolf   40:52
You can delete column F, right? Because that's already put over into. Oh no, hold on, hold on, hold on, hold on.

Lem   40:55
Yeah.
I think the ones missing is the job description, so because these are like the headers coming from the.

Peter Wolf   41:05
Yeah, yeah, but that one you copied already and pasted. But so job description like OK, so job description you put or no industry you put into the other comments column.

Lem   41:16
Yeah.
Yep, here.

Peter Wolf   41:22
But that's not where it should go, right? Industry, we said we were going to keep that was going to be the hold on other comments. Oh, so OK, that's my column coming over, right? Other comments is my column. You put it into the other comments. OK, Scroll down. Bart's team, just Scroll down. I just want to kind of see what shows up in that other.

Lem   41:34
Yeah, that's right. Yeah, this, this one.
I I think the job description is missing. I'm not sure.

Peter Wolf   41:42
CT Treasure Team.
Industry.
I see IT resource group. That's fine, that's fine. So so that one here and I'm just looking at mine now. Give me one second. So down description.

Lem   41:49
Uh.
Uh.

Peter Wolf   42:01
Contact category.
Description.

Lem   42:05
Um, let me just check also the.
CSV.
Uh yeah, the job description here is missing.
I just checked the.

Peter Wolf   42:19
No, no, it's it's missing on a lot of them. Scroll down. It's only the the.

Lem   42:23
Oh, OK. Um, oh.

Peter Wolf   42:25
Doesn't have it all on. Scroll all the way down the bottom. Keep going. Scroll, scroll, scroll, scroll, scroll, scroll. Keep going. There you go. See. So that job description, that's legitimate. That job description is legitimately the job description. Not that didn't go into other comments.

Lem   42:28
Uh.
Oh, OK, yeah. Um.
OK.
Um.
Yeah, I think this is the one, the job description. Um.

Peter Wolf   42:53
Right. So then you don't want to delete that industry one column QG. That was the one that you took to other comments because that's the header up there, right? Scroll all the way up.

Lem   42:55
Yep.

Peter Wolf   43:05
It is. You can see they're parallel, right? So get rid of, get rid of G.

Lem   43:08
Oh, I think this is contact category, the F1. Yeah, so it didn't can. Yeah, it was. Can I? I think I'll I'll import it again.

Peter Wolf   43:11
Contact care.
But then what happened to job description? What happened to job description then?
No, no, no, no, don't, don't, don't, don't, don't import again. Just wait one second because when we started copying columns then you didn't change the headers, right? So it looks like which ones came from the input or which ones were copied columns, so.

Lem   43:22
'Cause maybe, uh.
Oh.
Yep, that's right. Yeah, this this should be the headers that are coming from.

Peter Wolf   43:38
Yeah, they were the original original headers now. So when I sent it over to you, we had first name, last name, company, job description, contact category and other comments. So contact category.

Lem   43:40
Yeah.

Peter Wolf   43:54
So I think that is that is legit contact category right now. F can you just do me a favor and color, color, color in row two and just put green on contact category? No, no. Yep, Yep, Yep. Make that green.

Lem   44:08
This one.

Peter Wolf   44:11
Right. OK, so that's legitimately contact category, company, company date. So now in your date of last update, you need to go over there, click in that column and really get rid of all the content there, right? You just want to delete everything except for the name you want to put.

Lem   44:28
Yep.

Peter Wolf   44:32
You want to leave the column header right now just clear that. Yeah, right. That's that's going to be the last update that wasn't legit. So now that's correct. You know company, that's correct, right. So then it was other comments.

Lem   44:34
Yep.

Peter Wolf   44:46
Other comments, but then introduction. So then Scroll down. Business relationship introduction. I mean, it seems like we lost. We lost. Yeah, we lost job description.

Lem   44:49
Yeah, it's ready.
Yeah, the job description. It's not here.
Yeah, so it's not here in.
Um, maybe I did. I shouldn't click the like the.
Automatically get the headers or something like sync the headers. So I think we could just I could just import it again and toggle the.

Peter Wolf   45:22
OK, OK.

Lem   45:26
Um.
Because.
Uh, I think yeah, this one.
Then uh.
Then the current sheet and should be like just tab right or custom just tab please.
Uh oh.

Peter Wolf   45:55
No.

Lem   45:56
No, so it should be. Huh.

Peter Wolf   46:00
Yeah, what did you do last time? It worked fine, OK.

Lem   46:04
Yeah, a while ago it was just detect automatically and then append the current sheet. Maybe I Oh yeah, this is the job description. So I think I've a while ago. Let me just check.

Peter Wolf   46:16
So the date of the last update was job description.

Lem   46:20
Yeah.
I think it's, yeah, so it's right. This is the job description on D So I'll just maybe copy it to the right side so that it would be much.
Uh, their comments.
So other comments then just delete this one.
Um.
And then this one should be.
Um.
Uh.
Contact category so here.

Peter Wolf Jr   47:05
OK.

Lem   47:05
Conta category.
Then.
Yeah, the job description should be.
Should be.
Here.
Oh, oops.
Sure. Yeah. OK. So just double check. OK, it's good.

Peter Wolf   47:33
Yep.

Lem   47:34
And then so company uh, it should be.
Here the knee.
Last name.
Should be here.
Then first name.
OK.
Yep, I think it's it's good now. Just delete this row at the top.

Peter Wolf   48:14
And then we're we're getting rid of the industry, right? We're getting rid of the column industry.

Lem   48:17
Yeah, the industry also literal and then this one should be removed.

Peter Wolf Jr   48:22
OK.

Lem   48:26
And then job description introduction. Yeah, yeah, so yeah, for this one we move the columns. I need to like remap the.
Uh, remap the.
Here on the search one, so in the contact card sheets.
And then?
Uh, so uh.
All the relevant information about.

Peter Wolf   49:00
Set an alarm for 10:30.

Lem   49:05
Sure.
The counter sample roles.
Job title industry.
And then so here.
Um.
Yeah, because we changed the so I need to like uh change also the input data. So we have the industry. I need to delete this one.
Then change the this one to.
Job description.
Then I'll just copy the.
Description here.
OK, and then remap it here.
Oh.
Description introduction. Yep, it's already gone. OK, company.
Job description.
Introduction.
Distance relationships.
Personal.
HI Personal appearance.
Other comments.
Contact category.
Source. It's only on M, so OK.
Yep, I think this should work. So we could now we let's test out the finding of data.
So save and yeah, so um.
For example, what do you let's test it out? Do you want to test it out on like the job description or?

Peter Wolf   51:28
Yeah. Tell me everybody that's in the, in the, in, in the in marketing team, let's say.

Lem   51:32
Um.
Alright, so.
Meet everyone on the marketing team.
Just a marketing team, right? Can you tell me?

Peter Wolf   51:46
Yeah, just see what it says with that.

Lem   51:56
Nice.
Marketing team. So yeah, it only found one. Not sure. Let me just check.

Peter Wolf   52:20
Interesting because when I go to job description and I just do a search for marketing, it was her. Did her word, did it say marketing team in it? Like did her particular file say marketing team or something?

Lem   52:28
Uh.
Yeah, it actually, um.
Let me just check Director of Sales and Marketing. So this is Maggie Massar.

Peter Wolf   52:46
Yeah, and she's legit. But there's, uh, there's 25 more. If you just use the word marketing, there's 25 more people in there.

Lem   52:47
Maggie.
Yeah, uh.
Yeah, so on our first filter, it actually got the 26 people. It basically it filtered out the job description correctly. So as you can see here on.

Peter Wolf   53:03
OK.
OK, good. So 26, that seems right, right. That's in alignment. So then what was the second filter that it?

Lem   53:12
Yeah, so yeah, so the one that I think it's on ChatGPT as you can see the result because we fed it the query we said here like the query is.
Uh, like these are all the details and then.
Uh.
It is update.
Let me just check.
Oh right, I didn't. I didn't change here, edited here yet. So let let me just fix this one because we have also like the role here, so this should be the job.
Description.
So I think that's why it got confused and.

Peter Wolf   54:03
Right now we don't have industry anymore, right?

Lem   54:07
Yeah, so this should be the introduction.
Yeah, it moved. It moved all the.

Peter Wolf   54:14
Oh.

Lem   54:15
Yeah, so it actually like different categories because we moved the columns. So the mappings here also moved as you can see on the like first name, last name, company.

Peter Wolf   54:26
When we move the columns of what the spreadsheet?

Lem   54:28
Yeah, the spreadsheet when we move the columns here, so it would actually affect the mappings on the automations.

Peter Wolf   54:33
Yeah.
So it recognized it knew, it read the spreadsheet and recognized that the columns we I don't understand we or it we added extra columns and it kept them in the same place and so therefore the title and the the column and the text didn't match.

Lem   54:43
Uh, no, no, not really. Uh.
Yeah, that's right. It didn't match.

Peter Wolf   54:52
I'm just trying to understand. I'm raising this up so that Peter, Brian and Nick or whatever understand what just happened.

Lem   54:57
Yeah, yeah. So basically it didn't match the the like the company here a while ago like the the role was the job description and then we have the industry as introduction. So it it.

Peter Wolf   55:09
Yeah.
Right.

Lem   55:13
Confused ChatGPT, but the first filter actually works fine because as you can see, we didn't move the job description, so it was OK, OK, yeah.

Peter Wolf   55:20
That's not what I'm asking. That's not what I'm asking. When I'm asking what what happened that it it automatically realigned. It was like we added a new spreadsheet. It automatically realigned the the columns, but it didn't. It didn't change the.
The inputs to those columns, like you said before you had there, not job description, we had industry, right? But job description pushed down so that it was with industry instead of job description.

Lem   55:36
Oh.
Yep.
Oh, Oh yeah, yeah, that's right. Yeah, it it automatically edited, like pushed down the columns here. That's why the the mappings here were different. Yeah, that's right. That's right. Yep.

Peter Wolf   55:57
So when you when you have a spreadsheet input or database of information and then you're passing that to ChatGPT, ChatGPT is looking at the database file and it's automatically making its own interpretation there. Cause I don't understand how the how this map because isn't this the map?

Lem   56:12
Um.

Peter Wolf   56:17
That you were feeding or the map that you have set up.

Lem   56:20
Yeah, this is the mapping. Basically the other one here is just for the query. So this is custom query. So this is actually not feeding all of the data, it's just for example we give it the company so it would just.
Up here here the company, but all of the here, all of the variables here would be empty and then after that one it will find like the bundles, right? This one like the data and then it will feed to the aggregator. So we need to map the right columns here. Yeah, the right column for that first.
Name the first name, last name, last name so that ChatGPT would have context on where to find the like.

Peter Wolf   57:02
Yeah, I understand that it has to have it. It it seemed to me, and maybe I was looking away when you were doing it, but it seemed to me that it made changes in that map right there without us doing anything. Did I miss something? Did you make changes?

Lem   57:16
The changes only were here on the columns because we changed the like the columns right? So the one that actually changed is from the Google sheet maps mapping the Google sheet variables. So it changed from the job description here. So it was a while ago it was like a role or something then the for the.
It was industry. So that's why a while ago the G here is introduction and then it was on the industry. So the one that changed actually was here on the Google Sheets side, if that makes sense.
Um, yeah, so.

Peter Wolf   57:52
Yeah, OK. All right. I'll raise this up to you guys and say, guys, if you don't understand this, you need to work with Lem to and I don't say, I would say right now, like you should come up with two additional fields that you think should be added to this to test it and say how do I add those two fields? What would you have to do? Because if I come to you and say.
Hey, let's expand this. This is stuff you should be able to do. That's going to show you understand how to use it. It's going to show you can modify it. Like right now we're just taking this stuff that Lem is building and then putting it over and saying you understand it. But if you don't understand how to manipulate it, you're really not building and understanding.

Peter Wolf Jr   58:15
Right.

Lem   58:21
Yeah, that's right.

Peter Wolf   58:28
Right. You got to understand that level.

Peter Wolf Jr   58:29
I mean, this is pretty straightforward because we've used multiple Google sheet make models, so this is something we've had to do previously.

Bryan Wolf   58:29
This is pretty straightforward.

Peter Wolf   58:35
If you guys are telling me you're comfortable with it, it's. I'm just saying it's to you.

Lem   58:35
Yeah.

Bryan Wolf   58:37
Previously.
It's just making sure that it's mapping, right? Because we have to manually map it anywhere when.

Peter Wolf Jr   58:40
It's just making sure that it's mapping, right? Because we have to manually go in and map it anyway when Lem sends stuff so it adds more depth of understanding. Because when Lem sends these over to us, we have to remap everything anyway when we install the process flow into our mix.

Lem   58:43
Yeah, mapping correctly.

Bryan Wolf   58:55
Of the.

Peter Wolf Jr   58:58
Um.

Peter Wolf   58:59
OK, you say if that's the case, then great. I'm not, I'm not at that detail level, right? I'm just raising up to you. That's the stuff you definitely need to understand, right? OK, so then let's go back now if we have this reorganized and make the same query.

Lem   59:07
Yeah, so.
Yeah, so um.
Uh, let me just check. I'll see here. I need this updated. I'm not sure.
It is updated. It's actually feeding. All right, the other one. OK, so yeah, let's just click save and then let's test it up again. So for example, I'll just copy the.
On this one.
Then you chat then can tell me everyone the marketing team. I have no other information.
So what it should do is it should find the job description. Need at least first names if you can write.
Um.
Oh, at least first or last time. Uh, if you can probably name or any of the details, but.

Peter Wolf   1:00:09
Interesting.

Lem   1:00:16
If you have any text, I just uh, I need.
To check all the my contacts.
Yeah, I think, uh, it's because on the prompt I said, uh, but uh, no, I don't have more information.

Peter Wolf   1:00:53
Interesting.

Lem   1:00:54
So it's actually getting confused now. Uh.
So anyway, I won't be able to perform a targeted search. I'm not sure if it. Yeah, so it didn't push through here, didn't error it out. Also, yeah.

Peter Wolf   1:01:06
Yeah, and the first time you did find all of them, right? So what happened now?

Lem   1:01:12
Um.
Yes, we didn't push through.
I'm not sure why is uh like.
Uh.
Can you tell me everyone in the marketing team?
I need to check our contact card. I don't have other information, but that one.
Yeah, so it should push through the yeah so now it push through. I think this is because like the prompt is also like very long so GPT is getting confused and then because I also have like a guard.
Guidelines here on the general instructions where analyze each incoming. Then always ask clarifying questions if the user instruction is ambiguous.

Peter Wolf   1:02:18
Yeah, can you do me a favor? Can you cut this instruction out from this assistant and send it to me? Copy the entire instruction, the entire instruction.

Lem   1:02:25
This one.
OK.
Um.

Peter Wolf   1:02:31
Not just that top art, but you have that whole instruction you had, no? Yeah.

Lem   1:02:35
Oh, hold this one. OK, the the prom. OK.

Peter Wolf   1:02:39
Yeah.

Lem   1:02:39
Um, I'll e-mail it or just here in the chat.

Peter Wolf   1:02:42
You can send those either way, doesn't matter. You can put it into the chat.

Lem   1:02:45
OK, OK. Oh, it's limit exceeded, so I'll just e-mail it to you. Yeah, because I did.

Peter Wolf Jr   1:02:50
Can you CC us on that e-mail as well though?

Peter Wolf   1:02:51
OK.

Lem   1:02:55
This is quite low. OK, no problem.
Yeah, because this is quite long, I think. Um.
Uh uh.
From.
I.

Peter Wolf   1:03:16
You need to include me there too.

Lem   1:03:19
Oh, this is, yeah.

Peter Wolf   1:03:21
It's Peter. That's my son and Brian.

Lem   1:03:23
OK.
And then, yeah, so this is the whole prompt. Uh.
And then yes, so I haven't edited yet the other ones because we have here like the task for inputting data. So I just edited the one for the finding information this task tree.

Peter Wolf   1:03:47
OK.

Lem   1:03:49
Yeah, so now I found one. Yeah, it's just found one contact. That's odd.

Peter Wolf   1:03:54
Still only gave the one.

Lem   1:03:57
Yeah, but if we, yeah, if we check here, it actually gotten all of them.

Peter Wolf   1:04:04
I know. So what's happening where it's losing them?

Lem   1:04:06
Yeah, it's here actually on ChatGPT. I think I need to update the prompt that whenever the query ask for multiple like multiple person.

Peter Wolf   1:04:21
It should give them when I see your thing and it only grabs one out of them or something.

Lem   1:04:25
Yeah, that's right. So it actually, it's like quite specific. So it's just grabbing like Maggie Mazar, but.

Peter Wolf   1:04:34
Is she the first one on the list of 26 or something?

Lem   1:04:38
Um, yeah, she's actually, uh, the first one. And then.

Peter Wolf   1:04:39
Yep.

Lem   1:04:48
Oh, it's on the messages first, so I'm checking here the the input.
Uh.
Details updated.
Um.
First name Aghi Mazar.
I mean.
Um, what's this?
Mobile e-mail.
Um.
That's uh.
Oh, the original query, right?
So it should be in the message input.
Uh.
Um.
Original query. Yeah, it should have the original query. Yeah, so I think the main thing here it's it didn't pass out the original query, so I think I need to.

Peter Wolf   1:07:08
So what is it doing? It's getting it's getting 26 names and it doesn't know what the query is.

Lem   1:07:10
Edit the prompt.

Peter Wolf   1:07:25
Yeah.

Lem   1:07:26
So that a ChatGPT would have like context on the query right? And then but yeah as you can see here I have it on as a variable dynamic variable so this one original query so this is this should this is here.
So it's not feeding the original query to ChatGPT, so that would be here. The the main troubleshooting for that would be here on the prompt. So yeah, here this one.

Peter Wolf   1:07:48
Yes.

Lem   1:07:59
On the find contact. Uh, let me just.
Yeah, this one. So original query. So it didn't. It didn't include the original query on the field.
Yeah. So that's the main issue, I think.
I think I would add. I just had some rules here that I always include.
This include the original.
Create of the user.
So that's the because yeah we we could that's how we how I troubleshoot it. Also like checking the input from ChatGPT why why it outputted here. So as you can see here as I've said a while ago.
It actually didn't fed the original query, so we need to update also the prompt. So let me just check it again, test it up again.
Can you tell me all the people in the marketing team?
It's right.
Uh.
I just have that information.
So it should um.
Yeah, so now it OK, let's check.
Huh. So now.
I'm sorry, but your input message seems to be empty.
That's odd.
Um, yeah.
Uh.
It's not giving the original query. Uh.
The.
It's a problem.
Yeah, the message input is empty.
Yeah.
This message.

Peter Wolf   1:10:51
OK.

Lem   1:10:53
OK.
Yeah.
Extra understand there.
Oh, I see. I think it's because it's getting confused on.
Query.
Your final output should always the original query, so.
Wow.
OK.
Then.
Um.
What happened?
Yes, so now it filtered out wrong I think.
H.
This is relationship. Yeah, this is also I think as you can see because my my question is like kind of vague, so sometimes.
ChatGPT would uh.
Like, uh uh, what's this?
Analyze it in a different way. For example, it actually filtered out in the.
Here on the H column where this one so business relationships because like this is like kind of vague. So I think yeah because we need to be like precise also on asking like Chachi PT on what.
We want, so I think for example this one, can you tell me all the people in the marketing that has the job description on marketing team so that it would have a context because.
Yeah, yeah. As you can see it, it was confused also on filtering out the the, yeah.

Peter Wolf   1:14:22
OK, so let's try that. Let's try to be more specific. I think we need to work on the prompt for sure. And because I'm I'm not going to want it asking me, you know, 20 times. I don't tell me more people's names when I'm asking for the names, but let's try to put put it in there and just tell me.

Lem   1:14:26
Yeah.
Yep.
Yep, that's right.

Peter Wolf   1:14:37
Tell me everyone. Tell me everyone with marketing in their job description.

Lem   1:14:42
OK.
I think there child description. Oh, let me just check also if it also sent the because that's the. Yeah, so now we send the message input here, but yeah, let's check.
Try it again on uh here. Um, tell me everyone that the marketing in their job description.
K.
So it's, uh, open the task to find data contact share, so this should be.
Mm.
Yeah, I think this is much better because is thinking. So I think it would include all of the persons which is like 25. We have 25 there, right? Not compared a while ago, which is it just decided.
Uh, automatically.

Peter Wolf   1:15:58
Seems like it's taken an awful long time to look through 26 people contacts to get that information.

Lem   1:15:59
Yep.
OK.
Yeah, so uh.
It's also.
Get ready. It should already be good here.
Yes, so it actually inputted the 22, only 22. Not sure why only 22.

Peter Wolf   1:16:28
So let me see. It was probably because it has something very specific and I said what's marketing in the description and it'll turn out that it's marketing. Let me see. So I did a search.

Lem   1:16:37
Yeah, so.

Peter Wolf   1:16:41
Or.

Lem   1:16:42
Yeah, but it actually.
Yeah, it only we got like 26 bundles, but it because here it's just searching marketing, right? And then I think others has.
Uh.
Revenue marketing. Then the query here is.
Um.
Yeah, tell me everyone that have marketing in their job description. So it should, yeah, it should push out all of them, I should.

Peter Wolf   1:17:19
But that why didn't it? Why did it only give us 22 of the 26?

Lem   1:17:22
Oh.
Yeah, that's right. So.
So.
Yeah, it only gave it 22 actually. Not sure why, but this is like maybe we need to like upgrade the GPT like the model because we need some like this analyzation on the.
Like the context or something? Uh.

Peter Wolf   1:17:47
I thought 4O was the updated model.

Lem   1:17:51
No, we actually have like 444.1, so that's the much.
Much more.
Of course much more like token intensive. The price is much higher, but this is like the most intelligent. They actually have 4.5 but they I think it was it bleached out and they deprecated it so.
Now it it's just a 4.1 the most. So let let me just try also again this one because yeah, it just fed fed out the 22 here. So as you can see we have the 22 here with all their details.
And then?
Yeah, so let's check again.
Uh.
It should be 26.
I need other people on the marketing team in chat.
Oh.
Other information for now.
Yeah, I think let me just remove my guardrails here. It's because I have some general instructions here. It's actually.
OK, that should be it.
Yeah, it's much better. So it's not asking like double.
Yeah, so.

Peter Wolf   1:20:03
It does say that we it does say that we can like looking at the GPTS, the pricing 4.1 is smartest model for complex tasks is $2.00 per million tokens and $8 per million tokens out. But our output would be is going to be.

Lem   1:20:21
Short.

Peter Wolf   1:20:22
Smaller than input. No, our output or input here may not be much different, but we've already narrowed it down from the full database to this selection. But 4.1, it says affordable model balancing speed and intelligence. That's only $0.40 per million tokens.

Lem   1:20:31
Yep, that's right.

Peter Wolf   1:20:39
And 4.1 nano is the fastest, most cost effective model for low latency tasks, meaning it doesn't need quick response, but we'll have to see how fast that response is. It should have the same knowledge as the 4.1, but 4.1 nano just runs.
Lower and want to see what that latency is, right? Because that's only $0.10 per million tokens.

Lem   1:21:05
Yeah, yeah. So I yeah, I actually upgraded to 4.1, but it still can't get it. I'm not sure why.

Peter Wolf   1:21:19
So we can't see where it filtered, which ones it filtered out.
And why it filtered out? This is what they tell you in the in the old training about AI is the auditability, accountability. How do you, how do you show whether it's doing the right thing and how can you trace it? And right now, clearly we can't trace it.

Lem   1:21:26
Other.
Yeah.

Peter Wolf   1:21:40
And that's what we need to be able to do is understand why it's filtering some out, because it's not going to be helpful to me if I go call on the database and ask for information and it gives me incomplete information.

Lem   1:21:52
Yeah, Yep, that's right. Um.

Peter Wolf   1:21:56
And unfortunately, I'm going to have to jump on another call in 10 minutes.

Lem   1:22:00
OK.

Peter Wolf   1:22:01
Clearly I need to spend some time with you because I think this iteration stuff is gonna be critical here. Then just like I said the other day, I feel like we have a bunch of models that are good models, but but they are.

Lem   1:22:08
OK.

Peter Wolf   1:22:16
They're they're they're incomplete, right. We need to take them the extra mile, which is the real nuance stuff. And that's the stuff that I really need to engage with you on at a at a very granular level, like working through this like right now this would not work. We need to, we need to work on the prompt and on the selection criteria and how it's.

Lem   1:22:19
Yep.
Yep, that's right.

Peter Wolf   1:22:36
Working and tell it not to say or ask me for names. It should know automatically. If I don't give it a name, I'm asking it to go find the names. Don't ask me the names, right? Those are things we're gonna have to put into that prompt so that it doesn't do that. But we need to figure out why it's filtering out some of these that are very explicit. This one's straightforward. This is a straight.

Lem   1:22:45
Yep, that's right.

Peter Wolf   1:22:56
Forward as we're going to get is I'm actually asking for the word. I could be filtering in spreadsheet right now getting this result and and for somehow on AI I can't get the result. That's problematic, right?

Lem   1:22:58
Yes.
Yep, that's right. Yep. Um.
Oh, I think, yeah, I think I see the the main reason here because as you can see on the other comments, there's also like job title, so it's interfering with the analysis of ChatGPT.
So that's why, uh, I think.

Peter Wolf   1:23:32
Well, hold on, what job? Where to get job title from? Because we took job title out.

Lem   1:23:34
No, for example this one Jamie Hufnagle. So on the other comments he actually has like job title here. So I think for yeah, so let me just check.

Peter Wolf   1:23:44
Oh, and the other comments. Yeah, OK.

Lem   1:23:50
So I think this one.

Peter Wolf   1:23:50
We only told it. We told it to search only for the description that it had in the in the job description. We didn't tell it to not to look at other places and.

Lem   1:23:57
Yeah.
Uh, no. Uh. But basically what's happening here is whenever it's searched the like the.
The contact and then we we actually is feed the we we're actually feeding all of the data of the contact to ChatGPT because we need.

Peter Wolf   1:24:19
Right. Because then we wanted to be able to do a further filter, like we said they had brown hair and worked in the marketing department. Then it would say, OK, go find everybody with brown hair and then say look for if they're in the marketing department, right?

Lem   1:24:21
Yeah, that's right. So.
Yeah, so I I think, uh.
Mhm.
Yeah, I think we need to clean up also the other other comments section because yeah, I'm I'm actually, yeah, I'm checking the others here because as you can see for example this one like for Maggie Massar, the other comments has it's very long.

Peter Wolf   1:24:46
Yeah.

Lem   1:24:50
So it's up to here. It's actually up to here. So as you can see like it's, yeah, it also has like job titles. So I think the other ones have like a different job title. That's why it it it didn't.

Peter Wolf   1:24:53
Yeah.

Lem   1:25:05
Yeah, so I think that's interfering like this one.

Peter Wolf   1:25:06
But we didn't say anything. So did it filter them out or filter them in? Because we didn't say anything about job title. We just said that their job description says marketing has marketing in it.

Lem   1:25:11
No.
Yeah, that's right. Oh, the query, right. Yeah, no, the query was, can you tell me all the people in the marketing team, I think or yeah, so.

Peter Wolf   1:25:27
Well, that was the original one. We changed the query because it that was giving us trouble, right?

Lem   1:25:31
Um.

Peter Wolf   1:25:33
It changed the query to be much more specific. Give me everyone with with marketing and their job description. That's OK. I don't think that was the last one we ran.

Lem   1:25:36
Uh.

Bryan Wolf   1:25:37
I think we did.

Lem   1:25:43
Yeah, this was the last one. So let me just, yeah, let's test it again. If, yeah, I think the other comments is like interfering, but yeah, can you?

Peter Wolf   1:25:56
So then put in here just tell me everyone with marketing in their job description.

Lem   1:26:00
Everyone.
Marketing in their job description.
Yeah, I think this is much, yeah, much.
Specific so.
So let me just check here.
Yeah, so now it yeah, it just still given 23. Yeah, that's odd. So it we have 26 bundles, but it didn't add the other three.
Not sure why. So my my yeah, my yeah, I just added the 23. My hunch here is it's because of the other comments because.
It's also pretty long, right? Because of the like the other, it's like 26 persons and then we have like, yeah.

Peter Wolf   1:27:14
Yeah.

Lem   1:27:20
Um.
Yep. Um.

Peter Wolf   1:27:31
and and we're getting results that don't show that.

Lem   1:27:31
Um.
I think I I could put the query first because I put it on the last actually. So I think this should be. Yeah, it's much better if I could add this one so it ChatGPT would like the AI would read the message input first.
And before the database. So I think that would help also with the context. But yeah, basically this is just I think just prompt on the prompt engineering side. When your estimation message input, you can find the database from the list below for.
Uh.
I'm sorry, that's the first name. Um.
Show description.
Personal relationships.
Business relationships.
Appearance other comments.
So.
Message input.
Let's see this add more context there.
OK, let's check it again. Um.
Yeah.
OK.
23 Yeah. So it's just, yeah, it's not adding the three persons there. I'm not sure why.

Peter Wolf   1:30:29
I mean, shouldn't it be showing us what the filter was that it took for the that that pulled them out? Shouldn't we be able to see why it excluded them?

Lem   1:30:37
The.
Not really. Basically this is just the filter that this ChatGPT is analyzing it itself. But yeah the the filter first was correct like this was the like the filter as you can see here it's on.
Job description was four I think. Let me just check F so this is F so on F.
This 1F is it's marketing so it's filtering it out correctly. So as you can see we have 26 bundles. So now we are having the problem here on ChatGPT side because we have the like the final filter right for ChatGPT with the message input.
So the message input also as you can see here, yeah this one. So can you tell me everyone with the marketing in their job description? So and then the database is this one. So it's pulling it's coming from the Google sheet that is aggregated. I think it's just getting confused.
Use because of this particular other comments this one. So in the other comments section others other contacts has like a very long with the like job titles like this one so.
Also um.
Yeah, like this one that's also like another job title and we can't. Yeah. So basically I think it's like the AI and then it's actually like analyzing the whole database, right? Like for this one, so.
I'm just not sure if the other ones have like different job title, that's why it didn't include them.
Sample.
It says hist.
Yeah, because the jobs descriptions are actually correct.
Marketing.
OK.
Someone else has marketing.

Peter Wolf   1:33:21
Guys, I gotta jump to this other call, unfortunately. Yeah.

Lem   1:33:24
OK, OK, Peter, yeah, I'll I'll tweak this one and yeah, the prompt for like I think I need to optimize the prompt here also with this ChatGPT here to.

Bryan Wolf   1:33:25
OK.

Peter Wolf   1:33:38
And you know what, Len? You and I, I might need to get together with you earlier. The the time slot timing is going to be a challenge here for me. So let me let me reach out to you and I look at tomorrow. Tomorrow's Thursday.

Lem   1:33:46
OK.

Bryan Wolf   1:33:47
In the morning.

Lem   1:33:48
Uh.

Peter Wolf   1:33:54
Uh.
Yeah, I got a bunch of conflicting.
Thanks. Let me let me message you if you if if I had the opportunity, if I mean if I need to meet earlier, would you be able to get together at at even say 7:00 AM East Coast time?

Lem   1:34:11
Yeah. OK. That's not sure if like 2 hours earlier, right? Is that correct? OK, Yeah. OK.

Peter Wolf   1:34:16
Two hours earlier, yeah.

Bryan Wolf   1:34:17
Yeah, try it really.

Peter Wolf   1:34:20
Let me, I'll send you a message. OK, I got to jump right now guys. I I'm not sure with you or you want to keep moving forward to what you were already working with Lam and I apologize we didn't have time to catch up on that. We'll just have to connect later today to discuss where the other.

Lem   1:34:21
I'll get OK.
OK, Peter.

Bryan Wolf   1:34:30
No, you're good. You're good.
I'm just gonna switch over to working on the dashboard, but sorry about.

Peter Wolf   1:34:35
The other things are OK.

Lem   1:34:38
OK, Peter, got it. Oh, OK.

Bryan Wolf   1:34:40
Can you hear me?

Peter Wolf   1:34:41
Ryan, Peter.

Bryan Wolf   1:34:42
Yeah, can you hear me? Can you hear me?

Peter Wolf   1:34:43
No, I can't hear you. I can hear you through my door, but I can't hear you. You're on mute, Peter.
Brian, I don't hear you.

Bryan Wolf   1:34:53
Can you hear me now?

Peter Wolf   1:34:54
No, it's totally muffled. I gotta go.

Lem   1:34:55
Sorry.

Bryan Wolf   1:34:57
Bye.

Lem   1:35:10
OK. Bye, guys. Hi, Peter. You there? I think you're on mute.

Peter Wolf stopped transcription


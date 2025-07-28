# Process Automation Workshop (18)

**Original File:** Process Automation Workshop (18).docx
**Extracted Date:** 2025-07-01 (Tuesday)
**Converted:** 2025-07-28 11:40:38

---

Transcript

July 1, 2025, 12:59PM

Nicholas Westburg   0:15
Morning.

Peter Wolf Jr   0:17
Gentlemen, good morning.

Peter Wolf   0:17
Hey.

Nicholas Westburg   0:18
Oh.

Peter Wolf Jr   0:23
Big Pete, did you hear that?

Peter Wolf   0:23
Miss adela.

Peter Wolf Jr   0:24
They're no longer picking trash up.

Peter Wolf   0:27
Yeah, I know.
I brought my trash cans in just in a while ago.

Peter Wolf Jr   0:30
They they're protesting out in front at the.

Lem   0:33
Hi, guys.

Peter Wolf   0:35
OK.

Peter Wolf Jr   0:35
The Public Library right next to the house.

Nicholas Westburg   0:35
Morning, Glen.

Lem   0:37
Morning.

Peter Wolf   0:39
All right.
Alright, so let's let's look at that most recent flow and then we can.
We can discuss a couple things.
Appreciate all you guys being on.

Lem   0:51
OK.
The company flow right, the new one.
OK.
Let me just.
Share my screen.
OK.
Yeah. So.
Now this is the let me just.
The complete flow.
So yeah, first the trigger and then it will search the title from the.
I mean the company from the Google sheet and then it will get the prompt, then feed the prompt to perplexity and then.
This one is just just researching for the main website of the company because I'm using that.

Peter Wolf   1:38
OK.

Lem   1:39
Yeah, we'll we will be using that one for the like the photo logo.
And then.

Peter Wolf   1:44
Yeah, no.
Also, I like that we should bring that back along with the other information populated in, so that should be included the main website. That's a good one to to put into the output.

Lem   1:51
Yep.
To the.

Peter Wolf   1:56
Right. So when we create the Google Doc that has the content, I would say put that website in there so someone can be looking at the report and just click on it, go to their main website as well.

Lem   2:00
OK.
OK.
Yeah, but the.

Peter Wolf   2:08
I'd also bring that back and put it into the Google sheet.

Lem   2:14
Yeah.
The website.

Peter Wolf   2:18
Yeah.
Yeah.

Lem   2:19
Yep. Yeah, we could do that.
Just set the formatting of this one is actually.
Different, it's actually just outputting the website after this one.
Https because there's like a free website that can get the logo. As you can see here on the.
Format content so when you put the like the website.
On there, like after the WW dot.
So it just extracts the logo for free.
So that's, that's the one that I.

Peter Wolf   2:56
That's pretty good.
I mean, look, this is the kind of stuff when you just throw those out there, Lim.

Lem   2:58
Yeah.

Peter Wolf   3:00
To me this is like little gold, right?
This is awesome, OK.

Lem   3:03
Yep.

Peter Wolf   3:04
There's a site. Instead of trying to figure out how you go and find it was actually a site that does this where you just go out, put their website in and pull their logo. That's great stuff.

Lem   3:09
Yep.
Uh.
Yeah.
The thing only is. Yeah, this one. So logo.clearbit.com. So they. And then you would put like the this one microsoft.com so.

Peter Wolf   3:27
Yep.

Lem   3:28
And then yeah, it will just input it there. And then Yep, we could add this one to the spreadsheet.
The thing only here is it's actually like grabbing some like the like a little logo like so the by depending on the website so it's outputting like different.
Format, so sometimes it's a very small, so it's kind of blurred.
So for others it's good. But yeah. And then yeah, it will.

Peter Wolf   3:51
OK.
OK.
That's good to know.

Lem   3:55
Yeah. After that it will format the content also to HTML so that we could create it in the Google Docs as HTML also.
So this supports HTML format and then this will change the.
This will get a share link with access of editor.
So for for so that we can send the link and then other people can also edit it then this will download the document next and then feed it to the Gmail.
So this has the like like a notification or we can e-mail to a particular list. We can just add the recipients here and then.
Next is it will set a UID and then feed all that data to Google Sheets.
So what we will have now is something like this.
So we could our input here would only be like the company name and also like the check mark and then all of this will be automatically processed.

Peter Wolf   4:51
Yeah.
Yeah.

Lem   4:55
So the.

Peter Wolf   4:56
Can you do me a favor then? Simple thing.

Lem   4:58
End.

Peter Wolf   4:58
Can you put column C as column?
B.

Lem   5:02
This one.
Yep, no problem.

Peter Wolf   5:03
Yeah, yeah. Just move that over between C&D so that the check mark exactly. So all we do is enter the first one, hit the check mark and it fills in the rest, right.

Lem   5:04
I'll just adjust it on the.
Yep.
Yep.
And this one. Yeah, that's right, yeah.

Peter Wolf   5:13
And then here's where I would like to add the the company website in here website URL.

Lem   5:17
On on the C.

Peter Wolf   5:20
That's the Google doc.
No, no. Add another column after the Google Doc or before it. I don't care which and then put you know company website.

Lem   5:24
OK. Yeah.
Uh.
Yeah.
Yeah, company website. OK, so we could add that one, the company website also.
And then.
Yep. So the yeah.
So our perplexity is actually I've in yesterday we've used like ChatGPT 40, But I've tried it for other companies like a small company so like this one.
So Eastern Silk corporation. It wasn't able to, like search the yeah, but using chat G ChatGPT.

Peter Wolf   5:54
Yeah.
You can find anything.
OK.

Lem   6:01
But perplexity actually is.
Was able to like search their particular details, so that's good and.

Peter Wolf   6:09
Yeah, no, when I plugged in the perplexity, it did a great job.
I thought that's fine. Terrific. I'm glad. Perplexity.

Lem   6:13
Yep.
Yeah. And then yeah, so?
Yeah, the output will be something like this.
So like the overview Microsoft Executive summary with like logo we can put this like smaller I think.

Peter Wolf   6:28
Yeah.

Lem   6:28
Yep. And then overview and then like the citation links also like this one, the revenue and then key product services.
Then lines of business countries operation.

Peter Wolf   6:41
Love it.

Lem   6:42
Currently, yeah, banking.

Peter Wolf   6:42
Love it, that's great.
This is like a quick, you know, quick sales report that you'd pop it, you'd pop up right before you get on the call when you're seeing opportunity. This is this is great stuff.

Lem   6:44
And then.
Yep.
Yep.
Yep. Then this one is your most recent news articles.
And then, yeah, someday I also tried it to Bridgewater.
So yeah, this is also.
Yeah. So yeah, I think their logo here is.
Like not. Yeah, like Scott, but for other ones, it actually like for Accenture.
So it actually got the logo right.
But yeah, this is this is just free because this is just free.
So it's basically.

Peter Wolf   7:29
That's fine.
I don't need that to be perfect, right?

Lem   7:31
Yeah, yeah.

Peter Wolf   7:31
It's internal reporting. It's fine.

Lem   7:33
Yeah, and yeah, basically this is the. Yeah. Like a four page 123 to four page. Yep.

Peter Wolf   7:36
I think that's that's awesome.
Here's what I'd like to do is is now to expand this, and I'm probably having to be a second flow that would come before this, this one for sure by itself is a great flow, right?

Lem   7:46
OK.

Peter Wolf   7:49
I plug in the name, I hit the button and it goes and gets me the report and it it populates it in here you said it also sends an e-mail.

Lem   7:51
Yep.
Yep.
Yeah, it will send an e-mail.
So something like this so to it was it can send to like recipients. We could just add the recipient here.
So a while ago I've also added one of my emails.
So it also sent it. And yeah, then the test.

Peter Wolf   8:10
Here I tell you what I just started something. What about?
What about?
What about this? Go back to the spreadsheet.

Lem   8:17
OK.

Peter Wolf   8:19
Let's add in an e-mail address after.
A.
Put an e-mail address in there, so whoever's requesting the whoever's requesting you put it afterwards to the right, yeah.

Lem   8:26
OK.
Right. Yeah. Here like.

Peter Wolf   8:34
Whoever's requesting the e-mail, whoever's requesting report could put their e-mail there again. If we could send to whoever we want else in the make.
But if someone's requesting it right here, they're plugging it in.
They wanna get it.
They can put their e-mail address in here.

Lem   8:47
Yeah, yeah, that, that.
Yeah, we could add this one also. So Yep.

Peter Wolf   8:51
OK.

Lem   8:52
Or it's like a supplemental, right?
So we would also have like.

Peter Wolf   8:55
Yeah. Supplemental, supplemental. Yep.

Lem   8:58
OK. We will have like.
OK.
Yeah, because I think we could do that. There's.
We'll add here like.
Yeah, just add the recipient and then yeah, OK.
And can do that one.
So it's e-mail and then also company website.

Peter Wolf   9:24
OK.
Right, so here's here's the next thing this blow I I love it.

Lem   9:28
Yeah.

Peter Wolf   9:31
It's great.
We were talking about and I was actually, I did this before I had a meeting when I was in Amsterdam.

Lem   9:32
OK.

Peter Wolf   9:38
I was looking for companies that were implementing SAP so that I could argue to this client that that there weren't that many companies that were doing it right.
And then I wanted to emphasize who was doing a certain functionality.

Lem   9:49
OK.

Peter Wolf   9:53
And one of the ways I did that was to do AI think it was.
Perplexity.
Research.

Lem   10:07
OK. Yep.

Peter Wolf   10:09
That were looking for certain positions, so I want to make another flow that will do that job posting search and then when it's done, it's gonna come here and it's gonna take that company name. It's gonna plug it in here and it's going to give me the company.

Lem   10:13
Yes.
OK.

Peter Wolf   10:28
Summary and then it's gonna give me the job posting information. So it would be an extra long report or maybe what you would do is you would you would do the job posting.
Get all the job posting information.
Have that as a variable. Then call this flow.

Lem   10:41
Job post OK.

Peter Wolf   10:44
Add the company name in there.
It gets the whole company information, grabs the variable if it exists, right?
Because now you're on to the second flow, which is this flow, if it exists. If the variable exists for the job posting, then it should put the job posting information down below it.
Follow.

Lem   11:04
Not quite. So we will have like another CHEAT SHEET, right? Like another spreadsheet and.

Peter Wolf   11:05
OK.
So here.
No. Well, no, no.
That's not what I want.
What I want is a is a job that runs once per day schedule job that runs once per day and it looks for. It looks for companies that have job openings that meet specific.

Lem   11:21
OK.
OK.

Peter Wolf   11:35
Requirements, right?
So we're gonna define that I want.

Lem   11:37
OK.

Peter Wolf   11:39
It's gonna be.
The SAP Treasury cash management in House banking advanced payment management.

Lem   11:46
OK.

Peter Wolf   11:47
So we'll list several skill sets that we want to search the job boards for, indeed, and wherever else search the job boards for open jobs with those descriptions, and when it finds them, it should grab that information.

Lem   11:55
OK.

Peter Wolf   12:03
Create a little report about what the job posting is, what the company name is job posting.
What information is in that job posting and where's the location of it? And then it should hold that store that information, and then she then called this flow and it should feed into this flow. The company name. Then this flow does its normal process and it wants to.

Lem   12:15
OK.
OK.

Peter Wolf   12:31
Give me that company report coming out.
But then it should say well the Gimme the company report plus the job report.

Lem   12:35
OK.

Peter Wolf   12:40
So put the job report in below the company report.
So if you did the first blow, the job posting report and then made that a variable, then what it called the main company report.

Lem   12:48
OK.
OK.

Peter Wolf   12:55
It could produce the output that we already said it's going to produce. Then it could call the variable and say if this variable exists for the job posting, put it in the bottom of this report.

Lem   13:05
At the bottom of like this particular report, right?

Peter Wolf   13:08
Yes, yes, yes.
So if you if the output for this report the Google Doc report for company, if that output had an additional variable called that said, hey, if there's a variable in the job posting relevant to this, then go grab it and put it in this report.

Lem   13:10
OK.
Oh, OK.

Peter Wolf   13:31
That makes sense.

Lem   13:31
OK.
Yeah. So we will just add like, yeah, we'll add it, I think.
Yeah, add it the document. I think with that variable.
Umm.

Peter Wolf   13:44
Right now you have some HTML that says. Here's the output for the company report.

Lem   13:49
Yeah.

Peter Wolf   13:50
Right at the bottom of that you should add a variable that says hey, if there's actually a report for this company.
That's a job posting report.
Go populate it in.

Lem   14:01
OK.

Peter Wolf   14:03
Right. So in reality, I don't know if you should, if you if you should.

Lem   14:03
Yeah, it will add, yeah.
We could do add it here right at the bottom.

Peter Wolf   14:10
Yeah, exactly, exactly.
I'm trying to think you have this flow and I know you going this way. When you look to your right, but process flow going this way, right? If we have, if we have just again think about these as two discrete reports process flows then then I want to.

Lem   14:22
Yeah.
Look.

Peter Wolf   14:28
Pull together.
So I'm going to have one one process flow that goes out to look for job postings looking specifically for SAP, Treasury, cash management and house banking.

Lem   14:36
Every, yeah, every day.

Peter Wolf   14:40
So this list of, let's say 1015 keywords all SAP right?

Lem   14:46
OK.

Peter Wolf   14:46
Only company that's looking for that role to fill is a good prospect that they're doing projects with that functionality.
Obviously they're not hiring people in that role if they're not intending to implement that functionality or don't need support or don't need, you know, don't right.

Lem   14:59
Yep. Oh, OK. Yeah. So yeah, yeah.

Peter Wolf   15:02
That's what I'm trying to find out, so I'm using this as a trigger of a sales opportunity.

Lem   15:08
Yeah. So it it would be like the other flow will be like let's say scraping like indeed or LinkedIn something. And then if if it filters for example, it will filter out for example SAP, so that particular company is hiring for let's say SAP like manager or somet.

Peter Wolf   15:15
Yes.

Lem   15:27
So it will populate the company name here, right?

Peter Wolf   15:27
Yep.

Lem   15:29
That's that's what you it will automatically.
Trigger this particular scenario. Is that right?

Peter Wolf   15:35
Yeah. So there's already.

Lem   15:36
Yeah.

Peter Wolf   15:37
Let's let's do it this way.
You have a 'cause. It probably makes sense to me to have a different spreadsheet.

Lem   15:38
For example.

Peter Wolf   15:43
Or maybe maybe it makes sense 'cause they have it in here.

Lem   15:43
We could.
Yeah, we could.
Let's see if it's coming from the other flow.
We could add same.
The trigger would still be here and I'll just add there that this will be check marked when whenever for example Microsoft.

Peter Wolf   15:54
Yeah.
Is populated by the other flow, then it just gets check marked.

Lem   16:02
Yeah. Yeah, that's right.
Yeah, it's also gets check marked so that the other flow would be triggered and then it will add.
The.
Yeah. So it would.

Peter Wolf   16:13
Maybe maybe the other.
Maybe what we do is?

Lem   16:17
And.

Peter Wolf   16:19
Maybe what we do is, yeah, that process flow is running, right?
We'll call it the job posting flow.

Lem   16:27
Yeah, like, yeah.

Peter Wolf   16:28
The job posting flow is triggered automatically daily once per day, goes out and looks at all the sites.

Lem   16:32
OK.
OK.

Peter Wolf   16:36
If it finds one, it comes back here, populates the company name here.

Lem   16:41
Yep, Yep, that's right.

Peter Wolf   16:42
It it then populates the start research and then we should have a new column.

Lem   16:45
This one? Yep.

Peter Wolf   16:49
That would be a formatted document just for the job posting, because that way you could populate it somewhere you create a Google doc for it and then you could later roll and grab it back, right?
Because I feel like, and maybe you tell me you don't need it, can you?
I guess you could just hold that in a variable like I talked about earlier. The job posting report.

Lem   17:04
Uh.
The.

Peter Wolf   17:09
You create a job posting report that's just about the job.
Posting what the company name is location.
The description of the job the you know details.
And then hold that as a variable.

Lem   17:22
Yep.

Peter Wolf   17:22
Then come here.
Populate the company name.
Start the research it goes and does all the research, comes back, creates the report.
This is what I'm thinking is there's nothing here that then tells me that it has a job report in it.

Lem   17:37
Yep. So yeah, what we can actually do is like have a route like another route here.

Peter Wolf   17:38
Right.

Lem   17:45
For for example.
Because.
Yeah, like another route here. That search if there's like, it's from a the job post. Basically it would also run this one with like the certain job post.
Like a job post report.

Peter Wolf   18:04
Yeah, but it's a job.
But the job post has got to be a separate job because it's triggered automatically daily, right?
It's a scheduled job and so the job post when it finds an answer then could feed in and call this right?

Lem   18:10
Yeah.

Peter Wolf   18:17
Because it's essentially calling the trigger by populating the spreadsheet.

Lem   18:21
Yep, yeah. Basically we couldn't.
We could add also another like a column here with a job post document.

Peter Wolf   18:26
Yeah.
Exactly. Exactly.

Lem   18:28
Is that what you?
Yeah, OK. Like for example, yeah.

Peter Wolf   18:30
And then.

Lem   18:33
Like this is.

Peter Wolf   18:33
And then if it then I would say still I wanted to be a comprehensive like the first one would be comprehensive company report, right.

Lem   18:42
Yeah, this one is.
Comprehensive.

Peter Wolf   18:47
We can come up with something shorter than that, yeah.

Lem   18:47
So yeah, like for. Yeah, for example, just company report and then the other one would be like, yeah, job post, right job.

Peter Wolf   18:55
It's job posting.
And ultimately, if there is a job posting report, then it should also be in the company report.

Lem   19:00
Yeah.
Oh, right, yeah.

Peter Wolf   19:04
Right. There will be two separate docs, but ultimately when you produce the company report, it should grab the job posting report and embed it at the bottom.

Lem   19:13
Yeah. OK.

Peter Wolf   19:15
Because when I get the company report, I want the whole, I want everything together.

Lem   19:16
Uh.
Yep, yeah, I think we could add that one.

Peter Wolf   19:22
But there will always be a job posting report right? There will always be a job posting report.

Lem   19:25
Yep, yeah. But if there's yeah.

Peter Wolf   19:27
It's only when the job posting report triggers first and tells it to create a company report that there will be any report in that column.

Lem   19:31
Yeah.
Yeah, that's right. So yeah for.

Peter Wolf   19:38
Right. So in in the columns in the rows where someone manually enters a company code, it should populate the job posting report as Na.

Lem   19:48
Yep.

Peter Wolf   19:50
And then if it were the if it were triggered by job posting report, it should populate the job posting report link as a Google doc.

Lem   19:50
Yeah, it will, yeah.
Yeah, as a Google doc and then it will add the report also here.

Peter Wolf   20:05
Into the.
Into the full company report.

Lem   20:08
Full company report. Yeah, OK.

Peter Wolf   20:08
So the full company report is comprehensive. If there's a job report, it's in there. And if there's not one, no big deal, right?

Lem   20:10
Yeah, got it.
Yep.

Peter Wolf   20:15
Just a regular company report, but then there will always still be the job reports. Separate LinkedIn here.

Lem   20:15
Yeah.
OK.
Yeah, it's a link.
Yeah, it will.
Just like update this one with all the details here.
Yep, that's right.

Peter Wolf   20:29
Right. And also just like you did on the company report, you should have the source link.
So in the job report, it should definitely have the original.
The original links to the job postings, so someone can Click to go to it.

Lem   20:42
Yeah, like link also together with the link of the jog post right on where it is.

Peter Wolf   20:48
Yep.

Lem   20:49
Yeah. Where it is coming from.

Peter Wolf   20:51
Yep.

Lem   20:53
OK.
And then we could also trigger it here.
So yeah, I think, yeah, I got the picture whole picture.

Peter Wolf   21:01
And then since yeah.
So, since there's we're not gonna have a customized e-mail for this, it'll just be the standard default make e-mail.

Lem   21:03
And.
Uh.

Peter Wolf   21:11
Like as we said here is if someone manually plugs in a company name, they can manually plug in a supplemental e-mail address where they want to get the report.

Lem   21:15
Yep.

Peter Wolf   21:20
But when the reports triggered by the job posting job flow, it won't have an e-mail to put in here.

Lem   21:20
Oh, yeah. Yeah, that's right.
Yeah, it would just, yeah.

Peter Wolf   21:26
It'll just use whatever the default e-mail is.

Lem   21:29
Yeah, the default e-mail. Yep, that's right.
Yeah, it will.
Just use the default e-mail here.

Peter Wolf   21:36
I'm just.

Lem   21:37
Yeah.

Peter Wolf   21:37
I'm just thinking about this.
Let me just think about this.
The Who gets to deliver to right?
So first I'll think about my team and how we would use it. And then I think about broader.
So the broader organization.
Wouldn't care about the job posting one that's very specific to me, I think because I'm looking for Treasury SAP implementations, although they could now 'cause if they look for job postings for competitor functionality.
There's no reason to go after that.
They've already decided they're gonna go down that path of that software, so.
Pursuing them isn't really a good idea.
Isn't really gonna.
It's kind of late in the game to do it, so the job posting one is really only definitively relevant to my team.

Lem   22:25
OK.

Peter Wolf   22:25
And so.
Yeah, I think.
I think we should have in the job posting one.
We should also have a an e-mail function.
Or hold on.
Yeah, when we post the job posting, when we call the company here, we should populate an e-mail address predefined relevant just for job posting content, because that would go to my if if Microsoft was one of the ones we found job posting for.

Lem   22:48
OK.
Here on the e-mail.
OK.

Peter Wolf   23:02
Then then we should populate in that first blow the job posting flow.
There should be a defined e-mail account that we want to to send the the.
Company report to OK.

Lem   23:15
So yeah, we will also put the e-mail here, right.

Peter Wolf   23:17
Yeah, that's what I'm saying.

Lem   23:18
That's right.

Peter Wolf   23:19
But the the e-mail will be different than the one for the regular company.
Report. This one's relevant for the job posting when the when the job posting is the trigger for the company, report that one will go to my sales assistant that will go to my sales assistant, right? Me and my sales assistant. Whereas the one where we go to.

Lem   23:30
Alright. Yeah, yeah.

Peter Wolf   23:38
A company report.
That could be anybody on the sales team and they'll just plug in their e-mail address what they want to get.

Lem   23:42
Yeah. OK.
Yep.

Peter Wolf   23:47
Right. And then the and the default make e-mail address will also kick in.

Lem   23:49
4.
Yeah, that's right. Yep.
The but for the job posting, because this is actually triggered daily, so we don't have like.
Like a way to put a dynamic e-mail there, because it's it's already.

Peter Wolf   24:11
No, it wouldn't be dynamic in the job posting flow. I want you to add something a definitive e-mail address.

Lem   24:16
OK.
Oh, OK.
Yeah. Yeah, got it. Yeah.

Peter Wolf   24:22
That you're gonna include when you when you call this job, when you call this flow.

Lem   24:25
Yeah.
Yeah. So it it will also e-mail to like a different, for example default e-mail.

Peter Wolf   24:35
Yes, yes.

Lem   24:36
Is that right?
For example, this is like the flow right? Then at the end there will also sent.
It will also send the e-mail with complete complete company report with the job posting report to us particular e-mail, but like a different than this one. Is that what you?

Peter Wolf   24:53
Yeah, hold on.

Lem   24:58
Yeah, so it's it.

Peter Wolf   24:58
I'm just.
I'm just thinking about realistically where where is this going to go?
Because I mean this to me, we will use this immediately.
This is this is a freaking great flow.

Lem   25:06
OK.

Peter Wolf   25:08
But who's gonna get it?
So first of all, I know my team, if I'm doing it's my team.
It's clear it's easy.
I can list who I want in the make flow they're gonna get.
Everybody will get that report.
See the company.

Lem   25:21
Yep.

Peter Wolf   25:21
We can have a specific person.
Say well, I need this person to get the e-mail so I can plug it in here.
Plug it in manually, but when the job post.
But what about other teams?
I don't need to worry about that right now, right? This one's my flow. When we put it into Microsoft Environment, then I can worry about other teams.
So for now this one is just about my team and that means I can have the defaults in in the.

Lem   25:44
OK.
Yeah.

Peter Wolf   25:52
In the make for the regular one, right?
That's just the job posting. It'll go to everybody.

Lem   25:56
Yep, this one, yeah.

Peter Wolf   25:58
Then when it's a.
And would I need something different?

Lem   26:02
Yeah, go go to the sist and then.

Peter Wolf   26:05
I just wanna. I feel like I wanna get this functionality in here because I want the one with the with the job posting to potentially go to a different person.
And so if in the job posting flow you have a predefined e-mail again in the make in the make flow you just say hey whenever it's a job posting it should go to Chris Benson and he just plug Chris Benson's e-mail address.
Into that job flow posting. So when it creates a report it creates a job posting report and it comes over here, plugs the company in.

Lem   26:39
OK.

Peter Wolf   26:41
It should go grab what e-mail addresses in that job posting.
Definition.

Lem   26:49
Oh.

Peter Wolf   26:49
So just like you have predefined, you have predefined e-mail addresses in the in the company report.
I want you to have predefined e-mail addresses in the in the job flow report, but you don't have to send an e-mail then.

Lem   26:56
Yep.

Peter Wolf   27:03
You're just gonna put the e-mail into this so that when the full job report with the job with the job posting and the company report is done, it'll be sent to that person.

Lem   27:14
Oh.

Peter Wolf   27:16
Sorry, I'm not doing a good job, OK?
I'm gonna try it one more time, yeah.

Lem   27:20
We could.
Yeah, because like the e-mail.
Because yeah, for that one, for example, the flow started.
So this would already be populated.
After the flows started and then for yeah. For example, there's already a company.
A company a here and then there's like the link here, right?

Peter Wolf   27:44
Yep.

Lem   27:47
And then like this is also the link for the job posting report and then what I was planning.

Peter Wolf   27:47
Yep.
Yep, Yep.
But what I'm telling you is it should also populate B because B is only normally populated manually when someone plugs in a company name.

Lem   27:57
This one.
So.

Peter Wolf   28:03
Thing is, I want the job flow report to populate an e-mail address here.

Lem   28:08
Yeah.

Peter Wolf   28:08
That e-mail address can be a fixed, a fixed value on the job flow report on the job flow process. It can be a fixed value, just say.

Lem   28:10
But.
OK.

Peter Wolf   28:18
Here's the e-mail address I want you to populate in the spreadsheet.

Lem   28:18
Yeah.

Peter Wolf   28:21
Whenever I have a job flow report job post report.

Lem   28:25
Yeah. So yeah.
But we we we also send an e-mail to this one or no, just just populate this one right with a fixed e-mail.

Peter Wolf   28:32
Well.
Well, given given that the rule is 'cause at this point, once it's populated, it becomes the normal process flow for the full job for the full company report.

Lem   28:44
Oh, I, I see. I see.

Peter Wolf   28:44
So it will automatically take that e-mail address and send the full company report to that e-mail address.

Lem   28:45
I. Yeah. Yeah, yeah, yeah.
Yeah. Yeah, that's right.
So basically, yeah, this would be the first one on that flow, yeah.
OK, OK.
Yeah, I got it. So before.

Peter Wolf   28:56
Again, that's going to be a fixed value, a fixed value in the job, in the job search report.

Lem   28:58
Yeah, fixed value and then before triggering this one, Yep.
Yep, that's right. Yeah, yeah. Yeah, basically.

Peter Wolf   29:05
OK. And then it will do its normal rest of its flow and it will go and populate you know populate the links it will it will create the job report.

Lem   29:08
Yeah, that's right.
This one? Yep.

Peter Wolf   29:15
It'll it'll already have the job report. It'll give the job report link or give the company report link and then it'll combine the job report into the company report.

Lem   29:19
Yep.

Peter Wolf   29:23
Then it'll e-mail to the name in column B to the e-mail in column B, plus to all the defaults that are set in the make report for the company report.

Lem   29:25
Yeah. Yeah, that's right.
Yep, that's right.
Yeah. Yeah, yeah, yeah. I was able to get that one.
Yep. So yeah, basically whenever the first one.
So after the first first flow started like scheduled.
So let's say it it gets the company a with a job posting report.
So this would send a name here and also the e-mail and then click the this one.
Start research.

Peter Wolf   29:56
Yep.

Lem   29:57
And then yeah, it it will trigger the like the this one the original flow and then yeah it will send this to this e-mail also it will add this one.
Yeah. And then yeah, it will get the this particular final company report with job posting, yeah.
Yep, OK.
Yeah, got it.

Peter Wolf   30:14
Yeah. All right, good.

Lem   30:16
Yeah, OK. Yeah.

Peter Wolf   30:17
This is this is awesome.
This is this is really great.

Lem   30:19
Oh.

Peter Wolf   30:21
This is awesome for sales.
Kind of competitive analysis, quick action.
To to go after prospects.
All right.

Lem   30:32
It was just it also like I think will only take like 2 to 3 minutes also or less than three. Two minutes. Yeah, to from the trigger to the like the report.

Peter Wolf   30:38
OK.

Lem   30:44
So that would be, yeah.

Peter Wolf   30:44
Yeah, that's fine.
This is not one that's highly time sensitive, right?

Lem   30:47
Yep.

Peter Wolf   30:49
I mean, if someone comes in here, plugs in a company name, they should have done it.
At least you know if I have a call in a couple minutes, this is something I do now, right?
I have a call coming up my my business development resource sales guy sets up a call.
I don't plan to practice or prep for it at all. The last minute I go out and do a quick research on the company, know what their revenue, all this stuff.
I just come in here, plug this in a couple minutes before the the call.

Lem   31:12
Yeah, yeah.

Peter Wolf   31:15
Boom. I have the report.
Or, since I already know I got all this stuff, I don't have to do it.
Meaning, take a lot of time.
I'll just plug it in as soon as I know the the the meeting's coming up. I just go run this report and then I know I already have it to reference later on.
So this is a. This is a great real world active use process.

Lem   31:30
OK.

Peter Wolf   31:35
Both of them the the second one for the looking for sales.

Lem   31:37
OK.

Peter Wolf   31:38
It's just a great prospecting tool.

Lem   31:41
Yeah, for the.

Peter Wolf   31:41
Especially right now, companies are are in my area.
Companies are doing these new major shift projects to go over to new SAP release and they're posting for these jobs because they don't have a skill set.

Lem   31:54
OK.
I will just get also the list for the like filtering to the job posting. So because yeah we would I would need the like the particular job posting list that you want.
Specifically and Yep.

Peter Wolf   32:11
I don't understand what you mean.

Lem   32:13
The like the.

Peter Wolf   32:14
Oh oh, the list of the list of titles the the roles that I want the jobs that you're looking for. Yeah, OK. OK.

Lem   32:18
Yeah. Yeah, that's right.
Yeah, the jump.
Yeah, the jump post and then, Yep.
I'll just up plug it into like a scraper and then Yep, OK.

Peter Wolf   32:28
Yeah, actually, I'll tell you what I'm gonna. I'm gonna list them right now.
And what can one of you, Brian, can you pull it out of the notes here?
Of what I'm gonna list pulled out of the notes later on, OK?

Bryan Wolf   32:38
Yeah.

Peter Wolf   32:40
So you might wanna look at the time stamp where we are or you could search the transcript, but here's a list of of job posting definitions.

Lem   32:40
Umm.

Peter Wolf   32:49
So you should have SAP in front of everyone of these, so the SAP cash management SAP.

Lem   32:54
OK.

Peter Wolf   32:58
The Treasury management SAP risk management.
SAP apm.
SAP Advanced Payment management will be able to get them out of the out of the transcript. You don't have to type them down right now.

Lem   33:15
OK.

Peter Wolf   33:15
SAP in house bank.

Lem   33:15
Yeah, yeah.
Oh.

Peter Wolf   33:20
SAP APM hyphen ihb.
That's in house bank Ihb.
What else?
SAP cash flow analyzer.
I think I said STP cash management.
What else?
I think that's good for now.
Alright, so you can easily extract those, but I find them in the transcript.
Extract those and send them over to send them over to Lem.
I didn't run the fathom today, so you have to get them from the from the the internal.

Bryan Wolf   34:00
Yeah.

Lem   34:07
OK.

Peter Wolf   34:08
Teams, teams, recording.

Lem   34:10
OK.

Peter Wolf   34:12
Ryan, can you do that please?
OK, make a note.

Lem   34:13
Oh, I'll just ask it later.

Bryan Wolf   34:15
Yes, I get it.
No, I'll be able to get it sent to you.

Lem   34:18
OK.
Yep.

Peter Wolf   34:20
OK.

Lem   34:20
Oh yeah, the SAP ones.

Peter Wolf   34:20
So we'll start with those job postings.
I'm sure I'll probably add some more to that, but that's a that's a good foundation list.

Lem   34:26
Yep.
OK.
Yep.
Yeah. Basically I will like.
Yeah, create something like this with scraping, starting from the scraping 1.
Yeah, that will trigger daily.

Peter Wolf   34:44
Yep.
But again, I would like it as a as a package like you have where we have the folder, the one flows the scraper looking for job postings, the other is the company report, right?

Lem   34:47
Then yeah.

Peter Wolf   34:58
Because once we do this, when we get this over to Microsoft Environment, we're gonna expand on that company report. We're going to go to Salesforce and we're gonna pull the latest interactions with the company.

Lem   35:06
OK.

Peter Wolf   35:10
We're gonna look at what products they've already purchased from us.
What the last interactions were with the relationship is.
Who The Who? The account owner is.
And then on the, we're gonna go to zoom info, and we're gonna extract zoom info which will give you more clarity on where they are in the sales in a in a purchase cycle because it does things like look at what they're they're looking at, what software they.

Lem   35:25
OK.

Peter Wolf   35:36
Looking at things like that so we can extract that content.

Lem   35:38
Mm hmm.

Peter Wolf   35:39
So this will make it even more robust.

Lem   35:40
OK.

Peter Wolf   35:41
Those are proprietary internal systems.
At least Salesforce will have our proprietary information.
Zoom Info is a, you know, public repository.
You pay for that service though, so it's insight information that's not just generally available, it's information that they gathered up and compiled in their system.
So those are good supplements to this report.

Lem   36:02
Yeah.

Peter Wolf   36:04
Again, let's call it a. You know, sales, sales, strategy report or sales positioning report or.
Client or prospect preparation report.
Right, so this is this is great stuff, but we'll expand on it.

Lem   36:17
OK.

Peter Wolf   36:20
We can't get to those sources while we're on the outside.
We need to get into the Microsoft environment and then we can start drawing those other pieces of information as well.

Lem   36:32
Yep, got it.

Peter Wolf   36:36
All right.
So what else?

Lem   36:43
Post.
Daily.
Sugar.

Peter Wolf   36:50
All right, Brad, do you have any issues that you that ran into with the stuff you were working on or anything that Lem was doing yesterday?

Lem   36:52
Scrape.

Peter Wolf   36:56
Or are we all good in our environment?

Bryan Wolf   36:57
Nope.
I'm good.

Lem   37:00
From first.

Peter Wolf   37:00
OK.
Alright.

Lem   37:07
Add to company.

Peter Wolf   37:10
Yeah, after the call yesterday, you were still working with them, right?

Bryan Wolf   37:12
Yes.

Peter Wolf   37:13
Just working through stuff, looking at different stuff.

Bryan Wolf   37:16
Yeah, we're gonna work on, but they're we're gonna work on the flow that we did yesterday and then?

Peter Wolf   37:16
I mean, I would think.

Lem   37:17
Yep.

Bryan Wolf   37:22
I think I got a test the newsletter again and then it's really.

Peter Wolf   37:27
Alright, so you could you could work with him while he's working on this flow, but I was thinking I'll tell you what, Len. If you could drop off for a few minutes and then Brian can ping me back and you could come in. I just wanted to talk.

Bryan Wolf   37:31
Yeah.

Lem   37:35
OK.

Peter Wolf   37:38
With the guys for a couple minutes so you could start working on that flow. And then Brian could connect back with you and walk with you, walk through it with you as you're building that, OK.

Lem   37:41
OK.
OK.
No problem.

Peter Wolf   37:47
Alright, thanks.

Lem   37:49
Just yeah, just e-mail me. Or yeah, just ping me or message me when I'll come back.
OK.
Hey guys. Talk to you soon.

Peter Wolf   37:57
Thanks, bye.

Nicholas Westburg   37:59
Thanks Lam.

Peter Wolf   38:03
All right, so.
Few things one.
Yeah, one I think.
The the the flows that we're building right now, whether they seem like it or not, are really actually pretty, pretty cool flows that are really very useful.

Peter Wolf   38:22
These new ones, this these two new ones in the newsletter I think are the most intriguing 1.

Peter Wolf   38:23
And then I can see.

Peter Wolf   38:30
Excuse me? They're screaming outside.

Peter Wolf   38:34
Oh, what the the protesters.

Peter Wolf   38:36
Yeah, I think these ones are the most like ones I've been most hyped for because you can see actual.

Peter Wolf   38:42
Yeah, we're just finally getting.

Peter Wolf   38:44
Day-to-day application.

Peter Wolf   38:44
We're getting there, right?
We're getting there. We're getting there.

Nicholas Westburg   38:46
They look good, yeah.

Peter Wolf   38:48
And and I think you know some of the learnings we had from the other stuff is leading into this and I think these little again I just call that kind of gold Nuggets, some of that stuff is clearly again he's even though he considers himself relatively inexperienced he.
Pretty friggin. Far along, right?
I mean the stuff he's just come up.
Oh yeah, there's a there's one where I can go get this, and I'll. I don't know if that's stuff where he's going and doing research. It may well be because he's even set on several these.
He's like, why? I didn't know this.
Went, go, went. Found this.
So he's he's doing research as he's doing this, and I think that's one of the best things we've talked about before for you guys to learn is, yeah, where do I?
How do I go find this stuff out?
Well, yeah, these if I wanted to go get information, get the logo, you go get a logo, plug that stuff in.
Is there an API?
How can I do it with mink all that?
That's the kind of stuff where I keep bringing up and saying even if there isn't anything to work on.
Taking these flows and looking.
At what?
The steps are and saying how do I go find a new step?
How do I add a step?
How do I add some functionality?
How do I think about adding functionality?
How do I come up with if I did want to add the functionality and I know it may seem mundane, but like in the newsletter I brought this up before I just raised it up again.
To me, I would be taking the newsletter and saying OK, I need to learn how to manipulate that HTML, right?
I want to right now add a underline for the for the source names on the on the newsletters.
How do I add an underline OK?
Great. Play around with it.
Take that HTML work with figure out how you write the code in HTML and do an underline until you get that.
Put a big bold, you know, line around each of those boxes where the articles are.
These are the kinds of things where I just say my personal experience. Past experience when I was trying to learn new functionality.
These are the things I was doing.
How do I make it do this? How do I?
What happens if I'm missing some information?
How does it fail?
How do I troubleshoot it?
How do I make it better?
How do I expand on it?
Because I think that experience, there is also what's gonna enable you to be able to come up with new flows, think about how to pull them together, how to enhance a flow, etc.
But I think I agree.
I think these last few flows are really very good flows that can be used in a lot of different places by really any company for sure, because every company does sales right and having a competitive kind of information on that now maybe not the job look up that.
Very particular to me.
But it's not just to me. It's any company that's a consulting services company that would be a valuable flow, right that that going out and searching for companies that are doing a certain skill set where I know that's my specialty.
Let me go see what I can do now.
One of the things I didn't say to him, which I should have is we're gonna need that report to go and look. Did I already find this company before? If I already found this company before, just add the job posting to that company, update the company report.
So Brian, can you make note of that?
So when you go back to talk with him, So what I'm saying is when we we have the first blow, which is the job flow when that job flow finds a company, it populates into the company report spreadsheet and fills it out right and then runs the normal.

Bryan Wolf   41:59
Mm hmm.

Peter Wolf   42:07
Company report process. Well, if we already looked up, let's say DuPont manually rather we plugged it in the spreadsheet.
Last week and got a company report.
It's in the spreadsheet already.
And then.
Today, all of a sudden the the daily job posting flow found the that DuPont is listening for this position.
It should go in and see. Is DuPont already in the spreadsheet instead of just adding it? It should say oh is DuPont already in the spreadsheet?
If it is, you don't need to add it.
You don't need to do all that stuff.
You just need to go take the job report.
Plug it in the job report column and and then update the.
The company.
Report with that job report.

Bryan Wolf   42:52
OK.

Peter Wolf   42:54
You follow that.

Bryan Wolf   42:55
Yeah, yeah.

Peter Wolf   42:57
Are you outside the door?
Are you?
Are you there?

Bryan Wolf   42:59
Hey. No, no, I'm right here.

Peter Wolf   43:01
No, I thought I was seeing the outside door for some reason.

Bryan Wolf   43:01
Can you hear me?

Peter Wolf   43:04
My speaker's not working real well.
OK, let me try this.
Try again. Can you talk?
Yeah, I don't know why.

Bryan Wolf   43:13
Hey test test test.

Peter Wolf   43:14
It's my my speakers aren't working. Yesterday they failed.
I don't know what's going on, so it's coming out of my laptop and that's really dull, OK.
So that's, that's one thing, right?
I'm gonna try and come up with more flows like this.
That will continue to expand on that.
But I also wanna look at where we are, what we're trying to achieve.
I wanna you know, I want you guys to be finding this stuff as valuable.
Obviously I have a different perspective.
So maybe some things I think are valuable and I think would be broadly valuable.
Don't don't trigger for you guys, but for sure these last couple flows, there's nothing about these.
It is not transferable to other companies to talk about how you can do this kind of research, help their sales and and just help kind of competitive positioning.
What I would like to talk about is some other processes.
Like I said, I'm gonna take these, and I'm gonna certainly move several of these into the Microsoft environment, right?
Still need to find the Microsoft automate resource to do that.
And I did.
I did try to schedule with and maybe we can do this for tomorrow? I asked.
Let me just look at 10.
No tomorrow, Sox.
I asked.
You know the flow that, that, that Jill had made in Microsoft is really pretty basic, but it does tie into the SAPO data, which is something I think is really attractive and and again shows how we can tie systems together to get comprehensive reporting and insightful information and.
The the thing he has, he's just doing a manual trigger.
But this is where I want to add just like for these all these folks, I want to add things like.
Teams trigger.
I'm in teams right now.
I plug in a message and say hey, give me the company report and it automatically does all that stuff, populating the spreadsheet and all where I don't have to manually go there. That's that's really attractive, right?
Because people use teams in a Microsoft environment.
It's sitting there right in front of you as an easy trigger.
We do this today for serrala for reporting on our programs.
We can do we we give a tool that's delivered to our clients that will enable them in the Microsoft environment to do.
Which is the data that's in our custom tools, so like invoices.
Customer or vendor information, stuff like that.
But the invoice is primarily it's like what invoice?
Do I have that are due today?
What invoices are past due and what's a discount on them?
What invoices should I pay or could I pay now to accelerated discount?
Things like that is natural language processing and it's in a in a teams environment, which means it's always readily right there. You just plug it in real quick what you want.
And get results directly in the street.
So where we're saying send an e-mail and all that kind of stuff in the Microsoft Environment, I would see it.
You plug it in into teams, you get it back in teams.
Now you can also have it send an e-mail.
You can even say I want to send this to certain e-mail address. Put that in. It could extract that data, populate the spreadsheet as we were just talking about and it could send that report to your e-mail address as well.
So that's what makes these flows different in the teams environment or Microsoft Environment?
Because one the functionality is a little different. Two, we have different different platforms to be able to execute from to initiate efficiently and to get reports back in efficiently.
That's different than the e-mail approach and I think that's much more kind of real time real world.
Yeah, one SEC.
Nick then, then also the other thing, as I said, embedding other information.
Well, we have proprietary information.
Like in Salesforce I can't get that on the outside world.
That's information.
That's additionally insightful, very specific to my company. Every company's gonna have that their company information of their prospects, their sales and so updating and enhancing the sales report with that particular data is gonna be substantially valuable as well.
So those are the kinds of things that I think are really important when we get into Microsoft, where you get to bring that extra insight. And I think those are very attractive when we're talking about posting it on GitHub or, you know, pitching what?
Bill said is what environments you can work in.
I think this make.com stuff at Gmail.
Well, there's a there are smaller companies that all work in that you know in, in Google Environment, right.
There are some larger ones, but more Microsoft ones.
Microsoft Environment for large corporates and so I think having those two skill sets again strengthen the resume, show your ability to work in different environments that you understand the concepts, not just the individual tool, but you understand how to apply those concepts in different environments. I think that.
All really.
Valuable stuff.
That will help to juice your resume and and look very good when you're kind of pitching, being comfortable with them is important, right?
Brian's obviously one getting to run these things all the time, that's that's given him a certain comfort.
Nick, I know you've played around with this stuff, so whatever your comfort level is, you know, I'm not sure what that is.
I know, Peter.
It's a lot more difficult for you to get the time to be working on these, but these things I'm talking about playing around with it.
About tweaking, getting the idea of how do I change the format if we were on the newsletter instead of that logo at the top? I wanted a different logo.
Do you know how to change that logo?
How do we change the order of the stuff?
Take the the the the articles instead of them being the first section, make them or the you know the first section after the introduction.
Make them the third section. Those kinds of things are the things that I think are necessary.
To feel comfortable so that if you were sitting there interviewing with someone or talking about it just on the fly, you could throw these kinds of tidbits out there.
Just show that you have some insight, right?
So it's a little bit deeper, a little bit more hands on to show that you can you can be comfortable in processing those kinds of things.
I think that just strengthens the argument, strengthens your position, strengthens your capability to sell yourself in those in those skill sets.
But so Nick, you you want to you want to ask someone say something?

Nicholas Westburg   49:29
Yeah, just just a quick question.
So I keep running into and hearing the the the SAP Odata.

Peter Wolf   49:36
Yeah.

Nicholas Westburg   49:37
So is the Odata just like is it like SAP data in real time?
Like in your line of work like how?

Peter Wolf   49:46
Yeah.

Nicholas Westburg   49:46
Because Jill brought that up too, like a little a month ago or so.

Peter Wolf   49:49
Yep. So here's here's the thing. In in the in the in the in the older systems, which are called ECC enterprise core component.
That's what most companies are on right now.
SAP release of software that's been out there since.
I don't know, 15 years, right?
So that that subway they've been improving it and they get new releases, hot packs, upgrades, etc.
So that the the version is right now it's like 4.6 the release is 4.6 and it's like Enhancement Pack 8, right?
That's the latest version of ECC.

Nicholas Westburg   50:28
Is it public public data?

Peter Wolf   50:28
They're not really updating.
Say what?

Nicholas Westburg   50:33
It's public data at whatever.

Peter Wolf   50:34
No, no, that is.
That's that's the release date.
That's like saying that's like saying Microsoft Office 2016 or Microsoft Office 2020.
That's that's the release right and. And so that enhancement pack thing, they had an enhanced pack, one enhancement pack, two enhance pack three. And each time they had one of those enhancing packs, they threw more functionality in there. And so you wanted that functionality, you'd apply that EN.

Nicholas Westburg   50:46
OK.

Peter Wolf   50:59
Pack. But that was like a mini upgrade.
So that was their strategy.
You had a core.
The core release was called 4.6 and then they had these enhancement packs that they were building new functionality in different areas, and you'd apply that enhancement pack if you were if you wanted to get that functionality.
So now the newest release is called S4 HANA and in S4 HANA what they did was re engineer the structure.
They re engineered the structure because one of the core reasons is.
That in in SAP environment.
You build up.
This huge amount of data in these massive tables and you can't typically report in a big way on that data in real time, because if you have to analyze the data and you have to search the data in the production system in real time, it slows down the.
Database table processing, which means it slows down the production processing right?
So now where people are trying to process manufacturing or sales or whatever.
And you're running some kind of report.
I'm slowing down the business from being able to do its job right.
So this was a big problem.
Is a big problem in ECC and So what companies do is they extract all that data out whatever data they want, they pick specific data, they extract it out to something called a business warehouse.
The business warehouse is really just a repository of the same data that you have in your production system, but it's extracted into.
A database that's not your production system that can be indexed, so it's faster to search.
And when you search it, it doesn't impact on production system at all.
So the problem is it's not real time, right?
So normally you do this once per day.
Maybe you could do it more frequently, but even extracting that data, slowing down the production system.
So normally you would do this kind of once per day and you'd extract that data, put it into business, warehouse or BI business intelligence system just for that data for reporting, and then you build your reports all out of that system, right?

Nicholas Westburg   52:48
Yeah.

Peter Wolf   53:01
You use something like crystal reports or.
Business objects.
And you build your reports with the using that data, which is yesterday's data. But that was the best you could have, right?
You could run small reports in production, but anything that was big would drain the system and would cause performance issues and production. So in S4 HANA they re engineered design completely.
Now all these tables are optimized for in memory search.
You can search right now in production.
And not impact on production system?
So this was a massive advancement for companies, especially that are big data.
Let's talk about utility company, right?
Millions of customers and and millions of data points that they need to pull.
Well, if I want to pull reports on that, that's that's going to drain the system. But in in the in the S4 HANA environment that's that could be done in production, right?
So with all these re engineered tables, the structures all changed.
The the You know the old tables.
Many of the old tables they left there just from reference, but really they're using new optimized tables as the processing tables and with those tables they've now created this function called Odata and Odata is really an API interface to access that data in in real time in product.

Nicholas Westburg   54:22
The restate that it's called restful or Rest API or whatever it's called OK.

Peter Wolf   54:22
So the.
AP.
Yeah, rest.
Yeah, restful API.
Restful API, yeah.
So it's it's sitting there now.
STP delivers a whole bunch of Odata reports.
And really, Odata reports just is you deciding which tables of information you want to be accessible to you and you.
So some of them are delivered by SAP, let's say standard. And if you want something special then you write your own little O data function.
So Odata function you would write say call these tables and grab this information when I call the API and so you build this Restful API state, it's sitting there waiting for you and when I trigger it with a teams call through Microsoft automate it calls it goes to.
The Odata service it knows which Odata service I want. It grabs that particular service.
Feeds it the information it needs.
Give me what I want, like I might want a certain companies, you know, 'cause within the enterprise, we call them company codes in SAP.
They're legal entities.
Often they're legal, and it's most often their legal entities.
But you could split them in different ways, so every legal entity you know an enterprise might have a hundred 200. You know Microsoft has 400 legal entities, all under the umbrella of Microsoft.
Different countries different.
Different roles, different functions. They're all legal entities.
They have their own contracts.
They have their own, you know, kind of.
Structure they that isolates the risk across companies at a time or specific to giving countries specific functions, etc.
Those companies I'm like, only want the report for the sales on company 1-2 and three not all 400.
So that's where you feed information into the O data request and it gives you that data back in an API in a structured format.
Then you take that and do whatever you want with it.
This is the way that SAP.
Now that's four wants all interaction for data requests because SAP very smart.

Nicholas Westburg   56:30
Survey and power automate power automate and the Microsoft environment.

Peter Wolf   56:36
Yeah, the power automating in the Microsoft environment is just the is just the mechanism around which I'm triggering the call to the O data, right.

Nicholas Westburg   56:36
For.
My children, come on.

Peter Wolf   56:45
Normally I would write some custom report that says I want some information.

Nicholas Westburg   56:45
Yeah, yeah.

Peter Wolf   56:50
I would go to the tables and I'd go grab that information like we write. My team has written my development team's written scores of reports, hundreds of reports that go to the database tables directly and extract that data.
Well, now SAP doesn't want you to go directly to the tables.
I want you to go to this Odata service and partly because.

Nicholas Westburg   57:09
Via the Restful API.

Peter Wolf   57:11
Yeah.

Nicholas Westburg   57:12
Or yeah, OK.

Peter Wolf   57:13
Yeah, the the Restful API really just means the stuff is sitting there waiting for you to call it to trigger, right?
It's not.
It's not proactively going and getting the information and sending it to you. It's sitting there waiting for you to call it and say give me the information, right?

Nicholas Westburg   57:20
Yeah.

Peter Wolf   57:29
That's the restful part.

Nicholas Westburg   57:29
Yeah.

Peter Wolf   57:31
And so in what SAP is doing SAP what they really want?
Look, all companies, especially companies like SAP data, is the key.
We've talked about this before.
Data is the fricking gold.
Data is where the money is. Your ability to have the data control the data.

Nicholas Westburg   57:44
Yep.

Peter Wolf   57:48
Write reports on the data.
Analyze the data.
Use AI on the data.
Interpret the data.
That is where the value is.
So SAP knows the more it can control the data, the more control it has over pricing over.
Yeah, just over domain dominance from its competitors.

Nicholas Westburg   58:04
Yeah, yeah.

Peter Wolf   58:06
Or from vendors like me, right?
Vendors where we develop software SAP S making it harder and harder to embed that software they're making you go through API's so that they can start charging per API data flow. So every time you want to extract data out of SAP, they're going to charge you just.

Nicholas Westburg   58:21
Yep.

Peter Wolf   58:25
Like the tokens, that's where they're going.
So when they force you into these Odata services and these other AP is and they have something called BTP which is.
A.
Oh ****.
****, business transformation process or something that is the new mechanism for all interaction when you're talking about executing processes, not just reports which would be Odata service. But like in a process in in in my AP process, my company's AP process where we want to grab the.
Invoices and do something with the invoices we would integrate through this ptpi don't just want information, I want to be able.
To do something back to the information, right?
So if I have invoices there and I want to analyze those invoices and update status.
Well, I want to extract the data through the BTP. Then I want to do something out here outside SAP.
Then I want to shove it back in and have it be updated in SAP.
So I got to go through BTP in and out, but that's more than reporting, right?
The O data is just extracting information for reporting.
You can't push anything in.
You can't change the information in SAP with BTP. You can go both directions.
You can take stuff out.
You can shove stuff back in, but again.
SAP.
He owns the the the the portal right, the PTP portal and the and the the Odata portal.

Nicholas Westburg   59:43
Yeah.

Peter Wolf   59:47
You can write your own custom programs and all that kind of stuff, but SAP ultimately owns that gateway and this is where I know that they're going for pricing and cost and whatnot. But so for us, we know that our clients want certain reports. We're building custom reports.

Nicholas Westburg   59:55
Yeah.

Peter Wolf   1:00:02
For them, in addition to what SAP already has and we're making them easier to get to, right, right now a user would have to log.
To SAP would have to go to the specific report in Treasurer Cash management to see what FX trades. They have foreign currency trades, what intercompany loans they have between.

Bryan Wolf   1:00:22
Lamb usually gets off like 1111 thirty so.

Peter Wolf   1:00:25
Give me two more seconds.
I'll wrap up.
I got it.

Bryan Wolf   1:00:27
Yeah.

Peter Wolf   1:00:28
I understand.
I understand.
I appreciate that.
Thank you.
The but the what we're looking to do though, is to make it easier.
Make it more efficient that we can build these power automate tools that I can then take to my clients and say hey, plug this in your system, this is already a flow that works.
I'll write you the custom O data report.

Nicholas Westburg   1:00:48
Yeah.

Peter Wolf   1:00:50
You'll deliver the put the Odata report in there, then put this power automate flow in here.
And I'll be able to give you in teams. You just said give me my FX trades give me my intercompany loans in just normal natural language.
Not going into SAP.
Not going into the transactions, which are a little bit cumbersome to get in.

Nicholas Westburg   1:01:08
Yep.

Peter Wolf   1:01:10
Log in somewhere else.
I'm sitting here.
I just want the cash flow report great.
Give me the cash flow report and then we can do things like enhance it.
What we're doing is we're then taking that data, putting it into that like our dashboards, right?
Delivering a dashboard and having AI analyze it.
Say well, if your balance.
Negative. Tell the person that they need to fund that account.
So it goes to Odata, gets all the balances, is one example.
This is the example he has gets all the balances for bank accounts and says great. I'm going to feed these back to you and if there's any accounts that are negative, it goes to Microsoft Copilot custom copilot and says analyze these if any are negative tell the US.
They need to fund the account, like call it out, but that's just showing the logic showing the capability of the custom.
The.
Microsoft Copilot agent right.
But we could make that much more, much more advanced, right?
What the logic it's doing could be substantially more involved. It says well funded.
Here's the trigger.
Push this button.
I'll go fund the triggering mechanism.
It also goes calls copilot.
Tells what payment methods you use.
All this kind of stuff so you can build all kinds of stuff.
More advanced logic in there.
We're just trying to get our arms around these basic flows and then from there, just like we did with the newsletter, just like we're dealing with this.
This company report, right, we're figuring.
We have new ways to expand it and add new value.

Nicholas Westburg   1:02:30
Yeah.

Peter Wolf   1:02:31
That's what the focus is, right?

Nicholas Westburg   1:02:31
Yeah.
Yeah.

Peter Wolf   1:02:34
So. So that's what I intend to move forward with next.
Now I recognize we're one month into what really is only three months.
I've said it's four months and I've set it up so that we go into September.
But we're one month into three months, right?
And obviously it's been it's it's it's much lower than I wanted to be. I thought somehow I would be, you know, 50 flows in and whatever, it's just realities.
It's a learning curve for us. The availability of you guys of, of Lem, of whatever. I mean, Lem's not really an issue.
He's banging him out as fast as I can give him to him and I think we're putting them into our environment and moving forward with them quickly.
One of the problems real problems is that.
I only have a limited amount of time available, right?
I've got other priorities that I have to get done at the same time, and I'm also, as I've no, I've told you guys, I got this, this MIT thing.
It's done in essentially 2 weeks and I'm trying to make sure that I finish all my stuff there, right?
So that's the 18th.
It's actually 2 1/2 weeks after that. I'll free up a bit more.
But I want to continue to push these forward.
But what I want to do also is talk with you guys and ask you do you have? Is there something you wanna work on?
Is there something you're thinking about?
I know we talked about a lot of things like chat bots, and I know Nick, you were sending out stuff you're working on.
I'm very interested in hearing about stuff you're working on. Is there something you think that we could be doing in Microsoft Environment? In my environment, in company environment that would give you more assets that would give you more available information on whatever you're working on that would make?
It better, right?
That would give you make you make it something that would be more robust, more substantial. If there is, just tell me about it.
I'm more than happy to.
To be looking at that now I know you guys the challenges you don't have process experience and that's where I'm kind of the bottleneck of trying to pull this stuff together and figure it out.
But I also really need to be pulling in Bart and Jill more.
The problem is, right now we've got a lot of **** on our plate that we're trying to do with the sales, some massive sales, which is awesome.
I mean it, but it's taking a lot of our time as well, right?
And now we got the holiday coming up later this week, so.
So this is going to be a stunted week as well, but so I'll just put it out to you from that perspective, right.
Is there something that Nick I look for you especially given that I know you're working on other stuff is there?
Is there stuff that you think is that we could be doing or it could be expanding or somehow being in my environment being in a Microsoft environment, being in a environment that has access to other assets that that would be?

Nicholas Westburg   1:05:15
Well, yeah, there's there's always that option, right?

Peter Wolf   1:05:17
Value added.

Nicholas Westburg   1:05:19
So I Lem's doing a great job and he should not.
He's doing a fantastic job, like all the way around. What I'm doing is when Lem does a workflow like you have your excel sheet and Lam goes to the flows and walks through that.
I I like looking for other ways to replicate exactly what he's doing, and I look at it like, OK.
So we have, you know, there's a million different packages and environments.
Some ways to do certain things, and I always look at it.

Peter Wolf   1:05:47
Yeah.

Nicholas Westburg   1:05:47
OK, ROI. How can we do this at a cheaper way?
More private way secure way.

Peter Wolf   1:05:51
Yeah, yeah.

Nicholas Westburg   1:05:52
So when he does a workflow I I take it?
I look at it and I'm like, OK, so my environment, how can we approach this in a way that's cheaper, more secure and better? And and I try to veer it out to three different paths, right?
And I don't like I don't like getting into the details 'cause it's a lot and I don't want to disrupt, you know.
Lam's real Lem's work. Brian's learning.
You know what we're talking about, but.

Peter Wolf   1:06:17
Yep.

Nicholas Westburg   1:06:19
Yeah, that's what I'm doing.
So I'm taking what Lem's doing. His flows through make and I'm saying to myself, OK.

Peter Wolf   1:06:23
OK.
So let me so then just no, this is this is great.
So let me just yes, so you're getting value out of the stuff that Lem's doing. You're you're using that as a foundation to trigger other stuff.

Nicholas Westburg   1:06:29
Oh beyond.
Yeah, beyond.
Yeah, absolutely.

Peter Wolf   1:06:34
OK.
That's awesome.
That's good to know.
I'm I'm glad about that. Right 'cause you are bringing value. You're helping and driving stuff and giving. I know a lot of insight to Brian as well and and you're constantly sending stuff out there I think is very valuable to us.
I am.
I don't want it to be.
I agree.
I don't want it to be disruptive and the problem is, especially when you're talking about just getting your feet on the ground on some functionality, right? It's it's easy to be overwhelmed. Like there's 500 different directions we could go, right?

Nicholas Westburg   1:06:57
Yeah.

Peter Wolf   1:07:03
I can't be looking here here.
Here and doing all this stuff, you gotta, you know, focusing on something, building something that's solid foundation I think is really critical to get that out of the way.

Nicholas Westburg   1:07:04
Yeah.

Peter Wolf   1:07:12
But I I think we definitely need to be sitting down. The three of us are in whatever, bringing in Gill and Bart as well because I know they're interested in this stuff and talking about and looking at one of the things you're doing, how are you expanding it?
How should we be thinking about that when we go to Microsoft Environment cause my company's not going to be interested in in paying for.
Massive external tokens.
If they can avoid it right there, that right now I'm kind of throwing money at anything and just saying, yeah, this is what it's gonna cost to figure it out and learn it.

Nicholas Westburg   1:07:41
Yeah.

Peter Wolf   1:07:41
But ultimately, like we did with the news flow, it's like we originally had it say bring back 100 news articles and then take those and add them to ChatGPT and have ChatGPT do something.
It was like, well, I just did a 200 processes by grabbing the 100, then feeding it somewhere else and then having feed somewhere else. So that looking for optimization that's critical.
I think that's a big value.
Add when you when I talk about, you know understanding the flows is that kind of thinking being able to talk like that to a prospective employer or whatever and saying hey yeah, well, you know we were working on it this way, but we went and made these changes.
Because that was not cost effective.
That's the kind of stuff that shows you understand it.
This is the kind of stuff where I would be saying I would recommend.
To to be making I I do this myself.
I make notes of things that I think are interesting.
If I wanted to talk about my skill set, my experience 'cause I'm, you know, constantly trying to advance myself and prepare myself for some future endeavors.
That kind of list of things I've worked on, things I think I've achieved that I can bring out that that emphasize my strengths.
This is an example of something like that, right?
How do I talk about the process flows?
What you want to be doing is talking about the more than just a flow you want to be talking about them like you understand the concepts behind it, and you're thinking strategically.
Not just execution operationally, but strategically.

Nicholas Westburg   1:09:06
Yeah.

Peter Wolf   1:09:07
What's the cost of this?
Is this a realistic way to go about this process?
Let me re engineer the process to get a better result at less cost.
Talking about that is gonna make you look like you're deep in.
That is a differentiator, not just hey, I know how to set this flow up.
Here's step one.
Step 2.
Step three is like when we build this.
Originally we were calling 100.
Here we load it over.
Here we realized we were using 10,000.
Operations per day.
Well, that just maxed the sales.
So we had to come up with a new engineering.
We redesigned it.
Figured out if we just take the summary and that's smaller, only take the top three, that's the kind of **** that will make you look. That not only make it look, that's the kind of **** if you can think about it like that, that's gonna make you strong.

Nicholas Westburg   1:09:51
Yeah, I.

Peter Wolf   1:09:51
OK.
So look I I know's only got about 50 minutes left and I I wanna definitely get Brian working with him. I want to.
Definitely.
Nick, be looking at what you what you're working on.
I mean, that's very interesting to me.
What are? What are the ways you're looking at?
How you, you know taking alternative approach or other options for dealing with it. I think that's valuable for all of us to be talking about. I think it's obviously valuable for Brian and and Peter to also be thinking about again being able to talk in a broader context.
Like that makes you a stronger resource.
Makes you come across more insightful because it is more insightful, right?
Being able to think in those different environments and that's where the Microsoft plus the mate plus the Gmail plus the whatever Nan if we get into that, the more you show that breadth of understanding, the more it is your understanding the concepts and approaches, not just individual piece.
Technologies, right?
So I will again.
I'm gonna move forward.
I'm gonna get the automate guy.
I'm gonna get Len to show us again.
I don't wanna set.
It is too high explos just a basic flow, but it's just showing the environment and showing how we can pool the custom agent in and how we can do the same things we're doing here but inside Microsoft Environment.
Then we can expand on the flows we have.
We're gonna build them over there, but then I wanna think about other other tools and knowing that we only really have two months left of of truly, you know, kind of focused time.
But after that, just to be clear for you guys.
Like I said, I've scheduled this to go.
I think.
Deep into September and the other thing that I would propose to you and I, I'm not guaranteeing this, but I think I'll be able to do it.
I'm pretty sure I'll be able to do it is after this is over like you guys will have a resume item that says you did an internship.
I think it's gonna be great.
That's good.
A lot of strength will get the certificates. All that kind of ****.
Write some great review letters for you on LinkedIn and whatever.
I think that's all terrific stuff, but what I was thinking.
I could hire you guys after not full time.
Anything like that? But I can hire you as part time. Resources, pay you some miniscule amount to at least get it on the books. Your formal as part time resources.
Then you have another line item on your resume that says I did such a good job at my internship. They hired me part time because I was working on these flows and delivering value. That to me is like extra.
Wow, OK. You got hired by them after three months then or four months then.
Of working with stuff and it's only part time.
But yeah, that's I think that's a value add that will be a differentiator.
I mean, I don't know about whether that works for you, Nick or Peter, but I mean for Brian for sure.
That's a great one. I think as long as you can spin it of how did you combine these two things?
Well, ****. I've been combining things all along, right?
I've been combining work and school.
I've been combining school and you know, an internship or the work in the internship, those kinds of things.
And you can say, well, I really the thing was they wanted me so bad. They said I could work on these things whenever it was convenient for me.
So I worked on weekends and whatever else. I just think that's an extra.
It shows something different, not just you did the internship, but you were so valued. You got hired again.
So whether I could do that or not, I'm not 100% sure, but I think I will be able to because I'll just say you guys are adding value for me and I'll pay you out of my budget and.
You know, again small, but just something that shows that you're formally an employee.
Part Time employee and that you would then be legit. Putting that on your resume. Any thoughts?

Nicholas Westburg   1:13:32
Yeah, it's great.

Bryan Wolf   1:13:35
Good morning.

Peter Wolf   1:13:35
Alright, cool.

Nicholas Westburg   1:13:37
One more question for you.

Peter Wolf   1:13:37
So that's where.

Nicholas Westburg   1:13:38
So that document that you sorry that document that you sent us. I wanna say a month ago with all the flows and what not that you're you're brainstorming or whatever that you're keeping track of is that do you have a new Excel sheet where you're storing your thought?

Peter Wolf   1:13:44
Yeah.
Yeah.
Yeah.
Yeah.

Nicholas Westburg   1:13:54
Like your your workflow ideas and.

Peter Wolf   1:13:55
So, to be honest with you, I've got it in a chat and because I haven't created the flow that would let me store that yet, I'm doing it manually.

Nicholas Westburg   1:14:03
Yeah.

Peter Wolf   1:14:04
Which sucks.
I that's why I really want him to go do those on the flows because as much as they might not seem important to you guys are valuable to me.
They are legit.
I need them right now.
It's causing me inefficiency because I don't have them and I know that it wouldn't be hard for him to build what I'm looking for right now.

Nicholas Westburg   1:14:19
Yeah.

Peter Wolf   1:14:22
I got to go back into the chat and I constantly ask to chat.
Updated spreadsheet. The problem is when it goes back it makes adjustments and it's like oh, it forgets stuff.
I'm like guy.
We were further along on this.
It got to go back.
Double check. Now it's got to bring it back again. If I. If it was being stored in the spreadsheet, I wouldn't be losing the content, right?
And right now I'm having to struggle or work to bring it back up.
But yes, I do have that I haven't.
I haven't pushed much further alone from where I was, but again, these ones that I'm doing right now, right, the news flow is on there.
The company report was on there, the job posting.
Report was on there.
So these are the ones that were on there. I got to go back and look at where I am, what other things I have on there.
I know I have Microsoft versions of those that pulled in again.
Zoom Info pull in Salesforce, use teams for the execution. Those kinds of things.
But I got to look at what other flows I have and I don't have that updated spreadsheet now.

Nicholas Westburg   1:15:17
So quick question, would you be able if you're comfortable sending me the the conversation that you have and I'm I'm sure I could get everything formatted within that, whatever.

Peter Wolf   1:15:25
Yeah, sure, sure.
I'll send you the whole.
Yeah, sure.
I'll send you the whole conversation.

Nicholas Westburg   1:15:29
Whatever conversations that you have, I I've taken time.
I know how to get those out and formatted and all of those.

Peter Wolf   1:15:32
OK.
Awesome, I will. I'll send you.
I'll send you the conversation, no problem.
More than happy to.

Nicholas Westburg   1:15:38
Yeah, yeah. Whatever ones you have, and I'll and I'll and I'll strip all of those.
The I'll strip that, strip whatever conversations you have clean and get all of the the flow ideas and and whatever and what not into to an Excel.

Peter Wolf   1:15:43
OK.
Awesome. Perfect.
Perfect. The other thing that I really want to do, and I think this is a valuable it may not feel valuable, but I'm telling you it's valuable because I know being in business environment, being able to create the process flow diagrams that reflect us. Now I'm using that.
Mermaid and it's pretty basic.
And actually I'm not really impressed with it because I'm used to process flows that go much more kind of off in different directions.
Send information here. Come down. Come back.
I can show you some basic process flows from processes we do and they're pretty simplistic, but I think taking the the, the, the stuff we have in make and either printing out, cutting the, the the the screens and putting that in document and then defining what each of.
Those steps are we need documents like that. We need documents like that they need to be created one because you're gonna need that in the representation when you wanna be presenting to the world. This is what we did.
You're gonna need documents showing.
What the flow steps are and all that kind of stuff you're going to want to be comfortable talking about those flows. We need to be building those now.
Right now, we're still in the kind of in flux situation, but building those and getting the foundations, they can always be tweak, getting the foundations in there that's going to be something that also is going to take some time. But I think it's going to be really import.
For you, Juan, to remember the flows, understand what were all the logic things you wanted to do and also being able to take.
Really, normally you would do the process flow.
So then you build the process.
We're building the process flow.
Sometimes I'm giving.
I'm giving the overview of what to do, but then we're in the details, really changing it.
Then we need to capture that information back out to say hey, here is what the process flow is. I think that's a critical one that may not seem like it's especially valuable, but I believe it is valuable for you one to understand the processes really well 2:00 to.
Document them so you could be showing outside that you built these documents and built these process flows and you understand them.
And three so that you do better understand exactly what's going on.
Alright, so that's something we'll have to work on as well.
Alright, I got to jump. If you connect back with Len and keep moving forward, Brian, I'm going to give him a couple more things. I'm going to figure out what else I want to give him tonight to keep him moving.
And since we're out on Friday, I, you know, I'm still going to be paying him.
I want him to.
I want to have stuff for him to push forward on, so hopefully I'll get him to bang out a few more flows.
If he's not spending the time, you know the two hours on Friday.
For for kind of working with you or you guys, OK.

Bryan Wolf   1:18:26
Yeah.

Peter Wolf   1:18:28
Alright guys, thanks.
Talk to you and Brian.

Nicholas Westburg   1:18:31
Thank you.

Peter Wolf   1:18:31
Remember to give him.
Give him the list.
Give Len the list right of those job postings.

Bryan Wolf   1:18:34
So let's what do you mean? What? What list?

Peter Wolf   1:18:36
The job postings.

Peter Wolf   1:18:36
To you brother C Nick.

Nicholas Westburg   1:18:39
See you guys.

Bryan Wolf   1:18:39
I remember you saying that, but no, I forget.

Peter Wolf   1:18:40
Earlier, earlier in the meeting, I told you that you needed to extract the the the list of job titles that I want to be searched.

Bryan Wolf   1:18:41
So long.
Yeah. From the transcript. Yes. OK.
Alright. Bye bye. Yeah.

Peter Wolf   1:18:50
Yeah, that's it. OK, bye.

Bryan Wolf   1:22:01
How many mothers?
All right, good.

Lem   1:23:45
Hi, Brian.

Bryan Wolf   1:23:46
So how's it going?

Lem   1:23:47
Hello.
Yeah, all good.
Yeah, I started building this the new flow.

Bryan Wolf   1:23:56
Good job one. The one that we did yesterday or the one he was just talking about.

Lem   1:23:57
So.
Yeah, I would need to update this one also because I I think I would, yeah. Add another route for the one.

Bryan Wolf   1:24:04
And so I know he was.
He was talking about the job titles.

Lem   1:24:10
With.
Yeah.

Bryan Wolf   1:24:13
And I'm needing a chance to write him down so I can't get him to you until after, like, the call ends. And then I get the transcript, and then I'll go through.

Lem   1:24:19
OK. Yep.

Bryan Wolf   1:24:21
I'll find him and then I'll shoot you an e-mail with that.

Lem   1:24:24
OK.

Bryan Wolf   1:24:26
Man, that's really all I said, I think.

Lem   1:24:27
But.
Yeah, I've also.

Bryan Wolf   1:24:30
For that.
I'll pull up my make.

Lem   1:24:34
OK.
OK.
No problem.

Bryan Wolf   1:24:38
Do you wanna send?
Do you wanna send the one that you were show this morning or you're just gonna wait until you work tomorrow?
What do you wanna do?

Lem   1:24:50
Yeah, because.

Bryan Wolf   1:24:51
Because I still have this one from yesterday, so I can still keep playing around with it.

Lem   1:24:55
Yeah, I I can send you the like the complete one.
But yeah, basically I would still edit this one for.

Bryan Wolf   1:24:59
Yeah, be great.
It's the same though, right?

Lem   1:25:05
The.

Bryan Wolf   1:25:05
You're just adding to it. Is what you're saying.

Lem   1:25:08
Yeah, I will.

Bryan Wolf   1:25:09
Yeah, yeah.

Lem   1:25:10
Yeah, I'm creating the other one the job posting and then I would.

Bryan Wolf   1:25:13
Mm hmm.
Uh.

Lem   1:25:17
I would add another route here.

Bryan Wolf   1:25:19
That's what we did this morning, right?
We did this morning job posting.

Lem   1:25:24
Yeah, the.

Bryan Wolf   1:25:26
Is that the one that you showed?

Lem   1:25:28
No, no, that that was the complete.

Bryan Wolf   1:25:30
Research company.

Lem   1:25:31
Yeah, the research company and then, yeah, basically.

Bryan Wolf   1:25:34
Can you so send me that one? And then?

Lem   1:25:37
OK.
No problem.

Bryan Wolf   1:25:38
You can just work on the other one.

Lem   1:25:40
Let me just.
Shared screen.
Yeah, I'll. I think I can.
Yeah, I'll send this to you.
Not sure if I've read the yeah I'm not.
I haven't download this yet, so yeah, this is the. Yeah, this one.

Bryan Wolf   1:26:02
Yeah, this is the one.
I'm sorry, this is the one I saw this morning.
This is research company. Yeah. Yeah, that this isn't job posting, right? No, no. OK.

Lem   1:26:06
Yeah, the research company.
Yep, but yeah, this is actually already finished.
I will just.
Yeah, edit it one and let me just send you also the.

Bryan Wolf   1:26:12
So this.
Sheet of.

Lem   1:26:19
Oh, right.
Yeah, this won't work, I think because we've added the column.

Bryan Wolf   1:26:21
Yeah.

Lem   1:26:25
Let me just quickly add it.
Not sure if it's the. Yeah, it's still on C OK but.

Bryan Wolf   1:26:28
That's great.

Lem   1:26:38
Can you see? See my screen or OK OK.

Bryan Wolf   1:26:40
Yeah. Yeah, I can see him.
I'm looking.

Lem   1:26:42
OK.
Yeah. So let me just do it this for now.
And yeah, let's go back here because.
This would be like a different.
Start research.
True job posting.
Yeah, this should be the status not equal to process.

Bryan Wolf   1:27:04
OK.

Lem   1:27:06
And then this one.
So just rename.
Add that to.
Where sheets.
Uh share link.
Processed.
Alright, to refresh this one.
So.
Yeah, the status should be here.
Said you ID.
The.
The process be here.
The company report.
And then.
Company website should be.
This one.
Gbs.
And then.
Company name alright.
Just a company name e-mail.
OK.
I think that's good.
Let me just export this.
So K and then.
I'll share the link.
Umm.
Downloads.
OK. And then this is the spreadsheet.
OK.
Then yeah, we could just.
Duplicate this one and Yep then try.

Bryan Wolf   1:29:18
Let's go.
I can just try to go to go to the transfer, we're going to send you the job thing.
And then I mean that's all I have to.

Lem   1:29:25
Alright.
Yeah, you would need to.
Yeah, create the prompt.
So you will need to.

Bryan Wolf   1:29:33
Create the prompt for which one.

Lem   1:29:34
Write it.
Because this design is actually the prompt of perplexity is coming from a document.
Because, yeah, Peter wanted to like.
Edit The prompt coming from the document, not on here on make. So yeah, actually.

Bryan Wolf   1:29:53
OK.
So I gotta make a good doc with the prompt in it.

Lem   1:29:58
Yeah.

Bryan Wolf   1:29:58
You talking about the?
You're talking about the sheet that he has, the one that we went through yesterday where I know what you're talking about. Like you're talking about.

Lem   1:30:05
Yeah, the yeah this prompt.
So basically the prompt is. Yeah, yeah, this one.

Bryan Wolf   1:30:09
Which, yes. Yeah, yeah, yeah.

Lem   1:30:11
So let me just I think I'll just share this.
And so that you would also.
Just can duplicate this one and then.

Bryan Wolf   1:30:20
Did you send this to Mary?
Yeah, copy this. And then so wait, what did you change?

Lem   1:30:23
Yeah, I I haven't send it.

Bryan Wolf   1:30:25
What's what's changed about it?
How would I robust I figure?

Lem   1:30:28
This one.

Bryan Wolf   1:30:30
Yeah.

Lem   1:30:32
One it's I think I've.

Bryan Wolf   1:30:33
The same.

Lem   1:30:34
Yeah, it's actually it's the same.
I just added some like wordings like detailed executive summary and then yeah, you could just, yeah.

Bryan Wolf   1:30:42
He just wanted to pull it from docs instead of the actual OK.

Lem   1:30:45
And then yeah, that's right.
So instead of, the prompt is already like coded here like it's being put inputted here.
So it the just stuck.

Bryan Wolf   1:30:52
So what's in there?
Nothing is just, it's just, oh, OK company.

Lem   1:30:55
Yeah, like this company name.
And then the prompt is coming from the like the document, yeah.

Bryan Wolf   1:30:59
OK. All right. He's here though.

Lem   1:31:02
The Yep.
Then yeah, I think that's it.
And then the e-mail I just you could just edit the e-mail and then forward this one also I think.

Bryan Wolf   1:31:07
Yeah, let me just check your account.

Lem   1:31:12
Yeah, because we need the Google Drive connection for to to edit the access for, yeah.

Bryan Wolf   1:31:13
Which one?
I know, but remember mine is like I gotta.
I have to contact Google. I figure it out, but I'm gonna be doing some Peter's things. So.

Lem   1:31:23
Yeah.
OK. But yeah, you could still bypass this one.

Bryan Wolf   1:31:26
OK.

Lem   1:31:29
It's just if.

Bryan Wolf   1:31:31
I just don't need it.

Lem   1:31:32
Yeah. If we bypass this one, you would need to change the like the.
Link here so this the the link would be coming from this one web view link. So the the difference of yeah the difference is for example this one right.

Bryan Wolf   1:31:39
OK.
OK. All right.

Lem   1:31:50
Is this is like the coming from the web view link. So this this link is like a restricted on the owner.

Bryan Wolf   1:31:54
Yeah.
OK.
That's alright.

Lem   1:31:58
But this? Yeah, this drive drive that Google is. Yeah, is for everyone.

Bryan Wolf   1:32:02
It's for everyone.

Lem   1:32:05
So anyone with the link can open this one.

Bryan Wolf   1:32:05
OK.

Lem   1:32:08
So yeah, but actually this would be like already emailed to the person so they could also access it via e-mail actually.

Bryan Wolf   1:32:08
Mm hmm.

Lem   1:32:18
So for example this one.
So this one is, yeah, already like like a.

Bryan Wolf   1:32:20
That was good.

Lem   1:32:25
Not public, but because this was downloaded from here, downloaded and then sent as e-mail. So this is actually already an attachment, so.

Bryan Wolf   1:32:28
Uh huh.
OK.
All right, great.

Lem   1:32:33
Yeah.
Yep. And then.
Yeah. So.

Bryan Wolf   1:32:39
It's good.

Lem   1:32:41
Yeah, basically I'm. I'm first building like the the web book.

Bryan Wolf   1:32:43
What about the webhook?
And which one are you going?
And you keep going.
This post job this is this is what he told you, OK?

Lem   1:32:51
Uh.
The for the web book. Yeah, it's just one web book there on the Google Apps script, yeah.

Bryan Wolf   1:33:02
Oh, right.
OK, OK.
Let's just see I remember.
Yeah, yeah, yeah. OK.

Lem   1:33:05
Yeah. So it's just this is, yeah, different because it's only one.
So yeah, we have.
Yeah, only one here. So this one will be the web hook. And then. Yep. And then yeah, it's it's the same. All of all of it will be the same.

Bryan Wolf   1:33:25
Mm hmm.

Lem   1:33:26
And.
Yeah. So, yeah, for this? Yeah, I think we need to think about the route because basically this would create the job post and then I would edit the other flow that it will.
Do this.
Add another route in Delhi.
Yeah, it will edit this particular document.

Bryan Wolf   1:33:51
OK.

Lem   1:33:52
And.
Basically, if it would add it, I know actually it would be here.
Yeah, it will create the document here I think.

Bryan Wolf   1:34:00
Mm hmm.

Lem   1:34:03
And then.
Yeah, I'm still thinking about the logic for this one because yeah, but basically for the scraping this I found like a good scraping.

Bryan Wolf   1:34:10
Oh, that's OK.
OK.
Nice, it says on apple pie.

Lem   1:34:20
Actor in indeed, yeah.
And then it's actually it's actually picking up the SAP job titles, so.

Bryan Wolf   1:34:26
Oh wow.
Yeah, it is.

Lem   1:34:29
So SAP finances this one.

Bryan Wolf   1:34:29
Nice.

Lem   1:34:34
Then yeah.
And then this is from Accenture.

Bryan Wolf   1:34:36
That's perfect.

Lem   1:34:38
Yep, this is actually good SAP finance from Fujitsu, Yep.

Bryan Wolf   1:34:41
Yeah.

Lem   1:34:42
Then yeah, we could add here the.
Add.
Like the keywords. So I'm using here this one SAP finance for the Curie and then SAP Treasury.

Bryan Wolf   1:34:57
OK.

Lem   1:35:00
So yeah, we could just add this one add.
When I get the link, I will just add it here on the.
All right, here on the this one, so I'll add.

Bryan Wolf   1:35:13
No.

Lem   1:35:16
Like the keywords, SAP, finance, SAP, Treasury or other one SAP cash management. Yeah. And then, yeah. Then I'll. Then you would have like a filter here again for SAP. So that the other one because it's actually catching also other other like other jobs that doesn't have SAP. So.

Bryan Wolf   1:35:19
Yeah.

Lem   1:35:37
I'll add a filter and then yeah, it will search for duplicate.
So when the company is already.
In the spreadsheet, it won't pass through.
So I've added like a filter and then.
Yep. And then this one would create.
The like the.
Comprehensive job posting. I'm not also too sure about this one. Yeah I would.
Maybe tomorrow I'll just play around this for now because I'm.

Bryan Wolf   1:36:13
What the HTML is there are the input right there.

Lem   1:36:15
Yeah, I mean the like the structure of the like the job post document.

Bryan Wolf   1:36:19
Yeah.

Lem   1:36:20
So I'm not too sure on I guess.
Yeah, I added this simple prompt.
I create a comprehensive job posting document based on the information.

Bryan Wolf   1:36:26
Yeah.

Lem   1:36:29
Then I've. Yeah, I've added like the company name, job URL, salary.
Job details so the job details also is like a yeah, I think it would.

Bryan Wolf   1:36:38
That's good enough.

Lem   1:36:43
Yeah, I'm still testing this one.
So let's try it for like 1.
If it outputs like.
Then yeah, I think I would add this.
Same flow.

Bryan Wolf   1:37:08
Alright, like right after them.

Lem   1:37:10
Yeah, right after them.
And then I I will add.
Yeah, I will like edit the document and add the because Peter also wanted to like.
Add.
Alright, just yeah, just a job posting report here.
And also yeah, so that's that's good.

Bryan Wolf   1:37:32
OK.

Lem   1:37:34
Yeah, let's just.
Check this out.
If.
It's good.
The company, what the role is actually good.
Yeah, your responsibilities, your cards, skills and going.
Yeah, this is good, right?

Bryan Wolf   1:37:58
Yeah.

Lem   1:38:00
With the.
With the flying, yeah.

Bryan Wolf   1:38:02
That looks good though.

Lem   1:38:03
So it actually created.
A.
Yeah, we just need to like.

Bryan Wolf   1:38:07
Format a little more.
Yeah, that looks pretty good.

Lem   1:38:11
Can you invite to sender CV to HR headset Sir?

Bryan Wolf   1:38:15
Mm hmm.

Lem   1:38:16
Yep.
Company location.
I wonder why?
I did this.
Yeah. So actually I've this is like a different like a prompting style.
So in the past, right?
Like we have.
For the format, yeah, for the format.
So in the past, like we had like like a fixed format.
On the newsletter process flow, so as you can in the past we added.
The fixed formatting here, but for this one I actually like a different different style.

Bryan Wolf   1:38:56
OK.

Lem   1:39:01
So basically I've added this prompt 1st and then I've provided an example.
So like this one is like an input data example.

Bryan Wolf   1:39:10
OK.

Lem   1:39:10
And then this is like the output. So as you can see here this is.
User. So the role is user and then the role for this one is assistant.
So basically this is what I we inputted and then this is the output.

Bryan Wolf   1:39:22
OK.

Lem   1:39:26
So this is like a sample sample input and output and then the last here would be user.
So this is like the input data again.
And yeah, it will output same as this one.

Bryan Wolf   1:39:39
OK.

Lem   1:39:39
So the difference of this is the result would be dynamic, so it won't be like fixed as like like the newsletter flow.
So the newsletter flow was like fix HTML right?

Bryan Wolf   1:39:52
Yeah.

Lem   1:39:52
But for this one it would depend on the output of like perplexity.
So sometimes perplexity adds a table.
Or like it, it doesn't have like a bullet list so.
It actually the formatting here would be different per document.
So yeah, that that's one thing also there because I cannot put a fixed fixed like a fixed.
Formatting here because yeah, the perplexity has like different formattings on whenever you research per company. So per company there's like a different format.

Bryan Wolf   1:40:27
Yeah.

Lem   1:40:29
So yeah, that's why I've added that particular design.
So it's not like the fixed HTML formatting. Yeah, but.
I can also actually see it. I think there's some like the other ones has like table distance and that one, yeah. Basically the other ones have like.
Yes, as you can see, they have like a different formattings for documents of like little differences, yeah, so.

Bryan Wolf   1:40:55
All right, so are these ones that you just ran like last night or something?

Lem   1:41:01
Yeah, yeah, this.
Yeah, I run this a while ago.

Bryan Wolf   1:41:05
No.

Lem   1:41:06
While I'm testing.
So yeah.
So yeah, for example this one has lines, so the other one doesn't have lines.
So yeah, it's because the the output is dynamic and it's not fixed.

Bryan Wolf   1:41:13
Yeah.

Lem   1:41:18
It's. That's why.

Bryan Wolf   1:41:18
OK.

Lem   1:41:19
But yeah, basically it's just a formatting, but like the the content here is coming from perplexity so.
That's that's fine.
Yep, and yeah. So I think that is also what I would do here on.
Like the.
Yeah, I think that's I what I will do here also with.
With I think I'll just feed this into ChatGPT and then.
Feed this as as an example also.

Bryan Wolf   1:42:08
John.

Lem   1:42:12
So for example, let me just get the input data.
So the in.
So this was the input.
Alright, we have that.
Yeah, job reference this one.
OK.
So try to feed this to ChatGPT and let it create.
Let's say.
Yeah.
Create a.
And so it's probably use here.
Create a comprehensive.
Showboating document.
For the data below in HTML format.
In simple HTML format.
For Google.
Go doc.
Then I'll paste the input here.

Bryan Wolf   1:43:41
Thanks.

Lem   1:43:44
Umm.
Yeah, I think this is much better because the other one is.
Using this yeah, the CSS with all the. I think this is much better.

Bryan Wolf   1:43:53
Just looks all messy.
OK.

Lem   1:44:08
Let's check it.
Yeah, I think.
Yeah, this much simpler and company name.

Bryan Wolf   1:44:18
Yeah, it looks locally for sure.
This, that's the newer version right on the right.

Lem   1:44:23
Yeah.
So I think it's much better for this to be the link.
Just the link.
And then.
Yeah, I think this is much better in the description.
Get responsibilities.

Bryan Wolf   1:44:46
And what is this?
Is HTML online viewer. This is like.

Lem   1:44:49
Yeah, this is the yeah, the HTML online viewer so that I can like we could.

Bryan Wolf   1:44:53
This is great.

Lem   1:44:54
Yeah, we could easily see the output without like, Yep.

Bryan Wolf   1:44:56
So Lem, this, this, this like whole browser that you have.
You know how, like my, I brought it before like you have all that stuff on the left hand side like you've got all your tabs.

Lem   1:45:06
Yep.

Bryan Wolf   1:45:08
Is that?
That's only because this is a Mac or.

Lem   1:45:11
Nope, this is arc browser.
You can actually download this.

Bryan Wolf   1:45:15
Art browser.

Lem   1:45:15
Yeah, this is arc browser arc. Then I use this one.

Bryan Wolf   1:45:17
OK. Yeah.

Lem   1:45:20
Yeah, basically because I use this for actually for like the space they have like the different spaces.
So if I go to another space all the like the logins would be different.
So for yeah, for example this this make.

Bryan Wolf   1:45:32
Yeah.

Lem   1:45:36
Is mine and then for this one it would be like another make account.

Bryan Wolf   1:45:40
I know I'm not OK.

Lem   1:45:41
Yeah. And then like the e-mail something.
Yeah. So it's because if I use like Google. Like. Yeah, yeah. If we usegoogle.com like all the gmails mix up like the emails and all the. Yeah.

Bryan Wolf   1:45:46
Down there at the browsers here.

Lem   1:45:54
So it actually makes up.
So yeah, this pretty it's actually good.
Good.

Bryan Wolf   1:46:00
I download that.

Lem   1:46:02
Uh.
Intersection. So I think I would remove this one.
Just remove the addressed candidates.

Bryan Wolf   1:46:09
I'm going to be talking back.

Lem   1:46:13
Yeah, I think this is good.
So I would.
Yeah, what?
I will do.
Here is I would paste this as the output so that it's like a.

Bryan Wolf   1:46:24
The one that you just got from GBT.

Lem   1:46:26
Yeah, that's right.
So it would be like a example. So I would add here.

Bryan Wolf   1:46:28
Yeah.

Lem   1:46:32
On the add message like the first user.

Bryan Wolf   1:46:34
No. Yeah.

Lem   1:46:36
So.
I would.
And then.
The assistant.
So this would be like the output and then for the input. Let me just copy this one.
Input.
And then I did this one to the.
One in.
So.
So this should be.
Let me just.
Before I forget.
So that, yeah, this one.
So we could actually drag this below because this should be like the last one like the input.

Bryan Wolf   1:47:26
OK.

Lem   1:47:27
This one, the yeah. Then this would be like the sample input.

Bryan Wolf   1:47:27
Yeah.

Lem   1:47:32
This is from the user sample input and then from the AI sample output.
Then you could just feed here like the.
Company name other I think I can get this one below. So let me just.

Bryan Wolf   1:47:45
No.

Lem   1:47:57
Yeah. So.
Posting.
This.
You're a dumb *****, dumb *****.
Owner down to me.
So WRL for example this one.
Dot URL company name.
Or this one.
And salary.
So.
Turn this on.
Then.
I think it's USD right now.
Let me just check here. Yeah, USD.
Then.
For the.
So yearly.

Bryan Wolf   1:49:12
Which one, OK?

Lem   1:49:12
The engine and then job details.
I'll copy all the job details that is coming from here so.
Just get.
The subscription decks in this one.
Then feed it to chat GP. So this would be like yeah, the example and then it will get the context and create.
Something like this?

Bryan Wolf   1:49:49
So it's a cheaper when you drive over there and you pick it up.

Lem   1:49:50
And.
Yep.
Go on details.

Bryan Wolf   1:49:54
In Jerry Hills, you're going to get a instant cart from Costco down to there.

Lem   1:50:01
Job description.

Bryan Wolf   1:50:03
It's not work today like to revise the chicken, the mat, the chicken.

Lem   1:50:04
I don't think this is.

Bryan Wolf   1:50:07
Oh, you see, for me to breakdown.
Yeah, Barbara. OK.
Go ahead.
OK.
So I I can get more of those I can get.

Lem   1:50:16
Show details.

Bryan Wolf   1:50:20
You are so smart.
And if you don't mind just putting in the fridge for me, just in coffee boxes.

Lem   1:50:24
Information.

Bryan Wolf   1:50:31
I'll be back any time you want me.
Awesome. Your son's on the phone computer, and I'm going to service over here. Hang on.

Lem   1:50:37
Yep, I think that's good.

Bryan Wolf   1:50:42
OK.
Yeah, goodbye.

Lem   1:50:47
Create.
Shop posting.
Document.
Then let's try to.

Bryan Wolf   1:50:59
Yeah.

Lem   1:50:59
Yeah, feed it to.
So let's change this one to.
Job post.
With.
Yeah, I think we could pull out the company name here.

Bryan Wolf   1:51:21
Right.

Lem   1:51:22
Yeah. So this one company name.

Bryan Wolf   1:51:24
Good.
OK.

Lem   1:51:30
The date and the the content will be coming from ChatGPT.

Bryan Wolf   1:51:34
So it's yeah, OK.

Lem   1:51:38
Yep. Then now, yeah, we could try this one out.

Bryan Wolf   1:51:41
Thank.

Lem   1:51:45
Uh.
The only thing here is.
Let me just.
Add some rules here.
Only output the extra.
Uh, do not change the content.
Alright, this is not.
Do not output, do not put.
See.
Is that?
I think it's like.
A.
Why not put?

Bryan Wolf   1:52:44
OK.

Lem   1:52:46
Yeah, because it's actually like adding this like weird HTML tag on the. Yep.

Bryan Wolf   1:52:49
Yeah.

Lem   1:52:52
So let's try this on maybe like to.

Bryan Wolf   1:52:57
OK.

Lem   1:53:05
Then add it on the.
Hmm.
On the clear.
Document.
And uh.
Let's check out the output of this one.
So.

Bryan Wolf   1:53:36
Alright, there we go.

Lem   1:53:38
Well, it's actually, yeah, it's still adding like the.

Bryan Wolf   1:53:42
Where what I'm saying.

Lem   1:53:44
Yeah, weird caller.

Bryan Wolf   1:53:46
Yeah.

Lem   1:53:49
That's odd.

Bryan Wolf   1:53:52
Yeah.

Lem   1:53:57
Oh, so this one.
Company.
Yeah, we need to.
I need to adjust the prompt here.
Because.

Bryan Wolf   1:54:14
OK.

Lem   1:54:18
Yeah, it's getting confused with the headers and stuff.
Think this should be.
It's OK job posting.
And then.
Yeah, this is the problem.
And like the.

Bryan Wolf   1:54:52
Wherever that's that says right there, that's the correct style, right? The right there top.

Lem   1:54:54
The.
Yeah, but yeah, but the output is like, yeah, it's different because we didn't add like.

Bryan Wolf   1:55:01
He's just not picking up.

Lem   1:55:07
Like a fixed structure.
So it's just basing the HMO format here and then depending on the information, so it's actually adding like different formats.

Bryan Wolf   1:55:09
OK.

Lem   1:55:19
So I think I would.

Bryan Wolf   1:55:20
Hi.

Lem   1:55:21
Yeah, I would prefer because the I would prefer the fixed HTML because.

Bryan Wolf   1:55:28
Yeah.

Lem   1:55:29
Yeah, I think it would work here because Appify has like a the same we we would be having like a a uniform.

Bryan Wolf   1:55:38
Perfect. Say yeah.

Lem   1:55:39
Yeah, uniform input data.
So basically it's the same like.

Bryan Wolf   1:55:41
It all effects. Yeah, yeah.

Lem   1:55:43
Yeah. So it's much better to make this fixed. So I think I would like, yeah, I would create one for creating the job, posting document and then other one for form.

Bryan Wolf   1:55:54
OK. The second one for format, yeah.

Lem   1:55:57
Yeah, for formatting.
So I think that would be because, yeah, here I just added all the like the creation of the document and also the HTML formatting.
So I think that's why it's getting.
Kinda confused.
Umm.
Yeah, but basically this would be I think it would be.
Odd, yeah.

Bryan Wolf   1:56:36
Why he's not?

Lem   1:56:37
MMM.

Bryan Wolf   1:56:39
Oh, look, that one's good. Look.

Lem   1:56:39
And yeah, the header is messed up.

Bryan Wolf   1:56:43
What the color is going on and?

Lem   1:56:48
So the header should be here.
Oh.
Yeah, but the outputs actually good.
It's just that.
Yeah. And also this one should.
Yeah, basically remove the.
Send your resume something.
But the link is.
Think the link would work.
Yeah, the link is working, so that's good.
Task manager. So I think this is not.
Like a finance, right?
So.

Bryan Wolf   1:57:37
I should put it for the job done as I need to get you. Where would I put them in the?

Lem   1:57:39
Yeah, I.
Yeah, I think we could.
Yeah, we could add like a filter here.

Bryan Wolf   1:57:48
Here.

Lem   1:57:51
That with each, let's, say, finance, and then we could add.
Or say title is also like.
SAP Treasury, something like that.

Bryan Wolf   1:58:02
Mm hmm.
OK, OK.

Lem   1:58:04
So yeah, I'll I'll just filter it out.
Add some filter there.
Yeah.
Huh. Why did it pass through?
Contains ASAP finance.
Uh.
So I.
Maybe it's just the SAP.

Bryan Wolf   1:58:36
Mm hmm.

Lem   1:58:45
Yeah, it's true. It's true.
So the.
Also this one SAP, we think.
The SAP is only.

Bryan Wolf   1:59:08
It just says center right now.

Lem   1:59:10
No, it's only filtering out the SAPI.
Think. Yeah, I can just fix that out.
But yeah, so I think this would be better if.
This just creates the document and then.
Yeah.
Just read to our person, Joe pressing down based on the information provided below. So for example this one.
And then.
Yeah.
Clone this one.
And.
Information info, right?
Just delete this one for now.
So assistant OK.
Turn on brand SIV.
OK.
Alright.
Yep, that's wrong.
That should be.
Let me just test this.
It should be this one so.
Start there.
OK.
Uh.
Required.
Yeah, do not include how to apply.
You're not into.
How to apply?
Section.
Of.
Yeah.
Yeah.
Yeah, I think this is good.

Bryan Wolf   2:03:01
OK.

Lem   2:03:03
Yeah.
So what I'll do here is.
Feed it as an example.

Bryan Wolf   2:03:16
How do you do that?

Lem   2:03:18
So that it would be fixed also so.
Let's copy the.
I think I'll just.
To input.
Stop, put.
Then start.
Listen output.
Then input data would be.
And I'm just.
Connect it first.
Just copy the.
And this one.
Then now we have the yeah.
K.

Bryan Wolf   2:05:00
Pardon.

Lem   2:05:02
So.
Just check if.
Yeah, so basically I've added like the.
Example so same as the design a while ago.

Bryan Wolf   2:05:18
Uh huh.

Lem   2:05:20
So this is like the example input input data.

Bryan Wolf   2:05:26
Yeah.

Lem   2:05:26
Then yeah, this is the output.
Then at the last one, the dynamic 1 coming from the.
Yeah, coming from the data.
OK. And then yeah, I will add another.
Formatting here.
So.
Yeah. And I think we would use here like a fix.
A fix one.
Yeah. So.
Yeah, I think I will do something like this.
Description.
OK.
Pharma thing, but they had to start showing for my for them better.
Section of contention containing the very simple.
Data.
I'll just do it this one.
So let's make it fixed one.
Yep, the data.
This this one.
That what should be like this.
So.
So this would be the title.
Job posting.
Uh.
Put the title here.
Company name. So this one is the same as.
The one in the newsletter flow so.
And Yep, yeah, this. Yeah, I would.

Bryan Wolf   2:08:13
OK.

Lem   2:08:19
The same design so that it would be the HTML would be fixed.

Bryan Wolf   2:08:24
OK.

Lem   2:08:24
Then.
So.
Job URL here.
Sorry.
OK, Sean.
OK.
Check type here.
Experience.
Find.
Change refresh on.
Umm, just check the.
Position our review so it should be the position of review.
Yeah.
Go over.
Then for this one.
Put key responsibilities.
Yeah.
And remove.
Other ones.
I just went through.
The.
Set another one.
Here.
OK.
Required skills and qualification.
So the same.
Quartz kiss and qualifications.
Skills.
Words, skills.
OK.
Requires us to be responsible.
Description and it's just a.
OK.
I think this would be good.
Then just test it out just one.
Just one.

Bryan Wolf   2:12:04
Hmm.

Lem   2:12:06
Content should be here.
OK.
Yeah, I'll just send it to SAP first.

Bryan Wolf   2:12:21
SAP.

Lem   2:12:22
Yeah.
Just add it to SAP finance and treasure in the like when I get the list.

Bryan Wolf   2:12:31
OK.
I'll see you tomorrow.
The list from me.

Lem   2:12:33
Oh.
Yep. Can I? Yeah, just because I.

Bryan Wolf   2:12:37
Yeah. Yeah, I can.
I can only do it after the call 'cause. That's when the that's when I get the video access stuff. I have to get when we're done.

Lem   2:12:41
OK. OK, great.
Oh yeah, it's already 1112. Also. Yeah. I gotta gotta sign off.

Bryan Wolf   2:12:47
I know, I know, I know.
I'm sorry, I'm sorry.

Lem   2:12:49
Yeah, no problem.

Bryan Wolf   2:12:50
Yeah, that's OK. But so I'll e-mail to you and then whenever you get a chance tomorrow, whatever.

Lem   2:12:51
Let's just test it out finally.
OK.
No problem. Yeah.
Yeah, that's. I'll just check this out if it's actually like.

Bryan Wolf   2:12:59
Obviously not the same.
That's the other one. So yeah.

Lem   2:13:08
Yeah. Oh, I think, yeah, we need to.
Yeah, I need to add it this one, but yeah, so this would be, yeah, this would be the pretty the standard would be like a, yeah.

Bryan Wolf   2:13:11
I know it's alright though.
Similar, yeah.

Lem   2:13:21
OK.
I'll just, yeah, I'll, I'll fix this tomorrow.

Bryan Wolf   2:13:22
Alright, yeah.
Can you export this to me?
Oh yeah, you can fix it too. Honestly, before you even.

Lem   2:13:27
Yeah. So it is still not.

Bryan Wolf   2:13:27
That's fine too. That's OK.
Yeah, yeah, yeah.

Lem   2:13:29
Yeah, but.

Bryan Wolf   2:13:30
That's totally OK.
Alright, I'm gonna.
I gotta go through the transcript, but I'll either e-mail you in the next like 30 minutes or, you know by the time you're very sleepy.

Lem   2:13:36
OK, OK.

Bryan Wolf   2:13:38
But yeah, all right, lean. Thanks.

Lem   2:13:39
OK.
OK.
Bryan, talk to you soon.
OK.

Bryan Wolf   2:13:43
You always the best Mary.

Lem   2:13:43
Yeah, yeah, yeah.

Bryan Wolf   2:13:44
I'll talk to you tomorrow too.

Lem   2:13:45
OK. So yeah.

Peter Wolf stopped transcription


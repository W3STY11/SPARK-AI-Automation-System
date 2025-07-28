# Process Automation Workshop (10)

**Original File:** Process Automation Workshop (10).docx
**Extracted Date:** 2025-06-18 (Wednesday)
**Converted:** 2025-07-28 11:40:53

---

Transcript

June 18, 2025, 12:59PM

Bryan Wolf   0:19
Oh.

Lem   1:59
Hi, guys.

Bryan Wolf   2:03
Man, what's up?

Peter Wolf   2:07
Is.
Peter joining.

Bryan Wolf   2:14
I don't know.
I'm just probably working this morning.

Peter Wolf   2:19
Hey, Lam.

Lem   2:22
Hey, hi there. Hello.

Peter Wolf   2:25
Like can you check with Peter to see if he's joining?

Bryan Wolf   2:28
Yeah.

Lem   2:46
So I I've already sent the e-mail for on you guys for the updated Jason Blueprints.
There I also have the link video there and.
Sample Google sheet.

Peter Wolf   3:01
OK.

Lem   3:03
Yep.

Peter Wolf   3:03
Can we will still walk through though.
I'd like to get it on the recording here, OK.

Lem   3:08
Yep, no, no problem.

Peter Wolf   3:08
And another thing I wanted to is.

Bryan Wolf   3:08
Here's Peter.

Peter Wolf   3:12
I wanna check something out.
Can you?
You said you sent the e-mail with the Jason file.
Hold on a second.
Mm hmm.

Peter Wolf Jr   3:32
Hey, sorry for being a little late.

Peter Wolf   3:40
Yeah. So the the you sent 2 files.
So is that there are two different flows?
They were the ones where we said we were gonna do the the the webhook between the two.

Lem   3:52
Yeah, that's right. Yeah, but yeah.

Peter Wolf   3:53
OK.
So let's yeah, go ahead.

Lem   3:56
For this one, I didn't use a web book because we need to like update the Google document for that one.
So yeah, yeah.

Peter Wolf   4:03
Alright, so the trigger is the new is. The is the execution of the Google Doc, right?

Lem   4:09
Yeah, basically, yeah.

Peter Wolf   4:10
Is there anything we talked about, anything that was gonna allow us to say that the next step was the other flow, something that you could put there?
I know the webhook.
You're saying it doesn't really cause if I could do a web hook, I would just as easily put the flow right inside the addition. The existing flow, right?
So there has to be a disconnect there.

Lem   4:29
And.
Yeah, because we have the next step right for the editing of the Google Doc.
So that's why I've separated it, because if we put.

Peter Wolf   4:40
Yep, no, I understand why you separated it.
I understand why, but I'm just saying is there OK, bring up the flows.

Lem   4:43
Yeah.

Peter Wolf   4:47
Let's let's look at the flows, Peter.
I don't know if you watched the video from yesterday or not.

Lem   4:53
Uh.
Let me just share my screen.

Peter Wolf Jr   4:58
No, I didn't.

Peter Wolf   4:59
OK.

Lem   5:02
OK.
Yeah. So this is the updated one.

Peter Wolf   5:05
Give it a second.
It's it's blurry.
It takes a second to kind of clear up.

Lem   5:08
Yeah. OK.

Peter Wolf   5:08
There we go.
OK. So I'll I'll walk through.
Just say what I think the steps are, and then you clarify, right? So far left hand side first first bullet we got.

Lem   5:16
OK.

Peter Wolf   5:20
That's the trigger for for Meg to execute or to activate the process, right?

Lem   5:26
Yeah, this one.

Peter Wolf   5:27
Can you drill in a little bit?
Make it a little bit larger so we can.
I know we'll have the we won't fit all in one screen, but yeah.

Lem   5:31
This one.
Yeah, yeah.
So this will trigger every 888 AM, yeah.

Peter Wolf   5:35
This is in.
No, this is the inner reader, right?

Lem   5:38
The inner reader.
Yeah, that's right.

Peter Wolf   5:39
Right, so trigger the inner reader to to grab articles.
You're only using three articles, but we use whatever number we want, right?
We set that it gets the articles and what it's getting is the a summary and and the URL right and then it's searching for duplicates. If it's already got them, it's got duplicates.

Lem   5:47
Yep.
Yep.
Yeah, this one.

Peter Wolf   6:01
It weeds them out.
Right.

Lem   6:04
Yep.

Bryan Wolf   6:04
Oh.

Peter Wolf   6:04
Then then it creates a unique ID for each article, right?

Lem   6:11
Yep, unique ID.

Peter Wolf   6:14
Yep. Uuid so that it can be uniquely identified on the spreadsheet line items and anytime you want to reference individual articles. So it has a unique ID, put them all into the spreadsheet with the unique ID and that's the URL and the summary and the date of the.

Lem   6:20
Yep.

Peter Wolf   6:32
Of the draw or the news article.
I don't remember, but ultimately a date and then put them all into.

Lem   6:38
Yep.
Then put it here on one bundle. Yep.

Peter Wolf   6:42
Put them all into one bundle.
Yeah, no, this is.
This is after selection right at the OR do we have a selection?

Lem   6:50
No, this is the selection part.
The ChatGPT will choose the top three articles or top five articles from the.

Peter Wolf   6:56
OK.
So we could have had twenty articles, fifty articles, whatever, and then they all fifty of those they're sent in now in the analysis here, it's only analyzing the summary. It's not going looking at the full articles.

Lem   6:59
Yep, that's right. Yep.
Yeah, it's only gonna analyze the summary for that is coming from.

Peter Wolf   7:10
It.
Right, based on the summary that was provided by inode reader and and also in the in the in that step back there if it didn't have a summary, you cut it out, you dropped it.

Lem   7:15
I know reader.
Yep. Yeah, that's right.

Bryan Wolf   7:21
It.

Lem   7:24
Yeah, this one, yeah.
So there's a filter. If there's no summary, it won't.

Peter Wolf   7:26
Yep.

Lem   7:28
Yeah, it will drop.
Yep, that's right.

Peter Wolf   7:30
OK.
So now we feed that all into chat G BT and ChatGPT picks the three and again we set whatever number we want but it picks the three that are most relevant to fit the the the criteria.

Lem   7:35
Yep, here.
Yep.

Peter Wolf   7:45
Now in that feed we gave it an additional prompt, right?
A supplemental document to the prompt or no.

Lem   7:53
No, for for this one I just added like the past prompt like this one.
So for more context and treasury finance thought leader.
But yeah, you could actually like add your like some persona here or the one specific that you want.
But yeah, it's actually basing only for this one.

Peter Wolf   8:11
OK, so for right now we don't have a we don't have a document. If we wanted to add a document that was stored 'cause. I know we do that when we're prompting like for the individual.
News article to LinkedIn Post we we are including the Persona DOC or supplemental documents, right?
So in that model, do you have to put another step or do you just put something in there to, say, grab a document and bring it with me?

Lem   8:31
Yep.
Yeah, I I need to put another step.
But if we use actually anthropic cloud, it can actually.
Like if it's on anthropic cloud, we have, we will be able to put a file here.
So oh, it's not connected to the sound, but yeah.

Peter Wolf   8:57
But what if I want the file to be dynamic again?
I want the file to grab from the drive just like we do with the personas. I wanted to grab from a drive.

Lem   9:04
Yep.
Yeah. So basically we would have another step here, which is it will get the document like the content of the document like the persona and then it we will feed the content here to ChatGPT.

Peter Wolf   9:15
OK.
Yep.

Lem   9:19
Yeah. So it will add that.

Peter Wolf   9:20
OK.
I'd like to add that right.
I want to add that because even if we don't grab a document, if there is no document then it should just continue on right?

Lem   9:30
Yeah.
It will.
Yeah, it will just continue if there's like no document here, but.

Peter Wolf   9:37
So let's add that step.
Let's make a note specifically that we want to add this step for for supplemental document that's fed with the prompt.

Lem   9:46
Yep.

Peter Wolf   9:47
OK.
That'll give more contacts more information because that's where I was talking earlier.
We I created a prompt that said, you know for newsletter. I want 70% strategic or 60% strategic, 40% operational.
So that should be included in the in the ChatGPT assessment of what should be.
Should be what should be highlighted as the chosen articles.

Lem   10:10
Yep. Yeah, that's right.

Peter Wolf   10:10
So it's important, OK.

Lem   10:11
So yeah, we could just add another step here and then we could edit the, yeah.

Peter Wolf   10:16
Great. So can you make it?
Will I put it here as a follow up in these in the notes coming from this but a follow up is to add a step to supplemental document between the bundling of the article, some of the article summaries and Url's and the ChatGPT call for.

Lem   10:23
OK.
Yep.

Peter Wolf   10:37
The selection of what's going to be included.

Lem   10:41
Yeah, basically it would be this one.
Get content of a document and then you could just add the document ID here of the particular document.

Peter Wolf   10:48
And the menu and the path of where it is, right or.

Bryan Wolf   10:50
Alright.

Lem   10:52
Yep, and then it would just get the the content for that particular document.
Then if you added that one.

Peter Wolf   11:00
But I'm saying we would identify where the document is, right? Google Drive.

Lem   11:04
Yeah, basically we would, we would identify the document ID.
So what I do there is I go to the Google Drive.
Actually, I think we could.
Yeah, we could actually just choose it via drop down because this is actually static.

Bryan Wolf   11:18
Yeah.

Peter Wolf   11:19
There you go.

Lem   11:21
Yeah. So we could just choose here the let's say that particular persona.

Peter Wolf   11:21
Yeah.
OK, with that particular document, which will be supplemental selection criteria, newsletter supplemental selection criteria, so it doesn't exist now, but we would put something.

Lem   11:28
Yep.
Yeah, that's right. Yep, Yep.

Bryan Wolf   11:30
Yeah.

Lem   11:33
So that's for example, Yep. So for example this one I've just added for testing and then we would add this the content the text result here I mean the text content here to ChatGPT, so let's let's say.

Peter Wolf   11:39
Yep.

Lem   11:52
Here so I will let yeah for the context we would.
I will also add my like Persona and preferences.
To post on.
Your side persona, Princess.

Peter Wolf   12:13
That's fine.
We can refine that.
Just say I'm at my persona and preferences.

Lem   12:14
Yeah, like that. And then yeah then.

Peter Wolf   12:17
Yeah, that's fine.

Lem   12:18
We'll just add the persona here.
So the text content, so it will actually add that long depending on the content from the document it will add on the prompt.
So this is actually dynamic and if you added the document so it will also edit the prompt here on ChatGPT.

Peter Wolf   12:36
Very awesome.

Lem   12:37
Yep, so.

Peter Wolf   12:37
So guys, do you see that 'cause I I don't know if Brian, if you've been playing around with it?

Bryan Wolf   12:39
Yes. Yeah, that's it.

Peter Wolf   12:42
No, I meant the way he's grabbing the, you know, he goes to OK 'cause that grabbing and just making sure for for Pete.

Bryan Wolf   12:44
Yeah, yeah, yeah, that's yes, yes, yes, yes.

Peter Wolf   12:49
Like what we determined yesterday, Pete, and I think it's important difference is one step doesn't push to the next step. It's the next step. Pulls from the previous step.

Lem   12:57
Yep.

Bryan Wolf   12:59
Mm hmm.

Peter Wolf   13:00
So like the output from that Google Doc that he's got on the left hand side, the blue dot that doesn't push.

Lem   13:00
Yeah. Yeah, that's right, yeah.

Peter Wolf   13:05
Push the information to ChatGPT, step chat, GBD step calls back.

Lem   13:08
Yep.
Yep, that's right.

Peter Wolf   13:11
That's why under that persona, he's calling a specific piece of content that's 70. dot text content is the content in the in the document step.

Lem   13:16
Yep.

Peter Wolf   13:21
So he's saying I want to grab this from the previous step.
And this is important difference to me, right?

Lem   13:25
Yep, that's right.

Peter Wolf   13:26
You're you're you could be a grabbing from anywhere in the path.

Lem   13:27
Yep.

Peter Wolf   13:30
You could be grabbing back from steps that are 10 steps earlier, but it's pulling the step information rather than pushing it to the next step.

Lem   13:31
Yeah.
Yep, that's right.
Yep, that's right there.

Peter Wolf   13:41
OK.

Lem   13:41
There's only a little nuances on like manipulating data here on make whenever we have like an iterator and then aggregator.

Peter Wolf   13:46
Yeah.

Lem   13:50
So all of as you can see, there's like a dark space here, right?

Peter Wolf   13:54
Yeah.

Lem   13:54
So all of the steps here actually we cannot pull off in the following modules.
So that's how aggregators work on on make. That's why as you can see, I've added.
Two iterators here, right?
And then there are two aggregators also, so 2 aggregators.
Because I cannot pull out the particular data from here, then just add it inside so that's why.
Whenever we need another data here.
So you would need to like basically get again, get it again to process the data.
So if let's say as you can see like to explain it, let's say.

Peter Wolf   14:34
Well, here, let me hold on.
Let me walk through the rest of the process cause Peter Peter wasn't in that previous one. So I think it's gonna be important to catch the rest of the process.

Lem   14:39
OK. OK, OK. Yeah, no problem.
Yep. OK. OK.

Peter Wolf   14:42
So then we we send the the the the information from that document which is again additional really prompting criteria. What articles do I want?
What I wanna prioritize, we send that to Chachi EBT and then ChatGPT takes all the articles which were grabbed in that bundle.

Lem   14:53
Yep.
Yep.

Peter Wolf   15:01
And it assesses, based on the summary which ones look.
Best for us to put in this is for a newsletter. Peter.

Lem   15:05
Yes, that's right.

Peter Wolf   15:07
So then it captures all that information and now it has. It essentially comes back with. What are the three articles in this case 3, but we're saying I'm saying let's say 10, but it comes back with what are the articles that should be included now at this point?
We're coming to a rounder step, a choice, a decision point or a two different processes that will take place now previously.
Lemm had this is one big long process.
Process and that four steps up the top. They were pushed further down the line, but for visual for me for visual it was important to understand that those four steps were not dependent on those five steps or 6 steps below. Previously they were after those six steps and.

Lem   15:38
Yep.
This is actually here.
Yep.

Peter Wolf   15:53
It seemed to me like, oh, we have to run these six steps for the four to work, but in reality there are two parallel processes. They don't run in parallel.

Lem   15:53
Yeah, I'm here.

Peter Wolf   16:02
He has a little a little thing you can hardly.
See there says first and 2nd on the dotted lines. The top one says first and the bottom one says second.

Lem   16:07
Yep, this one.

Peter Wolf   16:09
So it's telling you it needs to do 2 things.
It's gonna do the top one, then it's gonna do the bottom one.
But they're not dependent on each other, right?
So I thought it was important for me looking at this.
We're gonna take this flow.
We're gonna put it into a into mermaid flow diagram, and I'm gonna see how mermaid treats this, but so up on the top when what happens is.
It takes those three articles and.
When when Cha Cha B sent it back, it sent back the three articles, the summary, the URL and its own. It already wrote the writing part right? It already added.
It's it's, it's in the bottom section. When it's doing it already.
Grab when Chachi BD sent it back, it sent back its interpretation, right?
Or it's it's spin on it, yeah.

Lem   16:55
Yep, for this one.

Peter Wolf   16:57
So when it when it we sent it ten articles and it based on the prompt it picked 3.
And then it wrote a little blurb.
A50 word blurb again will control what number that is.

Lem   17:07
Yep, that's right.

Peter Wolf   17:09
But let's say it was a fifty word blur.
But why this is important for the target audience.
So that's what now is is available coming out of ChatGPT.

Lem   17:14
Yep.

Peter Wolf   17:18
Then we go into this two choices of Paas or two Paas. The top Paas says, OK, I'm going to take those three article blurbs and I'm going to write a little introduction. If those three articles are the newsletter, I'm going to write.

Lem   17:32
Yeah, this one.

Peter Wolf   17:33
Introduction to the newsletter.
So it takes those blurbs, it feeds them.
And why is the? What's the today's insight step?
So this is iteration, so it takes the first one has to do it three times.

Lem   17:44
This one the aggregation, yeah.

Peter Wolf   17:47
Yeah. So it takes each of the articles that green dot with the lines the the green circle with the lines.

Lem   17:48
Yeah, it aggregates.

Peter Wolf   17:53
That's an iteration, Peter.
So we go up there and it says, well, ChatGPT doesn't put it all out in one burst. It says here's the first article.
Here's the second article.
Here's the third article, and so that green is an iteration. It says it's gonna run through this as many times as there are articles, and it's going to then.
Aggregate them.
That's the purple step.
So for every green step, you're always gonna have a purple step. You see down the bottom the same thing.
Green step has a purple step. The purple step is saying OK, you were iterating, giving me all the articles.
This is aggregating them, pulling them all together into 11 cluster instead of having them as three individual.
It's not one big, long message that has all three in it.

Lem   18:34
Yep, that's right.

Peter Wolf   18:36
Then we send the three points back to Chachi, BT.
And ChatGPT writes a little blurb as an introduction.
And then then the then that that turns into a variable or we save that as a variable that we can call later on.

Lem   18:51
Yeah, this one.

Peter Wolf   18:54
Unlike normal flow diagrams, you can't show that information coming back into later on.
You have to leave it as a variable and then call the variable later on and extract that information and use it.

Lem   19:01
Yep.

Peter Wolf   19:05
That's when that get variable information is right.

Lem   19:06
Yep.

Peter Wolf   19:08
Normally you'd have another line that says come back down from the top row.

Lem   19:09
Yeah, this one.
Yeah.

Peter Wolf   19:13
And come back into the main flow.
But you can't do that in make.
It's happening through that get variable piece, but you don't see a line there.

Lem   19:17
Yep, that's right.
This one.

Peter Wolf   19:22
OK.

Lem   19:22
Kim.

Peter Wolf   19:23
So. So then what happens is you go back down to the bottom.
Now it's going to iterate on the articles themselves, back to the left a little bit, Len.
So again, we're doing an iteration, we're doing an iteration here, and the Yep, the iteration is grabbing the articles just like at the top.

Lem   19:31
I was just so that.
Yep, this one.

Peter Wolf   19:41
It's grabbing all the articles or it's iterating?
Each time he's gonna grab each article and it's gonna do a process on each article, so it takes it.
It searches the article for the UUID again to get the unique ID that he added earlier.
So we know specifically what article it is and what spreadsheet line item all that kind of stuff.

Lem   19:58
Yep.

Peter Wolf   19:59
Then it goes and it says if it doesn't have it, look. If it doesn't have an image, create a random image looking like a business image, right?
Looks to see does it have an image? If it has one it gets the image.

Lem   20:08
Yep.

Peter Wolf   20:12
Do and it generates an image to include, right?

Lem   20:13
Yeah, this one.

Peter Wolf   20:15
Then it goes back to it goes back to oh, no, this is where it's writing the little blurb.
Actually, isn't it?

Lem   20:24
The Subs.
Yeah, this is the one that is writing the subsection.

Peter Wolf   20:25
Len.

Lem   20:28
So this one is outputting a commentary like an angle.

Peter Wolf   20:28
Yeah. OK. So.

Lem   20:33
Why it it it shows the?

Peter Wolf   20:33
Oh, so it's saying it's putting a spin on it, but it's not writing the blurb. It say these are the three best articles and here's what I think you should say about them.

Lem   20:36
Yeah, yeah, yeah. This.
Yeah, that's why, yeah. Yeah.

Peter Wolf   20:42
And then we're feeding that back over 1 by 1 to ChatGPT again.

Lem   20:45
Yep, to ChatGPT. Yep.

Peter Wolf   20:47
ChatGPT is saying OK, I saw the I got the three.
I'm gonna do one at a time.
Here's the first one.
Here's the spin that it says I should take.

Lem   20:53
Yep.

Peter Wolf   20:55
Then it writes a blurb with that spin, but it writes A50 word blurb.

Lem   20:57
Yep. Yeah, that's right.

Peter Wolf   20:59
And then it puts it into the aggregator and then holds that one.
Then it goes back and it starts again for the iteration and it keeps going back until it gets all three articles and they're all aggregated together in that aggregate data subsection.

Lem   21:03
Yep.
Yep.
Here.

Peter Wolf   21:13
They now all have a image.
They have a blurb, a spin blurb, and all three of them are together, right?

Lem   21:17
Yeah, this one.

Peter Wolf   21:21
And they're in HTML. That's the only thing they're in.

Lem   21:21
Yep.
No, I've yeah, I change it.

Peter Wolf   21:24
HTML for or we change that right?

Lem   21:27
Yeah, we already changed this to a plain text, so this is only plain text.

Peter Wolf   21:27
OK.
So they're plain text format here.
Same thing with the other one.
That was the introduction, which was the variable at the top.

Lem   21:36
Yeah, this is also a plain text.

Peter Wolf   21:37
So now, now we're still going on our path.
The next thing is go grab the variable 'cause. We can't have a line, but we're using the variable to grab the information from the intro.

Lem   21:43
Yeah.
This one.
Yep.

Peter Wolf   21:49
That grabs the information from the top line and it pulls it together and puts it all into a Google Docs.

Lem   21:52
From here.
Google doc.

Peter Wolf   21:54
So now we have the intro and then we.

Lem   21:55
Yeah, and this one intro.

Peter Wolf   21:57
We have all the body text for all the different blurbs and their images all into a Google Doc.

Lem   21:59
All the yeah.
Get this right? Yep.

Peter Wolf   22:03
Now we have the Google Doc and we it's added to to oh.
It's the information's added to the spreadsheet right?

Lem   22:11
Yeah. And the Google Doc is on the Google Drive.

Peter Wolf   22:12
And now we have the Google doc. Yep, go ahead.

Lem   22:16
So we can assign it on a particular Google Drive.
So I've just put it on our yeah, on.

Peter Wolf   22:19
Right.
OK.
So now there's a Google Docs, so we added this step Pete, because before it was going straight to processing and I said I wanted the opportunity to edit it and also to see what it was going to look like.

Lem   22:28
Yep.

Peter Wolf   22:32
So we created the Google Docs step and now like the Article 2 LinkedIn Post, you'll have an opportunity to edit.
So we will get the Google Doc. You know we should add here as well.

Lem   22:40
Yep.

Peter Wolf   22:44
Lemme is.
We should add is there an e-mail notification?
Or anything.
On the Google Doc, when it gets to this step.

Lem   22:51
We.
We don't need the notification because this is actually triggering every 8:00 AM.
So what will happen is, yeah, every eight.

Peter Wolf   23:01
All right, so we have a timeline.
We know what it is.
We'll go out and check. Yep. OK.

Lem   23:05
Yeah, every 8:00 AM there will be another newsletter here and then, yeah.

Peter Wolf   23:09
Good. But just for you guys, I think this is a good example of an opportunity to try something out. If you go look on some of the other flows, Len has a an e-mail trigger.
I think it would be good for you to practice here and say OK, when the document's ready.
When it's landed, then send an e-mail as well to say the documents been posted and it's ready to go. Something like that.

Lem   23:31
Yep, we can have. Yeah. Another.

Peter Wolf   23:33
That's a good practice, I think, right?

Lem   23:35
Yeah, another step here and then.

Peter Wolf   23:39
Because now this process is done and this is the thing that the I guess I say bothered me but is atypical for me.

Lem   23:39
For the notification.

Peter Wolf   23:49
If in, in my experience, when we write a process flow, the whole entire flow is in one diagram, and even if you create a document and you have something happen outside, you still have it. In one diagram. You might show it.

Lem   23:56
OK.

Peter Wolf   24:02
It ends like the first process step or the first mini process. Subprocess ends here.
And then you have another process below that this is OK with a second sub process begins here and there's an action between them that someone has to do so.
It doesn't automatically trigger. The thing is here that Google Doc is now waiting for someone to approve it to edit it and to click the button that says ready to go.

Lem   24:26
Yep.

Peter Wolf   24:27
That's going to trigger the next step, but in make you have to show a whole separate.
Flow diagram.
You can't tie them together.

Lem   24:34
Yeah, that's right. Yeah.

Peter Wolf   24:36
So what Len did was put them in a folder together and that.
Folder is the process but the steps are and you see we put the number up there.

Lem   24:42
Yep.

Peter Wolf   24:45
Now one dot inoreador RSS feed to select top three.
So that's the first mini process, the next one's going to go to dot.
So we know sequentially these all go together.

Lem   24:54
Yep.

Peter Wolf   24:56
They're in a folder and you can look at them holistically, but they're not in one diagram.
And that part can, I think to me gets a little confusing, especially if you didn't put them in bundles.

Lem   25:01
Yes, that's right.

Peter Wolf   25:05
And explicitly identify that they're together. If you didn't put them in a folder together.
With those step numbers, so we should be doing that in our Convention. Is the naming convention.

Lem   25:10
Yeah, yeah, it would be confusing if.

Peter Wolf   25:15
Is that every time you have a process, if there's more than one sub process, you gotta put the name on it and you gotta put what's the sub process number, right?

Lem   25:24
Yep.

Peter Wolf   25:24
Sub process one and then sub process 2 Yep.

Lem   25:26
Then we can actually put it.
Put it on another for example this one.
So this is actually on a folder same as this.
So I have like other UN categorized here and then there's like, yeah.

Peter Wolf   25:35
Yep.
Yeah. See, that looks good right there.
At least you come into the photo and say, OK, this is a 2 step process or three-step process and you can see the sub process steps and the numbering helps them be in order. So you don't just see them in random order, right?

Lem   25:44
Yeah.
Yep, that's right. Yep.

Peter Wolf   25:53
This is the order in which they're going to go, and I like the way you did the little diagram, Eno reader select top three, create new, you know, newsletter content, Google Doc.

Lem   25:53
Yep.
Yep.

Peter Wolf   26:04
So and then the next one is trigger with.
Yes, that's the Google Docs going to trigger.
So let's go into that flow.

Lem   26:08
Yeah, this one.
Yeah. OK.

Peter Wolf   26:19
We have the Google Doc and now this is triggered every 15 minutes looking for a yes.

Lem   26:23
Yeah. Yeah, that's right. Yep.

Peter Wolf   26:25
Now I I think just and this is for sure not on this one is in.
A is in a volume issue, but I know that ultimately you get a certain amount of credits for a certain amount of actions in make, and so I don't think we're really gonna do it this way. Whether it's searching for a yes, because that means we're we're doing.

Lem   26:37
Yep, that's right. Yeah.

Peter Wolf   26:45
Especially if we say something like every 15 minutes.
And we're only doing this.
Once a week or something, right?

Lem   26:50
Yep, that's right.

Peter Wolf   26:51
Can't the can't the can't the actual yes trigger something as opposed to it the yes, just changing the status and then the make looks for it to say change the status.

Bryan Wolf   27:01
OK.

Lem   27:04
Yeah, we we could actually create like a Google Google Apps script, but it would need like some coding.
So because it Google sheet doesn't have like a web trigger on natively here but not unlike let's say air table.

Peter Wolf   27:16
OK. But you know what we talked about, I think in the other in the other flow.

Bryan Wolf   27:19
Hold on. Hold on.
I lost track.

Peter Wolf   27:22
Well, hold one second. Let me ask.

Bryan Wolf   27:23
Here you go.
You go, you go.

Peter Wolf   27:25
Wait, you lost track?

Bryan Wolf   27:26
You know. Go, go, go, go, go.

Peter Wolf   27:28
No. So in the news.
In the news to LinkedIn posting right in that one, didn't we create a a browser trigger or no? We talked about that, but we didn't do it.

Lem   27:32
Yep.

Peter Wolf   27:38
We did it for the spreadsheet the same way.

Lem   27:39
Yeah, it's just, yeah, we use the spreadsheet.
So last time we would we talk about using err table but we need like the $20 or the like $10 I think or $20 plan. The Pro plan for the API API connections.

Bryan Wolf   27:50
Yeah.

Lem   27:56
So, but basically, yeah, for other like platforms like like CRM platforms or other like same as Google sheet they they have like a web book wherein whenever we click.
Something here?
It will. It will trigger automatically this flow.
So yeah, for example.

Peter Wolf   28:14
That's what I would like to create.
And you're saying, what will that take?

Lem   28:17
Yeah.

Peter Wolf   28:20
What would that take to do that change?

Lem   28:22
Yeah, I would need to add a Google Apps script here and do some like coding for the Google sheet.
Because yeah, Google sheet doesn't have a native as I've said, like native web book. So.

Peter Wolf   28:36
And so where does the Google script reside?

Lem   28:40
On.
Actually we need to.
Yeah, we would need to add an extension on there in this particular.
Google sheet.

Peter Wolf   28:53
So it would be in the Google sheet itself.
The script would be in the Google sheet OK look, I would like to add that as well.

Lem   28:56
Yeah, yeah, yeah, that's right.
Yeah, it would be on.

Peter Wolf   29:00
Lemm. So I'm gonna put this down as a as another one.

Lem   29:01
OK.

Peter Wolf   29:03
So we got the, the, the one spot where we said we wanted to grab and add the document, right.
And then we have.

Bryan Wolf   29:09
Yeah.

Lem   29:09
Yeah, persona.

Peter Wolf   29:10
We have this where I wanna do a trigger a trigger from the spreadsheet. I don't want it to keep looking, I want it to be an execution and once you build that script we'd be able to use that script for the for the news.

Lem   29:17
Go apps.
Yep.

Peter Wolf   29:22
The LinkedIn or news to LinkedIn would be able to use it here.
We'd be able to use it for a lot of places, so let's write that Google script trigger.

Lem   29:26
Yep.
OK.

Peter Wolf   29:34
OK.
So we'll put that as a as a follow up as well.

Lem   29:35
I would add that.

Peter Wolf   29:37
So we got the the the Google Doc added for the supplement to the prompt and then the Google the Google script to be able to trigger from the web, from the spreadsheet to to kick off the make.

Lem   29:48
Yeah, from the.
This one.

Peter Wolf   29:52
Instead of us searching for the change in status.

Lem   29:53
Yep.

Peter Wolf   29:56
So those are both follow-ups.
I'm just saying it that way.
So it goes into the notes. OK, good.

Lem   30:01
OK.

Peter Wolf   30:02
So now we go back.

Lem   30:02
OK, copy.

Peter Wolf   30:03
Yep. So now we have.
Now we where we at.
So so we trigger.
We're gonna trigger the the execution of the next step from within the Google sheet and then it's going to we can change that, but it would change instead of being a scheduled job, it's gonna be a, a trigger. Then it's gonna go and it's gonna get the content.

Bryan Wolf   30:15
Mm H.

Peter Wolf   30:25
That was in whatever the edited version of the document right now. It's gonna reformat that back into HTML format, which is what we need. The format we need to be able to feed it into the newsletter creator.

Lem   30:28
Yep.

Peter Wolf   30:38
It's gotta be an HTML format, and that's why we're feeding it back into ChatGPT telling it to put it into HTML format, then the it's not beehive.

Lem   30:40
Yeah, that's right.

Peter Wolf   30:49
What's the name of this version?

Lem   30:50
Brevo is this brevo?

Bryan Wolf   30:52
Provo yeah.

Peter Wolf   30:52
Rebel brevo bravo.
So this is the this is the newsletter creator newsletter tool and so we feed in the HTML content and then there's a whole.

Lem   30:58
Yep.

Peter Wolf   31:03
I think this is another thing you guys are gonna have to look at and get used to.
There's a whole platform where you have to go and and look at right where you have a dashboard, you manage your newsletters.
This is in the make, but it's calling that and sending the API information.
To to brevo.
But we're gonna have to manage within brevo as well.
Well, and so you guys will have to.
We'll have to get.
We have to get signed on accounts to the BREVO, but to manage the dashboard in there, right?

Lem   31:30
Yep.
Yeah. So for this particular system, I've added next other step which is send e-mail.
So this is will actually automatically.
Send the e-mail to that particular list, but we could.
Yeah, because in the past we've added a draft here, right?
This is just a draft and then we already have the draft on the where Google Docs.

Peter Wolf   31:50
Yeah.
Oh, right.

Lem   31:54
So yeah.

Peter Wolf   31:54
Originally we had it in HTML.
We put it in there.
We were gonna edit it in there, but then we I said I didn't really wanna edit in HTML because it's sloppy.

Lem   31:57
Yeah, on on brevo.
Yep, that's right. Yeah.

Peter Wolf   32:02
It looks it's a little hard for user, so that's why we changed it to normal text in the document.

Lem   32:04
Yep.
Yeah.

Peter Wolf   32:07
We added in the document.
Now when we feed it, it's not feeding into brevo it's it's actually going directly to the e-mail campaign and there's not an API for that.
And that's why you got that HTT.

Lem   32:16
Yeah, that's why I have.

Peter Wolf   32:17
That's why you got that unique step because Brevo doesn't have the API, just defeated.

Lem   32:17
Yeah, that's right.
Yep.

Peter Wolf   32:22
So I had to feed it a draft.
I could feed it a draft, but I couldn't feed it a finalized product.

Lem   32:27
No, this actually there's like 2 steps.
So this is creating the e-mail campaign and then this actually created a draft and then this next step will send that particular campaign.

Peter Wolf   32:33
Yeah.

Lem   32:40
So that's how.

Peter Wolf   32:40
Oh, oh oh, I misunderstood.
So the the blue step is triggering to say send it the the green step is all the preparation taking the document, putting it into the campaign, creating the campaign, giving it a name and prepping it all up.

Lem   32:47
Yep. Yeah, that's right. Yeah.
Yes, that's right. Yeah, Yep.

Peter Wolf   32:55
The blue step.
There's no API to say trigger.

Lem   32:57
Sending.

Peter Wolf   32:58
You have to do.
That's a custom one, right?
That's a custom call.

Lem   33:00
Yeah, this is a custom one.
So they don't have a native send e-mail campaign here.
Just send an e-mail.
So this is a different one. If you choose this one, it's just sending one e-mail to one particular person.

Peter Wolf   33:09
OK.

Lem   33:14
So this one is.
This one is an endpoint. They actually have an endpoint to send an e-mail campaign, but it's not available in week.
That's why, yeah, we have this particular HTTP request.

Peter Wolf   33:30
OK.

Lem   33:30
So yeah.

Peter Wolf   33:31
Let me ask you something else. You just said something.
So and I know I'm getting into the weeds on these, but now that I'm now that we're taking the time to walk through them, I really want to make them the way that I think they should be. Meaning I don't leave a whole bunch of things outstanding that.
Later on we come back.
I mean, if we're going to do this, then I want to build them comprehensively and and then be able to utilize them. So in my mind right now thinking about this, we had an edit.
All the way back we had to edit back upstream, right?
With a Google doc, we still haven't seen this thing in an e-mail yet.

Lem   34:04
Yep, Yep.

Peter Wolf   34:07
And you're telling me?

Lem   34:08
Yeah, that's right. Yeah.

Peter Wolf   34:09
You're telling me that that there was a step where I could send a single e-mail so I could right here trigger a single e-mail instead of the whole campaign and say just send the the draft e-mail or the the the what it is as the content send that.

Lem   34:15
Uh.

Peter Wolf   34:24
As a separate e-mail to one person.

Lem   34:24
Yeah.
Yeah, actually.
But actually we could if you want. If you want to like double check, we could actually.

Peter Wolf   34:33
Yeah.

Lem   34:35
Just.

Peter Wolf   34:35
Yeah, that's what I'm saying.
Put a router in there.

Lem   34:38
No, basically because this is already creating the draft.
So what we can do just to double check here is just log into our brevo brevo account and we could actually see the particular draft of that e-mail.

Peter Wolf   34:43
Yep.

Lem   34:54
So all this is already sent, so I've sent that already.

Peter Wolf   34:57
Hey, can I ask you a question?
What browser are you using?

Lem   34:59
Yeah. So.
This is arc arc browser.

Peter Wolf   35:05
Huh. Yeah, interesting.
And instead of having tabs up the top, you just have all your tabs on the left hand side and that's how you how you go around me that looks.
It just looks efficient.

Lem   35:13
Yeah, yeah.

Peter Wolf   35:15
I don't know why it looks different than, but I've never heard of arrrrrr.

Lem   35:16
Yeah.
Yeah, I'm using arc browser because we could actually use different spaces here.
So this is for a different client and then this is also for a different client.
So that's why, yeah, you can use like different like.

Bryan Wolf   35:27
Huh.

Peter Wolf   35:27
OK.
So a whole set of tabs that you're using for a certain set of clients you can have in one kind of folder and then another folder and you have a set and so you don't really close these, you just have them open and you can go to that.

Lem   35:35
Yep, that's right. Yeah.

Bryan Wolf   35:37
That's nice.

Lem   35:38
Yeah. Yeah, that's right.

Peter Wolf   35:43
Folder and have those available so you easily move around.

Lem   35:46
Yep, that's right. Yeah.
So these are. Yeah, that's right.

Peter Wolf   35:47
OK.

Lem   35:50
So to go back, yeah, basically we can actually see the like the end e-mail here as you can see.

Peter Wolf   35:50
Interesting.

Lem   35:57
So after let's say after we edit it on Google Doc and then this already triggered this particular or triggered. So this is actually creating the draft right?

Peter Wolf   36:03
Yep.

Lem   36:06
So we could actually check that one here.
So we just go on campaigns and then click the upper.

Peter Wolf   36:12
But you have to go one you have to log on to do that.

Lem   36:15
Yeah. Yeah, that's right on breville.

Peter Wolf   36:17
OK.

Lem   36:18
But yeah, and then we would need to like manually send it.
If that's. Yeah, that's the only thing there.

Peter Wolf   36:24
What was that? What was that?
What was that trigger step you had that said send send e-mail and it wasn't the campaign you said it was the send a single not in there in the brevo.

Lem   36:33
Hi this one.
Yeah, yeah, yeah.
We all actually have sent an e-mail.
Just one oh.

Peter Wolf   36:39
Is that send the e-mail saying it's ready or is that what is that?

Lem   36:44
It's just sending an e-mail, so depending on what you want to send so you can actually send an e-mail.

Peter Wolf   36:53
But that's what I'm asking. Can you send an e-mail that is the the finalized version before you actually send it?
Say send.

Lem   37:00
Yeah. Yeah, yeah. Yes, that's right. I.

Peter Wolf   37:01
That's what I'm asking.
So because I I the edited the document earlier, we know what it looks like in a document, but something could have still gotten corrupted in the e-mail format structure.

Lem   37:10
Yeah, in.

Peter Wolf   37:12
And So what I'm saying is if if we could have it send us a sample that we would validate before.

Lem   37:12
Yeah. ChatGPT. Yep, that's right.

Peter Wolf   37:18
We trigger the next part.

Lem   37:21
Yeah, we could actually do that.

Peter Wolf   37:22
You know what I'm saying? If I get a single instead of right here going to send campaign, I call.
The next step is is to is to do the single e-mail to me, we put in a unique address or a mailbox.

Lem   37:27
Yep.
Yep.
Yeah.

Peter Wolf   37:36
It sends the the what it would send is the campaign.
It sends that to that one e-mail.

Lem   37:43
Yep.

Peter Wolf   37:44
Then we then we review it and then what I would put is a Google is a a Gmail response to say we reply that says.
Is ready or accept or something like that and then it would go up and trigger the campaign because this gives us a last step to make sure we don't send out something that looks bad or sloppy or shooting up.

Lem   38:00
Oh.
Yeah, yeah, yeah, that's right.

Peter Wolf   38:06
Can we do that?

Lem   38:07
Yeah, but we would add again another flow system flow #3 for that one because.

Peter Wolf   38:11
Yeah.

Lem   38:14
Basically yeah, if we.

Peter Wolf   38:17
Because again, we have a control point where we stop and we have to do steps, so it has to be another flow.

Lem   38:23
Yeah, that's right.
So because we need to do something else.
So that's why it it would stop on that particular step.

Peter Wolf   38:28
OK.

Lem   38:30
Yeah, it couldn't wait for.

Peter Wolf   38:30
But so from what you OK.
Yeah, so can't wait 'cause. It doesn't have the rest of the steps.
We can't come back in.
That always has whenever there's a human intervention, it really has to be a separate flow after that.

Lem   38:42
Yeah. Yeah, that's right. Yep.

Peter Wolf   38:44
OK.
That's good learning point, but so then we would have the step of the create e-mail campaign and then the next step would be send single e-mail with that campaign content.

Lem   38:55
Yeah. Yeah, that's right.

Peter Wolf   38:56
And that would then send.
To a predefined.
A predefined address.

Lem   39:03
Yeah, we could.

Peter Wolf   39:03
And then.

Lem   39:04
Actually, we could also actually not create a campaign and just send the e-mail here.
So we would.

Peter Wolf   39:11
But is that going to be in the format that?
See, This is why what I'm trying to understand.
I don't really know what where like we're putting it in HTML and are you saying that's exactly the way it's going to look and the only thing it's going to be different is it's going to put it a header in the subject line, but otherwise it's going to.

Lem   39:21
Yep.

Peter Wolf   39:29
Look exactly like that.

Lem   39:30
Yeah, that's right.
It's on here on the ChatGPT, so I've added the prompt to output exactly the that particular this one.
The final output is that particular formatting and then I've just added the dynamic like the bullet form list here to this insights and then like the image source so the dynamic ones here.

Peter Wolf   39:44
Yep.

Lem   39:57
And then I've referenced it also.

Peter Wolf   39:58
OK.

Lem   39:59
On the top. So create different table for every subsection together with their image source citation link.
So this is also basing on the input data.
So you can remember in the input data, yeah we have image source so yeah. But of course ChatGPT is not perfect.

Peter Wolf   40:07
Yep, Yep, Yep.

Lem   40:14
So sometimes maybe like two to three, two to 3%, it would error out and then like it will basically like different HTML code, it will output a wrong one.
So yeah, that's a good step that we could review first before sending it to our list.
That's right.

Peter Wolf   40:30
Yeah, I think that's important.

Lem   40:31
So yeah.

Peter Wolf   40:32
So if we then review.
I mean, I know that you showed we can go into bravo directly, right?
And probably if there's something wrong with it, that's what you would do.

Lem   40:39
Yeah, this one.
And then just, yeah, it would.

Peter Wolf   40:42
If there's something wrong, you'd have to go into brevo and you'd do an edit right there, right?
Or no, at that point, is it already fixed?

Lem   40:48
Yeah, if if. If.
If.
If there's a wrong one, this would actually be like.
Like it will break.
So what will we?
What would we do is we could actually like manually trigger it again, if that makes sense.
So we would like like delete the sent here and then manually triggered again these two yes. So if that makes sense.

Peter Wolf   41:10
Yeah.
Yeah. OK.

Lem   41:15
Yeah.

Peter Wolf   41:17
It does, but I OK.

Lem   41:18
So and you just, yeah, we we would only have.

Peter Wolf   41:19
Sorry, go ahead.
But that's if something corrupted and we think that the output from chat, GBD, that if we send it again we're expecting it would be right and it would process.

Lem   41:24
Yeah. So.

Peter Wolf   41:30
That's the kind of failure you're talking about.

Lem   41:30
Yeah, that's right.
Yeah. So I would add here another router.
So for the errors, let's say like this one.
So it would pass through here if it is.
If like oh, it would be here on the other one so.
Let me just think.
Yeah, basically we would need to check it because it it would still not error out in with with the successfully sending it to e-mail.
But yeah, basically we could check the inbox, we would have a e-mail notification here that like a draft newsletter is ready and then.

Peter Wolf   42:09
So that would be our check. You're saying there wouldn't be an automated checks. We get the e-mail, we look at it, make sure it look good and if it wasn't, we have to go back and kind of re trigger it.

Lem   42:15
Yeah, that's right. Yeah.
Yeah. So we could here put on the subject line like a sample newsletter to be sent something like that. And then and then the day today.
So just the day-to-day or like the day which is created and then for the HTML body we would input like the ChatGPT result right here and then we would e-mail it first to our.

Peter Wolf   42:34
Yeah.

Lem   42:45
E-mail so we would add here to our own e-mail. Let's say my e-mail.
LG and then so the first one is it would be sent to our e-mail.
So that would be like the notification for us that the there's a ready like the it's the sample newsletter.
And then, but we would need again to have a next step, which is, yeah, another step which is.

Peter Wolf   43:08
Another step.
Yep. And now we've got a Step 3.
So this is if we wanted to retrigger, we can come back to that 'cause you're saying that would be manual anyway, right?

Lem   43:14
Yeah.
Yeah. So there would be two manual manual like, yeah, manual intervention for us.
So first is to which I'll change this to push to.
Test. Let's say a test test e-mail.
Test newsletter to Bevel and.

Peter Wolf   43:37
Well, you're saying you're you're saying you're thinking we would push it every time we have to push it every time after we review as opposed to only if I said there was something wrong with it.

Lem   43:48
No, it's just a next step to check the like the content if it's formatted correctly because basically we have two. The first one is we're checking the content right on the Google Docs.
So if it's already good, we could actually change here, let's say.
Test e-mail.
So let's say push test e-mail, then yes, then it will send the particular doc like content with the formatting of chat GP to our e-mail.
And then I would add another.
Another column here.
Let's say insert one column here and then I would add here like.
Send send to like send to.
List or like send the newsletter and then add yes again here.
So there would be like 2.
Two intervention for us.

Peter Wolf   44:45
But so again, I'd have to come back in here to to give the approval you're saying, if I do the test letter.

Lem   44:52
Yeah, that's right.
Yeah. If we have the because we need to check it, right.
So we need to trigger again another flows to send that particular campaign to the to the yeah, to the list.

Peter Wolf   45:05
Maybe I'm.
Maybe I'm.
Maybe I'm.
Maybe I'm making this part too tough and it really at this point it it everything goes into the brevo and you look at it in brevo to make sure it looks good.
I think I'm overcomplicating this part here because brevo should have it all ready to go.

Lem   45:19
Yeah.

Peter Wolf   45:25
And at this point, if I were in brevo, I'd preview the whole thing, and then I'd hit execute and it would do the.
It would send the mass campaign.

Lem   45:34
Yeah, that's right.
So we would just because the last step is here. So we would go to the like particular newsletter and then we would add the recipient to our list. And then let's say a list of active clients and then.

Peter Wolf   45:50
And that stores over time that builds the list up and it holds it.
I don't have to like people can't try to remember in the beehive, it said people could sign up and stuff like that.
Does it manage that or I have to manually add emails every time someone wants to join?

Lem   46:05
Yeah. For the yeah, you need to.
I think we could also like incorporate this to our like website or something. If you have you have one.

Peter Wolf   46:14
Yeah. Or or even on the e-mail that we send at the bottom.

Lem   46:14
But yeah, for this we could just.
Add.

Peter Wolf   46:19
Maybe it should say 'cause someone might forward it to somebody else to say you want to join or something like that.
We'll add that after we're worried about that after, but right now I end up, we end up having to add the every user that wants to be on the e-mail list we added into some into some contact list inside brevo. OK.

Lem   46:26
Like a.
Yeah, man.
Yeah. Yeah, that's that's right.
Yep, and yeah, and.

Peter Wolf   46:41
And can we manage those lists uniquely?
I mean, is there certain groupings of lists of of of contacts or benefits?

Lem   46:48
Yeah, we could.
Yeah, we could add them to like a different lists.
So let's say yeah like list for let's say depending on like this for serrala or list for yeah.

Peter Wolf   46:53
OK.
Yes, actually I could upload a list here too. Can I?

Lem   47:02
Yeah, you could add contacts here.
Import contacts as a CSV or yeah.

Peter Wolf   47:07
OK, perfect. 'cause, maybe we just take our whole contact list and then put them on there and then we put on there, you know.
A button for them if they don't want it anymore, but we proactively say we're sending it out and we just deliver it to everyone.
I might do that to start OK.

Lem   47:23
Yep.
Yeah.

Peter Wolf   47:25
Alright, so then let's go back to the flow.
I think I'm gonna drop drop this complexity at the end here.

Lem   47:31
Yeah.

Peter Wolf   47:31
So I think I think you'd go back to where you had it. I don't think it should go to the send campaign.
I don't think it should go to the same campaign, because that means it's going to do it automatically.
We don't have any pause for it, right?

Lem   47:46
Yeah. Yeah, that's right.
Yeah, we we won't have.
We won't be able to pause it, so it would be much safer if you would just have the have it as draft and then like notify you if it's already ready. And then Yep, we would be, yeah.

Peter Wolf   48:04
Yeah. So I would.
I wouldn't change that status to sent there because it's not sent yet, right?

Lem   48:09
Yeah. So.

Peter Wolf   48:09
It's it's sent.
The test is sent right? So it would.

Lem   48:13
Yeah, it would only be.
We would change this to done, let's say.
For here, let's say e-mail campaign draft status.
And then we could put here as done like then Yep.

Peter Wolf   48:23
Yeah. OK.
So then we could be done or sent, but it sent the test campaign the test one, but now the rest of it's going to be manual.

Lem   48:30
Yep.

Peter Wolf   48:31
We've got to go into Bravo, review it and trigger it for actual execution, right?

Lem   48:36
Yep, that's right. Yep. And then?

Peter Wolf   48:37
OK.
Let's go with that.
I like that.

Lem   48:41
Yeah. And then yeah, so this one, you won't be able to pull that one that they sent because yeah, it's.

Peter Wolf   48:46
No, but it could be the date.
It could be the date sent of the test e-mail.
I mean the test to us, right?
We're sending the content to ourselves, right?

Lem   48:54
Yeah, we could.

Peter Wolf   48:55
We're still doing that or no.

Lem   48:55
Yeah. Yeah, that's right.
We could.

Peter Wolf   48:57
Yeah.

Lem   49:01
Yeah, we could add here.
Yeah, I actually.
But Yep, we could add another step here so that we would test it and then I think that would be like the notification.
So if we add send an e-mail here as a test.

Peter Wolf   49:16
Yeah. Then you don't need the notification at the end there, right?

Lem   49:18
Yeah. So we, we, yeah, we won't need this notification because it would be like, yeah, redundant.
So yeah, basically I would just add here. Yeah, the.
Same text body and then.
HTML body and then just a subject the test.
Newsletter.
For I think I have.
There.
Oh, we need.
Dest newsletter and then format the date for today.
I think that's that would be much better.
Let me just find if I have some date here.
Thank.
Yeah, this one.
Uh.
And then.
Yeah, basically this would send to our, let's say my e-mail, so for.
My other e-mail and then.
Flight 2.
For testing, so this is a test.

Bryan Wolf   50:39
Mm hmm.

Lem   50:43
E-mail to me.
Then Yep, then it would add like a dawn's status here.

Peter Wolf   50:47
Like that.
Like that.
Yep.

Lem   50:52
So.
We changed this to done.
E-mail campaign, then. This would also the filter because we have actually I hear the filter for it so that it won't be picking up again be picked up again the feature.
So yeah, basically and that's the.

Peter Wolf   51:15
Alright, I like that.

Lem   51:17
Yeah, make a draft.

Peter Wolf   51:17
So then Bry need to set up.
We need to set up a brevo account.

Bryan Wolf   51:23
Yeah, I'm already kinda.

Peter Wolf   51:24
I don't think we need to set up more than one, OK?

Bryan Wolf   51:26
I already have one.
I have one I made yesterday but.
I'm not sure if I need to like pay for a subscription for it.

Lem   51:34
We we can actually use the free plan.

Peter Wolf   51:35
OK.
But then.

Bryan Wolf   51:35
But.

Lem   51:37
They have a free plan. Then you can.

Bryan Wolf   51:38
Yeah.

Lem   51:39
Actually, yeah, I can already access the the.
Yeah, the the their API.

Peter Wolf   51:46
OK.
So Brian, I need.

Lem   51:48
The AP API key.

Peter Wolf   51:48
I definitely need an account from me. OK, so we'll open an account for me and then and then you guys can open them for your own testing and what not.

Bryan Wolf   51:52
Oh God.

Lem   51:52
OK.

Bryan Wolf   51:55
No.

Peter Wolf   51:57
But I definitely need one for myself.

Lem   51:58
Set.

Bryan Wolf   52:01
Yeah.

Peter Wolf   52:01
OK, so I like this.

Lem   52:01
Dates and.

Bryan Wolf   52:02
Yeah.

Peter Wolf   52:03
I like this.
This is this looks really good to me and I think this is.

Lem   52:05
Test e-mail to me and.
At companion there.

Peter Wolf   52:09
I think what I'm gonna what?
I what I wanna think about is a way to supplement.
So if I said if I said I want, you know, ten articles, maybe I want to also have two blurbs on things happening at serrala or in my team, like the latest blog post that we made.
Or upcoming event and so I would create some kind of feeder that would create additional blurb content that would feed into the spreadsheet that then could be incorporated in.

Bryan Wolf   52:39
Mm H.

Lem   52:46
Like you would add to the.
Content I start with you.

Peter Wolf   52:51
Well, go back to go back to where we we aggregate everything together, right.
Well, even if that yes, step see the yes step is is saying you looked at the spreadsheet and everything in the spreadsheet is ready to go. It's what you wanna send.
What if I if I wanted to supplement with a couple of extra?

Lem   53:08
Yep.

Peter Wolf   53:13
But what if?
What if I had a specific article? I wanna include it.
That wasn't in the list.
Or yeah, I think that's a great example.
Well, if I had this is this is all compiling to A to a spreadsheet from which we select which we want to push, right?
Or was that back to the?
That gave us the ten options we selected.

Lem   53:33
He.

Peter Wolf   53:35
ChatGPT selected 3.

Lem   53:37
Yeah. ChatGPT. Yeah, that's the.

Peter Wolf   53:38
And at that point, what if I said I wanted to add or replace some of them?
That's a legitimate scenario to make this a personalized newsletter.

Lem   53:45
Uh.

Peter Wolf   53:46
I would want some other content, not just the generalized news.
But it would be serrala specific news and there wouldn't be a news feed for that. I'd have to figure out some way to feed similar kind of content that would go through the same kind of you know, blurbing process where ChatGPT would say, hey, we just put.
Out a new blog.
Go check it out or we got an upcoming webinar and that those would be a couple separate items.

Lem   54:11
Mm hmm.
I think, yeah, we I think we can edit or like add it on the content or you mean we you want to like choose the?

Peter Wolf   54:27
So let's say let's say chat, GBD gave me back the ten articles that it thinks yours is 3, right?
So it gave me the three articles that is selected from the full list. OK.

Lem   54:35
Here Yep.
OK.

Peter Wolf   54:39
Now, what if here I had an article that I read that wasn't on that list and I want to include that article.
I would want some way to to add that to the list.

Lem   54:54
Oh yeah, we can.

Peter Wolf   54:54
Right now we have that, yeah.

Lem   54:56
We could actually edit it on the like the Google doc if that makes sense.
Let's say let me just go to the like the Google doc say this one.
So yeah, we could, but it would be like manually like add here on or even.

Peter Wolf   55:11
Yeah. Let me. I'm thinking more automated because I'm thinking this would be a. This would be a regular process, right?
So let's let's go back and think about this.
Where would it make sense?
Where could it make sense? So at at?
Up until the point where the selection of the three articles we're feeding it recommendations really right, we're feeding it options. So I couldn't feed it in there because then it would think it was an option and it might decide it doesn't like that option, right, if I fed.

Lem   55:31
Yeah, here.

Peter Wolf   55:41
It an article that I liked that I wanted.
Specifically, I couldn't feed it in there because that would that wouldn't.
That wouldn't ensure it got in right.
I need a way to say here's what's coming out of the of the ChatGPT 3 selections and I need a way to put in a couple of my own.

Lem   56:01
OK.

Peter Wolf   56:04
So I'm starting to think that maybe this is a separate sub process.

Lem   56:08
Yeah, that would be separate.

Peter Wolf   56:10
So so if I created a separate sub process that I chose articles.
And fed those articles to.
Just like so, scroll back to the left.
No, 'cause, I don't want it to select.
I'm saying I want it so really.
Let's see here. Really what I want to do is it's down the lower part go to the right, the lower section, it's almost like I want to feed it in there.

Lem   56:38
Yeah.

Peter Wolf   56:39
I want to feed it into the iterate ChatGPT results, so it had output from ChatGPT that it was iterating into a bundle and then it aggregated.
Them at the end and I'm essentially saying I wanna. I wanna stick a couple extra in there.
So I could do another path that is like the.

Lem   56:57
Mm hmm.

Peter Wolf   57:02
I need the no. The Blur's not being written until here.

Lem   57:06
Yeah, this one.

Peter Wolf   57:08
So yeah, but so OK.
And I'm sure Brian and Peter, this is slowing down and frustrating, but this really I think these are critical aspects to the flow.

Bryan Wolf   57:17
No, that's OK.

Peter Wolf   57:19
These are really, I think, important and valuable aspects.

Bryan Wolf   57:19
Yeah, yeah, yeah, yeah.

Peter Wolf   57:22
Because really I'm trying not just to build a ******** flow, but a real flow we can utilize and putting in supplemental data information is going to be critical.

Lem   57:23
Uh.

Peter Wolf   57:30
Newsletter needs to be personalized.
This is a good way to give information about the company about upcoming events and blogs and stuff. So just hold one second I think.
So I would take.
The the choose top three, does it not only chooses, but it writes the slant of the way it would want to write something.
Right. That one creates a little not the full blurb, but it creates a a little summary kind of approach to.

Lem   57:53
Yeah, this one.

Peter Wolf   58:03
Summary approach to how it would how it would address that right.
That's what it does in that step.
It selects the three, but it also puts out not a full blur, but it puts out a kind of commentary spin or something, right?

Lem   58:09
Yeah, this one, yeah.
Yeah, yeah, yeah, a comment.
Yeah. A commentary. Yeah. The commentary, yeah.

Peter Wolf   58:18
So what I want is I want I want.
A similar ChatGPT step.
So I'm going to put a manual entry.
I'm going to feed in somehow.
I'm going to feed in somehow.
A. Let's just say it's one at a time.
I'm going to feed in an article, right?
And maybe I could do it by maybe I could do it on my Google.
I I mean you know how how we have the research and here's a great example where stuff can tie in.
You know how we have the research.
Glow when I put the word research in then it gets the article and puts it in the spreadsheet.

Lem   58:56
OK.

Peter Wolf   58:58
What if I took that or I took that spreadsheet where I had research?
And I could trigger from there and say, hey, I want this to go into my into my.
Into my newsletter now.
Right now, that research. Yeah, it was about articles, right?
I could do that same thing and say send myself a Gmail. That said, research it puts it on the spreadsheet and when I.
Go to that spreadsheet. I could actually select some of those and say they should go into the newsletter and then what it would do is feed them into into something like the choose, but not with the choose part.

Lem   59:31
Yeah.

Peter Wolf   59:37
It's only gonna it's gonna do the part about writing the little spin.
How do I spin it and then this is gonna feed into the iterate ChatGPT results. We're gonna make it like a get variable and then we could say get variable.
Would be the other articles other articles that are going to be stored in a spreadsheet.

Lem   59:58
Oh.
OK.

Peter Wolf   1:00:01
Yeah, this is starting to come together for me.
So.
So.
Because it's not gonna happen.
I'm not gonna.
It's not gonna happen on the, I mean, I might identify it on the fly and say, OK.
Yeah, that's something I wanna research.
I determine I wanna include it in a newsletter and so then I have this spreadsheet already that's got.
The It's got the blurb it.
It's it already has gone out and gotten a summary of it in that other one where we're doing the research, right? Get a summary of it. I could take that from that. Since you're writing that Google script that's gonna go from spreadsheet to trigger something, this is another.

Lem   1:00:35
Yep.

Peter Wolf   1:00:47
Example where we could reuse that Google script from a different spreadsheet.
That spreadsheet could trigger.
An output that would go into a flow that's gonna feed into this and feed.
Into maybe not this one, but in this process we'd have another step which would be variable inputs.
And.
Then it would do the same kind of thing. It would prepare a spin article.
I mean a spin blurb. We put it in.
It could then aggregate it together with the other articles.
And then.
Yeah, you know what?
This is all already happening automatically.

Lem   1:01:25
OK.

Peter Wolf   1:01:27
We gonna have to.
I'm gonna have to think about this. I I I.
This is definitely gonna go in.
But I'm gonna think about I'm gonna map it out exactly where it is.
And then I will.
And then I'll come back to you. But for right now, let's let's just add the document part, which I think you already did for for the supplemental prompting and then.

Lem   1:01:41
OK.
Yeah, we just need the document here for with the your. The persona, yeah.

Peter Wolf   1:01:54
Yeah. OK.
And then I think the rest is OK.
Give me one second, guys.
I gotta see.
I think I have.
A.
10:00.
Oh ****.
Hold on a second.

Lem   1:02:09
I'm trying to.

Peter Wolf   1:02:15
No, I'm not gonna get on that call.

Lem   1:02:17
Survive summary.

Peter Wolf   1:02:18
We're consulting.
OK, OK.

Lem   1:02:22
Umm.

Peter Wolf   1:02:22
So do me a favor.
Send me right now.
Can you put the the Jason create a Jason file for this and send it to me in the chat?

Lem   1:02:32
OK.

Peter Wolf   1:02:32
Just add it in the chat.

Lem   1:02:35
For the both both of this OK.

Peter Wolf   1:02:39
Yet for both of your steps, right?

Lem   1:02:40
Uh.

Peter Wolf   1:02:41
For both of your, I'll call them sub processes.

Bryan Wolf   1:02:47
There's a lot that you want to add that you just said, right? Yeah.

Peter Wolf   1:02:49
I know, but I'm. I'm gonna wait.
I just want right now I wanna put these into mermaid and see how the flow diagram looks.

Bryan Wolf   1:02:55
Married. OK.

Peter Wolf   1:02:57
That's the.
That's the flow charting document. Umm, right now I've been sending these flow documents to.

Bryan Wolf   1:03:00
Yeah.

Peter Wolf   1:03:03
I'll show you in a second 'cause I haven't shown you guys this.
I'll pull it up.
Now hold on a second.
And you guys should get used to this too, because this is what we're gonna do for each of these. And after they're created, hopefully the Jason should make it easy to create.
So I'm going to automations.
That's where I'm at, right?
So operational AI.
Process workflows.

Lem   1:03:34
Can can we send?

Peter Wolf   1:03:35
Let me share my screen.

Lem   1:03:37
Oh, I think we.

Peter Wolf   1:03:37
What?
Yeah, they send it by e-mail.

Lem   1:03:39
I think I can't send.

Peter Wolf   1:03:40
You can just send them by e-mail if you want.

Lem   1:03:41
OK, K Yup.

Peter Wolf   1:03:42
Just attach them to the last e-mail.
Let me share my screen.
OK.
So here's the workflow or process flow.
I'm gonna change this is Gmail article perplexity sheet.
No, this is newsletter, right?

Lem   1:04:05
I.
Peter newsletter.

Peter Wolf   1:04:07
So here is what I sent Lem when I asked him to build this.

Lem   1:04:13
Uh.
Yep, I'll just.
Oh, this is ready.

Peter Wolf   1:04:22
This is what I sent them when I asked him to build this blow.
So it's a newsletter comprehensive process flow.
Here's the here's the steps trigger frequency.
That's the way we had it.
Article aggregation aggregate the articles together that from Eno Reader.
Right. Our thirty articles or whatever he has in his sample AI is gonna curate them.
It's gonna write a little commentary now, the way he did it was the first iteration in.
Selecting.
Here selected the top articles and then it wrote a kind of mini commentary, not the full blur, but it gave a slant on why it was the right ones in the top 10.
Then it fitted out it it.
This is stuff that was important for make design that it had to iterate.
That's not something I include here because make has a specific way that has to process it.
I was thinking of in in kind of backche and then then it sent again.
In that little mini blur or the mini spin. And then it wrote the the actual blurb.
Then it wrote the the we didn't do a wrap up, but we did intro and and the visuals it grabbed the the, the thumbnail or whatever for each article and length.
Casey went further and he said if it didn't have one, just add 1.
Then it assembled the newsletter.
We couldn't use Bihar because they only had it for enterprise where I can use the API.
So we're using brevo and then here's a preview editing which we said it's gonna send us a sample, but really we're gonna edit directly inside of inside of the bravo. Then it's gonna distribute it, and then all this stuff is automatic.

Bryan Wolf   1:05:56
Yeah.

Peter Wolf   1:06:15
It's got the campaign. It's also going to then log the information to our Google sheet and then it has some statistic in beehive it then I think I saw that in yours too that we could update statistics potentially.
We're not doing that right now.
Back into the spreadsheet, right?
See how many people clicked and stuff like that.
But if not, that's in Brevo as well.
And then here is kind of key fields that were relevant then. This is what mermaid created.

Bryan Wolf   1:06:42
All right.

Peter Wolf   1:06:43
Now the way that mermaid creates this is.
Let me take this here.
Mermaid creates these float and I open an account.
You guys can play with this account.
The free account only lets you do like 3 flows or something, but if I go here.

Bryan Wolf   1:07:01
Yeah.

Peter Wolf   1:07:04
And say.
Search.
Mermaid.
So I think it's just down here process developer process flow.
So what what you do is you tell it to write a process flow in a script the way that mermaid understands this is a script that Mermaid understands.
Step one.
Step 2 sub pieces to step one and two.
Step 3 sub pieces and it takes this and it turns it into a diagram.

Bryan Wolf   1:07:38
Yeah.

Peter Wolf   1:07:42
So now what I wanna do is take.
Limbs gonna create a new one.

Bryan Wolf   1:07:47
Is Jason.

Peter Wolf   1:07:49
Yep, so so this is.
So the title this chat.
So this is process.
Flow 3 newsletter.
OK.
So now I'm gonna take.
This Jason.
Convert this.
Or use the attached.
Jason file to create.
A mermaid readable.
Process flow diagram.
Include as much detail as possible to ensure.
A comprehensive.
Process load is created in ruralid.
OK.
See if this works out well.
Be great when we're done to flow. We just export the J sons and we can create a visual and we'll see how this looks.
Does do different paths or what does it do?
I'm interested to see how it handles it.
Rather slow.
So while it's doing that, I'm going to put in the next one.
Do the same.
With this Jason.
Oh, it's definitely being detailed.
Look at how far satin stuff all the way over here.
So it's the lines are substantial compared to this other one, which were really just the bullet header or something the name.
And ultimately what we're going to want is we'll create one of these for every process flow a document like this.
So we'll be able to take the Jason file, put it in and tell Jason tell Chati BT to create a detailed human readable process flow, write up and then to create the mermaid flow right up.
So we could put it into.
A diagram.
And then we'll create a document like this for each process flow.
This will be very good. And then as we're looking at places we want to edit or adjust and we could say, you know, consider adding a step here for a notification or a control where this is ways that also I could give you guys guidance on. Hey take.

Lem   1:10:44
OK.
Yeah, like a documentation.

Peter Wolf   1:10:57
That thing that Lem added to add an extra document or add and change text in this step or change the title or change the location.
So this is a good way also for you guys to be looking at it and see things that you can practice, expand your skills and.
Kind of improve or understand how you might apply these steps in other process flows.

Bryan Wolf   1:11:18
Yeah.

Peter Wolf   1:11:20
OK.
So let's see.
Alright, so it's done here, so I'm gonna take this and see what happens.
Just copy the whole thing.
And go to mermaid.
I was already in somewhere.
Uh.
Skill hand over the date.
Oops.
Was already logged in. What happened?
What the hell?
Right.
OK.
So let's say create a new one.
New diagram.
I'm still not all that used to this so.
And here if I say.
May I ask you do repair?
I don't know if I should have done that first or not, but.
Oh, so hers.
OK.
Let's see.
So it does it. That's pretty simplistic.
Here I don't know that I'm gonna like this.
Umm.
Trigger every 15 minutes.
Check newsletter Draft sheet newsletter draft filter push brevo yes and e-mail campaign status done.
Push to brevo equals yes and e-mail campaign is best done.
Get content from Google Docs input document ID. Yeah, so it's not really giving clarity here, right?
That's a step to get the content from Google.
And to give it the content ID, those are different steps.
Format content using chat, GPD CONVERT newsletter, Google Docs text to HTML so to me it it combined whole steps right.
Push test e-mail yes.
Send test e-mail unsupported markdown and this also isn't really the way it goes right?
We're just sending the text sending the test.
Create Bravo e-mail and it's like. Either way it's going to this, but that's saying that no, I didn't send it to us.
Yes, I did send a test.
Either way, it's going to this, but I don't like this.
This is oh, so I think this was on the edit when it did the edit that it did discuss stuff.

Lem   1:14:37
Yeah, I think.

Peter Wolf   1:14:42
I think you know, we'd have to look at taking this and telling Jason to really break the steps down more clearly into individual steps.
So we can work on a prompt.
That probably will do a better job with that, Jason.
Because this is a little over, this is way oversimplified for me.
Alright, let's see what the second one does.
I should already done it.
Trigger start condition filtering.
Content retrieval.
See, even here it's doing it.
Maybe not Google sheet update. Yeah, it seems like it has even more clarity and details here than it does in the actual in the actual mermaid so.
Because 123-4567, right.
123-4567.
This is just a summary.
All branch data retrieved.
I don't know.
I I I mean the Jason has to be more comprehensive than that because the Jason is converting into all those little blurbs on make. So it knows the individual steps. It should really say those.

Lem   1:15:54
I.

Peter Wolf   1:15:56
It should then iterate and then aggregate and all that, yeah.

Lem   1:15:59
I think.
This is for the second flow. That's why it's yeah.

Peter Wolf   1:16:03
Ah, this is OK.
So now it's creating the other one.
So the other one you think maybe is going to be better, OK.

Lem   1:16:06
Yeah, yeah, this is done.
Yeah, this this is more, yeah.

Peter Wolf   1:16:11
OK.
All right, so let's see here.

Lem   1:16:12
Because the other one is just like couple of modules so.

Peter Wolf   1:16:17
Alright, so hold on.

Lem   1:16:24
But yeah, I think it's including like the some codes there on the wordings.

Peter Wolf   1:16:29
OK.
Yeah, what it should do is incorporate these notes too, because the other one didn't incorporate those notes, right? This stuff here.
It didn't incorporate these notes.
It only took this stuff.
So that's what we'd have to tell is somehow to incorporate that into, you know, into mermaid to create note boxes or something, I don't know.
Again, I'm not all that familiar with this.
Tool yet but.
Maybe there are certainly better tools out there.
But I already bought a subscription.
In this one 'cause I wanted to get started and they only sold it on annual. So I paid 80 bucks for this one.
So let's see.
Now let's go back to.
The diagram.

Bryan Wolf   1:18:40
You guys still here?
I can't hear you anymore.

Peter Wolf   1:18:42
I'm not saying anything.
I'm waiting for this AI to fix the do the repair.

Bryan Wolf   1:18:46
I was wondering what that was going.

Peter Wolf   1:18:49
We were unable to repair your diagram.
So.

Lem   1:18:57
Yeah, I think it's because Chachi, PT is like including here some.
Yeah, like that. Like.

Peter Wolf   1:19:05
Let me just take all this stuff out.

Lem   1:19:06
Br.

Peter Wolf   1:19:07
Hold on a second.
I'll take this pack 20, so it's doing.
Maybe it can't handle this path one path 2 stuff?
Let's take let's take out the notes part and see what it does.
Oh, it doesn't like it. Doesn't like to edit code.
You gotta edit each one individually, so I just gotta do a new one.
So let's kill this.
In diagram.
Just do this part.
Group.
I'm sure if I go back to, if I went to ChatGPT and and added this stuff in and said it didn't like this.
Let's see here.
For me encountered.
An error.
Please correct.
And address.
Yeah, see, if we I'm sure we could write a prompt here that would convert these much better if we knew these kinds of things, right.

Lem   1:21:38
Yeah, I think the code is breaking because there's like HTML codes.

Peter Wolf   1:21:43
Yeah, but it doesn't like it. Probably doesn't like slashes and things like that.

Lem   1:21:44
On the first one.
Yeah. Yeah, that's right.

Peter Wolf   1:21:47
It's looking at them as separators instead of HTML relevant coding, so I think now it's gonna do a better job. Again, once we figure this out, we can write some good prompts on how to convert the Jason into Mermaid.
And then I think we'll end up with content will be fine.
So let's just give it one second here to finish this up and then I'll try one more time.
But I think this is.
Honestly, I think this is a fricking great flow.
And if I can come up with the logic for supplementing, because there would definitely be things that would be like hot articles or topics that might not show up in.
In.
Might not show up in the inner feed, right?
That's a narrow feed.
I give a specific things.
Maybe there's a LinkedIn post that was made that's attractive, that that's relevant.
Maybe there's something on SAP specifically.
That's not showing up in news, but is somewhere in a blog to to, to to.
I think I need to think about that part and come up with a process flow for additional inputs and then I'm thinking what we'll really be doing is curating everything into a spreadsheet and then we pick and choose which items are gonna go into the newsletter so that.
Would definitely be a change here, but I think that's the way to to really do it is we'd be building the spreadsheet through a week.

Lem   1:23:07
Yeah. Yeah, that's right, yeah.

Peter Wolf   1:23:14
Through the week I might be sending different things in that are going to be component pieces that are going to go into the newsletter, and then we tell it at the end of the week to do the news search, which is the the capper. It goes and find.
The best of the best, and then we look at how many articles and things we already had included.
We take the additional supplemental where that's it's going out and figuring out the best stuff that it sees out in the marketplace. And then we pick and choose from that spreadsheet grab these 10.
Just like we do in the and this is where again I think these.
These feeds these process flows. You really start to be able to leverage stuff just like the one that's the news to LinkedIn Post.
We get to choose which one we want to blog on, but it feels it gives us multiple into a spreadsheet and we select which one we want. The same thing can happen here.

Lem   1:24:01
Yep.

Peter Wolf   1:24:02
We feed into a spreadsheet again through the standard flow and then through supplemental flows of hey, here's an article I send myself an e-mail with a title and it says great. Add this to the list and it puts it into that spread.
Cheap as another one for me to choose to potentially select from, and then at the end of the week I select which ones are gonna go into the news flow and maybe there was some stuff that's relevant to serrala, but I don't have enough space and I wait.
And I put that in the next weeks. But now you've got this kind of ongoing spreadsheet from which you've built content that you could that you could utilize.

Lem   1:24:38
Yeah, I think.

Peter Wolf   1:24:39
I think that's that's pretty good.
And now you still do the lead in after you decide what's in.
So you you still wait to kind of curate the whole thing together until it's a package and then you do the lead in and we'll do a kinda exit. And right now we only have the the writing of wording for what's the introduction, but we should have somet.
That wraps it up and then again in the middle is whatever we select that we're going to curate in the spreadsheet throughout the week that I think is going to be an amazing flow.

Lem   1:25:10
Yeah.
Yeah, I think, yeah, we could.

Peter Wolf   1:25:12
That would be hugely applicable.

Bryan Wolf   1:25:13
Huh.

Lem   1:25:16
Could cut the first automation and then just feed all the articles like the one Chachi Pete is choosing, and like feed it to a spreadsheet and then we could.

Peter Wolf   1:25:26
Yeah.

Lem   1:25:27
You could like add some of the articles that you want also and then at the end of the week you could trigger like that particular the. Yeah yeah, that's why that's right. Yeah.

Peter Wolf   1:25:35
The next flow that feeds it into the curation into writing the header, writing the following, and feeding it into into brevo.

Bryan Wolf   1:25:37
Yeah, yeah.

Lem   1:25:41
Yeah.

Peter Wolf   1:25:43
Brevo that's that's that'd be good, yeah.

Lem   1:25:44
Yeah. So it basically, yeah, it would pull out the data.
From the that spreadsheet and not on reader.
So there would be one that is pulling out from in reader and then the other one, yeah. And feeding spread and then.

Peter Wolf   1:25:57
Beating into the spreadsheet.
Yeah, like I would think, I would think it's still good. The first flow which feeds into which which actually gets the selection and gives you the subset.
That one's still a good flow again, but instead of feeding directly into going through and automatically going to brevo, it just goes into the spreadsheet.

Bryan Wolf   1:26:16
Change.

Peter Wolf   1:26:17
And then that's where we're waiting and that's gonna be where we're gonna feed in extra stuff.

Lem   1:26:18
Yeah, yeah, yeah, that's right. Yep.

Peter Wolf   1:26:21
And then will trigger the rest of the flow will make it another step.
But now it would be we we have much more content that we can control in there.
I'm. I'm really like this blow. I really think this is gonna turn out to be good with that customization part of, hey, what other things do I wanna include there that aren't showing up in the news? The news feed is to make it.

Lem   1:26:30
Yep, yeah.

Bryan Wolf   1:26:31
Yeah.

Peter Wolf   1:26:41
What's the hottest latest topics that I might not have seen and to make sure that they're getting in there and then the other ones are one of the things we want to be directing our.
Clients and prospects to look at and think about.
What we're doing is serrala news about us, upcoming events, blogs we posted, LinkedIn posts, we posted, articles we posted.

Lem   1:26:58
Yep.

Peter Wolf   1:27:02
I think that's really good stuff.

Lem   1:27:05
Yeah, the only thing.

Peter Wolf   1:27:05
So I will work on the sorry, go ahead.

Lem   1:27:08
Yeah, if there's like a link, yeah, we we would also need like a summary for that one.
So yeah, maybe.
I think we we need like another flow for.

Peter Wolf   1:27:17
Yeah, for sure, but let me let me map it out and do the same thing I did on this.

Lem   1:27:19
Yeah, is.

Peter Wolf   1:27:22
Then we can.
We can go from there.

Lem   1:27:25
OK.

Peter Wolf   1:27:26
So where was the last iteration? Didn't like this either, right?
I got a call to start in just a couple seconds here.
So I don't know, Brian, if you have other stuff you were having some problems with getting my account set up or something.

Bryan Wolf   1:27:45
Yeah. Yeah, yeah, yeah. I that's with Lam and then.
Yeah, I mean, you just, you know, yeah, that's about it.
And then I'm gonna work on the repository, but yeah.

Peter Wolf   1:27:54
OK.
Alright, so I'm gonna drop, but I think we're guys. I think we're making great progress.
Let me doing a great job. I think the you know this, it's gonna be hard for me to find this much time.

Lem   1:28:07
Yep, thanks.

Peter Wolf   1:28:08
But I think right now finding this much time is really gonna help us build flows that are gonna be really detailed and deep.

Bryan Wolf   1:28:11
Yeah.
Yeah, you made sure you got the most of it.

Peter Wolf   1:28:16
Yeah, and that's what I really you know, initially I was just like, OK.
Let's get flows on the table so you guys can start practicing and see, but the the the nitty gritty is where these things are gonna be.

Bryan Wolf   1:28:21
Yeah.

Peter Wolf   1:28:27
Really. You know excel, right?

Bryan Wolf   1:28:28
Separate themselves from better to yeah.

Peter Wolf   1:28:31
Something like what I just talked through.
That is a freaking awesome process that would work at any company and in my company in every department could do this stuff, right?

Bryan Wolf   1:28:37
Yeah.
Yeah.

Peter Wolf   1:28:40
Every consulting department, every product department could do this.
Exactly. And you do it with very little work. And then you curate all this extra stuff you want to. You want to include.

Bryan Wolf   1:28:50
Yes, yes, yes, yes.

Peter Wolf   1:28:51
Yep, OK.
Awesome guys, appreciate it.
Lemme, I'll send you an update sometime, sometime, sometime tonight.

Bryan Wolf   1:28:55
See ya.

Peter Wolf   1:28:59
So you'll have it in the morning time, OK.

Lem   1:29:00
OK.
Give me there. Give me there. Nope.

Peter Wolf   1:29:02
All right.
Thanks guys.
Talk to you. Bye.

Lem   1:29:04
OK, talk to you soon.

Peter Wolf Jr   1:29:05
Steve.

Bryan Wolf   1:29:09
And he likes to ramble, huh?

Lem   1:29:11
Done.

Bryan Wolf   1:29:12
Thank God. OK, so lemme I just have.
So I don't know what's what I'm doing wrong here for for.
So all the flows will be made like the the flow we made for newsletters in LinkedIn.

Lem   1:29:29
OK. Yeah.

Bryan Wolf   1:29:29
I I still am having trouble.
Connecting like the Google authorization for Google Drive and Gmail for Peter.

Lem   1:29:38
Oh, I see.

Bryan Wolf   1:29:39
And I don't know why.
I don't know what step I'm into because when I go to console it's I have everything there that I need and I remember that you had.
I don't know if it was a glitch or we just kept trying, but let me just see if I can log into real quick here.
So.
Yeah. So.
I appreciate you emailing me like late last night though, or or whatever time it was for you.
Like it was 11 for me. I've yeah.

Lem   1:30:14
Yeah, I was already signed off that time, so yeah.

Bryan Wolf   1:30:18
Yeah, yeah, I know, I know.
I just missed you. I know I just missed you. So let me pull this up.
This is.
This is my account.

Lem   1:30:31
Maybe the because as can you, as you remember last time, there's only like 2 scopes on.
The maybe the yeah.

Bryan Wolf   1:30:41
Drive. But even for for Google Drive? Yeah. But even for I mean Gmail would work. So look here.

Lem   1:30:47
For Gmail is also not.

Bryan Wolf   1:30:51
So which screen you looking at?
This one with the call, OK.

Lem   1:30:53
Yep, OK.

Bryan Wolf   1:30:54
So let me just so.

Lem   1:30:55
Yeah, yeah.

Bryan Wolf   1:31:01
So this is for him, right?
Let me just, where's the Gmail?
Or even for name testing.
Or do I not have one in here?
I don't have that one in there. OK, hold on.
Hold on.
Give me a second.
I'm gonna.

Lem   1:31:34
Do you wanna connect the like the Gmail? You could just.

Bryan Wolf   1:31:35
OK.

Lem   1:31:39
Maybe open Gmail note or.

Bryan Wolf   1:31:39
Is it?
That's one.
Oh, I just want you to show like, look, even when I put in my.
My.
Stuff right here.
It doesn't work.
I don't know why like I put in my client ID and my client secret and I I know last time.
So I got to make.com. I got his e-mail access.

Lem   1:32:00
OK.

Bryan Wolf   1:32:04
Still down here, chill.

Lem   1:32:04
Yep, that's right.
Audience is Yep.
Clients.
Scope is auth.
And yeah, I think this is.
That's why it's that's why.
It's what you call that like interfering because you have like plenty of scopes below.

Bryan Wolf   1:32:23
You know, like as well.

Lem   1:32:27
So yeah, yeah, this one.

Bryan Wolf   1:32:27
Too many.

Lem   1:32:29
So you could.

Bryan Wolf   1:32:30
I should get rid of these ones.

Lem   1:32:31
Yeah, just let's reset it and.

Bryan Wolf   1:32:35
OK.

Lem   1:32:35
Just add the two.
So there, there should be only like 2.

Bryan Wolf   1:32:40
Well, this is for Gmail, not Google Drive.
I'm doing this one for Gmail.

Lem   1:32:44
Yeah, it's OK because.
We we have the like the API already on the library.

Bryan Wolf   1:32:50
Yeah. OK.

Lem   1:32:51
Yeah. So for this one we it's like a.
Like a generalized.
Let me just open this.
May so I think it's just the user and.

Bryan Wolf   1:33:13
Gmail API.
Yeah.

Lem   1:33:16
Uh.
Consent.
It's on the.
Yeah, the auth that user info.
So user info that e-mail.
Can you search the user?
Let me just auth user info that e-mail.

Bryan Wolf   1:33:44
I'm looking out see it on here.

Lem   1:33:45
Auth it's not there, can you?

Bryan Wolf   1:33:49
Where is 1.

Lem   1:33:51
Just, yeah.
And then search for.
User info dot e-mail user info dot e-mail. Yeah, I think that's one.
Yeah, that, that's the one. Then just click the yeah. And then another one for.
Mail.google.com.
So yeah, this one mail.google.com. Yeah. And then.

Bryan Wolf   1:34:16
These are the only ones I need for drive to.

Lem   1:34:18
Yeah. And then update.
So for the Google then save, click save and then for the Google Drive we we would go to the AP is.
On.
On the library, so click the like the three three lines there on the left side.
Note on the left side. So beside Google Cloud and then API so.
Library. Yeah, that one. APN services in the library and then yeah, we would search the Google Drive here.
For the API.

Bryan Wolf   1:34:55
But yeah.

Lem   1:34:57
The other one then?
Yeah, this one enable and then also the Gmail for.

Bryan Wolf   1:34:58
Yeah. And what's the second one?

Lem   1:35:07
Yeah, it's already good.
So another one for Gmail.

Bryan Wolf   1:35:11
That's it, right?

Lem   1:35:13
It's already good, yeah.
It's already good, yeah.

Bryan Wolf   1:35:15
Alright, let me just here.

Lem   1:35:15
So I think, yeah, this would already work.

Bryan Wolf   1:35:18
So I don't think.

Lem   1:35:18
If.

Bryan Wolf   1:35:19
I.
I don't think I saved my.
I figured.
I'm gonna have to make a new one of these.

Lem   1:35:27
All the client secret, yeah.

Bryan Wolf   1:35:28
Uh.
Yeah, I don't know. Just.

Lem   1:35:30
Because.
Then you can actually like edit the name so that it won't be confusing for yeah, the connection name.

Bryan Wolf   1:35:42
Yeah, yeah, I remember.

Lem   1:35:44
Yeah. So that because it would be, yeah, recent.
Then yeah, for the client secret key.
Need to create a new one. I think if you haven't saved this one.

Bryan Wolf   1:36:10
Oh, do I not?
I don't if I saved.
Hold on.
Oh ****. ****.

Lem   1:36:14
Oh yeah, it's for the different.
Uh.
It's for P9 I think.
Yeah, yeah. You need to do it again, yeah.

Bryan Wolf   1:36:26
Not for me.
This song.
Alright.

Lem   1:36:49
Then yeah, the client secret.

Bryan Wolf   1:36:57
Gee, I I just ****** it up for sure. I think, OK, I don't know.

Lem   1:37:00
You are for the.
Uh.

Bryan Wolf   1:37:07
I think I just jacked it up, that's all.

Lem   1:37:08
Can you?
Yeah, you just open a Gmail module here.
We could actually use.
Yeah, you can actually just open.
Yeah, the Gmail for like authentication.
Then it will actually also have a connection.
On the.
So maybe.
Oh, that's odd.
Hmm.
Continue.
OK.
Yeah.
Yeah, I think.
Please reauthorize the connection.
That's all.
Can you go back to can you go here on the left side then click connections? I think that's already good.
Yeah, this one.
And then can you see the Peter connection?

Bryan Wolf   1:38:24
Oh, here we go.

Lem   1:38:25
Yeah. Can you?

Bryan Wolf   1:38:26
Reauthorize.

Lem   1:38:26
No, it's the Peter connection 11.
Yeah, I think this is the one.

Bryan Wolf   1:38:29
Oh.

Lem   1:38:31
And then click reauthorize.
Yeah, I think.

Bryan Wolf   1:38:33
Well, I just can I do? Can I delete some of these?
I just 'cause I only need one Google Drive.

Lem   1:38:37
Yeah you can.
Yeah, yeah you can.
You can delete that one actually.
So that won't be confusing also.

Bryan Wolf   1:38:46
I just delete it, but we just did but.

Lem   1:38:49
So yeah, I think this is the one that Peter connection then can you click reauthorize and then?
Let's see why.
Yeah, it says it's like refresh token.
Well, yeah, I think it's a really good.

Bryan Wolf   1:39:07
01, OK.
It works alright, so let me go to.

Lem   1:39:10
Yep. Can you go back to?

Bryan Wolf   1:39:14
Oh, oh, these are scenarios.
I just wanna import this real quick, sorry.

Lem   1:39:21
OK.

Bryan Wolf   1:39:32
Great. Great, great, great.

Lem   1:39:34
Oh, yeah, yeah, that's good.

Bryan Wolf   1:39:36
And now should I?

Lem   1:39:36
Yeah. So if if.

Bryan Wolf   1:39:37
What should I do for for this? Is for the first flow select?

Lem   1:39:42
Yep.
Yeah. Select you would, yeah, just select.

Bryan Wolf   1:39:47
I could use emails on specific OK alright, but so he this is for his so I'm not.

Lem   1:39:49
Yeah, select the first e-mail.

Bryan Wolf   1:39:52
He doesn't.
He doesn't have one in there, so I don't want to select one.
I'm just gonna press save so that.

Lem   1:39:57
OK.

Bryan Wolf   1:39:58
Yeah, see, so I'm just gonna do.

Lem   1:40:00
All emails OK.

Bryan Wolf   1:40:02
Is that should I do that 'cause I want this is just for the research thing how you type research in the in the hot bar OK.

Lem   1:40:07
Yep.

Bryan Wolf   1:40:09
Alright, now this I can just.
Oh, I just gotta I gotta.

Lem   1:40:13
You would need to. Yeah, you would need to actually put an account to all of the module to save that one.

Bryan Wolf   1:40:20
I can just unlink it though right now for now.

Lem   1:40:21
Uh.
Yeah, yeah, you can also.

Bryan Wolf   1:40:24
No, I just wanna make sure that it is.

Lem   1:40:28
So.

Bryan Wolf   1:40:28
Google Drive is working too.

Lem   1:40:31
Uh.

Bryan Wolf   1:40:32
How is Google Docs?
I gotta kill a docs.
I think this should work right? OK, update Commission.

Lem   1:40:38
Yeah, to just update the connection.

Bryan Wolf   1:40:49
Yeah. OK, good.

Lem   1:40:52
K.

Bryan Wolf   1:40:52
Uh.

Lem   1:40:53
Yeah, I think that would be.

Bryan Wolf   1:40:56
So would I have to do this too?

Lem   1:41:00
Uh. Uh.

Bryan Wolf   1:41:00
Or Google Docs.

Lem   1:41:04
For we already connected this. Oh, it's a Google Docs, right? Yeah.

Bryan Wolf   1:41:08
This is for Peters.
This is for Peters.

Lem   1:41:12
Can you?
Oh, that's odd.

Bryan Wolf   1:41:16
'Cause it usually I don't have to ask it like all this, right?
Let's just see if I can sign up with Google.

Lem   1:41:20
Yeah, I think you can just sign in.
I think you can just sign in because yeah, we already have the authorization for this.

Bryan Wolf   1:41:24
Yeah.

Lem   1:41:27
The just select all Yep.

Bryan Wolf   1:41:33
Nice. OK. I think it sheets account is connected to.

Lem   1:41:33
Yeah, that's good then.

Bryan Wolf   1:41:46
Yeah, well, I'm good. I'm good.

Lem   1:41:47
Yeah. OK.
Yeah, that's good.

Bryan Wolf   1:41:48
Good, good, good, good. Alright.

Lem   1:41:50
Umm.

Bryan Wolf   1:41:52
And then I was like, trying to follow along with.
What you guys were doing with this, but I'm just gonna wait.
I I just.
I did set up.
I'm I'm looking for my client ID for this because I can't.

Lem   1:42:04
Oh yeah, I you would need to go on the developer so.

Bryan Wolf   1:42:08
Well, I made one.
I made one, I thought.
Oh wait.
Hold on.
This is not my account, you know.
I'm just gonna worry about this tomorrow, to be honest with you, Lem. Cause. Yeah, yeah, yeah, we'll just talk then.

Lem   1:42:17
OK, K.
Yeah, yeah, no problem.

Bryan Wolf   1:42:20
Alright, sound good.

Lem   1:42:21
Yep, OK.

Bryan Wolf   1:42:22
All right.
Lemme. You're the man.

Lem   1:42:24
Gabriela. Yeah. Talk to you soon.

Bryan Wolf   1:42:26
I'll talk to you tomorrow.
Yeah, yeah.
I'll talk to you tomorrow. Sounds good.

Lem   1:42:28
Yeah. Tomorrow. OK, bye. Yeah.

Bryan Wolf   1:42:30
See you. Bye.

Peter Wolf stopped transcription


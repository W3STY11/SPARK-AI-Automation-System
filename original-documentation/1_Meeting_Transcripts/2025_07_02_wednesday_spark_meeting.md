# Process Automation Workshop (19)

**Original File:** Process Automation Workshop (19).docx
**Extracted Date:** 2025-07-02 (Wednesday)
**Converted:** 2025-07-28 11:40:56

---

Transcript

July 2, 2025, 12:48PM

Lem   11:42
Hey, guys.

Bryan Wolf   11:48
Morning.
Top line neck.

Nicholas Westburg   11:51
Boy, guys.

Lem   11:53
Yeah, all good. OK.

Bryan Wolf   11:53
Peter's not going to be in this morning, so we can get going.
I know he didn't send you any new flows last night to work on and I'm probably just gonna go over you after what we did yesterday when we knocked out, but and after that I just wanna go through.

Lem   12:00
OK, um.
Oh.

Bryan Wolf   12:16
My other flows and triple double check, make sure everything's firing, make sure everything's working and then I think we'll just be good.

Lem   12:21
OK.
OK.
OK, no problem.

Nicholas Westburg   12:28
Lem, also, I had a question for you. So I'm not really sure how you're storing all your flows, right? Everything that you're doing. So I know you're consistently updating right and adding and critiquing. I know you're doing a lot.

Lem   12:32
OK.
Yep.

Nicholas Westburg   12:43
So I'm not really sure how you keep track or organize your the flows that we're working on or the flows that Eater, you know, wants to build, right. So I I talked to him when you got off the call yesterday. So really what I'm doing with the flows that you create and make, I I try to take it in and do it different.

Lem   12:54
OK.
OK.

Nicholas Westburg   13:03
Do it in different ways, right? Whether it's from my command line or gentically or via different APIs. So I was thinking that if you could somehow send me like all of the flows that you have.

Lem   13:09
OK.

Nicholas Westburg   13:19
Or some sort of documentation. I know you you know you send those emails with updates and whatnot and like the the JSONS is there at like you have them stored anywhere or would be good for this where I can say OK this is the flow is you know I'm gonna.

Lem   13:24
OK.
Duh.

Nicholas Westburg   13:35
And I'm going to try to approach this and take this and and do it and find other ways to do it, you know, in the environment and the way that I want to do it, whether it's like.

Lem   13:43
Oh OK, I only have like the Jason files, so I haven't built yet the like the documentation for all of it. But yeah, basically all of the Jason files I I have. Yeah, that's the one I can, I think, send you.

Nicholas Westburg   13:52
Right.

Lem   14:01
As an e-mail and or yeah.

Nicholas Westburg   14:07
Yeah, that's fine. Do you see what you see or or kind of get what I'm asking?

Lem   14:08
OK.
Like, yeah, basically you wanna like build it also also on your own environment or something, but.

Nicholas Westburg   14:21
Yeah, like replicate the same exact flow that you're, you know, that we're building in make, but just in a different way. That's kind of how I'm doing it in a variety of different ways. And I'm trying to think about like, OK, so you're the, you have all of the flows or you know, I have.

Lem   14:24
Yeah.
Yeah, yeah, that's right. Yeah. Yeah, so.

Nicholas Westburg   14:41
Have the the ADA list that Peter, you know he sent to us a while ago and I I know we spoke on. He's gonna send me some conversations that he's had because he has those conversations with ChatGPT and that's where a lot of the brainstorming and.

Lem   14:46
OK.
Yeah.

Nicholas Westburg   14:56
You know, his his flows are currently stuck, like new ones and stuff like that. But other than that, that's, you know.

Lem   15:01
OK.
Yeah he also yeah actually also have like the yeah the document like the it's like a developer notes to on what to build but I think it I only have it for the newsletter process and also.
Um.
For the Yeah, it's only on the newsletter process. And then yeah, I don't have it for the research company, so let me just.

Nicholas Westburg   15:34
OK.

Lem   15:42
Yeah, I think I uh.

Nicholas Westburg   15:42
How many do we have completely finished that were that are, I don't want to say behind us, but you know, but OK.

Lem   15:48
We have.
Yeah, we have, yeah, we have four. I think the first one is like the filtering. Yeah, in, yeah, the in inbox. And then second one is the.

Bryan Wolf   15:54
4.

Nicholas Westburg   15:58
Yep.

Bryan Wolf   16:00
Main database, not the research thing.
OK.
LinkedIn.

Lem   16:07
The LinkedIn, yeah, the LinkedIn content and then the newsletter flow and then the newest one right now is the research company research and job posting. So actually what I can also suggest is maybe you can like import the Jason files and then.

Bryan Wolf   16:12
What we're doing right now?

Nicholas Westburg   16:16
So.

Bryan Wolf   16:17
Yeah.

Lem   16:24
Like just check even though you could because you could actually like see the like the diagram or let me just let me share my screen. Yeah, let me share my screen. So for example.

Bryan Wolf   16:36
That makes sense to Daria, yeah.

Lem   16:42
Um, for example, uh, I'll create uh like a new scenario, right? And then.
Because basically make.com is pretty good on the visual side, so we could actually like visualize what is happening here. So for example I'll like import this research research blueprint right? For example this one.

Bryan Wolf   17:05
Sorry.

Lem   17:10
So because there there's a lot here, so you don't, you won't be needing to like put all the credentials, right? Because it will take time and then to check. So if you would like to build it yourself, you could just like see.

Nicholas Westburg   17:10
Yep.

Lem   17:26
Like the how it is like.

Nicholas Westburg   17:29
The process.

Lem   17:30
Yeah, the process like, yeah, the process. And then because I've I've actually named it so that we could easily understand what is happening. For example, yeah, the research company and then this is using like perplexity. And then yeah, for example this is for searching the main website and then yeah, you could.

Nicholas Westburg   17:39
Yep, Yep.

Lem   17:50
Now like do something like this because basically if you if you feed like a diagram to like a chat GP or something to create like a visual format of this, but I think this is already like visually understandable.

Bryan Wolf   18:05
Yeah.

Lem   18:06
And then yeah, I think, uh, because uh, yeah, for now I don't have like the step by step documentation, but yeah.

Nicholas Westburg   18:06
OK.
I can yeah, no worries. Visual visuals are great too. I mean, not only do the LLMS understand it, I mean just personally it's a lot easier to visualize and and see the the the flow. So which ones do you like?

Lem   18:17
Yeah.
Yeah.
Yeah.
Uh.
I can.
Yeah, I can also send this one. So Peter also sent me like for this is like the newsletter flow, but basically this has like the it's like a dev note. So this is what he wanted to.

Bryan Wolf   18:32
Is this?
Mm.

Lem   18:44
Built for the newsletter flow. We just edited something here because he iterated it like like for different versions. But yeah, this is like the rough rough outline of the first.

Nicholas Westburg   18:46
Yep.

Bryan Wolf   18:46
Yeah.

Lem   19:00
Version of the newsletter flow and then I also yeah and this one and I think we I also have yeah for the research company. So I think we have I have it here.
Yeah, this one. So this is like for the research company. So I think yeah this is I can send you this one and also like by batch for example this one and then together with the Jason file for the research company.
Um, yeah, yeah. And then.

Nicholas Westburg   19:33
Cool. Yeah, sounds good. Um.
Out of the all of the flows, Bryan, Bryan, are you there? Like what you want like are not, like I said, not behind us, but done right where like.

Bryan Wolf   19:41
Yeah.
They're all dumb.
Like, well, I mean the newsletter one. The newsletter one I'm sure will still tweak around with because Pete said he wants to come back today and look at some stuff. He's just not available. Yeah, this morning.

Nicholas Westburg   19:48
We're not updating currently, like I know that we're we're adding.
Yeah, of course.

Lem   19:58
Yep.
The also the content. Yeah, the content I think there is.

Bryan Wolf   20:05
Yeah, we get out to the content on the newsletter one and then uh.
Lincoln one's done fine and this one we're about to do right now. I'm sure unless unless PT here and has any complaints around her, just like wants to change some things, then this one's done too.

Nicholas Westburg   20:16
Oh.

Lem   20:16
Yep.

Nicholas Westburg   20:23
Yep. Oh.

Lem   20:23
Yep. OK, yeah, I think I can. Yeah, I'll send you like different emails for like for example this one research company together with this dev dev notes and then I'll add the Jason blueprints and then Yep, you could.

Nicholas Westburg   20:38
Cool. Yeah, you gotta see what I'm saying, right? So it's so I can just so like the more documentation and the, you know, the more, you know, step by step, this is what we did can ensure that I'm not going to miss any steps.

Lem   20:39
Yeah, yeah, yeah. Uh.
Yep.

Nicholas Westburg   20:55
Or anything critical while trying to replicate and build these flows in different environments and be a different ways, you know what I mean?

Lem   21:05
Yeah, there there there are only some nuances. Yeah some little nuance for example because per for example Zapier has a different like on the like on the data for example.
Uh.
Like for example this one. So I've added here like like a simple formula for splitting the getting the document ID. So Zapier has a different like module for this one or the like other. For example you would use like the like power automation I think for the Microsoft.
So it would have like different basically different ways to manipulate data. So make.com has its own like a native ways on manipulating data. For example they on make.com they.
They use data as like bundles and then there are like arrays, right? And then I think for N 8 and also they all of the data are on an on an array. So like the manipulation of data is quite different from platform to platform. So yeah and then but yeah, but I think.

Nicholas Westburg   22:16
Yep.

Lem   22:19
Yeah it would I think help if you could also check like the like the settings for this one. Like how? Yeah because I didn't really yet created the like the documentation on the step by step here I just named it.
For to be easily understood, but yeah, there would be.

Nicholas Westburg   22:41
Is is there a way in make like to strip all of that whether it's like an export like not just the JSON cause the JSON gives you the template right? And then we have to go in and you know add what we need to add like you just said go into each.

Lem   22:52
Yep.
Yeah, the credentials. Yeah, each. Uh, yeah, for the each node, OK.

Nicholas Westburg   23:02
Yeah, yeah. Is there a way to somehow export like that there into like a spreadsheet or with with everything?

Lem   23:10
I'm not sure if yeah, I'm not sure if they have something like that, but yeah, I'm not really sure. But yeah, OK yeah, like in the past also like Peter also tried to like paste the whole Jason file to Chat GPD I think to create like a.

Nicholas Westburg   23:14
Yeah, ma'am.
I'll mess around with it.

Lem   23:30
Diagram, but I I didn't have like a good output for that one. I think because it depending on the scenario it would be like a pretty long code like a Jason code. So yeah that would be a problem to GP side but.

Nicholas Westburg   23:43
Yeah.

Lem   23:46
Um, yeah, right there.

Nicholas Westburg   23:47
I guess a better way to to to word it is basically to reverse engineer a flow like this. Reverse engineer into like a system like Langchain or Crew AI or like an S like Google SDK or open AI's SDK or ADK or.

Bryan Wolf   23:49
OK.

Lem   23:53
Yeah, like a university. Yeah, that's right. Yep.
OK.
Yeah, that got.

Nicholas Westburg   24:07
Obviously you have a lot of different wings.

Lem   24:09
Yep.

Nicholas Westburg   24:10
Yeah.

Lem   24:13
Yeah, but I think the most important thing here is for example like this dev notes, right? For example this one like the Treasury newsletter. So every platform has like different.
Like different system or manipulating on data, but the logic here is pretty much would be the same. But the yeah of course the depending on the platform it would be like a different step by step process. So yeah, I think.
Uh, like this format would also help like for example.
Um, like, yeah, what I would basically, uh.
For example for the treasury newsletter, So what would be like the end goal for this one? So the end goal would be for of course like the newsletter, right? And then you can like batch it up. First is the how to get the content and then yeah, depending on the platform because you you could change the like.
Steps here, but I think that's how I would think about it because I also have some clients that has different systems that I didn't build. I just they wanted to take out some errors or reverse not reverse engineer but basically.

Nicholas Westburg   25:31
Yep.

Lem   25:39
Update it, update it to a more yeah clean flow. So yeah that's how I I do it. If the if the past, the past creator don't have documentation is I just check it one by one and then also ask the like the client if what is the end goal of like the system.

Nicholas Westburg   25:40
Yep.

Lem   25:59
So basically, yeah, like the rough like like, yeah, an overview of the system and then I'll check one by one what what is it doing for example, yeah.
And for other stuff, it would be much difficult because they don't have like a naming convention. They don't change the names of every module. So that would be pretty. Yeah, you would need to check it one by one, but yeah, I think.
Yeah, I think that's how I yeah, how I do it usually is, yeah, I check the like the modules scenarios one by one, then just check the flow on where the data is going, how the data is being manipulated and then yeah, that's how I go about it.
But yeah, the documentation would definitely help if there's, uh, yeah, something like this, like uh.
Documentation for the.
Make the whole flow.

Nicholas Westburg   27:00
Yep.

Lem   27:02
OK.

Nicholas Westburg   27:02
Thanks. I don't want to eat up too much of your time, but yeah, I appreciate it.

Lem   27:05
Yeah.
Yep. OK. I'll I'll send you the and then yeah, maybe I'll tomorrow I'll like.
Because for this one it's already, I think I just need to like edit this one. Yeah OK, I'll send you like a rough like rough guide of the flow that I've built. Like maybe I'll just update this one for the new flow.
And then, yeah, I'll send Jason also too, so that you can like reverse engineer it and then like build it also on a different environment. OK, Nick.

Nicholas Westburg   27:38
Yeah, I mean if you want to too, we can always just get on a quick call and I kind of, I can just show you what I'm doing as well. You know you're busy. I know you're busy and and you know times different where you are. So and I'm working too. But yeah, it'd be cool. We can get on a call and we can. I can kind of show you what.

Lem   27:44
OK.
Yep.

Nicholas Westburg   27:57
Um, visualizing and and I think that would that would help too.

Lem   27:58
OK. Yeah.
Yeah, I think that would be, yeah, that would be nice. Yeah, I think we could do that also outside the, yeah, the 911 call here on the on the teams. Yep. OK, no problem.

Nicholas Westburg   28:04
Oh.

Lem   28:14
Uh.
Yep, so I think.
Let me just discard that one.

Nicholas Westburg   28:28
Is Peter joining?

Lem   28:30
I'm not sure if.

Bryan Wolf   28:30
Junior, I don't know.

Nicholas Westburg   28:34
Well, your dad, your dad wanted me to start calling him Peter. I don't know how I felt about that.

Bryan Wolf   28:37
No, he's not. He's not coming in.

Nicholas Westburg   28:39
I like Mr. Wolf.

Bryan Wolf   28:40
Is a.
He's not going in. I'm a little late. Can I catch the back? But I don't think so. So is this the same thing? There's two, two of the jump.

Lem   28:51
Yeah this yeah this is actually new. Also I think we also alright for the other flows we don't have like a recording for the step by step because last time right what I do is like I.

Bryan Wolf   28:55
Goodbye.

Lem   29:06
Add a loom video. I could also create a like a loom video for Nick for the. I'll just explain the I think yeah that would also like just a yeah like less than 5 minutes, yeah.

Bryan Wolf   29:16
That would be good too, Lemia.

Nicholas Westburg   29:18
Yeah, Luke's great. That that first video you sent was was, you know, well documented, well explained, and he took it step by step.

Lem   29:22
Yeah.
Yeah, yeah, just what is happening. Yeah, because in the past we also already have like like recording right for this one. That's why I stopped. I stopped recording on loom also because we I I was explaining it step by step but.

Nicholas Westburg   29:44
Yeah.

Lem   29:44
What? Yeah, what? Basically if in the past few days I wasn't able to explain it because there's some iterations and yeah, but yeah, I'll I'll create the like the short loom video, maybe I just less than 5 minutes loom videos for the.
close. OK, yeah, let let me just explain what I've updated here. So this is now the like the research company system. So yeah, basically what the we could add, we could trigger it manually here. So we could just add here like.
Like a company and then company and then for the check mark also here.
And then let's see, uh, add a company here and then.
Company name.
And then click start research. So what will happen is it will trigger the this scenario the this web hook and then it will go to the the top route.
So it will just search for that one and then get the prompt and then feed it to like perplexity and then get the company details for for that particular company and then it will research. This one is just researching the main website of that company.
Then next is ChatGPT will format it to HTML to create the document and then you will get the the share link for that which is already have like access to the like editor for all the whole all the people who ask the link and then it will download the document and.
Then send it to Gmail and then add all the data here on our spreadsheet and then this Gmail is the last one is just for the dynamic e-mail, so we could also add here like a dynamic e-mail.

Bryan Wolf   31:37
OK.

Lem   31:46
To, for example, e-mail it on a different like different person or our own e-mail. So we have that choice. So this one, this, yeah, this particular module will be the one sending it dynamically. So if it's empty, it won't pass through here.

Bryan Wolf   31:47
No.

Lem   32:05
And then yeah, so the other one is for the this is a job scraping. So we're using Appify for scraping and then we are just scraping like job posts on Indeed that has.

Bryan Wolf   32:15
Oh.

Lem   32:22
SAP Finance, SAP Treasury. So I would need also the other like queries here because I think we have like 6, I think six or seven. I'm not not too sure. But yeah, so it we will scrape this daily. So this is.

Bryan Wolf   32:29
Alright.

Lem   32:38
This will trigger everyday 8:00 AM then it will get all the data scrape here and then search for a duplicate. So our filter here is 2. We have filter for all the jobs that have SAP so sometimes.
We get we get jobs that doesn't have that SAP uh name and then we also have a filter for duplicate. So if the particular company is already on our database or on our Google sheet, so we won't be.
We won't. Uh, what happened here?
I think it's just so if they're the company for example this one, so for example Fujitsu, if Fujitsu is already here so this won't.
This won't pass through, so it won't be sending the the particular data to the next modules. And then yeah, so basically the filter would be the company name and if the.
This one E the job posting report exists so so this that is just for the filtering that duplicate duplicate duplicate ones and then yeah it will create the job posting document. So chat will create the job posting document and then.
Format it to HTML also and then it will create the document and then also get a link and then put all the data to the Google sheet and then the last step is it will trigger this automation. So we are just sending here like the.
Hook. We're just calling the hook and then this will trigger for after that one and then basically it will do all the things on the top route, but they're they're just some added steps because the final documents should have like the job post content. So I've added the.
Extraction of job post content here and then formatting it to HTML and then like adding it to the to the content of the final document here. So there are two two datas here. First is the like the company research company.
And then also for the job posting. So yeah, so for if the trigger would be coming from here. So that means this for example this example company and then we have like the e-mail here like the placeholder e-mail or placeholder e-mail.
And then we have the.
Link here link to the job posting. So all of that all of this would be auto populated and also check mark. This will be all populated after this automation so it will add it all to this particular module the all the data.

Bryan Wolf   35:28
Mhm.

Lem   35:30
And then what will happen is after this will trigger, it will catch this one, this particular row, the new row, and then it will trigger it for that particular company. And then yeah, so it will go here on the.

Bryan Wolf   35:37
Mhm.
OK.

Lem   35:45
The bottom route. So the filter here is as you can see if the job posting report does not exist, it will go at the top route and then if the job posting exists so it will go to the bottom route then Yep. So the yeah the main I mean the.

Bryan Wolf   35:53
Yeah.
Yeah.

Lem   36:02
Let me just delete this row. So the output for that would be, uh, something like this.
So now we have the like the logo executive summary, then the all of the all of the details with all the citations also here. So yeah those are links and then at the bottom we have the this one so the job posting.

Bryan Wolf   36:14
OK, nice. This looks really good.
Yeah, this looks really, really good.

Lem   36:28
Job posting senior SAP Finance functional consultant with all the job description, career responsibilities. Yeah, so yeah, for this one we don't have a way to like format it, right? So chat GPD doesn't have a context on that one, so we could just edit this one just.
Enter it, but I also have like other here for example this one.
Yeah, we also have the like the Fujitsu executive summary with the yeah, the job posting here below. And yeah, so we also have the individual job posting file here document also here on the job posting report column.

Bryan Wolf   36:58
OK.

Lem   37:09
So we also have it here for the just the job posting document. So yeah, basically this this is the same. So Yep. And then now we have the company website also. So Yep, now that's it. We have.

Bryan Wolf   37:24
Let's go.

Lem   37:25
Yeah. And then I think when we trigger this daily, so I I yeah, I set it up now to Max 50 outputs and then just 2020.

Bryan Wolf   37:30
At 5, yeah.

Lem   37:40
Search for every link so we you could just play around with this. For example we could put this as a 100 and then for example this one is for like like 25 for each for each link or for each query.
For example this one. So basically it will be 20. It will search for Max rows per per URL for this query, so it would be maximum 20, so 20/20/20 we could put here like 60.
60 Max maximum output and then what will happen here if on the first like scrapes. So it will be because we we still we don't have like data here right? So we just have like.
This one, this particular companies. So I think this would be like it would process for a lot of companies at first, let's say for example the first few weeks or the first week and then when we have like a lot of data already here with a lot of companies, what will happen is.
It this would just deduplicate it and won't pass through. So we won't be having more information here because yeah, because it won't get the same. It won't pass through if the like the company's already here.

Bryan Wolf   39:04
Oh.

Lem   39:04
So, yeah, so we, yeah, I'm thinking here we could do like a 10 or five because I've test it out on Appify and it's actually there are actually a lot of jobs that has like the SAP finance. Yeah, so there there are a lot of.

Bryan Wolf   39:18
SAP and finance in the AM.

Lem   39:21
It's actually scraping a lot of jobs on that one. So Yep, yeah, basically that that's the whole flow. And then.

Bryan Wolf   39:26
here

Lem   39:34
Yeah, so.
Yep, I could actually send you guys already this Jason file if you want. So Yep.

Bryan Wolf   39:47
Yes, I yeah, both both. That way I can start putting my stuff in there and then yeah, Nick, I got a freaking notification that our our open AIP API key credits are out. I need to go back and look at that. Used used one account though the.

Lem   39:51
OK.

Bryan Wolf   40:06
Um, log into that in there.

Nicholas Westburg   40:09
Uh, I'll tell you right now. I'll look right now too. Um.

Bryan Wolf   40:12
With a train of sex.

Nicholas Westburg   40:16
Peter Wolf. He a he a Wolf.
Uh.

Bryan Wolf   40:22
It's like from here off.

Nicholas Westburg   40:24
Her. Yeah. PPA Wolfie. Yeah, well, P8 Wolfie. I mean, I'll look real quick, but I'll text it too.

Bryan Wolf   40:27
Just text.
Yeah.
Alright, alright, Lamia, can you send this to me and then?

Lem   40:36
OK, so let me just.

Bryan Wolf   40:37
I'll start putting mission in.

Nicholas Westburg   40:39
Oh, we are net. Yeah. Wow. We are -12 bucks. OK, so we do. All right. I need to check the other ones. I'm looking. OK.

Bryan Wolf   40:40
That be uh the the.
Yeah, man.

Nicholas Westburg   40:50
So I mean, I had it to when we get blue five, but yeah, OK.

Bryan Wolf   40:55
I think it's 'cause we have them constantly running like I have the the constantly running from.

Nicholas Westburg   40:58
Yeah, yeah. I mean, that's what that's what happens with the.

Lem   41:07
OK.
Oh, for this one. Oh, I think I I I'll just send you another link, so that would be, yeah, much easier.
So this would be the.
Search company system.
Yeah.

Bryan Wolf   41:44
I need the, uh, Google sheet too.

Lem   41:48
Yep. Uh yeah. And this one would be the the updated Google sheet. And then yeah, you could just edit the Apps script for this one.

Bryan Wolf   41:53
Yeah.

Lem   42:01
OK.
Um.
Yep. So I think that's it. And yeah, I'll need also the.
Maybe tomorrow if Peter would be available so or.

Bryan Wolf   42:16
On.

Lem   42:18
Would need this insight also if it's already good or yeah, if yeah, it needs tweaking or something.

Bryan Wolf   42:20
Yeah, tell what's what he needs to tweak. What do you want? So yeah, I'm sure I'll take a look at the final products.

Lem   42:31
But Yep.

Bryan Wolf   42:38
Oh, ****. I really.

Nicholas Westburg   42:48
Peter, Brian, I'm gonna go ahead and put credits in there.

Bryan Wolf   42:51
Yeah, maybe that same card that I gave you. Yeah, yeah, it's OK.

Nicholas Westburg   42:55
I think it's in there.
Um.
I need to check Claude too.

Bryan Wolf   43:02
Well, Claude is different 'cause we don't have Claude on any of these flows.

Lem   43:10
Yeah, I think it's more on ChatGPT and perplexity. Yeah, so yeah, you haven't updated it yet to clog the newsletter flow.

Bryan Wolf   43:13
And the perplexity.

Lem   43:25
Yeah, but we really have a lot of modules using ChatGPT and.

Nicholas Westburg   43:37
Couldn't process the chain.
What are you guys waiting on me or?

Lem   43:55
Um.

Bryan Wolf   43:55
No, no, no, no, no, no.

Lem   43:57
No.

Nicholas Westburg   43:58
Hello.

Lem   43:59
Yep. Are you gonna let? Are we gonna check the Yep, the photos?

Bryan Wolf   44:03
I'm gonna walk through it. See. Yeah, yeah, yeah, yeah, yeah. Send it to me. And then I'm gonna, I'm gonna upload it into my thing right now. And then we're gonna, I'm gonna go through it just to make sure everything's cool. And then and then OK, great. I'm gonna run.

Lem   44:09
OK, Yep.

Nicholas Westburg   44:13
OK, there's credits in there now. All good.

Lem   44:15
OK.

Bryan Wolf   44:19
Um, um, just give me one second.

Lem   44:22
Yeah, no problem. And for this one also, we're using Google Drive. So that would be, yeah, pain in the ******** because, yeah, we need the.

Bryan Wolf   44:30
Well, that's for mine, for mine, for his repeat. I hopefully it's hopefully, hopefully that doesn't happen. Hopefully that does not happen.

Lem   44:34
Oh, OK, yeah.
Yeah, because we're at, yeah, we we need to change the like the access for the file, not just like a private.

Bryan Wolf   44:46
Oh, do we? I do.

Lem   44:49
No in the flow. So Peter wanted the like the link to be like accessible for anyone who has the link. So that's why we have like a Google Drive module here. So we can't do it on the yeah, yeah.

Bryan Wolf   44:58
Mm.
Yeah, I hit next one.

Lem   45:06
So it's like a next step on the.

Bryan Wolf   45:12
Read webpage.
OK, let's see sheets here.
Oh, so.
How do I find the spreadsheet ID?
On on the red spreadsheets like.

Lem   45:51
The.

Bryan Wolf   45:54
In the in actual, yeah, in the actual goo sheets. How do I find that for my 'cause isn't that how we're mapping?

Lem   45:54
On here, right?
Um.
Yeah.

Bryan Wolf   46:05
Bye from morning.

Lem   46:09
Yeah, I think you could search the file name keyword here on the ID Finder.

Bryan Wolf   46:12
But the one that the the one that's in my Google Sheets research company.

Lem   46:18
Yeah, yeah, that's right. Or the one if you would duplicate it, I think you would.

Bryan Wolf   46:21
I just duplicated. I just made a new one. It's just I heard new at the end of it, yeah.

Lem   46:24
OK, OK. Yeah, yeah, you could just, we could also like select it from your drive.

Bryan Wolf   46:33
I know that's what I'm trying to do. I don't know how to find that.
So select for my drive, right? OK, yeah, I like this more. This is easier for me.

Lem   46:41
Yep. Uh.
Yeah, I selected. It's just, uh, mine is, uh, glitching a little bit.
So we could, uh, easily get the.
I need. I think I need to reverify this one.

Bryan Wolf   47:28
No, I just fixed it. I figured it out. But what you're you're gonna change it. Well, I got the I I got the sheets at work by Madden, but.

Lem   47:32
OK.
OK, that's good.

Bryan Wolf   47:38
This one also is like document ID. Let me see. It's just like all document ID. Can we by drop down? OK, drop down.

Lem   47:39
Perfect.
Yeah.
Yeah, this is, uh, like the dynamic prompt from the perplexity.

Bryan Wolf   47:54
Yes. So which which get the prop? OK, yeah, so that's Peter's prop.

Lem   47:58
Yeah.
Yeah.

Bryan Wolf   48:04
Hey, hey, Peter's back.

Lem   48:13
You'd be there.

Bryan Wolf   48:15
I love Jen get on.

Lem   48:24
And uh.

Bryan Wolf   48:30
Actually.
Now you're you're updating all that stuff.
Perplexity and uh.

Nicholas Westburg   48:40
Yeah, ChatGPT is good. There's plenty of credits in there.

Bryan Wolf   48:43
Alright, I don't know about the flexion. Can you look at that or yeah, let me do that.

Nicholas Westburg   48:46
Yeah, I'll take a look at it now. Anthropic's good. We're not gonna run into any limits there.

Bryan Wolf   48:49
Thanks.

Nicholas Westburg   48:56
Let me get the.
Documentations for complexity.
We are.
Good with perplexity as well.

Bryan Wolf   49:27
OK.
From that in slingshot.
New document location.
He already has one PW Research Company system. Or is that yours, Lem?

Lem   49:52
Yeah, that's mine. So I've added the document. I've created a document on this like folder on Google Drive. So you would need to create another like folder for so that yeah it would all the documents would be on just specific folder.

Bryan Wolf   50:01
Yeah.

Lem   50:14
Um.

Bryan Wolf   50:23
OK.
Oh, should I name it the same thing? Probably not.

Lem   50:40
Um, yeah, no problem.

Bryan Wolf   50:41
Right.
No, it shouldn't though right 'cause it'll just pop up. I won't be able to tell though.

Lem   50:44
Or yeah, you could add it as like.

Bryan Wolf   50:50
I got it.

Lem   50:51
Research documents, research company documents or something.
Awesome.

Nicholas Westburg   51:12
All right, guys, I got to run. I'm swamped with with stuff at work. If you have any questions or need help with anything, just reach out. Len, thanks again for this morning. Appreciate it.

Bryan Wolf   51:14
Alright, so.
Mm-hmm. All right, cool.

Lem   51:20
OK, Nick. Yeah. OK. Talk to you soon, Nick. OK, bye.

Nicholas Westburg   51:23
Bye. Take care. Bye.

Bryan Wolf   51:43
Good.
Change.
Mm.
Mhm.
Oh, I still can. I'm not sure there.

Lem   52:26
The Google Drive. Is that the Google Drive? Uh, OK.

Bryan Wolf   52:27
I got, yeah, I found it. I found it. Yeah, it's all good.
Um.

Lem   52:35
Yeah, it's really been the.

Bryan Wolf   52:36
Choosing account so.
I gotta update my connection I think.
OK, am I gonna drive work? Thanks.
Um, she needs.
Shipping e-mail address to Peter Wolf.
I'm very in jail.
Um.
I'm having food delivered for us to take some shopping.
OK. Yeah.
All right, I think my first part's done, you know, and then the second one.
Yeah.
OK, So what appify am I?

Lem   57:23
Oh, right. Uh, the yeah, the appify.

Bryan Wolf   57:23
Do I need to add?

Lem   57:28
Yes.
Let me just.

Bryan Wolf   57:35
I'm just logging in.

Lem   57:37
yeah this one so
I'm just.
Yeah.
Yeah, Scraper PPR. So it's from.
Yeah, borderline. The creator is borderline.

Bryan Wolf   57:59
Uh, no results. I don't only have no results.
I don't see it. What the hell?

Lem   58:11
Really.

Bryan Wolf   58:12
It doesn't show up here. I'm on the search by name by actor.

Lem   58:17
Yeah, yeah, I'm here. Sorry for aktars then.

Bryan Wolf   58:17
Yep. And on on actors, search for actors.

Lem   58:24
Yeah, I can. Yeah, it's actually it's.

Bryan Wolf   58:30
Oh, I've got store. I'll pull over here. OK, I found it.

Lem   58:36
OK.

Bryan Wolf   58:37
So then I I press start or what do I do again? Um, I copy the Jason what?

Lem   58:40
Uh.
Um.

Bryan Wolf   58:45
Where?
No, what?

Lem   58:47
Yeah.
Just ressive.

Bryan Wolf   58:51
Oh, I I took a shower and laid down for a second afterwards. Um.
Sorry, I'm distracted, so I press start. What do I do again now? I copy the Jason file.

Lem   59:03
No, just just press yeah, start and save or just save. Then you could just abort it. Yeah, cause we just want it to be here on our on actors list then.

Bryan Wolf   59:05
Just start.
And add to my account.
I restart.
Right, right. OK.

Lem   59:20
Yeah, and and we, uh, we're actually.
Sending the the input data from the from make so.
Yeah, this one.

Bryan Wolf   59:36
Research company system.

Lem   59:40
Yes, we're sending it from here.

Bryan Wolf   1:00:48
Change your hairdrop.
Sure.
Oh, I don't folder.
Let's give it a go.
Share my screen before.
All right, should I trigger one at a time?

Lem   1:01:57
OK.

Bryan Wolf   1:02:10
And you know what? I didn't put the Google sheet, but look in there.

Lem   1:02:19
Alright, Google Apps Script. Yeah, we need.
On the hook.
And then for #2 yeah this is already good for the the scrape content system. So I think we would need to like the e-mail because it will also send on my e-mail. So yeah we will need to.

Bryan Wolf   1:02:50
Yeah.
I don't see it though. I don't see your airdrop anymore. Where is it?

Lem   1:03:02
Change.
OK.
I know on the like on the.com.

Bryan Wolf   1:03:09
I think I I think I changed it for the most part. I think I saw that and changed it for for here or for where? Which one?

Lem   1:03:16
Yeah, on the Gmail modules if.

Bryan Wolf   1:03:21
Where can I change to that?

Lem   1:03:23
Oh, OK. Uh, also on on number.

Bryan Wolf   1:03:24
I think, I think I don't know about for all of them.

Lem   1:03:28
For #2.
OK.
Because I added like.
Card coded on this one. Yeah, on the add date, add data to Google sheets. So yeah, this e-mail. So I have this. This is just like a placeholder e-mail.
Yeah.

Bryan Wolf   1:04:03
Yeah.

Lem   1:04:05
OK, that's good.
Um.
Yeah, so um, for this one, this is actually already with like a 50.
You could uh change the limit there for if you want just want to test it out.

Bryan Wolf   1:04:26
Or is or is the limit again?

Lem   1:04:27
For the the no the the other one, the other automation, the scrape scrape system.
So.
Yeah, this one. So on the on the scraping on the first one, on the first module, yeah, so the yeah, Max rose is actually 50, so you could just put it like for example 10 we could just.

Bryan Wolf   1:04:45
Which one?

Lem   1:05:00
Is 10.
For now, then, yeah, I think, yeah, that's OK. We just search for, I think SAP Finance for that one.

Bryan Wolf   1:05:03
It should change to 22, just keep it like that.

Lem   1:05:14
Then yeah, just to test it out. So we will have, uh, like 10.
Oh.

Bryan Wolf   1:05:20
So should I undo these or no?

Lem   1:05:24
You could, yeah, you could just delete them, actually, 'cause that would.
I just delete the from three to so that yeah, yeah, yeah, so that it won't.

Bryan Wolf   1:05:40
There's one there, yeah.

Lem   1:05:44
OK, so it would would have the format also then. Yep, we could now start this for the manual. So yeah.
Then.
Yep, we could. Uh, yeah. So you could go back to the spreadsheet.
Then add the company here on the company name.
Yep.

Bryan Wolf   1:06:11
What company? Any company?

Lem   1:06:12
Yeah, any company. So yeah, for example, just like Apple, maybe Apple or?

Bryan Wolf   1:06:20
That's good.

Lem   1:06:21
And then I start search. So I just copy the copy the Yep, then that should start the other automation.

Bryan Wolf   1:06:33
But so do I have to do that while this is on? See how this is just loading? It's not really.

Lem   1:06:37
Yeah, yeah, it's not picking it up. Um, I think.

Bryan Wolf   1:06:41
So I should have had this. I should have had this up already.

Lem   1:06:45
Can we go back to Google Apps Script? Because yeah, it's actually not picking it up and it's already saved so on edit. So therefore I think for the trigger we need.
To get the trigger, yeah, we need to add the trigger again. So onedit then click save.
Advanced. Yeah. Then go to and Yep, this one.

Bryan Wolf   1:07:26
Yeah.

Lem   1:07:28
Yeah, just just, yeah, OK, I think this is good. Do it now. So if we, yeah, you could trigger it again, just click the run once.
Yep. And then click the check mark again.
On the spreadsheet, yeah, just, uh, then click it again. Yep, that should trigger the automation.
So let's just Yep. OK, so it passed through it the top side because yeah, it's it doesn't have the job posting document, so it's on the top route.

Bryan Wolf   1:08:15
Uh, Steve, you just opened up. We just friggin filled this out. OK, hold on. It's my open API cards. We we just updated it. Otherwise, we should make it.

Lem   1:08:22
Um.
Oh, OK, yeah.
Yes.
Yeah, maybe it didn't. Uh, it's still updating or something or?

Bryan Wolf   1:08:39
We're gone. He might just. He might just ******* not press save or something. I have to get a local so.

Lem   1:08:40
Not or is it?
Yeah.
Or it's a different.

Bryan Wolf   1:08:51
Yeah, did you update this credits on open API? It's still not coming through. Or how do I look myself? Yeah, it's just gonna take a minute.

Lem   1:08:51
Connection.
Yeah.

Bryan Wolf   1:09:02
So Nick, how do I can you send me the there's a there's a login P8 Wolf and then the other one it's like P8 Wolf, right?

Lem   1:09:02
On.

Bryan Wolf   1:09:20
Then I go to API login, right?

Lem   1:09:23
Yeah, on the developer. Yeah, developer. Yeah, this one.

Bryan Wolf   1:09:25
Yeah.
Oh.
It's second.
OK. All right. Thanks. No, I'm not. But I I will be in a minute. I'll call you back if I have any problems. All right, Sir.
And I stopped sharing the screen.
Yeah.
Gmail.
Alright.

Lem   1:10:57
OK.

Bryan Wolf   1:11:15
What the ****, man?

Lem   1:11:18
Oh, what happened?

Bryan Wolf   1:11:23
Message you tried signing in if you using a password is not the authenticated method you used during sign up.
Yeah.
See if this works.
OK, that works. Good thing.
I don't know why it's not working. We have uh.

Lem   1:13:42
Is it working?

Bryan Wolf   1:13:44
It's uploaded here on our thing. It's run out of our credits. We have our credits right now.

Lem   1:13:45
OK.
The uh.
What's not working? The API key or?

Bryan Wolf   1:13:59
My HIGBT ABI credits. It says we ran out of credits, but and we did. We just updated them like at the beginning of the call. So you know that's just taking a while.

Lem   1:14:10
OK.
Yeah, it should update like the credits on the billing on.

Bryan Wolf   1:14:22
Yeah.

Lem   1:14:23
On the settings billing, yeah, there should be like credit balance here.

Bryan Wolf   1:14:38
Wait, where do you see that? Well, because I don't like I'm not here. So this is this is what I'm looking at here for our accounts. Sorry.

Lem   1:14:42
Uh, on the.
Yeah, on the right right hand side on the settings.
Yeah, this one. Then on the billing on left side, there's like a after the projects billing and Yep, this one. Oh yeah, yeah, you have.

Bryan Wolf   1:15:00
See, see, we have **** in here, so let's try it again.

Lem   1:15:04
Yep.

Bryan Wolf   1:15:04
Let's show you.

Lem   1:15:08
Or maybe have a different connection here, so I'm not also.

Bryan Wolf   1:15:12
Uh, let's see. So I I'm not sure about that. I think I have the same connection, but let's uh.
How do I get the the key from uh where the hell is the? How do I get the API key?

Lem   1:15:27
Yeah, here. Yes, you can. Yeah, this this one. But yeah, basically you won't. You can't get like the new secret key, the old one. So you would need to, yeah, create a new secret key for.

Bryan Wolf   1:15:38
Call.

Lem   1:15:44
Because uh, this is not already accessible after you create it and uh, if it's not saved.

Bryan Wolf   1:15:49
Should I just make a new key for Big Pete?

Lem   1:15:51
Can you check the make if there's some or there's only one like one connection there on make.com?

Bryan Wolf   1:15:59
Hold on, hold on, hold on. I'm sorry. I'm on the phone next year. One second.

Lem   1:16:02
OK, no problem.

Bryan Wolf   1:16:04
OK, OK. All right, cool. All right. That's all I needed to know. Thanks. Yeah. All right, too.
Alright, sorry, I'm just gonna create a new key and what were you saying?

Lem   1:16:16
Uh.

Bryan Wolf   1:16:18
I'm just gonna create a new one 'cause I'm 'cause this one also has doesn't just as my. I don't like that, you know, but should I try it again? Should I try and run it again?

Lem   1:16:26
OK. Yeah.
Uh, you could just try. Yeah, uh, we could.

Bryan Wolf   1:16:36
Should already.

Lem   1:16:37
Yeah, maybe it's a different. Yeah, not sure if it's different.

Bryan Wolf   1:16:40
OK.
We're gonna find out right now.

Lem   1:16:48
But yeah, you could just create another API key if this error error out. Yep.

Bryan Wolf   1:16:50
Maybe I can slag it down.

Lem   1:17:16
Yep. Yeah, I think I see it in the monthly.

Bryan Wolf   1:17:16
Oh yeah, I got that.

Lem   1:18:16
Uh.

Bryan Wolf   1:18:32
Sorry, hold on.

Lem   1:18:33
OK.

Bryan Wolf   1:20:43
I don't know.

Lem   1:21:00
OK.

Bryan Wolf   1:21:16
Oh.

Lem   1:21:18
Yep, so it's now working.
Oh.
OK.

Bryan Wolf   1:21:58
So I should have been one.

Lem   1:21:59
Now, yeah, we could check the spreadsheet. So now we have the company report.
Check that.
Yep, yes, this one has. It has a table. So Yep, this is structure.

Bryan Wolf   1:22:10
This looks good.
Yeah.
****. Oh, never mind. OK, and now what's the second one for?

Lem   1:22:25
Yeah, for the second one, you could.
Because uh.
The other one should be running because it should uh.

Bryan Wolf   1:22:38
So I gotta have it both at the same time.

Lem   1:22:41
Um, even. Yeah, just this Webhook. Yeah, just the the Webhook one. You could turn that on.

Bryan Wolf   1:22:42
So I should just do it like this.
So let's put another copy here. Let's do. Let's do. Uh, I don't know.

Lem   1:22:51
I know, uh, because uh, that would be populating there, so.

Bryan Wolf   1:22:56
Where? What do you mean? I was gonna say I was gonna undo this one for another company and then I just turned them both on.

Lem   1:23:01
No, I just turn on the research company system and then, yeah, just turn on.

Bryan Wolf   1:23:06
Again, it's gonna do Google. It's gonna do Apple again. I mean, whatever. Yeah, OK, ready this.

Lem   1:23:11
No, no, it won't. It it won't because it's already processed as you can see on the spreadsheet. So if we check, yeah, then yeah, because what will happen is after the job scrape, after this happens at the end, it will actually trigger the other.

Bryan Wolf   1:23:20
OK, so now this is on. Now I run this.

Lem   1:23:31
The other scenario as you can see on the the number one the research company. So after scraping the job postings here, yeah it will actually send also the the in this last part that trigger research company system that would trigger the other scenario.

Bryan Wolf   1:23:33
What other scenario?
OK.
Mhm.

Lem   1:23:52
Then Yep.
So uh.
Yeah, I think we have here 10.
10 job postings, so it would loop 10 times for that one. If you could check the no the other one, the data set, yeah, the data scrape. So if you Scroll down you could see the bundles. How many bundles we have here?
I think, uh, just um, yeah, I think we only have two.

Bryan Wolf   1:24:24
All these.

Lem   1:24:30
Uh, yeah, just this is just two, so I think we have.

Bryan Wolf   1:24:31
Yeah, I'm listening one.

Lem   1:24:36
Yeah, I think the limit there's, uh, we can check later after this.

Bryan Wolf   1:24:37
Try long.

Lem   1:24:44
Oh.
Yes, it's actually.
Oh, right. Have you? Yeah, I I think this wouldn't work because the last module here has the web hook from my end, so it's actually triggering the.

Bryan Wolf   1:25:11
Where? Which module?

Lem   1:25:15
Last last module. So yeah that would that that the website like the URL here should be your web hook. So I see. OK yeah can you just click yeah this one. So this URL should be your web hook so that.

Bryan Wolf   1:25:17
This one.
I would look OK.

Lem   1:25:34
If you could just copy that one, yeah, I think you could copy from here then.
Yeah, OK.
Yep. And then paste it here. Yep. OK, then click save. So. But basically we will also have when you check the research company spreadsheet, there will. Yeah, there's like 2 here.

Bryan Wolf   1:26:02
Um, cause if it mirrors.

Lem   1:26:03
Yeah, yeah, we could just delete this for now because I'll wait.
Yeah, so it actually created. So yeah, we could just delete this. Yeah, just delete this for now and then turn it again. Yeah, turn again. The yeah, just oh, can you check first?

Bryan Wolf   1:26:15
Oh, posting.

Lem   1:26:27
I know. Uh, sorry. Uh, just uh, go back here in. No, this is uh, yeah, the number two and then.
OK, can you go to the get data scrape? Yeah, this one. And then yes, so the limit is 1000. So it's good for the scrape indeed. Can we check the scrape indeed?
Not sure why we are only getting.

Bryan Wolf   1:26:54
2.

Lem   1:26:55
Two. Yeah, so.
Max rows per URL. I yeah, maybe we this Max rows per URL should be less than 10. Maybe it's glitching out because of the. Can you add your like?

Bryan Wolf   1:27:09
Like.

Lem   1:27:14
Yeah, OK, yeah, 8 because this is OK, save then. OK, let's run it once.

Bryan Wolf   1:27:15
OK.
Hmm.
Uh.

Lem   1:28:12
And uh.
Document.

Bryan Wolf   1:28:35
I.

Lem   1:28:36
OK, Yep. And then this will trigger the other automation.
Then Yep, so yeah, that should the other one is already working. So we should have here. Let's see after a minute. Nope, just yeah, you can't exit. But yeah, after a minute we would have the company report here also and all the data process.

Bryan Wolf   1:29:01
Watch this 'cause the other one's working right now, right? Oh, you're saying?

Lem   1:29:05
Yeah, yeah. So that, yeah, the other one is already activated, right? And then this last module just called that other automation. So which, yeah, which, yeah, we triggered.

Bryan Wolf   1:29:14
OK, so let's give it a minute. Oh, it's still doing more. Still it's just still for multiple. OK, so it found. It found more than.

Lem   1:29:18
Yeah, it's still.
Yeah, it's still do it because I I think.

Bryan Wolf   1:29:25
Still in two.

Lem   1:29:26
Oh, it's only two. Oh, that's odd.

Bryan Wolf   1:29:28
Yeah. Yeah.

Lem   1:29:32
Yeah, there are only two bundles.
Oh.
Um.
Can you?
Go to get data script and just change the limit. I think there's a limit here to let's say 100. I'm not sure why it's only outputting 2.
Oh.
Oh, can you click it? Uh.
The GE uh scrape indeed again.
They're not sure why Mark's rows 10.
Yes, this should be good. Sure, why?
Seriously, yes.
Um.
Sure, it's only getting two. Can you go to the Abbify website on the actors you have here? Yep. Then click the Indeed scraper. Let's just check the runs. Yep. And then the runs.
And.
Uh, store succeeded with. Yeah, there's actually a lot of results. So why it's not? Can you? Yeah.

Bryan Wolf   1:30:53
I can help.

Lem   1:30:56
It's. Oh, right. Can you go back to the Yeah, this one and then get data scrape. I think that's why. Yeah. So the data set ID here is actually hard coded. So yeah.
Um, just delete this one and then.
Yeah and then oh X this one for yeah data set and then just add the default at the bot. Find the default data set ID. So there's yeah this one that yeah that one the default data set. Yeah OK then click save. So I actually hard coded because I tested it.
A while ago, so I haven't, yeah, changed it yet, but yeah, it already went, yeah, one. And then later we would also have here, yeah, the other one. Yeah. So now we could actually, yeah, we could try it again.

Bryan Wolf   1:31:35
Mm-hmm.
Oh, this one did first one too. OK, so we got one.
They don't get this one.
Alright, OK.

Lem   1:31:51
Then.
So it would now get the new new script data. No, no the no need. So as you can see there it's already updated. So now you have yeah the company file with the job posting also for the other companies.

Bryan Wolf   1:31:56
Should I undo any of these or just keep on?
Mhm.
Yeah.

Lem   1:32:09
Yep.
Then yeah, so this is actually.
Yeah, it's filtered out one so it has already the duplicate and can you you check the bubble on get data scrape. So I think there there will already be 10 there on the get data scrape data.
Let's check the bundle for it on. Yeah, this one and just Scroll down.
Yeah, we already have bundle four. Yeah. But yeah, yeah, yeah. So yeah, we have 24 bundle 20 assistant 24. Yeah. So that's 24 data.

Bryan Wolf   1:32:42
Yeah. OK. Nice, nice, nice, nice, nice, nice. 2424 bundles. All right.
So that's gonna put 24 of these in here.

Lem   1:32:55
Just if the company's already here, it won't, it will, it will, it won't pass through. Yeah, it won't pass through. So this will process a lot of companies at first because yeah, we still don't have like a database, right? We don't.

Bryan Wolf   1:33:00
Yeah, right, right, right.
Mhm.
But then it'll just, yeah, in the future.

Lem   1:33:11
Yeah. And then it after for example after the second or third day, it won't be processing for other company for the the same companies, so.

Bryan Wolf   1:33:19
Mhm.

Lem   1:33:24
Yeah, so this would should this would process for the 24. Yeah, depending on the.
Yeah, so this is these are different companies.
Yep. So if we turn this on daily, yeah, basically it would scrape like 10 to 20 job postings per day. Yeah, then.

Bryan Wolf   1:33:55
All day, yeah.

Lem   1:34:04
Yeah.
Then after for example after we get the.
Like a long list of companies on our spreadsheet, on our Google sheet, we could like adjust the because maybe it's not, it's all filtering out, it's on no, not, no job posts are passing through. So we could just adjust the result of the.
Appify. So let's say 100 job posting or let's say 150.

Bryan Wolf   1:34:36
You're showing. Yeah, yeah. OK, yeah, yeah, yeah.

Lem   1:34:37
Yeah. In the, yeah, let's say, for example, in the next few weeks. Yeah, because we would already have a pretty long list here on the spreadsheet. Yep.

Bryan Wolf   1:34:45
OK.
Uh, I'm gonna I I wanna um, this is clearly working.

Lem   1:34:58
Yeah, so Yep, it's working. Yeah, the other one is also, yeah, we could actually like, pause this or like, just stop the.

Bryan Wolf   1:35:10
Yeah, because I I wanna before you go, I wanna just this newsletter I really because I had problems with it. It wasn't.

Lem   1:35:12
Yep.
OK, no problem.

Bryan Wolf   1:35:22
I gotta go through all this and change the the chat sheet between me.
Oh, it's.
Approach.
One.
I know.

Lem   1:35:57
Alright, it's all good.
No problem.

Bryan Wolf   1:36:00
No, you're a tired guy.
What time you usually go to web?

Lem   1:36:05
Pardon.

Bryan Wolf   1:36:09
What time do you usually go to bed?

Lem   1:36:11
12 Yeah. Sometimes I also have a call, so maybe two, 2:00 AM, yeah.

Bryan Wolf   1:36:14
OK, OK.
I know, yeah.

Lem   1:36:21
Hi.

Bryan Wolf   1:36:23
This is mine. This is.
Oh.
Oh, what is this?

Lem   1:36:44
Um.
Is this a different one or?

Bryan Wolf   1:36:57
I've got this one and this one. This is the newer one right there.

Lem   1:37:02
1-2 Can you open the other one the?
Yeah, I think this is the. I think this is the new. Yeah, because the naming here is already different. As you can see, content aggregation, content formatter. But yeah, but this is still.

Bryan Wolf   1:37:12
All of them.
Yeah.
So this is the old one. This is the old one.

Lem   1:37:25
No, yeah, this is, this is the new one. So the name, yeah, it's already 8. As you can see, we added the.

Bryan Wolf   1:37:26
This is old or this is no, this is old.
Oh, this is.
OK, I'm gonna get rid of this. It's getting confused, dude. Dude, OK, I'm gonna delete it. What do you think? That's probably a good idea, right?

Lem   1:37:38
Yeah.
You can just change the name for now because like old you can put like old there on the first no.

Bryan Wolf   1:37:55
How do I do that though?

Lem   1:38:00
Here on the on the title, you can edit the name there. Yeah, this one. Yep, just you can put like.

Bryan Wolf   1:38:08
Oh jeez, hold on.

Lem   1:38:09
No, just click it. Yeah that this one. So like colon old something.
Yeah, so.

Bryan Wolf   1:38:21
OK.

Lem   1:38:22
Then.

Bryan Wolf   1:38:23
Sure.
All right. Damn. OK, OK, OK.

Lem   1:38:26
OK, yeah, this is the new one because one of you. Yeah, it's already 8 and then the naming conventions here are already new.
Uh.
Not sure. I think we haven't tested this yet on your.

Bryan Wolf   1:38:55
I think we did. No, I think we did. We did test it. Yeah, we did. Yeah. This one. Well, we're about to find out. Let me change. But I'm. I'm really sure that we did. Yeah.

Lem   1:38:57
We did the new one.
Oh.
Yeah.
Because uh, this still doesn't have.

Bryan Wolf   1:39:07
I think I had run into an issue. Remember we I run into an issue where Google Sheets was like it was overloaded. It was like Google Sheets needs a break.

Lem   1:39:13
Uh.
All right. Yeah. Yep. Because there's still no, like, history operations on the. Yeah, there's not no. So I think the the one we tested was the old one. Yeah, the old one without the.

Bryan Wolf   1:39:15
Let's just give it a try.
Oh really? There isn't.
Oh, maybe. Maybe we didn't do. Maybe we didn't do. It's the old one. Yeah, I ****** **.

Lem   1:39:34
Without the like this five second delays and also.
Uh.
Yeah.

Bryan Wolf   1:40:02
Oh really? Do you need to try this?
Oh, I just clicked on them still up. Yeah, no.

Lem   1:40:09
Yep, the number two, so already done.

Bryan Wolf   1:40:12
Did I do this one? I did this one, yeah.

Lem   1:40:14
Um, the number one? Yep. Uh, so now #3.
Yeah, I think we have ChatGPT on all the scenarios, yeah.

Bryan Wolf   1:40:22
I know, I know it sucks. I gotta change it for every single one.

Lem   1:40:28
Yeah.

Bryan Wolf   1:40:34
Yup, Yup, Yup, Yup.

Lem   1:40:38
Fort, yeah.
Uh, for the.
Yeah, this one we don't have. Yeah, just the sending the newsletter campaign.

Bryan Wolf   1:40:50
We got a couple of machine.

Lem   1:40:51
Yeah.
Yes.
Just.
No.
Sara Srikmkaja music.
Um.
Alright, OK.

Bryan Wolf   1:43:55
Should I delete all of these?

Lem   1:43:59
Um, Yep.
Only for the don't just the prompt because it's actually manually.

Bryan Wolf   1:44:07
The test.

Lem   1:44:08
Yeah, yeah, just don't delete the task also for so that we could have the format and yeah, the number one, because it will actually copy the format of the header if we.
Uh, Yep, it's good and.
This is the.

Bryan Wolf   1:44:43
Should I keep these in here? Yes. You know what? Let's just run it. Let's just run it and then we'll go from there.

Lem   1:44:45
Yeah, we could just, yeah, we could run it. Yeah, this is OK because there's there's already status process, so this won't be processed by the yeah, processed again. So that's OK.

Bryan Wolf   1:44:58
OK, wait.

Lem   1:45:01
Then yeah, this one also, yeah, could run it from start to finish.

Bryan Wolf   1:45:09
So now should I turn these all on? Or isn't there one that I don't turn on?

Lem   1:45:10
Um.
Have you already put the hooks on the this?

Bryan Wolf   1:45:18
I think I did. I'm pretty sure that we did do that.

Lem   1:45:21
On the app script.

Bryan Wolf   1:45:26
There's only one month.

Lem   1:45:28
I think this is a.

Bryan Wolf   1:45:32
Oh, it is, it is, it is.

Lem   1:45:32
Yeah.
Yeah, it's a different one.

Bryan Wolf   1:45:35
Sorry, it is.

Lem   1:45:40
Uh, yeah, this one.
Uh yeah, I think it's already plugged in.
Not, not. I'm not sure if you plug this in on the like the old one, so can we?

Bryan Wolf   1:45:58
Let's see.

Lem   1:46:02
Um.
Yeah, we could check it. Double check, for example, this one. Yeah, so this is for RCW, so for RC double. Yeah, it's already here on the G.

Bryan Wolf   1:46:15
So which one was this picture?

Lem   1:46:23
So I think.

Bryan Wolf   1:46:23
I told you, Lam, I already got you. I'm already on top of it, Lam. Come on.

Lem   1:46:25
That's, yeah, that's good. Yeah. OK, yeah, yeah. Yeah. The you could turn on the ones with the web hook. So the yeah, this one number 234 and then 678.

Bryan Wolf   1:46:29
All right, so should I just turn the wall on manually?

Lem   1:46:41
And then we'll just trigger manually the I know reader and also the yeah, this one.
Uh.
OK, run once.
Well, so we just got one. How can we can you check the I know reader data? Yeah, if how many did we get?

Bryan Wolf   1:47:06
Yeah, I don't know.

Lem   1:47:16
Uh, OK, so that's 30. OK, that's good.

Bryan Wolf   1:47:17
We got a couple, yeah.
Yeah, I'm gonna back down on this.

Lem   1:47:28
OK, so now we have the.
That's this one also for the.
Scraping.
Let me just check the.
Uh.

Bryan Wolf   1:49:41
OK.
Do you know once?

Lem   1:49:47
Yes, yeah, there are new ones. Then you also have the AI tools.

Bryan Wolf   1:49:51
So now I'm gonna include. Let me go through this with you so I know what I'm doing. So am I am I including all three of these?

Lem   1:49:54
OK.
Yep.
Yeah, you could include three. Yeah, because this is, yeah, news articles. So you could add three or four. You could add four. Yep, that's that's no problem. And then AI tools. Yeah, you could also add here on the no.

Bryan Wolf   1:50:04
Or just one.
Three or 4.
Yes.

Lem   1:50:21
Uh, different. So on the include the newsletter. Yeah, this one say 5.
And then for the.
Yeah, prompt of the day. So sample that one. So this is the scraped one. But yeah, we could add also like, yeah, OK, just for testing.

Bryan Wolf   1:50:35
Do that one.
But it's probably, yeah, just one, right? I only did one prop, right? Yeah.

Lem   1:50:46
Yeah, just one. Yep for the then for the blog post.

Bryan Wolf   1:50:49
Blog post. Oh, I don't know if they did one for this. They didn't do one.

Lem   1:50:53
This one you could just yeah this from you could just remove the process status process.

Bryan Wolf   1:50:57
Surella and move one of them.

Lem   1:51:06
And then also the other one, the status process. Yep, then you can click the include the newsletter.
Yeah, this one so that it would include the two Saral events. So then this one, this is, yeah, this is also the upcoming events. So you could just add that, add them both and then for the social media posts. So this is the new ones so that you could add there like.

Bryan Wolf   1:51:19
No.

Lem   1:51:36
Five or four? Yeah, depending on. And then, yeah, you could trigger it. Uh, yes, now.

Bryan Wolf   1:51:43
Now will I do if you please too?

Lem   1:51:43
Yep, so.
No, just one one. Yes. So it will just trigger after. Yeah, so now it should populate here. Yep, this one.

Bryan Wolf   1:51:50
Yeah.

Lem   1:51:57
I think it would take like 2 minutes, I think 2 to 3 minutes. Yeah, because yeah, we could also check it.

Bryan Wolf   1:52:00
Alright, let's let's chill. Let's chill.

Lem   1:52:08
All right, it's already turned on. So if you go back to the, yeah, the content aggregator, so.
I thought it's already. I think it's already running a content aggregation, yeah.
Uh.
I think it's still running.
Not sure if it actually.

Bryan Wolf   1:52:38
And you said.

Lem   1:52:40
Uh, can you go back to the this one and then to the social media post? So it's G, right?
Yeah, so this that should maybe it's just taking. Yeah, it would appear on the history after like the.

Bryan Wolf   1:53:01
Here, Shannon.

Lem   1:53:03
Yeah, after it finishes. So let's let's, yeah, let's wait for two to three minutes because that's, yeah, pretty long flow with five second delays, I think 5.

Bryan Wolf   1:53:07
Let's just give it a couple hours.
2.
Mhm.

Lem   1:53:19
Yeah.
335 second delays per.
15 seconds, yeah, like a minute or so for the delays and then one minute for.

Bryan Wolf   1:53:28
Mhm.

Lem   1:53:33
We can just double check for now the I think the Google app Apps script. Let's just make sure if it's on the same.

Bryan Wolf   1:53:49
Turn on.
We were to go to Google Apps Scripts.

Lem   1:54:00
Yeah, let's check for the it's G think it's G right for yeah, this one then for RCWVR.

Bryan Wolf   1:54:09
That's all.
Or um, we already did this one. We already know this one's here.

Lem   1:54:16
Yeah. Oh, yeah. So it's, uh, it's actually, yeah, it's the same.
Yes, I that's a that's a trigger.
Just taking its time, I think.

Bryan Wolf   1:54:28
Yeah.

Lem   1:54:29
Yeah.
And then yes, so that should add some process. Huh, that's odd.
Yeah, it's it actually. Can you check the Google Apps script if there's already a trigger? Can you double check this one?
Oh, OK, so there's already a trigger.

Bryan Wolf   1:55:11
Maybe I don't have an app drive for docs.

Lem   1:55:17
Oh no, it's it's. Can you function as a trigger?
Can you go back to the Google Apps?
Pip code.
On the editor, so this should be on edit trigger OK.
Then the function there we could check it's logs actually, so I think it didn't on the left side and then executions.
Should I do? Yes, it uh.
Yeah, it actually triggered. I think it's actually.

Bryan Wolf   1:56:03
Mm-hmm. So I think it's just taking a while maybe. Or it's just, I don't know.

Lem   1:56:07
Yeah, because uh, as you can see, this should already be processed.

Bryan Wolf   1:56:12
Be working OK.

Lem   1:56:15
Yeah, the the, for example the filtered articles. So yeah, this one. So there should already be a process status there. Yeah, because this is the first step, right? So that means it didn't trigger the.

Bryan Wolf   1:56:25
Huh.
Yeah.

Lem   1:56:32
Scenario. So let me just think about this. Yeah, I think it's on the Google Apps side. Apps Script. Maybe we put on the wrong.

Bryan Wolf   1:56:46
Let's just go through and then go.

Lem   1:56:56
Yeah, let's, uh, try it. Uh, what's this?
No, this is already on content formatter, so we should be back on the content aggregator because we would be creating the document first. Yeah, this one. So let's try it to run once.
If yeah, OK and then.
Yeah, let's try to trigger it again from the spreadsheet. So let's try it. This should. Yeah, the on the social media post. So that would be the end. Yeah, the last one. Yeah, this one. So just click.
And I guess again.
Um.

Bryan Wolf   1:57:49
It starts talking.

Lem   1:57:51
Social media posts.

Bryan Wolf   1:57:53
Hey.

Lem   1:57:55
So can we?
Hmm.
Can we go back to the make.com if it trigger? Yeah, it's not catching it. Uh.
It's not catching the hook properly. Uh.
Um.
Uh, let's go back to the Google Apps script. Uh, let me just check the Can I see the G social media post? It's actually good.
Uh, Forest Mario? Yeah, social media post.
I'm not sure why this is not working.
Uh uh social media post GG Uh 7.
And then the web hook is good.
So, so on G, where's the word here?
Uh.
Uh, social media post G.
Is it 7? Let me just check.
5-6, Yeah, 7.
Social media posts.
Colon G.
Yeah, it should work. That's odd. Can we try to create another trigger here on the Google Apps script? So let's go back to the.
Uh, triggers.
And then.
Uh yeah, add trigger on edit.
Then click save.
Oh, it's actually around 10 forty-five AM.
Yeah, it actually run.
Huh.
But it it's not processing correctly I think.
Mm.
Oh, can you?
RG.
Can you go back to the again to the Google Apps Script code? Then let's try to click the debug debug button if it's working good on the Apps Script.

Bryan Wolf   2:01:14
I'm sorry.

Lem   2:01:15
Yeah, this one. Yeah, on the editor.

Bryan Wolf   2:01:18
There are executions.

Lem   2:01:19
I know on the editor on the yeah on the code editor up script code then just click on debug. So on the after the save run and then there's like a debug so there's.
Just try to.
Can you click that one? The. Yeah, this one. Yeah, that one. Yeah. So there's no break point. So it's actually good. I'm not. I'm not sure why. Oh, let's try to turn off it for now on the mix site and then just.
So that we could know, yeah, uh, turn off. Let's try to turn off this one.
Yeah, then OK, uh, let's go inside this content aggregation.
Um.
OK, then.
Let's just copy.
Can you copy it again? Let's just try to maybe something. Copy the webhook on the yeah here on yeah this one, then paste it again on the App Script on G.
Yeah, this one.
OK.
Yeah, I think it's the ROX. Yeah, a while ago it was ROXR. Then click save.
um can you click save yep then
Yeah, I think this should be.
Yeah, let's try it again and trigger it are on the. Let's run it once on me, OK?
And print it once.
And then click the yes again on the social media post on this Google sheet.
Yeah, just click again.
OK, so that should trigger. Let's go back again to the make.com.
Yep. So it's already triggered. Yeah. So there was one letter that was, yeah, it had that was added on the hook. So that's why it didn't it wasn't able to catch it.

Bryan Wolf   2:03:41
Probably not really.

Lem   2:03:50
But yeah, this is good. This is already good then. So for that one you could just double check for the other, let's say other automation if it's not working. So maybe the hook is.

Bryan Wolf   2:04:06
Off.

Lem   2:04:06
Yeah, there's like a missing letter or something. Oh.
Um.
Crap. Room number. Oh, that's odd.
Uh.
Social media content.
Right. Can you go back to the?
Social media post.
Yeah, we already included the.

Bryan Wolf   2:04:42
OK.

Lem   2:04:46
Uh.
Um, can we go back to the make.com and check the where did it stop?
Update status process.
Here see well required parameter row number. Can you go back to the search social media content on the I I don't here on the make.com beside the.
Uh, no, no. Uh, can you go back again?
All right, it was already gone. Yeah, just here. And then content creation. And then I think it was on, yeah, on the history. Can you?
So let's check the the Google sheet beside the error.
On the make.com.
Uh yeah, there's the yeah, this one. And let's check the data. I I want to see the data on the search.

Bryan Wolf   2:05:56
I I see that though, this thing right here.

Lem   2:05:59
Yeah, yeah, on the on the search social media content, the beside that one, beside the that one, yeah, this one, yeah. Can you check the like the data coming in?
Uh, Nope. I just uh.
The Yeah, that one. Yep. Yeah. So as you can see, there's no bundle. Um.

Bryan Wolf   2:06:20
Mhm.

Lem   2:06:26
Can you click this one the Google sheet so it can't find the?
Particular, yeah.
Oh right, you need you copy. Did you duplicate the new sheets? So actually this new sheets is not yet mapped correctly I think.

Bryan Wolf   2:06:37
You mean like out? I gotta. I gotta remap it.

Lem   2:06:52
Can you go back on the, yeah, this one and then, yeah, I think the spreadsheet is not.

Bryan Wolf   2:07:02
Oh, you're right.

Lem   2:07:03
Yeah, so uh, it's actually getting the wrong.
Yeah, it's actually getting the wrong. I think this is the same for all. Can we check?
Yeah, we need to.
Oh, just that that one. Oh, I think this it's for only that one, right? Yeah, I think only for that one. Let's just double check the other ones.

Bryan Wolf   2:07:21
Yeah.

Lem   2:07:31
Uh, OK.
OK.
Yep, uh, all good. So just save it and yeah, we could run it again.
Yeah, so there's the other one. Oh, before we run, can you go back to spreadsheet again? Let's delete the process because I think there's like process on the filtered articles and the other the status is already processed there, so it won't actually pick up on the.
So can you go back on the filtered article spreadsheet? Uh.
Uh oh.
Still don't have the process also on AI tools.
That's odd. Yeah, this one. Yeah, this is process. So you can you you can delete the. Can you delete the process there?

Bryan Wolf   2:08:36
It's processed.

Lem   2:08:43
Oh right, the filter articles won't be processed yet until the last part. Yeah, that's right. And then prompt of the day. Can you reject? Yes, this good. OK, we could trigger it again on the make side, make.com and then just run once.

Bryan Wolf   2:09:00
Should I do that one or all of them?

Lem   2:09:01
OK.
No, just go back in. So we could just trigger it manually. Yeah. And then click. Yeah, because we already have a like a trigger queue already on queue. Yeah, just existing data. Yep, that's right.

Bryan Wolf   2:09:14
Use existing data, right?

Lem   2:09:19
'Cause that's the the a while ago we clicked the yes, so it's saving the queue. Hit on queue.
Then Yep. Um.
I think it's already good, OK.
So the one that was post was on social media a while ago, right?
Then.

Bryan Wolf   2:10:18
Still going?

Lem   2:10:19
Yep, yeah, because there's like a 5 second delay here every. Yeah, every time it passes through the Google sheet. So it loops around it and then.

Bryan Wolf   2:10:24
Mhm.

Lem   2:10:33
So that it won't we won't get, uh, rate limited.
Yep, I think it's already. Yeah, it's, uh, in a few seconds, then it'll be done.
Uh, create Google Doc as just create and go and use.
Hmm.
Huh.
It's actually taking a long time creating the document.
okay yep so now we have the document on our newsletter so we can check it that there okay

Bryan Wolf   2:12:01
Perhaps.
Let's just go.

Lem   2:12:06
Um.
Yeah, we could just check. Yes. Yeah. So now we could. Yeah, that other automation should trigger. So yeah, we could just check that.
Yeah, so this is the.

Bryan Wolf   2:12:24
Or copy.

Lem   2:12:25
Yeah, let's just wait for it. So it should trigger.
Already if the hook is correct. Um.

Bryan Wolf   2:12:37
It's usually Bravo. It takes a while to remember.

Lem   2:12:38
Um.
Yeah, but if it already finishes this, the test e-mail status there should be sent.

Bryan Wolf   2:12:48
Oh.

Lem   2:12:50
So uh, but it is the content formatter. So this is actually the yeah, we could also check the hook here webhook.
Yeah, OK and.
Yeah, copy this one. This is for.
Um, you said their drafts. See, I think.

Bryan Wolf   2:13:13
I hope for me.
Uh, Sunday morning.

Lem   2:13:17
Yeah, new standard drafts.
No, I think it's above that one. Yeah, it's on newsletter drop C, so it's on the Webhook URL. Yeah, this one. So it's the same.

Bryan Wolf   2:13:33
Sick. Let's just.

Lem   2:13:37
GO. Oh, it's different. Huh. Oh, it's the same. Yep. Yeah, I think it's the same.

Bryan Wolf   2:13:43
So see.

Lem   2:13:44
Yeah, yeah, I think it's the same. So that should be good, I think.

Bryan Wolf   2:13:48
It's some.
OK.

Lem   2:13:51
Oh, OK, yeah, yeah, yeah, yeah, that's good. So that we, uh, we should receive a e-mail.

Bryan Wolf   2:13:52
That's it. See, she takes a little bit.

Lem   2:14:00
And then
Yeah, the test e-mail.

Bryan Wolf   2:14:09
Hello.

Lem   2:14:12
Oh, that's odd.

Bryan Wolf   2:14:14
Yeah, yeah, we love.

Lem   2:14:17
Oh, what happened there?
Hmm.
I think it bleed. Uh, yeah. Church PDS. Uh.

Bryan Wolf   2:14:33
I could just put a photo here. Can't put the phone up again, but I don't think it's.

Lem   2:14:39
Can you? Yeah.
I think this is on the formatting on ChatGPT.

Bryan Wolf   2:14:45
Yeah, it is.

Lem   2:14:47
Uh.

Bryan Wolf   2:14:52
This is good though.

Lem   2:14:54
Yeah, what? Uh, yeah.

Bryan Wolf   2:14:55
Other than this.

Lem   2:14:58
I think it glitch out there. Yeah, the.
On yeah you don't just no need to click yes there because it will actually send to a list. So actually we could check the history here on the yeah this one. Just click back and then we could check the history on the yeah this one.
Yeah.
OK.
Um.
Can you?

Bryan Wolf   2:15:35
And get bigger.

Lem   2:15:40
Not sure why it added that one. It actually triggered twice.
Uh.
Can you go back to our spreadsheet? I'll just, uh, check why it triggered twice.
Oh, no, it's just one.
OK and
Yeah, that's odd. The format content, the content formatter is, yeah, broke. Where can we check that out? Oh, right on. Can you open the Bravo for this this account?
We could check the output on Bravo actually, if that's just a one off or something.
Uh.
Glitching out. Let's see. Yeah, on this campaign. Yeah, this one. So can you. Oh, Twister 2.
Uh.
Yeah, this.
It is. Why is there to?
Can you?
Open the other one, then yeah, preview test.

Bryan Wolf   2:16:58
That's why the administration.

Lem   2:17:04
Yeah, it's actually good. Not sure why.

Bryan Wolf   2:17:07
I could just have a little moment.
This one.

Lem   2:17:11
Yeah.
Yeah, that looks good.
Wait, uh, I think, yeah, it was triggered twice.

Bryan Wolf   2:17:26
I just kind of like to close down.

Lem   2:17:30
Maybe uh.
OK.
Can you go back to the e-mail again on this? Because I think there's two emails that were sent.
Yeah, this is, yeah, this is actually 2 emails. Oh yeah, maybe. I think that's why it's actually, yeah, because the other one is, yeah, the the other one, yeah, it looks good. It was sent twice.

Bryan Wolf   2:17:52
Oh, Yep.
That is why. That is why.
Oh, this one's fine. Yeah, this one's good.

Lem   2:18:03
Yeah, yeah, it's what's actually sent twice. That's why it's.

Bryan Wolf   2:18:08
Yeah. OK. Well, that's good though.

Lem   2:18:09
Yeah, it it dish out. Yep. Yeah. Yeah. I think we clicked it twice, I think. Or yeah, because it's sent twice. Yeah, yeah, yeah. I think it works fine. Yep.

Bryan Wolf   2:18:17
Yeah, I think it works fine then. I think it works fine.
Let's just uh.

Lem   2:18:26
Yeah, it actually, yeah, we it it triggered twice.
On the.

Bryan Wolf   2:18:36
They were good though. Um.

Lem   2:18:37
Yep. Yeah, I think, yeah, I think it's, yeah, it's fine. And yeah, if you you would, yeah, I think we shouldn't turn it on the like the.

Bryan Wolf   2:18:38
I know you should get off the room this time.
No, I will keep it off.

Lem   2:18:52
Yeah, the screen. Yeah, yeah, just turn off it for now, for especially the eye reader. And yeah, the scrape so that it won't get on you. OK.

Bryan Wolf   2:18:55
Yeah, well, tomorrow, yeah.
All right. Oh, sure. I was just so much I want to. All right, love.

Lem   2:19:08
OK, Brian.

Bryan Wolf   2:19:09
Thank you so much. Uh, I'll talk to you tomorrow.
Yeah, yeah, sounds good.


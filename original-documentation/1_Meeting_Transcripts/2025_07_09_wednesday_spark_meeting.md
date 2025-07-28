# Process Automation Workshop (24)

**Original File:** Process Automation Workshop (24).docx
**Extracted Date:** 2025-07-09 (Wednesday)
**Converted:** 2025-07-28 11:40:50

---

Transcript

July 9, 2025, 12:59PM

0:19
Morning.

Nicholas Westburg   0:25
Morning.

Bryan Wolf   0:27
Morning.

Nicholas Westburg   0:29
Yes. Can you hear me?
1.

Bryan Wolf   0:32
Yep.

Nicholas Westburg   0:44
Did you meet with your dad or did he do it like?

Bryan Wolf   0:48
No. So today he's got time this morning. He leaves. He leaves at 1:00 today, right? So he we got on the call last night and he rambled a little bit and gave me some direction that he wants to do. Really. He just wants me to go over like.

Nicholas Westburg   0:49
I saw. I saw there's some meeting.

Bryan Wolf   1:03
The **** we've been doing rewatch, rewatch the vods and lamb going through stuff. And then I asked him to give me one more process to work through 'cause he's not gonna get back till Monday. So I figured what we're gonna work on today is what we worked on yesterday and then.

Lem   1:08
Oh, hey, guys.

Bryan Wolf   1:21
We'll do that Thursday and then Friday we'll introduce something new or I don't know. We're gonna have to wait and find out, but yeah.

Lem   1:28
OK.

Nicholas Westburg   1:29
Lab, you know what I did?

Lem   1:32
Yep.

Nicholas Westburg   1:32
So are you? You're familiar with Cloud code, I'd imagine. Have you seen it?

Lem   1:37
Cloud code or uh.

Nicholas Westburg   1:40
Like the anthropics clog code like your new uh.
MCP or whatever. Satellite term. Maybe not. I don't know anyways.

Lem   1:51
I haven't. OK. Haven't. Yeah, haven't still.

Nicholas Westburg   1:56
So they make.com has this really cool or make.com MCP server. So I'm in this environment via the API and I've hooked up the make so I can literally just write a command that we I can see.

Lem   2:05
OK.

Nicholas Westburg   2:14
You know, I just did it this morning, so I gotta play around with it, but just to see all the scenarios and stuff like that, which is actually really, really, really cool.

Bryan Wolf   2:17
It.

Lem   2:23
Oh, that's yeah, to clarify, like you could access the automations on that MCP server through your command line.

Nicholas Westburg   2:32
Oh, yeah. Yep. Yep.

Lem   2:36
Oh, that's yeah, that's awesome.

Nicholas Westburg   2:36
And it's like an, it's an agentic, like cloud codes agentic, right? So.

Lem   2:41
OK.

Nicholas Westburg   2:43
ICD into the folder, right? The MCP and then I use the API from the organization, the teams organization and it just has access to all of them. And being that it's like an agentic tool, it can.

Lem   2:50
OK.
Oh, I see.

Nicholas Westburg   2:59
Process and analyze and then I can connect other MCPS to it at the same time to look at the flows. I haven't messed around with it yet, but I'm excited. It looks promising. I'm still setting it up. Morning.

Lem   3:08
Mhm.

Peter Wolf   3:10
Hey, guys.

Lem   3:10
Yeah. Hi, Peter. Morning. Yeah, I haven't still, like, dived into that. But yeah, that would be.

Nicholas Westburg   3:23
Yeah, we go over whenever you have some free time. Just, you know, you and I, pretty cool.

Lem   3:24
I think I.
OK.
Yeah, that, yeah, that's actually, yeah, pretty cool. Would be much easier, right, to like connect to the all the flows and then it will just decide that. Yeah, I just wonder on how to set the automation there if it would be like a trigger of it, it's all like a trigger.

Nicholas Westburg   3:37
Yeah, yeah, definitely.

Lem   3:49
The trigger button.

Nicholas Westburg   3:49
It might be slash keys. Literally might just be slash keys.

Lem   3:53
Um, let's see.

Nicholas Westburg   3:55
So like slash and then like since you're in the folder, it would be like, I don't know, I haven't. I haven't got set it up yet. I plan on doing that later today.

Lem   3:56
Sure.
OK, yeah, yeah, that's pretty cool. It's actually pretty cool. Yep.

Peter Wolf   4:09
All right, so I'm certainly interested in hearing what you guys are talking about, but I got a very short period of time here. I'm probably going to have to jump off early. I'm flying to Germany and I have someone. I have Justin, who's going to join us at 10:30. I'm not sure if that's still going to work, but hold on.

Nicholas Westburg   4:28
Yeah.

Peter Wolf   4:29
One second. Let me, uh, see what he just chatted me about.
Yes, we have a meeting with a client at 10. He's gonna try and jump out at 10:30. I have some other stuff I gotta get done.
I don't know. We're going to see how this goes. So let's, let's, let's see where we are on the on the existing process that we're talking about the the contact database and then I'll talk about another process flow and that's where I was going to bring in Justin.

Lem   4:59
OK.
OK.
Yeah.

Peter Wolf   5:15
To to get involved in that.

Lem   5:19
Yes, so now I've uh.
Added the so I just build it still on the same like Google sheet so I just added here now updated like updated column so so I've yeah so for the AI it actually can't differentiate like.

Peter Wolf   5:34
Other columns? Yep, got it.

Nicholas Westburg   5:40
Where, Kelly? Come on, Kelly.

Lem   5:42
It's it's getting it. It's having a difficulty on differentiating the role and like the like what's the form. Yeah, the formal title. So what I did is I've just added a role here and then the industry so that it will get the context for just the industry like finance like.

Peter Wolf   5:50
Call title enroll.

Lem   6:02
In consulting or something like that or treasury or something and then for the role it would be like the manager or like the CEO something like that. And then for the yeah this is so the add data I've.
The prompt now is pretty long.

Peter Wolf   6:18
Can we, can we maybe change that to to not industry but to operational area or something? Industry feels to me like it's going to talk the business like my my company is a fintech company, but the person that works there was going to work in the HR operational area or in the.

Lem   6:26
OK.
Oh, I see. Yeah.
OK.

Peter Wolf   6:38
You know, Treasury operational area. So just make a note of that. I think that would that would work better for me and I think hopefully should align better with what I'm really looking for.

Lem   6:43
OK, Yep.
OK, yeah, so yeah, I've added the, so I've now updated the prompt with the. This is now pretty long, so it would actually like parse or process the the information from like like the.
The conversation words and then for example here on the task one, so this is adding data. You will receive plain unstructured text describing details about the person, then parse the text and extract. So the required fields are here and then I've also added the process even if the data is in plain and can infer.
In friend assign information so it will just put unknown if it's it's missing or and then I've added also that example input so that it will have contact contacts for for example this one add a new contact so this one.

Peter Wolf   7:31
Yep, Yep.
Yeah.

Lem   7:42
Is the one that you've given and then for the output, yeah, the output would be and then for that also the adding of data. I've updated it so that it will also process the, parse it and process the like the.

Peter Wolf   7:43
Yep. And then you show what the output would be. Yep. OK.

Lem   7:57
Fields and then I've updated for the find data I've added here like the columns. So now it could actually see check the columns via like the fields. So what I did here in the prompt is it will just.
Send up a word, just one word so that it it will not be confusing also for the like the Google sheet search search function. So I've added it on the on the find data task and then what will happen is it will.
Trigger this particular tool right and then it will add just depending on the message. So for example if we mention the name so it will add the name here and then if we if we mention the appearance so it will add like the one word appearance here so it will choose for example he's he was always wearing.
Black glasses and he has black hair so it will just choose like the word like black or hair or something like that and then it will search it on our database. So that would be like a first search filter so it won't get all of the all of the rows.
And then if there are multiple, multiple, multiple results, so that would be fed into ChatGPT now. So ChatGPT will get the context which is the query. So I've added here the query message, the original query message.
On the this one on as as an input so I've also added that on the prompt then it will cross reference that to the the information that is found from the Google sheet query. So we have like A2 filter here. So now we first is the filter using the words like like just one word.
And then next ChatGPT will filter like the final result if there are multiple multiple like multiple persons and then depending also on the context of the message. So if we need like all the lists of the company so it will also send all the lists to the company.
So to test this out, uh, let's.
I've already tested also this one a while ago, so for example let's check the database. So for example I will ask like a vague for yeah, so there are a lot of people here that has glasses and then I I will ask it.

Peter Wolf   10:19
Yep.
Yeah.
Yeah.

Lem   10:37
OK, so that will uh.
Can you find the person that I met with glasses on glasses?
Then as I remember, he joined one of our sessions at HIMSS. So if we enter that one, what will happen is that other.
No, just this.
Info this.
Mm.
Yeah, so as you can see, let's double check Sophie Klein. So this is the yeah, so ChatGPT was able to get Sophie Klein even though there are like like lots of glasses and then like there are.

Peter Wolf   11:40
OK, can you can you say the other way and say can you tell me the the person that I met with glasses? Make it that generic right and see what it says.

Lem   11:47
Yep. Uh, can you?
Get the person with.
Glasses on my.
All the yeah, so yeah, it it's asking more like more questions. For example, do you want me to provide details on all contacts with glasses? So yeah.

Peter Wolf   12:13
Yep. So how about you say no? Just tell me their their name and and their their appearance information.

Lem   12:24
Um, yeah, so uh, for.

Peter Wolf   12:24
It has to clarify, do you want me to provide details on all contacts with glass? Oh, I'm sorry, I misread that. Hold on. Or are you looking for a specific individual with glasses? If it's specific, any additional details? So just say no, not specific. Anybody with glasses. I thought it was asking what it wanted as output.

Lem   12:30
Yeah, yeah.
Yeah, so, yeah.
Yeah. So basically that it's asking here because yeah, yeah, it it want, yeah. So like multiple or one, so.

Peter Wolf   12:45
I understand what it's asking now. I'm sorry, I just misread it.
Just say no, don't. You don't want specific. We're gonna say anybody with glasses.

Lem   12:53
Yeah.
Want anybody with?
Access.
Oh, I should said here like the yeah, if I think if we said anybody it will just input one or if we yeah, so it would input one. So if we yeah, so if can you give me everyone with the glasses?

Peter Wolf   13:12
We want everyone with glasses, right?

Lem   13:27
Because the yeah, our message is also being sent to the other ChatGPT for the filter. So it would depend also on what we are the context of what we are seeing. So I I will also show on the back end on what's happening because.
Yeah, I think it will also help on its.

Peter Wolf   13:44
Yeah.

Lem   13:50
Yeah, so as you can see here are all the people with glasses. So I've this particular like format is a static, so it will feed all of the. Yeah, that's right. Yeah, I yeah, I define this format as static.

Peter Wolf   13:57
Yep. So you define that format. You define that format. OK, So what if you change it and say, just give me the names, the names of the people and the names of everyone with glasses. And hold on, because I want to throw it off a little bit, right? And say.

Lem   14:15
Yeah.

Peter Wolf   14:17
And and their and their role. So the names of everyone with classes and their and their role.

Lem   14:21
Give me any more?
Give me the names of everyone with blesses and just their role.
Yeah, so yeah, actually outputted it. Yep, yeah. And I also, yeah, I've used GPT 4.1 mini here because I'm I'm not using the nano one because we are not already like finding it on the whole database.

Peter Wolf   14:43
Good. Yeah. Yeah, that looks good.
Uh huh.

Lem   14:59
So yeah, so it's actually good. It's picking that up and let me also show the back end on what's happening. So basically this what's happening is it's just getting the like one word filter for example this one so.
We have like 9 filters right? Because we have 9 columns. So uh we we if we check the filter, so it's adding the filter here on the.
This one so the appearance has like the glasses so it it chosen the glasses as the like the keyword and yeah so I think yeah it's only because we added the only the glasses so it just added the glasses on the keyword and then.

Peter Wolf   15:36
Right.

Lem   15:43
Uh, the yeah, the bundle here.

Peter Wolf   15:45
So you had to map it. You had to map it to tell it that when I spoke natural language, it should categorize those items that I asked, then bucket them into the columns and then determine if I'm trying to query.

Lem   15:53
Yep, yes, yes, this.

Peter Wolf   16:00
Which query? Which column am I querying and put that item in there? But if I said the person, yeah, if I said the person with the mustache, beard and glasses, it would have put mustache, beard and glasses in there.

Lem   16:04
Yes, that's right. Yeah.
No, for just one category it would just yeah, I think it would also put it on if it's just on one category. So let's test it for example.
Glasses and then tall. So for example glasses and tall because I've added here it actually contains. So if we tell it, can you give me a list of just names?
With glasses and tall people, so it should pick up the all the glasses and like the tall appearance here.
Um, because I've added actually the.
And yeah, yes, in appearance.
So I'll check the because I've actually prompted it here that it would just check one. It will just input one word on the query.
And the person on the.

Peter Wolf   17:26
Because I don't think that's, I think that's gonna be too restrictive. Just one word on the query, right?

Lem   17:32
Only, yeah, because the first test that I've.

Peter Wolf   17:34
One word, one word per category or per feature. Like if I said the person that was the that was the colleague of Tom and and had the glasses, it would put Tom in the colleague or in the relationships.

Lem   17:39
Per yeah, per per feature. Yep, that's right.
Yep, that's right.

Peter Wolf   17:51
And then it would put the glasses in appearance. But if I put more than one thing in appearance, it couldn't, it can't handle it. So you've got tall, dark skin and and and neat. And if you had two people, one said there you got two that are tall, right? You got tall as Tom is tall and you got Amir is tall if I said tall and.

Lem   17:58
Um, it will.
Yep.
Yes.

Peter Wolf   18:11
Wears formal shoes. Then I would only want to get Tom, but it but you have tall and dark skin. But if you only use tall, it would pull back all of them, right?

Lem   18:19
Yeah.
Yeah, it would pull back like to the two people, right? But we have ChatGPT for the next filter. Yeah, that's right.

Peter Wolf   18:26
And then the second filter would apply, and the second filter would then apply the deeper details. OK, so you're using a basic filter of some single word that's a critical word to get the database narrowed down so that when we apply, we're not applying it to 1000.

Lem   18:31
Yeah, the deeper one and it yeah, so we fed also here.
Yeah, narrowed down. That's right.

Peter Wolf   18:46
And I may be applying it to many more than I want, but certainly substantially fewer. But it's just not using all the criteria in the filter. OK, I like that. That works.

Lem   18:46
Yep, that's right. Yeah.
Yep, that's right.
Yep. So yeah, yeah, that's right. So we're just like narrowing down so that for example like this, the glasses one, we actually have like 5 bundles. So it actually picked up the five people from from our database, but if we added there like the.

Peter Wolf   19:08
Yeah.

Lem   19:16
Company Optima Finance. So what will happen is it will it will still get like the five bundles and then ChatGPT will be the one who would extract I mean because the company is like straightforward but for example the vague one like the appearance so the ChatGPT would filter them out.

Peter Wolf   19:31
Yeah.

Lem   19:36
And it will choose like the right, like right data for that one because yeah, for the like the vague ones. So yeah, so it's like for the first filter we're narrowing it down and then for the second filter ChatGPT is choosing.
The right, right criteria, yeah, specific and yeah, so based also on the query message. So we have here on the content if you can see is we have the.

Peter Wolf   19:55
To get very specific, to get very specific in selection.

Lem   20:09
This one so message input. So this one is coming from the our message on like the assistant. So this is coming from there. So this is like the second context. So for example we put here give me everyone with glasses and like give me the.
The person with glasses and the one that I met on a on an event something so that is like a like for example two events. So it will just choose like for example all the glasses and then ChatGPT is the one who will filter out to this.

Peter Wolf   20:44
So then just don't understand. So the first pass is only going to be 1 characteristic. If I said I met them at the conference and they had glasses, it's only going to pick one. It's going to pick the glasses or it's going to pick the conference. It's not going to pick both. It's not going to include both in that filter.

Lem   20:44
Yeah.
Yeah, yeah, that's right.
Uh um, if.

Peter Wolf   21:01
So the first filter is only filtering on one characteristic.

Lem   21:06
No two. It's actually filtering. It can filter out nine. Yeah, just one per cut characteristic. Yep, that's. Yeah, yeah, that's right. Yeah, because I I tried it as a phrase and Google Sheets like search function is.

Peter Wolf   21:08
It's filtering on one per characteristic, just not more than one per characteristic, but up to one per characteristic, OK.

Lem   21:22
Actually, like, uh, like, uh, it's not picking up.

Peter Wolf   21:23
And if my phrase doesn't exactly match the way it's stored, then it won't work, right? So I think that's fine. I think the single word is fine. You're you're taking a keyword from the from the from my request. I guess the concern is does if the keyword is.

Lem   21:29
Yeah, yeah, it's just narrowing.
Yep, that's right.

Peter Wolf   21:41
A nuance and it doesn't quite match, right? Yeah, that's the only thing is if I if glasses is clear, beard, mustache, that's clear. But you know, if we said like, you know, where's where's sharp clothing or, you know, dress is fancy.

Lem   21:47
Yeah, so um.

Peter Wolf   21:58
And then later on when I say someone who dresses is well dressed and the word is fancy in there, then it's not gonna match, right? So it's not. It's using a true word search instead of a a context or a or a kind of a.

Lem   22:03
Yeah.

Peter Wolf   22:14
I don't know. Yeah, more broadly assessing it based on kind of AI logic. It's doing the true word search in that first search.

Lem   22:21
Yeah, yeah, that's right. Yeah.

Peter Wolf   22:24
Right. So that's the only risk that is somehow my word to be cautious that my word actually doesn't exclude that person. Because if I said and they are, they're a good dresser and and it puts in good dresser and instead what I said was a fancy dresser or well dressed.
Then it's not going to do it. Now again, I think that's a a good example of how we get screwed up. I don't think I would be doing something like that, searching by the guy who's the good dresser. But yeah, so I I think we're probably OK.

Lem   22:43
Yeah.
Yep, that's right.
Yeah, I I think, I think for that, yeah, it would need like the vector store for that one. It's just that I'm not really like, Yep.

Peter Wolf   23:02
Yeah. OK. All right. So there's limitations, but this is a reasonable, manageable model. It's not going to be, just can't be completely, you know, robust. So I I can handle that.

Lem   23:12
The vague. Yeah, Yep, that's right. Yeah. So yeah, the only limitation for here is if it's the like the parameter here is like very vague. Yeah, it would be difficult to filter out. So I think what?
Because it would really depend on like the data that we have right? Like for example we could use like the like the vector style like the vector store like rag style of getting the data but we would wouldn't put it on a tabular style so for example like a document so we would put like.

Peter Wolf   23:46
Yeah, let's stick with this. I I got you. Let's just stick with this. There may be other scenarios in which in which the the kind of vector form would work better, but this is this is better for my needs for sure right now.

Lem   23:47
Their names and yeah, yeah, so.
Yep.

Peter Wolf   24:00
Um.

Lem   24:00
Yeah, so yeah, yeah, we would just need like for the columns and just editing. So this one is just actually like test data. So I just ask ChatGPT for like test data, so.

Peter Wolf   24:13
Yep.

Lem   24:17
All of this are, yeah, just so Yep, basically.

Peter Wolf   24:20
Can you can we? I I think I added another column was introduced by.

Lem   24:26
Yeah, so I've just yeah, this one business relationships introduced by personal relationships, categorization of. And I think we could also add more context here on the prompt, for example business relationships. So I could add here like.

Peter Wolf   24:31
Yeah, yeah.

Lem   24:43
Like more context or you could like we could ask like ChatGPT on how to like format it because the only thing here is we should just explain it like thoroughly to ChatGPT so that it could get the context for this particular feed so.
I think that's more important because of course it would need like a context right for for example this one. So business relationship, personal relationship, then yeah, categorization of contact.

Peter Wolf   25:14
So I was thinking in business relationships, I'm thinking like, you know, works with John Smith in that department or is is the is the boss of Jim Jones or is, you know, reports to.

Lem   25:28
Yes.

Peter Wolf   25:30
Yeah, Axel Arabian. That's what I was thinking about business relationships with some kind of hierarchical or or kind of organizational relationships.

Lem   25:33
Yep.
Yes, we Yep.
We could just uh.
Yeah, so if we pull that data, I we could just add it here on because I I think I've added here a context also. So yeah, this one. So we could add the context here. So for this one this like a straightforward right? But.
If we move on more like like maybe this would confuse Chachipiti, so we could just add here the context for it and then yeah, Chachipiti would think would get that one.

Peter Wolf   26:12
Why don't where are you saying add the context where not without without adding a new field?

Lem   26:16
Uh.
No, we we would add the field and then we would like put the context on like a definition definition for this one because for example this one personal relationships and family details like it's it's pretty like very near, right? Yeah, it's.

Peter Wolf   26:21
Yeah.
Yeah.
That's confusing. Yeah, yeah, that's not clear.

Lem   26:39
So I think ChatGPT also would have a hard time differentiating these two. So I think what we can do is for example for personal relationships we could just add also the family details here so that if they if the like the field is.
Near or something. Uh, we could just merge them and then um.

Peter Wolf   27:00
OK. So we'd have more than because then let's just say, you know, it becomes more like that other comments box though, right? I mean, it's going to have a variety of miscellaneous points in there. And so we're already saying you're not going to really.

Lem   27:14
Yep.

Peter Wolf   27:18
Filter on it to to other than to say you got to pick one keyword or something from that area. So if I said um.
You know, someone's wife in their family relationship, but they also had, you know, that they had three kids or whatever. That's that's what I'm thinking about, right? When information that we put about they're married to this person, they have three kids, their mom's dead, their whatever.

Lem   27:41
Yep.

Peter Wolf   27:47
Whatever something like that. It's giving me a context to their family situation.

Lem   27:50
Oh, OK.

Peter Wolf   27:53
But I think you could put personal relationships and family details. I think you could probably put together. And again, it would just be about about their family structure, kind of who are they, who are they married to or what kids do they have? I guess their kids names, if I was going to do that right there, they got three kids. Susie.

Lem   27:53
OK.
Yeah, that's right.

Peter Wolf   28:13
Johnny and Billy or something, right?

Lem   28:16
Yep. Uh, yeah, because I just add it there.

Peter Wolf   28:17
And then and if I did that and then I said what are the what are their what are their names. So let let's take that go back to your the the document you have and yeah, so relationships.

Lem   28:26
On this one.

Peter Wolf   28:33
Um.
So did you do you have multiple people that like the the Tom is Tom or is there is there someone that's added in here multiple times like in relationships?

Lem   28:46
No, I'm not sure because this is just randomized, so not sure if.

Peter Wolf   28:54
Because I saw you had used some of the names earlier, I thought maybe you made a couple specific, but like here's supervisors, Greg's supervisor, Greg Smith.

Lem   29:04
Yeah, we could just edit one here to uh, like put a similar relationship is that.

Peter Wolf   29:09
OK, so put put in there again, Supervisor Greg Smith, because I can see that down below, right? So that one right there 10.

Lem   29:13
Uh, this. Uh, this one. OK.

Peter Wolf   29:18
Yeah, in 10.

Lem   29:19
And then put it in 10.

Peter Wolf   29:21
Intend make that supervisor Greg Smith as well.

Lem   29:24
OK.

Peter Wolf   29:28
And then somewhere else can you take, let's see under 1515 put in there.

Lem   29:38
Yeah, this one.

Peter Wolf   29:42
Supervisor Greg Smith. Hold on a second. No. So I'm saying supervisor of Greg Smith. You can't have multiple supervisors. You would say, let's say works for Greg Smith.

Lem   29:53
Works for.

Peter Wolf   29:53
First for Greg Mith and then U in the intent change that one to works for Greg Mith as well.

Lem   30:01
In turn, OK, this one.
OK.

Peter Wolf   30:07
So now can you go over and and in your question and say, can you tell me everyone, everyone that has a relationship with Greg Smith?

Lem   30:19
Everyone who has relationship with Greg Smith.

Peter Wolf   30:33
Is this a show me what their who's his boss? And so they say here change. Did I only give us one person?

Lem   30:43
Yeah, I think it. Here's the information for our contact was relationship with. Yeah, just one Maya Lee, I think, yeah, this one. So let's can you give me?

Bryan Wolf   30:44
Yeah, it did.

Lem   30:59
Or.
Yeah.
Oh yeah, so it actually added. If you'd like me to find more contacts with relationships, please let me know.

Peter Wolf   31:15
OK, so let's let's just say I say tell me all contacts, all contacts that have a relationship with Greg Smith.

Bryan Wolf   31:15
Yeah, nice.

Lem   31:20
Yeah, so it Yep, it actually given three, uh, the ones.

Peter Wolf   31:23
OK, can you change it and just say tell me all contacts that have a a relationship with Greg Greg Smith and tell me their relationship to him?

Lem   31:31
Uh uh what? Tell me.

Peter Wolf   31:34
Give me a tell me all, find me all contacts and have a relationship with Greg Smith and tell me what the relationship to him is.

Lem   31:38
Tell me all.
Our relationship.
Smith and tell me what their relationship to me is.

Peter Wolf   31:52
With him is or two. Yeah, Yep, that's good.

Lem   31:57
Oh, this is, this is right. And tell me what the relationship.

Peter Wolf   32:00
Or tell me, tell me what their relationship to him. Tell me what their relationship to him is. Yeah, OK.

Lem   32:02
To him. Oh, all right, right. To him. OK, to him is.

Peter Wolf   32:22
So relationship to Grace and mainly company. OK, Yep. So now it's giving us more information, but the first thing it's doing is giving us a relationship to Grace Smith, right? But that only gave us two and there were three.

Lem   32:25
Let's see.
OK.
Yep. Um.
Yeah, it's only.
More.
Is there more? Yeah, it's actually just given 2.
Are there more?

Peter Wolf   32:47
So clearly it's it's done that before, so I'll have to emphasize I want all of them, right?

Lem   32:50
Yeah.
Yeah, I think so.

Peter Wolf   32:55
So can you just enter it one more time and say please provide all contacts, all contacts that have a relationship with Greg Smith and only provide their name and their relationship to Greg Smith.

Lem   33:00
We find all contacts and our relationship with.
Smith.
And only provide their name and relationship to Greg Smith.
Huh. The only. Yeah, it only added two. No, I I think.

Peter Wolf   33:33
Again, only two. So it's not. It doesn't understand. It's not finding the boss or supervisor of Greg Smith.

Lem   33:42
It's because of the history. Maybe it's just pulling it out here. Let me just get the new chat if it.
Because it already.

Peter Wolf   33:57
And then go look at your filter. Go look at your filter because it should be looking in the relationship field for the word Greg Smith, which should find everyone.

Lem   34:02
Yeah, so.
Yeah, that's right. So yeah, so for example, this one, it just added one.

Peter Wolf   34:08
And maybe we need to give it instructions. Maybe we need to give it instructions to tell it to after it looks once, it needs to look again or something because it's not coming back with the full list.

Lem   34:21
Yeah, let me just check double check the if it actually filtered out the correct filter.
Yes, it actually filtered out four of them, but chat GPTS.
Contacts.
Yeah, it oh, it didn't send a message input. Yeah, so I think that's the issue. It didn't send a message input here, so it chat GPTA didn't have contacts, so I just added the one. I'm not sure.
Uh.
Yeah, so that this should be also passed to Chachi PT so that it would have more context. I'm not sure if yeah, I didn't add.

Peter Wolf   35:13
Oh, so it didn't even add that?
For the second filter, it didn't have guidance of what it was supposed to be looking for.

Lem   35:20
Yeah, so yeah, let me just try to change the model because sometimes if it's like a complex one, the the cheaper models have a hard time getting some like contacts there.

Peter Wolf   35:33
Yeah.

Lem   35:53
Yeah, so it only added two. Also, this red icon has set up a relationship with Greg. So it didn't have the boss, right?

Peter Wolf   36:04
It said supervisor of supervisor Greg Smith, but still says Greg Smith though.

Lem   36:08
Uh.
Yeah, yeah. So yeah, it still says Craig Smith. So I think the filter, let me just check if.
But did it filter out?

Peter Wolf   36:26
I guess you got to check the filter on both, right? The first one is did it select by Greg Smith and then if Greg Smith gave us.

Lem   36:28
Oh.

Peter Wolf   36:35
The supervisor one.

Lem   36:36
Yes, it actually added it. Yeah, it so it added the four bundles with the Greg Smith. So the filter here is, yeah, so the filter is Greg and then.

Peter Wolf   36:46
This is the first filter, yeah.
Yeah.

Lem   36:52
Yeah, the filter is just Greg, so that's right. And then yeah, so this one is ChatGPT. Oh, that's why it's GPT 4.1 nano. So yeah, it's it didn't get the context, but as you can see it, we actually inputted.

Peter Wolf   36:54
OK.

Lem   37:08
Given the four bundles, this one the yeah then yeah it did add so message input. Also we have please provide all contacts that have relationship but this is actually I've yeah GPT 4.1 so I think I need to change this model.

Peter Wolf   37:12
But somehow it didn't. Once it got the four bundles, it didn't understand that you include those.
OK, so let's make two changes. Change that to 40. But then let's also go into two other boxes and let's put Greg Jones in two other boxes.

Lem   37:38
OK, um, let me just.

Peter Wolf   37:39
So that it it finds the Greg, but it should get extras and then it should filter on the second one. It should get rid of them and only get the Greg Smiths and hopefully keep the supervisor one.

Lem   37:49
Yep, that's right. So yeah, so for this one, yeah, we need to have the more intelligent also Chechi PT. But yeah, I'll change this one. So for.

Peter Wolf   37:58
Got it.
Go to your spreadsheet and let's just put put in in 17, put colleague of Greg Smith. I mean, no, Greg, Greg Jones.

Lem   38:06
OK.
Color.
Oh, for Greg Jones, OK.

Peter Wolf   38:16
And then go down to to to 28 and put reports to Greg Jones.

Lem   38:25
Parts to.
Greg Jones. Uh, OK.

Peter Wolf   38:31
All right, so now if we oh, there's another one that says friend of Greg Smith, it isn't getting picked up.

Lem   38:39
Friend of.

Peter Wolf   38:40
Yeah, 29.
That wasn't getting picked up.

Lem   38:44
Yeah, Paolo Souza. Um.
Yeah, I think, oh, let me just check.
If.
No, I think it because we have 55, I think or.

Peter Wolf   39:04
It did.
OK, well, let's see what we get this time.

Lem   39:08
Uh, yeah, the Paulo Sousa. So it actually picked that up, but that that step is the one that it didn't correctly.

Peter Wolf   39:12
OK.
So how many did he get this time in the first in the first filter?

Lem   39:20
Uh four. So the filter that it chose is Greg and then it actually get the.

Peter Wolf   39:26
But should have gotten a lot more than for now, right?

Lem   39:28
Yeah, it would. It should get a lot more than four, that's right.

Peter Wolf   39:31
It should get six at least.

Lem   39:33
Yep, so let me just so I'll ask the same this one. Please provide all contacts that have a relationship with Greg Smith and only provide their name and relationship to Greg Greg Smith.

Peter Wolf   39:44
Yep.

Lem   39:46
OK.
So if we check the.
OK, success.
So if you check the filter.
Yeah, it's it got.
6 bundles, so the the filter is correct. Then if we say here, here are the contacts with the relationship to Greg Smith. So only yeah, the four, that's right. Yeah, the grandchild, yeah.

Peter Wolf   40:16
OK, that makes sense, right?
And that's the four. Yep. So it got rid of the Greg Joneses. That's good. That's the kind of testing we need to do, Bri, is that running or or anybody who's playing with it is running those kinds of iterations to to make sure that it can understand the nuances.

Lem   40:37
Yep, that's right.

Bryan Wolf   40:39
Yeah, trial. Yeah, yeah, yeah. I like that though. I mean, uh, I'll definitely do that, but troubleshooting and stuff like that, so.

Lem   40:50
Yeah, yeah, that's right. So yes, for this kind of, yeah, and for this kind also of like tasks. So we would need like the higher intelligent models, so.

Peter Wolf   40:51
Yeah.
OK.
OK, not a problem, but we're doing it with a lot less data.

Lem   41:01
So yeah.
Yeah, that's right. It would, yeah. So we would do it on a lot less data. So the prompt here is not also quite long, but I think this won't it would be if like we have 1000 contacts. So it's it would still be cheaper than like feeding like the 1000 contacts on.

Peter Wolf   41:23
Yeah, for sure.

Lem   41:24
'Cause I think, uh, let me just search word counter for the prompt.
Um, yeah, if.
Yeah, so this is just like 862 words, so for the prompt, so that's good.

Peter Wolf   41:41
Right. So that's that's that's about 1000 tokens.

Lem   41:44
Yep. And then, yeah, so we also have other for chat, the other ones, I think basically like 2000 tokens, I think 2000 to 3000 tokens together with this ChatGPT.
So this is also GPT 4 O and yeah, but I think it would be much cheaper compared to like the one that is like feeding all the database, right? So yeah.

Peter Wolf   42:10
Yeah.
Yep. OK.

Lem   42:13
And also of one thing also here is it would be like the filter would be narrower if we add two because for this one we were just adding like Greg for the filter right? But if we add 2 filters so it would actually narrow down more so.
And because.

Peter Wolf   42:32
You mean two filters for a for each characteristic?
Oh, you mean if I if I said Greg Smith and and they worked at booking.com or something? Yeah, OK.

Lem   42:38
No, I I no, I mean for.
Yep, that's right. Yeah. So it would just, I think, yeah, it would just choose all of them and if you have 1000.

Peter Wolf   42:49
Right. I don't think that the second filter is gonna be the, yeah, I I think that the fact that you've included the first filter is what's gonna weed out the majority of data, right? You're no matter what I put in there, it's going to narrow it.

Lem   43:00
Yep, Yep.
Yep, that's right.

Peter Wolf   43:05
Yeah. OK. So I'm good with that. So then let's let's talk about, well, let's go back over to your notes piece of things. I would like to include additional additional fields because I think, I think we need to, I think we need.

Lem   43:17
OK, this one. Yep.

Peter Wolf   43:23
I think it makes sense to have right now you have relationship, right? But it should be business relationship, personal relationship. At least I think that we should do that. I don't know whether the standard logic.
If we're using the 40, should be able to handle if I say you know he's married and has two kids, that that's a personal relationship. And if I say he works for John Smith, that that's a business relationship.

Lem   43:46
Yeah, I think, yeah, I think it could get that context. So it's not really vague if it's like a family relationship, yeah, family relationship here and then business relationship or core company.

Peter Wolf   43:58
So let's, so let's try and do that. I'd like to add those two, right? And then we can maybe, maybe in the prompt you have to add some additional context to tell it, right? Business relationship means that they work together or one reports to another or something like that.

Lem   44:04
OK.
Yep, that's right.
Um.

Peter Wolf   44:14
And that family relationships about spouse, kids, cousins, aunts, uncles, that kind of thing, right?

Lem   44:23
Yep, that's right. Yeah, so on.

Peter Wolf   44:23
OK, or friends with and you can say family also includes friends. So as a friend of Jim, he's, you know.

Lem   44:29
Yeah.
So we're uh work relationship.

Peter Wolf   44:33
So business relationships is work relationships, specifically reports to works for, you know, works with.

Lem   44:39
Um.

Peter Wolf   44:45
Supervisor of manager of.

Lem   44:46
Let's see.
Yes, Sir. Uh.
All work related and personalization insurance.

Peter Wolf   44:54
And then personal can be, you know, spouse, kids.

Lem   45:02
Kids.

Peter Wolf   45:03
Relatives, uncles, aunts.

Lem   45:06
OK.

Peter Wolf   45:08
Friends.

Lem   45:09
Because.

Peter Wolf   45:11
Friends with.
Right. So non business relationships, then categorization. Um.

Lem   45:19
And then?
No.
Sure.

Peter Wolf   45:26
Categorization. I'm trying to think of what I really want. There's um.
If I if I'm thinking of them in a business context or personal context.

Lem   45:37
Yeah.

Peter Wolf   45:45
Clients.
I probably need to figure out what I what I want, how many different categories I want, right? Clients, colleagues, family.

Lem   45:58
Yeah.

Peter Wolf   46:00
Let's leave, let's leave that one out for now and then I'll come back to that. You can then family details. You can scratch that because we're gonna, I'm gonna put that in personal relationships, right? Because I so I could put they have two kids, they're six years old, the name's Sally and.

Lem   46:05
OK, so yeah.
Yep.
Yep, Yep, that's right. Um.

Peter Wolf   46:16
Whatever, right? Then on the source I would wait. I'll come back to last interaction, but on the source, let's put.
Uh.
I mean, because I'm initially gonna load and that's gonna be my outlook, right? So if I load them up, my source is gonna be Outlook. But then when I communicate them, I guess it would just be through, you know, manual edition or something. So for right now, why don't we just put that? It's either.

Lem   46:35
OK.
Yep.

Peter Wolf   46:48
It's either either loaded as a as a source from Outlook or it's gonna be manually created through the through this app.

Lem   47:01
Yeah, uh, manually sourced.
K and then introduced by.

Peter Wolf   47:10
And then introduced by is if I specifically say that you know this person introduced me to them, otherwise I wouldn't put anything else there, right?

Lem   47:21
Uh.

Peter Wolf   47:22
Or it could be the other way around. Let's put call it just introduction. And then I could say that person either introduced me to someone or I was introduced to them by someone, right? So it's it's it would be that it would be a name of a person.

Lem   47:23
Yes, yes.
Yeah, introduction.
OK.

Peter Wolf   47:42
They either introduced me to or that introduced me to them.

Lem   47:45
The son introduced me to someone or.
Um, person introduce me to someone or me?

Peter Wolf   47:52
Yes, it's either. It's either someone they introduced me to, that contact introduced me to, or the contact that introduced me to that contact.

Lem   48:05
No.
Uh.
To the other contact.
Another car.
Or for example, the person, the person that introduces me to the other contact.
It's like like introduction, right? Yeah, I'd be like someone introduced you to that particular person or OK, Yep.

Peter Wolf   48:39
Yep. Or someone they introduced me to, right? And I'll put it that way. I'll put, you know, it's the contact of John Smith. And I say, John Smith, I'd say he introduced me to Sally, right? Or I would say Sally introduced me to him.

Lem   48:51
Yep.

Peter Wolf   48:58
Right.

Lem   49:00
Yep, that's right. Yep.

Peter Wolf   49:00
I think that that I don't think that one's going to be that complex. Now last interaction, this is where we were talking yesterday and I did more discussion with ChatGPT. ChatGPT kind of agreed with the model that I was saying. I think we were going down this path yesterday. It really needs to be two different databases.

Lem   49:03
Yep.

Peter Wolf   49:20
And they're linked together with a database key. And one of the things I said that we should add, and maybe this was after our call, you should put it in the list here, a sequential number, a contact sequential number. Because I could have, let's just say I had two people in there with the name John.

Lem   49:36
Yes.

Peter Wolf   49:39
And I didn't know their last name and I just put in John. So their last name would be listed as unknown. Normally you would have the database key would be the person's name, right? So that one database is the contact information. That's all the information we've been dealing with right here.

Lem   49:40
OK.

Peter Wolf   49:57
And the other database is is the times that I've interacted with that person or each person, right? So they could have 20. One person could have one interaction and another could have 20. The the link between the two databases is the person's name. So if I look up their name.

Lem   49:58
OK.

Peter Wolf   50:16
And the contact database, I get all their information about their relationships and their family and their work and all that. And then if I looked up in the history of of interactions, I would use their name and I would see, oh, I met them 20 times at 20 different conferences, right? So the the.

Lem   50:33
OK.

Peter Wolf   50:36
The link would be their name is the database key that makes those two database tables come together and be referenceable. But if I only had their name John and it said unknown and then I had times I met them and you use the database key John unknown.
It would confuse those together. So you need a sequential key that would be just first contact, second contact, third contact, 4th contact, just one unique number. And that unique number could actually be the cross reference, but I'll make it. I'll make it more explicit and say that unique sequential number plus.
Plus the name is the database key that ties them together. So John John unknown number #56 is different than John unknown number 125.

Lem   51:19
Mm.

Peter Wolf   51:30
You follow what I'm saying?

Lem   51:32
So not so basically like through like for example 2 spreadsheets here and then.

Peter Wolf   51:35
OK.
Yep, Yep.
Just copy that spreadsheet over. Copy that spreadsheet over.

Lem   51:42
Um.
Uh.
OK and.

Peter Wolf   51:53
Yeah, now delete everything. Uh, delete everything from column D to the right. Everything from D to the right.

Lem   52:00
Um here.

Peter Wolf   52:03
Yeah.
OK. And then put. So then now let's go back over to the to this to the first spreadsheet.
And then put a insert a new column on the left and put sequential number.

Lem   52:22
Oh.
Sequential.
For example, this one sequential number and then.

Peter Wolf   52:30
And then just put start all the way at the top. I don't think you're at the top, are you? You have something in row six? Yeah, and just put one there and just drag it down and make it 12345, right? Sequential numbering. You got to put 2-3 and then you can sequential.

Lem   52:36
Uh, and then?
OK.

Peter Wolf   52:48
Now if you drag it from the corner, it should work.
Yep.

Lem   52:54
OK.

Peter Wolf   52:54
OK, so every time we add a new contact you should get a new sequential number. That unique number is actually the identifier. But if I only use the number and I go over to the other spreadsheet, I'm going to have to cross reference the number. So the the next tab should have the number and the name as well. So just copy that first row.

Lem   52:59
OK.
Oh, OK.

Peter Wolf   53:14
That first column? Yep. Paste that in. This is now the database key. Insert. Yeah.
This is now the database key. Yep. So now insert 5 rows after between 2:00 and 3:00. Insert 5 rows between 2:00 and 3:00.

Lem   53:24
For this one.
OK.
Turn to entry.

Peter Wolf   53:36
Click on Rd. Yep.
You can just highlight 5 rows and then just insert highlight 5 rows and insert and you can do them all at once.
Maybe Google Sheets doesn't work the same. There you go. Now now hit insert. Yep, there you go. So now if you copied #3 Priya Gupta and put that in all those, not the date created, not the date last updated.

Lem   53:51
OK.
OK.
I'm just here.

Peter Wolf   54:02
Just the first three. Her sequential name #2 though.

Lem   54:06
Oh.
Also the sequential number.

Peter Wolf   54:12
Yep, just copy all three of those. Don't drag them, just copy them and then pick 'cause it might extend the number. There you go.

Lem   54:17
OK.

Peter Wolf   54:21
Highlight all four and then paste it in. Yeah, all five that are left, whatever. OK, OK, so now change that date of last update. Put that in date of last interaction.

Lem   54:28
OK.

Peter Wolf   54:42
Right.

Lem   54:43
Um.

Peter Wolf   54:43
Or last contact or whatever. Now you could put for for pre-ed, you could put, you know, June 25th and then June 17th and just kind of work your way backwards. Plug some earlier dates in September of last year, 2024.
And.

Lem   55:05
OK.

Peter Wolf   55:06
Is plug in any dates going backwards, right?

Lem   55:14
Then.

Peter Wolf   55:19
OK, now we need to figure out what other information would I store when I last interacted. So I would say I'd put place right location column E column E name that location.
Right. Then let's say event.
Right. Um.
And then put other comments.
Right. So now here if I say, yeah, I met her in in Boston at the AFP conference. So the first one put put Boston.
Right. Boston and then AFP Conference, Association of Financial Professionals and then put we discussed potential consulting opportunity.
Right. And now you can just, you can, you can put whatever Philadelphia and you can put, you know, um.

Lem   56:24
OK.

Peter Wolf   56:31
At at a restaurant and you know, whatever, we can just fill that all in with random stuff, but just say so then I could say, you know, who did I, who was the person I spoke to at that AFP conference in Boston about?

Lem   56:36
OK, OK.

Peter Wolf   56:47
Consulting opportunity.
Right.

Lem   56:51
Oh, so like it should search here, right? Is it?

Peter Wolf   56:57
Yeah, if I ask it to say, if I ask it something about interactions or last time I met with them or last time I interacted with them, then it should come over here and search.

Lem   57:10
Oh, right. Yeah, I see. Yep.
Yep. So basically what I would do is I would add another like find data and then it would be connected here and then the cross reference would be like the sequential number. Yep, that's right.

Peter Wolf   57:14
For the interactions.
Yep.

Lem   57:29
Um.

Peter Wolf   57:31
Right. Because then if I say who's the person, if I say who's the person that I met at AFP that that I've talked about consulting with, well, I would have this here, but there'd also be a contact card on her, right?

Lem   57:32
The only fear.
Yep, that's right. So.

Peter Wolf   57:48
They would have a contact card that said, OK, Priya Smith is the person who worked at booking.com and you know, is a manager or something. OK, and that's the person. So that this is where it gets a little more complicated, right? I'm going to need you to try and work through that to, you know, figure that out is.

Lem   58:02
Uh.

Peter Wolf   58:05
Is when I say I have a new contact, great. Then it goes into the contact database. That's the first sheet database. Then if I start talking about times I've interacted with them, then it's going to need to go into the interactions, right?

Lem   58:13
OK.
OK.

Peter Wolf   58:22
So I guess the only thing is where in the other comments in the contact card, it's like I guess having the AI brain determine when it should go there as opposed to into the interaction sheet.

Lem   58:24
Yeah, for.
Yeah, we.

Peter Wolf   58:38
Right.

Lem   58:38
Yep, that's right. So yeah, we wouldn't be adding the like the interaction here and then we would prompt the model that if the message has the context of like interaction or like a place something like that. So it would.

Peter Wolf   58:45
Yeah.

Lem   58:57
Choose this particular tool and find the find the.

Peter Wolf   59:00
Yeah.

Lem   59:04
Yeah, find the.

Peter Wolf   59:07
Yeah. So I mean, at that point, it depends on how I'm asking it, right. If I'm asking it for saying who, who did I meet at that conference? Well, it's gonna, it's gonna look up the same way it looked up for the the word Greg, right. It's gonna look up in here and say, OK, I met them at the AFP conference. Well, that would be on location.

Lem   59:08
Um.
Yep, that's right. Um, I'm just.

Peter Wolf   59:26
And and that would be, you know, or event location was Boston and event was AFP conference.

Lem   59:32
Yeah.
That's right. I'm just not sure if you, for example, you ask like the name I like duck. Yeah, I would need to like find a way on.

Peter Wolf   59:44
Maybe I should just put that all in one field. Instead of having a location and an event and the other, I should just say last interaction and then comments. And then that way I would say, well I met him in Boston DFP conference. That way you don't have to try and figure out which column you'd search on.

Lem   59:48
Um.

Peter Wolf   1:00:02
And it really, if it has to do with interaction, you'd look in this one, all you'd look in is the in the comments field and it would have everything combined in one.

Lem   1:00:03
Uh.
Yeah, but yeah, basically this is this has no problem like the location, but what I'm thinking was for example you would ask ChatGPT like who was the person that you met on for example AFP conference and then it will.

Peter Wolf   1:00:31
Yep.

Lem   1:00:32
Answer Priya Gupta right? And then if you said on like a one message that who was the person that I've met on AFP conference and give me the like the in yeah the contact information so.

Peter Wolf   1:00:34
Yep.
Contact information.
Yeah.
Right, so then it would have to do a cross reference back from Priyagupta #3 Priyagupta and it would go back to the contact database and say #3 Priyagupta and it would give me the rest of her information.

Lem   1:00:52
Yeah, that.
Yeah, that's right. Yeah.
Yep, that's right. So.

Peter Wolf   1:01:04
Right. So if I'm just asking for it, and the other way around would be tell me the last, tell me the last three times I met with Priya Gupta.
Right. Because then it would go and find the contact and would say, well, OK, the contact Priya Gupta, here's our sequential number and that's the link over here to the interaction. So let me go look at the last three times I met with Priya Gupta.

Lem   1:01:13
Yeah, uh, yeah.
Yeah, so Yep, that's right. So it would just search for this database. I'm just not sure if it can like. I think it can like trigger both of them like because it would need maybe it first trigger this one and then it will ask again if.
On the chat, for example here, let's say, let's say, can you give me what's that again? Like the person, can you give me the contact?

Peter Wolf   1:01:59
I know what you're saying. That has to be a two step process. If I ask you a question that's relevant to starting at this table, it could give me a name, but you're not sure it could go and automatically give me the rest of the contact information without two steps. OK, I can, I can deal with that. I mean, let's see if you can do it with one step, but.

Lem   1:02:02
Yep.
Yep, that's right.
Yep, that's right. Yeah, that's right. With. Yeah, without asking.
Yeah.

Peter Wolf   1:02:19
I can deal with it in 2 steps, right?

Lem   1:02:22
Yeah, because yeah, basically this would be just the same. I would just duplicate that one, then just change the context here and then yeah, we for the sequential number it's it's not it's not a problem. You could just cross reference like the first name, last name.
And then, uh, this.

Peter Wolf   1:02:41
But that's why I'm doing it with the number, right? Because I know it seems silly, but I I just want to avoid any conflict. If I say I I know the guy's name is John, I don't know his last name and there's two guys with the name John, then the number is the differentiator.

Lem   1:02:44
Yep.
Yep, that's right. Yep. Yep.
Yes, that's right. Yeah.
Yeah, that's right. So.
Yeah, the the two step process I think would be the.

Peter Wolf   1:03:05
I am thinking, I am thinking that that that probably we should put all that the notes into one field though because if you start filtering and location or event.
Like, what if I said, because here's a good example, Korgermania there. That's my fraternity, right? Is that a location? Is that an event? That'd be Munich.

Lem   1:03:34
OK.

Peter Wolf   1:03:35
I'm not sure what.

Bryan Wolf   1:03:40
Or start packing.

Peter Wolf   1:03:42
Yeah, I better start packing. I'm not.
Obviously, that's on my mind. That's why I've put it up. Um.

Bryan Wolf   1:03:49
Yeah.

Peter Wolf   1:03:52
I.

Bryan Wolf   1:03:52
You said your flight's at 1:00.

Peter Wolf   1:03:55
1:45 But I do still have to pack. I got all my clothes picked out. I do still have to pack though, and I still have to load a bunch of stuff to MIT before I go. So I was going to meet at the 10:30 with Justin, but I think we're going to have to jump right into this and.

Bryan Wolf   1:04:00
So.

Lem   1:04:08
OK.

Peter Wolf   1:04:11
Well, or maybe maybe you guys could still work on this. I could go pack and then come back at 10:30 and then Justin could get on and we could talk through the other process flow that I wanted to work on.

Bryan Wolf   1:04:23
Yeah.

Lem   1:04:24
OK.

Bryan Wolf   1:04:26
Well, I mean, you want Lem to work on this. Yeah, I mean, yeah.

Lem   1:04:27
Um.

Peter Wolf   1:04:28
Well, I mean, you guys could talk about what he's already done, walk through what he's done. I mean, it looks like there's some decent complexity here to get acclimated to, right? And this whole new thing I talked about here with the the, the combining databases. Yeah, I know this is going to add some complexity.

Lem   1:04:29
Come on.
Contact.

Bryan Wolf   1:04:32
Yeah.

Lem   1:04:35
Contact card.

Bryan Wolf   1:04:35
Sure.
Yeah.

Peter Wolf   1:04:46
To it.
But you understand. It seems you understand what I'm trying to achieve. The the the technical aspect of achieving it is the cross reference between the two databases seems to be the one thing you have a question about.

Lem   1:04:53
Yep. Yeah, that's right.
Like uh uh.
Yeah, that's right. The cross referencing is I think we know we won't have a problem. It's just that like when asking the chat sheet like the agent if it would automatically trigger the other one because for example give me the.

Bryan Wolf   1:05:04
But.

Peter Wolf   1:05:16
Yeah.

Lem   1:05:19
Contact contact details. So what I'm assuming is right now because I haven't tested it right, but what I'm assuming is we if we ask the EA agent who was the person, can you give me the contact details that I've met?
On Boston, an AFP conference and I think it would just give Priya and then we would need to can you give me the whole contact details of Priya? Yeah, so then it will go to this particular. So yeah, that's how I'm assuming that it would output.

Peter Wolf   1:05:37
At AFP, yeah.
Full contact information, yeah.
So think of this, think of this, this, this use case. If I go to a conference and I meet 10 people and they become sales contacts and I want to just plug them in here quickly, then I'm going to give the person's name, create a contact and then say.

Lem   1:05:54
And.
OK.

Peter Wolf   1:06:11
To to register that I met with them at the AFP conference and their sales contact right for Treasury or something else. So then if I come back and say tell me everybody that I interacted with at the AFP conference, you're telling me it would give me a list of the people's names and then I could say.

Lem   1:06:15
Yep. OK.
Yep, that's right.

Peter Wolf   1:06:30
OK, go get me the contact information for all those people.

Lem   1:06:34
Yep, that's right. Yep.

Peter Wolf   1:06:35
OK, I'm OK with that, but that's an exact use case. What I just told you is a definitive exact use case that I would do.

Lem   1:06:36
Um.
Oh, OK. OK. Yep. I I got the gist of it. So I think, yeah, that that one is possible. So like a two step. So first it would get like the names or yeah, the names here and then get the again the contact information when we tell it to. So that one would be, yeah.

Peter Wolf   1:06:57
Yeah. OK. Can you go back over to your notes? Because I now just thought about at least a few categorizations, categorizations of contacts. So let me say, let's say it's the next one down categorize up right there.

Lem   1:07:00
Oh, that should work.
Uh.
OK.
Yeah, this one.

Peter Wolf   1:07:14
So I would say sales, sales lead is gonna be specific categorization. So sales lead.
Uh, colleague.
Client.
It's GGUE, right? GEAGUE. Yeah, colleagues, clients or client, whatever.

Lem   1:07:40
Yeah.
Client.

Peter Wolf   1:07:50
Family slash friends. That would just be one family slash friends.

Lem   1:07:55
So.

Peter Wolf   1:07:59
Um.
Then we can just put business.

Lem   1:08:07
Business.

Peter Wolf   1:08:10
Right now it's kind of leave those and then I figure out if I add more but sales lead colleague client.

Lem   1:08:13
OK.

Peter Wolf   1:08:20
Family, friend, business.
Yep.
OK, so let me let me pack. You guys can can talk through whatever the other stuff you've already worked on. Lem, you can give us some guidance and I'll come back at 10:30 and I'll have Justin on here as well, OK.

Lem   1:08:31
OK.
OK.
OK, Peter, no problem.

Peter Wolf   1:08:44
Alright.

Bryan Wolf   1:08:44
What's adjusting or just overseeing with the flow?

Peter Wolf   1:08:46
No, Justin is. Justin is the project manager on the Chevron project. That's a project that's been running for about two years. He's responsible for managing the budget and tracking the hours and I want to the next process flow is going to be a customer self-service portal.

Bryan Wolf   1:09:00
OK.

Peter Wolf   1:09:05
Application that will allow them to check on the status of their budget, the hours being used and the and the budget utilized on their project. So he since he's been working on this stuff manually in a spreadsheet.

Lem   1:09:13
Mhm.

Peter Wolf   1:09:23
He should help. He should be able to help guide how we should structure this and help you to work on kind of what what it would look like, what the outputs are going to be, what the dashboard would look like. And then when Gilles is back, he'll be able to help us get to the PSA data better.
That's the that's the hours data, but Justin is already managing this stuff in a spreadsheet and so he'll know what the content is and what we're feeding into it when we feed it the budget and that'll be helpful in in guiding you guys while I'm away. Plus he wants to be involved, so.

Bryan Wolf   1:09:42
Yeah.
OK.

Lem   1:09:55
OK.

Peter Wolf   1:09:56
OK. Plus it will save him a lot of time. So I think he wants, he wants to make sure we get it built so that he can spare himself effort, OK.

Bryan Wolf   1:09:56
Yeah, yeah.

Lem   1:10:07
OK.

Bryan Wolf   1:10:07
Yeah.

Peter Wolf   1:10:08
I'll be back in a little bit.

Bryan Wolf   1:10:09
Yeah, go pack. Go pack.

Peter Wolf   1:10:11
Yeah, goodbye.

Bryan Wolf   1:10:19
Now let me personally, I don't have any questions. Like I just, I we've been watching you and Pete go through this whole thing together. So I'm pretty. I think I'm OK. I don't, you know, just if anything, it's just would be more.

Lem   1:10:19
Uh, I.
OK.

Bryan Wolf   1:10:34
Me playing around with it once, you know, we start to actually implement this.

Lem   1:10:40
Yeah, yeah, I think.
Yeah, you could play around, but yeah, basically you could also like test already the AI agent here on the make. So yeah, then just connect like your tools or even the ones that we've built in the past, we could just change the like the trigger.

Bryan Wolf   1:10:51
Make yeah.

Peter Wolf Jr   1:10:52
Thanks.

Bryan Wolf   1:11:00
Uh.

Peter Wolf Jr   1:11:01
Mm.

Lem   1:11:03
To like the ones.

Bryan Wolf   1:11:06
Lem, I'm wondering how many process lists do you have personally that that are like you that are outside of that you do with us?

Lem   1:11:09
Yeah.

Peter Wolf Jr   1:11:19
See.

Bryan Wolf   1:11:21
You've got a lot. You've got a ton, don't you?

Peter Wolf Jr   1:11:33
Make.

Lem   1:11:33
Yeah.

Bryan Wolf   1:11:33
Usually you go and make it, but for him.

Peter Wolf Jr   1:11:35
Um.

Lem   1:11:36
Yeah, that's right. So I I when I get.

Bryan Wolf   1:11:37
Oh ****, we should be doing that with you. That would be *******. That would be way better.

Lem   1:11:41
Yeah, I think Peter is like concerned with the like the credentials and.

Bryan Wolf   1:11:47
Hey, Pete, mute yourself.

Peter Wolf Jr   1:11:49
I have a question.

Lem   1:11:49
Credentials and Yep, no problem.

Bryan Wolf   1:11:50
Oh, OK, well, you got a lot of background.

Peter Wolf Jr   1:11:53
So what? Why does he think it would be better to have a two database system here? Does anyone understand why he feels like that would be better for this application?

Lem   1:12:01
I think I no, I think he just wants to like.

Peter Wolf Jr   1:12:04
'Cause he lost me at that point.

Bryan Wolf   1:12:04
I.
Yes.

Lem   1:12:11
For example this one has this particular like particular information are on the same person and then these are like different different data so.

Peter Wolf Jr   1:12:21
Right.

Bryan Wolf   1:12:21
Mhm.

Peter Wolf Jr   1:12:26
Times they met.

Lem   1:12:27
Yeah, if we put that here, it would be like, for example, there would be 3 Priya Gupta here. Was that? Can you?

Peter Wolf Jr   1:12:33
Too much?

Lem   1:12:40
Basically, um, this one is for example, we can't.
Uh like add here like columns for like this one because.

Peter Wolf Jr   1:12:53
I get, I get it. So it's really just a a reference last time they had met.

Lem   1:12:54
What? What? Yeah, but yeah.
Yep, that's right. Yeah. So we could also do like like for example the location, right, like location here and then you could like do like the Boston and then add the Philadelphia here that one, but.

Peter Wolf Jr   1:13:02
Oh no.

Bryan Wolf   1:13:06
OK.

Peter Wolf Jr   1:13:18
Right.

Lem   1:13:18
Yeah, I think I just wanted to try this more, I think more robust like design so that it could be used also for like other other use cases because yeah, for this one we have like in separate rows we have different.
Different information on location, event and other comments, but it has it's coming from the same person. But here on every row we have the all of the rows are.
Yeah, per row we have only one, like one owner of that row. So if that makes sense. So I think, yeah, that's why what he wants to, yeah, to do like.

Peter Wolf Jr   1:14:04
Excellent.

Lem   1:14:09
But yeah, basically like a different context, but for the same person here.
Yeah, different informations or something.
But yeah, I think it it's, uh, actually doable. We just, uh, duplicate the ones and tweak a little bit the prompt.
So the big thing here actually on especially on AI agents are the prompting. So if we like that's why it needs always it needs tweaking always like it needs to test out and then send a message and test it out again because Yep we need to.
explain it thoroughly to the to the pot and then yeah so that would be the main main thing here
So.
Do you want? Do you guys want to? I can also send like the.
Like this particular uh Jason files and then also.

Bryan Wolf   1:15:19
Yeah, at least definitely.

Lem   1:15:20
The prompt. So yeah, I could send it to you guys so that you could also like play around with it.

Bryan Wolf   1:15:22
Yeah, even though they're smaller, this problem's improved from yesterday, right? It's different, right?

Lem   1:15:30
Yeah, so this is more. Yeah, more.
Like.

Bryan Wolf   1:15:42
I know what you're saying, like in the other instructions, yeah.

Lem   1:15:43
Yeah, the instructions are more, but yeah, I've just ask also ChatGPT for this particular prompt and then depending on its answer I I've told it to like change it, tweak it a bit. So something like that and then I tested it. So until it works then for some I've manually just edited it myself.

Bryan Wolf   1:15:49
Mm.

Lem   1:16:02
So that it would get for example like this required field. So the other stuff here was a different ChatGPT inputted like different contacts here. So I've added some of this myself then.
Yeah, but yeah, Chat, we could now just ask Chat actually for the the inputs and stuff and it's doing a great job also on it. Yep.

Bryan Wolf   1:16:30
Nice.

Lem   1:16:33
Uh.

Bryan Wolf   1:16:37
That's pretty in-depth, actually.

Lem   1:16:39
Yeah this it yeah it's 800 words and it would be. I think it the only thing also is if we add the other sheets so we I would need to add the prompt here again that is like.

Bryan Wolf   1:16:53
Just cause it would be too much information, George data.

Lem   1:16:54
Same yeah, so it would be like 2 very long. So I'm not. That would also be like the challenge there if it it would still get the context because yeah, the task here are already quite long so it's not like the simple one.

Bryan Wolf   1:17:00
Yeah.

Lem   1:17:11
The same as yesterday, right? Like just add the data and stuff. So we have like the full context here like the also the example output, um example input. So for more more context.
But Yep.
Oh.
Yeah, there's also, but I'm not really an expert on like the database stuff like the pulling it out like for example for the vector database and pinecone, but I've just done some research about it. But yeah, from what I've researched if the tabular data it's.

Bryan Wolf   1:17:46
Yeah, I mean.

Lem   1:17:54
If yeah the data is something like this, it's much better with like a super base so but basically it would still be the same like the for the filtering stuff. It would just be the same for like I think that.
Term there is like the PostgreSQL, the SQL, PostgreSQL and then it's like just a like a tab tabular data and it's yeah, it's a super base.
But yeah, I think I can, uh, start.
Also editing this one.
Yes, so the other comments.
This is relationships.
This should be.
Relationships.
Yeah.
Yeah, I think this is.
All business relationships.
Mm.
Personal relationships.
Contact category.
Date of last update.
Uh, so we would be the uh.
That's the direction.
3.
Just this for now.
Uh.
Contact sequential number.
Source.
Contact category.
Source.
Introduction should be.
Let me take care.
OK.
Then.
So.
Production.
Yes.
This time.
I just need someone R.
To distance somewhere.
this
This for.
Yes.
Sure this.
To another contact.
So we changed the.
This is relationship.
It's nice relationship.
Nice.
Uh.
This is.
Situation share.
OK.
Oh, nice.
Shakes.
Oops.
Sample.
Yes.
Contact category.
Contact category.
This is.
Search need colleague, client.
Yes.
For the last interaction contacts number. Um, my new contacts number.
Oh, this is a data table sheet.
It's OK.
Source.
Source.
This source.
Resource.
Production.
Yes.
Yeah, I think we need to.
Remove that one.
Send the test update and.
So.
Um.
No, I think it's something. That's the date that if there are.
There are changes I think.
So.
Current date.
Company.
Oh.
Industry.
Mm.
In the industry.
Just this right now.
Production.
Um.
Oh my God.
Oh.

Bryan Wolf   1:32:17
Then maybe in the future we'll just have you work on Peter's account. That way I can just work on mine instead of doing, you know, twice.

Lem   1:32:25
Yeah, that is how I actually do it on my like other clients. I get all of their logins and credentials from the start and then I just build it all of it. And then when our contract finished, yeah, they would just change all the password.

Bryan Wolf   1:32:33
Yeah.
We should be doing that.

Lem   1:32:45
Then if there are like errors in soft, they would just give me again the like crunch. Yeah. So because our I think, yeah, Peter also mentioned it. I think in the past he wanted it to be like this also for that.
So that, uh, you guys also can learn. I think that's uh like was his like point.

Bryan Wolf   1:33:04
I know, but if we still do the walkthrough anyways, 'cause I have to put it on my account anyways, right? So if you do it on Peter's, I have to do it on mine anyways. So really I'm just doing it in an extra, like an extra time, which I don't have any problem doing, but yeah.

Lem   1:33:11
Yeah.

Peter Wolf   1:33:13
2.

Lem   1:33:18
Yeah. So yeah, that would actually be much also easier for me and much, yeah, because it would be like.
I would set it up all all of it there and then I'll just make a like a walkthrough and also we have also have I'm explaining it also on our like like videos on like yeah so I think that would be much.

Bryan Wolf   1:33:37
Yeah, yeah, I don't think there's anything wrong with that.

Peter Wolf   1:33:41
Yeah, what are you saying to have Lem build it directly in my build it directly in my account?

Bryan Wolf   1:33:45
Yeah, yeah. And then that way I could, I could just do it in only mine instead of yours and mine.

Lem   1:33:46
Yep, Yep.

Peter Wolf   1:33:50
Right. Instead of doing it in mine and yours, although I guess doing it more than once is a is a way to force you to to you know.

Bryan Wolf   1:33:56
The repetitions.
Yeah, yeah, yeah, yeah. I'm not. I'm not against that. But you know, maybe in the future. But whatever, I don't care.

Peter Wolf   1:34:04
And I agree this is these are getting pretty complicated too, right? So it's a lot of a lot of work, a lot of steps.

Lem   1:34:09
Uh, person.

Peter Wolf   1:34:14
I'm OK with doing it that way. You decide which one's gonna work better for you guys. You just you definitely need to be building at least once in your own environment, right?

Lem   1:34:15
Mhm.
Didn't.

Bryan Wolf   1:34:29
I already, I mean, yeah, whatever.

Lem   1:34:35
Oops.
Oh, I didn't save. That's too bad.
Uh.
Mhm.

Bryan Wolf   1:35:37
Can we just wait on Justin here?

Lem   1:35:39
Yes.
Sample.
Oops.

Bryan Wolf   1:35:54
That's.

Peter Wolf   1:35:54
Yeah, what? Sorry.

Bryan Wolf   1:35:56
Are we just waiting on Justin now?

Peter Wolf   1:35:57
Yeah.

Lem   1:35:58
This all.
Person.
Yes.

Bryan Wolf   1:36:10
What time do you think you're gonna leave 11:30?

Peter Wolf   1:36:13
Yeah.
I'm 45 at the latest, I'm thinking, although the first flight is a domestic flight, it's it's not an international, so it's not really.

Bryan Wolf   1:36:18
Make sure you got your passport and everything else.
Oh, right. It's going. Yeah, yeah, yeah, Charlotte.

Lem   1:36:25
Got the car.

Peter Wolf   1:36:26
But still, I just don't want to stress. Um, hold on.

Bryan Wolf   1:36:29
Mhm.

Lem   1:36:58
Sequential number.
It looks much longer.
Oh, I think we don't need this as input, so it's automatically.
Source just this source.

Justin Kemmerer   1:37:23
Hi, Peter. Hi, everybody.

Peter Wolf   1:37:25
Hey.

Bryan Wolf   1:37:26
Hey, Justin.

Peter Wolf   1:37:27
So.

Lem   1:37:27
Hello.

Peter Wolf   1:37:29
Justice, so we got we got Peter, Brian and is Nick's going Nick dropped off it looks like and Lem Lem is our offshore developers working on the process automation flows.

Lem   1:37:33
It's the source.
This is this is the source.

Bryan Wolf   1:37:38
Yeah.

Lem   1:37:40
This is this.

Peter Wolf   1:37:44
And doing a great job of it, if I do say so. So guys, we're going to jump over to this other process below. If you have any questions left on the on the contacts one, then we can just wrap it up when we get done.
But let's let's switch over to this other process flow. I'll talk you through what it is and then we can.

Lem   1:38:00
OK.

Peter Wolf   1:38:09
We can figure out the path forward, so hold on one second. I share my screen.
Sorry, hold on guys.
Too many different things going on.

Justin Kemmerer   1:38:51
See the EP budget dashboard.

Peter Wolf   1:38:54
Yeah. So, so that's what I'm going to call this, right. So Agentic process automation flow for client budget dashboard, right. So project budget dashboard and what the intention here is that we're going to ultimately I'll tell you what the.

Lem   1:39:06
OK.

Peter Wolf   1:39:14
State solution is and we'll talk about what the interim solution is. So our data, our time data is held in this PSA Professional Services Automation module that's in SAP. So we book our consulting time into that module and.
And then we use that or it's used to calculate invoices for clients. And right now, Justin, while we're talking, if you could pull up your spreadsheet for for or you know, I have it. Don't, don't bother.
It'd just be easier than switching back and forth, so.

Justin Kemmerer   1:39:47
OK.

Peter Wolf   1:39:54
Uh.
Everyone.
I meant.

Justin Kemmerer   1:40:01
Oh my God, all the versions.

Peter Wolf   1:40:05
Yeah, well, this is exactly what we're trying to avoid, right? Is this, this insanity that Justin is managing for our time tracking, so.

Justin Kemmerer   1:40:13
I hate looking at it. I always hate looking at it.

Bryan Wolf   1:40:16
Oh, wow.

Peter Wolf   1:40:18
Yeah. So what this is, is you can see here, hold on, this has been going on for and I don't know if we changed workbooks or when we changed workbooks. Yeah, so since October 2022, right. This is weekly time.

Bryan Wolf   1:40:18
This is quite a lot.

Peter Wolf   1:40:35
Yeah, we've got different sheets for different periods because we went through different releases, but what it has is the person, it has the billing rate. So all these different people we have and we actually have more people than this. Now this is an older one we've got.
Um, we've added even more people and uh.
And what we have ultimately is a projection. When we start, we have a a forecast of what their staffing is going to be per person and then what they actually build. And so then that calculates up to a weekly total of consulting, right, total forecasted hours versus actual hours.

Lem   1:41:08
Yeah.

Peter Wolf   1:41:16
The difference than the forecasted weekly total, the actual total, and then we get monthly totals as well. And so the intention is to create a dashboard that would allow them to compare their projected flows against their actual flows.
To to show that we're on track for budget and if we're not on track for budget then to call it to their attention so that we can discuss why we're not on track for budget, whether that means budget needs to change or whether we've over we're we're booking too many hours and or we need more budget.
Um.
And so it's going to be both on time, hours, hours per resource per week and hours per resource per month, total Billings, billing per resource, billing projections per resource, billing totals and then the cumulative where we are on the project and where we're.
Where we're where we were expected to be, 'cause it's not even, it's not even burn per per.
Yeah, it's not even burned per month for this. So we have for example if I look at RTX.
There we go.
We look down here.
This is a statement of work we're working on right now. Should be signed shortly. Hopefully you see right here we have.
The projection of staffing per resource, here's the billing rate, here's the hours per per. This is per month. This is not at a weekly level. And so we'll have to deal with that, right, whether we track it, whether we're showing it at weekly or monthly.
In yours, Justin, we obviously do weekly, right? Depending on the project here, we're only showing monthly, so we'll have to keep that in mind when we're talking about the reporting. But this is a lot to keep track of all these different people, all their hours, what their billing rate is, what the calculation is. Then you see here, this is the totals.

Lem   1:43:31
You.

Peter Wolf   1:43:48
This is the hours by resource and then we we don't have it in here, but we have this same thing with the calculation with the amount per month. And so this is what we need to be comparing to. So we'll load up a a baseline, we'll load up what the projection is, whether that's a weekly projection or.
Monthly projection of staffing by resource, by resource title and the and the rate and then and what their expected Billings are, what the monthly expected Billings are weekly. If we're doing at that level, I would assume we're really probably.
Probably gonna be doing that monthly, but we need to build it so it can handle weekly and then ultimately, where are we relative to the budget, right? Because you can see here sometimes the hours bump way up, right? There may be specific periods.

Lem   1:44:42
Oh.

Peter Wolf   1:44:42
Where certain work demands that we have higher staffing levels or they may be much lower. And so it's not just saying take this amount and spread it out evenly over the project. It's what were the expectations for this month because we're front loaded here and we're weaker in the back and so we want to make sure it doesn't look like we're burning too much budgeting.

Lem   1:44:45
I'm very.

Peter Wolf   1:45:02
Here if we just do an average burn, right?
So that is the foundation of it. I want a self-service portal where the client can go to this in the cloud, so a cloud hosted app where they can go to retrieve this information and.
And we can feed it information directly with a process flow directly from spreadsheet or from PSA. The intention will ultimately be from PSA, but we can feed it from a spreadsheet in the interim while we're waiting to get access to.
The PSA because right now they have some issue with us extracting directly. So we use a Google sheet for the time being while we while we do this and then back over here. Yep.

Justin Kemmerer   1:45:53
Wait, Peter, you said they had a problem with us extracting from PSA.

Peter Wolf   1:45:57
It's not that they have a problem with it. They don't. PSA doesn't provide the right data, apparently doesn't provide the appropriate data in the available report. And so Jill has to pull information from some other report and then manually coordinate things or.

Lem   1:46:11
I'm.

Peter Wolf   1:46:17
Collate them and we were we're looking for A and have submitted a request to get A to get a PSO data.

Justin Kemmerer   1:46:19
Mhm.

Peter Wolf   1:46:33
O data extract right that we were going to add that missing piece of information in the O data so we can get exactly what we want, which is going to be resourced by day, by by project.

Justin Kemmerer   1:46:41
Mhm.

Peter Wolf   1:46:48
Right. The billing rate's not going to be in there. We're going to have to feed the billing rates separately. We have to feed the budget separately. That's not going to be in PSA either. So we'll have to create the budget, establish what that budget orientation, what that's going to look like, how we feed that in, how we give the resources and the rates.
And and then extract the data from PSA. But again, we'll start with a with a start with a sorry I got my brain's on five different things. I gotta hold on, I gotta address something here. Edit change 11:15.
Um.
Start with just a spreadsheet.
So you'll take whatever you have, Justin, or I have this here. I think it's fine this. I don't really want to use this really complex one, but.
So here's PSA extracted a subset of the data.
And.
Um.
Like this is the project name, so project name will have to correlate to a code 'cause I don't, but they don't have the code in there, they just have a name.
So these are things we'll probably have to create some kind of cross reference to. But here's the client. Here's the name of the project or the engagement.
The resource is a project name again, the date for the time status, because we only want to prove. You and I talked about this yesterday, Justin, right? There's others like rejected or canceled. We only want approved.

Justin Kemmerer   1:48:52
Yeah.

Peter Wolf   1:48:54
Then the task this is.
Zort is other reportable income, ZSTA is time off, ZTAD is other reportable time. So right now we're going to build this for the client, external client facing, but ultimately we'll do this for internal as well, right? We have a dashboard we've already.
Built the kind of basic dashboard, but we'll probably use this app and do the same thing, feed it in, but it'll be for internal time management and review. So we'll be looking only for here. We'd be filtering out and saying, OK, I only want project time, so you pull the time by the project code and you only want approved and.
And this is the number of hours, right? So I would say we could use this and I'll send it to you guys. Hold on.

Lem   1:49:41
OK.

Peter Wolf   1:49:47
I would use this as the baseline for.
For the prototype.

Justin Kemmerer   1:50:04
And that that last spreadsheet that you were showing, was that straight out of PSA or did you have to modify that app?

Peter Wolf   1:50:09
Well, here's what came out of PSA. Here's what actually came out of PSA is this right here.
It's got.
It's got all these fields in it.
Right. But I went through and highlighted those that are critical fields and and then narrowed it down to what you saw. So let's just worry about those right now. We'll worry about if we get an extract from O data.

Justin Kemmerer   1:50:31
Yeah.
OK.

Peter Wolf   1:50:46
Then we would extract only the fields we wanted, OK.
You good, Justin? OK, so I just, I just dropped that into the chat.

Justin Kemmerer   1:50:53
Yep.

Peter Wolf   1:50:59
So that spreadsheet you guys can use as a baseline. Then what else I'm saying here is so originally we'll start with a Google sheet to simulate the data. That's what you have.

Lem   1:50:59
Um.
I can't see you.
I can't see the did did you send the spreadsheet here on? I can't.

Peter Wolf   1:51:12
Then.
I just put it in the chat, sorry.

Lem   1:51:17
Uh, I can't seem to.

Justin Kemmerer   1:51:18
Good.

Peter Wolf   1:51:20
Download it. OK, here, I'll send it to everybody.

Lem   1:51:21
Yeah, I don't have like access, I think.

Justin Kemmerer   1:51:23
I don't see it.

Lem   1:51:27
But OK.

Peter Wolf   1:51:27
Hold on.

Bryan Wolf   1:51:30
Yeah, I just got the e-mail and I think.

Lem   1:51:34
Uh, on the e-mail.
Oh.

Bryan Wolf   1:51:50
Can you see see me in there or?

Peter Wolf   1:51:53
I got you on there.

Bryan Wolf   1:51:55
No, I don't think you do.

Peter Wolf   1:51:57
I got you as interns, all of you.

Bryan Wolf   1:52:00
Oh, OK. OK.

Peter Wolf   1:52:04
Right.

Bryan Wolf   1:52:08
Yeah.

Peter Wolf   1:52:24
OK, so then we use the Google sheet original. So we need to come up with a and and Justin, you'll have this again looking at looking at what we have for for Chevron, but then also thinking in terms like the RTX, right, we're gonna have to do.
Where we only put the budget in at a monthly basis, not on a weekly basis. OK, so you'll need two different examples of that or you'll have to dummy up a a more detailed and a less detailed version. OK, then budgeting costs. We got to put the cost in there. What's the planning? Again, we'll do that at the weekly and at the.

Justin Kemmerer   1:52:55
Yeah.

Peter Wolf   1:53:02
The monthly level, ultimately where the actual hours work, this budgeting is not gonna be in the PSA output. That's gonna be in an upload we do first to establish the project right in this customer dashboard. Then we're gonna extract actual hours.
And those actual hours, I'm assuming we would have the the rates stored somewhere in the app separately because PSA doesn't have the rates either, right? These are things we have to keep in mind. So rates PSA is going to give us hours, the project and the date.
The resource, it's not going to give us the rate. So we're gonna have to store the rate somewhere so that it can apply those rates to a to the to the hours. But you also need to think, Justin, in terms of.
Like Chevron, where rates changed over time. So we're gonna have to think about rates with A and Brian, you have the recorder on, right?
Get the recording on.

Bryan Wolf   1:54:02
Yeah, I should be. I think, uh, when you're automatically in, when you create these meetings, it automatically records.

Peter Wolf   1:54:09
Yeah, I saw a trigger, but then I backed out. I'm assuming it was still running. OK, so the the the we're gonna have to think about time validity range for rates. So the rate may apply from January 1st to December 31st of 2025 and then on.

Bryan Wolf   1:54:11
It's it's on. It's on right now. It's on.

Justin Kemmerer   1:54:12
I I see it.

Peter Wolf   1:54:29
1st 2026, the rates going to change. So keep that in mind. We need to think about how do we handle a rate changing in a project, OK.

Justin Kemmerer   1:54:39
So quick, yeah, question for you Peter. When we if we are humming along with the Chevron project, say R1A and Christine wants to have a conversation about R2 in the next phase while we're still in R1A.
Would you be going into the this dashboard to pull the latest board?

Peter Wolf   1:55:00
I don't think so. I don't see how we would really handle it. I mean, let's stick with basics 1st and then worry about advanced. OK, from now, for now, let's just get a foundation that shows the original project plan. Then we'll have to think about incremental changes and extensions and whatnot, because I did put that in into.

Justin Kemmerer   1:55:06
OK.
Right.
OK.

Peter Wolf   1:55:20
Did discuss that with ChatGPD was, you know, try to decide whether we're just going to make an adjustment and change the base plan or whether we're going to show the incremental or we're going to have budget one, budget two comparison to them. I don't know. Let's stick with the basic first, OK.

Justin Kemmerer   1:55:35
OK, all right.

Peter Wolf   1:55:36
All right. So then, so then ultimately we're going to have comparison, the original plan, actuals as well as any revised plans. This is what you just talked about. We'll have to figure that part out. Let's leave that revised plans part right now, not as a.
Uh.
As a requirement for us to deliver. Let me just see where I'm. I don't even remember where I'm storing stuff here. Workflow. This is news process automations and this is APA.
Budget dashboard.
OK. And then, OK, so then this is the part that you guys are gonna, I'm gonna need you to do some research or I don't know, Lev, you have any input here and even maybe.

Bryan Wolf   1:56:42
Oh, my Glide is.

Peter Wolf   1:56:44
Yeah, Glide. After I talked to it, it said Glide. There was another one, but Glide ultimately seemed like it was the a less complex, more simplified version. I didn't think we needed something really over the top than complexity. It said this should satisfy the requirements. Got drag and drop setups and structures for how you.
Build the app. It's got predefined security authorization stuff, so we could build our own app, but I just think that's just a lot of wasted time. Kind of cool to put on a resume, but I don't think it's necessary. I think even using something like Glide and building.
The app from that, I think of it like the like the web page building tools that they have now where you just say, OK, I want an image here, you grab an image, you drop it, it puts it up in the corner, you put your name down here, signature over there, you're you know and you it's got structures and you just really.
Fall within those structures and that way it accelerates the process. You identify what the output should look like. So I think I need you guys to do some research on that. I didn't get a chance to. I'm not going to get a chance to. I'm hoping you can do some research on it, see what that looks like.
And again, working with ChatGPT and going in signing up for a base account, if we need to pay for an account of initial, then Brian, then you can set that up. So between you and Justin, if you guys can coordinate on that, Brian's got the information, we can set it up on my card.
So we need to figure out again the inputs. How? What is the inputs? How are we putting in the budget? How are we putting in the rate? Then how are we loading in the hours? How's it going to make the calculations and what's the output going to look like? Is it going to be bar charts, line charts?
Just calculations and values. This is the kind of stuff, Justin, I'm going to look for you to kind of visualize and come up with some proposals, right? I mean, draft some things up and we can always adjust and and and and move along in different directions, but let's get something on the table.
That works. OK. And so Lem, I'm looking at this as a basic process flow where ultimately someone's going to come into the app and the app is going to then be the trigger to process flow to is it? Is it?

Justin Kemmerer   1:58:47
OK.

Peter Wolf   1:59:04
Is it? I don't know. Maybe that's not true. Maybe the process flow is really ****. It's already 11. Maybe the process flow is that we're going to have an automation that's ultimately going to go to PSA, grab the data and feed it to the app.

Lem   1:59:05
Um.

Peter Wolf   1:59:21
And for now it's going to be the process flow is going to go to the spreadsheet, extract the latest data and feed it to the app. One question, another thing we need to think about, put this as a follow up or make a note of it is what happens when we load the data? Is it incremental or is it?
Is it cumulative, right? I'm hoping it's incremental, but I got a feeling there was something in PSA. It was like you didn't really you extracted the data, gave you all the data. I don't know that it was controlling, but that would be part of what we'd be looking to put in the.
In the in the filtering for the O data, but we need to think about that. You can't backdate right if the period's closed, but what if we ran the end of the period but the period wasn't closed and then someone added their their information after that. Justin, you obviously we have.
This the close period several days. Someone might still plug it in. When do we wait to extract the data? We have to wait till the end of the close period. OK, well remember at the end of last year they left three months open. They left three months open.

Justin Kemmerer   2:00:21
Yep.
Yeah, yeah. I don't, I don't think that's been sort of corrected. I think I could even go in now and change June hours.

Peter Wolf   2:00:35
Yeah. So I don't that's OK. So I'm just raising it up. I don't have time to think it all the way through, but we're gonna have to think about those things, right? How are we gonna ensure if someone back dates some data, how are we gonna get that in there without destroying what we already have or double counting?

Justin Kemmerer   2:00:39
Yeah.

Peter Wolf   2:00:52
OK, then, yeah, this is ultimately transitioned to live extraction from PSA. You know, while we're in the spreadsheet world, we can control what's in there. But but when we get to the live PSA, that's where it's going to start to be more problematic, right? Maybe we need something that says, Yep, this data was already recorded.
OK, well, how do we do that? How do we, how do we ensure? And maybe it's the process flow. Maybe the process flow stores the data and it confirms whether there's a duplicate. If it's a duplicate, it won't enter that. So let's think about that.
And then this design allow easy access. This is about kind of design changes and scope changes for projects, updating the project, the budget, clinic clear view, project progress deviations. Yeah, so.
I I think really the the majority of this work really needs to be on the on the app part of this right now, figuring out what this looks like and what it would take to get our data in there. So Len, you could still be working on this process automation for the contact, especially with the aspect we just put in the last.
Interaction, right? And when we find out, I'm sure there will be an API that we can deliver to this glide to feed the content.

Lem   2:02:04
OK.

Peter Wolf   2:02:15
So I I think we'll probably have two feeds. One, we'll have a spreadsheet feed that will be the budget, the budget and rates that I don't know if we'll use a process feed or process flow would load them directly into the into the app.
But potentially we would say, well, you just put the spreadsheet here with the process of it with the budget and then we click the process flow and it grabs it, sends it in the API and sends it to the app. I don't know if that's going to be necessary because it doesn't sound like there's a whole bunch of steps.
But then taking the actual data, to me that's a process flow. We don't want to load it up manually. We'll want to grab it from the spreadsheet again temporarily, but ultimately from PSA and load it directly in. Now I was thinking maybe we could add some kind of spicy thing that would be like a a.
AI assessment. This would be kind of a cool aspect. AI assessment of the budget, where we are relative to budget. And it could say on track, you know, running over budget, over budget by this much. It could show which people are running over budget or under budget. I'm just trying to splice.
Make it, you know, add some cool feature with the AI could give you a commentary on the latest status. So maybe the process flow is is taking the budget from the the glide and.
Looking at taking that and providing the latest recent data and having a I assess that and make some commentary on it. So I think we can think about about that. Let's just get the get an app up and running, get a structure up and some.
Visual reporting and then we can figure out how we can add some sice to it.

Lem   2:04:04
OK.

Justin Kemmerer   2:04:05
Thank you.

Lem   2:04:06
Um, yeah.

Peter Wolf   2:04:07
Questions.

Justin Kemmerer   2:04:07
Yeah.

Lem   2:04:10
OK, um.

Justin Kemmerer   2:04:11
So Brian, you have the ability to get an account in the glide.

Lem   2:04:14
Oh, I see where you.

Bryan Wolf   2:04:17
Yeah, I just, I would have to look into it a little bit more and then I have access to all the card information for us to build by APIs and stuff like that.

Justin Kemmerer   2:04:17
Yeah.

Lem   2:04:18
OK.

Justin Kemmerer   2:04:26
But.

Peter Wolf   2:04:28
Yeah. So I'd say let's do a little more, maybe go out and see if there's tutorials on Glide and get a little sense of that and then.

Lem   2:04:38
OK.

Peter Wolf   2:04:38
Yeah, then we go from there.

Lem   2:04:39
OK.

Peter Wolf   2:04:43
OK.

Lem   2:04:44
OK, got noted.

Peter Wolf   2:04:45
I know this is pretty, this is pretty loose. I know this not. I'm not giving a lot of clarity because I feel like we got to get in there and get a sense of glide. We got to get a sense of what those reports are going to look like, what kind of how we got to feed the data, you know what there's APIs in, APIs out.

Bryan Wolf   2:04:45
Yeah, sounds good to me.

Peter Wolf   2:05:01
Because if there's APIs and and then we can feed the data in, then we have an API that can grab the data out for a given period. Then we could feed that to ChatGPT for an analysis and it could come back with an assessment, something like that.

Lem   2:05:15
Yep.

Peter Wolf   2:05:16
OK.

Justin Kemmerer   2:05:16
Yeah, see, see if we can do a a prototype thing at least, because I'm sure we're gonna learn some lessons along the way, yeah.

Peter Wolf   2:05:23
Absolutely. We've been doing that all along. He's learning nothing but lessons since it's all new ground. Hey, Lem, could you do some research on the API part of the glide? What API's in and API's out? What capabilities there are?

Lem   2:05:30
Yep.
OK.
OK, note that the glide angle.

Peter Wolf   2:05:40
All right. And Brian, if you could do some, Brian and and Justin, if you guys could do some research on on Glide and using it and setting it up and creating the dashboards and then yeah, get an account set up. Let's just go with Glide. I'm not going to compare to others based on what.
Chachi TV was saying let's just use that one for now. Let's find out if they have a free account to get started with and and.

Lem   2:06:00
Yeah, they actually have.
Do you have API documentation? Yep. OK, that's good.

Peter Wolf   2:06:06
Yeah, OK.

Bryan Wolf   2:06:09
Yeah, I can do that right after this call.

Peter Wolf   2:06:11
Awesome. All right guys, I will be available, but just not probably for much to get on calls. But I certainly if you have questions or anything and I'll be touching base, OK.

Justin Kemmerer   2:06:22
Sounds good.

Peter Wolf   2:06:22
All right, thanks. So I think I just sent. I just sent this. I sent the spreadsheet I sent. Oh, no, here on, let me. I'm gonna send the document. I'm gonna attach this document as well here too. It's not all that detailed, but.

Lem   2:06:23
OK, Peter.

Bryan Wolf   2:06:23
Sounds good.

Lem   2:06:29
The also this. Yeah, the document. OK.

Peter Wolf   2:06:37
So.
Let's put that there.
And then?
Where am I?
Yes, I want to push this to.
Automations.
Dashboard. Where the hell am I? Works though.
Process automation.
Okay.
OK.

Justin Kemmerer   2:07:54
Yeah, I mean really, really what we the next, the next move really is Peter, we have an extract whatever it is from PSA. We have fields, we have columns, we have data and we're just going to try and put that data into glide and see if we can create some sort of actionable.

Peter Wolf   2:07:56
All good. Yeah.

Lem   2:07:56
OK, got it.

Justin Kemmerer   2:08:13
We're not actual, but dashboard and analysis from that data, right? Yeah.

Peter Wolf   2:08:15
Yep.
Right. Just taking into context what you're doing at Chevron and thinking we potentially do it on a weekly basis, but more likely doing it on a monthly basis, but capability to do it each way, right? Because these larger projects, we probably want to be able to see where we are, how we're running on a weekly basis, right?

Justin Kemmerer   2:08:20
Yep.
Yeah.
Yeah, I guess.

Peter Wolf   2:08:38
OK. Appreciate it guys. I got to go talk to you.

Lem   2:08:40
OK, Peter, note that.

Justin Kemmerer   2:08:40
Yeah.
All right, thanks, sis.

Lem   2:08:43
OK.
You guys.
I. right

Peter Wolf stopped transcription


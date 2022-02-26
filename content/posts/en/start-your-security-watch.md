---
title: "Get started on your security watch"
date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["security", "cyber", "watch", "tips"]
author: "Shinichii"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: true
hidemeta: false
comments: false
description: "Why and how to do some cyberwatch."
#canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link

mermaid: true
---

Hi there ! Hope you're doing well !

I was willing to write on this subject for a long time but didn't really feel legitimate to do so as this activity seem trivial at first.

## A regular question I get

During the last years, I've gotten from friends and peers trying to start in the infosec industry the following question : 

> How do I break into cybersecurity ?

That question is a tough one. **What would you say ?** Should he get started in vulnerability testing ? Should he try to exploit a [Damn Vulnerable Web App]() ? Maybe buy a used disk on Ebay and forensic the shit out of it. Hell, you could even tell him to rent an ESXi and build a home lab.

I mean, those are all valid options. But I have an issue on all of them. They're all solely focused on the technical side of infosec. And don't get me wrong, all of these advices will give useful skills to navigate the field. But they're hard to get started on, and you can get quickly and easily frustrated.

Do I have a better solution ? Well I'm not sure if it's the best, but I think it helped me a lot getting better.

One of the main things I recommend newcomers or people interested in the field is to start a security watch.

## A security watch ? What is this ?

I'll start by giving out a troll answer : "You just follow shitposting accounts on Twitter until you understand why their shitpost is funny".

The concept of having a security watch is to keep up with the new discoveries in the field. Basically, be able to answer "What's going on ?".

Infosec is a vast domain and so there's always something new whether it is an attack, a vulnerability, a data leak, you get the picture. And that's actually what's great when starting out.

Because there's a lot of reading of do. And as [Peleus put it so well when I wanted to get started](https://netsec.ws/?p=468). 

> The ‘best’ way to learn often more time is spent procrastinating wondering these questions rather than dedicating the time to actually learning.

So get ready, today we're learning how to procrastinate efficiently.



## Isn't that kind of useless ?

Yeah, reading is for nerds. But if that was useless, then there wouldn't be a business centered around getting information to every kind of security practioneer. With now pentesters, security analysts, CISO, sometimes the rest of the C-Suite, getting the right information to the right person is a tough challenge and you need persons dedicated to this task to be done efficiently.

So you may join a structure that outsources this, but it's always useful to know how to go fetch the informations that could be relevant to your job. Or to feed your curiosity, both are valid excuses. 



## How do I get started ?

Basically it's going to be the following process on which we'll iterate.

{{< mermaid >}}

graph TD;

A[Choosing a topic];

B[Identifying sources];

C[Reading];

D[Taking notes];

E[Summarizing];

F[Challenging];

G[Lessons learned];

A --> B;

B --> C;

C --> D;

C --> E;

C --> F;

D --> G;

E --> G;

F --> G;

G -- Getting a new subject --> A;

G -- Finding more sources --> C

{{</ mermaid >}}



Still interested ? Let's go.

_Note : This is more of a process than a todo-list. You don't have to write everytime you read something. I seldom write about news nowadays but I still read._

### What would you like to learn ?

Well this question is not trivial. Do you already have a specific field of interest or a topic you wish to understand better ?

This will definitely ease the next step. If you do, you should search credible sources which will help.

If you don't, that's alright, you should start by looking into traditionnal media dedicated to infosec and work your way up from there.

### Finding sources

Welp, if you thought "I just have to Google 'cybersecurity news' ", you're not wrong. Here's some more resources to help you getting started : 

#### Generalist infosec medias

Those medias are usually covering a lot of different security subjects and they're a good starting point. Try to read at least one article on these sites and you should be started.

* [bleepingcomputer.com](https://bleepingcomputer.com)
* [zdnet.com](https://www.zdnet.com/topic/cyber-threats/)

You can also find some traditional outlets (Washington Post, New York Times...) which post about cyber, however I prefer to get these news from specialized outlets.

#### Security vendors websites

_Disclaimer : I am not paid for this article._

They usually have a blog to create interest to their products : 

* [NakedSecurity by Sophos](https://nakedsecurity.sophos.com)
* [The Media by Recorded Future](https://themedia.record)
* [Kaspersky daily](https://www.kaspersky.com/blog/)

#### Technical advisories resources

You want to get technical ? Let's get technical !

* [MITRE](https://cve.mitre.org) or [NIST CVE](https://nvd.nist.gov/vuln) websites (if you don't know yet what is a CVE, go read on it.)
* [OLD SCHOOL STYLE] Mailing lists of popular open source projects (like softwares from the Apache Foundation)
* Github (or other SVN websites) to find exploit codes about vulnerabilities
* [Exploit-db](https://www.exploit-db.com/) (same as the one before). Try to understand why the exploit is working the way it's intended. What is the cause of the vulnerability and how this code exploits it to achieve the desired outcome. (Oh btw, what's the outcome ? ;))

#### Conferences slides

You may find in here state-of-the-art research which could inspire you in researching more. 

* [BlackHat](https://www.blackhat.com/)
* [VirusBulletin](https://vblocalhost.com/conference/)
* [BotConf](https://www.botconf.eu/)
* [PancakesCon](https://pancakescon.com/) (Plus, you get knowledge about other areas unrelated to security.)

#### Security researchers' medias

They can sometimes be wrong but they usually have a lot of insight on their area of expertise.
You can follow them on their blogs or social media but **do** note they may speak about other elements than their job and you should be okay with that.

Here are some of my prefered accounts on Twitter: 

* [SwiftOnSecurity](https://twitter.com/SwiftOnSecurity)
* [Lesley Carhart](https://twitter.com/hacks4pancakes)
* [Tavis Ormandy](https://twitter.com/taviso)
* [Alexander Jaeger](https://twitter.com/alexanderjaeger)
* [Alice Climent](https://twitter.com/AliceCliment)

Usually they post interesting snippets related to infosec. They should trigger your curiosity.

**Be nice. They're people as well.**

You can also follow @campuscodi and @lorenzofb for everyday infosec news.

#### NGO

These people are doing incredible feats. When you read one of their posts, you're in to learn A LOT of things. 

* [BellingCat](https://bellingcat.com)
* [The Citizen Lab](https://citizenlab.ca)



## Q&A that you didn't ask for.

> Dude that's soooooo many sources ! I won't have time to read them all

Yeah, that's fine. Just read whenever you have time. The more you read, the easier it'll become. The point is to try to get into a routine where you get some keypoints weekly. The trick is to avoid developping FOMO.

> Wait you didn't speak about [...]. 

Well great ! You already found more sources than I could speak of. You're already doing great ! :)

I cannot list all existing sources. 

> But I'm too bad to understand anything

What do you have trouble understanding ? Note it, and research on this concept. If you don't know what's a "SQL Injection", try to search for this. Then you may find youself wondering what is SQL. That is good. You do not need to write a thesis. Just get enough information to understand what is going on. If you know someone that has more technical skills in the domain, try to reach out to him. If you learned at least one thing, then it was worth it. If you still don't understand, don't sweat it, it will come eventually.

> This is not technical enough / This is too technical

Then I have a fun challenge for you. 

If the information is too technical, how would you summarize it to someone with NO infosec background ? If you see yourself explaining the technical terms with only other technical terms, you may find yourself going through a rabbit hole.

Not technical enough ? How could this information be pertinent to someone working on the technical side ? How would you frame it ?

> What tool should I use to gather these infos ?

Good question. If you go on websites, you could use a RSS feed parser to get the new infos. For mailing lists, you just need a mail address and client. Usually I just use my browser and go on the different websites. That and Twitter.

> I don't see how reading will magically make me great at cybersecurity

Because the goal is not to become "magically great" at cybersecurity. In my opinion, the goal is to foster curiosity and to create connections between the elements you know. To try to relate what you read with what you've learned. And then to identify new elements to research, to deep dive into, in order to better yourself. It's not magical, but it will help in the long term :)

Now here's my list of questions you should ask yourself to have an efficient watch.

#### Technical article 

* What is the theme of the article ?
* What is the technology used ? Where is it used ? What for ? 
* Is it widely used ?
* [If it's a vulnerability or new attack campaign] What is the category of the vulnerability ? (Get some inspiration from MITRE)
* Can it be exploited easily ? How ? (For this part, you do not have to write an exploit, but try to retrace the scenario as precisely as you can)
* What's the impact ? Will the application crash ? Will the attacker execute code ? What can the attacker do ?
* Is there any security fix available ? How is the vulnerability fixed ? (Note : Some editors have trouble being transparent on this point) Is there any other way to avoid exploitation without patching ? (Yes, it's suboptimal. But this question WILL comeback more often than you think.)
* Is there any publicly available code that implements this attack ? What does it do ?

If you can answer all these questions, congratulations ! Usually one article won't be enough to reply to all these questions, but do not hesitate to research. If you can't answer all of these questions don't fret, maybe the information is just unavailable (and usually, that's okay.)



#### Informations 

* Who is this article about ? Why ?
* What happened ? If you had to explain to someone who doesn't know anything about cybersecurity, how would you explain ?
* Why is this important ?
* If someone technical asked you details about this news article, what would you say to him ?
* Is there a specific entity or sector targeted ?
* Who is targeting ? Is this actor known ? If yes, what is (s.)he known for ?



#### Whitepapers / Publications

Read it, and try to summarize it to share with your peers. What information would you prioritize ? Try to keep it simple and make it stick.



Now try to start a routine to just get an article, read it and summarize it. Then contextualize it. Information without context is meaningless. Try to do once a week and as you go on, you'll read more and more (but you surely won't formalize it as much :)).



Anyway ! Happy reading, happy summarizing and happy hacking ;)



_Special thanks to Alice Climent for proofreading my article. Go see her blog !_ 

---

layout: col-sidebar
title: OWASP Copenhagen
tags: example-tag
level: 4

region: Europe
meetup-group: OWASP-Copenhagen-Chapter
country: Denmark
postal-code: 

---
The Copenhagen local chapter organizes quarterly events to promote OWASP and information security in general.

## Events
In this page we keep track of all past events that we organized, and is rarely updated. Go to [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/)] to check the latest events and subscribe to get the latest updates from our chapter.

If interested in giving a talk, please send a message to [Alessandro Bruni](mailto:Alessandro.Bruni@owasp.org).

### Thursday, May 23, 2024

A night of honeypots and information flow security

#### Can we outsmart the adversaries? (Effective) Cyber Deception with Honeypots 

In today's ever-evolving cyber threat landscape, traditional defence mechanisms often struggle to keep pace with attacker ingenuity. Cyber deception offers a proactive approach, utilizing traps and deceiving tactics to lure attackers into controlled environments. Honeypots are one of the prominent techniques of cyber deception that act as decoy systems for capturing attacks and analyzing the adversary strategy. They provide an early detection mechanism as well as a method for learning how adversaries work and think. However, over the past years, several researchers have shown methods for fingerprinting honeypots. This significantly decreases the value of a honeypot; if an attacker can recognize the existence of such a system, they can evade it. This talk delves into the world of cyber deception, focusing on honeypots, their efficacy, and some fingerprinting techniques from my research. We'll explore how honeypots function and the contributions from The Honeynet Project, a non-profit, open-source community. 

**Speaker**: [[Shreyas Srinivas](https://www.linkedin.com/in/shreyas-srinivasa-ph-d-47038b13/overlay/contact-info/)] is Cyber Security Specialist at TERMA Group, Co-founder of Selene CTI and previously Security Researcher at Aalborg University. He is contributor to the [Honeynet project](https://www.honeynet.org/), a non-profit dedicated to investigating the latest attacks and developing open source security tools to improve Internet security.

#### Information-Flow Security for the Working Software Engineer

How does information flow through your software? Awareness of this gives you a new perspective when writing software with security requirements; it helps you avoid introducing information leaks into software, and gives you a conceptual framework for reasoning about software security in general.

In this talk, you will meet concepts like information leak, sources & sinks, dependencies, side–channels, and flow policies. You will learn to identify information flows in software, to express application–specific security requirements as flow policies, and to implement software that adheres to said flow policies.

Want to try this out? Then bring a laptop; right after the talks, I will organize a little activity where you can tinker with `ifc-ts` - my TypeScript library for expressing flow policies. In `ifc-ts`, flow policy checks are reduced to checks performed by TypeScript's type checker. Thus, if your code type-checks, then your code is guaranteed to adhere to the flow policies expressed therein.

**Speaker:**
[[Willard Rafnsson](https://www.willardthor.com/)] is Associate Professor at the IT University of Copenhagen (ITU). He is member of the Center for Information Security and Trust (CISAT), as well as the Programming, Logic and Semantics (PLS) and Software Quality Research (SQUARE) groups.

### Tuesday, April 9, 2024 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/300007686/)]

#### OSINTer
OSINTer is a new, digital platform tailored towards breezing through the complexities involved in extracting strategic cyber threat intelligence from news about cyber threats. Designed to streamline the traditionally laborious process of manually tracing and compiling data, OSINTer offers an automated, efficient means of identification, collection, and tracking of the ever moving cyberthreat landscape. At this workshop we will delve into the platform's journey from a spark of an idea to a robust platform, currently serving 30.000 monthly users, and go over how you can integrate it into your daily work, helping you stay on top of the constant inflow of information.

**Speaker bio**
Bertram Madsen and David Clayton are co-conspirators in the realm of cybersecurity, with each specializing in different facets of the industry to combat digital threats effectively. Bertram, a proficient full-stack software developer, emphasizes open-source development and community collaboration, manifesting in the creation of a range of cybersecurity solutions. Most notably, he's responsible for the development of OSINTer, a digital platform designed to ease collection of strategic cyber threat intelligence (CTI), and in collaboration with David, they are attempting to rethink how we do CTI. David is an established leader within Denmark's cybersecurity landscape, with a breadth of experience spanning various critical infrastructure sectors, financial security and strategic leadership roles. He's renowned for championing the SagaLabs concept, gaining TF-CSIRT certification for his team, and providing exceptional insights as one of only two official SIM3 auditors in Denmark.

#### Tracking down the killer
In the mid 1990’s Rasmus Kierkegaard Kristiansen – suspected of killing and dismembering a business partner I Portugal – managed to escape and hide from authorities. After a longer period of intense investigation, the trail was considered cold.
In 2018, 25 years after the murder, the unsolved case was still bugging the leading investigator at the time. He teams up with a TV production company to give the investigation another shot. As a
base requirement for funding, Kristoffer Scavenius was tasked with making a probable case that the murderer was in fact still alive. After initial setbacks, Kristoffer was eventually able to make the
case that Rasmus Kierkegaard Kristiansen was still alive and well, living in Sao Paolo, Brazil.
The talk will discuss some of the OSINT approaches used in this investigation.

**Speaker bio**
Kristoffer Scavenius has worked in OSINT since 2013 and has held positions as researcher/programmer in both government and the private sector.

### Tuesday, January 23, 2024 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/297956007/)]

#### Navigating the AI Labyrinth: Ethics, Security, and Best Practices

This talk offers a comprehensive exploration of Artificial Intelligence (AI) from its historical evolution to the latest developments in AI security and ethics. Key topics include:

- A Brief History of AI: A snapshot of the pivotal milestones in AI development.
- AI and Ethics: Understanding AI's business impact, ethical guidelines, best practices, and risk mitigation strategies.
- Robustness & Reliability of AI Code Generation: Addressing common misuse patterns and reliability metrics in AI systems.
- Artificial Intelligence Security Introduction: Analyzing historical AI failures to draw lessons and improve future applications.
- OWASP Top Ten for Large Language Models (LLMs): A deep dive into security considerations specific to LLMs, ranging from prompt injection to model theft.
- Threat Modeling AI Systems: Outlining methodologies to assess and mitigate AI-related threats.
- Hugging Face Open Source AI Tools: Exploring the utility and application of these tools in AI research.
- Differential Privacy and AI: Discussing the principles of differential privacy in the context of AI.
- NIST AI Risk Framework: An overview of NIST's guidelines for AI risk management.
- EU AI Act: Analysis and impact on AI development and use.

The talk aims to provide attendees with a nuanced understanding of AI's ethical implications, security challenges, and practical approaches for secure and responsible AI deployment.

#### AppSec Training

In the rapidly evolving realm of web development and application security, the OWASP Top 10 remains a cornerstone document, acting as a beacon for developers and security professionals alike. Reflecting a broad-based consensus, it spotlights the most critical security risks threatening web applications, thereby shaping the frontier of secure coding techniques.
With an ever-increasing emphasis on web-based interactions, the significance of a deep understanding of these risks is paramount. As developers etch lines of code giving life to web applications, a firm grasp of secure coding practices becomes not merely beneficial, but essential.
This immersive and engaging presentation seeks to equip attendees with a comprehensive understanding of the OWASP Top Ten 2022 release, intending to empower developers with the knowledge necessary to author secure, resilient software. As we navigate through this labyrinth, we shall focus on in-depth discussions around:

- A01:2021-Broken Access Control
- A02:2021-Cryptographic Failure
- A03:2021-Injection
- A04:2021-Insecure Design
- A05:2021-Security Misconfiguration
- A06:2021-Vulnerable and Outdated Components
- A07:2021-Identification and Authentication Failures
- A08:2021-Software and Data Integrity Failures
- A09:2021-Security Logging and Monitoring Failure
- A10:2021-Server-Side Request Forgery

### Thursday, December 5, 2023 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/297344292/)]

A night of Backdoors & Breaches with a virtual touch of John Strand

John Strand from Black Hills Information Security (BHIS) will join us online and tell us about their incident response game; Backdoors & Breaches, why you should use it and how it can help you raise awareness among your peers

Afterwards Jon Bevers (also from BHIS) will show us how to play Backdoors & Breaches. Jon will also join us online.

Jon is one of BHIS' European community ambassadors and travels Europe from his home in Krakow, Poland. Jon was in Copenhagen recently as part of BSides København where he also had the opportunity to talk to you about Backboors & Breaches and he might even have given you a deck already. If not, fear not as we will have plenty of decks to share with you (and keep).

After the talk and demo from John and Jon it's time for pizza, drinks and the opportunity to get some hands on experience and try to game for yourself.

We hope to see you there!

### Thursday, September 21, 2023 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/296032478/)]

A night of Blackteaming, Supply Chain Attacks and DEFCON CTF

#### Brian Harris: War Stories in Physical Penetration Testing
This is going to be a talk about the how the world continues to drive full speed ahead on cyber security, but when it comes to physical security we are often around 10-20 years behind. I will show some war stories, techniques and the like to highlight just how vulnerable even high security locations are when it comes to physical penetration testing and that if you have no physical security, you have no cyber security

Brian Harris has a long career of phyiscal pen testing (aka blackteaming) behind him. He can truly do some amazing stuff that can make you stop and wonder why we even bother having locks in the first place, so obviously you don't want to miss this!

#### Mikkel Rømer: Infiltrating modern companies using Supply Chain Attacks
Case: Visual Studio Code
Within this session we will be deep diving into Supply Chain attacks. Supply chain attacks is a growing phenomenon, which allows the adversary to infiltrate widely whilst gaining the trust of legitimate software brands. This session will be technical. We will be designing and implementing techniques throughout the presentation until a final malware is ready for deployment. With a fully custom build malware, targeting the modern text- and code editing application Visual Studio Code, we will investigate its potential in terms of detection within top class endpoint detect and response software such as CrowdStrike Falcon and Microsoft Defender for Endpoint. We will compare the results with similar execution done via the notorious adversary framework Cobalt Strike. Brace yourself for a thrilling journey through the shadows of the digital realm, where adversaries roam undetected.

#### Adam Blatchley Hansen and William Ben Embarek: How to get 6th place at DEFCON CTF!
Every year the legendary hacker convention DEFCON hosts one of the oldest and most competitive cybersecurity CTF competitions in the world. This year, Kalmarunionen joined forces with teams from around the nordics as NORSECODE, and travelled to the finals in Las Vegas, where they took home a very impressive 6th place overall. In this talk Adam and William will share the story of the teams road to qualifying for, and competing at the DEFCON CTF finals. Introducing the world of "CTF" hacking competitions from the perspective of a top competitive team, and giving an inside look at what it takes to compete in international hacking competitions at the very highest level. From organisational strategies to interesting CTF challenges to internal team tooling, they'll go over what it took for Norsecode to outperform many much larger and more experienced teams, as well as some of the more unexpected challenges they encountered along the way!
Bio: Adam is a PhD student studying Cryptography at Aarhus university, as well Head Coach of Cyberlandsholdet and the current captain of Kalmarunionen and Norsecode. William is a Pentester at TDC NET, as well as being a longtime CTF player with Kalmarunionen he also handled onsite infrastructure for Norsecode during DEFCON finals in Vegas.

### Wednesday, November 9, 2022 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/289468129/)]

A night of collaboration, secure coding and -implementation

#### Klaus Agnoletti
Klaus will talk about how CrowdSec was able to enable the entire infosec community to work together by detecting attempts to exploit a critical 0day, reporting them centrally, thereby enabling anyone to protect themselves. CrowdSec is FOSS, collaborative threat intelligence and threat mitigation. More info at https://crowdsec.net

#### Sébastien Gondron
Manual code inspection is a very effective measure in detecting and preventing vulnerabilities and weaknesses. However, navigating applications that can span millions of lines of code can be an arduous task. Sébastien will share his experience and show how to make the best of static analysis tools to facilitate and enhance the manual inspection.

#### Linus Lagerhjelm
You have designed your application with security in mind but how do you make sure that the implementation is actually following these principles? Any sort of software system, even a simple one, usually consists of a lot of moving parts in a lot of different layers and getting everything correct can sometimes feel overwhelming. In this presentation, Linus will present a 'checklist' with the most important security controlls to apply in each layer of the application, from the database to the user's client. When security is applied in every layer of the application, the impact of a vulnerability will be much smaller.

### Tuesday, April 26, 2022 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/285064536/)]

#### Email spoofing via marketing platforms, By Martin Sohn Christensen, Security Advisor at Improsec.

Many mechanisms exist to prevent email spoofing, such as SPF, DKIM, and DMARC, but what if these were not sufficient even when configured correctly? Martin will present known anti-spoofing mechanisms and share his research on vulnerabilities in marketing platforms that can lead to effective email spoofing for threat actors and red teams.

#### Kalmarunionen in a world of CTF’s, By Morten Eskildsen, Kalmarunionen

Kalmarunionen is one of the top teams when talking cybersecurity and Capture The Flag (CTF) competitions in the whole world. So in this talk we will have a deep dive into what a CTF actually is and it’s applicability to the real world. The focus will be to look at it from the viewpoint of Kalmarunionen, bringing you stories and hard-earned learnings from some of the many competitions we have been a part of. We will discuss overall tactics and shortcomings before finally diving into how it can be applied in the real world.

### Thursday, February 17, 2022 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/283634757/)]

#### Magnus Stubman, Senior Red Team Consultant at Mandiant and former security consultant at Improsec and F-Secure.

Magnus started his career as a software developer and later turned his attention to Cyber Security, specifically attack and penetration testing, both digital and physical. Today Magnus specialize in Red Teaming.

The 'Initial Access' phase is part of every intrusion, regardless if it's a ransomware crew, nation state threat actor, or Red Team behind the attack. In Magnus' talk, he will be deep diving into this specific phase, and deliver a case study of a particular malware payload.

#### Linus Kvarnhammar, a cyber security professional and hacker for over 10 years. 

Linus will share some juicy details from the Swedish TV series “Hackad”. He’ll discuss how easy (or not) it is to hack private people, social media personalities and companies.

After the two talks there will be time for us to hang out and catch-up after two years captivity. Please be there at 17.00 / 5 PM. If it is your first time at ITU, you can just follow the signs that will be put up.

### Tuesday, October 5, 2021 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/280774265/)]

#### Dimitry: Did you just assume your product is secure?
People tend to assume things. I know I do. It's perfectly normal, it's how our brains evolved to work. Join me in exploring the role of assumptions in our everyday life and how that impacts the security of products we build. Or did I just assume that they do?.. Hmm.

#### Jonas: ImproHound Workshop: Protect your Domain Admins with tiering
It is not viable for system administrators and defenders in a large Active Directory (AD) environment to ensure all AD objects have only the exact permissions they need. It is too big of a task, why many organizations are vulnerable to AD attacks due to too loose or wrong permissions. At the same time, credential theft may lead to privileges AD users having their password stolen when they login to compromised computers. These vulnerabilities are chainable, why you in many AD environments can escalate your rights to Domain Admin no matter what computer or user you have.

### Thursday, July 1, 2021 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/278836329/)]

Scale Security by Embracing Secure Defaults and Best-practices for DevSecOps

####  Adam Berman : Scale Security by Embracing Secure Defaults

We’re in the middle of a significant shift in how security teams operate and prioritize their limited budget and person-time. Historically, as an industry, we’ve focused on building tools to identify vulnerabilities. While we’ve built impressive tools, these approaches have failed to address the challenges of modern engineering teams. Specifically, these tools often are too slow, require a prohibitive amount of security engineer time and domain expertise to tune, overwhelm users with false positives, and most importantly, do not ultimately raise a company’s security bar. But there’s another way.

When done correctly, combining secure defaults and lightweight checks that enforce invariants (properties that must always hold), organizations can solve classes of vulnerabilities by construction, preventing bug whack-a-mole. In this talk, we’ll present a practical step-by-step methodology for:

-    Choosing what to focus your AppSec resources on
-    How to combine secure defaults + lightweight invariant enforcement to eradicate entire vulnerability classes
-    How to integrate continuous code scanning into your CI/CD processes in a way that’s fast, high signal, and low friction for developers
-    How to use an open source, lightweight security linting tool to find bugs and anti-patterns specific to your company

#### Martin Clausen : Best-practices for DevSecOps

The presentation will show best-practices for DevSecOps (i.e. security part) and includes a case study about supply chain controls related to the Solarwinds incident.

### Thursday, May 20, 2021 [[meetup](https://www.meetup.com/owasp-copenhagen-chapter/events/277996588/)]

#### Per Thorsheim: "How I hacked the largest bank in Norway using a 1-page paper form"

We are so lucky that Per has chosen to premier his latest talk for us here at OWASP Copenhagen. So come join us for this. Per is a fantastic storyteller :-)

Back in 2019-2020 banks were running a campaign saying you should never share your BankID with anyone. Never give your OTP or password to anyone. Use a “power of attorney” (Danish: Fuldmagt) to give another person access to your bank account instead, to act on your behalf if needed. So Per Thorsheim got curious and started to investigate with a few friends.
This is the story on how they found a way to gain access to probably any personal account at the largest bank in Norway, using a 1-page paper form from the bank itself.

This is not a technical talk, but a talk about UX, design & process flaws, and responsible disclosure.

Could this be possible with your bank?

#### Stu: Why You Should Build a Community!
Stu discusses why community is important for fostering collaboration, forming important connections, mentoring, and the great things that can happen from this.

Stu shares his experience of building an infosec community The Many Hats Club, the highs and lows, but ultimately why this is something we should all strive to do. The talk will cover the following:

-    Why communities are vital in infosec
-    How to start out
-    Platforms
-    Pitfalls and things to avoid (from my many mistakes)
-    Mentoring
-    Key achievements - 2 x cons, CTF's, Podcasts, community projects, research, responsible disclosures etc.
-    Mods/Admins, COC etc things you cannot live without.
-    Why you should all build a community right now!
-    Q&A


### Thursday, April 29, 2021 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/277670961/)]

POST-QUANTUM DIGITAL SIGNATURES

Sahana Sridhar:
https://www.linkedin.com/in/sahsridh/

Former IBM Test Specialist and Master of Science from Norwegian University of Science and Technology (NTNU). Sahana will enlighten you on the findings of her master thesis on post-quantum digital signatures based on identification schemes.

THE FAILURES OF NEMID AND THE THREAT OF QUANTUM COMPUTERS

Lars Embøll Nielsen:
https://www.linkedin.com/in/qkd/

Lars will take you on a journey through the failures of NemID, the legal landscape of digital signatures in EU and why Quantum Computers can be a threat to the way we currently keep digital signatures secure.

AS ALWAYS....
... you will have the opportunity to ask questions for the participants

### Thursday, March 25, 2021 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/276419652/)]

DISCOUNT PHISH BURN BETTER and USER MODE API HOOKS AND BYPASSES

Note: THIS IS AN ONLINE EVENT! Link to stream will be released here prior to the event.

THE SPEAKER

Magnus Stubman, Security Advisor at Improsec and former security consultant at F-Secure and Zacco.
https://www.linkedin.com/in/magnusstubman/

Magnus started his career as a software developer and later turned his attention to Cyber Security, specifically attack and penetration testing, both digital and physical. Today Magnus specialize in Red Teaming.

Magnus will do something we haven't facilited in OWASP CPH before - He will do a double-presentation - to take you on a technical security ride.. Keep reading to learn more...

### Thursday, February 18, 2021 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/275689509/)]

SIEM and Elasticsearch for absolute beginners

Curious about SIEM and/or Elastic? You heard about it, but don't really know what it is? You know what it is, but curious about what to do next? This is the talk for you!
We will have a few subjects for you:
- SIEM as a concept
- Elastic as platform and it's usability
- Introduction to Elastic SIEM
- Introduction to TheHive - a security incident response platform that can help you get the most out of your Elastic platform.

Elastic is available for free - so is TheHive. So everybody can be on board here.

### Tuesday, February 16, 2021 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/276167153/)]

Mød Alexander Krog, en af Lyrebirds ethical hackers (OWASP youth event)

Disclaimer: the event will be in Danish, targeted at students 15-25 years old. Everyone is welcome to participate.

Har du altid undret dig over hvordan livet som professionel hacker er? Måske vil du gerne være én? Mød Alexander Krog, som sammen med sit hold af hackere ”Lyrebirds” opdagede “Cablehaunt”, en kritisk sårbarhed som var i stand til at give hackere adgang til modems rundt omkring i hele verden, hvilket potentielt ville have katastrofale konsekvenser. Alex vil fortælle sin historie, hvordan han endte op som en der professionelt finder IT-sikkerhedsmæssigfe sårbarheder, hvordan de fandt det nævnte sikkerhedshul. Alex deler sit indblik og erfaring indenfor IT-sikkerheds verdenen. Efterfølgende stiller Alex op til alle dine spørgsmål på YouTube.


### January 21st, 2021 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/275404398/)]

As we move into this mid- and post-pandemic world with remote and in-office work blending, what must organizations consider, in order to sustain data and application security and privacy while still considering an efficient working- and user experience? How does remote work change the security stack mix? And what’s still missing?

We will also be diving into how innovation in cyber became a must and how that can and will support companies and users on a daily basis.

YOUR PANELISTS ARE

Lone Juul Dransfeldt Christensen, Senior Security Architect at Bang & Olufsen. Formely in NNIT and the Danish Police.
https://www.linkedin.com/in/ldransfeldt/

Martin Clausen, Chief Security Architect, Head of Architecture, Research and Development at Saxo Bank. Former Head of Cyber Innovation Labs at Danske Bank.
https://www.linkedin.com/in/martin-clausen/

Luke Herbert-Andersen, PhD in Computer Science.
https://www.linkedin.com/in/lukeherbert/

Oksana Kulyk, Assistant Professor, Center for Information Security and Trust, IT-Universtiy of Copenhagen. Co-PI of the ASCD project (Assessment on the Status of CyberSecurity in Denmark).
https://twitter.com/okskulyk/


### December 10th, 2020 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/274829683/)]

#### Tim Sloth Jørgensen
Program chief for cybersecurity in the Danish Industry Foundation, Chief Strategy Officer of Defence and Security at Terma A/S, advisor to the Danish Ministry og Defence, professor at Copenhagen Business School, former Chief of the Danish Defence.
https://www.linkedin.com/in/tim-sloth-jorgensen-3b199a23/

Tim will share his insights based on several years of first-hand experience, and will tell us about what they are looking for when investing in new cybersecurity projects - What is he anticipating? Is he hopeful or concerned for the future?

#### Rasmus L. Fruergaard-Pedersen, Security Software Engineer at Kamstrup
(https://www.linkedin.com/in/rfruergaard/)

Rasmus enables the business to use security correctly.
Innovation in software, sensors and communications is what the company Kamstrup is associated with, but how do they ensure a sufficient security stance across a business spanning that wide?
Rasmus will talk briefly about technical security champions, business security principles and how to ensure a common understanding of what security is acceptable.

What will you learn from this talk?
Translating technical security to business risk; Making security a competitive parameter; Questions to ask when wanting to secure a product in a complex business environment.

### November 18th, 2020 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/274191483/)]

#### A Night of Fraud and Deception
This time we will be focusing on fraud - primarily past, present and future of fraud and related crime in Denmark.
The event will feature talks from Sune Gabelgård, Fraud Crusader at https://www.mobilepay.dk/ and Ketil Clorius, Head of Global Fraud Management at https://danskebank.dk/. We'll talk about juicy, crazy mindblowing case studies and methods used by threat actors. History and future will also be touched upon.

### May 5th, 2020 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/270213570/)]

#### “Going Phishin’ with GoPhish” by Alethe Denis and Patrick Laverty
Want to learn how to put together a phishing campaign? Great, let’s do it. We will use the free and open-source tool GoPhish to launch campaigns. We’ll show how to install, set up GoPhish, create each of the necessary pieces and launch. We’ll also talk about pretexts and how “mean” should we be, and mix in some stories of phishing successes and failures.

### April 16th, 2020 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/268476837/)]

#### Claus Vesthammer
Ethics and philosophy, politics and procedures. Experiences with the framework of responsible disclosure, positive and negative from the real world. Common problems regarding detection of vulnerabilities vs. hacking.

#### Magnus K Stubman
Magnus will then provide a quick introduction to finding file permissions and privileged escalation vulnerabilities (DLL hijacking, etc.) in Windows with procmon, accessenum, ghidra and IOninja. And review related selected CVEs, our own and others.

#### Sticks & Stones, Breaking Bones, by Lucas Lundgren
Experiences in pentesting medical devices, including DICOM and PACS machines. References here:
https://www.linkedin.com/pulse/sticks-stones-breaking-bones-lucas-lundgren/
https://techcrunch.com/2020/01/10/medical-images-exposed-pacs/

### January 30th, 2020 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/267302307/)]

#### Clickshare [[slides](https://drive.google.com/open?id=1fcwwGMNdOAk_H3bDNgqEtJsDuqK7IXCk)]
Dmitry Janushkevich from F-Secure will talk about major vulnerabilities found in ClickShare. More info on https://labs.f-secure.com/advisories/multiple-vulnerabilities-in-barco-clickshare/

#### Cable haunt: [[slides](https://drive.google.com/open?id=1lRi4NLDpwHRFaqJ-NAi2oHTVoIB6Zaf0)]
Researchers (mostly) from Lyrebirds found critical vulnerabilites found in various cable modems. They will talk about what they found and a bit on how. More info at https://cablehaunt.com/.
Prior to the meeting it's possible to join #chapters-copenhagen in the OWASP slack (invite link below) and ask questions and suggest topics to cover. So please do so.

#### DMARC (and friends): [[slides](https://drive.google.com/open?id=1XBz_OVgkzOZzykwWttK2VcuT1MeCVGpy)]
Dennis Kjær Jensen (or just SiGNOUT) will tell you about DMARC, SPF and all the other email extending security features that you simply have to have enabled on your domain to not look to much like a fool now that it's 2020 and those vulnerabilities have been around forever now. After that Kevin Kruse will tell you what he has done to secure his own email domain (via Proton Mail) and hopefully inspire you to do the same.

#### 36c3 wrap-up: [[slides](https://drive.google.com/open?id=1nxWEH_FLk-2PUnwn5QHllgkinLYaoc05)]
Denis Smajlović will tell us about his (mis)adventures on his recent trip to Leipzig and 36c3.

#### Backdoors & Breaches:
Klaus Agnoletti will introduce you to 'Backdoors & Breaches', a card game designed to train the incident response process. After pizza I'll set up a few gaming sessions. If you got a game at BSides København already, please bring it along with a 20-sided dice. If you don't have it, fear not, I have a few games left that I'll give away.

### November 25th, 2019 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/266380643/)]

#### Let’s Encrypt: An Automated Certificate Authority to Encrypt the Entire Web
*Speaker:* Alex Halderman

*Abstract:* Let’s Encrypt is a free, open, and automated HTTPS certificate authority (CA) created to advance HTTPS adoption to the entire Web. Since its launch in late 2015, Let’s Encrypt has grown to become theworld’s largest HTTPS CA, accounting for more currently valid certificates than all other browser-trusted CAs combined. By January2019, it had issued over 538 million certificates for 223 million domain names. We describe how we built Let’s Encrypt, including the architecture of the CA software system (Boulder) and the structure of the organization that operates it (ISRG), and we discuss lessons learned from the experience. We also describe the design of ACME,the IETF-standard protocol we created to automate CA–server inter-actions and certificate issuance, and survey the diverse ecosystem of ACME clients, including Certbot, a software agent we created to automate HTTPS deployment. Finally, we measure Let’s Encrypt’s impact on the Web and the CA ecosystem. We hope that the success of Let’s Encrypt can provide a model for further enhancements to the Web PKI and for future Internet security infrastructure.

#### Social Engineering For Physical Intrusions
*Speaker:* Sarka "the pirate queen"

*Objectives:* Objective is to let people understand what are different social engineering exploits that can be used against them, their employees or their loved ones. After holistic approach of different human attack vectors I use for my social engineering attacks for physical intrusions, I will step to the defensive side to let the audience understand what controls to put in place to stop a real malicious attackers.

*Description:* Social Engineering has many different faces from using open source intelligence (OSINT), phishing, vishing, smishing and all the other '-ishings',dropping weaponized USB flash drives to eventually getting right in middle of your target's own office! As there are many tools and described ways of all the -ishings, but almost all of them do not require any interaction with target. And I would like to focus on physical intrusions. If you are interested how I break into buildings like a pirate queen, I will explain how to interact with our target directly and that requires certain knowledge of techniques and skills.

There are many different skills and techniques while approaching a human target and testing their security. I would like to look at different human attack vectors.I also look at how to use this knowledge to not only understand world around us and better our own situational awareness, but I also explain why this is a fun topic we should teach our employees that would help with defending our company but also our loved ones. I like to uncover my offensive thinking while using facial expressions , body language or psychology research but I also see myself though someone else's eyes,  who's daily bread is defending networks and tries to understand human factor while deploying defense in depth at work.

### August 29th, 2019 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/263639514/)]
####  Reporting on BSides Las Vegas and DEF CON

*Presenter:* Christian Dinesen, NNIT
####  Approaching Bluetooth in 2019
*Presenter:* Martin Schroter
*Abstract:* Although Bluetooth has been around for the better part of 30 years, we keep innovating on the technology and new uses are found every year.  I want to cover: vulnerabilities in Bluetooth 1 up to 5; understanding the cryptography of Bluetooth; going over the considerations your company needs to make, when you decide to adopt Bluetooth into your infrastructure; know your tools Ubertooth sniffing, btlejuice, btlejack, gattacker; jamming Bluetooth drones mid air!  Can we really trust this technology and what are the challenges?

####  Experiences in OSINT
*Presenter:* Bjarne Tersbøl, Special Advisor at Konkurrence- og Forbrugerstyrelsen / Danish Competition and Consumer Autority

### May 27th, 2019 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/260941433/)]
####  Security in LPWAN IoT, a comparison (SigFox, LoRaWaN, NB-IoT)
*Name:* Florian Coman
*Bio:* Security Analyst at TDC, MSc in Telecommunication at DTU
*Abstract:* I've investigated the security features and possible vulnerabilities of some LPWAN IoT technologies: the license-free SigFox and LoRaWAN and the cellular NB-IoT. I have looked at their End-to-End architecture (from end-device to application server) and I will present some of my findings during the talk.

####  “Just Hacker Things with Jayson”
*Name:* Jayson E. Street (http://jaysonestreet.com/) 
*Abstract:* Instead of a usual talk, this will be an open discussion. He will share several stories of his travels & exploits (focused around Social Engineering where Jayson has mnay years of experience) but mostly will be there to answer questions about hacking, blue team, red team and DEF CON Groups! So come with questions and expect a few answers and a lot of great hugs!

### March 28th, 2019 [[meetup](https://www.meetup.com/OWASP-Copenhagen-Chapter/events/258987408/)]
####  XSSER: From XSS to RCE 3.0 [[slides](https://drive.google.com/open?id=1TPKkvLBot-h9dmk_wHupRj7LTNFKHUR2)]
*Abstract:* This presentation demonstrates how an attacker can utilise XSS to execute arbitrary code on the web server when an administrative user inadvertently triggers a hidden XSS payload. Custom tools and payloads integrated with Metasploit's Meterpreter in a highly automated approach will be demonstrated live, including post-exploitation scenarios and interesting data that can be obtained from compromised web applications. This version includes more payloads for common web apps and various other improvements too!"  
*Author:* Hans-Michael Varbaek / TDC Group

### October 25th, 2018 [[meetup](https://www.eventbrite.com/e/owasp-local-meetup-tickets-50365223740#)]
####  An ice-cold Boot to break BitLocker [[slides](https://drive.google.com/open?id=1VDfS-wNM7ywDW1NwMWmOCzcAd1yiVNCG)]
*Authors:* Olle Segerdahl & Pasi Saarinen / F-Secure

## Sponsors
- TDC <https://tdc.dk/>
- Dubex <https://www.dubex.dk/>
- IT-University of Copenhagen <https://www.itu.dk/>
- Copenhagen Business School <https://www.cbs.dk/>

## Local News

Meeting Locations: IT University of Copenhagen, Copenhagen Business School

Everyone is welcome to join us at our chapter meetings.


# hi, i'm marissa 
### i care about systems, i care about problems that intersect with other problems that are complicated and tricky and necessary to tackle, i care about people, i care about doing good work with good people.

i work a lot because i care about what i do and i talk about that below but i also do a lot outside of work too including community organizing with the interference archive in brooklyn ny, writing and publishing that writing in various zines, online publications, lit mags, and i run all the time (you can find me on strava :))

### work i've done
technical program manager @ aws
- owned everything AI for global enablement across the aws proserve org. here's the [blog post](https://aws.amazon.com/blogs/machine-learning/accelerate-enterprise-solutions-with-agentic-ai-powered-consulting-introducing-aws-professional-service-agents/) for the external launch i did all the enablement for in my third week on the job.
- what is enablement? it's basically how can we equip people with the tools and expertise they need to deliver quality solutions to the customer. i have __a lot__ of opinions on this and how this is done and sometimes that is not always loved because, well, people get attached to their way of working, but i know that at some point my ideas will have to adapt and change too because the world keeps moving especially AI so i keep pushing us to the frontier of what we can do.
- also overhauled multiple internal processes because i __love processes and ops optimization__ like let's perform our best and do our best work when we cut down on all the time we wasted finding things that are spread across five different knowledge bases, or that have already been done, or that someone else has an idea for, or etc etc etc.

software engineer @ amazon
- worked on ads specifically in geo-targeting on both the supply and demand side which was pretty cool because our bidding system gets millions of requests a day and requires such well defined, thoroughly tested, precise changes so you really have to nail down what you're doing, why you're doing, how you're monitoring it, and what success looks like to rollout a change which pushes you to be an expert in every single code you push.
- big thing was the radius targeting project which i led the frontend of and managed consultants (ugh) and a junior engineer, just got us to parity with basically all the other major DSPs. more fun though was the bug i found in how we split and matched based on zip codes that was only affecting the UK, we were losing tons of revenue to major UK firms that advertised with us and nobody seemed to care (?) but i did so i looked for the reason and fixed it.
- also worked on alexa, which was a throwback to my twitch days just more infrastructure based and networking, thinking about systems in a really big way which i __love__.
- coolest thing i did was deprecate and replace the signaling protocal in the system that orchestrates all calling across alexa devices. basically one layer orchestrates and manages a fleet of servers that calls actually get assigned to and when a message comes in the orchestration layer has to see if it has the record for the server with that call or what other server in it's layer does and then routes the message either server-to-server or server-to-websocket. had a pub/sub model which wasn't great because it's "fire and forget" and well, that's not how calling works, so basically implemented a full request-response lifecycle despite websockets not being http.
  
software engineer @ twitch
- worked on video distribution. this included delivery on the edge, internal protected replication, network traffic control management, basically everything that happens to video between ingest in the origin and playback in the browser.
- did lots of things like IPv6 compatibility, modifying the HLS format in our media playlist service, helped out a bit with [Luke Curley's Warp](https://datatracker.ietf.org/doc/draft-lcurley-moq-transport/), took a step out of infra to design in Figma the frontend of a new operations tool that allowed my team and the datacenter ops team to change the network links so say move our PoP in MAD to look upstream of IAD instead of SEA when we used to have to run a very precise tool in our cli that very often failed, mentored a junior engineer despite only being a year out of school myself, basically we were constantly in "keep the lights on" mode because it was a small team with huge scope which was __very__ fun.
- my favourite thing: in my first month out of university i built a version drift system that tracked thousands of servers across our global network called Argus.
- i was an intern beforehand in my last year of university working on a viewbot detection system

<!--
**marissap/marissap** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Project Name
 
Simple, lightweight workout and meal tracker. Good for keeping yourself accountable when you tell the doctor that you workout "a few times a week" and "I eat pretty healthy, I think".
 
**[Live demo](https://github.com/NotASpaceLizard/vorkout)** | Status: _Active_
 

## Why I built it
 
All the apps in the app stores were paid, had a lot of ads, spied on me, or all of the above. I really didn't nead much, I just wanted to be able to write down what workout I did and what I ate. I'm not counting calories, I'm not trying to be a body builder, I just want to be able to look back and go "yes, I did in fact workout four times this week" and "Oh man I ate more Halloween candy than I wanted to" without all the bloat.
 
## Features
 
- Lightweight by design
- 100% functional offline
- No ads, no subscriptions, no $$$ of any kind
- Designed to be colorblind friendly from the get go, no hunting for accessibility options

## How it was built
 
- **Tools:** Claude Code (Opus 5, max reasoning)
- **Stack:** HTML front end, JavaScript drives the functionality. Uses browser APIs such as localStorage to save data on the device.
- **Process:** Several iterations of requirements gathering and then I let it loose. This was an intentional experiment in me being fairly hands off, not nitpicking at design choices. An orchestrator agent leveraged an orchestration playbook developed throughout my other experiments to spin up an agentic team composed of a scrum master, developer, tester, and adversarial QA. There were some visual adjustments needed after the first pass (e.g. weird sticking and buttons overflowing the screen) but generally speaking this was done extremely quickly and efficiently.
- **What I learned:** For this experiment, I tried a lot of requirements gathering up front and that worked out remarkably well. I've tried "agiling" with agentic development in the past and it now feels like that just wastes a lot of tokens.

## Run it locally
 
1. [Open the web app on your mobile device](https://notaspacelizard.github.io/vorkout/index.html)
2. Save to your home screen.

## Known limitations

There are a lot of "dailys" that I considered putting in here that I haven't yet. I thought about adding in my sleep score from my CPAP, a little checkbox if I did my Duolingo, etc. Lots of things that already track me daily elsewhere, that I could put here too, just for the sake of having it all in one place. That felt like too much though, especially given that, again, that's already being tracked elsewhere. If I were to add anything to this at this point, I would add one box for "How did I show up for myself today?"

## Contact
 
Dave Sheldon | [LinkedIn](https://www.linkedin.com/in/DavidMSheldon/)

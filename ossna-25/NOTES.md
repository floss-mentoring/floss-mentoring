# NOTES.md
Here are the notes from our unconference session. Thank you everybody for contributing!

# "START HERE" Guide for New Contributors
- For coders, the starting path is a lot more obvious. For people who haven’t coded before, what does the pathway look like?

## How can contributors get started?
- Find a project that you like, start reading the docs! Fix a typo, grammar, etc. as a starting point

## What can maintainers do to make it easier for first time contributors?
- CONTRIBUTING.md
  - dev environment setup
  - Keep in mind "[beginners mind](https://en.wikipedia.org/wiki/Shoshin)". Also relevant "[Average Familiarity](https://xkcd.com/2501/)"
  - Writing commit messages, set expectations for maintainer response times
- Use "Good first issue" tags
  - How do you identify what a GFI is?
  - No common standard
  - Sometimes GFI are things that are obvious, or have good relevant docs to use as a starting point
  - CNCF Has "Take a penny, leave a penny" policy - after first contribution, mentee makes a GFI of their own, to be solved by a future mentee
  - Watch for stale GFIs, can be good indicator for things that are not actually GFIs
    - perhaps this can be automated
- Intentionally create typos, grammar mistakes in docs to create easy entrypoints for a fix
- Find the right people to represent your project. 
- Run IRL hackathons/sprints at meetups and conferences. In person connections make a big difference!
  - Helps maintainers feel less "scary" and more approachable.
- Find creative ways to teach and do outreach (like TikTok, Instagram Reels, and YouTube)
  - Juanita Gomez has done this with Scientific Python



## Resources
- CNCF: 
  - https://clotributor.dev/
  - https://mentoring.cncf.io
  - https://landscape.cncf.io/
- [Google Summer of Code Contributors Guide](https://google.github.io/gsocguides/student/)
- [Google Summer of Code Mentors Guide](https://google.github.io/gsocguides/mentor/)
- [Open Source Friday](https://opensourcefriday.com/)
- [First Timers Only](https://www.firsttimersonly.com/)
- [Code Triage](https://www.codetriage.com/)
- [Up For Grabs](https://up-for-grabs.net/#/)
- [Good First Issue](https://goodfirstissue.dev/)
- [24 Pull Requests](https://24pullrequests.com/)


# Finding Collaborators and Partners

- People do not know that OSPOS (be they academic or industry) exist, what they do, or how to get started working with them
- What opportunities does an academic institution have to give back to an OSPO they work with?
- Every single OSPO is different, especially comparing academic vs industry
- Different models that have worked:	
  - Term-long university courses on open source contribution, or capstones that focus on open source - instructors partnering with a project, maintainer, etc.
  - Project partnering with a co-op program at a university that offers it
  - One-off events that encourage students on campus, offer education
  - Student clubs that support individual open source contribution
  - Leveraging existing programs - e.g. universities participating in GSoC
  - Student development teams
  - Funneling students toward external mentorship programs (GSoC, Outreachy, MLH Fellowships, CodeDay Labs, etc.)
- How do students find out about opportunities available to them?
  - Word of mouth! Mentors can spread word of mouth to other potential mentors, contributors can do the same – alumni networks
  - Advertising in public libraries, K12 teachers
  - Have self-serve slide decks and flyers that people can access, informational calls (in multiple languages if possible) to help spread the word for you! (via GSoC/Steph Taylor)
  - Use existing conferences, distribution methods to plant seeds - look in the region you’re looking to build engagement and get involved there
  - Reaching non-native English speakers: localization is so important - even flyers, etc - put effort into translation
    - Localization can also be an on-ramp for first time contributions! Encourage people to translate key items into their own language
  - Recommend one-on-one when you see someone in your workplace or similar
- What about reaching non-students? How do we reach them and invite them in?

## Resources
- [CURIOSS](https://curioss.org/)
  - community of academic OSPOs - can be a place to start if you’re looking for a campus OSPO to collaborate with
- [TeachingOpenSource.org](http://TeachingOpenSource.org)
  - Maintains a low-traffic mailing list; good place to email for ideas of projects to put students in, or to find an instructor to partner with


# Non-code Contributions

Non-code contributions are just as important as code contributions! What can people do to help elevate and enable contributors working on things like:
- Governance
- Design/UX
- Writing/Documentation
- Localization
- Finance
- Market strategy
- Law/Code Licensing (Talk to Karla!!!!)
- Cybersecurity/code auditing
- Data Science
- Computing Research

## How can we support students looking to make non-code contributions?
- Connect with an instructor at a college/university around non-technical classes  (teaching schools and liberal arts colleges might be easier starting points)
  - offer to collaborate on an assignment, review student work, visit a class
- Librarians! 
    - Outreach to them around how they can point people towards open source (code and non-code), or to OSPOs when there’s one locally
- Prep repos for different kinds of contributions that you’re looking for (ex: Linux Foundation ‘sandbox project’)
- How can we fast track people into mentorship? You don’t have to have technical background to be a good mentor - so much of it is cultural guidance and advising, resource-finding
- First conversation between mentor/mentee can be about expectations, what are we experts on 
- Analogies can help with communication across disciplines 
  - (e.g. strategic choice of a license can help determine whether your project is the “best house on the block” or the “fixer upper” down the road, via Karla Padilla)

## Attribution can be a challenge
- NumFOCUS working on structured attribution for non-code contributions - Mapping Open Source Science ([MOSS](https://www.opensource.science/))
- Attribution in patch notes, mailing list
  - Consider including smaller changes than would usually be written in patch notes if they were made by a first time contributor
- Use GitHub actions/CI to automatically foreground recent or new contributors
- Non-code contributors are often treated as less important than technical contributors; how do we include them so that they don’t feel like outsiders? 
  - Advocate aggressively for these people to be included in maintainer lists

To maintainers: communicate the impact of your project in a broad sense that anyone can appreciate
  - who’s using it?
  - What for?
  - How many users?

To all contributors and maintainers: don’t downplay your contributions! They’re all important!

## Resources
UX – check out Superglue (org that supports open source UX)


# (Over)use of AI tools

## How can AI harm learning?
- Students work noticably lower quality
- Students thinking they know more about something than they actually do
  - Easy for students to miss the point without realizing, or not be exposed to concepts they didn't ask about
- In context of learning, impairs ability to internalize complex concepts, synthesize complex thoughts
  - makes it harder to "learn how to learn"

## How can AI help learning?
 - AI as a tool to help with writers block, or creating boilerplate/first draft
 - Can level the playing field for students who struggle with traditional education:
   - Neurodiverse and/or autistic students
   - Non-native English speakers
- AI can be helpful when used as a tool to learn, instead of to complete a task quickly

## Identifying harmful use of AI in students 
- Look for discrepancy between work output and what they are able to talk about verbally
  - Identifying this scales poorly
- Program admins: encourage Zoom conversations with shortlist of candidates/potential mentees, helps assess actual knowledge & experience of applicants
Code exercises can work (asking people to submit PRs on them)
- Get to know potential contributors/candidates through unpaid contribution before working with them in a paid or focused mentoring capacity
- Consider adding a final presentation where contributors need to be able to talk through their code in front of other people.
- The math world saw this same problem in 2014 with [PhotoMath](https://photomath.com/); an app that solves math problems (and shows work) from just a picture. One policy that worked in that scenario:
  - Random 50% of students selected for review of an exam with their instructor.
  - The instructor would ask why they made specific choices, or provide reasoning for mistakes
  - Students could gain points back if they showed they learned from a mistake, or lose points if they couldn't explain why they made a specific decision (even if that decision was correct) 
  - Students could also opt in to this review process, and lots of students did

## How do we educate students on appropriate levels of AI help?
- The challenge maybe isn’t discouraging or banning AI - we know it’s part of development workflow right now
- “Using AI is fine, not understanding your work is not”
  - Students can use AI as much as they like, but if they can't explain their code they are disqualified
- “You as the developer are responsible for your code”
- Students should be reminded of the people after them who will need to maintain their code.
- Option: Allow + encourage students to use AI as much as possible, so they can discover it's weaknesses hands-on. 
- AI makes people who are good at their job better, and makes people who are bad at their job worse.
- AI has strengths and weaknesses - embrace student use of AI when it’s a strength, educate and inform students on AI when it’s a weakness  


## How does AI impact our work as educators and program leaders?
- Time limited assignments create direct incentive for students to use AI. Think about how to align assignemtns with our goals
- Can we use AI to help identify our own blind spots when writing code?
- What challenges might we face using AI to write documentation?
- Teaching foundational skills/computational thinking/theory may involve different use of AI than teaching resourcefulness or simulated real-world tasks
- AI is a generational shift in what our careers look like - in n years we might all be writing pseudocode, the same way we shifted to high level languages over assembly, and assembly over machine code.



# Topics that were not chosen, and who to talk to after the event:

- Open Mentorship Handbook
- Engaging non-traditional students
  - Lola Egherman, CodeDay
- Mentoring mentors
- LFX (or other tools) pain points
- Mentorship to grow oss communities
- Funding
- Identifying first-time contributors projects

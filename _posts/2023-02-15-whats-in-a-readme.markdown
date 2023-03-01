---
layout: post
title:  "Ooh, ooh, README, README!"
date:   2023-02-15 12:01:39 -0600
categories: blog post
---

I started actually writing code in August of 2022. I had played around with HTML and Python before then, but not in any serious manner.

As I started to really dive into this process, it felt like my monitor had become a view port through which some oddly colored coordinated text document became an object. Not corporeal but still real. Describable. Useable. With each practice project I became a incrementally better at coordinating these documents. I could describe and coordinate a whole range of things. I could manage and use the files and directories needed to create an application... except one. The README. My understanding of this little structure was minimal at best.

It wasn't as if I didn't try to improve my use and understanding of READMEs. I searched through templates (props to [Best-README-Template](https://github.com/othneildrew/Best-README-Template)) and I attempted to recreate the success others had; I tried on everyone elses ideas because I had none of my own. It was frustrating and that frustration was compounded by the growth the rest of my fledgling skills were showing. However, I think I made my first breakthrough in this little endeavor. It may sound stupid (or obvious) and I don't want to oversell it as some great epiphany. Just my idea. One I like. One that I am proud of.

I started writing it for my desired audience.

I can already feel you moving your mouse to close out this tab in your browser (you probably have too many open anyway). I promise. I have a more then just *that*. So lets take a quick step backward.

> "Repos are products you build for developers. Products solve user problems."[^1]
> - Richard Kim

I love this contextualization by Richard Kim but I can't live up to it (yet). I'm not yet building for developers or customers, I'm building projects for my future employer. I am building them to showcase my potential, my growth, and my current ability. It also happens that building these projects improves all of those factors but that is beside the point. So, if my repos are for a potential employer, what is the problem of theirs I can solve? I would argue it's this: "Will I hire this person?"

Conveniently enough, helping a future employer solve this problem is quite beneficial to me. It also gives me a bit more direction for my READMEs. I am no longer trying to write for some amorphous audience. My future employer exists out there and they have a problem that I can help solve.

Now that I have identified who I see my audience as and what I see their problem to be, I will spend a bit of time to define the assumptions that I am making about them:
- First, I am actually using the singular *employer* to refer to a handful of people engaged in the hiring process.
- Second, they are broken down into three categories: Human Resources/Recruitment, Managers, and Software Engineers.
- Third I will have to engage with each group, one after the other, in that given order AND while they as a group have the problem "Will I hire this person" they each, individually, carry a slightly different part of that problem.
- Finally, I am not going to be mentioning any Applicant Tracking System (ATS). I am only concerned with human eyeballs reading my work and this would mean that, more then likely, my application has already made it past any ATS.

Let's take all that and look at each group, in order, and see what we can find:

- Human Resources:
    - Is not a subject matter expert (SME) in coding but is probably still knowledgeable.
    - Wants to take a large group of applicants and reduce this to a limited group for the managers.
    - They are trying to quickly review and (mostly) remove applicants who show red flags and maybe put a few on top who were particularly interesting.
- Managers:
    - Could be a SME
    - Wants to take that reduced list and really evaluate their work and produce some final selections for the engineering team to look at.
    - They are trying to really evaluate each applicant and find the ones they want. They will spend more time looking at technical ability.
- Software Engineers:
    - Is the SME
    - Wants to take those final selections and make a THE selection.
    - They will really look into your ability to ensure you wont be a hindrance to the team.

Once we draw out our groups we can see two patterns: **(1) Each group has more time to review any given applicant than the previous**, & **(2) each group has more self-interest in the resultant hire then the previous**, and **(3) their technical ability to read and understand code increases as we move through the hiring process.**

*As a quick aside. I know the above is general and simplistic but I also don't it's unfair or un-realistic. I promise, I am not going to try and make grand conclusions out of simple axioms.*

Now back to READMEs (and the conclusion).

We can now take these patterns and make some suggestions for writing a README.

If the initial HR group is time limited and not as able to evaluate code. Then:
- Get the 'bottom line up front' because no-one will see your awesome endpoint section if this person is a no.
- Start with a title, description, and graphics showing what your repo will do.
- Make this easily digestible by removing any use of esoteric language.
- If your app is deployed, prominently displayed a link in this section.
  - Remove anything that is a barrier between clicking on the repo link and seeing the app in motion.
- If you app is not deployed, make sure you have quality graphics that clearly show what the apps functionality.

If managers and engineers have more time to review your application and more of an aptitude for reading code. Then:
- After your application link (and/or graphics), immediatly pivot to **relivent and consice** documentation.
  - Think: Installation and requirements, Endpoints or Wireframes, Tech Stack, Features Roadmap
- Consider taking any documentation that you think is too long and move it somewhere else to keep things moving.
  - For example:
    - Use an `<details>` to hide the info on individual API Endpoints.
    - Only include a few endpoints and have a link to a separate document/webpage for the rest. Postman and Swagger are excellent for this.
    - Keep it DRY. You can link to other sections (as opposed to restating something in them) by using `<a href="#header_name">more about this here</a>`.

If managers and engineers have more of a stake in the hire (they will be the ones working with you day-to-day). Then:
- After the documentation. Get to you. Fast.
- Get a picture, name, links to other social media, and an invitation to contact you.
- Consider putting a quick explanation of what you wanted to get out of the project and if you think you were successful. Be honest AND proud.
- Also give and avenue for input and recognition.
  - Show people that you want to learn and that you will properly credit the work of others.

I hope you found these helpful or at least interesting. If you have any feedback, I would love to hear it.

Anyway thanks for reading!

---

[^1]: Kim, Richard. [*"How to Get Thousands of Stars on Your Github Project"*](https://blog.cwrichardkim.com/how-to-get-hundreds-of-stars-on-your-github-project-345b065e20a2). Dec 31, 2014.

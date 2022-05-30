# Notes for PMs

## Intro

### Get to know the client
- Research their business domain, but not just superficial, ask dumb questions that are obvious.
- Find out who is the key technical person
- Find out who is the decision maker in the team
- Push to get a "big picture" diagram of their system (at least core business) ahead of time
- What tools does the client use for progress reporting and overall communication
- Make sure our company can integrate to clients network

### Get to know the project
Learn the following before the project kick off meeting
- What is the project domain. If the project domain is very specific, then we need a domain consultant (example, if it's a medical application, do we need a medicine consultant)
- If a consultant is needed and introduced, plan some time for onboarding him to the team
- Is our team creating a project from scratch, joining an existing project, putting out a fire or just building an extension on an existing environment
- What is the preferred project management model? Quick short deployments, or longer structural development, maybe a hybrid model
- Is the team going to be managed solely by internal staff or client has an ambassador joining our ranks?
- What is the level of transparency or reporting the client prefers on the development progress?

## Project kick off

### Finding out the scope

- Try to get clear overall requirements as soon as possible. Do not make any estimates out of thin air or on a gut fealing. In our world things change fast, very fast.
- If time allows, ask questions just to get confirmation on some topic. This is the best way to meet eye to eye with the client and establish initial competence
- Never ask technical questions without at least a senior developer present, even if you get a straight answer, you will probably forget it or miss the context
- Leave the technology and software infrastructure to the technical personnel to settle
- Do not commit to any client estimates, you know your team velocity and resources, for the client our team is a black box
- There is a big difference between client wishes and client capabilities. If the client has an IT team, ask what they do and manage expectations for colaboration with them

#### Good starting point questions to ask the client:

- Have you done this kind of project so far and if yes, can you share some previous experience on the topic.
- Do you have any milestones' setup you want to hit, or timeline?
- Do we need to conform to some constraints?
- What kind of progress transparency do we want to commit to?
- What are the risks, penalties
- If joining an existing project, can we have a knowledge transfer from resident developer/product owner
- What is the scale of the project (number of users, total or per day)
- Are we expecting big scale ups and how often?
- How often do expect to have major releases, or big changes
- Do we need to tightly integrate with some existing services on the client side or third party vendors?
- Is it expected to have an OnCall staff from our side?
- If so, what is the expected response time?
- What system is expected to be used for ticketing/bug reporting?
- Take notes, always

### Often used phrases on meetings

| What they say                                      | What it implies                                                  | What it really means                                 |
|----------------------------------------------------|------------------------------------------------------------------|------------------------------------------------------|
| Let’s `circle back` on this                        | Lets revisit the topic later                                     | I don’t want to talk about it now.                   |
| After some consideration we decided to `pivot`     | After some consideration we are now changing direction           | We made a mistake                                    |
| Let’s not `boil the ocean` on this one             | Let’s not do something that requires more resources than we have | Lets not make it harder than it needs to be          |
| What was the `key learning?`                       | What was the lesson learned                                      | Do not make this mistake again                       |
| Feel free to `ping me`                             | Feel free to contact me using only the official channels we have | Please do not contact me                             |
| The idea won’t `scale`                             | The idea does not allow future growth                            | I do not like this idea                              |
| Let’s take this `offline`                          | Let’s not discuss this in the meeting                            | I don’t want to talk about this now                  |
| Just to be on the `same page`                      | Lets agree on this topic first                                   | I need more time to think                            |
| Just to `better` understand you                    | I need to wrap my head around it                                 | You don’t make any sense                             |
| We have to `analyze` the issue first               | We need more time to do some research on the matter              | We do not know how to solve the issue yet            |
| Please `prioritize` the issue first                | This was not on the agenda                                       | I don’t have time to look into this now              |
| We have to `extend` all the possibilities first    | Checking for alternative solutions                               | Its our fault, but we want to buy more time          |
| We have to `revisit the implementation`            | There was an unpredicted use case in the system                  | We have a bug                                        |
| I have to `double check` my email                  | I need to recall the topic we are discussing                     | I did not read your email                            |
| I will send you the info right `after the meeting` | I will provide you with the info you are referring to            | I should have sent you the info before the meeting   |
| It's on my `priority list`                         | I will do it ASAP                                                | I forgot to look into this                           |

## Managing a software development team

### Rules of a thumb

- You have 10 productive engineering weeks per engineer per quarter
- Budget 20% of time for generic sustaining engineering work across
  the board
- As you approach deadlines, it is your job to say no (especially when asked to add seemingly small features)
- If asked to give off-the-cuff estimate, use the doubling (take your guess and double it), 
but push for planning time to estimate longer tasks
- Be selective about what you bring to the team to estimate

### Managing software architects

#### Architects who know everything
- They possess great technical knowledge
- They don't share the knowledge unless explicitly asked. Even then, they provide vague answers and never to the point. This gives them the power of a favor, "if I told you how to do something, then you owe me"
- They want to be called when no one else can solve the problem, but never take responsibility if they can't solve the problem themselves, they will go to a blaming rampage that the product or conditions are bad
- They make all the decisions alone, never transparently, because someone might have a better idea, and then they lose the throne
- Every suggestion is always met with an attack: What more can you do with your solution, that you cant with mine?
- Usually stick to old technologies and methodologies and expect the world to conform to them, instead of evolving together with the team
- They expect for team members to be longing for their inclination and good will to help them.
- They micromanage and don't give the people the option to choose: "Do as I say", syndrome
- Never recognize a persons' contribution in any area, but themselves

#### Architects who want their team to know everything
- They possess great organizational skills, and rely on the whole team technical knowledge base
- They are the glue and the shield of the team, nothing more
- They are aware that they don't have to know everything, nor to be idolized by the team members
- They don't have solution for every problem that might come along. They just believe the team can solve anything if they put their heads together provided sufficient time
- They lay the groundwork, document as much as possible and educate the team, then let team pick up from there and get up to speed, so they finalize the product
- They stick to a schedule and respect each persons' time, they don't call and disturb staff whenever they feel like it
- They don't ask extensive reports from team members of what they did today, they look for the results and try to see the big picture
- They motivate team members to take pride in their choice in technology and present the others why this new thing is better
- They genuinely care about their team members, because they know the team health is more important than overshooting the deadline for one day

## Fending off the client
A manager’s job involves making it easy for her employees to get things done by
creating fertile environments in which work can happen. She focuses her team
so that they can do what they do best. She cultivates camaraderie and friendship
on the team, and helps people learn new skills. In all these things, she is an enabler,
a coach, and a champion.

### Saying NO politely
- `Yes, and`, then ask the client are they aware of the time constrictions or effect of this change?
- Create policies and communicate them with the client in advance. `Example: Due to not having a support
team standing by on weekend, we will not be doing deployments on Fridays`

<div hidden>
```
@startuml firstDiagram

Alice -> Bob: Hello
Bob -> Alice: Hi!
		
@enduml
```
</div>

![](firstDiagram.svg)

- `Our focus is currently on` followed by the elephant in the room (the biggest most important feature)
  NOTE: when you give an implied promise that “not right now” means that you’ll seriously do something
  “later”, you need to be sure that later can actually happen.
- `Work as a team`, sometimes you will need to act together to say no. Use your architects!
- `Don’t prevaricate`, When you know that you need to say no, it’s better to say it quickly than to delay
  and drag out the process.

### Company has your back

Ask yourself the following questions:
- Do I know what is expected of me at work?
- Do I have the materials and equipment I need to do my work right?
- Do I have the opportunity to do what I do best every day?
> If any of these yields a NO, then ask for help, we got your back

## Do's and Dont's

> Quote from `The manager's path`

## Good Manager, Bad Manager: Us Versus Them, Team Player

*Diana has just joined a midsize startup to run the long-neglected mobile team She was
told coming in that the team was a mess, so her first step is to quickly hire in a bunch of
new people who worked for her at BigCo. They aren’t quite a culture fit, and the team
quickly turns into a clique of developers who see themselves as better than the rest of the
organization. While the technology has improved, they seem to be clashing a lot with
the product team, and ultimately the apps aren’t evolving very quickly. After a year,
Diana gets fed up with the company and quits. The rest of her new team soon follows,
leaving the company right back where it started.*

- `Fragile to the loss of the leader` In-group teams tend to be very fragile to
the loss of their leader. When you hire a manager who builds a clique, that
clique is likely to dissolve and leave the company if the manager leaves the
company. This problem makes it that much harder to address the problems
that the manager is causing by creating a clique in the first place.
- `Resistant to outside ideas.` In-groups tend to be resistant to ideas that do
not come from those within the group. This means that they miss opportunities
to learn and grow. The lack of growth for members of the team often
causes the best members of the team to leave not just the group, but the
company. Because they believe they’re in the best group but they still find
themselves bored, they don’t appreciate the growth they could find just by
switching to a new team.
- `Empire building` Leaders who favor an us-versus-them style tend to be
empire builders, seeking out opportunities to grow their teams and their
mandates without concern for what is best for the overall organization.
This often results in competition with other leaders for headcount and
control of projects.
- `Inflexibility` These groups tend to struggle against change that comes from
outside the group. Reorganizations, cancelled projects, and shifting focus
all can cause breaks in the core parts of their identity. Whether it’s a move
from functional groups to cross-functional teams, delaying the iPad application,
or prioritizing a new product, the change can devastate the fragile
bonds of the team to the company.

***As a manager, be careful about focusing on your teams to the exclusion of
the wider group. Even when you have been hired to fix a team, remember that
the company has gotten this far because of some fundamental strengths. Before
you try to change everything to fit your vision, take the time to understand the
company’s strengths and culture, and think about how you’re going to create a
team that works well with this culture, not against it. The trick is not to focus on
what’s broken, but to identify existing strengths and cultivate them.***

*Neil has also joined a startup where things are chaotic. While he can see that he
needs to change the team, he moves cautiously to fire people and takes the time to make
sure that new hires are always vetted by someone who’s been with the company for a while. He spends a lot of time working closely with his peers in product, and proposes a
path forward that emphasizes cross-functional collaboration. He focuses on setting clear
goals and communicating them to his team. Things start out slow, but over time the
entire organization feels stronger and both the technology and the product have
improved dramatically.*

- `Resilient to loss of individuals` While the clique is fragile, especially to the
loss of the leader, the purpose-driven team tends to be very resilient to the
loss of individuals and leadership. Because they’re loyal to the mission of
the larger organization, they can see a path forward even through loss.
- `Driven to find better ways to achieve their purpose` Purpose-driven teams
are more open to new ideas and value changes that can help them serve
their purpose better. They care less about the source of an idea than its
merit in achieving their goals. The members of these teams are interested
in learning from others outside their function, and they actively seek out
chances to collaborate more broadly to create the best results.
- `First-team focused` Leaders who are strong team players understand that
the people who report to them are not their first team. Instead, their first
team is their peers across the company. This first-team focus helps them
make decisions that consider the needs of the company as a whole before
focusing on the needs of their team.
- `Open to changes that serve their purpose` The collaborative leader understands
that changes will happen to serve the wider purpose. Teams will
change structure and people will need to move to where the business
needs are. With that knowledge, these leaders create teams that are more
flexible and understanding of frequent change in service of the larger
vision.

***Getting clarity about the purpose of your team and your company can take
time. In startups especially, there is often some confusion about the current
goals and even sometimes the underlying mission. In the case where the goals
are fuzzy and the mission is unclear, do your best to understand the company
culture and think about how you can set your teams up to work well within that
culture. By collaborating across teams and across business functions, your teams
will come to understand the bigger picture and appreciate their mission as part
of that picture.***

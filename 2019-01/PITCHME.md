@title[Introduction]

### A guide on why, how, and where to help OpenStack

![](https://github.com/evrardjp/presentations/blob/master/2019-01/assets/i-want-you-to-contribute-to-upstream.jpg?raw=true)

Note:
- The untold tale of OpenStack heroes: You can be one too.

---

@title[This presentation]

#### This slidedeck is interactive and has links!

![](assets/qrcode-to-slides.png?raw=true)


Note:

- What I meant with the title is that it's an interactive session, and only you can shape it the way you want.
  I hope you will leave this presentation with at least one take away: Contribute upstream.
- This is the usual "Who are we" slide
- We also explain the presentation is a story, starting for a contributor from 0 to hero.
- If you are wondering where heroes are needed, this is further in the presentation
- Anyone can be a hero

---
@title[What's in it for me?]

@snap[north-west span-45]
@box[bg-green text-white demo-box-step-padding rounded](Survival#We depend on upstream, without it our product dies, and your job too)
@snapend

@snap[north-east span-45]
@box[bg-orange text-white demo-box-step-padding rounded](Responsibility#As one of the primary consumers of OpenStack we have a responsibility to invest back)
@snapend

@snap[south-west span-45]
@box[bg-blue text-white demo-box-step-padding rounded](Self-improvement#Become subject matter experts in order to fix bugs quicker and support customers better)
@snapend

@snap[south-east span-45]
@box[bg-pink text-white demo-box-step-padding rounded](Belongingness#Building relationships helps. Achieve more by earning trust and building credibility)
@snapend

@snap[midpoint]
#### Why would I want to contribute upstream?
@snapend

Note:

- For Reponsibility: What I mean by that is that if we selling an (OpenStack) product, we have a responsability to invest in its raw material, the upstream projects.
- For Self-improvement: If you are active in an upstream project, you will learn its code, its people, helping you grow your skills, know more about the project code (That will help you in product design, in solving customer problems, and many others).
- For Belongingness: Everything is awesome when you're part of a team. Land emergency patches with the trust you earned, and help others in the same case to strengthen the bond. We are all in that **** together).

---
@title[How to get started]

@snap[west span-20]
How to get started?
@snapend

@snap[east list-content-concise span-75]
@ol[](false)
- [Contributor portal @fa[external-link]](https://www.openstack.org/community/)
  [Code contributor guidelines @fa[external-link]](https://docs.openstack.org/contributors/)
- [Be in touch with First contact SIG @fa[external-link]](https://wiki.openstack.org/wiki/First_Contact_SIG)
- Fix low-hanging fruit items
- Read and update the project documentation
- Be active in the project: Meetings, office hours
- Be proactive: Code reviews
@olend
<br><br>
@snapend

Note:

For meetings, add the ICS from eavesdrop.o.o of your favorite project into your SUSE calendar. It shows you're busy.
---
@title[Code Reviews]

@snap[north-west]
Tips on code reviewing
@snapend

@snap[west list-content-verbose span-100]
<br>
@ul[](false)
- https://docs.openstack.org/project-team-guide/open-development.html#reviews-guidelines
- https://docs.openstack.org/project-team-guide/review-the-openstack-way.html
- https://www.openstack.org/videos/summits/sydney-2017/communication-through-code-how-to-get-work-done-upstream
@ulend
@snapend

Note:

- ask questions on changes you don't understand, this helps improve your understanding of the code and builds rapport with the team
- leave a +1 vote if you understand the code and think it's a good change
- leave a -1 vote if you disagree with the change or think the code needs significant work before it should be merged
- do not leave a +1 if you don't understand the change
- do not leave a -1 for nitpicks like typos

---
@title[Where to help]

@snap[north-west]
Contributors wanted...
@snapend

@snap[west list-content-verbose span-100]
<br>
@ul[](false)
- [Current and future community goals @fa[external-link]](https://governance.openstack.org/tc/goals/)
- [Help wanted list @fa[external-link]](https://governance.openstack.org/tc/reference/help-most-needed.html)
@ulend
@snapend

Note:

- We are now in community goals pre-work time. If no pre-work is done for those ideas of community goals, they won't be accepted as goals, and nothing will happen with them. Current goals mentionned for community goals: Deletion of project resources (chained purges), moving legacy CLIs to python-openstackclient, improve oslo healthcheck mw for real API healthchecks. Current goals are python3 and pre-upgrade checks.
- For the help wanted currently listed: We currently have Docs, Infra, Glance, Designate, Goal champions.
  4 are upstream projects and we are using them all for our product.

+++

@title[Context: What are we using?]

@snap[west]
@ul[](false)
- rpm-packaging
- OpenStack-Helm
- keystone
- nova
- cinder
- glance
- neutron
- oslo
- swift
- manila
@ulend
@snapend

@snap[east]
@ul[](false)
- heat
- horizon
- monasca
- ceilometer
- ironic
- barbican
- magnum
- sahara
- designate
- octavia
@ulend
@snapend

Note:

For the context, here is a list of projects part of our product

+++
@title[Context: What we are using behind the scenes]

@ul[](false)
- infra
- i18n/docs
- requirements
- stable
- qa
- release
- governance-(tc|uc)
- sigs (self-healing, diversity, first contact, api, security, upgrade, etc)
@ulend

Note:

Still for the context, other projects we are using behind the scenes.

---
@title[What about SUSE in the community?]

#### What about SUSE in the community?

@ul[](false)
- OpenStack tests against openSUSE Leap using our packaging
- When it breaks, they ping dirk on irc
- Occassionally dirk is not available
- We need to support the community and be fixing issues before they arise
- Please help projects (give support in the openSUSE image builds in infra/dib, in rpm-packaging).
@ulend

+++

#### State of openSUSE in the OpenStack community: Statistics

![](https://github.com/evrardjp/presentations/blob/master/2019-01/assets/contributions1.png?raw=true)

+++

#### State of openSUSE in the OpenStack community: Statistics

![](https://github.com/evrardjp/presentations/blob/master/2019-01/assets/contributions2.png?raw=true)

---
@title[Call to action]

#### Call to action

@ul[](false)
- Find something that interests you and start participating
- If you don't know what to contribute to, consider helping with OpenSUSE in OpenStack
@ulend

---
@title[What's next?]

#### What's next?

Discussion:

@ul[](false)
- Do you know what projects or initiatives you would like to help with?
- Do you feel prepared to make a contribution upstream?
- What needs to change at SUSE to enable you to contribute upstream?

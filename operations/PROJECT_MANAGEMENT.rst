Project Management
==================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Purpose
-------

Set conventions for communication between project stakeholders to maximize our velocity towards objectives.

Scope
-----

This document summarizes project management tooling and practices at Countable to assist with onboarding.

Process
~~~~~~~

-  Every project has a "Purpose" which must be documented and visible.
-  Every project has at least one `Objective and Key Result <OKRS.rst>`__ every month.
-  We use Scrum like `this <SCRUM.rst>`__.
-  Every day, try to get some `feedback <../peopleops/FEEDBACK_LOOPS.rst>`__ on your work.
-  Every day, coordinate with team mates on slack and prioritize.
-  Work together to minimize the amount of time anyone is blocked or waiting for someone's output as their input. The list of items in which people depend on each other's work is called the `critical path <CRITICAL_PATH.rst>`__.

Things We Want To Improve
-------------------------

-  Increase transparency of our work to clients, team mates, managers.
-  Dashboard for client.
-  Performance metrics, data for retrospectives.
-  Automate timesheets, and invoices using Trello card data.
-  Automate moving trello cards based on commits.
-  Simple to explain to new people. Mostly automated. Avoid slowing down developers who are less oriented to PM process.
-  Link bitbuckets commits.
-  Easy for clients to submit a ticket. Bug or Feature, URL, screenshot.
-  Provide our customers with a constant feedback loop, updating them upon a new feature release or any significant changes on their current project.

SCRUM
~~~~~

Countable uses`Scrum <https://en.wikipedia.org/wiki/Scrum_(software_development)>`__
to manage work delivery and collaboratively learn about problem domains.

Check out the guide book from the inventor of Scrum`here <https://www.scrumguides.org/scrum-guide.html>`__.

Principles
----------

1. Ship work to real users and get feedback *every sprint*. Don't allow "work in progress" to not be released. Instead, plan your work so it can be released every 2 weeks or *ideally, every day*.
2. Make sure everyone's clear regarding their *Objectives* and team members' Objectives and Key Results.
3. *Communicate* with your project team daily about meeting KRs.

User Stories
------------

User Stories serve as the central planning document for any given project. The purpose of User Stories is to ensure all stakeholders can understand what we're trying to accomplish, no matter their level of technical expertise. Check out the `User Stories <USER_STORIES.rst>`__ page for more detail and how to compose User Stories.

Process
-------

Project Objective and Key Results
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Every team should have one or more`Objectives <OKRS.rst>`__. This is a written goal discussed with the team to ensure clarity, and is used by the `Product Owner <#product-owner>`__ to order the `Backlog <#backlog>`__. An objective may be to meet a particular User Story.

Sprint
^^^^^^

A sprint is a period (1 week to 1 month) punctuated by a Sprint meeting.

The `Scrum Master <#scrum-master>`__ must review tickets for clarity (triage them) from Requests to Backlog. The `Product Owner <#product-owner>`__ must review tickets for priority (order the Backlog).

Before Sprint Review meetings, team members should:
"""""""""""""""""""""""""""""""""""""""""""""""""""

1. Measure what % done our Key Results are. Check any metrics necessary so we don't bog down the meeting looking in mixpanel for example.
2. Pick cards for the next sprint that will most impact KRs.

During the sprint meeting
"""""""""""""""""""""""""

Each team member updates the team on their

1. Key Result scores
2. what they shipped to cause those changes
3. and how they will meet the Key Results by the deadline (usually end of month)

Cards of Shame
""""""""""""""

1. Review any cards left in the sprint column. Why are they there? How can we avoid that?

Stand-up Meetings
"""""""""""""""""

Countable doesn't hold synchronous stand-up meetings. Instead, every day, please share something on your team's public slack channel regarding the work you did. It's best to show a screenshot of your work for feedback.

Reference
---------

Roles
^^^^^

These are the duties we must assigned when doing Scrum.

Product Owner
"""""""""""""

-  Develops User Stories by talking to real users and ensures those users' needs are being met by the team.
-  Clarifies how to achieve our `Key Results <../OKRS.rst>`__, while taking input from team.
-  Triage the Trello Requests column into an Ordered Backlog of work.
-  Makes sure items in the backlog are clear to developers. The product owner is typically our client.

Scrum Master
""""""""""""

-  Chair the sprint meeting, ensuring we follow the process.
-  Trains the team on Scrum and makes sure we're following the rules of scrum effectively (shipping each week, continuously learning, making tickets clear)
-  Nudge team to identify problems in workflow and make them visible to work together.

Developers (and other technicians)
""""""""""""""""""""""""""""""""""

-  Ensures they have a challenging yet doable amount of work each sprint.
-  Ensure they understand items in their sprint, an complain otherwise.
-  Takes responsibility for completing KRs, and shipping work to real users, clients, and team members (depending on output)

Backlog
^^^^^^^

The Backlog is a list of all the actions we current believe will accomplish the goal of our project. This should be ordered by impact to effort ratio. That is, items which make the biggest difference in the least time should be done first.

We do not have daily stand-up meetings since our team works in different timezones. Instead, we have a slack channel where people should communicate about what they're working on, coordinate code reviews, and figure out logistics to ship their work every week, and generate ideas for the sprint plan meeting.

For a visual aid of how our work is processed, see this `Business Process Diagram <https://drive.google.com/open?id=1VrniT1lRqVu9sJr0ZMK1aQLnFwEuFIQD>`__.

Note: Instead of just talking about what did you do this week, try to use a screen share feature to walk along all of your "done" trello tickets, explaining one by one. This helps the team to better understand all of your work.

Tools - GIT
~~~~~~~~~~~

For developers - We follow the `git flow <https://datasift.github.io/gitflow/IntroducingGitFlow.html>`__ branching conventions loosely. All projects should have a master (production) branch which releases are made from, and a develop (stable)
branch for developers as a foundation to build features on. Feature branches are created from develop and merged back in via pull request when ready. Here are some `examples <../developers/GIT.rst>`__ of how we'd use GIT in different cases.

Tools - Trello
~~~~~~~~~~~~~~

We use Trello for project management, as it allows unlimited access to boards by partners and clients, encouraging collaboration and transparency. 

We use Trello because:
  * it allows collaboration with clients on assignments.
  * is simple enough for people to join ad-hoc without training.

`See video version <https://www.youtube.com/watch?v=6X9x4SCLhKs>`__.

Trello Basics
-------------

We use Trello for project management, as it's simple to set up access to the appropriate boards by partners and clients. A Trello board consists
of a set of `Cards <#trello-cards>`__ (tasks) arranged in `Columns <#trello-board-columns>`__.

Trello Cards
------------

A card should contain a clear description of work to be done by one person required to support a given `User Story <USER_STORIES.rst>`__.
This may correspond to a single User Acceptance Test. 

A card should typically be between 1 hour and 1 day of work. If it's longer, split it into 2 cards in that column.

Trello Board Columns
--------------------

Ideas
^^^^^

Stuff that's not clear enough to be in backlog yet.

Requests
^^^^^^^^

This is the starting point for anyone to add cards, and where cards the client has requested live until the Scrum Master can review and ensure they're actionable and clear.

If they're actionable, move them to Backlog. If they're not, write a comment to the client asking for more information in order to make it actionable, and leave it in the deferred column.

If any additional requirements steps such as a mockup are required, mention that in the card. Attach any additional examples and/or
specifications to the card.

Feedback
^^^^^^^^

On this column, we may store cards that somehow need client or manager review before proceeding further. In practical terms, we use this
section whenever we need some client data or feedback to progress with our current task.

Backlog
^^^^^^^

Cards that are clear and actionable, and have an estimated impact and effort associated with them. This is the traditional Scrum backlog list, ordered by priority (highest on top), by the Product Owner.

There is only one backlog column, because we need to use the current
sprint's lessons to plan future sprints. So, we cannot plan future
sprints in advance, we can only set card priority.

Sprint
^^^^^^

Cards actively being worked on in the current week.

Done
^^^^

Cards that are ready to be tested by the client (and when that's not
possible, by the consultant). A test can take the form of a client
approval, code review, or automated test written.

Moving cards between columns
----------------------------

A diagram shows how cards can move from conception to completion
`here <https://drive.google.com/open?id=1VrniT1lRqVu9sJr0ZMK1aQLnFwEuFIQD>`__.
As the diagram illustrates, each column corresponds to a specific within the adapted `SCRUM <SCRUM.rst>`__ framework.

Progress Awareness
------------------

**It's essential to keep our clients informed about our current progress** on particular tasks, so our professional relationship is strengthened and trust is built. 

For this objective, we suggest that you:

1) Take screenshots of finished progress (when applicable) and post on your trello ticket.
2) Use checklists for keeping track of what's being done.
3) Use "Screencastify" chrome extension for recording short screencasts and attaching into your trello ticket

The "critical" label
--------------------

If you find something that's severly broken in any of our websites, please create a Trello card with a red label ``critical``, and tell the developer who you've assigned it to. Do this sparingly: only when it's something we're likely to quickly lose customers over such as a service being down completely or a button not working. 

For less serious bugs, don't use this label, just make a regular card.

Boards
------

We typically have one board per codebase with a client, and one per internal product orproject. 

The board background color indicates the following:

-  Green - nonprofit client (private)
-  Orange - corporate client (private)
-  Red - internal operations (private)
-  Purple - open source project, or other public board (public)
-  Blue - internal product (private)

Getting everything into Trello
------------------------------

Clients will often email you rather than use Trello. This can be fixed by forwarding their email to the Trello board.

Go to their Trello board, and click settings -> email-to-board settings, and add that email address as a contact in your email. You can then forward emails directly to your trello board.

However, it does make a bit of a mess since email signature images and other junk show up in the tickets, so it's nice to clean them up when you look at them in Trello.

Tools - Screencastify
~~~~~~~~~~~~~~~~~~~~~

Especially when dealing with a remote team, customers tend to be more anxious about project progress and features implementation. To overcome this situation and to keep our customers aware of our current development status we can use this chrome extension to **record short screencasts with a brief summary of the latest changes**. After this,
generate a shareable link and send to them through e-mail, in a **weekly basis**.

-  Don't spend more than 10 minutes to do it, since its just a short and simple video.
-  Be professional in your tone and language.
-  This methodology is particularly useful for front-end changes, since they're visible.
-  In case you're dealing with back-end related work, you can still do the screencast, but your approach should be different: You'll have to explain and summarize what you're working on, and show some important parts of the code that you developed.

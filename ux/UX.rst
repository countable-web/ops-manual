UX Practices
============

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Purpose
~~~~~~~

Scope
~~~~~

Marketing
---------

Defines how we communicate with potential clients. It screens for
clients with similar values, with whom we'd like to collaborate on
exciting projects. To anchor this, revisit our `Value Prop for Clients <./philosophy/PHILOSOPHY>`__

Branding Projects
-----------------

Branding Process
~~~~~~~~~~~~~~~~

1. Brand development questionnaire
2. Discovery meeting (review other work, discuss answers to
   questionnaire). The person delivering the work must attend this
   meeting, in-person or web conference.
3. Develop creative brief (internal). See the example Creative Brief below.
4. Propose sketches and color paletttes. Cherry pick key points from the
   creative brief to present.

Branding Guidelines
~~~~~~~~~~~~~~~~~~~

How can we get more buy-in, commitment, alignment and clarity earlier.

-  Validate the direction by reviewing other work together.
-  Inspiration board.

Demonstrating reasearch, expertise and intention in designs.

-  Provide about 3, no more than 5. "I've narrowed dozens of sketches
   down to the best 3. This is why I recommend these directions to your
   audience..."
-  Explain how the proposed designs capture their desired brand
   requirements, and appeal to the audience.

User Experience Design Process
------------------------------

Countable takes a Human Centered Design approach in its user experience
process.

Process
~~~~~~~

There are three major phases: User Research, Prototyping and Feedback.
These will overlap and repeat to some extent.

User Research
~~~~~~~~~~~~~

It's valuable to front-load much of the user research in a software
project so other work can be informed by information about real users,
not our assumptions.

Persona Development
^^^^^^^^^^^^^^^^^^^

First, identify the people who will interact with the work product
(Personas). Ideally, find a real person who embodies each persona and
stay in contact with them to collect feedback throughout the product
development.

Make a list of personas, and use those persona names consistently from
now on.

Interviews
^^^^^^^^^^

Interview representatives of each Persona to answer the following:

-  What problem are you solving for the persona? Why does that problem
   matter to them? What words do they use to describe the problem?
-  What is your Persona currently doing about this problem (prior to
   your solution)?
-  Take advantage of your "Fresh eyes" at this time, to identify needs
   does the user have that they're not consciously aware of. It's fine
   if you turn out to be wrong about these, just write them down to
   validate later.

Other Research
^^^^^^^^^^^^^^

Interviews should be the primary source of information about your users,
but you may *supplement* this with surveys, anecodotes from your product
owner (the client, most often) and other data sets to inform stories.

Stories
^^^^^^^

-  Write user stories. This is a functional spec of your software. Be
   clear about what is should do for users.
-  Validate your stories with the product owner and users, and adjust.

Prototyping
~~~~~~~~~~~

It's beneficial to involve your personas and other stakeholders in the
below steps where practical (co-design workshop). This speeds up the
"validation" step, below.

-  For any project with a user interface, create wireframes that support
   the important user stories. Validate these against conversations with
   the target market.

Depending on the project, you may also want to develop:

-  For projects with nontrivial sequences of interactions over time,
   consider a customer journey map, or process diagram (BPD).
-  For projects with many user interfaces or many views, develop an
   Information Architecture diagram to show how different user
   interfaces are linked.
-  For projects with nontrivial off-screen actions, consider
   storyboarding the actions a user must take related to their use of
   the product.
-  Other project-specific resources as needed to get everyone on the
   same page about any aspect of the user experience which is important
   to more than one the stakeholders.

Validation
^^^^^^^^^^

-  Validate your wireframes and other planning materials with the
   product owner and users, adjust, and repeat until everyone on your
   team has a clear shared vision.
-  You're now ready to hand off the wireframes to technical team members
   to build a `functional prototype <../developers/PROTOTYPING.rst>`__.

Feedback
~~~~~~~~

While user experience design can be front-loaded in a project somewhat,
it's critical to continue throughout the project to ensure incremental
improvements are made and a great end result is achieved.

-  Conduct `usability tests <./USABILITY.rst>`__ of the
   functional prototype as you iterate on it, each sprint.
-  Perform follow-up interviews on users after they've tried the
   product.
-  Build a feedback mechanism (chat widget, form, etc) into the User
   Interface for a quick easy way to get contextual feedback from users.
-  Ensure developers understand the critical user flows in order to
   align with acceptance criteria for automated tests.


Usability Testing
-----------------

The purpose of this document is to ensure thorough and standardized
usability tests can be followed by any member of the team (or any other
user), allowing Countable to better test its products. The top priority
is currently to create a guide which is easy to follow. We'll know we've
succeeded when anyone can conduct these tests and give feedback which
can be used by the product dev(s) to advance the prototype.

Disclaimer
~~~~~~~~~~

You may be testing a fully developed product, an early stage prototype,
or something in between. We'd also like you to know that we are testing
the prototype, and not you - any issues you have using it are
shortcomings of the prototype that we need to know about.

How To Test a Product’s Usability
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The following are questions to ask while Usability Testing:

-  Is the product under evaluation efficient enough (Are the users able
   to carry out their task while expending reasonable resources such as
   time, cognitive or physical demand)?
-  Is it effective enough (Can the user complete the tasks they are
   supposed to perform with the tool? Is their performance complete and
   accurate?)?
-  Is it sufficiently satisfactory for the users (What is the users’
   attitude towards the system? Do they experience discomfort?)?

Some Steps to Follow
~~~~~~~~~~~~~~~~~~~~

Follow and document these steps:

1. Blink Test:
   Look at the site (home page, or whichever page you are evaluating)
   for five seconds, then look away.

-  What do you remember most about the site?
-  What stood out to you?
-  What do you think this site is for? If it's featuring a product, what
   does that product do?

2. Reflect:

-  What was your first impression of the site?
-  What do you like about how it looks?
-  Can you see any issues with the site/home page?
-  Can you see any other areas of improvement?

3. Expectancy:

-  What do you expect to be able to do on the site?
-  What parts do you expect to be able to click (ie: buttons, links)? Do
   they work?

4. Context and Tasks:

-  Who is the main user of this site? If you aren't sure, consult with
   us. We will let you know who you should "pretend" to be as you use
   our site
-  What is a scenario you would be using this product in? If you aren't
   sure, consult with us.
-  What are the primary tasks you should be able to complete with this
   site/product?
-  Are you able to complete them? Please document any issues you have
   completing these primary tasks.

5. Bugs: Your experience may be interrupted by something on the site
   being clearly broken of dysfunctional. These are bugs and are
   priority fixes! Please notify us right away if you run into these,
   byt doing the following (if you've been granted access to Trello):

-  Briefly describe the current behaviour and how it differs from the
   desired behaviour.
-  Include the exact URL where the issue can be observed.
-  List any further steps (specific clicks, etc) to observe the issue.
-  For aesthetic problems, take a screenshot and circle the problem in
   red.
-  For text problems, quote the problematic text.
-  Add to the appropriate Trello list/board and use a red "bug" label to
   mark it.
-  Assign the bug to someone who can either fix or triage it.
-  (Refer to 
   `Bug Reporting in our Developers page <./developers/DEVELOPERS.rst>`__)

6. Finishing up and debrief:

-  Overall, how would you rate your experience using the product/site?
-  How do you feel now?
-  Were there any moments where you were delighted, or had fun? When?
-  Were there any moments you felt confused? When?
-  Were there any moments you felt frustrated? When?
-  How was your experience usability testing for us? Please let us know
   if we can improve the testing process itself.

Thank you!


Creative Brief
--------------

Visual design is a communication tool for meeting the right kinds of
clients and subcontractors. We aim to establish visual standards to best connect us with people who will go
the distance to make a big postive impact on the world.

Offering
~~~~~~~~

-  We rapidly prototype custom software using web technology to
   understand domain problems more deeply and demonstrate value early
   on.
-  We do our best to embody transparency and maximize value creation for
   everyone as a side-effect of creating value for stakeholders.

Audience
~~~~~~~~

Clients
^^^^^^^

-  We are segmenting (filtering for) groups inside organizations who
   identify as startups but often exist in other organization
   structures. People who want to try something new and affect change
   using the web.
-  Typically, small enterprises (50 to 500 employees) often with some
   technical acumen (3 to 5 out of 10), no in-house developer team, or
   an incomplete one that lacks some web tech areas.
-  Another example is a funded startup that needs a world class web
   technology component such as a dashboard, customer interface or API.
   *Persona: Tifa has raised seed funding and needs a prototype for
   market research, further momentum with funders.*
-  Lastly, we'd like to continue to pursue government contracts
   particuarly when there's a clear agenda for change using the web.
   There is a movement in BC government to embrace agile methods and
   improve software that we're excited to support and be part of.
-  The typical decider is the owner or tech lead of the organization.
   *Persona: Barrett runs a private firm that developed a disruptive
   hardware component but doesn't have web UI, apps or cloud
   integration.*
-  Their web app will touch many people. We'd rather build things that
   are publicly used by millions, because these tend to have higher
   impact (all other things equal), and create more visibility for us.
-  We want clients who are interested in "growing the pie" rather than
   "dividing the pie". A warning sign of a bad client might be someone
   who thinks our hourly rate is too high for example. An ideal client
   should be happy that we charge a profitable rate because: We want
   partners who want to make money together with us, not make money at
   our expense; We want partners who choose us because of outsized
   value, not because we're cheapest; We want clients who push us to
   create more value for them; If we can't provide enough value to
   charge profitable rates, we shouldn't be hired by that client because
   both sides should find a more ideal partnership.
-  We should be able to create *at least* $100,000 in value for the
   client, and should be able to charge a third of that. Our typical
   minimum contract size should be $30,000, so that they make at least
   $70,000 in profits.

Staff
^^^^^

We want to attract ambitious, talented people who are good
communicators. *Persona: Aeris wants a job that is challenging with lots
of autonomy to hone her skills alongside ambitious and skilled peers.*

Segmentation
^^^^^^^^^^^^

Given our experience range is so broad, it's hard to segment by
industry. Instead, we segment by ambition. Our value prop "Look at this
wide range of great projects we've done: We can do anything on the web.
If you have a moonshot idea, want to go beyond the status quo in our
business where no one else has before, you don't want someone who
specializes in your industry's status quo as they'll deliver just that.
We've demonstrated the ability to create next-level web technology that
disrupts your competitors and breaks your industry's mold. We create
leaders on the web."

Competition
~~~~~~~~~~~

Several other categories compete with us, including hiring in-house,
freelancers, placement firms and agencies. Of these, we most directly
compete with agencies who do end-to-end web based software development
work. Here are some we admire, and why.

-  `Dockyard <https://dockyard.com/>`__ - open source
   focused, profess to "make an effort to both teach and learn".
-  `Caktus Group <https://www.caktusgroup.com>`__ -
   They've focused on a specific technology (Django) to be best at.
   `Open source <https://www.caktusgroup.com/about/>`__
-  `TWG <https://twg.io>`__ - Great services page, `very clear <https://twg.io/services/>`__. Agile, fellow Canadian.

Top google results for "Web Application Firm" and "Web Software Firm".
This means they have pretty effective SEO/copy.

-  `CoResolutions <https://coresolutions.ca/>`__
-  `SCNSoft <https://www.scnsoft.com/>`__
-  `Falcon Software <http://www.falcon-software.com/>`__

Top company identified on clutch.io, Canada (that we actually like)

-  `Lift Interactive <https://liftinteractive.com/>`__ -
   Highest billable rates in this list.

Similar scope/approach:

-  `Five Agency <http://five.agency/how-we-work/>`__
   - Good process explanation.
-  `Breue <https://breue.com/>`__ - Super clear CTA "Get
   your free product roadmap today."
-  `AndYet <https://andyet.com/>`__ - Likes bleeding edge
   front end web tech, novel approach.

We admire these teams for beating us on contract bids :)

-  `Freshworks <https://freshworks.io/>`__ - Beat us at the
   Mines Digital Services contract.
-  `RealFolk <https://www.realfolk.io/>`__ - Beat us at
   the Concierge (devex) project.
-  `OliveWood <https://www.olivewood.io/>`__ - Beat us
   at the Queue Management System enhancements contract.
-  `LlamaZoo <https://www.llamazoo.com/>`__ - Beat us
   at a VR demo project.

How we want to Differentiate
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Specialize in audacity. Work with clients to develop a stretch goal
   that's exciting to collaborate on.
-  Expertise in prototyping quickly to test ideas and market response.
-  Pre-packaged best practices for avoiding technical debt, helping with
   succession, scalability, operations.
-  Focus on our versatility, and successes in many different industries.

Impression
^^^^^^^^^^

This is a web dev firm, that has great technical depth", as soon as the
page loads. This technical depth should be apparently simply from the
form of the site.

Theme
^^^^^

Space + dreams. Space is a little overdone, lean towards the latter
going forward. Dreams characterize our values of working for big impact
long term, enabling creators on the web, and making a better remote work
environment for our team.

Tone
^^^^

-  Audacity. Big Dreams.
-  Clarity and simplicity.
-  Adaptability.

Design Principles
~~~~~~~~~~~~~~~~~

1. All design elements should be intentional and have an explainable
   purpose. Less elements emphasizes the best ones. Don't try to be
   clever or subtle. This symbolizes how we value clarity and
   simplicity.
2. The design should be functional, and facilitate the intended usage.
3. The design need not always follow design trends but should at least
   indicate we are aware of them. Cherry pick some trends that work.
4. Advanced technical elements (3d, parralax, etc ) are good because
   they showcase out technical work but should not be used at the
   expense of being simple.
5. We value clarity over cleverness and subtlety.

We like the ideas from `Brutalist Web Design <https://brutalist-web.design/>`__

Evaluation of Creative Ideas
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To evaluate creative ideas, first spend 6 minutes generating your own
ideas for the problem and write them down. Compared to using evaluation
criteria, the best ideas are identified 77% of the time instead of 51%
of the time this way.

Inspiration
~~~~~~~~~~~

 - `Threejs examples <https://threejs.org/>`__
 - `Shader toy <https://www.shadertoy.com/>`__
 -
`Lars Berg <https://www.larsberg.net/#/thumpThump>`__
 -
`Teams on Dribbble <https://dribbble.com/teams?sort=trending>`__

`Vector icons and graphics <https://dribbble.com/shots/4391020-Bot-Ai-Hero>`__

`Monochrome <https://dribbble.com/shots/4364906-Aao-Milo-Intro-Screens>`__

`Animated illustrations <https://belichberg.com/en/>`__


Creative Resources
------------------

Fonts
~~~~~

-  `Google Fonts <https://fonts.google.com/>`__
-  `TheStocks <http://thestocks.im/>`__

Stock Photos
~~~~~~~~~~~~

-  `Unsplash <https://unsplash.com/>`__
-  `Pexels <https://www.pexels.com/>`__
-  `TheStocks <http://thestocks.im/>`__
-  `Use as assets in prototypes <https://gallery.manypixels.co/>`__

Icons
~~~~~

-  `FlatIcon <https://www.flaticon.com/>`__
-  `The Noun Project <https://thenounproject.com/>`__
-  `TheStocks <http://thestocks.im/>`__

Screen Mockups
~~~~~~~~~~~~~~

-  `Smart Mockups <https://smartmockups.com/>`__
-  `Mockup World <https://www.mockupworld.co/>`__

CSS Selectors
~~~~~~~~~~~~~

-  `w3 Schools <https://www.w3schools.com/cssref/css_selectors.asp>`__

Animations
~~~~~~~~~~

-  `Acko <http://acko.net/>`__
-  `Fun Programming <https://funprogramming.org/>`__

Inspiration
-----------

Design Trends
~~~~~~~~~~~~~

-  `Watch this <https://www.youtube.com/watch?v=dcc1VyGvaYk&list=PLqiiZyfH1jqTgZuqaqJeK1ZFs9MUH-HPj&index=3&t=0s>`__
-  `Awwwards <https://www.awwwards.com/>`__

Our Favourite Templates
~~~~~~~~~~~~~~~~~~~~~~~

-  `Bashooka templates <https://bashooka.com/template/cool-website-templates-for-artists-photographers-designers/>`__
-  `Insymbiosis <http://www.insymbiosis.com/>`__
-  `Beawesome <http://beawesome.rt.md/>`__
-  `html5 up <https://html5up.net/>`__

Our Favourite Agencies
~~~~~~~~~~~~~~~~~~~~~~

-  `Outcrowd <https://outcrowd.io/>`__
-  `Netrix Digital <https://dribbble.com/netrixdigital>`__
-  `OmniCreativora <https://dribbble.com/omnicreativora>`__

Infographs
~~~~~~~~~~

-  `FFCTN Honeybees <https://ffctn.com/en/project/honeybees>`__

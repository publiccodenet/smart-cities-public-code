# Workshop Public Code @ Amsterdam

*This workshop took place at November 20 10:00-16:00 at the Amsterdam University of Applied Sciences in Amsterdam*

The Smart Cities? Public Code! project aims to explore and develop the concept of public code. Public code is an early stage concept for a type of code developed with the public interest in mind. This means we need to look differently at the software developed for public tasks as compared to software for private tasks. At a minimum, we should guarantee that it is inclusive, usable, adaptive, open and sustainable.

In three international workshops, the context, challenges, and opportunities for public code are discussed with various actors in the field. How should we understand public code, what should we expect from it, and how can we create it? What kind of technological and institutional arrangements are needed to shift towards the production of public code?

The first workshop took place in Bucharest in October 2018, during the conference Heroes of Tech, organized by Code for All, an international network of organizations supporting each other to empower citizens to meaningfully engage in the public sphere and have a positive impact on their communities.

The second workshop took place in Barcelona, in November 2018 during the Smart City World Expo. We gathered a small group of participants from public institutions, NGOs and companies working in the space to build on the findings of the first workshop and consider some further issues.

A third workshop was organized in Amsterdam in November 2018, at the Amsterdam University of Applied Sciences. Participants included researchers and representatives from various civil society organizations, local governments and software companies.

## Why is public code important?

The third workshop started with a reiteration of the various arguments necessitating the introduction of the public code concept. The main argument is that the status of software in urban governance is changing. Increasingly it is becoming a fundamental infrastructure in a city’s operations and the interactions between citizens and governments, as well as a major force in the management of common resources. Software then is not just a commodity that can be ordered from a catalog like a desk or even a word processing suite. Increasingly it plays a role in the execution, monitoring and enforcement of city policies. In this process it is not just an ‘executor’ of policy, but increasingly software is set to play a role as a deciding actor, for instance when algorithms play a role in deciding which districts need extra policing or social services, which citizens are eligible for extra support or which citizens’ activities should be further scrutinized. In other words, software is now moving into a place where policy is active.

That means that computer code has to comply with a series of principles related to democratic governance. It needs to be understandable for its constituents, transparent in its execution, and both politicians as well as citizens and civil society organizations should be able to hold it accountable. Furthermore, it should comply with a series of other public values. For instance, its workings should be inclusive and non-discriminatory in character. This means that software cannot be a black box, ordered from outside companies. Instead, cities need technological sovereignty that allows them to control city software, just like they are able to control policy that is legally formulated in laws. At the same time citizens need this software to be transparent, a nascent ‘platform society’ should honor a series of digital citizens’ rights.

The concept of public code provides for this need for sovereignty and digital citizen rights in two ways. First, it proposes a set of values and criteria that software can be evaluated against. Second, it proposes a mode of production and stewardship for public code that enables governments and third parties to develop codebases and share these between cities.

## Public code criteria

A series of criteria were discussed that should be operative in public code software and its documentation:

* Privacy: how is the privacy of data guaranteed?
* (Meta)data procedures and flows: what are the inputs and outputs of the software? What data byproducts are produced? Where does the software tap into other systems and databases?
* Margin of error: can this be made explicit in the code or documentation?
* Data legibility: to what extent should not only the code itself but also the data it collects and produces be part of the public code requirements?
* Limits: probably not all data-processing processes should be open. If the algorithm for fraud detection is made public, this would enable fraudulent actors to change their practices to circumvent the algorithm. In the case of predictive policing, this principle becomes more ambivalent. On the one hand, criminals would be well served by opening-up the underlying algorithmic processes. On the other, citizens could claim they have a right to understand why their behavior is scrutinized, and to what extent racist or other biases play a role in the algorithms.
* Key variables: should they be made easily identifiable for further development/appropriation by third parties?
* Documentation: what forms of documentation should be required?
* Should public software also include particular values, such as eco-friendliness?

## Public code production

Public code provides also a framework for the production and distribution of code. The central idea is that public software is also open source and can be shared between governments. This led to the following discussion points:

* Who can produce public code? In essence, public code is a set of rules. Everyone who follows these rules can play a part in the production of public software. This means that the writing of code can also be provided by commercial companies.
* However, one of these rules is that the codebase should be open source and freely accessible. That means that companies who produce public code do not own the IP; this implies a shift in the business models for software consulting companies. Their business model is no longer based on the licenses they sell to access their IP-protected software, but rather should be based on hourly rated consulting fee.
* In order to be successful, public software would need a form of software stewardship. Who will take care of repositories and maintenance of software? Could an independent organization play a role here? Or could this be left to service contracts with commercial providers?
* How is liability organized in the production of public software? Who can be held responsible when things go wrong or the software does not deliver what it is expected to do?
* Procurement: could we move to outcome based tenders or service level based tenders, rather than starting from a precise definition of requirements, in which the problem is described, rather than the solution? A similar trend is discernible in architecture, where clients do not just order a building but take on a multi-year service contract that promises to deliver a particular performance.

## Case: Cut the shortcut, a highway surveillance system

To make the conditions for and repercussions of public code more concrete, a particular case was discussed in more detail. It concerns a town that is located right next to a busy highway. When there are traffic jams on the highway, many motorists seek refuge by taking a short-cut through the town; they simply get off the high way on one end of town, drive through the city center on a regional road, and get back on the highway at the other side of the city. Obviously, this behavior has a negative effect on the quality of life in the town itself, increasing traffic and exhaust. At the same time, it may bring in extra business, e.g. for local gas stations.

In order to limit the negative consequences of these motorists' tactical behavior, the local government has set up a ‘destination traffic only’ policy, making it illegal to cross the city. To effect this policy, traffic surveillance cams are set-up at the beginning and the end of the town limits. Motorists that drive in from one side and exit on the other side within a certain time limit are fined. Discussions have taken place about possible exceptions: e.g. customers of the gas station, taxis and other transport network companies dropping off or picking up customers are exempted.

What would it mean to build a codebase for such a system from a public code perspective? Obviously, the decision to fence off through-traffic is a democratic one that is taken by the local city council. From a public code perspective the codebase that is to enforce this measure should comply with a number of requirements:

* It should be transparent. Citizens or civic organizations should be able to understand what rule is enforced, and be able to check whether the software delivers on this. What units of measurement are used, what margins of errors?
* Variables used in such a system should be easily identifiable and adjustable. E.g. exceptions for particular vehicles (e.g. taxis picking up clients, or parents dropping off children at school)
* It should be accountable. If I get fined, I need to be able to verify that this was a just decision and have access to the proof assembled by the system as well as a procedure to debate its correctness/legitimacy.
* Privacy should be guaranteed.
* The software itself should be well documented and made available for other cities interested in similar measures. This again requires a modular organization of the software with easily changeable and amendable variables.

At the same time, a number of other issues were raised that require further discussion:

* Where exactly does the process of public code creation begin? Is it in the writing of the codebase itself, ordered by the city government from either an internal office or an outside contractor? Or should it include a broader participatory design trajectory in which local stakeholders think along about possible issues and solutions in the process?
* To what extent should this software be interfacing with other systems, e.g. should it be able to communicate to GPS-navigation systems the times of the day and classes of vehicles that it is of concern to?
* Who exactly decides on the criteria? Is it the local government? Or could there be a self-learning system in place that optimizes criteria based on a problem statement? If so then how could its logic be explained and the current variables in place be communicated?
* How is the whole process organized? Who sets up a design brief, who produces the code, how is it checked against public code criteria, who maintains the code, how can it be distributed?
* Where does the process of public code licensing end? For instance, should the hardware company providing the cameras (and possible algorithms) for license plate recognition also be evaluated against public code principles?

## Discussion: limits of public code

Like in the first two workshops, again two perspectives were discussed: a value-based perspective and a production perspective. The latter is a set of procedures for the production of code that is shareable, and could be understood as a form of ‘open source-plus’: its codebase is open source, but there is a number of extra requirements with regard to both the code itself as well as its stewardship and distribution practices.

Such a public code-perspective partly requires a cultural shift in the production of code, including new forms of procurement. One of the points under discussion is to what extent public code is the domain of govtech, or whether it can be applied to broader constituencies. Could, for instance, the software for (commercial) energy distribution platforms be required to run according to public code principles? Or could housing associations or even transport network companies subscribe to public code principles?

An important question is to what extent public code requires some form of a meta framework, such as for instance the ‘common ground’ framework currently under discussion by the VNG (Association of Netherlands Municipalities), that allows for modular development of service applications building on a particular organization of datasets?

With regard to the values-based perspective, other questions were raised about its limitations. Is public code mostly concerned with procedural democratic values such as transparency and accountability? Or should it also include a particular set of values, such as social inclusion, anti-discrimination, environmental impact and emancipatory potential?

Finally, a discussion took place about where to start with the development of public code. Is it possible to start with the values perspective first and tie in a production perspective later, or do both need to be operative from the very start? Or should there possibly be a tiered system with A/B/C qualifications?

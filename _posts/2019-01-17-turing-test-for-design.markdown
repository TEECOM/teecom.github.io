---
layout: post
title:  "A Turing Test for Design"
date:   2019-01-17 17:00:13 -0600
author: "AexM Team"
categories: update
author: Tyler Kvochick
author-link: https://teecom.com/people/tyler-kvochick/
summary:
  "In his seminal paper, “Computing Machinery and Intelligence,” Alan Turing set
  out what he called The Imitation Game. This game was designed as a principled
  way to answer the question: “Can machines think?” When we talk about a “Turing
  Test for Design,” we are talking about an experimental setup in which to
  answer the neighboring question: “Can machines design?”"
reposted_from: https://aexm.ai/blog/turing-test-for-design
reposted_from_title: AexM blog
---
## Architecture ex Machina

Architecture ex Machina is a group of architecture, engineering, and construction (AEC) professionals dedicated to advancing the state of the art in applications of machine learning to the design of buildings and cities. Although computer aided design (CAD) and building information modeling (BIM) have transformed the design process for buildings, we still have not found a way to capture and interrogate the design process itself. We think that technologies built on machine learning will fundamentally change this process by allowing us to model generative functions and statistical relationships in addition to our current abilities to create drawings and digital models of the built environment.

Over the past thirty years, the incorporation of design software into the the office has increased the complexity of design projects that can be documented, collaborated on, and ultimately constructed. However, the work of professional designers and engineers has not necessarily become faster or easier. Rather, the complexity of contemporary building projects now necessitates advanced 3D geometry and building information modeling. These models are rich data stores that describe the confluence of many domains of expertise. Beyond architecture, engineering, and construction, every discipline that has unique spatial requirements records some of its knowledge into its purpose-built spaces. Medicine, education, manufacturing, and more all require bespoke configurations of building and technological components in order to more effectively improve the human condition. This information is encoded, to some degree, in the work of architects and engineers.

We view the development of machine learning-enabled tool sets not as another layer of software complexity, but as a way to help navigate the complex patterns of design and construction that are hidden within the work of today’s designers. Experienced designers have certain intuitions when working within particular industry verticals, but typically this experience is difficult and slow to transfer to other designers. We see one of the value propositions of artificially intelligent design tools as the ability to model, examine, and augment these intuitions with patterns that are currently hidden behind gigabytes of 2D drawings, 3D geometry, schedules, and specifications.

Typical software platforms do not enable modeling of spaces and building elements at a level beyond the designer’s ability to create representations of these spatial configurations. Drawings and models encode the _record_ but not the _reasoning_. Platforms like Dynamo and Grasshopper have made some progress in this direction by allowing designers to quickly prototype logic that can be frozen as model geometry. But interactive parametric design tools do not solve the more general problem of understanding design trade-offs in their temporal, financial, and spatial contexts. The ability to model these contingent, probabilistic relationships is more useful for solving problems in building design than a rules-based approach as it should be able to capture tendencies that are difficult to state in discrete logic. This is similar to the success that deep learning has had in the area of image classification where the explicit programming of all the rules that are necessary to identify a cat is much more difficult than learning from a dataset of cat versus non-cat images. Establishing and refining this “virtuous cycle” between past decisions, their effects, and future decisions is one of the key tenets of a machine learning-reinforced design technology future. Encoding these contextual relationships as an executable statistical model is one of the core abilities of machine learning and the domain of expertise that is typically called “artificial intelligence.”

The ability to capture and examine these encoded, yet fuzzy, relationships is at the core of what we want to build for the future of architecture, engineering, and construction.

However, all the tangible benefits of deep integrations between machine learning and design that are becoming are balanced by challenges. Every transformative technology brings with it the potential for transformative catastrophe. A University of Oxford study on computerisable employment positions rated “Architectural and Civil Drafters” as having a 52% chance of being automated.[^oxford-study] All industries will have to deal with the human effects of automation and the AEC industry is no different. The other side of this discussion for which we must take responsibility is automation’s effects on policy and worker protection. Today’s practitioners are responsible for ensuring that the pursuit of better tools results in a world that is more equitable, sustainable, and valuable for everyone.

It would be foolish to suggest that we know exactly how to navigate this future. What we are sure of is that we need participation from across the industry and from industries that are adjacent such as robotics, data science, software development and more. The most important first steps for us are to gather interested and engaged participants, start discussions, and establish ways to measure improvements in the state of the art over time.

## Seeing Visions

> Let us consider an augmented architect at work…He is designing a building. He has already dreamed up several basic layouts and structural forms, and is trying them out on the screen. The surveying data for the layout he is working on now have already been entered, and he has just coaxed the clerk to show him a perspective view of the steep hillside building site with the roadway above, symbolic representations of the various trees that are to remain on the lot, and the service tie points for the different utilities. The view occupies the left two-thirds of the screen. With a "pointer," he indicates two points of interest, moves his left hand rapidly over the keyboard, and the distance and elevation between the points indicated appear on the right-hand third of the screen.
>
> -Douglas Engelbart, “Augmenting Human Intellect”[^engelbart]

This future envisioned by Doug Engelbart in 1962 has now come to pass. Without the awkward language, this would now sound like a rote description of a person using Revit or Rhino. In retrospect, we can now say that this vision was focused on recreating the work that designers do, but supported by computational tools. It did not offer a new way of _thinking_ about design, only a new way of _doing_ design.

What we are going to facilitate is a future in two parts where each necessarily reinforces the other. The first is to build design tools that have easy hooks into numerical and optimization libraries that form the core of machine learning. We think the best way to drive any field forward is to pursue excellent tooling and make it available to be hacked on by domain experts. In the same way that high-level programming languages made computer programming available to anyone with the interest and time to read a book or watch a video, we need to make development and deployment of machine learning accessible to designers and engineers in a way that can make incremental improvements in their daily lives. The second part of the equation is to leverage advances in computer vision and sensor systems to acquire accurate statistical models of occupancy that can be incorporated as a simulation layer in the design process. Building design has traditionally been an area of expertise that has operated by intuition rather than evidence and reason. We see the potential for machine learning to change this.

In addition to this vision, we want to sponsor and encourage intellectual investment into enterprise-scale development of and academic research into machine learning design (MLD) to accrue and accelerate the state-of-the-art knowledge that is generated by these pursuits.

### Design

We want designers and engineers to be empowered by tools that augment their creativity and free them to work on high-risk, high-reward tasks. Anyone who has ever worked in a design office has experienced the frustration of having to produce multiple options for some stage of a project and each iteration feeling like they are starting from scratch. We imagine one future of design tools as a collaborative process between the designer and their tools where they can set boundaries and variables, generate possible solutions, and then adapt and customize the output. We also envision that it will be trivial for designers to both train models based on past work, and to discover patterns hidden in their own decisions.

### Data

Every design firm maintains an archive of past projects. In a machine learning design future, these archives will be made into data sets that encode that firm’s tendencies. We believe that an integral part of the design process will become the statistical study of all past solutions in order to understand how to meet a specific project’s requirements. The development of open data sets has been integral to the success of machine learning in the areas of computer vision and natural language processing. It is of supreme importance to develop these in an open and collaborative way from across the AEC industry.

We aim to extract patterns of behavior from the built environment to understand how to make better design decisions. Currently we rely on the accumulated expertise of individuals, teams, and entire companies to get to the state of the art for some design. We think that this process arises from the inherent messiness of the world. People and events will always be difficult to predict, but advancements in computer vision will empower owners and facilities managers to better measure things like foot traffic in airport terminals or in university buildings. Enhanced occupancy analytics can then be reincorporated into design tools to illuminate more objective models of behavior and usage to which designers can respond.

## Baby Steps

There is no way that we can arrive at this future without input from around our industry and from those that are adjacent. In order to pursue these viewpoints and to decide if they are making the industry better, we will need to measure our performance.

### Ideas

One thing to make clear: we do not have the answers to these questions. What we are interested in is finding the answers with the help of all interested parties. To achieve this future, we need ideas from the parts of the industry that we are blind to and that have not been adequately addressed in the past.

### Policy

Some of the most important ideas that we are missing are those having to do with financial and employment policy. While mechanization and automation have done objective good, they have also done irreparable harm to people and to the environment. Machine learning, like all technologies, is just a tool. Its impacts are produced by, and the responsibility of, the people who make use of it. No discussion of the impact of machine learning on any industry will be complete without taking these factors into account.

### Discussion/Collaboration

Establishing an open forum for the discussion of the impacts of machine learning is paramount for success. The changes that machine learning enables for designers are not just a displacement of the design work into software, but will fundamentally change how we think about design and engineering. This could be thought of as a parallel to the advent of finite element analysis in structural design or Thomas Bayes’ mathematical formulation of reasoning under uncertainty. It is not just a new software, but a different way of solving design problems. In order to fully educate ourselves and the industry at large, we need to foster education programs and public discussion in order to transform responsibly.

### Competition/Innovation

Competitions have historically been used to sponsor innovation[^prize-innovation] and we see no reason that the application of machine learning to design tools should be any different. To be able to track our collective progress in this area, we are going to establish a competition that brings together AEC industry practitioners and experts from relevant fields such as computer science, neuroscience, AI ethics, etc. to measure the performance of the state of the art over time.

## Imitating the Imitation Game

In his seminal paper, “Computing Machinery and Intelligence,” Alan Turing set out what he called The Imitation Game. This game was designed as a principled way to answer the question: “Can machines think?” When we talk about a “Turing Test for Design,” we are talking about an experimental setup in which to answer the neighboring question: “Can machines design?”

Notably, in the paper, Turing side-steps the question: “Is [can machines think] a worthy one to investigate?”[^imitation-game] by assuming the answer to be self-evidently affirmative. Since we are working in an age where a reasonable suspicion of technology exists, we will not take this answer to be given. To us, our question is absolutely necessary to investigate. Our goal is to reduce the number of person-hours spent on the repetitive and menial tasks involved in thinking through the design of something that is both as complex and self-similar as buildings. What we hope to gain in exchange is a greater proportion of time spent on creative, rewarding, high-value work. By pursuing answers to whether or not machines can design, we want to be able to select a designing-machine from a field of candidates that accomplish these goals.

In Turing’s game, he establishes a question-answer pattern as the transaction for playing the game. This setup works for human language, but would not work so well for the spatial and symbolic language used in the design of buildings. Sitting at a screen and typing questions like “Is there a door in this wall?” repeatedly doesn’t exactly seem like the best way to judge the design of a building. We envision the setup to be a hybrid of computational prizes &mdash; such as the Loebner Prize or the Imagenet Large Scale Visual Recognition Challenge &mdash; and an architectural design competition. We see this as teams producing models that produce designs, and those designs being judged by a panel of experts in both computation and design.

With the inexorable advances in the state of the art, it seems clear that we will spend more and more time examining the products of machines in every context. If everything goes according to plan, a group of skilled practitioners should find it increasingly difficult to distinguish between the work of machines and human creatives. While architecture may not have the interactive component of Turing’s game, it’s easy to imagine a kind of design critique for machine-generated work.

While the details of this metric may be hazy from our contemporary moment, we hope that our partners will contribute their expertise in designing this test. Measuring improvement is impossible without an objective function and we hope to establish this test as a kind of societal metric that incorporates all of these concerns.

## The Beginning

In contrast to the descriptive nature of Engelbart’s vision of an “augmented architect” we do not purport to know what the future holds. We only know that it will be different. We are proposing that we begin with a way to use human intellect to measure these changes over time. And, more importantly, to learn from the past to direct the future.

We hope that everyone is as excited to work on these problems as we are. The transformations to our industry that machine learning offers are at least as significant as the first generation of software technology. We want the process of this transformation to be open to debate and direction from everyone that it will affect.

[^oxford-study]:[Frey, Carl B. and Osborne, Michael A. _The Future of Employment: How Susceptible are Jobs to Computerisation?_ 2013.](https://www.oxfordmartin.ox.ac.uk/downloads/academic/The_Future_of_Employment.pdf)
[^engelbart]:[Engelbart, Douglas C. _Augmenting Human Intellect: A Conceptual Framework._ 1962.](http://dougengelbart.org/content/view/138/000/)
[^prize-innovation]:[Brunt, Liam. Lerner, Josh. Nicholas, Tom. _Inducement Prizes and Innovation._ 2011.](http://www.hbs.edu/faculty/Publication%20Files/11-118_089bff4b-868a-41f1-8f3d-351d1a58d2c2.pdf)
[^imitation-game]:[Turing, Alan M. _Computing Machinery and Intelligence._ 1950.](https://www.csee.umbc.edu/courses/471/papers/turing.pdf)

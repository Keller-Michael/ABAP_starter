# :rocket: ABAP starter

## :pushpin: Motivation of this repository

This repository is intended to provide all interested people with an initial overview of the requirements to become an ABAP developer and the options for getting started. The trigger for the creation of this repository were increased questions from trainees and students, job starters and job changers. Instead of giving a lot of single answers to everyone, this hub was created as a central starting point.

The information given here is neither complete nor does it claim to be correct. It's much more a collection of information, experiences, considerations and expectations that is under constant revision. Anyone can and should help to improve the given information here. Take advantage of GitHub to collaborate.

It should also be noted that this is general information. Since everyone is different, everyone has to find his own way based on this information. Of course, you don't have to do this alone. All ABAP developers should offer help to the best of their ability.

## :cloud: First online impressions of the programming language

For a first online impression, some general information on the ABAP programming language can be found in this [Wiki article](https://en.wikipedia.org/wiki/ABAP). There is an [ABAP Exercism track](https://exercism.org/tracks/abap) where you can solve various programming tasks with ABAP online. Finally, very simple examples can be tried out with [Lars Hvam's](https://github.com/larshp) ABAP Online [Transpiler](https://transpiler.abaplint.org/). 

## :house: First offline impressions of the programming language

In order to experience the programming language, an accompanied course is recommended. There are often corresponding offers for students and trainees.

If you know an ABAP developer, you should get a personal introduction to the programming language, the development tools and the execution environment.

Reading a beginner's book is also recommended. You should make sure that the literature is as new as possible. A well-known publisher for ABAP literature is [Rheinwerk-Verlag](https://www.rheinwerk-verlag.de/) with the "[SAP Press](https://www.rheinwerk-verlag.de/sap/)" brand. Highly recommended. 

A good starting point might be the book "[ABAP - An Introduction](https://www.sap-press.com/abap_4955/)" by Brian O’Neill and Jelena Perfiljeva. For German-speaking readers, the book "[ABAP - Entwicklung für SAP S/4HANA](https://www.rheinwerk-verlag.de/abap-entwicklung-fuer-sap-s4hana/)" by Constantin-Catalin Chiuaru et al. could be interesting.

As soon as you've made your first experience with ABAP, read the book "[Clean ABAP: A Style Guide for Developers](https://www.sap-press.com/clean-abap_5190/)". The book gives many tips and suggestions on how to write maintainable ABAP source code. And that's exactly what it's all about every day.

## :memo: Typical activities of an ABAP developer

The following list is a mix of typical core tasks.

Many mentioned tasks here are typical tasks of every developer and therefore do not represent anything special when working with a programming language.

Please note: The term "applications" means also "interfaces" in this context.

* coordinate requirements
* write concepts
* develop new applications
* maintain existing applications
* test applications
* debug applications
  * find and fix bugs
  * clarify how something works
* write documentation
* work together
  * code reviews with colleagues
  * knowledge exchange in team
  * meetings with customers
  * training with users
* continuous learning

Maybe these tasks are also part of the work:

* manage sub-projects
* help to write quotations
* support sales team
* organize development

## :evergreen_tree: Tree view of usefull skills

The following tree view is not meant as "complete". In addition, not every term automatically has to play a role in the working life of an ABAP developer. Furthermore, it's impossible to achieve mastery in every skill or talent. A good mix is sufficient - with strengths and weaknesses. The team you work in should do what you can't do yourself. Find your place in the team.

```
ABAP developer
|
+-- [ soft skills ]
|   |
|   +-- analyzing
|   +-- structured thinking
|   +-- speaking/discussing
|   +-- visualizing
|   +-- writing
|   +-- working in a team
|   +-- working independently
|   +-- self-organisation
|   +-- self-motivation
|   +-- open to new ideas
|
+-- [ hard skills ]
    |
    +-- [ programming/markup/scripting/.. languages ]
    |   |
    |   +-- ABAP
    |   |   |
    |   |   +-- object oriented programming
    |   |   +-- procedural programming
    |   |   +-- RESTful application programming
    |   |   +-- ABAP SQL
    |   |   +-- ABAP Core Data Services (CDS)
    |   |
    |   +-- HTML/CSS
    |   +-- JavaScript
    |   +-- XML
    |
    +-- [ programming methods/styles ]
    |   |
    |   +-- Clean ABAP
    |   +-- database design
    |   +-- design patterns
    |   +-- Unified Modeling Language
    |
    +-- [ tools ]
    |   |
    |   +-- ABAP Development Tools for Eclipse
    |   +-- ABAP Test Cockpit
    |   +-- ABAP Unit
    |   +-- abapGit
    |   +-- ABAP Formatter
    |   +-- ABAP Cleaner
    |   +-- SAP GUI
    |   +-- Data Dictionary
    |   +-- Workbench
    |
    +-- [ interface technologies ]
    |   |
    |   +-- [ protocols ]
    |   |   |
    |   |   +-- HTTP/HTTPS
    |   |   +-- OData
    |   |   +-- REST
    |   |   +-- RFC
    |   |
    |   +-- [ formats ]
    |       |
    |       +-- CSV
    |       +-- IDoc
    |       +-- JSON
    |       +-- XML
    |
    +-- [ business processes ]
        |
        +-- <choose your business area, e.g. finance or logistics>
```

Regarding hard skills, it's also worth taking a look at Tobias Hofmann's [SAP Development Radar](https://tobiashofmann.github.io/sap-dev-tech-radar/). The radar is divided into the areas of "User Interface, Framework, Technology, and Tools" according to the recommendations "Adopt, Use, Hold, and Stop." This can provide some guidance. However, the SAP Development Radar doesn't just focus on ABAP, but on SAP development topics in general.

## :footprints: Make your first steps

First of all, check out the [ABAP Exercism Track](https://exercism.org/tracks/abap). You need nothing more than a browser to solve the tasks contained there.

After that, there is a tutorial called "[Learning the Basics of ABAP Programming on SAP BTP](https://learning.sap.com/learning-journeys/learn-the-basics-of-abap-programming-on-sap-btp)". Since there is a lot to discover, you should take your time.

Another good starting point could be this [blog](https://blogs.sap.com/2021/01/26/getting-started-with-abap-in-2021/) from Markus Haug, published on SAP Community.

## :computer: Get your ABAP Trial access

Actually there are different options to get access to an ABAP Trial system.

| Name | Description | Type | Link |
| :--- | :--- | :--- | :--- |
| ABAP Cloud Developer Trial 2022 | Docker image containing technical stack, no business functions | on-premises | [Blog on SAP Community](https://community.sap.com/t5/technology-blogs-by-sap/abap-cloud-developer-trial-2022-available-now/ba-p/13598069) |
| SAP NetWeaver Application Server ABAP Developer Edition 7.52 SP04 | Installations files containing technical stack, no business functions | on-premises | [SAP Learning Free Trials and Downloads](https://developers.sap.com/trials-downloads.html) |
| SAP BTP Trial | Shared Cloud-based ABAP runtime environment | Cloud | [Get a Free Account on SAP BTP Trial](https://developers.sap.com/tutorials/hcp-create-trial-account.html) |
| Developer Appliance Templates | Trials like SAP NetWeaver 7.52 via SAP Cloud Appliance Library | Cloud | [Cloud Appliance Library](https://cal.sap.com/) |

## :business_suit_levitating: Start a career

This is a proposal to start a career as ABAP developer:

* Find a company that supports you.
* Get to know and team up with your colleagues. They should write modern ABAP.
* Take ABAP basic courses and learn the fundamentals.
* Make your first experiences in small projects. Your colleagues should support you.
* Build your skills. There is no end.
* Take on more responsibility over time.
* Share your experiences.

## :people_holding_hands: Become part of the family

ABAP developers exchange information on different platforms. Below is a selection.

Please consider the following points:

* Always respect the [Netiquette](https://en.wikipedia.org/wiki/Etiquette_in_technology#Netiquette).
* If you have a question, always search for an answer yourself first.
* If you cannot find an answer after your search, please ask the question as precisely as possible.
* Don't expect an answer to your question. The community works on a voluntary basis alongside their actual jobs.

Here's the platform selection.

* [SAP Community](https://community.sap.com/)
* [LinkedIn](https://www.linkedin.com/)
* [Bluesky](https://bsky.app/) (check [SAP Developer Starter Pack](https://bsky.app/starter-pack/marian.marianzeis.de/3lavxhk26r32a) by [Marian Zeis](https://github.com/marianfoo))
* [X (formerly Twitter)](https://twitter.com/)
* [Stack Overflow](https://stackoverflow.com/)
* [GitHub](https://github.com/)
* [ABAP Blog](https://abapblog.com/)
* [Tricktresor](https://tricktresor.de/)
* [Die Codezentrale](https://codezentrale.de/category/sap/)

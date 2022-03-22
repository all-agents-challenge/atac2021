---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<div style="font-weight: bold; border: black 1px solid; padding: 5px; text-align: center;">
Proceedings of ATAC 2021 have been published <a href="http://ceur-ws.org/Vol-3111/">on CEUR-WS.org (vol. 3111)</a>.
</div>

<h1>All The Agents Challenge</h1>

<div style="margin-top: -10px;">
	<p>In conjunction with the <a href="https://iswc2021.semanticweb.org/" target="_blank">International Semantic Web Conference (ISWC) 2021</a> (October 24-28, 2021)</p>
</div>

## Motivation

Agents on the Web have been a part of the vision for the [Semantic Web](https://www.scientificamerican.com/article/the-semantic-web/).
While [it has](https://doi.org/10.1109/MIS.2007.62) been [noted](https://doi.org/10.1109/MIS.2006.62) that the original Semantic Web vision has not yet fully materialised, recent progress seems to indicate that we may now be at a stage where:
1. developments such as the [Web of Things](https://www.w3.org/TR/wot-thing-description/) may unlock new practical use cases for agents on the Web, and 
2. the substrate provided by recent Semantic Web technologies (e.g., [Linked Data Platform](https://www.w3.org/TR/ldp/), [Linked Data Notifications](https://www.w3.org/TR/ldn/), [SoLiD](https://solidproject.org/) PODs) may open [new perspectives](http://dl.acm.org/citation.cfm?id=3331893) on the integration of Semantic Web with agent technologies.

This bridging of technologies and communities has also been the topic of the [Dagstuhl seminar "Autonomous Agents on the Web"](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=21072) held in Feburary 2021.
Therefore, for the 20th edition of the ISWC conference and in spirit of [Jim Hendler's op-ed](https://doi.org/10.1109/MIS.2007.62) that asked "Where are all the agents?", we want to pose the *All-the-Agents-Challenge (ATAC)* to the Semantic Web community: 

<div style="text-align: center; width:100%;"><em style="font-style:italic; font-weight:bold;">The challenge to build agents that do things on Linked Data</em></div>

## Environments
Submissions to the challenge can make use of one of those environments -- or bring their own.

* The [Autonomous Maze Environment Explorer Project (AMEE)](https://amee-project.github.io/) provides an environment for agents that have to escape a maze by following hypermedia affordances. AMEE can simulate mazes of different sizes. We provide a [RDF version of AMEE](https://github.com/all-agents-challenge/maze-server).
    
* The [Building on Linked Data (BOLD)](https://github.com/bold-benchmark) environment is a description of a large real-world building (2 floors, over 250 rooms) with simulated occupancy and sunlight. Web agents can read occupancy and light level in rooms values through sensors. Agents can also actuate light switches located in the rooms. On this basis, participants to the challenge could implement several energy saving scenarios by interacting with the building's lighting system. The building and all sensors and actuators are modeled using the Brick and Semantic Sensor Network (SSN) ontologies. Participants can experiment with BOLD and program their agents against it by downloading the [BOLD server](https://github.com/bold-benchmark/bold-server/releases/tag/v0.1.0).

* Your amazing agent environment. If you have a cool agent environment that provides Linked Data and maybe Web of Things Thing Descriptions, like your SoLiD POD, or your semantic IoT deployment, why not submit an agent that uses it?

## Important Dates

| Event | Date |
|---|---|
| Release of environments: | May 22, 2021 |
| Submission deadline: | **August 1, 2021** (extended) |
| Notifications: | August 27, 2021 |
| Challenge presentations: | October 24-28, 2021 |

## Process

To take part in the challenge, you need to prepare a submission.
Then, the submission will be evaluated, and, in case of acceptance, there will be the opportunity to present/appear in the proceedings.
Details on presentation and proceedings will be published here.

### Submitting to ATAC 2021

Submissions should contain:
* 1-2 pages of text, including:
  * A link to a short demo video with running code
  * A link to source code

Submissions should be submitted via [easychair](https://easychair.org/conferences/?conf=atac2021).

### After Acceptance

There will be the opportunity to present for accepted submissions at ISWC, details are yet to be confirmed.
Accepted submissions (finalists) will be invited to extend their paper to 5 pages to appear in the challenge's proceedings.

## Judging Criteria

While there are no established metrics for evaluating the performance of agents on the Semantic Web, and as we want to foster creativity, the committee will evaluate submissions according to the criteria we describe in the following. The authors should make sure that adhering to these criteria does not lead to excessive complexity that is not warranted by the use case. 

### Clarity (hard criterion)
As we aim to attract a diverse set of submissions, we expect an accompanying short paper and demonstrator video that describe the use-case and the agent-based system. We expect the submission to be clear and understandable to the evaluation committee.

To raise the clarity you may want to say how you position yourself in well-established classifications for agent-based systems, e.g., the Russell/Norvig and (Genesereth/Nilsson) taxonomy to classify agents into Simple Reflex (tropistic) agents, Model-based (hysteretic) agents, and Goal-based (deliberate) agents.

### Linked Data (hard criterion)

A hard constraint we apply is that we expect agents to operate on Linked Data on the Web, i.e. to make HTTP requests, to process RDF, and to follow links. 

### Support for heterogeneity

To take an existing (multi-)agent system and make it interoperable with multiple sources/external data gives submissions some points in this category. The better a submission can cope with heterogeneous environments, the more points we award.

### Support for dynamicity

During the execution, an agent should exhibit adaptive behaviour (e.g., to cope with dynamic environments, if the environment is dynamic), i.e. we award points for submissions if agents:

* react to changes in the environment
* enact change in the environment
* update their state or evolve at runtime

### Support for interaction and coordination

Next to single-agent submissions, we also appreciate agents with a form of social ability, i.e., agents that can interact and coordinate with other agents (e.g., direct message exchange, stigmergy, organisations, policies and norms, automated negotiation, interaction with humans).

## Organization

### Challenge Jury
* Jim Hendler, Rensselaer Polytechnic Institute (USA)
* Jomi Hübner, Federal University of Santa Catarina (BR)
* Simon Mayer, University of St. Gallen (CH)
* Alessandro Ricci, University of Bologna (IT)
* Munindar Singh, North Carolina State University (USA)

### Challenge Organizers

* [Tobias Käfer](https://www.aifb.kit.edu/web/Tobias_K%C3%A4fer/en), Karlsruhe Institute of Technology (DE)
* [Andreas Harth](http://harth.org/andreas/), University of Erlangen-Nuremberg and Fraunhofer SCS (DE)
* [Andrei Ciortea](http://andreiciortea.ro/), University of St. Gallen (CH)
* [Victor Charpenay](http://www.vcharpenay.link/), MINES Saint-Étienne (FR)

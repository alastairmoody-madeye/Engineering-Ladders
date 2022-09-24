# Introduction

This framework allows managers and directors to have meaningful conversations with engineers about the expectations of each position and how to plan for the next step in their career path at Layr.  Although the framework uses roles and levels that are somewhat standard in the US tech industry, every company is different. The roles described in this repository are specific to Layr and the needs of Layr customers, internal users, and other stakeholders. We provide an "Also Known As" section for each role to help you communicate externally.

Our mission is to create the very best technology enabled experience possible for our those that use our software.  That means constantly improving our software, tooling, processes, team members, and culture. Use this document to plan out that journey for yourself.

We expect that the Layr Engineering Ladders will change over time as the landscape of software engineering changes.  We encourage all team members to submit pull requests to make the Layr Engineering Ladders better serve our customers with the very best experience possible. 

 There are a number of different systems at play in that work together to create a great, high value experience for our customers. The framework relies heavily role level responsibilities for the different systems necessary to deliver value to our customers.  To help you visualize the dimensions of these systems and the degree to which each level impacts that system, we rely heavily on radar charts:

![System Dimensions](charts/Layr-Engineering-Path.png "System Dimensions")

We designed these charts to represent the progression in the scope of responsibilities, skills, and accountability's as they relate to the role responsible for the system.  As you explore each path ask yourself - how can I level up my skills to achieve the next step in the path to have a bigger impact on the system for which I'm responsible? How can I expand my impact on the system to be more valuable to our customers?  We've provided training and expected performance telemetry to help you and hope that you contribute to the conversation about what each rung means. 

# Systems, Roles, Dimensions, Levels
The framework is composed of different systems, each of which is critical to delivering business value for our customers.

## Systems
For our purposes, the definition of a system, is -

_"A combination of people, technologies, and processes that produce artifacts used as inputs to high-value technology enabled experiences for our customers"_

Different companies use different systems depending on the technology under development.  The Layr Engineering team determine that the following systems are necessary to deliver for our customers, users, and stakeholders -
* Software
  * Application & Infrastructure code
  * Build processes
  * Architectural diagrams
* Quality
  * Testing plans
  * Automated testing code for UI's & APIs
* Delivery
  * Delivery road-maps
  * Performance metrics
* Product
  * Stories
  * Requirements (e.g., written, diagrams, etc)

## System Roles
There are two different types of roles operating within in each system:
* Engineers - Engineers are generally responsible for producing artifacts directly or indirectly used in the engineering process. Examples include application code, infrastructure code, automated tests, requirements, and project plans.
* Directors - Directors are primarily focused on team effectiveness, constantly looking for ways to reduce the cost, in time and money, of delivering business value. Examples include ensuring that engineers have what they need to quickly build high quality software in a team they love, for a mission in which they believe, and have career plans to help them continuously upgrade their skills. This could be new processes, technologies, skills, or even cultural changes.  They have deep experience in being an engineer, giving them the empathy they need to deeply understand what the team needs to be effective.

Consequently, for each system you will find an engineering role and a director role. So, who is responsible for the effectiveness of directors and the team as a whole?  This responsibility falls to the [**Engineering Director**](Engineering-Director.md). Using [RACI](https://en.wikipedia.org/wiki/Responsibility_assignment_matrix) vernacular, the Engineering Director is generally accountable for the effectiveness of the entire engineering team across all systems while engineering directors are responsible for the effectiveness of teams operating within their system. To better understand how this works refer to this overview on [directing directors](Directing-Directors.md)

There is sometimes confusion over the difference between a [Software Director](Software-Director.md) and an [Engineering Director](Engineering-Director.md), please refer to the [Software Director vs Engineering Director](Comparison-Software-Director-Engineering-Director.md) page for a detailed comparison.

## System Dimensions

Within each system, there are 5 different common dimensions:
* **Technology**: knowledge of the tech stack and tools used to deliver the primary artifact of the system
* **System**: level of ownership of the system that product the primary product fo the role
* **People**: relationship with the team(s) necessary to deliver the primary product for the role
* **Process**: level of engagement with engineering process used to create the primary product for the role
* **Influence**: social network influence of stakeholders in the primary product for the role

The **influence** axis can be seen as a *cross-cutting dimension* since it is orthogonal and applies to all the other dimensions.

Each axis has 5 different levels of performance. It is important to highlight that every level includes the previous one(s). For example, someone that *evangelizes* technology, *specializes* and *adopts* it as well.

### Dimension Levels
Below are the general skill level expectations for each dimension in a system.

#### Technology  

1. **Adopts**: actively learns and adopts the technology and tools defined by the team for the system
2. **Specializes**: is the go-to person for one or more technologies used in the system and takes initiative to learn new ones
3. **Evangelizes**: researches, creates proofs of concept and introduces new technologies to the team to accelerate the team and reduce costs
4. **Masters**: has very deep knowledge about the whole technology stack of the system
5. **Creates**: designs and creates new technologies that are widely used that dramatically accelerate the team and reduce costs

#### System

1. **Enhances**: successfully pushes new features and bug fixes to improve and extend the system
2. **Designs**: designs and implements medium to large size features while reducing the system's tech debt
3. **Owns**: owns the production operation and monitoring of the system and is aware of its SLAs
4. **Evolves**: evolves the system to support future requirements and defines its SLAs
5. **Leads**: leads the technical excellence of the system and creates plans to mitigate outages

#### People

1. **Learns**: quickly learns from others and consistently steps up when it is required
2. **Supports**: proactively supports other team members and helps them to be successful
3. **Mentors**: mentors others to accelerate their career-growth and encourages them to participate
4. **Coordinates**: coordinates team members providing effective feedback and moderating discussions
5. **Manages**: manages the team members' career, expectations, performance, productivity, and job satisfaction

#### Process

1. **Follows**: follows the team processes, delivering a consistent flow of features to system
2. **Enforces**: enforces the team processes, making sure everybody understands the benefits and trade-offs
3. **Challenges**: challenges the team processes, looking for ways to improve them
4. **Adjusts**: adjusts the team processes, listening to feedback and guiding the team through the changes
5. **Defines**: defines the right processes for the team's system, maturity level, balancing agility and discipline

#### Influence

1. **Sub Team**: makes an impact on individuals within a team but not the entire team
2. **Team**: makes an impact on the whole team including members playing other roles
3. **Many Teams**: makes an impact not only his/her team but also on other teams
4. **Company**: makes an impact on the whole tech organization
5. **Community**: makes an impact on their community

## Radar

By bringing together each of the pieces above -
* System
* Dimensions
* Roles
* Levels

We can map out the performance profile for every role and level in every system.  For example, let's says that a level three 3 has the following performance profile -
* **Specializes**: is the go-to person for one or more technologies used in the system and takes initiative to learn new ones
* **Designs**: designs and implements medium to large size features while reducing the system's tech debt
* **Supports**: proactively supports other team members and helps them to be successful
* **Challenges**: challenges the team processes, looking for ways to improve them
* **Team**: makes an impact on the whole team including members playing other roles
Which has the following profile on the radar -
![System Dimensions](charts/Layr-Engineering-Path-SE3.png "Software Engineer 3")

Here are the profiles for each role and level in Layr Engineering team (click on each for more details):
### Engineers

| Step | [Software](Software-Engineer.md) | [Quality](Quality-Engineer.md) | [Delivery](Delivery-Engineer.md) | [Product](Product-Engineer.md) |
| :---: | :---: | :---: | :---: |  :---: |
| 1 | [SE1](Software-Engineer.md#se1---software-engineer-1) | [QE1](Quality-Engineer.md#qe1---quality-engineer-1) | [DE1](Delivery-Engineer.md#de1---delivery-engineer-1) | [PE1](Product-Engineer.md#pe1---product-engineer-1) |
| 2 | [SE2](Software-Engineer.md#se2---software-engineer-2) | [QE2](Quality-Engineer.md#qe2---quality-engineer-2) | [DE2](Delivery-Engineer.md#de2---delivery-engineer-2) | [PE1](Product-Engineer.md#pe2---product-engineer-2) |
| 3 | [SE3](Software-Engineer.md#se3---software-engineer-3) | [QE3](Quality-Engineer.md#qe3---quality-engineer-3) | [DE3](Delivery-Engineer.md#de3---delivery-engineer-3) | [PE1](Product-Engineer.md#pe3---product-engineer-3) |
| 4 | [SE4](Software-Engineer.md#se4---software-engineer-4) | [QE4](Quality-Engineer.md#qe4---quality-engineer-4) | [DE4](Delivery-Engineer.md#de4---delivery-engineer-4) | [PE4](Product-Engineer.md#pe4---product-engineer-4) |
| 5 | [SE5](Software-Engineer.md#se5---software-engineer-5) | | | |
| 6 | [SE6](Software-Engineer.md#se6---software-engineer-6) | | | |
| 7 | [SE7](Software-Engineer.md#se7---software-engineer-7) | | | |

### Directors
| Step | [Software](Software-Director.md) | [Quality](Quality-Director.md) | [Delivery](Delivery-Director.md) | [Product](Product-Director.md) | [Engineering](Engineering-Director.md) |
| :---: | :---: | :---: | :---: |  :---: | :---: |
| 5 | [SD1](Software-Director.md#sd1---software-director-1) | [QD1](Quality-Director.md#qd1---quality-director-1) | [DD1](Delivery-Director.md#dd1---delivery-director-1) | [PD1](Product-Director.md#pd1---product-director-1) | [ED1](Engineering-Director.md#ed1---engineering-director-1) |
| 6 | [SD2](Software-Director.md#sd2---software-director-2) | [QD2](Quality-Director.md#qd2---quality-director-2) | [DD2](Delivery-Director.md#dd2---delivery-director-2) | [PD2](Product-Director.md#pd2---product-director-2) | [ED2](Engineering-Director.md#ed2---engineering-director-2) |
| 7 | [SD3](Software-Director.md#sd3---software-director-3) | [QD3](Quality-Director.md#qd3---quality-director-3) | [DD3](Delivery-Director.md#dd3---delivery-director-3) | [PD3](Product-Director.md#pd3---product-director-3) | [ED3](Engineering-Director.md#ed3---engineering-director-3) |


# FAQs

**What if some of the people don't meet all the points?**
That is very normal, people are usually stronger in some areas and weaker in others. The framework should not be used as a checklist to promote people but instead as guidance to have meaningful career conversations.

**What if I disagree with the Layr Engineering Ladders?**
The Layr Engineering Ladders is open to the entire Layr Engineering team.  We invite all members to submit pull requests to improve it.  Furthermore, the Layr Engineering Paths is in a public repository so anyone can help us improve with your perspectives.

**When is a person ready to move to the next level?**
We will measure performance Telemetry through quarterly 360 degree feedback.  We will measure training performance through assessments, certifications, skill demonstrations, etc. To level up your career at Layr your must, at a minimum, meet the training and telemetry expectations for at least one quarter. You must then present your case to the Coaching Team that you have successfully achieved the next scope of your chosen engineering path.

**How do I collect evidence to support the discussion with the Coaching team?**
Layr uses Lattice to collect the necessary data :
* 1:1 updates
* 360 degree feedback from peers and other teams
* Quarterly Individual Development Objectives (IDO's) 

In addition to Lattice, Layr also uses tools like LinearB to collect engineering performance.  Finally, we closely monitor team burn-down charts and individual contributions to the burn-down. 

**Could the framework provide more specific examples of behavior to support each level?**
Specific examples of behavior require knowledge about the way that the team works, the system architecture and its technology stack. It is recommended to allow each team to define their own examples for each role.

**Why do all the software paths except for software stop at level 4?**
Software engineering has many more dimensions than the other roles including things like programming languages, front-end versus backend, cloud experience, architectural paradigms, etc. This is not to say that the other roles are not as critical to a great customer experience; it is to say that ultimately it is the software engineer's output that the customer will touch directly and the breadth of knowledge required is extensive.

**Why does the framework stop at level 7 for Software Engineers?**
Levels 8 and above vary drastically from company to company. Organizations of different sizes tend to assign a diverse level of scope to positions so high in their structure.  At our current size, we've determined that 7 levels is more that enough to meet the needs of Layr's customers.

**Do you have any additional resources about the topic?**

* [The Manager's Path](http://shop.oreilly.com/product/0636920056843.do): Camille Fournier does an excellent job at describing the expectations and challenges of many engineering positions. Also, she provides good advice about writing a career path in chapter 9.

* [How to Be Good at Performance Appraisals](https://store.hbr.org/product/how-to-be-good-at-performance-appraisals-simple-effective-done-right/10295): Dick Grote explains in simple terms how to define job responsibilities and how to evaluate performance (results and behaviors).

* [Multipliers](https://multiplers.com): Liz Wiseman explains how to multiply the capabilities of your teammates

* [Impact Players](https://impact-players.com): Liz Wiseman explains operate as an individual contributor

# Other Pages
* [**Introduction**](README.md)
* [**Software Engineer**](Software-Engineer.md)
* [**Software Director**](Software-Director.md) 
* [**Quality Engineer**](Quality-Engineer.md)
* [**Quality Director**](Quality-Director.md)
* [**Delivery Engineer**](Delivery-Engineer.md)
* [**Delivery Director**](Delivery-Director.md)
* [**Product Engineer**](Product-Engineer.md)
* [**Product Director**](Product-Director.md)
* [**Engineering Director**](Engineering-Director.md)
* [**Software Director vs Engineering Support**](Comparison-Software-Director-Engineering-Director.md)
* [**Directing Directors**](Directing-Directors.md)

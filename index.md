# Productivity in Software Development

_Niek van der Plas (5363780) & Mark Meijhuis (4389255)_

TL;DR: Short summary of the research idea. This should be a 4-5 sentences paragraph, containing the motivation of the paper, its goal, a bit of its research method, results, and implication.

## Introduction

One of the most important tasks managers or product owners have is to improve productivity of their employees. Some of these managers use several metrics to track, and give feedback to, their developers so they know whether they are performing well or in what areas they can improve. Most still lack such a feedback system and rely on the developer reflecting back on his own _perceived_ productivity. 

Many factors impact the productivity of a developer. Oliveira *et al.* found that certain code characteristics correlated with the productivity of an employee as observed by the manager. These metrics could be measured automatically and given as feedback to both the employees and the managers. 

The effect this would have on the employees could go both ways. The employees could feel an incentive to work harder, as their productivity is being measured and they want the company to think that they are delivering good work. However, the additional surveillance could put more stress on the employees, causing them to be more unhappy, which could reduce their problem solving abilities (Graziotin, 2014).

Managers could use this information to keep an eye on certain employees that might have a reason to be less productive. They could then optimize the workflow of these employees to improve their productivity. They could also look at the most productive employees and see what they are doing right, to streamline the workflow of the team.

Our research question follows from these hypotheses and is as follows: *"Does objectively measuring productivity of software developers and giving this feedback to both the developers and managers have a positive impact on team productivity?"* 

<!-- 

To answer this, we will assess different businesses which all use the same programming language in a controlled experiment where one group gets weekly feedback on their productivity and have a survey at the end of our research period to answer our research questions.
- Main research question: what is the effect on managers/developers when 
they know that developer performance is objectively being measured?
- Does it give developers an incentive to be more productive?
- Does it give managers the tools to optimize their team?
- Is there a difference between the developer's perceived productivity and their actual productivity?



The introduction should be 4-5 paragraphs, explaining the overall motivation and goal of the paper. 

* Explain the broader topic of research
* Explain the research gap: what are we missing?
* YOUR RESEARCH, YOUR GENIUS IDEA
* Put your main research question
* A summary of the research method -->


## Background and Related Work 
Efficiency optimization is important for businesses to increase revenue and reduce time-to-market. Optimizing software development is important for software departments of these companies. Measuring productivity and taking steps to improve said productivity seems to be the obvious solution for optimization, but how is this done? 

There are both advantages and disadvantages to measuring software developer's productivity<sup>[[1]](#1)</sup>. Ko mentions that measuring productivity might bring a lot of negative unintended consequences with it. For example, more defects might ship to decrease time-to-market, due to unadequate testing. Additionally, qualitative and quantitative data on productivity may not be correlated. Too many details needs to be taken into account, such as productivity due to changes in the team, which makes interpretation and drawing conclusions from said details vague. Ko states that managers should be the main measurers for productivity.

Oliveira _et al._ have measured the correlation of objective code characteristics, such as lines f code produced by a developer, with the qualitative assessment of managers<sup>[[2]](#2)</sup>. Correlating commit behavior with manager assessment seemed to be tricky, but certain code characteristics seemed to correlate well with productivity. The code characteristics were _'Source Lines of Code by Time'_(SLOC/Time), _'Halstead Effort by Time'_(HE/Time) - which is a measure of source code complexity - and _Code Owned by Time_(CO/Time).

Meyer _et al._ state that efforts aimed at improving developer productivity are undertaken without knowledge about how developers spend their time at work and how it influences their own perception of productivity<sup>[[3]](#3)</sup>. Meyer _et al._ give insight into developer behavior and time spending, which made them draw the conclusion that productivity and the factors that influence it are highly individual.

Chapetta _et al._ made an effort to characterize software development productivity and to understand the influence of several factos on the productivity of software developers<sup>[[4]](#4)</sup>. In their study they proposed a framework, comprising of multiple factors (25) and relationships (33) obtained from empirical evidence based on technical literature over the last 30 years, which helps both practitioners and researchers with observing, deciding and controlling the productivity within software development teams.

Ganta proposes that the driver behind productivity is either intrinsic or extrinsic motivation and a good feeling associated with their work<sup>[[5]](#5)</sup>. The link between motivation and feeling good about one's job is complex and a clear action plan cannot be distinguished easily. Extrinsic motivation might be bonusses after delivering good work, while intrinsic motivation and feeling good about one's job might have more to do with the impact of the actual work or the relation with clients and co-workers. What motivates an employee is personal to the employee, so managers need to take this into account when they want to tackle productivity.

In addition to developers, we need quantitative measures to determine whether the managers and their associated business are doing their tasks correctly. Antolić gives an overview of Key Performance Indicators that can be used to evaluate software development process efficiency<sup>[[6]](#6)</sup>. These key performance indicators are as follows.
* Schedule adherence: is everything on time, according to the planning?
* Assignment Content Adherence: ability to deliver the project as agreed at the end of the process.
* Cost Adherence: how well do the development costs fit into the scope of the project?
* Fault Slip Through: how many faults are captured before delivery?
* Trouble Report Closure Rate: how many trouble reports are closed on time?
* Cost per Trouble Report: measures the maintenance costs in fixing trouble reports.

It is important to take a critical look at how productivity has been measured in the past. Oliveira _et al._ have investigated and made an effort to get a better understanding on how productivity should be measured<sup>[[7]](#7)</sup>. They did a systematic mapping study on publications regarding software productivity and noting down all the different measurements that researchers are using to measure producitivity. They noticed that single ratio metrics have a tendency to be used by researchers eventhough there is not any conscensus that this is the best method.

Forgsen _et al._ state that there are dimensions that can be optimized to increase software developer productivity<sup>[[8]](#8)</sup>. The authors have created a framework called the 'SPACE' framework that can be used as a reference to investigate these dimensions in software development companies and teams. The dimensions that should be taken into account and optimized for to ensure developer productivity are as follows.
* Satisfaction and well-being: it is possible that satisfaction could serve as a leading indicator for productivity. Retention of developers could be an indicator of this metric.
* Performance: a measure about code review velocity, customer satisfaction and reliability.
* Activity: how many actions or outputs are performed by the developer?
* Communication and collaboration: a measure of how people talk and work together. Could be measure by code review quality or thoughtfulness, knowledge sharing or quality of meetings.
* Efficiency and flow: doing work with minimal delays or interruptions. Could be measured by code review timing, productivity perception and lack of interruptions.


Sadowski _et al._ collected all the information of previous studies by software engineering though leaders into one bundle of ideas and challenges<sup>[[9]](#9)</sup>. One such chapter in this book is that of Graziotin _et al._ who provided an overview of their studies on happiness of software developers as well as the correlation with productivity<sup>[[10]](#10)</sup>. They set of by defining happiness and how to measure it and following up with multiple analyses on different aspects regarding happiness and software development, they especially focus on a few consequences of happiness and unhappiness:
* Cognitive performance: How efficiently information is processed
* Flow: How long-lasting states of intense attention and concentration are without interruptions.
* Motivation and Withdrawal

They conclude with several experiments and list potential impacts of happiness on both software development and other outcomes. They firmly state that through their experiments they have proved that there exists a link between happiness and productivity in software development and mention that the future will need more research on the topic as an increasing number of people will work with digital product and are performing tasks that can be narrowed down to software development.

Mota _et al._ emphasize the importance of improving software development productivity in an environment of external openness and globalization of business<sup>[[11]](#11)</sup>. They developed a web system to support software development teams in measuring their productivity and did a case study to determine its effectiveness. The effectiveness on two software development teams seemed to be positive.

<!--"Show off" your knowledge of the area; it gives all the background that the reader needs to understand your work; it gives an overview of the entire research area around the topic

* Write a background and/or related work selections
	* Background: Background knowledge that the reader needs
	* Related work: Papers that are related to your research and that the reader can use to compare with your work

* One paragraph per paper. Some sentences explaining what the paper is about. Some sentences explaining the methodology and results of the paper. Maybe limitations or future work. Maybe some comparison with the work you are doing.

* At least 10 papers in the related work section. Do not go over 15 papers.-->

## Research method
The goal of this study is to find out what the effect of different kind of measurements are on the productivity of both managers and developers. For us to research this, we want to rule out as many variables as possible. Thus, we will approach several software development teams varying from small (<5 employees) to large (>20 employees), who are developing in the same programming language. To measure productivity we will use different Key Performance Indicators (KPIs) for managers and developers.

We have identified several research questions that we want to answer:

_RQ1_: What is the effect on managers/developers when they know that developer productivity is objectively being measured?

_RQ2_: Does knowing you are being objectively measured give developers an incentive to be more productive?

_RQ3_: Does productivity measurements give managers the tools to optimize the productivity of their team?

_RQ4_: Is there a difference between the developer's perceived productivity and their actual productivity? 

To find out what the effect is on both managers and developers when they know that productivity is objectively being measured we will execute the experiment in a controlled environment where half of the software development teams know that they are being measured. They will receive weekly updates of their productivity for 6 weeks while the other half of software development teams do not. With this controlled experiment we can immediately answer our second research question since we can determine whether or not the thought of being actively measured incentivizes developers to be more productive. To analyze both these research questions we will do statistical analysis in the form of a 2-paired t-test since we compare two 2-paired groups. 

For the third research question, we will analyse the KPIs of the managers and determine whether there is a statistical difference between the two groups in the experiment. In addition to that, we will send out a survey which they all have to fill out which will then be analyzed to determine whether there are changes in perceived productivity of developers by the managers or whether there are changes in the mentioned KPIs. Next to the survey, we will again perform a 2-paired t-test here because we would like to know whether the weekly feedback half of the teams has makes a difference on the productivity on the team overall.

Our fourth research question will be answered through a follow-up survey at the end of the study. All developers will fill out this survey and with the data acquired we will be able to determine whether there exists a statistical difference between perceived and objectively measured productivity. We will determine this with the use of a 2-paired t-test because also here we deal with two paired groups. 

<!-- 
1e rq = 2-paired t-test
2e rq = 2-paired t-test
3e = survey + 2-paired t-test
4e = survey + 2-paired t-test
 -->


<!-- What you are going to research and how.

* State your research goal. "The goal of this study is to explore the relationship between sunlight and defects in open-source systems".
* What method are you doing to use? 
* Write down clear research questions (RQ1, RQ2, ...)
* For each RQ, describe the method you are going to use to answer the RQ
* Explain any datasets you are going to reuse or create. Why is this dataset the right one for your project?
* Explain any (human) subjects you are going to reuse or create. How are you going to find them? Why are they the right people to take part of your study?
* Explain any data analysis techniques you plan to use. Are you going to use some stastistical test? Which one? Why? -->

## Execution plan

<!-- First of all, we would look at related work and determine what other research deem to be the most important factors for objective productivity. Out of this pool of Key Performance Indicators (KPIs) we will choose the most relevant ones for our research.  -->

We will contact several software development teams in the Netherlands of which the team members are all based in the Netherlands as to avoid cultural differences within the team. These will be of small size (<5 employees) and of a large size (>20 employees). We will contact them that we have the intention of improving their productivity and whether they would like to take part in academic research. The software projects in this study will mostly use the same programming language, as differences in languages measured with our characteristics could lead to bias. We will only mention to half of the teams that their performance is being tracked and that they will get weekly feedback.

For the developers, will develop a tool that tracks the three performance metrics of source code as described by Oliveira _et al._<sup>[[2]](#2)</sup>:
* Source Lines of Code by Time
* Halstead Effort by Time
* Code Owned by Time

This tool will integrate with GitHub. All developers in the teams will be tracked. Developers will receive a survey assessing their own productivity.

To determine business metrics and whether the managing improves with access to this data, 6 Key Performance Indicators as described by Antolić<sup>[[6]](#6)</sup> will be measured at the start of the study. These indicators are:
* Schedule adherence: is everything on time, according to the planning?
* Assignment Content Adherence: ability to deliver the project as agreed at the end of the process.
* Cost Adherence: how well do the development costs fit into the scope of the project?
* Fault Slip Through: how many faults are captured before delivery?
* Trouble Report Closure Rate: how many trouble reports are closed on time?
* Cost per Trouble Report: measures the maintenance costs in fixing trouble reports.

Since these KPIs involve rich data, we will use a survey with likert scale questions to determine any significant changes before and after the study. The managers will also assess the perceived productivity of their individual team members.

For 6 weeks, the developers will be tracked, while half of the groups receive weekly feedback. The managers will receive the feedback on all of the developers in their teams. 

After these 6 weeks, we will send a follow-up survey that is identical to the first survey. The semi-objective productivity and perceived productivity of developers will be measured in this way. The managers will assess the KPIs and the perceived productivity of the employees.

The surveys will be tested by assessing differences in responses between questions. Significant changes between KPIs of software teams will be detected using a 2-2-paired t-test, since this data is numerical. The differences between question responses on likert scale questions will be also be analyzed using a 2-2-paired t-test, since the Central Limit Theorem states that we can use the average of the responses on each question to determine the means[[12]](#12). All these tests will be performed to determine whether a statistically significant difference exists between objective productivity of developers, perceived productivity of developers, managing performance of managers and differences in these dimensions between small and large businesses.


<!-- How to run this study?

* How you would you then run this study? -->

## References

<a id="1">[1]</a>: Ko A.J. (2019) _Why We Should Not Measure Productivity_. In: Sadowski C., Zimmermann T. (eds) Rethinking Productivity in Software Engineering. Apress, Berkeley, CA. https://doi.org/10.1007/978-1-4842-4221-6_3

<a id="2">[2]</a>: Oliveira, E., Fernandes, E., Steinmacher, I. et al.. _Code and commit metrics of developer productivity: a study on team leaders perceptions_. Empir Software Eng 25, 2519–2549 (2020). https://doi.org/10.1007/s10664-020-09820-z

<a id="3">[3]</a>: Meyer, André & Barton, Laura & Murphy, Gail & Zimmermann, Thomas & Fritz, Thomas. (2017). _The Work Life of Developers: Activities, Switches and Perceived Productivity_. IEEE Transactions on Software Engineering. PP. 1-1. 10.1109/TSE.2017.2656886. 

<a id="4">[4]</a>: Chapetta, W.A., Travassos, G.H. _Towards an evidence-based theoretical framework on factors influencing the software development productivity_. Empir Software Eng 25, 3501–3543 (2020). https://doi.org/10.1007/s10664-020-09844-5

<a id="5">[5]</a>: Girdwichai, Luedech & Sriviboon, Chutikarn. (2020). _Employee motivation and performance: do the work environment and the training matter?_. Journal of Security and Sustainability Issues. 42-54. 10.9770/jssi.2020.9.J(4). 

<a id="6">[6]</a>: Antolić, Ž. (2008). _An Example of Using Key Performance Indicators for Software Development Process Efficiency Evaluation_. 

<a id="7">[7]</a>: Oliveira, Edson & Viana, Davi & Cristo, Marco & Conte, Tayana. (2017). _How have Software Engineering Researchers been Measuring Software Productivity? - A Systematic Mapping Study_. 76-87. 10.5220/0006314400760087.

<a id="8">[8]</a>: Forsgren, Nicole & Storey, Margaret-Anne & Maddila, Chandra & Zimmermann, Thomas & Houck, Brian & Butler, Jenna. (2021). _The SPACE of Developer Productivity: There's more to it than you think_. Queue. 19. 20-48. 10.1145/3454122.3454124.

<a id="9">[9]</a>: Sadowski, Caitlin & Zimmermann, Thomas. (2019). _Rethinking Productivity in Software Engineering_. 10.1007/978-1-4842-4221-6.

<a id="10">[10]</a>: Graziotin D., Fagerholm F. (2019) _Happiness and the Productivity of Software Engineers_. In: Sadowski C., Zimmermann T. (eds) Rethinking Productivity in Software Engineering. Apress, Berkeley, CA. https://doi.org/10.1007/978-1-4842-4221-6_10.

<a id="11">[11]</a>: Mota, J.S.; Tives, H.A.; Canedo, E.D. _Tool for Measuring Productivity in Software Development Teams_. Information 2021, 12, 396. https://doi.org/10.3390/info12100396.

<a id="12">[12]</a>: Norman, G. Likert scales, levels of measurement and the “laws” of statistics. Adv in Health Sci Educ 15, 625–632 (2010). https://doi.org/10.1007/s10459-010-9222-y

<!-- Links

Why We Should Not Measure Productivity
https://link.springer.com/chapter/10.1007/978-1-4842-4221-6_3

- Measuring productivity creates a different incentive. For example, creative processes might not occur as regularly when, for example, lines of code is measured.
- A team might ship more defects or introduce technical debt.
- Trying to optimize for a single measure such as bugs closed, user stories finished or number of customers acquired always comes at the expense of other metrics.
- Avoid Big Brother situation.
- This book does not seem to have done any empirical studies, only thought experiments.
- Managers cannot understand the full picture and can therefore not make logical objective decisions.
- Doing experiments to measure productivity is not doable, since there are too many individual differences.
- The ultimate bottleneck in this experiment is behavior change.

- Improving productivity requires explaining the factors that affect it, but that requires qualitative insights into team behavior.
- Teams are always changing, making it even harder to get insights about team behavior through data.


--------------

Code and commit metrics of developer productivity: a study on team leaders perceptions
https://link.springer.com/content/pdf/10.1007/s10664-020-09820-z.pdf

- Asked leaders about the productivity of their team and looked for correlations between this opinion and metrics.
- Our quantitative data suggest a greater correlation of the leaders’ perceptions with codebased metrics when compared to commit-based metrics. Our qualitative data reveal that leaders have positive impressions of code-based metrics and potentially would adopt them.
- Developer productivity is essential to the success of development projects.
- Team leaders’ perceptions are usually the primary source of information when project managers make decisions about development teams.
- Perceptions are subjective and biased. Thus, a systematic productivity assessment could help team leaders in their work.

- Managers are best positioned to get these qualitative insights by interacting with their team.
- Many studies neglecting the analysis on the developer level.
- Uses characteristics in (1) source code and (2) commits.

Metrics (source code):
- Source Lines of Code by Time (SLOC/Time)
- Halstead Effort by Time (HalsteadEff/Time): source code complexity
- Code Owned by Time (CodeOwned/Time): if the highest percentage of lines is a developer's, then the developer is the owner for this metric.

Metrics (commits):
- Commits Performed by Time (Commits/Time)
- Committed Source Lines of Code by Time (CommittedSLOC/Time) 
- Committed Characters by Time (CommittedChars/ Time)

Results:
- Assessing developer productivity via commit-based metrics is tricky. The eight interviewed leaders are unanimous in stating that commit-based metrics strongly dependent on developers’ commit habits; thus, these metrics are quite unreliable. Particularly, team leaders expressed their concern about being unfair with developers who commit less but produce more complex program features than other developers. Therefore, we have learned that using commit-based metrics to assess developer productivity is tricky in practice.
- Code ownership as a key to assessing developer productivity. Our results were encouraging for code-based metrics: all code-based metrics are strongly correlated with team leaders’ perceptions of developer productivity.
- To what extent code-based and commit-based can complement the team leaders’ perceptions of their developer’ productivity? In summary, our results suggest that productivity metrics, especially code-based metrics, can complement the subjective perception of team leaders. Important results: revealing aspects of developer productivity not previously known, boost the fairness of productivity assessment, and acknowledge those developers that are productive
but underestimated.


--------------

The Work Life of Developers: Activities, Switches and Perceived Productivity
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7829407

-  All too often, efforts aimed at improving developer productivity are undertaken without knowledge about how developers spend their time at work and how it influences their own perception of productivity. 
- Researchers have investigated work practices and work fragmentation in detail from various perspectives, specifically the effect of interruptions on fragmentation and how developers organize their work in terms of tasks and working spheres.
- We did find that many developers consider email, planned meetings and work unrelated browsing as less productive activities, and usually perceive themselves as more productive when they have a higher user input rate as measured by mouse clicks and keystrokes.
- Developers’ work is highly fragmented, as developers are spending only very short amounts of time (0.3 to 2 minutes) in one activity before switching to another one.
- Table of multiple findings, such as 'Developers only spend about half their time active on their computer.'.


--------------

Towards an evidence-based theoretical framework on factors influencing the software development productivity
https://link.springer.com/content/pdf/10.1007/s10664-020-09844-5.pdf

- To evolve and replicate a systematic literature review (SLR) on software development productivity measurement and prediction methods.
- Productivity has been studied at least for three decades.
- Despite the number of available empirical studies on software productivity, the researchers have faced issues in employing the produced knowledge and synthesizing a theoretical framework from them.

Table 6 summarizes the important findings:
- In general, as more significant the increments of product’s LOC-based size over time, as higher the positive impact on software development productivity.
- Newer programming languages positively contribute more to software development productivity than older ones.
- Communication among developers positively affects and is necessary for software development productivity.
- Combining the use of methods and techniques regarding verification, validation, testing, or any other related to quality assurance has positive effects on software productivity.
- The long-term effect of increasing the project duration promotes slight losses in software development productivity.


--------------



Motivation in the workplace to improve the employee performance
https://d1wqtxts1xzle7.cloudfront.net/54026295/improve_performance-with-cover-page-v2.pdf?Expires=1635166560&Signature=GEiJNzzVC-ms0y4j-ge2Cp4KrNZTrX9I5Vrmi0phN7zAahglM6epAiaTaLoGGNIp9l1qExN5yi-ZyXgyQPiCy8JdmgkcQAhRba1a~ABB-ONwRSSwt60Md3~h0nQFhjtVMsHK~mkwwiLotK5ZLz5STAvqRkEJXlPKjVJ77l9Vn-v-aGySE-gqkX2RczNQ5S-i2rzNaCxM~TXDzXRSDfW6b1EnZm6vBlcNXpTAV09z9ng0y4J3oWNl8bpKJSsbQtHqquYHoM875QEHZLdHKppaZpK4z98Y1RAToDKkuHd7NzgRvqSCfdHsMUymyooH5IwzSqwehn7maOVnqepgkTr7pA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA


- Most employees need motivation to feel good about their jobs and perform optimally, intrinsic or extrinisic
- Motivation through incentives(Bonusses)
- The link between performance and employee motivation is very complex. 
- Motivation is very important for every company to improve the employee performance and productivity of the organization. 


-------------------

An Example of Using Key Performance Indicators for Software Development Process Efficiency Evaluation 
https://courses.cs.ut.ee/MTAT.03.243/2015_spring/uploads/Main/KPI.pdf

- Schedule adherence: is everything on time?
- Assignment Content Adherence: ability to deliver full assignment scope by end of assignment.
- Cost adherence
- Fault Slip Through: measures the ability to capture faults before making deliveries.
- Trouble Report Closure Rate: answer TRs within time.
- Cost per Trouble Report: cost fixing TRs

---------------------

How have Software Engineering Researchers been Measuring Software Productivity? 
https://www.scitepress.org/papers/2017/63144/63144.pdf

- researchers have not yet reached a consensus on how to properly measure productivity in software engineering.
- Measurement of productivity is necessary to assess the efficiency of software organizations and improving it can lower cost(Demarco, 1986) and time-to-market (Boehm, 1987) + increases competitivity within market. (Aquino Junior and Meira, 2009) 

-------------------------------------

The SPACE of Developer Productivity
https://dl.acm.org/doi/pdf/10.1145/3454122.3454124

- developer productivity is necessary not just to improve engineering outcomes, but also to ensure the well-being and satisfaction of developers, as productivity and satisfaction are intricately connected.
- SPACE captures the most important dimensions of developer productivity.
- Dimensions are:
	- Satisfaction & well-being
	- Performance
	- Activity
	- Communication & collaboration
	- Efficiency & flow

---------------------------------

Rethinking Productivity in Software Engineering
https://drops.dagstuhl.de/opus/volltexte/2017/7359/pdf/dagrep_v007_i003_p019_s17102.pdf

- Industry and research are looking into understanding and improving the productivity of individual software developers as well as teams
- researchers and practitioners with backgrounds in Software Engineering, Human Computer Interaction, and Computer-Supported CollaborativeWork who are interested and working on topics related to the productivity of software developers as well as more general knowledge workers
- A lot of interesting talks regarding how productivity should be measured

------------------------------------
Happiness and the productivity of software engineers
https://link.springer.com/chapter/10.1007/978-1-4842-4221-6_10

- Software companies nowadays often aim for flourishing happiness among developers such as perks.
- happy developers are **supposedly** more productive and, hopefully, also retained.
- To access skills and knowledge (which are in term needed to increase productivity), there need to be favorable conditions that allow the human potential to be realized, satisfaction, and thus happiness, is important because it can realize this potential.
- Happy developers solve problems better (Graziotin, 2014).
- Happiness and unhappiness influence how we can focus while coding, as put by one participant: “[…] The negative feelings lead to not thinking things through as clearly as I would have if the feeling of frustration was not present.”
- Unhappiness leads to low motivation for developing software
- Issue with research on happiness is that it is challenging to control the happiness of people. 
- Software productivity is still often managaed as if it were about delivering code on an assembly line.
- Link between happiness and productivity is real and many companies are starting to invest in employees well-being.
- Happiness and unhappiness bring a plethora of benefits and detriments to software development processes, people, and products.

-----------------------------------------------

Tool for Measuring Productivity in Software Development Teams (misschien niet een hele goede voor ons research ding)
https://www.mdpi.com/2078-2489/12/10/396/htm

- Productivity management in companies has become increasingly crucial in an environment of external openness and globalization of business
- one of the main objectives in software development is to improve productivity, as organizations want to produce more software and, at the same time, reduce development costs.
- 

 -->
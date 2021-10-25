# Research title

_Niek van der Plas (5363780) & Mark Meijhuis (4389255)_

TL;DR: Short summary of the research idea. This should be a 4-5 sentences paragraph, containing the motivation of the paper, its goal, a bit of its research method, results, and implication.

## Introduction

The introduction should be 4-5 paragraphs, explaining the overall motivation and goal of the paper. 

* Explain the broader topic of research
* Explain the research gap: what are we missing?
* YOUR RESEARCH, YOUR GENIUS IDEA
* Put your main research question
* A summary of the research method


## Background and Related Work 

"Show off" your knowledge of the area; it gives all the background that the reader needs to understand your work; it gives an overview of the entire research area around the topic

* Write a background and/or related work selections
	* Background: Background knowledge that the reader needs
	* Related work: Papers that are related to your research and that the reader can use to compare with your work

* One paragraph per paper. Some sentences explaining what the paper is about. Some sentences explaining the methodology and results of the paper. Maybe limitations or future work. Maybe some comparison with the work you are doing.

* At least 10 papers in the related work section. Do not go over 15 papers.

## Research method

<!-- Controlled experiment where one group knows we are measuring their producitivity and one does not. -->
What you are going to research and how.

* State your research goal. "The goal of this study is to explore the relationship between sunlight and defects in open-source systems".
* What method are you doing to use? 
* Write down clear research questions (RQ1, RQ2, ...)
* For each RQ, describe the method you are going to use to answer the RQ
* Explain any datasets you are going to reuse or create. Why is this dataset the right one for your project?
* Explain any (human) subjects you are going to reuse or create. How are you going to find them? Why are they the right people to take part of your study?
* Explain any data analysis techniques you plan to use. Are you going to use some stastistical test? Which one? Why?

## Execution plan

How to run this study?

* How you would you then run this study?

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



Motivation in the workplace to improve the employee performance
https://d1wqtxts1xzle7.cloudfront.net/54026295/improve_performance-with-cover-page-v2.pdf?Expires=1635166560&Signature=GEiJNzzVC-ms0y4j-ge2Cp4KrNZTrX9I5Vrmi0phN7zAahglM6epAiaTaLoGGNIp9l1qExN5yi-ZyXgyQPiCy8JdmgkcQAhRba1a~ABB-ONwRSSwt60Md3~h0nQFhjtVMsHK~mkwwiLotK5ZLz5STAvqRkEJXlPKjVJ77l9Vn-v-aGySE-gqkX2RczNQ5S-i2rzNaCxM~TXDzXRSDfW6b1EnZm6vBlcNXpTAV09z9ng0y4J3oWNl8bpKJSsbQtHqquYHoM875QEHZLdHKppaZpK4z98Y1RAToDKkuHd7NzgRvqSCfdHsMUymyooH5IwzSqwehn7maOVnqepgkTr7pA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA


- Most employees need motivation to feel good about their jobs and perform optimally, intrinsic or extrinisic
- Motivation through incentives(Bonusses)
- The link between performance and employee motivation is very complex. 
- Motivation is very important for every company to improve the employee performance and productivity of the organization. 


-------------------

An Example of Using Key Performance Indicators for Software Development Process Efficiency Evaluation 
https://courses.cs.ut.ee/MTAT.03.243/2015_spring/uploads/Main/KPI.pdf

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



 -->
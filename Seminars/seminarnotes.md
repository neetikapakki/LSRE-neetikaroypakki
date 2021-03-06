SEMINAR 0

HOMEWORK QUESTIONS
LARGE SCALE REQUIREMENT ENGINEERING

Any large organisation needs an efficient RE process where the number of new requirements increases whiles the management resources cannot be increased accordingly.  The RE process is often described as cyclic with each cycle consisting of elicitation, analysis and validation activities [1] [2]. Large scale requirement engineering (LSRE) is defined based on the size of the requirements set that is considered in the market driven requirements. Generally in large scale requirement engineering the order of magnitude exceeds 1000 requirements. Managing a complete set of interdependencies in LSRE is practically unfeasible, but feasible among small bundles of requirements [3].


There are many challenges that are identified in LSRE. Few of the challenges are listed below:
1.	Complex dependencies between requirements
2.	Cost estimation
3.	Requirements prioritization
4.	Finding right balance between selecting commercial requirements and internal quality requirements.
5.	Uncertain environments
6.	Resource allocation
7.	Handling of multiple customer or the stackholders

References:

[1]	S. Aaramaa, T. Kinnunen, J. Lehto, and N. Taušan, “Managing Constant Flow of Requirements : Screening Challenges in Very Large-Scale,” pp. 123–137.

[2]	L. N. Æ. P. A. Swatman, “Managing the requirements engineering process,” pp. 55–68, 2003.

[3]	B. Regnell, R. B. Svensson, and K. Wnuk, “Can We Beat the Complexity of Very Large-Scale Requirements Engineering ? 2 Orders of Magnitude in Requirements Engineering.” SEMINAR 0 
HOMEWORK:
The order of magnitude in RE is based on the size of the sets of requirement that are handled by the organization in developing a software intensive system [1]. The order of magnitude also relieves the effort that is required in managing the complete sets of interdependencies of the requirements.  

The order to magnitude in RE are categorised in 4 levels.

Level 1 - Small scale requirement engineering (SSRE)

The order of magnitude (or) the number of requirements the organisation can handle is: 10

Effort required: less effort 

Level 2 – Medium scale requirement engineering (MSRE)	

 The order of magnitude (or) the number of requirements the organisation can handle is: 100

Effort required: managing the set of requirements at this level is feasible but requires large effort.  

Level 3 – Large scale requirement engineering (LSRE)

The order of magnitude (or) the number of requirements the organisation can handle is: 1000

Effort required: practically unfeasible but feasible among small bundles of requirements.  

Level 4 – Very large scale requirement engineering (MSRE)

The order of magnitude (or) the number of requirements the organisation can handle is: 10000

Effort required: Managing a complete set of interdependencies among small bundles of requirements is unfeasible in practice.


SEMINAR 0

ARTICLE “The art and science of release planning"

Through this paper, the author has expressed his views on what a release plan means, difficulties faced in creating a release plan and the different types of approaches to release plan. Release planning helps in decision making for selecting features and assigning them in order to create a sequence of consecutive products release. Creating a release plan is not an easy task. A proper understanding of the planning objectives, constrains and important stakeholders and the feature preference is necessary. RP rarely relies on a popular model or methodology. Optimal selection and selecting features involve the rise of the complexity factor. More time is consumed for planning and follow up re-planning is being practised.
There are two kinds of approaches to the release planning.

1.	The art of release planning approach: This approach is involves the human intelligence in handling the conflicting objectives and constrains.
2.	The science of release planning approach: This approach deals the problems by formalizing them and use computational algorithms to obtain the best solutions.

The art of release planning approach:
 As the RP is not well defined and there is an organization’s lack of emphasis in the processes due to the lack of maturity in the RP process, it involves human intuition, communication and capabilities to solve the problem before seeking for its solution. In agile development, RP concentrates on planning on the next iteration which is done by conducting physical meetings among the most important stakeholders in order to discuss which features to be developed next and the effort calculation for those features. However RP fails to work well in deciding features and to prioritise them when large number stakeholders are involves in the agile development.

The science of release planning approach: 
In this approach by trying to formulating the problem approximately so that by working on this formulized problem, we can get the meaningful result. Different optimization approaches are modelled that helps in working on the features that satisfies the customer need within the given budget. These optimization approaches are most suitable for large size problems but somehow fails to give the costumer a chance to take part in the RP decisions and also they don’t plan beyond a single release. Decision variables are also considered that focuses on the set of new functionality, costumers’ change request, or defect correction and the features are assigned to a finite number K of release option. This approach also deals with the two types of dependency constrains C (coupling relation) and P (precedence relation), where coupled features are to be released jointly as they depend on each other and the precedent feature are released in a specific order. As all resources play an important role in the RP, while discussing and calculating the resources constrains, constrains that are related to budget and effort resources are taken into consideration.  As not all the stakeholders hold the equal importance, a scale that measures the importance level of each stakeholder is considered and is calculated in order to identify the most important stakeholders. Features are prioritised based on the values and urgency by using an ordinal nine point scale. An equation is formed by making certain assumptions that helps in forming a balance way of the planning objectives that includes aspects such as value, risk, urgency, satisfaction, dissatisfaction and return on the investment.
This paper also discuss about the hybrid approach based on integer linear programming. The algorithm adopted in this approach helps in solving the sequence of linear programming problems without integer conditions after which the problems are well understood and solved efficiently. To generate a set of good solutions, this approach is combined with heuristics. Though this approach, the set problems as variants of the original formal model are formulated after which the problem variants are solved in order to get a set of qualified alternative solutions. Since there is a coping problem in both art and science base approach, this hybrid approach offers a high level framework stressing on the continuous process that works on planning and re-planning.  Different tasks are performed in the three phases to improve this approach during the planning process.
Modelling phase:  The main activities in this phase are planning objective and constrains, offering stakeholder voting and estimation of resources.
Exploration phase: Algorithms are developed on integer programming to find out the solution space and generate alternative solutions.
Consolidation phase: Algorithms are developed that helps the decision makers to understand the problem better. The decision made after solving the problems, help in reducing the size of the problem and the complexity for the next iteration. At the end of the paper, a problem is considered as an example and the solution process is discussed.


SEMINAR:0 HOMEWORK
summary for the article “A market-driven requirements engineering process:results from an industrial process improvement programme”.
Basic idea of this paper: an improvement program REPEAT is developed that helps the improvement in release precision and product quality by considering the elements such as prioritisation of requirements, the effort estimation, the detailed requirements specification, and the continuous change management throughout design, implementation and verification that are used in the REPEAT.  
This paper focuses on the requirement engineering processes used in package software companies. REPEAT (Requirements Engineering ProcEss At Telelogic) is used in- house at telegolic(a fast growing company) for extracting, selecting and managing the requirements on a product family called telelogic tau which is a software development environment for real time systems that uses graphical languages and provide code generator for integrating several real time operating system and is used by large telecommunication systems providers in their software development. REPEAT manages the requirements throughout the release cycle by including activities such as elicitation, selection, management, documentation and validation and release planning of the requirements. There are different actors involved in REPEAT such as Requirements Management Group (RQMG), issuer, customer and developer, requirements team, construction team, test team, experts, requirements database. The elicitation of the requirement is a continuous process and the issuer issues a requirement at any time based on the market need. The requirements are stored in the database with a unique identity so that in the REPEAT process each requirement has a life cycle processing through different stages. With the support of the experts, the RQMG decides on requirement transitions on the states such as new, assigned, classified, rejected, selected and applied. There are different phases involved in the process of REPEAT such as;
Elicitation phase: in this phase the issuer collects the requirements and reasons for selecting that requirement along with its description is also given and is given an initial priority P.  These requirements are checked by the RQMG and sent back to the issuer for more clarification purpose of the requirement description. Then the experts classify the requirements to cost C and Impact effort estimation. If the effort is more than it is estimated, then the requirement is decomposed to smaller requirements considering the cost impact and the priority of the requirement.
Selection phase: this phase involves activities such as selecting the requirement to be implemented in the current release, specifying the selected requirements in more detail and validating the requirement document. 
Change management phase: based on the priority, the RD changes and when this happens a new requirement enters to the starting phases of the REPEAT process.
Construction: this is made by using a iterative design and implementation process and unit test 
Conclusion phase: final report is written which summarise the lesson learned in the REPEAT enactment.
Verification: The implemented requirements that are in the selected list are verified against RD using requirements-  based testing method
After this a partial process scenario model is designed that shows the event related to one requirement. And at the end of this paper, challenges such as over load control, connection fragment, cost value use case prioritisation etc were identified that are occurred while implementing REPEAT.

SEMINAR 0
HOMEWORK ARTICLE 

“Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model”

This paper highlights the importance of finding the right balance among competing quality requirements for market success.  For this purpose a model is developed that uses quality dimensions with addition to the cost and value dimensions while prioritizing the functional requirements. This paper presents a quality performance (QUPER) model which supports release planning and road mapping of quality requirements and it also presents one case of QUPER tailoring, implementation, and most important evaluation, conducted at Sony Ericsson. The main purpose of this is to investigate the implementation of QUPER in industry. This model involves three steps.

Step1.  Problem definition

Step2.  Model definition

Step3. Model validation

In the first step, the understanding of different requirement decision scenarios is done along with the identification of the need for a cost-benefit model including quality aspects to support road mapping and scoping.

The second step is based on the inputs of the first step. This step includes three kinds of view (QUPER benefit view, QUPER cost view, QUPER roadmap view)
In the QUPER benefit view, three breakpoints that indicate the principal changes in the benefit level with respect to experience and market value. A breakpoint is an important aspect of non-linear relation between quality and benefit. The three breakpoints are listed below:
a.	The utility breakpoint: represents the border between a quality level useless and useful quality.
b.	The differentiation breakpoint: represents the shift from useful to competitive quality, which makes them have a competitive market proposition.
c.	The saturation breakpoint: breakpoint imply a change in quality level from competitive to excessive quality, where higher quality levels have no practical impact on the benefit in the particular usage context considered.
In QUPER cost view, the notation of cost barriers that represents the non-linear relation between quality and costs is included.
In QUPER roadmap view, combines benefit and cost views by position the breakpoints and barrier together ordered on the same scale.

In the third step the evaluation of the model which is generally carried out through interviews and expert decisions is included.
All the above three steps are carried out in Ericsson by considering only benefit view since it is the most important part of the QUPER model. This implementation process is done in four steps:
1.	Define quality aspects.
2.	Estimate your product’s current quality and the competing products’ quality.
3.	For each quality aspect and for each relevant qualifier, estimate the breakpoints.
4.	Estimate candidate targets and discuss and decide on actual targets for coming releases.

Later in this paper a detailed description of practical application of QUPER model by conducting interviews and involving experts of the company. The results indicate that the quality performance model provides helpful information about quality requirements in release planning. And also the main identified challenge was difficulties to identify and specify the values for the differentiation and saturation breakpoints. Furthermore, different understanding of the breakpoints value among the staff was raised as a challenge.

SEMINAR 0 

HOMEWORK ARTICLE

“A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”

Quality requirements are seen as a key competitive advantage. This paper discuss about the QUPER model that was developed with the aim to support high-level decision-making in release planning of quality requirements. According to many surveys, QUPER is the only method which addresses quality and cost constraints of QR. This paper discusses about the guidelines of how to apply QUPER model in practice with an illustration of QR, added step which includes how to incorporate cost dependencies between quality requirements and two evaluations of complete version of QUPER model which helps to evaluate QUPER’s applicability.
 
 There are two main factors motivated the creation and evolvement of QUPER model;

a.	A direct need identified in industry

b.	A suitable model was not found in the literature, i.e. a model for supporting release planning of QR

The reason for adding the cost dependency step is because dependencies may have a major impact on the estimated cost for other QR. The cost to improve the quality level for one QR may imply an improved level of quality for other QR. This may lead to a change of other QR cost barriers and which QR to select for the coming release. Therefore, it is important incorporate a cost dependency step in the QUPER model. 

Application of QUPER model is presented in 7 steps by considering an example of quality requirements of a mobile TV

1.	Identify candidate QR: It is important to identify relevant features, market segment, competitor, and hardware platform capability. After the identification of the factors, the consequences for the particular QR should be considered.

2.	Define scale and unit: For the selected QR, a scale and a measurement unit that can be used to express the level of quality of QR should be defined.

3.	Identify reference levels: For each QR, it is important to identify reference levels based on actual products. Reference levels can be based on competing as well as own products.

4.	Elicit quality breakpoints: When all reference levels have been identified, for each QR, the market expectations should be defined in terms of the values of quality breakpoints.

5.	Estimate cost barriers: When market expectations have been identified, for each QR, estimate the cost in terms of the values of cost barriers.

6.	Set candidate requirements: in this step the estimations are made, propose candidate requirements, discuss and decide actual requirements for coming releases, where estimates can be given in three forms.

a.	With both a Good target and a Stretch target. 

b.	 With only a Stretch target, which means the highest value is specified. 

c.	 With only a Good target, which means the lowest accepted value is specified.

7.Identify cost dependencies: If cost dependencies among QR are considered important to identify for cost estimations, then, for each top-n QR, identify which modules that needs to be changed if that QR is to be improved beyond the ”next” breakpoint.

With the help of these steps, explanation of a practical view of QUPER model is given with the help of figures. 
In the later sections of this paper, the evaluation methodology of QUPER as it was evaluated in industry with a case company by finding out the answer for the research question that states “What are practitioners’ views on the utilities of QUPER extended with guidelines including domain-specific examples?” after the collection of the results we can gain the practical knowledge of applying this model and also helps to understand the problems that may arise while applying this model practically.

While comparing both the articles i.e. “Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model” and “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”, it was found out that the authors of both the papers has considered the quality requirements and have show practical results of the implementation of the QUPER model but in one paper the author has also included the cost dependencies among the quality requirements.

SEMINAR 1:
HOMEWORK QUESTION

Road mapping:
A roadmap is a strategic plan that provides the steps an organisation needs to take to achieve stated outcomes and goals. It provides vision to the links among tasks and priorities for action in the near, medium and long term. Metrics and milestone provided by the roadmap allow the organisation having a regular tracking of progress towards the goals.
There are specific key elements of a successful roadmap:
 
  A roadmap will contain a clear statement of desire outcome that follow a specific pathway for reaching the goal. The pathway contains the following:
  
1.	Goals: A clear and concise set of targets that, if achieved, will result in the desired outcome; quantified goals.

2.	Milestones: the interim performance targets for achieving the goals, pegged to specific dates.

3.	Gaps and barriers: a list of any potential gaps in knowledge, technology limitations, market structural barriers, regulatory limitations, public acceptance or other barriers to achieving the goals and milestones.

4.	Action items: actions that can be taken to overcome any gaps or barriers that stand in the way of achieving the goals; typical solution actions include technology development and deployment, development of regulations and standards, policy formulation, creation of financing mechanisms, and public engagement.

5.	Priorities and timelines: a list of the most important actions that need to be taken in order to achieve the goals and the time frames, taking into account interconnections among those actions and stakeholder roles and relationships.

IVA
Internal Value analysis is a technique to measure whether a product is following the proposed strategy by meeting the product line at every stage by considering limited resource such as cost, time, risk and knowledge. 
References 
[1]   T. Gorschek and A. M. Davis, “Requirements engineering: In
search of the dependent variables,” Inf. Softw. Technol., vol. 50, no.
1–2, pp. 67–75, 2008. 

SEMINAR 1 HOMEWORK:

Gap analysis:

This analysis mainly focuses on what the business is doing currently and where it wants to reach. This analysis is carried out by identifying the gaps by the process of comparing the actual performance with the desire performance. In order to perform the gap analysis, it is important to understand the expectation level of the performance in a company so that comparison of the current performance level with the expected performance level is done.

This analysis can be performed at the strategic level and the operational level.

It provides the company/ organisation with a foundation for measuring investment of time/ money/ human resources required to reach the desire goal.

This analysis can be used as a ranking of good, average and poor.

Planning gap is the process of comparing the forecast profits to the desire profits of the company. Planning gap is divided into two main elements:

1.	Usage gap:  This is the gap between the total potential for the market and the current usage by the consumers in the market.
            Usage gap= market potential – existing usage

2.	Product gap: A particular organisation is removed from the part of the market because of product or service characteristics.   

Gap process includes the following steps:

1.	Identifying the existing process: it is important to know what process/ method the company/ organisation is using.

2.	Identifying the existing outcome: to identify the current status of the outcome that the company is producing.

3.	Identifying the desire outcome: to identify what the company/ organisation wants.

4.	Identifying the process to achieve the desire outcome: to identify the procedure or the process that the company/ organisation uses to achieve the desire outcome.

5.	Identify and document the gap: to find the difference between the current outcome and the desire outcome.

6.	Develop the means to fill the gap: develop and using the correct tools or techniques required to fill the gap and reach the desire goal.

7.	  Develop and prioritise the requirements to bridge the gap.

SEMINAR 1 
HOMEWORK ARTICLE 4

“A cost-value approach for prioritizing requirements”

Authors argue that for a software project meeting needs and expectations of stakeholders is important to go ahead in a competitive world. In order to achieve this objective, an accurate management of stakeholder’s system requirements has to be done. It is a difficult task to decide the requirements and it is even important to consider time and budget constraints. Despite the fast growth of the research in requirements engineering, many managers of different companies still do not have idea about effective and industrial proven techniques for prioritizing. 
Requirement prioritization help companies to make acceptable trade-offs among conflicting goals (quality, cost and time-to- market) and to allocate resources based on importance of requirements to their project. 
Therefore the authors have developed an analytical tool for prioritization based on cost-value approach. This tool ranks the candidate requirements based on their value to the customers and on their estimated cost of implementation. This method is also implemented successfully in two telecommunication software development companies.
Cost value approach:
This approach help to make prioritization simple and straightforward giving out accurate and convincing results. Requirements prioritization is done according to their corresponding cost and value figures. Here cost is the cost for successfully applying candidate requirements where cost is calculated in terms of currency by many developers. The candidate requirements are investigated through Analytic Hierarchy Process (AHP) which compares the requirements pair wise according to their relative cost and value. Pair wise comparison is chosen because it includes redundancy and is sensitive to judgemental errors. 

Prioritization of requirements using cost-value approach includes five steps.

1. First the requirements engineers review all the requirements carefully to ensure that they are stated in an unambiguous way.

2. Customers and users apply AHP’s pair wise comparison to assess the relative value of candidate requirements.

3. Relative cost of each candidate requirement is estimated by experienced software engineers using AHP’s pair wise comparison.

4. Then the software engineers use AHP to calculate relative value and implementation cost of each candidate requirement and plots these values on a cost-value diagram.

5. Stakeholders use this diagram as a conceptual map for analysing and discussing the requirements and based on this discussion, software managers prioritize the requirements and decide which requirements should be actually implemented. 

Case study 1 (RAN project):

The authors’ goal for this project was to identify and specify requirements for a system that would give managers information about mobile telephony system operation. They identified 14 high-level requirements that would give managers information about quality, coverage and capacity of mobile communication system. These requirements were defined by authors and managers reviewed and agreed them. . A group of experienced project members are asked to represent customer’s views and carefully instructed them on prioritizing requirements, making pair wise comparisons carefully. The project manager explained each requirement and discussed it with all the participants of the project to be clear. Then pair wise comparisons were done based on the value and cost estimates. When all 14 requirements had been pair wise compared, value distribution and the cost distribution are calculated, as well as the consistency indices and ratios of the pair wise comparisons. Based on the distribution results, the candidate requirements are presented in a cost-value diagram and results were presented to the managers. Analysis is performed with the help of cost-value diagram which provided requirements selection.

Case study 2 (PMR project): this case study was done by the same authors having base on cost-value approach in the RAN project. The Performance Management Traffic Recording project is selected and cost-value analysis is applied for prioritizing the requirements for fourth release. The requirements are divided into three categories basing on those: demanding traditional defect correction, requiring performance enhancement and suggesting added functionality. The authors decided to prioritize only those suggesting added functionality as both the customers and project managers agreed to it that all defects had to be corrected and performance had to be enhanced. 11 high level functional requirements are made and 55 pair wise comparisons respectively. This approach can produce software system with substantial customer satisfaction at a significant reduction in cost.
In my opinion, this approach is suitable in prioritizing requirements for the projects which have less number of requirements. This approach does not consider interdependencies so it may be a disadvantage to apply it in large scale requirements engineering. It also have few advantages and can be implemented in large scale requirements engineering if it consider interdependencies.

SEMINAR 1

HOMEWORK  

ARTICLE 3

 “Requirements Engineering. In search of dependent variables”

In this paper the authors presented a framework of dependent variables that helps in most of the requirements engineering quality assessment. In many companies assessment is based on two main factors: 

•	The requirement process which have measurement of time and resources consumed.

•	The primary product such as measurement of the quality of software requirements.

But researchers’ pointed out that performance of either one or both of these tests is not necessary to be successful. Most of the efforts are performed with little concern improving the projects. In most of the cases engineers attempt to change their processes with a hope of achieving expected outcome. Dependent variable can vary from shortest term to longest term. Deciding the right dependent variable for a particular case is a major consequence. Hence to eradicate this gap, the authors presented a frame work of dependent variables which serve as a base for quality assessment of requirements engineering. As a change in requirements process occur we can observe their impact on dependent variables till five distinct levels.

Requirements phase: this level include dependent variables that relate to requirements cost, time and quality. 

Project: this level consists of information whether the project was completed on time, within budget, reached all the specified requirements and also include project cost, time, estimates and degree of requirements change.

Product: dependent variables within this stage determine the degree of product success. This level includes dependent variables that relate requirements selection and degree of impact.

Company: measures such as portfolio management, strategic alignment and degree of impact. 

Society: A project that contributes to a company’s bottom line but pollutes the environment or kills people must be considered as a failure. Include positive and negative externalities.
This paper includes summary of previous research on measures at all the five levels by which this article contribute as a reference for research performed in this area. Major contributions of this paper include:

1. It creates a clear classification of levels so that the impact of changes in RE process can be assessed.

2. It suggests that product strategies should reflect long term goals, but these goals also have to be aligned to both current market and technology trends.

3. It increases awareness that the strategies used must be stated explicitly and all the requirement engineers should be aware of this.

4. It exposes the fact that at higher levels in the taxonomy, we need to recognize that impacts are multidisciplinary and multi-perspective.

All these contributions serve the companies to take care of the dependent variable at the time of requirement engineering process changes are made and serves as a reference as it presents a clear frame work of all the variables in different views.


SEMINAR 2 HOMEWORK:
BOSTON MATRIX:
Boston matrix that is developed by Boston Consulting Group (BCG) is a marketing tool that analysis and manages the product portfolio which helps the investor to decide on which product he/she has to invest. 
Functionality of this tool:
This tool classifies the products in four categories based in the market share and the market growth.

1.	Dog: The products that are in dog category have low market share and low market growth. This means that these products do not consume nor will they generate much cost.

2.	Cash Cow: the assets of the products are much higher than the market growth in this category. So they generate most income then that is consumed.

3.	Question mark: these are the product that consumes large amount of cash by providing a high growth in the market and as they have low market share they don’t generate much income. These products can be places in the star category if the market share rises and also can be placed in cash cow if the market growth is slow.

4.	Star: these products produce and consume large amount of cash because their market growth is high and at the same time its market share is equally high. When the market growth falls for these products, they will become cash cow.



SEMINAR:4 HOMEWORK

Some of the tools that are available for the requirement management are listed as follow:
The tool for requirements management is used to manage the process steps “requirements analysis, allocation and flowdown and allocation of verification attributes”[1]. We also use requirement tools to prioritize requirements for testing process and also to store rquirement statements and the information about the requirement attributes. the requirements management tools work on maintaining the consistancy of the requirements, identifying undefined or missing requirements and also to trace through all levels of requirements. There are many requirement tools available. Few of them are listed below that were refered in some articles [2][3].

1.	Rational Suite Analyst Studio (Use CaseModeling).
2.	Telelogic DOORS
3.	Starbase Caliber-RM
4.	RDT 3.0
5.	RTM Workshop 5.0
6.	CORE Enterprise
7.	Vital-Link
8.	XTie-RT
9.	SLATE
10.	icCONCEPT-RTM
11.	RequisitePro
12.	Caliber-RM
13.	RDD-100
   

Tools for agile requirements management:

1.	Trace cloud
2.	agileSpecs
3.	Agile Designer
4.	Agile Tailoring Tool (ATT)
5. IceScrum
6. Agilefant


 

SEMINAR 1:

HOMEWORK ARTICLE:

“Quality Requirements in Industrial Practice – an extended interview study at eleven companies”

This paper focuses on the importance and analysis of QR in different companies.
Data collection area:
The data is collected by carrying out a semi structured interview which is conducted to the one project manager and one product leader each from 11 different industries that are selected by the gate keeper of corresponding industries that examines QR in practice. The collected data also includes the perspective of comparing B2B and B2C analysis which presents new data from all 11 cases.
4 RQ’s where formed and analysis of QR in related to each of the RQ is done by interviewing the 22 participators of 11 companies from various perspectives.

RQ1: What QR’s are considered most important and are there any distinguishably characteristics in relation to costumer type (B2B or B2C)?

RQ2: What interdependencies between QR are present in the companies?
	
	RQ2.1: What interdependencies are deemed most important, and how does this compare to the previous studies?
	
	RQ2.2: To what extent are interdependencies elicited analysed and documented?

RQ3: How are cost estimations of QR are performed, and what is the accuracy of these cost estimates?

RQ4: To what extent are QR dismissed from the project after project initiation?
	
	RQ4.1: If QR‘s are dismissed, is any consequences analysis performed pre– post dismissal?
	
	RQ4.2: Are RQ’s are specified in a measurable manner?

In relation to RQ1, for the findings the researchers have considered few Quality requirements such as usability, performance, reliability, stability and etc and researchers have tried to found out which requirement is considered most important. For B2B usability is considered most important and for B2C safety is considered most important. Depending on the company type the researchers enable to focus on certain quality aspects. Not all QR’s are given the same importance in all the companies. Each requirement is given different priorities based on the type of company and its specifications. Aimed approach could be one of the solutions in handling the different types of requirements in different types on companies.

In relation to RQ2 a set of six predefined interdependency types (AND, REQUIRES, TEMPORAL, CVALUE, ICOST, OR) were used by the interviewees to characterize perceived interdependencies, both among different QR and interdependencies between QR and FR. TXOR (time related exclusive) is an additional interdependency a  interviewee added  when given an option to add any additional interdependencies. The findings for RQ2, interdependencies, show that:

1)	REQUIRES and CVALUE are considered as the most common and important interdependency types to identify.

2)	B2B viewed REQUIRES as the most common and important one, B2C considered CAVLUE.

3)	AND and OR were considered the least common and least important interdependency types.

The reason for dealing with interdependencies is a complex task and the number of potential dependencies may be very large, resulting in an ad hoc approach to interdependency management where only a limited set of critical interdependencies are dealt with. Interdependencies can have a critical impact on product development in terms of planning, design, and quality. One of the interviewee stated that QR are assumed and so not actively looked for whereas another employee stated that the main focus should be on the functionality that will fulfil the customer needs and not on reflecting over QR. Moreover after the complete analysis, five of the companies reported that the order of implementation is affected by interdependencies where as the other company reported that delays or exclusions of requirements may be the result of QR interdependencies, which also affects what is implemented. The rest companies stated that the quality of the product is affected, e.g., performance and maintainability.

In relation to RQ3, cost estimation of QR, the findings show that:

1. There is no distinction between FR and QR during cost estimation.

2. Expert opinion is the predominant method for estimation.

3. In the worst case, B2B has much more inaccurate estimates than B2C.

 It is important to estimate the QR which is related to the impact of the entire system and span over all FR because this will make it difficult to estimate cost accurately. The major reasons for inaccurate estimates of requirements are overoptimistic estimates and user changes or misunderstandings. Therefore, it is important for practitioners to understand that estimates of QR demand a deeper analysis, and using the same resources and methods for QR and FR may not provide accurate estimates.

The findings for RQ4, dismissal of QR, show that:
At many cases there is a disagreement between the PM and the PL of the same companies in the issue related to the view of how often QR are quantified. In some cases the PM views differed, stating always or never. Almost in all the companies the views of the PM and the PL were quite different. This is due the communication gap between the PM and the PL. The analysis shows that:

1.	All QR are dismissed from the projects at some stage during development, with little or no consequence analysis performed.

2.	For B2C, performance requirements are more often dismissed due to the difficulties in proper estimation, while for B2B, QR that are not considered important, for example, usability, are more often dismissed than performance requirements.

3.	Poor cost estimation and the fact that QR has lower priority than FR are the main reason for dismissal.

It is important to acknowledge the participator about the importance of QR needs not only in theory but also in practice. It is important for them to understand and accept the fact that the dismissal of the QR may solve a short term problem but on a long term basis it will reduce the competitive advantages and the value of the system. To lower the dismiss rate of QR by improving the specification and quantification of the more difficult ones, it may be easier to keep them in the project instead of dismissing them when running out of time. However, the main problem is that QR are not taken into consideration during product planning and thus not included as hard requirements in the projects, making the realization of QR a reactive rather than a proactive effort. Product management may thus not be able to plan and rely on QR to achieve competitive advantages.

SEMINAR 1

HOMEWORK ARTICLE

“A method for early requirements triage and selection utilizing product strategies”

This paper measures an efficient and effective method that deals with the overload of the large number of requirements on a development organisation in case of market driven product development. Method for early requirements triage utility product strategies (MERTS) is built based on the needs in industries. This paper includes the evaluation of effectiveness and efficiency through controlled experiment in lab environment with 50 software engineering graduates as subjects. Evaluation is done by comparing MERTS with NL, natural language format. The authors of this paper argue that the requirements in market driven requirements engineering in contrast to traditional requirements engineering, come from internal sources (like developers, marketing, sales teams and bug reports) and also from external sources (different users, customers from different and multiple market segments and competitors) which results in large and continuous flow of requirements. It result to over load development organizations. For a company to reach the optimal strategy, all factors like selection, scalable, accuracy and cost effective way of selecting the requirements must be considered. In order to achieve this all the technical experts both middle and strategic management have to share a common vision. This need can be achieved by a method for Early Requirement Triage and selection (MERTS) which combine both strategic and technical perspectives for the formulation of product strategies. MERTS has two main purposes: 

1. It acts as a stepwise guide to create product strategies taking both technical and strategic views into account.

2. The strategies resulting from MERTS can be used by project managers to efficiently perform requirement triage and requirement selection in a reasonable amount of time.

MERTS background:

MERTS is centred on ensuring that the five strategic questions for a product are answered explicitly. The project managers using this method should follow three parts. Each part has several steps.

Part 1- Early requirement Triage: It provides steps to create an initial product strategy for use in requirement triage.

A. Specify: Includes specification of the directions of movement for the product deduced from the organisations’ mission statement. 

It includes answers for three strategic questions:

1. Where we want to go? 

2. How to get there?

3. What will be done?
for each product. The output of this step is a detailed understanding of goals and objectives associated with a specific product.

B. Assign weights: The answers from step 1 are assigned weights. The weights are assigned to each of the factors based on their relative importance. 

C. Compare requirements: Total weights of all requirements are compared against a threshold to select or reject each of the requirements.

Part 2- Requirements selection for release: After the identification of set of requirements, the next step is when to get there. This can be achieved through 

(i) Specification of product technology road map

(ii) Estimating resources        

 Part 3- Strategic Rationale: Once the strategic questions have been answered, reasoning behind the decisions should be documented.

In order to implement MERTS, requirements need to be comparable to the formulated strategies.

Experiment: the experiment was conducted in an academic setting, 50 engineering graduates of BTH taken as subjects. The aim of the experiment is to compare efficiency and effectiveness of MERTS with NL format. Subjects are divided into groups as one having product strategy in NL format and another in MERTS format. Each subject was given either NL or MERTS format. Each subject was given either NL or MERTS formatted strategy and detailed goals for new version of a mobile gadget targeted for entertainment oriented users in Asian market. Each requirement in the set has at least two levels product and feature, and also divided into functions and each requirement was formulated using attributes like unique id, product level requirement, feature level requirement, function level requirement, component level requirement. Hence this represents the requirements abstraction model. Applicable validity threats such internal, external and construct are also addressed in this experiment. The results of the experiment stated that MERTS is highly remarkable than NL when compared in terms of strategy formulation and utilization for the purpose of requirement triage. But MERTS have a drawback and it seems to be more resource intensive to use. This model takes more time but avoids errors and is a systematic method for thinking and to make decisions which miss with strategies. 
  
SEMINAR 3
HOMEWORK ARTICLE

“What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting”

The change in the decision on which feature or requirement has to be added or removed from the developing system depends on the change in the circumstances and demands for future improvement of the system.  This may cause dynamic evolution of the scope of software asset investments. In order to solve this problem, the researchers have presented a technique called Feature Survival Charts for visualization of scoping change dynamics. It is not practically possible to consider large number of requirements, so it is important to select a subset of requirements that can be useful for the upcoming improvement of any specific system. This process of selecting the requirements is called scoping. The proposed set of scope tracking measurements complements the proposed visualization technique, and they aim at further increasing the understanding of the rationale and dynamics of scope changes. The visualization technique provides feedback about ongoing scoping activities as well as a visualization of past project scoping activities. In scope tracking measurement the questions were formulated related to the external attributes of the scoping process which also connects to the internal attributes. The set of five scope tracking measurements is divided into time related measurements and feature related measurements are mentioned below.
Number of positive and negative scope changes per time stamp/baseline (M1) – This measurement comes under the 
Time to feature removal (M2)
Number of state changes per feature (M3)
Time to birth (M4)
Reason for scoping decision (M5)

For the purpose of scoping decision, the measurements discussed complement the visualization technique by quantitative characterization and qualitative rationale. The practitioners have highlighted the usefulness of the visualization technique and the scope tracking technique since they confirm the volatility of the scope and provide a tool to analyze the various aspects of this phenomenon. Case companies have use this results to adjust the process of scope setting decision more flexible. The results give a better overview of the scoping process of the whole project on a single page size graph. This method can be used in large scale projects and also if the characteristic of the scope changes, the manner in which the graphs together with measurements are used to increase the understanding of the performance of the scoping process is generally applicable.
Limitation:
1.	One threat is related to the mapping between measurements and external attributes.
2.	Another threat is related to the generalization of the results.




SEMINAR 1 HOMEWORK QUESTION

Continuous Integration:

Continuous integration is a process in which developers integrate code into shared repository several times in a day in order to reduce the risk factor  

Tools used for continues integration are as follow:

1.	Jenkins

2.	Buildbot

3.	Travis CI

4.	Strider

5.	Go

6.	Integrity  





SEMINAR 1
HOMEWORK ARTICLE

“Requirement Abstract model”

Requirement abstract model (RAM) mainly focuses on the product perspective, supporting a continuous requirement engineering effort, aimed at taking requirements of multiple types (abstraction level) as input, and offers a structure for the work-up of these requirements, i.e., breaking down abstract requirements into detailed ones and vice versa.

This model involves three steps.

1.	Specify:

This involves specifying the initial requirements and eliciting information to an extent of it being understood by the project manager performing continues requirements engineering. This step includes four attributes;

a.	Description: this attribute describes the centre essence of the requirements.

b.	Reason/ benefits/ rationale: this attributes consist of 2 parts. Why the requirements are specified and benefits of the requirements specified. 

c.	Risk: this attributes describes the risks with the requirements that are not specified.

d.	Title: this attribute should reflect the content of the requirement.   

2.	Place:

 This step analyse the requirements and place them in the level they belong. There are four levels: product level, feature level, functional level and the component level. In product level, the main focus will be on the goals, product strategies and indirectly on the organization strategies. Requirements which are features of the product are placed at the feature level. Features are characteristics of the system; requirements at this level provide abstract descriptions of these characteristics. At the functional level each requirement is described in such a way that it clearly shows what a user or system can do. In the component level the Requirements will have detailed information. Component Level can also act as clarification to one or more Function Level requirements.

3.	Abstraction:
This step involves abstracting and/or breakdown of a requirement, depending on the initial placement of the original requirement. New requirements are created on adjacent abstraction levels or linking to already existing one, depending on the situation. Every requirement has to be abstracted to the product level. For this 2 rules are set up.

R1. No requirement may exist without having a connection to the Product Level.

R2. All requirements have to be broken down to Function Level.

An example is considered that shows the work-up process of this model where the original requirement that belongs to the feature level is considered. According to the R1, it is mandatory to connect the original requirement in the feature level to the product level by creating the requirements. After which R2 is followed, where all the requirement are to be broken down to the functional level by creating the requirements. The breakdown to Component Level offers further details to relatively low-level requirements and is often associated with suggestions of how to implement a requirement.
There are additional attributes other then the attributes mentioned in the specify step. Requirement Source, Requirement Owner, Requirements Manager, Relation/dependency, State, Reject reason, Due date, Version, Date of creation, Last changed are the additional attributes that can be mandatory (manual or auto generated), optional. Further these attributes are related to either traceability or roles attribute or to process attribute.

Later in this article the state of the requirements in RAM is explained using a diagram.
There are generally four states a requirement be in. 

A.	Draft requirement

B.	Rejected requirement

C.	Incompletely specified

G.	Refined requirement  

In continuous RE, a requirement X is drafted to state A. Here if the requirement is incomplete it is sent to the state C or it is sent to state B if the requirement is out of scope. If it does not belong to both the states, then it is accepted for prioritization and sends to state D (internal prioritized requirement). If we find out that this requirement has low priority i.e. it is out of scope for the current plan then it is send to the state E (postponed requirements). After the requirement is prioritized, it is accepted for the plan and sent to the state F (planned requirement) and further sent to state G (refined requirement) and these requirements to designed are sent to started requirement state H, after which the process in completed. Requirements with the lower priority are send back to state E from state F, G, H. 

In the next section of this paper, validation of RAM in industry against an organization faced with the improvement issues is discussed. There are two types of validation.

1.	Static validation: The static validation consists of reviews and walkthroughs of RAM

2.	Dynamic validation: the dynamic validation consists of a live industry requirements engineering effort where the model was put through its phases.

The roles involves in Static Validation One involved eliciting feedback/ input regarding RAM:

(A) Product Manager (two persons interviewed)

(B) Ordered (one person interviewed)

(C) Project Manager (two persons interviewed)

(D) System Engineer (one person interviewed)

The roles involve in Static Validation Two involved eliciting feedback/ input regarding RAM:

(E) Developer (one person interviewed)

(F) System Test (one person interviewed)

(G) Upper Management (one person interviewed)

Dynamic validation:

 As the RAM model is completed, it is set to be tested in live development situation. The idea was to use the model for actual requirements engineering in order to validate its components and to check if the model was scalable to a real development situation. During the process of this type of validation, few questions are generated considering several aspects of RAM.
At the end this paper concludes stating the importance and the usage of the requirement abstract model. This will give clarity about the requirements and helps in taking decision for any future work on a particular requirement.



SEMINAR 2
 HOMEWORK ARTICLE
 
“Towards a Reference Framework for Software Product Management”

In this paper a framework is developed that provides the structure to the knowledge for a body of knowledge for software product management. A clear explanation of how a software product management process is carried out entirely by an organization and the structure of the software product management is not provided clearly. The authors of this paper has considered this as a research gap and developed a reference framework based on overview of state-of-the-art literature and industrial case studies. This framework explains the process carried out by the product manager during the software product management and also helps in identifying the stakeholders for the product and their relation during the software product management. This framework divides the software product management into four parts:

Portfolio management: Portfolio management entails the decision making about the set of existing products, introducing new products by looking at market trends and the product
development strategy, making decision about the product lifecycle, and establishing partnerships and contracts. It deals with the products in the product portfolio (no of products a company has).

Product release planning: Software release management is the process through which software is made available to, and obtained by, its users. Especially on the area of release planning, where the set of requirements for the next release is determined, much research has been carried out. It is used to identify the different releases of a product

Product road mapping: Receives input regarding product lines from portfolio management. It deals with the set of requirements that are to be released. 

Requirements management: Requirements management contains the activities of gathering, identifying, revising and organizing incoming requirements from the various stakeholders. Requirements management is a key area in product software companies. It deals with the content of each individual requirement.

These four processes are carried out as follow:

Portfolio management process involves four tasks

•	Partnering and contracting

•	Market trend identification

•	Product life cycle management

•	Product line identification

The input for this process helps in making the decision about the development strategy and lifecycle. A software product line is identified in this process which serves as an input for product road mapping.

 Product road mapping process involves these tasks

•	Theme identification

•	Core asset identification

•	Road map construction

This process receives input as product lines from portfolio management. This helps in identifying the themes and core assets. This roadmap also acts as an input to the requirements organization.

Requirements management process involves these three tasks

•	Requirements gathering

•	Requirements identification

•	Requirements organizing.

In this process the inputs are gathered from different stakeholders and were indentified. The product requirements are grouped according to the product and core asset.

Product release planning mainly involves these five tasks.

•	Requirements prioritization

•	Requirements selection

•	Release definition

•	Release verification

•	Launch application

Takes the input from the requirements management process where some of the prioritized requirements are selected. For these requirements, a release is prepared and different internal stakeholder validates it and sent it to the board for approval. Once the approval is received, the implementation process starts and the launch preparation package is delivered to the stakeholders.
As this framework also helps in identifying the stakeholders. Some of the stakeholders that are identified and mentioned in this framework are

•	External Stakeholders

o	Market

o	Partner companies

o	Customers

•	Internal stakeholders

o	Development

o	Support

o	Service

o	Research and innovation

o	Sales and marketing

o	Company board

This paper discuss what a software product management is by explaining each and every step involved in the software product management clearly. 


SEMINAR 2
HOMEWORK ARTICLE "Obsolete software requirements"

The authors of this paper mainly concentrated on understanding the nature of obsolete requirements and their role in requirements management. Software, as a business, is a demanding environment where a growing number of users, rapid introduction of new technologies, and fierce competition are inevitable. Obsolete requirements could dramatically extend project timelines, increase the total cost of the project or even cause project failure. Thus, the identification, handling, and removal of obsolete requirements are crucial. Some of the reasons for the cause of obsolete software requirements are mentioned.

•	Scope creep

•	Requirements creep

•	Requirements leakage

A survey is conducted and investigated the phenomenon of obsolete requirements and effort required to handle the obsolete requirements in industrial practice. This survey is conducted based on the research questions that were formed. 

1.	The obsolete software requirements create serious impact in industry practice.

2.	Requirements related to standards and laws are the least likely to become obsolete, while inconsistent and ambiguous requirements are the most likely to become obsolete. 

3.	OSRs identification is predominantly a manual activity.

4.	The identified OSRs should be kept in the requirements document or the database, but tagged as obsolete.

5.	Project managers and product managers indicate that they always find OSRs in their work even if many of the respondents do not actively look for them.

6.	OSRs are more likely to affect Large-scale requirements (LSRE) and Very large-scale requirements projects (VLSRE).

7.	OSRs should first of all be handled during the Requirements analysis and Requirements validation phases.

8.	The results point to the lack of methods and routines for actively handling OSRs as a central determinant.
	
From this article, I have learnt that it is not an easy task to handle the obsolete requirements. And if the management of these requirements are poor, then there will be a immense effect on the organization or company. 
SEMINAR 2 HOMEWORK ARTICLE:

“An Industrial Survey of Requirements Interdependencies in Software Product Release Planning”

The task of finding an optimal selection of requirements for the next release of a software system is difficult as requirements may depend on each other in complex ways. The task of scheduling an optimal selection of requirements for a particular increment is as complex as it is important. The main aim of this paper is to find out strategies for reducing the effort needed for identifying and managing interdependencies. The authors of this paper mainly concentrated on identifying the nature and frequency of requirements interdependencies and their importance in software release planning. An informal survey was conducted and identified six different planning parameters that need to be considered and satisfied for release planning they are 

•	Available resources

•	Delivery time

•	Requirements interdependencies

•	Requirements priority

•	System architecture and

•	Dependencies to code base

In the incremental process, it is important to prioritise the requirements. But because of the interdependencies between the requirements, it is difficult to prioritise the requirements. As the main aim is to identify the nature and frequency of requirements interdependencies, a survey is conducted in 5 companies. among the five cases, three of the cases can be labelled as product development, meaning that there was a mature product out on the market, and the development situation can be described as incremental and market-driven and The remaining two cases can be labelled as bespoke, meaning that there was no released version of the product on the market, and there was a specific customer paying for the development. Later in the data collection phase, the requirement managers were asked to select 20 high priority requirements from the current requirements repository. They are requested to prioritize the requirements without considering the interdependencies among each other and pair wise considerations are done for all the 20 requirements.  For each pair of requirements there were a number of considerations to make such as:

a.	No relation whatsoever could be found. In this case the RM was asked how certain he was of this, on the scale {Possibly, 
Probably, Positively).

b.	The relation between the requirements is found. This relation is identified using classification schema.

A preliminary set of interdependency types were created. The six types of interdependencies are as follow:

1.	AND

2.	REQUIRES

3.	TEMPORAL

4.	CVALUE

5.	ICOST

6.	Or

It is important that the functional interdependencies should have higher priority than the value related interdependencies. The interdependencies are prioritized in the following order:

1.	AND has the highest priority

2.	REQUIRES has the second priority

3.	TEMPORAL can be either functional related or value related. It can be either REQUIRES or ICOST. The priority order is next to the REQUIRES.

4.	ICOST and CVALUE come under the same priority. As both of them are value related dependencies. If a conflict arises between these two then a trade-off should be considered. The CVALUE interdependency type plays a major role in the release planning.

5.	OR has the least priority.

Later in this paper, visualization technique is used which is applied to the requirements and their interdependencies in order to support release planning. This technique is used for identification of the singular requirements, clusters of interdependent requirements and highly dependent requirements.  Another concept is used to support the release planning. The concepts requirements coupling and release coupling are used. Requirements coupling are used to describe the complexity of the planning. Release coupling is used to specify the number of interdependencies between the partitions. At the end of the paper the author has concluded that it is important to find the methods or techniques that identify the singular requirements, highly dependent requirements  or free clusters. 

SEMINAR 2
HOMEWORK ARTICLE

“Exploring factors affecting decision outcome and lead time in large scale requirements engineering”

In this article, the importance of decision making on the requirements is focused. In MDRE projects, requirements keep on coming, deciding which requirements to be implemented is far from trivial. Customer needs keep evolving and cause changes to requirements so to maintain the competitive standards of the market, it is important to analyze and decide upon these changes. Some of the characteristics of the change requirements are number of products, released number and the type of customer. Lead time, defined as the duration between the moment a request was filed and the moment the decision was made, is an important aspect of decision making in market-driven requirements engineering. Minimizing lead time allows software companies to focus their resources on the most profitable functionality and enables them to remain competitive within the quickly changing software market. The author has considered some factors such as

1.	To explore possible factors that may influence the decision lead time.

2.	To investigate the possible factors that may influence the decision outcome.

3.	To investigate if the decision leads time affects the decision outcome.

Based on these factors a case study at a large company and a survey of industrial practice is conducted. The results show that 

a.	The number of products affected by a decision increases the time needed to make a decision. So it is important to consider this aspect while planning for the efficient decision making and possibly reducing the complexity of decisions.

b.	The statistical analysis of the decision log suggests no significant relationship between the release of the product line that a change impacts and the decision lead time.

c.	The lead time for decisions is shorter when the change requests are issued by important customers. 

d.	The lead time makes a decision increases when more products are influenced by this decision. 

e.	Change requests issued by important customers are more likely to be accepted.

f.	The chance of accepting a change request is higher if it affects a greater number of products.

g.	Change requests affecting late releases have a significantly higher probability of acceptance.

h.	The lead time to reject a decision is significantly longer than that to accept a decision.

There is contradiction between the results obtained from survey and case study, for the release of product line has any impact on the lead time, the customer type has any impact on the lead time, number of products affected has any impact on the decision outcome, release number has any impact on the decision outcome.


SEMINAR 2 HOMEWORK ARTICLE

“Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Over scoping in Large-Scale Software Engineering”
Scope management is a key factor in releasing successful software products to the market. Scoping is the process of selecting which requirements to include into the next release of a software product. It is a complex and continuous task of assessing and re-assessing how these scoping changes impact the common code base of the software product line on which those products are built. This article mainly focuses on understanding over scoping in large scale, market-driven software development projects, and how agile requirements engineering practices may affect this situation. An interview is performed with nine practitioners at a large, market-driven software company. Research questions were framed based on the increase the understanding of factors involved in over scoping and thereby highlight this risk and take a step towards addressing and avoiding over scoping of projects. After which a case study is performed in three different phases.

1.	Pre-study and hypothesis formulation

2.	Interview study

3.	Validation questionnaire

The results have found that:

1.	That over scoping is mainly caused by the fast-moving market-driven domain in which the case company operates, and how this inflow of requirements is managed.

2.	Over scoping can lead to a number of negative effects, including quality issues, delays and failure to meet customer expectations. Delays and quality problems are expensive, not just considering the cost of fixing the quality issues, but also in loss of market shares and brand value.

3.	A situation of over scoping may cause even more over scoping, i.e. an organization may end up in a vicious cycle when over scoping ties up development resources which are then not available for participating in early project phases.

4.	Over scoping leads to increased communication gaps, which in turn are root causes of over scoping.

SEMINAR 2
HOMEWORK ARTICLE

"Assessing challenges of continuous integration in the context of software requirements breakdown: a case study"

As there is an increase in the complexity in the software development and the demand for the high quality products in a shorter delivery time by the customer, all the software companies are trying hard to improve their process to reach the goals and satisfy the customers. Companies that follow the agile process succeeds to some extent in reaching the goal and satisfying the customers because the agile process mainly focuses on customer collaboration and shorter feedback loops. For the further improving of the process, companies have adopted continuous integration which is the concept where teams integrate their code several times a day.  Continuous integration is not a trivial task since it requires frequent integration of smaller units of requirements that can be tested separately. In this paper a case study is carried out at Ericsson AB within the serving GPRS support node mobility management entity program to identifying the challenges of continuous integration, requirements breakdown and how the latter implementation of the continuous integration process. This case study involves several branches such as Work branch, Latest local version, Pre-Test build, Latest stable version while integrating and developing at different quality levels. Later in the case study all the cross functional teams identify several challenges that are related to continuous integration while different branches involved in the case study integrate the codes according to their needs. 

The challenges that were identified for continuous integration are listed below:
1.	Mindset: mindset plays an important role when transitioning to continuous integration. The challenges that are identified related to mindset are 

•	Scepticism 

•	Change old habits

•	Exposing work intention

2.	Tools and infrastructure:  Some of the problems that arise at the   time of using this tools and infrastructure are  

a)	Code review

b)	Maturity

c)	Regression feedback time

d)	Test automation

e)	Integration queue

3.	Testing: Challenges associated with this is due to lack of automated tests along with a stable test framework. Some of the challenges related to testing are 

a)	Unstable test cases

b)	Too many manual tests

c)	Implementation and test dependencies

d)	Preserving quality

4.	Domain applicable: It is defined as the suitability of continuous integration at the organization. The challenges that are identified because of domain applicability are

a)	Process suitability

b)	Product complexity

5.	Understanding: Teams and management might interpret the concept of continuous integration differently. As a result, some challenges are being identified as follows:

a)	Unclear goals

b)	Increased pressure

c)	Different interpretations

d)	Bottom-up approach

6.	Code dependency: Development was carried out by several developers instead of one, because of diving work into several integrations. This shows the importance of considering code dependencies and how it effects the integration process and challenges are as follows:

a.	Integration coordination

b.	Dead code

7.	Software requirements: When adopting continuous requirements they are treated as a challenge. The requirements need to be broken in order to allow more frequent integrations. How the software requirements affect the integration process is demonstrated by the challenges as mentioned:

a.	Requirements breakdown

b.	Deliver feature growth

c.	Integration of big impact changes

During requirement breakdown, there are some challenges that were identified:

1.	Requirements abstraction: It is very difficult when the requirements are too big, ambiguous or too low. The challenges that are identified related to the requirements abstraction are:

a.	Ambiguous requirements

b.	Large requirements

c.	Low-level requirements

d.	Architectural design

e.	Product complexity

2.	Alignment of requirements and tests: when integrating requirements into the main line, they need to be associated with tests and aligned properly. The challenges identified related to alignment of requirements and test are:

a.	Implementation and test case dependencies

3.	Customer value: It is a very process for breaking down requirements into small components by considered the market and customer value. The challenges identified in this area are:

a.	Access to customer

b.	Delivering the customer value

4.	Guiding principle: Lack of guidance and not having a clear idea on the unified process are identified as the possible reasons for this ambiguity. The challenges associated with this are due to

a.	No unified process

b.	Ongoing responsibility shift

c.	Unfit process

d.	Lack of guidance

The challenges that are identified because of requirements breakdown during continuous integration

1.	Necessity of software requirements breakdown: There is a need for the breakdown of software requirements in order to adopt an efficient continuous integration process with a beneficial integration frequency,. The challenges that are identified because of this are 

a)	Big impact requirements

b)	Maintenance versus feature development

2.	Implications of software requirements breakdown: The challenges identified relate to this area as follows:

a)	Implementation dependencies

b)	Integration scope

c)	Test dependencies

d)	On Demand Software Delivery

Related to increase integration frequency, roles of software requirements breakdown plays an important role when adopting continuous integration. 

SEMINAR 2
HOMEWORK ARTICLE:

"Market-Driven Requirements Engineering for Software Products"

This paper mainly discusses the overview of the special characteristics of market-driven requirements engineering and describes the most important challenges of the area.  A market driven refers to the situation where the development costs of a generic product are divided among many buyers on an open market and where the potential profit is rewarded to the producer Market-Driven Requirements Engineering (MDRE) covers the classical RE activities, such as elicitation, specification, and validation, adapted to the market-driven situation, where a software producer develops a product that is offered to an open market with many customers. MDRE also covers the specific activities needed in a market-driven context, such as release management and market analysis. In this paper the specific challenges of requirements engineering in a market driven software development context id discussed.
The primary objective of market-driven development is to deliver the right product at the right time. The MDRE case is more focused on prioritization, cost estimation and release planning, and these activities are all conducted by the developing organization. Some of the important characteristics are listed below.

a.	The developing organization makes all decisions but also takes all risks.

b.	 There is a continuous flow of requirements throughout the product lifetime. 

c.	 The requirements volume is potentially very large and continuously growing. 

d.	 A majority of the requirements are informally described. 

e.	 The product is evolving continuously and delivered in multiple releases.

f.	 Release planning focuses on time-to-market and return-on-investment.

There are some RE challenges in market-driven software development

1.	Balancing market pull and technology push.

2.	Chasm between marketing and development.

3.	Organizational instability and market turbulence.

4.	Simple tools for basic needs.

5.	Requirements dependencies

6.	Cost-value-estimation and release planning.

7.	Overloaded Requirements Management.

The key factor for a market driven company is to continuously improve in managing these challenges in such a way that it stays ahead of competitors. When designing an MDRE process for a specific company, it is important to realize that there are many factors that determine what the best concrete process implementation is. The factors are as follow.

a.	type of development process, 

b.	type of distribution channels,

c.	 price and licensing policy

d.	type of market

e.	 what is the distinguishing customer value

f.	 product complexity

g.	nature of competition

h.	 customer behaviour

i.	requirements on product flexibility and adaptability

j.	user interface complexity

k.	 predictions on sales

l.	 sales channels

Process quality issue in MDRE is the quality of decisions that are made about produced artefacts. Decision quality is referred to the ratio of correct requirement selection decisions that are made during the recurring release planning activity. The selection is carried out by the Alfa/beta model of MDRE selection quality.  An Alfa requirement is defined as a requirement with high quality that it is ideally selected. Beta requirements are defined as the requirements that should be rejected because of its low quality.

In MDRE data management, mainly contains two ingredients

1.	Requirements state model: the requirements state model used for progress tracking of requirements refinement. Requirements are received at any time, but the development of a product is made in releases that are produced at discrete points in time. For this purpose, two modes are identified.

a)	Continuous mode: in this mode, requirements are received and registered by the product manager.

b)	Release mode: The development of product releases is initiated at designated times according to the roadmap planning and the requirements management activities are in release mode.

To monitor the progress of the work on the requirements the following statuses of the requirements are discussed.

a.	Candidate: Each requirement received gets the status of “Candidate”.

b.	Approved: Accepted requirements get the status “Approved”.

c.	Specified: When the specification document is available the requirement gets the status “Specified”.

d.	Discarded: Rejected requirements get the status Discarded. A notification with the motivation of the rejection is send to the submitter.

e.	Planned: All requirements selected get the status “Planned”.

f.	Developed: When all these activities have been successfully completed, the requirement gets the status “Developed”.

g.	Verified: Several testing activities are done for the developed system. If the results obtained are positive then it gets a status of positive.

h.	Released: When all activities for the product release have been completed the requirement finally gets the status of 
“Released”.

2.	Requirements repository: requirements repository where relevant attributes of candidate requirements are stored.

Customers want to be sure that the future of the software product on which they depend is in line with their future plans for this a road mapping technique is designed. A roadmap is a document that provides a layout of the product releases to come over a time frame of three to five years. Taxonomy is established that classifies roadmaps according to their location in an applications-objectives space. This taxonomy scheme classifies the roadmaps broadly into the following four categories:

a.	Science and Technology Roadmaps 

b.	 Industry Technology Roadmaps 

c.	Corporate or Product-Technology Roadmaps 

d.	 Product or Portfolio Management Roadmaps

The roadmap helps identify precise objectives and helps focus the required resources on meeting those objectives. Road mapping has several potential uses and resulting benefits at both the individual corporate and industry levels. The three major uses of road mapping are:

a.	Development of a consensus about a set of needs and the technologies required to satisfy the needs.

b.	Provision of a mechanism to help experts forecast technology developments in target areas.

c.	A framework to plan and coordinate developments either within an organization or in an entire industry.

The structure of the road mapping process consists of four phases to  stratify from strategy making to the development of the software product.

1.	Phase 1: Initiation Phase:

2.	Phase 2: Preparation Phase

3.	Phase 3: Finalization Phase

4.	Phase 4: Follow-up Phase

Later in this paper an example Road mapping at Baan is considered. In the conclusion the author as stated that in MDRE context, there are so many challenges observed in the areas like prioritization, management of dependencies and tool support for handling large scale requirements.








 
















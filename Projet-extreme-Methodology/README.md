
# Project-extreme

## collaboratif Project

Our project is fixed to represent the extreme programming which is a method of programmation.

Extreme programming (XP) is a software development methodology intended to improve software quality and responsiveness to changing customer requirements. As a type of agile software development,it advocates frequent releases in short development cycles, intended to improve productivity and introduce checkpoints at which new customer requirements can be adopted.

Other elements of extreme programming include: programming in pairs or doing extensive code review, unit testing of all code, not programming features until they are actually needed, a flat management structure, code simplicity and clarity, expecting changes in the customer's requirements as time passes and the problem is better understood, and frequent communication with the customer and among programmers. The methodology takes its name from the idea that the beneficial elements of traditional software engineering practices are taken to "extreme" levels. As an example, code reviews are considered a beneficial practice; taken to the extreme, code can be reviewed continuously

## History

Kent Beck developed extreme programming during his work on the Chrysler Comprehensive Compensation System (C3) payroll project. Beck became the C3 project leader in March 1996. He began to refine the development methodology used in the project and wrote a book on the methodology (Extreme Programming Explained, published in October 1999). Chrysler cancelled the C3 project in February 2000, after seven years, when Daimler-Benz acquired the company. Ward Cunningham was another major influence on XP.

Many extreme-programming practices have been around for some time; the methodology takes "best practices" to extreme levels. For example, the "practice of test-first development, planning and writing tests before each micro-increment" was used as early as NASA's Project Mercury, in the early 1960s.[7] To shorten the total development time, some formal test documents (such as for acceptance testing) have been developed in parallel with (or shortly before) the software being ready for testing. A NASA independent test group can write the test procedures, based on formal requirements and logical limits, before programmers write the software and integrate it with the hardware. XP takes this concept to the extreme level, writing automated tests (sometimes inside software modules) which validate the operation of even small sections of software coding, rather than only testing the larger features

## Origin

Origins
Two major influences shaped software development in the 1990s:

Internally, object-oriented programming replaced procedural programming as the programming paradigm favored by some developers.
Externally, the rise of the Internet and the dot-com boom emphasized speed-to-market and company growth as competitive business factors.
Rapidly changing requirements demanded shorter product life-cycles, and often clashed with traditional methods of software development.

The Chrysler Comprehensive Compensation System (C3) started in order to determine the best way to use object technologies, using the payroll systems at Chrysler as the object of research, with Smalltalk as the language and GemStone as the data access layer. Chrysler brought in Kent Beck,[5] a prominent Smalltalk practitioner, to do performance tuning on the system, but his role expanded as he noted several problems with the development process. He took this opportunity to propose and implement some changes in development practices - based on his work with his frequent collaborator, Ward Cunningham. Beck describes the early conception of the methods:

The first time I was asked to lead a team, I asked them to do a little bit of the things I thought were sensible, like testing and reviews. The second time there was a lot more on the line. I thought, "Damn the torpedoes, at least this will make a good article," asked the team to crank up all the knobs to 10 on the things I thought were essential and leave out everything else.

Beck invited Ron Jeffries to the project to help develop and refine these methods. Jeffries thereafter acted as a coach to instill the practices as habits in the C3 team.

Information about the principles and practices behind XP disseminated to the wider world through discussions on the original wiki, Cunningham's WikiWikiWeb. Various contributors discussed and expanded upon the ideas, and some spin-off methodologies resulted (see agile software development). Also, XP concepts have been explained[by whom?], for several years, using a hypertext system map on the XP website at http://www.extremeprogramming.org circa 1999.

Beck edited a series of books on XP, beginning with his own Extreme Programming Explained (1999, ISBN 0-201-61641-6), spreading his ideas to a much larger audience. Authors in the series went through various aspects attending XP and its practices. The series included a book critical of the practices.

## Current state


XP generated significant interest among software communities in the late 1990s and early 2000s, seeing adoption in a number of environments radically different from its origins.

The high discipline required by the original practices often went by the wayside, causing some of these practices, such as those thought too rigid, to be deprecated or reduced, or even left unfinished, on individual sites. For example, the practice of end-of-day integration tests for a particular project could be changed to an end-of-week schedule, or simply reduced to testing on mutually agreed dates. Such a more relaxed schedule could avoid people feeling rushed to generate artificial stubs just to pass the end-of-day testing. A less-rigid schedule allows, instead, the development of complex features over a period of several days.

Meanwhile, other agile-development practices have not stood still, and as of 2019 XP continues to evolve, assimilating more lessons from experiences in the field, to use other practices. In the second edition of Extreme Programming Explained (November 2004), five years after the first edition, Beck added more values and practices and differentiated between primary and corollary practices.

## Principle

The principles of the eXtreme Programming method are not new since they are those of Agile methods . The difference and the originality reside in the fact that they are pushed to the extreme.

The eXtreme Programming method is based on:

- strong responsiveness to changing customer needs;
team work ;
- the quality of the work provided;
-the quality of the tests carried out as soon as possible.

XP is based on five core values:

- Communication  : it is essential that each member of the team communicates daily with their colleagues as well as with the client. It is an essential way to solve problems.
- Simplicity  : the simplest way to achieve the result is preferred. The project team does what is necessary and requested, nothing more. A simple application will be easier to develop later.
- Feedback  : Feedback between the project team and the client is essential. Each stage of the project is sent as quickly and often as possible to the client so that he can test, give his opinion and validate the stage. Each modification request is taken into account immediately.
- Respect  : Respect for each member of the team and their work is paramount. The management, the project team and the client respect each other.
- Courage  : It takes courage to make certain changes such as trying a new technique, restarting an unvalidated iteration or reviewing the organization of the project. Courage allows you to get out of an unsuitable situation.

## Functioning

The five XP values ​​are broken down into thirteen mutually reinforcing practices:

- Client on site  : the client must be represented on site throughout the duration of the project. This representative must have an overall vision of the result to be obtained and be available to answer the team's questions.
Planning game (or planning poker) : the planning is carried out in collaboration with the client. The latter creates scenarios for the functionalities that he wishes to obtain. The team estimates the time needed to implement them. The client then selects scenarios based on priorities and available time.
Continuous integration  : when a task is completed, it is immediately integrated into the complete product. This avoids the work overload due to the integration of all the elements before delivery. The tests facilitate this integration: when all the tests are positive, the iteration is finished.
- Small deliveries : deliveries must be as frequent as possible so that the customer gives his opinion and that the modifications are quickly taken into account by the team.
- Sustainable pace  : no overtime is tolerated. If there are, then the schedule needs to be reviewed. A tired employee works poorly and makes more mistakes.
- Functional tests  : based on the scenarios defined by the client, the team creates test procedures which make it possible to check the progress of the development. When all functional tests pass, the iteration is complete.
- Unit tests  : for each feature, a test is written to verify that it will work as expected. This test will be kept until the end of the project, as long as the functionality is required. With each modification of the code, all the tests are launched in order to immediately identify if there is a problem of operation.
- Simple design  : we go straight to the point by focusing only on the current needs of the customers. The simpler the application, the easier it will be to develop it in future iterations.
- Use of metaphors : XP teams use metaphors to describe the system and how it works to clarify the functionality to be achieved. Everyone speaks the same language.
- Refactoring (or reworking of the project) : the project is improved regularly. The goal is to have good bases and better working conditions for the team.
Collective ownership of the project : the responsibility for the project is collective. Each team member can modify all parts of the project, even those on which he has not worked. The goal is to be efficient and fast.
- Language standards : since everyone is working together on the project, it is essential to facilitate everyone's work by using the same terms, the same style and clear communication rules.
- Work in pairs  : employees work in pairs. The pilot and co-pilot change regularly in order to improve communication and collective knowledge of the project.
The projects managed by the eXtreme Programming method are based on short and rapid development cycles (iterations) which are carried out collectively by the project team and the client, whose involvement is constant.

Counterproductive activities have been removed to reduce costs and frustration for everyone involved.

## Success conditions

To be implemented effectively, the eXtreme Programming methodology requires a change of mentality and acceptance by all the teams involved.

In order to guarantee the success of XP, it is essential that the customer or a representative is totally invested in the project.

This method cannot work with large teams, if working in pairs is impossible or if the feedback is long and difficult to obtain.

## In Conclusion


With the eXtreme Programming methodology, managers, project team and client work together. This approach favors the simplest method, promotes the team's responsiveness and establishes continuous quality control.

Concretely, XP is not easy to apply and master because it requires a lot of discipline and communication. You have to move quickly, without losing sight of the rigor of the work and the final functions of the project. The great strength of the eXtreme Programming method lies in its simplicity and the fact that we go straight to the point, following a rhythm that must remain constant.

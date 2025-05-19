# Question 1

### S22

#### (a)What is meant by Software and Software Engineering? 03

- Software is a collection of programs which are needed to achive desired features, functionalities with high perfomance.
- Software has two types 1. Generic (developed to serve multiple applications) 2.Custom(developed to serve one application).
- Software engineering is a disipline, method and techniques to develop a software
- To develop software efficiently software engineer is needed
- Through Software engineering one can develop software efficiently and in less time and resources.

#### (b)Discuss merits and demerits of Waterfall model. 04

![Image Alt Waterfall](https://sqatools.in/wp-content/uploads/2020/09/waterfall_model.png)

- There are 6 major phases
  - **Requirements Gathering**: Identify customer needs and requirements through techniques such as interviews, surveys, and observations.
  - **Analysis**: Analyze the requirements to identify any inconsistencies or conflicts.
  - **Design**: Develop a preliminary design that meets the customer's requirements.
  - **Implementation**: Implement the design and develop working software.
  - **Testing**: Test the software to ensure it meets the required standards.
  - **Deployment**: Deploy the software to production.
  - **Maintanance**: Maintain the software
- Linear Sequential model Advantage
  - Simple to implemet
  - easy to understand
  - best for small software development
- Linear Sequential model Disadvantages
  - making changes are hard
  - only at the end customer can have a look at the product till than cant do anything.
  - All previous stages are needed to achive current stage hence working on multiple stages isnt possible.

#### (c)What is the importance of Process Model in development of Software System? Discuss Spiral Model in detail. 07

- Process model is a representation of process in order to develope software in abstract formate.
- It demonstrates life cycle of a software development.
- Its needed inorder to
  - **Improved quality**: To deliver high-quality software that meets user expectations.
  - **Increased efficiency**: By streamlining processes and reducing rework.
  - **Better risk management**: To minimize errors, delays, and costs associated with project changes.
  - **Enhanced collaboration**: To facilitate effective communication among team members and stakeholders.
- **Spiral Mode**
  ![Image Alt Spiral_Mode](https://i.postimg.cc/mD7s4rbw/Image.png)
- The Spiral Model is an iterative development approach in Software Engineering (SE) that combines the strengths of both Waterfall and Agile methodologies. This model involves a phased approach to project management, where each phase consists of a series of iterations.
- This is an incremental method in version of software
- Its suited for large scale projects
- There are 6 major phases
  - **Requirements Gathering**: Identify customer needs and requirements through techniques such as interviews, surveys, and observations.
  - **Analysis**: Analyze the requirements to identify any inconsistencies or conflicts.
  - **Design**: Develop a preliminary design that meets the customer's requirements.
  - **Implementation**: Implement the design and develop working software.
  - **Testing**: Test the software to ensure it meets the required standards.
  - **Deployment**: Deploy the software to production.
- Advantages
  - The changes are easy to made in each stage
  - Easy to debug
  - Clients will be aware about the feel and functions of software.
  - Breaks large project into smaller chunks
- Disadvantage
  - Costly and Time consuming
  - Since its Customer Communication based approach if communication isnt done properly the software developement may result in faliur.
- When to choose Spiral Model
  - The requirements arent clear
  - The software it too large
  - The errors are expected minimul / highly robust
  - Budget isnt an problem
  - Prototypes of software are needed

---

### S23

#### (a)What is Software Engineering? Justify Software is Engineered but not Manufactured 03 (RE)

- Justification of Software is Engineered but not Manufactured
  - **Lack of Physical Constraints**: Unlike manufactured goods, software has no physical constraints that affect its design or functionality. This freedom allows developers to focus on creating efficient, scalable, and user-friendly products without being bound by material limitations.
  - **Dynamic Nature**: Software is dynamic, meaning it can be easily modified, updated, or replaced as technology evolves or user needs change. In contrast, manufactured goods have a fixed product life cycle, with limited opportunities for modification after production.

#### (b)What is Process? Discuss the process framework activities. 04

- In software engineering, a process is a structured approach to managing and delivering software products.
- There are 6 process framework activities
  - **Requirements Gathering**
  - **Analysis**
  - **Design**
  - **Implementation**
  - **Testing**
  - **Deployment**
  - **Review and Retrospective**

#### (c)Explain Spiral Process Model and states its advantages and disadvantages. 07 (RE)

---

### S24

#### (a)Describe software engineering as a layered technology. 03

- Any software can be developed in these layered approach
  1. Quality Management layer
  2. Processes layer
  3. Methods layer
  4. Tools layer
- First the quality of software is estimated based on requirements tha the poper process is being decided based on given time and budget than the required methods such as requirements gathering, analysis,designing etc are conducted and finally the software is tested in with various tools in order to find bugs and errors in softtware.

#### (b)Describe various umbrella activities in software development. 04

![Image Alt Umbrella activities](https://i.postimg.cc/pdzWWCCz/umbrella-activity-modified.png)

- Umbrella activities
  - **Software Project Tracking and Control** This activity allows the software team to check the progress of software development.
  - **Formal Technical Reviews** Remove errors before they are propagated to the next activity.
  - **Software Quality Assurance** The quality of the software, such as user experience, performance, workload flexibility, etc., must be tested and verified after reaching the specified milestones, which reduces the tasks at the end of the development process.
  - **SCM or Software configuration management** It manages the impact of changes throughout the software development process.
  - **Document Preparation and Production** activities required to create work products such as models, documents, logs, forms, and lists.
  - **Re-usability Management** Defines the development of components that can be reused as different widget.
  - **Measurement and Metrics** Define process, project, and product metrics to help the team deliver software that meets the needs of stakeholders.
  - **Risk Management** Series of steps to help manage uncertainty.

#### (c)Discuss spiral model with diagram and compare it with waterfall model. 07

| Spiral model                               | Waterfall model                         |
| ------------------------------------------ | --------------------------------------- |
| Budget is high                             | Budget is Low                           |
| Quality of software is high                | Quality of software is high Low         |
| Required time is high                      | Required time is Low                    |
| Highly robust                              | Somewhat robust                         |
| Changes are easy to do                     | Changes cant be made                    |
| goes through each phase more than 1 time   | goes through each phase for 1 time only |
| Prototypes are available though each cycle | No prototypes are to be made            |
| Better suited for large software           | Better suited for small software        |

---

### W24

#### (a)Why Spiral Process Model is also known as Meta Model? 03

- The spiral model is not restricted to a fixed number of development phases. Instead, it supports different sets of phases.
- May be required for different projects, based on the complexity and application of the software/product.
- In a single iteration, these are the six phases:
  - **Requirements Gathering**
  - **Analysis**
  - **Design**
  - **Implementation**
  - **Testing**
  - **Deployment**
  - **Review and Retrospective**

### (b)Compare Prototype Process Model with RAD Process Model. 04

| Prototype Model                                  | RAD Model                                                                  |
| ------------------------------------------------ | -------------------------------------------------------------------------- |
| It is suitable for high-risk projects.           | It is not suitable when technical risks are high.                          |
| In this, quick initial reviews are not possible. | In this, quick initial reviews are possible.                               |
| It does not support automatic code generation.   | It supports automatic code generation as. results in minimal code writing. |
| Low team size is sufficient.                     | It requires a large team to carry out the operations.                      |
| In this user involvement is high.                | In this user Involvement is only at the beginning.                         |
| End-Product cannot be developed in less time.    | End-Product can be developed in less time.                                 |

### (c)Explain the working of Incremental Process Model with suitable diagram. 07

![Image Alt Incremental_Process](https://www.radhikaclasses.com/wp-content/uploads/2021/03/Incremental-model-image-new-2048x1043.png)

- Combines RAD and Spiral models.
- The software requirements are divided or broken down into multiple stand-alone modules/increments.
- Every new release of the module adds functionality to the previous release module.
- The process continues until all the intended functionality has been implemented and the complete system is developed.
- Each module (increment) passes through four phases:

  1. **design**
  2. **Coding**
  3. **Testing**
  4. **Implementation**

- **Advantages**:

  - The software objectives and requirements are met.
  - Requirements can be altered at any time throughout development.
  - Verifying and debugging this model is easy.
  - Produce working software earlier and more rapidly during product development.
  - Feedback on every build.
  - Identifying errors becomes easy.
  - Most important and useful functional capabilities can be developed in early stages.

- **Disadvantages**:

  - This model requires presice planning and designing.
  - It needs a complete and clear definition of the whole system for each stage.

- **When to use**:

  - Time is very less.
  - Software can be devided in modules.
  - Lots of distinct features and modules.
  - Software is required to serve main perpose ASAP.

- **Incremental process Example**:
  - The first release (A) of the software contains file management, document generation, and editing capabilities. With the next release (B), sophisticated editing tools and advanced file creation functionality will be included. This further increment (C) will provide features such as spell checking, grammar checking, mailing, etc.

---

# Question 2

### S22

#### (a)Define agile process .Give any two agile principles. 03

- The Agile process is a project management framework that emphasizes flexibility, collaboration, and customer feedback by breaking projects into smaller, manageable phases.
- This approach allows teams to adapt quickly to changes and continuously improve software.
- Agile principles
  - Satisfy the customer by early and continuous delivery of valuable software.
  - Business people and developers must work together throughput the project.
  - Motivate the people who are building the projects.
  - The proper attention to be given to technical excellence and good design.
  - The simplicity must be maintained while developing the project using this approach.
  - The teams must be the self-organizing team for getting best architecture, requirements and design.

#### (b)Describe FOUR Ps for Project Management. 04

- **Product**: This is the deliverable of the project. The project manager should define the product scope.The product does not necessarily need to be restricted to software.
- **Process**: Project managers and team members should have a methodology and plan that outlines their approach. Without a clearly defined process, team members will not know what to do and when to carry out project activities.
- **People**: In building a proper product, a well-managed team with clear-cut roles defined for each person/team will lead to the success of the product. We need to have a good team in order to save our time, cost, and effort.
- **Project**: Project manager must guide team members to achieve the project’s goals and objectives. The project manager must distribute tasks efficiently and help team members when needed.

#### (c)Explain Scrum with its advantages and disadvantages. 07

- Scrum is a management framework that teams use to self-organize tasks and work towards a common goal
- Scrum is an agile process model which is used for developing the complex software systems.
- It is a lightweight process framework that can be used to manage and control the software development using iterative and incremental approach. Here the term lightweight means the complexity of the process is kept as small as possible in order to maximize productive time.
- There are small working teams on the software developmernt projects. Due to this there is maximum communication and minimum overhead.
- The tasks of people must be partitioned into small and clean packets or partitions.
- The process should produce software increments. These increments must be inspected, tested and documented.

#### OR(c) Explain Extreme Programming (XP) in detail. 07

---

### S23

#### (a)Discuss the differences among Reactive and Proactive Risks. 03

#### (b)Explain the process model which is defined as the ability of a project team to respond rapidly to a change. 04

#### (c)Explain Project Scheduling Process. Also Explain Gantt Chart in detail. 07

#### OR(c) Explain COCOMO model for cost estimation. 07

---

### S24

#### (a)What are the characteristics of the software? 03

#### (b)Explain Gantt chart in detail. 04

#### (c)List different agile process models and describe any one model in detail. 07

- Various other agile process models apart from extreme programming are
  1. Adaptive Software Development
  2. Dynamic System Development Method
  3. Scrum
  4. Feature Driven Development
  5. Agile Modeling

#### OR(c) What are the principles of agile model? Also explain its advantages and disadvantages.07

---

### W24

#### (a)Why Software Engineering is also known as a Layered Technology? 03

#### (b)Explain Formal Technical Review (FTR). 04

#### (c)Define Coupling and Cohesion. Explain different types of Cohesion andits effects on software module. 07

#### OR(c) Illustrate Requirement Engineering with suitable diagram. 07

---

# Question 3

### S22

#### (a) What are the characteristics of good SRS document? 03

#### (b) How the activity diagrams are useful in eliciting the requirements of software system? 04

#### (c) Compute function point value for a project with the following domain characteristics:

- No. of I/P = 30, No. of O/P = 62 , No. of user Inquiries = 24
- No. of files = 8 , No. of external interfaces = 2 . Assume that all the
- complexity adjustment values are average. 07

#### OR (a) Discuss the use of Data dictionaries in analysis modelling. 03

#### OR (b) What are the tasks performed in requirement engineering? 04

#### OR (c) Discuss about COCOMO model for software estimation. 07

---

### S23

#### (a) List the characteristics of a good quality SRS. 03

#### (b) Draw Data Flow Diagram for Library Management System 04

#### (c) Enlist and Explain Requirement Engineering Tasks in detail. 07

#### OR (a) Compare Coupling and Cohesion. 03

#### OR (b) Draw Use Case Diagram for ATM System. 04

#### OR (c) What is Risk Management? Explain RMMM plan 07

---

### S24

#### (a) Describe software process metrics. 03

#### (b) Explain extreme programming process. 04

#### (c) Write short note on COCOMO model. 07

#### OR (a) Write characteristics of good SRS. 03

#### OR (b) Explain Earned value analysis in project scheduling 04

#### OR (c) What is risk management? Describe RMMM plan. 07

---

### W24

#### (a) Explain Function and Non-functional requirements using example. 03

#### (b) Explain RMMM. 04

#### (c) Illustrate Scrum with its advantages and disadvantages. 07

#### OR (a) Explain Gantt Chart w.r.t. project scheduling process. 03

#### OR (b) Write a short note on Extreme Programming (XP). 04

#### OR (c) Explain three golden rules for User Interface Design. 07

---

# Question 4

#### (a) Describe golden rules of User Interface Design. 03

#### (b) What is the importance of software design? List out various design principles of good software design. 04

#### (c) What is testing? Explain the different levels of testing. 07

#### OR (a) What is DevOps? 03

#### OR (b) What is architectural design? Enlist different style and patterns of architecture. 04

#### OR (c) Discuss the concepts of Cohesion and Coupling in detail. 07

---

### S23

#### (a) Describe golden rules of User Interface Design. 03

#### (b) What is BVA? List out guidelines of BVA. 04

#### (c) What is Software testing? Compare: Black box testing and White Box testing 07

#### OR (a) Give the difference between Validation and Verification. 03

#### OR (b) What is Cyclomatic Complexity? Define steps to find cyclomatic complexity using flow graph. 04

#### OR (c) Explain the importance of Software Quality Assurance. Also explain different CMM levels. 07

---

### S24

#### (a) Compare black box testing and white box testing. 03

#### (b) Write characteristics of good user interface. 04

#### (c) Explain details that should be incorporated in SRS. 07

#### OR (a) Differentiate alpha testing and beta testing. 03

#### OR (b) Describe phases of requirement engineering process. 04

#### OR (c) List out different architectural styles in software design and describe any one style in detail. 07

---

### W24

#### (a) Differentiate Object Oriented Design and Procedural Design. 03

#### (b) Explain at least four Software Reliability Metrics. 04

#### (c) Write a short note on CMM levels with suitable diagram. 07

#### OR (a) Define Stub and Driver w.r.t. Unit Testing. 03

#### OR (b) Explain Version Control and Change Control. 04

#### OR (c) What is McCabe’s Cyclomatic Complexity? Explain various steps to find Cyclomatic Complexity using flow graph. 07

---

# Question 5

### S22

#### (a) Explain Formal Technical Review. 03

#### (b) Compare white box and black box testing. 04

#### (c) Discuss five-level of SEI-CMM 07

#### OR (a) What is software quality? 03

#### OR (b) What is software maintenance? Describe different types of maintenance. 04

#### OR (c) Briefly explain software configuration management 07

---

### S23

#### (a) Describe CASE building blocks. 03

#### (b) Write short note on Reverse Engineering. 04

#### (c) List and explain the challenges in DevOps Implementation. 07

#### OR (a) Explain Version and Change Control Management. 03

#### OR (b) Explain Formal Technical Review. 04

#### OR (c) Explain Software Re-Engineering process model. 07

---

### S24

#### (a) Write a short note on formal technical reviews. 03

#### (b) Explain importance of SQA (Software Quality Assurance). 04

#### (c) Describe different types of maintenance in software engineering. 07

#### OR (a) Compare verification with validation. 03

#### OR (b) What are the advantages and disadvantages of component based development model? 04

#### OR (c) Describe phases of DevOps lifecycle. 07

---

### W24

#### (a) Compare Verification and Validation. 03

#### (b) Explain the core benefits of DevOps. 04

#### (c) Explain any Two Black Box Testing Methods with suitable example. 07

#### OR (a) Explain Client/Server Software Engineering. 03

#### OR (b) Differentiate between Reverse Engineering and Forward Engineering. 04

#### OR (c) Explain COCOMO Model for project estimation. 07

---

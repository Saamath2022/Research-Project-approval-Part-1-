Research & Project approval (Part 1) Portfolio Project

Event Management:
Event management is the process of planning, organizing, and executing events, such as conferences, conventions, concerts, weddings, and other gatherings. This involves managing various aspects like budgeting, venue selection, logistics, scheduling, coordination of activities, marketing, and ensuring that the event runs smoothly from start to finish.
Key tasks in event management include:
Planning: Defining the event's objectives, creating a detailed plan, and setting a timeline.
Budgeting: Estimating costs and managing financial resources.
Venue Selection: Choosing an appropriate location based on the event's needs.
Logistics: Coordinating transportation, accommodation, catering, and equipment.
Marketing and Promotion: Advertising the event to attract attendees.
Coordination: Managing the various teams and vendors involved in the event.
Execution: Overseeing the event on the day to ensure everything goes as planned.
Post-Event Activities: Conducting evaluations, gathering feedback, and closing out the event.
2. Technologies
Programming Language: Python
Framework: Flask
Database: PostgreSQL
Cloud Platform: AWS
Event Management Software: Eventbrite
Version Control: Git
Libraries: Pandas, NumPy, Matplotlib
1. Framework: Flask 
Flask: Flask is a lightweight and flexible micro-framework for Python, which allows developers to build web applications with minimal setup. It’s highly customizable and gives developers control over the components used.
Flask: Provides flexibility and control, allowing developers to only include what they need, making it ideal for smaller or more straightforward applications. However, this can also mean more time spent configuring and adding additional features.
2. Database: PostgreSQL vs. MySQL
PostgreSQL: PostgreSQL is an advanced open-source relational database known for its strong support for complex queries, data integrity, and extensibility.
MySQL: MySQL is another widely used open-source relational database that is known for its speed and ease of use, particularly in read-heavy applications.
Trade-offs:
PostgreSQL: Offers robust support for complex data types and operations, making it ideal for applications that require complex queries and data integrity. However, it can be more resource-intensive compared to MySQL.
MySQL: Known for its performance and ease of setup, MySQL is often preferred for applications that prioritize speed and are not as dependent on complex data structures.


Saa-Aondo Wuese Mathis
Role: Lead Developer & Project Manager
Responsibilities:
Lead Developer: Saa-Aondo will be responsible for writing the core codebase of the project, ensuring that the application is developed using best practices in Python and Flask. This includes setting up the backend architecture, integrating the database (PostgreSQL), and deploying the application on AWS.
Project Manager: In this role, Saa-Aondo will oversee the entire project, ensuring that all milestones are met on time, coordinating tasks, and managing communication with stakeholders. They will also be responsible for ensuring that the project stays within scope and budget.
Why these roles have been decided:
Lead Developer: Saa-Aondo has a strong background in backend development, specifically with Python and Flask, making them the ideal candidate to lead the technical development of the project.
Project Manager: Given Saa-Aondo’s understanding of the project’s goals, technical requirements, and the technologies involved, they are well-suited to manage the project’s timeline, resources, and deliverables. Their ability to balance both the technical and managerial aspects of the project ensures that the development process is streamlined and effective.



Challenges
1. Problem the Portfolio Project is Intended to Solve
Event management often involves multiple tasks, including planning, coordination, communication, and execution. These tasks can become overwhelming, especially when managing large or complex events. Common challenges include disorganized schedules, miscommunication between team members, inefficient resource allocation, and last-minute changes that disrupt the event’s flow. The Portfolio Project aims to streamline the entire event management process by providing a centralized platform that allows event organizers to plan, coordinate, and execute events efficiently. The platform will offer tools for scheduling, task management, resource allocation, communication, and real-time updates, all in one place.
2. What the Portfolio Project Will Not Solve
While the Portfolio Project addresses many aspects of event management, it will not handle external factors such as unforeseen weather conditions, vendor reliability, or unexpected technical failures during the event. Additionally, the project is not intended to replace the need for on-the-ground staff or personal interactions during the event. It is a tool to aid in the planning and coordination stages, but the success of the event will still depend on the execution and adaptability of the team on the day of the event.
3. Who the Portfolio Project Will Help / Who the Users Will Be
The Portfolio Project is designed to help event organizers, coordinators, and planners who manage events of varying sizes, from small corporate meetings to large-scale conferences or festivals. It will also benefit team members involved in event execution, such as vendors, contractors, and volunteers, by providing a clear and organized plan to follow. Additionally, the platform could be useful for clients who want to stay informed about the progress of their event planning.
4. Relevance to a Specific Locale
This project is not dependent on a specific locale and is designed to be flexible and adaptable to various regions and event types. Whether the event is in a large urban center, a rural area, or even a virtual setting, the platform can be customized to meet the unique needs of the location and type of event. The only consideration is that the platform may require localization features, such as language support and time zone management, to be truly effective in different regions.







Risks
1. Technical Risks

Risk: System Downtime or Server Failures

Potential Impact: If the cloud platform (AWS) experiences downtime or server failures, the entire event management system could become unavailable, leading to disruptions in planning and coordination. This could result in missed deadlines, miscommunication, or even the cancellation of events.
Safeguards/Alternatives: To mitigate this risk, the project will implement robust backup and disaster recovery plans. This includes regular data backups, the use of redundant servers, and the implementation of failover systems that automatically switch to a backup server in case of a primary server failure. Additionally, AWS's multi-region deployment can be used to ensure that the application remains accessible even if one region experiences issues.
Risk: Data Breach or Security Vulnerabilities

Potential Impact: A security breach could compromise sensitive data, such as personal information of attendees, payment details, and proprietary event plans. This could lead to legal liabilities, loss of client trust, and financial damage.
Safeguards/Alternatives: To prevent this, the project will incorporate strong encryption protocols, regular security audits, and adherence to best practices in secure coding. Additionally, implementing multi-factor authentication (MFA) for user access and continuous monitoring for suspicious activities will help safeguard the system against potential threats.

2. Non-Technical Risks

Risk: Misalignment with Client Expectations

Potential Impact: If the platform does not meet the specific needs or expectations of clients, it could lead to dissatisfaction, loss of business, and a negative reputation. Clients may find the tool too complex or lacking in necessary features, leading to underutilization or abandonment of the platform.
Strategies to Prevent Negative Outcomes: To mitigate this risk, regular client feedback will be sought throughout the development process. This includes conducting surveys, focus groups, and beta testing to ensure that the platform aligns with client expectations. Additionally, offering customizable features and comprehensive training for users will help ensure that the platform meets diverse client needs.
Risk: Dependence on External Vendors or Partners

Potential Impact: The success of an event often relies on external vendors (e.g., caterers, decorators, AV technicians). If these vendors fail to deliver on time or provide substandard services, it could negatively impact the event and the platform’s perceived effectiveness.
Strategies to Prevent Negative Outcomes: Building strong relationships with reliable vendors and creating contingency plans are essential strategies. The platform could include features that track vendor performance, allowing organizers to choose the best vendors based on past performance data. Additionally, having backup vendors on standby and clear communication channels will help mitigate the impact of any vendor-related issues.




Infrastructure
1. Branching and Merging Strategy
For this project, we will follow the GitHub Flow branching model. This process is simple and effective for continuous delivery and integration:

Branching: Each new feature, bug fix, or task will have its own dedicated branch created from the main branch. Branch names will be descriptive and follow a consistent naming convention (e.g., feature/booking-system, bugfix/user-authentication).

Merging: Once a branch’s work is complete and tested, a pull request (PR) will be created to merge the changes back into the main branch. The PR will be reviewed by at least one other team member to ensure code quality and adherence to project standards. After approval, the branch will be merged into main, and any conflicts will be resolved during this process. We will use squash merging to keep the main branch history clean by combining all commits from the feature branch into a single commit.

2. Deployment Strategy
The deployment of the Event Management platform will be carried out using AWS as the cloud platform:
Staging Environment: Before deploying to production, all code will first be deployed to a staging environment. This allows for final testing in an environment that mirrors production closely. The staging environment will be set up with the same AWS services as production but will operate independently to avoid any disruption.
Production Deployment: After successful testing in staging, the application will be deployed to the production environment using AWS Elastic Beanstalk. This platform-as-a-service (PaaS) makes it easy to deploy, manage, and scale applications. We will use blue-green deployment to minimize downtime and reduce risk. This involves deploying the new version of the application to a separate environment (blue), testing it, and then switching the traffic from the old version (green) to the new one.

3. Data Population Strategy
To populate the Event Management platform with data:
Initial Data Import: The initial data set will be populated using CSV files that contain information such as event types, venues, and default configurations. These files will be imported into the PostgreSQL database using Python scripts and the Pandas library. Eventbrite’s API will also be used to pull in event data for existing events that are being managed through the platform.

Ongoing Data Management: Users will be able to add, modify, and delete event-related data directly through the platform’s user interface. All changes will be reflected in real-time within the PostgreSQL database. Automated scripts will handle regular data cleanup and archiving to ensure that the database remains efficient and performant.


4. Testing Tools, Automation, and Processes

Testing is crucial to ensure that the Event Management platform is reliable and bug-free. The following tools and processes will be used:

Unit Testing: We will use pytest for writing and running unit tests. This will allow us to test individual components and functions in isolation to ensure they work as expected.

Integration Testing: Postman will be used for API testing to ensure that the backend services and endpoints function correctly when integrated. This will help identify issues with how different parts of the system interact.

End-to-End (E2E) Testing: For comprehensive testing of the entire user flow, we will use Selenium for automating browser-based tests. This ensures that the platform behaves as expected from the user’s perspective.

Continuous Integration/Continuous Deployment (CI/CD): GitHub Actions will be used to automate the testing process. Every time a new commit is pushed to a branch or a PR is opened, automated tests will run to catch any issues before they reach production. If the tests pass, the code can be automatically deployed to the staging environment for further validation.




Existing Solutions
1. Eventbrite
Similarities:

Like our Event Management platform, Eventbrite allows users to create, manage, and promote events. It provides tools for ticketing, registration, and event promotion, making it a comprehensive solution for event organizers.
Both platforms offer integration with social media for event promotion and have user-friendly interfaces designed to simplify event management.
Differences:

Customization: Eventbrite offers limited customization options compared to our platform, which will allow event organizers to tailor the event management tools to fit their specific needs, including custom workflows, branding, and reporting.
Target Audience: Eventbrite is primarily geared toward public events and large-scale gatherings, whereas our platform is designed to cater to both public and private events, including corporate meetings, conferences, and personal events like weddings.
2. Cvent

Similarities:

Cvent provides comprehensive event management solutions, similar to our platform. It includes tools for event registration, marketing, and attendee management.
Both platforms aim to streamline the event planning process and offer features for managing various aspects of events, from budgeting to logistics.
Differences:

Complexity and Pricing: Cvent is often seen as a more complex and costly solution, typically used by large corporations and organizations. Our platform, on the other hand, will offer a more straightforward and affordable solution, making it accessible to small and medium-sized event organizers.
Focus on Data: While Cvent provides extensive data analytics and reporting, our platform will focus more on user-friendly interfaces and automation, reducing the learning curve for non-technical users.
3. Whova

Similarities:

Whova offers a mobile event app and event management software that helps organizers engage with attendees, manage event logistics, and provide a seamless event experience. Our platform will also include mobile-friendly features and tools for attendee engagement.
Both platforms emphasize the importance of networking and community building within events, offering features like attendee profiles, messaging, and networking opportunities.
Differences:

User Experience: Whova’s platform is primarily mobile-first, meaning it’s designed for users who prefer managing events from a mobile device. While our platform will be mobile-friendly, it will also provide a robust web-based experience for event planners who prefer working on a desktop.
Feature Set: Whova focuses heavily on the attendee experience, with features like live polls and surveys. Our platform, while offering some of these features, will place a stronger emphasis on backend management tools like scheduling, budgeting, and resource allocation.
4. Reimplementation Strategy

Given the existing solutions, our platform seeks to reimplement a proven approach by combining the strengths of these existing tools while addressing their limitations:

Customization and Flexibility: Unlike existing solutions that may be rigid or overly complex, our platform will offer a customizable and flexible approach, allowing event organizers to tailor the system to their unique needs. This includes customizable workflows, templates, and branding options.

User-Centric Design: Our platform will prioritize ease of use, reducing the learning curve for users who may not have technical expertise. This includes an intuitive interface and automated processes that streamline event management tasks.

Cost-Effectiveness: By offering a pricing model that caters to small and medium-sized organizers, we aim to fill a gap in the market where existing solutions may be too costly for some users. Our platform will provide essential features without the burden of high costs, making it accessible to a broader audience.

The decision to reimplement is based on the desire to create a solution that is both comprehensive and user-friendly, addressing the specific needs of event organizers who may find existing solutions too complex, expensive, or inflexible.
`

# SDLC Lifecycle at ASHLAR

## Project Initiation, Requirements Gathering, and Validation
**Actors:** Project Supervisor/Product Owner or designated team member

- Collaborate with clients to gather and validate project requirements.
- Create wireframes using Figma for visualizing requirements and obtaining client feedback if required.
- Conduct meetings or use video demos (using Loom) to ensure alignment with client expectations.

## Project Planning, Risk Management, and Dev Server Setup
**Actors:** Project Supervisor/Product Owner and Scrum Master/Team Lead or designated team member

- Break down requirements, product vision, or epic into user stories and create a prioritized backlog in Trello.
- Plan and evaluate effort for each task with the team and assign them to appropriate team members.
- Plan sprints or timelines based on project type and client needs.
- Identify and manage potential risks through a risk management plan.
- Set up a dev server for transparent collaboration and review of web applications.

## Development and Implementation
**Actors:** Scrum Master/Team Lead

- Use GitHub for version control, collaboration, and code reviews, creating a repository for each project and implementing a branching strategy. <!-- ToDo by subtainishfaq add link of github strategy, repository naming convention and branching strategy -->
- Integrate Trello and GitHub with Slack for real-time project progress updates.
- Utilize Slack for team communication and discussing project-related matters.

## Testing and Quality Assurance
**Actors:** Scrum Master/Team Lead and QA Team

- Conduct regular testing throughout the development process.
- Use Sentry for bug reporting and create Trello cards to track and prioritize discovered bugs.
- Assign bugs to appropriate team members for resolution.

## Deployment, Monitoring, and Continuous Improvement
**Actors:** Scrum Master/Team Lead and DevOps Team

- Deploy the project to the production environment after development and testing.
- Monitor application performance and stability using tools like Sentry.
- Follow an iterative Agile approach for long-term projects, refining the product backlog and adapting plans based on feedback.

## Stakeholder Communication, Documentation, and Updates
**Actors:** Project Supervisor/Product Owner or designated team member

- Maintain consistent communication with stakeholders and solicit their feedback.
- Share periodic Loom videos or schedule meetings to update clients on project progress.
- Document projects comprehensively using tools like GitHub Wiki and readme.md. <!-- ToDo add documentation strategy -->
- Adapt communication styles to fit the nature of non-web projects.

## Performance Metrics and Team Development
**Actors:** Project Supervisor/Product Owner or designated team member

- Track key performance metrics to ensure project success and identify areas for improvement.
- Encourage team members to improve their skills through training programs and professional development opportunities.

## Continuous Integration (CI)
**Actors:** Scrum Master/Team Lead and DevOps Team

- Set up a CI tool (Github Actions or Circle CI) to automate code building and testing on each commit.
- Run unit, integration, and other relevant tests, as well as code quality checks.

## Continuous Deployment (CD)
**Actors:** Scrum Master/Team Lead and DevOps Team

- Implement a CD tool or service (e.g., Github Action) for automated deployment to staging or production environments after successful building and testing.

By involving the appropriate actors in each phase, ASHLAR ensures effective collaboration, communication, and coordination throughout the SDLC, leading to successful software development projects.

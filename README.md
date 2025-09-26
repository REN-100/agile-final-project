Agile Final Project: E-commerce Product Catalog Backend
Project Overview
This project demonstrates the application of Agile methodologies and DevOps practices by creating a Kanban board, product backlog, and sprint plan for developing the backend of an e-commerce product catalog system.

Scenario
Our team has been tasked with developing a comprehensive backend product catalog for an e-commerce website. The system must support full CRUD (Create, Retrieve, Update, Delete) operations, product engagement features (likes/dislikes), and be deployed in a cloud environment with automated deployment capabilities.

Stakeholder Requirements
The product must support the following capabilities:

Core Product Operations
Create a product - Add new products to the catalog

Retrieve a product - Fetch specific product details

Update a product - Modify existing product information

Delete a product - Remove products from the catalog

Product Engagement Features
Like a product - Allow users to like products

Dislike a product - Allow users to dislike products

Product Listing & Search
List all products - Display complete product catalog

Query products - Search/filter products based on criteria

Infrastructure & Deployment
Cloud hosting - Deploy application to cloud environment

Automated deployments - Implement CI/CD pipeline for automatic deployments

Project Structure
text
agile-final-project/
│
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── user-story.md
├── docs/
├── src/
├── README.md
└── (other project files)
Agile Artifacts
Kanban Board Columns
Icebox: Low-priority features for future consideration

Product Backlog: Prioritized list of all requirements

Sprint Backlog: Current sprint's committed work items

In Progress: Actively being developed

Review/QA: Ready for testing and quality assurance

Done: Completed and accepted work

Current Sprint Status
Sprint Name: Sprint
Duration: 2 weeks
Team Capacity: 4 story points

Sprint Progress:
✅ Create a product - Completed (Done)

✅ Retrieve a product - Completed (Done)

🔄 Update a product - In Progress

⏳ Delete a product - Sprint Backlog (Not started)

Technical Implementation Notes
Acceptance Criteria Format
All user stories follow the Gherkin syntax for clear, testable acceptance criteria:

gherkin
Given [precondition]
When [action performed]
Then [expected outcome]

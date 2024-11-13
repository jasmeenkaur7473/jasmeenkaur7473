# Hiring Platform Application

A web-based hiring platform application built with React, designed to streamline the recruitment process by organizing job postings, candidates, and assessments.

## Features

- **Dashboard**: Overview of job postings and candidate applications.
- **Job Posting**: Displays detailed information about each job role available for application.
- **Candidate Management**: Allows viewing and managing candidates who have applied for specific job roles.
- **Assessments**: Provides functionality to view assessments associated with job postings.

## Technologies Used

- **Frontend**: React, React Router DOM
- **Component Library**: Custom components (`QuestionCard`, `JobPostingCard`, etc.)
- **API Integration**: (Specify any backend or API used if applicable)
- **Styling**: (Specify any CSS libraries or frameworks, e.g., TailwindCSS or custom CSS)

## Project Structure


## Getting Started

### Prerequisites

- **Node.js** and **npm** installed.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/hiring-platform-app.git
   cd hiring-platform-app
Install dependencies:

bash
Copy code
npm install

Start the application:

bash
Copy code
npm start
Navigate to: http://localhost:3000 to view the application.

Routing Structure
The application uses react-router-dom for navigation:

/: Renders the Dashboard component.
/candidates/:jobId: Renders the Candidates component to manage applications for a specific job.
/assessment/:jobId: Renders the Assessment component for assessments related to a job.
/jobapp: Renders the JobApplication component where users can apply for jobs.
Components
QuestionCard: A reusable component to display questions and answers.
JobPostingCard: A reusable component to display job details like title, location, and description.
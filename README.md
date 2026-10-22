# Car Detailing CRM

A web-based Customer Relationship Management (CRM) application designed to manage car detailing business operations, including customers, employees, service jobs, estimates, vendors, and financial workflows.

## Features

- **Customer Management** — Organize and maintain customer records.
- **Employee Management** — Manage employee information.
- **Service Management** — Maintain detailing service information.
- **Job Card Management** — Organize and track service jobs.
- **Estimation** — Manage service estimates and quotations.
- **Vendor Management** — Maintain vendor records.
- **Finance Management** — Support financial workflow management.
- **Notifications** — Manage application notifications.
- **Site Settings** — Configure application settings.

## Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- JavaScript

### Backend
- Python
- Django
- Django REST Framework (if configured in the project)

## Project Structure

```text
Detailing_crm/
├── backend/
│   ├── apps/
│   │   ├── customers/
│   │   ├── employees/
│   │   ├── estimation/
│   │   ├── finance/
│   │   ├── jobcards/
│   │   ├── notifications/
│   │   ├── services/
│   │   ├── site_settings/
│   │   └── vendors/
│   ├── core/
│   ├── manage.py
│   └── requirements.txt
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites

Install the following before running the application:

- Python
- Node.js and npm
- Git

### 1. Clone the repository

```bash
git clone https://github.com/Maruthesh12131/Detailing_crm.git
cd Detailing_crm
```

### 2. Set up the backend

```bash
cd backend

python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt
```

Run database migrations:

```bash
python manage.py migrate
```

Start the Django development server:

```bash
python manage.py runserver
```

The backend will typically be available at `http://127.0.0.1:8000/`.

### 3. Set up the frontend

Open another terminal:

```bash
cd frontend

npm install
npm run dev
```

Open the local URL displayed by Vite in your terminal.

## Configuration

Configure environment variables, database settings, API endpoints, and other application-specific settings according to your local development environment.

Do not commit passwords, secret keys, API tokens, or other sensitive configuration values to version control.

## Development

Contributions and improvements can be managed through Git branches and commits. Test changes locally before pushing them to the repository.


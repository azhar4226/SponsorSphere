
# SponsorSphere

**SponsorSphere** is a web-based Influencer Engagement and Sponsorship Coordination Platform. It facilitates efficient collaboration between sponsors and influencers through streamlined campaign management, ad-request handling, and user role-specific dashboards.

---

## Features

### For Sponsors

- **Campaign Management**: Create, update, delete, and monitor advertising campaigns.
- **Ad Request Management**: Send, negotiate, and track ad requests to influencers.
- **Search Functionality**: Find influencers based on niche, reach, and more.
- **Performance Reports**: Analyze campaign reach, engagement, and ROI.

### For Influencers

- **Ad Request Handling**: View, accept/reject, or negotiate requests from sponsors.
- **Profile Management**: Update profile details like niche and reach for visibility.

### For Admins

- **User Management**: Monitor user activities and flag inappropriate content.
- **Analytics Dashboard**: Access reports on platform performance and engagement.

---

## Project Structure

```plaintext
SponsorSphere/
├── main.py               # Application entry point
├── requirements.txt      # Python dependencies
├── SponsorSphere/        # Core application modules
│   ├── models.py         # Database models
│   ├── api.py            # API endpoints
│   ├── views.py          # View logic
│   ├── templates/        # HTML templates
│   ├── static/           # Static assets (CSS, fonts, etc.)
├── Reports/              # Project reports, diagrams, and SRS
├── Screenshots/          # UML and diagram files
└── instance/
    └── database.db       # SQLite database
```

---

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js (for Tailwind CSS)
- SQLite

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/azhar4226/SponsorSphere.git
   cd SponsorSphere
   ```

2. Set up a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   flask run
   ```

Access the application at [http://127.0.0.1:5000](http://127.0.0.1:5000).

---

## Documentation

### System Architecture

- **Backend**: Flask (Python) for server-side logic.
- **Frontend**: HTML templates styled with Tailwind CSS.
- **Database**: SQLite for data storage.

### Model Diagrams

The platform design includes:

- **Use Case Diagrams**: Illustrate interactions between users and system features.
- **Class Diagrams**: Define system structure and relationships.
- **Data Flow Diagrams (DFDs)**: Represent data movement across the system.

Detailed diagrams can be found in the `Reports/Diagrams` directory.

---

## Contact

For questions or support, contact:

Azhar Quadri
Email: [azharquadri4226@gmail.com](azharquadri4226@gmail.com)
GitHub: azhar4226

---

## Contributing

We welcome contributions to SponsorSphere! To contribute:
    1.  Fork the repository.
    2.  Create a feature branch: git checkout -b feature-name.
    3.  Commit changes: git commit -m "Add feature-name".
    4.  Push to your branch: git push origin feature-name.
    5.  Open a pull request.

---

## Acknowledgments

- Thank you to the contributors who made this project possible.
- Inspiration and guidance from the open-source community.

---

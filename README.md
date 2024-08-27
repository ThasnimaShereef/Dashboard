
# Data Visualization Dashboard
### Overview

This project is a data visualization dashboard built using the MERN stack (MongoDB, Express, React, Node.js). It provides an interactive interface for analyzing and visualizing data from a JSON file. The dashboard features various charts and filters, making it easy to explore key metrics such as intensity, likelihood, relevance, and more.

### **Features**

- **Interactive Filters:** Dropdown filters for End Year, Topic, Sector, Region, PEST, Source, Country, and City. Filters adjust dynamically based on data.
- **Data Visualization:** Multiple chart types (bar, pie, line, radar) are used to visualize data. The dashboard organizes charts in a responsive grid layout.
- **Responsive Design:** Built with Bootstrap, the dashboard is fully responsive and adapts to various screen sizes.
- **Custom Styling:** Dropdowns are compact, charts are bordered, and pie/radar charts are reduced in size for better balance.

### **Technology Stack**

- **Frontend:** React.js, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Visualization:** Chart.js 

### **Project Structure**

```
root/
│
├── backend/                # Node.js/Express.js backend
│   ├── server.js           # Entry point for backend server
│   ├── routes/             # API routes
│   └── models/             # Database models
│
├── frontend/               # React.js frontend
│   ├── src/
│   │   ├── components/     # React components (charts, filters, etc.)
│   │   ├── App.js          # Main app component
│   │   ├── index.js        # React entry point
│   │   └── styles/         # Custom styles
│   └── public/             # Public files (HTML, images)
│
└── README.md               # Project documentation
```
### **Usage**

- The dashboard will automatically load data from the backend (running on `http://localhost:5000`).
- Use the dropdown filters to narrow down the data displayed in the charts.
- Explore various charts to gain insights from the data.


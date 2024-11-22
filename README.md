[# POE-FINAL-Submission
PROG6212
](https://github.com/VutiviBaloyi/POE-FINAL-Submission)

# Contract Monthly Claim System (CMCS)

## Overview
The **Contract Monthly Claim System (CMCS)** is a web-based application designed to streamline the monthly claim submission and approval processes for Independent Contractor lecturers. It automates calculations, enhances administrative workflows, and provides role-specific functionalities for Lecturers, Coordinators, Managers, and HR personnel.

---

## Features
### **Lecturer View:**
- Input hours worked and hourly rate.
- Auto-calculation of final payment.
- Real-time validation checks to ensure accurate data entry.
- Submission of claims with supporting documents.

### **Coordinator/Manager View:**
- Automated validation of claims based on predefined criteria.
- Approval and rejection workflows with optional comments.
- Real-time tracking of claim statuses.

### **Admin View:**
- Processing of approved claims.
- Generation of invoices and summary reports.
- Management of lecturer data, such as updating personal information.

---

## Technical Implementation
### **Technologies Used:**
- **Framework:** ASP.NET Core MVC
- **Frontend:** HTML, CSS, Bootstrap, JavaScript (with jQuery)
- **Backend:** ASP.NET Core, Entity Framework
- **Database:** SQL Server
- **Authentication & Authorization:** ASP.NET Identity
- **Reporting Tools:** Crystal Reports / SQL Server Reporting Services (SSRS)

### **Database Design:**
- **Tables Include:**
  - `Users`: Stores user details for authentication and role-based access.
  - `Claims`: Tracks lecturer claims with hours worked, hourly rate, and status.
  - `Approvals`: Logs coordinator/manager decisions on claims.
  - `Invoices`: Stores generated invoice data.

---

## Installation
### **Prerequisites:**
1. Install [Visual Studio](https://visualstudio.microsoft.com/) with .NET Core SDK.
2. Set up SQL Server.

### **Setup Instructions:**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cmcs.git
   ```
2. Navigate to the project directory:
   ```bash
   cd cmcs
   ```
3. Build the solution in Visual Studio.
4. Configure the `appsettings.json` file to include your database connection string.
5. Apply migrations to set up the database:
   ```bash
   dotnet ef database update
   ```
6. Run the application:
   ```bash
   dotnet run
   ```

---

## Usage
1. **Login/Register:**
   - Admins and Lecturers can register and log in based on their roles.
2. **Lecturer Portal:**
   - Input hours and hourly rates.
   - Submit claims.
3. **Coordinator/Manager Portal:**
   - View submitted claims.
   - Approve or decline claims.
4. **HR Portal:**
   - Process claims and generate invoices.

---

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes with descriptive messages.
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request for review.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
- **Developer:** Your Name  
- **Email:** your.email@example.com  
- **GitHub:** [your-username](https://github.com/your-username)

---

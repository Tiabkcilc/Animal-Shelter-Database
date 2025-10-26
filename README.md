# Grazioso Salvare Animal Shelter Dashboard

## Reflection and Analysis

### How do you write programs that are maintainable, readable, and adaptable?

Writing maintainable, readable, and adaptable programs begins with following clear design principles and modular programming practices. In this project, I achieved this by developing a separate **CRUD Python module (`CRUD_Python_Module.py`)** that handled all database operations. By encapsulating the Create, Read, Update, and Delete logic into a dedicated class, the dashboard code in Project Two remained clean, organized, and easy to understand.  

This modular approach provided several advantages. It allowed me to reuse the same database interface across different components of the application, making future changes—such as updating authentication credentials or modifying database queries—straightforward and low-risk. It also made debugging simpler, as the database logic could be tested independently from the user interface.  

In future projects, this CRUD module could easily be adapted for use in other applications that require interaction with MongoDB or similar databases. For example, it could serve as a foundation for administrative tools, analytics dashboards, or machine learning preprocessing scripts that rely on structured data access.

---

### How do you approach a problem as a computer scientist?

As a computer scientist, I approach problems methodically by breaking them down into smaller, more manageable components. For this project, Grazioso Salvare’s requirements involved building a dashboard that connected to a live MongoDB database and supported user interaction through data visualization. I began by analyzing the project specifications, identifying the key components—**database connection (model)**, **dashboard layout (view)**, and **interactive functionality (controller)**—and then mapped out how each would interact in the overall architecture.  

Compared to previous assignments, this project required a deeper understanding of system integration and data flow between backend and frontend components. I used an iterative approach—testing each part of the system (for example, CRUD operations, filter widgets, and data visualizations) before combining them.  

In future projects, I would continue applying this modular and iterative strategy when creating databases or dashboards. I would also incorporate additional best practices such as data validation, schema design optimization, and error handling to ensure scalability and long-term maintainability.

---

### What do computer scientists do, and why does it matter?

Computer scientists solve problems by designing and implementing computational solutions that make data more accessible, meaningful, and actionable. In this project, my work directly supports Grazioso Salvare’s mission by helping them manage and analyze large volumes of animal shelter data efficiently.  

Through the development of this interactive dashboard, I enabled the organization to quickly identify animals that meet specific training criteria, improving their ability to match dogs with rescue and service opportunities. This not only enhances operational efficiency but also contributes to saving more lives through faster and more informed decision-making.  

Ultimately, the work of computer scientists matters because it bridges the gap between complex data systems and real-world applications. By transforming raw information into usable insights, we empower organizations like Grazioso Salvare to achieve their goals more effectively and make a greater positive impact.

---

## Technologies Used
- **Python 3.10+**
- **MongoDB**
- **Dash (Plotly)**
- **Pandas**
- **Plotly Express**

## Author
**Donovan Taylor**  
Southern New Hampshire University  
Computer Science Major – Cybersecurity Track

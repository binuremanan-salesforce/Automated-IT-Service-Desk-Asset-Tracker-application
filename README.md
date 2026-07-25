## 📊 Data Model

<img width="940" height="443" alt="image" src="https://github.com/user-attachments/assets/a6c5794d-7d0d-4dbc-82e1-a6e3edcc6c23" />

The project is built around four main custom objects:

- 👤 Employee
- 👨‍💻 Technician
- 💻 IT Asset
- 🎫 Service Request

The **Service Request** object is the central object in the application. It connects employees, technicians, and IT assets, allowing the IT team to manage support requests efficiently.

---

## 🔗 Object Relationships

### 👤 Employee → 🎫 Service Request (Lookup)

Each employee can create multiple service requests, but each service request is linked to a single employee. This allows the IT team to identify who raised the request and maintain a complete support history for every employee.

**Relationship:** One Employee → Many Service Requests

---

### 👨‍💻 Technician → 🎫 Service Request (Lookup)

Each service request is assigned to one technician, while a technician can manage multiple service requests. This helps distribute work efficiently and makes it easier to track each technician's workload.

**Relationship:** One Technician → Many Service Requests

---

### 💻 IT Asset → 🎫 Service Request (Lookup)

A service request can be linked to the IT asset that requires support, such as a laptop, desktop, printer, or monitor. Since the same asset may need support multiple times, it can be associated with many service requests throughout its lifecycle.

**Relationship:** One IT Asset → Many Service Requests

---

### 👤 Employee → 💻 IT Asset (Lookup)

Each IT asset is assigned to one employee, while an employee can have multiple IT assets. This helps track asset ownership, monitor equipment allocation, and maintain an accurate inventory.

**Relationship:** One Employee → Many IT Assets

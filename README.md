# 🌍 **Export Management Platform for Indian SMBs**  
**A comprehensive platform to streamline international export processes for Indian small and medium businesses.**  
*Built with innovation for the Amazon Hackathon.*

---
##✅ **MVP Features**

| Feature                 | Description                                                               |
| ----------------------- | ------------------------------------------------------------------------- |
| 🔒 User Authentication  | Secure signup/login using JWT authentication                              |
| 📦 Shipment Management  | Create, update, and track shipments with carrier integration              |
| 🗂️ Document Management | Upload, verify, and manage export documents (Invoice, Packing List, etc.) |
| 🌐 Carrier Integration  | Fetch live shipping rates and schedules from available carriers           |
| 📊 Rate Comparison      | Compare rates between multiple carriers to choose the best option         |
| 🗓️ Schedule Management | View and manage upcoming shipment schedules                               |
| ✅ Document Verification | Validate uploaded documents via automated checks                          |

---

## 🛠️ **Tech Stack**  

| Component    | Technology         |
|--------------|--------------------|
| **Frontend** | React + Vite       |
| **Backend**  | Node.js + Express  |
| **Database** | MongoDB            |
| **Auth**     | JWT                |
| **File Handling** | Multer         |

---

## 📋 **Prerequisites**  
Ensure the following are installed:  
- **Node.js** (v14 or higher)  
- **MongoDB** (local or cloud instance)  
- **npm** or **yarn**  

---

## ⚙️ **Setup Instructions**  

### 1️⃣ Clone the Repository  
```bash
git clone <repository-url>
cd amazon-exportSMB
```

### 2️⃣ Install Frontend Dependencies  
```bash
npm install
```

### 3️⃣ Install Backend Dependencies  
```bash
cd backend
npm install
```

### 4️⃣ Configure Environment Variables  
- Copy `.env.example` to `.env` in the `backend` directory  
- Update the environment variables as required  

### 5️⃣ Start MongoDB  
Ensure MongoDB is running. Default connection:  
```plaintext
mongodb://localhost:27017/freshfruits
```

### 6️⃣ Start the Backend Server  
```bash
cd backend
npm run dev
```

### 7️⃣ Start the Frontend Server  
Open a new terminal and run:  
```bash
npm run dev
```

---

## 📚 **API Documentation**  

### 🔐 **Authentication Endpoints**  
| Method | Endpoint            | Description           |
|--------|---------------------|-----------------------|
| POST   | `/api/auth/register` | Register a new user  |
| POST   | `/api/auth/login`    | Login user           |
| GET    | `/api/auth/me`       | Get current user     |

### 📦 **Shipment Endpoints**  
| Method | Endpoint              | Description          |
|--------|-----------------------|----------------------|
| GET    | `/api/shipments`       | Get all shipments   |
| GET    | `/api/shipments/:id`   | Get single shipment |
| POST   | `/api/shipments`       | Create new shipment |
| PUT    | `/api/shipments/:id`   | Update shipment     |
| DELETE | `/api/shipments/:id`   | Delete shipment     |

### 🗂️ **Document Endpoints**  
| Method | Endpoint              | Description             |
|--------|-----------------------|-------------------------|
| GET    | `/api/documents`       | Get all documents      |
| GET    | `/api/documents/:id`   | Get single document    |
| POST   | `/api/documents`       | Upload new document    |
| PUT    | `/api/documents/:id`   | Update document metadata |
| DELETE | `/api/documents/:id`   | Delete document        |

### 🚛 **Carrier Endpoints**  
| Method | Endpoint                 | Description              |
|--------|--------------------------|--------------------------|
| GET    | `/api/carriers`           | Get available carriers  |
| POST   | `/api/carriers/rates`     | Get shipping rates      |
| POST   | `/api/carriers/schedules` | Get carrier schedules   |
| POST   | `/api/carriers/book`      | Book shipment with carrier |

---

## 👥 **Contributing**  

We welcome contributions!  

1. Fork the repository  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:  
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch:  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request  

---

## 📜 **License**  
This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

### ✨ **Let's Simplify Exporting for Indian SMBs!**

Feel free to reach out if you have any questions or suggestions. 🌟

--- 

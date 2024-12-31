
# **Cloud Playground**

Cloud Playground is a comprehensive suite of cloud-native applications designed for learning, experimentation, and real-world scenarios. This repository contains multiple projects showcasing various aspects of cloud development, from ERP systems to sentiment analysis.

## **Applications**

### 1. **ERP App**
- **Description**: A basic ERP (Enterprise Resource Planning) system demonstrating database management, role-based access control, and operational workflows.
- **Features**:
  - Inventory management.
  - User authentication and authorization.
  - Integration with messaging queues.
- **Technology Stack**:
  - Backend: Node.js/Golang.
  - Database: PostgreSQL/MySQL.
  - Messaging Queue: RabbitMQ/Kafka.

---

### 2. **News Crawler**
- **Description**: A web scraper designed to collect and aggregate news from various online sources.
- **Features**:
  - Customizable crawling settings.
  - Data transformation and storage.
  - API integration for analysis and visualization.
- **Technology Stack**:
  - Backend: Python (Scrapy).
  - Database: MongoDB/Elasticsearch.

---

### 3. **Random Content CDN**
- **Description**: A Content Delivery Network (CDN) for serving random multimedia content globally.
- **Features**:
  - Cache optimization for high performance.
  - Global edge server simulation.
  - File versioning and expiration handling.
- **Technology Stack**:
  - Backend: Node.js/Golang.
  - Storage: AWS S3/Azure Blob Storage.
  - CDN: Cloudflare/Akamai.

---

### 4. **To-Do App**
- **Description**: A minimal to-do list application showcasing CRUD operations and user task management.
- **Features**:
  - User authentication.
  - Task creation, editing, and deletion.
  - Real-time task updates via WebSockets.
- **Technology Stack**:
  - Frontend: React/Angular.
  - Backend: Express.js/FastAPI.
  - Database: SQLite/PostgreSQL.

---

### 5. **Twitter Sentiment Analysis**
- **Description**: A machine learning application for analyzing sentiment from tweets.
- **Features**:
  - Sentiment classification (Positive, Negative, Neutral).
  - Real-time tweet fetching using Twitter API.
  - Model training and prediction capabilities.
- **Technology Stack**:
  - Language: Python (Scikit-learn, TensorFlow).
  - Data Storage: SQLite/NoSQL database.
  - API Integration: Twitter API v2.

---

## **Getting Started**
1. Clone the repository:
   ```bash
   git clone https://github.com/rahulkumar-aws/cloud-playground.git
   ```
2. Navigate to an application folder:
   ```bash
   cd applications/erp-app
   ```
3. Follow the specific `README.md` in each folder for setup and usage instructions.

---

## **Common Features**
- **Cloud-Agnostic**: Applications can be deployed on AWS, Azure, or GCP.
- **Dockerized Deployments**: Each application includes a `Dockerfile` for easy containerization.
- **Learning-Oriented**: Each app serves as a learning module for cloud technologies and real-world use cases.

---

## **Contributing**
We welcome contributions to enhance the features and quality of this project. Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Submit a pull request.

---

## **License**
This project is licensed under the [MIT License](LICENSE).

---

## **Contact**
For any questions or feedback, please contact:
- **Email**: rahulkumar.aws@gmail.com
- **GitHub**: [GitHub Profile](https://github.com/rahulkumar-aws)

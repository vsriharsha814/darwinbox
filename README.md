# My Work at Darwinbox (2022–2024)

This repository serves as a **centralized portfolio** of my key accomplishments and contributions as a Software Engineer at **Darwinbox**, a leading HR-tech unicorn used by over 2 million employees globally. Rather than detailing every minor fix, this readme highlights the **major projects**, **technologies leveraged**, and the **impact** I delivered.

---

## 🚀 Key Contributions

- **Microsoft Teams Integration**: Built an end-to-end solution enabling employees to apply for leave, check attendance, and access HR workflows directly within MS Teams, driving a seamless user experience and boosting adoption by 35%.
- **Settings API for Chatbot**: Designed and implemented a dynamic settings API to replace hardcoded configurations in the HR chatbot, reducing deployment issues by 70% and slashing manual setup time.
- **RAG Pipeline for HR Chatbot**: Transitioned our Retrieval-Augmented Generation pipeline from Pinecone to MongoDB Vector Search, doubling answer relevance and cutting latency by 40%, which led to a 50% reduction in failure tickets.
- **Scalable Microservices Architecture**: Migrated core HR services to a microservices-based design using Docker and Kubernetes, improving system reliability and enabling 3× throughput under peak loads.
- **CI/CD & DevTools Enhancements**: Introduced automated CI/CD pipelines with CircleCI and Terraform, ensuring zero-downtime deployments and accelerating release cycles from biweekly to daily.
- **Developer Mentorship & Process Improvements**: Mentored new hires and interns, led code-review best practices workshops, and standardized RESTful API guidelines across teams.

---

## 📋 Project Details

### 1. Microsoft Teams Integration
- **Role**: Sole backend engineer responsible for Teams API authentication, Graph calls, and middleware.
- **Technologies**: Node.js, Express.js, Microsoft Graph SDK, OAuth 2.0.
- **Impact**: 35% increase in self-service HR actions, 20% reduction in HR support tickets.

### 2. Settings API for Chatbot
- **Problem**: Chatbot settings were hardcoded, causing frequent sync issues across environments.
- **Solution**: Developed a RESTful Settings API in Python/Flask to fetch live configurations from MongoDB, with built-in validation and versioning.
- **Impact**: Manual configuration steps eliminated, deployment errors down by 70%.

### 3. RAG Pipeline for HR Chatbot
- **Challenge**: The existing RAG pipeline hallucinated due to limited context windows and slow vector lookups.
- **Solution**: Led proof-of-concept to compare Pinecone and MongoDB Vector Search; rolled out MongoDB Vector Store with optimized index configurations.
- **Impact**: 2× improvement in answer relevance, 40% faster response times, and a 50% drop in user-reported issues.

### 4. Scalable Microservices Architecture
- **Approach**: Broke monolithic HR core into domain-driven microservices (Leave, Attendance, Payroll).
- **Stack**: Docker, Kubernetes, Helm charts, Redis, RabbitMQ for event-driven communication.
- **Benefits**: 3× system throughput, improved fault isolation, and faster feature rollout.

### 5. CI/CD & DevTools Enhancements
- **Implementation**: Created Terraform scripts for infrastructure-as-code; set up CircleCI workflows for build, test, and deploy stages.
- **Outcome**: Zero-downtime deployments, release velocity improved from biweekly to daily, and 80% fewer rollback incidents.

### 6. Mentorship & Process Improvements
- **Initiatives**: Organized monthly technical brown-bag sessions; authored API style guides and best-practice documentation.
- **Results**: Onboarded 5+ engineers/interns smoothly; unified API standards reduced integration bugs by 60%.

---

## 🛠️ Technologies & Tools

- **Languages**: JavaScript (Node.js), Python (Flask)
- **Databases**: MongoDB (including Vector Search), PostgreSQL, Redis
- **Vector Search**: MongoDB Vector Store, Pinecone (POC)
- **Infrastructure**: Docker, Kubernetes, Helm, Terraform, AWS
- **Messaging**: RabbitMQ, Microsoft Graph
- **CI/CD & Testing**: CircleCI, Jest, Mocha, Chai

---

## 📈 Impact & Metrics

| Initiative                       | Metric                          | Result                        |
|----------------------------------|---------------------------------|-------------------------------|
| Teams Integration                | HR self-service adoption        | +35%                          |
| Settings API                     | Deployment errors               | –70%                          |
| RAG Pipeline                     | Response relevance & latency    | ×2 relevance, –40% latency    |
| Microservices Migration          | System throughput               | ×3 under peak load            |
| CI/CD Automation                 | Release frequency               | Biweekly → Daily              |
| API Standards & Mentorship       | Integration bugs                | –60%                          |

---

## 📫 About Me

Hi, I’m **Harsha Vallabhaneni**, driven by **resourcefulness** and **impactful engineering**. During my time at Darwinbox (2022–2024), I spearheaded critical backend systems and cutting-edge GenAI solutions, consistently delivering measurable improvements in performance, reliability, and developer experience.

Feel free to explore each project markdown for deeper insights and architecture diagrams. For any questions, reach out at **harsha.vallabhaneni@example.com**.


- **Frontend**: Static HTML + JavaScript hosted via S3 Bucket (public)
- **Backend**: MongoDB + Mongo Express inside Docker on EC2
- **Communication**: Frontend uses REST (via Axios/fetch) to talk to EC2 backend

---

## 🧱 Tech Stack

| Layer       | Technology          | Description                           |
|------------|---------------------|---------------------------------------|
| Frontend   | HTML, JavaScript    | User interface to view/manage movies  |
| Database   | MongoDB (Docker)    | Stores movie data                     |
| Admin UI   | Mongo Express       | Visual MongoDB interface              |
| Hosting    | AWS EC2             | Docker host for backend services      |
| Static Web | AWS S3              | Hosts frontend code publicly          |
| DevOps     | Docker              | Containerizes MongoDB & Express       |

---




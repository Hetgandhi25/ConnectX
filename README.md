# ConnectX 📱  

*A Social Media Database Management System*  

ConnectX – Social Media Database is a PostgreSQL relational database project designed to simulate the backend of a social media platform. It manages users, posts, comments, likes, follows, messages, and groups, ensuring data consistency and scalability. The project includes ER and relational diagrams normalized to BCNF, and uses SQL for data definition, manipulation, indexing, and optimized queries, all managed through pgAdmin 4.

**Associated with Dhirubhai Ambani Institute of Information and Communication Technology (DA-IICT)**  



---

## 📌 Key Features  
- 👤 **User Accounts** – Register, log in, verify users, and manage profiles (username, name, bio, picture, multiple emails, multiple contacts)  
- 📝 **Posts** – Create posts with captions, locations, and upload media (images, videos, audio)  
- 🏷️ **Tags** – Tag users in posts  
- ❤️ **Likes & Comments** – Like/unlike posts and comments, add comments with timestamps  
- 👥 **Follow System** – Follow or unfollow other users  
- 📂 **Collections** – Create collections and save posts into them  
- 👪 **Groups** – Create groups, join/leave groups, and manage memberships  
- 💬 **Messaging** – Send private messages between users or group messages, with timestamps  
- 📢 **Advertisements** – Store ad details and place ads on posts  
- ⏱️ **Timestamps & Integrity** – Track post dates, likes, comments, and messages while maintaining referential integrity  

---

## 🏗️ Database Design  
- ER & Relational diagrams designed in **BCNF**  
- Minimal functional dependencies for efficiency  
- Managed with **pgAdmin 4**  

📊 **Entities include:**  
`User`, `Post`, `Comment`, `Likes`, `Follow`, `Message`, `Group`, `Collection`, `Ad`, `Tag`  

---

## ⚙️ Tech Stack  
- **Database:** PostgreSQL  
- **Tool:** pgAdmin 4  
- **Design:** ER & Relational diagrams  
- **SQL:** DDL, DML, Indexing, Joins, Advanced Queries  

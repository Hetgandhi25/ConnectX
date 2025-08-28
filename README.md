---

# ConnectX 📱

*A Social Media Database Management System*

![Institute Logo](https://upload.wikimedia.org/wikipedia/en/thumb/5/56/DA-IICT_logo.svg/1200px-DA-IICT_logo.svg.png)
**Associated with Dhirubhai Ambani Institute of Information and Communication Technology (DA-IICT)**

---

## 📝 Summary

ConnectX is a **PostgreSQL relational database project** that models a social media platform.
It manages **users, posts, comments, likes, follows, messages, and groups**, providing a scalable and normalized DBMS design with advanced SQL queries and efficient data handling.

---

## 📌 Overview

ConnectX is a **PostgreSQL-based relational database** designed to simulate the backend of a **social media platform**.
The system efficiently manages **users, posts, comments, likes, follows, messages, and groups**, ensuring:

* ✅ Data **consistency**
* ✅ High **scalability**
* ✅ Efficient **query optimization**

This project demonstrates a **real-world DBMS design** with complete normalization, entity-relationship modeling, and advanced SQL operations.

---

## 🔑 Features

* **User Management** – Profiles, contacts, emails, bios, profile pictures, and authentication.
* **Posts & Media** – Captions, images, videos, songs, locations, and post timestamps.
* **Likes & Comments** – Post likes, comment likes, threaded comments with timestamps.
* **Follow System** – Users can follow/unfollow others.
* **Messaging** – Private and group messaging with timestamps.
* **Groups & Collections** – Create/join groups, save posts into collections.
* **Ads Integration** – Posts associated with advertisers and campaigns.
* **Tags** – User tagging in posts.

---

## 🏗️ Database Design

* **ER Diagram & Relational Schema** designed in **BCNF (Boyce-Codd Normal Form)** for maximum efficiency.
* Includes **minimal functional dependencies** to reduce redundancy.
* Database managed using **pgAdmin 4**.

📊 **Relational Schema Includes:**

* `User`, `User_email`, `User_contact`
* `Post`, `Post_comment`, `Likes`, `Comment_Likes`
* `Follow`, `Message`, `Group`, `In1`
* `Tag`, `Collection`, `Ad`, `Placed_as`, `Saved_as`

---

## ⚙️ Tech Stack

* **Database:** PostgreSQL
* **Management Tool:** pgAdmin 4
* **Modeling:** ER Diagrams, Relational Diagrams
* **Techniques:** SQL DDL, DML, Indexing, Joins, Advanced Queries
* **Normalization:** BCNF

---

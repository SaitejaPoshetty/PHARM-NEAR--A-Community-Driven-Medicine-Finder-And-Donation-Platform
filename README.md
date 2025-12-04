PHARM NEAR – Community-Driven Medicine Finder & Donation Platform**

📌 **Overview**
Pharm Near is a socially impactful web platform designed to connect medicine donors, seekers, NGOs, and pharmacies in real time. The system reduces medicine scarcity by enabling users to search for nearby available medicines using their live location while encouraging responsible donation of unused but valid medicines. Pharm Near ensures safe and verified redistribution through NGO/pharmacy approval, preventing wastage and improving accessibility—especially in rural and underserved communities.

---

📊 **Methodology**

**🔹 Requirement Analysis:** Understanding gaps in medicine accessibility and identifying key stakeholders—donors, seekers, NGOs.
**🔹 Data Handling:** Collecting and storing medicine information such as name, expiry date, quantity, and donor details.
**🔹 Location-Based Matching:** Using geolocation and the Haversine algorithm to compute distances between donors and seekers.
**🔹 Backend Development:** REST APIs built with Flask/Node.js to manage donations, authentication, and real-time search.
**🔹 Database Design:** Storing user roles, medicine details, and request logs using SQLite/MongoDB.
**🔹 Verification Workflow:** NGOs/pharmacies authenticate medicine quality and approve donations.
**🔹 Evaluation Metrics:** System tested for accuracy, response time, scalability, and data security.

---

📂 **Project Structure**

```
/pharm-near
├── pharm_near.db                # Database
├── backend.py / app.py          # Flask backend with APIs
├── static/                      # CSS, JS, UI assets
├── templates/                   # HTML pages (donor, seeker, NGO portal)
├── requirements.txt             # Dependencies
├── README.md                    # Project documentation
```

---

⚙️ **Setup Instructions**

1️⃣ **Clone the Repository**

```
git clone https://github.com/your-repo/pharm-near.git
cd pharm-near
```

2️⃣ **Install Dependencies**

```
pip install -r requirements.txt
```

3️⃣ **Run the Application**

```
python app.py
```

---

🎯 **Features**

✅ Search nearby medicines using live location
✅ Donate unused but valid medicines
✅ NGO/pharmacy verification system
✅ Real-time tracking of donations & requests
✅ Secure authentication for all user roles
✅ User-friendly interface for donors & seekers
✅ Environmental impact reduction by preventing medication waste
✅ Transparent, community-driven healthcare support

---

🚀 **Future Improvements**

🔹 AI-based medicine recommendation system
🔹 Push notifications when required medicines become available nearby
🔹 Fully responsive mobile app (Android/iOS)
🔹 Blockchain-based verification for high-trust medicine tracking
🔹 Integration with government health databases
🔹 Enhanced analytics dashboard for NGOs

---

If you want, I can also create:
✅ A polished **README.md**
✅ A **project abstract (150/250/300 words)**
✅ A **poster or presentation content**

Just tell me!

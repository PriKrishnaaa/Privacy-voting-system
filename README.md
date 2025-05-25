🗳️ Easy Polls: Privacy-First Voting System
Easy Polls is a lightweight, privacy-centric voting system built with Python Flask. It allows users to participate in anonymous polls while protecting their identity using secure UUID-based authentication and minimal data storage.

✨ Key Features:
🔐 UUID-Based Voter Authentication
Each user is assigned a unique, non-trackable ID without storing personal information.

📋 Create & Vote on Custom Polls
Users can participate in polls that are pre-defined in CSV format.

📄 CSV Storage
Votes are stored securely in a flat CSV file instead of a database to ensure transparency and ease of audit.

🧠 Stateless, Simple Architecture
No login required; the system doesn't store names or emails, ensuring user anonymity.

📊 Real-Time Vote Counting
Results can be viewed immediately after voting, with duplicate submissions prevented per UUID.

🛡️ Minimalistic UI for Accessibility
Designed for ease-of-use even on low-bandwidth systems or mobile devices.


🚀 How to Run
bash
Copy
Edit
pip install Flask
python app.py
Visit: http://127.0.0.1:5000 in your browser to vote.😊



🔐 Why Privacy Matters
This project is designed to be used in settings where identity protection is crucial — like student elections, anonymous surveys, or feedback collection — without depending on heavy authentication or third-party tools.


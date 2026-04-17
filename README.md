# 🏥 Hospital Management System

A simple and efficient **Hospital Management System** built using Python and Tkinter.
This application helps manage doctors, patients, and appointment assignments with an easy-to-use graphical interface.

---

## 📌 Features

* 👨‍⚕️ Manage Doctors (Add & View)
* 🧑‍🤝‍🧑 Manage Patients (Add, Edit, Delete)
* 🩺 Automatic Doctor Assignment based on specialization
* ⏳ Waiting List for unavailable doctors
* 💾 Data Persistence using JSON files
* 🖥️ User-friendly GUI with Tkinter

---

## 🛠️ Technologies Used

* Python 🐍
* Tkinter (GUI Framework)
* JSON (Data Storage)
* OS Module (File Handling)

---

## 📂 Project Structure

```
Hospital-Management-System/
│
├── main.py
├── doctors.json
├── patients.json
└── README.md
```

---

## ⚙️ How It Works

* Doctors are stored with their specialization and availability.
* When a patient is added:

  * The system searches for an available doctor with matching specialization.
  * If found → Doctor is assigned.
  * If not → Patient is added to the waiting list.
* All data is stored locally using JSON files.

---

## 🚀 How to Run

1. Install Python (3.x)

2. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

3. Navigate to project folder:

   ```bash
   cd Hospital-Management-System
   ```

4. Run the application:

   ```bash
   python main.py
   ```

---

## 🖼️ Screens

* Patient Management Tab
* Doctor Management Tab
* Table View for Records

---

## 📊 Sample Data

Default doctors are automatically loaded if no data file exists:

* Dr. John Doe – Cardiology
* Dr. Jane Smith – Neurology
* Dr. Mark Johnson – Orthopedics

---

## ⚠️ Limitations

* No database (uses JSON instead)
* No authentication system
* Basic UI (Tkinter-based)

---

## 🔮 Future Enhancements

* 🔐 Login System (Admin/User)
* 🗄️ Database Integration (MySQL / Firebase)
* 📱 Web or Mobile App Version
* 📅 Appointment Scheduling System
* 📊 Reports & Analytics

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Developed by **Sai Tharun**

---

⭐ If you like this project, give it a star on GitHub!

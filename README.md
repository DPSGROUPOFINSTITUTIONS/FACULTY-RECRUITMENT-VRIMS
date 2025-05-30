# Faculty Recruitment Dashboard  
**Viraat Ramayan Institute of Medical Sciences**  
Location: VPO Koyla Belwa, PS Chakia, District East Champaran, Bihar, PIN 845412

## 🧩 Project Overview

This is a responsive, interactive, single-page **Faculty Recruitment Dashboard** for managing faculty recruitment processes, tracking real-time vacancies, and visualizing staff positions across multiple departments of a medical institute. It includes user login, role-based access, faculty records management, vacancy tracking, and data visualization using Chart.js.

## 🛠️ Features

- 📊 **Real-Time Vacancy Dashboard**  
  Department-wise listing of vacant vs. filled positions for various roles.

- 🧑‍🏫 **Faculty Management**  
  - Add new faculty
  - Edit/update faculty records
  - View recruited faculty in tabular format

- 🔒 **User Authentication**
  - Role-based login (Admin/User)
  - Session-based UI updates

- 🧾 **Audit Log**  
  Record of user activities for administrative review.

- 📈 **Vacancy Visualization**  
  Interactive bar chart displaying filled vs. vacant positions using Chart.js.

- 🧠 **AI Prompt Integration (Stub)**  
  Placeholder for future AI recommendations based on recruitment needs.

## 📁 Project Structure

```
index.html           # Main HTML file containing entire frontend logic
dist/styles.css      # TailwindCSS compiled stylesheet (external reference)
logo.png             # Institute logo displayed in header
```

## 💻 Tech Stack

- **HTML5, CSS3 (TailwindCSS)**
- **JavaScript (Vanilla)**
- **Chart.js** (for vacancy visualization)
- **LocalStorage** for session simulation
- **Mock Backend Integration** (with `localhost:4040` fallback)

## 🔧 Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone https://your-repo-url
   cd your-folder
   ```

2. **Serve the HTML**
   You can open `index.html` directly in a browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server
   ```

3. **Login Credentials (Demo Mode)**
   - Admin: `admin / admin123`
   - User: `user / user123`

> For live server-side integration, connect APIs at `http://localhost:4040/api`.

## 🚀 Future Enhancements

- Integrate with real database (e.g., MongoDB, MySQL)
- Add server-side authentication (JWT)
- Role-based CRUD permissions
- Excel export/import for bulk recruitment data
- AI-based faculty requirement prediction

## 🤝 Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under [MIT License](LICENSE).

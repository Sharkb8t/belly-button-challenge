# belly-button-challenge
# 📌 Belly Button Biodiversity Dashboard

## 📖 Description
This interactive dashboard visualizes microbiome data collected from human belly buttons. It allows users to explore bacterial sample data, view metadata, and analyze different bacterial cultures through interactive bar and bubble charts.

## 📍 Features

- **Dropdown Selector**: Choose a test subject ID to update the charts dynamically.

- **Bar Chart**: Displays the top 10 bacterial Operational Taxonomic Units (OTUs).

- **Bubble Chart**: Shows the distribution of all OTUs per sample.

- **Demographic Panel**: Displays metadata for the selected sample.

## 💻 Technologies Used

✔️ **JavaScript (D3.js, Plotly.js)** - Data handling & visualization.

✔️ **HTML, CSS, Bootstrap** - Layout and styling.

✔️ **GitHub Pages** - Project deployment.

## 🛠️ Installation & Setup

### 1️⃣ **Clone the repository**
   ```sh
   git clone https://github.com/your-username/belly-button-challenge.git
   ```
### 2️⃣ **Navigate to the project directory**
   ```sh
   cd belly-button-challenge
   ```
### 3️⃣ **Open with a local server** (required for JSON loading)
   - **Using Python**:
     ```sh
     python -m http.server 8000
     ```
   - **Using VS Code Live Server**:
     - Open `index.html` in VS Code.
     - Right-click and select **Open with Live Server** (Live Server Extension must be installed and enabled).
### 4️⃣ Open the browser and go to:
   ```
   http://localhost:8000/index.html
   ```

## 🗄️ Repository Structure
```
📁 belly-button-challenge
├── 📄 index.html         # Main HTML file for the website Dashboard structure
├── 📄 samples.json       # Data source file for JavaScript application
├── 📁 static             # Static asset JS
│   ├── 📁 js
│   │   ├── 📄 app.js     # Main JavaScript file
└── 📄 README.md          # Documentation of project info
```

## 🪛 Usage

- Select a **Sample ID** from the dropdown to view bacterial composition.

- Hover over **bubbles** in the chart for bacterial taxonomy details found in each sample.

- View demographic information for the individual whom the sample represents in the panel.


## :Resources

📘 Data Source: **Belly Button Biodiversity Dataset** (Reference `samples.json` file in project directory)

📗 Developed using **D3.js, Plotly.js, and Bootstrap**

---


# 🌤️ Power BI Weather Dashboard

This project is a dynamic and interactive **Weather Dashboard built in Power BI**. The dashboard visualizes real-time weather data for selected cities using data extracted from the **OpenWeatherMap API**.

---

## 📌 Project Overview

- Extracts **current weather data** and **5-day forecasts** via API
- Processes and visualizes data in **Power BI**
- Supports multiple locations with filtering and drill-down capabilities
- Automatically refreshes using Power BI's **scheduled refresh**
  
---

## 🌐 Data Source

- **API Used**: [OpenWeatherMap API](https://openweathermap.org/api)
- **Data Format**: JSON
- **Extract Method**: Power BI Web connector (`Web.Contents` function) or Power Query (`Power Query M` script)

---

## 📥 How It Works

1. API URL is generated for a selected city (or list of cities)
2. Power Query fetches the JSON data via `Web.Contents`
3. The data is transformed and cleaned
4. Dashboard visuals are built (KPIs, charts, cards, maps, etc.)

---

## 🔐 Security Note

Avoid sharing your API key publicly. Use Power BI parameter settings or store API keys in secured locations like Azure Key Vault (if using Power BI Premium).

---

## 🙋‍♂️ Contributing

Feel free to fork the repo, raise issues, or contribute improvements. All feedback is welcome!

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

For questions or support:

📧 shivam1234pawar@gmail.com

🔗 https://www.linkedin.com/in/shivam-dharpure-2570071b5


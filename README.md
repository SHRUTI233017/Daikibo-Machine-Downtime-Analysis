# 🚀 Daikibo Machine Downtime Analysis

### *Turning Raw Telemetry into Actionable Insights*

📊 **Tableau| Manufacturing Analytics**

---

## 🧠 Project Summary

Daikibo is a global manufacturing company operating multiple factories worldwide.
This project analyzes **machine telemetry data** collected every **10 minutes** from **9 machine types** across **4 factories** to identify **downtime hotspots** and **frequent machine failures**.

The goal is simple:
👉 **Find where machines fail the most and why.**

---

## 🌍 Factory Locations

| Factory  | City     | Country |
| -------- | -------- | ------- |
| Meiyo    | Tokyo    | Japan   |
| Seiko    | Osaka    | Japan   |
| Berlin   | Berlin   | Germany |
| Shenzhen | Shenzhen | China   |


---

## 🎯 Business Questions

✔ Which factory experienced the **highest machine downtime**?

✔ Which **machine types** broke down most frequently in that factory?

---

## 📦 Dataset Overview

* **Duration:** May 2021 (1 Month)
* **Frequency:** Every 10 minutes
* **Machines:** 9 device types per factory

**Key Fields Used**

* Factory
* Device Type
* Status (Healthy / Unhealthy)
* Timestamp

---

## 🧮 Calculated Measure

### 🔢 `Unhealthy`

* Assigns **10 minutes of downtime** for each `Unhealthy` status
* Represents downtime since telemetry is sent every 10 minutes

This converts raw status data into **meaningful downtime metrics**.

---

## 📊 Visualizations

### 📌 Down Time per Factory

**Chart Type:** Bar Chart

* Identifies which factory suffers the most downtime
* <img width="935" height="778" alt="Screenshot 2026-01-06 000318" src="https://github.com/user-attachments/assets/aecb24bb-dc06-476b-bdf5-5b7f6705973d" />


### 📌 Down Time per Device Type

**Chart Type:** Bar Chart

* Highlights machines responsible for frequent failures
* <img width="992" height="756" alt="Screenshot 2026-01-06 000353" src="https://github.com/user-attachments/assets/2c3f684a-340d-4167-a63d-33122010691c" />


---


## 🔍 Key Insights

🔴 **Daikibo Factory Seiko (Osaka)** recorded the **highest downtime**
🔴 **Laser Welder machines** failed most frequently
🔴 Indicates maintenance and process optimization gaps

---

## 💡 Business Impact

✅ Found the factory with the most machine failures.
✅ Identified high-risk machines
✅ Enabled targeted maintenance planning
✅ Reduced guesswork with data-backed insights

---

## 🏁 Final Outcome

This project demonstrates how **machine telemetry + visualization** can uncover operational inefficiencies and guide **data-driven manufacturing decisions**.



Just say the word 💬

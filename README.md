# 📘 HealthKart Influencer Campaign Dashboard

## 🎯 Objective

To build a fully interactive dashboard that visualizes and analyzes the Return on Ad Spend (ROAS), engagement rates, and overall performance of influencer campaigns across major social platforms. This tool is designed to help HealthKart make data-driven decisions about influencer investments and optimize ROI.

---

## 🌐 Live Demo

🔗 **Try the Dashboard Online (Deployed on Streamlit Cloud)**

👉 [https://healthkart-influencer-dashboard.streamlit.app](https://healthkart-intern-assignment-53whkyl8xbznt8xm7gaeuk.streamlit.app/)

---

## 📁 Project Structure

```
├── influencers.csv            # Influencer profile information
├── posts.csv                  # Influencer post reach, likes, comments
├── tracking_data.csv          # User purchases and revenue from influencer tracking
├── payouts.csv                # Payment logic and compensation per influencer
├── influencer_metrics.csv     # Computed metrics like ROAS, engagement, efficiency
├── app.py                     # Streamlit code to run the dashboard
├── README.md                  # Project documentation
```

---

## ⚙️ Setup Instructions (Local Deployment)

1. **Clone the Repository:**

```bash
git clone https://github.com/yourusername/healthkart-influencer-dashboard.git
cd healthkart-influencer-dashboard
```

2. **Install Required Libraries:**

```bash
pip install -r requirements.txt
```

3. **Run the Streamlit App:**

```bash
streamlit run influencer_dashboard.py
```

---

## 🧠 Metrics Computed

* **ROAS (Return on Ad Spend)** = `Revenue / Total Payout`
* **Engagement Rate** = `(Likes + Comments) / Reach`
* **Payout Efficiency** = `Revenue / Payout`
* **Influencer Tiering**:

  * Nano: < 10K followers
  * Micro: 10K–100K
  * Macro: 100K–500K
  * Mega: > 500K

---

## 📊 Dashboard Features

* Filter influencers by:

  * Platform (Instagram, YouTube, Twitter)
  * Gender
  * Category (Fitness, Wellness, etc.)
  * Influencer Tier
* Visualizations:

  * ROAS Histogram
  * Engagement Rate vs ROAS (scatter)
  * Payout Efficiency Leaderboard (bar chart)
* KPIs:

  * Total Revenue, Payout, Average ROAS
* CSV Export of filtered results

---

## 📈 Use Case Scenarios

* Identify high-ROI influencers for future partnerships
* Spot low-performing influencers to renegotiate or remove
* Choose ideal platforms and categories for product launches
* Guide influencer budget planning and brand strategy

---

## 📥 Deliverables

* 📊 Dashboard: Visual & Interactive Streamlit UI
* 📄 Insights Summary: Word/PDF Report with analysis (available on request)
* 📑 README: Full project documentation
* 🗂️ CSV datasets (influencer, posts, tracking, payouts, metrics)

# Unit-Cost Reduction Tracker

An end-to-end FP&A toolkit to forecast per-unit costs, run “what-if” scenarios on volume & process levers, and deliver a monthly dashboard of actual vs. target cost-reduction KPIs.

---

## 🚀 Project Structure
1. 📄 `README.md`  
2. 📂 `data/`  
   1. 🗂 `raw/`  
      1. 📄 `commodity_prices.csv`    # FRED global price index  
      2. 📄 `labor_rates.csv`         # BLS manufacturing avg hourly earnings  
      3. 📄 `futures_gold.csv`        # Quandl gold futures  
   2. 🗂 `processed/`  
      1. 📄 `sample_cost_data.csv`    # Merged & cleaned cost‐driver extract  
3. 🛠️ `scripts/`  
   1. 📄 `extract_fred.py`            # Download & save FRED CSVs  
   2. 📄 `extract_bls.py`             # Download & save BLS CSVs  
   3. 📄 `extract_quandl.py`          # Fetch & save futures via Quandl API  
4. 🗄️ `sql/`  
   1. 📄 `extract_cost_data.sql`      # Pull historical cost data into Snowflake  
   2. 📂 `views/`                     # Snowflake views for baseline & scenarios  
   3. 📂 `procs/`                     # Stored procedures for scenario generation  
5. 📊 `excel/`  
   1. 📄 `cost_forecast_prototype.xlsx`  
6. 🐍 `python/`  
   1. 📄 `monte_carlo_simulation.ipynb`  
7. 📈 `power_bi/`  
   1. 📄 `UnitCostDashboard.pbix`  
8. 📚 `docs/`  
   1. 📄 `requirements.md`            # Data & functional requirements  
   2. 📄 `test_plan.md`               # Test cases & validation steps  
   3. 📄 `user_guide.md`              # Handoff & usage instructions  





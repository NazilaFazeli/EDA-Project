# Does Renovation Always Pay Off?
### A Data Analysis of Housing Prices

This project analyzes housing sales data from King County, USA,  
to understand **when renovation increases sale prices — and when it does not**.

The analysis is framed from a **client and decision-making perspective**,  
focusing on actionable insights rather than purely descriptive statistics.

---

## 🧑‍💼 Client Context

**Client:** Charles Christensen  
**Goal:** Maximize return on property sales  
**Key Question:** Should houses be renovated before selling, or not?

---

## 📊 Dataset

- One year of housing sales data from **King County, USA**
- Approximately **21,000 transactions**
- Features include:
  - Property size and layout
  - House quality (grade) and condition
  - Renovation status
  - Location (zipcode)
  - Sale price and sale date

---

## 🔍 Analytical Focus

The analysis is guided by three hypotheses:

- **H1:** Bigger houses sell for higher prices  
- **H2:** House quality has a strong impact on sale price  
- **H3:** Renovated houses sell for higher prices  

Rather than evaluating these factors in isolation,  
the project focuses on **how size, quality, renovation, and location interact**  
to support informed renovation decisions.

---

## 📈 Key Insights

- Living area explains a large share of price variation but offers limited differentiation for renovation effects.
- House quality (grade) is a stronger and more consistent driver of sale price than size.
- Renovation does **not always pay off**; its effectiveness depends on:
  - Grade level
  - Location price segment
  - Investment context
- The most reliable renovation uplift is observed in **mid-grade properties (grades 8–10)**  
  located in **mid-price areas**.
- For very low and very high grades, data is sparse and results are uncertain,  
  indicating potential opportunities but requiring further investigation.

---

## 💡 Client Recommendations

- Avoid one-size-fits-all renovation strategies.
- Focus on **mid-grade houses in mid-price areas** where renovation effects are most consistent.
- Be cautious with very low-grade and very high-grade properties due to limited data.
- Consider timing, as spring sales tend to achieve higher prices than winter sales.

---

## 🗂 Project Structure

- `notebooks/` – Main analysis notebook (EDA and decision-oriented analysis)
- `data/` – Housing dataset (King County)
- `README.md` – Project overview and key findings

---

## ⚙️ Setup (Optional)

This project was developed using **Python 3.11**.

To run the notebook locally:

1. Create a virtual environment
2. Install dependencies from `requirements.txt`
3. Open the analysis notebook

```bash
pip install -r requirements.txt
````
## 🛠 Tools & Libraries

- Python  
- pandas, numpy  
- matplotlib, seaborn  

---

## 👤 Author

**Nazila Fazeli**  
Data Science Bootcamp – *neue fische*  
December 2025

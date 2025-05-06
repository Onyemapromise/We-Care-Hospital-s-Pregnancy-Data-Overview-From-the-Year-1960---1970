
![Dashboard 4](https://github.com/user-attachments/assets/82cf45a7-b25d-47e9-bb4a-34035ef73f3d)

 📌 Overview

This project investigates the influence of maternal health and lifestyle factors on newborn **birthweight**, a crucial indicator of neonatal well-being. By analyzing a perinatal dataset, we explore how variables such as gestation period, smoking status, maternal weight, height, age, and pregnancy history affect birth outcomes. These insights can guide health professionals, researchers, and policymakers in improving prenatal care and reducing low birthweight rates.



❓ Research Questions

This analysis addresses the following key questions:

* What is the average birthweight in the dataset?
* How is birthweight distributed among the population?
* Which maternal factors are most strongly correlated with birthweight?
* Does smoking significantly reduce birthweight?
* How do maternal age, weight, and height influence birth outcomes?
* Are there meaningful differences in birthweight based on gestation or parity?

---

## 🧠 Data Context

### 🎯 Industry Sector

**Healthcare / Public Health**

* Perinatal Health
* Epidemiology

📂 Dataset Description

Each row in the dataset represents a birth, with variables related to maternal characteristics and habits:

**Dependent Variable:**

* `bwt` – Birthweight (in ounces)

**Independent Variables:**

* `gestation` – Length of pregnancy (days)
* `parity` – First-time pregnancy (binary)
* `age` – Mother’s age (years)
* `height` – Mother’s height (inches)
* `weight` – Mother’s weight (pounds)
* `smoke` – Smoking status (binary)



 👥 Stakeholders

* Healthcare providers (nurses, midwives)
* Public health officials and ministries
* Academic and research institutions
* Policy makers in maternal-child health
* Expectant parents and families



 🔍 Pre-Analysis Insights

* Most births occur at full-term.
* Average birthweight and distribution trends help define normal ranges.
* Smoking mothers have significantly lower birthweight babies.
* Maternal height and weight positively correlate with birthweight.
* Young and older mothers show slight reductions in birthweight.
* Non-smokers and heavier mothers are associated with healthier birthweights.
* The `NA` group in smoking status had extremely low birthweight, possibly a data quality or vulnerability flag.



 📊 In-Analysis Findings

* Gestation** is a key factor — longer pregnancies yield higher birthweights (\~282 days = \~5878 oz).
* Age trends:** Peak birthweights occur at maternal ages 23 and 26.
* Height correlation:** Taller mothers (65") → \~21926 oz vs. shorter (62") → \~15385 oz.
* Smoking impact:**

  * Smokers: \~55229 oz
  * Non-smokers: \~91301 oz
  * NA group: \~1267 oz
* Maternal weight:** 130 lbs → \~9373 oz; 120 lbs → \~6475 oz



🧾 Post-Analysis Summary

* Birthweight is strongly impacted by:

  * Gestation duration
  * Smoking status
  * Maternal weight and height
* Preterm births are rare but critical to monitor.
* Younger and first-time mothers form the dataset’s core demographic.
* High smoking prevalence is a public health red flag.



✅ Recommendations

 🚭 Smoking

* Launch targeted smoking cessation programs for pregnant women.
* Investigate the NA group for underreported smoking and possible risks.

🥗 Maternal Health

* Promote healthy weight gain through prenatal nutrition and exercise.
* Design education programs on lifestyle impact during pregnancy.

👩‍⚕️ Prenatal Support

* Expand access to prenatal care, especially for first-time and young mothers.
* Encourage regular health screenings to monitor gestation and maternal weight.

🧬 Research & Policy

* Use findings to inform national health policies on maternal-child health.
* Focus on high-risk groups (smokers, underweight, young mothers) for intervention.


 🧩 Conclusion

This project demonstrates that maternal lifestyle and health — especially smoking, weight, and gestation period — play significant roles in determining newborn birthweight. The analysis highlights areas where improved public health strategies and education can positively impact birth outcomes and reduce neonatal risks.


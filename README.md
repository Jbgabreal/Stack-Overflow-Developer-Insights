# 📊 Stack Overflow Developer Insights 2024  

Analysis and visualization of the **Stack Overflow Developer Survey** to uncover current technology usage, future trends, and developer demographics.  
This project was built as part of a capstone assignment to demonstrate **data analysis, visualization, and storytelling** skills.  

---

## 🚀 Project Overview  
The goal of this project is to answer:  
- Which **programming languages** are most used today, and which are developers most excited to learn?  
- Which **databases and platforms** dominate current adoption, and where is momentum shifting?  
- How do **demographics (age, education, region)** shape the technology landscape?  

By comparing **“Have Worked With”** vs. **“Want to Work With”**, we highlight not just the **current state**, but the **future direction** of the developer ecosystem.  

---

## 📂 Project Structure  

```
├── data/                 # CSV extracts (languages, databases, demographics)
├── dashboards/           # Cognos/Looker screenshots (Current Usage, Future Trends, Demographics)
├── charts/               # Matplotlib charts generated for slides
├── presentation/         # Final PPTX presentation
├── report/               # PDF insights report
└── README.md             # Project documentation
```

---

## 🔧 Methodology  

1. **Data Source**: Stack Overflow Developer Survey (public dataset).  
2. **Cleaning & Wrangling**:  
   - Standardized technology categories  
   - Grouped responses to top 10 languages, databases, platforms  
   - Built summary tables for demographics  
3. **Analysis Tools**:  
   - Python (pandas, matplotlib)  
   - Cognos/Looker Studio dashboards  
4. **Visualization**:  
   - Side-by-side comparisons (Current vs. Future trends)  
   - Dashboards for **Technology Usage, Future Trends, Demographics**  
5. **Interpretation**: Derived actionable insights for **developers, employers, and educators**.  

---

## 📈 Key Insights  

- **Languages**:  
  - Current usage dominated by **JavaScript, SQL, HTML/CSS**.  
  - **TypeScript and Python** are the fastest-rising in *future interest*.  
  - **Rust and Go** show strong momentum despite smaller adoption.  

- **Databases**:  
  - **PostgreSQL** leads both current and future rankings.  
  - **Supabase** emerges in *future interest only*, signaling a shift to Postgres-based, developer-friendly cloud platforms.  
  - Traditional enterprise DBs (Oracle, SQL Server, MariaDB) show weaker forward momentum.  

- **Platforms & Frameworks**:  
  - Cloud adoption is anchored by **AWS**, followed by Google Cloud and Azure.  
  - **React, Node.js, and Next.js** dominate web frameworks, with **Svelte** showing future traction.  

- **Demographics**:  
  - Majority of respondents are **25–34 years old**, reflecting early-career choices that will drive hiring trends in the next 3–5 years.  

---

## 📊 Dashboards  

- **Current Technology Usage**  
- **Future Technology Trends**  
- **Demographics**  

(Screenshots available in `/dashboards` and within the final presentation.)  

---

## 🎯 Implications  

- **For Developers**: Learning **TypeScript + Python + SQL/PostgreSQL** is a resilient long-term bet.  
- **For Employers**: Hiring pipelines should emphasize these skills, with selective investment in **Go/Rust** for infra-heavy projects.  
- **For Educators**: Curricula should prioritize **modern web + data stacks** and cloud-native Postgres ecosystems.  

---

## 📑 Deliverables  

- [Presentation Slides (PPTX)](./presentation/StackOverflow_Survey_Insights_Final.pptx)  
- [Charts](./charts)  
- [Dashboards Screenshots](./dashboards)  
- [Full Report (PDF)](./report/Stack%20Overflow%20Insight.pdf)  

---

## 🛠️ Tech Stack  

- **Python**: pandas, matplotlib  
- **BI Tools**: Cognos, Looker Studio  
- **Presentation**: PowerPoint  
- **Version Control**: Git/GitHub  

---

## 🤝 Contributing  

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to add.  

---

## 📜 License  

This project is licensed under the MIT License.  

---

✨ *If you find this project useful, give it a ⭐ on GitHub!*  

# Case study: How does a bike-share navigate speedy success?

<img src="Cyclistic_logo.png" alt="Cyclistic Logo" width="150" align="left"> 

### How do annual members and Casual Riders use Cyclistic bikes differently?

<br clear="left"/>

## 📝 Project Overview
In 2016, **Cyclistic** launched a successful bike-share program in Chicago, growing to a fleet of 5,824 geotracked bicycles and 692 stations. The program stands out for its inclusivity, offering assistive options like tricycles and cargo bikes to ensure accessibility for all. While 30% of users use the bikes for commuting, the majority ride for leisure.

The company’s future growth strategy has shifted: rather than targeting all-new customers, Marketing Director Lily Moreno believes the key to success is **maximizing the number of annual members** by converting existing casual riders. This is backed by financial analysis showing that **annual members are significantly more profitable** than casual riders. As a Junior Data Analyst, my mission is to identify how these two groups differ to support this data-driven conversion strategy.

## 📂 Key Deliverables & Resources
The primary deliverable is a **[comprehensive Final Report](https://marielaramon-da.github.io/Cyclistic_Bike_Share)** designed to bridge the gap between technical data analysis and executive decision-making. To ensure a logical and rigorous flow, the report is organized according to the **Google Data Analytics Framework**: **Ask, Prepare, Process, Analyze, Share, and Act**. Each section corresponds to these analysis phases in order, providing a clear narrative from the business problem to the final recommendations.

To prioritize **transparency and clarity**, the report includes the complete R code for every step. This "open-box" approach ensures the project is fully reproducible, allowing stakeholders to verify the technical criteria—such as data cleaning logic and statistical calculations—behind every insight.

## 🛠️ Tools and Methodology
* **Language:** R (Statistical Programming)
* **Libraries:** `tidyverse` (dplyr, ggplot2, readr), `lubridate`, and `plotly`
* **Types of Analysis:**
    * **Descriptive Analysis:** Statistical summaries to establish foundational usage patterns.
    * **Comparative Analysis:** Direct comparison between segments regarding trip duration and frequency.
    * **Time-Series Analysis:** Identification of trends across monthly, weekly, and daily usage.
    * **Relational Analysis:** Investigating the link between trip duration and user categories based on pricing terms.

## 🔬 Critical Methodology Highlights
The data preparation process involved rigorous cleaning and standardization to ensure the integrity of the comparative analysis. I harmonized the datasets by renaming columns and recoding user labels to maintain consistency across the 2019 and 2020 schemas. A key step was the exclusion of records associated with the **"HQ QR"** station, as it was identified as an operational maintenance point rather than a public-facing docking station.

Regarding **outlier management**, I established specific upper thresholds for ride durations based on Divvy’s pricing terms to prevent anomalous data from skewing the results. For **casual riders**, the limit was set at 14,400 seconds (4 hours) because their Day Pass covers unlimited rides up to 3 hours, making significantly longer trips unrepresentative of typical usage. For **annual members**, the limit was set at 3,600 seconds (1 hour) to reflect their 45-minute free-ride limit. These caps removed only a tiny fraction of the data (1.5% for casuals and 0.3% for members) but significantly improved the statistical representativeness of the findings.

## 📊 Key Findings
* **Usage Behavior:** Members rely on bikes for commuting (short, peak-hour trips), while casual riders focus on leisure (long, weekend/afternoon trips).
* **Trip Metrics:** Casual riders have significantly longer trips (~22.9 min) compared to members (~8.4 min), although members complete a higher total volume of rides.
* **Seasonality:** Casual usage peaks in warmer months and is more sensitive to weather fluctuations than member usage.
* **Top Stations:** Identified <b>Lake Shore Dr & Monroe St</b> as a critical hub for casual user starts.

## 🚀 Proposed Strategy
1. **Leisure to Loyalty Membership:** A trial membership offering discounted weekend rates for casual riders.
2. **Tiered Membership Benefits:** Introduction of a leisure-focused tier with extended rental times.
3. **Targeted Digital Campaigns:** Personalized app messages focusing on cost savings during peak months.

## 👤 Contributors **Mariela Ramon Corria** - Data Analyst & CS/Math Graduate.

I am always looking to improve my methodology and technical approach. I welcome feedback, questions, or suggestions on this analysis through my contact channels or by opening an issue in this repository.

## 📞 Contact Me
* **LinkedIn:** [View Profile](http://www.linkedin.com/in/mariela-ramon-6b368732b)
* **Email:** [marielaramon7107@gmail.com](mailto:marielaramon7107@gmail.com)

## 📄 License
This project is licensed under the MIT License.


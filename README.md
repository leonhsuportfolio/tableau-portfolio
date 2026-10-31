# Tableau-portfolio
Data visualization projects by **Leon Hsu**, built with Tableau. Click any preview to open the live, interactive dashboard on Tableau Public.

**Skills shown:** data cleaning, calculated fields, table calculations, map visualization, dashboard design, and data storytelling.

---

## 1. Check the Forecast, Not the Calendar
### [Halloween trick-or-treat turnout, 2008-2025](https://public.tableau.com/views/HalloweenProject_17934851978400/HalloweenDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1003" height="800" alt="image" src="https://github.com/user-attachments/assets/366ec220-95d3-4c5e-b798-4f74a693e667" />


Does weather or the weekday drive Halloween turnout? Each dot is one Halloween (2020 excluded because of COVID).

- **Heavy rain cuts turnout by about a fifth.** No heavy-rain Halloween has topped 600 trick-or-treaters (median 533 vs. 673 on other nights).
- **Temperature and weekday show no meaningful link.** Temperature explains less than 1% of turnout variation (R² ≈ 0.007), and weekends do not draw bigger crowds.
- **Stocking guide:** stock for the busiest night on record, and plan on about a third less candy if heavy rain is forecast.

**Caveat:** only 4 heavy-rain years, so treat the rain effect as a strong signal, not proof.
**Data:** Jeffrey Shaffer (DataPlusScience.com); NWS Wilmington OH (KCVG)

---

## 2. Where U.S. Data Centers Are Built, and Where They Face Pushback
### [U.S. data centers dashboard](https://public.tableau.com/views/Makeover2_17934879308070/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1003" height="800" alt="image" src="https://github.com/user-attachments/assets/d54d8e2e-415c-4c92-a4fb-1815d9aeeec6" />

Virginia, Texas, and Georgia hold 52% of 1,621 tracked U.S. data centers.

- **Concentration:** VA (460), TX (205), and GA (180) account for 845 facilities.
- **Growth ahead:** most top states have more facilities planned than operating. Texas has 98 proposed against 66 operating.
- **Pushback:** rare in Virginia (under 2%), but above 30% of facilities in Missouri, Indiana, and Ohio, the places where growth is heading.

**Data:** [MakeoverMonday, US Data Center Locations](https://makeovermonday.vercel.app/dataset/us-data-center-locations)

---

## 3. The Great Recession, State by State
### [Monthly unemployment rate by state, Jan 2005 to Dec 2010](https://public.tableau.com/shared/JGPQQKKM3?:display_count=n&:origin=viz_share_link)

<img width="1920" height="1052" alt="image" src="https://github.com/user-attachments/assets/09a62704-0bcd-4c2e-9689-83245a5b9482" />

An animated map with a month slider that shows how the recession spread across the country: calm, then shock, then uneven recovery.

- By late 2007, 35 of 51 states sat under 5% unemployment.
- In 2008-09 the average state rate nearly doubled (4.5% to 8.9%) and 19 states passed 10%.
- By Dec 2010, Michigan had eased from its 14.6% peak to 11.3%, but Nevada (13.6%) and California (12.2%) were stuck near their highs.
- The Dakotas and Nebraska never topped 5.1%.

---

## 4. 2024 Taiwan Presidential Election
### [Taiwan Presidential Election, 2024](https://public.tableau.com/views/B09610001Assignment1/2024ElectionDashBoard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1281" height="726" alt="image" src="https://github.com/user-attachments/assets/791375b2-ffe5-4643-8566-50f0fcf89307" />

An interactive replay of election night. A racing bar chart shows each ticket's running vote total, an area chart tracks votes tallied per minute (peaking around 7 PM), and a bubble chart breaks ballots down by district, colored by county. Use the time slider to watch the lead build.

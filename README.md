# Spotify Data Analysis Dashboard

### 🎵 Project Overview
This project is an interactive Power BI dashboard designed to analyze Spotify music trends, artist performance, and song popularity. The goal was to transform raw data into actionable insights using advanced data visualization techniques.

To enhance the user interface (UI), I designed a custom background layout using **Figma**, giving the dashboard a modern, app-like aesthetic similar to the actual Spotify platform.

**Tools Used:** Power BI, Figma (for UI/Background), DAX (Data Analysis Expressions).

---

### 💼 Business Problems Solved
This dashboard helps stakeholders (Record Labels, Marketing Teams, or Analysts) answer critical questions:

* **Optimizing Release Schedules:** By analyzing "Songs by Month" and "Avg Popularity over Time," we can identify seasonal trends to determine the best time to release new music.
* **Artist Performance Evaluation:** Comparing "Total Songs" vs. "Popularity" helps separate high-volume artists from high-impact artists, guiding investment and promotion strategies.
* **Content Strategy (Singles vs. Albums):** Analyzing the "Songs by Album Type" split helps decide whether to focus resources on producing full albums or releasing standalone singles.
* **Audience Preference Analysis:** The "Explicit vs. Non-Explicit" breakdown provides insights into listener demographics and content restrictions for radio/playlist pitching.

---

### 📊 Dashboard Tour

#### 1. Home Page
Acts as the central navigation hub for the report. I designed this landing page to mimic the Spotify mobile app interface for a familiar user experience.
* **Features:** One-click navigation buttons to access specific analysis sections.
* **Screenshot:**
    ![Home Page](Insert_Home_Page_Screenshot_Link_Here)

#### 2. Overview Page
Provides a high-level summary of the entire dataset. This page answers the "big picture" questions about the music library.
* **Key Metrics (KPIs):** Tracks total distinct songs, average popularity scores, total artist count, and average song duration.
* **Visuals:**
    * **Donut Charts:** Breakdown of songs by Album Type (Single vs. Album) and Explicitness.
    * **Trend Line:** Analysis of Average Popularity over time to spot seasonal trends.
    * **Column Chart:** Monthly distribution of songs to identify peak release windows.
* **Screenshot:**
    ![Overview Page](Insert_Overview_Page_Screenshot_Link_Here)

#### 3. Artists Analysis
Focuses on artist-level performance metrics to identify top-tier talent and catalogue depth.
* **Key Insights:**
    * **Total Songs by Artist:** Identifies prolific artists (e.g., Taylor Swift, Drake).
    * **Popularity vs. Volume:** Compares artists based on their total reach versus their output volume.
    * **Detailed Table:** A granular view of tracks, album counts, and average duration per artist.
* **Screenshot:**
    ![Artists Page](Insert_Artists_Page_Screenshot_Link_Here)

#### 4. Songs Analysis
Drills down into individual track performance.
* **Key Insights:**
    * **Popularity Ranking:** Highlights the most streamed and popular tracks in the dataset.
    * **Hits per Artist:** Visualizes which artists are generating the most "hit" songs.
    * **Granular Data:** A detailed table view allowing users to filter by Year, Month, and Explicit content.
* **Screenshot:**
    ![Songs Page](Insert_Songs_Page_Screenshot_Link_Here)

---

### 🧠 Technical Highlights
* **Custom UI:** Integrated Figma backgrounds to move beyond standard Power BI layouts.
* **DAX Measures:** Used Data Analysis Expressions (DAX) to calculate custom metrics like `Avg Popularity`, `Distinct Song Counts`, and dynamic aggregations.
* **Data Modeling:** Established relationships between Artists, Songs, and Album tables to ensure accurate cross-filtering.

### 📂 Data Source
The dataset used for this analysis includes comprehensive details on tracks, artists, and popularity scores.
* **Source:** [Insert Data Source Link Here]

---

### 📬 Contact
If you have any questions about the dashboard logic or the design process, feel free to reach out!

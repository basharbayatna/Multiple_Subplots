# Weight-Height Analysis by Gender

This repository contains a practice notebook for exploring a sample dataset of height and weight measurements for males and females. The analysis includes filtering, comparison, and visualizations using Python, Pandas, Matplotlib, and Seaborn.

## Dataset
The dataset used is a **sample Weight-Height dataset**.

**Sample Data:**

| Gender | Weight   | Height     |
|--------|---------|------------|
| Male   | 71.9705 | 211.5428   |
| Male   | 69.1300 | 179.0063   |
| Male   | 67.8948 | 178.1773   |
| Male   | 70.8875 | 182.8880   |
| Male   | 67.1215 | 167.1915   |

**Number of rows:** 205+  
**Number of columns:** 3 (Gender, Height, Weight)

**Dataset Link:** [Google Drive](https://drive.google.com/file/d/1PdOdd24kbLLiKc8ssKRieqUkdE6GuV44/view)

---

## What I Did

### 1. Loaded the Data
- Imported the CSV into a Pandas DataFrame called `df`.  
- Previewed the first rows using `.head()`.

### 2. Created Gender Filters
- Filtered the dataset into `df_male` and `df_female` using the Gender column.  
- Verified the first rows of each filtered DataFrame.

### 3. Basic Subplots
- Created side-by-side subplots to practice plotting multiple axes.  
- Adjusted titles and axis labels for clarity.

### 4. Height vs. Weight Comparison
- Plotted scatter plots for males and females side by side.  
- Shared axes to compare distributions more effectively.  
- Key observations:
  - Male weights are generally higher for the same height range.  
  - Female weights show slightly less variation in the dataset.  

### 5. 2D Subplots with Histograms
- Created 2x2 subplots combining scatter plots (top row) and histograms (bottom row).  
- Histograms show distribution of heights for each gender:
  - Males: wider range of heights.
  - Females: more concentrated around the average.

### 6. Dark Background Style
- Applied `plt.style.use('dark_background')` for all visualizations to enhance readability.  
- Adjusted figure sizes and layout using `figsize` and `fig.tight_layout()`.

---

## Figures and Insights

1. **Scatter Plots Height vs. Weight (Males vs. Females)**  
   - Visual comparison between genders.
   - Shows that male individuals are generally heavier for a given height.
   
2. **Histogram of Heights by Gender**  
   - Males: taller on average, wider distribution.
   - Females: slightly shorter and more concentrated.

3. **2D Subplots Combining Scatter + Histogram**  
   - Allows simultaneous comparison of relationships (height vs. weight) and distribution (height frequency) across genders.

4. **Shared Axes Comparison**
   - Makes cross-gender visual analysis easier.

---
## Figures

<img width="850" height="759" alt="D Subplots Comparing Males Vs  Females" src="https://github.com/user-attachments/assets/159d9e3e-aa8b-4079-b72c-de583b615f6a" />


---
## Tools Used
- Python 3  
- Pandas  
- Matplotlib  
- Seaborn  

---

## Notes
- This analysis is exploratory and uses a **small sample dataset**.  
- ---
##  Information 
 For any Questions or Recommendations:
  - Bashar Bayatna (Mechatronics Engineer|Junior Data Scientist)
  - Basharbayatna11@gmail.com

---

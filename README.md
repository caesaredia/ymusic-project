# Music Streaming Behavior in Springfield & Shelbyville 🎧 
This project analyzes music streaming activity in two fictional cities, Springfield and Shelbyville. Using Python and Jupyter Notebook, it explores user behavior, genre preferences, and listening patterns throughout the week.

## Objectives
- Analyze music listening patterns in two cities
- Identify peak streaming times and most popular genres
- Understand day-wise and city-wise streaming behavior

## Key Insights (in the notebook)
- Streaming peaks in the **evenings**
- Both cities show high interest in **pop** and **hip-hop**
- Listening behavior differs slightly by day between Springfield and Shelbyville

## Notebook
* [`ymusic_analysis.ipynb`](./ymusic_analysis.ipynb): Exploratory data analysis of music listening behavior.

## Tools Used
- **Python**
- **Pandas**
- **Matplotlib** & **Seaborn**
- **Jupyter Notebook**

## Dataset
The dataset is stored in [`data/ymusic_data.csv`](./data/ymusic_data.csv), containing anonymized records of music listening behavior from various urban areas.
- Columns include:
  - `userID`: Unique user identifier
  - `City`: Either "Springfield" or "Shelbyville"
  - `Track`: Song title
  - `artist`: Artist name
  - `genre`: Music genre
  - `time`: Time of streaming
  - `Day`: Day of the week

## How to Run
Clone the repo and run the notebook:

```bash
git clone https://github.com/caesaredia/ymusic_project.git
cd ymusic_project
jupyter notebook music_streaming_analysis.ipynb

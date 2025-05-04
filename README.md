# Zipf's Law in Lady Gaga's Lyrics

This project analyzes Lady Gaga's song lyrics to examine the application of Zipf's Law in her music. Zipf's Law is a linguistic principle stating that the frequency of a word is inversely proportional to its rank in the frequency table.

## Project Overview

This data analysis project:
- Processes and cleans Lady Gaga's song lyrics
- Analyzes word frequency distribution
- Tests whether the lyrics follow Zipf's Law
- Visualizes the results through various charts and plots

## Dataset

The project uses a dataset (`LadyGaga.csv`) containing Lady Gaga's song lyrics. The dataset includes:
- Song titles
- Album information
- Complete lyrics for each song

## Installation and Setup

### Prerequisites
- Python 3.6+
- Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage

1. Clone this repository
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Hackdev.ipynb
   ```
3. Run the cells to reproduce the analysis

## Analysis and Results

The analysis includes:

1. **Data Cleaning and Preprocessing**:
   - Removing missing values
   - Tokenizing lyrics
   - Converting text to lowercase

2. **Word Frequency Analysis**:
   - Counting word occurrences
   - Ranking words by frequency

3. **Zipf's Law Verification**:
   - Comparing actual word frequencies with expected frequencies according to Zipf's Law
   - Log-log plotting of rank vs. frequency

4. **Visualization**:
   - Bar charts of top words
   - Log-log plots showing the relationship between word rank and frequency

### Key Findings

The analysis demonstrates how closely Lady Gaga's lyrics follow Zipf's Law, providing insights into linguistic patterns in popular music.

## Files in the Repository

- `Hackdev.ipynb`: Jupyter notebook containing the complete analysis
- `LadyGaga.csv`: Dataset with Lady Gaga's song lyrics
- `zipf_analysis.png`: Log-log plot of word rank vs. frequency
- `top_words.png`: Visualization of the most frequent words
- `top_words_chart.png`: Bar chart of the top words

## License

This project is available for educational purposes.

## Contact

For questions or feedback about this analysis, please open an issue in this repository.

# 🍸 Boozeless - Market Entry Strategy Analysis

## 📋 Project Overview

**Boozeless** is an emerging non-alcoholic spirits brand seeking to enter the upscale beverage market in Singapore. This project employs advanced data science techniques to identify optimal F&B venue partnerships through **emotion-based analytics** and **natural language processing**.

## 🎯 Project Objectives

The analysis aims to uncover high-potential target venues aligned with Boozeless's brand DNA across three key segments:

- **Young, Mild and Free**: Modern venues connected with active, healthy, and sporty lifestyles
- **Aesthetically Anchored**: Venues with unique design for special occasions  
- **Haute Cuisine**: Boundary-pushing restaurants willing to experiment with new menu concepts

## 🔬 Methodology

### Core Approach
Unlike traditional market segmentation relying solely on quantitative metrics, this analysis pioneers a **dual-strategy approach**:

1. **General Fit Analysis**: Ranking venues based on ratings, reviews, and sentiment scores
2. **Emotion-Based Fit**: Using custom emotion axes to score venues aligned with Boozeless's premium, health-conscious brand identity

### Technical Stack
- **Natural Language Processing (NLP)**: Text analysis of venue descriptions and customer reviews
- **Unsupervised Learning**: Clustering and pattern recognition in venue characteristics
- **Sentiment Analysis**: Emotion lexicon-based scoring for brand alignment
- **Geospatial Intelligence**: Location-based venue targeting and clustering

## 📁 Project Structure

### Core Files
- **`Project_ADS.Rmd`** - Complete R Markdown analysis with code, visualizations, and insights
- **`analysis_for_ads.pdf`** - Comprehensive analysis report and findings
- **`output.csv`** - Processed dataset containing venue information, sentiment scores, and analysis metrics

### Key Components
The analysis integrates multiple data science disciplines:
- **Data Preprocessing**: Cleaning and structuring venue data from multiple sources
- **Text Mining**: Extracting insights from venue descriptions and amenities
- **Sentiment Analysis**: Custom emotion scoring for brand alignment
- **Clustering Analysis**: Identifying venue segments and patterns
- **Visualization**: Interactive maps, word clouds, and statistical charts

## 💡 Key Insights

### Amenity Analysis
The analysis reveals that most venues focus on **functional amenities** (delivery, WiFi, ordering) rather than **experiential elements** (ambience, mixology, tasting menus). This gap presents opportunities for Boozeless to differentiate through premium, experience-focused partnerships.

### Brand Alignment Scoring
Venues are evaluated using custom emotion axes that capture:
- Premium positioning and sophistication
- Health-conscious and wellness-oriented characteristics  
- Innovation and willingness to experiment
- Design aesthetics and experiential focus

## 🚀 Getting Started

### Prerequisites
- R and RStudio
- Required R packages: `dplyr`, `ggplot2`, `tm`, `wordcloud`, `tidytext`, `leaflet`, `cluster`

### Running the Analysis
1. Open `Project_ADS.Rmd` in RStudio
2. Ensure `output.csv` is in the same directory
3. Install required packages if not already installed
4. Run the R Markdown document to reproduce all analyses

## 📊 Output and Deliverables

The analysis produces:
- **Venue Rankings**: Prioritized lists of target venues by segment
- **Sentiment Scores**: Emotion-based alignment metrics for each venue
- **Geographic Clusters**: Location-based venue groupings
- **Amenity Insights**: Analysis of venue characteristics and opportunities
- **Strategic Recommendations**: Data-driven partnership targeting


## 🔗 Repository

This project is originally extended from Synthesis' Take Home Challenge to my Applied Data Science course, demonstrating advanced analytics techniques for real-world business strategy development.

---

*This analysis represents a novel approach to market entry strategy, combining traditional business intelligence with cutting-edge data science methods to identify optimal partnership opportunities for emerging brands.*

# Day 3 — Category & Rating Analysis

## Objective
Understand which product categories perform best at scale using rating data.

## What I did
- Cleaned rating column (text → numeric)
- Removed invalid values
- Grouped products by category
- Filtered categories with meaningful volume (>50 products)
- Calculated average rating per category

## Key Insights

1. Smart televisions show the highest reliability at scale  
   - Avg rating: ~4.21  
   - Strong performance with high product volume

2. USB cables represent a saturated but stable market  
   - Highest product volume  
   - Ratings remain consistent (~4.15)

3. Remote control accessories show higher dissatisfaction risk  
   - Lower rating band (~3.8)  
   - Likely affected by compatibility issues

## Learning
- Large sample sizes matter more than perfect ratings
- Commodity categories stabilize around acceptable quality levels
- Data cleaning is required before analysis
# Day 2 — SQL Exploration & Data Cleaning

## Objective
Understand dataset structure and clean numeric columns for analysis.

## What I Did
- Explored rating distribution
- Converted rating (TEXT → NUMERIC)
- Removed commas from rating_count
- Filtered invalid values using regex
- Calculated average rating

## Errors I Faced
- invalid input syntax for numeric
- rating column had "|" values
- rating_count had commas

## How I Fixed Them
- Used regex: rating ~ '^[0-9.]+$'
- Used REPLACE(rating_count, ',', '')
- Used ::numeric casting

## Key Metrics
- Avg rating: 4.10
- Max rating: 5.00
- Min rating: 2.00
- High review products stabilize around 4.1–4.4

## What I Learned
- Text vs numeric matters
- Real datasets are messy
- Cleaning comes before analytics

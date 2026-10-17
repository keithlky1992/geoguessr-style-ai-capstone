# Step 11: Explore OpenStreetView-5M Metadata

## Goal
Understand the structure of the dataset metadata so we can later filter the 8 selected countries and sample ~400 images each.

## Planned Actions
1. Load metadata only (without downloading all images) using Hugging Face `datasets` library
2. Check available columns (country, latitude, longitude, image path, etc.)
3. Count how many images exist for each of our 8 countries:
   - Japan
   - France
   - Brazil
   - Australia
   - India
   - South Africa
   - United States
   - Thailand
4. Decide sampling strategy based on the counts

## Notes
- Full dataset is ~5.1 million images and very large
- We will only use a small balanced subset
- Must respect CC-BY-SA-4.0 license (attribution required)

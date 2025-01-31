# Global-Scale Chlorophyll-a Monitoring for Inland Lake Water Quality Framework: Advancements, Machine Learning Models, and Transferability Challenges

# Data-Source-Global-Chla-Compiled-In-situ-Sentinel-2-Data

# Gathered and Filtered Data
1_Gathered Raw Insitu Data 
- Information of coordinates, Date, Lat, Long, Smapling Depth, Chla values, and Sources.

2_Filtered Raw Insitu Data 
- Information of coordinates, Date, Lat, Long, Smapling Depth, Chla values, and Sources.

3_GEE Compiled Insitu Satellite Data (Origin)
- Information of coordinates, Date, Lat, Long, Smapling Depth, Chla values, Sentinel 2 Bands (1 to 12 + 8A) and Sources.

4_GEE Compiled Insitu Satellite Data (Filtered)
- Information of coordinates, Date, Lat, Long, Smapling Depth, Chla values, Sentinel 2 Bands (1 to 12 + 8A) and Sources.
- Filteration based on SCL Classes, non-water and absence of pixel values.

5_Selected GEE Compiled Insitu Satellite Data 
- Information of coordinates, Date, Lat, Long, Smapling Depth, Chla values, Sentinel 2 Bands (1 to 12 + 8A) and Sources.
- Selection based on NDCI index, and data cleaning.

6_Unselected GEE Compiled Insitu Satellite Data
- Information of coordinates, Date, Lat, Long, Smapling Depth, Chla values, Sentinel 2 Bands (1 to 12 + 8A) and Sources.
- Unselection based on NDCI index, and data cleaning

# Features and Model Input
7_Group_1 Bands and Indices (Before Feature Selection)
- Individual Bands and Indices

8_Group_2 Bands and Derived Features (Before Feature Selection)
- Individual Bands and Derived features by Math Functions
- Column name : A = Band 1,
                B = Band 2,
                C = Band 3,
                D = Band 4,
                E = Band 5,
                F = Band 6,
                G = Band 7,
                H = Band 8,
                I = Band 8A,
                J = Band 11,
                K = Band 12.

9_Group_1 Bands and Indices (Selected Features_Model Input)
- Final Input Dataset

10_Group_2 Bands and Derived Features (Selected Features_Model Input)
- Final Input Dataset
- Column name : A = Band 1,
                B = Band 2,
                C = Band 3,
                D = Band 4,
                E = Band 5,
                F = Band 6,
                G = Band 7,
                H = Band 8,
                I = Band 8A,
                J = Band 11,
                K = Band 12.

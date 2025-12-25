# Kuppismart-Task2
Poultry Monitoring System: Bird Counting & Weight Estimation
This prototype provides an automated solution for monitoring poultry health and density using fixed CCTV footage. It leverages Deep Learning for real-time detection and a geometric proxy for weight estimation.

🚀 Features
Temporal Bird Counting: Real-time tracking of individual birds to provide population density over time.

Stable Tracking: Utilizes BoT-SORT/ByteTrack to maintain unique IDs even during bird-to-bird occlusions.

Visual Weight Proxy: Computes a weight index based on segmented pixel area and bounding box geometry.

RESTful API: FastAPI-based service for video processing and data retrieval.

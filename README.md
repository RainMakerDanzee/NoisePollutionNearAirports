# NoisePollutionNearAirports
Using the airport noise data from the government, we create a new metric for investors

DATASET: https://data.nsw.gov.au/data/dataset/epi-protection-airport-noise?nsw_prev=aHR0cHM6Ly9kYXRhLm5zdy5nb3YuYXUvZGF0YS9kYXRhc2V0Lz90YWdzPW5vaXNl%0A

We call this Airport Noise Exposure Score (ANES) - a sub-component of the Environmental Comfort Index, derived from proximity to airport noise zones
Formula used: ANES = 100 - (Noise_Zone_Level / Max_Noise_Level) * 100
Lower decibel zones get higher scores.

A score of a 100 means not affected by airport noise at all, a score of 0 indicates otherwise.

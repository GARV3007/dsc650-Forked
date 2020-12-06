---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Jane Doe
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     | Wrote 128 characters in a notepad and checked the size
| 1024x768 PNG image                         | 3 MB          | For 32 bit depth
| 1024x768 RAW image                         | 3 MB          | For 32 bit depth
| HD (1080p) HEVC Video (15 minutes)         | 878.9 MB      |
| HD (1080p) Uncompressed Video (15 minutes) | 195530 MB     |
| 4K UHD HEVC Video (15 minutes)             | 4940 MB       |
| 4k UHD Uncompressed Video (15 minutes)     | 22247 MB      |
| Human Genome (Uncompressed)                | 150 trillion GB|

https://4nsi.com/faq/how-do-i-calculate-the-file-size-for-a-digital-image
https://www.circlehd.com/blog/how-to-calculate-video-file-size
https://www.videoproc.com/edit-4k-video/video-size-calculator.htm

#### b. Scaling

|                                           | Size     | # HD  | 
|-------------------------------------------|---------:|------:|
| Daily Twitter Tweets (Uncompressed)       | 64 GB    |   1   |
| Daily Twitter Tweets (Snappy Compressed)  | 37.6 GB  |   1   | With 1.7x compression ratio
| Daily Instagram Photos                    | 257.9 TB |  78   |
| Daily YouTube Videos                      | 2530 TB  | 760   |
| Yearly Twitter Tweets (Uncompressed)      | 23.36 TB |   7   |
| Yearly Twitter Tweets (Snappy Compressed) | 13.74 TB |   5   | With 1.7x compression ratio
| Yearly Instagram Photos                   | 94.13 PB | 25,684|
| Yearly YouTube Videos                     | 923.45 PB|251,962|

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | ??   |            |
| Twitter Tweets (Snappy Compressed) | ??   |            |
| Instagram Photos                   | ??   |            |
| YouTube Videos                     | ??   |            |

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | 147.432 ms           |
| Low Earth Orbit Satellite | 73 ms                |
| Geostationary Satellite   | 280 ms               |
| Earth to the Moon         | 1250 ms              |
| Earth to Mars             | 3-21 minutes         | 

References:
https://www.satsig.net/latency.htm
https://www.satellitetoday.com/telecom/2009/09/01/minimizing-latency-in-satellite-networks/
https://www.spaceacademy.net.au/spacelink/commdly.htm

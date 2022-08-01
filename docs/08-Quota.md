# ⭐Quotas and limits

This article contains a quick reference and a detailed description of the quotas and limits for Metrics Advisor for Equipment.

| Description                                                  | Quota                   |
| :----------------------------------------------------------- | :---------------------- |
| **Data ingestion**                                           |                         |
| Maximum number of variables per dataset                     | 300                     |
| Maximum number of datasets per account                       | 15                      |
| Maximum number of pending data ingestion jobs per account    | 5                       |
| Maximum number of models per account                         | 15                      |
| Maximum length of variable name                             | 200 characters          |
| Maximum size per dataset                                     | 50 GB                   |
| Minimum granularity of the raw data                          | 1 min                   |
| Maximum number of inference schedulers per model             | 1                       |
| **Training and evaluation**                                  |                         |
| Maximum number of data points in training data  (data points= number of variables * number of timestamps) | 100 million data points |
| Maximum number of data points in evaluation data             | 150K data points        |
| Maximum number of variables in training data      | 300                     |
| Maximum training data sliding window                         | 2880 data points        |
| Maximum number of evaluations per model                      | 100                     |
| Maximum retention of evaluations per model                   | 30 days                 |
| Maximum retention of inference per model                     | 6 months                |
| Maximum retention of alert per model                         | 7 days                  |
| **Real-time Inference Schedule**                                                |                         |
| Maximum number of real-time inference schedule per model                       | 1                       |
| Maximum inferences lead time                                 | 3 days                  |
| Minimum inference lead time                                  | 1 day                   |
| Maximum replay time range                                    | 1000 data points        |
| Maximum number of replay jobs per inference                       | 100                     |

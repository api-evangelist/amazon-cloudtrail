---
title: "Identifying resources driving Amazon CloudWatch GetMetricData charges using AWS CloudTrail"
url: "https://aws.amazon.com/blogs/mt/identifying-resources-driving-amazon-cloudwatch-getmetricdata-charges-using-aws-cloudtrail/"
date: "2025-04-29"
author: "Ryan Thomas"
feed_url: "https://aws.amazon.com/blogs/mt/tag/aws-cloudtrail/feed/"
---
Organizations frequently use third-party monitoring tools to retrieve CloudWatch metric data for their dashboards and alerting systems. This practice often leads to significant GetMetricData API usage and results in high CloudWatch costs. A common challenge for cost optimization teams is identifying which specific resources or applications are driving these increased expenses, especially when they’re not directly involved with the operational workflows.

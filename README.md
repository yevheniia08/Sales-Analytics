# Country-Based User Activity and Messaging Behavior Analysis

This SQL project focuses on analyzing account creation and messaging behavior across countries to help identify key user segments, active markets, and user engagement patterns.

## Key Insights

- **Top 10 countries** by account creation and message volume  
- **Segmentation by send interval, verification, and unsubscribe status**  
- **Daily breakdown** of accounts and messaging activity  
- **Cross-analysis of sent, opened, and visited messages**

## How It Works

The project involves:
- Aggregating user activity metrics by country, date, and user attributes  
- Using **window functions and ranking** to highlight top-performing countries  
- Creating a custom table `message_data_opanasiuk` with sent, open, and visit message flags  
- Joining account, session, and country-level parameters for enriched analysis

## Use Cases

- Identifying and comparing **high-performing countries**  
- Segmenting users by **email engagement behavior**  
- Informing **targeted campaigns** based on verification and unsubscribe status  
- Supporting **market expansion strategies** with data


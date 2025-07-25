# product_documentation
Mosaic Platform Product Documentation
Table of contents
Table of contents
Introduction
Problem Statement
Stakeholders
User Personas
Glossary & Terminology
Customer Journey Maps
Product Features (Epics)
Key use cases
Core Assumptions
Troubleshooting & Known Issues
Success Metrics
System Overview & Architecture
Designs & UI Mockups
Informational Website
SWOT Analysis
AI Agent (Data & Code)
FAQ
Changelog & Versioning
Reference & Resources
Feedback & Contribution




Introduction
The global fashion industry produces 10% of worldwide pollution, with unsustainable textile practices as a leading cause. In Kenya, the Gikomba market is the heart of the second-hand clothing(Mitumba) ecosystem, providing economic opportunity and affordable clothing. However, used and discarded clothing continues to feed landfills like Dandora, increasing the environmental burden.

Our platform addresses this gap by connecting traders with designers for garment upcycling, aiming to turn waste into value and foster sustainable habits in the local fashion market.
Problem Statement
How might we foster the culture of reusing unsold clothing to reduce textile waste in Dandora?
Stakeholders
Gikomba Traders: Sellers of second-hand clothes seeking new value for unsold stock and upcycled products for their customers.
Designers: Creators who wish to source affordable garments to redesign and upcycle, selling unique products.
User Personas

Name
Age
Role 
Goals
Pain points
Mark
26
Trader
Satisfy demand for upcycled clothes: offload unsold stock
No reliable sourcing or upcycling channels; unsold inventory
Brenda
27
Designer
Source low-cost materials; match designs to real demands 
Uncertain demand; limited material for redesigns 

Glossary & Terminology
Mitumba: Second-hand clothing in Kenya
Upcycling: Converting old garments into higher-value, often redesigned, products. 
Trader: Seller of second-hand clothes at a market
Designer:  individual/ group creating new designs from used clothing
Customer Journey Maps
View Customer Journey Map (Figma)
Product Features (Epics)
View full epic list

Key use cases
Trader
Steps:

Login/register as a Trader
Select item(s) for upcycling
Browse the designer catalog or search by style or material
Place order  (choose preferences: style)
Request for a delivery
Track order progress 
Receive final product (within 14 days maximum)
Review and rate the service
Designer: 
Steps:

Login/register as Designer
List available design services, update designs
Manage order requests
Mark completed orders
Track history and receive ratings/feedback

Features & Acceptance Criteria

Trader & Designer Registration
The system shall allow users to register as either a trader or a designer.

Design Catalog 

Designers shall maintain a catalog visible to traders (unless >10 pending orders).

Order request

Traders shall submit requests specifying preferences, with order tracking enabled.

Order Capacity Control

The designer catalog entry is hidden if the designer has 10 or more pending orders.

Order Deadline

System shall ensure all orders are completed within 14 days, or notify affected traders.
Core Assumptions
Users are in the same region for logistics.
Designer listings hidden at ≥10 active orders.
Max upcycling turnaround is 14 days.
Troubleshooting & Known Issues

Problem 
Solution/Next step
Designer listing is “missing”
The designer has reached the 10-order limit
Cannot upload designs
Clear cache, retry login. Or reach out on the contact us info
No response to the order
Try another designer or resubmit the request
Order not delivered within 14 days
Check order status or reach out to contact us for info









Success Metrics
100+ active users in 3 months
50+ design transactions in 3 months
≤2% churn rate per month

System Overview & Architecture


Designs & UI Mockups
Platform Design Mockup(Figma)
Informational Website
Informational website(netlify)
SWOT Analysis
SWOT Analysis Document
AI Agent (Data & Code)
Mosaic Data Source Document 
AI Agent Source Codes



FAQ
Q: Who can use the platform?
Mosaic is a platform that connects traders with unsold clothes to designers who redesign the clothes for them. Our mission is to reduce textile waste, support sustainable fashion and promote local talent.
Q: Who can use the platform?
Local traders and designers are directly involved in second-hand clothing upcycling. 
Q: How do I submit an upcycling request?
 Register as a trader, browse the designer catalog, to pick out a design you are interested in. And then submit a request through your dashboard.
Q: Why can’t I find a certain designer?
 Designers with 10+ pending orders are temporarily hidden to maintain quality.
Q: What if my order is late?
 Check status in-app or contact support.
Q: How fast will I get my upcycled item?
 All orders are guaranteed to be completed within a maximum of 14 days.
Q: Who do I contact for help?
Reach out to us through our “Contact us” page or email us at mosaic@info.com. We respond within 24 hours. 
Changelog & Versioning

Version
Date
Changes
1.0
2025-07
Initial release: trader/design flows, order system, designs, and metrics tracking.



Reference & Resources
JIRA project Board
Customer Journey Map(Figma)
System Architecture(Lucidchart)
ERD Document
Product Mockups(Figma)

Feedback & Contribution
We welcome your feedback!
Suggest changes or report Issues via  email
[mosaic@info.com]
Contact the team to request onboarding guides, developer integration docs, or further resources.



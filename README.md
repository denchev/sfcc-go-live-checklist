# sfcc-go-live-checklist
A list of tasks to check in order to prepare your Salesforce Commerce Cloud for a successful go-live

This list covers generic tasks that every site should do before going into Live mode on Production. There are thousand more than the team responsible for the site development should do on top of them - site must be developed according to specifications, all tests (manual or automated) should pass successfully, catalog, price, inventory, and other data should be imported and so on.

The "Time before go-live" is mostly "rule of thumb" - it may vary in your case.

|Item | Time before go-live| 
|:---|:---|
| Initial data and code replication from Staging to Production | 1 month |
| Configure Business Manager preferences with the Production values | 1 week |
| Whitelist IP addresses and ports for In-Out network connections | 2 weeks |
| Business Manager users and permissions | 2 weeks |
| Configure sequence numbers | 2 weeks |
| Configure shipping methods | 2 weeks |
| Configure Custom object retention | 2 weeks |
| Services have proper timeout, rate limitter and curcuit breaker | 2 weeks |
| Configure job notification settings | 2 weeks |
| Configure jobs and their schedules | 2-3 weeks |
| Search indexation happens on Staging and replicated to Production | 1 week |
| Search index is scheduled to happen once per day | 1 week |
| Obtain SSL certificates | 3 weeks |
| Install SSL certificates | 2 weeks |
| Configure robots.txt | 2 weeks |
| Schedule data replications | 2 weeks |
| Configure 404 page | 2 weeks |
| Configure maintenance / site down page | 2 weeks |
| Configure legacy URLs (if migrating from another platform) | 1 week |
| Configure aliases and static mappings | 2 weeks |
| Have plan what to do with old customers and their passwords (if migrating from another platform) | 2 weeks |
| eCDN setup | 1 week |
| Update domain TTL to 5 minutes | 1 week |
| Clean up test data on Production | 1 week |
| Speak with Salesforce to asses your site and allow Live mode (SRA) | 2-3 weeks |
| Ensure no quotas are violated during test period | 2 weeks |
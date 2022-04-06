# DP-500-Exam
### PBI Admin
[Config Premium Capacity](https://docs.microsoft.com/en-us/power-bi/enterprise/service-admin-premium-manage)

[Managing Premium Capacity](https://docs.microsoft.com/en-us/power-bi/enterprise/service-admin-premium-manage)

[Optimizing capacity](https://docs.microsoft.com/en-us/power-bi/enterprise/service-premium-capacity-optimize)

### REST API and XMLA
[PBI REST API connection](https://www.sqlshack.com/how-to-access-power-bi-rest-apis-programmatically/)

[XMLA Basics](https://radacad.com/what-is-the-xmla-endpoint-for-power-bi-and-why-should-i-care)

[XMLA - MS Doc](https://docs.microsoft.com/en-us/power-bi/enterprise/service-premium-connect-tools)

[Partition Refresh using XMLA](https://sqlserverbi.blog/2021/12/27/hybrid-tables-incremental-refresh-and-table-partitioning-in-power-bi/)

### Performance
[Desktop Performance Analyzer](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-performance-analyzer)

[Query Diagnostics](https://blog.crossjoin.co.uk/2020/05/21/monitoring-power-query-memory-usage-with-query-diagnostics-in-power-bi/)

[Monitoring Query](https://www.jamesserra.com/archive/2020/05/monitoring-power-bi/)

[Optimizing Power Query](https://blog.crossjoin.co.uk/2020/05/31/optimising-the-performance-of-power-query-merges-in-power-bi-part-1/)

[Aggregations and debug](https://www.antmanbi.com/post/getting-started-with-aggregations-in-power-bi-part-1)

[Large Tables](https://sqlserverbi.blog/2021/06/01/doing-power-bi-the-right-way-10-designing-and-managing-large-datasets/)

### Other features
[RLS](https://www.antmanbi.com/post/create-static-row-level-security-in-power-bi)

[OLS](https://youtu.be/8s3MByrZJgg)

### Explore and visualize data
[Automatic page refresh](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-automatic-page-refresh)

Points:
1. Maximum concurrent refreshes - 1.5 times the v-core capacity rounded up to nearest integer
2. Automatic Page refresh - Setting present in admin side overrides the refresh setting per page and query running time is the actual page refresh frequency
3. For a full refresh, twice the amount of memory is required
4. While doing OLS, take relationships into consideration. Hiding a single table with relation to other tables results in error

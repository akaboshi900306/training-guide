# Data Analyst Foundations

### Data Visualization:
* Tableau
    * Begin: https://www.tableau.com/learn/learning-paths/analyst
    * More Practice: https://app.pluralsight.com/library/courses/build-first-dashboard-tableau/table-of-contents
    * https://app.pluralsight.com/library/courses/tableau-desktop-building-effective-data-communications/table-of-contents
    * Advanced: https://app.pluralsight.com/library/courses/tableau-desktop-building-effective-dashboards/table-of-contents
* Data Story Telling - https://www.youtube.com/watch?v=IIMHicxQ0LY
    * https://www.youtube.com/watch?v=4pymfPHQ6SA
    * https://www.youtube.com/watch?v=JsDxcEH5VeA
    * https://www.youtube.com/watch?v=yXjpD0SLDIk
    * https://www.youtube.com/watch?v=snYapIIWDSw
    * https://app.pluralsight.com/library/courses/data-storytelling-moving-beyond-static-data-visualizations/table-of-contents
    * https://www.youtube.com/watch?v=6VBGkpfTKqs

### Coding 
### Git
* https://app.pluralsight.com/library/courses/how-git-works/table-of-contents

#### SQL:
* Stop writing ugly queries.
    * Proper naming of columns
    * https://javarevisited.blogspot.com/2017/01/a-better-way-to-write-sql-queries.html
* Read through the documentation here: https://cloud.google.com/bigquery/docs
* Beginners read this first: https://www.amazon.com/Head-First-SQL-Brain-Learners/dp/0596526849?tag=javamysqlanta-20
* VERY Advanced Only do this once you’ve masted everything below: https://www.amazon.com/Puzzles-Answers-Edition-Kaufmann-Management/dp/0123735963
* Data Modeling
    * How to build a relational database
        * https://towardsdatascience.com/designing-a-relational-database-and-creating-an-entity-relationship-diagram-89c1c19320b2
    * Avoiding Database Anti-patterns
        * https://www.amazon.com/SQL-Antipatterns-Programming-Pragmatic-Programmers/dp/1934356557
* Schemas
    * DML/DDL
    * Proper usage of data types
        * String, Float, byte, numeric, etc.
        * Can you answer what is the technical difference between INT vs INT64?
        * https://app.pluralsight.com/library/courses/sqlserver-why-physical-db-design-matters/table-of-contents
* Window functions - https://www.youtube.com/watch?v=H6OTMoXjNiM & https://www.youtube.com/watch?v=H6OTMoXjNiM
    * Row number over
    * Partition by
    * Tricks you can do with window functions

* Nested columns & Arrays - https://cloud.google.com/bigquery/docs/reference/standard-sql/arrays
    * Example: https://www.kaggle.com/alexisbcook/nested-and-repeated-data
    * How to build a pivot table in BQ - https://corecompete.com/how-to-build-pivot-tables-in-bigquery-fast-and-easy/
* Table clustering - https://cloud.google.com/bigquery/docs/clustered-tables
* Table partitioning - https://cloud.google.com/bigquery/docs/partitioned-tables
* Temporary Tables - https://cloud.google.com/bigquery/docs/reference/standard-sql/data-definition-language#temporary_tables
* Regular expressions - https://app.pluralsight.com/library/courses/regular-expressions-fundamentals/table-of-contents
    * My fav tester - https://regexr.com/
* Wildcard tables - https://cloud.google.com/bigquery/docs/querying-wildcard-tables
* Table decorators - https://cloud.google.com/bigquery/table-decorators
    * Prefix/suffix
    * Table recovery using range
* Map / Reduce concept (Understand this before implementing any UDFs or stored procs
* Stored Procedures
    * This can be database specific
    * https://cloud.google.com/blog/products/data-analytics/command-and-control-now-easier-in-bigquery-with-scripting-and-stored-procedures
    * User defined functions - https://cloud.google.com/bigquery/docs/reference/standard-sql/user-defined-functions
        * Requires knowledge of javascript which isn’t that different from python in a lot of ways.
        * Using nested columns, arrays and udfs, can you write a generic function to do a pivot now?
        * Understand the answer here: https://towardsdatascience.com/easy-pivot-in-bigquery-one-step-5a1f13c6c710

#### Python:
* Fundamentals - https://www.amazon.com/Head-First-Python-Brain-Friendly-Guide/dp/1491919531/
* Automate the boring stuff - https://automatetheboringstuff.com/
* Functions
* Control Flow
   * If else
   * loops (for while)
   * Basic dependency management via virtual environments
   * Exception handling
       * try except
* Data types
* What is duck typing in python?
* Classes vs functions.
* Analytical packages
   * When should you use pandas vs doing it in BQ?

# Sr. Data Analyst Foundations
### Data warehousing concepts:
* https://www.youtube.com/watch?v=oF_2uDb7DvQ
* How to test data for reporting - https://www.youtube.com/watch?v=f8_866Wz2tM
* https://www.youtube.com/watch?v=jor49_utDlU
* Research yourself or can you answer this now? Why is staging data important?

### Pipelining:
* https://www.youtube.com/watch?v=8-Hp31WHtI8 — API driven pipeline
* https://www.youtube.com/watch?v=VtzvF17ysbc
* https://www.youtube.com/watch?v=pzfgbSfzhXg
* This is probably out of scope unless you work in IT but worth it if you want to know more: https://app.pluralsight.com/library/courses/building-batch-data-pipelines-gcp-1/table-of-contents

### Databases:
* Indexing - https://www.essentialsql.com/what-is-a-database-index/
    * What is a hash?
    * How does indexing affect performance?
* Clustering - https://cloud.google.com/bigquery/docs/clustered-tables
* Table Partitioning
* Query and Database optimization
    * MUST READ: https://www.amazon.com/Performance-Explained-Everything-Developers-about/dp/3950307826/

### Coding 
You should be very good at this by the Sr. Data Analyst level.
 * Python
     * Functional programming
         * Closures
         * Generators
         * Decorators
         * Map/reduce/filter/lambda
     * Namespaces
     * You need to know what this is: ```If __name__ == “__main__”```
     * Master: Dependency management via requirements.txt
         * pip commands
     * Repl - https://repl.it/languages/python3

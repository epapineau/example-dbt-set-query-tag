# Example `set_query_tag`
A companion code-snippet for the 2023 Coalesce talk [How dbt Labs tunes model performance and optimizes cloud data platform costs with dbt](https://coalesce.getdbt.com/agenda/how-dbt-labs-tunes-model-performance-and-optimizes-cloud-data-platform-costs-with-dbt). An example of overriding the default behavior of [dbt-snowflake](https://github.com/dbt-labs/dbt-snowflake/tree/main) [`set_query_tag`](https://github.com/dbt-labs/dbt-snowflake/blob/a1ae40de46166b2e0f7264971f1300ad002fb644/dbt/include/snowflake/macros/adapters.sql#L202) macro to enable 1:1 mapping between dbt invocations and Snowflake query IDs.

#### Implementation
Create a file called `set_query_tag.sql` in the `macro` directory of your dbt project. Use the example and customize as needed. 
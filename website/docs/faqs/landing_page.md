Our [Frequently Asked Questions](https://docs.getdbt.com/faqs/all) (FAQs) section is a space where we answer some questions we get asked a lot (but that we’re happy to answer!)

### What is dbt?
dbt (data build tool) enables analytics engineers to transform data in their warehouses by simply writing select statements. dbt handles turning these select statements into tables and views.

dbt does the T in ELT (Extract, Load, Transform) processes – it doesn’t extract or load data, but it’s extremely good at transforming data that’s already loaded into your warehouse.

The role of dbt within a modern data stack is discussed in more detail [here](https://blog.fishtownanalytics.com/what-exactly-is-dbt-47ba57309068).

dbt also enables analysts to work more like software engineers, in line with the dbt Viewpoint.

### What is the difference between dbt Core, the dbt CLI and dbt Cloud?

dbt Core is the software that takes a [dbt project](https://docs.getdbt.com/docs/building-a-dbt-project/projects) (.sql and .yml files) and a command and then creates tables/views in your warehouse. dbt Core includes a command line interface (CLI) so that users can execute dbt commands using a terminal program. dbt Core is [open source](https://github.com/dbt-labs/dbt) and free to use.

dbt Cloud is an application that helps teams use dbt. dbt Cloud provides a web-based IDE to develop dbt projects, a purpose-built scheduler, and a way to share dbt documentation with your team. dbt Cloud offers a number of features for free, as well as additional features in paid tiers (check out the [pricing here](https://www.getdbt.com/pricing/)).
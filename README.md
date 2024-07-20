# Big-Data-Pyspark

The objective of the assignment is to design and build spark pipeline to enable
downstream applications to find key insights.
1) Dataset:
1. The teams have freedom to choose problems and datasets as per their
familiarity with specific domain.
2. Choose a dataset with reasonable size.
3. The dataset should have at least 6 columns and 10 MB in size.
4. Define the schema and load the data as per schema.
1. Ensure handling of bad record, if any, should be designed in the pipeline.
2) Business Insights
1. Define at least 7 key business insights that will be derived from the data.
1. Ingest the raw files into the Databricks file system.
2. Apply required schema and store the dataset as a table. Decide on the data
formats and partitions (if required) based on the analysis required to create
business insights.
3. Apply required data transformation before ingesting data into the table in a
columnar format.
4. The table should be utilized to create specified “Insights”.
3) Pipeline Creation
1. Choose two business insights (out of 7 insights) that will involve the below
complex operations.
 Projection, filter
 Group By
 Join
 Partition over ranking function
 Moving average
 Lead or lag
2. The pipelines can be created either using Spark DataFrame APIs (at least two)
or Spark SQLs (at least two) depending on your comfort and skill level.
4) Dashboards/Charts
1. Create one dashboard for each insight mentioned in the “Business Insights”
section.
2. Create charts whenever necessary using Databricks features or Seaborn or
matplotlib APIs. Mention the specific insights being created. And write that
queries (in SQL) for each specific insight.
5) Development Requirements
The solution should be developed:
1. On Databricks community edition and use spark DataFrame and/or Spark SQL
as required.
2. Code should follow PEP8 coding guidelines for code formatting
3. The code should be segregated into separate sections with proper headings.
Proper sections should be created for clarity (like heading 2/3).
4. The project name, team members (with IDs) and description at the top.
5. Clear description of the problem and dataset. Each section should be explained
clearly (objective and approach).
6. Describe the inferences from the business insights derived.
7. There should be conclusion section with summary of accomplishment and few
bulleted points of lessons learnt in developing the project.

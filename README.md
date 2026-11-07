# Learn Apache Spark by Doing: notebooks

The code of the lessons of [Learn Apache Spark by Doing](https://dataenglab.com/courses/learn-apache-spark-by-doing/), one notebook per module, to run in Google Colab without installing Java or Spark. Apache Spark 4.2.0, local mode.

| Module | Notebook |
|---|---|
| 2. Your first PySpark DataFrames | [Open in Colab](https://colab.research.google.com/github/dataeng-lab/learn-apache-spark-by-doing/blob/v2/notebooks/02-dataframes.ipynb) |
| 3. Spark SQL, joins and window functions | [Open in Colab](https://colab.research.google.com/github/dataeng-lab/learn-apache-spark-by-doing/blob/v2/notebooks/03-sql-joins-windows.ipynb) |
| 4. How Spark executes your code | [Open in Colab](https://colab.research.google.com/github/dataeng-lab/learn-apache-spark-by-doing/blob/v2/notebooks/04-execution.ipynb) |
| 5. Partitioning and file layout | [Open in Colab](https://colab.research.google.com/github/dataeng-lab/learn-apache-spark-by-doing/blob/v2/notebooks/05-partitioning.ipynb) |
| 7. Performance: diagnose before you tune | [Open in Colab](https://colab.research.google.com/github/dataeng-lab/learn-apache-spark-by-doing/blob/v2/notebooks/07-performance.ipynb) |
| 8. Structured Streaming | [Open in Colab](https://colab.research.google.com/github/dataeng-lab/learn-apache-spark-by-doing/blob/v2/notebooks/08-streaming.ipynb) |

The first cell installs Java 17 when the Colab image has an older one, installs `pyspark==4.2.0` and downloads `datasets.zip`: a synthetic webshop feed (orders, customers, order items, products, order events) generated for the course.

The Spark UI is not reachable from Colab. The lessons that rely on it, the final project, the tests and `spark-submit` are meant for your own machine; the course's setup lesson explains the install.

These notebooks are generated from the course lessons; changes are made there, not here.

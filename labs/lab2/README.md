# Data Engineering with Spark

## Lab 2: Structured data analysis with DataFrames

### Prerequisites

Connect to the Adaltas cloud cluster using OpenVPN.

### Goals

Analyze the New York City datasets:
- Gather interesting stats about the data

### Connection to Zeppelin

1. Navigate to http://zep-1.au.adaltas.cloud:9995 with your browser
2. Login using your Adaltas cloud credentials
3. In the folder `ece-2020/spark/ref`:
   1. Navigate to the `lab2` notebook
   2. Create a copy of the notebook (by using the **Clone this note** button) and name it like follow: `ece-2020/spark/cluster-username/lab2` (e.g. `ece-2020/spark/gauthier/lab2`). This should create your folder in `ece-20202/spark`.
   3. In your notebook `lab2` → **🔒 Note permissions**: add the user `gauthier` to the “Runners” (and any other user you want)
   4. Initialize your interpreter by running the first cell

### During the session

Go through the notebook and fill the blanks. By the end of the session we should have:
- Gathered basic stats about drivers
- Joined the 2 datasets to enrich the data

### Homework

1. Computed the total money earned by each driver for each day
2. Compute by hour:
   - The average tip
   - The average duration
   - The average “distance at the crow flies” (“à vol d’oiseau”)
3. Find the hour of the day when the tips are the highest
4. Find the percentage of each type of payment
5. Find the top 10 drivers that:
   - Won the most money
   - Did the greater number of rides

### Resources

Spark docs:

- [Spark SQL Guide](http://spark.apache.org/docs/latest/sql-programming-guide.html)
- [Pyspark SQL Module doc](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html)
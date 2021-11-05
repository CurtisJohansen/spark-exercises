# spark-exercises



## Spark Setup / Installation

1. Open up a terminal

1. Install the Java Environment

    ```
    brew tap adoptopenjdk/openjdk
    brew install adoptopenjdk11
    ```

1. Install `pyspark`

    ```
    python -m pip install pyspark
    ```

1. Launch a python session and verify your install

    ```
    python

    >>> import pyspark
    >>> spark = pyspark.sql.SparkSession.builder.getOrCreate()
    # lots of output...
    >>> spark.range(5).show()
    +---+
    | id|
    +---+
    |  0|
    |  1|
    |  2|
    |  3|
    |  4|
    +---+
    ```

1. If you've made it this far, you're good to go!
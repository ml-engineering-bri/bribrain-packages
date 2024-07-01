# BRIBrain

Python Packages Bribrain as a standard library for standardization code on data development process in the BRIBrain Department

## Installation

Use the package manager pip to install bribrain.

```bash
pip install bribrain
```

## Usage

```python
import bribrain

# returns spark session
spark = bribrain.sparkSession()

# returns list partition hive table
partitions = bribrain.get_list_partition(spark, schema, table)
```
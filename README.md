# What is Flink?

- Flink is open-source stream processing framework for distributed, high-performing, always available and data streaming apllication.
- It also provides support for Batch processing, Graph processing, Iterative processing.
- Speed comparison : Flink > Spark > Hadoop.
- Low latency and high throughput application.

-------------------------------------------------------------------------

# Hadoop vs Spark/Flink

## Hadoop
- Batch processing framework.
- Read and write data from disk. (HDFS -> MAPPER -> REDUCER -> Output file)
- Manual hand code each and every operation.
- Does not support iterative processing. (Chain mappers and chain reducers are available but not efficient).

## Flink
- Streaming processing framework.
- Read and write in memory. (input_file -> In memory operations -> output_file).
- Easy to program with tons of high level operators.
- Supports iterative processing.

-------------------------------------------------------------------------

# Spark vs Flink

## Spark
- Spark is not a true real time processing framework, it's near to real time processing framework.
- Spark is implemented in Scala.
- Spark does not have an efficient memory management.

## Flink
- Flink is focused on the streaming processing.
- Flink is implemented in Java.
- Flink has it's own efficient automatic memory manager.

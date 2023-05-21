"What is Flink?"

1. Flink is open-source stream processing framework for distributed, high-performing, always available and data streaming apllication.
2. It also provides support for Batch processing, Graph processing, Iterative processing.
3. Speed comparison : Flink > Spark > Hadoop.
4. Low latency and high throughput application.

-------------------------------------------------------------------------

"Hadoop vs Spark/Flink"

Hadoop
- Batch processing framework.
- Read and write data from disk. (HDFS -> MAPPER -> REDUCER -> Output file)
- Manual hand code each and every operation.
- Does not support iterative processing. (Chain mappers and chain reducers are available but not efficient).

Flink
- Streaming processing framework.
- Read and write in memory. (input_file -> In memory operations -> output_file).
- Easy to program with tons of high level operators.
- Supports iterative processing.
## REFERENCES  

* MapD Source code:  https://github.com/mapd/mapd-core
* General information about column-store databases:  http://www.redbook.io/ch4-newdbms.html
* MapD optimization using Apache Calcite:  https://www.mapd.com/blog/2017/02/08/fast-and-flexible-query-analysis-at-mapd-with-apache-calcite-2/
* GPU
  * GPU-tuned algorithms:  https://arxiv.org/pdf/1702.08734.pdf
  * Bucket Select:   http://www.math.grin.edu/~blanchaj/Research/ABGS_KSelection.pdf
  * Optimizing Data Warehousing with GPUs:  http://gpuocelot.gatech.edu/wp-content/uploads/optimizing-data-warehousing-applications-GPUs.pdf
  * GPUs + Data Warehousing:  http://gpuocelot.gatech.edu/publications/optimizing-data-warehousing-applications-for-gpus-using-kernel-fusionfission/
* Overview of MapD and GPUs:  https://www.mapd.com/blog/2017/01/23/what-is-a-gpu-and-why-do-i-care-a-businesspersons-guide-2/
* MapD + GPU + Machine Learning:  https://www.mapd.com/blog/2017/05/30/end-to-end-on-the-gpu-with-the-gpu-data-frame-gdf/
* Compiler Resources
  * LLVM:  https://llvm.org
  * MapD explanation of use of LLVM:  https://devblogs.nvidia.com/parallelforall/mapd-massive-throughput-database-queries-llvm-gpus/
  * Stack vs. Register speeds:  https://arxiv.org/abs/1611.00467
  * Discussion - stack vs. register:  https://markfaction.wordpress.com/2012/07/15/stack-based-vs-register-based-virtual-machine-architecture-and-the-dalvik-vm/
  * JIT SQL execution engines:  https://sandjoshi.wordpress.com/2016/02/29/jit-style-sql-execution-engines/
  * Kernel Fusion:  http://www.compileroptimizations.com/category/loop_fusion.htm
  * MapD + Kernel Fusion: https://devblogs.nvidia.com/parallelforall/mapd-massive-throughput-database-queries-llvm-gpus/
  * Performance benchmarks:  C++ and LLVM:  https://blog.acolyer.org/2016/05/23/efficiently-compiling-efficient-query-plans-for-modern-hardware/
  * How SQL Server executes a query:  http://rusanu.com/2013/08/01/understanding-how-sql-server-executes-a-query/
* MapD + Kafka streams:  https://www.mapd.com/docs/latest/mapd-core-guide/kafka/
* MapD + distributed computing:  https://www.mapd.com/docs/latest/getting-started/ha/?highlight=distributed
* Quantum
  * ScaffCC:  https://arxiv.org/pdf/1507.01902.pdf
  * Discussion of ScaffCC, Scaffold, QASM:  https://www.quora.com/Will-programming-languages-need-to-be-rebuilt-in-the-face-of-quantum-computing-Would-it-be-worth-it
  * General Quantum article:  https://www.nature.com/nature/journal/v549/n7671/full/nature23459.html?foxtrotcallback=true
* MapD Tweetmap:  https://www.mapd.com/blog/2017/09/15/tweetmap-data-bigdata-mapd/)
* MapD whitepaper:  http://go.mapd.com/rs/116-GLR-105/images/MapD%20Technical%20Whitepaper%20Summer%202016.pdf
* Cloudera Impala + LLVM:  https://llvm.org/devmtg/2013-11/slides/Wanderman-Milne-Cloudera.pdf
* MemSQL:  http://blog.memsql.com/memsql-5-ships/

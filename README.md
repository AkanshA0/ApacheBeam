# ApacheBeam

This project provides an end-to-end demonstration of various Apache Beam concepts and transforms, including:

-   **Installation and Imports**: Setting up the environment and importing necessary libraries.
-   **Minimal Pipeline**: A basic example to understand the fundamental structure of a Beam pipeline.
-   **Pipeline IO**: Reading data from a text file (`ReadFromText`) and writing results to a text file (`WriteToText`).
-   **Element-wise Transforms**: Using `Map`, `Filter`, and `ParDo` (with a custom `DoFn`) to process individual elements in a PCollection.
-   **Composite Transform (PTransform)**: Encapsulating a sequence of transforms into a reusable `PTransform`.
-   **Partition**: Splitting a single PCollection into multiple PCollections based on a partitioning function.
-   **Windowing**: Demonstrating fixed windows with `TestStream` to process data based on event time.

**Sections include:**

1.  Install & Imports
2.  First Minimal pipeline
3.  Pipeline IO: ReadFromText & WriteToText
4.  Map · Filter · ParDo (DoFn)
5.  Composite Transform (PTransform)
6.  Partition
7.  Windowing

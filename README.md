# Project B: CSV Mini Database & Query Engine

Project B is a lightweight CSV-based mini database and query engine designed to store, manage, and query structured data from comma-separated value files without relying on a full database system.

This project focuses on:

- Parsing CSV data into in-memory table structures.
- Supporting basic query operations such as selection, projection, filtering, sorting, and aggregation.
- Providing a simple query syntax or API for retrieving and analyzing CSV data.
- Delivering a compact, efficient engine ideal for small datasets, educational use, and rapid prototyping.

The goal is to demonstrate how a minimal database engine can be built from scratch for data persistence and query processing using CSV as the underlying data format.

## Overview

The CSV Mini Database & Query Engine is intended to mimic core database behavior using plain CSV files. It aims to provide a clear, modular implementation of:

- CSV file parsing and schema detection.
- Row-based storage in memory.
- Query evaluation over tables.
- Output formatting and reporting.

This project is especially useful for learning how database internals work and for small-scale applications where full database systems are unnecessary.

## Key Features

- CSV import and parsing with support for header rows.
- Basic query operations:
  - Selection (`WHERE`-style filtering)
  - Projection (column selection)
  - Sorting and ordering
  - Aggregation (sum, count, average, min, max)
- Simple query builder or API to run queries against loaded CSV tables.
- In-memory execution for fast response on modest datasets.

## How It Works

1. Load a CSV file into memory as a table.
2. Parse the header row to identify column names.
3. Convert each CSV record into a typed row representation.
4. Execute query operations step-by-step over the loaded table.
5. Return results in a readable table or CSV format.

## Example Use Cases

- Dataset exploration and quick ad hoc analysis.
- Educational demonstrations of query processing concepts.
- Prototyping applications that need lightweight data storage.
- Small projects where external database installation is impractical.

## Future Improvements

Potential enhancements for later versions include:

- Support for joins between multiple CSV tables.
- Query optimization and indexing.
- Persistent storage of query results.
- More advanced query syntax with nested conditions.
- Support for additional file formats such as TSV or JSON.

## Project Structure

At present, this repository contains the project documentation and can be extended with implementation files for the CSV parser, query engine, and usage examples.

## Getting Started

1. Add source code files for CSV parsing and query execution.
2. Implement a command-line driver or API entry point.
3. Load a sample CSV file and execute queries against it.
4. Display the output as table rows or write results back to a file.

## Notes

This repository is intentionally simple and focused on the core idea of building a mini database engine around CSV input. It is a strong foundation for expanding into more advanced data management and query processing topics.

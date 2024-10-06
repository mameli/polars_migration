# Pandas to Polars in Data Analysis

This project explores the transition from using Pandas to Polars for data analysis, highlighting the advantages and challenges of adopting Polars, a DataFrame library built with Rust.

## Table of Contents

- [Introduction](#introduction)
- [Why Polars?](#why-polars)
- [Use Case](#use-case)
- [Migration Process](#migration-process)
- [Key Observations](#key-observations)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

The data community is witnessing a trend of rebuilding popular products using Rust. Polars is one such example, offering a fast and efficient alternative to Pandas for data manipulation.

## Why Polars?

Polars is described as a "blazingly fast DataFrame library" and offers several advantages over Pandas, including speed and a different, more intuitive syntax. It is gaining traction due to its passionate community and compatibility with major data science libraries.

## Use Case

The project involves migrating an existing Pandas notebook to Polars, using a Kaggle Titanic dataset as a practical example. The goal is to evaluate the ease of migration and the benefits of using Polars in real-world scenarios.

## Migration Process

The migration involves converting Pandas code to Polars, utilizing Polars' unique syntax and functions. Key changes include:

- Replacing `info()` with `describe()`
- Using `null_count()` instead of `isna().sum()`
- Adopting Polars' `when`, `then`, and `otherwise` functions for conditional operations

## Key Observations

- **Syntax**: Polars offers a more explicit and verb-based syntax compared to Pandas, making it easier to understand and write.
- **Ecosystem**: Polars is compatible with libraries like Matplotlib, Plotly, Seaborn, and Scikit-Learn.
- **Data Handling**: Polars provides clear and efficient handling of null and NaN values, improving code clarity and reducing errors.
- **Performance**: Polars demonstrates better performance for data transformations and large datasets.

## Conclusion

Polars is a promising alternative to Pandas, especially for personal projects. However, adopting it in a work environment requires consideration of existing workflows, team receptiveness, and current challenges with Pandas.

## References

- [Polars Migration GitHub Repository](https://github.com/mameli/polars_migration)
- [Polars Documentation](https://docs.pola.rs/user-guide/getting-started/)
- [Pandas vs Polars Syntax Comparison](https://codecut.ai/pandas-vs-polars-syntax-comparison-for-data-scientists/)
- [Polars vs Pandas Benchmarking](https://blog.jetbrains.com/pycharm/2024/07/polars-vs-pandas/)
- [Kaggle Titanic Dataset](https://www.kaggle.com/code/faressayah/data-science-best-practices-using-pandas-titanic)
<h2 align="center">
   Data-Clumps-Dataset
</h2>

<p align="center">
    <img src="https://github.com/FireboltCasters/Data-Clumps-Dataset/raw/main/public/logo.png" alt="logo" style="height:100px;"/>
</p>


<h3 align="center">
Data-Clumps Deep Dive: A Granular Dataset for Enhanced Software Analysis
</h3>

## About

This repository contains a comprehensive dataset for data-clumps at various levels including file, class, method, field, parameter, and code line. The aim of this dataset is to provide a rich resource for researchers and developers interested in studying and understanding data-clumps in software development.

Unlike unified datasets, this dataset is unique in its focus on data-clumps and its granularity, providing detailed data at multiple levels. This allows for a more in-depth analysis and understanding of data-clumps and their impact on software quality and maintainability.

## Dataset Scope

Our dataset is specifically designed to focus on the source code of the project itself, excluding external modules and packages. This means that while we strive for comprehensive data-clump detection, some data-clumps that span across external dependencies may not be included. Our primary aim is to provide a detailed analysis of data-clumps within the boundaries of the individual project, offering a focused perspective on the project's internal code structure and quality.


## Dataset Format

In our endeavor to ensure precision and standardization in reporting data clumps, we utilize the following specification: [Data-Clumps-Type-Context](https://github.com/FireboltCasters/data-clumps-type-context/).
It provides information at different levels, each level provides specific insights into the occurrence and characteristics of data-clumps:
- File Level
   - Class Level
      - Method Level
         - Field Level
            - Parameter Level
               - Code Line Level


## Usage
This dataset can be used for a variety of research and practical applications including:

- Studying the impact of data-clumps on software quality
- Developing and validating models for predicting data-clumps
- Understanding the distribution and characteristics of data-clumps at various levels of software development

## Contribution

Feel free to analyse your repository and upload the results using our [Contribution Guide](https://github.com/FireboltCasters/Data-Clumps-Dataset/Doc/Contribution_Guide.md).

## Data Acquisition
Our dataset is generated using the data-clumps detection tool available at [FireboltCasters/data-clumps](https://github.com/FireboltCasters/data-clumps). This tool is based on the award-winning research paper titled `Live Code Smell Detection of Data Clumps in an Integrated Development Environment`. This paper was honored with the Best Student Paper Award and can be accessed [here](https://www.scitepress.org/Link.aspx?doi=10.5220/0011727500003464). By leveraging this cutting-edge technology, we've ensured the highest level of accuracy and reliability in our data-clumps detection process.

## Keywords
Data-clumps, software metrics, static code analysis, data-clump prediction

## Access:
The dataset is publicly available for everyone. Researchers and developers are encouraged to use this dataset for their studies and to contribute to its improvement.


## Related Applications
- [Data-Clumps Visualizer](https://github.com/FireboltCasters/data-clumps-visualizer)  
   For a more interactive experience with our dataset, we recommend using the Data-Clumps Visualizer. This tool allows you to upload the data-clumps files and visualize them, providing a more intuitive understanding of the data. You can access the Data-Clumps Visualizer [here](https://github.com/FireboltCasters/data-clumps-visualizer). Explore, analyze, and gain insights from our dataset in a visually engaging manner.
- [data-clumps](https://github.com/FireboltCasters/data-clumps)
   The detection tool used to generate this dataset

## Roadmap

- [ ] Scripts
   - [ ] Add auto script support analyse projects

## License

MIT


## Contributors

<a href="https://github.com/FireboltCasters/Data-Clumps-Dataset"><img src="https://contrib.rocks/image?repo=FireboltCasters/Data-Clumps-Dataset" alt="Contributors" /></a>

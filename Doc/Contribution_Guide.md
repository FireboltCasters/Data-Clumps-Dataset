<h2 align="center">
   Contribution Guide
</h2>

<p align="center">
    <img src="https://github.com/FireboltCasters/Data-Clumps-Dataset/raw/main/public/ContributionIcon.png" alt="logo" style="height:100px;"/>
</p>

## Data Generation Procedure
The generation of this dataset can be performed by executing the following command:

```
npx data-clumps@0.1.93 --output <path_to_output> --commit_selection tags --source <source_files> <path_to_project>
```

### Parameter Explanation:

- `<path_to_output>`
   - This is the output directory where the generated data will be stored. The format of this path should be as follows: /Data-Clumps-Dataset/Data/Projects/{project_name}/tags/{project_commit}.json. The {project_name} and {project_commit} must be replaced with the respective name of the project and the commit hash/tag respectively.
- `<path_to_project>`
   - This is the root directory of the project which is to be analyzed. For example, if your project argouml is located in the Documents/Git/ directory, the path should be /Documents/Git/argouml.
- `<source_files>`
   - This is the directory containing the source files to be analyzed. In the context of our example project argouml, this directory could be /Documents/Git/argouml/src/argouml-app.

Example Execution:
Suppose, we wish to generate the dataset for a project named argouml. The command would be as follows:

```
npx data-clumps@0.1.93 --output /Users/nbaumgartner/Documents/GitHub/Data-Clumps-Dataset/Data/Projects/argouml/tags/{project_commit}.json --commit_selection tags --source /Users/nbaumgartner/Desktop/argouml/src/argouml-app /Users/nbaumgartner/Desktop/argouml
```

The variable `{project_commit}` will be replaced with the specific commit hash/tag if you have a git repository.






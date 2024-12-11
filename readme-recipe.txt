---
title: "Create README.md Files Recipe"
date: "`r Sys.Date()`"
output: html_document
---

# Create README.md Files

## Ingredients

* Project information
* Installation requirements
* Usage instructions
* Project structure
* Contributing guidelines
* License information

## Instructions

Use this prompt template:

````
Please help create a README.md for:

### Project Overview
* Name: [project name]
* Type: [package/analysis/dashboard/etc]
* Purpose: [main goal]
* Status: [development/production/archived]

### Technical Details
* Language: [R/Python/etc]
* Dependencies: [key packages/requirements]
* System requirements: [if any]
* Compatibility: [versions/platforms]

### Structure needs:
* Sections needed:
    - [list key sections]
* Detail level: [basic/intermediate/comprehensive]
* Special requirements:
    - [badges needed]
    - [graphics/logos]
    - [specific formatting]

### Additional elements:
* Example code: [yes/no]
* Contributing guidelines: [yes/no]
* Citation information: [if needed]
* Documentation links: [if available]
````

## Tips

* Start with clear overview
* Include installation steps
* Show basic usage example
* List dependencies clearly
* Add badges if relevant
* Include contact info
* Consider CI/CD needs

## Serves

* R packages
* Analysis projects
* Data products
* Dashboards
* Documentation
* Teaching materials
* Research projects

## Example

````
Please help create a README.md for:

### Project Overview
* Name: tidyhydrology
* Type: R package
* Purpose: Streamflow data analysis tools
* Status: development

### Technical Details
* Language: R (>= 4.0.0)
* Dependencies:
    * tidyverse
    * lubridate
    * sf
* System requirements: none
* Compatibility: All platforms

### Structure needs:
* Sections needed:
    - Installation
    - Basic usage
    - Functions
    - Data sources
    - Contributing
    - License
* Detail level: comprehensive
* Special requirements:
    - CRAN/GitHub badges
    - Example plots
    - Code of conduct link

### Additional elements:
* Example code: yes
* Contributing guidelines: yes
* Citation: yes
* Documentation: pkgdown site
````

## Standard Sections

### Essential Sections

1. **Title and Description**
   * Project name
   * Brief description
   * Status badges
   * Key features

2. **Installation**
   * Prerequisites
   * Step-by-step instructions
   * System requirements
   * Troubleshooting

3. **Usage**
   * Basic examples
   * Common use cases
   * Configuration
   * Options

4. **Documentation**
   * Function reference
   * Vignettes
   * Tutorials
   * API documentation

### Optional Sections

1. **Development**
   * Contributing guide
   * Development setup
   * Testing instructions
   * Style guide

2. **Community**
   * Code of conduct
   * Support channels
   * Discussion forums
   * Issue reporting

3. **Project Status**
   * Roadmap
   * Known issues
   * Release notes
   * Version history

4. **Meta Information**
   * Authors
   * License
   * Citation
   * Acknowledgments

## Style Guidelines

### Formatting

1. **Headers**
   * Clear hierarchy
   * Descriptive titles
   * Consistent capitalization
   * Proper nesting

2. **Code Blocks**
   * Syntax highlighting
   * Clear examples
   * Output comments
   * Error handling

3. **Lists**
   * Consistent markers
   * Proper indentation
   * Logical grouping
   * Clear hierarchy

4. **Links**
   * Descriptive text
   * Working URLs
   * Internal references
   * External resources


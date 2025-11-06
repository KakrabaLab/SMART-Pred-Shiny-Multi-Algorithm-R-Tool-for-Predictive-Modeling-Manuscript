<!-- PROJECT LOGO -->
<h1 align="center">Basic SMART-pred</h1>

  <p align="center">
    SMART-pred is an interactive web application built with R Shiny that provides a comprehensive and customized machine-learning and deep-learning pipeline for classification and regression tasks. 
    <br />
    <a href="https://github.com/whan4/Basic-SMART-pred"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/whan4/Basic-SMART-pred/issues">Report Bug</a>
    ·
    <a href="https://github.com/whan4/Basic-SMART-pred/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The application offers an intuitive interface for data analysis, model training, and performance evaluation. At the same time, an R markdown pipeline version is also provided for developers to conduct customized analysis. The design of this software aims to enable talented researchers without programming expertise to fully leverage these powerful analytical methods.This repository is just a _**demo version**_. If you would like more features and a complete version of the app, please contact us.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To install this software, please follow the steps below.

### Prerequisites

R (version 4.4.0) and R Studio software(Strongly Recommend).

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/whan4/Basic-SMART-pred.git
   ```
2. Open R project by clicking on R.Rprofile
3. Restore R packages by renv.lock
   ```r
   renv::restore()
   ```
4. Install dependencies
   ```r
   install.packages("shiny", "rmarkdown")
   ```
5. Every time you run the app, the software will perform a self-check. If additional packages are needed, select 'y' to install them.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

### R Shiny Web Application

1. Open R and set working directory
2. Launch the app
```r
library(shiny)  
runApp('./app')
```
### R markdown pipeline

If you want to reproduce the result in our paper, please load _**partial_air_paper_pca_results**_, _**full_varimp_results.rds**_, _**full_pca_results.rds**_ and run specific code block of _**pipeline.Rmd**_ to get the specific result.

1. Open R and set working directory
2. Run the whole pipeline or specific code block

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

### [Samuel Kakraba, PhD.](https://sph.tulane.edu/bios/samuel-kakraba), led supervisor

- 1440 Canal St, New Orleans, LA 70112, USA

- Tel: +1-504-988-2475

- Email: [samuel.kakraba@tulane.edu](samuel.kakraba@tulane.edu) 

### [Sudesh Srivastav, PhD.](https://sph.tulane.edu/bios/sudesh-srivastav)

- 1440 Canal St, New Orleans, LA 70112, USA

- Tel: +1-504-988-2472

- Email: [ssrivas@tulane.edu](ssrivas@tulane.edu) 

Project Link: [https://github.com/whan4/Basic-SMART-pred](https://github.com/whan4/Basic-SMART-pred)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Contributors
* Han Wenzheng,Department of Biostatistics and Data Science, Celia Scott Weatherhead School of Public Health and Tropical Medicine at Tulane University, New Orleans, LA, USA
* [Edmund F. Agyemang, PhD(Student), Department of Biostatistics and Data Science, Celia Scott Weatherhead School of Public Health and Tropical Medicine at Tulane University, New Orleans, LA, USA
*[Samuel Kakraba, PhD.](https://sph.tulane.edu/bios/samuel-kakraba), Assistant Professor, Department of Biostatistics and Data Science, Celia Scott Weatherhead School of Public Health and Tropical Medicine at Tulane University, New Orleans, LA, USA
* [Sudesh Srivastav, PhD.](https://sph.tulane.edu/bios/sudesh-srivastav), Professor,Department of Biostatistics and Data Science, Celia Scott Weatherhead School of Public Health and Tropical Medicine at Tulane University, New Orleans, LA, USA
*[Prof. Jeffery G. Shaffer, PhD.](https://sph.tulane.edu/bios/jeffrey-shaffer), Associate Professor, Department of Biostatistics and Data Science, Celia Scott Weatherhead School of Public Health and Tropical Medicine at Tulane University, New Orleans, LA, USA

## Acknowledgments  

* [Shiny Framework](https://shiny.posit.co/)
* [Caret R package](https://github.com/topepo/caret)  

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->

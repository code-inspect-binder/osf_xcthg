# Executable Environment for OSF Project [xcthg](https://osf.io/xcthg/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Fandom biases retrospective judgments not perception

**Project Description:**
> Attitudes and motivations have been shown to affect the processing of visual input, indicating that observers may see a given situation each literally in a different way. Yet, in real-life, processing information in an unbiased manner is considered to be of high adaptive value. Attitudinal and motivational effects were found for attention, characterization, categorization, and memory. On the other hand, for dynamic real-life events, visual processing has been found to be highly synchronous among viewers. Thus, while in a seminal study fandom as a particularly strong case of attitudes did bias judgments of a sports event, it left the question open whether attitudes do bias prior processing stages. Here, we investigated influences of fandom during the live TV broadcasting of the 2013 UEFA-Champions-League Final regarding attention, event segmentation, immediate and delayed cued recall, as well as affect, memory confidence, and retrospective judgments. Even though we replicated biased retrospective judgments, we found that eye-movements, event segmentation, and cued recall were largely similar across both groups of fans. Our findings demonstrate that, while highly involving sports events are interpreted in a fan dependent way, at initial stages they are processed in an unbiased manner.

**Original OSF Page:** [https://osf.io/xcthg/](https://osf.io/xcthg/)

---

**Important Note:** The contents of the `xcthg_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_xcthg/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_xcthg/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `xcthg_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-xcthg:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-xcthg
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.

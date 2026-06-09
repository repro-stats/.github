<div align="center">

<br/>

**Reproducibility infrastructure for statistical computing in R**

<br/>

<!-- Ecosystem: reproducr hex + placeholder slots for future packages -->

<!--
<img src="https://raw.githubusercontent.com/repro-stats/.github/main/profile/ecosystem.svg"
width="520" alt="repro-stats ecosystem" />
-->

<br/><br/>

[![CRAN](https://img.shields.io/badge/CRAN-reproducr-276DC3?logo=r&logoColor=white)](https://cran.r-project.org/package=reproducr)
[![docs](https://img.shields.io/badge/docs-repro--stats.github.io-0F6E56)](https://repro-stats.github.io/reproducr/)
[![database](https://img.shields.io/badge/database-reproducr--db-orange)](https://github.com/repro-stats/reproducr-db)

</div>

-----

## What we build

Silent breaking changes in R packages corrupt analytical results without
error or warning. We build tooling that makes these risks visible, trackable,
and auditable — for academia, pharma, and regulated workflows.

-----

## Packages

|Package                                                        |Description                                                   |Status                                                                                                                                                                            |
|---------------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|[**reproducr**](https://github.com/repro-stats/reproducr)      |Audit scripts, certify outputs, detect drift, generate reports|[![R-CMD-check](https://github.com/repro-stats/reproducr/actions/workflows/R-CMD-check.yml/badge.svg)](https://github.com/repro-stats/reproducr/actions/workflows/R-CMD-check.yml)|
|[**reproducr-db**](https://github.com/repro-stats/reproducr-db)|Community database of known silent breaking changes           |[![validate](https://github.com/repro-stats/reproducr-db/actions/workflows/validate.yml/badge.svg)](https://github.com/repro-stats/reproducr-db/actions/workflows/validate.yml)   |

-----

## Gallery

|Repo                                                                   |Domain                    |Report  |
|-----------------------------------------------------------------------|--------------------------|--------|
|[reproducr-ecology](https://github.com/repro-stats/reproducr-ecology)  |Ecology / penguins        |minimal |
|[reproducr-clinical](https://github.com/repro-stats/reproducr-clinical)|Clinical trials / oncology|pharma  |
|[reproducr-rwe](https://github.com/repro-stats/reproducr-rwe)          |Real world evidence       |academic|
|[reproducr-cmc](https://github.com/repro-stats/reproducr-cmc)          |CMC statistics / ICH      |pharma  |

-----

## Contributing

Add a breaking-change entry to [**reproducr-db**](https://github.com/repro-stats/reproducr-db) —
see the [contributing guide](https://github.com/repro-stats/reproducr-db/blob/main/CONTRIBUTING.md).

-----

<div align="center">
<sub>MIT licensed &nbsp;·&nbsp; built with R &nbsp;·&nbsp; contributions welcome</sub>
</div>

# OpenSAFELY COVID-19 Vaccine Coverage Report

This is the code and configuration of our pre-print paper available the [OpenSAFELY website here](https://opensafely.org/research/2021/covid-vaccine-coverage/) and on [MedRxiv here](https://www.medrxiv.org/content/10.1101/2021.01.25.21250356v2). You can sign up for the [OpenSAFELY email newsletter here](https://opensafely.org/contact/) for updates about the COVID-19 vaccine reports and other OpenSAFELY projects.


- If you are interested in how we defined our variables, take a look at the [study definition](analysis/study_definition_delivery.py); this is written in `python`, but non-programmers should be able to understand what is going on there.
- We have made .csv files available here in the [`machine readable outputs`](https://github.com/opensafely/nhs-covid-vaccination-coverage/tree/master/released-outputs/machine_readable_outputs) folder with the data behind the tables and charts for inspection, further analysis and re-use by anyone as long as [OpenSAFELY.org](https://opensafely.org/) is credited and/or linked to.
* If you are interested in how we defined our code lists, look in the [codelists folder](./codelists/). All codelists are available online at [OpenCodelists](https://codelists.opensafely.org/) for inspection and re-use by anyone 
* - Jupyter notebooks prepared to generate tables and graphs are in `/notebooks`. If notebooks do not load you can paste the link in https://nbviewer.jupyter.org/ Please note these contain dummy data. See `released outputs` folder for outputs.
* Developers and epidemiologists interested in the framework should review [the OpenSAFELY documentation](https://docs.opensafely.org)

# About the OpenSAFELY framework

The OpenSAFELY framework is a secure analytics platform for
electronic health records research in the NHS.

Instead of requesting access for slices of patient data and
transporting them elsewhere for analysis, the framework supports
developing analytics against dummy data, and then running against the
real data *within the same infrastructure that the data is stored*.
Read more at [OpenSAFELY.org](https://opensafely.org). 


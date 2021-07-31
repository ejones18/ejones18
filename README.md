## Hi there! 👋 ##

I am a 2nd year undergraduate student studying towards a Bachelor's degree in Computer Science at the University of Sheffield. Alongside my degree, I am an assistant data analyst at <a href="https://www.solar.sheffield.ac.uk/"> Sheffield Solar </a> - A research group based at The University of Sheffield. I have recently worked with Sheffield Solar alongside the Turing Institute and Open Climate Fix on the <a href="https://www.turing.ac.uk/research/research-projects/solar-nowcasting-machine-vision">‘solar nowcasting with machine vision’</a> project which aims to produce an open PV dataset with high coverage across the UK that will have positive knock-on effects in the on-going battle against climate change. My prior responsibilities include the managing, uploading and analysing of PV data on <a href="https://www.microgen-database.org.uk/">Microgen Database</a> as well as the development of the Sheffield Solar PV-live interactive regional map back in 2017 which helps to map the regional PV production across the UK.

## Projects ##

### *Solar nowcasting with machine vision* ###
Joint project between Sheffield Solar, Turing Institute and Open Climate Fix with the aim to produce an open PV dataset with high coverage across the UK that will have positive knock-on effects in the on-going battle against climate change.

My role in the project was the cleaning, validation and analysis of the PV dataset. I semi-automated this process by creating a series of scripts in Python using libraries like Pandas as well as a lightweight flask application that provided a visual aide to validate the PV matches. I also used JMP alongside data exploration techniques when looking through existing datasets such as the REPD.

### *COVID-19 UK case visualiser* ###

An <a href="http://covidmap.ddns.net:8080/">Angular.js site</a> that visualises the UK's COVID-19 case data on both an interactive map and graph. Uses the <a href="https://coronavirus.data.gov.uk/details/developers-guide">Public Health England Python API</a> for the data and uses highcharts and leaflet.js to display it. A <a href="https://github.com/ejones18/nhs_covid_visualiser">data handling script</a> with a CLI was also developed.

### *PV_Live API version 3* ###

The <a href="https://www.solar.sheffield.ac.uk/pvlive/api/">PV_Live web API</a> (Application Programming Interface) provides access to near-real-time and historical estimates of PV generation on the GB transmission network. It returns a computer friendly (JSON) response for use in software, websites, apps etc. My role in the development of the third version of the API covered writing unit tests, updating existing functionality to enable data to be returned as a Pandas DataFrame as well as improving user experience by simplifying function parameters etc.

### *Regional PV_Live - Generation mapping* ###
An interactive map which accesses data in real-time from the project’s web APIs and enabled users to examine regional PV out-turn estimates in more detail.

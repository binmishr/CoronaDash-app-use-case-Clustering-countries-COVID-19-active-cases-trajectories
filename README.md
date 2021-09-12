# CoronaDash-app-use-case-Clustering-countries-COVID-19-active-cases-trajectories

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

The dataset : https://petolau.shinyapps.io/coronadash/

COVID-19 disease spread hit the World really globally and also the field of mathematicians/ statisticians/ machine learning researchers and related.
These experts want to help to understand for example future trends (forecast) of the coronavirus spread. My motivation, in this case, was to create interactive dashboard about COVID-19 to inform about various scenarios in every country and compare them through data mining methods.

CoronaDash shinydashboard application that is hosted on https://petolau.shinyapps.io/coronadash/
The dashboard provides various data mining/ visualization techniques for comparing countries’ COVID-19 data statistics as:

    1.extrapolating total confirmed cases by exponential smoothing model,
    2.trajectories of cases/ deaths spread,
    3.multidimensional clustering of countries’ data/ statistics – with dendrogram and table of clusters averages,
    4.aggregated views for the whole World,
    5.hierarchical clustering of countries’ trajectories based on DTW distance and preprocessing by SMA (+ normalization), for fast comparison of a large number of countries’ COVID-19 magnitudes and trends.

I use the below datsets:

1. worldometers population size datsets: https://www.worldometers.info/coronavirus/
2. Test data : covid19-master -covid19-master -Test Data.zip
3. Cases and Death Numbers : COVID-19-master cases and deaths numbers.zip
4. recovery cases number : covid19-timeseries-master recovery cases number.zip

Tsrepr package documentation : https://cran.r-project.org/web/packages/TSrepr/index.html

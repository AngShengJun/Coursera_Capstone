
# IBM Data Science Professional Capstone - Battle of the Neighborhoods

## Background
This capstone project is the cumulation of the courses within the syllabus of the 
IBM Data Science Professional Course. 

For this project, course participants are introduced to the FourSquare API and
Geopy library for working with geospatial data. The broad sceanrio is to identify
a business problem that requires the use of location data and neighborhood clustering.

In my instance, I imagined a client has approached the Consultation firm to seek 
advise on the business strategies and execution roadmap for setting up restaurants
 in Kyoto. 
 The initial business problem question is “Should the Client setup a restaurant chain
  in Kyoto, and where?”


I decided on to collect and analyse restaurants in Kyoto, 
perform neighborhood clustering and derive insights to influence the formulation 
of business strategies for the client. 


## Final Report

[Link to Report](https://github.com/AngShengJun/Coursera_Capstone/blob/main/Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods%20(Week%201%262)%20report.pdf)

  
## Lessons Learned

### Geopy libary and Subject Matter Knowledge
Having some prior knowledge of the wards in Kyoto and other Japan cities
such as Tokyo greatly facilitated in troubleshooting of the visualization of 
geo spatial data. Not all kyoto wards were generated on the initial folium map.
The probable cause was in the presence of duplicated ward names across different cities,
Geopy had defaulted to retrival of Tokyo ward coordinates. The issue was easily resolved
through specifying the affected ward names, followed by the city name in Geopy.

### Choice of colors for visualization
The initial choice of colors selected for visualization was unable to clearly 
present all the clustered restaurants. This led to an erroneous assumption that K-Means 
Clustering had returned fewer clusters than the specified k clusters. Updating 
the colormap for improved visuals addressed the visualizations.

### Optimum number of K for K-Means Clustering
This was not explicitly covered in the course. Literature review on K-Means 
clustering prior to project commencement had highlighted this aspect. For this project,
the Silhouette method was implemented to determine the optimum number of k for clustering.

### Creative & Structured Problem Solving
A mix of creative and structured problem solving approaches was applied to reframe the
 initial problem statement. Through this process, the problem statement was better defined
 as "What can be done to determine the Client’s business positioning and potential 
 restaurant locations in Kyoto?" This had also brought clarity in terms of the rationale 
 and limitations of applying K-Means Clustering to address specific parts of the 
 business problem. 

### Project Efficiency Tools
Use of readme.so tool greatly facilitated the creation and editing of the project README.  
## Author

- [@AngShengJun](https://github.com/AngShengJun)

  

# Seismic Event Clustering in Mainland Portugal: DBSCAN Approach

The identification of seismic zones continues to be a relevant topic, mainly in regions with considerable seismic activity, as is the case of Portugal, and the application of quantitative methods has shown to be highly versatile. In this work, in a first part, the DBSCAN algorithm is applied to a catalog of seismic events for Mainland Portugal and surrounding maritime area, considering the Haversine distance between epicentres of seismic events. When compared to a defined seismic zonation, the resulting clusters fit especially well within the zones. In a second part, a novel distance index is presented. This index will calculate the distances between seismic events taking into account, not only the geographical distance between epicentres, but also the time of occurrence and size of the events. 

The distance values calculated with the proposed distance index will be used in conjunction with the DBSCAN algorithm with the purpose of identifying sets of seismic events originated from the same geological structures but in different time periods. With simulated data, the proposed distance index shows exactly the intended behaviour. Applying it to the seismic event catalog for Mainland Portugal, also shows interesting results, being able to identify several geographically overlapped clusters but separated in time. 

This approach could be used to study how often seismic activity is expected from a specific geological structure and how these structures interact with each other.

![Geogrphical representation of earthquakes based on their magnitude.](https://github.com/andrebrito0/dbscan_seismic_data/blob/main/map.pdf)

![Geogrphical representation of seismic clusters.](https://github.com/andrebrito0/dbscan_seismic_data/blob/main/mapST.pdf)

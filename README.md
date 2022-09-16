Summary of the project

A talent sourcing and management company is interested in finding talented individuals for sourcing these candidates to technology companies. The nature of the job requires a lot of human labor and is full of manual operations. Towards automating this process they want to build a better approach that could save them time and finally help spot potential candidates that could fit the roles which are in search for.
    
    The objective is to create a robust and automated ML model that is able to list and rank potential candidates based on a fit score.
    
    The data* comes from their sourcing efforts. There are removed fields that could directly reveal personal details and gave a unique identifier for each candidate.
    
    
* Data has been deleted from the repository because of privacy reasons

Files used in the repository 

jupyter notebook: analysis can be seen in the notebooks folder 
original data: has been deleted because of privacy reasons

Conclusion 

- For ranking candidates, we process 5 text similarities: euclidian, cosine, fuzzy, jaccard and levensthein. To get the fit column score, we make a mean of the mentioned metrics to get the final values. Each time a ranking is starred, the fit score increases marginally. For these cases, there are a lot of candidates with similar job titles and locations. It would be interesting to refit if there are unique values in the dataset, but it also  seems unrealistic that could happen.
    
    - A larger pool of candidates could also provide more insight on the variance of fit score. 
    
    - Bias can be decreased by adding more feature and increasing the size of the dataset.

Acknowledgement/References 

Thanks to Apziva for providing the data
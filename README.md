# Document Clustering For Cryptocurrency Info Document Set
This project implements document clustering with the EM (Expectation-Maximization) algorithm for a Cryptocurrency Information Document Set.

In this project, I have solved a document clustering problem for a data set that contains text from multiple documents sourced from the SCI Cryptocurrency community. I used two versions of the unsupervised learning algorithm, EM called Hard clustering and soft clustering. 

The following steps were followed to achieve the hard and soft clusters:

1. I derived the Expectation and Maximization steps of the hard-EM algorithm for Document Clustering. In particular, I included all model 
   parameters that should be learnt and the exact expression (using the same math convention that should be used to update these
   parameters during the learning process (ie., E step, M step and assignments).
2. I implemented the hard EM (derived above) and soft EM.
3. Next, I loaded the  document text file and necessary libraries, performed text processing operations, set the number of clusters K=6, 
   and ran the soft-EM and hard-EM algorithms on the provided data.
4. I performed PCA on the clusterings created based on the hard-EM and soft-EM. Then, I visualized
   the obtained clusters with different colours where the x and y axes are the first two principal components. Observe the differences 
   between the formation of the clusters generated from the hard and soft EM algorithms.


**Instructions for Use**: Please maintain the appropriate references and reusing guidelines as stated under the GNU General Public License 3.0 for reusing this code.

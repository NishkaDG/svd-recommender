# svd_recommender.
User-based recommender system with complete SVD implementation. Final Project for course Advanced Data Mining.
svd_compute calculates SVD of a mxn matrix in O(mn^2) time. 
Setting k (rank) to be much smaller than n reduces complexity to O(mnk) improves efficiency without affecting accuracy.
svd_recommend parses a csv file of recommendations (user IDs x Item ids) and uses svd_compute to return a list of recommended item IDs.

TODO: Add documentation.

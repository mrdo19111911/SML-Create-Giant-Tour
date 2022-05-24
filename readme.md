!pip install SMLGT

import GiantTour as gt

gt._help()

giant_tour_problem = gt.GT(DM,size_of_cluster =  6)

s = giant_tour_problem.create_giant_tour()

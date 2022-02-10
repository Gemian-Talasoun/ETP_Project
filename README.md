# ETP_Project

The electronic tour planner system (ETP) generates a plan for tourists who would like to
visit Luxor. The ETP is a mobile application and has three types of data, user data (favorite
list, forbidden list, preferences), trip data (start time, end time, budget) and places data
(name, open time, close time, preferences, minimum duration, minimum cost, description).
Most of these data classified into hard constraints such as (budget, trip start and end
times, …) and soft constraints such as (favorite list, preferences, …). ETP uses hard
constrains to generate candidate plans and use soft constrains to evaluate the generated
plans. The planner system is divided into three parts and each part sends his output data to
the next part: First part responsible for getting all data; Second part preparing data; Third
part responsible for getting the user’s plan. The ETP used the tabu search algorithm to
generate his plan and used (swap, insert, delete) operations to get the neighbors. Also, the
algorithm divides the plan into 2 parts morning and night parts to do his operations on each
part sequentially. And it divides all places into the morning, night, and full-time places
based on their working times, but difference between tabu and our algorithm use in ETP is
that after make 70 or more test in ETP the time required to get plan is that 3 scorned in
maximum. Also, the application provides more services like Ekko chatbot that used to
improve the user usability by helping him to use the application, The dashboard which is a
store of shared plans which used to allow more than one user use the same plan or
exchanging the opinions between users to get a better plan from an old shared plan, The
places' information which allows the user to know information about the places in the
system.

Keywords: Electronic tour planner (ETP), point of interests (POIs).

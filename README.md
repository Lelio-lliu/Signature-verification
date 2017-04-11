# Signature-verification
handwriting signature verification system
# Subject：Handwriting signature verification
# Data：4-11-2017
# Registrar：lliu

System Designing

Data Set Form:
Genuine and Forgery of different users
Forgeries in three type：
Random forgery ： forger have no information about user
Simple forgery ： forger have total or partial information about user's name
Skilled forgery ： forger have all information about user’s name and signature

Challenges：
1. High intra-class variability
Figure1：Superimposed example of multiple signature of the same user
As Figure1 shows the task have a high intra-class variability
2. Train system with partial knowledge 
In realistic scenario，we only have access to genuine signature for the users enrolled to the system
3. Numbers of train data is limited
It's difficult to get many data for training in real application

Method：
Clustering or classification （best result）
Matching（at first try）

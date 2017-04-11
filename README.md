# Signature-verification
handwriting signature verification system\n

Subject：Handwriting signature verification\n
Data：4-11-2017\n
Registrar：lliu\n

System Designing\n

Data Set Form:\n
Genuine and Forgery of different users\n
Forgeries in three type：\n
Random forgery ： forger have no information about user\n
Simple forgery ： forger have total or partial information about user's name\n
Skilled forgery ： forger have all information about user’s name and signature\n

Challenges：\n
1. High intra-class variability\n
Figure1：Superimposed example of multiple signature of the same user\n
As Figure1 shows the task have a high intra-class variability\n
2. Train system with partial knowledge \n
In realistic scenario，we only have access to genuine signature for the users enrolled to the system\n
3. Numbers of train data is limited\n
It's difficult to get many data for training in real application\n

Method：\n
Clustering or classification （best result）\n
Matching（at first try）\n

# EN #

## Must requirements ##
- The most common way to validate your identification in real world is to show the passport (ID card).
- THe most common way to provide anonymous vote is to give you a blank form without information about your id and provide a observable place where to store the response.
- The most common way to prove the election is honest is to follow specific protocol for results validation.
System should implement all 3 items above.


## Should requirements ##
New features that is not allowed by usual democratic vote can be implemented.
-  vote recall
-  anonymous statistic gathering (sex, age, wealth, region, etc)

## ID validation ##
System generates some random condition (salt) - to validate that photo is taken right now. E.g. how many fingers to show.
User takes one photo with him and his passport where random condition is satisfied.
System decodes user information from the photo and checks that it's not generarated or edited.
System validates picture on the passport and human face.
System stores decoded user information
System stores photo with some watermark, that can't be restored
System stores user encrypthed login.
Do not store the link between user ID and user login.
The first is used only to disallow duplicate and fake accounts.

# RU #
todo

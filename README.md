# adServer
Deployment Instruction
1. Unzip the project
2. Deploy the war in the server
3. Go to the url for creating new ads: <Host>/adServer/homePage
4. To get all the ads:  <Host>/adServer/ad/getAllAds
5. To get a ad based on partner id : <Host>/adServer/ad/{partner_id}

Application consists Of
1. Creating new ads
2. Getting ads based on partner id
3. Getting all the ads(Bonus Question)
4. Getting and Storing multiple ads for partner id(Bonus)
5. JUnits
6. Error Handling

Advantages & Disadvantages of Persistance mechanism(Bonus)
Advantages:
All the ads are stored as key value pairs, where the key is the partner id and value is list of ads
Easy to retrive, add new ads and add ads to existing partner id
Disadvantages:
Not thread safe
Once the application is restared all the data is deleted



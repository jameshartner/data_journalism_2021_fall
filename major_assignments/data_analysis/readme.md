# Data analysis project

This folder is for data analysis project materials

# First Memo (Deliverable Three)
To this point, we’ve been working through all the datasets we’ve been provided, trying to clean through them and find notable PPP loans to senators’ companies/assets. We’re aiming to clean and standardize the names of companies/assets in the datasets so that we can join those datasets to the main PPP loan dataset. From there, we can look through the PPP loans connected to senators and see if any loans stick out for any reason. 

So far, we’ve been able to pull out one particularly interesting loan connected to Idaho Sen. Mike Crapo. Using the PPP loan dataset, the dataset listing senators’ assets, and online research. There was a loan of around $2,000 provided to Crapo Estate Holdings, LLC in Utah. Notably, the address of this company (as listed on the PPP dataset) is actually a residential address, and Mike Crapo’s wife, Susan Crapo, was listed online as being linked to this address. We couldn’t find any firm evidence of anything wrong in this case, and the loan amount was relatively small, but it still raised questions as to the purpose of this loan. 

Moving forward, we’re looking to expand the scope of our search. To this point, we focused on businesses described as LLCs, but we’re planning on identifying businesses under other descriptions, as well. For now though, we’re trying to find the best way to clean the names of the businesses so that we can easily join the datasets together. 


# Second Memo (Deliverable Four)
Initial pitch: The ties between politicians and their interests in private business practices will always be a pertinent aspect of the private lives of those that run the United States government. But it’s an aspect that doesn’t get talked about as often as its implications would warrant. 

The Small Business Administration’s Paycheck Protection Program, put in place in the early days of the COVID-19 pandemic, gave an extended glimpse into the business practices and monetary allocations of those politicians. Reporting on the PPP requests of the everyday American is fairly commonplace; pulling the numbers tied to congresspeople is far more interesting to the American public. 

Our findings opened the door to exactly that. We were able to locate certain representatives and their activity within the PPP program, as well as what they were tied into regarding assets and other LLC partnerships. This data goes beyond your standard search into party donations or investments and shows more personal activity.

Specific summary of results: So far, we have found three considerable results with one senator having an exact match! Our first exact match of the senator's data and the PPP data was Cindy Hyde-Smith and a farm called Mathis Farm, INC. Some possible matches were Rick Scott matching with AJ 3 LLC to AJ LLC (from PPP) and Mike Crapo joining with Crapo Enterprises. Further investigation is needed. 

Pros and Cons: Our datasets consisted of PPP listings from the SBA and senator-specific listings which outlined more targeted behavior on behalf of representatives. While the data was incredibly detailed, these datasets were also very dense, creating difficulty when it came time to fuzzy join sets together or clean/filter through them. A lot of the data was split between multiple different datasets as well (the PPP data was split among 13 different large files), which made cleaning an issue as well. Of course, working with such expansive and detailed data was a plus in terms of making concrete findings, and lends itself to further use going forward. We simply do not have machines powerful enough to efficiently run through this many variables. 

Verify/bringing home: Verification would likely require more detailed research on the companies we found to be tied to representatives. In addition, to continue this story, visiting the locations of these businesses and reaching out to not just those employed/tied to them, but also the representatives themselves would bring much more clarity to this project as a whole. (name specific reps/places)

# Final Memo (Deliverable Five)
Initial pitch: 

The ties between politicians and their interests in private business practices will always be a pertinent aspect of the private lives of those that run the United States government. But it’s an aspect that doesn’t get talked about as often as its implications would warrant. 

Summary:

The Small Business Administration’s Paycheck Protection Program, put in place in the early days of the COVID-19 pandemic, gave an extended glimpse into the business practices and monetary allocations of those politicians. Reporting on the PPP requests of the everyday American is fairly commonplace; pulling the numbers tied to congresspeople is far more interesting to the American public. 

Our findings opened the door to exactly that. We were able to locate certain representatives and their activity within the PPP program, as well as what they were tied into regarding assets and other LLC partnerships. This data goes beyond your standard search into party donations or investments and shows more personal activity.

We found multiple senators that stood out with somewhat intriguing records, but a few of those records stood out among the rest. For example, Republican South Dakota Senator Mike Rounds’ PPP ties with BirdDog Hospitality raise serious questions. 14 rows came back to BirdDog after a final cleanup, with the matching of the PPP loan address and the BirdDog Hospitality. Also, each row for BirdDog had the exact same forgiveness amount, but different names. It would be interesting to look into that more. 
Our dive into the data point to Rounds pulling PPP requests from a ‘Bird Dog Hospitality Fund’ multiple times, with different funds pulled from different funds under the same name numbered one through five as well. BirdDog is listed as a hospitality and private equity firm based in Sioux Falls, South Dakota, and has received serious attention from Rounds in recent years. 
Rounds’ assets didn’t stop appearing in the PPP data though. Locals Love Us, LLC, is another affiliate with the senator. 

Pastor and Georgia democratic senator Raphael Warnock is also included in our findings. Warnock was tied to multiple PPP requests for Ebenezer Baptist Church, the Atlanta church at which Warnock is a pastor. While the PPP applications were not made in the same frequency as the ones tied to Rounds, they still warrant an inquiry. 

Warnock’s name also tied back to three other assets that were seen in the PPP data. Those assets were New Georgia Baptist Church, Inc. and Martin Luther King Sr. Community Resources Collaborator  were definite matches, whereas Georgia Interfaith Public Policy Center, INC. still needs review. 

The same can be said for other senators as well, like William F. Hagerty of Tennessee with his company of Eakin Partners, or Ron I Wyden of Oregon with his company Strand Book Stores Inc. Wyden’s and Hagerty’s both took out two different loans for their respective companies. 

Pros and Cons: 

Our datasets consisted of PPP listings from the SBA and senator-specific listings which outlined more targeted behavior on behalf of representatives. While the data was incredibly detailed, these datasets were also very dense, creating difficulty when it came time to fuzzy join sets together or clean/filter through them. A lot of the data was split between multiple different datasets as well (the PPP data was split among 13 different large files), which made cleaning an issue as well. Of course, working with such expansive and detailed data was a plus in terms of making concrete findings, and lends itself to further use going forward. We simply do not have machines powerful enough to efficiently run through this many variables, which resulted in us having to whittle our scope down more and more as the project progresses.

On the flip side, the depth of the data allowed us to truly cover the entire scope of the country. Had we chosen to look at PPP loans in terms of every person across the country, we would have been able to (this, however, would have taken considerably longer and required even more powerful machines). The scope of this data is boundless; we could have explored any avenue within small business behavior in the U.S., looking for a myriad of different trends or pursuing any sort of lead we received. The data was particularly useful for looking into the financial movements of politicians. As previously mentioned, the depth of this information was more than enough for us to uncover some interesting trends.

Verification/ Conclusion:

Verification would likely require more detailed research on the companies we found to be tied to representatives. Looking into the histories of these companies, their ties to the senator involved, and their monetary behavior are all avenues we could pursue in working towards a story. In addition, to continue this story, visiting the locations of these businesses and reaching out to not just those employed/tied to them, but also the representatives themselves would bring much more clarity to this project as a whole. While getting a response from a senator that knows they have been involved in some sort of behavior that takes advantage of the PPP loan system would be unlikely (spare for a statement from a spokesperson), looking into this trend would surely yield important results. Going and asking questions at Ebenezer Baptist Church in Atlanta, for example, would provide clarity. Speaking to those tied to Bird Dog’s business interests, whether that be on the equity or hospitality holdings side, would prove to be fruitful as well. 




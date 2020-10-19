# postmint

Inspiration
Globally, small businesses are facing an unprecedented economic disruption due to the COVID-19 epidemic. Strict safety protocols haven't been enough to persuade customers to come through the door for many small businesses, and inventory and overhead costs have been especially tough to deal with considering the inability to connect to new customers. We wanted to help out small business owners during this time.

What it does
In a nutshell, Post Mint transforms small businesses into large brands. Our project is a platform that small business owners that have a social media presence can use to post images periodically to their web pages. Our project currently allows users to log in with Instagram accounts, and then they can upload various product images to our site and select how often they want to post. Then, we use a machine learning API to associate the images to product names. After that, we get scrape trend information for all of the products, and we normalize the data and choose the product with the highest z-score for that day compared to the set of trend data over the last 5 years. When a post is supposed to be posted, we find the product that has the highest relative interest for the day, and then we generate a comment and hashtags automatically, and post to the user's page instantly.

How I built it
We used flask and python for the backend implementation, and we used html, css, and javascript for the front end. We accessed Google's trend information, and we also used Google's Cloud Vision API to recognize various product images to tell what they are without asking the user to input text information. Along with this, we made an instagram api that would then post those images.

Challenges I ran into
During the hackathon, we ran into issues such as many frustrating bugs and problems connecting elements written in various languages together. Also, we encountered problems making an api from scratch which can post images to instagram. But at end, all of us ,despite our differences in age and time zones, pulled through and created Post Mint.

Accomplishments that I'm proud of
We are proud of the fact that we ended up with a working product that was able to do what we set out to do! Also, we feel really accomplished, that we could get data from google trends, make graphs using it and use it as the brain behind our project. We all learned new technologies and are happy to create something that can help small businesses in the time of this crisis.

What I learned
Along the way, we learned a bunch of skills. We honed our front end design skills, we learned how to host websites on cloud servers, and we learned how to access new APIs.

What's next for Postmint
The next step for Postmint would be to expand the number of platforms that small businesses can connect to. Currently we have only set up an implementation that allows for users to post on Instagram. In the future, adding additional social media platforms such as Twitter and Facebook would help improve functionality and allow us to reach a wider audience of small businesses that may not use instagram.

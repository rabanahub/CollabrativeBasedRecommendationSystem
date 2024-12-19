Collaborative filtering recommender systems have played a significant role in the rise of web services and content platforms like Amazon, Netflix, YouTube, etc. in recent years. In this age of information, knowing what the customer wants before they even know it themselves is nothing short of a superpower. As the name suggests, recommender system algorithms are used to offer relevant content or product to the consumer based on their taste or previous choices. In this article, we will look at how a particular type of recommender system works: collaborative recommender system.


![image](https://github.com/user-attachments/assets/40a71501-d6ac-4963-8821-a82ea972b22e)
Two kinds of collaborative filtering techniques used are:

There are two general types of collaborative filtering:

User to user
Item to item
User to user collaborative filtering basically operates under the assumption that users who gave similar ratings to a certain item are likely to have the same preference for other items as well. Therefore this method mainly relies on finding similarity between users. However, in some cases, user preference might be to abstract to be broken down. This is where item to item collaborative filtering comes in handy. Here, similarity between items is used instead of similarity between users. In this article, we’ll be focusing on user to user collaborative filtering.

Workflow of collaborative filtering:

![image](https://github.com/user-attachments/assets/d9626993-9061-4e3d-ada5-7894b283379e)



User to user collaborative filtering
The process starts by converting the rating data into a utility matrix where the list of users are the rows and list of items are the columns.
The next step is the Neighborhood collaborative filtering model where we use a similarity function to compute similarity between users with the output being a similarity matrix.
A certain amount (K) of similar users (also known as neighbors) is taken and the rating prediction will be obtained by doing regression on these neighbors’ rating data.
The items will then be sorted based on the highest rating and the top items will be recommended to the user.

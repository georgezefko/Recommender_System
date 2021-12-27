

# Data analysis and implementation of recommender systems for Olist a brazilian retailer.


E-commerce has recorded significant growth during the last decade following the rapid evolution of technology. Today, e-commerce businesses are using technology and data in many different areas to stay ahead of the competition. In this context we have chosen 3 main Key Performance Indicators (KPIs) which can help Olist (Brazilian e-commerce) to boost its business such as increasing the monthly sales, increasing the average order size, and increasing the customer lifetime value. Therefore, to achieve the first KPI, we aim to develop a recom- mendation system which can boost the sales of Olist. Additionally, we try to help them to better understand their product-order network as well as their customers’ satisfaction to achieve second and third KPIs respectively.
Inspired by online e-commerce websites like Amazon which use different recommen- dation systems to provide different suggestions to different users, we built several systems for the same purpose for Olist. 10 recommendation systems were built using collaborative filtering which utilizes the purchased products, the customers, and the review scores. At a high level, this type of filtering matches each of the user’s purchased and rated items to similar items, then combines those similar items into a recommendation list for the user. By considering the ac- curacy of those 10 models, finally 3 of them were selected as the best models. Even though we tried to create a recommendation model using content-based filtering approach, due to the limited information regarding the contents of the products the results cannot be taken as satis- factory. Therefore as a further study content based filering would be a good approach if Olist can provide more details on contents of the products. Furthermore, as part of the recommen- dation system, we applied artificial neural networks to evaluate whether such a more advanced technique can lead to a better outcome. The results of the study revealed that for Olist the deep learning models provided may be successfully used for customer-product recommendation, as they outperform the best traditional model developed as a part of this project. To provide a more general tool, a model was developed to predict the average ratings of product categories for each state, but due to its low performance, the customer-product models cannot be aided by it.
The second part of the study aims to analyze the reviews that the customers have given to a few of the products that they have purchased. The analysis was divided into two sections. For the first section, a topic analysis was carried out where we classified the text of the reviewers’ comments and reviews’ title in 5 different topics. The outcome of this analysis, in accordance to the wordcloud (visual representation of words) is that most of Olist’s customers are satisfied. The topic analysis revealed that the most common reviews mainly refer to delivery time and how the product delivered. Therefore, it is recommended to focus more on maintaining efficient delivery service to enhance customer satisfaction. In the second section we performed sentiment analysis, a method to detect whether a review was positive or negative and identified that majority of the customers were satisfied with the service offered by Olist.
Lastly, to get better understanding about the connections between the orders and the products available on Olist, network analysis was performed. The network consisted of nodes that represented the products and edges (links) that connected some products. The products that were connected were included in the same order. The node that represents products that were included in the order with the largest amount of other products has the biggest size in the network. By analyzing the network, we have seen that the average number of products in an order is less than 10 for the 80% of the orders. So by identifying the average order size, Olist can predict its sales and can target more on customers through recommendation systems to increase the average order size.

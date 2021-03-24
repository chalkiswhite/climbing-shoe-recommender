# climbing-shoe-recommender

# A Recommender System for climbing shoes
(Based on the Taxonomy Concept from John Riel and Joseph A. Konstan, *'Word of Mouse: The Marketing Power of Collaborative Filtering', Business Plus, 2002*)


## 1. Domain:

Climbing

## 2. Target

Provider  | Customer
------------ | -------------
Help Customers with the buy decision | Get better orientation when buying climbing shoes
Less returns | Less wrong buy decisions
Sell more | Make better decisions when buying 
| |More fun at climbing

## 3. Context

Need to buy new climbing shoes:

* Someone new to the sport:
  * unexperienced: never bought climbing shoes before
  * first steps in climbing: searching a more comfortable shoe to start the journey
  * spending his time mainly with one climbing style

* Someone experienced:
  * has had more than one pair of shoes before
  * knows popular manufacturers 
  * (follows different pro climber on social media)
  * knows exactly his/her use case (bouldering, climbing, ...)
  * searching for specific type of shoes (asymmetric, aggressive, performance, endurance/comfort... ) 

Sources of information:
  * Online Research
  * Climbing Magazines
  * Retailer


## 4. Grade of Personalization:
Not-Personalized            | Semi-Personalized | Personalized
------------                | ------------- | ------------ | 
Top 5 Climbing shoes        | Best shoes for climbing style | Individual recommendations based on user features
Most selled shoes           | Best shoes for beginners
Best rated shoes            | Best shoes for specific foot shape
Climbing shoes of the month | | 


## 5. 'Who's opinion':

Experts  | Customers
------------ | -------------
Much knowledge | Opinion of the mass
More experience | Homogenous group of different people
Could be professional | broad range from beginner to expert


## 6. Security / Trust:
### Security
Data can be stored anonymously, secured and private

### Trust
Organic Presentation: Hosting an indipendent recommendation site without any selling purpose

Non-organic presentation: Implementing recommender system into e-shop to boost selling


## 7. Interface:

Input  | Output
------------ | -------------
Street shoe size | Top X shoe recommendation
Footsize (len, width) | optimal shoe size
Footshape (egypt, greek,..)
Height
Weight
Gender
Use-Case
Past climbshoe

### Model choice (model accuracy-model interpretaion trade-off)

White-Box: 

Black-Box:


## 8. Algorithms:

Collaborative Filtering  | Content-based Filtering | Hybrid Recommender
------------ | ------------- | -------------


# Ideas

## Implicit Ratings

### Weighting

Possible weighted rating calculations:

weight  | feature | value
------------ | ------------- | -------------
w1 | experience | 100
w2 | using_frequency | 50
w3 | climbing_grade | 15

IR = (w1 x experience) + (w2 x using_frequency) + (w3 x climbing_grade)



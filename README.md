# Market-Basket-Analysis
#### Market basket analysis is used to identify items that are frequently purchased together. This technique uncovers hidden correlations that cannot be identified by the human eye by using a set of statistical rules to identify product combinations that occur frequently in transactions.
#
## Algorithm Used:
#### Aprior Algorithm: used for association rule mining.
#
## Components of Aprior algorithm:
#### 1.) Support = freq(x,y)/N
#### 2.) Confidence = freq(x,y)/freq(x)
#### 3.) Lift = conf(x,y)/supprt(x)
#
## Result:
##### The higher the lift value, the higher the association between the items will be. If the lift value is more than 1, it is enough for us to say that those two items are associated with each other.
#### From the Aprior algorithm table, it is clear that the following are the three most popular combination of products that are frequently brought together.
#### 1.) WOODEN PICTURE FRAME WHITE FINISH and WOODEN FRAME ANTIQUE WHITE
#### 2.) SWEETHEART CERAMIC TRINKET BOX and STRAWBERRY CERAMIC TRINKET BOX
#### 3.) RED HANGING HEART T-LIGHT HOLDER and WHITE HANGING HEART T-LIGHT HOLDER
#### Beside that, we could also see the support value of RED HANGING HEART T-LIGHT HOLDER and WHITE HANGING HEART T-LIGHT HOLDER are 0.0391% which means there are 3.91% out of total transaction that these 2 items were sold together.
#### The confidence value of SWEETHEART CERAMIC TRINKET BOX and WOODEN FRAME ANTIQUE WHITE. It means that a customer will tend to bring Wooden Frame Antique White after they bought Sweetheart ceramic trinket box.

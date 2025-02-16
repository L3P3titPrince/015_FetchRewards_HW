#Main Diagram
Generated using [DbSchema](https://dbschema.com)




### Main Diagram
![img](./MainDiagram.svg)



### Collection test_1.receipts_raw 
|Idx |Name |Data Type |
|---|---|---|
| * &#128273;  | \_id| objectId  |
|  | bonusPointsEarned| int  |
|  | bonusPointsEarnedReason| string  |
| * | createDate| date  |
| * | dateScanned| date  |
| * | modifyDate| date  |
|  | pointsAwardedDate| date  |
|  | pointsEarned| string  |
|  | purchaseDate| date  |
|  | purchasedItemCount| int  |
|  | rewardsReceiptItemList| array[object]  |
|  | rewardsReceiptItemList.barcode| string  |
|  | rewardsReceiptItemList.competitiveProduct| Boolean  |
|  | rewardsReceiptItemList.finalPrice| string  |
|  | rewardsReceiptItemList.itemPrice| string  |
| * | rewardsReceiptItemList.partnerItemId| string  |
|  | rewardsReceiptItemList.quantityPurchased| int  |
|  | rewardsReceiptItemList.rewardsGroup| string  |
|  | rewardsReceiptItemList.rewardsProductPartnerId| string  |
|  | rewardsReceiptItemList.needsFetchReview| Boolean  |
|  | rewardsReceiptItemList.needsFetchReviewReason| string  |
|  | rewardsReceiptItemList.preventTargetGapPoints| Boolean  |
|  | rewardsReceiptItemList.userFlaggedBarcode| string  |
|  | rewardsReceiptItemList.userFlaggedDescription| string  |
|  | rewardsReceiptItemList.userFlaggedNewItem| Boolean  |
|  | rewardsReceiptItemList.userFlaggedPrice| string  |
|  | rewardsReceiptItemList.userFlaggedQuantity| int  |
|  | rewardsReceiptItemList.originalFinalPrice| string  |
|  | rewardsReceiptItemList.originalMetaBriteBarcode| string  |
|  | rewardsReceiptItemList.originalMetaBriteItemPrice| string  |
|  | rewardsReceiptItemList.originalMetaBriteQuantityPurchased| int  |
|  | rewardsReceiptItemList.description| string  |
|  | rewardsReceiptItemList.originalMetaBriteDescription| string  |
|  | rewardsReceiptItemList.pointsEarned| string  |
|  | rewardsReceiptItemList.pointsPayerId| string  |
|  | rewardsReceiptItemList.targetPrice| string  |
|  | rewardsReceiptItemList.discountedItemPrice| string  |
|  | rewardsReceiptItemList.itemNumber| string  |
|  | rewardsReceiptItemList.pointsNotAwardedReason| string  |
|  | rewardsReceiptItemList.brandCode| string  |
|  | rewardsReceiptItemList.competitorRewardsGroup| string  |
|  | rewardsReceiptItemList.originalReceiptItemText| string  |
|  | rewardsReceiptItemList.deleted| Boolean  |
|  | rewardsReceiptItemList.priceAfterCoupon| string  |
| * | rewardsReceiptStatus| string  |
|  | totalSpent| string  |
| * | userId| string  |
|  | finishedDate| date  |


##### Indexes 
|Type |Name |On |
|---|---|---|
| &#128273;  | \_id\_ | ON \_id|





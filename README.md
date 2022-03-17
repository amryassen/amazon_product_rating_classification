# amazon_product_rating_classification
Simply this project aims to predict the product grade from {A , B , C , D}.<br />
Our CSV file has alot of features needs to be processed, then doing a features selection process, and finally our best model after alot of Attempts.<br />
 
 ### Preprocessing techniques Used:
  . dropping rows which has null values.<br />
  . some columns i fill it by zero or by the mean, it depends on the logic and the dataset itself<br />
  . feature scaling<br />
  . label encoder for strings<br />
  . regex strings for findings specific parameters in cells<br />
 
### Classification Models Used:
 . Polynomial SVM with Kernal<br />
 
<h2 align = "left">Data Variables</h2>
* uniq_id
* product_name
* manufacturer
* price
* number_available_in_stock
* number_of_reviews
* number_of_answered_questions
* amazon_category_and_sub_category
* sellers
* product_information
* ProductGrade
The test set contains all the above variables except for average_review_rating, which is to be predicted.

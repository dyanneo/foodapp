# foodapp API 

## UPC and Food lookup API - nutritionix.com

* https://developer.nutritionix.com/admin/access_details
* My Application ID: df3ca64d
* My API Key: 083716a7769e2af692768f900f514838
* Logged in w/Git

### Example API call w UPC #:  
https://api.nutritionix.com/v1_1/item?upc=49000036756&appId=df3ca64d&appKey=083716a7769e2af692768f900f514838

### Example API call w food name (cheddar cheese):  
https://api.nutritionix.com/v1_1/search/cheddar%20cheese?fields=item_name%2Citem_id%2Cbrand_name%2Cnf_calories%2Cnf_total_fat&appId=df3ca64d&appKey=083716a7769e2af692768f900f514838

### Example API call w food name (gouda cheese):  
https://api.nutritionix.com/v1_1/search/gouda%20cheese?fields=item_name%2Citem_id%2Cbrand_name%2Cnf_calories%2Cnf_total_fat&appId=df3ca64d&appKey=083716a7769e2af692768f900f514838

### Example API call w food name (gouda cheese) - Response: 
{
"total_hits": 42430,
"max_score": 12.743745,
"hits": [
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "513fceb375b8dbbc21000049",
"_score": 12.743745,
"fields": {
"item_id": "513fceb375b8dbbc21000049",
"item_name": "Cheese, gouda - 1 oz",
"brand_name": "USDA",
"nf_calories": 100.93,
"nf_total_fat": 7.78,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "583323ec6ced7f904c966cf8",
"_score": 12.496248,
"fields": {
"item_id": "583323ec6ced7f904c966cf8",
"item_name": "Cheese, gouda - 1 cup, shredded",
"brand_name": "USDA",
"nf_calories": 384.5,
"nf_total_fat": 29.64,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "513fceb375b8dbbc21000048",
"_score": 12.426779,
"fields": {
"item_id": "513fceb375b8dbbc21000048",
"item_name": "Cheese, gouda - 1 package (7 oz)",
"brand_name": "USDA",
"nf_calories": 704.88,
"nf_total_fat": 54.33,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "54db80afc643db754d5f124a",
"_score": 4.0596356,
"fields": {
"item_id": "54db80afc643db754d5f124a",
"item_name": "Gouda",
"brand_name": "The Good Life Cheese",
"nf_calories": 90,
"nf_total_fat": 7,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "54fd67352d725a326c78442f",
"_score": 2.7395132,
"fields": {
"item_id": "54fd67352d725a326c78442f",
"item_name": "Gouda Cheese",
"brand_name": "Moon Cheese",
"nf_calories": 70,
"nf_total_fat": 5,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "51c54c2d97c3e6efadd61460",
"_score": 2.466355,
"fields": {
"item_id": "51c54c2d97c3e6efadd61460",
"item_name": "Cheese, Gouda",
"brand_name": "Borden",
"nf_calories": 65,
"nf_total_fat": 5,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "51c3c27597c3e6d8d3b49f33",
"_score": 2.466355,
"fields": {
"item_id": "51c3c27597c3e6d8d3b49f33",
"item_name": "Cheese, Gouda",
"brand_name": "Holland Farm",
"nf_calories": 110,
"nf_total_fat": 9,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "529e7debf9655f6d350029ca",
"_score": 2.466355,
"fields": {
"item_id": "529e7debf9655f6d350029ca",
"item_name": "Gouda Cheese",
"brand_name": "Newk's Eatery",
"nf_calories": 35,
"nf_total_fat": 4,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "56bbe3c37263b5f507c1bc31",
"_score": 2.466355,
"fields": {
"item_id": "56bbe3c37263b5f507c1bc31",
"item_name": "Gouda Cheese",
"brand_name": "Dutch Garden",
"nf_calories": 110,
"nf_total_fat": 9,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
},
{
"_index": "f762ef22-e660-434f-9071-a10ea6691c27",
"_type": "item",
"_id": "51c3f3cf97c3e6de73cbde8c",
"_score": 2.466355,
"fields": {
"item_id": "51c3f3cf97c3e6de73cbde8c",
"item_name": "Cheese, Gouda",
"brand_name": "Frico",
"nf_calories": 120,
"nf_total_fat": 10,
"nf_serving_size_qty": 1,
"nf_serving_size_unit": "serving"
}
}
]
}

# steps taken
## browser
* Added JSON viewer browser extension to chrome  

## aws
* logged in as my amazon account
* created dybox1
* added security group for http/ssh in; all out
* installed git:  `sudo yum install git`  
* downloaded key

## putty
* created putty profile dybox1
* used puttygen.exe to convert dybox1.pem to dybox1.ppk and added to profile dybox1



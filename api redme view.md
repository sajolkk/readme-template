Quotation Route API

- [X]
## New quotation request store api
### POST Method
  
http://solverapps.solverbd.com/api/v4/quotation-request-store
 
### Data insert in quotation master table	
|Column			| Data Type		| Required 	|
| --------- 	| --------- 	| ------- 	|
|customer_id	| integer 		|- [x] Yes |
|total_amount	| float/double 	|- [x] Yes |
|discount		| float/double 	|- [x] Yes |
|vat			| float/double 	|- [x] Yes |
|vat_amount		| float/double 	|- [x] Yes |
|vat_type		| var/string 	|- [x] Yes |
|grand_amount	| float/double 	|- [x] Yes |
|payment_option	| integer 		|- [x] Yes |
|delivery_option| integer 		|- [x] Yes |
|qut_format		| var/string 	|- [x] Yes |
|format_qty		| var/string 	|- [x] Yes |
|qut_type		| var/string 	|- [x] Yes |
  

## Data insert in quotation details table
Note: Product sent with list;
  
List Name: "product_list"
  
| Column		| Data Type 	| Required	|
| ----------- 	| --------- 	| --------	|
| product_id 	| var/string 	| - [x]		|
| unit_price 	| float/double 	| - [x]		|
| warranty 		| var/string 	| - [x]		|
| qty 			| integer 		| - [x]		|
| total_price 	| float/double 	| - [x]		|

  
## Quotation request update api
### POST Method
http://solverapps.solverbd.com/api/v4/quotation-request-update
  
### Data insert in quotation master table	
|Column			| Data Type		| Required 	|
| --------- 	| --------- 	| ------- 	|
|customer_id	| integer 		| - [x] Yes |
|total_amount	| float/double 	| - [x] Yes |
|discount		| float/double 	| - [x] Yes |
|vat			| float/double 	| - [x] Yes |
|vat_amount		| float/double 	| - [x] Yes |
|vat_type		| var/string 	| - [x] Yes |
|grand_amount	| float/double 	| - [x] Yes |
|payment_option	| integer 		| - [x] Yes |
|delivery_option| integer 		| - [x] Yes |
|qut_format		| var/string 	| - [x] Yes |
|format_qty		| var/string 	| - [x] Yes |
|qut_type		| var/string 	| - [x] Yes |
  

## Data insert in quotation details table
Note: product sent with list;
  
List Name: "product_list"
  
| Column		| Data Type 	| Required	|
| ----------- 	| --------- 	| --------	|
| product_id 	| var/string 	| - [x]		|
| unit_price 	| float/double 	| - [x]		|
| warranty 		| var/string 	| - [x]		|
| qty 			| integer 		| - [x]		|
| total_price 	| float/double 	| - [x]		|


## Quotation request report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-report/from_date/to_date

  
## Quotation request detail/view api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-details/request_id


## Quotation request delete api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-delete/request_id


## Quotation request employee wise report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-employee-report/emp_id/from_date/to_date



## Quotation request pending report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-pending-report/from_date/to_date




## Quotation request working report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-working-report/from_date/to_date



## Quotation request completed report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-completed-report/from_date/to_date


## Quotation request employee wise pending report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-pending-employee-report/emp_id/from_date/to_date


## Quotation request employee wise working report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-working-employee-report/emp_id/from_date/to_date


## Quotation request employee wise completed report api
### GET Method
http://solverapps.solverbd.com/api/v4/quotation-request-completed-employee-report/emp_id/from_date/to_date


  



## Open a case with keys

#### HTTP Request

`POST http://api.vgo.gg/ICase/OpenWIthKeys/v1`

#### Authorization

Requires API Key authentication.

#### Input

Parameter | Type | Required   | Description
--------- | -----| :--------: | -----------
case_id | int | + | The ID of the case being opened
amount  | int | - | Number of cases to open.  Defaults to 1.  Maximum value of 100.
    
#### Output

Parameter | Type | Description
--------- | -----| -------- 
cases | array | Containing OpenedCase objects


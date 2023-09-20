[![License](https://img.shields.io/github/license/petro-logistics/petro-api-power-bi.svg)](LICENSE)

# Petro API Power BI
This module is a Power BI API client (with an example) for retrieving data with the [Petro-Logistics API](https://secure.petro-logistics.com/client/api).

## Dependencies
- [Power BI Desktop](https://www.microsoft.com/store/productid/9NTXR16HNW1T?ocid=pdpshare)

## Running the example:
1. Install [Power BI Desktop](https://www.microsoft.com/store/productid/9NTXR16HNW1T?ocid=pdpshare)
2. Download and open the file [test_example.pbix](examples/test_example.pbix?raw=1)
3. Refresh data result of query `PLTestQuery`
4. You can see an example of result data in a table

## Using your credentials and Parameters
1. Install [Power BI Desktop](https://www.microsoft.com/store/productid/9NTXR16HNW1T?ocid=pdpshare)
2. Download and open the file [test_example.pbix](examples/test_example.pbix?raw=1)
3. Right click on `PLTestQuery` query and select `Edit query`
4. You can see a list of parameters, here you can put your credential and parameters:
    - **api_url_endpoint:** Selector field to select one of the API endpoint (movementsdata, movdata, ...)
    - **api_key:** Text field to insert user API key
    - **api_hash:** Text field to insert user API hash
    - **http_user:** Text field to insert user HTTP username
    - **http_pass:** Text field to insert user HTTP password
    - **query_name:** Text field to insert desired query name
5. You can now save and apply your changes closing query editor
6. Refresh data result of modified query `PLTestQuery`
7. You can see the result data of your request query in a table

### Short Tuto Video
![](docs/assets/test_example_tutorial.mp4)
[Download video here](docs/assets/test_example_tutorial.mp4?raw=1)
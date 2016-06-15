This Walmart2016 repository provides the solution to the Walmart assignment.
The src folder consists of various packages like com.walmart.labs.api.controller, com.walmart.labs.api.model, com.walmart.labs.api.search and com.walmart.labs.api.util.
The controller folder (src->com->walmart->labs->api->controller) has the process.java file. It pules the search entered by the user and then displays the either the productView.jsp or the error.jsp depending on what was processed.
The model folder (src->com->walmart->labs->api->model) has the product.java file which represents the data.
The serach folder (src->com->walmart->labs->api->serch) has the ReviewSearchImpl.java and the SearchService.java file. ReviewSearchImpl implements the SearchService.                                                                                                          The getRecommendedProducts is a processor that will take thecustomer query and process the internal walmart API calls and perform the following tasks,                                                                                                                                         * 1.Searching for products based upon a user-provided search string                                                                   	  * 2.Take the first item in the search response as input for the product recommendation search                                           * 3.Retrieve reviews of the first 10 product recommendations                                                                             * 4.Rank order the recommended products based upon the review sentiments                                                 The getUserProductItemId is a utility method that will take the query and return the possible item id. The steps that are performed include,                                                                                                                                                 * 1.Searching for products based upon a user-provided search string                                                                      * 2.Taking the first item in the search response as input for a product recommendation search
The util folder (src->com->walmart->labs->api->util) has the JsonUtil.java file contains code that establishes connection with Walmart Open API.
The Resource folder has the properties file. The properties file includes my API Key used to access the Walmart Open API.
The test folder houses the com.walmart.labs.api.test package. This package is comprised of various files like demo.java, JsonUtilTest.java, ReviewSearchTest.java and TestRunner.java that are used for testing the code that I developed.
The WEB-INF folder inside WebContent has the index.html, productView.jsp and error.jsp pages.
"# Walmart"

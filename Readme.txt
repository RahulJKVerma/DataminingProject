Instructions -

*************************************************************************

Yelp Web scrapping iPython notebook -


1) Kindly enter you Yelp username and password in the YelpLogin function defined in the code. This information is needed to login to Yelp search page and search for user profiles.

2) Please run all the cells above 'main' function. Once all the functions are loaded into the namespace, please run the main function

3) I have provided random time buffers between scrapping attempts, but this number I believe is dynamic and depends upon the traffic on the cdn server. There might be scenarios where you will come across '500 error' in which case we can individually call the PassScrubbedRevRecords(ReviewTupList) and proceed.

4) Due to the buffer time, it takes considerable time to scrape decent size of records. As the code uses selenium to click on drop downs and selection user locations, if we minimize the selenium chrome driver run window to work on other browsers, there are times when the dropdown element vainshes from the DOM due to our inadvertent clicking on some other page. When this happens, a 'dropdown element not found' error is displayed. Ideally, this error should be caught and the code run again but due to time constraints, I was not able to incorporate error handling as well. In case this error appears, please call the PassScrubbedRevRecords(ReviewTupList) in order to proceed.

***************************************************************************

Data mining project iPython notebook

1) Please use the below dropbox link to access the data

https://www.dropbox.com/sh/6jaew9c4jkhoszu/AABHRoOPNtboukkSokNSGGYSa

2) Please place the json files in the same folder as code.

3) You can run the entire code together for getting the final results.

***************************************************************************

Please feel free to get in touch me if you need any clarifications or in case of any issues.

Thank you.




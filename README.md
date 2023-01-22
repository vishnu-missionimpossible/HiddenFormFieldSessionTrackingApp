# HiddenFormFieldSessionTrackingApp

1. In case of Hidden Form Field a hidden (invisible) textfield is used for maintaining the state of an user. In such case, we store the information in the hidden field and get it from another servlet. This approach is better if we have to submit form in all the pages and we don't want to depend on the browser.
2. In this App, firstly we have collected sid, sname, saddr and then in the first servlet, using the print writer object we make this fileds and hidden. and we will ask for sage and after that we will link to second servlet
3. In the second servlet, we will collect the information from request object and make them as hidden along with the previous fileds.
4. In the third servlet, we will display the result. 

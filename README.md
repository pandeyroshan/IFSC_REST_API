IFSC_REST_API

This API runs on Python 3.6. Make sure you have Python 3.6 and pip installed.

Production URL The API is hosted on Heroku:

http://bank1api.pythonanywhere.com/api/banks/
URLs and Features The API has 2 features:

Get all the banks

 URL: http://bank1api.pythonanywhere.com/api/banks/
This will return a paginated JSON Data of Banks all over India.

Get Bank details using IFSC Code

 URL: http://bank1api.pythonanywhere.com/api/banks/<IFSC Code>/
 
 example: http://bank1api.pythonanywhere.com/api/banks/SBIN0000139/
will return

     {
         "id": 81725,
         "ifsc": "SBIN0000139",
         "bank_id": 1,
         "branch": "NAINI",
         "address": "MIRZAPUR ROAD, NAINI, ALLAHABAD, UTTAR PRADESH, PIN 211008",
         "city": "ALLAHABAD",
         "district": "ALLAHABAD",
         "state": "UTTAR PRADESH",
         "bank_name": "STATE BANK OF INDIA"
     }

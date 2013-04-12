waitrose_survey_batch
=====================

www.waitrosecares.com - survey helper, having array of batch receipts and userdata as input
Will complete number of survey cycles for the user based on the number of receipts in array.

######Pre-requisites: 
1. Make sure you have Ruby 1.9.3 installed and watir-webdriver gem.
2. Fork repo and copy to local.
3. Add receipts to waitrose_receipts.txt, each from new line.
4. Add your data (including name, address, email, etc) to waitrose_userdata.txt in the following order:

* First Name
* Last Name
* Street Address
* Town
* ZIP
* Email
* Phone


#Instructions
1. In waitrose_survey_batch.rb uncomment lines 166-174 by removing # in fron of each line. (in order to have the requests sent at last step).
2. run "ruby waitrose_survey_batch.rb"

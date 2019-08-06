# BCG-application
BCG DV - Engineering Internship Program

# 1. Get an API Key

Endpoint: GET https://interns.bcgdvsydney.com/api/v1/key

Returns: key.json file:

{

      "key": "14ae13d0-dada-4acc-a922-8acea0a050f6", 
        
      "expires": "2019-08-06 10:01:42.395734"
}

HTTP Status: 201 Created

Screenshot: get_key.png

# 2. Application Submission
A name and email address are payloads to be submitted using the generated API key above as an application/json request.

Endpoint: POST https://interns.bcgdvsydney.com/api/v1/submit?apiKey=14ae13d0-dada-4acc-a922-8acea0a050f6

Body: submit.json file:

{

       "name": "Xu Han", 
  
       "email": "xhhan1@student.unimelb.edu.au"
}

HTTP Status: 202 Accepted

Screenshot: submit.png

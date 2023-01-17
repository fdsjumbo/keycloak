ERROR TYPE: { "error": "invalid_request", "error_description": "Missing form parameter: grant_type" }

Hi all, if you are experiencing an error in ARC "grant_type" when making a POST request to test keycloak you can do the following modifications in the parameter: set HEADER to "content_type" and set the value to "application/x-www-form-urlencoded"

Please leave a comment to indicate if this solution was able to help you.

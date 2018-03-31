# Serverless Framework AWS Python 3.6 Template
[![Serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)
[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
[![Build Status](https://travis-ci.org/ServerlessOpsIO/wild-rydes-auth.svg?branch=master)](https://travis-ci.org/ServerlessOpsIO/wild-rydes-auth)

Creates the Wild Rydes authentication and authorization service.  This is powered by [AWS Cognito](https://aws.amazon.com/cognito/) to handle signup and authentication.

## Resources

This will create:
* Cognito User Pool
* Cognito Client ID
* Lambda Function (For updating Wild Rydes website auth configuration)

## Outputs

__UserPoolId:__ ID of user pool that to handle user management for Wild Rydes.

__UserPoolClientId:__ Client ID for website to access user pool.


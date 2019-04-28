# A boilerplate for cloudfront react applications

This builds on the example at https://github.com/serverless/examples/tree/master/aws-node-single-page-app-via-cloudfront

## Building from scratch

1. Install serverless framework.
2. Initialize a serverless application
3. Copy/Replace the serverless.yml with the one from this repo
4. In the serverless.yml, update to the appropriate AWS region under the
5. `sls deploy` Deploy the cloudfront distribution and bucket
6. Build Single page app `npm init react-app app`
7. Build the single page app. `cd app && npm run build`
8. Deploy the single page app. `aws s3 sync build/ s3://<your-bucket>`
9. ???
10. Profit

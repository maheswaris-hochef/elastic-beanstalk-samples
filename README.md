# elastic-beanstalk-samples
This repository complements the AWS Elastic Beanstalk documentation.
Currently, it contains examples of [configuration files (.ebextensions)](https://github.com/awslabs/elastic-beanstalk-samples/tree/master/configuration-files).

You can report issues, make pull requests, and contribute your own resources to help other AWS Elastic Beanstalk customers use the service. We are committed to helping developers learn more about Beanstalk, and we hope you find the this forum useful. Please don't hesitate to let us know how we can improve it to be more useful.

The full set of Elastic Beanstalk documents is at http://aws.amazon.com/documentation/elastic-beanstalk/.

An open source version of the Elastic Beanstalk Developer Guide is at https://github.com/awsdocs/aws-elastic-beanstalk-developer-guide/.

## Sample applications
Sample applications that show the use of additional web frameworks, libraries and tools are available as open source projects on GitHub.

### AWS-provided sample applications
- [Load Balanced WordPress](https://github.com/awslabs/eb-php-wordpress) ([tutorial](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-hawordpress-tutorial.html)) – Configuration files for installing WordPress securely and running it in a load balanced AWS Elastic Beanstalk environment.
- [Load Balanced Drupal](https://github.com/awslabs/eb-php-drupal) ([tutorial](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-hadrupal-tutorial.html)) – Configuration files and instructions for installing Drupal securely and running it in a load balanced AWS Elastic Beanstalk environment.
- [Scorekeep](https://github.com/awslabs/eb-java-scorekeep) - RESTful web API that uses the Spring framework and the AWS SDK for Java to provide an interface for creating and managing users, sessions, and games. The API is bundled with an Angular 1.5 web app that consumes the API over HTTP. Includes branches that show integration with Amazon Cognito, AWS X-Ray, and Amazon Relational Database Service. The application uses features of the Java SE platform to download dependencies and build on-instance, minimizing the size of the souce bundle. The application also includes nginx configuration files that override the default configuration to serve the frontend web app statically on port 80 through the proxy, and route requests to paths under /api to the API running on localhost:5000.
- [Does it Have Snakes?](https://github.com/awslabs/eb-tomcat-snakes) - Tomcat application that shows the use of RDS in a Java EE web application in AWS Elastic Beanstalk. The project shows the use of Servlets, JSPs, Simple Tag Support, Tag Files, JDBC, SQL, Log4J, Bootstrap, Jackson, and Elastic Beanstalk configuration files.
- [Locust Load Generator](https://github.com/awslabs/eb-locustio-sample) - This project shows the use of Java SE platform features to install and run Locust, a load generating tool written in Python. The project includes configuration files that install and configure Locust, a build script that configures a DynamoDB table, and a Procfile that runs Locust.
- [Share Your Thoughts](https://github.com/awslabs/eb-demo-php-simple-app) ([tutorial](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-ha-tutorial.html)) - PHP application that shows the use of MySQL on Amazon RDS, Composer, and configuration files.
- [A New Startup](https://github.com/awslabs/eb-node-express-sample) ([tutorial](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/nodejs-dynamodb-tutorial.html)) - Node.js sample application that shows the use of DynamoDB, the AWS SDK for JavaScript in Node.js, npm package management, and configuration files.
- [Cognito Quickstart](https://github.com/awslabs/aws-cognito-angular2-quickstart) - an AngularV4-based QuickStart web app utilizing Amazon Cognito, S3 or Elastic Beanstalk, and DynamoDB (serverless architecture).

### Community-provided sample applications
- [go-beanstalk-gin](https://github.com/sudo-suhas/go-beanstalk-gin) - Demonstrates the deployment of a simple webapp built using `gin` to Elastic Beanstalk. Dependencies are managed using `dep`. Provided by [Suhas Karanth](https://github.com/sudo-suhas).

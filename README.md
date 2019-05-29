# Serverless-React-PWA-on-AWS

> How to create a serverless Progressive Web App, using React, Redux, React Router, TypeScript on frontend and AWS Lambda, Cloudfront, Amazon SES, API Gateway for a zero maintenance required backend.

## Route53

Create *your-domain.com* hosted zone and configure domain provider with AWS name servers.

On *Route53*:

![Create hosted zone](./images/Route53-Create_hosted_zone.png)

On your domain provider:

![Configure name servers](./images/Route53-Configure_name_servers.png)

## SSL Certificate

Go to *Certificate Manager* AWS service. Request an SSL certificate for _your-domain.com_ and
add also _*.your-domain.com_. Choose DNS validation option.

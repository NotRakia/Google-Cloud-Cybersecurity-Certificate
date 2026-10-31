# Serverless Computing

## 1. Serverless Computing Defined

- Serverless computing is a cloud computing model where servers are abstracted from development.
- Despite the name serverless, this computing model does involve servers.
- The servers and resources are completely managed by the cloud service provider (CSP).
- This allows developers to focus on creating and deploying code without worrying about backend infrastructure.

## 2. Backend as a Service (BaaS)

Serverless computing is delivered in two main cloud service models:

- Backend as a service (BaaS)
- Function as a service (FaaS)

BaaS

- BaaS is a form of serverless computing where the CSP manages all aspects of the backend infrastructure.
- This includes servers, containers, and virtual machines.
- Developers use BaaS to speed the creation of web applications.
- With BaaS, developers can focus on writing the front-end code, which is the code that builds the user interface.
- Organizations have access to other services, like databases, file storage, and authentication services that can be native or third-party to the platform.

## 3. Function as a Service (FaaS)

- FaaS is a form of serverless computing that runs functions.
- A function is a small piece of code.
- Functions are ephemeral, meaning they only exist for a short period of time.
- Developers can use their choice of programming language to create functions, which makes adopting serverless computing more convenient.

Example: Customer Sign-up and Welcome Email

- Companies can use functions to better engage their customers.
- A company chooses an event, like a customer signing up to join their website.
- Once the customer submits their sign-up request, they receive an email welcoming them to the website.
- In this example, the customer signing up triggered a function to send the email.
- The function only lived for the amount of time it took to trigger the email.
- Once the email was sent, the function expired.

Google Cloud Functions

- Google's Cloud Functions is a serverless product that facilitates event triggers using functions.
- With Cloud Functions, developers only need to write their code; Google Cloud handles the operational aspects of running servers and scaling your resources.

## 4. Benefits

Scalability and Pay-as-you-go Model

- One benefit of serverless computing is that it's scalable and follows a pay-as-you-go model.
- Resources scale up and down depending on demand.
- When a lot of customers sign up for the website at one time, the volume of functions scale up to meet the demand.
- The user only pays for the resources while they're being used.

Improved Developer Productivity

- Serverless also improves developer productivity.
- Since the CSP configures the backend infrastructure, teams can focus on developing code.
- They can also devote time to improving security, like securing firewalls and access to resources.

## 5. Security in Serverless Computing

Shared Security Responsibilities

- The security of serverless technology is important.
- Organizations share security responsibilities with the CSP.
- With serverless computing, organizations inherit the security controls the CSP has in place for their underlying infrastructure.
- The CSP takes some of the responsibility, but organizations also have security considerations to take into account.
- They're responsible for protecting their data and functions from vulnerabilities, and managing access to resources.

Security Advantages of Functions

- The short lifespan of functions contributes to their security.
- Since each function is short-lived, malicious actors have a very limited window to impose threats.
- Also, each function has a single role in a software application.
- If a malicious actor were to gain access to a function, they could only threaten the part of the application that uses that function.

Security Example: Vulnerability Notifications

- An organization adopts serverless computing to improve the security of integration with third-party applications.
- A function is created and run that will trigger an email whenever a security vulnerability appears.
- This allows the organization to be instantly notified of any immediate security concerns.

## 6. Key Takeaways

- Serverless computing is an emerging service with a lot to offer.
- With serverless computing, developers can focus on writing code without the responsibility and time it takes to configure servers.
- BaaS and FaaS are service models that can make using serverless technology even more beneficial.
- Scalability and increased productivity are also important benefits for organizations.
- Serverless computing poses new security considerations for cloud security professionals.
- While organizations share responsibilities with their CSP, security professionals should be prepared to protect data and resource access in a serverless environment.

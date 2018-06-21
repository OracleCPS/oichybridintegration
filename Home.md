# OIC (ICS) Developer Workshop

![](images/j2c-logo.png)

> Updated: March 13th, 2018

## Upgrade To The Cloud: Oracle Autonomous Integration Cloud (AIC) Hands-on Workshop
A hands-on workshop to dive into development on Oracle's Autonomous Integration Cloud Platform

## Overview
Enterprises can innovate faster, improve customer engagement, drive business-process efficiency, and accelerate digital transformation with Oracle Cloud. Oracle is the enterprise technology partner that positions companies for tomorrow, today; empowering businesses of all sizes on their journey of digital transformation. Oracle Cloud provides leading-edge capabilities in software as a service, platform as a service, infrastructure as a service, and data as a service.

At Oracle we have invested in delivering a plethora of new Cloud Services and we want to show you how simple – yet powerful they are. We specifically wanted to focus on low code, high productivity services that can be used in building enterprise grade solutions. We believe the best way to do this is to showcase a real world business solution comprised of these services. You will build the entire solution during the course of this workshop all in a stress-free fun environment. 

This workshop will focus on the Integration Cloud Service (ICS) capabilities within Oracle Integration Cloud (OIC).  Oracle ICS delivers best in class “Hybrid” Integration. ICS is a simple and powerful integration platform in the cloud to maximize the value of your investments in SaaS and on-premises applications. 

It includes an intuitive web based integration designer for point and click integration between applications and a rich monitoring dashboard that provides real-time insight into the transactions, all running on a mature runtime platform on Oracle Public Cloud. ICS will help accelerate integration projects and significantly shorten the time-to-market through it's intuitive and simplified designer, an intelligent data mapper, and a library of adapters to connect to various applications.

## About OIC:

Oracle Integration Cloud (OIC) brings together all the critical capabilities of a complete Application Integration, Process Automation, Visual Application Building and Integration Analytics solution into a single unified cloud service. Oracle Integration Cloud now brings real-time and batch based integration, structured and unstructured processes, case management, stream analytics, zero code integration insight etc, allowing customers to service all their end to end integration needs in one cohesive platform so that all users can now transition and collaborate across these capabilities and projects seamlessly.

![](images/oic.png)

### Oracle Integration Cloud Features

- Integrate Applications - Deliver integrations up to 6X faster with pre-built adapters for your SaaS and on-premises systems.

- Automate Processes - Streamline your digital workforce with an easy, visual, low-code process automation platform that simplifies day to day tasks by getting employees, customers, and partners the services they need to work anywhere, anytime, and on any device.

- Build Applications Visually - Rapidly create and host engaging business applications with a visual development environment right from the comfort of your browser. Define business objects, integrate data from external system, incorporate business processes, and design tailored interfaces to create your apps.

- Gain Insight - Gain real-time insight into end-to-end processes with guidance on best next steps for your business operational excellence and run massively parallel real-time analytics on streaming data for instant actionable insights. 

## Hands-on Lab Overview
This hands-on lab will allow participants to do the following:
- Lab 100 - Explore Oracle Integration Cloud Service
- Lab 200 - Create a simple Hello World API echo service
- Lab 300 - Create an API to retrieve enterprise information from an On-Premise Oracle Database using OIC Connectivity Agent
- Lab 400 - Implement an Order API to create Orders in an On-Premise Enterprise Application (Oracle EBusiness Suite)

The ICS integration that we'll be working with is shown in the following picture:

![](images/overview-image.png)

Here is a description of what is happening with this integration:

SoapUI will be used to test the exposed Web Service endpoint of the ICS integration called *UserXX Create EBS Order* (where XX will be the Number assigned by the Instructor).  This integration has 3 connections.  The incoming message is received by the incoming *UserXX SOAP* Soap Connection.  The *UserXX Create EBS Order* orchestration makes 1 query into the database using the *UserXX Oracle DB 12c* connection to get details needed to create an order.  The orchestration finally uses the *UserXX EBS OPERATIONS* EBS Adapter connection for creating the order in EBS.  After the order is created in EBS, the Order Number is returned to the calling web service.

## Get Started: 
Open the navigation menu using the hamburger icon in the upper left of the menu bar to choose a lab guide and get started.

The hamburger menu has an icon that looks like this: <img src="images/menu.svg">

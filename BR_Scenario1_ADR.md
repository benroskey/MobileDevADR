# Architectural Decision Record - Retail Company App

Scenario 1 from the Assignment - Architectural Decisions will be what the following report is based on.

## Status

Proposed

## Context

The issue being faced is that You are a team responsible for developing a new mobile app for a retail company. The question being which app type to move forward with; Native, Web, or Hybrid.

Let us begin with looking at the company requirements.

- The retail company wants the app to support offline mode. This allows customers to brows products and view their order history even when not connected to the internet.
- Push notifications are a request from the company, this way customers can receive order updates, new products, and exclusive offers.
- Payment gateways to accomodate secure transactions for customers that are to be secure, and easy to use.
- Customer behaviour and tracking can be accessed through the app, as the company will require personal information. Therefore being able to track and use analytics to direct other products towards the same customers. This provides the company valuable analytics and information on all of their customers.
- Supporting multiple languages throughout the app so no customer has a barrier and is able to use the app effectively.

A Native App would be specifically designed for a single platform, in this case a handheld device being either an Apple or Android device.

Web Apps are accessed through a user's web browser, require an internet connection, but are compatible with multiple platforms and devices.

A Hybrid App is exactly as the name describes. Having cross-platform compatibilty and built in web technologies, a user can decide to access the company's retail site through their app OR website. Though both require an internet connection.

## Decision
Based off that the app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries, have a loyalty program feature, where customers can earn and redeem points for discounts on future purchases. A Native App would be most widely used and accepted by not only customers, but the company as well.

For this scenario, a Web App has the most disadvantages as the key issue is it requires internet to function at all times, thus disregarding it in the competition for which app will be chosen.. The Native and Hybrid App routes do have advantages and disadvantages, breaking them down shows how a Native App has the least amount of disadvantages.

#### Hybrid App
Hybrid Apps are relatively cheaper in cost, use one codebase, are able to be built more quickly, and as a result are great for simpler applications. The fact that this is not a simple application does not bode well for a solution, especially when tied in with the downside uses. They are not high performers, consist of less mature platforms that do not document, require a complexity higher than other app requirements, and have no access to native features such as Touch and Face ID for payments. Again, a requirement from the company being effective and efficient ways of paying for products.

#### Native App
Native Apps do not require internet to operate AND operate at higher speed, they provide a softer and more recognizable feel for users on the front-end, and have the ability to maintain apsect ratios on varying handheld devices improves the quality of the product images. The downside is they (most of the time) have lengthy downloading procceses from the app store, time-consuming and expensive developments which has the opportunity to make the company become impatient. There is also no flexibility when it comes to the platform, again increasing the development time as developers must code one platform at a time. Bug fixes can pose issues and may require multiple updates if it persist or many arise. Though with the team of coders on call, this becomes a quick fix in the modern world.

## Consequences

A Native App allows the company to optimize performance, work offline, easily access device features at high speeds, and have a higher customer satisfaction rating. Though it comes at a literal cost of longer development time, multiple codebases, and is pricier. But when one looks at the business requirements, it is easier to recommend a Native App for the company.
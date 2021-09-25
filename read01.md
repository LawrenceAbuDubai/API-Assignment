# APIs and SDK

in this page, i will be explaining :

API types
the benefits of APIs
the differences between API and SDK

## What is an API? (Application Programming Interface)

Application Programming Interface (API) is a software middleman that allows two apps to communicate with one another. You utilize an API every time you use an app like Facebook, send an instant message, or check the weather on your phone.

### What Is an Example of an API?

When you use a mobile phone application, it connects to the Internet and sends information to a server. The server then retrieves the information, interprets it, takes the appropriate actions, and sends it back to your phone. The software then analyses the data and displays the information you requested in a legible fashion. All of this happens via API, which is what an API is.

Consider yourself at a restaurant table with a menu of options to choose from. The kitchen is a component of the overall “system” that will prepare your order.What's missing is the crucial link that allows you to communicate your order to the kitchen and have it delivered to your table. That's where the waiter, sometimes known as an API, comes in. The waiter is the messenger – or API – who receives your request or order and transmits it to the kitchen – or system. The waiter then gives you the response, which in this case is the food.

Here's an example of a real-world API. You may be aware with the procedure for looking for flights on the internet. You have a range of alternatives to pick from, much like the restaurant, including different cities, departure and return dates, and more.Assume you're looking to book a flight on an airline's website. You can select a departure city and date, as well as a return city and date, cabin class, and other options. To book a flight, you go to the airline's website and search their database to see if any seats are available on those dates and how much they will cost.

What if you aren't utilizing the airline's website, which provides immediate access to the information? What if you're using an online travel service like Kayak or Expedia, which compiles data from multiple airline databases?

In this scenario, the travel service communicates with the airline's API. The API is the mechanism through which that online travel provider, like your friendly waiter, may request information from the airline's database in order to reserve seats, baggage options, and so on. The API then sends the airline's response to your request back to the online travel service, which displays the most up-to-date, relevant information.

#### What an API Also Provides Is a Layer of Security

The data on your phone is never completely exposed to the server, and the server is never completely exposed to your phone. Instead, each connects with little data packets, sharing only the information that is required—such as ordering takeout. You tell the restaurant what you want to eat, they tell you what they require in exchange, and you get your meal at the end.

APIs have become so lucrative that they now account for a significant portion of many companies' revenue. Google, eBay, Salesforce.com, Amazon, and Expedia are just a handful of the major corporations that profit from their APIs. This marketplace of APIs is referred to as the "API economy."

#### The Modern API

Over the years, the term "API" has been used to refer to any type of application communication interface. However, in recent years, the modern API has acquired key qualities that make it extremely valuable and useful:

+ Modern APIs adhere to developer-friendly, easily accessible, and widely understood standards (usually HTTP and REST).
+ They're regarded as though they're products rather than code. They are developed for specific audiences (e.g., mobile developers), are documented, and are versioned in such a way that users can expect certain maintenance and lifetime expectations.
+ They have a lot greater discipline for security and governance, as well as being monitored and controlled for performance and scale, because  they are much more standardized.
+ The modern API, like any other productized software, has its own software development lifecycle (SDLC) that includes designing, testing, constructing, maintaining, and versioning. Modern APIs are also well-documented in terms of usage and versioning.

------------------------------------------------------------------------

## API types

APIs are widely used and approved in online applications. Public, partner, private, and composite APIs are the four most prevalent forms of API used in web-based applications. The API's "type" shows the intended scope of use in this case.

+ **Public APIs**: APIs that are open to the public. Any outside developer or business can utilize a public API because it is open and available. A company that develops and offers a public API will have a business model that includes sharing its applications and data with other companies.

Authentication and authorisation are usually moderate in public APIs. An organization may also try to monetize the API by charging a per-call fee to use the public API.

+ **Partner APIs** : A partner API is a tool for facilitating business-to-business transactions that is only available to a small group of outside developers or API consumers. For example, if a company wishes to share customer data selectively with outside CRM businesses, it can utilize a partner API to connect the internal customer data system with those external partners — no other API use is allowed.

Access to such APIs is limited to partners with specific permissions and licenses. As a result, partner APIs typically include more robust authentication, authorisation, and security features. In addition, most businesses do not directly monetize APIs; rather, partners are compensated for their services, not for API usage.

+ **Internal APIs**: An internal (or private) API is designed to connect systems and data within the company. An internal API, for example, might link an organization's payroll and HR systems.

Because internal APIs are meant for internal usage, and such security levels are presumed to be in place through other policies, they typically have minimal security and authentication — or none at all. This is changing, however, as organizations' API strategies are more influenced by increased threat awareness and regulatory compliance requirements.

+ **Composite APIs**: Composite APIs are made up of two or more APIs that work together to create a series of connected or interdependent activities. Composite APIs can be useful for addressing complex or closely linked API behaviors, and they can occasionally outperform individual APIs in terms of speed and performance.

------------------------------------------------------------------------

## Benefits of APIs

+ Increases productivity:
As the demand for contemporary software grows, businesses are looking for faster ways to prototype and develop new products. Developers wasting time designing applications from the ground up when a similar solution is already available as an API might have a detrimental impact on your company's productivity.

APIs are a valuable tool for accelerating development. Instead of designing solutions from the ground up, developers can use APIs to swiftly apply existing functionality.

For example, Microsoft offers a Text Analytics API that allows you to conduct activities like language detection, key phrase extraction, and sentiment analysis using text.

You can use sophisticated state-of-the-art technologies and integrate them into your apps using such an API. This can help you save a lot of time on development and increase the productivity of your company, allowing you to achieve your goals faster.

According to a recent survey, firms that used APIs saw a 59 percent gain in efficiency across various key aspects of their operations.

+ Saves costs:
The cost of developing an app is determined by a number of factors, including the project's complexity, the technology employed, and the developers' experience. According to one poll, the average cost of building and deploying an app is $270,000.
The opportunity to save money is one of the most significant advantages of APIs for businesses. Using APIs to construct applications is a wonderful method to cut expenses because they greatly reduce development work.
Developers can use APIs to get the majority of the functionality they need to build apps from other places, rather than having to start from scratch. They can leverage cost-effective APIs from third-party suppliers or their own internal APIs instead of wasting precious resources and time recreating the wheel.

Using APIs allows developers to focus on fine-tuning the unique capabilities of their apps faster, which helps businesses save time and money.

+ Improves connectivity and collaboration:
Private APIs, often known as internal APIs, can help businesses increase cooperation and internal communication. APIs enable disparate systems, applications, and platforms to communicate and share data, as well as perform a variety of operations.

The average corporation used only 5 to 10 different programs in the early 1990s. In today's world, it's estimated that the average business operates 464 custom applications.

As organizations adopt new applications at unprecedented speeds, separate and siloed environments emerge, obstructing communication and connectivity.
APIs act as the glue that connects and interacts between otherwise disparate software systems, such as those for customer relationship management (CRM), marketing automation, and financial services.

This increased connectivity and collaboration results in interoperable components that let businesses deliver their desired functions without constraints.

APIs are also extremely useful when an application is constructed utilizing the microservices design, which consists of a collection of small, loosely linked components that communicate with one another using APIs.

+ Encourages innovation:
Another significant advantage of APIs is that they allow businesses to accelerate innovation. In today's digital world, more than ever, innovation is critical to an organization's success.

Businesses who fail to introduce new items on a regular basis to satisfy changing client expectations and evolving technical trends will be left behind. In fact, it's estimated that 56% of customers prefer to buy from the most forward-thinking businesses.

APIs are fantastic for causing disruption and fostering innovation. Enterprises may use APIs to deploy cutting-edge technology with minimal resources, quickly adjust to client requirements, and open up new business opportunities.APIs help businesses improve their competitiveness, differentiation, and efficiency by allowing them to connect with each other. According to the aforementioned survey, businesses that integrated APIs saw a 51 percent increase in innovation.

APIs, according to Gartner, are critical in minimizing the friction that often results from a bimodal IT strategy, in which old systems (Mode 1) coexist with flexible, creative solutions and approaches (Mode 2).

APIs can serve as a connecting layer, allowing for a more seamless connection between the two modes, resulting in the development of innovative and feature-rich apps. APIs allow you to seamlessly extract value from legacy data sources and improve your business.

+ Enhances customer experience
Let us now discuss the advantages of APIs for customers.

Enterprises may establish innovative and effective ways of communicating with customers by exploiting APIs' capabilities, especially in the present digital age when consumers demand top-notch experiences.

Personalized experiences, rather than one-size-fits-all business solutions, are what today's customers want. According to Gartner, businesses who use personalized messages to assist customers can expect a 16 percent gain in revenue over those that don't.
API users can take control of their own customer experiences, allowing organizations to disclose their data and services via APIs, opening up a world of possibilities. These interfaces allow customers to take control of the customer journey and identify its flaws.

Developers can use APIs to design solutions that fulfill specific client requirements, which would be impossible to do otherwise.

Many organizations, for example, use APIs to implement cutting-edge artificial intelligence and predictive analytics technology that analyzes a buyer's unique path and suggests the "next best action." This enhances the shopping experience for customers and increases sales.

------------------------------------------------------------------------

## differences between API and SDK

API and SDK are two words in software development that are sometimes misunderstood. API stands for "Application Programming Interface," and it relates to programming instructions and standards for interacting with a website or database. For example, a software business may frequently make its API available to other software developers, either publicly or privately, so that they can create products that use the service. An SDK, or Software Development Kit, can be used to bundle an API.
An SDK is a set of software development tools that allows you to create apps for a certain platform. One or more APIs, as well as development tools and documentation, can be found in SDKs. Consider the Java SDK, which includes an API as well as compilers, runtimes, and other tools.

An API is a collection of libraries that make up the core language and can be used right away, whereas an SDK is a development kit that makes it easier to use an API. Both are, in theory, ways for your application to communicate with and control resources offered by another piece of software. A web service, an end-user app, an OS service or daemon, or a kernel device driver could all be examples of software.
So, an API is nothing more than an interface to a service, whereas an SDK is a collection of tools or components for a specific purpose. In truth, an SDK provides you with an API to interact with, but you can utilize an API without the underlying components if the API is given through a web service, for example.

------------------------------------------------------------------------

## references

<https://www.mulesoft.com/resources/api/what-is-an-api>
<https://searchapparchitecture.techtarget.com/tip/What-are-the-types-of-APIs-and-their-differences>
<https://blog.api.rakuten.net/api-benefits/>
<https://www.axway.com/en/products/api-management/extend-apis/sdk>

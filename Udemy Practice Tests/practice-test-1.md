# AEM Business Practitioner Practice Tests / Udemy

### Practice Test 1


1 // What is the recommended method to view a pages as it was in a previous point in time?

:heavy_check_mark: Use Timewarp to simulate the published state of a pace at specific times in the past

2 // A client is building out their website using several different content pages web specific components to be used on each page. What is the recommended system to restrict components on specific templates?

:heavy_check_mark: Use content policies

3 // A developer plans to use the Text component on its pages. However, the out of the box (OOTB) Text component does not allow authors to edit HTML source on the component. How should the developer support HTML source editing?

:heavy_check_mark: Extend the OOTB Text component and enable the source edit Rich Text Editor (RTE) plugin

4 // What is the main function of AEM Screens?

:heavy_multiplication_x: AEM Screens is used to emulate the content of different devices

:heavy_check_mark: AEM Screens is used to display intereactive content on digital signs

5 // You want your online store to be updated quarterly so that the featured products align with the current season. What is the best approach to prepare the new web pages for the next quarterly update?

:heavy_check_mark: Develop your content by creating and editing a launch

6 // A client has approached you and said that their renditions are not appearing for an asset recently uploaded. As an author, how would you troubleshoot this issue?

:heavy_check_mark: Check the properties of the asset

7 // The customer wants to set up the organization so that edited pages are reviewed and approved by a limited set of business stakeholders prior to being published. How do you establish this process?

:heavy_multiplication_x: Remove publishing rights for general authors

:heavy_check_mark: Use a publish workflow

8 // You want users to be able to fill out wizard like forms on any device. What AEM Forms type is best suited for this scenario?

:heavy_multiplication_x: XFA Form

:heavy_check_mark: Adaptive Form 

❗ o adaptive form é usado mais para adptações de layout, displays, etc, enquanto o XFA form tem a ver com conteúdo (usa xml)

9 // Developers made changes to a page. The client views the page but still sees the old version. However, when the client views the page in Incognito mode, the new page displays correctly. What is the solution to this problem?

:heavy_check_mark: Clear the cache of the browser and access the page again

10 // Regarding performance, what are the Adobe recommended response time guidelines for uncached HTML requests?

:heavy_check_mark: 70% of the request for pages should have a response in less than 100ms

11 // If a client wants to add a Facebook pixel or do analytics tracking, what option do you recommend?

:heavy_multiplication_x: Add a custom script with Adobe Target

:heavy_check_mark: Use a tag management toll such as Adobe Launch

❗ O Adobe Target serve mais para experiências personalizadas e o Adobe Launch é mais para analytics e estatísticas.

12 // A template author wants to modify the default layout for all existing product pages. If the original editable template is modified, what happens?

:heavy_multiplication_x: All existing product pages are changed to reflect the change including the initial content and structure of the template

:heavy_check_mark: All existing product pages are changed to reflect the change in structure excluding the initial content

13 // How can an author determine the number of Language Copies for a given page?

:heavy_multiplication_x: The language copies will be displayed in the filters section

:heavy_check_mark: The language copies will be displayed in references section

14 // SEO best practice states that if a user were to see a URI and none of the content on the page, they should be able to describe what the page is. Which AEM feature allows you to control a URL while maintaining SEO integrity?

:heavy_check_mark: Use the vanity url field of the page property to configure the url

15 // A client’s side is having authoring consistency issues due to authors publishing pages with components ordered differently on each page. Using AEM Best Practices, what is the best way to configure content components in order to avoid this issue?

:heavy_multiplication_x: Create a Continuity Outline for authors, allowing for a structured design while maintaining flexibility

:heavy_check_mark: Set allowed components within a template, bracketed by structural components that remain constant

16 // Developers implement a home page that seems to render slowly. What feature does AEM provide to measure the time it takes for a page to render?

:heavy_multiplication_x:Run the recommendation report to check the load time of the page

:heavy_check_mark: Use the developer mode to observe computational time needed to render all components

17 // A company plans to develop a set of pages with the same design and structure. The only difference between the pages is the content inside the body. What is the best approach to develop the pages?

:heavy_check_mark: Create a page template for all pages with a layout container in the body

18 // A company has an existing English language site for the Canadian market. It is planning to create a new site for the US market. While most of the control of the current site can be reused for the new site, how would you create the new site in the most efficient manner?

:heavy_multiplication_x: Copy the site root (ca/en) and paste int in the regional root (us/en)

:heavy_check_mark: Create a live copy from the (ca/en) root to (us/en)

19 // A client wishes to moderate communication between their customers and their in house product experts, expecting a very large amount of user generated data. How can this be accomplished?

:heavy_check_mark: Create a forum and Q&A site using AEM Communities

20 // A company foresees the structure of page templates will change frequently for its pages. Why is it important to use editable templates instead of static templates?

:heavy_multiplication_x: Editable templates are replicated faster to a publish server

:heavy_check_mark: A dynamic connection is maintained between the page and the template on existing pages

21 // You want to create a grouping of all the assets under a specific category that are contained in various location across the DAM. What is the best way to achieve this?

:heavy_check_mark: Use Smart collections

22 // As an asset manager, how could you best ensure that only valid metadata is shown for a particular asset type?

:heavy_check_mark: Define a metadata schema for a type and apply it to a specific folder

23 // You are running through an AEM Assets Discovery Checklist for your customer. Their main concerns are low downtime and minimum latency issues. What are two most important questions that you can ask the customer to best address their concerns? Choose two.

:heavy_multiplication_x: Do you intend to use Creative Cloud Integration?

:heavy_multiplication_x: What are the types of assets to be migrated?

:heavy_check_mark: What is the typical network connectivity for users accessing AEM?

:heavy_check_mark: What hours are considered "off peak" for your content authors?

24 // Given that your company has a team of creative content creators for your AEM managed website, which is true for managing images and videos?

:heavy_multiplication_x: You should connect AEM to the Creative Cloud

:heavy_check_mark: You should enable the Smart Tagging feature to sabe time on video tagging

❗ Não entendi pq esse ta errado

25 // Refer to the exhibit. Which is an AEM page mode?

:heavy_multiplication_x: Publish

:heavy_check_mark: Timewarp

26 // What can be done to obtain a better bounce rate for your site? Select two.

:heavy_check_mark: Use Adobe Target A/B testing to determine the best performing versions of your pages

:heavy_check_mark: Use AEM Insights to capture activity details and make data driven

27 // Your company is launching a website with customers from around the world. What capabilities of AEM Sites would allow you to make the content more relevant to the largest amount of customers? Choose two.

:heavy_multiplication_x: Launches

:heavy_multiplication_x: Editable templates

:heavy_check_mark: Translation framework

:heavy_check_mark: Multi Site Manager

❗ Usar ferramentas de linguagem para ter maior capacidade de afetar usuários

28 // A specific user is encountering an error while editing a page that other authors have not reported. How would you troubleshoot the problem using AEM?

:heavy_multiplication_x: Check the Page timeline

:heavy_check_mark: Impersonate as the user reporting the issue

29 // When a user requests a cacheable document from the AEM Dispatcher, what will the Dispatcher check to access whether the document exists in the web server file system? Choose two.

:heavy_check_mark: If the document is cached, the AEM Dispatcher returns the file from the CDN Cache

:heavy_check_mark: If the document is not cached, the Dispatcher requests the document form the AEM instance

30 // An author would like to display an AI summarized version of an article. Which method would you recommend to achieve this?

:heavy_multiplication_x: Create a varitation of an experience fragment

:heavy_check_mark: Create a variation of a master content fragment

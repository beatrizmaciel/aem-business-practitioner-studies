# Exam AD0-E121

1 // An author would like to display an AI-summarized version of an article. Which method would you recommend to achieve this?

✔️ Create a variation of a master content fragment

2 // A customer watns to add a field to the properties of all existing and new assets in AEM Assets to capture the asset rating. After the team uploads an asset the review team needs to go through the uploaded assets and fill the ratings. How should the Business Practitioner meet this requirement?

✖ Create a new schema with the rating property via the Folder Metadata Schemas tool

✔️ Guild a new profile with the rating property for assets via the Metadata Profiles tool

❗ Metadata profiles são utilizados para replicação de propriedades em assets. Assim, esses profiles podem ser aplicados a pastas e todos os assets que estiverem nestas pastas passam a ter as mesmas propriedades. Se tiverem mais de um profile em pastas mães ou irmães, os metadata profiles usam o profile mais próximo, respeitando a hierarquia da árvore. [Saiba mais sobre metadata profiles aqui](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/configuring/metadata-profiles.html)

3 // A new user who is a member of the content-authors group needs to access the AEM web console. The new user should not be added to the administrator's group. What should the Business Practitioner recommend?

✖ Give additional permissions to the new user

✔️ Update the IMS configuration

❗ O Adobe IMS (Identity Management System) é utilizado para fazer integrações do AEM Cloud com o Adobe Analytics ou o Adobe Target. Essas configurações são feitas no Adobe Developer Console. [Saiba mais sobre o Adobe IMS aqui](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/authentication/adobe-ims-authentication-technical-video-understand.html)

4 // A customer has a multi-step asset creation workflow process that contains the following
steps:
• Create Asset
• Off-shore Review
• On-shore Review
• Legal Approval
• Brand Approval
• Complete

When viewing the individual tasks the customer prefers to see a simplified view of the
process which consists of the following phases:
• Create
• Review
• Approval
• Complete

What should the Business Practitioner recommend that the customer create and assign?

✖ A workflow step to a model

✔️ A stage property to each workflow step

❗ É possível configurar as propriedades das etapas do workflow, deixando-as mais adaptáveis. [Leia mais aqui](https://experienceleague.adobe.com/docs/experience-manager-65/developing/extending-aem/extending-workflows/workflows-models.html), no item 5 de "Configuring Workflow Stages (that show Workflow Progress)".

5 // A developer plans to use the Text component on its pages. However the out-of-the-box (OOTB) Text component does not allow authors to edit HTML source on the component. How should the developer support HTML source editing?

✖ Extend the OOTB Text component and enable the source edit Rich-Text Editor (RTE) plugin.

✔️ Edit the OOTB Text component directly to enable sourceedit Rich-Text Editor (RTE) plugin.

6 // A customer that uses version 6.5 wants to have a text component with basic text editing features. The solution must require minimal effort cost and time to meet the deadline. Which approach should a Business Practitioner recommend?

✔️ Use Core Text Component

7 // A major logistics company wants to repurpose the content copy created for us website access the enterprise applications, so that they can be displayed differently in multiple channels and locations. Which feature should a Business Practitioner recommend in AEM 6.5?

✖ Experience Fragment

✔️ Published Content

❗ Eu não entendi... esse published content se refere ao [Locked (Published) Content Fragment Models](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragment-models.html)?

8 // A company plans to develop a set of pages with the same design and structure. The only difference between the pages is the content inside the body. What is the belt approach to develop the pages?

✔️ Create a page template for all pages with a layout container in the body.

9 // A customer wants to enable Two authors to finish each other's assignee workflow tastes when one author is absent or share an excessive load in the short term. What should a Business Practitioner recommend?

✖ Add both authors to workflow-users group

✔️ Add both authors to dam-users group

❗ Não entendo porquê... outras opções são "Add both authors as impersonators of each other" e "Add both authors to a participant step"

10 // A customer has been using the AEM ContextHub feature Cut wants to extend it by adding an additional API. The additional API will be used to allow digital marketers to target banners based on CRM data for the current visit. What should the Business Practitioner recommend that the customer create?

✔️ A ContextHub UI module

❗ ContextHub é um framework que ajuda o marketing a acessar as informações dos visitantes da pagina. As outras opções não tem como objetivo o marketing. Revisando:

- "A custom session store candidate" : permitem acesso para dados de amarzenamento, essa opção não se relaciona com dados para marketing.

11 // Due to a major conflict In the 'add to cart" functional requirement in the e-commerce project, the development team cannot proceed with the planning and implementation. After a detailed discussion with the product Owner and development team, the requirement conflict is still not resolved. Who should the business Practitioner meet with to resolve this issue?

✖ Business Owner & Architect

✔️ Scrum Manager & Project Manager

❗ Isso não faz sentido

12 // The marketing team runs a campaign that starts at midnight. The campaign includes multiple updates to the existing pages across the website. The marketing team needs to activate all changes automatically during non-business hours. What should the Business Practitioner recommend?

✖ Set On Time to the campaign start hours in On/Off Time section of page properties

✔️ Run "Request for Activation" workflow and specify the campaign start time m the workflow title

❗ O "Request for Activation" funciona de forma automática. "The OOTB “Request For Activation” workflow is located here: /libs/settings/workflow/models/request_for_activation", [fonte](https://blogs.perficient.com/2019/02/11/customizing-request-for-activation-deactivation-wizards-aem-6/).

13 // A customer has a website that serves an English-speaking market. The customer wants to expand to a German-speaking market. What should the Business Practitioner recommend to seamlessly create the new website structure?

✔️ Use the MSM functionality to create a live copy

❗ O Multi Site Manager (MSM) é um framework de configuração para deploy de conteúdo automático. É responsável por live copies, blueprints e rollouts

14 // A new content author at 3 media company joins a team to manage content taxonomy, me author has been set up as a new use' and must only have the minimum rights for this job. Which group should the author be added to m order to meet this requirement?

✖ user-administrators

✔️ projects-administrators

15 // Regarding performance, what are the Adobe recommended response Time guidelines for uneached HTML requests?

✔️ 70% of the requests for pages should have a response in less than 100mt

16 // A media customer wants to implement an enterprise DAM to manage their assets. The customer works closely with third-party agencies who build and deliver bulk creatives for their projects. The marketers manage asset renditions for mobile and web layout. Which two features should the Business Practitioner recommend for the setup? (Choose two.)

✖ A Dynamic Media

✔️ An integration with Adobe Creative Cloud

✔️ An AEM Assets with Adobe Asset Link

❗ O Adobe Asset Link é uma extensão para o Adobe Creative Cloud que permite a integração de programas terceiros, tais como Photoshop, Illustrator, InDesign, entre outros.

A Creative Cloud é uma coleção com mais de 20 aplicativos, um tipo de ambiente que possibilita o acesso aos apps e criação e organização de bibliotecas publicas ou privadas.

Quando falamos de integração de programas terceiros, o Dynamic Media não dá conta dessa associação, por isso as outras opções estão corretas.

17 // A content manager has many assets that the team is working to upload into AEM. Multiple users are responsible for adding the assets. Each asset must be uploaded only once. What should the Business Practitioner update?

✔️ Day CQ DAM Asset Upload Restriction

❗ A configuração de `Day CQ DAM Asset Upload Restriction` é feita no Configuration Manager e serve para restringir o tipo de assets que usuários podem fazer upload. [Saiba mais aqui](https://github.com/AdobeDocs/experience-manager-64.en/blob/main/help/assets/configuring-asset-upload-restrictions.md)

O Digital Rights Managements for digital assets serve para associação com licenças que especificam termos de duração de uso.

18 // A customer with multi-regional offices wants 10 create a website. The digital marketing team wants the content to be created once so that it can be re-used on other sites. The regional offices are allowed to make variations to the website without modifying the core information supplied by the head office. Which feature should the Business Practitioner recommend?

✔️ Live Copy

19 // A customer wants to place lag manager scripts on its pages based on the environment The three environments are as follows: 
• Dev Environment 
• QA Environment 
• Production Environment 

The Business practitioner needs to recommend a feature so that the scripts are loaded in the correct environment. What should the Business Practitioner recommend the company use?

✔️ Runmodes

20 // A content manager needs to see how rent/ published AEM pages perform by seeing Page Views. Unique Visitors, and Time on page while viewing the pages In the AEM Site Console. Which two recommendations should the Business Practitioner make? (Choose two)

✖ Use Column View

✔️ Configure AEM to Integrate with Adobe Analytics

✔️ Use Card View

❗ Teoricamente a visuação em cards não mostra visualizações, por que essa é a recomendação?

21 // Which role is responsible for implementing websites, mobile applications and DAM features?

✔️ Developer

22 // Which AEM feature provides support for content editing of single-page applications?

✔️ SPA Editor

23 // A customer needs to update their live site when the author triggers any content activation. What should a Business Practitioner recommend be configured?

✖ Dispatcher Flush Agent

✔️ Chain Replication Agent

❗ "Durante a criação, há um agente de replicação configurado para apontar para a instância publish que, quando algo for ativado, ele acionará para enviar o arquivo e todas as suas dependências para o publish", [fonte](https://experienceleague.adobe.com/docs/experience-manager-learn/ams/dispatcher/disp-flushing.html?lang=en). Uma chain replication é uma abordagem para coordenar clusters de servidores de armazenamento anti-falha.

24 // A customer Is going through assets implementation and is concerned that load testing tasks will increase the cost of the project budget What should the Business Practitioner recommend?

✔️ Conduct Risk Assessment

25 // Which tool should the Business Practitioner recommend to the content team to manage their team, tasks, and relevant resources?

✖ Projects

✔️ Blueprint

❗ Não faz sentido!!!!

26 // An end user tries to create a page on the Sites console but receives the following error: Problem Accessing '’/content/loo/bar.html.’ Reason: 403 Forbidden How should the Business Practitioner categorize the issue during the initial triage?

✔️ Permission issue

27 // A business uses AEM as a Cloud Service. The production pipeline in Cloud Manager Keeps reporting a maintainability issue during the hot-fix deployment It will take more than 1 business day for the development learn to resolve the deployment issue. The business wants an immediate resolution. What should the Business Practitioner recommend to the development team?

✖ Set important failure behavior setting to "Continue immediately" and re-run the build

✔️ Uncheck Go Live Approval setting in Production Deployment Options and re-run the build

❗ 

28 // An author plans to change the source pages that occur as a result of normal maintenance. The author will handle multiple root branches and promote the content without disturbing the published content. What should a Business Practitioner recommend to the content authoring team?

✔️ Use the rollout option on a blueprint

29 // A content author receives a request to build a new page with content that includes images and layout that exists on other pages. The page must be built using the existing content. What should the Business Practitioner recommend to meet this requirement?

✖ Leverage the experience fragment reference component

✔️ Leverage the content fragment reference component

30 // Which Workflow model property should a Business Practitioner select for a workflow that will be ran often and does not require saving workflow runtime history?

✖ Transient Workflow

✔️ Asset Microservice

❗ 

31 // Which role is responsible for scope and timeline delivery to a customer?

✔️ Project Manager

32 // A product manager wants to Incorporate content that lets users knows where they are in the purchase flow. This feature needs to be implemented efficiently and as quickly as possible. What should the Business Practitioner recommend to meet this requirement?

✔️ Use the progress bar component

33 // A developer makes the requested changes to a page on a live site. The developer then verifies that changes are reflected correctly on the page. The customer reports that they still set an older version. What should the Business Practitioner verify first?

✖ Page reflects changes on Incognito Mode

✔️ Dispatcher cache refresh

34 // An AEM project (i.e. Myproject) has been deleted. What would happen to the groups (Myproject Owners. Myproject Editors and Wyproject Observers) associated with the deleted project?

✔️ These groups will remain in AEM and require manual deletion by administrators

35 // You are running through an AEM Assets Discovery Checklist for your customer. Their main concerns are low downtime and minimum latency issues. What are two most important questions that you can ask the customer to best address their concerns? Choose two.

✔️ What is the typical network connectivity for users accessing AEM?

✔️ What hours are considered "off-peak" for your content authors?

36 // A new content author joins a company for a content editing and authoring job. A user Has been created. The user needs only the minimum rights for this job. Which group should the user be added lo in order to meet this requirement?

✖ The "content-authors" group

✔️ The "contributor" group

37 // The editorial manager notices that the content team Is not following the recommended taxonomy and created tag duplicates in the different places of the tag hierarchy. The editorial manager follows up with the team and asks the Business Practitioner for the most efficient solution for the duplicates. What should the Business Practitioner recommend the editorial manager use?

✖ Delete operation

✔️ Unpublish operation

38 // How should a Business Practitioner integrate Adobe Sensei with AEM for Smart tag feature?

✖ Use Adobe Sensei configuration

✔️ Use Adobe Launch to integrate Adobe Sensei

39 // A customer plans to launch a sub-site. All of the pages will have a similar design win the only difference being the authored content. How should a Business Practitioner develop these pages?

✖ Create one editable template with a layout container

✔️ Create one editable template with a text component

40 // A content owner is concerned about violating current license agreements for assets that have reached their contract end date. The Business Practitioner needs to make sure the published assets get unpublished. Users from the Authors or Contributors groups should not be able to republish an asset when it reaches Us contract end date. Which asset property should the Business Practitioner set?

✖ isChecketOut

✔️ Expires

41 // An IT company gets a new project. The sponsors want to know whether everything they are asking for can be completed within their time constraints and budget. What should the Business Practitioner recommend to meet these requirements?

✖ Use AEM Projects

✔️ Onboard trained technical resources

42 // A customer is preparing for holiday sales and needs to update the live site at exactly midnight local time, without any manual intervention. All changes are already done on the author instance. Which two AEM functionalities should the Business Practitioner recommend? (Choose two)

✔️ Manage Publication

✔️ Launches

43 // A customer wants DAM users to have the ability to share a group of assets bases on search criteria with other DAM users. What should the client use?

✖ Smart Collections

✔️ bghtbox Collections

❗ "Brightcove Collections" (often abbreviated as "bghtbox Collections") refers to a feature that allows integration between AEM and Brightcove, a popular online video hosting platform. Brightcove Collections facilitate the management and embedding of videos hosted on Brightcove within AEM-powered websites.
Smart Collections do not inherently support the sharing of assets among DAM users based on search criteria, as requested in the scenario. Smart Collections are more about automating the process of asset organization and grouping based on specific parameters, rather than facilitating asset sharing among users.

44 // A customer wants different teams to collaborate with each other by connecting Adobe Experience Manager (AEM) Assets with Creative Cloud desktop apps: InDesign. Photoshop and Illustrator. Which AEM feature can be used for this requirement?

✖ Dynamic Media

✔️ Adobe Asset Link

❗ 

45 // A customer has a business requirement to trigger a specific workflow in author whenever there is a change to a particular type of node in AEM. Which functionality should the Business Practitioner recommend?

✖ Launches

✔️ Workflow launchers

❗ 

46 // A company wants to develop a website that contains interactive and multimedia experiences that will work across all devices, the Business Practitioner needs to make sure rich media assets are used without adding too much workload to asset managers. How should the Business Practitioner meet this requirement?

✖ Use Dynamic Media image presets

✔️ Use Dynamic Media Smart crop

❗ 

47 // Which additional AEM Assets features become available after integration with Dynamic Media? (Choose two.)

✔️ Smart Cropping

✔️ Generation of static renditions

48 // A company requests a new banner component that should conform to company design standards. Details on what the authoring dialog experience should be have not been provided. Which two additional pieces of information should the Business Practitioner clarify for the developer? (Choose two.)

✔️ Content model

✔️ Selectable fields

49 // A Business Practitioner needs to deactivate content that Is published In production. Where should the deactivation workflow be initiated?

✔️ On the author

50 // A customer wants to implement social media pixels directly on AEM templates What should the Business Practitioner recommend?

✖ Add an Adobe Analytics Cloud configuration

✔️ Add an Adobe Target Cloud configuration


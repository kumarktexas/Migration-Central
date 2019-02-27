<div xmlns:db="http://docbook.org/ns/docbook" id="aws-nav" class="aws-nav-header">

<div class="aws-nav-header-left">

<div class="aws-nav-logo">[![Amazon Web Services](images/aws_logo_105x39.png)](http://aws.amazon.com)</div>

</div>

<div id="aws-nav-header-right" class="aws-nav-header-right">

<div class="aws-nav-cta-button-outer">[Sign In to the Console](https://console.aws.amazon.com/console/home)</div>

<div class="aws-nav-popover-trigger" data-dropdown="aws-nav-dropdown-lang"><select id="languageSelection" onchange="SelectLanguage()"><option value="/de_de/patterns-and-practices/latest/migration/First-Time-User_14386499.html">Deutsch</option> <option value="/en_us/patterns-and-practices/latest/migration/First-Time-User_14386499.html" selected="selected">English</option> <option value="/es_es/patterns-and-practices/latest/migration/First-Time-User_14386499.html">Español</option> <option value="/fr_fr/patterns-and-practices/latest/migration/First-Time-User_14386499.html">Français</option> <option value="/it_it/patterns-and-practices/latest/migration/First-Time-User_14386499.html">Italiano</option> <option value="/ja_jp/patterns-and-practices/latest/migration/First-Time-User_14386499.html">日本語</option> <option value="/ko_kr/patterns-and-practices/latest/migration/First-Time-User_14386499.html">한국어</option> <option value="/pt_br/patterns-and-practices/latest/migration/First-Time-User_14386499.html">Português</option> <option value="/zh_cn/patterns-and-practices/latest/migration/First-Time-User_14386499.html">中文 (简体)</option> <option value="/zh_tw/patterns-and-practices/latest/migration/First-Time-User_14386499.html">中文 (繁體)</option></select></div>

[](http://www.amazon.com/dp/B078XCC142 "Open Kindle")[](patterns-and-practices-migration.pdf#First-Time-User_14386499 "Open PDF")</div>

</div>

<div id="content-container">

<div id="left-column">

<div id="left-col-header">

<div xmlns:db="http://docbook.org/ns/docbook" id="left-col-top-content">

<div id="service-name">Proserve Patterns and Practices</div>

<div id="guide-info">Migration Central</div>

</div>

<form id="finegrainedSearch" method="get" onsubmit="return searchFormSubmit(this);" action="/search/doc-search.html">

<div id="search-form"><select id="search-select" name="searchPath"><option value="all">Entire Site</option> <option value="AWSMarketplace">AMIs from AWS Marketplace</option> <option value="amis">AMIs from All Sources</option> <option value="articles">Articles & Tutorials</option> <option value="products_and_info">AWS Product Information</option> <option value="case_studies">Case Studies</option> <option value="customerapps">Customer Apps</option> <option value="documentation">Documentation</option> <option value="documentation-product">Documentation - This Product</option> <option value="documentation-guide" selected="selected">Documentation - This Guide</option> <option value="datasets">Public Data Sets</option> <option value="releasenotes">Release Notes</option> <option value="solution_providers">Partners</option> <option value="code">Sample Code & Libraries</option></select>  
<input id="search-query" name="searchQuery" type="text" placeholder="Search"><input id="search-button" src="images/search-button.png" alt="Go" type="image"></div>

<input type="hidden" name="this_doc_product" id="this_doc_product" value="Proserve Patterns and Practices"><input type="hidden" name="this_doc_guide" id="this_doc_guide" value="Migration Central"><input type="hidden" name="doc_locale" value="en_us"></form>

</div>

</div>

<div id="main-column">

<div id="main">

<div id="main-content">

<div id="main-col-body">

<table summary="Breadcrumbs">

<tbody>

<tr>

<td>

<div class="breadcrumb">[AWS Documentation](/index.html) » [Proserve Patterns and Practices](/patterns-and-practices/index.html) » [Migration Central](index.html) » [Migration Central - Internal : AWS Migration Central - Internal](AWS-Migration-Central---Internal_14385761.html) » <span class="breadcrumb">Migration Central - Internal : First Time User</span></div>

</td>

</tr>

</tbody>

</table>

<div id="SEARegionDisclaimer">This prerelease documentation is confidential and is provided under the terms of your nondisclosure agreement with Amazon Web Services (AWS) or other agreement governing your receipt of AWS confidential information.</div>

# Migration Central - Internal : First Time User

Created by Sindhu, PJ, last modified on Mar 12, 2018

Welcome !

AWS Migration Central is your gateway to everything Migration - Migration Best Practices, tutorials, How-to's, Tools, migration patterns, Tutorials, use cases, escalations for additional support, and a lot more.

There are two easy ways to get started with the toolkit : **Top Navigation Menu** or **Search** (top right corner). Some menus provide second-level navigation options, so if you know what you are looking for you can get to them in one click. If you are unsure you can always start at the top-level menu and drill down for more information - it's that easy.

Let's dive into more details on each Menu item to give you more insights.

Migrations is a good place to start if you are a new user. This section covers the three broad phases under Migration, starting with Assessment:

<div class="orderedlist">

1.  **Assessment** - If you want to figure out where does an organization stand in it's overall readiness for migrating to AWS, you start with assessment. This stage is also called **Migration Readiness and Assessment (MRA)**. It dives into details on how-to conduct assessment, templates/tools to use, and how to summarize the findings for the customer. You can use the output from the assessment to generate SOW deliverables.

2.  **Readiness and Planning** - After you have assessed the readiness (conducted MRA) and signed the SOW, time to move some apps to AWS. This section dives deep into the 8 work streams under **Migration Readiness and Planning (MRP)**. After conducting this phase successfully, you will lay down the foundation for customer to migrate workloads to AWS at scale.

3.  **Migration-at-scale** - After the foundation in Security, Operational Integration, Organizational Changes, Program Management are laid out by migrating a few applications to AWS in a Landing Zone that is well architected and compliant (with customer requirements), it's time to move 1000s of applications using our Migration Factory. Migration-at-scale covers detail on how to use MRP fundamentals to scale to 1000s of applications.

</div>

MRA and work streams within MRP follow the same format to organize content. For each work stream, there are basically 5 pages.

<div class="itemizedlist">

*   **Landing page:** This is the second level navigation from the top-right menu. You will find 8 of them under "Readiness and Planning" under Migrations. This page outlines the different sections for work streams - it's basically a teaser into the detailed topics.

*   **How-to page**: This page dives into how to conduct the work stream. It helps you answer questions like:

    <div class="itemizedlist">

    *   What do I need to begin work? When do I begin work?

    *   What are the tasks I need to carry out? Any sequencing concerns?

    *   What are the dependencies with other work streams?

    </div>

</div>

How-to is divided into three broad areas:

<div class="itemizedlist">

*   <div class="itemizedlist">

    *   **Discovery (of current state)**: What tasks need to be carried out to understand the current state?

    *   **Design (of target state)**: What tasks to complete to understand the design of target state in AWS?

    *   **Build and Validate (EPICs to execute):** What tasks to carry out to get the customer from current to future state.

    </div>

*   **Deliverables**: This page contains documents, templates, and questionnaires that have to be delivered to the customer. Examples include: excel template for calculating TCO, MRP kickoff powerpoint, etc. If you are looking for any document for training customers can be found under References section.

*   **References & Help:** This page contains references in the form of links, case studies, blogs, videos, and anything that can help you ramp up on the domain covered in work stream.

*   **FAQs & Feedback:** This page contains question and answers related to the work stream and three ways for providing feedback to Migration Speciality team.

</div>

**[Click here for more information...](Migrations_14385976.html)**

Tools are required for all phases of migration from assessment to migrations-at-scale. This new section dives into the various tools available under Partner Tools and AWS Tools. This is the place to find what tools to use for which phase, pros and cons of each tool, licensing requirements for partner tools, feedback from colleages, use cases, etc.

**[Click here for more information...](Tools_14386516.html)**

FAQs are available for each section within Migration Central for every phase. However, come here directly if you want to quickly scan all of the questions in one place. You will find three ways to provide feedback at the bottom of the page:

<div class="itemizedlist">

*   By Email : [aws-migration-central@amazon.com](mailto:aws-migration-central@amazon.com)

*   By Form: Included on the page

*   By opening support a ticket in SIM for applicable group:

    <div class="itemizedlist">

    *   Business Case and TCO - [Open Business Case related SIM Ticket](http://tiny.amazon.com/po3gb9gs/BusinessCaseandTCOAnalysis)

    *   Execution and Migration Planning - [Open Business Program Execution related SIM Ticket](http://tiny.amazon.com/jsxw8tc1/ProgramManagementProcess)

    *   Portfolio Discovery & Analysis - [Open Portfolio Discovery related SIM Ticket](https://tiny.amazon.com/b62nwwd0/PortfolioDiscovery)

    *   AWS Landing Zone - [Open Landing Zone related SIM Ticket](https://tiny.amazon.com/1jevjusjx/VirtualDataCenter)

    *   Operational Integration - [Open Operations related SIM Ticket](http://tiny.amazon.com/18jx11e1f/OperationalIntegration)

    *   Security, Risk & Compliance - [Open Security related SIM Ticket](http://tiny.amazon.com/1iesva9i7/SecurityRiskandCompliance)

    *   People, Skills and OCM - [Open People & OCM related SIM Ticket](http://tiny.amazon.com/1j3n1ugpr/PeopleSkillsOCM)

    *   Migration Readiness & Assessment - [Open MRA related SIM Ticket](http://tiny.amazon.com/1gucnykc5/MRA)

    *   Application Migration - [Open App Migration related SIM Ticket](http://tiny.amazon.com/7dslkukb/ApplicationSelectionandMigration)

    *   Migration Patterns - [Open Migration Pattern related SIM Ticket](https://tiny.amazon.com/e8fip1u9/patterns)

    *   Automation/AWS Tools - [Open AWS Tools related SIM Ticket](https://tiny.amazon.com/r6zqbt7i/AWSTools)

    *   Partner Tools - [Open Partner Tools related SIM Ticket](https://tiny.amazon.com/9ar7acdf/partnertools)

    *   For all general issues related to Migration Central that do not fall in the above categories, please [go here](https://tiny.amazon.com/1hs2e8xw7/General)

    </div>

</div>

Feel free to provide comments at the bottom of each page (positive or negative).

However, please use email or form to escalate migration related challenges and opportunities, such as lack of content, update to tooling, training, advance help or for anything else where Migration Speciality can improve.

**[Click here for more information..](FAQs-and-Feedback_14387196.html)**

</div>

<noscript>

<div>

<div>

<div>

<div id="js_error_message">

**Javascript is disabled or is unavailable in your browser.**

To use the AWS Documentation, Javascript must be enabled. Please refer to your browser's Help pages for instructions.

</div>

</div>

</div>

</div>

</noscript>

<div id="main-col-footer">

<div id="doc-conventions">[Document Conventions](/general/latest/gr/docconventions.html)</div>

<div id="next">[« Previous](AWS-Migration-Central---Internal_14385761.html) [Next »](VMware-Cloud-on-AWS_19007021.html)</div>

<div id="copyright-main-footer">© 2019, Amazon Web Services, Inc. or its affiliates. All rights reserved.</div>

</div>

</div>

</div>

</div>

</div>

<div id="cookie-notice">

<div class="cookie-notice-text">We use cookies to provide and improve our services. By using our site, you consent to cookies. [Learn more](http://aws.amazon.com/legal/cookies)</div>

</div>

<div id="footer">

<div id="footer_short_fb" class="hide" title="Feedback">[](https://alpha-docs-aws.amazon.com/forms/aws-doc-feedback?feedback_destination_id=f75427da-646b-4015-aa68-02e1f57746e5&topic_url=http://alpha-docs-aws.amazon.com/en_us/patterns-and-practices/latest/migration/First-Time-User_14386499.html&hidden_guide_name=Migration Central&hidden_api_version=&hidden_file_name=First-Time-User_14386499)</div>

<div id="footer-left">[Terms of Use](http://aws.amazon.com/terms) <span class="awsdocs-footer-text">|</span> [Privacy](http://aws.amazon.com/privacy) <span class="awsdocs-footer-text">|</span> <span class="awsdocs-footer-text">© 2019, Amazon Web Services, Inc. or its affiliates. All rights reserved.</span></div>

<div id="footer-right">

<div id="feedback">

<div id="feedback-message" class="awsdocs-footer-text">Did this page help you?</div>

<div id="feedback-yesno-buttons">[Yes](feedbackyes.html?topic_url=http://alpha-docs-aws.amazon.com/en_us/patterns-and-practices/latest/migration/First-Time-User_14386499.html)[No](feedbackno.html?topic_url=http://alpha-docs-aws.amazon.com/en_us/patterns-and-practices/latest/migration/First-Time-User_14386499.html)</div>

<div id="feedback-feedback-button">[Feedback](https://alpha-docs-aws.amazon.com/forms/aws-doc-feedback?feedback_destination_id=f75427da-646b-4015-aa68-02e1f57746e5&topic_url=http://alpha-docs-aws.amazon.com/en_us/patterns-and-practices/latest/migration/First-Time-User_14386499.html&hidden_guide_name=Migration Central&hidden_api_version=&hidden_file_name=First-Time-User_14386499)</div>

</div>

</div>

</div>
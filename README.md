# OpenCart 2 - Newsman Newsletter Sync
[Newsman](https://www.newsmanapp.com) plugin for OpenCart 2. Sync your OpenCart customers / subscribers to Newsman list / segments.

This is the easiest way to connect your Shop with [Newsman](https://www.newsmanapp.com).
Generate an API KEY in your [Newsman](https://www.newsmanapp.com) account, install this plugin and you will be able to sync your shop customers and newsletter subscribers with Newsman list / segments.

![image](https://raw.githubusercontent.com/Newsman/OpenCart2-Newsman/master/assets/newsmanBr.jpg)

# Installation
Manual installation:
1.  Copy contents of the uploads folder and paste to your opencart root directory
2.	Give priveleges to your user in admin->System->Users->User Groups
3.  Go to admin->Extensions->Modules and then install Newsman Newsletter Sync module
4.  After installation edit the Newsman Newsletter Sync module

# Newsman Remarketing

1. Extensions -> Installer -> Upload newsmanremarketing.ocmod.xml
2. Extensions -> Modifications -> Refresh
3. Extensions -> Analytics -> Newsman Remarketing

Fill in your Remarketing ID from Newsman account. Settings -> Remarketing.
Select enable and save.

# Setup

1. The process is automated, login with Newsman via Oauth and the settings will get automatically filled based on your selection

![image](https://raw.githubusercontent.com/Newsman/OpenCart2-Newsman/master/assets/oauth1.png)
![image](https://raw.githubusercontent.com/Newsman/OpenCart2-Newsman/master/assets/oauth2.png)

2. Fill in your Newsman API KEY and User ID and click connect
![](https://raw.githubusercontent.com/Newsman/OpenCart2-Newsman/master/assets/api-setup-screen-opencart2.png)

3. Choose destination segments for your newsletter subscribers and customer groups
All your groups will be listed and you can select the Newsman Segment to map to.
You can also choose to ignore the group or to upload the group members but include them in any segment.
For the segments to show up in this form, you need to set them up in your Newsman account first.
![](https://raw.githubusercontent.com/Newsman/OpenCart2-Newsman/master/assets/mapping-screen-opencart2.png)

For the automatic synchronization to work, you must setup a webcron to run the url displayed in newsman settings

# Description

With the NewsMAN Plugin for Opencart 2.x, you have the power to streamline your email and SMS marketing efforts. This tool enables you to manage subscription forms, contact lists, newsletters, email campaigns, SMS functionalities, smart automations, detailed analytics, and ensure reliable transactional emails - all accessed through the NewsMAN platform, providing you with enhanced marketing capabilities.

# Subscription Forms & Pop-ups:

* Create: Craft visually engaging subscription forms and pop-ups, like embedded newsletter signups or exit-intent popups, strategically capturing potential leads before they leave. Customize these forms with compelling visuals and user-friendly designs to entice visitors effectively.

* Sync: Ensure forms are consistent across multiple platforms by synchronizing them, regardless of the device used. This maintains a smooth user experience and upholds brand consistency.

* Connect to Automations: Seamlessly integrate subscription forms with automated workflows. This enables the activation of welcome emails or specific responses upon form submissions, enhancing user engagement through automated processes.

# Contact Lists & Segments:

* Auto Import Sync: Automate the import and synchronization of contact lists from different sources such as websites, e-commerce platforms, or marketing/sales software. This streamlines data management, ensuring your contact information remains accurate and updated effortlessly.

* Advanced Segmentation: Utilize demographic or behavioral segmentation techniques to better target specific audience segments. Tailor offers or promotions specific to regions based on users' interests and behaviors, enhancing the relevance of your marketing approaches.

# Marketing Campaigns (Email and SMS):

* Mass Campaigns: Send newsletters or promotional offers to a broad subscriber base with convenience. This keeps your audience engaged with regular updates on fresh products or services.

* Segmented & Personalized: Tailor campaigns to resonate individually with subscribers by personalizing content. Address subscribers by name or suggest products aligned with their preferences or past interactions, ensuring personalized engagement.

* Resend to Unopened: Re-engage subscribers effectively by resending campaigns to those who haven't opened the initial email. Modify content to enhance interaction and expand reach, fostering increased engagement.

* A/B Tests: Improve campaign performance by experimenting with various elements such as subject lines, content formats, or visuals through A/B tests. Identify the most effective strategies to refine your approach.

* Fully Automated: Optimize campaign performance through experimentation with various elements like subject lines, content formats, or visuals to identify the most effective strategies.

# Marketing Automation (Email & SMS):

* E-commerce & Non-E-commerce: Automate personalized product suggestions or follow-up emails based on user behavior, enhancing user engagement and providing customized experiences.

* Cart Abandonment & Product Views: Strategically address cart abandonment or showcase related products to encourage users to finalize their purchase journey, reclaiming potential sales opportunities.

* Order Review & Post-Purchase: Gather post-purchase feedback to bolster relationships and refine products/services based on valuable testimonials, strengthening customer satisfaction.

* Extensive Automation Flows: Develop comprehensive workflows triggered by specific user actions. Guide users through diverse touchpoints in their journey, such as onboarding sequences or re-engagement strategies, ensuring a fluid user experience.

# Ecommerce Remarketing:

* Efficient Targeting: Reconnect with subscribers by sending targeted offers or reminders based on their past interactions, amplifying the effectiveness of re-engagement strategies.

* Custom Flows: Personalize interactions by providing exclusive offers or reminders based on users' behavior or preferences, fostering a sense of exclusivity and engagement.

# SMTP Transactional Email & SMS:

* Transactional Emails: Guarantee the prompt and reliable delivery of critical messages, such as order confirmations or shipping notifications, through SMTP. This ensures users consistently receive important communications without delay.

# Extended Email and SMS Statistics:

* Comprehensive Insights: Gain comprehensive insights into open rates, click-through rates, conversion rates, and overall campaign performance. These detailed analytics empower data-driven decision-making, refining future campaigns and enhancing overall performance.

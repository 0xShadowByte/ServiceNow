# ServiceNow

## Objective

A portal is a ServiceNow user interface (UI), built using the Service Portal framework, which provides an alternative user experience to the standard UI. It is an intuitive way for users to interact with the underlying Now Platform using a minimum number of clicks from any device: desktop, tablet, or smartphone.

## Skills Learned
- Learned how to navigate the Service Portal
- Creating and managing a portal

## Tools Used
- ServiceNow

## Content
- Navigating the Service Portal
- Hands-on Project 1: Creating and testing out the Portal
- Hands-on Project 2: Creating a Page and setting it up as the Active Portal
- Hands-on Project 3: Add Widgets and Set Options
- Hands-on Project 4: Set Options the Widgets
- Hands-on Project 5: Set Portal Homepage

# Navigating the Service Portal

### Steps

*Ref 1: Log in to ServiceNow instance as the admin user to open the portal*

![image](https://github.com/user-attachments/assets/ad3421ef-ac82-498a-8c32-f0ed2f3c0dbf)

*Ref 2: Open the baseline portal*

To open the baseline portal, modify the instance URL by adding /sp to the end. Note: In a common use case, users would automatically be taken to the portal when logging in to ServiceNow; they would not need to type the portal name at the end of the URL.

![image](https://github.com/user-attachments/assets/6813aeec-78f6-48fa-9b70-010f50d5692d)

*Ref 3-4: using the search field to find out information on virus and then click on the link for the Dealing with Spyware and Virus article*

The Dealing with Spyware and Virus article is part of the Knowledge Base. Examine the article's page to see what is on the page besides the article text. For exasmple, can you tell how many times the article has been viewed? Viewed 12 times.

![image](https://github.com/user-attachments/assets/d4098b77-32c8-42a2-925b-4a9cdd26cd53)

![image](https://github.com/user-attachments/assets/1757988f-78e1-412d-be79-e62f01ce8841)

# Hands-on Project 1: Creating and testing out the Portal

### Steps

*Ref 5-6: Create and Configure a Portal*

In the main ServiceNow browser window, use the All menu to open Service Portal > Service Portal Configuration. Then click the New Portal tile on the *Service Portal Configuration* page. 

Configure the new portal with these fields: title: Portal Meum, URL suffic: pm, Homepage: index, KB Home page: kb_view2, 404 page: 404, Catalog home page: sc_home, main menu: SP Header Menu, Theme: Stock - High Contrast. 

Add an icon to the portal. In the *Icon* field, click the Upload an Image button. In the file browser, navigate to the icon.png file you downloaded in the Preparation section of this exercise. Select the icon.png file. Click the Open or OK button. Then click Save button. 

![image](https://github.com/user-attachments/assets/1d5efdb6-c3bd-4d6d-bc4b-ba13cf82e8fb)

![image](https://github.com/user-attachments/assets/50c580eb-d902-462f-8063-1a000ea3dbe2)

*Ref 7: Testing out the Portal Meum*

In a new browser tab or window, open Portal Meum. Examine Portal Meum. It should have the rocket logo in the banner, rocket icon as part of the tab title, the text *Portal Meum* should be in the tab name and the banner and other page elements are blue.

![image](https://github.com/user-attachments/assets/7303b193-d02a-4ccb-a4d1-66c00c100b4a)

# Hands-on Project 2: Creating a Page and setting it up as the Active Portal

### Steps

*Ref 8-10: Creat a Page*

Click the Designer tile on the Service Portal Configuration page. 

Click the Add a new page link

Configure the page with *Page title:* Portal Meum Homepage  and *Page ID:* pm_index then click submit.

![image](https://github.com/user-attachments/assets/9c8dcf4a-c7dc-41e0-9458-b68382c09c33)

![image](https://github.com/user-attachments/assets/f3a8058f-6f4f-4e7c-8d93-e677ad87f4f0)

![image](https://github.com/user-attachments/assets/127c84aa-ee04-4665-846f-1b201e694d71)

*Ref 9-10: Set Portal Meum as the Active Portal*

Examine the Service Portal Designer header to see which portal is active. If Portal Meum (pm) is not the active portal, click on the portal name to select a new portal. Click Portal Meum to select it as the active portal. Example the Service Portal Designer header again to see which portal is active. You should see pm as the active portal. 

![image](https://github.com/user-attachments/assets/77e63feb-84db-4461-9401-8f7d7bc94385)

![image](https://github.com/user-attachments/assets/9b6e4668-d8ad-4da1-820a-1997b0c6265c)

*Ref 11-14: Add Containers and Rows to the Page*

The default page layout includes one container. Add two more containers to the page by dragging a container form the *Layouts* to the page.

Add a row with a single column spanning all 12 grid columns. Drag the 12 layout item from the *Layouts* to the first container.

Add a row with a 3-column, equally sized columns layout to the second. Add a row with a 3-column, unequally sized column layout to the thrid container. (shortcut is to click on the "+" in the container to add the column.

![image](https://github.com/user-attachments/assets/b6e4a459-b46c-4769-add1-5f3becf422fb)

![image](https://github.com/user-attachments/assets/8a511a36-42bd-4a1a-8815-8ae0863636c8)

![image](https://github.com/user-attachments/assets/2f9ec044-c9e5-4fa2-9d06-e9ae6548c07e)

![image](https://github.com/user-attachments/assets/c71cb120-87f2-463d-a98a-1230bc74816f)

# Hands-on Project 3: Add Widgets and Set Options

*Ref 15-16: Add Widgets to the Page*

Add a *Homepage Search* widget to the first container on the page. In the widgets lists, locate the *Homepage Search* widget. Drag the Homepage Search widget to the first conatiner. When the container row turns grey, drop the widget. 

Add widgets to the page by dragging them from the widgets list to the columns. Most of the columns contain a single widge, one of the columns contain two widgets. (Icon Link x3, Simple List, Cool Clock, Report Organization Chart)

![image](https://github.com/user-attachments/assets/c92f8f18-b63c-42c0-952c-db0a8ee98610)

![image](https://github.com/user-attachments/assets/b538dacb-0b44-4447-ab62-91e91da37eb8)

*Ref 17-18: Set the Homepage Search Widget Options*

Click anywhere in the *Homepage Search* widget to select it. Examine the banner to make suer the widget is selected. Click the Edit Options button in the banner *or* in the widget. Configure the *Homepage Widget* options. (*Title:* We are happy to see you here!)

Click save and the *Homepage Search* widget should have the title.

![image](https://github.com/user-attachments/assets/7851d870-d32f-4d22-8f59-8997176502e5)

![image](https://github.com/user-attachments/assets/ad67dd13-1437-4644-84a2-3916b4996c60)

# Hands-on Project 4: Set Options for the Widgets

*Ref 19: Preparation*

In a new browser window or tab, open the baseline portal by adding /sp to the end of your instance URL.

![image](https://github.com/user-attachments/assets/67c2c272-510b-4312-809a-25fa4b1fe547)

*Ref 20: Container Properties*

ServiceNow has created CSS to give *Icon Link* widgets an attractive appearance. Select the second container on the *Portal Meum Homepage* page that contains three *Icon Link* widgets. Click the Edit Options button for the container and configure the container with (*Screen reader title:* Quick Links to order something, access the Knowledge Base, and get help; *Parent class:* homepage-quicklinks) Tip: make sure you're clicking on the column and not the widget.

![image](https://github.com/user-attachments/assets/45db0925-e899-4f20-a5f5-8a2336a43af8)

*Ref 21-22: Configure the Order Something Icon Link Widget*

Click the first (leftmost) Icon Link widget to select it. Click the Edit Options button (on the widget or in the banner). Configure the *Order Something* widget (*Type:* Page, *Page:* sc_home, *Title:* Order Something, *Short Description:* Browse the catalog for services and items avaliable to you, *Bootstrap color:* Primary, *Glyph:* usd, *Template:* Top Icon

![image](https://github.com/user-attachments/assets/ab94cbb4-4c64-4d54-a487-7c8c0e31ffea)

![image](https://github.com/user-attachments/assets/183d3683-dbef-4a61-a4c5-e8db21716829)

*Ref 23-24: Configure the Knowledge Base Icon Link Widget*

Click the second (middle) Icon Link widget to select it. Click the Edit Options button (on the widget or in the banner). Configure the *Knowledge Base* widget (*Type:* KB Category, *KB Category:* Policies, *Page:* kb_category, *Title:* Knowledge Base, *Short description:* Look for answers to your questions about corporate processes and policies, *Bootstrap color:* Primary, *Glyph:* eye, and *Template:* Color Box. Then click save.

![image](https://github.com/user-attachments/assets/93fc3032-71f8-430a-ad03-0d0943a85f66)

![image](https://github.com/user-attachments/assets/df6048df-5627-4026-8b4b-4a3ccb4b922a)

*Ref 25-26: Configure the Get Help Icon Link Widget*

Click the third (right) Icon Link widget to select it. Click the Eidt options button (on the widget or in the banner). Configure the *Get Help* widget (*Type:* Catalog Category, *Catalog category:* Can we help you?, *Page:* sc_category, *Title:* Get Help, *Short description:* Contact the support team for assitance with technical questions, *Bootstrap color:* Danger, *Glyph:* Wrench, and *Template:* Circle Icon.

![image](https://github.com/user-attachments/assets/3d6e26cb-d9fb-4b0c-a9d4-3f0d4946971a)

![image](https://github.com/user-attachments/assets/faec6553-7b23-4c5e-a787-190e016cdec3)

*Ref 27-28: Set Options for the Simple List Widget*

Click the Simple List widget to select it. Click the Edit Options button. Configure the *Simple List* widget to display active *Incident* records opened by the currently logged in user (Table: Incident [incident], Filter: paste in the query you copied in the Preparation section of this Exercise, Display field: Short description, Secondary fields: Number and Updated (after selection, the fields will be listed as number and sys_updated_on), Link to this page: ticket, Show even when empty: Selected (checked), Glyph:
list (fa-list), Maximum entries: 7).

![image](https://github.com/user-attachments/assets/91dd2b61-998d-4e2a-ae76-73ce77585894)

![image](https://github.com/user-attachments/assets/5f306196-bfca-4200-b05a-a2f418b20494)

*Ref 29-20: Configure the Cool Clock Widget*

Click the Cool Clook widget to select it. Click the Edit Options button. Configure the *Cool Clock* widget (*Time Zone:* Leave at the default value of America/Los_Angeles, *Title:* Time at ServiceNow Headquarters in Santa Clara, California, *Second hand color:* #FFA500). Click save.

![image](https://github.com/user-attachments/assets/2c5533e6-7d49-4b13-b94f-471951f94120)

![image](https://github.com/user-attachments/assets/069b2beb-25c8-4b4f-b542-60a6d2af7fd1)

*Ref 31-32: Configure the Report Widget*

Click the Report widget to select it. Click the Edit Options button. Configure the *Report* widget (*Report:* All incidents by Category, *Show title:* Selected (checked)). Click Save.

![image](https://github.com/user-attachments/assets/6f2d27a7-e2fa-41aa-b26b-f70fd65a1cc0)

![image](https://github.com/user-attachments/assets/3fbf850d-3100-4494-84a6-d3be817e07d1)

# Hands-on Project 5: Set Portal Homepage

*Ref 33-35: Set the Portal Homepage*

In the page Designer click the Edit portal properties button. Change the *Homepage* field value to pm_index then click save. Test the new configuration by entering the url https://https://dev242095.service-now.com/pm.

![image](https://github.com/user-attachments/assets/43888530-787c-4bcf-a895-a7a8ade7e6b9)

![image](https://github.com/user-attachments/assets/8d89e4ce-dbd2-4556-973a-6a36aefb9a28)

![image](https://github.com/user-attachments/assets/6b7f66b8-7a2c-497b-890c-6cfde0d4180d)



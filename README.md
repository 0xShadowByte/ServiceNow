# ServiceNow

## Objective

To leverage ServiceNow’s cloud-based automation and workflow management capabilities to enhance IT service delivery, streamline business operations, and improve overall efficiency.

## Skills Learned
- Learned how to navigate the Service Portal
- Creating a portal

## Tools Used
- ServiceNow

## Content
- Navigating the Service Portal
- Hands-on Project 1: Creating and testing out the Portal
- Hands-on Project 2: Creating a Page and setting it up as the Active Portal
- Hands-on Project 3: Add Widgets and Set Options

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

*Ref 15 : Add Widgets to the Page*

Add a *Homepage Search* widget to the first container on the page. In the widgets lists, locate the *Homepage Search* widget. Drag the Homepage Search widget to the first conatiner. When the container row turns grey, drop the widget. 

![image](https://github.com/user-attachments/assets/c92f8f18-b63c-42c0-952c-db0a8ee98610)


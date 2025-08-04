Create a Static site instructions. With live website at the end.

1- Write HTML code on VS code editor. See Example below
Create a Folder in your documents or on your desktop, this is where the HTML, CSS( optional), and image file (optional)

<!-- index.html -->
<!DOCTYPE html>
<html>
  <head><title>This Is My First Azure. Site Created on 8/2/25 by Dan Tierney </title></head>
  <body>
    <h1>Hello from Azure!</h1>
  </body>
    <h2>This is just the beginning of a long journey to the world of azure. I started with AZ-900 training on July 28th 
      2025, and created this static website. and plan on testing within the next month. Amazon AWS will be next after 
      this along with learning Python to better understand how the cloud works. I will be adding to this site weekly entries
      on how thigs are and my progress to gaining the AZ-900 certification.
         </h2>
        <h3> Week 1 - 
           <p>Understanding the different cloud models, SaaS,PaaS,IaaS and On Prem:
           <br>Cloud Models: IaaS vs PaaS vs SaaS - see below:<br>
 <br>SaaS
- <br> - Customer is responsible for:
-  <br>Information and data
-  <br>Devices(Mobile and PC's)
-  <br>Accounts and identies
-  <br>Shared responsibilities:
-  <br>Identity and directory infrastructure -<br>
 <br> - Microsoft's responsibilities:
-  <br>Applicationa
-  <br>Network controls
-  <br>Operating system
-  <br>Physical hosts
-  <br>Physical network
-  <br>Physical datacenter - <br>
 <br>PaaS
- <br> - Customer is responsible for:
-  <br>Information and data
-  <br>Devices(Mobile and PC's)
-  <br>Accounts and identies
- <br>Shared responsiblities:
-  <br>Identity and directory infrastructure
-  <br>Applications
-  <br>Network controls - <br>
<br> - Microsoft's responsibilities:
-  <br>Operating system
-  <br>Physical hosts
-  <br>Physical network
-  <br>Physical datacenter -<br> 
 <br>IaaS
- <br> - Custoner responsibilities
-  <br>Information and data
-  <br>Devices(Mobile and PC's)
-  <br>Accounts and identies
-  <br>Identity and directory infrastructure
-  <br>Applicationa
-  <br>Network controls
-  <br>Operating system -  <br>
 <br> - Microsoft's responsibilites
-  <br>Physical hosts
-  <br>Physical network
-  <br>Physical datacenter - <br>
 <br>On-Prem
- <br> - Custoner responsibilties
-  <br>Information and data
-  <br>Devices(Mobile and PC's)
-  <br>Accounts and identies
-  <br>Identity and directory infrastructure
-  <br>Applicationa
-  <br>Network controls
-  <br>Operating system
-  <br>Physical hosts
-  <br>Physical network - 
</p> </h3> 
    <h4><p>thanks for stopping by. <br>
    Dan Tierney</p></h4>  
</html>

Save file as .HTML file

Step 2-
Sign on to your aure account at Azure.portal.com
  - Create a resource
  - select storage account
  - create a resource group
  - create a storage account name, It has to be golbally unique
  - once created select Data management and select static webiste and select enable it
  - The primary endpoint will be the live link to the static site.
  - under index document name upload ypur HTML file
  - under error document file type in 404.HTML

Step 3-
  -Search for containers on the left tool bar.
  -click on the $web 
  -Click on the upload option on the top selections
  -select the HTML file from the folder we created earlier.
  -Optional- Select the image file and the CSS file

Step 4-

Copy and paste the primary endpoint into the web browser and your static site should appear


Here is mine.
https://movietime.z13.web.core.windows.net/



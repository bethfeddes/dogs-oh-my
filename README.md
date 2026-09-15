# Dogs, Oh My!
A website that allows the user to select a dog breed whose slideshow they'd like to view.  
Hosted using Azure at [this address](https://agreeable-island-082fd9010.5.azurestaticapps.net/)
  
Author: Bethany Feddes  
Project: Lions and Tigers and Bears, Oh My!  
Credits: full credit to Brad Schiff, code follows his ["Dogs, JavaScript & An API" tutorial](https://www.youtube.com/watch?v=AVmGmLFcukM). Claude AI was used for bug fixes and instructions how to run the app locally.

## Steps for Executing the Application  
1. Clone the repository:  
   git clone https://github.com/bethfeddes/dogs-oh-my.git  
   cd dogs-oh-my  
2. Serve the folder locally (recommended, to match how it behaves once deployed):  
&emsp; - Using VS Code: install the "Live Server" extension, right-click index.html, and select "Open with Live Server."  
&emsp; - Using Python: run python -m http.server in the project folder, then visit http://localhost:8000.  
&emsp; - Alternatively, double-click index.html to open it directly — this usually works, but some browsers restrict fetch() requests on file:// pages.  
3. Use the app:  
&emsp; - Select a dog breed from the dropdown menu.  
&emsp; - A slideshow of images for that breed will automatically begin cycling.  

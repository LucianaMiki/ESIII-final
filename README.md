# ENGIII

# 1º Step
Clone the repository to an empty folder. Example: Clone in a folder named "ESIII"

# 2º Step
Download eclipse.
To download eclipse: https://www.eclipse.org/downloads/

# 3º Step
Add project to eclipse
Following our example:
  -Open eclipse
  -Click "File"
  -Click on "Open Projects from File System..."
  -Click on "Directory"
  -Select the "ESIII" folder (created in the 1st step)
  -Select the project when it appears in the largest whiteboard on the screen
  -Click Finish

# 4º Step
Add the server
  -Click "File"
  -Click "New"
  -Click "Other"
  -Click on "Server"
  -Select "Server"
  -Click "Next"
  -Choose the Tomcat you want (if you don't have Tomcat, download it from https://tomcat.apache.org/download-90.cgi)
  -Click "Finish"
 
# 5º Step
Add the project to the server
  -Click on "Window"
  -Click "Show view"
  -Click "Other"
  -Select "Server"
  -Click "Open"
  -When it appears below, right-click on Tomcat
  -Click "Add and Remove"
  -Select the project and change it from "Available" to "Configured", selecting it and clicking "Add"
  -If it doesn't show up:
      -Right-click on the project folder on the left side
      -Click on "Properties"
      -Click on "Project Facets"
      -Tick the boxes "Dynamic Web Module", "Java" and "Javascript"
      -On the right side, click on "Runtime"
      -Tick or Tomcat
      -Click "Apply and Close"
      -Check if it appears now, repeating those steps to add to the server
      

# 6º Step
Turn on the server
  -Right click on Tomcat
  -Click "Start"
  -Go to the Browser and access "http://localhost:8000/ESIIItest/index.jsp"
      -note: you may have to change the port

# Skyobjident
Sky Object Identification

Jupyter notebook  file having model creation and analysis is present under folder Notebooks
Flash app, docker file and other deployment artifcats are present under deploy folder
Download the deploy folder and create image image from folder deploy. Sample is provided below
docker build -t skyident:1.0 .
Create conatiner using following port configuration

docker run -p 5000:3000 docker/skyident:1.0

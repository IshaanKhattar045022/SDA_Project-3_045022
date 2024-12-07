# SDA_Project-3_045022
# Submitted By: Ishaan Khattar, Streaming Data Analytics- Individual Project 


# *Team Blog-in-Docker*

This repository provides a quick and easy way to deploy a team blogging platform using Docker. The platform is based on a pre-configured image that supports seamless content creation and publishing for collaborative blogging.

---

## *Pre-requisites*
1. A system with Docker installed and configured.
2. Basic knowledge of command-line tools.

---

## *Steps*

### *1. Pull the Docker Image*

Run the following command to pull the pre-built Docker image for the blogging platform:
bash

docker pull pysatellite/dj-twenty-six.github.io:bmt


### *2. Start the Team Blog Instance*

Use the following command to run the blog container:
bash

docker run -dit --name team-blog -p 9999:80 pysatellite/dj-twenty-six.github.io:1.4.1


---

## *Access the Blog*

Once the container is running, you can access the team blog in your web browser at:

http://localhost:9999


---

## *Video Walkthrough*

For a quick demonstration of the setup process, watch the video:  
(#)

---

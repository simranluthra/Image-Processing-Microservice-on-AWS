# Full Stack Apps on AWS Project

You have been hired as a software engineer to develop an application that will help the FBI find missing people.  The application will upload images to the FBI cloud database hosted in AWS. This will allow the FBI to run facial recognition software on the images to detect a match. You will be developing a NodeJS server and deploying it on AWS Elastic Beanstalk. 
You will build upon the application we've developed during the lessons in this course. You'll complete a REST API endpoint in a backend service that processes incoming image URLs.

## Getting Started

You can clone this repo to run the project locally, or navigate to the workspace in the Udacity course.

## Project Instructions

Follow below steps to run the project:
- npm i
- npm run dev

## Testing

Successful URL responses should have a 200 code. Ensure that you include error codes for the scenario that someone uploads something other than an image and for other common errors.

## License

[License](LICENSE.txt)

Github link - https://github.com/simranluthra/Image-Processing-Microservice-on-AWS

Added 3 different examples of working elastic beanstalk URL. You need to find a image from google and copy the image address.

Working elastic beanstalk URL - http://udacityebimagefilter-env.eba-p9wmzkku.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://miro.medium.com/max/1400/1*mk1-6aYaf_Bes1E3Imhc0A.jpeg

http://udacityebimagefilter-env.eba-p9wmzkku.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://images.unsplash.com/photo-1503023345310-bd7c1de61c7d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8aHVtYW58ZW58MHx8MHx8&w=1000&q=80

http://udacityebimagefilter-env.eba-p9wmzkku.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWMt4OUo8-HaLhyqqjC7MsKYQ5fUhd2txHE7VCLBnDYe5OPiRZCNwofblM2jdey8AXyWQ&usqp=CAU
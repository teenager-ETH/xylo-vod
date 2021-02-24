

In this workshop we will build the video on demand streaming platform that allows you to upload, process, and serve videos to authenticated users.

The workshop is split into three primary sections with a collection of optional extensions:

**Backend Deployment with Amplify CLI** - Use the Amplify CLI to deploy the API, Authentication, and Video Streaming infrastructure.

**Web Client Admin View** - Build a web application to add videos and associate basic metadata.

**Web Client User View** - Stream videos to users who have signed into the service.

**Optional Extensions** - An optional section containing a collection of tutorials to extend the application functionality.

### Installing Packages and Configuring Environment

1. Clone this repository 
1. We will now be installing the development tools using the Node Package Manager(NPM)
1. Install the AWS Amplify CLI using this command.
    * `npm install -g @aws-amplify/cli`
1. Finally, install Amplify Video, a custom AWS Amplify CLI plugin for creating our video resource, by running this command. 
    * `npm install -g amplify-category-video`


[Click Here to begin implementing the back end!](./documentation/Backend.md)

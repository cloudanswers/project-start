<project name>
==============

<insert continuous integration build status image here, like from codeship>

<describe what this org or managed package is focused on>


Development 
------------

1. Each developer should have their own <devorg|sandbox>
1. Create new project in mavensmate
1. Open terminal, cd to project folder
1. `git clone -f <this repo> . # you're on master at this point`
1. Populate variables in the .env file
1. Deploy to your dev org with `foreman run ant deploy`
1. Create a branch in git to track your feature/fix
1. Commit and push often to your branch, the build system will automatically notify you of problems
1. Open a pull request against master when it's ready to review
1. Include screenshots or video to help people understand the user experience

License
-------

<confidential|mit|bsd|gpl>
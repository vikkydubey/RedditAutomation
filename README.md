# Introduction 
This is a Reddit web automation framework created using Google Puppteer. The language used in this is Javascript and its a node based project.

# Getting Started
Installation and Setup
1.	Make sure node js is installed on the client where you intend to run this test suite. If node is not installed then please download and run the setup from https://nodejs.org/en/download/ 
2.	Software dependencies : Node js (internally npm.)
3.	Once Installation of node is done then please download the projext zip from https://drive.google.com/file/d/1nx6TtUjyo-rAV-xfuoMTqFPFJwP9dg3D/view?usp=sharing  and unzip on a local directory
4.	Go to Root of the project and open command prompt at root viz: \RedditAutomation
5.  On Command Prompt window type "npm run test" (without quotes) to run the test cases
6.  There are 5 test cases - List all subscribed subreddits, Search and Open Private Subreddit, Create Post, Create post and Comment on it and upvote and downvote a post.
7.  At the end of execution there will be one HTML Report generated at \RedditAutomation\html-report\report.html
8.  ALso for every test case action there are screenshot captured and grouped together based on test cases folder. This can be found at ..\RedditAutomation\Report\Screenshot

# Build and Test
Since this is a node based project it doesnt require to build this.
Also i have intentialnally added node module folder so that there is no dependency for versions and packages.
Unzip the project and simply fire "npm run test" command from root directory using command prompt.

# Salient Feature Implemented
1. Page object model architecture using Javascript.
2. Every action has capability to take screenshot without any direct call.
3. Intutuive HTML Report as an output.
4. Detailed error capturing inside HTML report to point out excat issue with test cases/scenario.


# Reach me
 Please feel free to contact me on Email: vikkydubey@gmail.com 

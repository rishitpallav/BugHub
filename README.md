# BugHub

BugHub is a project aimed at observing data analytics from various platforms to improve applications and efficiency.

## Overview

BugHub provides a comprehensive solution for collecting and analyzing data from different platforms. By leveraging advanced data analytics techniques, BugHub helps developers gain valuable insights into their applications and identify areas for improvement.

## Key Features

- Data Collection: BugHub seamlessly integrates with popular platforms, allowing developers to gather data from multiple sources.
- Platforms: Currently integrated with StackOverflow and GitHub to gather several information such as Tags, Questions, Issues, Commits with respect to date.
- Performance Optimization: By analyzing the collected data, BugHub helps developers identify bottlenecks and optimize their applications for better performance.

## Getting Started

To get started with BugHub, follow these steps:

1. Clone the repository: `git clone https://github.com/rishitpallav/BugHub.git`
2. Get a GitHub Personal Access Token and StackApps Token.
3. Replace your GitHub Personal Access token with the one present in the application. The PAT in code won't work.
4. Run the application using Python Notebook application of your choice.

## Steps to get GitHub Personal Access Token

1. Go to the GitHub website and sign in to your account.
2. Click on your profile picture in the top-right corner of the page and select "Settings" from the dropdown menu.
3. In the left sidebar, click on "Developer settings".
4. In the left sidebar, click on "Personal access tokens".
5. Click on the "Generate new token" button.
6. Give your token a descriptive name in the "Note" field.
7. Select the desired scopes for your token. These scopes determine the permissions granted to the token.
8. Click on the "Generate token" button.
9. Copy the generated token and securely store it. Note that you won't be able to see the token again once you leave the page.

## Steps to get StackApps Token

1. Go to the Stack Apps website and sign in to your account.
2. Click on "Apps" in the top navigation bar.
3. Click on "Register Your Application".
4. Fill in the required details such as "Application Name", "Description", "OAuth Domain", and "Application Website".
5. Click on "Register Your Application".
6. After registration, you will be provided with a "Client Id", "Client Secret", and "Key".
7. To get an access token, you need to make an OAuth request. This can be done by navigating to a URL in the following format: `https://stackoverflow.com/oauth/dialog?client_id=YOUR_CLIENT_ID&scope=SCOPE&redirect_uri=REDIRECT_URI`. Replace `YOUR_CLIENT_ID` with your actual client id, `SCOPE` with the required permissions (e.g., `no_expiry,write_access`), and `REDIRECT_URI` with the redirect URI you specified during registration.
8. After authorizing the application, you will be redirected to the specified redirect URI with an access token in the URL.

Remember to keep your token secure and avoid sharing it with others.

## Contributing

I welcome contributions from the community! Please let me know more ideas on what can be implemented.

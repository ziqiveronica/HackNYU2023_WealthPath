# HackNYU2023_WealthPath

## Project Name:
WealthPath

## Inspiration
The inspiration behind WealthPath comes from the need to empower individuals with the tools and knowledge to take control of their financial future. We believe that everyone deserves to have access to financial literacy resources, regardless of their socioeconomic background. Through WealthPath, we aim to break down barriers to financial inclusion and make financial literacy accessible to all.

## What it does
WealthPath is a financial literacy platform that aims to empower Gen Z to make informed financial decisions and take control of their financial future. It provides a range of resources, including interactive educational tools, a community forum, and access to financial advisors.

## How we built it
We built WealthPath as a web-based platform using modern web development technologies, including React and Node.js. We incorporated various financial literacy resources, including videos, articles, and interactive tools, to provide users with a comprehensive understanding of personal finance. Additionally, we integrated blockchain technology to provide users with a secure and transparent way to manage their financial transactions.

## Challenges we ran into
One of the main challenges we faced was ensuring the platform was user-friendly and accessible to individuals with varying levels of technical knowledge. We also faced challenges in sourcing and organizing financial literacy resources in a way that was comprehensive and easy to understand. Additionally, incorporating blockchain technology added an extra layer of complexity to the project, requiring us to learn and integrate new technologies effectively.

## Accomplishments that we're proud of
Raising awareness about the importance of financial literacy and helping to reduce the racial wealth gap through the use of innovative technology like blockchain.

## What we learned
Through this project, we learned about the importance of financial literacy and how it can impact one's financial well-being. We also learned about the challenges faced by individuals who are unbanked or underbanked and how financial technology can play a role in improving financial services for these individuals. Additionally, we learned about blockchain technology and its potential to address issues of wealth inequality.

## What's next for WealthPath
Integration with financial institutions: In order to make the app more useful for users, we plan to work on integrating WealthPath with various financial institutions, such as banks, investment firms, and credit unions. This will enable users to easily connect their accounts and get a holistic view of their finances.

**Here are some features we are planning to implement using Matlab, Twilio, Velo, and Hedera for our WealthPath project :**

**I. Matlab:** We can use Matlab to develop and implement financial models that help users make informed investment decisions. For example, we can use machine learning algorithms to analyze market trends and provide personalized investment recommendations to users.

**II. Twilio:** We can integrate Twilio's SMS API to send users personalized financial alerts, such as updates on their investment portfolio performance, reminders to pay bills, or notifications of suspicious account activity.

**III. Velo:** We can use Velo to develop a mobile application version of WealthPath, making it even more accessible to users on-the-go. We can also use Velo's database integration capabilities to securely store user data and ensure that their personal financial information is protected.

**IV. Hedera:** We can use Hedera's blockchain technology to create a decentralized financial marketplace where users can securely exchange assets, such as cryptocurrency or non-fungible tokens (NFTs), without intermediaries. This could potentially expand the financial services available to users and promote financial inclusion.

These are just a few examples of how we can leverage the technologies provided by MLH sponsors to enhance WealthPath and provide more value to our users.


**The main Java codes for the basic features for WealthPath are included in a seperated zip package**

**Here is some sample code that we are planning to run in the matlab for our project WealthPath for analyzing financial data:**

% Load financial data from a CSV file
data = readtable('financial_data.csv');

% Compute the mean return over a given period
mean_return = mean(data.Return);

% Compute the standard deviation of returns over a given period
std_dev = std(data.Return);

% Compute the Sharpe ratio
risk_free_rate = 0.02;
sharpe_ratio = (mean_return - risk_free_rate) / std_dev;

% Visualize the data using a histogram
histogram(data.Return, 'Normalization', 'pdf');
title('Distribution of Returns');
xlabel('Returns');
ylabel('Probability Density');

% Save the Sharpe ratio to a text file
fid = fopen('sharpe_ratio.txt', 'wt');
fprintf(fid, 'Sharpe Ratio: %.2f\n', sharpe_ratio);
fclose(fid);



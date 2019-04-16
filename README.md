# build_deforestationDash_DS1

Proposal

- What problem does your app solve?

The Deforestation Dashboard is an awareness platform where users gain insights into how the world’s forests are changing.
	
- Be as specific as possible; how does your app solve the problem?

By presenting accurate, historical data, The Deforestation Dashboard allows users to view the decline or increase in forest cover throughout the world. By presenting the data in a historical and geographical context we aim to raise personalized awareness about the planet’s deforestation.

- What is the mission statement?

“To educate and inspire through accurate and current information .”
Features

- What features are required for your minimum viable product?

1. Choropleth maps that show forest cover by country over time
2. An interactive component that allows users to select a country and get more detailed information
3. Create a model that predicts future forest cover based upon historical data"
	
- What features may you wish to put in a future release?

1. Create a ""tutorial"" about forest loss and its effects on geosystems
2. Include governmental changes by country in the time series data and look for connections

- What do the top 3 similar apps do for their users?
Frameworks - Libraries

- What 3rd party frameworks/libraries are you considering using?

ReactJS, Redux, Redux-Thunk, Axios, React-Router, Styled-Components, Plotly, LESS and/or SASS

- Do APIs require you to contact its maintainer to gain access?  no
- Are you required to pay to use the API?  no
For Data Scientists


- Describe the Established data source with at least rough data able to be provided on day 1. 

https://github.com/manjulamishra/Deforestation

- You can gather information about the data set you’ll be working with from the project description. Be sure to collaborate with your PM, and your Backend Architect to chat about the resources you have.

We will create a backend server to import data from multiple resources, analyze all inputs, and create a model that predicts future forest cover based upon historical data.

- Write a description for what the DS problem is (what uncertainty/prediction are we trying to do here? Sentiment analysis? Why is this a useful solution to a problem?)

We are considering using time series analysis that predicts future values of forest cover based on previously observed values.

- A target (e.g. JSON format or such) for output that DS students can deliver to web/other students for them to ingest and use in the app

The output will be in JSON format

Target Audience

- Who is your target audience? Be specific.

	Anyone interested in how the forests of the world are changing with time!  As well as prospective employers that want to see some cool work done by Lambda students!

- What feedback have you gotten from potential users?

	Having an intuitive interface to view and navigate well representative graphs/plots built off solid data will make this app stand out.

- Have you validated the problem and your solution with your target audience? How?

Research

- Research thoroughly before writing a single line of code. Solidify the features of your app conceptually before implementation. Spend the weekend researching so you can hit the ground running on Monday.
Prototype Key Feature(s)

- This is the “bread and butter” of the app, this is what makes your app yours. Calculate how long it takes to implement these features and triple the time estimated. That way you’ll have plenty of time to finish. It is preferred to drop features and spend more time working on your MVP features if needed.

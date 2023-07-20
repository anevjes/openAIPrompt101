# openAIPrompt101
Open AI Sample prompts and challenges

## Challenge 1

Classify Microsoft, Rio Tinto, BHP, Atlassian and Telstra into their verticals. 
Write the answer as COMPANY#INDUSTRY. Do not write it as an ordered list, but write a new line for each. 
Also add the yearly revenue for each company. Write the answer as COMPANY#INDUSTRY#REVENUE. Do not write it as a ordered list, but write a new line for each.


## Challenge 2


Revenue increased $7.5 billion or 16%. Commercial products and cloud services revenue increased $4.0 billion or 13%. O365 Commercial revenue grew 22% driven by seat growth of 17% and higher revenue per user. Office Consumer products and cloud services revenue increased $474 million or 10% driven by Consumer subscription revenue, on a strong prior year comparable that benefited from transactional strength in Japan. Gross margin increased $6.5 billion or 18% driven by the change in estimated useful lives of our server and network equipment. 
Our competitors range in size from diversified global companies with significant research and development resources to small, specialized firms whose narrower product lines may let them be more effective in deploying technical, marketing, and financial resources. Barriers to entry in many of our businesses are low and many of the areas in which we compete evolve rapidly with changing and disruptive technologies, shifting user needs, and frequent introductions of new products and services. Our ability to remain competitive depends on our success in making innovative products, devices, and services that appeal to businesses and consumers.

- Your goal is to summarise key financial information, and various risk factors.

- Sort the risks based on level of potential impact.

- Once you have the summary produce a tabular view.

## Challenge 3

Phone conversation: Hi I just had a car accident and wanted to report it. OK, I hope you're alright, what happened? I was driving on the I-18 and I hit another car. Are you OK? Yeah, I'm just a little shaken up. That's understandable. Can you give me your full name? Sure, it's Sarah standl. Do you know what caused the accident? I think I might have hit a pothole. OK, where did the accident take place? On the I-18 freeway. Was anyone else injured? I don't think so. But I'm not sure. OK, well we'll need to do an investigation. Can you give me the other drivers information? Sure, his name is John Radley. And your insurance number. OK. Give me a minute. OK, it's 546452. OK, what type of damages has the car? Headlights are broken and the airbags went off. Are you going to be able to drive it? I don't know. I'm going to have to have it towed. Well, we'll need to get it inspected. I'll go ahead and start the claim and we'll get everything sorted out. Thank you. 


- Extract information from above conversation and summarise it into a JSON file with following fields:
reason, cause, driver_names, insurance_number, location, damages, summary


## Challenge 4
Build a web api in c# language. API needs to return minerals mined by Rio Tinto. 
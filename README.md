## Inspiration

People often enjoy vacationing to relaxation havens in order to take a break from their daily life and enjoy themselves. But with tickets to popular relaxation places that cost as much as 2000 dollars, it's hard to find your perfect vacation. So I created the Alexa skill cheap flights skill, that allows users to find cheap flights to their favorite places.

## What it does

After you tell Alexa to use the cheap flights skill, you simply tell Alexa to fly from one airport to another (for example "fly from ORD to ATL"). Then Alexa would tell you about the cost, airline, and dates of the three cheapest flights. Alternatively, you can tell your origin, destination and date of your flight to get the information of the three cheapest flights.

## How I built it

I used the Amazon Alexa console to create all the utterance and intents of the skill (the phrases the user would say so the backend could figure out the origin, destination, and possibly date of the trip). I built the code for the backend on VS Code, using Axios to make requests to the Sky Scanner Api in order to get information about the cheapest flights. Then, I parsed that information and returned JSON containing the information back to Alexa to say it. The code was deployed to AWS Lambda in order to make the application serverless and scalable.

## Challenges I ran into

This was the first Alexa skill I created, so I had lots of difficulty setting the backend up. Especially, since I had to bundle npm packages like Axios with the code and I had to deploy the code to the lambda every time I had to test it.

## Accomplishments that I'm proud of

I created my first Alexa skill, so future Alexa skills would be much easier to create given that I know have the experience! So, I'm really looking forward to making more Alexa skills that can help others.

## What I learned

I learned how to create lambdas compatible with Alexa skills. This will be very helpful for making future Alexa skills.

## What's next for Cheap Flights

I plan to add more features and make the skill public so that it will be accessible to everyone and help them with their flights.

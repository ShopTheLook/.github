# The Stylist as a Service
Ever found a t-shirt you liked but couldn't find it anywhere? Do you struggle deciding what to wear when going out? ShopTheLook will be your savior in these situations. Thanks to our AI-powered assistant, you can search, discover, and even try on clothes all from the palm of your hand. Just open WhatsApp and start chatting. Add it to your group chat, and you'll always know what to wear!
## What it does
When you send an image of a clothing piece to the chat, the assistant searches for similar items and presents them to you with a big picture, a brief description, a price tag, and a link where you can purchase it. Moreover, if you don't know what you're looking for, you can ask for recommendations given your style and use case. Lastly, if you're not sure how a certain piece of clothing will fit you, there's the option of using our virtual try-on. See how you would look with those clothes on, from the comfort of your own home.
## How we built it
The user interface is based on a WhatsApp chat that receives message events and forwards them to the backend. There, they're processed by an LLM, and using _Inditex Tech_'s API, we obtain products that adjust to the given requirements. These results are then sent to the chat, where they are presented to the user in an intuitive manner.
## Challenges we ran into
All the process was a constant uphill battle. The unorthodox user interface created some unique constraints when using the provided APIs, but using novel technologies, we were able to overcome them. The use of an advanced AI for the virtual try-on feature further complicated the backend design.
## Accomplishments that we're proud of
Despite all the challenges stated previously, we managed to deliver a product that exceeded our own expectations, and we are very proud of it. Our unique frontend made us have to search for other solutions when using _Inditex Tech_'s API, but the solution we reached left us very satisfied.
## What we learned
The two less experienced first-year computer science students learned the basics of backend development and API interaction. In addition, the scope of our solution required us to branch out into new fields such as AI, cloud services, and web scraping.
## What's next for ShopTheLook
The future of ShopTheLook looks bright, with ideas of taking the interaction system to the next level.

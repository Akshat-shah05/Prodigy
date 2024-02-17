Heyy, I'm working on getting it deployed. Going to be available to use very very soon. Stay Tuned 👀
Update: I have run out of credits for the OpenAI Api, not sure if I'm going to spend the money to get more credits

# Prodigy: 🎵🌟 All Your AI Generation Needs Packed into one SaaS Platform 🎨🔥

<img width="1136" alt="Prodigy" src="https://github.com/Akshat-shah05/Prodigy/assets/133422818/74d251dc-06aa-4e24-9602-010e0d45dd57">
<img width="1136" alt="Codegen" src="https://github.com/Akshat-shah05/Prodigy/codegen.png">

## Inspiration 💡💭
The inspiration for this project was really just wanting an all-in-one, easy-to-use tool to handle every AI generation need I'd ever have. I found it pretty time-consuming to have to use different AI platforms each for their own specific purpose. I'm a programmer, and the best way to solve this problem was simply to code up my own solution. Hence, Prodigy was born, an application leveraging OpenAI and ReplicateAI to package all of my generative AI needs into one beautifully made platform. 

## Features ⚙️
- Authentication with 5+ social logins, handled with Clerk
- Free and Pro tier options, with free trial and payment settings handled seamlessly with the Stripe API integration
- 5 different generative models: Text, Music, Video, Image, and even Code!! (from OpenAI and ReplicateAI)
- Can download anything generated directly to your laptop
- Comes with an AI Chatbot helpline to handle customer service
- Saves user data to a MySQL database, powered by Prisma

## Technologies 💻🔐
- Next.js / React
- MySQL / Prisma
- Tailwind + ShadCN
- Clerk Auth
- Stripe (payment handling)

## Challenges I ran into 💪🤔
- Reading through loads of documentation to set up my first NextJS + ShadCN application
- Figuring out how to use Prisma (it was my first time using an ORM)
- Learning how to work with ShadCN properly as its not the same as other component libraries I've used such as ChakraUI (it isn't in the node modules, rather you install actual components in @/components/ui
- Used the Stripe API for the first time so I had to watch a few videos on getting it set up correctly
- Though authentication would be hard, but clerk is ridiculously easy to use, 1000% would recommend, literally took no effort.
  - Just put the key in the ENV, set the routes correct (with folder structure), and you're good to go
- Had a few connection issues with MySQL --> ended up being somethign I needed to change in .zshsrc, thanks stack overflow.
- Figuring out some of the typescript nuances was pretty difficult since this was basically my first time working on a large scale Next + Typescript application!

## What I learned 🧠
- This project was full of learning, and a lot of firsts
- I learned more about setting up routes and folder structures in Next (I usually use react only with react router - one of my first times working with next after a long while)
- First time working with Stripe, Clerk, ShadCN, or Prisma, so those were all amazing learning experiences
- Improved significantly in my API design skills

## Next steps for this project 📈
- Implementing more plans for usage
- Adding more generative models
- Maybe creating an actual application version of this natively (on mobile with react native or flutter)
- Getting it all up and deployed so people can use it


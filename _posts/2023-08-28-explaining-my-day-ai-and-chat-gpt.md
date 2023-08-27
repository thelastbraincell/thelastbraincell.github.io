---
layout: post
title:  "Explaining my Dad AI and Chat-GPT"
date:   2023-08-28T01:00:00+05:30
author: Abhinav Jain
categories: Blog
tags:	Technology AI
cover:  "/assets/ai-xkcd-banner.webp"
---

*"Are you a millennial or younger who interacts with AI daily? Do you have parents who try hard to understand AI and what it does but fail to understand fully? Do you get dispirited because they are unable to understand AI despite your best explanations over calls? Well, look no further! We've done the hard work for you and have gathered all the AI knowledge that your parents can digest in a single reading. From the basics of artificial intelligence, and its history to the present, top-notch models like Chat-GPT and Midjourney, we have it all covered."*

Before I talk about AI, I would like to talk a bit about my dad. Born around the time of the Sino-Indian war, my father comes from a middle-class family that survived comfortably in license-raj India but didn't have a lot of imported luxuries. He didn't really experience the revolution of the first Macintosh in 1976, in fact, the telecom revolution itself came to India around the mid-1980s. Given the history of India concerning the contemporary world, it is fair to say we leap-frogged on a lot of technology. My dad told me about technology in his youth like this

*"Back in the 80s, people used to laugh at Rajiv Gandhi because he used to say that one day people will be able to see things around the world using a television but he was right. I don't think you remember but we had an aluminium antenna which was used for catching TV signals. Every evening people would shout from their terrace saying 'Signal aaya kya?' (Is the TV receiving the signal properly? while adjusting the antenna.)"*

Actually, I do remember that antenna, we had it until a couple of years before I was born. And like every self-respecting Indian household, it stuck around for at least another decade before we switched over to dish receivers.

It's quite interesting to think about the technologies we jumped through without experiencing. My parents' generation never actually spent a lot of time with pagers, they didn't get to spend time with TV digital video recorders, and they didn't even spend a lot of time with actual computer programming. My dad's experience with computers was using docs, spreadsheets, some portals and printing; all of which he worked with on his office computer. It's not to say that everybody in my parent's generation had the same experience. I am sure many might have had different experiences with technology and software depending on who they were, what they studied, and where they were located. After all, India's IT giant Infosys was founded around the same time when my dad was in his youth. However, for my father and numerous individuals across India residing in non-metropolitan areas and localities, the reality is skipping over multiple generations of technology.

So this brings us to the present. My dad knows that I work as a software engineer. He understands that I write code on a dark screen and get frustrated on my laptop every 30 minutes or so. But AI: Well, that's a different league.

AI or Artificial Intelligence is formally defined as the capability of machines to perform tasks independently without human intervention. Informally, it is the process of making rocks do things without explicit commands. Starting from the times we call myths, AI was imagined in various forms that mostly related to the process of task automation. Hephaestus - The Greek god of craftsmen, is said to have created a machine that would circle the island of Crete three times a day to protect the Phoenician princess Europa from her kidnappers. In the more modern version, AI has been at the center of attention for computer scientists looking to solve the problem "What if we could do even less work than we do right now?". Poor jokes aside, the history of AI is quite fuzzy. The field itself is more interdisciplinary than it seems. It is a gargantuan, multi-headed beast: Imagined and theorised by philosophers, inspired by psychology and neurology, instrumented by mathematicians and computer scientists and brought to life by engineers. To be clear when I say AI, I mostly refer to computer algorithms that can perform tasks on their own without the need for explicit commands of their creator. This special subset of algorithms is called Machine Learning or ML but is used interchangeably with AI as most of the applications of AI today are done using machine learning techniques.

Having our definition of AI etched in Silicon, if I have to mark an event for its history, I would pick the introduction of perceptron in 1958 by Cornell University psychologist Frank Rosenblatt. The perceptron was a basic simulation of neurons in our brains. It, together with a lot of mathematics and computing became the basis of most AI products that we see today. The perceptron was designed to "see" a 20x20 pixel image and distinguish between images. To do this, the perceptron was trained on a set of images associated with some of its constituent properties, just like we teach a young child what an apple is and what a banana is.

Coming from these humble beginnings AI has now taken a role in many aspects of our life. Don't believe it? Let me list down some ways where AI has already become an integral part of life as we know it:

1. In your mail: Remember the spam folder that automatically catches all the Nigerian Prince's emails? Or those fake account-blocked emails? To keep you protected from spam and scams AI algorithms called a classifier are used which sorts emails using their subject lines, the sender address, phrases within the body of the email and even activity tracking of the sender.


2. In your everpresent (but just out of sight) assistant: "Alexa, tell me the weather forecast for today" - Yes, Alexa and all other assistants are also AI programs. They use what is called Natural Language Processing or NLP. These AI programs of this category undergo extensive training in numerous instances of speech recognition and speech-to-text conversions. As a result, they acquire the capacity to engage in conversations and perform enjoyable tasks like sharing short jokes and composing poems.


3. In the editing of this blog: Did you use Grammarly? The AI writing assistant can give word suggestions, improve grammar in your writing and even help you with writing in a specific tone. NLP is one of the things used here.


4. In your traffic tickets: Exhausted from constantly violating traffic regulations and incurring fines? Point your finger at Image Recognition AI for this predicament. With the capability to decipher text contained within images and discriminate between different images, these technologies directly follow in the footsteps of perceptrons.


5. In your fake news: Enjoyed watching your least favourite politician apologising for something that they never apologised for? Bad news, it was an AI. Generative AI specifically. These can learn to mimic the real world and create things out of thin air with their own "imagination". From images and sounds, all the way to 3D animations and simulations.


Of these examples (and others that haven’t been mentioned here), I have tangled more with generative AI. In my thesis project for my master's degree, I worked on generative AI. My project involved creating material structure images that did not exist before. This was done by having two AI agents. The first agent, aptly named the generator would create an image and show it to the second agent called the discriminator. The discriminator would also "look" at real-world images and use them as a benchmark to mark the fake images created by the generator. Thus, the generator would learn to best dupe the discriminator all while creating better images that match real-world creations. In my case, these images would be of material structures that could then be tested in simulators for their physical properties. Material structures with superior properties can then be picked for synthesis and real-world applications. Thus my work could speed up the process of research by many folds because creating new structures was just at the click of a button.

However, my project involving generative AI isn't presently ubiquitous for all. It is Chat-GPT. The AI that can write pages of text with short, structured prompts. The AI that can solve math problems. The AI that can give you business ideas, code snippets, and recipes. The AI that elevates the humble Google search. The AI that... I think I've given enough "The AI" examples now. What is Chat-GPT though? In simple words, Chat-GPT is just another generative AI. This model is a part of a class of models called Large Language Models. The kind that learns and then reproduces text that it "created" based on the prompt provided to it. The company behind the AI - OpenAI has apparently fed the entire internet as the data to the Chat-GPT model for its training before releasing it to the public. This is not even the first model of Open-AI in this regard, the most famous model is version 3.5 of Chat-GPT. There is Chat-GPT 3 which is old and not so great and then there is Chat-GPT 4 which is pay-to-use and superior to the famous free-to-use Chat-GPT 3.5. Chat-GPT is also not the only such AI in town, there are several other competitors as well, which have adapted the GPT algorithms for other purposes. Bard from Google comes to my mind at this point. Even Amazon and Facebook are trying to streamline their services by foraying into this field.

However, credit where credit's due, Chat-GPT is the real hotshot of AI models. It can accomplish numerous tasks that were once deemed exceedingly challenging, even among AI optimists. Apart from writing the fun teleshopping ad style intro of this piece above here are some more things that you can do with Chat-GPT

**Write feature-length content**\
Whether it's narratives, blog entries, or video scripts, it handles them with proficiency. The most remarkable aspect is its capacity to accomplish this while assimilating contextual hints from user-provided prompts. Enhancing the output is possible by indicating additional contextual cues and refining the key elements to emphasize when generating its content. So, if you discover the necessity to compose a cover letter, let's say, for a university application. Chat-GPT can give you a 2-page cover letter in 10 seconds with the information provided by you such as your qualifications, your field of research and the research done in the field.

**Explain difficult-to-understand concepts**\
Yep, Chat-GPT could have explained to you what AI is. Its assistance can facilitate the comprehension of even more challenging subjects such as quantum computing, advanced mathematics, and even your colleague's poorly written code.

**Hold conversations**
If you've used Google Assistant or Siri on your phone you understand how they are incapable of holding conversations for more than 2 sentences. This is where Chat-GPT shines. It can talk and talk like a human with you.

**Extended functionalities**
The newer GPT-4 is even more powerful than the current free-to-use version. With the help of the Duolingo extension, you can learn a new language by having a conversation with the AI as if it is a real speaker of the language you're trying to learn. Additionally, it has the potential to offer customer support and enhance operational efficiency with minimal oversight. An application called Be My Eyes uses GPT-4 to act as a virtual assistant, helping with conversational assistance to low-vision users.

While obviously, you can use Chat-GPT for almost everything text. No data is in the form of text. There are images, audio and videos too. So there are other shining AIs that work with these data. The first one of them is image generation. Models like Midjourney and DALL E can generate images that did not exist before. Type in a prompt like "An image of an astronaut exploring the streets of New York drowned in the sea" and you'll get something like
\
\
<a href="/assets/astronaut-drowned-new-york.png" data-lightbox="An astronaut exploring the streets of New York drowned in the sea" data-title="An astronaut exploring the streets of New York drowned in the sea">
<img src="/assets/astronaut-drowned-new-york.png" title="An astronaut exploring the streets of New York drowned in the sea">
</a>
\
\
Huh! You don't need to write that prompt, I've already done the work for you.

Another noteworthy AI is AlphaGo, developed by Google's DeepMind team. In 2017, this program triumphed over the reigning Go world champion. The game of Go poses a substantial challenge for AI systems, surpassing even the complexity of Chess. This event stands as one of the recent instances where AI achieved victory over a human opponent.

Lastly, a shot out to personal assistant AIs like Siri, Google Assistant and Alexa. While Chat-GPT steals the show from them for being all too powerful. Personal AI assistants on smartphones and smart devices have been active participants for an extended period and continue to excel in tasks such as scheduling appointments and skillfully managing our smart devices. They are the real MVPs of AI in the hands of the public.

With the advent of such capable and efficient AIs, the logical next question would be what's next? What is the future of AI from here? How is it going to affect industries and businesses? And how will it impact jobs and lifestyle? The truth is, no one knows has concrete answers to these questions, not even GPT-4. As an AI optimist, I see its value in our lives. From the soothing comfort of being able to give voice commands to the speed and efficiency of doing mundane tasks like writing cover letters, there's something for everyone today. GPT-4 is considered to be close to Artificial General Intelligence. However, the legal yet unethical act of stealing every bit of work done by normal people on the internet to train the AI we use today is a dilemma that needs resolution as soon as possible. As for the economy, jobs are going to be lost. How many? I don't know but quite a lot. But new ones will also be created too. Some jobs that could not have been imagined even two decades ago are now raking in millions of dollars annually.

You never know, and neither does AI.

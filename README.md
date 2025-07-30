# Trip Helper App for Rocket.Chat 🚀 - GSoC 2025 Final Report

## Introduction

Hi! I'm **Piyush Bhatt**, and I had the incredible opportunity to contribute to Rocket.Chat during Google Summer of Code 2025. 

During my GSoC period, I worked on the Trip Helper App, an intelligent travel companion integrated with Rocket.Chat that leverages LLM technology to provide comprehensive trip assistance. This innovative app serves as your personal travel guide, offering valuable insights, recommendations, and information to enhance your travel experience through the power of AI and seamless chat integration.

## What's Rocket.Chat?

Rocket.Chat is an open-source business chat tool. It's a software that allows companies and organizations to communicate on their own platform.

In this project, I worked on developing new features that can be utilized on the Rocket.Chat platform.

## Project Overview

The goal of this project was to develop an intelligent Trip Helper App that could be seamlessly integrated with Rocket.Chat to serve as a comprehensive travel companion. In Trip Helper 2025, my focus was on leveraging LLM technology to create an interactive chat-based assistant that provides personalized travel recommendations, destination insights, and trip planning assistance. The project sought to enhance the travel experience by offering real-time information about attractions, local customs, weather updates, and practical travel tips through an intuitive conversational interface. I also worked on integrating the app with Rocket.Chat's ecosystem, ensuring smooth communication flows and developing features that make trip planning collaborative and accessible to users within their familiar chat environment.

## Project Goals 🏁

The main objective of my project was to create an AI-powered trip assistance app that seamlessly integrates with Rocket.Chat. Specifically, I aimed to:

• Implement an intelligent conversation system capable of providing personalized travel recommendations and destination insights.

• Develop a chat-based interface allowing users to easily interact with the trip helper directly within Rocket.Chat.

• Integrate open-source LLMs (such as Llama) to power the travel assistance and recommendation engine.

• Ensure the generated travel information is accurate, relevant, and formatted appropriately for immediate use in trip planning.

• Create a comprehensive knowledge base covering attractions, local customs, weather patterns, and practical travel tips.

• Build a foundation for future developments, including real-time booking integration and collaborative trip planning features.

These goals were designed to address the challenge of making travel planning more accessible and informed for Rocket.Chat user communities.

## How This Application Works

The system works as follows. Steps 6 and 7 are planned for future development:

<img src="./assets/trip-helper-workflow.png" alt="Trip Helper App Workflow" width="500" height="650"/>

*Figure: Trip Helper App Workflow Diagram*

1. The user creates a dedicated trip channel to access all Trip Helper functionality within Rocket.Chat.

2. The user shares an image of their current surroundings from their trip location, or alternatively, the app can use device location services if image sharing is not possible.

3. The LLM analyzes the provided image or location data to detect and identify the user's current location.

4. The system provides the detected location information and prompts the user with a "Yes" or "No" confirmation to verify if the location detection is accurate.

5. Once the user confirms the location, the trip channel transforms into a specialized environment where they can interact with the AI travel assistant.

6. The user can now chat with the bot and ask any questions about their trip, including local attractions, dining recommendations, cultural insights, weather updates, and travel tips.

7. Future enhancements will include real-time booking integration and collaborative trip planning features for multiple users.

## Why I Chose This Project

Honestly, I've always been that person who spends way too much time researching before any trip. You know, scrolling through countless travel blogs, asking friends for recommendations, and still feeling like I'm missing out on the best spots locals actually go to.

When I saw this project opportunity with Rocket.Chat, it just clicked for me. I thought - what if there was a way to have all that travel knowledge at your fingertips, right in your chat? No more switching between 10 different apps to plan a trip or figure out what to do next.

The tech side really excited me too. Working with LLMs and integrating them into something people actually use daily? That's the kind of challenge I live for. Plus, Rocket.Chat's platform seemed like the perfect playground to build something that could genuinely help travelers.

I guess you could say I wanted to solve my own problem - and hopefully help other travelers along the way!

## Project Links 🔗
- [GitHub Repository](https://github.com/RocketChat/Apps.Trip.Helper)
- [GSoC Project Details](https://summerofcode.withgoogle.com/programs/2025/projects/Ffe2Bu26)



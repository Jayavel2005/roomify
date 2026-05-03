# Roomify

Roomify is an AI-powered floor plan visualizer. It takes a 2D floor plan image and turns it into a photorealistic, top-down 3D architectural render.

## Project Overview

This project helps users quickly visualize how a flat floor plan can look as a realistic 3D space. Users can upload a floor plan, generate an AI render, compare the before and after images, and export the final result.

## Main Features

- Puter login and logout
- Floor plan upload with drag-and-drop support
- AI-based 3D render generation
- Project history storage
- Before and after comparison slider
- Export generated render as a PNG image

## How The App Works

1. The user opens the Roomify home page.
2. The user signs in using Puter.
3. The user uploads a floor plan image.
4. The app saves the uploaded image as a project.
5. The user is redirected to the visualizer page.
6. Roomify sends the floor plan to Gemini through Puter AI.
7. Gemini generates a top-down 3D architectural render.
8. The app shows the generated render.
9. The user can compare the original and generated images.
10. The user can export the final render.

## Tech Stack

- React
- React Router
- TypeScript
- Vite
- Tailwind CSS
- Puter.js
- Gemini AI image generation
- React Compare Slider
- Lucide React icons

## Video Script

Hi everyone, this is my project called Roomify.

Roomify is an AI-powered application that converts a 2D floor plan into a realistic top-down 3D architectural render.

On the home page, users can see the Roomify landing section, sign in with Puter, and upload their floor plan image.

After the image is uploaded, the app creates a new project and saves the original floor plan using Puter storage and hosting.

Then the user is taken to the visualizer page. Here, Roomify sends the uploaded floor plan to Gemini AI through Puter. The AI follows a detailed prompt to keep the room layout, walls, doors, and windows accurate while generating a clean 3D render.

Once the render is ready, the app displays the final 3D image. Users can also use the comparison slider to compare the original floor plan with the AI-generated render.

Finally, users can export the generated render as a PNG image.

The main technologies used in this project are React, React Router, TypeScript, Vite, Tailwind CSS, Puter.js, Gemini AI, and React Compare Slider.

In short, Roomify makes architectural visualization faster and easier by turning simple floor plans into realistic 3D views using AI.

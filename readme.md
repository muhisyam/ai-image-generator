# Fullstack MERN AI Image Generator App using OpenAI API

:star: Give star on GitHub — it motivates a lot!

This project was written by seeing [JavaScript Mastery Crash Course](https://www.youtube.com/@javascriptmastery), created with Fullstack MERN technology, and connect to the OpenAI API for the image generator. This app can created an image using ai and share it with others on community.

## Tools used in this project

- Node.js, Express.js, MongoDB, and React.js together form the powerful MERN stack
- Tailwind CSS
- OpenAI's DALL-E model: A deep learning model that generates images from text input
- Cloudinary: A cloud-based image storage service

## How to install this project

The easiest way to see how this works is to watch the series, but here's the short version.

1. Clone this project
2. Open terminal and execute `npm install` command on client folder and server folder too
3. Create `.env` file in server folder
4. Get [OpenAI API](https://platform.openai.com/docs/api-reference), [MongoDB Url](https://www.mongodb.com/cloud/atlas/register), and [Cloudinary Cloud and API](https://cloudinary.com/)
5. Put it all secret key to `.env` file
6. Open terminal, go to client directory, execute `npm run dev` command
7. Split the running terminal, go to server directory, execute `npm start` command
8. Then the app will works properly

## Find the error message

If you find the error message that tell the MongoDB atlas cant connect to the server.

**Make sure** your IP Address is whitelisted on Network Access at mongodb.

And then..

1. Get your current [ip address](https://www.whatismyip.com/)
2. Go to Network Access at Mongo atlas panel
3. Then edit the IP Address before the slash and save
4. Go to terminal press `Ctrl+C` and `y`, then run `npm start` command again. That will solve the problem

## Find a bug?

If you found an issue or would like to submit an improvement to this project, please submit an issue using the issues tab above. If you would like to submit a PR with a fix, reference the issue you created.

## Watch the full crash course

<a href="https://www.youtube.com/watch?v=EyIvuigqDoA" target="_blank">
<img src="https://i.ibb.co/p0f27C2/Thumbnail-9.png" alt="Watch the series" width="160" height="100">
</a>
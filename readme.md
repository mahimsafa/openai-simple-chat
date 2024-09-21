# Sample chat app with OpenAI and Chat GPT

![Application Home](/SS/app-home.png)


# Run the app:

- Clone the repo
- Install the dependencies
`pip install -r requirements.txt`
- Run the app.
`python main.py`
- Visit the app on [http://localhost:5000](http://localhost:5000)

# Run with docker

- Clone the repo
- Build the docker image
`docker buildx build -t openai-chat .`
- Run the container
`docker run --rm -p 5000:5000 openai-chat`
- Visit the app on [http://localhost:5000](http://localhost:5000)

# Deploy 

You can use the Dockerfile.lambda to deploy the app on AWS Lambda
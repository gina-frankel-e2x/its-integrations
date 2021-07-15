name: its-integrations

needs a simple hello world function that will be tested, published to artefactory using rvm-cli

everyone from Caas team should have access to this

TypeScript to be used as language

## How to start and watch server:

    "start": "functions-framework --source=build/src/ --target=helloWorld",
    "watch": "concurrently \"tsc -w\" \"nodemon --watch ./build/ --exec npm run start\"",
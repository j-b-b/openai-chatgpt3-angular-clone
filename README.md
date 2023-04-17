## Fork of Open AI ChatGPT Chat Page Clone

It's looks like;

![main_screen](./screenshots/main_screen.png)

Happy chating 🤟🏻

## Installation

```bash
## Clone the repository to your local
git clone https://github.com/j-b-b/openai-chatgpt3-angular-clone.git

## Navigate to project's directory
cd openai-chatgpt3-angular-clone

## Install the packages
npm install
```

After these steps you have to create an OpenAI account to create an API. You can create an account from [this link](https://openai.com/api/). Then you have to create an API key. Copy `apiKey` and `organizationId` and paste it to `src/environments/environment.prod.ts` and `src/environments/environment.ts` files as shown below.

```javascript
// environment.ts file
export const environment = {
  production: false,
  organizationId: "{your organization id}",
  openAiApiKey: "{your api key}",
};
```

Then you are ready to run the application!

```bash
npm run start
```

You can try the [DEMO.](chatgpt-clone-yny.web.app/)

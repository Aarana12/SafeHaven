# SafeHaven: Resources at a SNAP of your finger

SafeHaven is a new way to find support using Snapchat's map tab. This button will show the user a list of location resources near them, spotlights, and stories from snap stars and users all tailored around finding help to overcome housing insecurity. Non-profit organizations will also have a donate button on their location details to help encourage users to get involved in helping those in need. Are you ready to find your Haven?

![Starter screen](assets/Starter%Screen.png)

![Explore SafeHaven](assets/Explore%20SafeHaven.png)

![Location Details](assets/Location%20Details.png)

## How to see the feature on your phone

1. Download Visual Studio Code onto your local machine.

2. Clone the repository onto your local machine pressing the green code button. Use any method that works best for you. We used GitHub CLI by first running `brew install gh` in our terminal and then running the GitHub CLI provided in underneath the green code button. 

3. Once cloned, run `cd housingSecurityTeam`, then open in visual studio code running `code .` in your terminal.

4. Open the terminal inside your Visual Studio Code and run `yarn install`.

5. 

## Clone the Forked Repository
1. Go to your forked repository on GitHub.
2. Click on the green "Code" button and copy the URL.
3. Open your terminal or Git Bash and run: 
```js
$ git clone https://github.com/your-username/repository-name.git

```
4. Navigate to the repository directory

# Install Yarn
1. Run the following command to be able to run your program.
```js
$ git yarn install
```

# Set Up the Upstream Remote
1. Add the original repository as a remote: This allows you to pull in updates from the original repository.
```js
$ git remote add upstream https://github.com/Snap-Engineering-Academy-2024/SnapChatStarter.git
```
2. Verify the new remote named 'upstream'

```js
$ git remote -v
```
##  Add Supabase Environment Variable!

Get the code running! You'll need to rename `.env.example` to `.env.local` file. You should be able to reuse the Supabase keys from earlier's week project.
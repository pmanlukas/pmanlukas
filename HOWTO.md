# Instructions

This repository contains the code to run the following demo.

### 🗣 Update your GitHub profile README.md using Actions and Siri Shortcuts

In this demo we will learn how to use Siri Shortcuts and Actions to update the README.md file inside your personal GitHub repository with a message.
To reproduce, follow these instructions.


1. Fork this repository (https://github.com/pierluigi/pierluigi)
2. Generate a new Personal Access Token with `repo` permissions https://github.com/settings/tokens
3. Download my Siri Shortcut by following this iCloud link on your iOS device: https://www.icloud.com/shortcuts/0f28733463b94c8fafda83c23801be4d 
    **⚠️ Please note** You may have to enable the `Allow Untrusted Shortcuts` flag under `Settings -> Shortcuts` on you iOS device if you are receiving an alert when trying to install my Shortcut. You will be able to review what my shortcut does before finally installing it.

You need to change the following values:

<img src="https://raw.githubusercontent.com/pierluigi/my-actions-talk/master/shortcuts-info.jpeg" width="380" />

1. Change `[USERNAME]` and `[REPOSITORY]` with the corresponding values of your fork (e.g. `pierluigi` and `pierluigi` in this case) inside the `URL` field. 
2. Expand the `Get contents of URL` section `Show More ->  Headers - Authorization` and add the GitHub PAT you generated in step 2 above. It must look something like `token xyz123...`.
3. You can change the sentence to your own liking to trigger this shortcut. By default, it will respond to `Hey Siri – Update GitHub README`. After a short pause, Siri will ask you `With what text?`. At this point you can commence the dictation of the issue description.


Done! Have fun keeping your GitHub README updated using Siri ;)

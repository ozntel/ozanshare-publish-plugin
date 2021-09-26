# OzanShare Publish Plugin

This plugin allows you to publish your Markdown Notes with a single click directly from your Obsidian vault.

Each of your published files will have unique code, which is only available to you. You can share with someone the link and republish once you make small changes. It will keep the same `code` and `URL`.

**IMPORTANT**: 
- This is not an open source project. 
- The plugin is only available to users, who are on `Exclusive Support Level` on `BuyMeCoffee`: <a href="https://www.buymeacoffee.com/ozante" target="_blank">Exclusive Support Level</a>. Once you are in this support level, I will send you the `TOKEN` you can use for the plugin. You can also reach me out directly using the details from [Contact](#Contact) below to find out more.

**REMEMBER**: 
- This is still early stage for the plugin. There might be some bugs and missing features, which will be gradually improved, implemented. I will be grateful for your kind patience in case you see any bug, error and report me as soon as possible so that I can work on it.
- For the moment, the plugin will be available on Desktop only. Once I find a solution for the error, I plan to allow on mobile, as well.

To see more details, you can visit the page of `OzanShare Publish`: <a href="https://ozanshare.web.app" target="_blank">https://ozanshare.web.app</a>

## See How Plugin Works

<a href="https://www.youtube.com/watch?v=tgo3KwH4zOE" target="_blank">
    <img src="https://raw.githubusercontent.com/ozntel/ozanshare-publish-plugin/main/images/Watch%20on%20Youtube.png" width="550px"></img>
</a>

## Plugin Description

1. You need to be on `Exclusive Support Level` on `BuyMeCoffee` to be able to use the plugin. You will receive a `TOKEN` from me to be able to use the plugin and publish feature. For the moment, only limited people can be on this support level. Once you enter the `TOKEN` in plugin settings and click verify, you can start enjoying all features available: <a href="https://www.buymeacoffee.com/ozante" target="_blank">Exclusive Support Level</a>

2. You can `Publish` your notes and all related notes to the main note with a single click from the `Context Menu` of the file.

3. Your pages are going to be served on [https://ozanshare.web.app/](https://ozanshare.web.app/)

3. Plugin `Renders` the followings as HTML:

	- Admonitions
	- Transclusions (and also nested)
	- Linked Files
	- Mermaids
	- Code Blocks
	- Any Basic Markdown String

4. You can also add your `Custom CSS`. Go to settings and use to button to open your `Custom CSS` settings.

5. You can see all your published notes from the `View` created for plugin. Just click the `Ribbon Icon` and list your published notes.

6. As long as you don't unpublish your notes and change the place of the file in the vault, the `Republish` function will keep the old publish references. It will help you to update the files you have already shared with someone. You won't need to send a new link.

7. `Images` are uploaded to Firebase server, which are also served with a secret token. Image source with the provided token is automatically embedded into your final publish on OzanShare. 

8. Each publish triggers a scan of your `Published Files` and `Vault`. It means you shouldn't remove the references from `Frontmatter` manually by hand since it will trigger removing the published note from the server. You should rather use `Unpublish` button if you don't need the note anymore to be shared. This will remove the shared note from the server.

9. You can open the published notes on `Web Application` directly from the `Context Menu`.

## Contact

If you have any issue or you have any suggestion, please feel free to reach me out directly using contact page of my website <a href="https://ozan.pl/contact/" target="_blank">Ozan.pl Contact</a> or directly to <me@ozan.pl>.
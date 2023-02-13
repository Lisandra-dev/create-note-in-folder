# Create new note in folder  

This plugin add a new command to create a new note in a specific folder.  

To add a folder, use the settings tab. It will ask you to select a folder. The plugin will then create a new note in this folder.  

You can choose how, by default :  
- The note is named  
- The note is created (in the current tab, in a new tab, windows or in a split view)  
- If the note must be focused after creation  

After adding the folder, you can use the command "Create new note in folder {folder path}" to create a new note in this folder.  

> **Note**  
> If you have set a template for the folder, the new note will be created with the template.  

## Installation  

- [ ] From Obsidian's community plugins  
- [x] Using [BRAT](https://github.com/TfTHacker/obsidian42-brat#adding-a-beta-plugin) using `https://github.com/Lisandra-dev/create-note-in-folder`  
- [x] From release page:  
  - Download the latest release  
  - Unzip create-note-in-folder.zip in `.obsidian/plugins/` folder  
  - In Obsidian settings, reload the plugin  
  - Enable the plugin  

## Translations  

- [x] English  
- [x] French  

To add a translation:  
- Fork the repository
- Add a new file in `plugin/i18n/locales` with the name of the language (ex: `de.ts`)
- Copy the content of [`plugin/i18n/locales/en.ts`](plugin/i18n/locales/en.ts) in the new file
- Translate the content of the file
- Create a pull request


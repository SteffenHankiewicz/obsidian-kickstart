# Obsidian Kickstart
This is a repository to easily start using Obsidian for Meeting Notes and to let these be converted to PDF files with custom design based on the intranda corporate design.

To use this Kickstart just open the Terminal in the root folder where a new Vault shall be created and execute the following commands there:

## Usage for intranda corporate design

```bash
# go to the Vault root folder
cd ~/my-vault-folder

# create a hidden obsidian config folder and put the kickstarter files there
mkdir .obsidian;
cd .obsidian;
wget https://github.com/SteffenHankiewicz/obsidian-config/releases/download/2024-03-17_14-23-39_UTC/obsidian-intranda.zip -O o.zip;
unzip o.zip;
rm o.zip
cd ..
```

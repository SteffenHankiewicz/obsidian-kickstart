# Obsidian Kickstart
This is a repository to easily start using Obsidian for Meeting Notes and to let these be converted to PDF files with custom design based on the intranda corporate design.

# Usage
To use this Kickstart first you need to install Obsidian of course. Afterwards open the Terminal and execute the following commands:

## 1) Go to Vault root folder
First go into the root folder where a new Vault shall be created:

```bash
# go to the Vault root folder
cd ~/my-vault-folder
```

## 2) Download and install the correct corporate design
Now download and unzip the kickstarter files for the appropriate corporate design.

### a) intranda 
Download and unzip the kickstarter files for the intranda corporate design:

```bash
wget https://github.com/SteffenHankiewicz/obsidian-kickstart/releases/latest/download/obsidian-intranda.zip -O o.zip
unzip o.zip
rm o.zip
```

### b) ScanDataExperts 
Download and unzip the kickstarter files for the ScanDataExperts corporate design:

```bash
wget https://github.com/SteffenHankiewicz/obsidian-kickstart/releases/latest/download/obsidian-sde.zip -O o.zip
unzip o.zip
rm o.zip
```

## 3) Use this kickstarter package in Obsidian
Now you can start Obsidian and use the kickstart files:

- You will notice simple clean layout for your notes
- Using #tags will show these with different colors to highlight responsibilities
- Using the tag #done or #erledigt will have a bright grey tag color to mark things as done
- Use the configured PDF export (Better Export PDF) with your corporate design to get a shareable PDF stored directly beside your current document
- Use these shortcuts to make your life easier:

| Shortcut                   | Function                                                       |
| -------------------------- | -------------------------------------------------------------- |
| `option` + `command` + `g` | Highlight the current document in the file list                |
| `option` + `command` + `f` | Open Finder for the path of the current document               |
| `option` + `command` + `p` | Generate a PDF file with corporate design for the current note |


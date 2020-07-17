# Documentation.Automation.Pandoc

Convert Markdown to PDF documentation.

## Getting Started

### Prerequisites

Check out https://pandoc.org/installing.html.

### Preparing

Copy the PowerShell script to your markdown files (download it from the github release). 

### Installing

If you have not installed chocolatey on your windows host, please refer to https://chocolatey.org/install.

Check out official installation guide https://pandoc.org/installing.html.

Hint for avoiding problems with MikTex: Run MikTex Console (as administrator), switch du administrator mode and check updates.

## Running

### Markdown to PDF

Switch to the location of the markdown files and powershell script:

```
cd yourLocation
```

Execute the following command on the Command Prompt (as administrator):

```
powershell.exe -ExecutionPolicy bypass -File "markdownToPdf.ps1"
```

When it is finished, a PDF has been generated in the current path.

## Authors

- [Thierry Iseli](https://github.com/thierryiseli) - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Built With

- [Pandoc](https://pandoc.org/)
- [Eisvogel Template](https://github.com/Wandmalfarbe/pandoc-latex-template)

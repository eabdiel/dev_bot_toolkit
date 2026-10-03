# dev_bot_toolkit

Experimental Python chatbot developer toolkit with standalone automation utilities and planned natural-language tool access.

A project of **[ProgreTech LLC](https://progretech.com)**, owned and maintained by **Ed Rodriguez**. Third-party components and contributions retain their respective ownership and notices.

[Project website](https://progretech.com) · [Report an issue](https://github.com/eabdiel/dev_bot_toolkit/issues) · [Contribute](CONTRIBUTING.md)

Chatbot based dev-tools; the bot will call/execute some of my tools based on text input (currently chatbot_core is the sample ui with simple responces and definitions - other tools will be made standalone first before final bot is available with NLP functions to access seperate tools)
 Planned tools->
 1. Bulk search/replace content in txt files from FTP
 2. SAP Macro execution (using https://github.com/eabdiel/sap_automation)
 3. Extract XLSX - Iterate through and open each Sheet#.xml file - Remove <Protection tags from them to reset passwords from MS files - re-pack and save to target folder
         
         10/9/2020:---found open source prog from github.com/petemc89 (Thanks Pete!); I've adapted it to the dev-tools ui as standalone prog - next version will be available on chatbot_core.
         
 4. Search functionality for Job log csv (using https://github.com/eabdiel/sap_automation/tree/master/AutomatedGetJob_Data_Analysis_Tool)
 5. File downloader
 6. Target XML url to Spreadsheet

## Collaboration

Reproducible bug reports, platform compatibility, installation documentation, and small regression fixes are useful ways to help. Read [CONTRIBUTING.md](CONTRIBUTING.md) for issue reports, proposed changes, and attribution requirements.

## License and reuse

The repository includes MIT terms in [LICENSE](LICENSE). Preserve applicable copyright and license notices. Consult the full license for modification, distribution, and any source-provision requirements.

The original README credits tools adapted from petemc89. Identify the exact upstream project, revision, and applicable license before redistributing the adapted component; retain its original notices.

## More from ProgreTech

Explore [CodeSeal](https://codeseal.progretech.com) for signed software provenance and project history.

Discover the wider portfolio at [progretech.com](https://progretech.com). These links identify related products; they do not imply a bundled integration or shared license.

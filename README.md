[![License: CC BY-NC-SA 3.0](https://img.shields.io/badge/license-CC%20BY--NC--SA%203.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode)

# SS13PaperworkSimulator
Renders SS13 (Baystation12/Paradise Station) pencode into HTML.

This aims to replicate the same process the game uses to render pencode, so whatever you see in the output will look similar to the same pencode rendered on paper ingame.

Hosted on [https://ss13.haydenredacted.com/paperwork-simulator/](https://ss13.haydenredacted.com/paperwork-simulator/)  
Paradise Station Guide to Paperwork: [Guide to Paperwork](https://www.paradisestation.org/wiki/Guide_to_Paperwork)  
Paradise Station Example Paperwork: [Example Paperwork](https://www.paradisestation.org/wiki/Example_Paperwork)

# Adding a New Template
Place your templates in the `templates` directory in the most relevant folder. If the template is related to a certain department, please put it in the respective folder. Otherwise, the subdirectory you choose is up to you. If applicable, put it in the relevant server folder. If your server isn't there, feel free to add yours!
- In <b>templates/index.json</b>, find the category your template best fits under, usually the department. If you're adding a set of record skeletons, put them under a group in "Records" with your name instead so that they're grouped with similar templates. Add a new element where it's most appropriate.
- Make sure the new JSON is correct. You can test in Microsoft Edge (doesn't prevent you from accessing local files via AJAX) or just paste the contents into jsonlint.com to validate.
- Place your template in a `.txt` file in a directory inside `templates/`, then add its name and path to `templates/index.json`. 
- If you would like to test if your changes on local, make sure you have the code downloaded locally. If you have Python installed, open up a command line in the repository and run <b>python -m http.server 8080</b> and then open up <b>[localhost:8080](localhost:8080)</b> in your web browser.
- Submit via pull request and check here for requested changes until it is merged. When submitting your work, you may add your name or ckey to `credits.json`. <b> Make sure you are submitting a pull request to THIS REPO, not upstream</b>

# Contribution
Please feel free to submit your own work if you are willing to have it available under CC BY-NC-SA 3.0.

To add a template, place it in a `.txt` file in a directory inside `templates/`, then add its name and path to `templates/index.json`. 

# Attribution
All included images have been sourced from the Baystation12/Baystation12, Aurorastation/Aurora.3, or ParadiseSS13/Paradise repository and are attributed to their respective original authors. All included templates, whether sourced from the Baystation12 Wiki/Paradise Station or committed by or on behalf of their original authors, are attributed to their respective original authors. Any characters, settings, and events referred to as part of the Baystation12/Paradise Station story and lore are attributed to their respective original authors.

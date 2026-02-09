Contributing
Please feel free to submit pull requests or open issues to improve Contributor Covenant, whether through code, content, design, or translations.

If you're new to contributing to projects hosted on Github, or need a refresher, you may find How to make your first pull request on GitHub a useful resource.

Check the issues for the latest discussions involving the current and future versions of the Contributor Covenant. If your question, concern, or suggestion is not already listed, please open a new issue using the New Issue button, and select either the 🪲Bug Report or 💡Feature Request template.

Adding Your Community to the List of Adopters
Fork the repository.
Edit the assets/adopters.csv file
Add a row with your project or community name in the first column, and its URL in the second column.
For human readability, please make sure that you've preserved alphabetical order in the list.
Open a pull request.
We respect and appreciate different kinds of contributions
Ways that you can contribute:

Community governance experts
We value collaboration with contributors who bring their experience with code of conduct design or enforcement to continue to improve Contributor Covenant.

Writers and copy editors
We welcome contributions to improve the language of our site.

Designers
We welcome improvements to the design elements of our website or other ways that you can use your talents to improve contributor-covenant.org.

Translators and native speakers
We're always looking for translations by native speakers are thankful to the dozens of volunteer translators and reviewers who have donated their time and expertise.

If you are a native speaker interested in doing a translation, please follow these steps:

Fork the repository and make a branch for your translation.
If it's a new language, add it to config.toml, with a localized name and language code/optional region (e.g. pt or pt-br).
Create a markdown file with your translation in version/3/0/code_of_conduct.LANGUAGECODE.md. (Underscores, not hyphens.) Use the English markdown file as an example.
Update the two fields at the top of your new markdown file: reportingPlaceholder, which should contain the exact placeholder text in the "how to report" section, and enforcementPlaceholder, which should contain the exact placeholder text in the "Addressing and Repairing Harm" section.
Open a pull request.
We will put out a call to have one or more other native speakers review the translation.
Collaborate until the translation is satisfactory.
We will merge your translation!
HTML and plain text versions are automatically generated from your markdown file.
A link to your translation is automatically added to the translations page.
Note that we will not accept machine translations.

Developers
Code contributions to improve the development or operation of the contributor-covenant.org web site are welcome. To do so, first check to make sure your issue is not already listed in the issues.

Build the website locally
To build the website locally, first fork the repo and then clone it to your local machine.
install Hugo using your package manager of choice.
For example, on Debian/Ubuntu:

apt-get install hugo
If you are using Arch Linux:

pacman -S hugo
If you are using Homebrew on macOS:

brew install hugo
From the repository's root directory, start the development server and then view it at http://localhost:1313/.
hugo server -D
Any changes you make will be reflected in the browser.
Code Style
Use spaces for indentation
Order properties alphabetically
HTML
Include alt attribute for all images
Include title attribute for all links
Close all your tags properly
CSS
Try to use classes instead of IDs unless things are absolutely unique
One selector per line
Support all modern browsers
Use rem over em or px
Capitalize hexadecimal
Breaking lines should be 1px solid #CCC
Maintain contrast to WCAG AA on normal text, WCAG AAA on large text
Use colors from this palette
Markdown
Do not use fancy quotes, dashes, and such; the Markdown processor will handle that.

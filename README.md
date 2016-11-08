# sandbox

## Welcome
Welcome to the Lingoport Sandbox. Use the sandbox to get a feel for Lingoport's
Globalyzer. You may commit Java, JavaScript or C# code under the relevant
folder. Once the code has been pushed to the repository, it will be
automatically scanned by Globalyzer. Within a couple of minutes, the results
will be shown on the sandbox dashboard at [sandbox.lingoport.com](http://sandbox.lingoport.com/dashboard/index?id=Lingoport.Sandbox%3Ascan).

Video introductions to the sandbox are available at
[lingoport.com/pd/lingoport-suite-sandbox](http://lingoport.com/pd/lingoport-suite-sandbox/).

## Access

To use the sandbox, you will need contributor access. Please [create an
issue](https://github.com/lingoport-public/sandbox/issues/new) to request access.

## In this Sandbox:

+ Add or modify C# (.cs), Javascript (.js, .html) and Java (.java) files: The Dashboard should reflect new i18n issues.
+ Add or modify resource bundles with \_en\_US.(json/properties) / .en-US (resx) for the base files, and \_fr\_FR.(json/properties) / .fr-FR (resx) for the translated files.
* The tracked locales are: en\_US (the files to be translated), fr\_FR, de\_DE, ja\_JP, and zh\_CN.
  * So for example: messages\_en\_US.properties and messages\_ja\_JP.properties, etc. Or errors.en-US.resx and errors.de-DE.resx, etc.

## Usage

1. Clone the repository
   * $ git clone https://github.com/lingoport-public/sandbox.git
2. Checkout the <b>working</b> branch
   * $ git checkout <b>working</b>
3. Add Java, JavaScript and/or C# code under the relevant directory.
4. Commit and push you changes
   * $ git add &lt;changed files here&gt;
   * $ git commit
   * $ git push origin working

Within a couple of minutes, the Lingoport Sandbox
[Dashboard](http://sandbox.lingoport.com/dashboard/index?id=Lingoport.Sandbox%3Ascan)
will update to include a scan of your changes.

## Notes

The 'working' branch will be reset to match 'master' on a weekly basis. Pushing to master is disabled.

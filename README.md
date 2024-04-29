# Gmail Bulk Attachment Downloader

Currently gmail is not providing to download attachments from different different mails with in single click. Using this program you can do it now.

You need `credentials.json` before start this utility. You can get it from https://developers.google.com/gmail/api/quickstart/nodejs by enable GMAIL API.
Save file `credentials.json` in the root folder of the project

Clone Project

`git clone https://github.com/munir131/attachment-downloader`

Install dependencies

`npm i`

Run program in interactive mode

`node index.js`

Run program in non-interactive mode

`node index.js --label LABEL_NAME`

## Contributors

Thanks to all the people who already contributed!

<a href="https://github.com/munir131/attachment-downloader/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=munir131/attachment-downloader" />
</a>

Made with [contrib.rocks](https://contrib.rocks).


# Kevin Notes

* Run with `node index.js`
* Select the 'Using q' option, and modify the example query with the new dates. I'm okay with an extra day on each end of a year. A few duplicates doesn't matter
* delete all .xml, .txt, maybe images (png, jpeg)
* brew install fdupes, then run `fdupes files -rdN`, as there will be a lot of duplicate files `1234.pdf`, `1234 (<timestamp>).pdf`

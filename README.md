React component for ONLYOFFICE Document Server

Install the project dependencies:
`yarn install`

Test component:
`yarn test`

Create package:
`yarn rollup && npm pack`

Example:
```
<DocumentEditor
  id="docxEditor"
  documentserverUrl="http://documentserver/"
  config={{
    "document": {
      "fileType": "docx",
      "key": "Khirz6zTPdfd7",
      "title": "Example Document Title.docx",
      "url": "https://example.com/url-to-example-document.docx"
    },
    "documentType": "word",
    "editorConfig": {
      "callbackUrl": "https://example.com/url-to-callback.ashx"
    }
  }}
/>
```

Properties:

`id` - identifier of element

`documentserverUrl` - address ONLYOFFICE Document Server

`config` - generic configuration object for opening a file with token

`document_fileType` - the type of the file

`document_title` - the file name

`documentType` - the document type

`editorConfig_lang` - the editor interface language

`height` - the document height in the browser window

`type` - the platform type used to access the document

`width` - the document width in the browser window

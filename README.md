Fineuploader-dropbox
====================

Fineuploader-dropbox is an adaptation of [fineuploader](https://github.com/FineUploader/fine-uploader) for quick use with dropbox.

How to use:

    var uploader = new qqdropbox.FineUploader({
                element: document.getElementById('AreaUpload-File'),
                multiple: true,
                request: {
                  paramsInBody: true,
                    customHeaders: {
                      "Authorization": "Bearer_Authorization "          
                    },
                    path: '/'
                },
                template: "qq-template",
                autoUpload: true
    });

Fineuploader-dropbox uses all fineuploader the default settings except the path that indicates where you want to save your file in the dropbox.

 For more information, please see the [documentation](http://docs.fineuploader.com/).

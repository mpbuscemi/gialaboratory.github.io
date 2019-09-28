![GIA](/static/gia-logo.svg)

# GIA Laboratory Developer Documentation

This is the source for https://gialaboratory.github.io


### Generate Reference Documentation

Install graphdoc from https://github.com/2fd/graphdoc

Delete the existing `reference` folder.

```
set REPORT_RESULTS_API_KEY=ENTER_API_KEY_HERE
set REPORT_RESULTS_API_ENDPOINT=ENTER_ENDPOINT_HERE
graphdoc -e %REPORT_RESULTS_API_ENDPOINT% -o ./reference -x "Authorization: %REPORT_RESULTS_API_KEY%"
```






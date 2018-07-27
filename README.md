# regexp hub
A collection of useful regex patterns, if you find error, please tell me or give me a pull request, thank you very much...

### regexps

```javascript
  'require': /^.+$/, // required
  'username': /^[a-zA-Z0-9_-]{3,16}$/, // username
  'positiveInteger': /^\d+$/, // positive integer
  'negativeInteger': /^-\d+$/, // negative integer
  'integer': /^-?\d+$/, // integer
  'positiveNumber': /^\d*\.?\d+$/, // positive or negative number
  'negativeNumber': /^-\d*\.?\d+$/, // positive or negative number
  'positiveOrNegativeNumber': /^-?\d*\.?\d+$/, // positive or negative number
  'yyyy/mm/dd hh:mm:ss': /^([0-9][0-9][0-9][0-9])([ \/\-])(0?[1-9]|1[012])\2(0?[1-9]|[12][0-9]|3[01])(([ -])([0-1]?[0-9]|2[0-3]):[0-5]?[0-9]:[0-5]?[0-9])?$/, // yyyy/mm/dd hh:mm:ss
  'dd/mm/yyyy hh:mm:ss': /^(0?[1-9]|[12][0-9]|3[01])([ \/\-])(0?[1-9]|1[012])\2([0-9][0-9][0-9][0-9])(([ -])([0-1]?[0-9]|2[0-3]):[0-5]?[0-9]:[0-5]?[0-9])?$/, // dd/mm/yyyy hh:mm:ss
  '24hourTime': /^([01]?[0-9]|2[0-3]):[0-5][0-9]$/, // 24hour time
  'htmlTag': /^<([a-z1-6]+)([^<]+)*(?:>(.*)<\/\1>| *\/>)$/, // html tag
  'url': /^((https?|ftp|file):\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/, //url
  'email': /^.+@.+$/, // email
  'IPv4 Address': /^(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)$/,
  'IPv6 Address': /^(([0-9a-fA-F]{1,4}:){7,7}[0-9a-fA-F]{1,4}|([0-9a-fA-F]{1,4}:){1,7}:|([0-9a-fA-F]{1,4}:){1,6}:[0-9a-fA-F]{1,4}|([0-9a-fA-F]{1,4}:){1,5}(:[0-9a-fA-F]{1,4}){1,2}|([0-9a-fA-F]{1,4}:){1,4}(:[0-9a-fA-F]{1,4}){1,3}|([0-9a-fA-F]{1,4}:){1,3}(:[0-9a-fA-F]{1,4}){1,4}|([0-9a-fA-F]{1,4}:){1,2}(:[0-9a-fA-F]{1,4}){1,5}|[0-9a-fA-F]{1,4}:((:[0-9a-fA-F]{1,4}){1,6})|:((:[0-9a-fA-F]{1,4}){1,7}|:)|fe80:(:[0-9a-fA-F]{0,4}){0,4}%[0-9a-zA-Z]{1,}|::(ffff(:0{1,4}){0,1}:){0,1}((25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])\.){3,3}(25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])|([0-9a-fA-F]{1,4}:){1,4}:((25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])\.){3,3}(25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9]))$/,
  'en': /^[a-zA-Z]+$/, // en

  'zh': /^[\u4e00-\u9fa5]+$/, // chinese
  'zh-identity': /(^[1-9]\d{5}(18|19|([23]\d))\d{2}((0[1-9])|(10|11|12))(([0-2][1-9])|10|20|30|31)\d{3}[0-9Xx]$)|(^[1-9]\d{5}\d{2}((0[1-9])|(10|11|12))(([0-2][1-9])|10|20|30|31)\d{2}$)/, // china id card
  'zh-mobile': /^1\d{10}$/, //china mobile number
  'zh-postcode': /^\d{6}$/ //china postcode

```

[![Build Status](https://travis-ci.org/flameddd/Travis_CI_Practice.svg?branch=master)](https://travis-ci.org/flameddd/Travis_CI_Practice)
[![Coverage Status](https://travis-ci.org/flameddd/Travis_CI_Practice.svg?branch=master)](https://travis-ci.org/flameddd/Travis_CI_Practice)

# Travis_CI_Practice
#Travis CI的流程如下：
```
  1.從GitHub下載專案(clone)。
  2.進入資料夾。
  3.Checkout到特定的版本。
  4.執行before_install。
  5.執行install。
  6.執行before_script。
  7.執行script。
  8.執行after_success或after_failure。
  9.執行after_script。
```

#Travis CI、Node.js  
這次測試是用Node.js，在根目錄下新增檔案`.travis.yml`，檔案內容為
```
language: node_js
node_js:
  - "6"
  - "6.1"
  - "5.11"
  - "0.6"
  - "iojs"
```
這樣就是預設環境語言

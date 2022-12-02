# Test Reporter with PR Comment

This Github Action is a modified version of [Test Reporter](https://github.com/dorny/test-reporter) to automatically comment test summary on Pull-request. Only two features are added in this repo: 1. exporting test summary markdown as step output variable, 2. attaching comment containing test summary on Pull-request. 

## How it Looks
![image](https://user-images.githubusercontent.com/13706388/203845403-94db986c-7542-4fad-becf-7d0da26ee79d.png)

## How to Use
Totally same with the original [Test Reporter](https://github.com/dorny/test-reporter)! There is no additional setup needed. 
If you want to export and utilize the summary by yourself, you can use `steps.<stepId>.outputs.summary` to get an access to the summary markdown string. 

## Original Repository
- [Test Reporter](https://github.com/dorny/test-reporter)
- [Test Reporter / Marketplace](https://github.com/marketplace/actions/test-reporter)

## License
The scripts and documentation in this project are released under the [MIT License](https://github.com/dorny/test-reporter/blob/main/LICENSE)

# Codecov Language Standards

[![Build Status](https://travis-ci.org/codecov/standards-scripts.svg?branch=master)](https://travis-ci.org/codecov/standards-scripts)

## What is this?

This is a repository containing aggregated information about the state of all Codecov language standards. Each lanaguage standard ensures that Codecov is processing reports for said lanaguge properly if it's build is passing. Repositories for each standard along with their current build statuses are listed in the table below.

Inside the `scripts` folder, you can also find shell files for each standard that run on a Travis CRON job (daily). Essentially, this allows us to make sure coverage is uploaded to Codecov on a regular basis for each repo. 

## List of Standards

|                           Standard                           | Build Status                                                                                                                      |
| :----------------------------------------------------------: | --------------------------------------------------------------------------------------------------------------------------------- |
| [Python](https://github.com/codecov/Python-Standard.git) | [![Build Status](https://travis-ci.org/codecov/Python-Standard.svg?branch=master)](https://travis-ci.org/codecov/Python-Standard) |
|[Swift 5/Xcode 11](https://github.com/codecov/Swift-Standard) |[![Build Status](https://travis-ci.org/codecov/Swift-Standard.svg?branch=master)](https://travis-ci.org/codecov/Swift-Standard) |
|[Ruby 1 - Codecov Gem](https://github.com/codecov/Ruby-Standard-1) |[![Build Status](https://travis-ci.org/codecov/Ruby-Standard-1.svg?branch=master)](https://travis-ci.org/codecov/Ruby-Standard-1) |
|[Ruby 2 - Bash Uploader](https://github.com/codecov/Ruby-Standard-2) |[![Build Status](https://travis-ci.org/codecov/Ruby-Standard-2.svg?branch=master)](https://travis-ci.org/codecov/Ruby-Standard-2) |
|[TypeScript](https://github.com/codecov/TypeScript-Standard) |[![Build Status](https://travis-ci.org/codecov/TypeScript-Standard.svg?branch=master)](https://travis-ci.org/codecov/TypeScript-Standard) |

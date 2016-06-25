
# ng2-form-utils
[![Build Status](https://travis-ci.org/haiko/ng2-form-utils.svg?branch=master)](https://travis-ci.org/haiko/ng2-form-utils)
[![Coverage Status](https://coveralls.io/repos/github/haiko/ng2-form-utils/badge.svg?branch=master)](https://coveralls.io/github/haiko/ng2-form-utils?branch=master)
[![peerDependency Status](https://david-dm.org/haiko/ng2-form-utils/peer-status.svg)](https://david-dm.org/haiko/ng2-form-utils#info=peerDependencies)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/haiko/ng2-form-utils/master/LICENSE)

Utility functions to assist you dealing with Angular2 Forms.

ng2-form-utils uses the model-driven form approach for building Angular2 forms. Large forms with more then 10 fields are tedious to code out. It does the heavy lifting of creating the Angular2 Controls.


* [Installation](#installation)

## Installation
First you need to install the npm module:
```sh
npm install ng2-form-utils --save
```

## Usage

Create an object and feed to FormObjectBuilder. Then in your template you define the ngControls with as value the name of the corresponding fields of the object. This is best illustrated with an example.  



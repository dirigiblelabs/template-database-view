# Template - Database View

[![Eclipse License](http://img.shields.io/badge/license-Eclipse-brightgreen.svg)](LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/dirigiblelabs/template-v3-database-view.svg)](https://github.com/dirigiblelabs/template-v3-database-view/graphs/contributors)


## Overview

Simple "Database View"
```javascript
{
	"name": "{{viewName}}",
	"type": "VIEW",
	"query": "SELECT EXTENSION_DESCRIPTION FROM DIRIGIBLE_EXTENSIONS where EXTENSION_EXTENSIONPOINT_NAME = 'ide-template'",
 	"dependencies": [{
 		"name":"DIRIGIBLE_EXTENSIONS",
 		"type":"TABLE"
 	}]
}
```


## License

This project is copyrighted by [SAP SE](http://www.sap.com/) and is available under the [Eclipse Public License v 1.0](https://www.eclipse.org/legal/epl-v10.html). See [LICENSE](LICENSE) and [NOTICE.txt](NOTICE.txt) for further details.

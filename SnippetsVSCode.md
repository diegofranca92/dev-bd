### Criação de Snippets VSCode
```
{

	"Function React Native": {
		"prefix": "trn",
		"body": [
			"import React from 'react'",
			"import { View } from 'react-native'",
			"",
			"export function ${1:${TM_DIRECTORY/^.*(\\/|\\\\)([^(\\/|\\\\)]+)$/$2/}}() {",
			"  return (",
			"    <View>",
			"    </View>",
			"  )",
			"}"
		],
		"description": "Function React Native"
	}
}
```

**Snippet generator**

https://snippet-generator.app/

**Variaveis VsCode**

https://code.visualstudio.com/docs/editor/userdefinedsnippets

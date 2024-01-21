# vscode nestjs code snippet

```typescript
  "NestJS-Service": {
    "prefix": "nssv",
    "body": [
      "import { Injectable } from '@nestjs/common';",
      "",
      "@Injectable()",
      "export class ${TM_FILENAME_BASE/([a-z]+)([-.])?([a-z]+)?/${1:/pascalcase}${3:/pascalcase}/} {",
      "	constructor() {}",
      "}",
      ""
    ],
    "description": "NestJS-Service-Snippet"
  },
```

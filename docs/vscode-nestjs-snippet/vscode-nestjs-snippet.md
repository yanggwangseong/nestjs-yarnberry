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
  "NestJS-Controller": {
    "prefix": "nsco",
    "body": [
      "import { Controller } from '@nestjs/common';",
      "",
      "@Controller('cats')",
      "export class ${TM_FILENAME_BASE/([a-z]+)([-.])?([a-z]+)?/${1:/pascalcase}${3:/pascalcase}/} {",
      "	constructor() {}",
      "}",
      ""
    ],
    "description": ""
  }
```

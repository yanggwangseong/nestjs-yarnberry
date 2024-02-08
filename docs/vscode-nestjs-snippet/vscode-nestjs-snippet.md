# vscode nestjs code snippet

> camelcase : 파일 이름을 camel case로 변환
> pascalcase : 파일 이름을 pascal case로 변환
> upcase : 파일 이름을 모두 대문자로 변환
> downcase : 파일 이름을 모두 소문자로 변환

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
      "@Controller('${TM_FILENAME_BASE/([a-z]+)([-.])?([a-z]+)?/${1:/downcase}/}')",
      "export class ${TM_FILENAME_BASE/([a-z]+)([-.])?([a-z]+)?/${1:/pascalcase}${3:/pascalcase}/} {",
      "	constructor() {}",
      "}",
      ""
    ],
    "description": "NestJS-Controller-Snippet"
  },
  "NestJS-Module": {
    "prefix": "nsmo",
    "body": [
      "import { Module } from '@nestjs/common';",
      "",
      "@Module({",
      "	imports: [],",
      "	controllers: [],",
      "	providers: [],",
      "	exports: [],",
      "})",
      "export class ${TM_FILENAME_BASE/([a-z]+)([-.])?([a-z]+)?/${1:/pascalcase}${3:/pascalcase}/} {}"
    ],
    "description": "NestJS-Module-Snippet"
  }
```

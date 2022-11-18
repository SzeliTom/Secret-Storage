# Secret-Storage

## Introduction

This repo intended to store the practice work for TypeScript, NestJs and others.

## Task

### Functional requirements

  - The secret application can create, retrieve and list the secrets.
  - You can create a secret by defining a secret text and a remaining views counter. The secret application then returns your secret hashed (you can choose what hashing algorithm you use, but MD5 is fine).
  - Every time a secret is retrieved, the remaining views counter is decreased by one. (Secret is not retrievable if the remaining views is 0)
  - Listing secrets doesn't returns the secret text.

### Non-Functional requirements

  - Should be done in typescript
  - Use dependency injection
  - Use a monorepo (NX - angular\nestjs monorepo is strongly advised)
  - Input should be validated based on the included OpenApi documentation
  - Use TDD for atleast one file\service\class
  - Use proper git commit practices (eg.: https://github.boschdevcloud.com/CCPS-Reporting/Lotus-2/wiki/Git-Best-Practices)
  - Copy the end-points but you can extend if you feel the need to
  - (In short create an API that is defined in the openApi documentation)

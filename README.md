# Module-TypeScript

## Prerequisites
Node.js should be installed on your system.  
Download link : [NodeJS](https://nodejs.org/en)

## Setting up TypeScript locally
1. Install typescript: `npm install -g typescript`
2. Compile command: `tsc filename.ts` 

**Alternate way :** you can use web based compiler :[Typescript Compiler](https://www.typescriptlang.org/play/)

## Basic Types
- number
- string
- boolean
- any
- void
- null
- undefined
- never

## Advanced Types & Interfaces
- Arrays & Tuples
- Enums
- Type Aliases vs. Interfaces
- Union & Intersection Types

## Functions & Classes
- Function types & parameters
- Optional & default parameters
- Classes, inheritance, access modifiers (public, private, protected)
- Abstract classes & interfaces in OOP



# Typescript-basic 
#### Install type script globally by running command 
    npm install typescript -g 

#### Compile multiple ts files. create a folder and inside that run command below. It will create tsconfig file.
    tsc -init
    
#### Run command to check result of typescript code.
    tsc filename.ts

#### Run watch mode compiler by running command 
    tsc -w

#### Run command to check result of javascript code.
    node filename.js
    
#### Run command to check result of typescript code.
    tsc filename.ts
    
#### watch mode compiler
    tsc -w

### Variables 
Scope
    - var   : function scoped
    - let   : block scoped
    - const : block scoped and value will not change

### Data Types :
Primitive  : 
    1. number
    2.string
    3. bool
    
If the data type is not explicitly defined, ts uses "automatic type reference"
Examples : var/let/const <<variable-name>> : <<data-type>> =<<value>>

unknown and never types are also there in the typescript.

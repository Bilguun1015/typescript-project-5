# CVS Data Report

Learn how to work with cvs data with node and analyze the data to report

## Environment Setup

1. `tsc --init` to initiliaze tsconfig.json

   - uncomment outDir and rootDir to organize js build

2. Install nodemon and concurrently

   - `npm init -y` and `npm install nodemon concurrentyl`

3. Update script in package.json with the following

   `"scripts": { "start:build": "tsc -w", "start:run": "nodemon build/index.js", "start": "concurrently npm:start:*" },`

## Notes

1. When working with Node.js install `@types/node` for Type Definition File

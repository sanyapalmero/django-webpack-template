# Django template project with webpack

## Usage

Create virtual environment
```bash
python -m venv venv
```
Activate virtual environment on Linux
```bash
source venv/bin/activate
```
Activate virtual environment on Windows
```bash
source venv/Scripts/activate
```
Install dependencies
```bash
pip install -r requirements.txt
```
For installing npm packages you need to run
```bash
npm install
```
For test you need to run
```bash
npm run watch
```
After that you will see something like that
```bash
webpack is watching the files…

Hash: f047715d2c108d328983
Version: webpack 4.15.1
Time: 15309ms
Built at: 21.02.2020 17:18:41
                   Asset      Size  Chunks             Chunk Names
main-f047715d2c108d32.js  3.85 KiB    main  [emitted]  main
[./static/ts/main.ts] 14 bytes {main} [built]
```

## Notes
Don't forget to edit package.json file

```json
{
    "name":"project name here",
    "repository": {
        "url": "git+https://github.com/username/project.git"
    },
    "bugs": {
        "url": "https://github.com/username/project/issues"
    },
    "homepage": "https://github.com/username/project#readme",
}
```


# pesy-new


[![CircleCI](https://circleci.com/gh/yourgithubhandle/pesy-new/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/pesy-new/tree/master)


**Contains the following libraries and executables:**

```
pesy-new@0.0.0
│
├─test/
│   name:    TestPesyNew.exe
│   require: pesy-new/library
│
├─library/
│   library name: pesy-new/library
│   require:
│
└─executable/
    name:    PesyNewApp.exe
    require: pesy-new/library
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x PesyNewApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```

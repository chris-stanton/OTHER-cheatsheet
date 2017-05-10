# Notyf

### Install

1. `` npm install --save notyf ``

2. Verify that dependancies were added to `` package.json ``

3. Add `` notyf.min.js `` and `` notyf.min.css `` to /vendors folder located inside of /assets folder

4. Sources the script and link elements into ``index.html``
```
<script src="./assets/vendor/notyf.min.js" type="text/javascript"></script>
```
```
<link rel="stylesheet" type="text/css" href="./assets/vendor/notyf.min.css">
```
5. Add global variable `` var notyf = new Notyf(); `` to every document that will be using Notyf

6. Basic Alerts:
  - Confirm: `` notyf.confirm('Your changes have been successfully saved!'); ``
  - Alert: `` notyf.alert('You must fill out the form before moving forward');
``

---

### Options
[Notyf GitHub Account](https://github.com/caroso1222/notyf)

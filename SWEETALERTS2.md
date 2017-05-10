# Sweetalert 2

### Install

1. `` npm install sweetalert2 ``

2. Verify that dependancies were added to `` package.json ``

3. Add `` sweetalert2.min.js `` and `` sweetalert2.min.css `` to /vendors folder located inside of /assets folder

4. Sources the script and link elements into ``index.html``
```
<script src="./assets/vendor/sweetalert2.min.js" type="text/javascript"></script>
```
```
<link rel="stylesheet" type="text/css" href="./assets/vendor/sweetalert2.min.css">
```

5. Basic Alerts:

  ``
  swal({
  title: 'Error!',
  text: 'Do you want to continue',
  type: 'error',
  confirmButtonText: 'Cool'
})
``


---

### Options
[Sweetalert2 GitHub Account](https://limonte.github.io/sweetalert2/)

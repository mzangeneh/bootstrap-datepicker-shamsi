# bootstrap-datepicker-persian


Shamsi Or Jalali Datepicker (Iranian Calendar) which contains all features of bootstrap-datepicker alongside with shamsi features.

# Installation


Simply clone or download the source code and add this libraries to your page

```html
<link href="/dist/js/persiandate.min.js" rel="stylesheet"/>
<script src="/dist/js/bootstrap-datpicker.min.js"></script>
```

# Usage

Create a tag like input or whatever:
```html
<input type="text" id="dp">
```

And call this code and do the magic

```html
<script type="text/javascript">
    $(function(){
        $('#dp').datepicker({
            format: 'YYYY-MM-DD',
            autoclose: true,
            todayHighlight: true,
        });
    });
</script>
```

# Demo with full instruction
[DEMO](https://mzangeneh.github.io/bootstrap-datepicker-shamsi)

# Special Features

Defualt date can be Any Format in Any Locale and Calendar.

# Required Libraries

## JQuery
## Twitter Bootstrap

# Thanks to

Persian date (great persian date library for js).
[Persian Date](https://github.com/babakhani/PersianDate) 


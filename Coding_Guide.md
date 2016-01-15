## Coding Guide

### jQuery handle ajax

```javscript
$.ajax({
    url: 'url', // if has form get form action
    type: 'POST', // POST, PUT, GET, DELETE,
    data: {
        // data
    },
    success: function(data) {
        if (data.status === 'ok') {
            // do something
        } else {
            // do something
        }
    },
    error: function(data) {
        // do something
    }
});
```


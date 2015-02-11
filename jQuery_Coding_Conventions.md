$.ajax({
    url: // API URL
    type: 'POST', // method: GET, POST, PUT, DELETE
    data: {
        // data
    },
    success: function(data) {
        // console.log(data);
        if (data.status === 'ok') {
            // do something
        } else {
            // do something
        }
    },
    error: function(data) {
        console.log(data);
    }
});

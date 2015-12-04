# gulp-http-server
Auto-detective unused port, and create http server by nodejs.


###Using at gulp:

    var createServer = require('smart-http-server');
    
    gulp.task('http-server', function () {
        createServer();
    });
cp = require 'child_process'

task 'test','run tests', ->
  cp.spawn "./node_modules/mocha/bin/mocha"
    ,[ "--compilers","coffee:coffee-script/register","test/"]
    ,{ stdio: 'inherit' }
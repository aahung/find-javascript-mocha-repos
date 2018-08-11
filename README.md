# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:47 08/11/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43135 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41104 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39616 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30068 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25660 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24443 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23115 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19684 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18927 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16765 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16512 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15124 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14319 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13923 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13420 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13106 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12670 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12617 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12294 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12235 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11754 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11459 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11107 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11096 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10414 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10087 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 10086 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10080 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 10011 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9937 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9568 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9356 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9312 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9063 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9007 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8977 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8689 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8667 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8617 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8485 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8438 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8423 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8298 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8215 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8159 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8051 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7948 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7889 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7711 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7687 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7552 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7551 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7419 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7213 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7190 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7181 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7030 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7000 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6963 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6879 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6808 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6436 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6375 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6313 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6240 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6212 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6171 | `mocha test/test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6063 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6049 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5959 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5886 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5812 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5799 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5717 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5685 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5596 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5594 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5583 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5410 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5311 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5260 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5175 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5151 | `mocha --color` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5118 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5078 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4960 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4951 | `gulp lint && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4937 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4839 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4737 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4736 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4732 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4728 | `mocha -R spec 'tests/app'` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4726 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4694 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4604 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4529 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4461 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4431 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4406 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4405 | `mocha --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4399 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4391 | `npm run lint && npm run mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3848 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3840 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3765 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3761 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3700 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3666 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3651 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3607 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3576 | `mocha tests/javascript` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3574 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3548 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3539 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3523 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3515 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3500 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3459 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3454 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3437 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3428 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3392 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3389 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3327 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3232 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3228 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3226 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3219 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3168 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3163 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3148 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3142 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3140 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3128 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3109 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3064 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2967 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2951 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2928 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2888 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2885 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2876 | `mocha -R spec --recursive src/test` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2869 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2862 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2860 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2826 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2816 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2813 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2802 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2785 | `mocha -R landing test/index` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2770 | `mocha --require should --reporter spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2766 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2722 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2720 | `mocha --reporter dot` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2716 | `mocha -R spec spec spec/reporters` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2705 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2671 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2646 | `mocha --timeout 100000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2639 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2626 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2609 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2605 | `eslint . && mocha -t 5000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2597 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2585 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2534 | `nyc mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2605 | `eslint . && mocha -t 5000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2601 | `npm run build && cd test && mocha . --reporter dot` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2597 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2569 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2534 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2519 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2506 | `mocha "test/**/*-test.js"` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2497 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2452 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2443 | `mocha test/src/**/*.unit.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2440 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2438 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2434 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2412 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2411 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2534 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2519 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2506 | `mocha "test/**/*-test.js"` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2497 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2471 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2452 | `mocha test` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2443 | `mocha test/unit --require mochahook` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2443 | `mocha test/src/**/*.unit.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2440 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2438 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2434 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2412 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2411 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2406 | `mocha --no-colors --reporter spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2172 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2135 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2123 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2107 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2097 | `standard && mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2045 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2044 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2044 | `nyc npm run _mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2143 | `cross-env BABEL_ENV=test mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2135 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2123 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2107 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2102 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2097 | `standard && mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2068 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2045 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2044 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2068 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2045 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2044 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2044 | `nyc npm run _mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1982 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1979 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1969 | `mocha --compilers js:babel-core/register __tests__` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2011 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1982 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1979 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1969 | `mocha --compilers js:babel-core/register __tests__` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1967 | `mocha -c test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1965 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1962 | `mocha --require=test/test_helper.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1961 | `mocha && eslint *.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1959 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1943 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1933 | `./node_modules/.bin/mocha && npm run jshint` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1929 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1926 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1918 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1916 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1911 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1911 | `npm run lint && mocha -R dot && npm run cover` | 
| [pahen/madge](https://github.com/pahen/madge) | 1908 | `npm run lint && npm run mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1908 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1883 | `mocha test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1874 | `mocha tests.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1864 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1834 | `mocha --reporter spec && npm run test-typescript` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1818 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1816 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1804 | `mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1800 | `mocha test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1799 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1797 | `mocha && npm run lint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1795 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1791 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1789 | `mocha test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1787 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1779 | `mocha --reporter spec --grep .` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1778 | `mocha --compilers js:babel-register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1777 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1759 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1752 | `mocha test/**/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1739 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1731 | `mocha test -u bdd -R spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1703 | `./node_modules/.bin/mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1699 | `mocha ./test/basic.js -t 5000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1690 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1686 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1684 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1676 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1671 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1667 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1660 | `npm run lint && npm run mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1657 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1657 | `mocha test/* --reporter spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1651 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1599 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1591 | `mocha test/setup.js test/spec/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1586 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1569 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1566 | `eslint --cache . && tsc && mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1566 | `mocha test` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1563 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1559 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [zeit/ms](https://github.com/zeit/ms) | 1559 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1557 | `standard "./src/*.js" && mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1542 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1482 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1473 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1452 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1442 | `nyc mocha --timeout=20000 test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1504 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1499 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1497 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1482 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 1473 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1452 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1473 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1452 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1442 | `nyc mocha --timeout=20000 test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1416 | `mocha --timeout 10000 ./tests/lib.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1412 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1407 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1407 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1380 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1379 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1376 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1374 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1369 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1367 | `mocha test/unit` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1362 | `npm run build && mocha -r should` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1358 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1354 | `TEST=all mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1347 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1347 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1345 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1345 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1334 | `mocha --opts test/opts/mocha.opts` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1332 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1329 | `istanbul cover _mocha test -- --timeout 20000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1327 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1322 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1322 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1320 | `./node_modules/.bin/mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1319 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1319 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1316 | `mocha tests/test-*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1312 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1309 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1306 | `standard && istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1302 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1297 | `mocha --reporter dot` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1284 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1284 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1275 | `NODE_ENV=test mocha tests/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1271 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1269 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1262 | `mocha ./test/test*.js --reporter spec` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1261 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1258 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1256 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1254 | `mocha -R spec ./test/unit/**` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1251 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1250 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1249 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1249 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1247 | `mocha test/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1241 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1230 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1229 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1224 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1220 | `mocha src/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1220 | `mocha src/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1216 | `npm run prepublishOnly && mocha test/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1216 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1216 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1215 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1213 | `mocha --recursive test/bin` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1204 | `npm run lint && npm run mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1198 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1197 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1191 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1168 | `mocha --compilers js:babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1168 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1155 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1153 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1151 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1149 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1144 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1140 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1132 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1129 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1127 | `webpack && npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1126 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1149 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1144 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1140 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1132 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1129 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1127 | `webpack && npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1126 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1123 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1119 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1117 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1116 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1114 | `istanbul cover _mocha test/*.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1110 | `npm run lint && mocha --require @babel/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1107 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1106 | `npm run mocha:istanbul` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1106 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1103 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1102 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [router5/router5](https://github.com/router5/router5) | 1101 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1092 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1089 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1087 | `mocha --timeout 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1081 | `mocha --compilers js:babel-register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1065 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1064 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1059 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1054 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1051 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1044 | `mocha --reporter spec --bail --check-leaks test/` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1041 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1038 | `standard && mocha -b` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1036 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1035 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1025 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tomas/needle](https://github.com/tomas/needle) | 1020 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1020 | `eslint src test && mocha --compilers babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1019 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1014 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1011 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1009 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1004 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1001 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1001 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1009 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1004 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1001 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1001 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 983 | `mocha -R list` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 982 | `npm run convertto:es5 && npm run mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 960 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 952 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 948 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 944 | `mocha --recursive -r tests/setup tests` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 943 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 940 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 938 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 937 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 934 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 934 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 928 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 925 | `npm run lint && mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 920 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 917 | `mocha ./test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 915 | `mocha tests` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 913 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 910 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 909 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 909 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 900 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 897 | `mocha -t 600000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 886 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 885 | `node_modules/.bin/mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 884 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 882 | `mocha test` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 879 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 875 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 871 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 868 | `./node_modules/.bin/mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 866 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 865 | `./node_modules/.bin/mocha -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 865 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 864 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 862 | `mocha -t 5000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 860 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 855 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 855 | `standard && standard ./bin/* && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 853 | `mocha test --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 851 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 853 | `mocha test --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 851 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 848 | `nyc --check-coverage mocha test/*.test.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 841 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 840 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 840 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 840 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 839 | `mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 839 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 837 | `mocha --reporter list` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 836 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 832 | `mocha --recursive ./test/*_spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 809 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 807 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 806 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 805 | `mocha --async-only` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 796 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 795 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 793 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 789 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 786 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 786 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 811 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 809 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 807 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 806 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 805 | `mocha --async-only` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 795 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 796 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 795 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 793 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 789 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 789 | `mocha --harmony --full-trace --check-leaks` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 786 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 786 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 785 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 785 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 785 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 783 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 783 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 782 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 780 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 780 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 780 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 774 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 773 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 771 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 766 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 765 | `mocha --no-timeouts` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 758 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 758 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 756 | `mocha --recursive -s 15 test/` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 752 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 752 | `mocha -r should --reporter spec test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 751 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 751 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 743 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 741 | `./node_modules/.bin/mocha test/**/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 740 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 740 | `npm run lint && npm run mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 739 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 738 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 737 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 737 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 737 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 736 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 735 | `mocha tests/*.mocha.js` | 
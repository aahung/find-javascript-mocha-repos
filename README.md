# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:05 03/12/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39966 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39815 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 37103 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28942 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23515 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22421 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21046 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20275 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17988 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17700 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15690 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15078 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13883 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13351 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12806 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12220 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12158 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12034 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11819 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11755 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11591 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11266 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10739 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10698 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10205 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9813 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9697 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9399 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9398 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9362 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9224 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9167 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8937 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8608 | `grunt mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8460 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8459 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8179 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8168 | `mocha test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8152 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8102 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7926 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [websockets/ws](https://github.com/websockets/ws) | 7899 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7890 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7794 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7774 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7683 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7632 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [dthree/cash](https://github.com/dthree/cash) | 7461 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7388 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7387 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7200 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7187 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7030 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7004 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6811 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6585 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6551 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6515 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6485 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6483 | `nyc mocha test/**/* -r ./test/before` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6465 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6392 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6379 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6359 | `mocha --compilers js:babel-core/register` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6001 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5993 | `npm run lint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5895 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5887 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5859 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5765 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5607 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5526 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5520 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5435 | `mocha && eslint lib/**` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5407 | `mocha test/test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5393 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5390 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5258 | `mocha --exit --require babel-core/register` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5166 | `mocha --color` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5163 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5139 | `mocha src/**/*Tests.js --harmony` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5101 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5042 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5019 | `npm run build-cli && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4800 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4788 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4754 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4746 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4666 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4644 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4624 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4622 | `mocha -R spec 'tests/app'` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4555 | `standard && mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4535 | `mocha ./test/runner.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4524 | `gulp build; mocha;` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4506 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4452 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4446 | `mocha; jshint *.js lib` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4425 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4394 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4364 | `./node_modules/.bin/mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4361 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4227 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4227 | `mocha test` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4222 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4216 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4099 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4017 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3942 | `mocha --recursive && make test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3914 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3894 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3875 | `NODE_ENV=test mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3870 | `mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3853 | `export TESTING=true; mocha --reporter list` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3816 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3809 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3804 | `mocha --require should --reporter spec` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3785 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3685 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3684 | `mocha -R spec ./test` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3650 | `npm run lint ; mocha && mocha test/individual` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3622 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3605 | `mocha ./test/*.spec.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3572 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3557 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3547 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3547 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3541 | `mocha tests/javascript` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3515 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3489 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3460 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3441 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3409 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3402 | `node_modules/.bin/mocha test/lib/` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3399 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3399 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3382 | `npm run lint && npm run mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3367 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3341 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3300 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3230 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3190 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3182 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3172 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3131 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3122 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3101 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3072 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3069 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3061 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3024 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2991 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2980 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2979 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2976 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2944 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2935 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2898 | `mocha test/*.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2864 | `NODE_ENV=test mocha test/**/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2858 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2817 | `nyc mocha && tsc` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2809 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2795 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2794 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2787 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2769 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2769 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2768 | `mocha -R spec --recursive src/test` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2760 | `mocha --require should --reporter spec` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2758 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2753 | `mocha test/index.js && npm run demo` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2742 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2742 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2738 | `istanbul cover _mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2735 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2696 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2694 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2690 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2683 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2676 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2669 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2648 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2647 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2641 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2631 | `xo && mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2617 | `mocha --opts mocha.opts` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2616 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2614 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2600 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2597 | `mocha --timeout 100000` | 
| [css/csso](https://github.com/css/csso) | 2586 | `mocha --reporter dot` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2584 | `mocha-phantomjs ./test/index.html` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2578 | `npm run mocha && npm run lint` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2552 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2543 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2527 | `mocha --recursive --watch` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2525 | `mocha --compilers js:babel-register --recursive spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2518 | `export TESTING=true; mocha --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2512 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2509 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2509 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2491 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2465 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2461 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2442 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2430 | `mocha --reporter=spec test/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2407 | `NODE_ENV=test mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2402 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2393 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2378 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2371 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2357 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2345 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2340 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2332 | `mocha --no-colors --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2331 | `nyc mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2330 | `grunt jshint && mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2328 | `npm run build && cd test && mocha . --reporter dot` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2325 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2312 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2309 | `mocha test` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2264 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2261 | `nyc --reporter=html --reporter=text mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2247 | `npm run lint && mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2229 | `export TESTING=true; mocha --reporter list` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2226 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2224 | `mocha test/unit --require mochahook` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2224 | `mocha test test/unit/**/*_test.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2222 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2220 | `mocha "test/**/*-test.js"` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2218 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2215 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2206 | `npm run lint && npm run build && npm run mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2202 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2201 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2201 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2174 | `mocha -R spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2167 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [gajus/swing](https://github.com/gajus/swing) | 2141 | `mocha --compilers js:babel-register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2093 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2085 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2084 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2075 | `mocha test.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2066 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2047 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2042 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2024 | `mocha -R landing test/index` | 
| [noble/noble](https://github.com/noble/noble) | 2018 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2017 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2016 | `mocha && eslint .` | 
| [slate/slate](https://github.com/slate/slate) | 2014 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1970 | `mocha test && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1934 | `mocha --require=test/test_helper.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1930 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1930 | `standard && mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1909 | `mocha -c test/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1903 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1901 | `mocha --bail --reporter spec --check-leaks test/` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1898 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 1890 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1887 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1884 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1876 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1860 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1856 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1849 | `mocha tests.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1845 | `mocha --reporter spec --timeout 5000` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1829 | `mocha test/runner.js --reporter spec` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1819 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1811 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1799 | `cross-env NODE_ENV=test mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1790 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [then/promise](https://github.com/then/promise) | 1788 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1787 | `mocha --compilers js:babel-core/register __tests__` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1784 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1779 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1775 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1774 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1767 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1755 | `mocha test` | 
| [kach/nearley](https://github.com/kach/nearley) | 1752 | `mocha test/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1746 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1742 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1733 | `npm run lint && mocha -R dot && npm run cover` | 
| [share/sharedb](https://github.com/share/sharedb) | 1732 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1724 | `mocha && eslint *.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1723 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1717 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1716 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1707 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1706 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1706 | `mocha -R spec spec spec/reporters` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1706 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1697 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1690 | `mocha --reporter spec && npm run test-typescript` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1689 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1688 | `npm run mocha && npm run karma` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1688 | `npm run lint && mocha server/test --recursive --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1681 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1675 | `nyc npm run _mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1668 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1668 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1661 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1645 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1623 | `mocha && npm run lint` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1619 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1614 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1606 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1604 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1601 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1594 | `mocha --reporter spec --grep .` | 
| [pahen/madge](https://github.com/pahen/madge) | 1584 | `npm run lint && npm run mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1584 | `mocha test/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1580 | `npm run lint && mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1577 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1574 | `mocha tests --compilers js:babel-core/register` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1573 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1573 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1567 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1564 | `mocha test/**/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1550 | `mocha ./test/basic.js -t 5000` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1543 | `mocha --reporter spec test/*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1539 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1538 | `mocha test --timeout 600000` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1537 | `mocha spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1537 | `mocha test/* --reporter spec` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1520 | `standard "src/*.js" && npm run build && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1507 | `npm run lint && npm run mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1503 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1503 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1497 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1495 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1484 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1479 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1473 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1459 | `mocha --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1457 | `mocha --reporter spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1457 | `node_modules/.bin/mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1438 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1432 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1424 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1414 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1409 | `mocha test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1407 | `eslint --cache . && tsc && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1405 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1403 | `mocha --check-leaks -R dot` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1402 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1401 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1400 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1393 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1387 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1383 | `standard "./src/*.js" && mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1367 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1366 | `eslint . && mocha -t 5000` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1359 | `mocha --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1356 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1352 | `./node_modules/mocha/bin/mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1349 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1344 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1341 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1332 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1330 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1329 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1323 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1323 | `mocha compiled_tests/` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1315 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1304 | `mocha test/setup.js test/spec/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1302 | `nyc npm run mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1295 | `mocha-phantomjs tests/index.html` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1294 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1293 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1287 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1286 | `npm run build && mocha -r should` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1263 | `./node_modules/.bin/mocha test` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1249 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1249 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1249 | `mocha spec/exec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1247 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1245 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1242 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1235 | `istanbul cover _mocha test -- --timeout 20000` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1221 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1220 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1213 | `mocha tests` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1213 | `mocha --check-leaks --require @babel/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1211 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1206 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1206 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1202 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1200 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1196 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1194 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1190 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1189 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1188 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1185 | `mocha --opts test/opts/mocha.opts` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1185 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1173 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1172 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1171 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1166 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1166 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [teambit/bit](https://github.com/teambit/bit) | 1161 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1151 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1150 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1149 | `mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1146 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1136 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1130 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1130 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1128 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1127 | `standard && istanbul cover _mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1122 | `mocha --reporter dot` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1116 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1115 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1115 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1115 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1112 | `node_modules/.bin/mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1111 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1110 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1109 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1108 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1107 | `mocha test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1107 | `eslint src && mocha && karma start --single-run` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1100 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1098 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1096 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1088 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1088 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1083 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1081 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1081 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1072 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1070 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1068 | `mocha test/*` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1065 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1061 | `xo && mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1060 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1058 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1054 | `nyc mocha --timeout=20000 test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1051 | `mocha --check-leaks --reporter spec --bail test/` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1050 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1047 | `mocha tests/test-*` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1044 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1036 | `istanbul test _mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1028 | `istanbul cover _mocha test/*.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1028 | `NODE_PATH=. mocha **/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1021 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1018 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1017 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1016 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1015 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1008 | `mocha test/tests.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1003 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1003 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 995 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 990 | `npm run prepublishOnly && mocha test/test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 988 | `mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 987 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 983 | `standard && mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 980 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 978 | `mocha --recursive --bail --reporter spec test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 972 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 971 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 969 | `mocha --recursive test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 968 | `npm run rollup-cjs && mocha test/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 966 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 963 | `mocha --compilers js:babel-core/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 961 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 958 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 957 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 957 | `mocha -R list` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 955 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 955 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 953 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 952 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 951 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 945 | `mocha test` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 945 | `mocha -t 120000 test/*.test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 944 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 944 | `mocha --reporter spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 942 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 941 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 940 | `webpack && mocha test/unit` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 940 | `standard && mocha -b` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 937 | `mocha -R spec ./test/unit/**` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 934 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [electron/asar](https://github.com/electron/asar) | 933 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 930 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 925 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 922 | `mocha tests/*.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 921 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 914 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 913 | `eslint src test && mocha --compilers babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 911 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 910 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 907 | `mocha ./test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 903 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 899 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 898 | `npm run lint && npm run mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 898 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 893 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 891 | `mocha "client.test" --compilers js:babel-register` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 891 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 889 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 885 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 883 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 875 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 874 | `mocha --compilers js:babel-register test/*.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 874 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 867 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 863 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 863 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 857 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 856 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 856 | `mocha ./test -R spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 853 | `node_modules/.bin/mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 853 | `npm run convertto:es5 && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 851 | `npm run lint && mocha --require @babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 849 | `npm run lint && mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 848 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 843 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 842 | `npm run lint && npm run mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 837 | `mocha tests` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 837 | `mocha --timeout 200000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 835 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 834 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 831 | `node_modules/.bin/mocha test/spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 830 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 825 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 824 | `mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 818 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 816 | `mocha --reporter spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 815 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 814 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 812 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 807 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 804 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 804 | `standard && standard ./bin/* && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 803 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 802 | `mocha -t 600000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 801 | `istanbul cover _mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 797 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 797 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 796 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 796 | `mocha --require babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 795 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 794 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 794 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 793 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 793 | `mocha test --compilers js:babel-register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 791 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 789 | `mocha --reporter spec --bail --check-leaks test/` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 788 | `mocha -t 5000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 786 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 783 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 783 | `istanbul cover -- _mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 782 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 782 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 778 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 777 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 776 | `mocha --colors --reporter spec test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 772 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 771 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 769 | `mocha --reporter list` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 769 | `mocha spec/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 767 | `npm run mocha:istanbul` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 766 | `npm run lint && mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 766 | `./node_modules/.bin/mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 765 | `mocha --async-only` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 761 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 761 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 757 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 753 | `mocha --ui tdd --require ./test/__setup` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 751 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 750 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 741 | `mocha -R spec src/**/*_test.js` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 741 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 739 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 734 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 732 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 728 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 728 | `mocha --recursive -s 15 test/` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 727 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 725 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 725 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 721 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 721 | `mocha test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 717 | `npm run mocha-test test/integration` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 715 | `mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 713 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 711 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 710 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [developit/decko](https://github.com/developit/decko) | 708 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 706 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 706 | `npm run build && istanbul test _mocha test/test.js` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 706 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 705 | `mocha tests/*.mocha.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 702 | `npm run bundle && mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 700 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 699 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 697 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 695 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 695 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 694 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 694 | `mocha` | 
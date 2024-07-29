# ghost-docker-cjk-korean

NavyStack@5700X:~/ghost$ yarn test
yarn run v1.22.22
$ nx run-many -t test
 
    ✔  nx run @tryghost/member-events:test (902ms)
    ✔  nx run @tryghost/admin-x-design-system:test  [existing outputs match the cache, left as is]
    ✔  nx run @tryghost/domain-events:test (958ms)
    ✔  nx run @tryghost/in-memory-repository:test (3s)
    ✔  nx run @tryghost/post-events:test (2s)
    ✔  nx run @tryghost/admin-x-framework:test  [existing outputs match the cache, left as is]
    ✔  nx run @tryghost/members-csv:test (826ms)
    ✔  nx run @tryghost/nql-filter-expansions:test (2s)
    ✔  nx run @tryghost/referrers:test (847ms)
    ✔  nx run @tryghost/i18n:test (5s)
    ✔  nx run @tryghost/members-offers:test (1s)
    ✔  nx run @tryghost/tiers:test (1s)
    ✔  nx run @tryghost/version-notifications-data-service:test (896ms)
    ✔  nx run @tryghost/email-content-generator:test (840ms)
    ✔  nx run @tryghost/email-analytics-service:test (1s)
    ✔  nx run @tryghost/member-attribution:test (958ms)
    ✔  nx run @tryghost/html-to-plaintext:test (875ms)
    ✔  nx run @tryghost/extract-api-key:test (736ms)
    ✔  nx run @tryghost/bookshelf-repository:test (3s)
    ✔  nx run @tryghost/mailgun-client:test (1s)
    ✔  nx run @tryghost/link-redirects:test (934ms)
    ✔  nx run @tryghost/email-addresses:test (2s)
    ✔  nx run @tryghost/email-events:test (836ms)
    ✔  nx run @tryghost/magic-link:test (971ms)
    ✔  nx run @tryghost/constants:test (856ms)
    ✔  nx run @tryghost/members-payments:test (1s)
    ✔  nx run @tryghost/api-version-compatibility-service:test (966ms)
    ✔  nx run @tryghost/collections:test (4s)
    ✔  nx run @tryghost/model-to-domain-event-interceptor:test (3s)
    ✔  nx run @tryghost/email-analytics-provider-mailgun:test (971ms)
    ✔  nx run @tryghost/importer-handler-content-files:test (807ms)
    ✔  nx run @tryghost/express-dynamic-redirects:test (845ms)
    ✔  nx run @tryghost/custom-theme-settings-service:test (1s)
    ✔  nx run @tryghost/announcement-bar-settings:test (790ms)
    ✔  nx run @tryghost/mw-api-version-mismatch:test (916ms)
    ✔  nx run @tryghost/dynamic-routing-events:test (807ms)

    ✖  nx run @tryghost/external-media-inliner:test
$ yarn test:unit
$ NODE_ENV=testing c8 --all --check-coverage --100  --reporter text --reporter cobertura -- mocha --reporter dot './test/**/*.test.js'
       
       
         ..................!.....
       
         23 passing (307ms)
         1 failing
       
         1) ExternalMediaInliner
              Special URL & file type handling
                Handles URLs with unicode characters:
       
             AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:
       + actual - expected
       
       + '你好.png'
       - 'ni-hao.png'
             + expected - actual
       
             -你好.png
             +ni-hao.png
             
             at Context.<anonymous> (test/ExternalMediaInliner.test.js:753:20)
             at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
       
       
       
       ----------------------------|---------|----------|---------|---------|-------------------
       File                        | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
       ----------------------------|---------|----------|---------|---------|-------------------
       All files                   |     100 |      100 |     100 |     100 |                   
        external-media-inliner     |     100 |      100 |     100 |     100 |                   
         index.js                  |     100 |      100 |     100 |     100 |                   
        external-media-inliner/lib |     100 |      100 |     100 |     100 |                   
         ExternalMediaInliner.js   |     100 |      100 |     100 |     100 |                   
       ----------------------------|---------|----------|---------|---------|-------------------
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
       
       
    ✔  nx run @tryghost/email-suppression-list:test (655ms)
    ✔  nx run @tryghost/members-events-service:test (1s)
    ✔  nx run @tryghost/mentions-email-report:test (858ms)
    ✔  nx run @tryghost/settings-path-manager:test (919ms)
    ✔  nx run @tryghost/mw-session-from-token:test (897ms)
    ✔  nx run @tryghost/verification-trigger:test (984ms)
    ✔  nx run @tryghost/adapter-cache-redis:test (1s)
    ✔  nx run @tryghost/slack-notifications:test (1s)
    ✔  nx run @tryghost/update-check-service:test (2s)
    ✔  nx run @tryghost/audience-feedback:test (890ms)
    ✔  nx run @tryghost/mw-cache-control:test (877ms)
    ✔  nx run @tryghost/bootstrap-socket:test (918ms)
    ✔  nx run @tryghost/mw-version-match:test (955ms)
    ✔  nx run @tryghost/members-importer:test (1s)
    ✔  nx run @tryghost/mw-error-handler:test (958ms)
    ✔  nx run @tryghost/session-service:test (961ms)
    ✔  nx run @tryghost/adapter-manager:test (958ms)
    ✔  nx run @tryghost/importer-revue:test (938ms)
    ✔  nx run @tryghost/oembed-service:test (2s)
    ✔  nx run @tryghost/data-generator:test (2s)
    ✔  nx run @tryghost/api-framework:test (1s)
    ✔  nx run @tryghost/recommendations:test (5s)
    ✔  nx run @tryghost/post-revisions:test (3s)
    ✔  nx run @tryghost/posts-service:test (1s)
    ✔  nx run @tryghost/link-replacer:test (903ms)
    ✔  nx run @tryghost/staff-service:test (1s)
    ✔  nx run @tryghost/link-tracking:test (1s)
    ✔  nx run @tryghost/stats-service:test (3s)
    ✔  nx run @tryghost/package-json:test (979ms)
    ✔  nx run @tryghost/email-service:test (5s)
    ✔  nx run @tryghost/webmentions:test (2s)
    ✔  nx run @tryghost/mail-events:test (3s)
    ✔  nx run @tryghost/members-ssr:test (967ms)
    ✔  nx run @tryghost/members-api:test (2s)
    ✔  nx run @tryghost/milestones:test (1s)

    ✖  nx run @tryghost/security:test
$ yarn test:unit
$ NODE_ENV=testing c8 --all --reporter text --reporter cobertura -- mocha --reporter dot './test/**/*.test.js'
       
       
         ........!...!!......!.!........
       
         26 passing (82ms)
         5 failing
       
         1) Lib: Security - String
              Safe String
                can handle null strings:
            TypeError: Cannot read properties of null (reading 'normalize')
             at module.exports (/home/NavyStack/ghost/node_modules/@tryghost/string/lib/slugify.js:15:21)
             at Object.safe (lib/string.js:8:12)
             at Context.<anonymous> (test/string.test.js:14:44)
             at process.processImmediate (node:internal/timers:483:21)
       
         2) Lib: Security - String
              Safe String
                should replace all of the html4 compat symbols in ascii except hyphen and underscore:
       
             AssertionError: expected '¡¢-¤¥¦§-̈©a«¬®-̄°±23-́μ¶·-̧1o»1-41-23-4¿' to be '_-c-y-ss-c-a-r-deg-23up-1o-1-41-23-4'
             + expected - actual
       
             -¡¢-¤¥¦§-̈©a«¬®-̄°±23-́μ¶·-̧1o»1-41-23-4¿
             +_-c-y-ss-c-a-r-deg-23up-1o-1-41-23-4
             
             at Assertion.fail (/home/NavyStack/ghost/node_modules/should/cjs/should.js:275:17)
             at Assertion.value (/home/NavyStack/ghost/node_modules/should/cjs/should.js:356:19)
             at Context.<anonymous> (test/string.test.js:37:27)
             at process.processImmediate (node:internal/timers:483:21)
       
         3) Lib: Security - String
              Safe String
                should replace all of the foreign chars in ascii:
       
             AssertionError: expected 'àáâãäåæçèéêëìíîïðñòóôõö×øùúûüýþßàáâãäåæçèéêëìíîïðñòóôõö-øùúûüýþÿ' to be 'aaaaaaaeceeeeiiiidnoooooxouuuuuthssaaaaaaaeceeeeiiiidnooooo-ouuuuythy'
             + expected - actual
       
             -àáâãäåæçèéêëìíîïðñòóôõö×øùúûüýþßàáâãäåæçèéêëìíîïðñòóôõö-øùúûüýþÿ
             +aaaaaaaeceeeeiiiidnoooooxouuuuuthssaaaaaaaeceeeeiiiidnooooo-ouuuuythy
             
             at Assertion.fail (/home/NavyStack/ghost/node_modules/should/cjs/should.js:275:17)
             at Assertion.value (/home/NavyStack/ghost/node_modules/should/cjs/should.js:356:19)
             at Context.<anonymous> (test/string.test.js:42:27)
             at process.processImmediate (node:internal/timers:483:21)
       
         4) Lib: Security - String
              Safe String
                should properly handle unicode punctuation conversion:
       
             AssertionError: expected 'に間違いがないか-再度確認してください-再読み込みしてください' to be 'nijian-wei-iganaika-zai-du-que-ren-sitekudasai-zai-du-miip-misitekudasai'
             + expected - actual
       
             -に間違いがないか-再度確認してください-再読み込みしてください
             +nijian-wei-iganaika-zai-du-que-ren-sitekudasai-zai-du-miip-misitekudasai
             
             at Assertion.fail (/home/NavyStack/ghost/node_modules/should/cjs/should.js:275:17)
             at Assertion.value (/home/NavyStack/ghost/node_modules/should/cjs/should.js:356:19)
             at Context.<anonymous> (test/string.test.js:77:27)
             at process.processImmediate (node:internal/timers:483:21)
       
         5) Lib: Security - String
              Safe String
                should still remove/convert invalid characters when passed options with truthy importing flag:
       
             AssertionError: expected '-slug--with--invalid-characters-に' to be '-slug--with--invalid-characters-ni'
             + expected - actual
       
             --slug--with--invalid-characters-に
             +-slug--with--invalid-characters-ni
             
             at Assertion.fail (/home/NavyStack/ghost/node_modules/should/cjs/should.js:275:17)
             at Assertion.value (/home/NavyStack/ghost/node_modules/should/cjs/should.js:356:19)
             at Context.<anonymous> (test/string.test.js:87:27)
             at process.processImmediate (node:internal/timers:483:21)
       
       
       
       ----------------|---------|----------|---------|---------|--------------------------
       File            | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s        
       ----------------|---------|----------|---------|---------|--------------------------
       All files       |   78.29 |    84.61 |   77.77 |   78.29 |                          
        security       |      96 |      100 |   83.33 |      96 |                          
         index.js      |      96 |      100 |   83.33 |      96 | 15                       
        security/lib   |   76.39 |    81.81 |      75 |   76.39 |                          
         identifier.js |       0 |        0 |       0 |       0 | 1-25                     
         password.js   |     100 |      100 |     100 |     100 |                          
         secret.js     |     100 |      100 |     100 |     100 |                          
         string.js     |     100 |      100 |     100 |     100 |                          
         tokens.js     |   76.74 |    72.22 |      60 |   76.74 | 4-14,18-32,67-68,112-113 
         url.js        |     100 |      100 |     100 |     100 |                          
       ----------------|---------|----------|---------|---------|--------------------------
error Command failed with exit code 5.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed with exit code 5.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
       
       
    ✔  nx run @tryghost/job-manager:test (2s)
    ✔  nx run @tryghost/donations:test (2s)
    ✔  nx run @tryghost/mw-vhost:test (885ms)
    ✔  nx run @tryghost/minifier:test (1s)
    ✔  nx run @tryghost/members-stripe-service:test (1s)
    ✔  nx run @tryghost/mw-update-user-last-seen:test (906ms)
    ✔  nx run @tryghost/announcement-bar:test  [existing outputs match the cache, left as is]
    ✔  nx run @tryghost/adapter-cache-memory-ttl:test (914ms)
    ✔  nx run @tryghost/sodo-search:test  [existing outputs match the cache, left as is]
    ✔  nx run @tryghost/ghost:test (3s)
    ✔  nx run @tryghost/portal:test (10s)
    ✔  nx run @tryghost/comments-ui:test (14s)
    ✔  nx run ghost:test (13s)
    ✔  nx run ghost-admin:test (1m)

 —————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————

 >  NX   Ran target test for 87 projects (2m)
 
    ✔    85/87 succeeded [4 read from cache]
 
    ✖    2/87 targets failed, including the following:
         - nx run @tryghost/external-media-inliner:test
         - nx run @tryghost/security:test
 
   Hint: Try "nx view-logs" to get structured, searchable errors logs in your browser.
 
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
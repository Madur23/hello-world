# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.

_____________________________________________________
.github/workflows/nodejs.yml

2020-04-02T22:47:16.6823174Z ##[group]Run npm ci
2020-04-02T22:47:16.6823555Z [36;1mnpm ci[0m
2020-04-02T22:47:16.6869883Z shell: /bin/bash -e {0}
2020-04-02T22:47:16.6870077Z ##[endgroup]
2020-04-02T22:47:17.1336413Z npm ERR! code ENOENT
2020-04-02T22:47:17.1342145Z npm ERR! syscall open
2020-04-02T22:47:17.1343493Z npm ERR! path /home/runner/work/hello-world/hello-world/package.json
2020-04-02T22:47:17.1344143Z npm ERR! errno -2
2020-04-02T22:47:17.1353092Z npm ERR! enoent ENOENT: no such file or directory, open '/home/runner/work/hello-world/hello-world/package.json'
2020-04-02T22:47:17.1354056Z npm ERR! enoent This is related to npm not being able to find a file.
2020-04-02T22:47:17.1355075Z npm ERR! enoent 
2020-04-02T22:47:17.2802027Z 
2020-04-02T22:47:17.2802990Z npm ERR! A complete log of this run can be found in:
2020-04-02T22:47:17.2804622Z npm ERR!     /home/runner/.npm/_logs/2020-04-02T22_47_17_135Z-debug.log
2020-04-02T22:47:17.2859254Z ##[error]Process completed with exit code 254.
___________________________________

2020-04-02T22:47:17.2936753Z Post job cleanup.
2020-04-02T22:47:17.4029433Z [command]/usr/bin/git version
2020-04-02T22:47:17.4106617Z git version 2.25.2
2020-04-02T22:47:17.4162679Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:17.4205917Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:17.4505482Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:17.4542454Z http.https://github.com/.extraheader
2020-04-02T22:47:17.4552417Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2020-04-02T22:47:17.4592923Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :

2020-04-02T22:47:13.3436535Z ##[group]Run actions/setup-node@v1
2020-04-02T22:47:13.3436814Z with:
2020-04-02T22:47:13.3436953Z   node-version: 12.x
2020-04-02T22:47:13.3437182Z   always-auth: false
2020-04-02T22:47:13.3437398Z ##[endgroup]
2020-04-02T22:47:13.8826213Z [command]/bin/tar xz --warning=no-unknown-keyword -C /home/runner/work/_temp/2a199308-b2a9-4c9f-afbc-d4631ecd4e00 -f /home/runner/work/_temp/f55160d8-39d6-4cbd-b56b-9cc8085b681a

2020-04-02T22:47:09.8673301Z Current runner version: '2.168.0'
2020-04-02T22:47:09.8699193Z ##[group]Operating System
2020-04-02T22:47:09.8699948Z Ubuntu
2020-04-02T22:47:09.8700134Z 18.04.4
2020-04-02T22:47:09.8700291Z LTS
2020-04-02T22:47:09.8700401Z ##[endgroup]
2020-04-02T22:47:09.8700566Z ##[group]Virtual Environment
2020-04-02T22:47:09.8700750Z Environment: ubuntu-18.04
2020-04-02T22:47:09.8700954Z Version: 20200323.1
2020-04-02T22:47:09.8701145Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu18/20200323.1/images/linux/Ubuntu1804-README.md
2020-04-02T22:47:09.8701375Z ##[endgroup]
2020-04-02T22:47:09.8702435Z Prepare workflow directory
2020-04-02T22:47:09.8908401Z Prepare all required actions
2020-04-02T22:47:09.8919574Z Download action repository 'actions/checkout@v2'
2020-04-02T22:47:12.3470539Z Download action repository 'actions/setup-node@v1'

2020-04-02T22:47:12.5335028Z ##[group]Run actions/checkout@v2
2020-04-02T22:47:12.5335451Z with:
2020-04-02T22:47:12.5335806Z   repository: Madur23/hello-world
2020-04-02T22:47:12.5336217Z   token: ***
2020-04-02T22:47:12.5336430Z   ssh-strict: true
2020-04-02T22:47:12.5336618Z   persist-credentials: true
2020-04-02T22:47:12.5336865Z   clean: true
2020-04-02T22:47:12.5337000Z   fetch-depth: 1
2020-04-02T22:47:12.5337183Z   lfs: false
2020-04-02T22:47:12.5337368Z   submodules: false
2020-04-02T22:47:12.5337634Z ##[endgroup]
2020-04-02T22:47:13.3085815Z Syncing repository: Madur23/hello-world
2020-04-02T22:47:13.3086351Z ##[group]Getting Git version info
2020-04-02T22:47:13.3086934Z Working directory is '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.3087217Z [command]/usr/bin/git version
2020-04-02T22:47:13.3087700Z git version 2.25.2
2020-04-02T22:47:13.3088297Z ##[endgroup]
2020-04-02T22:47:13.3088709Z Deleting the contents of '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.3089396Z ##[group]Initializing the repository
2020-04-02T22:47:13.3089856Z [command]/usr/bin/git init /home/runner/work/hello-world/hello-world
2020-04-02T22:47:13.3090282Z Initialized empty Git repository in /home/runner/work/hello-world/hello-world/.git/
2020-04-02T22:47:13.3090837Z [command]/usr/bin/git remote add origin https://github.com/Madur23/hello-world
2020-04-02T22:47:13.3091246Z ##[endgroup]
2020-04-02T22:47:13.3092375Z ##[group]Disabling automatic garbage collection
2020-04-02T22:47:13.3092820Z [command]/usr/bin/git config --local gc.auto 0
2020-04-02T22:47:13.3093032Z ##[endgroup]
2020-04-02T22:47:13.3094597Z ##[group]Setting up auth
2020-04-02T22:47:13.3095215Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:13.3095783Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:13.3096290Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:13.3096960Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2020-04-02T22:47:13.3097462Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2020-04-02T22:47:13.3097908Z ##[endgroup]
2020-04-02T22:47:13.3098092Z ##[group]Fetching the repository
2020-04-02T22:47:13.3099409Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8:refs/remotes/origin/master
2020-04-02T22:47:13.3099694Z remote: Enumerating objects: 6, done.        
2020-04-02T22:47:13.3100003Z remote: Counting objects:  16% (1/6)        
2020-04-02T22:47:13.3100162Z remote: Counting objects:  33% (2/6)        
2020-04-02T22:47:13.3100374Z remote: Counting objects:  50% (3/6)        
2020-04-02T22:47:13.3100579Z remote: Counting objects:  66% (4/6)        
2020-04-02T22:47:13.3100764Z remote: Counting objects:  83% (5/6)        
2020-04-02T22:47:13.3101119Z remote: Counting objects: 100% (6/6)        
2020-04-02T22:47:13.3101308Z remote: Counting objects: 100% (6/6), done.        
2020-04-02T22:47:13.3101494Z remote: Compressing objects:  25% (1/4)        
2020-04-02T22:47:13.3101993Z remote: Compressing objects:  50% (2/4)        
2020-04-02T22:47:13.3102343Z remote: Compressing objects:  75% (3/4)        
2020-04-02T22:47:13.3102794Z remote: Compressing objects: 100% (4/4)        
2020-04-02T22:47:13.3103013Z remote: Compressing objects: 100% (4/4), done.        
2020-04-02T22:47:13.3103456Z remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0        
2020-04-02T22:47:13.3104623Z From https://github.com/Madur23/hello-world
2020-04-02T22:47:13.3105412Z  * [new ref]         f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8 -> origin/master
2020-04-02T22:47:13.3136502Z ##[endgroup]
2020-04-02T22:47:13.3137064Z ##[group]Determining the checkout info
2020-04-02T22:47:13.3137237Z ##[endgroup]
2020-04-02T22:47:13.3137470Z ##[group]Checking out the ref
2020-04-02T22:47:13.3141032Z [command]/usr/bin/git checkout --progress --force -B master refs/remotes/origin/master
2020-04-02T22:47:13.3210507Z Reset branch 'master'
2020-04-02T22:47:13.3232387Z Branch 'master' set up to track remote branch 'master' from 'origin'.
2020-04-02T22:47:13.3233004Z ##[endgroup]
2020-04-02T22:47:13.3233673Z [command]/usr/bin/git log -1
2020-04-02T22:47:13.3275628Z commit f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8
2020-04-02T22:47:13.3294633Z Author: Madur23 <63068360+Madur23@users.noreply.github.com>
2020-04-02T22:47:13.3295284Z Date:   Thu Apr 2 12:36:22 2020 -0700
2020-04-02T22:47:13.3295458Z 
2020-04-02T22:47:13.3295645Z     Create nodes.yml
2020-04-02T22:47:13.3295790Z     
2020-04-02T22:47:13.3295969Z     Release

2020-04-02T22:47:05.3581968Z ##[section]Starting: Request a runner to run this job
2020-04-02T22:47:05.5086745Z Requesting a hosted runner in current repository's account/organization with labels: 'ubuntu-latest', require runner match: True
2020-04-02T22:47:05.6419459Z Labels matched hosted runners has been found, waiting for one of them get assigned for this job.
2020-04-02T22:47:05.6726449Z ##[section]Finishing: Request a runner to run this job
2020-04-02T22:47:09.8674948Z Current runner version: '2.168.0'
2020-04-02T22:47:09.8699467Z ##[group]Operating System
2020-04-02T22:47:09.8699961Z Ubuntu
2020-04-02T22:47:09.8700141Z 18.04.4
2020-04-02T22:47:09.8700295Z LTS
2020-04-02T22:47:09.8700407Z ##[endgroup]
2020-04-02T22:47:09.8700571Z ##[group]Virtual Environment
2020-04-02T22:47:09.8700756Z Environment: ubuntu-18.04
2020-04-02T22:47:09.8700959Z Version: 20200323.1
2020-04-02T22:47:09.8701216Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu18/20200323.1/images/linux/Ubuntu1804-README.md
2020-04-02T22:47:09.8701382Z ##[endgroup]
2020-04-02T22:47:09.8702454Z Prepare workflow directory
2020-04-02T22:47:09.8908438Z Prepare all required actions
2020-04-02T22:47:09.8919599Z Download action repository 'actions/checkout@v2'
2020-04-02T22:47:12.3470565Z Download action repository 'actions/setup-node@v1'
2020-04-02T22:47:12.5335068Z ##[group]Run actions/checkout@v2
2020-04-02T22:47:12.5335465Z with:
2020-04-02T22:47:12.5335816Z   repository: Madur23/hello-world
2020-04-02T22:47:12.5336290Z   token: ***
2020-04-02T22:47:12.5336437Z   ssh-strict: true
2020-04-02T22:47:12.5336625Z   persist-credentials: true
2020-04-02T22:47:12.5336873Z   clean: true
2020-04-02T22:47:12.5337059Z   fetch-depth: 1
2020-04-02T22:47:12.5337189Z   lfs: false
2020-04-02T22:47:12.5337375Z   submodules: false
2020-04-02T22:47:12.5337640Z ##[endgroup]
2020-04-02T22:47:13.3085867Z Syncing repository: Madur23/hello-world
2020-04-02T22:47:13.3086368Z ##[group]Getting Git version info
2020-04-02T22:47:13.3086950Z Working directory is '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.3087226Z [command]/usr/bin/git version
2020-04-02T22:47:13.3087707Z git version 2.25.2
2020-04-02T22:47:13.3088310Z ##[endgroup]
2020-04-02T22:47:13.3088721Z Deleting the contents of '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.3089498Z ##[group]Initializing the repository
2020-04-02T22:47:13.3089866Z [command]/usr/bin/git init /home/runner/work/hello-world/hello-world
2020-04-02T22:47:13.3090293Z Initialized empty Git repository in /home/runner/work/hello-world/hello-world/.git/
2020-04-02T22:47:13.3090848Z [command]/usr/bin/git remote add origin https://github.com/Madur23/hello-world
2020-04-02T22:47:13.3091254Z ##[endgroup]
2020-04-02T22:47:13.3092389Z ##[group]Disabling automatic garbage collection
2020-04-02T22:47:13.3092832Z [command]/usr/bin/git config --local gc.auto 0
2020-04-02T22:47:13.3093037Z ##[endgroup]
2020-04-02T22:47:13.3094616Z ##[group]Setting up auth
2020-04-02T22:47:13.3095230Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:13.3095797Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:13.3096319Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:13.3096977Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2020-04-02T22:47:13.3097533Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2020-04-02T22:47:13.3097916Z ##[endgroup]
2020-04-02T22:47:13.3098098Z ##[group]Fetching the repository
2020-04-02T22:47:13.3099434Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8:refs/remotes/origin/master
2020-04-02T22:47:13.3099702Z remote: Enumerating objects: 6, done.        
2020-04-02T22:47:13.3100014Z remote: Counting objects:  16% (1/6)        
2020-04-02T22:47:13.3100168Z remote: Counting objects:  33% (2/6)        
2020-04-02T22:47:13.3100399Z remote: Counting objects:  50% (3/6)        
2020-04-02T22:47:13.3100586Z remote: Counting objects:  66% (4/6)        
2020-04-02T22:47:13.3100771Z remote: Counting objects:  83% (5/6)        
2020-04-02T22:47:13.3101172Z remote: Counting objects: 100% (6/6)        
2020-04-02T22:47:13.3101315Z remote: Counting objects: 100% (6/6), done.        
2020-04-02T22:47:13.3101502Z remote: Compressing objects:  25% (1/4)        
2020-04-02T22:47:13.3102003Z remote: Compressing objects:  50% (2/4)        
2020-04-02T22:47:13.3102514Z remote: Compressing objects:  75% (3/4)        
2020-04-02T22:47:13.3102886Z remote: Compressing objects: 100% (4/4)        
2020-04-02T22:47:13.3103019Z remote: Compressing objects: 100% (4/4), done.        
2020-04-02T22:47:13.3103469Z remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0        
2020-04-02T22:47:13.3104650Z From https://github.com/Madur23/hello-world
2020-04-02T22:47:13.3105434Z  * [new ref]         f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8 -> origin/master
2020-04-02T22:47:13.3136742Z ##[endgroup]
2020-04-02T22:47:13.3137076Z ##[group]Determining the checkout info
2020-04-02T22:47:13.3137244Z ##[endgroup]
2020-04-02T22:47:13.3137478Z ##[group]Checking out the ref
2020-04-02T22:47:13.3141061Z [command]/usr/bin/git checkout --progress --force -B master refs/remotes/origin/master
2020-04-02T22:47:13.3210553Z Reset branch 'master'
2020-04-02T22:47:13.3232424Z Branch 'master' set up to track remote branch 'master' from 'origin'.
2020-04-02T22:47:13.3233023Z ##[endgroup]
2020-04-02T22:47:13.3233688Z [command]/usr/bin/git log -1
2020-04-02T22:47:13.3275669Z commit f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8
2020-04-02T22:47:13.3294668Z Author: Madur23 <63068360+Madur23@users.noreply.github.com>
2020-04-02T22:47:13.3295302Z Date:   Thu Apr 2 12:36:22 2020 -0700
2020-04-02T22:47:13.3295467Z 
2020-04-02T22:47:13.3295653Z     Create nodes.yml
2020-04-02T22:47:13.3295797Z     
2020-04-02T22:47:13.3295976Z     Release
2020-04-02T22:47:13.3436567Z ##[group]Run actions/setup-node@v1
2020-04-02T22:47:13.3436822Z with:
2020-04-02T22:47:13.3436960Z   node-version: 12.x
2020-04-02T22:47:13.3437189Z   always-auth: false
2020-04-02T22:47:13.3437406Z ##[endgroup]
2020-04-02T22:47:13.8826486Z [command]/bin/tar xz --warning=no-unknown-keyword -C /home/runner/work/_temp/2a199308-b2a9-4c9f-afbc-d4631ecd4e00 -f /home/runner/work/_temp/f55160d8-39d6-4cbd-b56b-9cc8085b681a
2020-04-02T22:47:16.6823249Z ##[group]Run npm ci
2020-04-02T22:47:16.6823565Z [36;1mnpm ci[0m
2020-04-02T22:47:16.6869911Z shell: /bin/bash -e {0}
2020-04-02T22:47:16.6870083Z ##[endgroup]
2020-04-02T22:47:17.1336798Z npm ERR! code ENOENT
2020-04-02T22:47:17.1342172Z npm ERR! syscall open
2020-04-02T22:47:17.1343516Z npm ERR! path /home/runner/work/hello-world/hello-world/package.json
2020-04-02T22:47:17.1345055Z npm ERR! errno -2
2020-04-02T22:47:17.1353133Z npm ERR! enoent ENOENT: no such file or directory, open '/home/runner/work/hello-world/hello-world/package.json'
2020-04-02T22:47:17.1354076Z npm ERR! enoent This is related to npm not being able to find a file.
2020-04-02T22:47:17.1355098Z npm ERR! enoent 
2020-04-02T22:47:17.2802075Z 
2020-04-02T22:47:17.2803013Z npm ERR! A complete log of this run can be found in:
2020-04-02T22:47:17.2804654Z npm ERR!     /home/runner/.npm/_logs/2020-04-02T22_47_17_135Z-debug.log
2020-04-02T22:47:17.2859290Z ##[error]Process completed with exit code 254.
2020-04-02T22:47:17.2936785Z Post job cleanup.
2020-04-02T22:47:17.4029519Z [command]/usr/bin/git version
2020-04-02T22:47:17.4106677Z git version 2.25.2
2020-04-02T22:47:17.4162716Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:17.4205957Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:17.4505539Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:17.4542495Z http.https://github.com/.extraheader
2020-04-02T22:47:17.4552456Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2020-04-02T22:47:17.4593080Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2020-04-02T22:47:17.4943823Z Cleaning up orphan processes

2020-04-02T22:47:05.3590031Z ##[section]Starting: Request a runner to run this job
2020-04-02T22:47:05.5105786Z Requesting a hosted runner in current repository's account/organization with labels: 'ubuntu-latest', require runner match: True
2020-04-02T22:47:05.6436280Z Labels matched hosted runners has been found, waiting for one of them get assigned for this job.
2020-04-02T22:47:05.6736560Z ##[section]Finishing: Request a runner to run this job
2020-04-02T22:47:10.8742510Z Current runner version: '2.168.0'
2020-04-02T22:47:10.8763427Z ##[group]Operating System
2020-04-02T22:47:10.8763993Z Ubuntu
2020-04-02T22:47:10.8764114Z 18.04.4
2020-04-02T22:47:10.8764273Z LTS
2020-04-02T22:47:10.8764455Z ##[endgroup]
2020-04-02T22:47:10.8764619Z ##[group]Virtual Environment
2020-04-02T22:47:10.8764756Z Environment: ubuntu-18.04
2020-04-02T22:47:10.8764963Z Version: 20200323.1
2020-04-02T22:47:10.8765209Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu18/20200323.1/images/linux/Ubuntu1804-README.md
2020-04-02T22:47:10.8765418Z ##[endgroup]
2020-04-02T22:47:10.8766413Z Prepare workflow directory
2020-04-02T22:47:10.8945319Z Prepare all required actions
2020-04-02T22:47:10.8955288Z Download action repository 'actions/checkout@v2'
2020-04-02T22:47:12.8520019Z Download action repository 'actions/setup-node@v1'
2020-04-02T22:47:13.0585307Z ##[group]Run actions/checkout@v2
2020-04-02T22:47:13.0585743Z with:
2020-04-02T22:47:13.0586046Z   repository: Madur23/hello-world
2020-04-02T22:47:13.0586420Z   token: ***
2020-04-02T22:47:13.0586571Z   ssh-strict: true
2020-04-02T22:47:13.0586732Z   persist-credentials: true
2020-04-02T22:47:13.0586897Z   clean: true
2020-04-02T22:47:13.0587060Z   fetch-depth: 1
2020-04-02T22:47:13.0587201Z   lfs: false
2020-04-02T22:47:13.0587362Z   submodules: false
2020-04-02T22:47:13.0587523Z ##[endgroup]
2020-04-02T22:47:13.5035345Z Syncing repository: Madur23/hello-world
2020-04-02T22:47:13.5035963Z ##[group]Getting Git version info
2020-04-02T22:47:13.5036432Z Working directory is '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.5080611Z [command]/usr/bin/git version
2020-04-02T22:47:13.5247100Z git version 2.25.2
2020-04-02T22:47:13.5271814Z ##[endgroup]
2020-04-02T22:47:13.5282865Z Deleting the contents of '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.5285225Z ##[group]Initializing the repository
2020-04-02T22:47:13.5288488Z [command]/usr/bin/git init /home/runner/work/hello-world/hello-world
2020-04-02T22:47:13.5378662Z Initialized empty Git repository in /home/runner/work/hello-world/hello-world/.git/
2020-04-02T22:47:13.5392232Z [command]/usr/bin/git remote add origin https://github.com/Madur23/hello-world
2020-04-02T22:47:13.5439401Z ##[endgroup]
2020-04-02T22:47:13.5439851Z ##[group]Disabling automatic garbage collection
2020-04-02T22:47:13.5443661Z [command]/usr/bin/git config --local gc.auto 0
2020-04-02T22:47:13.5479623Z ##[endgroup]
2020-04-02T22:47:13.5486692Z ##[group]Setting up auth
2020-04-02T22:47:13.5495215Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:13.5526243Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:13.5949109Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:13.5988120Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2020-04-02T22:47:13.6304908Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2020-04-02T22:47:13.6357661Z ##[endgroup]
2020-04-02T22:47:13.6358202Z ##[group]Fetching the repository
2020-04-02T22:47:13.6368226Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8:refs/remotes/origin/master
2020-04-02T22:47:13.9388725Z remote: Enumerating objects: 6, done.        
2020-04-02T22:47:13.9389077Z remote: Counting objects:  16% (1/6)        
2020-04-02T22:47:13.9389237Z remote: Counting objects:  33% (2/6)        
2020-04-02T22:47:13.9389377Z remote: Counting objects:  50% (3/6)        
2020-04-02T22:47:13.9389485Z remote: Counting objects:  66% (4/6)        
2020-04-02T22:47:13.9389789Z remote: Counting objects:  83% (5/6)        
2020-04-02T22:47:13.9390326Z remote: Counting objects: 100% (6/6)        
2020-04-02T22:47:13.9390474Z remote: Counting objects: 100% (6/6), done.        
2020-04-02T22:47:13.9390614Z remote: Compressing objects:  25% (1/4)        
2020-04-02T22:47:13.9390748Z remote: Compressing objects:  50% (2/4)        
2020-04-02T22:47:13.9390883Z remote: Compressing objects:  75% (3/4)        
2020-04-02T22:47:13.9391015Z remote: Compressing objects: 100% (4/4)        
2020-04-02T22:47:13.9391109Z remote: Compressing objects: 100% (4/4), done.        
2020-04-02T22:47:13.9392044Z remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0        
2020-04-02T22:47:13.9392667Z From https://github.com/Madur23/hello-world
2020-04-02T22:47:13.9393253Z  * [new ref]         f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8 -> origin/master
2020-04-02T22:47:13.9393876Z ##[endgroup]
2020-04-02T22:47:13.9394272Z ##[group]Determining the checkout info
2020-04-02T22:47:13.9394552Z ##[endgroup]
2020-04-02T22:47:13.9394715Z ##[group]Checking out the ref
2020-04-02T22:47:13.9395120Z [command]/usr/bin/git checkout --progress --force -B master refs/remotes/origin/master
2020-04-02T22:47:13.9395644Z Reset branch 'master'
2020-04-02T22:47:13.9396174Z Branch 'master' set up to track remote branch 'master' from 'origin'.
2020-04-02T22:47:13.9396512Z ##[endgroup]
2020-04-02T22:47:13.9396868Z [command]/usr/bin/git log -1
2020-04-02T22:47:13.9397179Z commit f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8
2020-04-02T22:47:13.9397341Z Author: Madur23 <63068360+Madur23@users.noreply.github.com>
2020-04-02T22:47:13.9397655Z Date:   Thu Apr 2 12:36:22 2020 -0700
2020-04-02T22:47:13.9397904Z 
2020-04-02T22:47:13.9398021Z     Create nodes.yml
2020-04-02T22:47:13.9398271Z     
2020-04-02T22:47:13.9398736Z     Release
2020-04-02T22:47:13.9465522Z ##[group]Run actions/setup-node@v1
2020-04-02T22:47:13.9465973Z with:
2020-04-02T22:47:13.9466079Z   node-version: 10.x
2020-04-02T22:47:13.9466172Z   always-auth: false
2020-04-02T22:47:13.9466392Z ##[endgroup]
2020-04-02T22:47:15.8305001Z [command]/bin/tar xz --warning=no-unknown-keyword -C /home/runner/work/_temp/56e65197-4188-4806-9036-212c6fe891b7 -f /home/runner/work/_temp/6c2eeb69-ad7e-45d5-ae4c-49f04fa69890
2020-04-02T22:47:16.6759569Z ##[group]Run npm ci
2020-04-02T22:47:16.6759818Z [36;1mnpm ci[0m
2020-04-02T22:47:16.6801642Z shell: /bin/bash -e {0}
2020-04-02T22:47:16.6801756Z ##[endgroup]
2020-04-02T22:47:17.1942868Z npm ERR! code ENOENT
2020-04-02T22:47:17.1945721Z npm ERR! syscall open
2020-04-02T22:47:17.1947138Z npm ERR! path /home/runner/work/hello-world/hello-world/package.json
2020-04-02T22:47:17.1948058Z npm ERR! errno -2
2020-04-02T22:47:17.1952268Z npm ERR! enoent ENOENT: no such file or directory, open '/home/runner/work/hello-world/hello-world/package.json'
2020-04-02T22:47:17.1953067Z npm ERR! enoent This is related to npm not being able to find a file.
2020-04-02T22:47:17.1953557Z npm ERR! enoent 
2020-04-02T22:47:17.3218122Z 
2020-04-02T22:47:17.3221296Z npm ERR! A complete log of this run can be found in:
2020-04-02T22:47:17.3224287Z npm ERR!     /home/runner/.npm/_logs/2020-04-02T22_47_17_195Z-debug.log
2020-04-02T22:47:17.3276429Z ##[error]Process completed with exit code 254.
2020-04-02T22:47:17.3349798Z Post job cleanup.
2020-04-02T22:47:17.4413034Z [command]/usr/bin/git version
2020-04-02T22:47:17.4462861Z git version 2.25.2
2020-04-02T22:47:17.4499409Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:17.4532618Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:17.4788545Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:17.4814318Z http.https://github.com/.extraheader
2020-04-02T22:47:17.4826666Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2020-04-02T22:47:17.4856253Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2020-04-02T22:47:17.5145860Z Cleaning up orphan processes

2020-04-02T22:47:16.6759484Z ##[group]Run npm ci
2020-04-02T22:47:16.6759809Z [36;1mnpm ci[0m
2020-04-02T22:47:16.6801616Z shell: /bin/bash -e {0}
2020-04-02T22:47:16.6801751Z ##[endgroup]
2020-04-02T22:47:17.1942461Z npm ERR! code ENOENT
2020-04-02T22:47:17.1945688Z npm ERR! syscall open
2020-04-02T22:47:17.1947112Z npm ERR! path /home/runner/work/hello-world/hello-world/package.json
2020-04-02T22:47:17.1948033Z npm ERR! errno -2
2020-04-02T22:47:17.1952237Z npm ERR! enoent ENOENT: no such file or directory, open '/home/runner/work/hello-world/hello-world/package.json'
2020-04-02T22:47:17.1953025Z npm ERR! enoent This is related to npm not being able to find a file.
2020-04-02T22:47:17.1953540Z npm ERR! enoent 
2020-04-02T22:47:17.3218010Z 
2020-04-02T22:47:17.3221260Z npm ERR! A complete log of this run can be found in:
2020-04-02T22:47:17.3224251Z npm ERR!     /home/runner/.npm/_logs/2020-04-02T22_47_17_195Z-debug.log
2020-04-02T22:47:17.3276386Z ##[error]Process completed with exit code 254.

2020-04-02T22:47:17.3349764Z Post job cleanup.
2020-04-02T22:47:17.4412993Z [command]/usr/bin/git version
2020-04-02T22:47:17.4462823Z git version 2.25.2
2020-04-02T22:47:17.4499381Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:17.4532585Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:17.4788505Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:17.4814286Z http.https://github.com/.extraheader
2020-04-02T22:47:17.4826633Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2020-04-02T22:47:17.4856196Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :

2020-04-02T22:47:13.9465491Z ##[group]Run actions/setup-node@v1
2020-04-02T22:47:13.9465960Z with:
2020-04-02T22:47:13.9466074Z   node-version: 10.x
2020-04-02T22:47:13.9466167Z   always-auth: false
2020-04-02T22:47:13.9466387Z ##[endgroup]
2020-04-02T22:47:15.8304960Z [command]/bin/tar xz --warning=no-unknown-keyword -C /home/runner/work/_temp/56e65197-4188-4806-9036-212c6fe891b7 -f /home/runner/work/_temp/6c2eeb69-ad7e-45d5-ae4c-49f04fa69890

2020-04-02T22:47:10.8741881Z Current runner version: '2.168.0'
2020-04-02T22:47:10.8763391Z ##[group]Operating System
2020-04-02T22:47:10.8763976Z Ubuntu
2020-04-02T22:47:10.8764109Z 18.04.4
2020-04-02T22:47:10.8764267Z LTS
2020-04-02T22:47:10.8764448Z ##[endgroup]
2020-04-02T22:47:10.8764612Z ##[group]Virtual Environment
2020-04-02T22:47:10.8764750Z Environment: ubuntu-18.04
2020-04-02T22:47:10.8764955Z Version: 20200323.1
2020-04-02T22:47:10.8765201Z Included Software: https://github.com/actions/virtual-environments/blob/ubuntu18/20200323.1/images/linux/Ubuntu1804-README.md
2020-04-02T22:47:10.8765411Z ##[endgroup]
2020-04-02T22:47:10.8766391Z Prepare workflow directory
2020-04-02T22:47:10.8945285Z Prepare all required actions
2020-04-02T22:47:10.8955263Z Download action repository 'actions/checkout@v2'
2020-04-02T22:47:12.8519981Z Download action repository 'actions/setup-node@v1'

2020-04-02T22:47:13.0585269Z ##[group]Run actions/checkout@v2
2020-04-02T22:47:13.0585729Z with:
2020-04-02T22:47:13.0586036Z   repository: Madur23/hello-world
2020-04-02T22:47:13.0586410Z   token: ***
2020-04-02T22:47:13.0586564Z   ssh-strict: true
2020-04-02T22:47:13.0586725Z   persist-credentials: true
2020-04-02T22:47:13.0586891Z   clean: true
2020-04-02T22:47:13.0587053Z   fetch-depth: 1
2020-04-02T22:47:13.0587194Z   lfs: false
2020-04-02T22:47:13.0587355Z   submodules: false
2020-04-02T22:47:13.0587516Z ##[endgroup]
2020-04-02T22:47:13.5035151Z Syncing repository: Madur23/hello-world
2020-04-02T22:47:13.5035950Z ##[group]Getting Git version info
2020-04-02T22:47:13.5036418Z Working directory is '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.5080577Z [command]/usr/bin/git version
2020-04-02T22:47:13.5247046Z git version 2.25.2
2020-04-02T22:47:13.5271776Z ##[endgroup]
2020-04-02T22:47:13.5282823Z Deleting the contents of '/home/runner/work/hello-world/hello-world'
2020-04-02T22:47:13.5284875Z ##[group]Initializing the repository
2020-04-02T22:47:13.5288454Z [command]/usr/bin/git init /home/runner/work/hello-world/hello-world
2020-04-02T22:47:13.5378617Z Initialized empty Git repository in /home/runner/work/hello-world/hello-world/.git/
2020-04-02T22:47:13.5392189Z [command]/usr/bin/git remote add origin https://github.com/Madur23/hello-world
2020-04-02T22:47:13.5439364Z ##[endgroup]
2020-04-02T22:47:13.5439836Z ##[group]Disabling automatic garbage collection
2020-04-02T22:47:13.5443628Z [command]/usr/bin/git config --local gc.auto 0
2020-04-02T22:47:13.5479584Z ##[endgroup]
2020-04-02T22:47:13.5486666Z ##[group]Setting up auth
2020-04-02T22:47:13.5495174Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2020-04-02T22:47:13.5526200Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :
2020-04-02T22:47:13.5949019Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2020-04-02T22:47:13.5988076Z [command]/usr/bin/git submodule foreach --recursive git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :
2020-04-02T22:47:13.6304864Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2020-04-02T22:47:13.6357625Z ##[endgroup]
2020-04-02T22:47:13.6358185Z ##[group]Fetching the repository
2020-04-02T22:47:13.6368192Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8:refs/remotes/origin/master
2020-04-02T22:47:13.9388678Z remote: Enumerating objects: 6, done.        
2020-04-02T22:47:13.9389065Z remote: Counting objects:  16% (1/6)        
2020-04-02T22:47:13.9389231Z remote: Counting objects:  33% (2/6)        
2020-04-02T22:47:13.9389342Z remote: Counting objects:  50% (3/6)        
2020-04-02T22:47:13.9389480Z remote: Counting objects:  66% (4/6)        
2020-04-02T22:47:13.9389777Z remote: Counting objects:  83% (5/6)        
2020-04-02T22:47:13.9390309Z remote: Counting objects: 100% (6/6)        
2020-04-02T22:47:13.9390467Z remote: Counting objects: 100% (6/6), done.        
2020-04-02T22:47:13.9390608Z remote: Compressing objects:  25% (1/4)        
2020-04-02T22:47:13.9390742Z remote: Compressing objects:  50% (2/4)        
2020-04-02T22:47:13.9390876Z remote: Compressing objects:  75% (3/4)        
2020-04-02T22:47:13.9391009Z remote: Compressing objects: 100% (4/4)        
2020-04-02T22:47:13.9391104Z remote: Compressing objects: 100% (4/4), done.        
2020-04-02T22:47:13.9392019Z remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0        
2020-04-02T22:47:13.9392643Z From https://github.com/Madur23/hello-world
2020-04-02T22:47:13.9393233Z  * [new ref]         f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8 -> origin/master
2020-04-02T22:47:13.9393696Z ##[endgroup]
2020-04-02T22:47:13.9394259Z ##[group]Determining the checkout info
2020-04-02T22:47:13.9394522Z ##[endgroup]
2020-04-02T22:47:13.9394706Z ##[group]Checking out the ref
2020-04-02T22:47:13.9395108Z [command]/usr/bin/git checkout --progress --force -B master refs/remotes/origin/master
2020-04-02T22:47:13.9395624Z Reset branch 'master'
2020-04-02T22:47:13.9396154Z Branch 'master' set up to track remote branch 'master' from 'origin'.
2020-04-02T22:47:13.9396499Z ##[endgroup]
2020-04-02T22:47:13.9396855Z [command]/usr/bin/git log -1
2020-04-02T22:47:13.9397166Z commit f0dd8fd4ab6734cd2eeb20b7a0a3a38844d7fcb8
2020-04-02T22:47:13.9397334Z Author: Madur23 <63068360+Madur23@users.noreply.github.com>
2020-04-02T22:47:13.9397647Z Date:   Thu Apr 2 12:36:22 2020 -0700
2020-04-02T22:47:13.9397891Z 
2020-04-02T22:47:13.9398015Z     Create nodes.yml
2020-04-02T22:47:13.9398260Z     
2020-04-02T22:47:13.9398721Z     Release



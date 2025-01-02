# nativephp demo

```shell
$ nativephp-demo [main] php artisan native:serve

  Starting NativePHP dev server…

 Fetching latest dependencies…

 Installing NPM dependencies (This may take a while)...

 Installing NPM dependencies using the npm package manager...

 Fetching latest dependencies…


> Laravel@1.0.0 postinstall
> node ./node_modules/electron-builder/cli.js install-app-deps

  • electron-builder  version=24.13.3
Arch:  arm64
Platform:  darwin
  • loaded configuration  file=/Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js/electron-builder.js

up to date, audited 1091 packages in 5s

138 packages are looking for funding
  run `npm fund` for details

4 vulnerabilities (3 moderate, 1 high)

To address all issues, run:
  npm audit fix

Run `npm audit` for details.

 Starting NativePHP app

  Copying app icons...

 App icons copied

 Running the dev script with npm...

 Fetching latest dependencies…


> Laravel@1.0.0 dev
> cross-env node php.js && electron-vite dev --watch

Binary Source:  /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/php-bin/bin/mac/arm64/php-8.3.zip
Binary Filename:  php
PHP version: 8.3
Unzipping PHP binary from /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/php-bin/bin/mac/arm64/php-8.3.zip to /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js/resources/php
Copied certificate file to /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js/resources/cacert.pem
Copied PHP binary to  /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js/resources/php/php
renderer config is missing
vite v4.5.5 building SSR bundle for development...

watching for file changes...

build started...
✓ 31 modules transformed.
out/main/index.js  58.66 kB
built in 228ms.

build the electron main process successfully

-----

vite v4.5.5 building SSR bundle for development...

watching for file changes...

build started...
"contextBridge" and "ipcRenderer" are imported from external module "electron" but never used in "src/preload/index.js".
✓ 1 modules transformed.
out/preload/index.js  0.70 kB
built in 5ms.

build the electron preload files successfully

start electron app...

Skip checkForUpdates because application is not packed and dev update config is not forced
checkForUpdatesAndNotify called, downloadPromise is null
Electron API server started on port 4000
Starting PHP server... /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js/resources/php/php artisan serve /Users/stellonde/Code/MoChi-Coder/nativephp-demo []
Making sure app folders are available
Skipping Database migration while in development.
You may migrate manually by running: php artisan native:migrate
PHP Server started on port:  8104
PHP Server started on port:  8104
Running scheduler...




```


- log

```shell
$ tail -f  /Users/stellonde/.npm/_logs/*

==> /Users/stellonde/.npm/_logs/2025-01-02T12_42_17_919Z-debug-0.log <==
176 silly ADD
177 silly ADD
178 silly ADD
179 silly ADD
180 verbose cwd /Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js
181 verbose os Darwin 24.0.0
182 verbose node v22.10.0
183 verbose npm  v10.9.1
184 verbose exit 0
185 info ok

==> /Users/stellonde/.npm/_logs/2025-01-02T12_42_20_050Z-debug-0.log <==
2 info using node@v22.10.0
3 silly config load:file:/opt/homebrew/lib/node_modules/npm/npmrc
4 silly config load:file:/Users/stellonde/Code/MoChi-Coder/nativephp-demo/vendor/nativephp/electron/resources/js/.npmrc
5 silly config load:file:/Users/stellonde/.npmrc
6 silly config load:file:/opt/homebrew/etc/npmrc
7 verbose title npm run dev
8 verbose argv "run" "dev"
9 verbose logfile logs-max:10 dir:/Users/stellonde/.npm/_logs/2025-01-02T12_42_20_050Z-
10 verbose logfile /Users/stellonde/.npm/_logs/2025-01-02T12_42_20_050Z-debug-0.log
11 silly logfile done cleaning log files

```

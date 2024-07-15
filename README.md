PS C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1> npm install
npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm warn deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated abab@2.0.6: Use your platform's native atob() and btoa() methods instead
npm warn deprecated domexception@2.0.1: Use your platform's native DOMException instead
npm warn deprecated w3c-hr-time@1.0.2: Use your platform's native performance.now() and performance.timeOrigin.
npm warn deprecated puppeteer@13.7.0: < 22.6.4 is no longer supported
npm warn cleanup Failed to remove some directories [
npm warn cleanup   [
npm warn cleanup     'C:\\Users\\User\\OneDrive\\Рабочий стол\\AW_HW puppeteer_1\\node_modules\\global-prefix',
npm warn cleanup     [Error: EPERM: operation not permitted, rmdir 'C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1\node_modules\global-prefix\node_modules'] {
npm warn cleanup       errno: -4048,
npm warn cleanup       code: 'EPERM',
npm warn cleanup       syscall: 'rmdir',
npm warn cleanup       path: 'C:\\Users\\User\\OneDrive\\Рабочий стол\\AW_HW puppeteer_1\\node_modules\\global-prefix\\node_modules'
npm warn cleanup     }
npm warn cleanup   ],
npm warn cleanup   [
npm warn cleanup     'C:\\Users\\User\\OneDrive\\Рабочий стол\\AW_HW puppeteer_1\\node_modules\\resolve',
npm warn cleanup     [Error: EPERM: operation not permitted, rmdir 'C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1\node_modules\resolve'] {
npm warn cleanup       errno: -4048,
npm warn cleanup       code: 'EPERM',
npm warn cleanup       syscall: 'rmdir',
npm warn cleanup       path: 'C:\\Users\\User\\OneDrive\\Рабочий стол\\AW_HW puppeteer_1\\node_modules\\resolve'
npm warn cleanup     }
npm warn cleanup   ]
npm warn cleanup ]
npm error code 1
npm error path C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1\node_modules\puppeteer
npm error command failed
npm error command C:\WINDOWS\system32\cmd.exe /d /s /c node install.js
npm error ERROR: Failed to set up Chromium r982053! Set "PUPPETEER_SKIP_DOWNLOAD" env variable to skip download.
npm error Error: Download failed: server returned code 403. URL: https://storage.googleapis.com/chromium-browser-snapshots/Win_x64/982053/chrome-win.zip
npm error     at C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1\node_modules\puppeteer\lib\cjs\puppeteer\node\BrowserFetcher.js:371:27
npm error     at ClientRequest.requestCallback (C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1\node_modules\puppeteer\lib\cjs\puppeteer\node\BrowserFetcher.js:500:13)
npm error     at Object.onceWrapper (node:events:634:26)
npm error     at ClientRequest.emit (node:events:519:28)
npm error     at HTTPParser.parserOnIncomingClient (node:_http_client:698:27)
npm error     at HTTPParser.parserOnHeadersComplete (node:_http_common:119:17)
npm error     at TLSSocket.socketOnData (node:_http_client:540:22)
npm error     at TLSSocket.emit (node:events:519:28)
npm error     at addChunk (node:internal/streams/readable:559:12)
npm error     at readableAddChunkPushByteMode (node:internal/streams/readable:510:3)

npm error A complete log of this run can be found in: C:\Users\User\AppData\Local\npm-cache\_logs\2024-07-15T17_57_10_029Z-debug-0.log
PS C:\Users\User\OneDrive\Рабочий стол\AW_HW puppeteer_1>  
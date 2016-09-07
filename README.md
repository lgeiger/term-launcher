# :computer: :rocket: Term Launcher

Launch terminals and jupyter consoles from node.

## Installation
```
npm install term-launcher
```

## Usage
```javascript
const term = require('term-launcher');

term.launchTerminal('echo Hello world!');
term.launchTerminal('ls', '~/Desktop');
term.launchTerminal('ls', '~/Desktop', 'iTerm.app');

term.launchJupyter('<path-to-connection-file-of-running-kernel>');
term.launchJupyter('<path-to-connection-file>', 'Desktop', 'iTerm.app');
```

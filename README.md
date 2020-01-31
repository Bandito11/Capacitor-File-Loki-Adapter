# Capacitor-File-Loki-Adapter
A Basic adapter for LokiJS that uses Capacitor File plugin.

Instructions on how to use on NodeJS.
```
import myAdapter = require('capacitor-file-loki-adapter');
import loki = require('lokijs');

const mydb = new loki('db.txt', {adapter: myAdapter});
```

Instructions on how to use on TypeScript
```
import myAdapter from ('capacitor-file-loki-adapter');
import loki from 'lokijs';

const mydb = new loki('db.txt', {adapter: myAdapter});
```

# Capacitor-File-Loki-Adapter
A Basic adapter for LokiJS that uses Capacitor File plugin.

Instructions on how to use on NodeJS.
```
import myAdapter = require('capacitor-file-loki-adapter')();
import loki = require('lokijs');

const myDb = new loki('db.txt', {adapter: myAdapter});
```

Instructions on how to use on TypeScript
```
import {CapacitorFileLokiAdapter) from ('capacitor-file-loki-adapter');
import loki from 'lokijs';

const myAdapter = new CapacitorFileLokiAdapter();
const myDb = new loki('db.txt', {adapter: myAdapter});
```

or inside a class function
```
import {CapacitorFileLokiAdapter) from ('capacitor-file-loki-adapter');
import loki from 'lokijs';

class MyClass {
myDb;
myAdapter;

constructor(){
     this.myAdapter = new CapacitorFileLokiAdapter();
     this.myDb = new loki('db.txt', {adapter: myAdapter});
  }
}
```

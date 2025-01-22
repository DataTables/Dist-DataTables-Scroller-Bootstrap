# Scroller for DataTables with styling for [Bootstrap](https://getbootstrap.com/docs/3.3/)

This is the distribution package for the [Scroller extension](https://datatables.net/extensions/scroller) for [DataTables](https://datatables.net/) with styling for [Bootstrap](https://getbootstrap.com/docs/3.3/).

Scroller is a virtual rendering plug-in for DataTables which allows large datasets to be drawn on screen very quickly. Virtual rendering means is that only the visible portion of the table is drawn, while the scrolling container gives the visual impression that the whole table is visible, allowing excellent browser performance.


## Installation

### Browser

To use DataTables with a simple `<script>` tag, rather than using this package, it is recommended that you use the [DataTables download builder](//datatables.net/download) which can create CDN or locally hosted packages for you, will all dependencies satisfied.

### npm

For installation via npm, yarn and other similar package managers, install this package with your package manager - e.g.:

```
npm install datatables.net-bs
npm install datatables.net-scroller-bs
```

Then, to load and initialise the software in your code use:

```
import DataTable from 'datatables.net-bs';
import 'datatables.net-scroller-bs'

new DataTable('#myTable', {
    // initalisation options
});
```


## Documentation

Full documentation and examples for Scroller can be found [on the DataTables website](https://datatables.net/extensions/scroller).


## Bug / Support

Support for DataTables is available through the [DataTables forums](//datatables.net/forums) and [commercial support options](//datatables.net/support) are available.

### Contributing

If you are thinking of contributing code to DataTables, first of all, thank you! All fixes, patches and enhancements to DataTables are very warmly welcomed. This repository is a distribution repo, so patches and issues sent to this repo will not be accepted. Instead, please direct pull requests to the [DataTables/Scroller](http://github.com/DataTables/Scroller). For issues / bugs, please direct your questions to the [DataTables forums](//datatables.net/forums).


## License

This software is released under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.


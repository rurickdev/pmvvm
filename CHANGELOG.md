# 4.0.0

* Replace the `onDispose` callback method of the view model by `onUnmount`
* Add `onMount` callback in the view model
* Remove `initOnce` parameter and make the `init` method of the view model get called only after `initState` of the MVVM widget
* Add `onDependenciesChange` in the view model to get called when the `didChangeDependencies` of the MVVM widget gets triggered

# 3.0.0

* Replace the `implicitView` parameter with the `builder` factory constructor.
* Add observables

# 2.3.0

* Added the `implicitView` parameter to the MVVM builder to allow using explicit reactive views instead of predifined views classes.

# 2.2.3

* Fixd typos in the README.
* Update the code documentation.

# 2.2.2

* Fixd typos in the README and updated the documentation structure.
* Update the code documentation.
* Update the package dependencies.

# 2.2.0

* Fix minor bug with hooks.
* Support multiple app life cycle events invocation.
* Update documentation

# 2.0.1

* Fix `null-safety` bug
* Update example code.

# 2.0.0

* Migrate to `null-safety`

# 1.0.0

* Removed `createNewModelOnInsert` parameters of the `MVVM` widget.
* Removed `MVVMWidget` class.
* Handled app lifecycle state methods inside `ViewModel`.
* Updated Example.
* Updated README.
* Updated Dependencies.

# 0.4.0

* Added `listen` parameter to `context.fetch<T>()`
* Updated README.

# 0.3.0

* Added `context.fetch<T>()` which is equivalent to `Provider.of<T>(context)`
* Updated 2 factor authentication example
* Updated README.

# 0.2.2

* Updated README file with extra details about `StatelessView`, code snippets, ..etc.

# 0.2.1

* Added examples: counter, firebase 2-factor auth.

# 0.2.0

* Added `StatelessView` widget.

# 0.1.2

* Update dependencies `flutter_hooks`.

# 0.1.1

* Fixed a bug by removing `protected` decorator from the `ViewModel`.

# 0.1.0

* Package Deployment

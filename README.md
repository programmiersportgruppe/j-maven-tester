This is an example application that can be launched using the
[`jlauncher`](https://github.com/programmiersportgruppe/j).

The `j-manifest.json` file is generated using the j-maven-plugin.
Essentially it contains the main class, as well as the coordinates
of the fully resolved dependencies.

To start the test app you need to install jlauncher

~~~ .bash
gem install jlauncher
~~~

Then all you need to do is to run this:

~~~
j org.programmiersportgruppe:j-maven-tester:VERSION --name World
~~~

On the first launch it will download and cache the dependencies.
On subsequent launches it will use the cached files.


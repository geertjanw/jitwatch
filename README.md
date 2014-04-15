This project has moved to <a href="https://github.com/AdoptOpenJDK/jitwatch">AdoptOpenJDK/jitwatch</a> to benefit the wider Java community.

All further development will take place on the AdoptOpenJDK fork.

JITWatch
========

Log analyser and visualiser for the HotSpot JIT compiler.

<h3>For instructions and screenshots see the wiki</h3>
<h3>https://github.com/AdoptOpenJDK/jitwatch/wiki</h3>

<h2>ant</h2>
<pre>ant clean compile test run</pre>

<h2>maven</h2>
<pre># Java 7
mvn clean compile test exec:java</pre>
<pre># Java 8
mvn -f pom-java8.xml clean compile test exec:java</pre>

<h2>Build an example HotSpot log</h2>
<pre># Build the code first with ant / maven / IDE
./makeDemoLogFile.sh</pre>

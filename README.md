This is my example of JMeter Plugins.
I have built this repository to show my some JMeter experiences.
## Overview ##

This is an example project for running a [JMeter][1] test with the [JMeter Maven Plugin][2] and the [JMeter Analysis Maven Plugin][2] out of the box.

It runs a [JMeter][1] test against a few URLs on www.mozilla.com and illustrates how the maven plugin can be used to run
with different configurations, for example a "warmup" and a "real" test.

Included is a [JMeter][1] Testplan `test.jmx` that supports 4 distinct threadgroups which can be configured individually.

Look at the included files for further information, the `pom.xml` is fully commented, and the JMeter Testplan `test.jmx` as well.



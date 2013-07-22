# trihug-kafka-demo

Kafka demo for TriHUG July 23, 2013

Build the demos with ant:

    ant clean compile

Included is a ant target that will run the ZooKeeper server:

    ant zk -Dzk.port=2181 -Dzk.dir=/tmp/zk

The ZooKeeper directory can be cleaned up with

    ant clean-zk

# License
Copyright 2012 David Arthur

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

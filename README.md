# linux-tux
this can help you to create a test
+1
:+1:


            Client                                       
          +---------+                    +--------------+              
          |  JVM    |                    |              |              +-------------+               +-------------+  
          |  Tomcat |                    |              |              |             |               |             |
          |  Solr   |    queries         |   jmxtrans   |              |             |               |             |  
          |  AMQ    +------------------->|   server     +------------->|  influxDB   |+------------->|   Grafana   |
          |  Camel  |                    |              |              |             |               |             |  
          |  Kafka  |                    |              |              |             |               |             |
          |  Sys    |                    |              |              +-------------+               +-------------+  
          +---------+                    +--------------+                                            

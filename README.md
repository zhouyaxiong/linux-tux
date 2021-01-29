# linux-tux
this can help you to create a test
+1
:+1:


jvm属性监控

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

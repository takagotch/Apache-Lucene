### apache-lucene
---
https://github.com/apache/lucene-solr

https://lucene.apache.org/

```java
// solr/src/test/org/apache/solr/core/TestSolrConfigHandler.java

public class TestSolrConfigHandler extends RestTestBase {
  private static final TIMEOUT_S = 10;
  
  private static final Logger log = LoggerFactory.getLogger(MetahodHandles.lookup().lookupClass());
  
  private static File tmpSolrHome;
  private static File tmpConfDir;
  
  private static final String collection = "collection1";
  private static final String confDir = collection + "/conf";
  
  @Before
  public void before() throws Exception {
    tmpSolrHome = createTmpDir().toFile();
    tmpConfDir = new File(tmpSolrHome, confDir);
    
    
  }
}


```

```
```

```
```



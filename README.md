Random example cookbooks for AWS OpsWorks
==========================

Java: Installs either OpenJDK or Sun/Oracle Java - take from https://github.com/opscode-cookbooks/java and adapted for OpsWorks.
If you want to use Oracle, make sure to have the following in your custom JSON: 

{
  "java": {
    "oracle": {
      "accept_oracle_download_terms": true
    }
  }
}



curl -L -O https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-8.16.1-linux-x86_64.tar.gz 
tar xzvf elastic-agent-8.16.1-linux-x86_64.tar.gz
cd elastic-agent-8.16.1-linux-x86_64
sudo ./elastic-agent install --url=https://4d050ebd166443bf8bfd305a976f79a1.fleet.us-central1.gcp.cloud.es.io:443 --enrollment-token=YmxBd2RKTUJsZUJxNm55OXZNTlY6OE8zVXY3TzJROS1jenc3aDNrQVVhQQ==

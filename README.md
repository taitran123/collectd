# collectd
Collectd Graphite Config


sudo apt-get install collectd

```SQL
CREATE USER monitor WITH PASSWORD '12345678'; 
GRANT CONNECT ON DATABASE genki TO monitor; 
GRANT USAGE ON SCHEMA public TO monitor; 
GRANT SELECT ON ALL TABLES IN SCHEMA public TO monitor; 
ALTER DEFAULT PRIVILEGES IN SCHEMA public GRANT SELECT ON TABLES TO monitor;```

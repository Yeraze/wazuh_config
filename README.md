# wazuh_config
Rules and Decoders for Wazuh use

# Prequisites
This assumes you have Wazuh running in containers, with Docker+Rsyslog integration enabled
and log monitoring of those logs integrated with Wazuh.  Details can be found in this blog post:
https://wazuh.com/blog/docker-container-security-monitoring-with-wazuh/

# Authentik
* Tagged as T1110.001 (Brute Force, Password guessing)
  * Login Failure - invalid password with Authentik
  * Login Failure - invalid password or account with Synology DSM

* Tagged as T1589.001 (Reconaissance, Credentials)
  * Login Failure - invalid account with Authentik

* Tagged as T1590.006 (Reconaissance, Network Security Appliances)
  * System Test Message sent from Synology Log Manager

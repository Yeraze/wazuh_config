# wazuh_config
Rules and Decoders for Wazuh use

# Prequisites
This assumes you have Wazuh running in containers, with Docker+Rsyslog integration enabled
and log monitoring of those logs integrated with Wazuh.  Details can be found in this blog post:
https://wazuh.com/blog/docker-container-security-monitoring-with-wazuh/

# Authentik
* Login Failure - invalid password with Authentik
  * Tagged as T1110.001 (Brute Force, Password guessing)
* Login Failure - invalid account with Authentik
  * Tagged as T1589.001 (Reconaissance, Credentials)

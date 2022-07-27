FireEye Agent-

As the internet world is growing, the security of user data has become a questionable topic. We continuously hear about new cyber attacks, vulnerabilities, or ransomware targets. FireEye Endpoint Security protects your endpoints with multi-engine protection in a single modular agent.

Endpoint Agents let you monitor the use, connectivity, and performance of VPN gateways and end-to-end network connections. Due to this, the remote employee can consume business-critical internal and SaaS apps with zero impact on user experience.

Checkout this blog for further reference- https://blog.knoldus.com/introduction-to-fireeye-endpoint-security/

To use the playbook run the following command in the main folder-

ansible-playbook -i (the host file if you are using) playbook/install-fireeye-agent.yml

before running the playbook do specify the <hostname> in the ansible playbook and check for the default variable values


In case we want to Rollback the deployed agent for DR, we can run the following playbook and role-

ansible-playbook -i (the host file if you are using) playbook/uninstall-fireeye-agent.yml

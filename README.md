# ansible__

This a flask app, ready to be deployed with a simplified ansible playbook,in this HAproxy acts as the load balancer, UDP load balancing is achieved and additionally, installed snmpd daemon onto the dev servers. In this case, HAproxy takes care of the flask app while nginx takes care of SNMP.

Run the playbook as: ansible-playbook -i hosts site.yaml

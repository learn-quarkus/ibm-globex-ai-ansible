## Installation

1. Update the inventories/inventory.template file with details of your LLM and save it as inventories/inventory

2. `oc login` in your local machine

3. Run following command

```
ansible-playbook playbooks/ocp4_workload_globex_ai_poc.yml -e ACTION=create -i inventories/inventory
```

4. 
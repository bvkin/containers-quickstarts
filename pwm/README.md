# PWM

## Usage

1. Clone this repository: `git clone https://github.com/redhat-cop/containers-quickstarts`
2. `cd containers-quickstarts/pwm`
3. Run `ansible-galaxy install -r requirements.yml --roles-path=galaxy`
4. Login to OpenShift: `oc login -u <username> https://master.example.com:8443`

### Build and Deploy PWM

Run the openshift-applier to create the `PWM` project and deploy required objects
```
ansible-playbook -i .applier galaxy/openshift-applier/playbooks/openshift-cluster-seed.yml
```



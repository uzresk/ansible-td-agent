# td-agent setup ansible script

set up td-agent(fluentd)

## Provides

* td-agent
* td-agent-plugins
* kernel & limits settings(http://docs.fluentd.org/articles/before-install)

## Requires

1. Ansible(checked 1.9.1)
2. CentOS 6.5 later

## Usage

### Get the code
`$ git clone https://github.com/uzresk/ansible-td-agent.git`

### change hosts file 

	[server]  
	192.168.1.20  

### Run the Playbook

`$ ansible-playbook -i hosts site.yml`



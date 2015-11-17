# neutron-ha-tool

This is a extended version. The original version, was published [here](./baremetal/roles/openstack_network_node/files/usr/local/sbin/neutron-ha-tool.py)

This version also containes funtions to migrate LBaaS between network nodes.
The new parameters are:

    --lbaas-agent-check: Show LBaaS associated with offline lbaas agents
    --lbaas-agent-migrate: Migrate LBaaS pools away from offline lbaas agents

Extended information about LBaaS HA in OpenStack can be found in [this blog article]()

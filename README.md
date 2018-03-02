# ansible-role-vpnc-client
[![Build Status](https://travis-ci.org/vinayski/ansible-role-vpnc-client.svg?branch=master)](https://travis-ci.org/vinayski/ansible-role-vpnc-client)

Ansible Galaxy Role (https://galaxy.ansible.com/vinayski/ansible-role-vpnc-client) to Setup VPN client for Cisco VPN3000 Concentrator, IOS and PIX for use with RSA Token

## Requirements

None

## Role Variables

Available variables are listed in the below example, along with default values.

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - role: vinayski.vpnc-client
          vpnc_options:
            ipsec_gateway: gateway.server.com
            ipsec_id: id
            ipsec_secret: secret
            xauth_user: vpnuser
            xauth_password: password
          token_file: /tmp/token.sdtid

## License

none

## Author Information

This role was created by [vinayski](http://www.github.com/vinayski).

# OpenvpnAS ansible role

This is a role used to deploy a working stack for OpenvpnAS. This only works currently on Ubuntu machines.
This role is depends on the following:
* Docker
* Python
* Python module docker
* Python module ldap3

Here are the variables that need to be set: 

 Key                    | DEFAULT                                     | Type
----------------------- | ------------------------------------------- | -------------
`openvpn_as_version   ` | `2.5.2`                                     | `string`
`openvpn_certs_db`      | `/usr/local/openvpn_as/etc/db/certs.db`     | `string`
`openvpn_certs_db`      | `/usr/local/openvpn_as/etc/db/certs.db`     | `string`
`openvpn_config_db`     | `/usr/local/openvpn_as/etc/db/config.db`    | `string`
`openvpn_db_password`   | `test`                                      | `string`
`openvpn_db_user`       | `test`                                      | `string`
`openvpn_ldap_password` | ``                                          | `string`
`openvpn_ldap_port`     | `636`                                       | `integer` 
`openvpn_ldap_uri`      | ``                                          | `string`
`openvpn_ldap_url`      | ``                                          | `string`
`openvpn_ldap_user`     | ``                                          | `string`
`openvpn_ldap`          | `false`                                     | `boolean`
`openvpn_log_db`        | `/usr/local/openvpn_as/etc/db/log.db`       | `string`
`openvpn_os`            | `Ubuntu16`                                  | `string`
`openvpn_url`           | `ovpn.test.com`                             | `string`
`openvpn_user_password` | `openvpn`                                   | `string`
`openvpn_user_prop_db`  | `/usr/local/openvpn_as/etc/db/userprop.db`  | `string`

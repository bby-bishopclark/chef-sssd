# 0.5.2
	make adcli use an OU when joining if requested
	fix generation of computer name
	remove versioning from dependencies, tested with current

# 0.5.1

Make `sssd` service actions configurable with a new attribute `node['sssd']['service_actions']`. Defaults to
`[:enable]`.

# 0.5.0

Use adcli --stdin-password to set the password instead of expect

# 0.1.0

Initial release of sssd

## 1.0.7

- Update launchd configuration to listen on localhost only
- Prevent VMware installation check during uninstall on Windows
- Add support for faster additions of port forwards
- Optimize port forward pruning behavior

## 1.0.6

- Fix permission issue with macOS installer

## 1.0.5

- Retain network device ownership and permissions when configuring
  networks on Linux platforms
- Add support for DHCP reservations

## 1.0.4

- Automatically fix registry permissions when state is incorrect
- Ignore invalid port forward description fields

## 1.0.3

- Fix service install command for sysv
- Provide better DHCP lease handling on service re-configure

## 1.0.2

- Reduce Windows event logging noise
- Add vmnet verification to help ensure running vmnet processes
- Fix port forwarding behavior in Fusion 8

## 1.0.1

- Wrap Fusion services process when modifying networking settings
- Use isolated settings for NAT tracking to prevent data loss

## 1.0.0

- Initial utility release

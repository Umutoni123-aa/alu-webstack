# HTTPS SSL Project

This project implements SSL/TLS termination on HAProxy and configures secure HTTPS traffic.

## Files

- `0-world_wide_web`: Bash script to audit domain subdomains
- `1-haproxy_ssl_termination`: HAProxy config with SSL termination
- `2-redirect_http_to_https`: HAProxy config with HTTP to HTTPS redirect

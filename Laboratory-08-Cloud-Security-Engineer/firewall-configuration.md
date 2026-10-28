
# Firewall Configuration

## 1. Allow SSH Access

Before enabling the UFW firewall, allow SSH connections to help prevent losing remote access to the server.

```bash
sudo ufw allow ssh
```

## 2. Configure Default Firewall Policies

Block all incoming connections by default while allowing outgoing connections.

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

## 3. Enable the Firewall

Activate UFW to apply the configured firewall rules.

```bash
sudo ufw enable
```

## 4. Allow Web Server Traffic

Allow incoming TCP traffic through port 8080 so users can access the Nginx web server.

```bash
sudo ufw allow 8080/tcp
```

## 5. Verify Firewall Rules

Check whether the firewall is active and confirm that the required rules are configured.

```bash
sudo ufw status verbose
sudo ufw status numbered
```

## 6. Test the Nginx Web Server

Send an HTTP request to verify that the web server responds on port 8080.

```bash
curl -I http://localhost:8080
```

A successful response should include `HTTP/1.1 200 OK`.

## Expected Results

- UFW is active.
- Incoming connections are denied by default.
- Outgoing connections are allowed by default.
- SSH access is allowed.
- TCP port 8080 is allowed.
- The Nginx web server responds successfully.


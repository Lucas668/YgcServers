# YgcServers
A MacOS App, The 8-in-1 server suite built for network experts. Easily deploy DNS, DHCP, FTP, SFTP, TFTP, Web, NTP, and Syslog services.

# Download in Mac App Store
  https://apps.apple.com/us/app/ygcservers/id6749007667


## Function and preview picture：

### DNS Server
<img width="1468" height="917" alt="en_dns" src="https://github.com/user-attachments/assets/afad7c50-6751-451e-8a18-035c8279c5be" />


- Forward resolution: Supports A, AAAA, CNAME, MX, NS, TXT, and SRV record types
- Reverse resolution: Supports PTR records for IP-to-domain reverse lookups
- Conditional forwarding: Set up forwarding servers based on domain names
  
  - Multiple record types:
  - A records: IPv4 address resolution
  - AAAA records: IPv6 address resolution
  - CNAME records: Domain aliases
  - MX records: Mail server configuration
  - TXT records: Text information (SPF, DKIM, DMARC, etc.)
  - SRV records: Service discovery
  - Forwarding: Supports upstream DNS server forwarding for complete DNS solutions
  - Caching: Intelligent caching to improve query performance

### DHCP Server
<img width="1470" height="919" alt="en_dhcp" src="https://github.com/user-attachments/assets/fa56eb73-9dca-45de-a69f-ff1b5fcc7744" />

- Dynamic IP allocation: Automatically assigns IP addresses and network configuration to network devices
- Multi-subnet support: Configurable multiple subnet pools for complex network environments
- Lease management: Real-time monitoring of IP lease status, viewing active connections and lease expiration times
- Advanced options: Supports Option 43 (vendor-specific information) and Option 150 (TFTP server address)
- Broadcast and unicast responses: Intelligent response mode selection to ensure clients receive configuration correctly

### FTP Server
<img width="1470" height="919" alt="en_ftp" src="https://github.com/user-attachments/assets/7ddcb206-ca6b-4519-a6d4-c2a1abdade1a" />

- Multi-user management: Support for creating multiple user accounts with individual permission settings
- Anonymous access: Configurable anonymous user access for easy file sharing
- Permission control: Fine-grained permission management (read, write, delete, create directory)
- Passive mode: Supports PASV mode to resolve connection issues in firewall environments
- Multi-language support: Full UTF-8 and Chinese support


### TFTP Server
<img width="1468" height="917" alt="en_tftp" src="https://github.com/user-attachments/assets/17c9ebb7-47ed-48e5-981f-016e676780f3" />

- Lightweight transfer: Suitable for network booting, firmware updates, and other scenarios
- Option negotiation: Supports block size, transfer size, and window size options
- Transfer monitoring: Real-time display of transfer progress and status
- Error handling: Complete TFTP error code support
- Bidirectional transfer: Supports both file read and write operations

### Web Server
<img width="1468" height="917" alt="en_web" src="https://github.com/user-attachments/assets/2096e070-65e5-467d-ada6-abf738616a89" />

- Local website hosting: Quick deployment of local websites and file sharing
- Directory browsing: Configurable directory index display
- Static file serving: Efficient static file transfer

### NTP Server
<img width="1470" height="919" alt="en_ntp" src="https://github.com/user-attachments/assets/2d4ce9f8-e755-43b3-b11b-1f3d6303f87e" />

- Time synchronization: Provides accurate network time services
- Upstream synchronization: Supports multiple upstream NTP servers
- Client monitoring: Tracks connected clients and synchronization status
- Performance statistics: Displays latency, offset, jitter, and other statistical information
- Hierarchical architecture: Supports NTP hierarchical time architecture

### Syslog Server
<img width="1470" height="919" alt="en_syslog" src="https://github.com/user-attachments/assets/dcb4c57c-5a91-440d-9831-2cf87044f29a" />

- Log collection: Centralized collection of network device and system logs
- Log rotation: Automatic log file rotation and archiving
- Formatted output: Customizable log formats
- Client filtering: Supports allowed client IP lists
- Real-time monitoring: Real-time display of received log information

- ### SFTP Server
<img width="1468" height="917" alt="en_sftp" src="https://github.com/user-attachments/assets/691f0c50-53a3-4241-b388-0b139875bcc5" />

- Secure transfer: SSH-based encrypted file transfer
- User isolation: Chroot directory restrictions ensure users can only access designated directories
- Permission management: Supports read, write, delete, create directory, and execute permissions
- Concurrent control: Configurable maximum connections per user
- Logging: Detailed connection and operation logs

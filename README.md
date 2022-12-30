# linux-service

Copy shell script to executable path:
```bash
sudo cp hello /usr/local/bin
```

Copy service into the system:
```bash
sudo cp hello.service /etc/systemd/system
```

Check the service status:
```bash
systemctl status hello
```

Start the service:
```bash
systemctl start hello
```


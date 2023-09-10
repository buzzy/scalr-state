# Install dependencies

```bash
pip3 install -r requirements.txt
```

# Download all state files

```bash
download_state_files.py --host example.scalr.io --token xxx --output-dir /tmp/scalr-state-files
```

# Environment variables

Instead of providing the host and token on the command line, you can set the following environment variables:

```bash
export SCALR_HOST=example.scalr.io
export SCALR_TOKEN=xxx
```

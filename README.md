## Advanced Shall
to start this projuct first open your git Bash and install jq.exe
```bash
# Download jq binary for Windows
curl -L -o jq.exe https://github.com/stedolan/jq/releases/latest/download/jq-win64.exe

# Move to a directory in your PATH (like /usr/bin or create ~/bin)
mkdir -p ~/bin
mv jq.exe ~/bin/jq.exe

# Add to PATH if ~/bin isn't already there
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

always make you file executable using

`chmod +x ${file_name}`

**NOTE**
- What is jq?
jq is a command-line JSON processor - think of it as "sed for JSON data."
- Main uses:

Parse JSON - Extract specific values from JSON responses
Format JSON - Make ugly/minified JSON readable (pretty-printing)
Filter data - Get only the parts you need from large JSON files
Transform data - Convert JSON structure, rename fields, etc.

- What is .bashrc?
.bashrc is a configuration file that runs every time you start a new bash shell session.
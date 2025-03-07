# remove all the node_modules and .venv files to free up space

`find . -type d \( -name "node_modules" -o -name ".venv" \)`

`find . -type d \( -name "node_modules" -o -name ".venv" \) -exec rm -rf {} +`

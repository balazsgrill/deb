```
# Add the repository key
wget -O - 'https://balazsgrill.github.io/deb/key.asc' | sudo apt-key add -

# Add the repository
echo 'deb https://balazsgrill.github.io/deb unstable main' | sudo tee -a /etc/apt/sources.list

# Update package lists
sudo apt update
```

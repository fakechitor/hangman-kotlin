<h1>Виселица</h1>
Реализация проекта из <a href="https://zhukovsd.github.io/java-backend-learning-course/projects/hangman/">роадмапа</a> на языке программирования Kotlin в функциональном стиле

test

# Register the Regolith public key to your local apt
wget -qO - https://regolith-desktop.org/regolith.key | gpg --dearmor | sudo tee /usr/share/keyrings/regolith-archive-keyring.gpg > /dev/null

# Add the repository URL to your local apt
echo deb "[arch=amd64 signed-by=/usr/share/keyrings/regolith-archive-keyring.gpg] https://regolith-desktop.org/release-3_0-ubuntu-jammy-amd64 jammy main" | \
sudo tee /etc/apt/sources.list.d/regolith.list

# Update apt
sudo apt update
echo Regolith Desktop can be installed by executing: sudo apt install regolith-desktop regolith-session-flashback regolith-look-lascaille
FROM swift:5.9

# Install extra tools
RUN apt-get update && apt-get install -y \
    curl git unzip zip libssl-dev libsqlite3-dev \
    && rm -rf /var/lib/apt/lists/*

# Optional: install Xcode CLI-like tools via custom scripts (limited)
RUN git config --global user.name "Your Name" && \
    git config --global user.email "your@email.com"
